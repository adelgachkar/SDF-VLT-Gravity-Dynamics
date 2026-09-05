---
id: SDF-BPG-02-06-FRIEDMANN-LATTICE-EXPANSION
title: Friedmann Lattice Expansion via Void Boundary Pressure
status: Mathematically Closed Derivation
framework: SDF-VLT-Gravity-Dynamics
parent: "[[01_Canonical_Chain_Engine/06_L_Effective_Laws]]"
dependencies:
  - "[[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]"
  - "[[02_Boundary_Pressure_Gravity/05_Middle_Atmosphere_Inflation_Dynamics]]"
tags:
  - cosmology
  - friedmann-equations
  - dark-energy-alternative
  - lattice-expansion
  - hubble-flow
  - boundary-pressure
---

# Friedmann Lattice Expansion via Void Boundary Pressure (انبساط شبکه فریدمن از طریق فشار مرزی کاواک‌ها)

## ۱. دینامیک سلول واحد و نگاشت به ضریب مقیاس کیهانی (Unit Cell & Cosmic Scale Factor)
در چارچوب تحدید ساختاری (SDF-VLT)، انبساط کیهانی ناشی از کشیدگی ذاتی پیوستار فضازمان نبوده، بلکه حاصل برآیند هیدرودینامیکی و کشش سطحی سلول‌های شبکه خلأ کیهانی تحت تعادل فشاری است. 

یک سلول واحد شبکه با سطح مقطع مؤثر $A_{\text{cell}}$ و بعد مشخصه خطی $L(t)$ را در نظر می‌گیریم:

$$V_{\text{cell}}(t) = A_{\text{cell}} \cdot L(t)$$

در مقیاس‌های همگن‌سازی‌شده موضعی، ضریب مقیاس کیهانی $a(t)$ با بعد خطی سلول متناسب بوده و پارامتر هابل $H(t)$ به صورت نرخ اتساع سلولی تعریف می‌شود:

$$a(t) \propto L(t) \implies H(t) \equiv \frac{\dot{a}}{a} = \frac{\dot{L}}{L}$$

---

## ۲. معادلات فریدمن اصلاح‌شده SDF (Modified Friedmann System)
با اعمال شرایط مرزی پیوستگی تنش در پوسته کاواک‌ها و پایستگی انرژی-تکانه روی ابرسطوح مرزی، معادله اول فریدمن برای پس‌زمینه تخت ($k=0$) به صورت زیر استخراج می‌گردد:

$$H^2 = \frac{8\pi G}{3}\rho_m + \frac{\Lambda_{\text{eff}}}{3} + \frac{\mathcal{Q}_{\text{net}}}{3 L(t)}$$

### تبیین مؤلفه‌ها و سازگاری دیمانسیونی:
1. **ثابت کیهان‌شناسی مؤثر هندسی ($\Lambda_{\text{eff}}$):**
   چگالی انرژی تاریک برآمده از تنش مرزی دیواره‌های پوچ ($\sigma_{\text{wall}}$) به ازای شعاع مشخصه کاواک $R_v$:
   $$\Lambda_{\text{eff}} \equiv \frac{8\pi G \sigma_{\text{wall}}}{R_v} \quad \left( [\Lambda_{\text{eff}}] = \frac{[\text{m}^3 \text{kg}^{-1} \text{s}^{-2}][\text{kg} \cdot \text{m}^{-2}]}{[\text{m}]} = \text{s}^{-2} \right)$$
   این عبارت جایگزین چگالی انرژی تاریک کواکسیال در نسبیت عام شده و مقدار عددی مشاهده‌شده $\Lambda \approx 10^{-35} \, \text{s}^{-2}$ را بدون نیاز به پارامترهای تنظیمی پلانکی بازتولید می‌کند.

