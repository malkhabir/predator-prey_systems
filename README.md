# Predator-Prey Systems
This repository contains an excel spreadsheet which contrasts the __Lotka-Volterra__ model for predator-prey systems to the __Leslie-Gower__ model.

## Lotka-Volterra Equations

The Lotka-Volterra equations are a pair of first-order, nonlinear, differential equations that are used routinely to describe the __dynamics__ of __biological systems__ in which __two species interact__, one as the __prey__ and the other as the __predator__.

The equations are given as shown:

![alt text](https://wikimedia.org/api/rest_v1/media/math/render/svg/79752d662d4760abcc84c6f0bb94d708f17ff442)

Where:
* x = population of prey
* y = population of predators
* t = time
* \alpha   = birth rate of prey
* \gamma  = death rate of predators
* \beta = interaction term between predators and prey
* \delta  interaction term between prey and predators

## Main assumptions of the model

The Lotka-Volterra model has several assumptions, which decrease the accuracy of the model when applied to real world scenarios. These include the following:

* The prey population never runs out of food.
* The predators consume only the prey.
* The rate of change of populations are proportional to their size.
* The environment does not change in favour of one species, and genetic adaptation of offspring is negligible.
* Predators have limitless appetite.

## Leslie-Gower Equations

The Leslie-Gower equtions are a modified version of the Lotka-Volterra equations, which similarly describe the dynamics of a predator-prey system. The equation
