# Surf_up
W. Avy, an investor, who is famous for his love of surfing going to invest for a Surfn'Shake shop selling surfboards and ice cream to locals, tourists in Hawaii. He invested in a surf shop early in his career. However, he didn't ask for any weather analysis and that early venture was rained out of existence.

W.Avy knows I've been learning how to properly analyze data and asks if I can run some analysis on a weather dataset he has from the very island where like to open the shop in beautiful Ohau.

First part of analysis completed by analyzing and plotting 12 months precipitation levels. Now he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine the surf and ice cream business is sustainable or not in year-round.

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
According to the above two summery statistics and bar graphs there is no significant temperature different in the months of June and December data sets. Considering temperature factor for summer months (June) and winter months (December), the business will be sustainable in year-round.

To make a best decision for invester W. Avy ,I did below extra queries: 

1) Output for  June and December  months station wise min,max and average temperature queries:

   
   ![](Resources/minmaxjuneO.PNG)   ![](Resources/minmaxdecO.PNG)
   
   Not only temperature we should also consider percipitation factor.
   
 2) Output for  June and December  months station wise min,max and average percipitation queries:
 
   ![](Resources/avgpercjune.PNG)     ![](Resources/avgpercpdec.PNG)
   
   From looking at above outputs, investor can get a clear idea about how station wise temperature\ precipitation vary in summer (June) and winter (December) months.
   
Surfing is usually best when it's wind-free, so if we can have data about wind conditions it will help for more accurate analysis 
   
   
