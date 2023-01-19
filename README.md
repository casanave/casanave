### Hi there 👋 I'm Louis 

I am a storyteller who is passionate about data, writing, public speaking and building community. I hold a special place in my heart for Natural Language Processing (spaCy, NLTK,) and inferential modeling (statsmodels, scikit-learn, and using SHAP or LIME explainers.) Additionally, I have experience with data wrangling, scraping, and engineering, (pandas, selenium,) and using machine learning algorithms (decision tree/Random Forest, Linear and Logistic regression analysis.) I also adore making visualizations (seaborn, matplotlib,) and using maps (folium.) I have experience using APIs (Google, Yelp, Twitter) as well as using public data sets (NYC Open Portal.) A firm believer in a well-written code comment, accessible documentation, and better coding with functions. 

# Projects 

### HurriHelp 
[ReadMe](https://github.com/casanave/Hurri_Help)
[Main Code Notebook](https://github.com/casanave/Hurri_Help/blob/main/analysis_and_modeling_notebook.ipynb)

##### Natural Language Processing project using sentiment analysis to help find Hurricane Ian survivors in distress, and provide them with links to National Disaster Distress Helpline and FEMA Info.  
- Scraped Twitter for over seven thousand original tweets 
- Used three different sentiment analysis analyzers (TextBlob, VADER, and a distillBERT model) to find the sentiment of tweets
- Used analysis to explore the most common words in negative and positive sentiments. 
- Used Random Forest, Naive Bayes, XGBoost, and Catboost on vectorized tweets for 80% precision in the best-tuned model
- Used Lime Text Explainer for the inferential understanding of the most common words in data, and found words most likely to be in negative tweets

###  Fetal Health Project
[ReadMe](https://github.com/casanave/fetal_health)
[Main Code Notebook](https://github.com/casanave/fetal_health/blob/main/final_notebook.ipynb)

##### Health information project for early detection and faster diagnosis of pathological fetal heartbeats.  
- Built data pipelines and created two early detection algorithms ready for A/B testing
- Tested Logistic Regression, K-Nearest-Neighbors, Support Vector Machine, and Random Forest for the highest recall of pathological class of 92%
- Used OneVsRest wrapper and GridSearchCV for model specialized to pathological class and best-tuned machine. 
- Used Shap Values for the inferential understanding of the model, and reduced dimensionality of the algorithm by five input features for 90% recall

### Seattle Section 8 Expansion Project 
[ReadMe](https://github.com/casanave/Seattle_Section_8_Expansion_Project)
[Code Notebook](https://github.com/casanave/fetal_health/blob/main/final_notebook.ipynb)

##### Built inferential linear regression model to inform the city of Seattle on where to build new public housing.
- Performed in-depth EDA, determining the effect of renovations over time on property values for efficient budgeting. 
- Used Google’s geocoding API and selenium to engineer features: how close each property is to the closest public school, hospital, and police station for infrastructure insights related to property values
- Visualized multicollinearity in seaborn with correlation heat maps, for feature selection 
- Iteratively constructed eight versions of the linear regression model, removing features with low P Values for an R-Squared score of 83%
Produced automated findings report for human analysis of coefficients, including inferential analysis of inequity by zip code

### Film Analysis Project
[ReadMe](https://github.com/casanave/Film_Analysis_Project)
[Code Notebook](https://github.com/casanave/Film_Analysis_Project/blob/master/Film_Analysis_Project%20.ipynb)

##### Advised hypothetical Microsoft Studios on what kinds of feature films to produce by analyzing box office financial data.  
- Aggregated data using Pandas and visualized in Seaborn to discover the most popular genres by net profit: Animation, Adventure, Fantasy and Family films 
- Pivoted Table to aggregate films of most popular genres by release date to infer seasonal trends: best months for releasing new films in most popular genres to be June, July, May, March, November, and April
- Inferred best run time for new films is between 120-150 minutes based on historical popularity 

### Stop And Frisk Project

[ReadMe](https://github.com/casanave/stop_and_frisk_2020)
[First Code Notebook](https://github.com/casanave/stop_and_frisk_2020/blob/main/zipcode_frequency.ipynb)

##### In-depth analysis, static visualization, time series modeling, and Tableau Public dashboard for public transparency. 
- Visualized frequencies of stops and consent-asked in 2020 NYPD stop and frisk data towards understanding inequities in policing. 
- Investigated anomalies and outliers, patterns, and relationships for insights into different zip codes and communicate results with choropleth maps and graphs made in Folium and Seaborn
- Resulting artical [Using Folium On Police Data](https://towardsdatascience.com/using-folium-on-police-data-3207e505c649) published by Towards Data Science 

[ReadMe](https://github.com/casanave/stop_and_frisk_2021)
[Code Notebook](https://github.com/casanave/stop_and_frisk_2021/blob/main/2021_analysis.ipynb)

- Used Pandas to clean 2021 Stop and Frisk Data for later use in a Tableau public viz
- Resulting Visualization used in article [EDA with Tableau: 2021 NYPD Stop-and-Frisks by Demographics](https://medium.com/towards-data-science/eda-with-tableau-2021-nypd-stop-and-frisks-by-demographics-e5e88eb43939) published by Towards Data Science

[ReadMe](https://github.com/casanave/time_series_stop_and_frisk)
[Main Code Notebook](https://github.com/casanave/time_series_stop_and_frisk/blob/main/Stop_And_Frisk_Timeseries_Notebook-Monthly.ipynb)

- Used pandas to clean 10 years of Stop and Frisk Data for later use in a Tableu public viz showing demographic breakdown: https://public.tableau.com/views/2011-2021NYPDStopandFrisksbyRacePrecinctandOutcome/2011-2021NYPDStopandFrisksbyRacePrecinctandOutcome?:showVizHome=no
- Used SARIMA Time Series Modeling with statsmodels, Auto Arima to investigate if there was seasonality to when stops did not lead to an arrest. (No seasonality detected.) 

# LINKS

### [LINKEDIN](https://www.linkedin.com/in/louis-casanave-78057aa0/) 

### [MEDIUM](https://medium.com/@ls.casanave)


<!--
**casanave/casanave** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
