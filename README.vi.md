<div align="center">

<!-- Custom Engineered Hero Banner -->
<img src="./assets/hero-banner.svg" alt="Structural & CAD Architecture" width="100%" />

<br/><br/>

<p align="center">
  <a href="README.md">English</a> &bull;
  <b>Tiếng Việt</b> &bull;
  <a href="README.ru.md">Русский</a> &bull;
  <a href="README.zh.md">中文</a> &bull;
  <a href="README.fa.md">فارسی</a>
</p>

</div>

---

### Giới Thiệu

**Văn Đăng** — Kỹ sư Kết cấu & Kỹ sư Phát triển Lõi CAD/BIM.

Lĩnh vực chuyên môn trọng tâm:
- **Kỹ thuật Kết cấu:** Thiết kế & lập bản vẽ chi tiết (Shop Drawing) kết cấu thép công nghiệp nặng theo tiêu chuẩn AISC, Eurocode, TCVN; mô hình hóa kết cấu 3D tham số, thiết kế liên kết và chuẩn bị dữ liệu phôi cắt CNC.
- **Phát triển Lõi CAD/BIM:** Đóng góp cho hệ sinh thái CAD/BIM mã nguồn mở bằng **Rust** và **Python** ([SolidCraft](https://github.com/tangency-labs/solidcraft), [IngeTrazo](https://github.com/ingelibre/ingetrazo), [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio)), phát triển engine CAD hiệu năng cao trên nền tảng **.NET 10** ([VNCAD](https://github.com/vandang890615/vncad)), và tự động hóa quy trình vẽ kỹ thuật qua giao thức **MCP (Model Context Protocol)**.
- **Công cụ Kỹ thuật & Hạ tầng:** Xây dựng hệ thống điều độ sản xuất chế tạo thép, đường ống xử lý dữ liệu vật tư (BOM), và các tập lệnh tự động hóa bằng AutoLISP / Python.

---

### Đóng Góp Mã Nguồn Mở

Đóng góp vào các dự án lõi CAD & hình học 3D quốc tế:

| Dự Án | Pull Request | Chi Tiết Đóng Góp | Công Nghệ | Trạng Thái |
|:---|:---:|:---|:---:|:---:|
| [**IngeTrazo**](https://github.com/ingelibre/ingetrazo) | [#936](https://github.com/ingelibre/ingetrazo/pull/936) | Tích hợp toàn diện bản địa hóa tiếng Việt (3.036 chuỗi UI), đưa tiếng Việt thành ngôn ngữ chính thức thứ 11 và bổ sung bộ dịch nút hộp thoại Qt | `Python` `Qt/PySide6` `BIM/CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#5823](https://github.com/tangency-labs/solidcraft/pull/5823) | Cập nhật hoàn thiện 100% gói bản địa hóa tiếng Việt cho v0.24.0 (3.309 / 3.309 keys) và đưa tiếng Việt vào nhóm ngôn ngữ chuẩn hoàn chỉnh (COMPLETE) | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#2069](https://github.com/HakanSeven12/OpenCADStudio/pull/2069) | Sửa lỗi tính toán thụt lề MTEXT và khoảng cách tab theo đơn vị bản vẽ trong tệp định dạng DXF | `Rust` `CAD Engine` `DXF` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#1960](https://github.com/HakanSeven12/OpenCADStudio/pull/1960) | Tích hợp gói tài nguyên chuỗi ký tự Fluent bản địa hóa | `Rust` `Fluent i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#2915](https://github.com/tangency-labs/solidcraft/pull/2915) | Tích hợp gói bản địa hóa tiếng Việt (`vi`) ban đầu cho CAD tham số 3D thuần Rust | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |

---

### Kỹ Năng & Công Cụ

#### Lập trình & Môi trường phát triển
<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,cs,python,cpp,ts,bash,git,docker,linux,postgres&perline=10" />
</div>

<br/>

#### Kỹ thuật Kết cấu & CAD/BIM
| Lĩnh vực | Nền tảng & Công nghệ mở | Năng lực Kỹ thuật cốt lõi |
|:---|:---|:---|
| **Lõi CAD** | SolidCraft, IngeTrazo, OpenCADStudio, FreeCAD, VNCAD | Tăng tốc đồ họa Rust WebGPU (wgpu), bộ phân tích định dạng DXF/DWG, kiến trúc CAD trên .NET 10, AutoLISP scripting |
| **BIM & Hình học 3D** | Open BIM (chuẩn IFC), Blender 3D, Parametric Modeler | Mô hình hóa kết cấu 3D, tự động trích xuất bảng kê BOM/BBS, xử lý dữ liệu phôi cắt CNC, thuật toán hình học tính toán |
| **Hệ thống & Backend** | .NET 10, FastAPI, SQLite, PostgreSQL, Rust | Engine tính toán hiệu năng cao, giao thức Model Context Protocol (MCP), tự động hóa bản vẽ kỹ thuật |

---

### 🚰 Triết Lý Kỹ Thuật: Bản Đồ "Đường Ống" (The Pipeline Mental Model)

> *“Kỹ sư công trình sắp đặt hệ thống ống vật lý để vận hành một nhà máy. Kỹ sư phần mềm kiến trúc hệ thống đường ống dữ liệu để vận hành thế giới số.”*

<details>
<summary><b>Tiếng Việt: Mọi thứ trong Công nghệ thực chất chỉ là "Đường Ống"</b></summary>
<br/>

Xuất phát từ nền tảng kỹ sư kết cấu & cơ điện công trình (MEP), tôi nhìn nhận và thiết kế kiến trúc phần mềm lõi thông qua mô hình tư duy **"Hệ thống Đường Ống"**:

#### 🗺️ Đối Chiếu Hệ Thống Ống Vật Lý & Kỹ Thuật Phần Mềm

| 🏠 Ống Vật Lý (Công Trình / MEP) | 💻 Khái Niệm Tương Đương Trong Phần Mềm | ⚙️ Ứng Dụng Thực Tế Trong Các Dự Án Của Tôi |
| :--- | :--- | :--- |
| **Nước, Khí gas, Dầu** | **Dữ liệu (Byte, Chuỗi ký tự, Vector, Token)** | Vật chất thô lưu chuyển trong bộ nhớ RAM và các luồng xử lý. |
| **Đường ống cục bộ trong nhà** | **Ống cục bộ (`stdio`, IPC, Bộ nhớ dùng chung)** | Cách máy chủ **MCP** trao đổi dữ liệu trực tiếp với phần mềm CAD/BIM (SolidCraft, VNCAD, IngeTrazo) với độ trễ gần như bằng không. |
| **Đường ống ngầm đô thị** | **Giao thức mạng (HTTP, WebSockets)** | Đồng bộ phân tán giữa các xưởng gia công kết cấu thép và máy chủ điều hành trung tâm. |
| **Ống thép bọc giáp bảo vệ** | **Đường hầm mã hóa (SSH, VPN, TLS/HTTPS)** | Truyền tải bảo mật bảo vệ bản vẽ kết cấu chi tiết và tệp phôi gia công CNC. |
| **Van điều tiết & Trạm lọc** | **API Gateway & Pipeline xử lý dữ liệu** | Lọc và xác thực tính toàn vẹn hình học trước khi đưa vào tính toán kết cấu. |
| **Vòi nước chảy liên tục** | **Luồng dữ liệu (Data Stream: `Readable`/`Writable`)** | Truyền tải dữ liệu mô hình BIM và BOM Tekla nặng hàng trăm MB theo từng khối (chunk) vào RAM, chống tràn bộ nhớ. |

#### 📐 Giải Mã Thuật Ngữ Kỹ Thuật Bằng Khái Niệm Vật Lý
* **Giao thức (Protocol):** *Mối nối ren và khớp tiêu chuẩn của ống.* Hai đầu nối bắt buộc phải khớp ren (JSON-RPC, REST, gRPC) mới không bị rò rỉ dữ liệu.
* **Băng thông (Bandwidth):** *Đường kính ống.* Đường kính càng rộng thì lưu lượng megabyte bản vẽ truyền tải mỗi giây càng lớn.
* **Độ trễ (Latency):** *Chiều dài đường ống.* Khoảng thời gian để giọt nước đầu tiên di chuyển từ đầu phát đến đầu thu qua khoảng cách vật lý.
* **Di sản Triết lý Unix:** Thập niên 1970, UNIX phát minh ký tự gạch đứng `|` (Pipe operator) — nối trực tiếp đầu ra (stdout) của chương trình này vào đầu vào (stdin) của chương trình khác. Ngày nay, **Model Context Protocol (MCP)** kế thừa trọn vẹn triết lý kinh điển này.

</details>

---

### Hệ Thống Kỹ Thuật Tiêu Biểu

Các engine và hệ thống kỹ thuật do chính tác giả thiết kế và phát triển:

| Hệ Thống / Phần Mềm | Công Nghệ | Mô Tả & Năng Lực Trọng Tâm | Vai Trò / Trạng Thái |
|:---|:---:|:---|:---:|
| **VNCAD Engine** | `.NET 10` `C#` `MCP` | Engine CAD 2D hiệu năng cao chuyên dụng thiết kế kết cấu theo TCVN/ISO và tự động hóa vẽ qua giao thức Model Context Protocol. | Kiến trúc sư trưởng / Đang phát triển |
| **Structural Fabrication Twin** | `FastAPI` `Python` `OpenBIM` | Hệ thống quản lý sản xuất xưởng kết cấu thép thời gian thực, điều độ Vector Gantt và đường ống dữ liệu phôi cắt CNC. | Tác giả / Vận hành thực tế |
| **VietStruct Detailing Suite** | `AutoLISP` `.NET` `Python` | Bộ công cụ tự động hóa bản vẽ kết cấu, chi tiết liên kết thép tham số và kiểm tra tiêu chuẩn TCVN/AISC. | Tác giả / Vận hành thực tế |
| **Material Takeoff & BBS Engine** | `Python` `PyQt5` `SQLite` | Thuật toán bóc tách bảng kê vật tư kết cấu thép và bê tông (BOM), tự động phát sinh bảng thống kê thép (BBS) và phân tích hình học cấu kiện. | Tác giả / Vận hành thực tế |

---

### Kết Nối & Hợp Tác

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

<p align="center">
  <sub>Sẵn sàng hợp tác nghiên cứu phát triển lõi CAD/BIM, tự động hóa thiết kế kết cấu và tính toán hiệu năng cao.</sub>
</p>

</div>
