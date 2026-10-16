<div align="center">

# Hi there, I'm LI Hao 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=06B6D4&center=true&vCenter=true&width=720&lines=Quantum+Dynamics+%26+AI+for+Science+(AI4S)+Researcher;Developer+of+QGM+(QuantumGeneralModule)+%26+AQD;HPC+%26+Scientific+Computing+Engineer+(Modern+Fortran+%2B+Python);Passionate+Full-Stack+Maker+(FutureWork%2C+Android%2C+Systems))](https://git.io/typing-svg)

<p align="center">
  <a href="mailto:12331061@mail.sustech.edu.cn">
    <img src="https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Education-SUSTech-8B5CF6?style=flat-square&logo=academia&logoColor=white" alt="SUSTech" />
  <img src="https://img.shields.io/badge/Focus-Quantum%20Dynamics%20%7C%20AI4S-06B6D4?style=flat-square&logo=physics&logoColor=white" alt="Focus" />
  <img src="https://img.shields.io/badge/Location-Shenzhen%2C%20China-3B82F6?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-10B981?style=flat-square&logo=gitbook&logoColor=white" alt="Open to Work" />
</p>

</div>

---

## 🔬 专业定位 (Professional Overview)

我是一名主攻**量子动力学（Quantum Dynamics）与科学智能（AI for Science / AI4S）**的计算物理研究人员，目前在**南方科技大学 (SUSTech)** 开展研究。

- ⚛️ **核心主业：量子动力学演化与 AI for Science 深度交叉**
  - **物理主航道**：专注于原子分子与光物理 (AMO Physics)、微观体系量子波包时间演化动力学 (Wavepacket Dynamics)、量子反应散射 (Reactive Scattering)、强场超快光学 (HHG, Ultrafast Optics) 与非绝热耦合动力学 (Non-adiabatic Dynamics)；
  - **核心算法自研**：深入掌握并独立实现 Sinc-DVR (离散变量表象法)、Split-Operator 分步算符谱方法、虚时间演化基态求解、吸收势边界 (CAP/PML) 及精确量子反应散射矩阵代数优化；
  - **AI for Science 全栈落地**：主导开发势能面 (PES) 自动化求解与机器学习拟合工具链，打通高精度从头算（PySCF / xTB / ASE）与神经网络（NN）主动学习拟合引擎，具备大型超算集群（Slurm / MPI 并行加速）百核作业工程化调度底蕴。

- 💡 **业余探索：旺盛的好奇心与极客造物 (Passionate Maker & Explorer)**
  - 在严谨的主业物理科研之余，编程与创造是我探索数字世界的最佳延伸。
  - 我对现代软件工程、多模态交互和移动端技术怀揣极大的自驱力，业余时间独立主导开发了**未来多模态自然人机交互生产力核心** (`FutureWork`)、**现代 Android 响应式音乐播放器** (`LunaMusic`)、**新型可变帧率视频格式** (`DynamicsVideo`) 等完备项目——具备一个人从算法设计、架构解耦、单元测试（400+ 项全绿）到 Linux / Android / Windows 全平台发行部署的完整闭环工程力。

---

## 🌟 核心科研代表作 (Flagship Scientific Computing & AI4S Projects)

```
  ┌─────────────────────────────────────────────────────────────────────────┐
  │                           核心主业技术航道                                │
  │   [从头算电子结构 PySCF/xTB] ──▶ [高维势能面网格扫描 & NEB过渡态搜索]       │
  │                                    │                                    │
  │   [神经网络势能面主动学习拟合] ◀───────┴──▶ [现代 Fortran 量子波包时域传播]   │
  │            (AI for Science)                     (Quantum Dynamics / QGM)│
  └─────────────────────────────────────────────────────────────────────────┘
```

### 1. 🔬 [QGM (QuantumGeneralModule)](https://github.com/l1Ha/QuantumGeneralModule) · 现代量子动力学通用算法库
> **基于 Modern Fortran 2008 与 Python 构建的高性能量子波包演化与 AMO 物理动力学核心算法库**

- **深厚物理与数学实现**：
  - 实现了基于 Sinc-DVR、Legendre/Fourier 离散变量表象的高精度哈密顿量构建与对角化；
  - 精确实现时域薛定谔方程的 Split-Operator（分步算符传播）谱方法与虚时间演化基态求解算法；
  - 模拟双色及超短激光脉冲强场作用下的高次谐波产生 (HHG) 光谱，建模多电子激发态之间的非绝热耦合跃迁动力学；
