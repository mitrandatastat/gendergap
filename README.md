{\rtf1\ansi\deff0{\fonttbl{\f0\fnil\fcharset0 Courier New;}{\f1\fnil\fcharset2 Symbol;}}
{\*\generator Msftedit 5.41.21.2510;}\viewkind4\uc1\pard\lang1033\f0\fs22 Objectives\par
Below is the list of questions that we are looking to answer as a final outcome of this project:\par
\par
\bullet\tab How to visualize the gender gap across various college degrees?\par
\par
\bullet\tab How to export the charts/diagram/graphs as an image file from the Jupyter notebooks?\par
\par
\bullet\tab How to clean the pictorial output and make it aesthetic for the management presentation?\par
\par
Goal Significance\par
Why do we need to know the gender gap across college degrees? What benefit we could derive by visualizing the gender gaps in various degree programs? Below are the goals we can enlist:\par
\par
\bullet\tab This information will give us an idea about the current market trends: i.e.\par
\par
(1)\tab To understand the gender specific choice across various course degrees (2)\tab To identify the courses with severe gender gap that needs to be addressed\par
\par
\bullet\tab This will help us to understand the gender wise market segmentation for various college degrees.\par
\par
Data Source\par
=======\par
# gendergap\par
This repository contains project that visualizes the gender gap in college degrees.\par
\par
### Objectives ###\par
\par
Below is the list of questions that we are looking to answer as a final outcome of this project:\par
    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 How to visualize the gender gap across various college degrees?\par
{\pntext\f1\'B7\tab}How to export the charts/diagram/graphs as an image file from the Jupyter notebooks?\par
{\pntext\f1\'B7\tab}How to clean the pictorial output and make it aesthetic for the management presentation?\par
\pard\par
### Goal Significance ### \par
\par
Why do we need to know the gender gap across college degrees? What benefit we could derive by visualizing the gender gaps in \par
various degree programs? Below are the goals we can enlist: \par
\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 This information will give us an idea about the current market trends: i.e. \par
\pard    \par
  (1)\tab To understand the gender specific choice across various course degrees\par
  (2)\tab To identify the courses with severe gender gap that needs to be addressed\par
    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 This will help us to understand the gender wise market segmentation for various college degrees. \par
\pard   \par
### Data Source ###\par
\par
#### The data is available for download at:\par
\par
https://www.google.com/search?hl=en&gl=us&tbm=nws&authuser=0&q=gender+gap+stem&oq=gender+gap+stem&gs_l=newsDataLists\par
\par
The data is available in the .csv file format. File name: "percent-bachelors-degrees-women-usa"\par
\par
#### Data Extraction Details:\par
\par
The dataset shows proportion of women across 17 different college degrees from 1970 thru 2011. The degrees can be broadly classified in to three broad categories: \lquote STEM\rquote , \lquote Library Arts\rquote  and \lquote Other\rquote .\par
\par
Highlights of the code\par
Software packages used:\par
\par
\bullet\tab Python\par
\par
\bullet\tab Pandas\par
\par
\bullet\tab Matplotlib.pyplot\par
\par
Overview:\par
\par
\bullet\tab Read the data and form the data frame\par
\par
\bullet\tab Classify the college degrees into three broad categories\par
\par
\bullet\tab Plot line diagram to see how gender participation changes over the years\par
\par
\bullet\tab Carry out series of actions to make the diagrams aesthetically clean and more presentable as: (1)\tab Remove X-axis labels for all top and intermediate plots (2)\tab Restrict Y-axis labels for limiting values only (3)\tab Insert separation lines at 50% of Y-axis\par
\par
\bullet\tab Finally, export the tabular chart from Jupyter Book to a file\par
\par
Explain the results in a simple, concise and easy way. (non-technical audience)\par
The analysis and results give very useful info about change in women\rquote s preference for various college degrees over the years. The details can be easily seen in the tabular charts above.\par
\par
Explain the results in the most technical way. (technical, data-scientist audience)\par
\bullet\tab Women proportion dominate in the following degree programs: (1)\tab Psychology (2) Foreign Languages (3)\tab English (4)\tab Health Professions (5)\tab Public Administration (6)\tab Education\par
\par
\bullet\tab Men proportion dominate in the following degree programs: (1)Computer Science (2)\tab Engineering\par
\par
\bullet\tab Following degrees programs indicate significant changes in gender proportion with increased women students over the years: (1)\tab Psychology (2)\tab Biology (3)\tab Physical Sciences (4)\tab Communication and Journalism (5)\tab Agriculture (6)\tab Business (7) Architecture\par
\par
\bullet\tab Men and Women interest remain stable in the following degrees over the years: (1)\tab Math and Statistics (2)\tab Engineering (3) Foreign Languages (4)\tab English (5)\tab Art and Performance (6)\tab Social Sciences and History (7)\tab Health Professions (8)\tab Public Administration (9)\tab Education\par
\par
\bullet\tab The pictorial results can be easy to visualize for the management and technical audience, if we: (1)\tab Remove excessive axis labels, (2)\tab Show data label once at the top of the diagram, and (3) major data demarcation line for the target feature.\par
\par
Conclusion\par
What we learn from this outcome. (non-technical audience)\par
\par
By this study, we can:\par
\par
\bullet\tab Understand how course preferences for men and women change over the time.\par
\par
\bullet\tab Visualize the degrees where men and women maintain their interest over the time.\par
\par
\bullet\tab Know about the courses where women student population clearly took over the proportion in their favor and dominates now.\par
\par
\bullet\tab Realize that women participation improves significantly for number of degrees. However, men proportion does not improve considerably in any of the degree region but decline rather over the time.\par
\par
\bullet\tab Be sure that removing the axis clutter, showing minimal data labels and providing major data demarcation line make the results aesthetic and more presentable to the management.\par
\par
Technical significance of the results. (technical, data-science audience)\par
\par
Please refer to the technical results for the data science audience above.\par
=======\par
### Data Extraction Details ###\par
\par
The dataset shows proportion of women across 17 different college degrees from 1970 thru 2011. The degrees can be broadly \par
classified in to three broad categories: \'e2\'80\'98STEM\'e2\'80\'99, \'e2\'80\'98Library Arts\'e2\'80\'99 and \'e2\'80\'98Other\'e2\'80\'99.\par
\par
### Visualize the Results ###\par
\par
#### 1. Gender proportion across college degrees in compact tabular chart\par
![output_3_0](https://user-images.githubusercontent.com/33802087/40476793-8535b304-5f62-11e8-854f-0105c6c8aee0.png)\par
\par
#### 2. The compact tabular chart with clean X-axis labels\par
![output_5_0](https://user-images.githubusercontent.com/33802087/40476892-cac1991a-5f62-11e8-80ad-aee2f23a26c5.png)\par
\par
#### 3. The compact tabular chart with Limiting Values of Y-axis\par
![output_7_0](https://user-images.githubusercontent.com/33802087/40476904-d2595398-5f62-11e8-89df-b50b6a3ffdbd.png)\par
\par
#### 4. The compact tabular chart with 50% Demarcation Line\par
![output_9_0](https://user-images.githubusercontent.com/33802087/40476915-d98f235e-5f62-11e8-8a2b-33056deac508.png)\par
\par
### Highlights of the code ###\par
\par
#### Software packages used:  \par
\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Python\par
{\pntext\f1\'B7\tab}Pandas\par
{\pntext\f1\'B7\tab}Matplotlib.pyplot\par
\pard\par
#### Overview:\par
\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Read the data and form the data frame\par
{\pntext\f1\'B7\tab}Classify the college degrees into three broad categories\par
{\pntext\f1\'B7\tab}Plot line diagram to see how gender participation changes over the years\par
{\pntext\f1\'B7\tab}Carry out series of actions to make the diagrams aesthetically clean and more presentable as:\line\par
\pard\li720 (1)\tab Remove X-axis labels for all top and intermediate plots\par
(2)\tab Restrict Y-axis labels for limiting values only\par
(3)\tab Insert separation lines at 50% of Y-axis\par
\pard  \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Finally, export the tabular chart from Jupyter Book to a file \par
\pard\par
### Explain the results in a simple, concise and easy way. (non-technical audience) ###\par
\par
The analysis and results give very useful info about change in womens' preference for various college degrees over the years. The details can be easily seen in the tabular charts above. \par
\par
### Explain the results in the most technical way. (technical, data-scientist audience) ###\par
\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Women proportion dominate in the following degree programs:\par
\pard\li720 (1)\tab Psychology\par
(2) \tab Foreign Languages\par
(3)\tab English\par
(4)\tab Health Professions\par
(5)\tab Public Administration\par
(6)\tab Education\par
\pard   \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Men proportion dominate in the following degree programs:\par
\pard\li720 (1)\tab Computer Science\par
(2)\tab Engineering\par
\pard\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Following degrees programs indicate significant changes in gender proportion with increased women students over the years:\par
\pard\li720 (1)\tab Psychology\par
(2)\tab Biology\par
(3)\tab Physical Sciences\par
(4)\tab Communication and Journalism\par
(5)\tab Agriculture\par
(6)\tab Business\par
(7)\tab Architecture\par
\pard\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Men and Women interest remain stable in the following degrees over the years:\par
\pard\li720 (1)\tab Math and Statistics\par
(2)\tab Engineering\par
(3)\tab Foreign Languages\par
(4)\tab English\par
(5)\tab Art and Performance\par
(6)\tab Social Sciences and History\par
(7)\tab Health Professions\par
(8)\tab Public Administration\par
(9)\tab Education\par
\pard  \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 The pictorial results can be easy to visualize for the management and technical audience, if we:\par
\pard\li720 (1)\tab Remove excessive axis labels, \par
(2)\tab Show data label once at the top of the diagram, and\par
(3) \tab major data demarcation line for the target feature.\par
\pard   \par
### Conclusion ###\par
\par
#### What we learn from this outcome. (non-technical audience)\par
\par
By this study, we can:\par
\par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Understand how course preferences for men and women change over the time.\par
\pard    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Visualize the degrees where men and women maintain their interest over the time.\par
\pard    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Know about the courses where women student population clearly took over the proportion in their favor and dominates now. \par
\pard    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Realize that women participation improves significantly for number of degrees. However, men proportion does not improve considerably in any of the degree region but decline rather over the time.\par
\pard    \par
\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720 Be sure that removing the axis clutter, showing minimal data labels and providing major data demarcation line make the results aesthetic and more presentable to the management. \par
\pard    \par
#### Technical significance of the results. (technical, data-science audience)\par
   \par
Please refer to the technical results for the data science audience above. \par
}
 