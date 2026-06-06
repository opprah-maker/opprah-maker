<div align="center">

# Opprah Manyika

**Aerospace Engineering : Computational Simulation, Numerical Methods, and Systems Design**

Aerospace engineer focused on **computational fluid dynamics**, **fluid-structure interaction**,
**transient heat transfer**, and **conceptual aircraft design**. Tools: MATLAB, GNU Octave,
ANSYS Fluent & Mechanical, SolidWorks.

This profile hosts the full university engineering portfolio : MATLAB scripts, ANSYS
post-processing, wind-tunnel data, hand-written PDE solvers, and the complete academic
reports as PDFs.

</div>

---

## ⭐ Pinned: Individual Project Dissertation

### [Reforming the UK Energy Market for Sustainable Development: Integrating Renewables, Fair Pricing, and Demand-Side Response](https://github.com/opprah-maker/UK-Energy-Market-Sustainable-Reform)

The full individual project dissertation evaluating UK electricity market reform pathways to Net-Zero. Three policy scenarios (Baseline, Renewable Incentivisation, Demand-Side Response) compared using HRES scenario modelling in MATLAB.

| Metric | Baseline | Renewable Incentivisation | Demand-Side Response |
|---|---|---|---|
| Renewable Integration | $15\%$ | $65\%$ | $80\%$ |
| Carbon Emissions (Mton/yr) | $120$ | $45$ | $20$ |
| Grid Resilience (1-100) | $40$ | $55$ | $90$ |
| Consumer Cost Index (1-100) | $85$ | $50$ | $30$ |

**Key finding**: DSR delivers an **83.3% carbon reduction** and **125% grid resilience gain** while reducing consumer costs.

