# Hybrid-EV-Battery-Cooling-System-Design-and-Analysis
Hybrid PCM–water cooling for EV battery packs: integrates RT44 paraffin with a serpentine liquid-cooling layout (Tesla-inspired). ANSYS + SolidWorks simulations and a small prototype show reduced peak cell temperatures, improved uniformity, enhanced safety in hot climates, and lower manufacturing cost and is ideal for Indian summer conditions.
Hybrid PCM–Liquid Cooling System for EV Battery Packs
Computational and Experimental Study using SolidWorks, ANSYS Fluent, and Physical Prototyping
Overview
This project presents the design, simulation, and validation of a hybrid battery thermal management system that integrates Phase Change Material (PCM) with serpentine liquid cooling for cylindrical Li-ion battery packs. The work focuses on improving temperature uniformity, reducing thermal stress, and enhancing safety for electric vehicles operating in high-temperature environments, particularly Indian summer conditions where ambient temperatures exceed 45°C.
The system combines RT44 paraffin-based PCM with a Tesla-inspired serpentine liquid cooling layout. Using SolidWorks for CAD modelling, ANSYS Fluent for CFD analysis, and a physical demonstration prototype, the study evaluates liquid cooling, PCM cooling, and the combined hybrid architecture.
The proposed design delivers strong thermal buffering, lower peak temperatures, and improved cost-efficiency compared to traditional liquid-cooling systems.
Objectives
Develop a combined PCM–liquid cooling model for EV battery packs.
Evaluate performance under high ambient and high load thermal conditions.
Compare PCM cooling and liquid cooling using transient CFD.
Build a small-scale physical prototype to validate thermodynamic behaviour.
Propose a cost-effective thermal management solution suitable for mass-market EVs.
Background
EV batteries experience rapid performance degradation at temperatures above 40°C. Traditional cooling methods such as air and liquid systems often struggle to maintain safe operating temperatures under fast charging, high loads, and extreme climates.
Phase Change Materials offer passive thermal regulation by absorbing heat during their melting process. However, PCM alone cannot support long-duration heat removal. Combining PCM with liquid cooling enables continuous heat extraction while preserving passive thermal stability.
RT44 PCM was selected due to its suitable melting range (41–44°C), high latent heat, strong cycling durability, and compatibility with EV packaging materials.
System Architecture
CAD Development
Complete 3D modelling done in SolidWorks.
Battery module includes nine 18650 cylindrical cells (3S3P).
Tesla-style serpentine aluminium cooling channel modelled and adapted.
PCM enclosure includes copper heat-spreader rods placed at multiple heights for improved conduction.
Assembly exported to ANSYS for simulation.
PCM Model
PCM domain fully surrounds battery cells.
Copper rods enhance heat distribution within PCM.
Aluminium casing provides structural support and conduction paths.
Simulation Methodology (ANSYS Fluent)
Geometry and Meshing
Tetrahedral mesh with local refinement near battery walls, serpentine channels, and PCM regions.
Clean separation of solid and fluid domains for conjugate heat transfer.
Mesh quality validated using skewness and orthogonality checks.
Liquid Cooling Setup
Coolant: water at 23°C inlet temperature.
Inlet velocity: 2 m/s.
k–ε turbulence model with enhanced wall treatment.
Battery cell surfaces maintained at 50°C equivalent heat load.
Transient simulation for 300 seconds.
PCM Simulation Setup
RT44 properties defined using enthalpy–porosity phase change method.
Solidus: 40°C, liquidus: 44°C, latent heat: 250 kJ/kg.
Density, viscosity, and heat capacity defined as temperature-dependent.
Gravity enabled to capture buoyancy in melted PCM.
Results
PCM Cooling Performance
PCM absorbed heat through latent fusion, maintaining a stable plateau around 308 K.
Repeated melting–solidification cycles demonstrated strong thermal buffering.
No rapid temperature rise observed during entire transient window.
Liquid Cooling Performance
Liquid cooling initially reduced temperature rapidly.
Cell boundary temperature gradually increased over time due to continuous heat load.
Temperature did not stabilise within simulation domain, indicating reliance on flow rate and pump efficiency.
Comparative Summary
PCM maintained nearly constant cell boundary temperatures.
Liquid cooling removed heat quickly but lacked passive stability.
Hybrid PCM–liquid cooling is identified as the optimal solution for sustained thermal control, peak-load buffering, and cost reduction.
Physical Prototype
A small-scale demonstration model was developed to validate practical feasibility.
Construction
Steel enclosure with precision-drilled holes for copper channels.
Combination of 3.0 mm and 2.0–2.1 mm copper tubes soldered to form a continuous coolant path.
9× 18650 cells arranged in 3S3P configuration.
Paraffin-based PCM melted and poured to encapsulate the cells and tubes.
Experimental Behaviour
Under load, cell temperatures increased until PCM melting point.
PCM absorbed heat and slowed temperature rise.
Circulated water through copper channels extracted heat and re-solidified PCM.
Prototype confirmed the hybrid cooling behaviour observed in simulation.
Cost Analysis
Traditional Serpentine Liquid Cooling (Tesla-style)
Cost: ₹1.25–1.70 lakh per module
High machining requirements
Complex structural sealing
Heavy system architecture
Proposed Hybrid PCM–Liquid Cooling
Cost: ₹30,000–45,000 per module
Simplified copper micro-tube network
PCM is inexpensive and easy to integrate
Reduces cost by approximately 65–75 percent
Conclusion
The hybrid PCM–liquid cooling model demonstrates significant improvement in thermal stability, peak temperature reduction, and safety for cylindrical Li-ion EV batteries. RT44 PCM effectively buffers temperature spikes, while the serpentine liquid channel ensures continuous heat removal.
The design is highly suitable for Indian climatic conditions and offers a practical, scalable, and economically viable alternative to conventional EV cooling systems. The combination of simulation and prototype testing confirms that hybrid cooling can deliver long-term reliability and improved battery life.
Future Scope
Development of high-conductivity PCM composites using graphene or carbon nanotubes.
Multi-layer PCM structures for ultra-fast charging applications.
Intelligent thermal control using AI and real-time sensor integration.
Extended prototype testing with full-scale EV battery modules.
Use of bio-based PCM materials for sustainability.
Integration with motor and inverter thermal loops.
