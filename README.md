# Analysis of Global Inflation and in Portugal between 1970 and 2022

This project seeks to examine and analyze the inflation rates of countries and major economic unions worldwide.  In particular, analysis of Portugal's inflations is made, while comparing with the European Union and other major economies. The dataset utilized is a publicly available dataset sourced from Kaggle, containing inflation rates of countries from 1970 to 2022.

Dataset: https://www.kaggle.com/datasets/belayethossainds/global-inflation-dataset-212-country-19702022

## Introduction

Inflation, defined as the rate at which the overall level of prices for goods and services increases, resulting in a decrease in purchasing power, is important in decision-making for policymakers and investors. Analyzing data related to inflation both globally and in Portugal can be achieved through a Business Intelligence solution, which enables gaining insights into its impact on the economy and making informed decisions. To this end, a dataset titled "Global Inflation 1970-2022" was utilized, with the data being cleansed and integrated into a single repository through Extract, Transform, Load (ETL) tools. Descriptive and predictive analysis techniques were employed to create two interactive dashboards, allowing exploration of different types of global inflation and comparison with metrics from Portugal. Information obtained from the dashboards led to the conclusion that the median inflation has been decreasing globally, with Consumer Price Index (CPI) and food prices being the components of inflation carrying the most weight. When focusing on the last 15 years in Portugal, it is evident that energy prices have a significant contribution to total inflation. Additionally, there is a trend of increasing inflation across all types in Portugal and Europe from 2020 onwards, which can be attributed to events such as COVID-19 and the war in Ukraine.

## Analysis & main results

  
The primary data source used for analyzing global inflation between 1970 and 2022 includes a dataset titled "Global Inflation Dataset - (1970~2022)" obtained from the Kaggle website (Hossain, 2023). This dataset comprises columns representing countries, their abbreviations and country codes, inflation percentages, types of inflation, and years. Initially, the dataset underwent transformation using the Extract, Transform, Load (ETL) process through Power Query.

Additionally, several measures were created to facilitate data analysis ), such as total inflation, medians for various types of inflation, medians for inflation types in countries and/or periods, and correlations between inflation types for specific countries and periods. Due to the dispersion of values found for inflation, median was chosen over mean as the measure of central tendency, as it is more robust. Furthermore, a column was added to the Global_Dataset_of_Inflation table (EU_status) to classify each country as belonging to the EU or not.

With the obtained data and created measures, it was possible to explore a Business Intelligence solution through a dashboard providing a global overview and main inflation trends between 1970 and 2022, as well as another dashboard focusing on inflation in Portugal over the last 15 years and its comparison with reference countries. The dashboards were produced, using Power Bi.

