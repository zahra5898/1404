# 🧪 practices Environment

This repository contains an `environment.yml` file for setting up a Python data science environment using `conda`.

## 📊 Project Description

This project demonstrates a simple **regression analysis** using Instagram user data.  
The dataset, downloaded from [Kaggle](https://www.kaggle.com/), contains various features extracted from Instagram profiles and posts.

The goal is to build a basic regression model to predict a numeric target variable (e.g., number of followers, likes, or engagement rate) based on available features.

This environment provides all necessary packages for data analysis, visualization, and modeling using Python.

📁 *Note:* Make sure you have the dataset downloaded locally or through Kaggle’s API to run the analysis.


## 📦 Included Packages

The environment includes the following essential packages:

- `numpy` – Numerical computing
- `pandas` – Data manipulation and analysis
- `matplotlib` – Data visualization
- `seaborn` – Statistical data visualization
- `scikit-learn` – Machine learning

## ⚙️ How to Use

### 1. Create the environment

Make sure you have [conda](https://docs.conda.io/en/latest/) installed. Then, open a terminal or Anaconda Prompt and run:

```bash
conda env create -f environment.yml
