---
id: SDF-ENG-01-08-METRIC-GAUGE
title: Metric Grounding and Temporal Gauge
created: 2026-09-05
updated: 2026-10-05
author: Adel Gachkar
license: MIT
status: canonical
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

# Metric Grounding and Temporal Gauge

## 1. Temporal Gauge Fixing and 3+1 ADM Foliation
Within the Structural Delineation Framework (SDF), the time parameter is not a pre-existing component: it is the rate of advance of the delimitation phase along the unit normal $n^\mu$ of the spatial sheets. Effective spacetime is grounded through the standard $3+1$ ADM decomposition:

$$ds^2 = -N^2 c^2 dt^2 + \gamma_{ij} (dx^i + \beta^i dt)(dx^j + \beta^j dt)$$

where:
- $N(x, t)$ is the lapse function, setting the local proper-time passage rate relative to the sheet-synchronized time ($d\tau = N dt$).
- $\beta^i(x, t)$ is the shift vector, describing the relative sliding of coordinate lines along the foliation.
- $\gamma_{ij}$ is the induced 3-dimensional Riemannian metric on the co-phase sheets $\Sigma_t$.

In the absence of induced rotations and pure momentum interactions ($\beta^i = 0$), the line element reduces to the standard diagonal form:

$$ds^2 = -N^2 c^2 dt^2 + \gamma_{ij} dx^i dx^j$$

---

## 2. Physical Grounding of the Lapse Function in the Boundary-Stress Potential (Lapse Grounding)
The gauge coefficient $N$ is directly determined and constrained by the gradient of the boundary-stress density and the geometric potential of the cavities ($\Phi_{\text{boundary}}$):

$$N = \sqrt{1 - \frac{2\Phi_{\text{boundary}}(x)}{c^2}}$$

In the weak-field limit ($\Phi_{\text{boundary}} \ll c^2$):

$$N \approx 1 - \frac{\Phi_{\text{boundary}}(x)}{c^2}$$

This structure shows that gravitational time dilation is the direct consequence of the reduced phase-transfer rate in the vicinity of concentrated surface stresses of the cavity walls.

---

## 3. Lapse Gradient and the 4-Acceleration (Acceleration & Lapse Gradient)
The 4-acceleration of the uniform flow lines orthogonal to the sheets ($a_\mu = n^\nu \nabla_\nu n_\mu$) follows directly from the logarithmic gradient of the lapse function:

$$a_i = \partial_i \ln N = \frac{1}{N} \partial_i N \approx -\frac{1}{c^2} \partial_i \Phi_{\text{boundary}}$$

This relation is equivalent to the boundary acceleration arising from the phase-leak field of [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]:

$$a_i = -\frac{1}{c^2} \nabla_i \Phi_{\text{boundary}} = \mathcal{Q}_{\text{leak}, i}$$

---

## 4. Sheet Compatibility Condition and Gauge Conservation
To guarantee gauge-invariance preservation and the kinematic closure of the canonical chain, the extrinsic curvature of the sheets ($K_{ij}$) is coupled to the time variation of the spatial metric:

$$K_{ij} = -\frac{1}{2N} \left( \partial_t \gamma_{ij} - D_i \beta_j - D_j \beta_i \right)$$

In the phase-normal gauge ($\beta^i = 0$):

$$\partial_t \gamma_{ij} = -2N K_{ij}$$

This equation guarantees that the evolution of the spatial geometry remains fully continuous with the Israel junction conditions on the walls.

## 5. Network Links and the Canonical Chain
- Parent chain node: [[01_Canonical_Chain_Engine/05_M_Manifold_Foliations]]
- Metric foundations: [[03_Geometric_Metric_Emergence/01_Effective_Metric_Tensor]]
- Boundary-pressure acceleration field: [[02_Boundary_Pressure_Gravity/03_Acceleration_Emergence_Field]]
