# Identifying Age-Related Conditions (ICR)

## Overview
This repository contains the code and documentation for my participation in the "Identifying Age-Related Conditions" competition on Kaggle. I am proud to share that I achieved a Silver Medal, ranking in the top 2% of the competition leaderboard.

### Competition Description
The goal of the competition is to use machine learning to predict whether a person has any of three specific medical conditions. Participants are tasked with creating a model trained on measurements of health characteristics to make these predictions. The conditions are categorized into two classes: 
- Class 0: No medical conditions
- Class 1: At least one of the three medical conditions

This competition is crucial as it aims to streamline and simplify the process of identifying these medical conditions, which typically involves a lengthy and intrusive data collection process from patients. Our predictive models aim to expedite this process while ensuring patient privacy by utilizing essential characteristics related to the conditions and encoding them effectively.

By participating in this competition, I contributed to the advancement of medical research by aiding in the discovery of the relationship between various health characteristics and potential patient conditions.

### Context
Aging is a natural process, but it brings along a multitude of age-related health issues. These include heart disease, dementia, hearing loss, arthritis, and more. The field of bioinformatics is growing, encompassing research into interventions that can slow down and even reverse biological aging, thereby preventing major age-related ailments. Data science plays a pivotal role in developing innovative methods to address problems that involve diverse datasets, even when the dataset size is limited.

The competition is hosted by InVitro Cell Research, LLC (ICR), a private company committed to regenerative and preventive personalized medicine. They have state-of-the-art research facilities in the greater New York City area and a team of dedicated scientists who drive their mission to research ways to expedite the rejuvenation of aging individuals.

In this competition, participants work with data related to health characteristics to address critical problems in bioinformatics. With minimal training data, the objective is to build a model that can accurately predict if a person has any of the three medical conditions, with the goal of outperforming existing methods.

### Repository Contents
- **Data**: This folder contains the dataset used in the competition. Due to privacy concerns, the data is anonymous.
- **Notebooks**: This directory contains Jupyter notebooks that detail the data analysis, feature engineering, model building, and evaluation steps.
- **Results**: This folder holds the final model(s) and predictions submitted to Kaggle.

### Achievements
I am delighted to announce that my efforts in this competition resulted in a Silver Medal, placing me in the top 2% of the competition's leaderboard. This achievement reflects not only my dedication to data science but also my commitment to contributing to advancements in the field of bioinformatics.

I've selected XGBoost model for predicting medical conditions. In my case, after extensive hyperparameter tuning, I was able to achieve an accuracy of 98% and a log loss of 50% with a recall of 100% using the XGBoost model. This level of performance is crucial, especially in cases where lives are at stake, as it ensures the reliability and consistency of predictions across different cases.

Feel free to explore the code and documentation in this repository to gain insights into my approach to tackling this challenging problem. Your feedback and collaboration are highly appreciated as we continue to explore new methods for solving complex problems with diverse data in the ever-evolving field of data science and healthcare.

Thank you for your interest in my work!

*Author: Lorenzo Arcioni*

*Date: 11-07-2023*
