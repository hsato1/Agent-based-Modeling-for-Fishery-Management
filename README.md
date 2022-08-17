# Agent-based-Modeling-for-Fishery-Management
Submitted to Rollins College as 2021-22 academic year honor in major thesis

## Technical skills & concepts
- Agent-based modeling 
- NetLogo
- Python

## Summary
This agent-based modeling for fishery management through emergence, simulates spatial distribution dynamics of Atlantic Mackerel, and their migration movement based on real world environmental data such as sea surface temperature, sea surface velocity, and phytoplankton density which is a proxy for food availability. 

### - Why is this project important?/Why does this matter?

Fisheries in the United States contributes significantly to our economy by generating over 1.5 millon jobs. Fishery management agencies such as NOAA Fisheries conduct stock assessments to manage a good ecological balance and enforce restrictions to sustain good ecological balance and protect the ecosystem. Maintaining the good health of fishery is correlated to maintaining good economic balance. **Therefore conducting efficient stock assessments without permanently damaging the ecosystem is crucial for sustainability of environment and economy.**


### What is agent-based model?

An agent-based model (ABM) simulates a system which encapsulates unique, independent and autonomous
entities, and their interactions with each other and with their surrounding environment locally. Railsback and Grimm [3] list three important and unique properties of ABM.


1. **Local interaction**: Agents do not interact with all other agents only with neighbors that are geographically
close.

2. **Being Autonomous**: Agents act independently of each other to pursue their objectives
3. **Adaptive Behavior**: Agents are capable of adjusting their behavior to the current states of themselves,
of other agents, and of their environment

These three unique properties allowed us to model the spatial distribution of fish in response to the change in environmental drivers such as sea surface temperature, sea surface velocity and food availability for this project.  

### - How is this project different from previous work done by other researchers?

We begain our project by looking at recent ABM researches and projects. Especially we focused on *SEASIM*[2] to understand the approach to solve our problem.

*Boyd et al* [1] highlight that traditionally ecologists fit the available data into mathematical models to estimate the benchmarks that are
used to evaluate the current stock status. However, mathematical modeling is limited based on choice of the equations, complexity of problem. 

Moreover, recently researchers discovered that the available data is dependent on environmental components of the ecosystem such as food-web interaction and environmental drivers *SEASIM*[2]. Mathematical models cannot represent the interaction of individuals in the system, influence of environmental drivers.

In order to overcome these limitations and be capable of modeling spatial distribution of fish, we utilized **agent-based modeling**.

In addition to the choice of simulation framework, our model is unique in three different ways

  - **Use of python script and webscraping**: We used NetLogo's python script extension to dynamically scrape data from NOAA data servers based on user's input: simulation start date and end date. We processed the scrapped data into proper GIS format which NetLogo can understand and loaded the data onto the simulation framework. 
  - **Generalizing algorithm for fish movement**: *SEASIM*[2] implemented their movement algorithm by employing normal arrhenius function. We instead found generalized arrhenius function function to calculate fish movement with simplified parameters. 

### - What did we achieve?

- We achieved to generalize the algorithm with generalized arrhenius function 


### - What is next step?


## References (For this sumamry)


