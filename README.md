# Surf_up

## Overview of the statistical analysis

### Programming Features and databases

 - Data base: hawaiii.sqlite
 
 - Programming Files: 

 - Tools:pandas,SQLAlchemy

 - Software :SQlite,Python,Jupyter Notebook

## Results

Using Python, Pandas functions and methods, and SQLAlchemy, I filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the  June and December months and generate the summary statistics.

### June and December months temperature Summery Statistics

![](Resources/Junedsc.PNG)   ![](Resources/Decdsc.PNG)

#### Key values:

##### Comparison of count:

- June data set has count of 1700 data values and December dataset has 1517, so December data set has less 180 records.

##### Comparison of min/max temperatures:

- According to above 2 tables, the minimum temperature in month of June is 64F and December 56F .
Keep in mind water temperature is typically about two months behind air temperature. Winter surfing is generally done in water below 50°F.
Since minimum temperature in December is 56F, W. Avy  can run his shop even in December.

##### Comparison of mean:

- The June temperatures were little over 3 degrees comparing to average temperature in December.
The December average temperature is 71 degrees and the June having an average of 74 degrees.
As it has only 3 degrees different, Oha can get considerable income even in month of December.

##### Comparison of standard Deviations:

- The June temperature data has 3.257417 std whereas the December temperature had a standard deviation of 3.745920.The December data having a higher standard deviation tells me that the December temperature data is more spread out or dispersed than the June data.

### Bar graphs for June and Deceember tempratures

![](Resources/jenebar.PNG)  ![](Resources/decbar.PNG)

## Summary

To make a best decision ,I did following to extra queries: 
1) Output for  June and December  months station wise min,max and average temperature queries:

   
   ![](Resources/minmaxjuneO.PNG)   ![](Resources/minmaxdecO.PNG)
   
 2) Output for  June and December  months station wise min,max and average percipitation queries:
 
   ![](Resources/avgpercjune.PNG)     ![](Resources/avgpercpdec.PNG)
