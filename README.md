# Forecasting-price-of-Diamond-(TSA)

## Abstract 
 
This study presents a comprehensive time series analysis of diamond prices, 
aiming to discern underlying patterns and trends in the market. Leveraging the 
Diamond Financial Index (DFX) as a daily indicator available since April 2018, 
we explore the intricacies of the diamond market influenced by various external 
forces. The analysis spans from April 2018 to August 2020, revealing distinct 
phases in diamond price movements characterized by steady growth, 
significant downturns, and subsequent recoveries. Decomposition of the time 
series data uncovers both upward and downward trends, alongside a noticeable 
seasonal component with a two-month period. Statistical tests confirm the 
stationary nature of the data and guide the selection of an appropriate ARIMA 
model. The chosen SARIMAX(1, 1, 1)x(0, 1, 1, 2) model, validated through 
rigorous statistical criteria, offers insights into future price trends, with 
predictions accompanied by confidence intervals. Furthermore, we explore the 
impact of key economic indicators such as inflation rates, interest rates, and 
gold prices on diamond price movements. Our findings contribute to a deeper 
understanding of diamond market dynamics and provide valuable insights for 
stakeholders in the industry, facilitating informed decision-making in this 
complex market environment. 

## Problem Statement 
 
" The problem is to develop a predictive model for diamond prices using daily 
data from April 28, 2018, to June 4, 2021. Leveraging time series analysis 
techniques and the Diamond Financial Index (DFX), we seek to accurately 
forecast future diamond prices, considering market demand, economic 
conditions, and industry trends. The model targets stakeholders such as jewellers, 
investors, and consumers, providing them with valuable insights for informed 
decision-making. 

## Conclusion 

In conclusion, our time series analysis of diamond prices reveals several key 
insights: 
• Trend Analysis: Initially, diamond prices exhibited a steady increase from 
April to August 2018, followed by a significant decrease until August 2020. 
However, this decreasing trend was then followed by an almost linear 
upward trend. 

• Decomposition Analysis: Decomposing the time series data revealed both 
upward and downward trends, as well as a clear seasonal component with 
a period of 2 months. 

• Statistical Testing: Statistical tests confirmed the homoscedastic nature of 
the data and established the stationary property of the differenced data. 
ACF and PACF plots indicated significant correlations at lag 1, guiding the 
selection of the ARIMA model. 

• Model Selection: The SARIMAX(1, 1, 1)x(0, 1, 1, 2) model was initially 
chosen based on statistical criteria such as AIC and BIC. 

• Residual Analysis: While the model demonstrated minimal residuals 
overall, there were some outliers present. The Jarque-Bera test indicated a 
departure from normality in the residuals, and heteroskedasticity was 
observed. 

• Prediction: Future diamond prices were predicted with confidence 
intervals, highlighting the variability in the forecasted values. 

• Validation: The comparison of predicted values with actual values, along 
with confidence intervals, provides a visual assessment of the model's 
performance. 

In summary, our analysis provides valuable insights into the trends and 
patterns of diamond prices, guiding future forecasting and decision-making 
in the diamond market.
