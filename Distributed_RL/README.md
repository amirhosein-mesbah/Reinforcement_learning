# Multi‑Agent Distributed Reinforcement Leanrning for grid Environment
In this project, I've Implemented a grid environemnt with 2 agents and 2 goal states. The agents have to learn to reach the goal states with recieving the maximum reward and avoiding obstackles.
The environement is shown below  
  
![Environment](Environment.jpg "Environment")
  
Elements of Environment:
- Agents: Blue Squares
- Obstackles: Red Squares
- Goal States: Green Squares

## Training
After training each agent lonely with sarsa algorithm, I implemented several distributed algorithms like:
- Distributed On-Policy algorithm like SARSA
- Min-Max Q-Learning
- Belief Based Algorithm 
- Distributed Actor-Critic

## Results
Average Reward during the learning episodes for SARSA, Min-Max Q-Learning and Belief-Based learning is shown at Below:
  
- Average Reward during the learning episodes for SARSA  
  
![Average reward for SARSA](sarsa.jpg "Average reward for SARSA")
  
- Average Reward during the learning episodes for SARSA  
  
![Average reward for Distributed SARSA](OnPolicy_distributed.jpg "Average reward for Distributed SARSA")
  
- Average Reward during the learning episodes for Min-Max Q-Learning  
  
![Average reward for Min-Max Q-Learning ](MIn-Max.jpg "Average reward for Min-Max Q-Learning ")
  
- Average Reward during the learning episodes for Belief Based Algorithms  
  
![Average reward for Belief Based Algorithms ](Belief-Based.jpg "Average reward for Belief Based Algorithms ")

  
  
