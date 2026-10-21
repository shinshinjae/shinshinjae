<div align="center">

# 👋 Jaewan Shin | 신재완

### Mathematical Modeling · Scientific Computing · Research-Driven Software

**From mathematical theory and real-world data to validated models and working applications.**

[![GitHub](https://img.shields.io/badge/GitHub-shinshinjae-181717?style=flat-square&logo=github)](https://github.com/shinshinjae)
[![PADO CALL](https://img.shields.io/badge/PADO%20CALL-Live%20Demo-16a6a1?style=flat-square)](https://shinshinjae.github.io/pado-call/)

</div>

## About Me

복잡한 현실 문제를 **수리모형·확률과정·통계적 추론**으로 분석하고, 가설을 **수치실험·검증·소프트웨어**로 연결하는 연구에 참여하고 있습니다. 반도체 공정, 교통 시스템, 감염병 확산 및 금융 변동성 등 서로 다른 응용 영역에서 모델의 가정과 한계를 명시하고 데이터로 평가하는 작업에 관심이 있습니다.

I work across **mathematical modeling, statistical inference, computational validation, and software implementation**, with research experience spanning manufacturing processes, transportation, infectious-disease dynamics, and financial volatility.

## Research Focus

- **Mathematical & stochastic models:** differential equations, Markov/birth–death processes, stochastic simulation, dynamical systems.
- **Statistical inference & validation:** parameter estimation, particle filtering/smoothing, uncertainty and sensitivity analysis, out-of-sample evaluation.
- **Mobility & transportation:** public-transport demand, demand-responsive transit (DRT), operational and economic evaluation.
- **Scientific software:** reproducible computational analysis, cross-checking mathematical models against numerical implementations.

## Research Papers & Manuscripts

> **Publication status (as provided by the author):** 1 forthcoming in the *Journal of the Korean Data Analysis Society* (한국자료분석학회), and 4 under peer review. The forthcoming paper does not yet have confirmed volume, pages, DOI, or publication date. Status is based on the author’s update, not independent journal verification. Individual contribution statements are included only where explicitly reported in the manuscripts.

### 01 · Vacuum–Repressurization Void Removal in Flip-Chip Underfill

**Status:** Under peer review (심사 중)

**Vacuum–repressurization void removal in flip-chip underfill: a hybrid reduced-order process model**  
*Jaewan Shin, Sanghyun Lee, Minsoo Kim*

- Developed a **hybrid reduced-order model** separating void expansion, geometric connection to a release boundary, and gas release.
- Used an **area-weighted population response** calibrated to experimental before–after void measurements; the model fitted removal ratios of **40.8%, 59.5%, and 90.7%** at vacuum depths of **0.03, 0.06, and 0.09 MPa** for 3-minute holds.
- Derived a **geometry-only connectability criterion** to screen which voids could reach a release boundary, while explicitly distinguishing geometric accessibility from demonstrated gas release.
- **My role (CRediT in manuscript):** Methodology, Software, Formal analysis, Writing – original draft.

`Hybrid dynamical systems` `Reduced-order modeling` `Parameter calibration` `Image analysis`

### 02 · Mobility-Informed Regional Influenza Transmission

**Status:** Forthcoming / scheduled for publication (게재 예정) — *Journal of the Korean Data Analysis Society* (한국자료분석학회). Bibliographic details pending.

**A mobility-informed SIR model for regional transmission dynamics: Evidence from subway mobility data in Korea, 2016–2023**  
*Jaewan Shin, Eunhwa Jeong, Seojin Jo, Minsoo Kim, Seungbae Ahn, Chankeun Park*

- Integrated **aggregated subway boarding data** with a mobility-adjusted **SIR model**, avoiding the requirement for a full origin–destination mobility matrix.
- Estimated time-varying transmission using **particle filtering and smoothing**, with a **negative-binomial observation model** for overdispersed daily influenza counts.
- Studied five metropolitan areas across four influenza seasons; in a synthetic benchmark, smoothing reduced reproduction-number estimation RMSE from **0.109 to 0.029** relative to filtering.
- Manuscript identifies **Jaewan Shin, Eunhwa Jeong, and Seojin Jo as equal contributors**.

`SIR models` `Human mobility` `Particle smoothing` `Spatial epidemiology`

### 03 · DRT Conversion Conditions for Low-Demand Bus Services

**Status:** Under peer review (심사 중)

**Conditions for Converting Low-Demand City Bus Services to Demand-Responsive Transit in Busan: Minute-Level Stop Demand Reconstruction and a Kolmogorov Forward-Equation Model**  
*Jaewan Shin, Minsoo Kim*

- Reconstructed **minute-level stop demand** from 30-minute smart-card counts for **160 Busan bus routes**, preserving aggregated totals.
- Modeled fixed-route waiting using an **impulsive differential equation** and DRT request states using the **Kolmogorov forward equation** of a birth–death process.
- Compared trip-block conversion plans under waiting-time standards, chance constraints, fleet requirements, and economic costs.
- Found **no stable DRT conversion candidate under baseline assumptions among 62 eligible routes**, highlighting the importance of vehicle-hours, idle-vehicle positioning, and zone-based pooling.

`Public transit` `DRT` `Kolmogorov forward equation` `Stochastic queues` `Economic evaluation`

### 04 · Identifiability in Mobility-Adjusted Influenza Models

**Status:** Under peer review (심사 중)

**Practical Identifiability and Model Dependence in Mobility-Adjusted Influenza Transmission Models: A Multi-City Analysis Using Subway Ridership**  
*Jaewan Shin, Minsoo Kim*

- Evaluated whether a mobility term in a **negative-binomial renewal model** can be distinguished from flexible residual transmission.
- Compared no-mobility, proportional-mobility, and estimated-elasticity specifications over **five regions and four influenza seasons**.
- Assessed **practical identifiability** using regularization sensitivity, likelihood profiling, dependence-robust uncertainty, temporal and geographic negative controls, and held-out scoring.
- Found that estimated mobility effects were **model- and calendar-dependent**; mobility-augmented specifications did **not improve pooled held-out scores** in the reported comparisons.

`Renewal models` `Identifiability` `Negative controls` `Regularized inference`

### 05 · Post-Crisis Volatility Forecasting

**Status:** Under peer review (심사 중)

**A Transition-Discounted Regime-Dependent GARCH Model for Post-Crisis Volatility Forecasting**  
*Jaewan Shin, Eunhwa Jeong, Seojin Jo, Seongjin Jeong, Minsoo Kim*

- Proposed **TD-RDP-GARCH**, reducing the carryover of crisis-period variance during a crisis-to-normal transition without forcing low-volatility-regime persistence downward.
- Tested the method through **Monte Carlo experiments** and **KOSPI/S&P 500 crisis episodes**, selecting transition discounting with held-out validation.
- Obtained lower pooled QLIKE loss with several **range-based realized-volatility proxies**; the model reverted to its benchmark when the close-to-close proxy did not support discounting.
- **My role (CRediT in manuscript):** Methodology, Software, Visualization, Writing – original draft. Four student authors are identified as equal contributors.
- **Reproducibility code:** [KMOU-RDP-GARCH-model](https://github.com/jaewansh/KMOU-RDP-GARCH-model) (repository referenced in manuscript).

`GARCH` `Regime-dependent volatility` `Monte Carlo` `Forecast evaluation`

## Conference Presentations

- **2026 Annual Meeting of the Korean Society for Mathematical Biology** (June 25–28, 2026) — Poster presentation  
  *Disentangling Mobility-Driven and Intrinsic Transmission in Regional Influenza Dynamics*  
  Jaewan Shin, Eunhwa Jeong, Seojin Jo, Minsoo Kim

- **Mathematical Pharmacology Symposium 2026** (July 31–August 1, 2026) — Poster presentation
  *Quantitative Modeling Reveals Reaction-Driven Propagation of IP3-Mediated Calcium Waves*  
  Jaewan Shin, Sung-Chul Hong, Minsoo Kim

---

## Software Project

### 🌊 PADO CALL — Multilingual Tourism Mobility Platform

[**Source Code**](https://github.com/shinshinjae/pado-call) · [**Live Demo**](https://shinshinjae.github.io/pado-call/)

![PADO CALL demo](https://raw.githubusercontent.com/shinshinjae/pado-call/main/image/demo.gif)

- Interactive tourism-mobility demonstration connecting **Gimhae Airport and Busan visitor areas**.
- Features airport shuttle booking, demand-responsive rides, congestion visualization, **QR boarding**, multilingual interfaces, and a control dashboard.
- Integrates a **Python reference model** and **TypeScript/React application** with testable modeling and simulation components.
- The payment flow and selected data are **demonstration/simulated features**, not a production payment or transit operation.

`Python` `TypeScript` `React` `Vite` `Simulation` `Data visualization`

## Tools & Methods

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

**Methods:** Numerical simulation · Differential equations · Stochastic processes · Monte Carlo · Particle filtering/smoothing · Statistical estimation · Model validation

## Contact

- **GitHub:** [@shinshinjae](https://github.com/shinshinjae)

---

<sub>Publication statuses were provided by the author and should be updated after editorial confirmation or final publication. Research descriptions are based on manuscript versions; journal volume, pages and DOI should only be added once verified. Coauthor credits and research limitations should be preserved.</sub>
