---
id: NT_ECS_Noether_Conservation
title: Variational Principle, Israel Junction Conditions
parent: '[[00_Root_Governance/00_Mathematical_Definitions_and_Units]]'
status: Mathematically Closed Derivation
dependencies: []
tags: []
---

# اصل تغییراتی و شرایط مرزی اتصال (Israel Junction Conditions)

## ۱. کنش جامع (Total Action)
در چارچوب مرزبندی ساختاری (SDF)، کنش جامع فضا-زمان شامل ترم‌های هیلبرت-اینشتین، میدان مرزی، ترم مرزی گیبونز-هاوکینگ-یورک (GHY) و ترم انرژی سطحی دیواره به صورت زیر تعریف می‌شود:

$$S = S_{\text{EH}} + S_{\Phi} + S_{\text{GHY}} + S_{\Sigma}$$

که در آن کنش سطحی دیواره مرزی $\Sigma$ به‌صورت زیر صراحتاً مشخص می‌گردد:

$$S_{\Sigma} = -\int_{\Sigma} d^3\xi \sqrt{-q} \, \sigma_{\text{wall}}(\Phi)$$

که در آن $q = \det(q_{ab})$ دترمینان متریک القایی $q_{ab}$ روی ابرسطح ۳-بعدی مرز $\Sigma$ است و $\sigma_{\text{wall}}(\Phi)$ نشان‌دهنده کشش سطحی دیواره ناشی از گرادیان میدان است.

---

## ۲. شرایط پیوستگی مرزی (Israel Junction Conditions)
با اعمال تغییرات کنش نسبت به متریک در حضور توزیع سطحی دیواره، پرش انحنای برونی $[K_{ab}] \equiv K_{ab}^+ - K_{ab}^-$ با تانسور تنش سطحی $S_{ab}$ موازنه می‌شود:

$$[K_{ab}] - q_{ab}[K] = -8\pi G \, S_{ab}$$

با فرض ایزوتروپی سطحی برای دیواره ($S_{ab} = -\sigma_{\text{wall}} q_{ab}$):

$$[K_{ab}] - q_{ab}[K] = 8\pi G \, \sigma_{\text{wall}} \, q_{ab}$$

با گرفتن اثر تانسوری (Trace) روی رابطه فوق با ضرب در $q^{ab}$ (با توجه به اینکه در ۳ بعد فضازمانی روی مرز $q^{ab}q_{ab} = 3$ است):

$$[K] - 3[K] = 8\pi G \, \sigma_{\text{wall}} (3) \implies -2[K] = 24\pi G \, \sigma_{\text{wall}}$$

بنابراین، پرش تریس انحنای خارجی به صورت دقیق به دست می‌آید:

$$[K] = -12\pi G \, \sigma_{\text{wall}}$$

این رابطه (شرط اتصال اصلاح‌شده اسرائیل) **بستار هندسی** و ناوردایی علامت را بین دو ناحیه متفاوت فضازمان (VOID و Lattice Wall) تضمین می‌کند.

### الحاقیه تعمیم‌یافته بارابِس-اسرائیل (Barrabès–Israel Null Limit)
در گذار به مرزهای نوری پوچ ($ds^2 = 0$) با بردار انتقال $\ell^\mu$ ($\ell_\mu \ell^\mu = 0$ و $\ell^a q_{ab} = 0$):

$$[\mathcal{K}_{ab}] = -8\pi G \, \sigma_{\text{wall}} \, \ell_a \ell_b$$

که به علت ماهیت لورنتسی بعد زمان و جهت‌گیری پیمانه زمانی، تغییر علامت فاز در هندسه موج هم‌راستا شده و پیوستگی پایستگی دیفرنسیالی تضمین می‌گردد.

---

## ۳. اثبات پایستگی توزیعی (Distributional Conservation)
تانسور انرژی-تکانه کل شامل مؤلفه‌های bulk و اثرات توزیعی سطحی است:

$$T_{\text{total}}^{\mu\nu} = T_{(\Phi)}^{\mu\nu} \Theta(\mathcal{M}) + S^{ab} e^\mu_a e^\nu_b \, \delta(\Sigma)$$

با استفاده از هویت بیانکی و شرط تقارن $\nabla_a S^{ab} = 0$:

$$\nabla_\mu T_{\text{total}}^{\mu\nu} = 0 \iff [T_{\mu\nu}^{(\Phi)} n^\mu n^\nu] + S^{ab} \bar{K}_{ab} = 0$$

که در آن $n^\mu$ بردار نرمال واحد بر ابرسطح $\Sigma$ و $\bar{K}_{ab} = \frac{1}{2}(K_{ab}^+ + K_{ab}^-)$ میانگین انحنای خارجی دو طرف مرز است. این هویت تضمین می‌کند که «تنش دیواره‌ها» نه یک فرض بیرونی، بلکه نتیجه‌ی لزوم پایستگی دیورژانس انرژی-تکانه در یک ساختار غیر-تخت است.
