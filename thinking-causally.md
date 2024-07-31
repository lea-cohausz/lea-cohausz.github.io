---
layout: page
title: Thinking Causally in EDM
subtitle: A Hands-On Tutorial for Causal Modeling Using DAGs – EDM 2024
---

**Update**: During the tutorial, I mentioned our package for fairness through causal modeling. It is available [here](https://github.com/lea-cohausz/causalfair). The paper introducing it will be published soon.

During the EDM 2024 conference, I will be holding a tutorial on Causal Modeling in EDM. 

### Who can participate?
In short, anyone who is interested in learning something about causal modeling and Directed Acyclic Graphs (DAGs) in a hands-on way.
The tutorial will be held in a hybrid fashion, meaning that you can particpate virtually or in person. Either way, I'm looking forward to meeting you!

The Zoom meeting link will be pusblished here 15 minues before the event starts.

### What will we discuss?
We start with a theoretical introduction to causality, DAGs, and important concepts regarding this. This will include a brief recap of conditional independence, an explanation of confounders, colliders, and blocking variables. Don't worry if you have never heard of some of those terms – we will start from the beginning.
Afterward, we introduce [DAGitty](https://www.dagitty.net/dags.html), a tool that allows us to model DAGs and that helps us in analyzing them. For example, *DAGitty* tells the user which variables to control for when we are interested in estimating the effect one variable has on another.
Finally, we will introduce the R package *bnlearn* and show how to learn DAGs from observational data using different methods. 
Throughout the tutorial, we will continuously work with the same example setting, showcasing the need for causal thinking.

### Why is this interesting?
Causal Modeling and DAGs are interesting in many ways. The most important are:
- We know which variables to control for if we want to estimate the effects of variables on a target variable using observational data. If we, for example, want to know the effect of taking a mental health class on well-being, we know what variables we need to control for when estimating the effect.
- We can understand in which way sensitive variables (e.g. gender) impact the target variable, which allows us to detect potential fairness problems Machine Learning models trained on observational data may have.
- We can select only those variables for predictive models that should have a causal influence on the target, therefore, using DAGs for feature selection. This might not only lead to better and more efficient models but also models with influences we know and can explain. This, in turn, leads to better explainability and generates trust.

### Tentative Schedule
The exact date and time will be anounced soon. Here is a tentative timeline:

| Time          | Activity                                |
| ------------- | --------------------------------------- |
| 9:00-9:45 am  | Introduction to Causality and DAGs      |
| 9:45-10:00 am | Mini Break                              |
| 10:00-10:10 am| Introduction to *DAGitty*               |
| 10:10-10:30 am| Group Work using *DAGitty*              |
| 10:30-11:00 am| Break                                   |
| 11:00-11:15 am| Finishing up and discussing the results |
| 11:15-11:45 am| Introduction to Learning DAGs from Data |
| 11:45-12:15 am| Small Group Work using *bnlearn* & Break|
| 12:15-12:25 am| Concluding Remarks                      |

### Materials
[Here are the materials we will use during the tutorial.](https://github.com/lea-cohausz/EDM24-Causal-Modeling)

