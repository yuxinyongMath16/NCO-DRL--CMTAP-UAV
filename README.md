# NCO-DRL--CMTAP-UAV

# Neural Combinatorial Optimization for Cooperative Multi-Task Assignment of Heterogeneous UAVs

This repository provides the source code and experimental data for the paper:

> **Cooperative Multi-Task Assignment of Heterogeneous UAVs: Neural Combinatorial Optimization with Constraint-Aware Masking**  
> (under review)

## 📌 Overview

This work studies the **Cooperative Multi-Task Assignment Problem (CMTAP)** in heterogeneous multi-UAV systems, where UAVs must collaboratively execute multiple interdependent tasks under strict execution sequences and resource constraints.

We propose an **end-to-end neural combinatorial optimization (NCO) framework** that:
- Reformulates CMTAP as a Markov Decision Process (MDP)
- Guarantees **deadlock-free** task–vehicle assignment
- Employs a **Transformer-based policy network** with constraint-aware masking
- Is trained using rollout-based reinforcement learning

Extensive experiments demonstrate superior performance over state-of-the-art metaheuristic algorithms, especially in large-scale scenarios, with strong generalization capability.

## 视频演示

<video src="result/result.mp4" width="600" controls>
  你的浏览器不支持视频标签
</video>>

## 📂 Repository Structure
