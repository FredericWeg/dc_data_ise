Generic EMT Modeling of Data Center Load v0 (DC-EMTv0)

Example version: v0 (DC_EMTv0)
Authors: Xingyu Zhao, Yingyi Tang, and Junbo Zhao
Affiliation: Dartmouth College
Contact author: Xingyu Zhao
Contact email: xingyu.zhao.th@dartmouth.edu
PSCAD version: 5.0.2

Brief description

This example provides a modular EMT model of data center loads supplied by a
centralized UPS. It includes power electronic converters, IT workload profiles,
and motor-driven cooling loads. Average, switching, and reduced-order converter
models support studies of internal control interactions, data center-grid
coupling, and workload power propagation. Two cases demonstrate a complete data
center model and comparisons between modeling fidelity levels.

Special execution instructions

1. Open the DC_EMT_ws workspace in PSCAD 5.0.2. Ensure that the component
   library DC_EMT_lib.pslx is loaded with the example projects.

2. IMPORTANT: In each project's settings, go to:
   Project Settings > Runtime > Network Solution Accuracy
   Leave "Use ideal branches for resistances under" UNCHECKED.
   Apply this setting to both DC_EMT_demo and DC_EMT_compare, and to any
   new project using these library modules.

3. Build and run the desired example project:
   - DC_EMT_demo: Complete data center example using average converter models.
   - DC_EMT_compare: Comparison of model responses at different fidelity levels.

Repository
https://github.com/xingyuz-phd/Generic-EMT-Modeling-of-Data-Center-Load
