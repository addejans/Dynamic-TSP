# Solving the Dynamic Travelling Salesman Problem (DTSP) via Ant Colony Optimization  _(June 2018)_

### Description
An abundance of literature on vehicle routing problems is available.  Most of the known work deals with static problems, where all data are known in advance (i.e. before the optimization has started). However, in practice, not all data is known in advance, or data changes as applicable to the situation.  In vehicle routing, orders may be received as time progresses and must be dynamically incorporated into the routes.

In this project, I give a full **Python** implementation to quickly optimize the Dynamic Travelling Salesman Problem (DTSP)  by using Ant Colony Systems.  The idea is to use the original route to quickly build a new route for the added nodes without restarting the optimization process.  There is a clear advantage when compared to linear programming when the amount of nodes is large and similarly runtime.

### Visualizations
The next two images show what happens when we add another stop to the problem (_in this example, we add the "Factory"_).
![First Solve](https://github.com/addejans/Dynamic-TSP/blob/master/Screenshots/Ant%20Colony%20System_tour-test1-1.png)

![Second Solve](https://github.com/addejans/Dynamic-TSP/blob/master/Screenshots/Ant%20Colony%20System_tour-test1-2.png)
