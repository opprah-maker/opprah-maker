# Opprah Maker
### Quantitative Engineering Researcher & Aerospace Systems Analyst

Quantitative engineering researcher focusing on Computational Fluid Dynamics (CFD), Fluid-Structure Interaction (FSI), transient thermal modeling, and aerospace systems design. Experienced in modeling and validating aerodynamic, structural, and energy market systems using MATLAB/Octave, ANSYS Fluent/Mechanical, and Solidworks.

---

## 🛠️ Tech Stack & Technical Competencies
* **Simulation & CFD**: ANSYS Fluent (rotating machinery, internal flows), ANSYS Mechanical (FEA, modal analysis), FSI Coupling.
* **Programming & Numerical Methods**: MATLAB / GNU Octave (numerical analysis, FDM explicit FTCS solvers, scenario simulation).
* **CAD & Design**: Solidworks (aerodynamic surfacing, mechanical layout), ANSYS Design Modeler, SpaceClaim.
* **Aerodynamics**: Wind tunnel testing, airfoil coefficient validation, boundary layer separation studies.

---

## 📁 Research & Project Portfolio

### 1. Computational Fluid Dynamics & Fluid-Structure Interaction (CFD / FSI)

#### **[CFD-Axial-Flow-Fan-Analysis](https://github.com/opprah-maker/CFD-Axial-Flow-Fan-Analysis)**
* **Description**: Numerical CFD & FSI analysis of computer cooling fans. Optimizes blade installation angles ($30^\circ$) and tip clearance ($\le 1.5\text{ mm}$ for $2.1\%$ efficiency gain).
* **Numerical Details**: Unstructured mesh (7,805 elements, 4,085 nodes, Skewness $< 0.1$, Orthogonal quality $> 95\%$). Solves standard $k-\epsilon$ turbulence equations with pressure-based steady solver.
* **Validation**: Excellent agreement with wind tunnel experimental data within **$\pm 3\%$**.

#### **[Bellmouth-Inlet-CFD-Gas-Turbine](https://github.com/opprah-maker/Bellmouth-Inlet-CFD-Gas-Turbine)**
* **Description**: Design and optimization of an elliptical bellmouth inlet to minimize inlet pressure loss and maximize mass flow rate ($\dot{m} = 1.0\text{ kg/s}$).
* **Numerical Details**: Viscous Standard $k-\epsilon$ turbulence model solved in ANSYS Fluent to analyze static, dynamic, and total pressure distributions and wall shear stress contours.

---

### 2. Numerical Simulation & Heat Transfer

#### **[Heat-Conduction-FDM-Analysis](https://github.com/opprah-maker/Heat-Conduction-FDM-Analysis)**
* **Description**: 2D transient thermal conduction solver built from scratch in MATLAB/Octave.
* **Mathematical Scheme**: Discretized using the Forward-Time Central-Space (FTCS) explicit Finite Difference Method (FDM) governed by:
  $$T_{i,j}^{n+1} = T_{i,j}^n + \alpha \Delta t \left[ \frac{T_{i+1,j}^n - 2T_{i,j}^n + T_{i-1,j}^n}{\Delta x^2} + \frac{T_{i,j+1}^n - 2T_{i,j}^n + T_{i,j-1}^n}{\Delta y^2} \right]$$
* **Stability Limits**: Sized and validated to respect the von Neumann stability limit:
  $$\Delta t \le \frac{\min(\Delta x, \Delta y)^2}{4\alpha} = 0.25\text{ s}$$

---

### 3. Aerodynamics & Sizing Analysis

#### **[NACA-0012-Aerodynamics-Wind-Tunnel](https://github.com/opprah-maker/NACA-0012-Aerodynamics-Wind-Tunnel)**
* **Description**: Experimental wind tunnel data processing and analytical comparison against theoretical lift/drag models.
* **Parameters**: Evaluates pressure coefficients ($C_p$) around a circular cylinder and NACA 0012 lift-to-drag ($L/D$) curves across $\alpha \in [-2^\circ, 20^\circ]$.
* **Physical Insights**: Pinpoints peak aerodynamic efficiency ($L/D = 5.122$) at $\alpha = 4^\circ$ and aerodynamic stall at $\alpha = 16^\circ$.

#### **[Heavy-Lift-Aircraft-Design](https://github.com/opprah-maker/Heavy-Lift-Aircraft-Design)**
* **Description**: Sizing code and directional stability analysis of a heavy-lift cargo transport aircraft.
* **Mathematical Parameters**: Sized wing loading ($W/S = 10,980\text{ N/m}^2$) and thrust-to-weight ratio ($T/W = 0.30$) for heavy payload operations. Verifies directional yaw stability derivative $C_{n\beta} > 0.004$ via vertical tail stabilizer volume sizing.

---

### 4. Systems Sizing & Energy Modeling

#### **[UK-Energy-Market-Sustainable-Reform](https://github.com/opprah-maker/UK-Energy-Market-Sustainable-Reform)**
* **Description**: HRES (Hybrid Renewable Energy Systems) scenario modeling evaluating carbon emissions trajectories and consumer electricity cost indices.
* **Metrics**: Compares grid integration scenarios (Baseline vs Renewable Incentivisation vs Demand Side Response), modeling an $83.3\%$ carbon reduction and a $125\%$ gain in grid resilience via DSR battery buffering.
