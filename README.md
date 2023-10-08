# Distribution-restrained Softmax Loss for the Model Robustness
 
Hao Wang, Chen Li, JinZhe Jiang, Xin Zhang, Yaqian Zhao and Weifeng Gong. 
 
 
This repository contains the code and data for the following paper:  
<a href='https://github.com/karlieswift/DRSL'><img src='https://img.shields.io/badge/Project-Page-Green'></a>  <a href='https://arxiv.org/abs/2303.12363'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>  
## Abstract

Recently, the robustness of deep learning models has received widespread attention, and various methods for improving model robustness have been proposed, including adversarial training, model architecture modification, design of loss functions, certified defenses, and so on. However, the principle of the robustness to attacks is still not fully understood, also the related research is still not sufficient. Here, we have identified a significant factor that affects the robustness of models: the distribution characteristics of softmax values for non-real label samples. We found that the results after an attack are highly correlated with the distribution characteristics, and thus we proposed a loss function to suppress the distribution diversity of softmax. A large number of experiments have shown that our method can improve robustness without significant time consumption.
