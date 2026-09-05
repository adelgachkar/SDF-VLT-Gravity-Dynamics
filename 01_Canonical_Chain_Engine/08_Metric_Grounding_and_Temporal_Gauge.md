---
id: SDF-ENG-01-08-METRIC-GAUGE
title: Metric Grounding and Temporal Gauge
status: Mathematically Closed Derivation
framework: SDF-VLT-Gravity-Dynamics
parent: "[[01_Canonical_Chain_Engine/05_M_Manifold_Foliations]]"
dependencies:
  - "[[00_Root_Governance/NT_ECS_Noether_Conservation]]"
  - "[[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]"
tags:
  - canonical-engine
  - temporal-gauge
  - metric-grounding
  - adm-decomposition
  - lapse-function
---

# Metric Grounding and Temporal Gauge (زمینه‌سازی متریک و پیمانه زمانی)

## ۱. تثبیت پیمانه زمانی و تجزیه برگه‌بندی ADM (Temporal Gauge Fixing & 3+1 ADM Foliation)
در چارچوب تحدید ساختاری (SDF)، پارامتر زمان نه یک مؤلفه از پیش موجود، بلکه آهنگ پیشروی فاز تحدید در امتداد بردار نرمال یکه برگه‌های فضایی ($n^\mu$) است. فضا-زمان مؤثر از طریق تجزیه $3+1$ استاندارد ADM زمینه‌سازی می‌گردد:

$$ds^2 = -N^2 c^2 dt^2 + \gamma_{ij} (dx^i + \beta^i dt)(dx^j + \beta^j dt)$$

که در آن:
- $N(x, t)$ تابع لغزش زمانی (Lapse Function) است که نرخ گذر زمان ویژه محلی را نسبت به زمان هماهنگ برگه تعیین می‌کند ($d\tau = N dt$).
- $\beta^i(x, t)$ بردار شیفت مکانی (Shift Vector) است که لغزش نسبی خطوط مختصات را در طول برگه‌بندی توصیف می‌نماید.
- $\gamma_{ij}$ متریک ریمانی القایی ۳-بعدی روی برگه‌های هم‌فاز $\Sigma_t$ است.

در غیاب چرخش‌های القایی و برهم‌کنش‌های تکانه‌ای خالص ($\beta^i = 0$)، المان خط به فرم قطری استاندارد کاهش می‌یابد:

$$ds^2 = -N^2 c^2 dt^2 + \gamma_{ij} dx^i dx^j$$

---

## ۲. ریشه‌یابی فیزیکی تابع لغزش زمانی از پتانسیل تنش مرزی (Lapse Grounding)
ضریب پیمانه $N$ مستقیماً توسط گرادیان چگالی تنش مرزی و پتانسیل هندسی کاواک‌ها ($\Phi_{\text{boundary}}$) تعیین و مقید می‌شود:

$$N = \sqrt{1 - \frac{2\Phi_{\text{boundary}}(x)}{c^2}}$$

در حد میدان ضعیف ($\Phi_{\text{boundary}} \ll c^2$):

$$N \approx 1 - \frac{\Phi_{\text{boundary}}(x)}{c^2}$$

این ساختار نشان می‌دهد که اتساع گرانشی زمان، نتیجه مستقیم افت آهنگ انتقال فاز در مجاورت تمرکز تنش‌های سطحی دیواره کاواک‌هاست.

---

## ۳. گرادیان لغزش و شتاب ۴-برداری (Acceleration & Lapse Gradient)
شتاب ۴-برداری خطوط جریان یکنواخت عمود بر برگه‌ها ($a_\mu = n^\nu \nabla_\nu n_\mu$) مستقیماً از گرادیان لگاریتمی تابع لغزش به دست می‌آید:

$$a_i = \partial_i \ln N = \frac{1}{N} \partial_i N \approx -\frac{1}{c^2} \partial_i \Phi_{\text{boundary}}$$

این رابطه با شتاب مرزی برآمده از میدان نشت فاز در [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]] هم‌ارز است:

$$a_i = -\frac{1}{c^2} \nabla_i \Phi_{\text{boundary}} = \mathcal{Q}_{\text{leak}, i}$$

---

## ۴. شرایط سازگاری برگه‌ها و بقای پیمانه (Gauge Conservation)
برای تضمین حفظ ناوردایی پیمانه‌ای و بستار سینماتیکی زنجیره کانونی، شرط انحنای برونی برگه‌ها ($K_{ij}$) با آهنگ تغییرات زمانی متریک فضایی جفت می‌شود:

$$K_{ij} = -\frac{1}{2N} \left( \partial_t \gamma_{ij} - D_i \beta_j - D_j \beta_i \right)$$

که در پیمانه نرمال فازی ($\beta^i = 0$):

$$\partial_t \gamma_{ij} = -2N K_{ij}$$

این معادله تضمین می‌کند که فرگشت هندسه فضایی، پیوستگی کامل با شرایط اتصال اسرائیل (Israel Junction Conditions) در دیواره‌ها را حفظ می‌نماید.

## ۵. پیوندهای شبکه و زنجیره کانونی (Network Links)
- گره والد زنجیره: [[01_Canonical_Chain_Engine/05_M_Manifold_Foliations]]
- مبانی پایه‌ای متریک: [[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]
- میدان شتاب ناشی از فشار مرز:
  [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]
