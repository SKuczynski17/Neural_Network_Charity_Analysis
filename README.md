# Samuel Kuczynski Neural_Network_Charity_Analysis

## Overview of Project

### We are working with Beks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Below are the following variables on the datasaet. 

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively 

## Deliverables

### There were 4 main objectives we attacked during this task.
    - Part 1: Preprocessing Data for a Neural Network Model
    - Part 2: Compile, Train, and Evaluate the Model
    - Part 3: Optimize the Model
    - Part 4: A Written Report on the Neural Network Model (README.md)

## Results 

The variables that were the target of this project was the "Is_Successful" metric. The results on our initial project were only 70% which is below our target of 75%. However I went ahead and made a couple of additional tests with a few adjustments below.

![Part_0](https://github.com/SKuczynski17/MechaCar_Statistical_Analysis-/blob/main/Images/Part_1.png)

## Part 4: Design a Study Comparing the MechaCar to the Competition
## Optimization 1

In Optimization 1 I made added a third hidden layer with 15 layers. The result of this was an accuract score of 62.4%

![Part_1](https://github.com/SKuczynski17/MechaCar_Statistical_Analysis-/blob/main/Images/Part_1.png)

## Optimization 2

In Optimization 2 I doubled the amount of layers each hidden layer had. I took the first layer to 160 from 80, and the second layer to 60 from 30. The result of this was an accuract score of 53.2%

![Part 2](https://github.com/SKuczynski17/MechaCar_Statistical_Analysis-/blob/main/Images/lot_summary.png)

## Optimization 3

In Optimization 3 I made added a third and fourth hidden layer using sigmoid activation. The layers were staggered at 100/75/50/25. The result of this was an accuracy score of 53.7%.

![Part 3](https://github.com/SKuczynski17/MechaCar_Statistical_Analysis-/blob/main/Images/T-Test.png)

## Summary

As I tried to make further changes and add additional test & nodes/layers it only made our accuracy score go further down. I believe adding more is very hurtful to this model and the next steps I would reccomend would be to taking layers + further data away to really get it above that 75% target.
