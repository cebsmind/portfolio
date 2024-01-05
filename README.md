# [PROJECT 1 : Spaceship Titanic :](https://github.com/cebsmind/portfolio/blob/main/TitanicSpaceShip.ipynb) 
- [Competition link (from kaggle)](https://www.kaggle.com/competitions/spaceship-titanic)
- [Python Note book code](https://github.com/cebsmind/portfolio/blob/main/TitanicSpaceShip.ipynb)
  
## What I Have Learned:
1. *Enhanced proficiency in data preprocessing techniques.*
2. *Gained hands-on experience in using Python for data analysis and machine learning.*
3. *Developed skills in model evaluation and interpretation.*

## Key steps :

* **Exploratory Data Analysis (EDA)**:
  - *Utilized Pandas for comprehensive data exploration.*
  - *Employed Matplotlib & Seaborn for creating visualizations to gain meaningful insights into the dataset.*

* **Data Preprocessing**:
  - *Cleaned and prepared the dataset for analysis and modelisation*
  - *Addressing missing values*
  - *Encoding categorical and ordinal variables. Also scaling numerical variables*
  - *Feature engineering to create meaningful variables to gain model performance.*
  - *Creating a pipeline to preprocess our data*

* **Model Development**:
  - *Employed Scikit-learn for building predictive models.*
  - *Applied a GridSearch to find the best model & hyperparameters*
   

* **Model Evaluation and Interpretation**:
  - *Assessed model performance using relevant metrics (accuracy, precision, recall, etc.).*
  - *Interpreted model outcomes and discussed potential implications.*
  - *Used "Learning Curves" to have a better view of our model performance and see if our model is over fitting or not*

![](https://github.com/cebsmind/portfolio/blob/main/images/download.png?raw=true)


* **Submitted my predictions to Kaggle and ranked in the top 27% on the leaderboard**

# [PROJECT 2 : Image Classification : Cats vs Dogs ](https://github.com/cebsmind/portfolio/blob/main/Deep%20Learning%20CatDog.ipynb) 
- [Data link (from kaggle)](https://www.kaggle.com/datasets/d4rklucif3r/cat-and-dogs)
- [Python Note book code](https://github.com/cebsmind/portfolio/blob/main/Deep%20Learning%20CatDog.ipynb)
  
## Key steps :

* **Data Preparation**:
  - *Organized the data into training, validation, and testing sets.*
  - *Used ImageDataGenerator for preprocessing, including resizing, normalization, image transformation etc*
  - *Plotted random images with labels (cats/dogs) to gain insights into the dataset's content and structure*

* **Model Building**:
  - *Constructed a Convolutional Neural Network (CNN) architecture using TensorFlow's Keras API.*
  - *Utilized Conv2D layers for feature extraction and MaxPooling2D for downsampling.*
  - *Employed Dense layers for classification, ending with a sigmoid activation for binary output.*

* **Model Evaluation**:
  - *Trained the model on the training dataset and evaluated its performance on the validation set.*
  - *Monitored metrics such as accuracy, loss, and validation accuracy to gauge model performance..*
   
* **Web Scraping for Data Collection:**
  - *Accessed the Unsplash API to retrieve a wide array of cat and dog images.*
  - *Utilized scraping techniques to acquire a diverse dataset, essential for training and testing the model*
  
* **Predictive Function for Image Classification:**
  - *Developed a function capable of loading the pre-trained deep learning model.*
  - *Implemented the model within the function to make accurate predictions on new images sourced from Unsplash.*

  ![](https://github.com/cebsmind/portfolio/blob/main/images/deeplearning.jpg?raw=true)


* **Conclusion :**
  The project prominently showcased the application of deep learning methodologies, specifically CNNs, in tackling image classification challenges. The strategic utilization of these techniques resulted in a robust and accurate model for distinguishing between cats and dogs based on visual data.






# [PROJECT 3 : Immunization (COVID-19) Project](https://public.tableau.com/app/profile/cebrail/viz/ImmunizationFlu/Tableaudebord1)
- [Data source](https://github.com/cebsmind/portfolio/tree/main/sql-data)
- [SQL code](https://github.com/cebsmind/portfolio/blob/main/SQL-code)
- [Tableau visualisation](https://public.tableau.com/app/profile/cebrail/viz/ImmunizationFlu/Tableaudebord1)
- Note : all of this data is synthetically generated (i.e. fake), and comes from a project called Synthea
  
## Objectives : Create flu shots dashboard for 2022 that does the following

* *Total % of patients getting flu shots stratified by*
   - Age
   - Race
   - County (On a Map)
   - Overall
    
* *Running Total of Flu Shots over the course of 2022*
* *Total number of Flu shots given in 2022*
* *A list of Patients that show whether or not they received the flu shots*
   
## Key steps :

* **Used SQL (PostgreSQL) to clean, filter, and prepare the data for Tableau.**
  
* **Utilized Tableau's functionalities to create a variety of visualizations :**
  - *Flu Shots by Age (Barchart)*
  - *Flu Shots by Race (Barchart)*
  - *Flu Shots By County (Map)*
  - *Running sum Flu Shots 2022*
  - *Flu Shots List*
    
* **Dashboard preview :** 

![](https://github.com/cebsmind/portfolio/blob/main/images/DataFluShots.png?raw=true)


# [PROJECT 4 : Twitter Sentiment Analysis (NLP) :](https://github.com/cebsmind/portfolio/blob/main/Tweeter%20Sentiment%20Analysis%20Beginner.ipynb) 
- [Data Set link (from kaggle)](https://www.kaggle.com/datasets/kazanova/sentiment140)
- [Python Note book code](https://github.com/cebsmind/portfolio/blob/main/Tweeter%20Sentiment%20Analysis%20Beginner.ipynb)

## Objectives : 
In this project, I endeavored to delve into the realm of Natural Language Processing (NLP) by constructing a foundational model. Leveraging a Twitter Sentiment Dataset sourced from Kaggle, the aim was to predict the sentiment of text, specifically tweets. The primary goal was to initiate my journey into understanding how machines interpret human text and the methodologies involved in its analysis.

While this project marked the initial steps in my NLP exploration, it underscored the significance of continued learning. There remains an abundance to explore and comprehend in this dynamic field, and this foundational project serves as a springboard for delving into more sophisticated models and techniques in the future.
  
## Key Steps :

**Data Preprocessing :** 
- *Cleaning text data (remove hastags, @usernames, URL, stopWords...) & also replacing Emojis with words, using regex*
- *Lemmatization using NLTK library (Natural Language Toolkit)*

**Data representation** :
- *Used Cloud Words to represent cleaned data*
  
**Feature Engineering :** 
- *Utilizing CountVectorizer for creating bag-of-words representation of text data.*
  
**Model selection** : 
- *Experimented with multiple machine learning models such as Naive Bayes, SVM. Conducted hyperparameter tuning and cross-validation to optimize model performance.*

**Evaluation and Analysis :** 
- *Evaluated models using various metrics like accuracy, precision, recall, F1-score & Matrix confusion.*
- *Analyzed results using visualizations to understand strengths and weaknesses of each model.*
- *Testing our model using a sample of random tweets to see how it perform*

![](https://github.com/cebsmind/portfolio/blob/main/images/download%20-%20Copie.png?raw=true)


