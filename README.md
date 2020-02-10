# Corona Prophet Prediction

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EXYNOS-999/corona_prophet/master)


<iframe src="https://ghbtns.com/github-btn.html?user=exynos-999&type=follow&count=true" frameborder="0" scrolling="0" width="170px" height="20px"></iframe>

2019-nCoV Global Cases by Johns Hopkins

https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

![Coronavirus 2019-nCoV Global Cases by Johns Hopkins CSSE](media/interactive_map.png)

>***Can we build an original, comprehensive solution to help handle the crisis?***

>***We are looking to predict, visualize and act to contain the 2019 n-Coron Virus, through the power of data science.***

With the objective of understanding and minimizing epidemic spread, we devloped an method to accuractely predict and visualize the necessary features relating to **n-Corona virus** using *Time Series Analysis* and *EDA*.

The following dataset has been taken from 
[Novel Corona Virus 2019 Dataset:](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) along with custom feature engineering by extracting data from web.

![](media/dataset_viz_0.png)

![](media/dataset_viz_1.png)



### Kernels 

* Mathematical Simulation of nCOV Transmission Model.
* Feature engineeing and analysis of their effects in predicting extent of the nCOV Virus.
* Prediction model for expected new cases in the Mainland China region. 
* Prediction model for expected new cases in the Mainland China region.

![](media/prophet.jpg)



## Mainland China* Death Trends

Following trend indicates **daily,weekly,monthly** trend in confirmed death rates in China .It was obtained using [Prophet](https://facebook.github.io/prophet/) an open source tool for Time Series analysis.

![](media/china/trend_chart_china.png)

*Mainland China includes SAR provinces and Hong Kong.

## Uncertainty in Prediction


![](media/china/uncerntainty_prediction.png)

## Prediction with uncertainty and changepoint  

![](media/prediction_with_uncertainty.png)


![](media/changepoint.png)

## Long-term forecast and trends

![](media/long_term_forecast.png)

![](media/trend.png)

## Correlation Matrix 

**_Pearson’s correlation coefficient is the test statistics that measures the statistical relationship, or association, between two continuous variables.  It is known as the best method of measuring the association between variables of interest because it is based on the method of covariance.  It gives information about the magnitude of the association, or correlation, as well as the direction of the relationship._**

Features include  *StockPrice*,*Lowest/Highest Daily Temperature*,*Humidity(%)*,*StockPrice*,*Currency*,search terms such as *cold,etc*.

![](media/Feature_Correlation_Matrix.png)


## Feature Relationships
We explore the relationship of various features with the spread of the disease  by plotting graphs.

- Stock Price Relationship

![Stock](media/StocksEU.png)


-  Humidity  Relationship

![Stock](media/Humidity.png)


-  Flights Search  Relation

![Stock](media/CDvsFlights.png)


-  Lowest Temperature  Relation

![Stock](media/CDvsFlights.png)

# Simulations

![](media/epidemic_simulation.gif)



![](media/infection_V6.gif)



# References and citations 

[1] https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

[2] https://www.cdc.gov/coronavirus/2019-ncov/index.html

[3]https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

[4] https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance

[5]https://www.maa.org/press/periodicals/loci/joma/the-sir-model-for-spread-of-disease-the-differential-equation-model

[6]https://facebook.github.io/prophet/

[7]https://ai.googleblog.com/2017/07/facets-open-source-visualization-tool.html

[8]https://scikit-learn.org/stable/

[9]https://seaborn.pydata.org/

[10]https://colab.research.google.com/





