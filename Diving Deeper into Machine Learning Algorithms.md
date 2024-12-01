### Supervised Learning

In supervised learning, the algorithm learns from labeled data, where each data point is associated with a corresponding output or target variable. The goal is to learn a mapping function that can accurately predict the output for new, unseen data points.  

**Key Algorithms:**

- **Linear Regression:** Predicts a continuous numerical value (e.g., house prices, stock prices).
- **Logistic Regression:** Predicts a binary outcome (e.g., spam/not spam, cancer/no cancer).
- **Decision Trees:** Creates a tree-like model of decisions and their possible consequences.
- **Random Forest:** An ensemble method that combines multiple decision trees to improve accuracy.
- **Support Vector Machines (SVM):** Finds the optimal hyperplane to separate data points into different classes.
- **Neural Networks:** Inspired by the human brain, neural networks are composed of interconnected nodes called neurons.

### Unsupervised Learning

Unsupervised learning involves training models on unlabeled data. The goal is to discover hidden patterns and structures within the data.  

**Key Algorithms:**

- **Clustering:** Groups similar data points together.
    - **K-Means Clustering:** Divides data into K clusters based on similarity.
    - **Hierarchical Clustering:** Creates a hierarchy of clusters.  
        
- **Dimensionality Reduction:** Reduces the number of features in a dataset while preserving important information.
    - **Principal Component Analysis (PCA):** Identifies the principal components that explain most of the variance in the data.
    - **t-SNE:** Visualizes high-dimensional data in a lower-dimensional space.

### Reinforcement Learning

Reinforcement learning involves training agents to make decisions in an environment by interacting with it and receiving rewards or penalties. The agent learns to optimize its actions to maximize cumulative reward.

**Key Concepts:**

- **Agent:** The decision-making entity.
- **Environment:** The world in which the agent operates.
- **State:** The current situation of the agent and the environment.
- **Action:** The choice made by the agent in a given state.
- **Reward:** The feedback received by the agent for its action.

**Key Algorithms:**

- **Q-Learning:** Learns the optimal action-value function, which estimates the expected reward for taking a specific action in a given state.
- **Deep Q-Networks (DQN):** Combines deep neural networks with Q-learning to handle complex environments.
- **Policy Gradients:** Directly optimize the policy function, which maps states to actions.