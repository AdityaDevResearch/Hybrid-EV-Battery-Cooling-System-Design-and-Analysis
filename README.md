# Hybrid PCM–Liquid Cooling System for EV Battery Packs
### Computational and Experimental Study using SolidWorks, ANSYS Fluent, and Physical Prototyping

## Overview
This project presents the design, simulation, and validation of a hybrid battery thermal management system integrating Phase Change Material (PCM) with serpentine liquid cooling for cylindrical Li-ion battery modules. The work addresses thermal challenges in high-temperature regions, particularly Indian climates where ambient temperatures exceed 45°C.

The hybrid architecture combines RT44 paraffin-based PCM with Tesla-inspired serpentine liquid cooling. Using SolidWorks for CAD development, ANSYS Fluent for CFD simulation, and a physical prototype for demonstration, the project evaluates PCM cooling, liquid cooling, and their combined performance.

---

## Objectives
- Develop a hybrid PCM–liquid cooling thermal management system for EV battery packs.  
- Simulate and compare PCM and liquid-cooling methods under high load.  
- Analyse thermal stability, temperature uniformity, and peak temperature control.  
- Build a physical prototype to validate cooling behaviour.  
- Propose a scalable, cost-effective cooling solution for Indian EV applications.

---

## Background
Li-ion batteries exhibit accelerated degradation above 40°C. Traditional cooling systems (air/liquid) often struggle during fast charging, high-load operation, and extreme ambient conditions.  
PCM provides passive thermal buffering through latent heat absorption but lacks continuous heat rejection.  
Liquid cooling is effective but complex and expansive.  
The hybrid PCM–liquid model combines the strengths of both systems.

RT44 PCM was selected for its melting range (41–44°C), high latent heat capacity, stability, and compatibility with automotive materials.

---

## System Architecture

### CAD Development
- Developed full 3D battery module using SolidWorks.
- Model includes nine 18650 cylindrical cells in a 3S3P arrangement.
- Tesla-style serpentine aluminium cooling pipe designed for uniform coolant flow.
- PCM enclosure includes copper heat-spreader rods for enhanced conduction.
- Assembly exported to ANSYS Fluent.

### PCM Model
- PCM domain encapsulates battery cells.
- Copper rods serve as passive heat spreaders.
- Aluminium enclosure supports conduction and structural rigidity.

---

## Simulation Methodology (ANSYS Fluent)

### Geometry and Meshing
- Tetrahedral mesh with curvature-based refinement.
- High-resolution mesh near serpentine channels and battery walls.
- Clean solid–fluid domain separation for conjugate heat transfer.
- Mesh quality validated using skewness and aspect-ratio metrics.

### Liquid Cooling Setup
- Coolant: Water at 23°C inlet temperature.
- Inlet velocity: 2 m/s.
- Turbulence model: k–ε with enhanced wall treatment.
- Battery surfaces maintained at a representative 50°C load.
- Transient simulation for 300 seconds.

### PCM Simulation Setup
- RT44 PCM defined using the enthalpy–porosity phase change model.
- Solidus: 40°C, Liquidus: 44°C, latent heat: 250 kJ/kg.
- Temperature-dependent density, heat capacity, and viscosity.
- Gravity used to capture buoyancy-driven motion in melted PCM.

---

## Results

### PCM Cooling Performance
- PCM absorbed heat through latent fusion, holding boundary temperature near 308 K.
- Demonstrated stable thermal plateau during melting.
- No rapid temperature rise during simulation.

### Liquid Cooling Performance
- Initial temperature drop observed due to coolant entry.
- Gradual temperature increase due to continuous heat load.
- No passive stabilization or plateau observed.

### Comparative Analysis
- PCM provided strong temperature stability and uniformity.
- Liquid cooling removed heat quickly but produced rising temperature trends.
- Hybrid PCM–liquid design optimizes both continuous and peak-load cooling.

---

## Physical Prototype

### Construction
- Steel enclosure drilled to integrate copper cooling pipes.
- Two pipe diameters used: 3.0 mm (main channels) and 2.0–2.1 mm (bends).
- Nine 18650 cells arranged in 3S3P.
- PCM (paraffin wax) melted and cast around the assembly.

### Behaviour
- Heating load increased temperature until PCM melting point.
- PCM absorbed heat and reduced the temperature rise rate.
- Water flowed through copper channels to extract heat and re-solidify PCM.
- Prototype performance aligned with simulated trends.

---

## Cost Analysis

### Tesla-Style Liquid Cooling (Reference)
- ₹1.25–1.70 lakh per module.
- Requires precision-machined aluminium ribbons and high-pressure pumps.

### Proposed Hybrid PCM–Liquid Cooling
- ₹30,000–45,000 per module.
- Uses low-cost PCM and simple copper micro-tube channel.
- Reduces manufacturing cost by approximately 65–75%.

---

## Conclusion
The hybrid PCM–liquid cooling system significantly enhances temperature stability, reduces peak temperature rise, and improves safety of Li-ion battery modules under harsh thermal conditions. RT44 PCM effectively buffers heat spikes while serpentine liquid cooling supports continuous heat rejection. This configuration is suitable for Indian climates and can be manufactured cost-effectively at scale.

---

## Future Scope
- Development of PCM composites using graphene or carbon nanotubes for higher conductivity.  
- Multilayer PCM structures for fast-charging scenarios.  
- AI-enhanced thermal control using real-time sensor feedback.  
- Full-scale pack testing and long-term cycling studies.  
- Integration with EV drive-unit cooling systems.  
- Exploration of bio-based PCM for sustainability.

---


