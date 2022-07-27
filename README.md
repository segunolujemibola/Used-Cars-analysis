# (Used Car Data Exploration)
## by (Olujemibola Oluwasegun)


## Dataset
This dataset contains different types of used cars and their features. The dataset was gathered from kaggle's datasets(https://www.kaggle.com/datasets/shubham1kumar/usedcar-data). The aim of the analysis is to find features are significant to predicting the prices of the cars.
The dataset contains data of  7901 used cars, each with 18 features like, the selling price, no of seats, km driven, engine power,max power and several other features


## Summary of Findings
From my exploration I found out that there was a fairly strong relationsip between the selling price and the engine maximum power(max_power). The relationship between price and max_power is fairly linear when logarithmic transformation is applied to price. The slope is very gently with change just being noticed around the 300,000 price value. I also found out that, price tends to decrease as the number of owners of a car increases. For other categorical vairables, transmission and fuel mainly. The price differs between their variable levels. For transmission,automatic transmision is costlier than manual transmission.
For the data wrangling process,I did not do any data cleaning because I found out that, the data was in a tidy format and it had high quality after performing data assessment.

Asides my main aim, I found out that most of the cars in the dataset were not sold(less than 30% sold).Upon investigating the possible cause,I found no difference between cars being sold and not sold . The occurence seems to be independent of the features in the dataset.

## Key Insights for Presentation

For the presentation, I am focusing on the influence of max_power and the following categorical varables, transmission and no of owners,on the selling price. I start by introducing the distribution of the selling price variable followed by the distribution of the max power variable. The I'll plot the scatter plot of the two variables.
Next, I'll introduce the categorical variables and their price and max_power distirbution .Finally I'll show the differences in price between the most significant categorical variables(transmission and no of owners). 