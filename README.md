# Matplotlib Challenge
Overview
The tumor response to several cancer treatments were compared for 250 mice over the course of 45 days. Changes in tumor volume, number of metastatic sites and survival rate were calculated and analyzed. The results were visualized using Matplotlib.

Datasets
Two datasets were used in this analysis. The first called “mouse_drug_data.csv" contains the mouse ID and the treatment that was used. The second dataset called "data/clinicaltrial_data.csv" contains the mouse ID, and the tumor volume and metastatic sites at specific time points. 

General workflow
From the two datasets, Dataframes were created and merged on the mouse ID. First, the tumor response to treatment was calculated by calculating the average tumor volume for each drug at each time point. This shows how the tumor volume changes over time for each treatment. Also, the standard error of tumor volumes was calculated for each treatment and every timepoint. The results were graphed in a scatter plot using Matplotlib. 

