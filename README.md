# gendergap
This repository contains project that visualizes the gender gap in college degrees.

### Objectives ###

Below is the list of questions that we are looking to answer as a final outcome of this project:
    
•	How to visualize the gender gap across various college degrees?
         
•	How to export the charts/diagram/graphs as an image file from the Jupyter notebooks?
    
•	How to clean the pictorial output and make it aesthetic for the management presentation?

### Goal Significance ### 

Why do we need to know the gender gap across college degrees? What benefit we could derive by visualizing the gender gaps in 
various degree programs? Below are the goals we can enlist: 

•	This information will give us an idea about the current market trends: i.e. 
   
  (1)	To understand the gender specific choice across various course degrees
  (2)	To identify the courses with severe gender gap that needs to be addressed
    
  •	This will help us to understand the gender wise market segmentation for various college degrees. 
  
### Data Source ###

The data is available for download at:

https://www.google.com/search?hl=en&gl=us&tbm=nws&authuser=0&q=gender+gap+stem&oq=gender+gap+stem&gs_l=newsDataLists

The data is available in the .csv file format. File name: "percent-bachelors-degrees-women-usa"

### Data Extraction Details ###

The dataset shows proportion of women across 17 different college degrees from 1970 thru 2011. The degrees can be broadly 
classified in to three broad categories: ‘STEM’, ‘Library Arts’ and ‘Other’.

### Visualize the Results ###

![Gender proportion across college degrees in compact tabular chart](https://github.com/mitrandatastat/gendergap/tree/master/images/output_3_0.png?raw=true)

![The compact tabular chart with clean X-axis labels](https://github.com/mitrandatastat/gendergap/tree/master/images/output_5_0.png?raw=true)

![The compact tabular chart with Limiting Values of Y-axis](https://github.com/mitrandatastat/gendergap/tree/master/images/output_7_0.png?raw=true)

![The compact tabular chart with 50% Demarcation Line](https://github.com/mitrandatastat/gendergap/tree/master/images/output_9_0.png?raw=true)

### Highlights of the code ###

>>> Software packages used:  

•	Python
 
•	Pandas
 
•	Matplotlib.pyplot

>>> Overview:

•	Read the data and form the data frame 
 
•	Classify the college degrees into three broad categories 
 
•	Plot line diagram to see how gender participation changes over the years 
 
•	Carry out series of actions to make the diagrams aesthetically clean and more presentable as:
(1)	Remove X-axis labels for all top and intermediate plots
(2)	Restrict Y-axis labels for limiting values only
(3)	Insert separation lines at 50% of Y-axis
 
•	Finally, export the tabular chart from Jupyter Book to a file 

### Explain the results in a simple, concise and easy way. (non-technical audience) ###

The analysis and results give very useful info about change in women’s preference for various college degrees over the years. The details can be easily seen in the tabular charts above. 

### Explain the results in the most technical way. (technical, data-scientist audience) ###

•	Women proportion dominate in the following degree programs:
(1)	Psychology
(2) Foreign Languages
(3)	English
(4)	Health Professions
(5)	Public Administration
(6)	Education
  
•	Men proportion dominate in the following degree programs:
(1)Computer Science
(2)	Engineering

•	Following degrees programs indicate significant changes in gender proportion with increased women students over the years:
(1)	Psychology
(2)	Biology
(3)	Physical Sciences
(4)	Communication and Journalism
(5)	Agriculture
(6)	Business
(7)	Architecture

•	Men and Women interest remain stable in the following degrees over the years:
(1)	Math and Statistics
(2)	Engineering
(3)	Foreign Languages
(4)	English
(5)	Art and Performance
(6)	Social Sciences and History
(7)	Health Professions
(8)	Public Administration
(9)	Education
 
•	The pictorial results can be easy to visualize for the management and technical audience, if we:
(1)	Remove excessive axis labels, 
(2)	Show data label once at the top of the diagram, and
(3) major data demarcation line for the target feature.
  
### Conclusion ###
>> What we learn from this outcome. (non-technical audience)

By this study, we can:

•	Understand how course preferences for men and women change over the time.
   
•	Visualize the degrees where men and women maintain their interest over the time.
   
•	Know about the courses where women student population clearly took over the proportion in their favor and dominates now. 
   
•	Realize that women participation improves significantly for number of degrees. However, men proportion does not improve considerably in any of the degree region but decline rather over the time.
   
•	Be sure that removing the axis clutter, showing minimal data labels and providing major data demarcation line make the results aesthetic and more presentable to the management. 
   
>>> Technical significance of the results. (technical, data-science audience)
   
Please refer to the technical results for the data science audience above. 


