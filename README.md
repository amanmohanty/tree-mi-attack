# tree-mi-attack
This repository contains code and data files of the project "Membership Inference Attack on Tree-based Models Leveraging Structural White-box Information".

### Project Description:

Abstract:
Machine learning models generally store information about their training data, due to certain peculiarities of their internal parameters. This stored information can be exploited to mount a membership inference attack, i.e, to find the presence of a particular instance in the model’s training data. Previous attacks have leveraged both black-box and white-box settings to demonstrate information leakage, but the extent and causes of such leakage are not well understood. The white-box attacks were implemented on deep-net models, which have pre-defined internal parameters. On the other hand, structured models like trees do not have pre-defined internal parameters, hence extracting white-box information is not easy. 

In this paper, we propose a novel white-box membership inference attack based on the effects of training data on the internal parameters of a tree-based model. We present three algorithms to demonstrate our attack on four real world data-sets. Our attacks perform as well or better than the state-of-the-art baseline results of Leino and Fredrikson in terms of accuracy and precision. Furthermore, we evaluate the effect of number of estimators of a random forest model on the attack metric and show that with decreasing generalization error, attack accuracy increases. This observation questions the relationship of overfitting with membership information leakage. Further research on this idea can refine the understanding of how training data influences internal parameters of models, and this information can be used to reinforce defense strategies.
