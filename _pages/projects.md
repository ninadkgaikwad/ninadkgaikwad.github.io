---
permalink: /projects/
hidden: false
  
feature_row:

  - image_path: /assets/images/nkg-projects-page-ICNB.jpg
    alt: "Building Controls"
    title: "Intelligent Control of Networked Buildings"
    excerpt: "The project involves developing and comparing computationally inexpensive black/grey-box developing models (neural network architectures and Bayesian estimation methods) for residential/commercial buildings where data comes from EnergyPlus and other open-source building data repositories like PecanStreet. Then a simulation framework has to be developed to co-simulate these building models at scale with OpenDSS (along with HELICS) to aid the development of both single-building and aggregator-level intelligent controllers which can optimize the energy consumption of buildings for grid support. Currently, we are pursuing model estimation and development of the co-simulation platform."
    url: "https://github.com/ninadkgaikwad/IntelligentControlOfNetworkedBuildings"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    
  - image_path: /assets/images/nkg-projects-page-PowerEdu.jpg
    alt: "PowerEdu.jl"
    title: "Power Systems Analysis Toolbox (PowerEdu.jl)"
    excerpt: "Course project for Analysis of Power Systems (EE521). A Julia-based package is being developed to perform Newton-Raphson-based power flow, continuation power flow, power system static state estimation, and basic power system optimization. Currently, power system stability analysis and transient simulation capabilities (EE523) are being implemented."
    url: "https://github.com/ninadkgaikwad/PowerEdu"
    btn_class: "btn--primary"
    btn_label: "Learn more"    
  
  - image_path: /assets/images/nkg-projects-page-HEMS.jpg
    alt: "Energy Resiliency"
    title: "Home Energy Resiliency"
    excerpt: "Where during grid outage scenario smart houses with PV, Battery storage, EVs and smart loads will be capable of managing their energy based on optimal control and reinforcement learning. MPC and RL-based central controllers for a single house have been developed. Currently work on centralized and distributed architectures based on MPC and RL for energy resiliency of community of houses is being pursued."
    url: "https://github.com/ninadkgaikwad/EnergyResiliency_SmartCommunity_MPC_RL"
    btn_class: "btn--primary"
    btn_label: "Learn more"

  - image_path: /assets/images/nkg-projects-page-SWEEFA.jpg
    alt: "Energy Forecasting"
    title: "Forecasting of Solar & Wind Energy"
    excerpt: "Master’s Thesis project, in which an entire software for solar and wind energy estimation and forecasting was created in MATLAB using GUI. The software can generate plant-level energy estimation capability for both wind and solar generation plants. The software also has a weather and generation data preprocessing system. Forecasting using ANN and ARIMA can be done using their respective GUI interfaces. Forecasting using WRF (NWP model) is also automated by developing BASH Shell scripts and running it on a cluster of four RaspberryPi-2 micro-computers."
    url: "https://github.com/ninadkgaikwad/SWEEFA_Development"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---

{% include feature_row %}
