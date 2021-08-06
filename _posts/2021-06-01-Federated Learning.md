---
layout: post 
title: Federated Deep Learning
---

## "under construction"

### Federated Learning: 

Federated Learning is an approach where multiple devices (clients) train models (local models) on their on-device data (local data) and communicate only the trained models' parameters to the central server for updating and subsequently downloading the global model (mainly the parameters). 

In federated learning the goal is typically to solve the following equation: <br> 
<img src="https://latex.codecogs.com/svg.image?\min_{w}f(w)&space;=&space;\sum_{k=1}^{m}p_{k}F_{k}(w)" title="\min_{w}f(w) = \sum_{k=1}^{m}p_{k}F_{k}(w)" />
