# Estimation-and-Learning

How can robots determine their state and properties of the surrounding environment from noisy sensor measurements in time?  In this module you will learn how to get robots to incorporate uncertainty into estimating and learning from a dynamic and changing world.  Specific topics that will be covered include probabilistic generative models, Bayesian filtering for localization and mapping.

## Attentions
Assigment "Particle Filter Based Localization" still has problems. When the robot move to the long hall, due to the high similarity of measurements of different positions at the long hall, the code will fail to find the right pose of the robot.

## Gaussian Model Learning

The Gaussian distribution for parametric modeling in robotics. The Gaussian distribution is the most widely used continuous distribution and provides a useful way to estimate uncertainty and predict in the world. We will start by discussing the one-dimensional Gaussian distribution, and then move on to the multivariate Gaussian distribution. Finally, we will extend the concept to models that use Mixtures of Gaussians.

## Bayesian Estimation - Target Tracking

The Gaussian distribution for tracking a dynamical system. We will start by discussing the dynamical systems and their impact on probability distributions. This linear Kalman filter system will be described in detail, and, in addition, non-linear filtering systems will be explored.

## Mapping

Understand a mapping algorithm called Occupancy Grid Mapping based on range measurements. Later in the week, we introduce 3D mapping as well.

## Bayesian Estimation - Localization

How range measurements, coupled with odometer readings, can place a robot on a map. Later in the week, we introduce 3D localization as well.

