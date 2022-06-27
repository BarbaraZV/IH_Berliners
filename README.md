# IH_Berliners
Project team: Barbara and Michael

#Project Name
Topic: Predicting Covid-19 related mortality rate in countries based on demographic and dietary factors.  
This combines multiple datasets on nutrition with a dataset on demographic information as independent/input variables.
Outcome/dependent variable is mortality rate (deaths from Covid-19 / total confirmed cases)

#### -- Project Status: [Active, In process]

## Project Intro/Objective
The purpose of this project is ......

### Methods Used
* EDA
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* MySql
* Pandas, jupyter

## Project Description
Data sources: 
* https://www.kaggle.com/code/mtmeanmachine/eda-and-projections/data?select=data.csv
* https://www.kaggle.com/datasets/mariaren/covid19-healthy-diet-dataset


files: 
  1. demographic country data
     - 258 rows x 347 columns
  2. Fat_Supply_Quantity_Data
     -  170 rows x 32 columns
  3. Food_Supply_kcal_Data
     -  170 rows x 32 columns
  4. Protein_Supply_Quantity_Data
     -  170 rows x 32 column

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

**DATA CLEANING (Monday)
  - Dropping columns
  - Merging files
  - Replacing non values
  
  New file: (IH_Berliners > Data > Final > full_merge_non_nan
  - copy_merged_file
  148 rows x 262 columns
  
** EDA 
  - Multicollinearity graphs
  - Histograms
  - Boxplots
  - Map bubbles



NOTES :


**Approaches Rafa suggest we explore**

- PCA - Principle component analysis

- Shapely value regression - to handle multicollinearity in the features

- Dimension reduction techniques such as RFE below
- Recursive feature elimination - to remove features rather than do it manually
