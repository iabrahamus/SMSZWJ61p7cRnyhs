# Project 1: Happy Customers

## Problem: Predict customers happiness

We are one of the fastest growing startups in the logistics and delivery domain. We work with several partners and make on-demand delivery to our customers. During the COVID-19 pandemic, we are facing several different challenges and everyday we are trying to address these challenges. We thrive on making our customers happy. As a growing startup, with a global expansion strategy we know that we need to make our customers happy and the only way to do that is to measure how happy each customer is. If we can predict what makes our customers happy or unhappy, we can then take necessary actions.

**Goals:**  The goal of this project is to predict customer happiness/unhappiness based on their rating

**Success Criterion:** Reach 73% accuracy score or above or convince why your solution is superior.Provide your insight in finding which questions/features are more important when predicting a customer’s happiness. Using a feature selection approach show us understand what is the minimal set of attributes/features that would preserve the most information about the problem while increasing predictability of the data we have. Is there any question that we can remove in our next survey?

## Data Description
Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers

X1 = my order was delivered on time

X2 = contents of my order was as I expected

X3 = I ordered everything I wanted to order

X4 = I paid a good price for my order

X5 = I am satisfied with my courier

X6 = the app makes ordering easy for me

Attributes X1 to X6 indicate the responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer.

## Approach
1. Apply data wrangling, exploratory data analysis on the data set.
2. For modeling, apply LazyPredict to narrow down potential ML candidates. Using time and accuracy the top ML models chosen are: Perceptron, NuSVC, QuadraticDisriminant analysis

