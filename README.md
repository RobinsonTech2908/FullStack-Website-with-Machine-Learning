# FullStack-Website-with-Machine-Learning
For our this project, we decided we wanted to explore life expectancy around the world. We set out on a journey to unveil the data behind one of the most mysterious controversial questions we all ponder. The term “life expectancy” refers to the number of years a person can expect to live. Life expectancy is important for assessing population health. By understanding how the data is shaped by the demographics you can gain a broader more unbiased look at the world.
Data & Modeling Approach:Our data set was posted on Kaggle and was created using health data from the World Health Organization and economic data from the United Nations. The CSV file covers 193 countries with 22 columns. The time period of the data goes from 2000 to 2015. We also found a CSV from the World Bank that had income groups for the countries over a similar timeline. Before starting the machine learning problem to answer our questions above, we wanted to take some time to explore the data. When exploring the data, we wanted to see how correlated each of our inputs are, to get a sense of what data may be most predictive for estimating life expectancy.
Results of Machine Learning Problem:We looked at many different machine learning models, but in the end, we selected Random Forest Regressor. This model performed very well for our data with an Out Sample R-squared factor of 93.9%. This outperformed the Gradient Boosting Regressor and XGB Regressor models which had R-squared factors of 89.4% and 92.3% respectively. Our model found that the rate of HIV/AIDS deaths is by far the most significant health indicator in predicting life expectancy of a country. The income group of a country is also a significant indicator on the life expectancy of a country. On average, the countries grouped into the “High Income” tier of gross national income per capita had a higher life expectancy.
