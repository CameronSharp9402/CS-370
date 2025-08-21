# CS-370 Current/Emerging Trends in CS 2025
## Reflection
What code were you given? What code did you create yourself?

For the project, I had various base Python files:
- TreasureMaze.py – that established the maze world and agent's action and reward logic rules
- GameExperience.py – which utilized experience replay memory to gather and sample episodes
- An IPython file for a Jupyter notebook (TreasureHuntGame.ipynb) that I was requested to implement the deep Q-learning logic in the Q-training section of the notebook. I authored the entire qtrain() function, which:
  - Selects starting agent positions at random
  - Decides on exploration or exploitation activities
  - Functions through the environment's API
  - Stores episodes in memory
  - Trains a Q-network to approximate Q-values
  - Win rate, loss, and training progress trackers
  - Sees the environment.
- I also drafted accompanying rationale for loss tracking, completion checks, and summaries for training.

##
What do computer scientists do and why does it matter?
- Computer scientists perform real-world tasks by coding algorithms, building systems, and making data-driven decisions. From all that you see from the artificial intelligence of mobile apps and video games to medical breakthroughs, security, and planet simulations, it is all accomplished through them. In this project, you witness computer scientists making machines learn and adjust on their own, something that has immense use in robots, autonomous systems, and game development.
##
How do I approach a problem as a computer scientist?
- Being a computer scientist, I approach the things systematically:
   - Get used to the context — learn the domain (in our example, maze and agent behavior rules)
   - Break down the problem into pieces — identify inputs, outputs, and constraints
   - Learn and employ tried-and-tested methods — i.e., reinforcement learning and neural networks\
   - Test and iterate — try exploratory methods, keep track of performance, and adjust hyperparameters as necessary
- This project necessitated that I learn to balance theory (such as the Bellman equation) and practice (debugging training loops and convergence logic).
##  
What are my ethical responsibilities to the end user and the organization?
- My ethical duties are:
   - Transparency – that models are comprehensible and not acting in biased or unexpected manners
   - Efficiency – using computer resources efficiently (e.g., control of training time and use of memory)
   - Fairness and confidentiality – and particularly in higher-scale systems of AI, so models aren't reinforcing detrimental patterns
   - Organizational responsibility - coding that is reusable or scalable, maintainable, and well documented
- In this project, that involved not computing things more often than necessary, making progress in training transparent, and crafting an agent that could learn adequately from any initialization.
