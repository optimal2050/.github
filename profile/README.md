Optimal 2050
================

A collection of open-source libraries and research frameworks designed to support energy system modeling, planning, analysis and optimization of long-term energy transition scenarios. It includes model generators, data processing tools, and visualization libraries that facilitate the development of energy system models and scenarios opmimized energy transition pathways.

## Core Projects

---

<img src="https://optimal2050.github.io/multimod/logo.png" alt="multimod logo" width="120" align="left" style="margin-right: 15px;"/> 


**[multimod](https://optimal2050.github.io/multimod/)**  
The `multimod` R package is an effort to bridge alternative mathematical modeling frameworks and languages, particularly those used in energy system modeling. It defines a domain-specific language (DSL) for representing mathematical programming models in a unified, abstract format. `multimod` currently supports partial parsing of models written in GAMS (General Algebraic Modeling System), and is being extended to JuMP (Julia), Pyomo (Python), and GMPL (GNU Math Programming Language). Parsed models in `multimod` format can be redered to LaTeX and other modeling languages. The package is designed to facilitate the exchange of mathematical models across different languages and solver frameworks, with the goal of simplifying the development, comparison, and reuse of complex optimization models in energy systems and beyond.

---

<img src="https://github.com/optimal2050/energyRt/blob/dev/docs/logo.png?raw=true" alt="energyRt logo" width="120" align="left" style="margin-right: 15px;"/>

  **[energyRt](https://github.com/optimal2050/energyRt)** 
  `energyRt` (*energy* system modeling *R-t*oolbox /ˈɛnərdʒi ɑrt/) is a
set of classes, methods, and functions that define a macro-language for
energy system modeling within the R environment. This package offers a
high-level, user-friendly interface that simplifies the development and
analysis of complex energy models. The package has been used—and shaped—by the development of several large-scale energy system models (including USENSYS, IDEEA, CEPRO - see below). It currently underway a major overhaul to integrate with `multimod` system and provide a more flexible and powerful modeling framework.

---

<img src="https://raw.githubusercontent.com/optimal2050/merra2ools/184fbee8869fbc7bdf93e1599d08f6a00bad0edc/man/figures/logo.png" alt="merra2ools logo" width="120" align="left" style="margin-right: 15px;"/>  

**[merra2ools](https://optimal2050.github.io/merra2ools/)**
 An R package and dataset for evaluating the potential output of variable energy resources (VER) — specifically wind and solar — globally, using over 40 years of hourly MERRA-2 reanalysis data. The dataset was assembled, and the package initially developed, to support the authors' internal and collaborative energy modeling studies, and is made available for public use. Further development will be guided by the needs of related research projects and contributions from the broader community.

---
<img src="https://raw.githubusercontent.com/optimal2050/energypal/refs/heads/main/docs/logo.png" alt="energypal logo" width="120" align="left" style="margin-right: 20px;"/> 

**[energypal](https://optimal2050.github.io/energypal/)** 
  Color palettes and styling tools for energy-related data visualization. (*placeholder*)
  The goal of the project is to assemble a curated collection of color palettes tailored for energy-related visualizations, ready to use with ggplot2 and other plotting frameworks. The palettes are inspired by — and occasionally shamelessly pirated from — publicly available visualizations used in major energy modeling projects and reports, with the goal of returning them to the public domain and promoting clarity, consistency, and visual appeal in energy system research and communication.

---

- **[globalwindatlas](https://optimal2050.github.io/globalwindatlas/index.html)** 
  Tools for accessing and processing high-resolution wind resource data from the Global Wind Atlas. 

---
- **[nrel.dev.api](https://optimal2050.github.io/nrel.dev.api/index.html)** 
  R functions for querying NREL developer APIs and processing renewable
  energy datasets.

------------------------------------------------------------------------

## Related Projects

<img src="https://raw.githubusercontent.com/usensys/usensys/63c64244dca05b32aed7c9062eba3e1dd3c87d22/docs/logo.svg" alt="multimod logo" width="140" align="left" style="margin-right: 10px;"/> 

**[usensys.org](https://www.usensys.org)**
*United States Energy System Optimization Model*
USENSYS is a linear programming optimization model for the United States energy system. It belongs to a class of models known as Macro Energy Models, also called Reference Energy System Models or Capacity Expansion Models (particularly in the context of the electric power sector). USENSYS optimizes the long-term development of the energy system considering alternative technological options, available resources, and policy options. Its primary objective is to determine the cost-optimal capacity expansion of technological chains while accounting for the current state of the system, resource- and policy-constraints.
  
---

<img src="https://github.com/ideea-model/IDEEA/blob/main/docs/logo.png?raw=true" alt="multimod logo" width="140" align="left" style="margin-right: 10px;"/> 

**[IDEEA](https://ideea-model.github.io/IDEEA/index.html)** 
*Indian Zero Carbon Energy Pathways (IDEEA)* is a collaborative open energy modeling initiative to develop tools and scenarios of India’s energy transition. The project aims evaluation a broad set of scenarios with high penetration of variable renewables and identify a set of most cost-efficient options of deep decarbonization and carbon neutrality for India for broad public discussion.  
  
---
<!-- <img src="https://avatars.githubusercontent.com/u/51479590?v=4" alt="multimod logo" width="130" align="left" style="margin-right: 25px;"/> 

**[opendecarbonization](https://github.com/opendecarbonization)** -->
...




------------------------------------------------------------------------

## Roadmap
We are currently working on the following projects and features:


## Contributing
We welcome contributions to all our projects! If you are interested in contributing, please check out the [contribution guidelines]
