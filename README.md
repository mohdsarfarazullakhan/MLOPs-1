# MLOPs-1

# Spam Detection MLOps Project

## Overview

This project implements a **Spam Message Classification system** using **Machine Learning and MLOps practices**.
The pipeline includes **data ingestion, preprocessing, model training, and evaluation** managed using **DVC**.

---

## Project Structure

```
├── data/                # Train and test datasets
├── src/                 # Source code files
├── reports/             # Evaluation metrics
├── params.yaml          # Project parameters
├── dvc.yaml             # DVC pipeline
├── requirements.txt     # Dependencies
└── README.md
```

---

## Install Dependencies

Install all required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib nltk wordcloud dvc
```

---

## Run the Pipeline

Execute the full pipeline using DVC:

```bash
dvc repro
```

---

## Dataset

Spam dataset used in this project:
https://raw.githubusercontent.com/vikashishere/Datasets/main/spam.csv

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* DVC
* Matplotlib
* WordCloud

---

## Author

Sarfaraz Khan
