# Covid-Tweets-Influence

### Project Definition
-----
With a drastic spike in COVID-19 cases all over the world in the recent past, there is a need to understand the causes for such spikes. Moreover, as various governments scramble to flatten the curve using several methodologies, one major medium for awareness is social media. This project focuses on understanding the impact of tweets related to COVID by influential accounts and how the trend in new cases is affected by such tweets and awareness. This project focuses on building models to find the best fit and correlation between the tweets on COVID-19 cases on a daily basis and every two weeks.

### Description
-----
The major concept behind this project requires data from two major sources, the daily COVID-19 related data and the various tweets posted daily from specific accounts. After data collection is done followed by preprocessing, the K-means clustering method is used to label the data based on whether there is an increase, decrease or no change in COVID cases. Moreover, care must be taken to consider minute and negligible changes in cases, hence self-labeling of data will also be done where a specific benchmark will be set for the data boundaries. Finally, three different models will be built, trained, validated, and tested to find the one with the highest accuracy. Three different algorithms were used for classification alongside the different methodologies of labeling and variances of data. All in all, a total of twelve different models will have been created.

### Results
-----
By validation and testing data it was foud that predictions made using the data for following 14 days provides better results. Validation was used to change hyperparameters of decision tree and random forest. Also, it was found that out of all three algorithms used for the model evaluation, Random Forest shows higher efficiency of all, as its evaluation value for every type of data remains high. Hence, it is recommended that the model made using data for next 14 days using Random Forest is highly reliable. Also, by comparison of validation scores and data scores of two different approach of labeling it was found that labeling by the clustering is better option.
