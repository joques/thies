# Thies

This repo contains brainstorming information about an intelligent waste management system. The project uses several technologies, including **Internet of Things** (IoT), **robotics**  and **artificial intelligence** (AI). We aim to build a multi-agent system to sort recyclable waste. One of the scenarios we intend to develop is as follows. Consider a multi-storey building, where __collector__ agents are deployed to periodically help collect and assemble waste at each floor. We aggregate the refuse in a central place, use a computer vision tool to detect recyclable objects and then complete the sorting using __robotic arms__ and __intelligent bins__.

In this project, we seek to:

1. develop **transofrmer**-based computer vision models to detect recyclable objects from an image. We will focus on bottles at first;
1. develop an __intelligent__ **sequential decision-making** tools inspired from reinforcement learning.

For the iobject detection problem, we will organise/generate a dataset of recyclable waste items (e.g., bottles). Next, we will build several models for object detection and segmentation. Our model development efforts will focus on the transformer architecture.

Moreover, we will formulate the waste sorting problem as **decentralised partially observable Markov Decision Process** and explore several distributed and parallel algorithms in sequential decision-making (reinforcement learning, multi-armed bandits, Monte Carlo Tree Search, Group Related Policy Optimisation, etc.). 
..........................................................................Progress.......................................................................
1.4.1 Main Objective 

To build a multi-agent-powered model for waste sorting at the public refuse

1.4.2 Specific Objectives

This study will be guided by the following specific research objectives (RO):

i.	To investigate the data requirements needed for building a multi-agent-powered model for waste sorting at the public refuse (RO1)
ii.	To develop a multi-agent-powered model for waste sorting at the public refuse (RO2)
iii.	Validate the developed model (RO3)

Description of the RO:

RO1: “To investigate the data requirements needed for building a multi-agent-powered model for waste sorting at the public refuse” To achieve this objective, we will initially gather data through field surveys, social questionnaires, and face-to-face interviews with residents, recycling sites, and government statistical records in Namibia. We will focus on the characteristics, parameters, decision-making processes, and data relevant to each type of agent in the proposed model. In order to train the model to accurately identify and classify different types of waste using computer vision techniques, we primarily need image data of various waste items, carefully labeled with their corresponding categories (such as plastic, paper, glass, metal, and organic). Depending on the model's requirements, additional data points like sensor data (to detect material properties) and waste volume information may also be beneficial.

RO2: “To develop a multi-agent-powered model for waste sorting at the public refuse”. Effectively mapping visual observations to optimal actions based on received rewards, a function approximator for waste image classification is one technique that will be utilized to achieve this goal. In other words, Convolutional Neural Networks (CNNs) enable the agent to "see" and better understand its environment, thereby enhancing decision-making in visually complex situations. Additional techniques include partially observable Markov Decision Processes and sequential decision-making algorithms. To achieve our goal, we will need to create a variety of individual models. This includes developing sophisticated sequential decision-making tools using reinforcement learning, as well as transformer-based computer vision models capable of identifying recyclable items in images, with an initial focus on bottles. We will organize and generate a dataset that consists of recyclable waste items, such as bottles, to address the object detection problem. Following that, we will construct multiple models for both segmentation and object detection. Our model development efforts will primarily focus on the transformer architecture-"Attention is All You Need" (Subakan et al., 2021).
In our investigation of scoped distributed and parallel algorithms within the context of sequential decision-making, particularly in reinforcement learning, Markov Decision Processes, and multi-armed bandits, we will define the waste sorting problem as a decentralized partially observable Markov decision process. This approach is necessary because our model involves multiple agents.

RO3: “Validate the developed model”. Validating the model ensures that it generalizes well beyond the training data, helping to identify overfitting and underfitting. This process aligns the model's performance with business goals, builds confidence in its reliability, and enables early identification of potential issues for correction. We will evaluate different validation approaches, such as cross-validation, holdout validation, bootstrap methods, and domain-specific techniques, to determine their suitability for the specific purpose under consideration. Performance metrics such as accuracy, precision, and recall will be used for model validation. AI-driven models can be validated by following best practices, including using multiple evaluation metrics for a comprehensive assessment, simulating real-world conditions to test performance under likely scenarios, and implementing continuous monitoring to track performance over time. Additionally, it is important to align validation efforts with business objectives to ensure that metrics reflect specific goals, as well as to address bias and fairness to mitigate potential biases relevant to the scenario. Model validation is crucial, as it demonstrates how well our model performs with random test datasets. Our goal is to achieve a high level of validation accuracy.
