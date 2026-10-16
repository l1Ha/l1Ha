<div align="center">

# Hi there, I'm LI Hao 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=06B6D4&center=true&vCenter=true&width=680&lines=Quantum+Dynamics+%26+AMO+Physics+Researcher;HPC+%26+Scientific+Computing+Engineer+(Modern+Fortran+%2B+Python);Developer+of+QGM+(QuantumGeneralModule)+%26+AQD;Curious+Builder+of+Next-Gen+Tech+%26+Tools)](https://git.io/typing-svg)

<p align="center">
  <a href="mailto:12331061@mail.sustech.edu.cn">
    <img src="https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Education-SUSTech-8B5CF6?style=flat-square&logo=academia&logoColor=white" alt="SUSTech" />
  <img src="https://img.shields.io/badge/Location-Shenzhen%2C%20China-06B6D4?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-10B981?style=flat-square&logo=gitbook&logoColor=white" alt="Open to Work" />
</p>

</div>

---

## 🔬 专业定位 (Professional Overview)

我是一名主攻**量子动力学（Quantum Dynamics）与高性能科学计算（Scientific Computing / HPC）**的计算物理研究人员，目前在**南方科技大学 (SUSTech)** 开展研究。

- ⚛️ **核心主业：量子物理与前沿数值计算**
  - **研究领域**：原子分子与光物理 (AMO Physics)、量子波包时间演化动力学 (Wavepacket Dynamics)、量子反应散射 (Reactive Scattering)、强场超快光学 (HHG, Ultrafast Optics) 及非绝热耦合动力学 (Non-adiabatic Dynamics)；
  - **旗舰成果**：自主研发量子动力学底层算法通用库 **QGM (QuantumGeneralModule)** 与势能面自动化拟合系统 **AQD (AutoQuantumDynamics / AutoQuantumPES)**；
  - **算法与仿真**：深入掌握并独立实现 Sinc-DVR (离散变量表象法)、Split-Operator 分步算符谱方法、虚时间演化基态求解、吸收势边界 (CAP/PML) 及精确量子反应散射矩阵求解；
  - **AI for Science**：精通高维势能面 (PES) 从头算计算流程 (PySCF / xTB / ASE) 与神经网络机器势能面高精度拟合，具备大型 Slurm 超算集群高通量任务编排与并行加速经验。

- 💡 **业余探索：极客好奇心与软件工程爱好 (Side Interests)**
  - 在主业科研之余，我保持着对计算机底层与前沿技术的充沛热情，利用业余时间探索了**未来多模态自然人机交互核心** (`FutureWork`)、**现代 Android 应用架构** (`LunaMusic`)、**新型动态视频格式** (`DynamicsVideo`) 等跨界开源项目，具备完整的跨平台工程落地与自动化构建交付能力。

---

## 🌟 核心科研代表作 (Flagship Scientific Projects)

### 1. 🔬 [QGM (QuantumGeneralModule)](https://github.com/l1Ha/QuantumGeneralModule) · 现代量子动力学通用算法库
> **基于 Modern Fortran 2008 与 Python 构建的高性能量子动力学演化与 AMO 物理算法库**

- **理论与算符实现**：涵盖 Sinc-DVR 表象变换、Split-Operator 时间传播算符、虚时间传播基态求解、双色/超短脉冲强场高次谐波产生 (HHG)、多势能面非绝热跃迁动力学；
- **工业级严谨度**：代码架构严格模块化，配套完善的测试驱动开发（TDD）体系，**390+ 项自动化物理与数值测试 100% 全绿通过**；
- **文献追踪完备**：详细对齐 PRL、PRA、RMP、Science、Nature 等 40 余篇经典与前沿文献算符基准。

---

### 2. 🧬 [AQD (AutoQuantumDynamics)](https://github.com/l1Ha/AutoQuantumDynamics) & [AutoQuantumPES](https://github.com/l1Ha/AutoQuantumPES) · 自动化量子动力学与势能面拟合系统
> **电子结构从头算 → 势能面扫描工作流 → 数据集主动学习 → 神经网络拟合的全栈闭环**

- **多后端计算引擎集成**：原生兼容并调度 PySCF、xTB 与 ASE，支持闭壳层/开壳层分子从头算单点能、平衡几何优化与全振动频率分析；
- **动力学路径与光谱特性**：支持任意内坐标网格扫描、NEB 过渡态搜索、IRC 反应路径追踪以及激发态 TD-DFT 与自旋-轨道耦合 (SOC) 效应计算；
- **AI for Science**：设计神经网络势能面自动拟合与误差主动收敛流水线，内置 Slurm 超算作业模板与计算收敛证据链。

---

### 3. 🎯 [ABC_S](https://github.com/l1Ha/ABC_S) & [molscat](https://github.com/l1Ha/molscat) · 量子反应散射模拟
> **原子-双原子碰撞与化学反应量子态-态散射动力学演化**

- 采用现代 Fortran 重构并优化经典 ABC 量子反应散射计算架构，引入紧致动力学表象；
- 实现超精细能级散射矩阵与态态微分反应截面计算，针对大规模矩阵对角化与坐标变换实施内存局部性优化。

