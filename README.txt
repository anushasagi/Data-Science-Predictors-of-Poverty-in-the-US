Group Information 
Name		
Fatima Kahack  
Lydia Tse	  
Anusha Sagi  

Data Science Approach:
We will use a dataset that is the compilation of 2017 U.S. Census Demographic Data (Kaggle
2017). This dataset provides ample numerical and categorical variables that can be utilized as
predictors for our regression and classification models. Such predictors include race, gender,
household income, unemployment rate, and so forth. Additionally, the dataset is fairly
complete in the sense that missing data is at a minimum
	

Instructions to Run Code 
1. After downloading the zip file, run the code in the following order 
	- partition_Data - (No Need to execute data is already partitioned)
	- US_Census_DataPreProcessing - (Data Processing for train) -
 	  (input : census_train_data.csv)  (output : train_dp_output.csv)
	- DPTestdata - (Apply columns data to test set)
	 (input : census_test_data.csv)  (output : test_dp_output.csv)
	- Census_Regression - (Regression)
	(input : train_dp_output.csv)  (output : sample_output.xlsx)
	- Census_Classification - (Classification)
	(input : train_dp_output.csv)  (output : sample_output.xlsx)
	- Classification Map (input : train_dp_output.csv) 

Notes: 
Currently, there is known issue that matplotlib version 3.1.1 does not properly display the heatmap on macOS. If there is an issue doing so, please downgrade to matplotlib version 3.1.0 upgrade to matplotlib 3.1.2.
https://github.com/matplotlib/matplotlib/issues/14675


If there are issues running the code for task #06, check to see if pyshp, plotly, shapely, and geopandas packages are properly installed. Otherwise run the following commands using the command line interface of your choosing:


$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas
