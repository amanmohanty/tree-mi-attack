# tree-mi-attack
This repository contains codes, data files and results of the project "Membership Inference in Decision Forests: White-box Attacks vs. Generalization Error".

### Project Description:
In this project, we implement membership inference attacks on non-parametric tree-based models leveraging white-box information about the target model. Membership inference attacks exploit the model's stored information on it's training dataset to infer the membership of an instance. Formally, the adversary aims to predict whether a certain record, r, was used to train the target model, M, using some auxiliary knowledge. The adversary assumes white-box access to the target model.

The target models being attacked are tree-based models, Random Forests and Gradient Boosting Machines. We implemented the Sklearn-RandomForestClassifier and GradientBoostingClassfier algorithm. The attack model is a neural network implemented using the pytorch framework.

We show that non-parametric models (RFs and GBMs) are as vulnerable to membership inference as comparably accurate parametric models (deep-net models) in prior literature. Furthermore, we evaluate the effect of number of estimators (trees) in random forests on membership inference vulnerability and show that with decreasing generalization error, attack accuracy increases. For more details, refer to our paper: *coming soon*

### Project Dependencies
```
python 3.7
jupyter notebook
scikit-learn
pytorch 1.5
shap
numpy
pandas
ipyparallel
matplotlib
pickle
tqdm
termcolor
```
