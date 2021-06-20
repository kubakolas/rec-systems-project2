# Recommender Systems Project 2 - Neural network recommender

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Author: Jakub Kolasiński and Piotr Zioło (lecturer)

This project contains implementation and evaluation of neural network recommender, used for predicting recommendations of hotel rooms for users. Input dataset consists of historical users interactions (rooms bookings).
Recommender was implemented with pytorch library. Neural network architecture:

- linear transformation layer (input)
- ReLU
- linear transformation layer (output)

### Final results of evaluation

Recommender | HR@10
--- | ---
NNRecommender | 0.253373
AmazonRecommender | 0.200395
NetflixRecommender | 0.206976

### Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8. External libraries needed to run notebooks in this project:
  - numpy 1.19.2
  - pandas 1.1.3
  - matplotlib 3.3.2
  - seaborn 0.11.0
  - torch 1.8.0
  - livelossplot 0.5.4
  - IPython 7.19.0

2. Clone this repository

3. Install Jupyter

4. Run `jupyter notebook` in project folder Project notebooks:
  - `project_1_data_preparation.ipynb` - notebook for data preprocessing
  - `project_2_recommender_and_evaluation.ipynb` - notebook with recommender implementation and evaluation
