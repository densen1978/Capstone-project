# Capstone Project

## Customers segmentation and Probability of Purchase Modelling

The Google Analytics data pertains to a fictional company specializing in online retail of electronics. The data source for this project is a publicly available dataset obtained from Kaggle.com, accessible [here](https://www.kaggle.com/datasets/colinpearse/ga-analytics-with-json-columns).

The primary objective of the company is to enhance customer experience, elevate satisfaction levels, and ultimately boost revenue. To achieve these goals, the project employed various data analysis techniques, including RFM segmentation, assessment of customer lifetime value (CLV), and analysis of purchase probability.
The project's intended audience is the sales and marketing executives of the company, keen on comprehending the company's sales performance and pinpointing areas for improvement. It aims to deliver detailed insights into various facets of the company's operations, such as sales and marketing trends, customer analysis and performance improvement.

### The project aimed to answer several questions, including:

•	Who are the company's most valuable customers, and how can the company segment them to improve the effectiveness of targeted marketing campaigns?
•	What is the Customer Lifetime Value (CLV), and how does it vary across different countries? How can the company enhance its value?
•	How can the company estimate the customers' probability of purchase based on their behavioural characteristics, and what marketing strategies can be used to improve targeting of such customers?


## Results 

- [Main Report](Customers-segmentation-and-probability-to-purchase-prediction-report.pdf)
- [Presentation](Capstone presentation - Customers segmentation and probability to purchase prediction.pdf)
- [Interactive Looker Dashboard](https://lookerstudio.google.com/reporting/deb964d9-e23e-4576-808e-0bfafc357cf2)
  

### Queries 

- Customers Segmentation for [non-transacted](https://console.cloud.google.com/bigquery?sq=175663785125:8a32998c4c9542cba5c93b22966ebb40) and [transacted](https://console.cloud.google.com/bigquery?sq=175663785125:32d9e6bcc252461da659595b4d052eda) visitors
- Customers Lifetime Value (CLV): [average revenue per week](https://console.cloud.google.com/bigquery?sq=175663785125:34feebd2b00b42bcbb005e79618a46b5), [cumulative sume of revenue](https://console.cloud.google.com/bigquery?sq=175663785125:7970983a8bed4497995aec700607c72b) and [revenue forecast](https://console.cloud.google.com/bigquery?sq=175663785125:7df53b52536643c39428d16c4bc52a7f)
- [Probability of Purchase Analysis](https://colab.research.google.com/drive/1Ei0U5FfjKwgpa-mxXWWZZ_jnu0KHUBBn?usp=sharing)
