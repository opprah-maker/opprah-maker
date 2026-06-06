<div align="center">

# Opprah Manyika

**Principal Systems Architect, Irene Vera Foundation &nbsp;|&nbsp; Quantitative Engineering Researcher**

Engineering researcher and systems architect operating at the intersection of **rigorous numerical engineering** and **sovereign AI infrastructure**. Doctoral-level experience in computational fluid dynamics, fluid-structure interaction, and transient thermal modelling, combined with architectural leadership of production AI systems on Oracle Cloud Infrastructure for [Irene Vera Foundation](https://ireneveryfoundation.com).

For background, architecture decision records, and the Sovereign AI Stack programme &rarr; see the [Irene Vera Foundation website](https://ireneveryfoundation.com).

[![Website](https://img.shields.io/badge/Website-ireneveryfoundation.com-blue?logo=google-chrome&logoColor=white)](https://ireneveryfoundation.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](#)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0000--0000--0000-A6CE39?logo=orcid&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?logo=gmail&logoColor=white)](mailto:contact@ireneveryfoundation.com)
[![GitHub followers](https://img.shields.io/github/followers/opprah-maker?style=social)](https://github.com/opprah-maker)

</div>

---

## Affiliation

### Irene Vera Foundation
**London, United Kingdom** &middot; [ireneveryfoundation.com](https://ireneveryfoundation.com)

Not-for-profit operating at the intersection of **AI governance, digital identity, and data protection**. Irene Vera Foundation develops and maintains a structured digital governance framework aligned with:

| Regulatory Standard | Scope |
|---|---|
| UK GDPR & Data Protection Act 2018 | Lawful basis, special category safeguards |
| Data (Use and Access) Act 2025 | Digital verification, smart data |
| ICO Accountability Framework | Controller obligations, breach readiness |
| DCMS Digital Maturity Framework | Domain-based governance evaluation |
| NHS Digital Maturity Assessment | Public-sector-aligned maturity scoring |
| NCSC Cyber Assessment Framework | Security controls, incident response |
| ISO/IEC 27001:2022 | Information security management system |

**Role: Principal Systems Architect**

- Architecture Decision Records (ADRs) for the Sovereign AI Stack programme
- Oracle Cloud Infrastructure (OCI) Always Free &mdash; ARM Ampere A1 compute layer
- Gemma 4 via Ollama for sovereign reasoning; EmbeddingGemma 300M via ONNX for in-database RAG
- Oracle Autonomous Database 23ai with `DBMS_VECTOR_CHAIN` and `DBMS_SCHEDULER` orchestration
- Oracle APEX / ORDS as the API and management plane
- Foundation Digital Maturity Index: **52.8 %** (Developing &rarr; Defined, GREEN ICO status)

---

## Pinned Projects &mdash; University Engineering Portfolio

Quantitative engineering projects from undergraduate study in **Aerospace Engineering**, demonstrating numerical methods, CFD simulation, aerodynamics, and aerospace systems design. *(Toolchain: MATLAB / GNU Octave, ANSYS Fluent & Mechanical, SolidWorks.)*

### Computational Fluid Dynamics

#### [CFD-Axial-Flow-Fan-Analysis](https://github.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis)
Quantitative CFD and Fluid-Structure Interaction simulation of an axial-flow cooling fan. Solves the standard $k$-$\epsilon$ turbulence transport equations with a pressure-based steady solver. Optimised blade installation angle ($30^{\circ}$) and tip clearance ($< 0.1D$) deliver a measured **2.1 %** efficiency gain over baseline. Validated against wind tunnel data within **$\pm 3\%$**.

| `cfd` `ansys-fluent` | `fsi` `axial-fan` | `fluid-dynamics` `finite-element-analysis` |

#### [Bellmouth-Inlet-CFD-Gas-Turbine](https://github.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine)
Design and CFD optimisation of an elliptical bellmouth inlet to minimise inlet pressure loss and maximise mass flow rate ($\dot{m} = 1.0\,\text{kg/s}$) for gas turbine engines. Validated using the von K&aacute;rm&aacute;n integral boundary layer method for adverse pressure gradient flows. Five Fluent contour plots and the full dissertation text are included.

| `cfd` `ansys-fluent` | `bellmouth-inlet` `gas-turbine` | `aerospace-engineering` `heat-transfer` |

### Numerical Methods

#### [Heat-Conduction-FDM-Analysis](https://github.com/opprah-maker/Heat-Conduction-FDM-Analysis)
MATLAB numerical simulation of transient 2D heat conduction on a square plate using the explicit Finite Difference Method (FDM) with the Forward-Time Central-Space (FTCS) scheme. Validated against the von Neumann stability criterion
$$\Delta t \;\le\; \frac{(\Delta x)^2}{4\alpha}.$$
The full discretisation,
$$\frac{T_{i,j}^{n+1} - T_{i,j}^{n}}{\Delta t} \;=\; \alpha\!\left[\,\frac{T_{i+1,j}^{n} - 2T_{i,j}^{n} + T_{i-1,j}^{n}}{(\Delta x)^2} \;+\; \frac{T_{i,j+1}^{n} - 2T_{i,j}^{n} + T_{i,j-1}^{n}}{(\Delta y)^2}\,\right],$$
is documented in the README alongside boundary conditions, stability margins, and steady-state contour output.

| `finite-difference-method` `numerical-methods` | `heat-conduction` `ftcs-scheme` | `matlab` `pde-solver` |

### Aerodynamics & Sizing

#### [NACA-0012-Aerodynamics-Wind-Tunnel](https://github.com/opprah-maker/NACA-0012-Aerodynamics-Wind-Tunnel)
Experimental wind tunnel data processing for the NACA 0012 symmetric aerofoil. Computes lift and drag coefficients ($C_L$, $C_D$) across angles of attack $\alpha \in [-2^{\circ}, 35^{\circ}]$. Identifies aerodynamic stall at $\alpha \approx 16^{\circ}$ and a peak lift-to-drag ratio $(L/D)_{\max} \approx 5.12$ at $\alpha = 4^{\circ}$. Atmospheric reference: $P = 1001.25\,\text{hPa}$, $T = 20.1^{\circ}\text{C}$.

| `aerodynamics` `wind-tunnel-testing` | `naca-0012` `fluid-mechanics` | `matlab` `experimental-methods` |

#### [Heavy-Lift-Aircraft-Design](https://github.com/opprah-maker/Heavy-Lift-Aircraft-Design)
MATLAB conceptual sizing, aerodynamic configuration, and directional stability analysis of a heavy-lift cargo transport aircraft. Sizes wing loading ($W/S = 10\,980\,\text{N/m}^2$) and thrust-to-weight ratio ($T/W = 0.30$) for heavy-payload operations. Validates directional yaw stiffness $C_{n_{\beta}} > 0.004$ via vertical tail stabiliser volume sizing.

| `aircraft-design` `matlab` | `aircraft-sizing` `aerodynamics` | `directional-stability` `conceptual-design` |

### Energy & Policy Modelling

#### [UK-Energy-Market-Sustainable-Reform](https://github.com/opprah-maker/UK-Energy-Market-Sustainable-Reform)
MATLAB Hybrid Renewable Energy Systems (HRES) scenario modelling of UK electricity market reform pathways towards Net-Zero. Compares Baseline, Renewable Incentivisation, and Demand-Side Response (DSR) Battery Buffering scenarios. Models an **83.3 %** carbon reduction trajectory and a **125 %** gain in grid resilience via DSR battery buffering.

| `energy-modeling` `matlab` | `renewable-energy` `grid-resilience` | `policy-modeling` `net-zero` |

---

## Core Competencies

### Engineering Simulation &amp; CFD
| Domain | Tools | Methods |
|---|---|---|
| Computational Fluid Dynamics | ANSYS Fluent / Mechanical | $k$-$\epsilon$ turbulence, pressure-based steady solver, mesh sensitivity, skewness &amp; orthogonal quality metrics |
| Fluid-Structure Interaction | ANSYS Mechanical + Fluent | FSI coupling, modal analysis, stress / strain field extraction |
| Aerodynamics | MATLAB / wind tunnel | Lift / drag polars, boundary layer separation, stall onset identification |
| Numerical Methods | MATLAB / GNU Octave | FDM (FTCS, explicit), von Neumann stability, convergence analysis |
| CAD &amp; Design | SolidWorks, ANSYS DesignModeler, SpaceClaim | Aerodynamic surfacing, mechanical layout, geometry clean-up |

### Systems Architecture &amp; Sovereign AI
| Domain | Tools | Methods |
|---|---|---|
| AI Infrastructure | Oracle Cloud Infrastructure (OCI) Always Free | ARM Ampere A1, LXD virtualisation, sovereign deployment |
| AI Inference | Ollama, Gemma 4, EmbeddingGemma 300M | ONNX native loading, RAG pipeline, vector search |
| Database &amp; Orchestration | Oracle Autonomous Database 23ai | `DBMS_VECTOR_CHAIN`, `DBMS_SCHEDULER`, APEX / ORDS |
| Data Governance | UK GDPR, DPA 2018, DUA 2025 | ICO accountability, NCSC CAF, maturity scoring |
| Architecture Documentation | Architecture Decision Records (ADRs) | GDS ADR framework, component diagrams, rationale logging |

### Aerospace Systems &amp; Policy
| Domain | Methods |
|---|---|
| Aircraft Conceptual Design | Wing loading, thrust-to-weight, stability derivatives, vertical tail volume |
| Energy Systems Modelling | HRES scenario analysis, carbon reduction trajectories, DSR battery buffering |
| Regulatory &amp; Policy Modelling | UK electricity market reform, Net-Zero pathway analysis, grid resilience metrics |

---

## Engineering Software &amp; Toolchain

<p>
  <img alt="MATLAB" src="https://img.shields.io/badge/MATLAB-Orange?logo=mathworks&logoColor=white" />
  <img alt="GNU Octave" src="https://img.shields.io/badge/GNU%20Octave-0790C0?logo=octave&logoColor=white" />
  <img alt="ANSYS Fluent" src="https://img.shields.io/badge/ANSYS%20Fluent-FFB71B?logo=ansys&logoColor=black" />
  <img alt="ANSYS Mechanical" src="https://img.shields.io/badge/ANSYS%20Mechanical-FFB71B?logo=ansys&logoColor=black" />
  <img alt="SolidWorks" src="https://img.shields.io/badge/SolidWorks-DA1F26?logo=solidworks&logoColor=white" />
  <img alt="Oracle Cloud" src="https://img.shields.io/badge/Oracle%20Cloud-F80000?logo=oracle&logoColor=white" />
  <img alt="Oracle Autonomous DB" src="https://img.shields.io/badge/Oracle%20Autonomous%20DB-F80000?logo=oracle&logoColor=white" />
  <img alt="APEX" src="https://img.shields.io/badge/Oracle%20APEX-F80000?logo=oracle&logoColor=white" />
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000?logo=ollama&logoColor=white" />
  <img alt="Gemma 4" src="https://img.shields.io/badge/Gemma%204-4285F4?logo=google&logoColor=white" />
  <img alt="ONNX" src="https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
  <img alt="Markdown" src="https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white" />
</p>

---

## Foundation Digital Governance Snapshot

This portfolio is published under the **Irene Vera Foundation** digital governance framework. Key indicators (April 2026):

| Domain | Indicator | Current | Target | Gap |
|---|---:|:---:|:---:|:---:|
| Leadership Governance | Formal digital governance documentation | 3 | 4 | 1 |
| Lawful Basis Mapping | Full Article 6 &amp; 9 documentation | 2 | 4 | 2 |
| Identity Control | Unique user accounts enforced | 2 | 4 | 2 |
| Access Management | Least privilege formally implemented | 2 | 4 | 2 |
| Security Controls | Multi-factor authentication coverage | 2 | 4 | 2 |
| Breach Protocol | 72-hour response readiness | 3 | 4 | 1 |

**Digital Maturity Index:** $\displaystyle \frac{19}{36}\times 100 = 52.8\%$
**ICO recorded status (28 April 2026):** GREEN &mdash; "You don't need to pay a fee." Full UK GDPR compliance still required.

---

<div align="center">

&copy; Opprah Manyika &middot; Portfolio published under the Irene Vera Foundation Digital Governance Framework
<br/>
<sub>This README is generated content maintained as part of the Foundation's published digital maturity evidence.</sub>

</div>
