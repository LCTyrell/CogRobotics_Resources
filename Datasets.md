---
layout: default
title: Datasets
nav_order: 6
---

## 3D Objects Datasets

* [Procedurally Generated Random Objects](https://sites.google.com/site/brainrobotdata/home/models) - Google Brain. In order to enable training of robot grasping and other tasks in simulation, we require a set of sample objects.  We used a set of randomly generated simple rigid objects.  Here we provide 3D models for these objects in OBJ format and URDF representations for use with Bullet. 

## Simulated Robotics Environments

* [Ingredients for Robotics Research](https://openai.com/blog/ingredients-for-robotics-research/#requestsforresearchheredition) - OpenAI. We’re releasing eight simulated robotics environments and a Baselines implementation of Hindsight Experience Replay, all developed for our research over the past year. We’ve used these environments to train models which work on physical robots. 

## Vision-Based Robotic Manipulation Datasets

* [Multiview Pouring Dataset](https://sites.google.com/site/brainrobotdata/home/multiview-pouring) - Google Brain. This dataset contains a variety of people pouring liquids into containers, taken from multiple angles, which can be used to learn representations of the abstract task of pouring for robot learning.

* [Grasping Dataset](https://sites.google.com/site/brainrobotdata/home/grasping-dataset) - Google Brain. This dataset contains recordings of 650k robotic grasp attempts. Each grasp attempt is annotated with the success or failure of the grasp. Data was collected using real robots and several hundred different objects.

* [Push Dataset](https://sites.google.com/site/brainrobotdata/home/push-dataset) - Google Brain. This dataset contains recordings of 59k object pushing interactions. Each push includes video and joint angle sequences. Data was collected using real robots and several hundred different objects.

* [RoboNet](https://www.robonet.wiki/) - The standard paradigm in robot learning is to set-up experiments in a single lab environment and train a robot from scratch from data collected in that setting. In contrast, essentially all machine learning fields accumulate and share large datasets across institutions, which enables training of models that generalize much more broadly. We aim to take a step in this direction by collecting a large dataset from 7 robot platforms across multiple institutions, which we call RoboNet. Critically, we find that pre-training on RoboNet enables us to generalize to entirely new robot platforms with less data than training from scratch.
