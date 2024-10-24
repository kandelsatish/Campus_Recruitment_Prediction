# Campus Recruitment Prediction

This repository contains a project that predicts the placement status of students in a campus recruitment drive using machine learning techniques. The project evaluates multiple machine learning models and combines them using a Voting Classifier for optimal performance.

## Project Overview

The goal of this project is to predict whether a student will be placed based on several attributes, including academic performance, test scores, and personal characteristics. Various machine learning models are used, including:

- Random Forest Classifier
- Decision Tree Classifier
- K-Nearest Neighbors (KNN) Classifier
- Voting Classifier (ensemble method)

The project includes the following key steps:
1. Data Preprocessing
2. Model Selection and Hyperparameter Tuning
3. Model Evaluation
4. Implementation of a Voting Classifier

## Dataset

The dataset used in this project is related to campus recruitment and contains various features, including:

- **Unnamed:**  0: Appears to be an index.
- **StudentId:**  Unique identifier for each student.
- **CGPA:**  Cumulative Grade Point Average of students.
- **Major Projects** : Number of major projects completed by the student.
- **Workshops/Certifications:**  Number of workshops or certifications completed.
- **Mini Projects:** Number of mini-projects done.
- **Skills:**  Number of technical skills.
- **Communication Skill Rating:** Rating of communication skills on a scale.
- **Internship:**  Whether the student has completed an internship (Yes/No).
- **Hackathon:**  Whether the student has participated in a hackathon (Yes/No).
- **12th Percentage:** Marks scored in the 12th standard.
- **10th Percentage:**  Marks scored in the 10th standard.
- **Backlogs:**  Number of backlogs.
- **PlacementStatus:**  Whether the student is "Placed" or "Not Placed".
- **Salary:**  The salary offered to the student if placed.


## Installation

### Prerequisites
Make sure you have the following installed:
- Python 3.6+
- Jupyter Notebook
- Required libraries (Install via requirements.txt)

### Install Dependencies

```bash
pip install -r requirements.txt
```


### How to run?
```
git clone https://github.com/kandelsatish/Campus_Recruitment_Prediction.git 
```
```
cd Campus-Recruitment-Prediction
cd notebook

```
```
jupyter notebook Campus_Recruitment_Prediction.ipynb

```