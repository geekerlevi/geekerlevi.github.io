---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 😸 About Me

I am currently a graduate student studying Electrical Engineering in University of Southern California, Los Angeles, United States.


My research interest includes: 
- System Identification (SysID)
- Model Predictive Control (MPC)
- Linear Control
- Nonlinear Control
- Robotics Control



# 🎓 Educations 
- *2024.08 - 2026.05*, Masters of Science (MS) in Electrical Engineering, <a href="https://minghsiehece.usc.edu/"><img class="svg" src="/images/USC-Viterbi.svg" width="23pt"></a> Ming Hsieh Department of Electrical and Computer Engineering, University of Southern California, Los Angeles, United States 

- *2021.09 - 2024.06*,Bachelors of Engineering (BEng Honors) in Electrical and Electronic Engineering, <a href="https://www.eee.manchester.ac.uk/"><img class="svg" src="/images/university-of-manchester.svg" width="20pt"></a> Department of Electrical and Electronic Engineering, the University of Manchester, Manchester, United Kingdom 
 

# 🛠 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2022</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Yuhua Li`, Abdulrahman AlMashaan, Sariaj Patil
- Supervisor: Dr. Jay H. Lee at USC  
- *2025 Jun - 2025 Aug*, Model Predictive Control and Reinforcement Learning
  - Implemented system identification techniques and Kalman filtering for accurate state estimation in multivariable systems, integrating noise modeling and parameter tuning for enhanced robustness.
  - Developed and applied LQR and MPC algorithms for constrained multivariable control problems, incorporating cost function optimization, horizon tuning and stability analysis.
  - Designed data-driven control strategies, leveraging real-time and historical data, feature extraction, and system modeling to optimize performance under operational and safety constraints.
  - Applied control algorithms to a DAC unit, forecasting temperature and humidity using autoregressive models and Kalman predictors, enabling dynamic regulation of environment parameters.
  - Validated control strategies through simulation and HIL testing, ensuring process efficiency, system stability and scalability for industrial deployment.
