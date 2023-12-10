# BaseBall EDA Case Study Analysis  
Exploratory Data Analysis Project 

This project conducts exploratory data analysis (EDA) on a dataset of career statistics for major league baseball players. The goal is to understand the relationships between different performance metrics and player salary. The Rmarkdown html code file can be found [here](https://github.com/omotuno/baseball_exploratory_data_analysis/blob/main/EDA-5470-PROJECT.html)

The analysis focuses on key variables like AtBat, Hits, and Salary. After cleaning the data and dealing with missing values, univariate analysis is performed to understand the distribution of individual variables. Bivariate analysis explores the relationships between variables through visualizations like scatterplots, boxplots, and spread-level plots.

## Some key steps include:

-- Handling missing data
<img width="853" alt="Screenshot 2023-12-10 at 4 34 00 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/e0fa3ceb-1b3a-4717-97c8-fef7ff4fadc4">

<img width="922" alt="Screenshot 2023-12-10 at 4 34 32 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/65ecd15d-1a10-4f0f-a77a-2e53efad3c24">

-- Exploring distributions of key variables

<img width="944" alt="Screenshot 2023-12-10 at 4 34 54 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/fb5caaa3-b3d2-4c8a-898d-13c5307daf93">
<img width="975" alt="Screenshot 2023-12-10 at 4 35 18 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/dd96ef56-6336-4be5-b046-bb6c161906a5">
<img width="955" alt="Screenshot 2023-12-10 at 4 35 36 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/207c636a-3725-4542-b9da-9cf4da73908b">

-- Checking for outliers
<img width="928" alt="Screenshot 2023-12-10 at 4 35 47 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/081a4695-d276-4c30-948b-ab372c75a5f4">

-- Using transformations to make distributions more symmetric
<img width="946" alt="Screenshot 2023-12-10 at 4 36 04 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/8fe884ea-c149-43c5-9e15-44b67d3a0dfa">
<img width="914" alt="Screenshot 2023-12-10 at 4 36 14 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/1ac7eecb-bd02-454b-9473-9c69b9cff266">

-- Fitting resistant models to understand relationships
<img width="938" alt="Screenshot 2023-12-10 at 4 36 43 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/f60cb74d-ac0e-43d8-804f-ec8a4b70f7c9">
<img width="926" alt="Screenshot 2023-12-10 at 4 36 53 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/eb6d28d7-5100-4740-8e9b-cde3041ef72c">


-- Binning data and constructing rootograms
<img width="943" alt="Screenshot 2023-12-10 at 4 37 12 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/a9f81497-40bc-499f-b83c-949a22855acf">
<img width="936" alt="Screenshot 2023-12-10 at 4 37 25 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/62f3b163-d0e1-4e18-83dd-c568f503e646">

<img width="880" alt="Screenshot 2023-12-10 at 4 37 37 PM" src="https://github.com/omotuno/baseball_exploratory_data_analysis/assets/65866718/a339f4b5-86e6-4b05-90a4-85617eb59495">

## The analysis provides insights like:

-- Salary has a positive correlation with AtBat

-- Hits are right skewed while AtBat is left skewed

-- Power transformations improve symmetry

-- Roots of Hits/AtBat deviate from normality

## Overall, this project demonstrates core EDA concepts and workflows that can be applied to any dataset. The methods help uncover insights and inform future modeling
