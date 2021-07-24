# Disaster Response Project(Udacity Project which includes)
1. ETL Pipeline 
2. Machine Learning (Supervised ML and NLP)
3. Deployment 
4. API exposing to Classify the new messages based on the trained model


**Disaster Response Pipeline**

Overview
The project used a data set from Figure Eight that contained labeled disaster messages received. A Random Forrest classifier was trained and natural language processing (NLP) was also used to model the Labeled Text Messaged.

An ETL pipeline was created with below steps 

1.Extracting data from the CSV Files

2.Cleaning the CSV Files and loading into an SQL database which will be further picked by model for training

3.ML pipeline is created to extract the Text features and optimize algorithm using grid search as thought in Udacity

4.A web app is developed that extracts data from database and provides visual summaries


**Technologies Used**

Python Libaries used for this project are 

1. Pandas -- For reading the files
2. sklearn -- For ML Training and Splitting data into train and test
3. sqlite3  -- Database to load data 
4. sqlalchemy -- Data Tool Kit which will be used to load engineered 
5. nltk -- Libary for Natural Language processing 
6. plotly  -- Displaying the Visuals 
7. flask -- To build the Flas APP



**Instructions**:

Following commands needs to be run in the project's root directory to set up DB and Model

To run ETL pipeline that cleans data and stores in database are as below 

1.data/process_data.py 

2.data/disaster_messages.csv 

3.data/disaster_categories.csv 

4.data/DisasterResponse.db

To run ML pipeline that trains classifier and saves the pickle files are 

1.models/train_classifier.py 

2.data/DisasterResponse.db 

3.models/classifier.pkl