[<img src="https://raw.githubusercontent.com/opprah-maker/UK-Energy-Market-Sustainable-Reform/main/images/figure-04.png" width="400" alt="Carbon emission reduction trajectory"/>](https://github.com/opprah-maker/UK-Energy-Market-Sustainable-Reform)

| `uk-energy` `dissertation` | `net-zero` `grid-resilience` | `demand-side-response` `policy-modelling` |

---

## Table of Contents — University Engineering Portfolio

1. [Pinned: Individual Project Dissertation](#-pinned-individual-project-dissertation)
2. [CFD & FSI — Axial-Flow Fan](#cfd--fsi--axial-flow-fan)
3. [Aircraft Aerodynamics & Design](#aircraft-aerodynamics--design)
4. [CFD — Bellmouth Inlet for Gas Turbine](#cfd--bellmouth-inlet-for-gas-turbine)
5. [Numerical Methods — Heat Conduction FDM](#numerical-methods--heat-conduction-fdm)
6. [Core Competencies](#core-competencies)
7. [Toolchain](#toolchain)

---

## CFD & FSI : Axial-Flow Fan

#### [CFD-Axial-Flow-Fan-Analysis](https://github.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis)
Comprehensive CFD and FSI analysis of a 60mm computer cooling axial-flow fan with 6 NACA 0012 blades. ANSYS Fluent with $k-\omega$ SST turbulence, 3D fan simulation, and coupled FSI validation. Optimal blade installation angle $30°$, delivering $6.34 \times 10^{-3}\,\text{m}^3/\text{s}$ flow rate and 10.8 Pa pressure rise. FSI maximum von Mises stress 15.2 MPa (safety factor 2.6).

[<img src="https://raw.githubusercontent.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis/main/images/figure-01.png" width="400" alt="Velocity streamlines from ANSYS Fluent"/>](https://github.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis)

| `cfd` `ansys-fluent` `fsi` | `axial-fan` `naca-0012` | `k-omega-sst` `fluid-dynamics` |

---

## Aircraft Aerodynamics & Design

#### [Aircraft-Aerodynamics-Design](https://github.com/opprah-maker/Aircraft-Aerodynamics-Design)
Combined project: experimental aerodynamics of the NACA 0012 aerofoil plus the conceptual sizing of a heavy-lift transport aircraft. Wind-tunnel data ($C_L$, $C_D$ at $-2°$ to $35°$), lift / drag polars, $(L/D)_\text{max} \approx 5.12$ at $\alpha = 4°$, stall onset at $\alpha \approx 16°$, plus the aircraft sizing loop ($W/S = 10{,}980\,\text{N/m}^2$, $T/W = 0.30$, $C_{n_\beta} > 0.004$).

[<img src="https://raw.githubusercontent.com/opprah-maker/Aircraft-Aerodynamics-Design/main/images/aerodynamics/figure-01.png" width="400" alt="NACA 0012 lift curve"/>](https://github.com/opprah-maker/Aircraft-Aerodynamics-Design)

| `aerodynamics` `aircraft-design` | `aircraft-sizing` `directional-stability` | `matlab` `naca-0012` `wind-tunnel-testing` |

> *Note: The original NACA-0012-Aerodynamics-Wind-Tunnel and Heavy-Lift-Aircraft-Design repos have been merged into this single project.*

---

## CFD : Bellmouth Inlet for Gas Turbine

#### [Bellmouth-Inlet-CFD-Gas-Turbine](https://github.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine)
CFD optimisation of an elliptical bellmouth inlet for a gas turbine engine. Mass flow rate $\dot{m} = 1.0\,\text{kg/s}$, total-pressure recovery $\eta_p > 0.99$. Validated using the von Kármán integral boundary layer method for adverse pressure gradient flows. Five Fluent contour plots (static, dynamic, total pressure, velocity, wall shear).

[<img src="https://raw.githubusercontent.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine/main/images/figure-08.png" width="400" alt="Bellmouth inlet pressure contour"/>](https://github.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine)

| `cfd` `ansys-fluent` | `bellmouth-inlet` `gas-turbine` | `aerospace-engineering` `boundary-layer` |

---

## Numerical Methods : Heat Conduction FDM

#### [Heat-Conduction-FDM-Analysis](https://github.com/opprah-maker/Heat-Conduction-FDM-Analysis)
Transient 2D heat conduction on a square plate solved with the explicit FTCS Finite Difference Method in MATLAB. Validated against the von Neumann stability criterion $\Delta t \le h^2/(4\alpha)$. Discretisation:

$$\frac{T_{i,j}^{n+1} - T_{i,j}^{n}}{\Delta t} = \alpha \left[\frac{T_{i+1,j}^{n} - 2T_{i,j}^{n} + T_{i-1,j}^{n}}{h^2} + \frac{T_{i,j+1}^{n} - 2T_{i,j}^{n} + T_{i,j-1}^{n}}{h^2}\right]$$

[<img src="https://raw.githubusercontent.com/opprah-maker/Heat-Conduction-FDM-Analysis/main/images/figure-09.png" width="400" alt="Steady-state temperature contour"/>](https://github.com/opprah-maker/Heat-Conduction-FDM-Analysis)

| `finite-difference-method` `numerical-methods` | `heat-conduction` `ftcs-scheme` | `matlab` `pde-solver` `von-neumann-stability` |

---

## Core Competencies

### Engineering Simulation & CFD
| Domain | Tools | Methods |
|---|---|---|
| Computational Fluid Dynamics | ANSYS Fluent / Mechanical | $k$-$\omega$ SST turbulence, pressure-based steady solver, mesh sensitivity, skewness & orthogonal quality |
| Fluid-Structure Interaction | ANSYS Mechanical + Fluent | FSI coupling, modal analysis, stress / strain field extraction |
| Aerodynamics | MATLAB / wind tunnel | Lift / drag polars, boundary layer separation, stall onset |
| Numerical Methods | MATLAB / GNU Octave | FDM (FTCS, explicit), von Neumann stability, convergence analysis |
| CAD & Design | SolidWorks, ANSYS DesignModeler, SpaceClaim | Aerodynamic surfacing, mechanical layout, geometry clean-up |

### Aerospace Systems & Policy
| Domain | Methods |
|---|---|
| Aircraft Conceptual Design | Wing loading, thrust-to-weight, stability derivatives, vertical tail volume |
| Energy Systems Modelling | HRES scenario analysis, carbon reduction trajectories, DSR battery buffering |
| Regulatory & Policy Modelling | UK electricity market reform, Net-Zero pathway analysis, grid resilience metrics |

---

## Toolchain

<p>
  <img alt="MATLAB" src="https://img.shields.io/badge/MATLAB-Orange?logo=mathworks&logoColor=white" />
  <img alt="GNU Octave" src="https://img.shields.io/badge/GNU%20Octave-0790C0?logo=octave&logoColor=white" />
  <img alt="ANSYS Fluent" src="https://img.shields.io/badge/ANSYS%20Fluent-FFB71B?logo=ansys&logoColor=black" />
  <img alt="ANSYS Mechanical" src="https://img.shields.io/badge/ANSYS%20Mechanical-FFB71B?logo=ansys&logoColor=black" />
  <img alt="SolidWorks" src="https://img.shields.io/badge/SolidWorks-DA1F26?logo=solidworks&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
  <img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white" />
</p>

---

<div align="center">

<sub>University engineering portfolio · Aerospace Engineering · MATLAB / Octave / ANSYS Fluent / SolidWorks</sub>

</div>
