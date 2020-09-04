# Predictors of Poverty in the US

## Data Science Approach:
This project uses the dataset that is the compilation of 2017 U.S. Census Demographic Data (Kaggle 2017). <br> 
This dataset provides ample numerical and categorical variables that can be utilized as predictors for our regression and classification models. <br>
Such predictors include race, gender, household income, unemployment rate, and so forth. <br> 
Additionally, the dataset is fairly complete in the sense that missing data is at a minimum <br>	

## Dependencies
```
$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas
```

## Instructions to Run Code 
After downloading the zip file, run the code in the following order <br> 
1. partition_Data - (No Need to execute data is already partitioned)
2. US_Census_DataPreProcessing - (Data Processing for train) 
```
input : census_train_data.csv
output : train_dp_output.csv
```
3. DPTestdata - (Apply columns data to test set) 
```
input : census_test_data.csv
output : test_dp_output.csv
```
4. Census_Regression - (Regression)
```
input : train_dp_output.csv
output : sample_output.xlsx
```
5. Census_Classification - (Classification)
```
input : train_dp_output.csv
output : sample_output.xlsx
```
6. Classification Map 
```
input : train_dp_output.csv
```

## Notes: 
* Currently, there is known issue that matplotlib version 3.1.1 does not properly display the heatmap on macOS. <br>
If there is an issue doing so, please downgrade to matplotlib version 3.1.0 upgrade to matplotlib 3.1.2. <br>
https://github.com/matplotlib/matplotlib/issues/14675

* If there are issues running the code for task #06, check to see if pyshp, plotly, shapely, and geopandas packages are properly installed. <br>
Otherwise run the following commands using the command line interface of your choosing:
```
$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas
```

