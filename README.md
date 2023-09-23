# Q-learning__SARSA__SARSA(lambda)__Expected-SARSA
1. CliffWalking Environment: Implementing Q-learning algorithm in python in the CliffWalking environment with different parameter values.

* Implemented a Q-learning agent using a purely random behavior policy for the following learning rates α = [0.0005,0.005,0.01,0.07,0.1]. Studying the effect of α on Q-learning and demonstrating it using plots. Plotting the learning curve of the policies learnt in each case using episode vs. avg reward/episode.
* Implementing Q-Learning using the ϵ -Greedy behaviour policy with α = 0.0001 and ϵ = [0.95, 0.76, 0.55, 0.25, 0.1]. Studying the effect of ϵ on the performance of Q-Learning. Creating graphs of Epsilon with Average Q-values for start State(3,0), state(0,4), state (1,7) and state(2,9).
* Implementing Q-Learning using the  ϵ− Greedy behaviour policy where  ϵ  is reduced from 1 to 0.01 with increasing number of episodes. Plotting the learning curve of the policy being learnt using episode vs. avg reward/episode.

2. Lunar Lander Environment from OpenAI Gym: Implementing SARSA, SARSA(λ) Expected SARSA algorithm in python in the Lunar Lander environment with different parameter values.

* Considering Q<sub>0</sub> (s, a) = 0  ∀  (s,a),  ϵ=0.1  and  α  = 0.01 and implementing SARSA and Expected SARSA. Plotting the graphs for: episode vs. max-time step and episode vs. average-reward in each case.
* Experimenting with different  α  = [0.0005,0.005,0.01,0.1] and  ϵ  = [0.9, 0.5, 0.3, 0.1] combination for SARSA and Expected SARSA agents. Discussing how changing  α  and  ϵ  affect the agent’s learning performance.
* Implementing SARSA( λ ) with  λ=0.5  and the best combination of the  α  and  ϵ  values from the previous exercice. Comparing the performance of SARSA( λ ) with that of plain SARSA algorithm.
