---
title: "Research Activities on Transport Science (2016-2018, 2023-Present)"
excerpt: "Energy efficiency optimization and environmental impact assessment of construction vehicle operations. <br/><img src='https://beichuanh.github.io/beichuan/images/wheel_loader.png' style='width: 550px; height: auto;'>"
collection: portfolio
---

Research at KTH Transport Planning Division, the Department of Civil and Architectural Engineering
------

This study at KTH from 2016-2018 within the topic “Optimal Construction Operations” results in 2 journal and 4 conference papers. My work at the Transport Planning division, Department of Civil and Architectural Engineering involves the optimal control application on construction operations. The research activities involve:

* Motion planning for autonomous wheel loaders.
* Operational patterns and emission measurements of construction vehicles.
* Discrete-event simulation for optimizing construction operations.

### Motion planning for autonomous wheel loaders

The research investigates optimal control methods aimed at minimizing fuel consumption and emitted pollutants from the wheel loader during the loading process. The vehicle dynamic model an autonomous wheel loader has been established in Simulink / Simscape based on the measurement data. Then, control-oriented models of the tested wheel loaders are developed in Matlab and Python to integrate with optimization and control algorithm. The path planning has been conducted using optimal control theory and the control methods such as model predictive control, H-infinity.

<img src="https://beichuanh.github.io/beichuan/images/wl_1.png" alt="autonomous_driving" style='width: 650px; height: auto;'>

<span style="font-size: small;">Related publications: Path planning for wheel loaders: A discrete optimization approach, in 2017 IEEE 20th International Conference on Intelligent Transportation Systems (ITSC), IEEE, 2017, pp. 1–6, [10.1109/ITSC.2017.8317882](https://doi.org/10.1109/ITSC.2017.8317882).</span>
<span style="font-size: small;">Path optimization for a wheel loader considering construction site terrain, in 2018 IEEE Intelligent Vehicles Symposium (IV), IEEE, 2018, pp. 098–2103, [10.1109/IVS.2018.8500447](https://doi.org/10.1109/IVS.2018.8500447).</span>

### Data-driven emission modelling for construction vehicles

This research project also conducts in-lab test, real-world PMES measurement, and operational pattern analysis for non-road HD vehicles. Various operating patterns are systematically categorized and identified through the application of pattern recognition techniques employing support vector machine. In particular, the trasient and steady operating processes are identified by hidden Markov model. Emission models for construction vehicles were established, and the construction processes were evaluated in a discrete-event simulation and optimized by genetic algorithm.

Based on measurements conducted on construction vehicles and equipment, the study assesses the impacts of various operational processes under real-world operational conditions. 

<img src="https://beichuanh.github.io/beichuan/images/wl_2.png" alt="kalman" style='width: 650px; height: auto;'>
<img src="https://beichuanh.github.io/beichuan/images/wl_3.png" alt="linear_regression" style='width: 650px; height: auto;'>
<img src="https://beichuanh.github.io/beichuan/images/wl_4.png" alt="em" style='width: 650px; height: auto;'>

<span style="font-size: small;">Related publication: Modeling of dynamic NOx emission for nonroad machinery: A study on wheel loader using engine test data and on-board measurement, in Transportation Research Board (TRB) 95th Annual Meeting, Transportation Research Board (TRB), 2016. [TRB Link](https://trid.trb.org/view/1396449)</span>

### Discrete-event simulation for optimizing construction operations

A discrete-event simulation platform is developed, integrating the construction operations with the non-road emission model proposed in previous work. This platform aims to evaluate the energy consumption and emission levels of all equipment used during construction operations.

<img src="https://beichuanh.github.io/beichuan/images/wl_5.png" alt="location" style='width: 650px; height: auto;'>
<img src="https://beichuanh.github.io/beichuan/images/wl_6.png" alt="discrete_events" style='width: 550px; height: auto;'>

<span style="font-size: small;">Related publications: Related publication: quantification of emissions for non-road machinery in earthwork: Modeling and simulation approaches, in Transportation Research Board (TRB) 96th Annual Meeting, Transportation Research Board (TRB), 2017. [TRB Link](https://trid.trb.org/view/1438723)</span>
<span style="font-size: small;">Assessment of emissions and energy consumption for construction machinery in earthwork activities by incorporating real-world measurement and discrete-event simulation, Sustainability, 2022, [10.3390/su14095326](https://doi.org/10.3390/su14095326).</span>
