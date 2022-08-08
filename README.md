# YouTube-Trending-Video-Data-Analysis

Performed data cleaning and EDA on 143k YouTube trending videos to investigate and visualize the underlying trends, user behaviors, and factors that affect the popularity of videos

Conducted Feature Engineering and then implemented multiple multiclass classifiers (Ex. KNN, Random Forest, XGBoost) to predict the level of views a video could get

The best classfier reached 73% accuracy.

## Motivation
* YouTube can use this to design a more scientific advertising strategy; for example, they can put important / high ROI ads on videos which have more potential to get large number of views.
* Channels or YouTubers can gain insight of how to make their videos more likely to get on the trending page (Ex. when to post, popular topics, popular/more tags, etc).

## Data Source
https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset 

## Technology Used 
Python (Pandas, Sklearn, Matplotlib, Seaborn, etc)

## Detailed Process
### EDA
Examples:

<img width="453" alt="trend" src="https://user-images.githubusercontent.com/88640967/183321792-823fcf2d-c446-4f19-9abd-f94f7fd2c078.png">

<img width="912" alt="trend_1" src="https://user-images.githubusercontent.com/88640967/183321841-a806416c-7743-483c-9c37-ea5beb6dcb8a.png">

<img width="777" alt="time" src="https://user-images.githubusercontent.com/88640967/183321858-935dc5b2-f9ef-4add-80b1-39f5ccc0fb4f.png">

### Feature Engineering
### Modeling 
Multiple classifiers with time-based cross validation

Model         | Accuracy  | Precision  | Recall   | F1-Score
------------- | --------- | -----------| ---------| ---------
KNN           | 69%       | 68%        | 69%      | 68%
Random Forest | 73%       | 73%        | 73%      | 73%
XGBoost       | 73%       | 76%        | 73%      | 74%








