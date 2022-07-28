
# [1. Web Scraping Housing Data](https://github.com/karanchinch10/Web-Scraping-)
Web scraping used to obtain huge data from websites & extracting/parsing required info from it which usually in unstructured form (HTML format) and then its converted into structured data in a spreadsheet or database so it can be used in various applications.

* Used `requests` and `BeautifulSoup` libraries to perform the web scraping.
* All **Important parameters** related to housing such **house price, total sqft area, project by, location, BHK and so on**  are scraped from website ***<a href="https://www.makaan.com"><strong>makaan.com</strong></a>*** 
* Objective is to know Price of house for **differents location** in **mumbai** city. 
* Data from **250 pages scarpped, store in single dataframe** & export to csv file.
* **Clean Scrapped data and Visualize** to know important features & their correlation with house price.
* Compare **Price rate for different location BHK wise** to understand location with higher rate. 
* Tech stack used:`Python,requests,BeautifulSoup,pandas`.<br>
- 
  -  👉<a href="https://github.com/karanchinch10/Web-Scraping-/blob/main/Web%20Scraping%20-%20House%20mumbai.ipynb"><strong>Web Scraping</strong></a> 💝
  -  👉<a href="https://github.com/karanchinch10/Web-Scraping-/blob/main/House%20Price%20Visualization%20Mumbai.ipynb"><strong>Scraped Data Process</strong></a> 💝

  
# [2. Predict Price of Old Car](https://github.com/karanchinch10/Oldcar_Sell_Regression)                                      
 
Now a day many peoples prefer to <strong>buy second hand car instead of buying new one</strong>, as its better investment option where we get almost <strong>30-40% discount</strong>. but main question here is how seller will know <strong>actual selling price of old car</strong> base on car features or which factors play major roles?? So to solve this complex problem, I have build <strong>ML model</strong> which predict <strong>estimated price of car</strong> base on given input features as <strong>brand,KM drive,Power,Year and so on..

