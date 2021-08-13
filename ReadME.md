<h1 align="center"> Sentiment Analysis using Natural Language Processing </h1>

<p align="center">
    <a href=" " title="Sentiment Analysis">View Demo</a>
    ·
    <a href=" " title="Sentiment Analysis">Repository</a>
    ·
    <a href=" " title="Sentiment Analysis">Report</a>
</p>


## Table of Contents

1. [Introduction](#introduction)
2. [Manifest](#manifest)
3. [Prerequisites](#prerequisites)
4. [Stepwise Implementation](#stepwise-implementaion)
5. [Installation Steps](#%EF%B8%8F-installation-steps)
6. [Installation of Python Libraries](#-installation-of-important-libraries)
7. [Code Implementation](##-implementation-of-code)
8. [Future Work and Discussion](#-future-scope)

## Introduction

This project is an implementation of Sentiment Analysis using Natural Language Processing. Brief explanation of the concepts Sentiment Analysis and Natural Language Processing can be found in the Report. This code can be used by any organization as a backend code which needs to perform Sentiment Analysis for business purposes. The dataset I used in this code is "Amazon Fine Food Reviews", but Sentiment Analysis can be run on any dataset like Twitter data, Social media comments, Movie Reviews, etc. These datasets are available on Kaggle.com. 



## Manifest

```
- Sentiment_Analysis.ipynb --> Python file in which the project code is implemented.
- Reviews.CSV --> File containing the Dataset. 

```

## Prerequisites

You need to have basic Python knowlegde to understand the code in this project. Also, basic Machine Learning and Natural Language Processing knowledge is required to understand how this project works.

I have implemented this code using Google Colab, so there are no prerequistes as such, but if you want to run this code on your local system, you need to have the following items installed on your PC. 

- Python
- NLTK Library
- Keras
- TensorFlow
- Pandas
- NumPY
- MatplotLIB

## Stepwise Implementation

1. The following is the snapshot of my Google Colaboratory. First we have to mount our Google drive, in which we have to upload our Dataset file which would generally be in .csv or .json format. 

![StepwiseImplementation](Images/snapshot1.png)

2. Then, to display the Dataset we are using Pandas Library. 

![StepwiseImplementation](Images/snapshot2.png)

3. Pre-processing of the data is a crucial part of the data mining process. Knowledge discovery during the training phase is more challenging if there is a lot of irrelevant and repetitive information or noisy and inaccurate data. We have used Stemming, Lemmatization and Stop word Removal to Clean the data.

![StepWiseImplementation](Images/snapshot4.png)

4. It is very difficult to classify a sentiment if we are using complex classes. So here we just have used 2 classes (Positive and Negative) to achieve maximum accuracy.

![StepWiseImplementation](Images/snapshot5.png)

5. This snapshot shows the accuracy of different number of features we selected for the analysis.

![StepWiseImplementation](Images/snapshot6.png)

![StepWiseImplementation](Images/snapshot7.png)

![StepWiseImplementation](Images/snapshot8.png)



















​    

