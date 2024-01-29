# H&M Personalized Fashion Recommendation System

## Introduction

In this project, we aim to develop a personalized fashion recommendation system for H&M, inspired by this [Kaggle competition](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/overview). The dataset comprises three key components:

- **articles.csv**: Contains information about the products in the catalog.
- **customers.csv**: Provides details about customers (note: customer information won't be used in the models).
- **transactions.csv**: Lists the purchases made by each customer for each date.

The project workflow includes the following steps:

1. **Data Exploration**: We will thoroughly explore the three datasets to understand the underlying patterns and characteristics.

2. **Recommendation Systems**:
    - **Collaborative Filtering**: Utilizing the user-item interaction matrix to provide personalized recommendations.
    - **Hybrid Model**: Combining the user-item interaction matrix with product information to enhance recommendation accuracy.

3. **Focus on 'menswear' Category**: Due to computational constraints, we will concentrate our efforts on the 'menswear' category, as it aligns with our available computing resources.

4. **Library Usage**: LightFM, a Python library for recommendation systems, will be employed to build and implement our models.

5. **Conclusions and Suggestions**: The project will conclude with a detailed comparison of the collaborative filtering and hybrid models. Additionally, we will provide suggestions for potential enhancements to the recommendation system.

## Project Structure

The project structure includes Jupyter notebooks in the `notebooks/` directory, housing code for data exploration, model implementation, and evaluation. The `data/` directory contains the dataset files, and the main documentation is provided in the `README.md` file.

## Dependencies

Ensure the following dependencies are installed:

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- LightFM
- Matplotlib
- Seaborn
