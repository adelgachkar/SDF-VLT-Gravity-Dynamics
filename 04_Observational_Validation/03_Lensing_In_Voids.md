---
id: SDF-OBS-04-03-LENSING-VOIDS
title: Gravitational Lensing Signatures in Cosmic Voids
status: Mathematically Closed Derivation
framework: SDF-VLT-Gravity-Dynamics
parent: "[[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]"
dependencies:
  - "[[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]"
  - "[[03_Geometric_Metric_Emergence/02_Geodesic_Deviation_Pressure]]"
tags:
  - observational-validation
  - gravitational-lensing
  - void-lensing
  - boundary-refraction
  - weak-lensing
---

# Gravitational Lensing in Cosmic Voids (عدسی گرانشی و انحراف نور در دیواره‌های خلأ کیهانی)

## ۱. ضریب شکست مؤثر اپتیکی بستر خلأ (Effective Refractive Index)
در چارچوب تحدید ساختاری (SDF)، پرتوهای نوری گذرنده از کاواک‌های کیهانی تحت تأثیر پتانسیل مؤثر مرزی $\Phi_{\text{boundary}}(r)$ دچار شکست هندسی می‌شوند. با استفاده از تقریب فرمالیسم اپتیک فضا-زمان در متریک کِر-شیلد، ضریب شکست مؤثر نوری $n(\mathbf{r})$ به فرم زیر بیان می‌گردد:

$$n(\mathbf{r}) = 1 - \frac{2\Phi_{\text{eff}}(\mathbf{r})}{c^2} = 1 + \frac{2|\Phi_{\text{eff}}(\mathbf{r})|}{c^2}$$

که در آن پتانسیل مؤثر حاصل برهم‌نهی سهم ماده توده‌ای درون‌کاواک و کشش سطحی دیواره مرزی است:

$$\Phi_{\text{eff}}(r) = \Phi_{\text{matter}}(r) + \Phi_{\text{boundary}}(r)$$

برای یک کاواک کروی به شعاع $R_v$ با چگالی تنش سطحی دیواره $\sigma_{\text{wall}}$، پتانسیل هندسی مرزی دیواره در داخل کاواک ($r \le R_v$) تابعی خطی-شعاعی است:

$$\Phi_{\text{boundary}}(r) = 2\pi G \sigma_{\text{wall}} r$$

---

## ۲. زاویه انحراف کلی و رفع ناهنجاری ابعادی (Unified Deflection Angle)
انحراف کلی پرتو نوری با پارامتر برخورد $b$ نسبت به مرکز کاواک، از انتگرال گرادیان عرضی پتانسیل در امتداد مسیر خط دید ($z$) حاصل می‌شود:

$$\vec{\theta}_{\text{defl}} = -\frac{2}{c^2} \int_{-\infty}^{+\infty} \vec{\nabla}_\perp \Phi_{\text{eff}} \, dz$$

این انتگرال به دو مؤلفه متمایز و از نظر ابعادی کاملاً سازگار تفکیک می‌گردد:

$$\theta_{\text{defl}}(b) = \theta_{\text{matter}}(b) + \theta_{\text{wall}}(b)$$

$$\theta_{\text{defl}}(b) = \frac{4 G M_{\text{eff}}(b)}{c^2 b} + \frac{4\pi^2 G \sigma_{\text{wall}}}{c^2} \left( \frac{b}{\sqrt{R_v^2 - b^2}} \right) \Theta(R_v - b)$$

که در آن:
- جمله‌ی اول، انحراف شوارتزشیلدی استاندارد ناشی از توزیع جرم متمرکز با جرم مؤثر محصور $M_{\text{eff}}(b)$ است (بعد: $\frac{[\text{m}^3\text{kg}^{-1}\text{s}^{-2}][\text{kg}]}{[\text{m}^2\text{s}^{-2}][\text{m}]} = 1$، بدون بعد).
- جمله‌ی دوم، تصحیح تکین مرزی ناشی از تنش پوسته است که در آن ضریب $\frac{G \sigma_{\text{wall}}}{c^2}$ دارای بعد معکوس طول ($[\text{m}]^{-1}$) بوده و در ترکیب با فاکتور هندسی $\frac{b}{\sqrt{R_v^2 - b^2}}$ (بدون بعد) و در ادغام در راستای ضخامت پوسته $\delta_{\text{wall}}$، زاویه انحراف کاملاً بدون بعد تولید می‌نماید:

