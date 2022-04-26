# Debiasing-Image-Recognition-Using-Multiple-Adversaries
This repository contains code from other repostiories that are combined together to provide an algorithm with multiple adversaries for ensuring fairness. 
## Generating Fair Dataset 
The first portion invloves code from the repository [TabFairGAN](https://github.com/amirarsalan90/TabFairGAN)
It utilizes the second version listed with fairness. It sets the protected attribute to sex, the underpriviliged group to female, the decision label to income, and the desired value label is >50k
The dataset that was generated is also posted within this document under the generating fair data folder.

## Second Adversarial Network
The second adversarial network is pulled from the repository [AIFBAREND](https://github.com/bspanjers/AIFBAREND) 
It utilizes the example and demo for adversarial debiasing which uses Jupyter Notebooks and tensorflow. 
This program was run with both the original adult dataset, which is contained within the adversarial debiasing folder, and the newly generated dataset.


