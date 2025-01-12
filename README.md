# **Movie Rating Prediction Using Ensemble Modeling**

This project predicts movie ratings by combining **neural networks** and **matrix factorization** in an ensemble model. The entire workflow, from data preprocessing to model evaluation, is implemented in a single Jupyter Notebook.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Dataset](#dataset)
4. [Notebook Walkthrough](#notebook-walkthrough)
5. [Installation](#installation)
6. [Usage](#usage)

---

## **Project Overview**
The project aims to predict user movie ratings by leveraging an ensemble of **neural networks** and **matrix factorization**. The entire workflow, including data cleaning, exploratory data analysis (EDA), modeling, and evaluation, is implemented in a Jupyter Notebook.

---

## **Key Features**
- **Data Cleaning**: Handled missing values, outliers, and inconsistencies in the dataset.
- **Exploratory Data Analysis (EDA)**: Visualized data distributions and relationships to guide feature engineering.
- **Ensemble Modeling**: Combined neural networks (e.g., MLP) with matrix factorization (e.g., SVD) for improved prediction accuracy.
- **Model Evaluation**: Evaluated performance using **RMSE**.

---

## **Dataset**
The dataset used in this project is the [MovieLens dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset), which contains:
- **Ratings**: User-movie ratings on a scale of 1 to 5.
- **Movies**: Metadata about movies (e.g., title, genre).
- **Users**: Demographic information about users.

---

## **Notebook Walkthrough**
The Jupyter Notebook (`movie_rating_prediction.ipynb`) is structured as follows:
1. **Data Loading**: Load the MovieLens dataset.
2. **Data Preprocessing**: Clean and normalize the data.
3. **Exploratory Data Analysis (EDA)**: Visualize data distributions and relationships.
4. **Modeling**:
   - Build a neural network (MLP) to capture non-linear relationships.
   - Implement matrix factorization (SVD) to capture latent user-movie interactions.
   - Combine the two models into an ensemble for final predictions.
5. **Evaluation**: Measure model performance using **RMSE** and **MAE**.
6. **Results**: Visualize and interpret the results.

---

## **Installation**
To run the notebook locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-rating-prediction.git
   cd movie-rating-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the notebook file: `movie_rating_prediction.ipynb`.

---

## **Usage**
1. Run the notebook cells sequentially to:
   - Load and preprocess the data.
   - Perform exploratory data analysis (EDA).
   - Train and evaluate the ensemble model.
   - Visualize the results.

2. Modify the notebook to experiment with different models, hyperparameters, or datasets.

### **View the Notebook on GitHub**
You can directly view and interact with the notebook on GitHub:  
[`movie_rating_prediction.ipynb`](https://github.com/your-username/movie-rating-prediction/blob/main/movie_rating_prediction.ipynb)

---

### **Alternative: Use Google Colab**
If you prefer to run the notebook in the cloud, open it in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JV4ygrPvma3jA13Mc9_jSdSZTdMSihLv)
