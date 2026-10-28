<div align="center">

<!-- Custom Engineered Hero Banner -->
<img src="./assets/hero-banner.svg" alt="Structural & CAD Architecture" width="100%" />

<br/><br/>

<p align="center">
  <a href="README.md">English</a> &bull;
  <a href="README.vi.md">Tiếng Việt</a> &bull;
  <a href="README.ru.md">Русский</a> &bull;
  <b>中文</b> &bull;
  <a href="README.fa.md">فارسی</a>
</p>

</div>

---

### 个人简介

**范登 (Van Dang)** — 结构工程师 / CAD与BIM内核开发工程师。

专注于重型工业钢结构工程与底层工程软件研发：
- **钢结构工程:** 依据 AISC、Eurocode 及 TCVN 规范进行工业重型钢结构设计与深化图（Shop Drawing）设计；3D 参数化结构精细建模、节点连接验算以及工厂数控（CNC）切割套料。
- **CAD/BIM 内核研发:** 为基于 **Rust** 与 **Python** 的跨平台开源 CAD/BIM 核心 ([SolidCraft](https://github.com/tangency-labs/solidcraft), [IngeTrazo](https://github.com/ingelibre/ingetrazo), [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio)) 贡献代码；研发基于 **.NET 10** 的专业 CAD 引擎 ([VNCAD](https://github.com/vandang890615/vncad))；探索基于 **MCP** 协议的 AI 辅助图纸自动化生成。
- **工程自动化工具链:** 钢结构制造车间排产调度流水线、BOM 物料清单处理管道及 AutoLISP / Python 工程自动化脚本。

---

### 开源项目贡献 (Open-Source Impact)

为国际 CAD 核心和 3D 几何算法库贡献核心代码：

| 仓库 (Repository) | 合并 PR | 贡献内容与影响 | 技术栈 | 状态 |
|:---|:---:|:---|:---:|:---:|
| [**IngeTrazo**](https://github.com/ingelibre/ingetrazo) | [#936](https://github.com/ingelibre/ingetrazo/pull/936) | 完整集成越南语本地化语言包（3,036 词条），使越南语成为其第 11 种官方语言并补齐 Qt 标准对话框按钮翻译 | `Python` `Qt/PySide6` `BIM/CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#5823](https://github.com/tangency-labs/solidcraft/pull/5823) | 全面更新 SolidCraft v0.24.0 越南语本地化目录（3,309 / 3,309 词条，100% 覆盖）并将 vi 纳入 COMPLETE 核心语言组 | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#2069](https://github.com/HakanSeven12/OpenCADStudio/pull/2069) | 修复 DXF 图纸中多行文本（MTEXT）段落缩进与制表符坐标的图元单位计算偏差 | `Rust` `CAD Engine` `DXF` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#1960](https://github.com/HakanSeven12/OpenCADStudio/pull/1960) | 引入 Fluent 本地化多语言资源包 | `Rust` `Fluent i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#2915](https://github.com/tangency-labs/solidcraft/pull/2915) | 为纯 Rust 参数化 3D CAD 软件新增越南语本地化支持 | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |

---

### 技术栈与工具箱

#### 编程语言与开发环境
<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,cs,python,cpp,ts,bash,git,docker,linux,postgres&perline=10" />
</div>

<br/>

#### CAD / BIM 与工程软件
| 领域 | 开源技术与核心框架 | 核心技术能力 |
|:---|:---|:---|
| **CAD 核心引擎** | SolidCraft, OpenCADStudio, FreeCAD, VNCAD | Rust WebGPU 渲染加速 (wgpu), DXF/DWG 解析引擎, .NET 10 CAD 架构, AutoLISP 自动化 |
| **BIM 与 3D 几何** | Open BIM (IFC 标准), Blender 3D, 参数化建模器 | 3D 结构精细建模, BOM/BBS 物料清单自动化生成, CNC 套料数据流水线, 计算几何算法 |
| **后端与工业系统** | .NET 10, FastAPI, SQLite, PostgreSQL, Rust | 高性能计算引擎, MCP 自动化服务协议, 工程图纸自动化协议 |

---

### 🚰 工程架构哲学：“管道”心智模型 (The Pipeline Mental Model)

> *“土木与机电工程师铺设物理管网以保障工业设施运转；软件工程师架构数据管道以驱动现代数字世界。”*

<details>
<summary><b>中文：工程架构哲学——为什么技术世界本质都是“管道”？</b></summary>
<br/>

我有着工业重型钢结构与机电工程（MEP）的工程实践背景。在设计底层核心软件系统时，我发现自己做的事情如出一辙：把“流体”以额定的流量和压力，精准稳定地从一处输送到另一处，杜绝泄漏，并在事故发生时具备阀门切断保护。唯一的不同，在于现在的流体是数据。

#### 🗺️ 物理管网与软件工程映射图谱

| 🏠 物理管网 (土木 / 机电 MEP) | 💻 软件工程等价概念 | ⚙️ 实际工程项目落地实践 |
| :--- | :--- | :--- |
| **水、气体、流体** | **数据 (字节流、文本、向量、Token)** | 在内存堆栈与计算线程中流动的原始物质。 |
| **建筑室内管道** | **本地管道 (`stdio`, IPC, 共享内存)** | 本地 **MCP 服务器** 与宿主 CAD/BIM 软件（SolidCraft、VNCAD、IngeTrazo）实现零网络开销毫秒级指令通信。 |
| **市政地下主干管网** | **网络通信协议 (HTTP, WebSockets)** | 钢结构制造车间排产调度终端与云端控制中心之间的分布式数据同步。 |
| **高承压装甲加固管道** | **加密通信隧道 (SSH, VPN, TLS/HTTPS)** | 加密保障工业 Shop Drawing 详图资产及 CNC 数控套料数据在传输中防窃听防篡改。 |
| **调压阀门与净水处理站** | **API 网关与数据清洗管道** | 在复杂 3D 几何拓扑解算前进行动态流控拦截与数据模型验证。 |
| **持续流淌的自来水龙头** | **数据流式传输 (`Readable` / `Writable`)** | 对几百兆的重型 BIM 几何模型与 Tekla BOM 物料清单进行流式按需加载，彻底避免内存溢出 (OOM)。 |

#### 🔧 管网需要沿线设备保障

管道仅承担输送职能。一个完整可靠的管网系统必须配备沿线管件与动力设备：

| 🏠 沿线物理设备 (MEP / 供水管网) | 💻 软件架构等价概念 | ⚙️ 钢结构制造与工程场景实战 |
| :--- | :--- | :--- |
| **储水池 / 储罐** | **数据库、持久化存储** | Master BOM 总物料清单数据库、钢材现货库存与工序进度表。 |
| **加压水泵** | **CPU/GPU 算力集群、Worker 进程** | 空间结构有限元求解计算、工程量自动统计线程。 |
| **缓冲水箱 (Surge Tank)** | **消息队列、内存缓冲区 (Buffer/Queue)** | 图纸处理任务排队削峰，防止并发峰值击垮后端服务。 |
| **流量计量表** | **系统可观测性、日志监控 (Monitoring/Log)** | 实时追踪吞吐量指标与管线瓶颈节点定位。 |
| **止回阀 (单向阀)** | **限流策略 (Rate Limiting) / 单向同步** | 阻断逆向脏数据回流，防止接口遭遇突发流量雪崩。 |
| **安全泄压阀** | **熔断机制 (Circuit Breaker)** | 当下游节点故障时主动切断支路，防止故障级联蔓延至全系统。 |

#### 📐 用工程物理指标拆解抽象术语
* **协议 (Protocol)：** *管道螺纹与法兰标准。* 接口两端必须具备完全匹配的口径规格与螺纹参数（如 JSON-RPC、REST、gRPC），流体才不会泄漏。
* **带宽 (Bandwidth)：** *管道内径截面。* 管道越粗，每秒流过的工程图纸数据通量（MB/s）就越大。
* **延迟 (Latency)：** *管道物理长度。* 第一滴水跨越地理距离流抵出水端所需的物理耗时。
* **背压机制 (Backpressure)：** *管道逆向憋压。* 当下游消费端处理缓慢时，压力向源头反馈以动态调节发包速率，这是保障百兆 BIM 大文件不引发 OOM 崩溃的核心。
* **泄漏与堵塞 (Leaks & Deadlocks)：** 内存泄漏 (*Memory Leak*) 如暗漏之滴水穿石；死锁 (*Deadlock*) 如两端阀门互锁死等，无一能够泄流。
* **🧬 Unix 管道哲学与 MCP 传承：** 1970 年代，UNIX 创始人发明了竖线 `|`（管道操作符），将前一个程序的 `stdout` 无缝注入后一个程序的 `stdin`。今天大火的 **Model Context Protocol (MCP)** 在 `stdio` 模式下本质就是纯粹的管道：JSON-RPC 消息通过 `stdin`/`stdout` 在 AI 智能体与 CAD 工业软件之间自由流淌。

> *🎯 核心启示：机电工程师无需洞悉每个水分子的微观物理；他们掌控的是压力、流速、接口、阀门与蓄水池。软件架构亦然：理清数据水系的流向，再庞大的系统也井然有序。*

</details>

---

### 自研工程系统与架构

作为核心架构师与独立作者主导研发的工程计算引擎与系统：

| 系统 / 软件 | 技术栈 | 核心能力与功能定位 | 角色 / 状态 |
|:---|:---:|:---|:---:|
| **VNCAD Engine** | `.NET 10` `C#` `MCP` | 面向钢结构深化设计的轻量级高性能 2D CAD 引擎，支持 MCP 协议驱动 AI 制图。 | 核心架构师 / 研发中 |
| **Structural Fabrication Twin** | `FastAPI` `Python` `OpenBIM` | 重型钢结构加工车间实时生产排产系统、矢量甘特图调度与数控套料数据流水线。 | 独立作者 / 生产运行 |
| **VietStruct Detailing Suite** | `AutoLISP` `.NET` `Python` | 钢结构图纸自动化生成工具、参数化节点深化程序及 TCVN/AISC 规范校核。 | 独立作者 / 生产运行 |
| **Material Takeoff & BBS Engine** | `Python` `PyQt5` `SQLite` | 结构钢材与钢筋材料清单（BOM）自动提取、钢筋下料表（BBS）生成及构件几何算量算法。 | 独立作者 / 生产运行 |

---

### 联系方式

<div align="center">

<p align="center">
  <a href="mailto:vandang890615@gmail.com">
    <img src="https://img.shields.io/badge/Email-vandang890615%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/vandang890615">
    <img src="https://img.shields.io/badge/GitHub-vandang890615-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

</div>
