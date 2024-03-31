## Table of Contents:

- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Rank Estimation with Linear Regression](#rank-estimation-with-linear-regression)
- [College Clustering with K-means Algorithm](#college-clustering-with-k-means-algorithm)
- [Visualizations](#visualizations)
- [Summary Statistics](#summary-statistics)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

With the power of data-driven growth, let’s help reimagine what's possible and empower the next generation of medical professionals. We solve two problems: 
- Challenges in providing accurate counseling due to missing NEET scores and ranks in student profiles.
- Lack of insights into college preferences and attrition rates hinders effective guidance for students' academic choices.

## Data Preparation

Problem 1: Incomplete Data in Student Scores and Ranks Around 40% of the dataset contains missing scores for NEET Ranks.

Our study commences with an in-depth examination of data analytics, aiming to reveal valuable insights capable of influencing academic counseling practices. We scrutinized a sizable dataset comprising 100,000 entries, noting that 40% of the data contained gaps, posing a notable challenge for analysis. 

<p float="left">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Missing%20data.png" width="300" height="300">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Given%20dataset.png" width="500" height="300">
</p>

## Rank Estimation with Linear Regression

To address the problem of colleges experiencing varying levels of attrition (dropout rates) among students and the lack of understanding about factors influencing student attrition, our project delved into Rank Estimation with Linear Regression.

<img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Linear%20Regression%20Prediction.png" width="450" height="450">

## College Clustering with K-means Algorithm

Problem 2: Colleges experience varying levels of attrition (dropout rates) among students. Lack of understanding about factors influencing student attrition.

To address this, our project delved into College Clustering using the k-means algorithm. By applying this technique to a dataset of 400 colleges, we clustered them based on Round 1 closings and attrition rates. To refine our clustering process, we employed methods like the elbow curve and silhouette score. Our goal was to gain insights into the factors contributing to student attrition.

<p float="left">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Elbow%20Curve%20%26%20Silhouette%20Score.png" width="250" height="450">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/State-wise%20Distribution%20of%20Students.png" width="650" height="450">
</p>

## Visualizations

Continuing our analysis, we computed the "Attraction Index" for colleges, providing insights into their appeal. This index, derived from analyzing 324 colleges, revealed a mean score of 94.45, highlighting the prestige of various institutions.

<p float="left">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Attrition%20%25%20by%20State.png" width="350" height="350">
  <img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Average%20Attrition%20%25%20by%20Cluster%20.png" width="350" height="350">
</p>

## Summary Statistics

We then moved on to compute the Attraction Index. Through K-means clustering, a robust unsupervised machine learning algorithm, we categorized the colleges based on their characteristics. This approach sets the stage for developing tailored counseling strategies, catering to the unique dynamics of each college.

<p float="left">
<img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Attrition%20vs.%20College%20Rank.png" width="400" height="300">
<img src="https://github.com/danushkhanna/Statistical-Analysis-and-Prediction-of-National-Medical-Exam-Performance-Using-ML/blob/main/Top%20Colleges%20by%20Attraction%20Index.png" width="400" height="200">
</p>


Next, we conducted model validation by analyzing regional trends and evaluating our predictive models. Through box plots, we visually represented the differences in attrition rates across various states, providing insights into the educational landscape. Additionally, our Linear Regression model achieved a robust R-squared value of 0.8925 during validation, indicating its accuracy in predicting Expected Scores based on NEET Ranks.

## Usage

If you're excited to leverage the potential of our project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required libraries and dependencies listed in the `requirements.txt` file.
3. Execute the provided scripts to experience the power of predictive modeling and college clustering firsthand.

## Contributions

Your contributions are invaluable to us! Whether it's enhancing existing features, introducing novel insights, or refining the codebase, we welcome your input. Feel free to submit issues or pull requests to be a part of this project.

## License

This project operates under the permissive [MIT License](LICENSE), allowing you to explore, modify, and share the codebase.

## Acknowledgements

We extend our gratitude to the open-source community and all the contributors who enrich this project. Your efforts fuel innovation and leave an enduring legacy at the intersection of data analytics and educational guidance.
