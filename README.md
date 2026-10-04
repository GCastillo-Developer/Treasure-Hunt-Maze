# EmergingTrendsinCS

# Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
I programmed the agent to choose the best optimal path to the target in a maze. I was given the code where the maze is initalized, the pirate intelligent agent is resetted, the actions where the pirate is allowed to take and each reward and penalty with each move. Check the game status, observe the current state, and draw the maze with the best path taken. 

The game experience class keeps track of the episodes which the agent later learns through exploration. It holds the inputs and targets of each episode. 

I created a Deep-Q learning algorithm which consisted of a training loop, an epsilon-greedy strategy, win-rate calcuation and checking whether the game is over, and whether the agent has found the optimal path/epoch. The training loop chooses whether to choose the next action based on the epsilon value. The action is taken on the environment and the state, reward, and game status are recorded. The episode gets recorded on a game experience object. The training networks is fed samples from all the episodes in the game experience object. The win rate is calculated to check whether the agent has found the 100% optimal epoch win-rate.

# Connect your learning from throughout this course to the larger field of computer science: Computational finance can benefit from reinforcement learning with this algorithm for trading can boost gains in investors portfolios. The AI agent can make the best financial decisions when calculating risk to reward ratio.


# What do computer scientists do and why does it matter?
Computer scientist design algorithms and test them for any adjustments. The goal is to create the best algorithm for any applications, in this case, data structures. In addition, they write and test code to see its behavior and write reports. They secure computers and data in general from malicious hackers. In essence, they improve the our lives and strengthen many industries. Computer scientist and their work has impacted the economy by a large scale.


# How do I approach a problem as a computer scientist?
One must first understand the problem and break it up into manageable task and choose the correct data structures and algorithms. Document any results for feedback and make sure to reflect on the problem.


# What are my ethical responsibilities to the end user and the organization?
Assure that the users data is secure and remains confidential. I'll need to be transparent on what data is collected and how it will be used. Make sure to prioritize the organizations well-being and stay up-to-date with any laws and company standards. Create technology that will not be used for illegal activities.
