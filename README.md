# Hi there 👋 I'm Louis 

## INTRO VIDEO
[<img width="1280" alt="Screen Shot 2023-02-08 at 11 23 20 AM" src="https://user-images.githubusercontent.com/8728172/217589930-ef3c9d06-f578-4479-890c-1dfb236a1205.png">](https://www.loom.com/share/43c90039c31f4c57b88c720dda6e723b)

I am a storyteller who is passionate about data, writing, public speaking and building community. I hold a special place in my heart for Natural Language Processing (spaCy, NLTK,) and inferential modeling (statsmodels, scikit-learn, and using SHAP or LIME explainers.) Additionally, I have experience with data wrangling, scraping, and engineering, (pandas, selenium,) and using machine learning algorithms (decision tree/Random Forest, Linear and Logistic regression analysis.) I also adore making visualizations (seaborn, matplotlib,) and using maps (folium.) I have experience using APIs (Google, Yelp, Twitter) as well as using public data sets (NYC Open Portal.) A firm believer in a well-written code comment, accessible documentation, and better coding with functions. 

# Projects 

### Pumpkin_Spice (Time series analysis and modeling Modeling)
[ReadMe](https://github.com/casanave/Pumpkin_Spice/blob/main/README.md)

[Main Code Notebook](https://github.com/casanave/Pumpkin_Spice/blob/main/Pumpkin_Spice.ipynb)
##### Time series analysis with naive, SARIMA and ETS modeling.  
- Google trends last 5 years of data with the "pumpkin spice" search term
- Performed both additive and multiplicative time series decomposition of data with explinations
- Tested naive models that use last year and last week's data as today's direct prediction
- Tested SARIMA and ETS itterations of models with terms based on both ACF and PACF plots, as well as an itterative approach with PMD Auto Arima
- Best model was an ETS model with MAPE: 12.118428034881385, RMSE: 4.429939957414803 which is roughly 2-3 times better than using last year's data 
- Downloaded final [model](https://github.com/casanave/Pumpkin_Spice/blob/main/pumpkin_spice_predictor.sav) and will verify last two weeks of data in blind verification




### HurriHelp (Natural Language Processing Task and Modeling)
[ReadMe](https://github.com/casanave/Hurri_Help)

[Main Code Notebook](https://github.com/casanave/Hurri_Help/blob/main/analysis_and_modeling_notebook.ipynb)

##### Natural Language Processing project using sentiment analysis to help find Hurricane Ian survivors in distress, and provide them with links to National Disaster Distress Helpline and FEMA Info.  
- Scraped Twitter for over seven thousand original tweets 
- Used three different sentiment analysis analyzers (TextBlob, VADER, and a distillBERT model) to find the sentiment of tweets
- Used analysis to explore the most common words in negative and positive sentiments. 
- Used Random Forest, Naive Bayes, XGBoost, and Catboost on vectorized tweets for 80% precision in the best-tuned model
- Used Lime Text Explainer for the inferential understanding of the most common words in data, and found words most likely to be in negative tweets




###  Fetal Health Project (Catigorization Task and Modleing) 
[ReadMe](https://github.com/casanave/fetal_health)

[Main Code Notebook](https://github.com/casanave/fetal_health/blob/main/final_notebook.ipynb)

##### Health information project for early detection and faster diagnosis of pathological fetal heartbeats.  
- Built data pipelines and created two early detection algorithms ready for A/B testing
- Tested Logistic Regression, K-Nearest-Neighbors, Support Vector Machine, and Random Forest for the highest recall of pathological class of 92%
- Used OneVsRest wrapper and GridSearchCV for model specialized to pathological class and best-tuned machine. 
- Used Shap Values for the inferential understanding of the model, and reduced dimensionality of the algorithm by five input features for 90% recall




### Seattle Section 8 Expansion Project (Regression Task and Modeling)
[ReadMe](https://github.com/casanave/Seattle_Section_8_Expansion_Project)

[Code Notebook](https://github.com/casanave/fetal_health/blob/main/final_notebook.ipynb)

##### Built inferential linear regression model to inform the city of Seattle on where to build new public housing.
- Performed in-depth EDA, determining the effect of renovations over time on property values for efficient budgeting. 
- Used Google’s geocoding API and selenium to engineer features: how close each property is to the closest public school, hospital, and police station for infrastructure insights related to property values
- Visualized multicollinearity in seaborn with correlation heat maps, for feature selection 
- Iteratively constructed eight versions of the linear regression model, removing features with low P Values for an R-Squared score of 83%
Produced automated findings report for human analysis of coefficients, including inferential analysis of inequity by zip code




### Film Analysis Project (Exploritory Data Analysis) 
[ReadMe](https://github.com/casanave/Film_Analysis_Project)

[Code Notebook](https://github.com/casanave/Film_Analysis_Project/blob/master/Film_Analysis_Project%20.ipynb)

##### Advised hypothetical Microsoft Studios on what kinds of feature films to produce by analyzing box office financial data.  
- Aggregated data using Pandas and visualized in Seaborn to discover the most popular genres by net profit: Animation, Adventure, Fantasy and Family films 
- Pivoted Table to aggregate films of most popular genres by release date to infer seasonal trends: best months for releasing new films in most popular genres to be June, July, May, March, November, and April
- Inferred best run time for new films is between 120-150 minutes based on historical popularity 




### Stop And Frisk Project 

#### Tableau Dashboard, 

[ReadMe](https://github.com/casanave/stop_and_frisk_2021)

[Code Notebook](https://github.com/casanave/stop_and_frisk_2021/blob/main/2021_analysis.ipynb)

##### Tableau Public dashboard using demographic information from 2021 for public transparency.

- Used Pandas to clean 2021 Stop and Frisk Data for later use in a Tableau public viz
- Resulting Visualization used in article [EDA with Tableau: 2021 NYPD Stop-and-Frisks by Demographics](https://medium.com/towards-data-science/eda-with-tableau-2021-nypd-stop-and-frisks-by-demographics-e5e88eb43939) published by Towards Data Science


#### Geospacial Vizualization
[ReadMe](https://github.com/casanave/stop_and_frisk_2020)

[First Code Notebook](https://github.com/casanave/stop_and_frisk_2020/blob/main/zipcode_frequency.ipynb)

##### In-depth analysis, static geocoding visualization of consent-asked for rates in 2020 for public transparency.

- Visualized frequencies of stops and consent-asked in 2020 NYPD stop and frisk data towards understanding inequities in policing. 
- Investigated anomalies and outliers, patterns, and relationships for insights into different zip codes and communicate results with choropleth maps and graphs made in Folium and Seaborn
- Resulting artical [Using Folium On Police Data](https://towardsdatascience.com/using-folium-on-police-data-3207e505c649) published by Towards Data Science 




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
