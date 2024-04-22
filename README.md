# EMRIL
_Welcome to this repository !_ 

This repository contains the code and data used in the paper:

**EMRIL** : Ensemble Method based on ReInforcement Learning for binary classification in imbalanced drifting data streams, Submitted to Neurocomputing, 2024. 

The main code file is available at the root folder in the form of Jupyter Notebook. The code is written in Python and may require some libraries to be installed prior to running. All synthetic data streams could be generated using the scripts available in data streams folder. Virtual and Real-world data streams used in the experiments are also available in a folder at root. In case of any difficulty in using the code/data streams, please contact at the email given at the end.

✒️ __EMRIL Brief:__ EMRIL performs binary classification in imbalanced and drifting data streams. It could deal with highly imbalanced data characterized by various imbalanced difficulty factors. EMRIL is based on two major components. ICRC, which balances the batch data in terms of imbalance difficulty factors whereas EPM manages the ensemble pool using ReInforcement Learning framework. 

⚛️ __Paper Abstract__ The co-occurrence of evolving concepts and imbalanced data deteriorates the learning performance of classifiers in data streams. Recent studies do not account for data difficulty factors associated with class imbalance, complicating the learning under drifting data environment. This paper proposes EMRIL, a novel batch-based ensemble method, to deal with this challenge. As part of EMRIL, Imbalance Complexity Redressing Component (EMRILICRC), a data-level balancing module, resolves the imbalance complexity to increase minority class visibility for the base classifiers of the ensemble. Additionally, a novel ensemble pool management (EMRILEPM) technique is designed using Reinforcement Learning (RL). EMRILEPM regularly updates the ensemble pool and constructs an optimal base classifier subset for predictions through effective training and evaluation policies. Handling imbalance complexity, and RL-based ensemble pool management helps EMRIL to effectively perform the binary classification task in imbalanced and evolving data streams. A comprehensive experimental evaluation is conducted with 104 data streams which contain a variety of concept drifts and imbalance ratios categorized by various data difficulty factors. The results are compared with 15 state-of-the-art methods showing the superiority of the proposed method. 

__Paper Link:__  https://www.ssrn.com/abstract=4682920 (Pre Print)

__Authors:__ Muhammad Usman, Huanhuan Chen

🗳️ __For any queries:__ muhammadusman@mail.ustc.edu.cn
