# ECE 143 Group Project Team 2

# Authors:
Shiming Luo<br>
Yatian Jiang<br>
Kenny Sitú<br>
Tejas Bhakta

# Overview <br>
In this project we will scrape, then visualize mental health issues and gun violence data with heatmaps. We will then run statistical tests on the data, and seek answer the following questions.:

**Are Mental Health Illnesses Correlated with Gun Fatalities?**<br>
**Are Mental Health Illnesses Correlated with Violent Crime**<br> (Rape, assault, gun violence, etc... Essentially a larger set that includes gun fatalities as well as other crimes) 
**Is the medical Treatment of Mental Health Illnesses correlated with lesser Gun Fatality rates?**<br>
**Given a number of Mental Health Illnesses in a State, can we accurately predict the number of Gun Fatalities?** <br>


# Folders <br>
**Correlation**<br>
One jupyter notebook with all correlation analysis
**Predictive Model**<br>
One jupyter notebook with all predictive model analysis
**Scraping_Data**<br>
Multiple jupyter notebooks with all correlation analysis, subfolders of sources and outputs
**Visualization**<br>
One jupyter notebook with all Visualization analysis, one subfolder name figure with all our heatmaps saved
**data**<br>
csv files (result of the data scraping) we used in our analysis

# Data Scraping
For the Mental Health Scrapping Data, all the content is stored in the Scraping_Data folder in Github. 
The Original PDFs contain all the PDFs downloaded from the source website. 
The HTML_Files contain all the converted HTML files from the Original PDFs. 
The CSV_Files folder contains all the csv files that contain the total mental health issues in a region 
while the Percentage_CSV_Files folder contains all the csv files that contain the percentage of the population with mental health issues. 
Lastly, the Jupyter notebook contains the code and my documentation that scraped and cleaned my data. 

# Visualization
**Pairplot**<br>
**Heat map**<br>
According to the method of exploratory data analysis, we first do the pairplot to show the relevance between each item at the very beginning. This data tells us there is no relavance for the shown items.
![alt text](https://github.com/KennySitu/Team_Two_But_-1_In_Standings/blob/master/Visualization/figure/PairPlot.png)
<br>
Then we do the heat maps.
![alt text](https://github.com/KennySitu/Team_Two_But_-1_In_Standings/blob/master/Visualization/figure/heatmap_deaths.png)

# Correlation
In this Notebook, we will fetch gun violence and mental health data from our csv files using pandas, and using statisical tests like Pearson Correlation and t-test we will conclude if Mental Heath Illnesses affects Gun Violence.
![alt text](https://github.com/KennySitu/Team_Two_But_-1_In_Standings/blob/master/Correlation/forREADME.PNG)

# Predictive Model
In this Notebook, we create a prediction model, which we are able to use because of the strength of our correlation data, where the user can enter a number of mental illnesses and get a semi-accurate approximation of how many gun fatalities there will be. (R^2 value is 0.8)
![alt text](https://github.com/KennySitu/Team_Two_But_-1_In_Standings/blob/master/Predictive%20Model/predict_forREADME.PNG)

