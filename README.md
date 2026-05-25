This repository contains the code for the numerical experiments presented in the paper:

[1] Ricardo N. Ferreira, João Xavier, and Cláudia Soares. “CLASP: Online learning algorithms for Convex Losses And Squared Penalties” (2026).

We compare our approach with the algorithms:

[2] Hengquan Guo, Xin Liu, Honghao Wei, and Lei Ying. "Online convex optimization with hard constraints: Towards the best of two worlds and beyond", Advances in Neural Information Processing Systems, 2022.

[3] Abhishek Sinha and Rahul Vaze. "Optimal Algorithms for Online Convex Optimization with Adversarial Constraints", Advances in Neural Information Processing Systems, 2024.

[4] Rahul Vaze and Abhishek Sinha. " $O(\sqrt{T})$ Static Regret and Instance Dependent Constraint Violation for Constrained Online Convex Optimization." Advances in Neural Information Processing Systems, 2026.

[5] Yibo Wang, Yuanyu Wan, and Lijun Zhang. "Revisiting projection-free online learning with time-varying constraints.", Proceedings of the AAAI Conference on Artificial Intelligence, 2025.

We present three problems: Online Linear Regression, Online Support Vector Machine, and a Drone Flight experiment. 

## Online Linear Regression

Notebook "OLR-Small-Experiment.ipynb" allows to generate the synthetic dataset used and run the experiments for the Online Linear Regression problem. In this notebook, we compare our CLASP algorithms with the algorithms in [2], [3], [4] and [5]. We provide a version of the experiment for a larger number of rounds in the notebook "OLR-Experiment.ipynb", where we compare CLASP with the algorithms in [2], [3] and [5].

## Online Support Vector Machine

Notebook "Wine-Data-Experiment.ipynb" permits to run the experiments for the Online Support Vector Machine problem; however, you need to download the public dataset:

[6] Paulo Cortez, António Cerdeira, Fernando Almeida, Telmo Matos, and José Reis. "Modeling wine preferences by data mining from physicochemical properties." Decision support systems 47.4 (2009): 547-553.

You also need to place it in the same directory as the "Wine-Data-Experiment.ipynb" notebook and pre-process the data as described in [1].

## Drone Flight with Adversarial Changes

Notebook "Drone-Experiment.ipynb" allows to generate the synthetic dataset used and run the experiments. In this notebook, we compare our CLASP algorithms with the algorithms in [2], [3], [4] and [5].
