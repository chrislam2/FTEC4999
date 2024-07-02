# Optimization Algorithms for Statistical Learning
Federated learning is a decentralized approach to machine learning that allows multiple devices or entities to collaboratively train a shared model without sharing their raw data. Instead of sending data to a central server, federated learning enables training to occur locally on individual devices or servers. The process involves sending only model updates or gradients to a central aggregator, which then combines and averages the updates from multiple participants to improve the shared model. This distributed learning paradigm offers several benefits, including enhanced privacy and data security since sensitive information remains on the local devices. Federated learning also enables efficient training on large-scale datasets distributed across various devices or locations, making it particularly useful in scenarios where data cannot be easily centralized.

## Project Goal
1. Evaluate the performance of existing federated learning algorithms.
2. Investigate the influence of adversaries and stragglers on the performance and efficiency of federated learning.
3. Assess the robustness and resilience of federated learning algorithms in real datasets.
4. Identify areas for improvement and advancement in federated learning based on the findings.

## Experiment Settings
- Algorithms: FedAvg, FedProx, Scaffold
- Code details: Main.ipynb

The experiment focuses on evaluating the performance of three federated learning algorithms: FedAvg, FedProx, and Scaffold. The code implementation and specific details can be found in the Main.ipynb file.
