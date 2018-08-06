# TEMPO - Techno-Economic Mini-Grid Planning and Optimization
##  a flexible open-source modelling framework for evaluating hybrid mini-grid applicablity, costs and performance in variable contexts

#### Created by: 
### Energy Research Centre - University of Cape Town (ERC-UCT) and the South African National Energy Development Institute (SANEDI) - for - the South African Department of Science and Technology (DST)

##### Author: Gregory Ireland - ERC-UCT (Energy Systems, Economics and Policy group)
#### Submitted together in conjuction with dissertation report in partial fulfilment of the degree of:
## Master of Science in Sustainable Energy Engineering

<img src="http://imgur.com/VmLwNpP.png">

### Essential Core Mini-Grid Model Code and Visualisations:

1. Python & Cython Boilerplate Library Imports, Connection to Plotly Servers & Offline Jupyter Notebook Initialization</h4>
2. Solar Irradiation Data Capture with Transposition Model and Power Output Model
3. Windspeed timseries data capture and turbine curve application
4. Technology cost and performance data, Diesel Efficiency, and Demand Data file reads
5. Function Definition: Core Mini-Grid Operation (Compiled with Cython into C code for Efficiency, ~50x speedup vs pure Python)
6. Function Defintion: Particle Swarm Optimization (PSO) for Mini-Grid Component Sizing
7. Particle Swarm Optimization Run
8. Mini-Grid Operational Timeseries Visualization
9. Timespan Averaged Energy Mix Plotting (Monthly, Weekly, Daily, etc...)
10. Levelized Cost of Energy Component Decompoisiton
