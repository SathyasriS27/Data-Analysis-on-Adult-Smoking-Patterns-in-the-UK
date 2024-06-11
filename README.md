# Data-Analysis-on-Adult-Smoking-Patterns-in-the-UK

## Aim 🔍
The aim of this analysis is to understand the smoking patterns among adults in the UK. 

## Introduction 📊
Analysing adult smoking habits within the United Kingdom presents a complex yet vital endeavour in understanding public health behaviours. With a dataset focused on this issue, exploring the multifaceted dimensions of smoking patterns, prevalence, associated demographics, and potential trends becomes imperative. The UK, like many nations, grapples with the societal and health implications of smoking, making it a crucial subject for investigation. Through comprehensive analysis of this dataset, we aim to unveil insights that could inform targeted interventions, policy formulations, and public health campaigns to reduce smoking prevalence among adults, striving for a healthier and more informed society.

## About the Datasets 🚭
The "Adult Smoking Habits in the UK" dataset sourced from the [Office for National Statistics (ONS)](https://www.ons.gov.uk/). This dataset provides a comprehensive overview of smoking prevalence and trends among individuals aged 16 and above in the UK, incorporating data from diverse sources such as the [Annual Population Survey (APS)](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/methodologies/annualpopulationsurveyapsqmi) and the [Opinions and Lifestyle Survey (OPN)](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/healthandlifeexpectancies/methodologies/opinionsandlifestylesurveyqmi). The dataset encompasses various facets of smoking habits, including:
1. Demographic Information : Includes details on age, gender and geographic location, offering insights into the variations in smoking habits across different groups.
2. Smoking Status : Provides information on whether individuals are current, former, or non-smokers, contributing to a nuanced understanding of smoking behaviours.
3. Attempting to Quit : Offering insights into individuals who have made efforts to quit smoking and their daily smoking patterns, this data sheds light on the challenges and dynamics of smoking cessation.
4. Trends and Time-related Data : Historical data or trends in the data help us analyse changes in smoking prevalence, smoking habits, and associated factors across different years.

In addition, we have amalgamated our dataset with others, such as 'E-cigarette use in UK' and 'Smoking habits in UK-by Occupation.' This collaborative approach incorporates recent trends in nicotine consumption and explores additional factors contributing to smoking behaviours, providing a more comprehensive understanding of the landscape.

## Objective 🚬
Analyzing the Adult Smoking Habits in the UK dataset encompasses a diverse set of objectives with the goal of understanding smoking behaviours. These objectives include:
1. Understanding the Prevalence and the Trends of Smoking:
   * Identifying trends or patterns in smoking prevalence across various demographics and geographic areas.
   * To monitor how smoking habits have evolved over time.
   * Identifying and understanding trends and correlations between traditional cigarettes and e-cigarettes in recent times.
2. Identifying Factors Contributing to Smoking:
   * Revealing correlations between smoking and factors such as age, gender, and socio-economic status.
   * To identify the trends and correlations between cigarettes and e-cigarettes in the recent times.
   * Investigating individuals ready to quit smoking and examining their smoking behaviours.

Overall, the analysis of the Adult Smoking Habits in the UK dataset is a valuable tool for understanding smoking behaviour, its causes and consequences, and for informing effective public health policy and interventions aimed at reducing smoking and promoting a smoke-free society.

## System Design 👩🏻‍💻
### Architecture 🏛️

<div align="center"><img width="767" alt="Screenshot 2024-06-11 at 16 52 03" src="https://github.com/SathyasriS27/Data-Analysis-on-Adult-Smoking-Patterns-in-the-UK/assets/80045599/913c5e4f-42ab-4028-9ac1-7ae09f483da0"></div>


* Step 1 - Sourcing Data : The data on Adult Smoking Habits in the UK was obtained from the Office of National Statistics.
* Step 2 - Data Quality Check : In this step, we examine the data for missing values, errors, and overall legitimacy to ensure its integrity.
* Step 3 - Understanding Data : This involves gaining clarity on the objectives of the analysis and determining the specific actions needed to be taken with the data.
* Step 4 - Data Transformation : Transforming the data based on our objectives, which may include removing values, organizing the data, normalising the data and creating pivot tables.
* Step 5 - Data Exploration : Conducting an exploration of the data to uncover patterns and trends.
* Step 6 - Result : Utilizing graphical visualizations to illustrate and interpret the results of our exploration objectives effectively.

### Processing Modules and Algorithms  ➕
1. Converting the shape file (.shp) consisting of the boundaries for every county in the United Kingdom and adding their polygon geographic locations to a pandas dataframe using a library called geopandas. Merged this dataframe into the smokerspercentage dataset using the key ‘Local Authorities’ resulting to a dataframe with all values.
2. Eliminating outliers and focusing solely on weighted data from the year 2000 onward. Unweighted data predating 2000 is excluded.
3. Merging our primary dataset, "Adult Smoking Habits in the UK," with additional datasets on smoking based on occupation and data on e-cigarette usage in the UK.
4. Condensing the extensive datasets into compact pivot tables for comprehension.

## Acknowledgements 😼
Team members who made this project possible
1. Priyanka Singh
2. Omkar Pawar
3. Akshay Deshmukh