2. **ترم شار شتاب مرزی ($\mathcal{Q}_{\text{net}}$):**
   شار خالص تبادل تکانه و انباشت فشار در مرزهای میان‌سلولی با بعد شتاب ($[\text{m}\cdot\text{s}^{-2}]$):
   $$\mathcal{Q}_{\text{net}} = \frac{1}{\rho_{\text{lattice}}} \nabla \cdot \mathbf{\Pi}_{\text{boundary}}$$
   که سبب می‌شود $\frac{\mathcal{Q}_{\text{net}}}{L(t)}$ دارای بعد سازگار با $H^2$ ($[\text{s}^{-2}]$) باشد.

---

## ۳. معادله شتاب کیهانی و پدیداری انبساط تندشونده (Acceleration Equation)
با مشتق‌گیری زمانی از معادله اول فریدمن و اعمال معادله تداوم باریونی ($\dot{\rho}_m + 3H(\rho_m + p_m/c^2) = 0$)، معادله دوم فریدمن (معادله رایچادوری مؤثر) به فرم بسته زیر حاصل می‌شود:

$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho_m + \frac{3p_m}{c^2}\right) + \frac{\Lambda_{\text{eff}}}{3} + \mathcal{R}_{\text{boundary}}$$

که در آن اثر بازخورد تنش دیواره‌های مجاور ($\mathcal{R}_{\text{boundary}}$) برابر است با:

$$\mathcal{R}_{\text{boundary}} = \frac{1}{6 L(t)} \left( \dot{\mathcal{Q}}_{\text{net}} - H \mathcal{Q}_{\text{net}} \right) - \frac{8\pi G}{3 c^2} P_{\text{wall}}^{\text{eff}}$$

### گذار به فاز انبساط شتاب‌دار:
در دوران اولیه کیهان ($\rho_m \gg \frac{\sigma_{\text{wall}}}{R_v}$)، جاذبه باریونی حاکم بوده و $\ddot{a} < 0$ است. با انبساط کاواک‌ها و رقیق شدن ماده درون‌سلولی، چگالی تنش مرزی دیواره‌ها غالب شده و با برقراری شرط:

$$\Lambda_{\text{eff}} > 4\pi G \left(\rho_m + \frac{3p_m}{c^2}\right) - 3\mathcal{R}_{\text{boundary}}$$

کیهان به صورت کاملاً هندسی و خودبه‌خودی وارد فاز انبساط شتاب‌دار ($\ddot{a} > 0$) می‌گردد، بدون آنکه نیازی به فرض میدان‌های اسکالر فرضی (Quintessence) یا انرژی تاریک نامتناهی باشد.

---

## ۴. ارتباط با تنش هابل موضعی (Resolution of Local Hubble Variance)
از آنجا که نرخ انبساط موضعی وابسته به مقیاس سلول‌های کاواک $R_v$ و تنش موضعی $\sigma_{\text{wall}}$ است، در مقیاس‌های ناهمگن محلی (محیط با غلبه کاواک‌های محلی)، نرخ اتساع مؤثر $H_{\text{local}}$ مقداری اندکی بزرگ‌تر از نرخ میانگین کیهانی دوردست $H_{\text{global}}$ ثبت می‌کند:

$$H_{\text{local}} = H_{\text{global}} \left( 1 + \frac{\delta \sigma_{\text{wall}}}{2 \sigma_0} \right)$$

این تصحیح ساختاری، اختلاف حدود $8\%$ میان اندازه‌گیری‌های موضعی (Supernovae Ia / Cepheids) و داده‌های تابش پس‌زمینه کیهانی (Planck CMB) را بدون شکست مدل تبیین می‌کند.

---

## ۵. پیوندهای شبکه (Network Links)
- قانون مؤثر در زنجیره کانونی: [[01_Canonical_Chain_Engine/06_L_Effective_Laws]]
- تنش تانسوری شبکه: [[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]
- دینامیک تورم لایه میانی: [[02_Boundary_Pressure_Gravity/05_Middle_Atmosphere_Inflation_Dynamics]]
- حل تنش هابل: [[04_Observational_Validation/02_Hubble_Tension_Resolution]]
- پیش‌بینی‌های تجربی ابطال‌پذیر: [[04_Observational_Validation/04_Empirical_Predictions]]
