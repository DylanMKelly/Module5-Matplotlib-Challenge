# Module 5 Assignment

This project is a demonstration of the use of matplotlib to develop graph data for analytical reviews. In this assignment you will see the following:

# Preparation of Data
 - Merging of two csv files (Mouse_metadata.csv, Study_results.csv) into one single DataFrame
 - Number of mice within merged data
 - Identifying duplicate mice found through Mouse ID and Timepoint data
 - Cleaned DataFrame excluding duplicate mice
 - Number of mice in cleaned merged data

# Generation of Summary Statistics
Calculations using groupby function categoized by Drug Regimens showing the following:
  - The mean of the tumor volume 
  - The median of the tumor volume 
  - The variance of the tumor volume  
  - The standard deviation of the tumor volume 
  - The SEM of the tumor volume  
  - A DataFrame created with the new summary statistics
  
# Creation of Bar Charts and Pie Charts
  - Bar Plot comparing total number of timepoints for all mice, categorized per Drug Regimen generated using Pandas and pyplot
  - Pie Plot showing distribution of females vs. male mice generated using Pandas and pyplot

# Calculation of Quartiles, Identifying Outliers, and Box Plot Graphic
  - A DatFrame created using the groupby function containing  the last timepoint for each mouse ID  
  - The index of the DataFrame is reset
  - Retrieval of the maximum timepoint for each mouse
  - A list containing the following four treatment groups: Capomulin, Ramicane, Infubinol, and Ceftamin 
  - An empty list is created to fill with tumor volume data 
  - A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group 
  - Box Plot displaying the distribution of the final tumor volume for all the mice by treatment group 

# Creation of Line Plot and Scatter Plot
  - Line Plot analysising one mouse from Capomulin comparing the tumor volume vs. time point 
  - Scatter Plot showing the average tumor volume vs. mouse weight for the Capomulin  

# Resources
The following are resources and links used to help with the creation of these scripts
 -  Used provided sample solution "pymaceuticals_starter.ipynb" to build and organize results, copying format and notes to help develop solutions
 -  Class recordings and posted answers to previous homework were used to help determine paths toward solutions, specifically outliers
 -  Matplotlib.org - "List of named colors": https://stackoverflow.com/questions/45751390/pandas-how-to-use-pd-cut](https://matplotlib.org/stable/gallery/color/named_colors.html
 -  Stack Overflow - "Dropping invalid columns FutureWarning" :[https://realpython.com/pandas-sort-python/](https://stackoverflow.com/questions/72223610/dropping-invalid-columns-futurewarning) 
 -  Stack Overflow - "python pandas groupby() results": https://stackoverflow.com/questions/17666075/python-pandas-groupby-result
 -  Towards Data Science - "Matplotlib Guide For People In A Hurry" : https://towardsdatascience.com/all-your-matplotlib-questions-answered-420dd95cb4ff
 -  Matplotlib.org - "matplotlib.pyplot.ylabel" :https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.ylabel.html
 -  Stack Overflow - "Selection with .loc in python" :https://stackoverflow.com/questions/44890713/selection-with-loc-in-python

# Additional Help 
TA assistance Sunil helped with corrections and formatting to errors in my intial school_sumary 

