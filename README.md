# Mood predictions based on personal data analytics.

[![PyPI - Python](https://img.shields.io/pypi/pyversions/iconsdk?logo=pypi)](https://pypi.org/project/iconsdk)
---
PyCaret 
---
_The inspiration for this project was trying to find an answer to one of the eternal questions. ‘What is happiness?’ ‘What makes us happy?’ In my opinion, this is more of a philosophical question, but I chose to approach this from a more scientific point of view._ 

### Project Status
Project is: _complete_

## Table of Contents
* [General Info](#general-information)
* [Project Components](#project-components)
* [Room for Improvement](#room-for-improvement)

## General Information
In this project, I tried to define happiness and depression from a more scientific point of view. 
Since our mood affects our productivity at work or school, our communication with others, and of course our health I decided to undertake this project.
I completed this research project by predicting mood states by using various ML models. These models were trained on my personal data which included the most important factors influencing our mood. (Weather, physical actvity, nutrition, social life, stress, menstrual cycle and some others). 
To collect the data I used different data sources.
1. Period and Ovulation tracker (Clue). (from this application I obtained my target attribute - mood feature)
2. Nutrition trackig app (FatSeret)
3. Apple Health
4. Smart Scales (Renpho)
5. Google Calendar
6. Historical weather data (Met Éireann)
My dataset in the end had data only for 76 days.

### The purpose of the project
The initial idea of this project was to outline the factors that could possibly affect the mood state. The main goal was to find out what can be changed in the everyday lifestyle to become happier and decrease the risk of mental illnesses.
One of the application of this project is to provide some insights in order to improve the user’s mood.
Another use case is primarily aimed at identifying the user’s potential depression.

## Project Components 
#### 1. A project report. [a relative link](Report.pdf). It includes the initial idea and inspiration of the project. Data collection with detailed description of data sources. EDA analysis including graphs and results with extensive explanations. Commercial potential. App design prototype. Ethical issues. Conclusions. References.
#### 2. Jupyter Notebook. [a relative link](Mood_Analysis.ipynb). This python notebook includes all the relative code. All of the experiments including EDA, data encoding, feature engineering, synthesising additinal data, visualisations, machine learning. 
#### 3. Dataset. [a relative link](personal_data_merged.csv) The original dataset that is being used in the Jupyter notebook. Detailed data description. 

## Room for Improvement
My project started with a hypothesis about whether it is possible to make a person happier with the help of AI. I found this question quite childish and was relatively sceptical about the results. Nevertheless, the results of my research showed that this is a rather serious problem that affects millions of people, because even a prolonged state of apathy can lead to more severe mental illnesses, including depression.
I found out that this is a complex and at the same time subjective problem. But despite this, my experiments have shown that this is a feasible task. I have obtained some useful insights and accuarte predictions for some of the mood states that can be found in the Report. 
Since mood predictions is a very personal problem to reduce the risk of bias I would like to collect more data from other individuals so that I can conduct more efficient experiments. I also believe that professional experts in psychology and mental health are needed to solve this problem. After all, inaccurate AI predictions can only harm human health.
