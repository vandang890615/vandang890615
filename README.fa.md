<div align="center">

<!-- Custom Engineered Hero Banner -->
<img src="./assets/hero-banner.svg" alt="Structural & CAD Architecture" width="100%" />

<br/><br/>

<p align="center">
  <a href="README.md">English</a> &bull;
  <a href="README.vi.md">Tiếng Việt</a> &bull;
  <a href="README.ru.md">Русский</a> &bull;
  <a href="README.zh.md">中文</a> &bull;
  <b>فارسی</b>
</p>

</div>

---

<div dir="rtl">

### درباره من

**ون دانگ (Van Dang)** — مهندس سازه و توسعه‌دهنده هسته نرم‌افزارهای CAD/BIM.

تمرکز بر تحلیل سازه‌های فولادی سنگین صنعتی و توسعه زیرساخت‌های نرم‌افزاری مهندسی:
- **مهندسی سازه‌های فولادی:** طراحی و تهیه نقشه‌های شاپ‌دراوینگ سازه‌های صنعتی سنگین مطابق با استانداردهای AISC و Eurocode؛ مدلسازی پیشرفته در Tekla Structures، طراحی اتصالات و بهینه‌سازی برش قطعات برای ماشین‌آلات CNC کارخانه.
- **توسعه هسته CAD/BIM:** مشارکت در توسعه موتور گرافیکی و پردازش متون در نرم‌افزارهای متن‌باز CAD با زبان **Rust** ([OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio), [SolidCraft](https://github.com/tangency-labs/solidcraft))؛ ساخت موتور مستقل CAD بر پایه **.NET 10** ([VNCAD](https://github.com/vandang890615/vncad))؛ و اتوماسیون فرایندهای نقشه‌کشی با پروتکل **MCP**.
- **اتوماسیون و ابزارسازی:** توسعه سامانه‌های پایش تولید کارخانجات اسکلت فلزی، استخراج خودکار لیستوفر (BOM) و برنامه‌نویسی با زبان‌های Python و AutoLISP.

---

### مشارکت‌های متن‌باز (Open-Source Impact)

مشارکت در مخازن بین‌المللی هسته CAD و هندسه سه‌بعدی:

| مخزن (Repository) | پول ریکوئست (PR) | جزئیات مشارکت | استک فنی | وضعیت |
|:---|:---:|:---|:---:|:---:|
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#2069](https://github.com/HakanSeven12/OpenCADStudio/pull/2069) | رفع باگ محاسباتی تورفتگی پاراگراف‌ها و فاصله‌بندی تب‌ها در MTEXT برای فایل‌های اتوکد DXF | `Rust` `CAD Engine` `DXF` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**OpenCADStudio**](https://github.com/HakanSeven12/OpenCADStudio) | [#1960](https://github.com/HakanSeven12/OpenCADStudio/pull/1960) | یکپارچه‌سازی بسته منابع رشته‌های متنی با فریمورک Fluent | `Rust` `Fluent i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) | [#2915](https://github.com/tangency-labs/solidcraft/pull/2915) | افزودن پشتیبانی از بومی‌سازی زبان ویتنامی به موتور CAD پارامتریک سه‌بعدی تماماً مبتنی بر Rust | `Rust` `3D CAD` `i18n` | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=git&logoColor=white) |

---

### مهارت‌ها و ابزارها

#### زبان‌های برنامه‌نویسی و زیرساخت
<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,cs,python,cpp,ts,bash,git,docker,linux,postgres&perline=10" />
</div>

<br/>

#### مهندسی سازه، CAD و BIM
| حوزه | نرم‌افزارها و ابزارها | محورهای تخصصی |
|:---|:---|:---|
| **موتورهای CAD** | OpenCAD Studio, AutoCAD, FreeCAD | رندرینگ شتاب‌یافته گرافیکی با Rust (wgpu)، اتولیسپ (AutoLISP)، آبجکت‌ای‌آراکس (ObjectARX)، خط لوله DXF/DWG |
| **مدلسازی BIM** | Tekla Structures, Autodesk Revit, Blender | شاپ اسکلت فلزی، رابط Tekla Open API، لیستوفر و خروجی CNC |
| **بک‌اند و سیستم‌ها** | .NET 10, FastAPI, SQLite, PostgreSQL | موتورهای پردازش مهندسی سریع، سرورهای MCP، سامانه ردیابی تولید |

---

### سامانه‌ها و نرم‌افزارهای مهندسی اختصاصی

موتورهای محاسباتی و نرم‌افزارهای تولیدی توسعه داده شده توسط معمار اصلی:

| سامانه / نرم‌افزار | استک | شرح قابلیت‌ها و تمرکز فنی | نقش / وضعیت |
|:---|:---:|:---|:---:|
| **VNCAD Engine** | `.NET 10` `C#` `MCP` | موتور محاسباتی سبک و قدرتمند CAD منطبق با استانداردهای سازه و ترسیم خودکار نقشه با هوش مصنوعی MCP. | طراح و معمار اصلی / در حال توسعه |
| **HCNT Workshop Digital Twin** | `FastAPI` `Python` `Tekla` | سامانه دوقلوی دیجیتال برای خط تولید کارخانجات اسکلت فلزی، زمان‌بندی گانت وکتور و خط لوله داده CNC. | نویسنده / استقرار عملیاتی |
| **VietStruct Desktop** | `AutoLISP` `.NET` `Python` | ابزارهای اتوماسیون نقشه‌کشی سازه، شاپ اتصالات پارامتریک فولادی و انطباق با استانداردهای TCVN/AISC. | نویسنده / استقرار عملیاتی |
| **Structural BOQ & Cost Engine** | `Python` `PyQt5` `SQLite` | پایگاه داده متره و برآورد احجام سازه‌های فولادی و بتنی و سامانه آنالیز بهای واحد. | نویسنده / استقرار عملیاتی |

---

### ارتباط با من

<div align="center">

<a href="mailto:vandang890615@gmail.com">
  <img src="https://img.shields.io/badge/Email-vandang890615%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/vandang890615">
  <img src="https://img.shields.io/badge/GitHub-vandang890615-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

</div>
