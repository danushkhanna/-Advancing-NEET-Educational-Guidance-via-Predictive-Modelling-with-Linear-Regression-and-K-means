National Eligibility cum Entrance Test (NEET) Rank Estimation and College Clustering using Linear Regression and K-means Algorithms.

## Table of Contents:

- [Introduction](#introduction)
- [Predictive Rank Estimation](#predictive-rank-estimation)
- [College Clustering](#college-clustering)
- [Attraction Index Computation](#attraction-index-computation)
- [Regional Trends Analysis](#regional-trends-analysis)
- [Model Validation](#model-validation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

In the ever-evolving landscape of academic counseling, the integration of data analytics and predictive modeling has emerged as a revolutionary approach. This repository dives deep into the realms of data exploration, predictive modeling, and clustering methodologies, all aimed at redefining the NEET educational guidance process.

## Predictive Rank Estimation

Our journey begins with a profound exploration of data analytics, uncovering hidden gems that have the potential to reshape academic counseling. We delved into the nuances of the dataset, juggling a vast repository of 100,000 entries. Intriguingly, 40% of this data contained gaps, presenting a unique challenge.

<p float="left">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Missing%20data.png" width="300" height="300">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Given%20dataset.png" width="500" height="300">
</p>

## College Clustering

Next, we dived into the realm of Linear Regression, leveraging this technique to forecast Expected Scores from NEET Ranks. We navigated the complexities of the dataset, weaving predictions into its fabric to provide personalized guidance. The outcome was a predictive model that enables tailored interventions, even for students with missing data.

<p float="left">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Elbow%20Curve%20%26%20Silhouette%20Score.png" width="300" height="500">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/State-wise%20Distribution%20of%20Students.png" width="700" height="500">
</p>

## Attraction Index Computation

The project then embarked on the journey of K-means clustering, a powerful unsupervised machine learning algorithm. By applying K-means to a dataset of 400 colleges, we clustered them based on Round 1 closings and attrition rates. This strategic clustering lays the foundation for more informed counseling strategies, tailored to each college's unique story.

<img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Attrition%20vs.%20College%20Rank.png" width="500" height="500">

## Regional Trends Analysis

One of the highlights of our analysis was the computation of the "Attraction Index" for colleges. This index quantifies the allure of colleges, assigning scores that provide valuable insights. Through rigorous analysis of 324 colleges, we discovered a mean "Attraction Index" of 94.45, shedding light on the prestige and appeal of various institutions.

<img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Attrition%20%25%20by%20State.png" width="500" height="500">

## Model Validation

Our exploration didn't stop there. We delved into regional trends, unearthing intriguing variations in attrition rates across different states. Visualizing this data through box plots illuminated the diverse academic landscapes of various states. To validate our predictive models, we obtained an impressive R-squared value of 0.8925, confirming the efficacy of our approach.

<img src="https://raw.githubusercontent.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/main/Linear%20Regression%20Prediction.png?token=GHSAT0AAAAAACEW24XLLZTOOATMGDFJDJLWZQJY3HA" width="500" height="500">

## Usage

If you're excited to harness the potential of data analytics and predictive modeling in the field of NEET counseling, follow these steps:

1. Clone this repository to your local machine.
2. Install the required libraries and dependencies listed in the `requirements.txt` file.
3. Execute the provided scripts to experience the power of predictive modeling and college clustering firsthand.

## Contributions

Your contributions are invaluable to us! Whether it's enhancing existing features, introducing novel insights, or refining the codebase, we wholeheartedly welcome your input. Feel free to submit issues or pull requests to be a part of this transformative project.

## License

This project operates under the permissive [MIT License](LICENSE), allowing you to explore, modify, and share the codebase.

## Acknowledgements

We extend our gratitude to the open-source community and all the contributors who enrich this project. Your efforts fuel innovation and leave an enduring legacy at the intersection of data analytics and educational guidance.
