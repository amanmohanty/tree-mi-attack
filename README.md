# tree-mi-attack
This repository contains code and data files of the project "Membership Inference Attack on Tree-based Models Leveraging Structural White-box Information".

### Project Description:
In this project, we implement membership inference attacks on tree-based models leveraging white-box information about the target model. Membership inference attacks exploit the model's stored information on it's training dataset to infer the membership of an instance. Formally, the adversary aims to predict whether a certain record, r, was used to train the target model, M, using some auxiliary knowledge. The adversary assumes white-box access to the target model.

The target model being attacked is a tree-based model, Random Forest. We implemented the Sklearn-RandomForestClassifier algorithm. The attack model is a neural network implemented using the pytorch framework.

We show that our attack performs as well or better than the current state-of-the-art results of Leino and Fredrikson [arXiv](https://arxiv.org/abs/1906.11798). Furthermore, we report on some interesting points which question the current understanding of membership inference attacks. For more details, refer to our paper: *coming soon*