- **工业级严谨工程标准**：
  - 遵循严格的测试驱动开发（TDD）哲学，内置 **390+ 项自动化数值与物理基准测试 100% 全部通过**；
  - 详细对齐 PRL、PRA、RMP、Science、Nature 等 40 余篇经典与前沿物理文献的算符理论基准。

---

### 2. 🧬 [AQD (AutoQuantumDynamics)](https://github.com/l1Ha/AutoQuantumDynamics) & [AutoQuantumPES](https://github.com/l1Ha/AutoQuantumPES) · AI for Science 势能面计算与机器学习拟合
> **电子结构从头算 → 势能面扫描工作流 → 主动学习 (Active Learning) → 神经网络拟合的全栈闭环**

- **多后端计算引擎打通**：
  - 原生无缝集成并调度 PySCF、xTB 与 ASE 后端，支持开壳层/闭壳层分子的能量单点算、平衡结构几何优化与振动简正模式频率计算；
  - 支持复杂反应内坐标多维网格扫描、NEB (微动弹性带) 过渡态搜索、IRC 反应最小能量路径追踪与自旋-轨道耦合 (SOC) 效应分析；
- **AI for Science 核心落地**：
  - 构建**物理对称性保持的神经网络势能面拟合引擎**，结合主动学习策略实现稀疏关键构型自适应采样，大幅缩减传统高精度从头算的高昂开销；
  - 配套标准 Slurm 超算批处理模板与完整收敛验证链，实现从量子化学数据生成到机器学习拟合评估的一键自动化。

---

### 3. 🎯 [ABC_S](https://github.com/l1Ha/ABC_S) & [molscat](https://github.com/l1Ha/molscat) · 量子反应散射模拟
> **原子-双原子碰撞与化学反应态-态散射动力学演化与矩阵优化**

- 采用现代 Fortran 重构并优化经典量子反应散射求解器，引入紧致散射表象算法；
- 求解精细能级散射矩阵与微分反应截面，针对大规模散射矩阵对角化实施局部性内存布局与 BLAS/LAPACK 性能调优。

---

## 🛠️ 专业技术矩阵 (Technical Arsenal)

| 核心领域 | 专业工具与技能栈 | 熟练度与应用场景 |
| :--- | :--- | :--- |
| **科学计算语言** | **Modern Fortran** (2008/2018), **Python 3** (NumPy, SciPy, SymPy), **Bash / Shell** | 长期高频使用；编写高稳定、高性能物理模拟算法与超算批处理脚本 |
| **量子物理与仿真** | Sinc-DVR, Split-Operator, HHG 光谱, 非绝热动力学, ABC 反应散射, 光解离/光电离 | 核心研究领域；深入理解底层薛定谔方程多维数值离散演化与边界处理 |
| **AI for Science** | 神经网络势能面拟合 (NN PES), PySCF, xTB, ASE, 主动学习采样, 物理信息建模 | 核心研究方向；打通从头算量子化学与机器学习力场全套流水线 |
| **高性能计算 (HPC)** | MPI 进程并行, OpenMP 多线程加速, Intel MKL/oneAPI, Linux 集群作业调度 (Slurm) | 具备大型超算多节点协同调度、矩阵计算加速与高并发批处理调优经验 |
| **跨界工程栈 (Interests)**| Kotlin (Android Jetpack Compose, Media3), OpenCV (YuNet DNN), 轻量 Web HUD | 业余探索；独立构建全平台原生应用、多模态视觉处理与跨端系统发布 |

---

## 💡 业余爱好与极客造物 (Passionate Explorations & Side Projects)

> *“在主业追求数理严谨与算力极限的同时，业余时间我热衷于把前沿的交互与工程灵感快速转化为高完成度的真实产品。”*

### 🚀 [FutureWork](https://github.com/l1Ha/FutureWork) · 全平台多模态自然交互生产力核心
**探索后键盘鼠标时代，人与生产力工具之间的自然交互方式**
- **多模态感知流**：接入真实物理摄像头画面，基于 OpenCV 官方轻量 **YuNet DNN** 实现 CPU 实时人脸与视线锁定（5ms 超低延迟，强抗低光与侧脸），配合 FACS 动作单元分析微表情认知负荷，基于肤色与凸包缺陷（Convexity Defects）几何分析单指指向、张手、握拳与点赞手势；
- **异步时间窗口高斯对齐**：针对摄像头（30fps）、麦克风（语音断句延时）与眼动仪异步异构时序，采用动态高斯衰减时间窗口（$W(t) = \exp(-\frac{\Delta t^2}{2\sigma^2})$）精准对齐说话发音时的指代锚点与视线；
- **自适应认知与安全沙盒**：支持双通道意图消歧、动态条件控制流（`如果...就...否则...`）、长期遗忘曲线情境记忆与智能反悔回填；严密拦截远程代码执行等安全红线；
- **全平台发行交付**：独立产出 **Android APK**（内置摇一摇拒绝与震动反馈）、**Linux 原生 ELF 独立应用**、**Windows 便携免安装包**与可视化 Web HUD，全项目 **412 项自动化测试 100% 通过**，端到端 P95 延迟约 **0.34ms**。

