# Covid-Vaccine-Hashtagged-Tweets

## Scope:
Analyze the sentiment of tweets related to the COVID-19 Vaccine and visualize insights.

## Business question: 
Is twitter a viable marketing tool to use for the roll out of our new covid vaccine? 

## Brief Synopsis  

After cleaning up the data set, we were able to run our sentiment analyis (code here): https://github.com/abarnatan/COVID-Twitter-Sentiment-Analysis/blob/main/Sentiment%20Analysis/TweetSentiment.ipynb

Our sentiment analysis evaluates the subjectivity and polarity of each tweet. The subjectivity score (0 to 1) measures how factual the tweet is, with a higher score closer to 1 indicating more opnion and less fact. The polarity score (-1 to 1) indicates whether the tweet is positive (score above 0), negative (score below 0) or neutral (score of 0).

With the subjectivity and polarity scores assigned to each tweet, we then exported the data to a new CSV and loaded it into Tableau and created the following visuals.

![image](https://user-images.githubusercontent.com/70718724/119423905-435be680-bcb9-11eb-9a60-9f83df879d0a.png)

- Above, one can see the increased mentions of the vaccine in tweets as we approached the vaccine's release. On the daily chart big spikes in mentions are clearly visible. These dates were days with big news releases regarding the vaccines. 

----------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/70718724/119424608-a437ee80-bcba-11eb-822e-dc52fe833292.png)

- Next we look at the change in average subjectivity in tweets over time. Surprisingly tweets remained more factual than not. 
- Averaging the positvity monthly shows a significant increase in the sentiment regarding the vaccine over time. People are growing to embrace the vaccine. 
----------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/70718724/119425640-a1d69400-bcbc-11eb-9f00-5ab1345edec4.png)

- Above we can see how the mentions of the top 4 manufacturers increased over time, similarly to the mentions of the vaccine. It is apparent that when people are talking about the vaccine, the brand names are also heavily involved in those discussions. 
- The sentiment towards all 4 brands experienced postive growth in November when all the news regarding their release came out, creating hype and positive marketing buzz. 


### Team: 
Brett Williams, Sung Choo, Aaron Garber-Paul, Alejandro Barnatan, Adam Fancher 

### Data Source:
Our initial dataset was sourced from Kaggle. It's a dataset containing individual tweets from twitter.com from Jan 2020 through March 2021 containing the hashtag #CovidVaccine. 
URL: https://www.kaggle.com/kaushiksuresh147/covidvaccine-tweets

### Contact: 
- Alejandro Barnatan
- ale.barn19@gmail.com
- 503.867.3455