</div>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sens. Actuators Phys. 2021</div><img src='images/sna2021.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Yuhua Li`, Yancong Deng
- A Study on Task Offloading and Service Caching Integration in Edge-Cloud Collaborative Systems
- Journal of Advances in Information Technology 16(6):801-808, DOI:10.12720/jait.16.6.801-808
[[Preview]](https://github.com/geekerlevi/geekerlevi.github.io/blob/main/pdf/JAIT-V16N6-801.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2022</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Yuhua Li`
- Optimal Algorithm Comparison in Frequency Allocation -IFR, Water Falling and FLG  
- Proceedings Volume 12332, International Conference on Intelligent Systems, Communications, and Computer Networks (ISCCN 2022); 123321L (2022) https://doi.org/10.1117/12.2652526
[[Preview]](https://github.com/geekerlevi/geekerlevi.github.io/blob/main/pdf/Optimal.pdf) 

</div>
</div>


# 💬 Conferences

- The 2024 International Conference on Cloud Computing and Big Data (ICCBD 2024), Dali, China
- International Conference on Intelligent Systems, Communications, and Computer Networks (ISCCN 2022), 2022, Chengdu, China



# 🏭 Internships
- *2025 Aug - 2025 Sep*, Siemens AG, Los Angeles, United States
  - *Technical Assistant – PLC & Smart Infrastructure*
  - Industrial Automation & PLC Programming: Developed and deployed Siemens S7-1200/1500 PLC programs (LAD/SCL), including self-holding and interlock control logic. Independently designed, tested and debugged motor start-stop control systems, integrating safety interlocks and fault diagnostics to enhance system reliability.
  - Energy Management & Optimization: Implemented Siemens three-layer energy management system (field, production, management levels) for real-world projects. Configured energy monitoring systems, conducted KPI-driven energy audit, and executed peak load shaving strategies that reduced energy costs. Designed retrofit solutions for small-to-medium factories, achieving measurable efficiency improvements.
  - Digital Twin & Intelligent Control: Built proof- of -concept digital twin models covering product, production, and performance layers. Simulated EV manufacturing process to optimize energy flow, predictive maintenance, and production scheduling. Applied intelligent control algorithms to integrate building automation with E-mobility infrastructure, enabling energy-efficient charging and smart grid combability.
  - Smart Infrastructure: Developed smart building integration strategies using IOT-enabled energy meter, demand response algorithms, and MPC to balance charging infrastructure with building loads. Proposed cyber-physical solutions that reduced peak demand, improved energy efficiency, and advanced green mobility initiatives.


- *2025 Jun - 2025 Aug*, Shanghai ZAFEN Automotive Systems Co., Ltd., Shanghai, China.
  - *System Developer Intern in R&D Department*
  - Engine Simulation Sound System: Designed and debugged embedded control modules for real-time engine sound simulation for the AUDI -E5 Sportback model. Developed signal processing algorithms to generate realistic engine tones, optimized system latency and audio fidelity, and conducted to end-to-end HIL testing. Supported full system integration and testing, leading to successful Audi acceptance of the sound system.
  - Active Noise Control (ANC) System for FAW Heavy Trucks: Implemented embedded ANC algorithms, including adaptive filtering and real-time sensor data fusion, to reduce cabin noise. Performed system parameter acquisition, tuning and validation. Assisted in preparing and presenting a working ANC demo, which received high recognition from customers.
  - Automotive Electronic & System Integration: Participated in ECU-level integration, sensor interface testing, and hardware-software co-design. Applied control strategies and signal processing techniques to achieve stable, high- performance automotive electronic systems.

- *2024 Jun - 2024 Aug*, Hoyu-Zephon UAV Technology (Shanghai) Co., Ltd., Shanghai, China.
  - *Hardware Engineer Intern in R&D Department*
  - Embedded System development: Developed embedded modules for UAV flight control systems. Implemented real-time sensor data acquisition and processing routines, optimizing communication between IMU, magnetometer and barometer sensors to ensure stability and accuracy. Optimize communication between sensors and MCU via SPI/I 2 C protocols to reduce latency and ensure operation. 
  - Hardware Design & Signal Processing: Assisted in PCB layout and design of power management modules, focusing on minimizing noise, voltage ripples, and electromagnetic interference. Conducted signal integrity analysis using oscilloscopes and vector network analyzers, optimized trace routing, decoupling capacitor placement, and grounding strategies to ensure high-fidelity signal transmission. 
  - System Integration & Performance Optimization: Conducted end-to-end testing of propulsion system (ESCs, motors, batteries), collected performance and power consumption data, and proposed component selection and configuration improvements to enhance system efficiency. 
  - Prototype Assembly & Integration: Participated in prototype UAV assembly, including harness soldering, connector installations, and pre-power checks. Ensured robust hardware integration and operational readiness, demonstrating strong hands-on skills and engineering discipline.


- *2022 Jun - 2022 Jul*, Advanced Micro Devices, Inc. (AMD), Manchester, United Kingdom.
  - *Assistant of R&D Center-CPU*
  - CPU Architecture & Embedded systems: Analyzed CPU microarchitecture, including pipeline, cache hierarchy, memory controllers, and data interfaces (PCIe, DDR). Studied hardware-software co-design and OS-hardware interaction mechanisms to understand embedded system integration and performance optimization.
  - Hardware design & Circuit Analysis: Developed and interpreted PCB schematic diagrams and circuit layout of CPU modules. Conducted signal path analysis, power distribution evaluation, and interface verification, building a solid foundation in standard circuit design and hardware debugging. 
  - System Operation & Programming: Implemented small-scale tests and simulations using C7C++ and assembly to validate CPU operation modes and peripheral communication. Investigated OS-level interactions with CPU registers and memory mapping to support future design improvements.


  
