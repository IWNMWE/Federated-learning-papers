# Federated Learning Algorithms

This repository contains implementations of various federated learning algorithms, including FedAvg, FedProx, Scaffold, BN-Scaffold, and FedSGD. These methods address challenges in decentralized and privacy-preserving learning environments by enabling model training across distributed clients without centralized data.

## Implemented Algorithms

1. **FedAvg** - The foundational algorithm for federated learning that performs model averaging across client updates.
2. **FedProx** - A variant of FedAvg that adds a proximal term to the objective function to handle heterogeneous data distributions across clients.
3. **Scaffold** - Introduces control variates to correct client drift, which stabilizes training under non-i.i.d. data conditions.
4. **BN-Scaffold** - An extension of Scaffold that incorporates Batch Normalization, which helps with training in scenarios where data distributions vary significantly across clients.
5. **FedSGD** - A simpler approach where each client performs only a single gradient update before averaging, often used as a baseline.
