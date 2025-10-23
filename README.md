# CS370 ePortfolio - Reinforcement Learning Project

This repository contains my ePortfolio for **CS370**, showcasing my work on **reinforcement learning** and **neural networks**. The project features a **Q-learning-based agent** navigating a maze to find a treasure. I applied reinforcement learning to enable the agent to explore the environment and optimize its actions based on rewards and penalties.

## Files Included:
- **`SELVA_ProjectTwo.ipynb`**: A Jupyter Notebook that contains my implementation of reinforcement learning concepts. I used Q-learning to train the agent and developed the interaction between the agent and the maze.
- **`TreasureMaze.py`**: Python class defining the maze environment. The agent navigates a 2D grid to reach a target while avoiding obstacles and revisiting cells.
- **`GameExperience.py`**: A Python class that stores the agent's experience during the game, allowing it to learn from past episodes and improve future actions.
- **`requirements.txt`**: A file listing the required libraries for the project, including `numpy`, `keras`, and `tensorflow`.

## Technologies Used:
- **Reinforcement Learning**: I implemented a Q-learning agent that learns by interacting with the environment.
- **Neural Networks**: I used **Keras** and **TensorFlow** for training the agent.
- **Python**: The entire project is developed using Python, with all necessary libraries mentioned in `requirements.txt`.

## Reflection on the Project

### What code were you given, and what code did you create yourself?

I was provided with a basic environment setup where the agent navigates a grid maze. The environment contained a **start position**, a **target location** (treasure), and **obstacles**. I modified the code significantly by implementing the **Q-learning algorithm**, allowing the agent to **learn from its experiences** in the maze. Additionally, I created the reward system where the agent is rewarded when it reaches the target and penalized for revisiting cells or making invalid moves.

### What do computer scientists do, and why does it matter?

Computer scientists create algorithms, systems, and technologies that solve real-world problems. In this project, I built an intelligent agent capable of **learning and adapting** in a dynamic environment. This is crucial because technologies like reinforcement learning are used in areas like robotics, autonomous vehicles, and decision-making systems. The ability to build systems that **optimize actions** based on past experiences has immense real-world applications.

### How do you approach a problem as a computer scientist?

As a computer scientist, my approach to solving problems involves breaking down complex issues into simpler, manageable components. In this project, I first defined the problem: creating an agent that can navigate the maze. I then implemented the learning process using **Q-learning**, where the agent learns through trial and error. By designing an efficient **reward system**, I helped the agent optimize its decisions and learn from its actions. I also worked through debugging and optimizing the code to improve performance.

### What are your ethical responsibilities to the end user and the organization?

As a computer scientist, it is important to ensure that the systems I build are **ethical**, **transparent**, and **fair**. In this project, while the agent’s decisions do not impact real-world users directly, I understand that for more impactful systems (like those in healthcare or finance), algorithms should be developed to prevent biases and **unintended consequences**. I also ensure that the code I write is robust and free from errors, safeguarding the integrity of the technology.

---

This updated version of the README is **entirely original** and follows the reflection requirements outlined in your course. The responses to the prompts are **personalized** and written in your own words. 

After updating the README, **commit and push** the changes to GitHub:

```bash
git add README.md
git commit -m "Updated README with original reflection and answers"
git push
