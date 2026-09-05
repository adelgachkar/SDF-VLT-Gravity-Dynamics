---
id: SDF-GOV-00-MATH
title: Mathematical Definitions, Operators and Physical Units
status: Release Grounded
framework: Structural Delineation Framework (SDF)
phase: SDF-VLT-Gravity-Dynamics
tags:
- governance
- definitions
- units
- mathematical-formalism
- canonical-operators
parent: []
dependencies: []
---

# Mathematical Definitions, Operators and Physical Units (تعاریف ریاضی، عملگرها و یکاهای فیزیکی)

## ۱. بیانیهٔ حاکمیتی و مرجعیت ساختاری (Formal Statement)
این سند مرجع رسمی و بنیادین تعاریف ریاضی، عملگرهای کانونی و یکاهای فیزیکی در مدل **دینامیک گرانش و شبکه خلأ ابرشاره (SDF-VLT-Gravity-Dynamics)** است. تمامی نودهای زیرمجموعه در لایه‌های هفت‌گانه زنجیره کانونی ($G \to \mathcal{C}_{\text{id}} \to S \to R \to M \to L \to F$) و مشتقات پدیدارشناختی ملزم به تطابق کامل با تعاریف، دیمانسیون‌ها و نمادگذاری‌های این سند هستند.

---

## ۲. جدول جامع عملگرهای زنجیره کانونی (Canonical Chain Operators)

| عملگر / لایه | نماد ریاضی | نگاشت ساختاری | تعریف فیزیکی / دامنه |
| :--- | :--- | :--- | :--- |
| **تولید بنیادین ($G$)** | $\hat{\mathcal{G}}$ | $\hat{\mathcal{G}}: \emptyset \longrightarrow \mathcal{H}_{\text{pre}}$ | عملگر مولد فازهای نامقید در بستر بنیاد-لا |
| **تحدید هویت ($\mathcal{C}_{\text{id}}$)** | $\hat{\mathcal{C}}_{\text{id}}$ | $\hat{\mathcal{C}}_{\text{id}}: \mathcal{H}_{\text{pre}} \longrightarrow \mathcal{S}_{\text{bounded}}$ | اعمال کران‌های موضعی، لنگرهای مرزی و فازهای ایزوله |
| **قید ساختاری ($S$)** | $\hat{\mathcal{S}}$ | $\hat{\mathcal{S}}: \mathcal{S}_{\text{bounded}} \longrightarrow \mathcal{C}_{\text{stable}}$ | اعمال قیدهای توپولوژیک و پایداری کینماتیکی سلول‌ها |
| **تنظیم تشدید ($R$)** | $\hat{\mathcal{R}}$ | $\hat{\mathcal{R}}: \mathcal{C}_{\text{stable}} \longrightarrow \Omega_{\text{res}}$ | هم‌راستاسازی فازهای فرکانسی و رزونانس دیواره‌های پوچ |
| **ورقه‌بندی منیفلد ($M$)** | $\hat{\mathcal{M}}$ | $\hat{\mathcal{M}}: \Omega_{\text{res}} \longrightarrow (\mathcal{M}_4, g_{\mu\nu})$ | ورقه‌بندی فضا-زمان $3+1$ و ظهور تانسور متریک پیوسته |
| **قوانین مؤثر ($L$)** | $\hat{\mathcal{L}}$ | $\hat{\mathcal{L}}: (\mathcal{M}_4, g_{\mu\nu}) \longrightarrow \mathcal{F}_{\text{field}}$ | استخراج معادلات حرکت، فریدمن اصلاح‌شده و اتصال پوسته |
| **نقش پدیدارشناختی ($F$)** | $\hat{\mathcal{F}}$ | $\hat{\mathcal{F}}: \mathcal{F}_{\text{field}} \longrightarrow \mathcal{O}_{\text{obs}}$ | نگاشت به کمیت‌های رصدی (منحنی دوران، لنزینگ، تنش هابل) |

---

## ۳. کمیت‌ها، تانسورها و نمادگذاری‌های استاندارد (Tensors and Symbols)

