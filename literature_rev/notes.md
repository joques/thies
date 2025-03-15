# Notes
Below are notes compiled from the literature used while brainstorming about the problem. We organise these notes in different sections.

## Sequential Decision Making

- Paper 1
    - Introduction to Multi-Armed Bandits
    - bibentry: slivkins:2024
    - summary: this document presents a detailed introduction to multi-armed bandits algorithms, a decision-making technique under uncertainty.

**Paper 1: ## Multi-Armed Bandits** 
This paper discusses the Multi-Armed Bandits (MAB) problem and its relevance to the research topic: "building a multi-agent system for sorting recyclable waste at refuse stations". It includes introduction to Multi-Armed Bandits (MAB), a detailed account to MAB algorithms, a decision-making technique under uncertainty.
**ABSTRACT**
.....................................................................................................................................
.................................................................................................................to be placed
**INTRODUCTION**
Though it may sound like a throwback to the Wild West, the term "multi-armed bandit" has far more meaning than just shootouts and standoffs. It includes an area where statistics, probability, and cutting-edge algorithms come together to assist individuals in making calculated choices and maximizing their endeavors. Digital levers are used by multi-armed bandit (MAB) algorithms to increase their chances of success. The MAB is a simple yet very powerful framework for algorithms that manage uncertainty while making decisions over time (Slivkins, 2019). An agent must select actions (or arms) in this machine learning setting in order to maximize its cumulative long-term payoff (Zhao, 2025). The agent is given some context about the current condition at the beginning of each round. It makes its decision based on this data as well as the knowledge gathered from earlier rounds. The reward linked to the chosen action is given to the agent at the conclusion of each round.
In the MAB problem, an agent is given several options (or "arms"), each of which offers a reward selected from an unknown probability distribution. The agent seeks to maximize its cumulative reward across a sequence of trials (Vermorel and Mohri, 2005). In order to choose the best arm, one must strike a balance between exploring different arms to learn more about their reward distribution and taking use of recognized arms that have historically yielded large payouts.
.............................................................................................................................cont's

## Dec POMDPs
**Paper 2: ## Dec POMDPs (Actions, States and Observations)**
This study outlines the decentralized Partially Observable Markov Decision Process (Dec-POMDP) framework and its relevance to the research topic: "building a multi-agent system for sorting recyclable waste at refuse stations".

**ABSTRACT**
A group of agents collaborates to optimize a global reward using only local information in a decentralized partially observable Markov decision process (Dec-POMDP). As a result, the agents do not perceive a Markovian signal during their execution, which means their specific policies are derived from their histories and translated into actions. This paper reviews recent research on decentralized Markov decision processes (MDPs), where each agent's control is influenced by a limited perspective. We focus on a general framework represented as a Dec-POMDP, which accounts for uncertainty regarding the environmental state.

**I. INTRODUCTION**
Previous studies have broadened the scope of decision-making to include multiple agents and to operate in situations where the state is unknown, such as in Partially Observable Markov Decision Processes (POMDPs). Additionally, most research on multi-agent systems under partial observability has primarily focused on planning scenarios where the environmental model is already provided, rather than on complete reinforcement learning (RL) settings. In this study, we aim to further generalize this research by considering scenarios with multiple agents and state uncertainty. Specifically, it focuses on groups of cooperative agents that share a common goal. The Dec-POMDPs can be used to define such circumstances (Pynadath and Tambe, 2002; Bernstein et al, 2002).  Additionally, the research addresses issues about sequential decision-making under Dec-POMDPS and concentrates solely on planning, with some recommendations for RL techniques. Lastly, the paper presents the Dec-POMDPS planning model and pertinent Dec-POMDPS scenarios. 
This model is based on the principle that, in a scenario involving two agents, each agent acts independently at every stage. The state of the environment changes depending on the actions taken by both agents, resulting in a reward. Each agent receives a unique observation of the new state. There is a common understanding that planning occurs offline, with the plans then executed online. During the fully decentralized online phase, each agent has access to its own history of actions and observations, as well as its share of the joint policy developed during the planning phase (Chang & Kaelbling, 2003). In contrast, the offline planning stage is centralized. According to Claus and Boutilier (1998), we assume that a single computer calculates the joint plan and subsequently distributes it to the agents, who then carry it out online.
We provide a concise overview of recent developments relevant to addressing the Dec-POMDP (Decentralized Partially Observable Markov Decision Process) challenge. In part II, we will explicitly discuss sample scenarios of the Dec-POMDP model. Next, in section III, we will explore Dec-POMDP planning, including actions, states, and observations. Sections IV and V present insights on sequential decision-making within the context of Dec-POMDP and reinforcement learning (RL) respectively. In section VI, we will introduce several notable classes of Dec-POMDPs. Finally, in part VII, we will conclude our discussion.
......................................................................................................cont's

## Reinforcement Learning
**Paper 3: ## Reinforcement Learning**

## Multi-agent Systems
**Paper 4: ## Reinforcement Learning**

## Image Classification and Detection
**Paper 5: ## Reinforcement Learning**