* Completed stepwise <strong>EDA (Exploratory Data Analysis)</strong> and visualization to get data insight & to know <strong>important features also their correlation</strong> with car price
* Done <strong>Feature Engineering</strong> includes <strong>Features extraction & Features construction</strong> based on my domian knowledge & visualization
* <strong>Train model</strong> with multiple regression algorithms then Analysed & compare performance of differents models based of <strong>accuracy and complexity</strong>
* Got well accuracy by <strong>RandomForestRegressor(cross validation-around 90%)</strong>
* <strong>Build Web App</strong> using streamlit and <strong>deploy</strong> model 
* Tech Tools:`Python,Numpy,Pandas,sklearn,matplotllib,seaborn,html,css`.
* * [View on kaggle](https://www.kaggle.com/code/karanchinchpure/predict-price-of-used-cars-regression-problem) 💝
  * [Web App](https://karanchinch10-oldcar-sell-streamlit-app-p6gwqq.streamlitapp.com) 💝
  

# [3. Bank Marketing Campaign](https://github.com/karanchinch10/Bank-Marketing-Campaign-ML)
<strong>Marketing campaigns</strong> are sets of strategic activities that promote a <strong>business’s goal</strong> or objective also can be used to promote a product, service, or any brand as a whole. The project is focus on analysis of <strong>Bank Marketing</strong> dataset which contains data of customers details (Personal + Banking) and aims to get useful insights from data. By understanding important features and <strong>patterns of target customers</strong> which can help to get best strategies to improve for the next marketing campaign 
* Build Model which predict either a new customer will accept a deposit offer or not
* Done <strong>EDA & Data Correction</strong> and Handle outliers 
* Visualize data to know pattern of target customers by their previuos campaign deatils includes contact duration,type,no of contact perform, also banking details & so on..
* <strong>RandomForest & XG boost Perform best (R2score 86%)</strong> after Train and Evaluate model performance based on accuracy, R2 score & complexity 
* Build <strong>Pipeline</strong> for <strong>deployment</strong> session & Deploy the model  
*  Tech stack used:`Python,pandas,matplotlib,seaborn,numpy,html,css`.
* * [View on kaggle](https://www.kaggle.com/code/karanchinchpure/bank-marketing-who-will-subscribe-for-deposit) 💝
  * [Web App](https://karanchinch10-bank-marketing-campaign-ml-app1-mc8w1z.streamlitapp.com/) 💝
   


<!-- <h1><a href="https://github.com/karanchinch10/IRIS_Classification">4. IRIS flowers Detection</a></h1>
To determine <strong>class or cateogry of flower</strong> which its belong to base on their 4 features or parameters such as <strong>sepal length,sepal width, petal length and petal width.</strong> Dataset contains total <strong>3 category of flowers</strong> of 50 instances each<strong>(setosa,virginica,versicolor)</strong>, where <strong>each class</strong> refers to a type of <strong>iris plant</strong>. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other. contents of <strong>Multiclass classification problem</strong> as below

- <strong>EDA (Exploratory Data Analysis)</strong> and visualization to get <strong>data insight</strong> or important features
- Train model with multiples <strong>classification</strong> algorithms
- Analysed & compare performance of differents models based on <strong>F1 score</strong>
- <strong>SVM and KNN</strong> had given best accuracy 
- Vary K value still accuracy was almost same 97.2 then after <strong>cross validation</strong> SVM accuracy was more than KNN
- Finally Build </strong>web application</strong> using streamlit and <strong>deploy the model.</strong> 
- <strong>Web App</strong>👉 <strong><https://karanchinch10-streamlit-iris-app-0k57bb.streamlitapp.com//></strong> 💝
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>
- 
  -  <a href="https://www.kaggle.com/code/karanchinchpure/iris-classification-problem-eda"><strong>View On Kaggle</a></strong> 💝
  -  <a href="https://github.com/karanchinch10/IRIS_Classification"><strong>View On Github</a></strong> 💝 -->
  


# [4. G-Play Apps Visualization](https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb)
<strong>Google Play Store</strong> team is about to launch a new feature wherein, certain apps with higher priority in recommendations sections (“Similar apps”,“New and updated games”) that are promising, are boosted in visibility also in search results visibility. This feature will help bring more attention to <strong>newer apps that have the potential.</strong>

* Perform <strong>EDA, Data cleaning and Data correction on raw data</strong> 
* Done <strong>visualization</strong>by various plots to draw useful insight from data and which will help for <strong>decision making</strong> like
1. <strong>Total No of apps</strong> of all category (like games,sports,medical,education,beauty..etc) 
2. Which <strong>category</strong> has <strong>highest demand</strong>, rating, installation or reviews?
3. Total <strong>percentages of free and paid apps</strong> available in glapy store
4. Is there is any <strong>relation of apps rating and reviews with their installation?</strong>
* Tech stack used : `Python,numpy,pandas,matplotlib,seaborn.`
* * [View on kaggle](https://www.kaggle.com/code/karanchinchpure/gplay-playstore-data-visualization-eda) 💝
  * [View on Github](https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb) 💝
 

# [5. Bank Management Web App](https://github.com/karanchinch10/Bank-management-Web)
<h4><strong>Python | Flask | SQL | HTML | CSS </strong></h4> 

 I have made<strong> Flask Project of Bank Management Web Application System</strong> designed for <strong>customer/bank holder</strong> to get all <strong>basic bank services</strong>
* Front end was created by HTML and CSS without use of bootstrap
* Connect python with SQL database to manage all information by CRUD operation
* First customer has to <strong>open their bank account</strong> by filling basic bank details such as Name, Password, DOB, mob no, Initial Deposit & register their bank account
* Now user can <strong>login</strong> account by entering <strong>user ID and password</strong>
* User can <strong>view and modify</strong> their <strong>personal details</strong> & change password also can logout acccount due to turning off the login session
* User can <strong>withdraw, credit money</strong> into their account and <strong>check current balance</strong>
* Tech stack used:`Python,Flask,MySql Database,XAMPP,html,CSS`<br>
* - [View Project Report](https://drive.google.com/file/d/1OWEpEZOMQLKn9l1bylQrqw8NeEoizxoF/view?usp=sharing)
  - [View on Github](https://github.com/karanchinch10/Bank-management-Web)
  
<h1><a href="https://karanchinch10.github.io/karan-chinchpure-portfolio/">6. Personal Web PortFolio</a></h1>
<h4><strong>HTML | CSS | BOOTSTRAP </strong></h4>  

- I have made Personal web Portfolio to showcase my <strong>skills, technical knowledge and personal projects</strong>
- 👉<a href="https://karanchinch10.github.io/karan-chinchpure-portfolio/"><strong>Click to View My Personal Web Porfolio</strong></a> 💝


