# Predicting Retail Gasoline Prices at a Weekly Frequency in the United States 
(Time Series Forecasting)

Problem Statement
Gasoline is a widely used motor fuel globally, with North America having the largest market share, followed by the Asia-Pacific region. 
The increasing demand for personal cars and small aircraft of private planes is expected to drive the growth of the gasoline market. 
The average global gasoline price is currently $1.32 per liter, $93 per barrel, with significant price disparities between countries due to 
varying gasoline taxes and subsidies. According to Data Bridge Market Research, the gasoline market was valued at USD 125,000 million in 2021,
is expected to reach USD 140,811.6 by 2029, and is expected to grow significantly in the coming years. 
Gasoline prices are a major concern for both consumers and businesses due to their impact on the economy. They have significant influence on 
nearly everything, from food to smartphones. Dorothy, Neufeld (2022) notes that oil prices have a considerable impact, accounting for up to 64% 
of food price movements and  have far reaching effect on the world economy, contributing to rising global inflation, slower global growth, and 
rising food insecurity and social unrest. Therefore, accurately predicting the fluctuations in gasoline prices and understanding the dynamics of 
pricing trends are essential for both individuals and organizations to make informed decisions.
In this report, we will provide a detailed analysis of historical gasoline price trends and use this information to make predictions about future 
fuel prices. The report will be useful for individuals and organizations who want to gain a better understanding of gasoline prices and how they 
are likely to change in the future. It will also provide valuable insights for policymakers and industry experts.
Research Question: Given the price history in last 23 years, what will be the optimal forecast value for gasoline prices for next 3 months starting
from 18th of July 2022 to 8th of October 2022?

Dataset 
The detailed datasets are provided by variety of resources, but for this study the dataset presented by 
California Energy Commission will be used (https://www.energy.ca.gov/media/5893). The California Energy Commission is the energy policy and 
planning agency that aims to influence policy makers to prepare for a future powered entirely by 100% clean energy. The dataset they provide contains 
weekly updates on gasoline prices in USA over the past 23 years, comprising 1228 weeks from January 4, 1999, to July 11, 2022. Only three updates are 
missing updates from the dataset: May 8, 2000, September 4, 2000, and August 27, 2001. The dataset includes two price values: Branded Fuel Prices (BFP)
and Unbranded Fuel Prices (UFP), and it encompasses the following variables for both BFP and UFP):

1-	Date
2-	Branded Fuel - Distribution costs, and profits
3-	Branded Fuel - Crude oil cost
4-	Branded Fuel - Refinery costs and profits
5-	Branded Fuel - State underground storage tank fee
6-	Branded Fuel -State and local sales tax
7-	Branded Fuel - State exercise tax
8-	Branded Fuel - Federal exercise tax 
9-	Branded Fuel - Average retail prices
10-	Unbranded Fuel - Distribution costs, and profits
11-	Unbranded Fuel - Crude oil cost
12-	Unbranded Fuel - Refinery costs and profits
13-	Unbranded Fuel - State underground storage tank fee
14-	Unbranded Fuel -State and local sales tax
15-	Unbranded Fuel - State exercise tax
16-	Unbranded Fuel - Federal exercise tax 
17-	Unbranded Fuel - Average retail prices
