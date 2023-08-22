# Fake news detection  :newspaper:

According to the Collins dictionary, fake news can be defined as 'false, often sensational, information disseminated under the guise of news reporting. Despite the fact that fake news existed for many years, its impact has recently increased. This trend can be easily observed, e.g., by means of Google Trends too. It shows that the phrase 'fake news' has rapidly become more popular since November 2016. Traditionally, fake news was known as rumors or propaganda, mostly used in order to make political or economic gains. The main goal of creating fake news has remained unchanged. However, currently it can spread more easily thanks to the popularity of social networks. The current pandemic reality has led to a serious outbreak of misinformation. It can be very dangerous in social, health-care and political aspects, like in the case of the fake news concerning the COVID-19 pandemic and its connection with the 5G transmission. 

## Objective 🎯
The task is to try to distinguish fake and real informations!

## Methodology ⚙️
### In the project I'll perform:
  - Get 3 datasets from kaggle
  - Data analysis (I'll use pandas-profiler)
  - Data preprocessing
  - Check the quality of the data (convert them to lower case, cut “stopwords”, convert words to their lemma, check the article language)
  - Use bag-of-words algorithm
  - Divide prepared dataset into two subsets (train and test)
  - Use PyTorch library for Logistic Regression model

## Results  :chart_with_upwards_trend:
1. based on 61,500 different texts, PyTorch model has predicted 91% of fake/real texts
2. based on 80,282 different titles, PyTorch model has predicted 84% of fake/real titles
3. in case for titles the score is lower than for texts because of much fewer words
