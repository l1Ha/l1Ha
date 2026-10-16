<div align="center">

# Hi there, I'm LI Hao (李浩) 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=06B6D4&center=true&vCenter=true&width=620&lines=AI+%26+Multimodal+Interaction+System+Engineer;Quantum+Dynamics+%26+HPC+Researcher;Passionate+Builder+of+Next-Gen+Productivity+Tools;Bridging+Physical+Computing+%26+Modern+AI)](https://git.io/typing-svg)

<p align="center">
  <a href="mailto:12331061@mail.sustech.edu.cn">
    <img src="https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Location-Shenzhen%2C%20China-06B6D4?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Education-SUSTech-8B5CF6?style=flat-square&logo=academia&logoColor=white" alt="SUSTech" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-10B981?style=flat-square&logo=gitbook&logoColor=white" alt="Open to Work" />
</p>

</div>

---

## 👨‍💻 关于我 (About Me)

我是一名兼具**前沿 AI 与多模态人机交互（HCI）系统工程力**与**量子物理/超算科学计算（HPC & AI for Science）深厚底蕴**的复合型创新研发工程师 / 研究员，目前就读于**南方科技大学 (SUSTech)**。

- 🧠 **双核驱动的技术底色**：
  - **前沿 AI & 多模态交互**：自主设计从视觉注视、微表情认知、3D 手势识别、语音韵律到异步时间窗高斯对齐、意图状态机与全平台工具调度的端到端人机自然交互架构。
  - **超算与科学计算 (AI for Science)**：精通量子动力学（Sinc-DVR、Split-Operator、HHG、非绝热动力学）与从头算势能面（PES）机器学习拟合，具备大型 HPC 超算集群（Slurm / MPI 并行优化）底层开发经验。
- 📱 **工业级全栈工程交付**：
  - 从底层的跨平台独立原生二进制编译（Linux ELF）、Android 原生现代应用架构（Kotlin + Jetpack Compose + Media3）、Windows 便携分发包到零依赖轻量跨端 Web HUD，具备独立完成**产品架构、算法落地、自动化测试与跨端全平台发行**的完整闭环能力。
- 🛡️ **对工程质量保持敬畏**：
  - 核心开源项目自动化测试覆盖率高（400+ 项测试全绿），重视系统安全与边界防御（全链路防御代码注入、越权与目录穿越），追求亚毫秒级性能与极致交互流畅感。

---

## 🛠️ 核心技能图谱 (Skills & Competencies)

```
  [ 前沿 AI & 多模态 HCI ] ──── [ 高性能计算 HPC & AI4S ] ──── [ 现代移动端与系统工程 ]
  • OpenCV (YuNet DNN)          • Modern Fortran (2008/18)      • Android (Kotlin / Compose)
  • 视觉视线注视追踪 (Gaze)      • MPI & OpenMP 并行计算          • Media3 / Material You 架构
  • FACS 微表情与注意力分析      • Slurm 集群任务调度 & 优化      • Linux ELF 原生应用打包
  • 3D 手势几何分析 (YCrCb)     • 量子动力学 (Wavepacket/HHG)   • Windows 便携式分发构建
  • 异步高斯时序窗口对齐         • 势能面 (PES) 拟合 (PySCF/xTB) • 轻量 Web HUD / MCP 协议
```

| 维度 | 掌握技能与工具链 |
| :--- | :--- |
| **编程语言** | **Python** (高频/高级), **Modern Fortran** (2008/2018 科学计算), **Kotlin** (Android 现代架构), **C/C++**, **JavaScript/TypeScript**, **Bash Shell**, **SQL** |
| **人工智能 & 计算机视觉** | OpenCV (DNN 人脸检测、Haar 级联族、CLAHE 自适应增强), FACS 动作单元分析, 凸包缺陷手势分类, 语音韵律流式处理, 语义向量检索 (Embedding & Cosine Similarity) |
| **科学计算 & AI for Science** | PySCF, xTB, ASE, NumPy, SciPy, Sinc-DVR, Split-Operator, 分子/原子反应散射计算 (ABC, Molscat), 势能面神经网络拟合 |
| **系统架构与韧性工程** | 声明式能力抽象 (Capability Registry), 有限状态机 (FSM), 动态控制流执行, 指数退避重试 (Exponential Backoff), 熔断器 (Circuit Breaker), 撤销快照栈 (Undo Manager), 安全沙盒 |
| **平台与 DevOps 工具** | Linux / Ubuntu, Windows 10/11, Android SDK (aapt2/r8/d8), Git & GitHub Actions CI/CD 矩阵发布, PyInstaller, Docker |

---

## 🌟 旗舰开源代表作 (Featured Projects)

### 1. 🚀 [FutureWork](https://github.com/l1Ha/FutureWork) · 全平台多模态自然交互生产力核心
> **面向未来人机交互的革命性范式：让人类用语言、手势、微表情与视线注视直接指挥生产力工具**

