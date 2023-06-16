# Group4 Project2 - Data Visualisation with Python Moringa Course

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

Visualisations;
1. Missing Data

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/5d0acea0-1b08-4aee-a44b-68fc3b93ff4d)

2. Histograms showing the distributions of Life expectancy (men), Life expectancy(women), Depression (%)

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/c46507ef-eea4-434c-84b1-ff60f198071d)

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/dfa09e9a-e42b-4004-8500-5870ae51b277)

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/24611eb9-9fe1-4f34-87b4-5cc317474dd8)

3. Exploring Correlations in our Dataset

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/1ab83087-2ff2-4743-a6c8-fe67fd4c6c61)

4. Life Expectancy for Men and Women per Country in 2015

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/588f915e-cbb7-4b79-a73d-38f743a9c353)

5. Prevalence of Mental Health Disorders in EAC Countries in 2015

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/6791d4a9-946d-435b-ab82-27b4ae446fb2)

6. Prevalence of Mental Health Disorders in European Countries in 2015

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/346bc17b-d005-467f-a184-9b5b0faf5349)

7. Depression (%) vs. Income composition of resources

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/24dca692-21d5-4d59-8ef7-74942b717e91)

8. Life Expectancy for Men vs. Depression (%)

  ![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/593c4b4a-ecf4-4e1c-9042-3c9705bf1d26)

9. Life expectancy(women) vs. Depression (%)

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/4fcdb856-a061-4590-b47f-f5181ff36780)

10. Eating disorders (%) vs. BMI

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/b190351d-5bc4-492d-95de-a8a642bdc226)

11. Top 10 countries with the highest rates of Depression

![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/e261bb1b-d9b8-405d-ba9a-1aec98ace961)

12. Bottom 10 countries with the least GDP

  ![image](https://github.com/26margaretwanjiru/Group4_Project2/assets/34502518/79c16d66-0f2c-457f-a2a9-377dcc1cdfb1)


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
