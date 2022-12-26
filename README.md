# Datatone. Team Pawfull 🐾

## Table of contents 
[1. Our team](https://github.com/ekaterinatao/datatone_Pawfull#team)   
[2. Description](https://github.com/ekaterinatao/datatone_Pawfull#description)   
[3. Aim](https://github.com/ekaterinatao/datatone_Pawfull#aim)  
[4. Datasets](https://github.com/ekaterinatao/datatone_Pawfull#datasets)  
[5. Results](https://github.com/ekaterinatao/datatone_Pawfull#results)  

## Team
[Ekaterina Tao](https://github.com/ekaterinatao) - project manager  
[Eugene Baev](https://github.com/EugeneBaev-dsu4) - product manager  
[Kseniya Belousova](https://github.com/Kseniyabel) - data analyst  
[Arina Mironova](https://github.com/Nenneke2999) - data analyst  
Alexander Nesterov - data analyst  
Andrej Agafonov - data analyst   

## Description
Here is our team project for datatone. We preprocessed several datasets and create our own for further analysis. Different datasets contain information related to mortality, air pollution, smoking rate and happiness level.   

## Aim
To describe relationship between air pollution, smoking rate, happiness level of people and mortality rate caused by respiratory diseases.   

**Briefing**  
- Pipeline of data analysis you can find in the main notebook.  
- There are 8 datasets.
- We should preprocess row data and create own dataset for analysis.
- We should perform EDA and prepare data for modeling.
- *We should perform prediction model with target parameter 'mortality'.  

**Skills**  
  
Train team building.    
Train time memanagement.   
Train row data preprocessing.  
Train analytics skills.   
Train data modeling.      

## Datasets
You can find all datasets in the project folder [data](https://github.com/ekaterinatao/datatone_Pawfull/tree/master/data).  
  
Original sourses of data:  
1. [Air pollution](https://sedac.ciesin.columbia.edu/data/set/aqdh-country-trends-major-air-pollutants-2003-2018)  
2. [Mortality rate](https://ourworldindata.org/grapher/respiratory-disease-death-rate)  
3. [Smoking prevalence](https://ourworldindata.org/smoking)  
4. [Happiness data](https://www.kaggle.com/datasets/unsdsn/world-happiness)  

**Modified dataset**
We have created new dataset using information from data above. You can find our dataset [here](https://github.com/ekaterinatao/datatone_Pawfull/blob/master/final_dataset.csv).  
We have selected features for further analysis. The complete list is below.

**Parameters**
- country  
- year  
- increase_mort - mortality difference between previous and current year
- smoke_prev - Prevalence of current tobacco use (% of adults)  
- increse_smoke - smoke prevalence difference between previous and current year  
- CO - carbon monooxide Population-Weighted (ppm)  
- CO-mean  
- uplift_CO - difference between previous and current year  
- O3 - ozone Population-Weighted (ppm)  
- O3_mean  
- uplift_O3 - difference between previous and current year  
- PM - particulate matter (pollution) Pop.-Weighted (kg m^-3)  
- PM_mean  
- uplift_PM - difference between previous and current year  
- Family - mean number of family members  
- Freedom  
- Generosity  
- Happiness Score - score based on answers to the main life evaluation question asked in the poll (known as the Cantril ladder)  
- Economy (GDP per Capita) - Gross domestic product per Capita  
- Health (Life Expectancy)  
- Trust (Government Corruption)  
- Dystopia Residual  

**Target feature**
- mortality - Deaths from Chronic respiratory diseases per 100 000 population  

## Results
- Row datasets were preprecessed and features were selected.  
- Dataset was created for further analysis.  
- EDA and hypothesis testing were performed.  
- Multicollinearity was checked and feature selection was performed.  
- Several regression models were realized (detailed info in colab [notebook](https://github.com/ekaterinatao/datatone_Pawfull/blob/master/Team_Pawfull.ipynb)).