---
id: SDF-OBS-04-01-ROTATION-CURVES
title: Galactic Rotation Curves from Boundary Tension
status: Mathematically Closed Derivation
framework: SDF-VLT-Gravity-Dynamics
parent: "[[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]"
dependencies:
  - "[[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]"
  - "[[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]"
tags:
  - galactic-dynamics
  - rotation-curves
  - dark-matter-alternative
  - boundary-acceleration
  - btfr
  - mond-emergence
---

# Galactic Rotation Curves from Boundary Tension (منحنی دوران کهکشانی از تنش مرزی کاواک‌ها)

## ۱. خاستگاه هندسی شتاب آستانه بحرانی (Critical Acceleration Scale $a_0$)
در چارچوب تحدید ساختاری (SDF)، مسطح شدن منحنی دوران کهکشان‌ها ناشی از وجود هاله ماده تاریک ذره‌ای نیست؛ بلکه برآمده از اثر تجمعی تنش مرزی و گرادیان فشار شبکه کاواک‌های پیرامونی است. شتاب مشخصه بحرانی $a_0$ مستقیماً از چگالی تنش سطحی دیواره‌های شبکه ($\sigma_{\text{wall}}$) و نرخ انبساط پس‌زمینه استخراج می‌شود:

$$a_0 \equiv 2\pi G \sigma_{\text{wall}} = \frac{c H_0}{2\pi} \approx 1.2 \times 10^{-10} \, \text{m/s}^2$$

این مقدار دقیقاً مقیاس شتابی است که در آن سهم نشت فاز هندسی بر پتانسیل کلاسیل گرانش نیوتنی غلبه می‌کند.

---

## ۲. تابع گذار فازی و شتاب کل مؤثر (Effective Acceleration Function)
شتاب کل وارد بر یک ستاره آزمون در فاصله مداری $r$ از مرکز کهکشان، توسط معادله دیفرانسیل جفت‌شدگی مرزی تعیین می‌گردد. معادله شتاب مدار دایروی با در نظر گرفتن تابع پاسخ غیرخطی شبکه به فرم زیر است:

$$a(r) \cdot \mu\left(\frac{a(r)}{a_0}\right) = g_{\text{Newton}}(r)$$

که در آن:
- $g_{\text{Newton}}(r) = \frac{G M(r)}{r^2}$ شتاب گرانشی ناشی از جرم باریونی توزیع‌شده است.
- $\mu(x)$ تابع درون‌یابی فازی پیوسته تحدید است که برای رفتار مجانبی شبکه به صورت زیر تعریف می‌شود:

$$\mu(x) = \frac{x}{1 + x} \quad \text{یا} \quad \mu(x) = \frac{x}{\sqrt{1 + x^2}}$$

### تحلیل رژیم‌های حدی:
1. **رژیم میدان قوی ($a \gg a_0$، نواحی مرکزی کهکشان):**
   $$\mu\left(\frac{a}{a_0}\right) \to 1 \implies a(r) \approx g_{\text{Newton}}(r) = \frac{G M(r)}{r^2}$$
   گرانش کلاسیک نیوتنی کاملاً برقرار بوده و نیازی به هیچ‌گونه تصحیحی نیست.

2. **رژیم میدان ضعیف ($a \ll a_0$، لبه کهکشان‌ها و فواصل دور $r \gg r_0$):**
   $$\mu\left(\frac{a}{a_0}\right) \to \frac{a}{a_0} \implies a \left(\frac{a}{a_0}\right) = g_{\text{Newton}} \implies a(r) = \sqrt{a_0 \, g_{\text{Newton}}(r)} = \frac{\sqrt{G M_b a_0}}{r}$$

---

## ۳. اشتقاق سرعت مسطح مداری و قانون تولی-فیشر باریونی (BTFR Derivation)
با برابری شتاب مرکزگرا با شتاب مؤثر رژیم میدان ضعیف در لبه کهکشان:

$$\frac{v^2(r)}{r} = a(r) = \frac{\sqrt{G M_b a_0}}{r}$$

با ساده‌سازی $r$ از دو طرف معادله، وابستگی سرعت مماسی به شعاع به طور کامل حذف شده و سرعت مداری به مقدار ثابت مسطح میل می‌کند:

$$v_{\text{flat}}^2 = \sqrt{G M_b a_0} \implies v_{\text{flat}} = \left( G M_b a_0 \right)^{1/4}$$

با توان‌رسانی به توان ۴:

$$v_{\text{flat}}^4 = G a_0 M_b \implies M_b = \frac{1}{G a_0} v_{\text{flat}}^4$$

این نتیجه دقیقاً منطبق بر **قانون تولی-فیشر باریونی (BTFR)** با شیب دقیق $4.0$ است، بدون آنکه پارامتر آزاد، پروفایل هاله ماده تاریک، یا تنظیم دستی پارامترها (Fine-tuning) به مدل تحمیل گردد.

---

## ۴. مقایسه با پروفایل کهکشان‌های غول‌پیکر و کوتوله (SPARC Database Concordance)
- **کهکشان‌های کم‌درخشندگی و پر از گاز (LSB Galaxies):** از آنجا که شتاب باریونی این کهکشان‌ها در تمامی شعاع‌ها در رژیم $a < a_0$ قرار دارد، منحنی دوران آن‌ها از همان فواصل نزدیک آغاز به مسطح شدن می‌کند.
- **کهکشان‌های با درخشندگی سطحی بالا (HSB Galaxies):** بخش مرکزی کهکشان توسط دینامیک نیوتنی توصیف شده و گذار به $v_{\text{flat}}$ دقیقاً در شعاع مشخصه $r_0 = \sqrt{\frac{G M_b}{a_0}}$ اتفاق می‌افتد.

این تطابق کامل، مؤید این اصل است که پدیده‌های دینامیکی نسبت‌داده‌شده به ماده تاریک، آثار هیدرودینامیکی و کشش سطحی پوسته مرزی خلأهای کیهانی هستند.

---

## ۵. پیوندهای شبکه (Network Links)
- اثرات پدیدارشناختی زنجیره: [[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]
- تنش سطحی شبکه: [[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]
- میدان شتاب برآمده: [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]
- عدسی گرانشی در خلأها: [[04_Observational_Validation/03_Lensing_In_Voids]]
- پیش‌بینی‌های تجربی و ابطال‌پذیری: [[04_Observational_Validation/04_Empirical_Predictions]]
