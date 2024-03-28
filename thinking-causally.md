---
layout: page
title: Thinking Causally in EDM
subtitle: A Hands-On Tutorial for Causal Modeling Using DAGs – EDM 2024
---

During the EDM 2024 conference, I will be holding a tutorial on Causal Modeling in EDM. 

### Who can participate?
In short, anyone who is interested in learning something about causal modeling and Directed Acyclic Graphs (DAGs) in a hands-on way.
The tutorial will be held in a hybrid fashion, meaning that you can particpate virtually or in person. Either way, I'm looking forward to meeting you!

### What will we discuss?
We start with a theoretical introduction to causality, DAGs, and important concepts regarding this. This will include a brief recap of conditional independence, an explanation of confounders, colliders, and d-separation.
Afterward, we introduce *DAGitty*, a tool that allows us to model DAGs and that helps us in analyzing them. For example, *DAGitty* tells the user which variables to control for when we are interested in estimating the effect one variable has on another.
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
| 9:45-10:00 am | Introduction to *DAGitty*               |
| 10:00-10:20 am| Break                                   |
| 10:20-11:00 am| Group Work using *DAGitty*              |
| 11:00-11:45 am| Introduction to Learning DAGs from Data |
| 11:45-12:00 am| Break                                   |
| 12:00-12:30 am| Group Work using *bnlearn*              |
| 12:30-12:45 am| Concluding Remarks                      |

### Materials
Links to resources will be added here soon.

