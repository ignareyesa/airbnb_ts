# Airbnb Dataset

This **repository is the second in a series of three** in which various Airbnb datasets are studied using different analysis methods.

- [Part 1: Exploratory Data Analysis](https://github.com/ignareyesa/airbnb_eda)
- [Part 2: Natural Language Processing on reviews](https://github.com/ignareyesa/airbnb_nlp)
- [Part 3: Time Series Forecasting](https://github.com/ignareyesa/airbnb_ts)

![Airbnb](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_Bélo.svg/320px-Airbnb_Logo_Bélo.svg.png)

Airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking.

### Airbnb Data
The data used in this series is collected by [Inside Airbnb](http://insideairbnb.com), and the study is mainly focus in Madrid, Spain until February 2020 (pre-Covid19)

The dataset consists on the following files:
| File Name | Description |
| ------ | ------ |
| listings.csv.gz | Detailed Listings data. |
| calendar.csv.gz | Detailed Calendar Data. |
| reviews.csv.gz | Detailed Review Data. |
| listings.csv | Summary information and metrics for listings in Madrid. |
| reviews.csv | Summary Review data and Listing ID. |
| neighbourhoods.csv | Neighbourhood list for geo filter. Sourced from city or open source GIS files. |

## Part 2:

This part of the project analyses different aspects of the evolution of Airbnb in the city of Madrid. For this purpose, the number of rentals over time is used as a time series.

The analysis first focuses on the data, such as seasonality, growth, correlation, etc.

Subsequently, different training and predictions will be carried out using classical time series prediction techniques such as ARIMA, exponential methods, Naive, etc. Prior to this, the different components of the time series (trend, seasonality, noise) will be analysed and decomposed using different methods. In addition, attention is paid to the concept of stationarity.

Finally, a comparison is made between the different predictive methods on the validation data, reaching interesting conclusions.

---------------------------------------------------------------------------------------------------------------------

Ignacio Reyes Arboledas

**[Go back to website](https://ignacioreyesarboledas.tech/)** &#128522;
