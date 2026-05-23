---
title: "CubeDoc – Backend Instructions"
notion_url: "https://www.notion.so/55dbfee5f8fa46d4b47c3aa296df7067"
source_notion_page: "https://www.notion.so/2d4045eea61980aa806be93b5f9d788f"
---

**CubeDoc – Backend Instructions<br>**It has 3 main tasks:<br>Receive data from medical devices (via Kiosk/Tauri)<br>Manage medical logic and workflows<br>Send standard data to ClinicOS (FHIR/HL7)

(تصاویر داخل Notion هستند؛ در خروجی اولیه ممکن است لینک فایل محلی داشته باشند و بعداً بهتره جداگانه مدیریت شوند.)

Sample:Spirometer → GDT File → Rust → JSON → Backend API<br>1:1️⃣Backend Architecture:<br>\[Medical Devices\]<br>↓<br>\[Tauri / Rust Backend (Local)\]<br>↓<br>\[CubeDoc Backend APIs\]<br>↓<br>\[ClinicOS Core API\]<br>

(ادامهٔ متن از Notion در این نسخه همان‌طور که هست منتقل شد.)
