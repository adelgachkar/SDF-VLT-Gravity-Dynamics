---
id: SDF-REL-CHANGELOG-v1.0.0
title: Release Changelog v1.0.0 - Gravity Dynamics Vault
created: 2026-09-05
status: Release Approved
framework: Structural Delineation Framework (SDF)
phase: SDF-VLT-Gravity-Dynamics
tags:
- changelog
- release
- provenance
- governance
parent: []
dependencies: []
---

# Release Changelog v1.0.0

## نگارش v1.0.0 — تثبیت فاز P0/P1 و دینامیک فشار مرزی (Gravity Dynamics Core)

### ۱. تغییرات عمده و ساختاری (Major Structural Updates)
* **تثبیت زنجیره کانونی:** استقرار و استانداردسازی ۸ گره موتور زنجیره (`01_G` تا `08_Metric`) با حذف پسوندهای مضاعف و تثبیت متادیتای صوری.
* **حل ناپیوستگی‌های توپولوژیک گراف:** تفکیک و رفع تداخل نودهای هم‌نام در ماژول‌های فشار مرزی و اعتبارسنجی رصدی.
* **افزودن گره تعاریف ریاضی:** استقرار سند حاکمیتی `00_Mathematical_Definitions_and_Units` جهت تثبیت عملگرها و دستگاه یکاها.

### ۲. اصلاحات و رفع تداخل‌ها (Fixes & Harmonization)
* اصلاح پیوند میان اصل پایستگی نویتر [[00_Root_Governance/NT_ECS_Noether_Conservation]] و تانسور تنش شبکه.
* تثبیت مرجع اعتبارسنجی رصدی در مسیر صلب [[04_Observational_Validation/02_Hubble_Tension_Resolution]].
* بازسازی پیوندهای Wikilink به فرمت استاندارد دوطرفه بدون شکستگی (Zero Broken Links).

---

## مراجع رهاسازی و استناد (Release Anchors)
* **مانیفست رهاسازی دینامیک گرانش:** [[05_Registration_Artifacts/03_Gravity_Dynamics_Release_Manifest]]
* **اصل پایستگی بنیادین (Noether):** [[00_Root_Governance/NT_ECS_Noether_Conservation]]
* **اصل ریشه ساختاری:** [[00_Root_Governance/SDF_CORE_AXIOM_01]]
