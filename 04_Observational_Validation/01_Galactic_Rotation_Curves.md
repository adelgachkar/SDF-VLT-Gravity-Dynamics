---
id: SDF-OBS-04-01-ROTATION-CURVES
title: Galactic Rotation Curves from Boundary Tension
created: 2026-09-05
updated: 2026-10-05
author: Adel Gachkar
license: MIT
status: canonical
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

# Galactic Rotation Curves from Boundary Tension

## 1. Geometric Origin of the Critical Acceleration Scale $a_0$
In the SDF framework, the flattening of galactic rotation curves does not stem from a halo of particle dark matter: it emerges from the cumulative effect of boundary stress and the pressure gradient of the lattice of surrounding cavities. The critical characteristic acceleration $a_0$ is extracted directly from the surface-stress density of the lattice walls ($\sigma_{\text{wall}}$) and the background expansion rate:

$$a_0 \equiv 2\pi G \sigma_{\text{wall}} = \frac{c H_0}{2\pi} \approx 1.2 \times 10^{-10} \, \text{m/s}^2$$

This is precisely the acceleration scale at which the geometric phase-leak contribution overtakes the Newtonian classical gravitational potential.

---

## 2. The Phase-Transition Function and the Total Effective Acceleration
The total acceleration acting on a test star at orbital radius $r$ from the galactic center is determined by the boundary-coupling differential equation. The circular-orbit acceleration equation, including the nonlinear response function of the lattice, takes the form:

$$a(r) \cdot \mu\left(\frac{a(r)}{a_0}\right) = g_{\text{Newton}}(r)$$

where:
- $g_{\text{Newton}}(r) = \frac{G M(r)}{r^2}$ is the gravitational acceleration from the distributed baryonic mass.
- $\mu(x)$ is the continuous delimitation phase-interpolation function, defined for the lattice's asymptotic behavior as:

$$\mu(x) = \frac{x}{1 + x} \quad \text{or} \quad \mu(x) = \frac{x}{\sqrt{1 + x^2}}$$

### Analysis of the limiting regimes:
1. **Strong-field regime ($a \gg a_0$, galactic central regions):**
   $$\mu\left(\frac{a}{a_0}\right) \to 1 \implies a(r) \approx g_{\text{Newton}}(r) = \frac{G M(r)}{r^2}$$
   Classical Newtonian gravity holds fully, with no correction required.

2. **Weak-field regime ($a \ll a_0$, galaxy edges and large distances $r \gg r_0$):**
   $$\mu\left(\frac{a}{a_0}\right) \to \frac{a}{a_0} \implies a \left(\frac{a}{a_0}\right) = g_{\text{Newton}} \implies a(r) = \sqrt{a_0 \, g_{\text{Newton}}(r)} = \frac{\sqrt{G M_b a_0}}{r}$$

---

## 3. Derivation of the Flat Orbital Velocity and the Baryonic Tully–Fisher Relation (BTFR)
Equating the centripetal acceleration with the effective weak-field acceleration at the galactic edge:

$$\frac{v^2(r)}{r} = a(r) = \frac{\sqrt{G M_b a_0}}{r}$$

Simplifying by $r$ on both sides, the dependence of the tangential velocity on the radius cancels completely and the orbital velocity tends to a constant flat value:

$$v_{\text{flat}}^2 = \sqrt{G M_b a_0} \implies v_{\text{flat}} = \left( G M_b a_0 \right)^{1/4}$$

Raising both sides to the fourth power:

$$v_{\text{flat}}^4 = G a_0 M_b \implies M_b = \frac{1}{G a_0} v_{\text{flat}}^4$$

This result matches the **Baryonic Tully–Fisher Relation (BTFR)** with the exact slope $4.0$, with no free parameter, no dark-matter halo profile, and no fine-tuning imposed on the model.

---

## 4. Comparison Across Giant and Dwarf Galaxy Profiles (SPARC Database Concordance)
- **Low-surface-brightness, gas-rich galaxies (LSB):** since the baryonic acceleration of these galaxies lies in the regime $a < a_0$ at all radii, their rotation curves begin flattening from very small radii.
- **High-surface-brightness galaxies (HSB):** the central region is governed by Newtonian dynamics, and the transition to $v_{\text{flat}}$ occurs exactly at the characteristic radius $r_0 = \sqrt{\frac{G M_b}{a_0}}$.

This full concordance confirms the principle that the dynamical phenomena attributed to dark matter are the hydrodynamic and surface-tension effects of the shells of cosmic voids.

---

## 5. Network Links
- Chain phenomenological effects: [[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]
- Lattice surface stress: [[02_Boundary_Pressure_Gravity/02_Lattice_Stress_Tensor]]
- Emergent acceleration field: [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]
- Gravitational lensing in voids: [[04_Observational_Validation/03_Lensing_In_Voids]]
- Empirical predictions and falsifiability: [[04_Observational_Validation/04_Empirical_Predictions]]
