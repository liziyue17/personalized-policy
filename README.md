#### Learning to Personalize Treatments When Agents Are Strategic 

This repository contains Julia code for the simulation and empirical sections of my paper. The latest working paper version is [available here]() on ArXiv. 

The Julia package dependencies for the project are as follows: 

```
dependencies = ["Plots", "Random", "Distributions", "Optim", "RollingFunctions" ] 
```

They can be installed via `Pkg.add(dependencies)` 

```
julia sc_figure.jl
``` 
Runs the simulation and generates the figure and data for Table 1 and Figure 1. 
```
julia price_figure.jl
``` 
Runs the simulation and generates the figure and data for Table 2 and Figure 2. 
``` 
julia experiment_figure.jl
``` 
Loads the experiment data and generates the figure and data for Table 3 and Figure 3. 
