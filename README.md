# Waze User Churn Analysis: Hypothesis Testing
***Please note:** If the files do not load promptly, kindly give it a moment or try refreshing the page. GitHub occasionally takes a few seconds to render files, especially if they are content-rich. Your patience is appreciated!*


## Introduction
Welcome to the Waze User Churn Analysis Hypothesis Testing Project! 

Join me as I embark into a detailed analysis of user behavior on Waze, an app that guides millions to their destinations safely and efficiently. While Waze is a travel companion for many, there is a constant challenge of keeping the users engaged to prevent churn - defined as when users stop using the app.


## Business Problem/Context
While the overarching aim is to understand the reasons behind users' discontinuation from using Waze, this project focuses on analyzing the relationship between the mean number of rides and device type. Specifically, it investigates whether there is a statistically significant difference in the mean number of rides between iPhone® and Android™ users.
## Methodology
The analysis began with a visual comparison of driving patterns between iPhone and Android users via box plots. These initial findings indicated a surprising similarity in behavior across the two platforms. To delve deeper, a two-sample Hypothesis Test (t-test) was conducted to analyze the mean number of rides per user on each platform. By proposing a Null Hypothesis (no difference in average drives) and an Alternative Hypothesis (a difference exists), the groundwork was laid for the subsequent t-test.

Using the t-test, I determined the p-value to measure the likelihood of the observed data given the Null Hypothesis. A significance level of 5% was set as the standard for making a statistical conclusion.


## Challenges and Resolutions
One significant challenge was converting categorical device data into a numerical format suitable for t-test computations. To facilitate this, 'iPhone' and 'Android' labels were encoded numerically as '1' and '2', respectively. Additionally, conveying complex statistical results in an easily understandable format for a non-technical audience required simplifying the language used to communicate the findings, ensuring clarity and comprehension.
## Results
The obtained p-value from the t-test is 0.1433, or 14.33%, which exceeds our significance threshold of 0.05, or 5%. Consequently, we fail to reject the Null Hypothesis, leading to the conclusion that there is no statistically significant difference in the mean number of drives between Android and iPhone users.
## Next Steps
* User Feedback Collection: Deploy surveys to understand platform-specific user experiences.
* Feature Enhancement: Use feedback to drive development that enhances user engagement.
* Further Statistical Analysis: Continue Hypothesis Testing to validate marketing strategies.
* Machine Learning Applications: Develop churn prediction models and apply user segmentation for targeted marketing.
## Tools and Packages Used
* Python, Git, Google Sheets
* Python version 3.11.0
* Pandas version 1.4.2
* Matplotlib version 3.5.1
* Seaborn version 0.11.2

## Sharing and Collaboration
The shared Jupyter Notebook and Executive Summary are not only a demonstration of my Data Analytics capabilities but also an invitation to inspire and guide others in their Data Analysis endeavors. Your engagement and feedback enrich the collective learning experience, contributing to a dynamic Data Analytics community.

📌 *The Waze app dataset used in this study was curated by the Google Analytics team in cooperation with Waze for pedagogical purposes. It does not reflect or represent the exact user behavior of the Waze navigation app.*
