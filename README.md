# Day1_Analytics.Setup
Internship Task - Environment Setup & Dataset Seelction
## 📘 Objective
To set up the environment and select a dataset for
future data analytics tasks.
## 🛠 Tools Installed
- Anaconda (Python, Jupyter Notebook)
- Power BI Desktop
## 📂 Dataset Chosen
**Dataset:** cereals
**Source:** [Kaggle –Dataset]
(https://www.kaggle.com/code/rtatman/fun-beginner-friendly-datasets)
import pandas as pd

df = pd.read_csv('cereal.csv')
print(df.head())
print(df.tail())
