Spotify Music Popularity Prediction
-----------------------------------

Exploratory data analysis on Spotify dataset, to predict Spotify's popularity using regression models (KNN, Linear Regression, Decision Tree & Random Forest Regressor).


Dataset
-------

The project uses an existing dataset that was present on kaggel. The dataset consists of audio features of approximately 600,000 songs released in between 1922 and 2021, along with the data of over 1.1 million artists. For this project, we concentrate on “data_o.csv” file for the evaluation and processing.

data_o.csv: This CSV file contains nearly 170,000 songs with 19 different features columns. The features include the song name, artist, release date as well as some characteristics of the song such as acousticness, danceability, loudness, tempo and so on.


File Organization 
-----------------

The project is coded in python.
'Spotify Regression Modeling.ipynb' file consist of all the code for this project.
'data_o.csv'(29.8MB) is the data I used for this analysis, but it cant be uploaded to github because of exceeding size..



Prerequisite 
------------

	▪	Install Pydot :  !pip install pydotplus
	▪	Install Graphviz  
		▪	For Mac OS : brew install graphviz
	   	▪	Or For Windows : conda install -c anaconda graphviz python-graphviz


Steps to interact with the dataset and reproduce our results
------------------------------------------------------------

	1)	Execute the Jupyter file cell by cell to maintain the integrity of the code.
	2)	Import the data_o.csv and convert it into a Pandas DataFrame
	3)	Cleaning and reshaping the dataframe for better visualization
	4)	Exploratory data analysis on categorical and numerical features of the tracks.
	5)	Pre-processing of the dataset in order to remove unnecessary features and missing values.
	6)	Predict the popularity of a tracks using 4 different regression models on the dataset obtained from the step 4. The model with least ‘mean squared error’ will be selected as a best fit model for the           dataset. 


Known limitations
-----------------

	1)	While credible, this data is not a primary data from Spotify.com; it is a secondary data uploaded on kaggle by someone else.
	2)	The Random forest model and KNN model will take around 30 mins to execute because of the size of our dataset(~ 29.8 Mb)
	3)	Because of this time constraint we are restricting ourselves to excute 200 iterations for decision tree and 100 iteration for KNN and random forest model respectively.