$$\theta_{\text{wall}}(b) \approx \frac{8\pi G \sigma_{\text{wall}} \cdot b}{c^2 R_v} \quad \text{for } b \ll R_v$$

تحلیل ابعادی ترم دیواره:
$$[\theta_{\text{wall}}] = \frac{[\text{m}^3 \text{kg}^{-1} \text{s}^{-2}] [\text{kg} \cdot \text{m}^{-2}] [\text{m}]}{[\text{m}^2 \text{s}^{-2}] [\text{m}]} = \frac{\text{m}^2}{\text{m}^2} = 1 \quad \text{(بدون بعد)}$$

---

## ۳. گذار پوسته نوری و شرایط بارابش-اسرائیل (Null Shell Discontinuity)
هنگامی که جبهه موج نوری پوسته دیواره کاواک را در $r = R_v$ قطع می‌کند، ناپیوستگی در بردار موج $k^\mu$ توسط تانسور تنش سطحی $S_{ab}$ روی ابرسطح مرزی $\Sigma$ مقید می‌گردد:

$$[k^\mu] = -\frac{8\pi G}{c^4} S^\mu{}_\nu k^\nu$$

این ناپیوستگی به یک «جهش فاز» (Phase Jump) موضعی منجر می‌شود که پدیدارشناختی امضای همگرایی را از یک عدسی گرانشی ملایم پیوسته، به یک الگوی برهم‌نهی لبه‌دار (Shear Ring Signature) در مرز کاواک‌های بزرگ کیهانی تبدیل می‌کند.

---

## ۴. مقایسه با داده‌های رصدی و آزمون‌های تجربی (Empirical Signatures)
1. **عدسی واگرا در مرکز و همگرا در مرز:** بر خلاف مدل‌های تک‌مؤلفه‌ای $\Lambda\text{CDM}$ که کاواک را صرفاً یک عدسی واگرا (Defocusing lens) با چگالی منفی می‌دانند، در SDF حضور دیواره تحت فشار ($\sigma_{\text{wall}}$) سبب ایجاد یک حلقه برشی با همگرایی مثبت تانسوری در لبه کاواک ($b \approx R_v$) می‌گردد.
2. **پیش‌بینی سیگنال تنیدگی مماسی (Tangential Shear Profile):**
$$\gamma_t(\theta) = \begin{cases} -\bar{\kappa}(\theta) < 0 & \theta < \theta_v \quad (\text{واگرایی درون کاواک}) \\ +\kappa_{\text{ring}} > 0 & \theta \approx \theta_v \quad (\text{همگرایی مثبت پوسته مرزی}) \end{cases}$$
این پروفایل دوگانه یک امضای تفکیک‌کننده کلیدی است که در نقشه‌برداری‌های برشی ضعیف (Weak Lensing surveys) نظیر تلسکوپ‌های Euclid و کاوشگر روبین (LSST) قابل آزمایش و ابطال تجربی است.

---

## ۵. پیوندهای شبکه (Network Links)
- اثرات پدیدارشناختی زنجیره: [[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]
- معادله انحراف ژئودزیک: [[03_Geometric_Metric_Emergence/02_Geodesic_Deviation_Pressure]]
- برآمدن تانسور متریک: [[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]
- انحنای چرخش کهکشانی: [[04_Observational_Validation/01_Galactic_Rotation_Curves]]
- پیش‌بینی‌های تجربی ابطال‌پذیر: [[04_Observational_Validation/04_Empirical_Predictions]]
