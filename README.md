# Recommendations with IBM
1. [Installation](#installation)
2. [Objective](#objective)
3. [File Descriptions](#file-descriptions)
4. [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

## Installation
The code was developed using Python 3.6.3. Necessary packages beyond the Python Standard Library are:
- numpy==1.12.1
- pandas==0.23.3
- matplotlib==2.1.0

## Objective
In this project different techniques to recommendation approaches for articles from the [IBM Watson Studio](https://dataplatform.cloud.ibm.com) platform are evaluated including:
- rank-based recommendations
- collaborative filtering
- matrix factorization

The notebook starts with a short explorative data analysis to create a general understanding of the data.

## File Descriptions
**data**
- user-item-interactions.csv
  - user-article interaction data
  - main input for the recommendation techniques investigated
- articles_community.csv
  - article content information

**Recommendation_with_IBM.ipynb**
- notebook applying the different recommendation techniques

**Recommendation_with_IBM.html**
- html version of the Jupyter notebook

**project_tests.py**
- test module for verification

**top_5/10/20.p**
- test outputs for verification

**user_item_matrix.p**
- base for matrix factorization part

## Licensing, Authors, Acknowledgements
The data used in this project was kindly provided by [IBM](https://dataplatform.cloud.ibm.com) in cooperation with [Udacity](https://www.udacity.com/) in the [Udacity Data Science Nanodegree](https://www.udacity.com/school-of-data-science) program.