---

### 🌙 [LunaMusic](https://github.com/l1Ha/LunaMusic) · 现代 Android 本地音乐播放器
**基于 Google 现代 Android 架构指南（Modern Android Development）打造的高颜值沉浸式音频播放器**
- **响应式 UI 体系**：采用 **Kotlin + Jetpack Compose** 全声明式构建，深度适配 Material You (Material 3) 动态壁纸取色系统与流体过渡动效；
- **工业级音频链路**：底层基于 **AndroidX Media3 (ExoPlayer)** 实现无缝高保真音频回放，内置专业多段图形均衡器、平滑歌词滚动引擎与睡眠定时器；
- **单向数据流架构**：严格遵循 UDF 与 MVI 响应式状态管理，模块化解耦，保持极高的代码纯净度与交互流畅度。

---

### 🎬 [DynamicsVideo (DyV)](https://github.com/l1Ha/DynamicsVideo) · 动态视频格式与生态探索
**面向低带宽与高静态屏幕场景的新型轻量多媒体生态**
- 针对传统视频编码在高静态画面下的冗余，探索局部像素差分刷新与自适应可变帧率（VFR）格式设计；
- 自主编写跨平台文件转换工具链、Web 轻量播放器与自动化测试工作流，采用双许可商业开源模式运作。

---

### 📚 [FutureTxt](https://github.com/l1Ha/FutureTxt) · 知识驱动的长文本自动化创作流水线
**硬核科幻叙事体系与自然语言工程工作流的结合实践**
- 设计涵盖世界观构筑、角色弧光、情节树推演、章节生成及前后文一致性约束的 8 阶段自动化结构创作流；
- 成功验证产出长达 20 章的高密度硬核科幻小说《意识纪元》全本，验证复杂知识图谱在长内容生成中的稳定性。

---

### ⚡ [filex](https://github.com/l1Ha/filex) & 📱 [shikeji](https://github.com/l1Ha/shikeji) · 解决日常痛点的极简跨端工具
- **filex**：纯静态、零依赖的局域网跨设备文件互传 Web 应用，手机与电脑浏览器秒级直连传输；
- **时刻计 (shikeji)**：微信健康提醒小程序及配套 Android 原生应用，集成久坐提醒、呼吸冥想与健康打卡功能。

---

## 📊 GitHub 研发活跃度 (Activity & Stats)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=l1Ha&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=l1Ha&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Top Languages" />
</div>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=l1Ha&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</p>

---

## 🎯 意向与合作方向 (Research Interests & Career Focus)

- 🔬 **主要意向与研究方向**：
  - **量子计算 / 量子动力学仿真研究员** (Quantum Dynamics & Physical Simulation Researcher)
  - **AI for Science (AI4S) 算法研发专家** (物理神经网络、势能面拟合、深度学习加速科学计算)
  - **高性能计算 (HPC) 与物理仿真模拟工程师** (High-Performance Scientific Computing)
  - **跨界前沿技术 / 基础系统攻坚工程师**
- 📍 **地点偏好**：深圳、北京、上海、杭州、远程合作 (Remote)
- 🤝 **核心特质总结**：
  - **深厚数理科学底蕴**：物理理论功底扎实，精通复杂量子微分方程数值离散与微观演化算法；
  - **极客自驱力与全栈实现力**：业余时间自发打磨出多款覆盖多模态交互、Android 与媒体格式的工业级开源产品，学习与技术迁移能力极快；
  - **求真务实的代码工程素养**：坚持测试驱动（数百项自动化测试保障），注重真实场景证据链，拒绝浮夸包装。

---

<div align="center">

### 📫 期待与物理学、科学智能 (AI4S) 或前沿科技领域的同行及团队深入交流！

[![Email](https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:12331061@mail.sustech.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-l1Ha-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/l1Ha)

*Copyright © 2026 LI Hao. Driven by quantum physics, empowered by AI & code.*

</div>
