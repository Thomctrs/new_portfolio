---
title: Thermostat Regulation
publishDate: 2023-03-02 00:00:00
img: ../assets/ela_project.jpg
img_alt: frontend of our wixsite
description: |
  A 3 weeks project about the simulation of a thermostat regulation with Analogic Electronic, STM32 & C regulation.
tags:
  - Analogic Electronic
  - SMT32
  - C Regulation
---


## Objective of the project



By pair and for 3 weeks, we had to set up a project to simulate the regulation of a house thermostat. The project was divided into 3 weeks, with one week for each subject, culminating in a MCQ and an oral presentation by each pair


### An Analogic Electronic part

First of all, to simulate the real conditions of the walls of the habitat on a thermal RC model, thermal resistance calculations were performed. 

These results have been converted to correspond to values of electronic components that can be welded to an electronic board (resistors, capacitors). A test phase was necessary to validate that each component of the board was functional.

![image of ela](../assets/ela_soude.jpg)


### A C thermostat regulation 

The second step of this project was to set up a program that simulates a thermostat control loop depending on the temperatures outside the home and the permitivity of the walls of the house.

The regulation was divided into many functions following the tree structure below

![image of tree](../assets/c_program.jpg)

To visualize the regulation a Python user interface was developped.

![image python](../assets/ihm.jpg)

### And finally, a Numeric Electronic visualisation (STM32)

The end of this project was to vizualize the regulation of thermostat by connecting the Electronic part and the C part on a STM32 board. The home vizualisation is set up on a TFT screen. Bouttons and potentiometers allow the opening and the firmness of an anise window that to push or not the heating of the house.

![image stm32](../assets/stm32.jpg)
