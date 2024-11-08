# Mobile Price Prediction Analysis (2024)

This project is aimed at predicting mobile phone prices in 2024 based on various features of the phones using machine learning algorithms. The analysis uses data from a mobile phone dataset and explores key factors influencing mobile prices such as screen quality, size, weight, and storage.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Seaborn**: For statistical data visualization.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Kagglehub**: To fetch and manage datasets directly from Kaggle.

## Project Overview
The goal of this project is to predict mobile phone prices using machine learning models. By analyzing various mobile phone features, we aim to uncover which factors have the most impact on mobile pricing. We use Random Forest and other machine learning techniques to train and evaluate our models.

## Conclusion

- **Prediction Accuracy**: Using machine learning algorithms, such as Random Forest, mobile prices can be predicted with **80% accuracy**.
- **Key Variables**: Features like **screen quality**, **screen size**, **weight**, and **storage** were found to be the most important factors affecting mobile prices.
- **Less Impactful Features**: Mobile features such as **NFC** and **Foldable** had minimal influence on mobile pricing in this dataset.
- **CPU Factors**: Although **CPU** components were not measured in this algorithm, they are widely known to play a critical role when consumers choose a mobile phone, and should ideally be included in future analyses.

## Dataset
The dataset used in this project contains various mobile phone specifications, such as screen size, storage, weight, features (like NFC, Foldable), and price. The dataset was sourced using Kaggle API through **Kagglehub**.

## How to Run the Project
1. Clone this repository.
   ```bash
   git clone https://github.com/jgomezba/DataScience-Mobiles-analysis.git
   cd path/to/your/git/repository/cloned

2. Launch Jupyter notebook from Python
    ```Python
    jupyter notebook

3. Open main.ipynb