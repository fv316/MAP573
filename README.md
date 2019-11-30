# MAP573 - Time Series Forecast

## Presentation:
Presentation: https://docs.google.com/presentation/d/1qFmQMnXmSfjJPaBi75d9R2WJuk4bxjiIsOM6VnXIkyM/edit?usp=sharing


## Useful links:

https://www.kaggle.com/apoorvabhide/energy-consumption-time-series-forecasting-in-r/notebook#Introduction
https://www.kaggle.com/c/global-energy-forecasting-competition-2012-load-forecasting/dat
Recency Effect https://www.sciencedirect.com/science/article/pii/S0169207015001557?via%3Dihub
Weather Station Select: https://www.sciencedirect.com/science/article/pii/S0169207014001319?via%3Dihub
Hierchical Forecasting: https://www.sciencedirect.com/science/article/pii/S0169207013000757


## About usage and folder structure:

The python jupyter notebook (with the code of the RNN) is whitin the root directory. 
Other important files/folders: 

+ **./Data** stores all used data
+ **./powerpoint** stores ppt presentations
+ **./src** stores python an R scripts 
+ **./RVis** keeps all the code to generate the R Visualisation tool
+ **./Suppor Material** keeps articles, notebooks, etc, with relevant information



## Necessary python libraries in notebook: 

+ TensorFlow
+ Keras
+ tqdm
+ pandas
+ matplotlib
+ numpy
+ sklearn

## How to run R visualisation app:

Required libraries:

+ dygraphs (interactive Time Serie Plot)
+ data.table
+ xts (time serie object)
+ tidyverse
+ lubridate
+ sqldf (sql commands in dataframes)
+ shiny

Run, in this root folder: 

```{r}
   > library(shiny)
   > shinyApp("RVis")
```