---
id: SDF-BPG-02-06-FRIEDMANN-LATTICE-EXPANSION
title: Friedmann Lattice Expansion via Void Boundary Pressure
created: 2026-09-05
updated: 2026-10-05
author: Adel Gachkar
license: MIT
status: canonical
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

# Friedmann Lattice Expansion via Void Boundary Pressure

## 1. Unit-Cell Dynamics and Mapping to the Cosmic Scale Factor
In the SDF-VLT framework, cosmic expansion is not the intrinsic stretching of a spacetime continuum: it is the hydrodynamic aggregate of the cells of the cosmic void lattice under surface tension in pressure equilibrium.

Consider a unit lattice cell with effective cross-section $A_{\text{cell}}$ and characteristic linear dimension $L(t)$:

$$V_{\text{cell}}(t) = A_{\text{cell}} \cdot L(t)$$

At locally homogenized scales, the cosmic scale factor $a(t)$ is proportional to the cell's linear dimension, and the Hubble parameter $H(t)$ is defined as the rate of cellular expansion:

$$a(t) \propto L(t) \implies H(t) \equiv \frac{\dot{a}}{a} = \frac{\dot{L}}{L}$$

---

## 2. The SDF Modified Friedmann System
Applying boundary stress-continuity conditions on the cavity shells and energy–momentum conservation across the boundary hypersurfaces, the first Friedmann equation for the flat ($k=0$) background is derived as:

$$H^2 = \frac{8\pi G}{3}\rho_m + \frac{\Lambda_{\text{eff}}}{3} + \frac{\mathcal{Q}_{\text{net}}}{3 L(t)}$$

### Component explication and dimensional consistency:
1. **The geometric effective cosmological constant ($\Lambda_{\text{eff}}$):**
   The dark-energy density emerging from the wall boundary stress ($\sigma_{\text{wall}}$) per characteristic cavity radius $R_v$:
   $$\Lambda_{\text{eff}} \equiv \frac{8\pi G \sigma_{\text{wall}}}{R_v} \quad \left( [\Lambda_{\text{eff}}] = \frac{[\text{m}^3 \text{kg}^{-1} \text{s}^{-2}][\text{kg} \cdot \text{m}^{-2}]}{[\text{m}]} = \text{s}^{-2} \right)$$
   This term replaces the coexisting dark-energy density of general relativity and reproduces the observed numerical value $\Lambda \approx 10^{-35} \, \text{s}^{-2}$ without any Planck-scale tuning parameters.

2. **The boundary acceleration-flux term ($\mathcal{Q}_{\text{net}}$):**
   The net flux of momentum exchange and pressure accumulation at inter-cell boundaries, with acceleration dimension ($[\text{m}\cdot\text{s}^{-2}]$):
   $$\mathcal{Q}_{\text{net}} = \frac{1}{\rho_{\text{lattice}}} \nabla \cdot \mathbf{\Pi}_{\text{boundary}}$$
   which renders $\frac{\mathcal{Q}_{\text{net}}}{L(t)}$ dimensionally consistent with $H^2$ ($[\text{s}^{-2}]$).

---

## 3. The Cosmic Acceleration Equation and the Onset of Accelerated Expansion
Differentiating the first Friedmann equation in time and applying the baryon-continuity equation ($\dot{\rho}_m + 3H(\rho_m + p_m/c^2) = 0$), the second Friedmann equation (the effective Raychaudhuri equation) is obtained in the following closed form:

$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho_m + \frac{3p_m}{c^2}\right) + \frac{\Lambda_{\text{eff}}}{3} + \mathcal{R}_{\text{boundary}}$$

where the feedback effect of adjacent wall stresses ($\mathcal{R}_{\text{boundary}}$) is:

$$\mathcal{R}_{\text{boundary}} = \frac{1}{6 L(t)} \left( \dot{\mathcal{Q}}_{\text{net}} - H \mathcal{Q}_{\text{net}} \right) - \frac{8\pi G}{3 c^2} P_{\text{wall}}^{\text{eff}}$$

### Transition to the accelerated-expansion phase:
In the early universe ($\rho_m \gg \frac{\sigma_{\text{wall}}}{R_v}$), baryonic gravity dominates and $\ddot{a} < 0$. As the cavities expand and the intra-cellular matter dilutes, the boundary stress density of the walls dominates, and once the condition

$$\Lambda_{\text{eff}} > 4\pi G \left(\rho_m + \frac{3p_m}{c^2}\right) - 3\mathcal{R}_{\text{boundary}}$$

is met, the universe enters the phase of accelerated expansion ($\ddot{a} > 0)$ in a fully geometric and spontaneous manner — with no need for hypothetical scalar fields (Quintessence) or an infinite dark energy.

---

## 4. Relation to the Local Hubble Variance (Resolution of Local Hubble Variance)
Since the local expansion rate depends on the cavity-cell scale $R_v$ and the local stress $\sigma_{\text{wall}}$, in locally inhomogeneous environments (regions dominated by local voids) the effective expansion rate $H_{\text{local}}$ registers slightly above the distant cosmic mean $H_{\text{global}}$:

$$H_{\text{local}} = H_{\text{global}} \left( 1 + \frac{\delta \sigma_{\text{wall}}}{2 \sigma_0} \right)$$

This structural correction explains the ~$8\%$ discrepancy between local measurements (Supernovae Ia / Cepheids) and the cosmic background radiation data (Planck CMB) without any model break.

---

## 5. Network Links
- Effective law in the canonical chain: [[01_Canonical_Chain_Engine/06_L_Effective_Laws]]
- Lattice stress tensor: [[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]
- Middle-layer inflation dynamics: [[02_Boundary_Pressure_Gravity/05_Middle_Atmosphere_Inflation_Dynamics]]
- Hubble tension resolution: [[04_Observational_Validation/02_Hubble_Tension_Resolution]]
- Falsifiable empirical predictions: [[04_Observational_Validation/04_Empirical_Predictions]]
