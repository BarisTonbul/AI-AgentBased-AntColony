# This is an Agent Based Modelling Project

## Main idea of this program is to simulate ants while they finding their way among food source and home.

Before get started make sure you have numpy, pandas, matplotlib and seaborn libraries in your python environment.
In case of you got error with importing pandas nowadays, use pip install numpy==1.19.3 because new version of pandas has some issues with the windows 10 and this can lead some problems.

## What is Ant Colony Optimization ?

- The principle of this project works with agent based modelling which follows the pathway of ants between home and food locations. 
- Ants realese pheromone to the ground while they are moving. Pheromone is a hormone that influences the decisions that ants make when they are deciding path which they will follow, also pheromone evaporates from the ground after it is realesed from the ant. 
- Since the pheromone on the short path will evaporate less than other routes(because the path is shorter there wont be enogh time for pheromone to evaporete quicly compared to the long path while they reach the food source), ants will prefer the path with a high pheromone level, and after a while, this will be the only way to be used at the end of a certain period, since more ants will use this path.

## How it works ?

- I created a random matrix between 5-100, Then create 20 agents. 
- I chose a true path to simulate the road between home and food.
- At the beginning ants makes first decisions randomly. After they reach the food, then pheromone is starting to influence the ants to make decisions in particular ratio.