![Global inflation](https://github.com/natmag93/Global_Dataset_of_inflation/blob/7ccd069435937ee8cf5e408c495fc0063f0f4029/dashboard_1_global.png)

From this dashboard, it's possible to observe that countries with the highest total inflation rates (ranging from 23,000 to 441,000) are located in Central and South America, Africa, and Eastern Europe. Regarding countries with lower inflation rates (between 2 and 59), their location is scattered, but mostly referring to smaller or more recent territories. The same trend is found in the distribution of annual median inflation, where values are higher in Central and South America, Africa, Eastern Europe, as well as the Middle East and Southeast Asia. Overall, Consumer Price Index (CPI) (35.47%) and food prices (32.45%) are the types of inflation carrying the most weight in the global median. Additionally, it can be observed that energy prices (19.49%) are particularly prominent in Europe, which may be due to its energy dependency on other regions. Meanwhile, core Consumer Price Index (coreCPI) (5.5%) values are evident in Europe and the Middle East.

Analyzing the median inflation, it's also noticeable that several peaks have occurred since 1970. The first peak in inflation occurred in 1974 (17.55%), followed by another peak approximately 6 years later, in 1980 (14.59%). These years happened during the period of "Great Inflation," where the oil crisis and other consumer goods explained this increase (Nordhaus & Shoven, 1974). Subsequently, inflation peaks occurred in 1991 and 1994 (8.99% and 8.48%, respectively). Only after 14 years did a new increase occur, reaching 9.08% in 2008. These data are associated with the US real estate market crisis and the bankruptcy of Lehman Brothers (the fourth-largest US bank), which caused a global crisis in 2008 (Zhao, 2023). In 2011, there was a slight increase in inflation of about 5.14%, associated with the request for recovery to the IMF, followed by a slight recovery until 2022, reaching a new record of 9.11%, due to the impacts of COVID-19 and the War in Ukraine (Caporale et al., 2022).

When comparing global inflation with that of Portugal, it's observed that until the 1990s, Portugal had inflation values (total and in different types) well above the global median inflation levels. With entry into the European Union in 1986, inflation decreased in Portugal. Only from 1994 onwards did Portugal's value remain below the global median, being more or less close to the average in the remaining years. However, from 2021 onwards, inflation in Portugal has again exceeded the global median, reaching a value of 12.33% in 2022, compared to the median value of 9.11%.

![Portugal inflation](https://github.com/natmag93/Global_Dataset_of_inflation/blob/7ccd069435937ee8cf5e408c495fc0063f0f4029/dashboard_2_Portugal.png)

From this dashboard, it's possible to observe in more detail the inflation in Portugal over the last 15 years and identify clear contributions of different types of inflation to the overall median inflation of the country. Comparatively with the median in Portugal, it is generally observed that energy prices have a significant contribution to inflation increase in Portugal. Conversely, production prices tend to be lower when energy prices are at lower levels. In 2012 and 2015, drops in core Consumer Price Index (coreCPI) levels to negative values were recorded, -20.14% and -24.85%, respectively, likely associated with unemployment rate evolution and real estate market downturn. Between 2021 and 2022, the effects of COVID-19 and the war in Ukraine contributed to a very sharp increase in energy inflation (23.85%) and production prices (23.00%), resulting in the highest values of the last 15 years (Caporale et al., 2022).

Consumer Price Index (CPI) inflation is a crucial inflation data point to assess the state of a country's economy, assist central banks in adjusting monetary policy, and plan cost-of-living adjustments and investments in general. Analyzing Portugal's position, it can be observed that the country (similar to the median of European Union countries, Australia, and the United States) manages to stay below the global median. However, an increase is observed from 2020 influenced by COVID-19 and the War in Ukraine for most countries except China and Japan, countries that are energy producers and have independence in most of the production of general consumer goods, managing to maintain stability in inflation despite external factors.

Regarding inflation in Portugal, there is a decreasing trend for different inflation components, except for production prices. However, the increase in inflation observed from 2020 is reflected in the forecasts made and in the values for the 95% confidence interval limits, which become considerable from the first year of forecasting onwards.


**Key insights:**


1.  **Global Inflation Trends**: The median inflation has been decreasing globally, with Consumer Price Index (CPI) and grocery prices being the most significant contributors.
    
2.  **Regional Disparities**: Countries/regions in Central and South America, Africa, and Eastern Europe tend to have higher inflation rates compared to others. Meanwhile, smaller or newer territories typically exhibit lower inflation rates.
    
3.  **Impact of Socio-economic Factors**: Socio-economic factors such as COVID-19 and the war in Ukraine have led to significant increases in inflation globally, particularly observed from 2020 onwards.
    
4.  **Energy Prices**: Energy prices play a significant role in driving inflation, especially in Portugal and Europe. There's a notable association between energy prices and overall inflation levels.
    
5.  **Consumer Price Index (CPI)**: CPI is a crucial indicator for assessing a country's economic state. Portugal, along with several other countries, manages to maintain inflation levels below the global median.
    
6.  **Forecasting and Predictive Analysis**: Data from recent years can be used to make predictions about future prices and inflation trends, providing valuable insights for decision-making.
    
7.  **Impact of Events**: Recent events such as COVID-19 and the war in Ukraine have influenced inflation trends, counteracting previous trends of decreasing inflation observed until 2020.



  

## CONCLUSIONS

The Business Intelligence solution developed for the "Global Inflation 1970-2022" dataset allowed for exploration of inflation in its various aspects. From a global perspective, the median inflation has been decreasing, with Consumer Price Index (CPI) and food prices being the most relevant types of inflation. Looking at Portugal, particularly over the last 15 years, the significance of energy prices is notable. It's also possible to observe the rapid impact that socio-economic factors, such as COVID-19 and the war in Ukraine, seem to have on inflation increase, across all its components, observed from 2020 onwards both in Portugal and Europe. It is hoped that these dashboards enable users to explore trends, compare countries, and make informed decisions based on inflation rates. The purpose may include identifying economic patterns, assessing the impact on various sectors, and supporting strategic decision-making for investments or policy planning.

## References

 1. Caporale, G. M., Infante J., Gil-Alaña, L. A., Ayestaran, R. (2022).
    Inflation persistence in Europe: The Effects of the COVID-19
    Pandemic and of the Russia-Ukraine War. CESifo Working Paper, No.
    10071.
 2. Nordhaus, W., & Shoven, J. (1974). Inflation 1973: The Year of
    Infamy. Challenge. 17(2): p. 14-22.
 3. Zhao, Y. (2023) The Price of Risk: Exploring the Impact of the 2008
    Global Financial Crisis. Highlights in Business, Economics and
    Management. 15. p. 175-181.
    
## Authors
[Natalia Magalhaes]([https](https://github.com/natmag93)
[Zita Martins](https://github.com/zitasamartins)
