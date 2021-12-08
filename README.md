# SentimentAnalysis_MobileJKN
Sentiment Analysis of Indonesia’s National Health Insurance Mobile Application using Naïve Bayes Algorithm

## Full Code 
[![Open In Collab](https://colab.research.google.com/drive/1tX3k-voSHFTrnES_HVHC3Os0ARhJ3Di5?usp=sharing)

## Library

- [google-play-scraper](https://pypi.org/project/google-play-scraper/)
- [Sastrawi](https://pypi.org/project/Sastrawi/)
- [pandas](https://pandas.pydata.org/)
- [sklearn](https://scikit-learn.org/stable/)
- [matplotlib](https://matplotlib.org/)

## Dataset
### Dataset : [**MJKN_Review**](https://drive.google.com/drive/folders/12ght6hvBV7lz9hxbmILLYVZGRHB65Rc6?usp=sharing)
Review data collection process is carried out through the Google Play Store Mobile JKN application. In crawling, the google-play-scraper library is used to retrieve reviews on applications with parameters only in Indonesian language reviews. The data taken is approximately 20 thousand data. Some of the data that is a review for the application version 3 and above is separated for analysis. Then the other review data are labeled with a balanced composition between negative and positive labels.
    
## Accuracy
![image](https://user-images.githubusercontent.com/63284781/145137363-be54881a-acf3-4fa7-92f8-5c0d3e9507c5.png)


## Sentiment Analysis
Comparison of Sentiment Reviews for Mobile JKN Application Version 3 and above:

![image](https://user-images.githubusercontent.com/63284781/145137406-85c0bdf4-3e53-4c5b-b075-202200f33390.png)

Visualization of Negative Reviews:

![image](https://user-images.githubusercontent.com/63284781/145137547-5783f903-49fb-4ed6-aa2e-41c2ba2fa489.png)

Visualization of Positive Reviews:

![image](https://user-images.githubusercontent.com/63284781/145137599-1eec4122-9b8d-416f-af22-1662d3cbb8b9.png)
