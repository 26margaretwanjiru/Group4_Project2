# Group4 Project2 Data Visualisation with Python Moringa Course

Group 4 Members:
KENNETH MARARO
FELIX MUCHANGA
GABRIEL OTIENO
ABIGAEL GITAU
MARGARET KINYANJUI


Disclaimer;

This project may contain sensitive topics on mental health disorders that may make some people feel uncomfortable.

We realize that there is a variety of types and extents of mental illnesses which we will not be able to cover due to time. We acknowledge that they exist and should not be ignored.

# 1. Background

The original dataset i.e. Life Expectancy contains 2938 entries with 25 columns by Marya Lebron while the second data set i.e. Global Trends in Mental Health Disorder contains 108553 entries and 11 columns by https://data.world/amitd. The data sets were obtained from Kaggle.

The 2 data sets used contain informative data from countries across the globe about;
1. Factors that affect life expectancy in men and women such as status of the country, adult mortality, infant deaths, expenditure, immunization coverage etc.

2. The prevalence of mental health disorders including schizophrenia, bipolar disorder, eating disorders, anxiety disorders, drug use disorders, depression, alcohol use disorders.

The data sources;

Life Expectancy Data by Country available here; https://www.kaggle.com/datasets/maryalebron/life-expectancy-data

Global Trends in Mental Health Disorder available here; https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder

# 2. Objectives

The objectives of the analysis are as follows:

1. To explore how life expectancy compares between men and women for our selected sample data sets inclusive of developed and developing countries where the developing countries are within East African Community and the 5 developed countries are within Europe.

2. To visualize the prevalence of mental health disorders comparing and contrasting depression, anxiety, and alcohol use disorders across the sample countries in 2015.

3. To illustrate the relationship between eating disorders and BMI.

4. To show how the mental health disorders have an impact on life expectancy for both men and women.

5. To demonstrate and visualize whether higher depression means lower income composition of resources for all countries.

# 3. Data

#Load the first data set i.e. life expectancy data

df1 = pd.read_csv("C:/Users/kinyanjuim/Desktop/Project2_Groupwork/life expectancy data/Life_Expectancy_Data_v2.csv")

#Load the second data set i.e. Global Trends in Mental Health Disorder

df2 = pd.read_csv("C:/Users/kinyanjuim/Desktop/Project2_Groupwork/mental health data/Mental_health_Depression_disorder_Data.csv", 
                  low_memory=False)

# 4. Conclusion

1. Alcohol use has a positive correlation with life expectancy. The higher the alcohol use, the shorter the life expectancy.
2. There's a positive correlation between eating disorders and BMI.
3. There's a positive correlation between anxiety disorders and depression.
4. The higher the effective utilization of a company’s resources, the lower the depression rates.
5. Uganda had the highest depression rates in comparison to the other EAC countries while Kenya had the least. In Europe, Sweden had the highest depression rates in comparison to the other European countries while Denmark had the least rates.

# 5. Recommendations

1. Hospitals, health institutions – Provision of network support of mental health care providers and affordable services.

2. Non-government Organizations (NGOs) e.g. WHO - Develop awareness within communities to break stigma, and provide opportunities for collaboration between providers, patients and local communities.

3. Leaders within society to champion for research resources and funding within mental health institutions.

Beneficiaries of the results/ outcome from the project;
1. Hospitals, health institutions
2. Non-government Organizations (NGOs) e.g WHO
3. Leaders within society

Future Work

A data scientist will never have enough time to explore all aspects of dataset. If you had more time, what other aspects of the dataset would you explore?

1. Predictive analytics using Machine Learning models; Regression etc

2. Combined the data with treatment data and assess impact changes on life expectancy.

3. Geospatial analysis of the prevalence of mental disorders across various continents.

# 6. Thank you.
