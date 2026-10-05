---
id: SDF-OBS-04-03-LENSING-VOIDS
title: Gravitational Lensing Signatures in Cosmic Voids
created: 2026-09-05
updated: 2026-10-05
author: Adel Gachkar
license: MIT
status: canonical
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

# Gravitational Lensing in Cosmic Voids

## 1. The Effective Optical Refractive Index of the Void Substrate
Within the Structural Delineation Framework (SDF), light rays passing through cosmic cavities undergo geometric refraction under the effective boundary potential $\Phi_{\text{boundary}}(r)$. Using the spacetime-optics formalism in the Kerr–Schild metric, the effective optical refractive index $n(\mathbf{r})$ takes the form:

$$n(\mathbf{r}) = 1 - \frac{2\Phi_{\text{eff}}(\mathbf{r})}{c^2} = 1 + \frac{2|\Phi_{\text{eff}}(\mathbf{r})|}{c^2}$$

where the effective potential is the superposition of the lumped-matter contribution inside the cavity and the boundary wall surface tension:

$$\Phi_{\text{eff}}(r) = \Phi_{\text{matter}}(r) + \Phi_{\text{boundary}}(r)$$

For a spherical cavity of radius $R_v$ with wall surface-stress density $\sigma_{\text{wall}}$, the geometric wall potential inside the cavity ($r \le R_v$) is a linear-radial function:

$$\Phi_{\text{boundary}}(r) = 2\pi G \sigma_{\text{wall}} r$$

---

## 2. The Unified Deflection Angle and Dimensional-Consistency Resolution
The total deflection of a light ray with impact parameter $b$ relative to the cavity center follows from the transverse potential-gradient integral along the line of sight ($z$):

$$\vec{\theta}_{\text{defl}} = -\frac{2}{c^2} \int_{-\infty}^{+\infty} \vec{\nabla}_\perp \Phi_{\text{eff}} \, dz$$

This integral separates into two distinct and dimensionally consistent components:

$$\theta_{\text{defl}}(b) = \theta_{\text{matter}}(b) + \theta_{\text{wall}}(b)$$

$$\theta_{\text{defl}}(b) = \frac{4 G M_{\text{eff}}(b)}{c^2 b} + \frac{4\pi^2 G \sigma_{\text{wall}}}{c^2} \left( \frac{b}{\sqrt{R_v^2 - b^2}} \right) \Theta(R_v - b)$$

where:
- The first term is the standard Schwarzschild deflection from a concentrated mass distribution with enclosed effective mass $M_{\text{eff}}(b)$ (dimension: $\frac{[\text{m}^3\text{kg}^{-1}\text{s}^{-2}][\text{kg}]}{[\text{m}^2\text{s}^{-2}][\text{m}]} = 1$, dimensionless).
- The second term is the boundary-shell correction from the shell stress: the coefficient $\frac{G \sigma_{\text{wall}}}{c^2}$ has inverse-length dimension ($[\text{m}]^{-1}$), and combined with the geometric factor $\frac{b}{\sqrt{R_v^2 - b^2}}$ (dimensionless) and integration along the shell thickness $\delta_{\text{wall}}$, it produces a fully dimensionless deflection angle:

$$\theta_{\text{wall}}(b) \approx \frac{8\pi G \sigma_{\text{wall}} \cdot b}{c^2 R_v} \quad \text{for } b \ll R_v$$

Dimensional analysis of the wall term:
$$[\theta_{\text{wall}}] = \frac{[\text{m}^3 \text{kg}^{-1} \text{s}^{-2}] [\text{kg} \cdot \text{m}^{-2}] [\text{m}]}{[\text{m}^2 \text{s}^{-2}] [\text{m}]} = \frac{\text{m}^2}{\text{m}^2} = 1 \quad \text{(dimensionless)}$$

---

## 3. The Null-Shell Discontinuity and the Barrabès–Israel Condition
When the optical wavefront crosses the cavity wall shell at $r = R_v$, the discontinuity in the wave vector $k^\mu$ is constrained by the surface stress tensor $S_{ab}$ on the boundary hypersurface $\Sigma$:

$$[k^\mu] = -\frac{8\pi G}{c^4} S^\mu{}_\nu k^\nu$$

This discontinuity produces a local **phase jump** that shifts the lensing signature from a mild continuous gravitational lens to an edge-patterned superposition (Shear Ring Signature) at the boundaries of large cosmic cavities.

---

## 4. Comparison with Observational Data and Empirical Tests
1. **Diverging center, converging edge:** unlike single-component $\Lambda\text{CDM}$ models that treat a void purely as a diverging (defocusing) lens with negative density, in SDF the presence of the pressurized wall ($\sigma_{\text{wall}}$) generates a shear ring with positive tensor convergence at the cavity edge ($b \approx R_v$).
2. **Tangential shear profile prediction:**
$$\gamma_t(\theta) = \begin{cases} -\bar{\kappa}(\theta) < 0 & \theta < \theta_v \quad \text{(divergence inside the void)} \\ +\kappa_{\text{ring}} > 0 & \theta \approx \theta_v \quad \text{(positive convergence of the boundary shell)} \end{cases}$$
This double profile is a key discriminating signature, testable and falsifiable in weak-lensing surveys such as the Euclid telescopes and the Rubin Observatory (LSST).

---

## 5. Network Links
- Chain phenomenological effects: [[01_Canonical_Chain_Engine/07_F_Phenomenological_Prints]]
- Geodesic-deviation equation: [[03_Geometric_Metric_Emergence/02_Geodesic_Deviation_Pressure]]
- Effective metric tensor emergence: [[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]
- Galactic rotation curvature: [[04_Observational_Validation/01_Galactic_Rotation_Curves]]
- Falsifiable empirical predictions: [[04_Observational_Validation/04_Empirical_Predictions]]
