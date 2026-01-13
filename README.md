# Python Research Project 
Explore how financial factors like income, economic performance, and the volatility of the financial market affect heart disease death rate in the United States. Our goal is to identify if better health outcomes are associated with financial stability and well-being, or conversely, if financial instability could lead to a higher death rate.

H1: County-level economic stress—measured by GDP growth, unemployment, and uninsured rates—is linked to age-adjusted heart-disease mortality in the U.S.

H2: Counties (or states) with higher median household income have lower age-adjusted heart disease mortality rates.

H3: Greater exposure to market volatility is linked to bigger rises in heart-disease mortality during economic crises.

Key Finding

1. Among the three economic indicators, unemployment consistently shows the strongest and clearest relationship with heart-disease mortality. In contrast, the local uninsured rate and GDP growth are weakly associated with mortality.
2. Across states, counties, and national data, higher median income is strongly associated with lower heart-disease mortality, making income a powerful financial predictor in our study.
3. Economic shocks create volatility, but heart-disease mortality does not automatically spike. Risk depends more on baseline vulnerability (existing health conditions, pre-crisis mortality) and the severity of the local unemployment shock.


Dataset 

We will join three main datasets in Jupyter Notebook:

Yahoo Finance (^GSPC) has past data on the S&P 500, such as highest and lowest prices, closes, adjusted closes, and volumes.

CDC's National Center: According to the CDC's National Center for Health Statistics, heart disease kills about 100,000 people a year, when age is taken into account.

FRED: Like the median household income and the percentage of GDP rise each year, FRED gives data about income and GDP. We will combine all three sets of data into a single DataFrame using the year value.



Note: please disregard the initial error as it would require me to upload all the project dataset.
