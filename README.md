# [Towards a Scalable Deployment of AI Models via Uncertainty Quantification](https://odsc.com/speakers/towards-a-scalable-deployment-of-ai-models-via-uncertainty-quantification/)
Tutorial @ Open Data Science Conference, London, June 16th, 2022

## Abstract

Deep learning-based models have tremendous potential to have an impact on socially-relevant problems like medical diagnosis. At the same time, safety critical applications must carefully balance potential harms and benefits and should only be deployed if they provide a net benefit.

This tutorial will introduce the glossary of uncertainty quantification relevant for deep learning and contextualise which aspects are most important in order to ease model deployment. While the identification of difficult samples for collaborative approaches between human and AI can be very successful in-domain, the reliable detection of out-of-distribution samples via uncertainty remains an active field of research. We'll provide an overview of promising recent developments and end with building a neural network that knows when it does not know - in a simple setting and for illustrative purposes.

#### Session Outline

The session will consist of two parts:
1. A talk that introduces to the topic of uncertainty in the context of safety-critical industrial ML applications and gives an overview about the current state of the field.
2. A short demo of building a neural network with uncertainty in a simple setting. This part can be followed along much like the talk, but the code will also be provided.

#### Background Knowledge
1. Familiarity with deep learning, in particular classification problems
2. Familiarity with Python & a DL framework such as Tensorflow or Pytorch

#### Material
* [Slides](https://docs.google.com/presentation/d/18yQwiwAjOKklrpicwiKe-2K0WiGjFhKHrk-TJbuxiys/edit?usp=sharing)
* [Code demo](https://github.com/chleibig/uncertainty-odsc/blob/master/odsc_demo.ipynb)

#### Setup
If you want to put your hands on the code demo (you can also just follow along), you should setup 
a python environment in advance. E.g. via anaconda:
```bash
conda create -n odsc pip
conda activate odsc
pip install -r requirements.txt
```