- **多模态感知流**：接入真实摄像头与视频流，结合轻量 **YuNet DNN** 实现 CPU 实时人脸与注视追踪、FACS 表情认知负荷分析、3D 手势几何分析及点头/摇头确认检测；
- **异步时间窗口高斯对齐**：采用高斯核时间衰减滑动缓冲模型，消除各物理硬件（摄像头 30fps、麦克风 VAD、眼动仪）之间的传输延迟与采样率异步错位；
- **自适应认知引擎**：中英双语双通道意图匹配、动态条件控制流（`如果...就...否则...`）、指代消解与反悔纠正（`不对，应该是 X` 槽位智能回填）；
- **跨会话长期情境记忆**：引入**艾宾浩斯遗忘曲线（Ebbinghaus decay）**与访问频次加权激活评分，跨进程、跨会话秒级唤醒“刚才那个文件”；
- **安全与全平台发行**：内置多层黑名单防御与状态快照撤销；提供 **Android APK**、**Linux 独立 ELF**、**Windows 便携发行版**及 Web HUD 控制台，单项目 **408 项自动化测试 100% 通过**，端到端 P95 延迟维持在亚毫秒级（~0.34ms）。

---

### 2. ⚛️ [QuantumGeneralModule](https://github.com/l1Ha/QuantumGeneralModule) & [AutoQuantumPES](https://github.com/l1Ha/AutoQuantumPES) · 量子动力学与科学计算算法库
> **凝聚态物理、原子分子光物理（AMO Physics）高精度动力学演化与 AI for Science 势能面拟合**

- 基于 **Modern Fortran 2008 & Python** 构建，实现 Sinc-DVR、Split-Operator 时间演化、高次谐波产生 (HHG) 及超快非绝热动力学算法；
- 集成 PySCF / xTB / ASE 计算化学后端，支持平衡几何优化、过渡态扫描、NEB / IRC 计算及激发态自旋-轨道耦合 (SOC)；
- 提供神经网络 (NN) 势能面机器学习高精度拟合与大规模 Slurm 超算任务自动化编排。

---

### 3. 🌙 [LunaMusic](https://github.com/l1Ha/LunaMusic) · 现代 Android 音乐播放器
> **基于 Google 现代 Android 架构指南（Modern Android Development）打造的高颜值本地播放器**

- 采用 **Kotlin + Jetpack Compose** 全声明式 UI 构建，遵循 Material You (Material 3) 动态色彩系统；
- 底层接入 **AndroidX Media3 (ExoPlayer)**，支持高质量专业音频回放、内置多段均衡器调节、歌词同步滚动与睡眠定时器；
- 遵循单向数据流（UDF）与响应式状态驱动架构，具有极佳的代码可读性与平滑交互体验。

---

### 4. 🎬 [DynamicsVideo](https://github.com/l1Ha/DynamicsVideo) · 动态视频格式生态 (DyV)
> **探索轻量级局部刷新、可变帧率（VFR）的未来多媒体生态**

- 针对低带宽与高交互场景设计新型动态视频封装机制，支持智能局部像素差分与自适应帧率刷新；
- 配套提供跨平台转换工具链、Web 轻量播放器与完善的 CI/CD 流程，采用健全的双许可商业化开源架构。

---

### 5. 📚 [FutureTxt](https://github.com/l1Ha/FutureTxt) · 长文本智能创作流水线
> **面向复杂知识图谱与创意叙事的内容生成工作流**

- 包含 8 阶段自动化结构创作流水线（角色设定、世界观构筑、脉络推演、章节生成与前后一致性校验）；
- 成功验证产出长达 20 章的高密度硬核科幻小说《意识纪元》全书文本。

---

## 📊 GitHub 活跃度与技术统计 (Stats)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=l1Ha&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=l1Ha&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Top Languages" />
</div>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=l1Ha&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</p>

---

## 🎯 求职意向与个人特质 (Career Goals & Culture Fit)

- 💼 **意向岗位**：
  - **AI 算法 / 系统研发工程师**（多模态感知、具身智能人机交互、Agent 智能体系统）
  - **科学计算 / AI for Science 研究员 / 工程师**（HPC 高性能计算、量子计算模拟、应用物理数学算法）
  - **跨平台基础软件 / 核心系统工程师**（Linux / Android / C++ / Python 高性能后端）
- 📍 **意向地点**：深圳、北京、上海、杭州、远程办公 (Remote)
- 💡 **工作态度**：
  - **深入本质，不惧底层**：习惯探究代码底层逻辑与物理模型，能啃硬骨头；
  - **全栈全局观**：既能做前沿算法理论推导，又能一站式打包发布全平台生产级应用；
  - **积极敏捷，高效交付**：擅长将抽象需求转化为高可测、高扩展、优雅健壮的工程落地。

---

<div align="center">

### 📫 期待与优秀的团队同行，共同创造触碰未来的产品与科技！

[![Email](https://img.shields.io/badge/Email-12331061%40mail.sustech.edu.cn-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:12331061@mail.sustech.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-l1Ha-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/l1Ha)

*Copyright © 2026 LI Hao. Built with precision and passion.*

</div>
