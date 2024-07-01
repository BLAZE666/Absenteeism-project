# Absenteeism-project

This project focuses on analyzing absenteeism data to understand patterns and predict absenteeism based on various factors.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)

## Introduction
Absenteeism from work can be costly for organizations. This project aims to analyze absenteeism patterns using historical data and develop a model to predict future absenteeism. Various factors such as transportation expense, distance to work, age, and others are considered.

## Dataset
The dataset used in this project contains information about absenteeism at work. It includes features such as transportation expense, distance to work, age, daily work load average, body mass index, education level, number of children, number of pets, and the number of hours of absenteeism.

## Project Structure
The project structure is as follows:
absenteeism-project/
│
├── data/
│ └── absenteeism_data.csv
│
├── notebooks/
│ └── Absenteeism_Data_Exploration.ipynb
│
├── src/
│ ├── data_preparation.py
│ ├── model.py
│ ├── train.py
│ └── evaluate.py
│
├── results/
│ ├── model_accuracy.png
│ ├── feature_importance.png
│ └── evaluation_metrics.txt
│
├── README.md
├── requirements.txt
└── main.py
## Requirements
- Python 3.7+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter
