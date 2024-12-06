# DSI_Team_Project-Bankruptcy_Prediction: :bar_chart:

## Project Overview
[This project focuses on analyzing car sales data to derive business insights and build predictive models. We are addressing key business questions to help automotive dealerships and manufacturers optimize their operations, marketing strategies, and pricing models based on data-driven insights.]

## Context
The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange.
## Attribute Information
 Updated column names and description to make the data easier to understand (Y = Output feature, X = Input features)
## Source
Deron Liang and Chih-Fong Tsai, deronliang '@' gmail.com; cftsai '@' mgt.ncu.edu.tw, National Central University, Taiwan
The data was obtained from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction
## Relevant Papers
Liang, D., Lu, C.-C., Tsai, C.-F., and Shih, G.-A. (2016) Financial Ratios and Corporate Governance Indicators in Bankruptcy Prediction: A Comprehensive Study. European Journal of Operational Research, vol. 252, no. 2, pp. 561-572.
https://www.sciencedirect.com/science/article/pii/S0377221716000412

- [data/](https://github.com/Erfan-Nazari/DSI_Team_Project-Car_Sales_Report/tree/main/data)
  - [processed/](https://github.com/Erfan-Nazari/DSI_Team_Project-Car_Sales_Report/tree/main/data/processed)
  - [raw/](https://github.com/Erfan-Nazari/DSI_Team_Project-Car_Sales_Report/tree/main/data/raw)
  - [sql/](https://github.com/Erfan-Nazari/DSI_Team_Project-Car_Sales_Report/tree/main/data/sql)
- [experiments/](https://github.com/Erfan-Nazari/DSI_Team_Project-Car_Sales_Report/tree/main/experiments)
- [models/](models)
- [reports/](reports)
- [src/](src)
- README.md
- .gitignore



## :moneybag: Business Case and Value
### Our project focuses on three key business questions related to car sales:

#### Predicting Car Body Style Preference: :red_car:

Question: Can we predict which category of car (e.g., SUV vs. Sedan) a customer is likely to purchase based on demographic factors and historical purchase data?

Business Value: By understanding which demographic factors influence the purchase of different car categories, businesses can better tailor their marketing efforts and inventory planning. For instance, if certain regions or income levels are more likely to buy SUVs, dealerships can optimize their stock and promotions to meet this demand, leading to increased sales and customer satisfaction.

#### Predicting Best-Selling Car Models: :star2:

Question: Can we predict whether a particular car model will be a "best-seller" (yes/no) based on features, historical sales data, and marketing efforts?

Business Value: Identifying the features and conditions that make a car model a best-seller allows businesses to improve marketing strategies, adjust pricing models, and focus resources on cars that are more likely to perform well in the market. This reduces wasted marketing budgets and improves profitability.

#### Price Estimation for Cars: :moneybag:

Question: Can we estimate the selling price of a car based on its features, brand reputation, and market conditions?

Business Value: A reliable price estimation model helps dealerships to set competitive yet profitable prices based on market trends and car features. This ensures that they are neither underpricing their cars, which can lead to lost revenue, nor overpricing them, which can drive away potential customers.
