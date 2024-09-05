# Phase 3 Project

This repository contains the Phase 3 project for the data science course. The project involves analyzing water pump functionality data to predict the operational status of water pumps in Tanzania.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Required Libraries](#required-libraries)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project was completed as part of the Phase 3 curriculum for the data science course. The main objective of this project is to develop a machine learning model that can predict the functionality status of water pumps in Tanzania based on various features such as water quality, quantity, location, and pump type.

### Final Project Submission Details

- **Student Name**: Alex Irungu
- **Group**: Group 1
- **Student Pace**: Part-Time
- **Scheduled Review Date/Time**: Phase 3
- **Instructor Name**: Samuel Karu

## Project Structure

The repository contains the following files and directories:

- `index.ipynb`: Jupyter Notebook containing the project code, analysis, and results.
- `README.md`: This README file.
- `requirements.txt`: List of Python packages required for this project.
- `data.csv`: Datasets used for this project.

## Installation

To run the code in this repository, you will need to have Python and Jupyter Notebook installed. You can install the necessary Python libraries by running:

```bash
pip install -r requirements.txt
```

## Usage

To view and run the project:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `index.ipynb` in the Jupyter Notebook interface.
5. Run the cells in the notebook to see the analysis and results.

## Required Libraries

The following Python libraries are used in this project:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import LabelEncoder, OneHotEncoder
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report
import warnings
```

These libraries provide essential functionality for data manipulation, visualization, and machine learning tasks.

## Results

Our analysis led to several key findings:

1. The Random Forest model was selected as the final model, achieving the highest performance metrics (Accuracy: 66%, Precision: 66%, Recall: 66%, F1_Score: 62%).
2. Water quality and quantity are crucial factors in pump functionality, with soft water and sufficient water quantity correlating with better functionality.
3. There are significant regional variations in pump functionality across Tanzania.
4. Different water sources (e.g., springs, shallow wells, boreholes) have varying levels of reliability and maintenance needs.
5. Water scarcity is strongly correlated with pump non-functionality.

For a more detailed breakdown of the results and their implications, please refer to the `index.ipynb` notebook.

## Author
This code was contributed by Alex Irungu.

## Contributing

While this is a course project, constructive feedback and suggestions are welcome. Please feel free to fork this repository and submit pull requests, or open issues to discuss proposed changes or improvements.