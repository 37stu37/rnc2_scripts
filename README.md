![RNC2 project](https://github.com/37stu37/rnc2_scripts/blob/main/project%20image.png)

> Learn more about the [Resilience to Nature's Challenges National Science Challenge](https://resiliencechallenge.nz/).

---

## Table of Contents

- [Publications](#publications)
  - [Publication 1](#publication-1)
    - [Abstract 1](#abstract)
    - - [Authors](#authors)
    - [Scripts](#scripts)
    - [Data](#data)
  - [Publication 2](#publication-2)
    - [Abstract 2](#abstract)
    - [Authors](#authors)
    - [Scripts](#scripts)
    - [Data](#data)

---

## Publications

### Publication 1: Including Dynamics in a Network Based Stochastic Multi-Hazard Model

#### Abstract:
Network models have been proposed for cascades of natural hazard events, for example storm, flooded river, breached stop banks, damaged infrastructure. However, these have generally not taken time into account, with the cascade of events effectively assumed to occur instantaneously. We extend the methodology to account for multiple temporal processes, often occurring on quite different time scales. Further, since state of the art physical models generally involve heavy computation, we advocate the use of computationally simple probability distributions to describe the dynamics and interaction of the hazard events in our proposed network model. This enables a larger number of simulations of the model, ensuring greater accuracy of model forecasts. The modeling approach takes into account the dynamic and evolving nature of the temporal processes. By doing so, it may be possible to identify key elements of the system that are most vulnerable or critical, and thus develop strategies for mitigating risks, and examine restoration strategies in a dynamic hazard environment.

--

- **Authors**:
  - Mark Bebbington*
    - *Massey University, Palmerston North NZ*
    - *Corresponding author: [m.bebbington@massey.ac.nz](mailto:m.bebbington@massey.ac.nz)*
  - Alex Dunant
    - *University of Durham, Durham UK*
  - David Harte
    - *Statistics Research Associates, Wellington NZ*
  - Melody Whitehead
    - *Massey University, Palmerston North NZ*
  - Stuart Mead
    - *Massey University, Palmerston North NZ*
   
--

#### Scripts

##### Main Simulation Script

- [Main_sim.py](https://github.com/37stu37/rnc2_scripts/blob/main/scripts/Main_sim.py): This script is the main simulation script responsible for simulating the flow of water in a river catchment system. It includes functions for modeling catchment behavior and river flow.

##### River Flow Simulation Module

- [mod_river_flow.py](https://github.com/37stu37/rnc2_scripts/blob/main/scripts/mod_river_flow.py): This module contains functions for simulating the flow of water in a river network and visualizing the flow dynamics. It is used as part of the main simulation script.

##### Catchment Flow Simulation Module

- [mods_catchment_flow.py](https://github.com/37stu37/rnc2_scripts/blob/main/scripts/mods_catchment_flow.py): This module includes functions for generating daily rainfall amounts, simulating catchment reservoir flow, and managing the flow of water in catchment areas.

--

#### Data
The GIS input data required for the scripts are located in the [data](data) folder. This data includes geospatial information about catchments, river networks, and other relevant parameters necessary for the simulations.

------

### Publication 2: WIP 

- **Authors**:
  - Author 1
    - *Affiliation*
  - Author 2
    - *Affiliation*
  - Author 3
    - *Affiliation*

