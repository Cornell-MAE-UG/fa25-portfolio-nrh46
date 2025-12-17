---
layout: project
title: Turbine Blade Design
description: Advanced CAD Project
technologies: [Autodesk Fusion]
image: /assets/images/Blade-CAD.jpg
---

Project Overview:

For MAE 4272, Fluids and Heat Transfer Laboratory, my team of two others and I designed and tested a wind-turbine blade for a three blade horizontal axis turbine. The turbine was intended to operate in a controlled wind tunnel environment characterized by a Weibull wind speed distribution. From those parameters, our objective was to design a blade that could safely and efficiently extract power across the full range of probable wind speeds, rather than optimizing performance at a single operating point.

Design Process:

Our design process began by defining the turbine’s operating envelope using the prescribed Weibull wind speed distribution, as well as the laboratory air conditions, allowing us to identify the most probable flow conditions and design for performance across the full range. To enable quicker modeling and iteration, we adopted a set of simplifying aerodynamic and structural assumptions, including steady, incompressible flow, two-dimensional lift and drag behavior, and linear elastic blade bending with a fixed root. While these assumptions limited model fidelity, they allowed rapid comparison of candidate designs and informed early design decisions.

We then evaluated multiple low Reynolds-number airfoils and selected the E216 airfoil based on lift to drag ratio under expected operating conditions. Using a target tip speed ratio of five, supported by literature as efficient, we generated a spanwise pitch distribution to align each blade section with the airfoil’s optimal angle of attack. Finally, we performed a parametric optimization for chord length and taper ratio, computing aerodynamic loads, torque production, and structural limits for each configuration. Designs that exceeded allowable stress or torque production were discarded, and a high-performance set of configurations was identified. The final blade geometry was selected from this region to balance power production and safety for all operating conditions.

Test and Evaluation:

After fabrication via 3D printing, the blade set was experimentally evaluated in a wind tunnel using a torque brake to simulate the resistive load imposed by a turbine gearbox. Testing began at a wind speed approximately three standard deviations below the mean of the prescribed Weibull distribution. At each wind speed, the applied brake torque was increased incrementally while recording the turbine’s rotational speed and applied torque, continuing until the turbine stalled. The brake load was then reduced, the wind speed increased by one standard deviation, and the procedure repeated. This process was carried out across the full wind-speed distribution to capture performance over the turbine’s intended operating envelope.

The resulting data were used to generate power curves for multiple wind speeds, enabling evaluation of turbine efficiency as a function of operating condition. Efficiency was quantified using the coefficient of power, defined as the ratio of mechanical power produced by the turbine to the available power in the incoming airflow. The design was considered successful, as the peak coefficient of power occurred near the target tip-speed ratio of five, consistent with the design assumptions and optimization objectives.

![Graph of Coefficient of Power vs Tip Speed Ratio]({{ "/assets/images/TSR-vs-CP.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Graph of Power Produced vs Turbine RPM]({{ "/assets/images/Power-vs-RPM.jpg" | relative_url }}){: .inline-image-l}

My Role:

Throughout the project, I contributed across all phases of design, modeling, testing, and evaluation. Early in the project, I conducted a literature review on wind turbine aerodynamics and low Reynolds number blade design to inform initial design decisions. Based on these findings and team discussions, I developed an analytical model that iterated through internal force and stress calculations to identify safe design limits while maintaining sufficient lift for power generation.

I was then primarily responsible for designing the test plan, including the definition of performance and safety metrics used to evaluate the blades. Following testing, I led the analysis of experimental data and worked with the team to assess whether the final design met our efficiency and power generation objectives.