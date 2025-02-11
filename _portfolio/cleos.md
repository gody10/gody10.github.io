---
title: "Federated Learning for Phising Attack Detection with the use of Over-The-Air-Computing"
excerpt: "This project has been sent to IEEE Globecom 2025. A realistic framework is created under which a global model is trained using Federated Learning to detect phising attacks [(no github repository for now)](): **Federated Learning, DeepML, Game Theory, Over-The-Air-Computation** <br/><img src='/images/phisinh.jpg' width='700'>"
collection: portfolio
---

## CLEOS: Contract-Theoretic Federated Learning through Over-the-Air-Computation

### Description

This project formulates a realistic framework for Federated Learning that handles and optimizes the communication between the local users and the central server while also making sure that the model trained is proficient in detecting phising attacks.

_CLEOS paper: CLEOS: Contract-Theoretic Federated Learning through Over-the-Air-Computation"._

### Implementation Details

This framework was built utilizing Pytorch, JAX and CVXPY. We perform convex optimization to get the optimal transmission powers of each user and the amplification factor of the receiver using CVXPY. We preprocess the [data](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset) by eliminating nulls, one-hot encoding specific values and concatanating texts. Then we feed the text feature to a TFIDFVectorizer to extract embeddings. All of these features are then fed to a Deep Neural Network with 3 Hidden layers that utilize Batch Normalization and have RELU activation functions. Finally, there is a softmax function that allows us to extract probabilities for if the current instanse is a phising attempt or not.

### Technologies Used

- **Deep Machine Learning** – Leveraging Federated Learning to detect phising attacks.
- **Problem Modeling** – Structuring complex problems into solvable frameworks.
- **Cutting-Edge Libraries** – Utilizing Pytorch, JAX and CVXPY to accelerate the DML training process and solve the Optimization problem.