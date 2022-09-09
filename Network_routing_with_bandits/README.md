# Network routing with multi-armed bandit algorithms

In this Project I've used Bandit Algorithms to solve the Problem of Routing for the graph below:  
  
![Network Graph](Network.jpg "Network Graph")

  
## Algorithms:  
For solving this task I've used different algorithms for multi-armed bandit problems like UCB and Epsilon-Greedy. each route in the network is considered an arm for a multi-armed bandit and each arm has its own stochastic reward due to the delays that may occur during the route.


## Results
Below you can see the average reward for the epsilon greedy algorithm and the percentage of optimal action selection for UCB and epsilon greedy algorithms:  

- the average reward for epsilon greedy algorithm  
  
![average reward for epsilon greedy](average_reward_epsilon.jpg "average reward for epsilon greedy")


- the percentage of optimal action selection for UCB and epsilon greedy  
  
![Optimal action selection](optimal_action.jpg "Optimal action selection")



