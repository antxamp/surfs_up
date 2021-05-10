# surfs_up

## Overview of the analysis:
W. Avy likes my analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in **Oahu**, in order to determine if the surf and ice cream shop business is sustainable year-round. My objective is to complete the deliverables below in order to find the statistics for both months and to give an anaylsis on my findings. 

### Resources: 
##### Jupyter Notebook, Python3.8, VScode, Pandas, SQLAlchemy and .sqllite files were supplied

### Objective:
###### Deliverable 1: Determine the Summary Statistics for June

###### Deliverable 2: Determine the Summary Statistics for December

### Results from deliverables:
**Here are the statistical results for the month of June in _Oahu_.** 

![image](https://github.com/antxamp/surfs_up/blob/main/Resources/june_temps_stats.png)

**Here are the statistical results for the month of December in _Oahu_.**


![image](https://github.com/antxamp/surfs_up/blob/main/Resources/dec_temps_stats.png)

### Analysis:
##### As you can see from above this data gives us a summary of different statistics for the temperatures in the months of June and December in Oahu. The count is the number of times the temperature was observed. The other statistics that I will use for this analysis are going to be the mean, min and max.
  - Mean temperatures
      - The mean temperature for Oahu in June is 74.9 degrees and December is 71F (both in Fahrenheit).
       -  Given that both mean temperatures are relatively close we can distinguish that December is much cooler overall in Oahu.
      
  - Minimum temperatures
      - The minimum temperature for Oahu in June is 64F degrees and December is 56F.
      - With this data we can see that there is a much larger difference in minimum temperatures. This can be the result of the time of day that this data was recorded or it could be an outlier.

  - Maximum temperatures
      - The maximum temperature for Oahu in June is 85F degrees and December is 83F.
      - From this data alone we can verify that year round that temperatures at this range are ideal for business.


## Final results with additional queries
##### With the data sorted and statistics present. I can verify that there are more observation counts in the month of June comparable to December in order to understand more, I've made more queries to draw a better picture for my conclusion. 
##### I've made addtional queries and provided addtional data below to give a better visual on how often the the temperaures are observed which indicate that although December is cooler it does exhibit more than 50% of its observations in the 70, 80F range. In addition to my analysis you can see where there is an outlier of 9 observations recorded for the minimum temperature in December. 

#### Conclusion: **Year-round sustainability is possible for business in Oahu.**


![image](https://github.com/antxamp/surfs_up/blob/main/Resources/june_temp_range.png)




![image](https://github.com/antxamp/surfs_up/blob/main/Resources/dec_temp_range.png)





