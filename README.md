# Recommendations with IBM
## Overview

This project focuses on building recommendation systems using data from the IBM Watson Studio platform. The notebook explores various recommendation techniques, including rank-based, user-user collaborative filtering, and matrix factorisation.

## Table of Contents

1. Exploratory Data Analysis
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Content Based Recommendations (Extra - Not Required)
5. Matrix Factorisation

## Installation

To run this notebook, you'll need to install the following Python libraries:

```
pandas
numpy
matplotlib
```

You'll also need to have the project-specific `project_tests.py` file in the same directory.

## Usage
1. clone the repo
   ```
   git clone https://github.com/romanwolf-git/recommendations_ibm.git
   ```
2. Run the notebook cells sequentially to perform data cleaning, analysis, and visualisation.

## About the Data

The project uses two main datasets:

1. `user-item-interactions.csv`: Contains user interactions with articles.
2. `articles_community.csv`: Contains information about the articles.

## Methods

The notebook implements several recommendation techniques:

1. **Rank-Based Recommendations**: Recommends the most popular articles based on interaction frequency.

2. **User-User Based Collaborative Filtering**: Finds similar users and recommends articles based on what similar users have interacted with.

3. **Matrix Factorisation**: (Not implemented in the provided code snippet)

## Acknowledgements & Licensing

The project is part of the Udacity course Data Scientist. The data is provided by IBM Watson Studio platform.
