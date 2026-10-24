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
- **CAD/BIM 内核研发:** 为基于 **Rust** 的跨平台开源 CAD 渲染与几何核心 ([OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio), [SolidCraft](https://github.com/tangency-labs/solidcraft)) 贡献代码；研发基于 **.NET 10** 的专业 CAD 引擎 ([VNCAD](https://github.com/vandang890615/vncad))；探索基于 **MCP** 协议的 AI 辅助图纸自动化生成。
- **工程自动化工具链:** 钢结构制造车间排产调度流水线、BOM 物料清单处理管道及 AutoLISP / Python 工程自动化脚本。

---

### 开源项目贡献 (Open-Source Impact)

为国际 CAD 核心和 3D 几何算法库贡献核心代码：

| 仓库 (Repository) | 合并 PR | 贡献内容与影响 | 技术栈 | 状态 |
|:---|:---:|:---|:---:|:---:|
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#2069](https://github.com/HakanSeven12/OpenCADStudio/pull/2069) | 修复 DXF 图纸中多行文本（MTEXT）段落缩进与制表符坐标的图元单位计算偏差 | `Rust` `CAD Engine` `DXF` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#1960](https://github.com/HakanSeven12/OpenCADStudio/pull/1960) | 引入 Fluent 本地化多语言资源包 | `Rust` `Fluent i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#5823](https://github.com/tangency-labs/solidcraft/pull/5823) | 完整补全 SolidCraft v0.21.0 越南语本地化语言包（2,385 词条，100% 覆盖） | `Rust` `3D CAD` `i18n` | ![CI Passed](https://img.shields.io/badge/CI%20Passed-2ea44f?style=flat-square&logo=githubactions&logoColor=white) |
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
