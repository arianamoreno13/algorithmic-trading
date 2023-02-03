# Algorithmic Trading Bot

![license badge](https://shields.io/badge/license-mit-blue)

## Description

This project was executed in jupyter lab using python libraries to read the CSV file and to create the machine learning algorithm. This project aims to make a bot that will make good trades based on machine learning algorithms.

Algorithmic trading is the use of algorithms to automate the decision-making process of buying and selling financial instruments in financial markets. It involves developing mathematical models that analyze market data and use that information to make trades. In this model we use Scikit-learn. Scikit-learn is a Python library for machine learning that can be used for developing and testing algorithmic trading models.

The importance of algorithmic trading for data analysts lies in its ability to handle large amounts of data in real-time and make trades faster and more accurately than a human trader could. Algorithmic trading can also help to remove emotions and biases from the trading process, leading to more consistent and profitable results.

## Table of Contents

- [Algorithmic Trading Bot](#algorithmic-trading-bot)
    - [Description](#description)
    - [Table of Contents](#table-of-contents)
    - [1. Installation](#1-installation)
    - [2. Usage](#2-usage)
    - [3. License](#3-license)
    - [4. Contributing](#4-contributing)
    - [5. Tests](#5-tests)
    - [6. Deployment](#6-deployment)
    - [7. Contact](#7-contact)
    - [8. Results](#8-results)

## 1. Installation

If you would like to clone the repository, type "git clone https://github.com/arianamoreno13/algorithmic-trading.git". In your terminal, with the conda dev environment activated, install the following packages and dependencies before running the algorithmic trading bot. To understand how to install these, refer to the Usage. 

## 2. Usage

- csv - Used to store data

- Jupyter Lab - version 3.4.4 - Used to create and share documents that contain live code, equations, visualizations and narrative text.

- pandas - For data analysis.

- pathlib - version 1.0.1 - This was used to locate through the directory or file path.

- scikit-learn - version 1.2 - Tools for data analysis

- NumPy - version 1.24.0- Provides tools when dealing with classification with imbalanced classes



## 3. License
    MIT License
Copyright (c) 2023 Ariana Moreno

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## 4. Contributing

[Ariana Moreno](https://github.com/arianamoreno13)

## 5. Tests

- There is currently no tests associated with this project 

## 6. Deployment

- There is currently no live deployment of this notebook on a common server, but the user has the ability to run this notebook locally on their machine via:
    - Jupyter Lab: In terminal Navigate into cloned git file, then open jupyter lab. 

## 7. Contact

- [Ariana's Linkedin](www.linkedin.com/in/arianapmoreno)

## 8. Results

In the Support vector machines (SVMs) plot we have a very well predicted model. This model is a supervised learning algorithm used for outlier detection, regression, and classification. Though this model is well executed I want to see how well it compares with the ada boost Classifier.

![SVM](screenshots\SVM-actual-strategy-returns.jpg)


AdaBoost can be used to boost the performance of any machine learning algorithm. As you can see it does a good job till it hits 2018. After 2018 it isn't able to predict well. AdaBoost works best with weak learners such as decision trees with one level. SVMs is a stronger learner you can see from these plots. 

![ABC](screenshots\ABC-actual-strategy-returns.jpg)
