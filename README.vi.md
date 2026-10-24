<div align="center">

<!-- Hero Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,14,24,35&height=160&section=header&text=V%C4%82N%20%C4%90%C4%82NG&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%" />

<p align="center">
  <img src="https://img.shields.io/badge/Chuy%C3%AAn_ng%C3%A0nh-K%E1%BA%BFt_c%E1%BA%A5u_th%C3%A9p_%26_CAD_Engine-1976D2?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Qu%E1%BB%91c_gia-Vi%E1%BB%87t_Nam-00C853?style=flat-square&logo=globe&logoColor=white" />
</p>

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
- **Kỹ thuật Kết cấu:** Thiết kế & lập bản vẽ chi tiết (Shop Drawing) kết cấu thép công nghiệp nặng theo tiêu chuẩn AISC, Eurocode, TCVN; mô hình hóa 3D với Tekla Structures, thiết kế liên kết và chuẩn bị dữ liệu phôi cắt CNC.
- **Phát triển Lõi CAD/BIM:** Đóng góp cho lõi đồ họa và hình học CAD mã nguồn mở bằng **Rust** ([OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio), [SolidCraft](https://github.com/tangency-labs/solidcraft)), phát triển engine CAD hiệu năng cao trên nền tảng **.NET 10** ([VNCAD](https://github.com/vandang890615/vncad)), và tự động hóa quy trình vẽ kỹ thuật qua giao thức **MCP (Model Context Protocol)**.
- **Công cụ Kỹ thuật & Hạ tầng:** Xây dựng hệ thống quản lý sản xuất xưởng cơ khí, đường ống xử lý dữ liệu vật tư (BOM), và các tập lệnh tự động hóa bằng AutoLISP / Python.

---

### Đóng Góp Mã Nguồn Mở

Đóng góp vào các dự án lõi CAD & hình học 3D quốc tế:

| Dự Án | Pull Request | Chi Tiết Đóng Góp | Công Nghệ | Trạng Thái |
|:---|:---:|:---|:---:|:---:|
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#2069](https://github.com/HakanSeven12/OpenCADStudio/pull/2069) | Sửa lỗi tính toán thụt lề MTEXT và khoảng cách tab theo đơn vị bản vẽ trong tệp AutoCAD DXF | `Rust` `CAD Engine` `DXF` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#1960](https://github.com/HakanSeven12/OpenCADStudio/pull/1960) | Tích hợp gói tài nguyên chuỗi ký tự Fluent bản địa hóa | `Rust` `Fluent i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#2915](https://github.com/tangency-labs/solidcraft/pull/2915) | Tích hợp gói bản địa hóa tiếng Việt (`vi`) cho phần mềm CAD tham số 3D thuần Rust | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |

---

### Kỹ Năng & Công Cụ

#### Lập trình & Môi trường phát triển
<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,cs,python,cpp,ts,bash,git,docker,linux,postgres&perline=10" />
</div>

<br/>

#### Kỹ thuật Kết cấu & CAD/BIM
| Lĩnh vực | Phần mềm & Framework | Năng lực kỹ thuật |
|:---|:---|:---|
| **Lõi CAD** | OpenCAD Studio, AutoCAD, FreeCAD | Tăng tốc đồ họa GPU bằng Rust (wgpu), AutoLISP, ObjectARX, xử lý tệp DXF/DWG |
| **BIM & Chi tiết** | Tekla Structures, Autodesk Revit, Blender | Bóc tách chi tiết kết cấu thép, Tekla Open API, tự động trích xuất bảng kê BOM |
| **Hệ thống & Backend** | .NET 10, FastAPI, SQLite, PostgreSQL | Engine tính toán hiệu năng cao, giao thức tự động hóa MCP, quản lý sản xuất |

---

### Hệ Thống & Phần Mềm Tự Phát Triển

Các engine và hệ thống kỹ thuật do chính tác giả thiết kế và phát triển độc lập:

| Hệ Thống / Phần Mềm | Công Nghệ | Mô Tả & Năng Lực Trọng Tâm | Vai Trò / Trạng Thái |
|:---|:---:|:---|:---:|
| **VNCAD Engine** | `.NET 10` `C#` `MCP` | Engine CAD 2D hiệu năng cao chuyên dụng thiết kế kết cấu theo TCVN/ISO và tự động hóa vẽ qua giao thức Model Context Protocol. | Kiến trúc sư trưởng / Đang phát triển |
| **HCNT Workshop Digital Twin** | `FastAPI` `Python` `Tekla` | Hệ thống quản lý sản xuất xưởng kết cấu thép thời gian thực, tiến độ Vector Gantt và đường ống dữ liệu phôi cắt CNC. | Tác giả / Vận hành thực tế |
| **VietStruct Desktop** | `AutoLISP` `.NET` `Python` | Bộ công cụ tự động hóa bản vẽ kết cấu, chi tiết liên kết thép tham số và kiểm tra tiêu chuẩn TCVN/AISC. | Tác giả / Vận hành thực tế |
| **Structural BOQ & Cost Engine** | `Python` `PyQt5` `SQLite` | Cơ sở dữ liệu định mức bóc tách khối lượng kết cấu thép/bê tông và hệ thống tự động phân tích đơn giá dự toán. | Tác giả / Vận hành thực tế |

---

### Kết Nối

<div align="center">

<a href="mailto:vandang890615@gmail.com">
  <img src="https://img.shields.io/badge/Email-vandang890615%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/vandang890615">
  <img src="https://img.shields.io/badge/GitHub-vandang890615-181717?style=flat-square&logo=github&logoColor=white" />
</a>

</div>
