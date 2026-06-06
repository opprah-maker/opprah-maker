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

## University Engineering Portfolio

Six projects covering CFD, aerodynamics, numerical methods, aircraft sizing, and energy
policy modelling.

### Computational Fluid Dynamics

#### [Aircraft-Aerodynamics-Design](https://github.com/opprah-maker/Aircraft-Aerodynamics-Design)
Combined project: experimental aerodynamics of the NACA 0012 aerofoil plus the conceptual
sizing of a heavy-lift transport aircraft. Wind-tunnel data ($C_L$, $C_D$ at $-2^\\circ$ to
$35^\\circ$), lift / drag polars, $(L/D)_\\text{max} \\approx 5.12$ at $\\alpha = 4^\\circ$,
stall onset at $\\alpha \\approx 16^\\circ$, plus the aircraft sizing loop
($W/S = 10{,}980\\,\\text{N/m}^2$, $T/W = 0.30$, $C_{n_\\beta} > 0.004$).

| `aerodynamics` `aircraft-design` | `aircraft-sizing` `directional-stability` | `matlab` `naca-0012` `wind-tunnel-testing` |

#### [CFD-Axial-Flow-Fan-Analysis](https://github.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis)
Individual project: CFD and FSI simulation of a computer cooling axial-flow fan. Standard
$k-\\epsilon$ turbulence model, pressure-based steady solver, unstructured tetrahedral mesh
(7,805 elements, 4,085 nodes, skewness $< 0.1$, orthogonal quality $> 0.95$). Optimal blade
installation angle $30^\\circ$, tip clearance $< 0.1D$, $+2.1\\%$ efficiency over baseline,
validated against wind tunnel data within $\\pm 3\\%$.

| `cfd` `ansys-fluent` `fsi` | `axial-fan` `fluid-dynamics` | `finite-element-analysis` `turbulence-modelling` |

#### [Bellmouth-Inlet-CFD-Gas-Turbine](https://github.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine)
CFD optimisation of an elliptical bellmouth inlet for a gas turbine engine. Mass flow rate
$\\dot{m} = 1.0\\,\\text{kg/s}$, total-pressure recovery $\\eta_p > 0.99$. Validated using the
von K\\&aacute;rm\\&aacute;n integral boundary layer method for adverse pressure gradient flows.
Five Fluent contour plots (static, dynamic, total pressure, velocity, wall shear).

| `cfd` `ansys-fluent` | `bellmouth-inlet` `gas-turbine` | `aerospace-engineering` `boundary-layer` |

### Numerical Methods

#### [Heat-Conduction-FDM-Analysis](https://github.com/opprah-maker/Heat-Conduction-FDM-Analysis)
Transient 2D heat conduction on a square plate solved with the explicit FTCS Finite
Difference Method in MATLAB. Validated against the von Neumann stability criterion
$\\Delta t \\le h^2/(4\\alpha)$. Discretisation:

$$\\frac{T_{i,j}^{n+1} - T_{i,j}^{n}}{\\Delta t} = \\alpha \\left[\\frac{T_{i+1,j}^{n} - 2T_{i,j}^{n} + T_{i-1,j}^{n}}{h^2} + \\frac{T_{i,j+1}^{n} - 2T_{i,j}^{n} + T_{i,j-1}^{n}}{h^2}\\right]$$

| `finite-difference-method` `numerical-methods` | `heat-conduction` `ftcs-scheme` | `matlab` `pde-solver` `von-neumann-stability` |

### Energy &amp; Policy Modelling

#### [UK-Energy-Market-Sustainable-Reform](https://github.com/opprah-maker/UK-Energy-Market-Sustainable-Reform)
MATLAB scenario modelling of the UK electricity market reform towards Net-Zero. Compares
Baseline, Renewable Incentivisation, and Demand-Side Response (DSR) battery buffering
scenarios. Models an $83.3\\%$ carbon reduction trajectory and a $125\\%$ gain in grid
resilience via DSR.

| `energy-modelling` `matlab` | `renewable-energy` `grid-resilience` | `policy-modelling` `net-zero` |

---

## Core Competencies

### Engineering Simulation &amp; CFD
| Domain | Tools | Methods |
|---|---|---|
| Computational Fluid Dynamics | ANSYS Fluent / Mechanical | $k$-$\\epsilon$ turbulence, pressure-based steady solver, mesh sensitivity, skewness &amp; orthogonal quality |
| Fluid-Structure Interaction | ANSYS Mechanical + Fluent | FSI coupling, modal analysis, stress / strain field extraction |
| Aerodynamics | MATLAB / wind tunnel | Lift / drag polars, boundary layer separation, stall onset |
| Numerical Methods | MATLAB / GNU Octave | FDM (FTCS, explicit), von Neumann stability, convergence analysis |
| CAD &amp; Design | SolidWorks, ANSYS DesignModeler, SpaceClaim | Aerodynamic surfacing, mechanical layout, geometry clean-up |

### Aerospace Systems &amp; Policy
| Domain | Methods |
|---|---|
| Aircraft Conceptual Design | Wing loading, thrust-to-weight, stability derivatives, vertical tail volume |
| Energy Systems Modelling | HRES scenario analysis, carbon reduction trajectories, DSR battery buffering |
| Regulatory &amp; Policy Modelling | UK electricity market reform, Net-Zero pathway analysis, grid resilience metrics |

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

<sub>University engineering portfolio &middot; Aerospace Engineering &middot; MATLAB / Octave / ANSYS Fluent / SolidWorks</sub>

</div>
