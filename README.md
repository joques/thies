# Thies

This repo contains brainstorming information about an intelligent waste management system. The project uses several technologies, including **Internet of Things** (IoT), **robotics**  and **artificial intelligence** (AI). We aim to build a multi-agent system to sort recyclable waste. One of the scenarios we intend to develop is as follows. Consider a multi-storey building, where __collector__ agents are deployed to periodically help collect and assemble waste at each floor. We aggregate the refuse in a central place, use a computer vision tool to detect recyclable objects and then complete the sorting using __robotic arms__ and __intelligent bins__.

In this project, we seek to:

1. develop **transofrmer**-based computer vision models to detect recyclable objects from an image. We will focus on bottles at first;
1. develop an __intelligent__ **sequential decision-making** tools inspired from reinforcement learning.

For the object detection problem, we will organise/generate a dataset of recyclable waste items (e.g., bottles). Next, we will build several models for object detection and segmentation. Our model development efforts will build on recent developments in self-supervised learning (contrastive learning) and representation learning for object detection. These techniques include vision transofrmers, cross-attention, BYOL and autoencoders.  

Moreover, we will formulate the waste sorting problem as **decentralised partially observable Markov Decision Process** and explore several distributed and parallel algorithms in sequential decision-making (reinforcement learning, multi-armed bandits, Monte Carlo Tree Search, Group Related Policy Optimisation, etc.). 
