# Recommender Systems Project 1 - Content Based Recommender

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Author: Jakub Kolasiński and Piotr Zioło (lecturer)

This project contains implementation and evaluation of content based recommender, used for predicting recommendations of hotel rooms for users. Input dataset consists of historical users interactions (rooms bookings).
Recommender was implemented in two versions:
- using random forest based regression,
- using neural network based regression.

### Final results of evaluation

Recommender | HR@10
--- | ---
NeuralNetworkCBUIRecommender | 0.042
RandomForestCBUIRecommender | 0.039
AmazonRecommender | 0.200

### Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8. External libraries needed to run notebooks in this project:
  - sklearn
  - numpy
  - pandas
  - matplotlib
  - seaborn

2. Clone this repository

3. Install Jupyter

4. Run `jupyter notebook` in project folder Project notebooks:
  - `project_1_data_preparation.ipynb` - notebook for data preprocessing
  - `project_1_recommender_and_evaluation.ipynb` - notebook with recommender implementation and evaluation
