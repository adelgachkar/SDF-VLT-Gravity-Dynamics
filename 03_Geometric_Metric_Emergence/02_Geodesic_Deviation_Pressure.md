---
title: Geodesic Deviation Under Boundary Pressure
created: 2026-09-05
framework: Structural Delineation Framework (SDF)
phase: SDF-VLT-Gravity-Dynamics
tags:
- geodesic-deviation
- riemann-curvature
- pressure-gradient
- weak-equivalence-principle
- kerr-schild
id: SDF-VLT--03_Geometric_Metric_Emergence-02_Geodesic_Deviation_Pressure
status: Draft
parent: []
dependencies: []
---

# Geodesic Deviation Under Boundary Pressure (انحراف ژئودزیک تحت فشار مرز)

## ۱. معادله انحراف ژئودزیک تعمیم‌یافته و حفظ اصل هم‌ارزی (WEP)
حضور گرادیان فشار مرزی، معادله انحراف ژئودزیک میان دو مسیر مجاور با بردار انحراف $\xi^\mu$ را به فرمی تصحیح می‌کند که استقلال کامل از جرم ذره آزمون تضمین شود و اصل هم‌ارزی ضعیف (WEP) کاملاً پایدار بماند:

$$\frac{D^2 \xi^\mu}{d\tau^2} + R^\mu{}_{\nu\alpha\beta} u^\nu u^\alpha \xi^\beta = \frac{1}{\rho_{\text{lattice}}} \nabla_\xi \left( \nabla_\nu T^{\text{boundary}\,\mu\nu} \right)$$

که در آن:
- $u^\mu = dx^\mu/d\tau$ ۴-سرعت نرمال‌شده ذره آزمون است ($u_\mu u^\mu = -c^2$).
- $\rho_{\text{lattice}}$ چگالی لختی مؤثر بستر شبکه است و جایگزین جرم دلخواه ذره آزمون شده تا ماهیت شتاب، صرفاً هندسی باقی بماند.
- $\nabla_\xi \equiv \xi^\alpha \nabla_\alpha$ مشتق هم‌وردا در امتداد بردار جدایی ژئودزیک است.

---

## ۲. همگرایی مسیرهای نوری و حد صفر-فاصله (Null Rays Limit)
برای پرتوهای نوری و فوتون‌های عبوری از مجاورت مرز کاواک‌ها، با استفاده از پارامتری‌سازی آفین $\lambda$ و بردار موج نوری $k^\mu = dx^\mu/d\lambda$ ($k_\mu k^\mu = 0$):

$$\frac{D^2 \xi^\mu}{d\lambda^2} + R^\mu{}_{\nu\alpha\beta} k^\nu k^\alpha \xi^\beta = \nabla_\xi \left( \mathcal{Q}_{\text{leak}}^\mu \right)$$

که در آن $\mathcal{Q}_{\text{leak}}^\mu$ میدان شتاب خالص هندسی برآمده از گرادیان نشت فاز در ابرسطح مرزی است:

$$\mathcal{Q}_{\text{leak}}^\mu \equiv -\frac{8\pi G}{c^4} \left( \nabla_\nu S^{\mu\nu}_{\text{eff}} \right) = \frac{1}{c^2} \nabla^\mu \Phi_{\text{boundary}}$$

این فرم هندسی نشان می‌دهد که انحراف فوتون‌ها نه ناشی از برهم‌کنش ماده با ماده، بلکه ناشی از گذار از گرادیان انحنای القایی پوسته کاواک است.

---

## ۳. ساختار تک‌تانسوری کِر-شیلد (Kerr–Schild Mono-Tensor Reduction)
به منظور پرهیز از دوگانگی ناهماهنگ در فضا-زمان پس‌زمینه و اختلالات، متریک برآمده در حضور نشت فاز تشعشعی مرزی به فرم تک‌تانسوری کِر-شیلد بیان می‌شود:

$$g_{\mu\nu} = \eta_{\mu\nu} + \frac{2\Phi_{\text{boundary}}}{c^2} k_\mu k_\nu, \qquad k_\mu k^\mu = 0$$

تحت این بازنمایی، تانسور انحنای ریمان $R^\mu{}_{\nu\alpha\beta}$ به‌طور طبیعی با شرط نوری هم‌بعدی ($dt = dx/c$) جفت شده و معادلات انحراف بدون نیاز به فرضیات ماده تاریک، پدیده‌های همگرایی را بازتولید می‌کنند.

---

## ۴. پاسخ میدان تیدال و شتاب جزرومدی
نیروی کششی جزرومدی مؤثر وارد بر بردار انحراف $\xi^\mu$ تحت تأثیر هم‌زمان انحنای پس‌زمینه و گرادیان فشار مرزی به فرم تانسوری زیر خلاصه می‌شود:

$$\mathcal{E}^\mu{}_\beta \equiv -R^\mu{}_{\nu\alpha\beta} u^\nu u^\alpha + \nabla_\beta \mathcal{Q}_{\text{leak}}^\mu$$

$$\frac{D^2 \xi^\mu}{d\tau^2} = \mathcal{E}^\mu{}_\beta \, \xi^\beta$$

این تقارن ساختاری تضمین می‌کند که انحراف ژئودزیک‌ها در مرز کاواک‌ها به‌طور خودکار شرایط بقای دیورژانس انرژی-تکانه را برآورده سازد.

---

## پیوندهای شبکه
- متریک مؤثر: [[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]
- زمینه‌سازی متریک و پیمانه زمانی: [[01_Canonical_Chain_Engine/08_Metric_Grounding_and_Temporal_Gauge]]
- اصل تغییراتی و شرایط مرزی اسرائیل: [[00_Root_Governance/NT_ECS_Noether_Conservation]]
- عدسی در خلأ: [[04_Observational_Validation/03_Lensing_In_Voids]]
