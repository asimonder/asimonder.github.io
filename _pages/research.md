---
layout: page
title: Research
permalink: /research/
description: Current Research Focus
nav: true
nav_order: 4
display_categories: []
horizontal: false
---

<p style="text-align: center;">
  <img src="{{ '/assets/img/BlockThrustsWebPage2.jpg' | relative_url }}" alt="Research Thrusts" style="width: 65%; max-width: 800px;  min-width: 200px; height: auto;">
</p>

---

### **Offshore Wind Systems**

<div class="row">
  <div class="col-sm-5">
    <img src="{{ '/assets/img/WindFarmWSeaBed.jpg' | relative_url }}" alt="VOF-LES of a wind farm" class="img-fluid rounded">
  </div>
  <div class="col-sm-7">
    Our work in this area focuses on creating high-fidelity "digital twins" of offshore wind farms. We use large-eddy simulation (LES) coupled with a volume-of-fluid (VOF) method to capture the complex, unsteady interactions between the turbulent atmosphere, dynamic ocean waves, and the turbine structures. This aero-hydro coupled approach allows for the accurate prediction of turbine performance, wake effects, and structural loads, providing crucial data for improving the design and operational efficiency of offshore wind energy systems in Taiwan.
  </div>
</div>

---

### **Air-Sea Interactions**

<div class="row">
  <div class="col-sm-5">
    <img src="{{ '/assets/img/DNS_MABL.jpg' | relative_url }}" alt="DNS of air-sea interface" class="img-fluid rounded">
  </div>
  <div class="col-sm-7">
    This is the core of our research program. We use large-scale Direct Numerical Simulation (DNS) to generate "ground-truth" data of the turbulent air-sea boundary layer, unraveling the fundamental physics of momentum, heat, and gas exchange. The insights from these simulations are used to develop and validate a new generation of more accurate, physics-aware turbulence models and novel machine learning methods for two-phase flows.
  </div>
</div>

---

### **Regional Wind Planning**

<div class="row">
  <div class="col-sm-5">
    <img src="{{ '/assets/img/SAR_WindFarms.jpg' | relative_url }}" alt="Regional model grid over Taiwan" class="img-fluid rounded">
  </div>
  <div class="col-sm-7">
    We bridge the gap between our high-fidelity simulations and the regional-scale atmospheric models used for wind resource assessment. By analyzing data from our farm-scale LES and fundamental DNS, we develop new, physics-based "farm drag parameterizations" and "ocean drag models." These improved parameterizations are designed to be implemented in mesoscale models (like WRF) to more accurately predict the impact of large wind farm clusters on regional energy resources, a critical challenge for Taiwan's energy strategy.
  </div>
</div>


