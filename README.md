# GunViolenceProject
Data Science Tools 1  Group Project - Summer 2022

Purpose: To analyze the mass shootings in the United States from Jan. 2013 to March 2018, inclusive. The dataset is from James Ko's repositiory (https://github.com/jamesqo/gun-violence-data) that incorporated data from the Gun Violence Archive. His dataset had 260k gun violence incidents.  

Due to the lack of federal definition of mass shooting, we have opted to define a mass shooting as an incident with three or more fatalies. This narrow down the dataset to just over 800 incidents.

Our original research question is we want to see the correlation between gun types and how they impact mass shootings and the shooter's attributes. However, we've realized that there is a very large number of unknown gun types in comparison to known gun types (you'll see a bar graph of it later in the code), so we've shifted our focus from that research question to more of exploratory data analysis (EDA) on our dataset. We did, however, do regression models on known gun types. 

Scope of Work:
- Data Preparation: Selected 16 columns/attributes from 29 attributes from the raw dataset, and extracted needed informations from selected columns. Sometimes we had to resort to recursive functions to extract the right attributes from a column due to double colon (::). 
- Data Analysis: Exploratory data analysis (EDA) and regression models on known gun types.
- Data Visualization: Pair plots by state, histogram of guns by type, maps, bar plots, boxplots, violin plots, and scatter plots. 

As the co-lead, I have split my energy and time with my partner on data cleaning and data extraction, exploratory data analysis (EDA), and creating regression models of a few selected variables. 

All code was written in Python via Jupyter Notebook. 
