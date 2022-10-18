---
title: "Online Map Recognition using Bayesian Updates"
excerpt: "Present a system for online map recognition method with Hidden Markov Modelwith novel heuristic-based likelihood model. Conducted experiments with Gazebo simulation and visualization of localization process through RVIZ "
collection: portfolio
---
Present a system for online map recognition method with Hidden Markov Model where the state is the belief that we are in a given map and observations are particle distributions.

Adopted particle filter based Adaptive Monte-Carlo Localization (AMCL) as our re-localization approach.

Developed a novel heuristic-based likelihood model to model the conditional probability of a particledistribution given a map with our main factors for place recognition belief Update from the particle filter being covariance of the estimated position, and the ratio of free space occupying particles.

Conducted experiments with Gazebo simulation and visualization of localization process through RVIZ in ROS based on ROBOTIS Turtlebot3 robot platform with our own dataset.


Report can be viewd [here]([https://www.overleaf.com/read/gpdqjsqvggrh](https://www.overleaf.com/read/gvbvggxfvsxc) and slides can be viewed [here](https://docs.google.com/presentation/d/1XK8ie3_NdOfbn96_KCTx3Zc9yU9yDQ0dhDGJp0T_Id0/edit?usp=sharing).