| کمیت / متغیر | نماد | یکا ($\text{SI}$) | دیمانسیون | شرح فیزیکی |
| :--- | :--- | :--- | :--- | :--- |
| **تنش سطحی دیواره** | $\sigma_{\text{wall}}$ | $\text{kg} \cdot \text{s}^{-2} \equiv \text{N}\cdot\text{m}^{-1}$ | $[M T^{-2}]$ | کشش سطحی و چگالی انرژی سطحی دیواره کاواک |
| **چگالی سطحی دیواره** | $\Sigma_{\text{wall}}$ | $\text{kg} \cdot \text{m}^{-2}$ | $[M L^{-2}]$ | چگالی جرمی سطحی پوسته مرزی ($\sigma_{\text{wall}}/c^2$) |
| **چگالی شبکه پس‌زمینه** | $\rho_{\text{lattice}}$ | $\text{kg} \cdot \text{m}^{-3}$ | $[M L^{-3}]$ | چگالی مؤثر جرم/انرژی محیط ابرشاره خلأ |
| **شتاب نشت فاز** | $\mathcal{Q}_{\text{leak}}^\mu$ | $\text{m} \cdot \text{s}^{-2}$ | $[L T^{-2}]$ | شتاب خالص هندسی ناشی از عدم تقارن مرزی |
| **تانسور تنش سطحی** | $S_{ab}$ | $\text{N} \cdot \text{m}^{-1}$ | $[M T^{-2}]$ | تانسور لنسره تنش-انرژی روی ابرسطح مرزی $\Sigma$ |
| **تانسور متریک القایی** | $q_{ab}$ | - | $1$ (بدون بعد) | متریک ریماینی القاشده روی دیواره مرزی |
| **انحنای برونی دیواره** | $K_{ab}$ | $\text{m}^{-1}$ | $[L^{-1}]$ | تانسور انحنای برونی و نرخ تغییرات نرمال دیواره |
| **گرادیان فشار کاواک** | $\Delta B$ | $\text{Pa} \equiv \text{J}\cdot\text{m}^{-3}$ | $[M L^{-1} T^{-2}]$ | اختلاف فشار هیدرودینامیکی درون و برون کاواک |
| **شتاب آستانه بحرانی** | $a_0$ | $\text{m} \cdot \text{s}^{-2}$ | $[L T^{-2}]$ | مقیاس شتاب گذار به رژیم تنش مرزی ($2\pi G \sigma_{\text{wall}}$) |

---

## ۴. سیستم یکاها و ثوابت بنیادین (System of Units)

کلیه محاسبات در دستگاه بین‌المللی یکاها ($\text{SI}$) همراه با بهنجارسازی فاز پلانک تعریف می‌شوند:

* **طول پلانک:** $\ell_P = \sqrt{\frac{\hbar G}{c^3}} \approx 1.616255 \times 10^{-35} \text{ m}$
* **زمان پلانک:** $t_P = \sqrt{\frac{\hbar G}{c^5}} \approx 5.391247 \times 10^{-44} \text{ s}$
* **جرم پلانک:** $m_P = \sqrt{\frac{\hbar c}{G}} \approx 2.176434 \times 10^{-8} \text{ kg}$
* **چگالی انرژی خلأ پس‌زمینه:**
  $$\rho_{\text{vac}} = \frac{\Lambda c^2}{8\pi G} \quad [\text{J}\cdot\text{m}^{-3}] \quad \left( \text{or } \rho_m^{\text{vac}} = \frac{\Lambda}{8\pi G} \quad [\text{kg}\cdot\text{m}^{-3}] \right)$$

---

## ۵. اتحاد بقای نویتر و سازگاری دیورژانس کل (Total Conservation Law)
بقای موضعی و توزیعی انرژی-تکانه در سرتاسر منیفلد $\mathcal{M}_4$ و روی ابرسطح ناپیوستگی مرزی $\Sigma$ به صورت زیر مقید است:

$$\nabla_\mu \left( T^{\mu\nu}_{(\text{matter})} + \mathcal{T}^{\mu\nu}_{(\text{lattice})} \right) + \delta(\Sigma) \mathcal{D}_a S^{ab} n_b^\nu = 0$$

که در آن $\mathcal{D}_a$ مشتق هموردای منطبق بر متریک القایی $q_{ab}$ و $n^\nu$ بردار یکه عمود بر دیواره مرزی است.

---

## ۶. پیوندهای حاکمیتی و اتصالات شبکه (Governance Anchors)
* اصل بنیادین ریشه: [[00_Root_Governance/SDF_CORE_AXIOM_01]]
* بقای نویتر و شرایط مرزی اسرائیل: [[00_Root_Governance/NT_ECS_Noether_Conservation]]
* زنجیره ثبت اکسیوم‌ها: [[00_Root_Governance/Axiom_2_3_Chain_Registration]]
* لنگرهای تحدید: [[01_Canonical_Chain_Engine/02_Cid_Delimitation_Anchors]]
* قوانین مؤثر حاکم: [[01_Canonical_Chain_Engine/06_L_Effective_Laws]]
