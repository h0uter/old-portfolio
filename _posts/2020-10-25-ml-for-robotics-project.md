---
title: 'Machine learning for robot gripper'
categories:
  - projects
tags:
  - machine learning
  - MSc. Robotics
  - Python
image: 
  path: /assets/images/ml_knife.png
  thumbnail: /assets/images/ml_knife.png
  caption: "test"
actions:
  - label: "Published Notebook"
    icon: arrow-right  # references name of svg icon, see full list below
    url: "https://deepnote.com/publish/452790e4-76c0-49f0-8fb0-80760653c8f0"
  # - label: "execute the code"
  #   icon: arrow-right  # references name of svg icon, see full list below
  #   url: "https://deepnote.com/project/452790e4-76c0-49f0-8fb0-80760653c8f0"
---

The goal of this project was to employ machine learning for the purpose of picking up cutlery with a small robot.
To this end a machine learning pipeline had to be setup from start to finish.
The general ML pipeline looks like this:

1. **Overview**
  - make a plan
2. **get the data**
	- representiveness
	- need to annotate
	- use simulation to obtain data (really well suited for reinforcement learning)
3. **Inspect Data, gain insights**
	- GOAL: develop intuition
	- find outliers
	- determine physical meaning
4. **Prepare data**
	- GOAL: expose the underlying patterns to the ML algorithm
		- how2translate 'task' to 'ML problem'
	- Feature selection/ feature engineering
	- what do the measurements represent
	- data compression
		- which variance is informative
		- which variance can be removed
	- data transforms to deal with:
		- missing values
5. **Explore different models**
	- for robotics fast inference required as part of control loop
	- training time more forgiving
	- "more data vs. better model" ROI consideration
6. **Fine tune your model**
	- Optimise hyperparameters
7. **Present your solution**
	-  ensure results are reproducible
8. **Launch, monitor and maintain your system**

So we went though the pipeline for the challenge at hand and our results can be seen in the published notebook.


Additionaly, you can execute our code yourself on [Deepnote](https://deepnote.com/project/452790e4-76c0-49f0-8fb0-80760653c8f0)

Worked together on this project with Wesley who made a post about our success:

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6737753292039872512" height="600" width="704" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>