---

## 🛠️ 技术矩阵 (Tech Stack Radar)

```
  [ 核心主业 · 科学计算与量子物理 ] ─────── [ 业余探索 · 前沿软件工程与 AI ]
  • Modern Fortran (2008 / 2018)            • 多模态人机交互 (Visual/Gaze/FACS/Speech)
  • Python (NumPy / SciPy / SymPy)          • OpenCV (DNN YuNet / 几何缺陷分析)
  • MPI & OpenMP 节点级/分布式并行加速       • 现代 Android (Kotlin / Jetpack Compose / Media3)
  • Slurm 超算作业调度系统 & 集群优化       • 跨平台独立分发 (Linux ELF / Android APK / Win)
  • 量子波包传播 (Split-Operator, DVR)     • 状态机与安全沙盒防御机制
  • 从头算化学与势能面 (PySCF / xTB / ASE)  • 异步高斯时序窗口对齐
```

| 领域 | 核心技能与主要工具 |
| :--- | :--- |
| **科学计算语言** | **Modern Fortran** (2008/2018，长期密集使用，工程架构严谨), **Python 3** (算法实现、数据流水线与高通量编排), **Bash/Shell** |
| **量子动力学与物理模拟** | Sinc-DVR, Split-Operator, 高次谐波产生 (HHG), 非绝热演化 (Non-adiabatic Transition), 散射理论 (ABC Scattering, Molscat), 光电离/光解离模拟 |
| **计算化学与 AI4S** | 势能面 (PES) 扫描与优化, NEB (微动弹性带过渡态搜索), IRC, 激发态与自旋-轨道耦合 (SOC), 神经网络拟合势 (NN PES) |
| **高性能计算 (HPC)** | MPI 进程级并行, OpenMP 共享内存加速, Intel oneAPI / MKL / FFTW 数学库, Linux 超算集群 (Slurm) 自动化批处理 |
| **业余探索栈 (Interests)** | Kotlin (Android Jetpack Compose, Media3), OpenCV (DNN 人脸/视线/手势追踪), 跨平台打包 (PyInstaller ELF / APK 签名构建) |

---

## 💡 个人业余兴趣与技术探索 (Side Projects & Explorations)

在主业科研之余，我常利用业余时间把玩各种好玩的前沿技术，探索人机交互、移动应用与多媒体领域的可能性：

| 项目 | 领域方向 | 亮点与技术特性 |
| :--- | :--- | :--- |
| 🚀 [**FutureWork**](https://github.com/l1Ha/FutureWork) | **多模态人机自然交互** | 自主研发用语音、3D手势、FACS面部微表情、视线注视直接指挥生产力工具的核心系统；实现异步高斯时序对齐、条件流执行、长期记忆持久化，支持 Android APK、Linux 独立二进制与 Windows 全平台分发（**408 项测试全绿**）。 |
| 🌙 [**LunaMusic**](https://github.com/l1Ha/LunaMusic) | **现代 Android 应用** | 基于 Kotlin + Jetpack Compose + Media3 (ExoPlayer) 架构打造的本地高颜值音乐播放器，遵循 Material You 响应式动态主题，包含专业音频均衡器与歌词系统。 |
| 🎬 [**DynamicsVideo**](https://github.com/l1Ha/DynamicsVideo) | **动态视频多媒体** | 探索局部差分像素刷新与自适应可变帧率（VFR）的轻量视频封装格式与播放器生态。 |
| 📚 [**FutureTxt**](https://github.com/l1Ha/FutureTxt) | **知识图谱与长文生成** | 构筑 8 阶段自动化结构创作流，验证产出 20 章架构严密的硬核科幻小说《意识纪元》全本。 |
| ⚡ [**filex**](https://github.com/l1Ha/filex) | **跨端轻量网络工具** | 纯静态极简局域网跨设备文件互传 Web 应用，手机与电脑浏览器秒级互通。 |

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

- 🔬 **主要意向方向**：
  - **量子计算 / 量子动力学演化仿真研究员** (Quantum Dynamics & Simulation Researcher)
  - **科学计算与高性能计算 (HPC) 工程师** (High-Performance Scientific Computing)
  - **AI for Science (AI4S) 算法研发** (物理神经网络、势能面与分子模拟建模)
  - **基础软件与前沿技术攻坚工程师**
- 📍 **地点偏好**：深圳、北京、上海、杭州、远程合作 (Remote)
- 🤝 **特质总结**：
  - **深厚数理功底 + 扎实代码力**：能推导复杂物理公式，能写出测试严谨、规范优雅的底层高性能代码；
  - **极客自驱力**：业余时间自发打磨出多项工程完备的跨界开源产品，学习与技术迁移能力极强；
  - **求真务实**：注重实际验证数据与证据链，拒绝浮夸宣传。

---

<div align="center">

### 📫 期待与物理学、科学计算或前沿技术领域的同行深入交流！

[![Email](https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:12331061@mail.sustech.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-l1Ha-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/l1Ha)

*Copyright © 2026 LI Hao. Driven by physics, crafted with code.*

</div>
