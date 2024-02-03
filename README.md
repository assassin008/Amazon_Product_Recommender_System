# Amazon Product Recommender System

## Overview
This Amazon Product Recommender System leverages collaborative filtering techniques to provide personalized product recommendations based on user ratings. Built using Python and the Surprise library, the system analyzes the `ratings_Electronics.csv` dataset to predict user preferences and suggest relevant products.

## DataSet
The data set "ratings_Electronics.csv" is available at : https://www.kaggle.com/datasets/saurav9786/amazon-product-reviews

## Features
- Utilizes Singular Value Decomposition (SVD) for accurate prediction of user-item interactions.
- Offers top-N product recommendations tailored to individual user profiles.
- Efficient handling of large-scale datasets with over 7 million reviews.

## Installation

### Prerequisites
- Python 3.x
- pip

### Libraries
To install the required libraries, run the following command in your terminal:

```bash
pip install pandas numpy scipy scikit-surprise matplotlib seaborn
