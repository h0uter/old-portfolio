---
title: 'ML pipeline for Robot Gripper'
description: Using fiver to avoid boring labeling tasks.
# categories:
#   - projects
# tags:
#   - Machine Learning
#   - Uni Project
#   - Python
img: /assets/img/ml_knife.png
# image:
#   path: /assets/img/ml_knife_wide.jpg
#   thumbnail: /assets/img/ml_knife.png
#   caption: "wtf"
actions:
  - label: "Published Notebook"
    icon: arrow-right  # references name of svg icon, see full list below
    url: "https://deepnote.com/publish/452790e4-76c0-49f0-8fb0-80760653c8f0"
---

A small robot gripper has to detect cutlery and determine a suitable grip pose. To this end we built a complete ML pipeline start to end.

The general ML cookbook looks something like this:

1. **Overview**
  - make a plan
2. **get the data**
	- representiveness
	- need to annotate
	- use simulation to obtain data (well suited for reinforcement learning)
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
