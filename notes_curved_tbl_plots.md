# Plots shown in the curved-surface TBL literature

Which plot types each curved-surface / bump / curvature paper in `bibliography_MA.bib` presents.
The wide matrix is split into three readable tables that share the same paper rows.

**Legend:** ✓ = shown · ~ = partial / minor · blank = not shown

The papers fall into three families:

- **[E] Classic convex/concave experiments**
- **[S] Modern bump / airfoil DNS & LES**
- **[R] RANS / model-assessment on curvature**

| # | Paper |
|---|---|
| E1 | So & Mellor 1973 — convex |
| E2 | So & Mellor 1975 — concave |
| E3 | So & Mellor report — convex+concave, separation |
| E4 | Gillis & Johnston 1983 — convex + recovery |
| E5 | Johnston, Moffat & Kays — convex |
| E6 | Muck, Hoffmann & Bradshaw 1985 — convex |
| E7 | Meroney & Bradshaw 1975 — longitudinally curved |
| E8 | Patel — cylinder + 90° duct |
| E9 | Schwarz & Plesniak 1996 — convex, ZPG/FPG |
| E10 | Baskaran, Smits & Joubert 1991 — curved hill |
| E11 | Chiwanga & Ramaprian 1993 — convex, structure |
| S1 | Wu & Squires 1998 — bump LES |
| S2 | Balin & Jansen 2021 — Gaussian bump DNS |
| S3 | Spalart, Jansen & Coleman 2024 — bump vs transpiration |
| S4 | Pargal et al. 2022 — airfoil vs flat, matched K |
| S5 | Matai & Durbin 2019 — parametric bumps LES |
| S6 | Cavar & Meyer 2011 — 2D bump LES |
| R1 | Yang & Tucker 2016 — 60° bent channel |
| R2 | Monson et al. 1990 — U-duct |

---

## 1 · Setup & wall distributions

| # | Setup geom. | Cp | Cf | δ*, θ, H, Re | β / K / Λ | δ/R curv. |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| E1 | ✓ | ✓ | ✓ | | | |
| E2 | ✓ | ✓ | ✓ | ~ | | |
| E3 | ✓ | ✓ | ✓ | ✓ | | ~ |
| E4 | ✓ | | ~ | ~ | | ~ |
| E5 | ✓ | ✓ | ✓ | ✓ | | |
| E6 | ~ | ✓ | ✓ | | | |
| E7 | ~ | ✓ | | ✓ | | |
| E8 | ✓ | ✓ | | ✓ | | |
| E9 | ✓ | | ✓ | ✓ | ✓ | |
| E10 | ~ | | | | | |
| E11 | ✓ | ✓ | ✓ | | | |
| S1 | ✓ | ✓ | ✓ | ✓ | ✓ | |
| S2 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| S3 | ✓ | ✓ | ✓ | ✓ | | ✓ |
| S4 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| S5 | ✓ | ✓ | ✓ | ~ | ✓ | ✓ |
| S6 | ✓ | ✓ | ✓ | ~ | | |
| R1 | ✓ | ✓ | ✓ | | ✓ | |
| R2 | ✓ | ✓ | ✓ | | | |

---

## 2 · Mean-velocity & Reynolds-stress profiles

| # | Vel. defect/outer | Vel. wall-units | Shear −uv | Normal stresses | TKE |
|---|:-:|:-:|:-:|:-:|:-:|
| E1 | ✓ | ✓ | ✓ | ✓ | ~ |
| E2 | ✓ | ✓ | ✓ | ✓ | |
| E3 | ✓ | ✓ | ✓ | ~ | |
| E4 | ✓ | ✓ | ✓ | | |
| E5 | ✓ | ✓ | ✓ | ✓ | ✓ |
| E6 | | ✓ | ✓ | ✓ | |
| E7 | | | ✓ | ✓ | |
| E8 | | ✓ | | | |
| E9 | | | ✓ | | |
| E10 | | | ✓ | ✓ | ✓ |
| E11 | | | | | |
| S1 | | ✓ | ✓ | ✓ | ✓ |
| S2 | | ✓ | ✓ | ✓ | ✓ |
| S3 | | ✓ | ✓ | ✓ | |
| S4 | | ✓ | ✓ | ✓ | |
| S5 | | ✓ | ✓ | ✓ | ✓ |
| S6 | | ✓ | | ✓ | |
| R1 | ✓ | ✓ | | | ✓ |
| R2 | | | ✓ | | ✓ |

---

## 3 · Budgets & advanced diagnostics

| # | Budgets | Mix.len / eddy-visc | Spectra | 2-pt corr. | Contours / vis. | RANS model |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| E1 | ~ | | | | | |
| E2 | | | | | | |
| E3 | | | | | | ✓ |
| E4 | ~ | ✓ | | | | |
| E5 | ~ | ✓ | | | | ✓ |
| E6 | ✓ | ✓ | | | | |
| E7 | | | | | | |
| E8 | | | | | | ✓ |
| E9 | | | | | | |
| E10 | ✓ | ✓ | | | | |
| E11 | | | | | ✓ | |
| S1 | ✓ | | ✓ | | ~ | |
| S2 | ✓ | | | | ✓ | ~ |
| S3 | ~ | ✓ | | | ✓ | ✓ |
| S4 | | | | ✓ | | |
| S5 | ~ | ✓ | | | ✓ | ✓ |
| S6 | | | | | ✓ | ✓ |
| R1 | | | | | ✓ | ✓ |
| R2 | | | | | | ✓ |

---

## Takeaways

- **Near-universal backbone** (in almost every paper): setup geometry, wall Cp, wall Cf, mean-velocity profiles, and the Reynolds shear stress −uv — the most curvature-sensitive quantity.
- **Two velocity scalings** are the classic curvature diagnostic: the outer/**defect** plot (older experiments) and the inner/**wall-units** semilog plot (modern DNS/LES).
- **Pressure-gradient parameters (β, K, Λ)** and **δ/R curvature** appear mainly in the modern bump/airfoil DNS-LES papers (S2, S4, S5, S3); older experiments rarely plot β — Schwarz & Plesniak (E9) is the exception.
- **TKE budgets with an explicit curvature-production term** are a hallmark of the physics-focused papers (E6, E10, S1, S2).
- **RANS-model overlays** dominate the assessment papers (R1, R2, S3) and the data-driven bump study (S5).
- **Chiwanga & Ramaprian (E11)** is the outlier: a flow-visualization (smoke-photo) structure paper, not a statistics paper.

_Generated 2026-07-06 from figure captions extracted from the PDFs in `bibliography_MA.bib`. The ~ partials are judgment calls — spot-check against the actual figures before relying on a single cell._
