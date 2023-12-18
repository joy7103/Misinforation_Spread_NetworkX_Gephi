In an increasingly interconnected world dominated by social media platforms and digital communication, 
the proliferation of misinformation poses a significant challenge. This project aims to depict how quickly misinformation can travel through a network and 
analyses which nodes played the biggest role in the spread of misinformation.

This project's focus centers on employing social network analysis techniques to dissect the complex web of connections 
through which misleading or false information propagates. By employing the Independent Cascade Model (ICM) and the Cost-Effective Lazy Forward (CELF) algorithm,
we've delved into the dynamics of information dissemination.
At the heart of our investigation lies the identification and examination of the most influential nodes within these networks. These pivotal nodes 
wield immense power in shaping the trajectory of misinformation dissemination.
As misinformation continues to permeate various online platforms, understanding the interplay between influential nodes, content, 
and network structures becomes pivotal. This not only illuminates the pathways through which 
misinformation navigates but also endeavors to provide insights that can aid in developing robust strategies to curb its influence.


● Dataset: The code makes use of real-life dataset of Facebook users putting the code to use in the real world.
● Modularity:The code is modular, with separate functions for loading the graph, visualizing the graph,
  running the Independent Cascade Model, and performing influence maximization using CELF. This makes the code more readable and maintainable.
● Visualization:The code provides a visual representation of the graph at each iteration of the Independent Cascade Model,
  making it easier to understand the spread of influence.
● Parameterization:The code allows for easy parameterization, such as changing the probability of activation (p), the number of iterations, 
  and the number of influential nodes to select (k).
● Random Seed Nodes:Seed nodes are randomly generated, providing flexibility for testing the algorithm with different initial conditions.
● Documentation and Comments:The code includes comments to explain the purpose of each function and important steps within the functions. 
  This helps others understand the code more easily.
  
Libraries Used:
The code leverages popular Python libraries such as NetworkX, pandas, numpy, and matplotlib for efficient graph manipulation, data loading, and visualization.

