![image](https://github.com/randellmwania/Movie-Recommendation-System/assets/122815372/6d1dcbf3-10bd-4872-b782-2a99d6aeb1bd)


## MOVIE RECOMMENDATION SYSTEM 
## Overview
This project consist of building a movierecommendation system. Our project aims to enhance customer satisfaction by providing personalized movie suggestions, fostering engagement, and driving user retention



## Business and Data Understanding
The primary goal is to enhance the user experience by providing personalized movie recommendations. The system will suggest the top 5 movies to each user based on their previous ratings. This tailored recommendation system aims to boost user engagement, satisfaction, and overall retention within a movie-streaming platform.
## Problem Statement
With so many movie alternatives available nowadays, people find it difficult to choose films that suit their tastes due to information overload. Manual searches take a lot of time, which causes decision fatigue and lowers user engagement on a platform. A customized movie recommendation system that makes use of user-specific information and collaborative filtering methods will address this. By creating an effective recommendation engine that smoothly connects with user profiles, this project seeks to improve user satisfaction and retention by enabling a more efficient and enjoyable exploration of the extensive movie catalogs.
## Components
* The [Jupyter Notebook](https://github.com/Wairimukimm/Customer-churn/blob/main/Untitled.ipynb) is the main deliverable. It contains the details of the approach taken and the methodology. It contains data cleaning, exploratory data analysis, data preparation for modelling and building the recommendation system.

* The [Presentation](https://github.com/Wairimukimm/Customer-churn/blob/main/presentation.pdf) is the non technical Presentation of the project. It contains the objectives, problem statment, model evaluation, findings and recommendations.

* The dataset used for this project can be found in [Kaggle](https://grouplens.org/datasets/movielens/latest/)




## Technologies
* Python version: 3.6.9
* Matplotlib version: 3.1.3
* Seaborn version: 0.9.0
* Pandas version: 0.25.1
* Numpy version: 1.16.5

    
## To begin

* Clone this [repository](https://github.com/Wairimukimm/Customer-churn)
* Download the [Dataset](https://grouplens.org/datasets/movielens/latest/) used and install any technologies if necessary


## Data Wrangling
In this section, we did data preparation which invloved:
* Checking for missing values, removing duplicates, renaming columns and dropping unnecessary columns to ensure the data is clean and suitable for analysis and modelling.



## Explaratory Data Analysis(EDA)
We perfomed both univariate and bivariate analysis to uncover patterns in the dataset. 
* The top 5 genres were drama, comedy, thriller, action and romance
* The most viewed movies were pulp fiction, fight club, star wars and inception

## Collaborative filtering

* The recommendation system will heavily rely on collaborative filtering as its primary mechanism. This technique involves making predictions about a user's preferences by aggregating insights from numerous users. 

* Approach: Singular Value Decomposition (SVD) is employed for collaborative filtering. This technique analyzes users' historical ratings to make personalized movie suggestions.

* Implementation: The Surprise library is used for collaborative filtering. The model is trained on a dataset containing user ratings.

## Content Based Filtering System
* Content-based filtering is a recommendation system technique that suggests items such as movies to users based on the characteristics of items and the preferences expressed by the user. The primary idea is to recommend items that are similar to those the user has liked or interacted with in the past.

* Approach: Content-based filtering relies on movie attributes, such as genres and titles, to recommend similar items.
* Implementation: A TF-IDF vectorizer is used to convert movie genres and titles into numerical representations. Cosine similarity is then calculated to find movies with similar content.
## Conclusion

 
