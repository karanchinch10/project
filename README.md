
# [1.Quotes Scraper](https://github.com/ashwinshetgaonka/Web-Quotes-Scraper)
Web scraping or web data extraction is used for extracting data from websites,this involves fetching data and extracting/parsing required info from it. Fetching is the downloading of a page (which a browser does when a user views a page).

* Implemented Web Scraping to extract data from static sites.
* Used `requests` and `BeautifulSoup` libraries to perform the web scraping.
* The project involved extracting the names of all topics of quotes and then scraping quotes along with their author name for all topics
  previously scraped.<br>
<!-- * Deployed the project using streamlit as a Web app. -->
* Tech stack used:`Python,requests,BeautifulSoup,pandas`.<br>
<!--   [To view the web app](https://share.streamlit.io/ashwinshetgnkar/web-quotes-scraper/main/app.py) -->

  



# [2.IPL Batting Analysis 2008-2021](https://github.com/ashwinshetgakar/Data-Visualization-Projects/tree/main/IPL%20Batting%20Analysis%202008-2021)                                      
 
The Indian Premier League is a professional men's Twenty20 cricket league, contested by ten teams based out of ten Indian cities.The league was founded by the Board of Control for Cricket in India in 2007.The Dataset contains the stats of all the batsman to have played the league from 2008 upto 2021.

* Visualized the data after performing various data manipulations using my domain knowledge about Cricket so as to discover various useful insights from the available data that would help team owners / people playing fantacy games get information about players that are leading in various batting stats like :
1. Players with max Strike Rate.
2. Players with least balls/boundary.
3. Players with most runs per season and many more.<br>
* Performed around 35 such queries and visualized the results which will give almost all the key attributes of batting.<br>
* Tech stack used:`Python,pandas,matplotlib,seaborn,numpy,html,css`.<br>
  [To view on kaggle](https://www.kaggle.com/code/ashwinshetgakar/ipl-batting-analysis-2008-2021)
  


# [3.Super Store Analysis](https://github.com/ashwinshgaonkar/Data-Visualization-Projects/tree/main/Super%20Store%20Analysis)
Competition in the retail industry is rising day by day. In a marketplace that’s becoming increasingly digital, retailers are compelled to use advanced analytics to ensure their business survives the competition. Before using analytics to evaluate store performance, 
it is necessary to identify the objectives behind adopting it. This ensures that the derived intelligence is effectively acted upon.
Dataset contains Information related to Sales, Profits and other interesting facts of a Superstore giant.

* Visualized the data so that the store owner viewing it can easily understand the Market demands and Customer behaviour which will intern help him in making decision like:

1. How much discounts to offer and for what products.
2. When to offer and in which regions to offer.
3. Make customized policies for customers of various segments and many more.<br>
*  Tech stack used:`Python,pandas,matplotlib,seaborn,numpy,html,css`.<br>
   [To view on kaggle](https://www.kaggle.com/co/ashwinshetonkar/super-store-analysis-data-visual-seaborn) 
   


<!-- # [4.Road Deaths Analysis](https://github.com/ashwihetgaonkar/Data-Visualization-Projects/tree/main/Road%20Deaths%20Analysis)
* The Dataset contains information of number of deaths in various regions of the World from 1990-2019,along with other data like historical population,region code,Side of driving.

* My objective for this Project was to visualize the available data to draw insights from it which are not perceived just by reading through an excel/csv file.
* Here I have visualized the number of deaths using various plots to gain various insights from the data.
* From this I can easily state the regions with maximum,mean deaths,year in which max deaths occured and many more.<br>
  [To view on kaggle](https://www.kaggle.com/code/ashhetgaonkar/road-deaths-data-visualization-seaborn) -->
  


# [4.Estimating Mechanical Properties of Steels](https://github.com/ashwsgaonkar/Estimate-Mechanical-Properties-of-Steel-compostions)
Since currently there are no precise theoretical methods to predict mechanical properties of steels,I have made an attempt to predict the mechanical properties of steels using Maching Learning.The dataset contains compositions by weight percentages of low-alloy steels along with the temperatures at which the steels were tested and the values mechanical properties observed during the tests. 

* Developed a Regression model to predict the mechanical properties of steels after giving its composition as an input.
* Visualized the data and performed various `Data Transformations` to bring the data into a suitable form for efficient modeling.
* Tuned LightGBM model using Optuna framework to get `rmse of 24.23,21.54,2.78,4.32 for the four outputs`.
* Deployed the model using `Streamlit` as a web app.
* Tech stack used : `Python, numpy, pandas, matplotlib, seaborn, lightgbm, optuna, streamlit, html, sklearn, scipy, joblib.`<br>
  [To view on kaggle](https://www.kaggle.com/code/ashwigaonkar/mech-prop-lightgbm-optuna),[To view the web app](https://share.stmlit.io/ashwintgakar/estimate-mecnical-properties-of-steel-compostions/main/app.py)
 

# [5.Movie Rating Sentiment Analysis](https://github.com/ashwitgaonkar/Movie-Rating-Sentiment-Analysis)
Sentiment analysis, also referred to as opinion mining, is an approach to natural language processing (NLP) that identifies the emotional tone behind a body of text.The dataset contains movie reviews consisting of text along with its labels taken from IMDB.
* Trained and compared the performance of various models on the basis of `f1_score and time taken per prediction`.

* Demostrated how increasing the complexity of the model will lead to better performance but will hamper the time taken per prediction.
* The best performing model on the bases of f1-score alone was `fined tunned bert-base-uncased[Hugging Face Transformer]` with score of `0.92`.
* Deployed a web app using streamlit which uses model trained using a feed forward neutral network which gave an f1-score of 0.89.
* Tech stack used:`Python,numpy,pandas,sklearn,tensorflow,streamlit,html,css,tranformers.`<br>
  [To view on kaggle](https://www.kaggle.com/code/ashshetgaonkar/movie-rating-sentiment-analysis),[To view the web app](https://share.streamlit.io/ashwinsheonkar/movie-rating-sentiment-analysis/main/app.py)
  
  
  
# [6.Vegetable Classifier](https://github.com/ashwinaonkar/Vegetable-Classifier)
From vegetable production to delivery, several common steps are done manually like picking, and sorting vegetables.
Therefore, it would be a great idea to automate this process in the coming future by using a robot empowering it using Computer Vision.
The dataset consists of training/validation/test sets of images of 15 different vegetables.

* Developed a Multiclass Classification model using pretained model `efficientnetB0` that provides an accuracy greater than `95%` in classfying the 15 vegetable classes.
* Incorporting suitable `Data Augmentation` layer and `callback functions` I improved the accuracy above `99%`.
* Visualized the performance on some samples of the test data.<br>
* Tech stack used:`python, numpy, pandas, tensorflow, html, css, matplotlib, seaborn, pywebio, flask, heroku.`
  [To view on kaggle](https://www.kaggle.com/code/ashwigaonkar/vegetable-clf-transfer-learning-error-analysis)

# [7.Object Detection and Motion Tracking](https://github.com/ashwinshetgaonkar/Object-Detection-and-Motion-Tracking)
* Implemented Object Detection on images and Object Detection and Tracking on webcam input.
* Tech stack used: `Python, OpenCv`.

<!-- # [8.Fake News Classifier](https://github.com/ashwinshetgaonkar/Fake-News-Classifier)
* In today's world which contains a lot of digital data it will be very beneficial to have some kind of an software that will help us in descriminating between Fake and Real News with some given constraints.
* The dataset contains news instances with title and text along with its labels taken from various sources.
* My objective for this project was to train and compare the performance of various models on the basis of f1_score and time taken per prediction.
* Here I have demostrated how increasing the complexity of the model will lead to better performance but will hamper the time taken per prediction.
* Build an web app using streamlit which uses model trained using a feed forward neutral network.<br>
  [To view on kaggle](https://www.kaggle.com/code/ashwinshetgaonkar/fake-news-classifier-nb-bert),[To view the web app](https://share.streamlit.io/ashwinshetgaonkar/fake-news-classifier/main/app.py) -->
