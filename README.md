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
    o	To understand the gender specific choice across various course degrees
    o	To identify the courses with severe gender gap that needs to be addressed
  •	This will help us to understand the gender wise market segmentation for various college degrees. 
  
### Data Source ###

The data is available for download at:

https://www.google.com/search?hl=en&gl=us&tbm=nws&authuser=0&q=gender+gap+stem&oq=gender+gap+stem&gs_l=newsDataLists

The data is available in the .csv file format. File name: "percent-bachelors-degrees-women-usa"

### Data Extraction Details ###

The dataset shows proportion of women across 17 different college degrees from 1970 thru 2011. The degrees can be broadly 
classified in to three broad categories: ‘STEM’, ‘Library Arts’ and ‘Other’.

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
 
  o	Remove X-axis labels for all top and intermediate plots
  o	Restrict Y-axis labels for limiting values only
  o	Insert separation lines at 50% of Y-axis
 
•	Finally, export the tabular chart from Jupyter Book to a file 

### Explain the results in a simple, concise and easy way. (non-technical audience) ###

The analysis and results give very useful info about change in women’s preference for various college degrees over the years. The details can be easily seen in the tabular charts above. 

### Explain the results in the most technical way. (technical, data-scientist audience) ###

•	Women proportion dominate in the following degree programs:
  o	Psychology
  o	Foreign Languages
  o	English
  o	Health Professions
  o	Public Administration
  o	Education
  
•	Men proportion dominate in the following degree programs:
  o	Computer Science
  o	Engineering

•	Following degrees programs indicate significant changes in gender proportion with increased women students over the years:
  o	Psychology
  o	Biology
  o	Physical Sciences
  o	Communication and Journalism
  o	Agriculture
  o	Business
  o	Architecture

•	Men and Women interest remain stable in the following degrees over the years:
  o	Math and Statistics
  o	Engineering
  o	Foreign Languages
  o	English
  o	Art and Performance
  o	Social Sciences and History
  o	Health Professions
  o	Public Administration
  o	Education
 
•	The pictorial results can be easy to visualize for the management and technical audience, if we:
  o	Remove excessive axis labels, 
  o	Show data label once at the top of the diagram, and
  o	Provide major data demarcation line for the target feature.
  
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


