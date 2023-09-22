# Data-Visualization by YK
Pymaceuticals Inc., a pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. 
Access given to complete data of most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. 
Timeline of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of their drug; Capomulin against other drug treatment regimens.
All of the tables and figures were generated for the technical report of the clinical study besides the summary of the study results.

Instructions of this work:
This assignment is broken down into the following tasks:

•	Preparation of the data:

    - The datasets are merged into a single DataFrame

    - The number of mice are shown from the merged DataFrame
    
    - Each duplicate mice is found based on the Mouse ID and Timepoint
    
    - A clean DataFrame is created with the dropped duplicate mice
    
    - The number of mice are shown from the clean DataFrame


•	Generation of summary statistics:

    - The Mean of the tumor volume for each regimen is calculated using Groupby

    - The Median of the tumor volume for each regimen is calculated using Groupby
    - The Variance of the tumor volume for each regimen is calculated using Groupby
    
    - The Standard Deviation of the tumor volume for each regimen is calculated using Groupby
    
    - The SEM of the tumor volume for each regimen is calculated using Groupby
    
    - A new DataFrame is created by using the summary statistics

    
•	Creation of bar charts and pie charts:

    - A Bar Plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated
    
    - A Bar Plot showing the total number of timepoints for all mice tested for each drug regimen using Pyplot is generated
    
    - A Pie Plot showing the distribution of female versus male mice using Pandas is generated
    
    - A Pie Plot showing the distribution of female versus male mice using Pyplot is generated


•	Calculation of quartiles, outliers and creation of a box plot:

    - A DatFrame that has the last timepoint for each mouse ID is created using Groupby
    
    - The index of the DataFrame resets
    
    - Retrieve the maximum timepoint for each mouse
    
    - The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list
    
    - An empty list is created to fill with tumor volume data
    
    - A For Loop is used to display the Interquartile Range (IQR) and the Outliers for each treatment group
    
    - A Box Plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group


•	Creation of a line plot and a scatter plot:

    - A line plot is generated that shows the tumor volume vs. time point for single mouse treated with Capomulin
    
    - A scatter plot is generated that shows average tumor volume vs. mouse weight for the entire Capomulin treatment regimen


•	Calculation of correlation and regression:

    - The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen
    
    - A Plot is generated on top of the previous scatter plot for the linear regression model 


•	Final analysis:

    - Observations and inferences
