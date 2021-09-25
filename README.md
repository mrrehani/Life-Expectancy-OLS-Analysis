This project is focused on using machine learning to predict life expectancy based on a wide range of factors. To achieve this, I used a multiple linear regression method and combined this with interactive graphs and displays to demonstrate how variables like education and average GDP link to life expectancy across continents. I ensured that all data I used fit key assumptions for the regression analysis and worked to correct for factors like heteroscedasticity, multicollinearity, etc. that can potentially disrupt my end results. 
The data is from the following website: https://www.kaggle.com/kumarajarshi/life-expectancy-who. 
The project allows the user to input their own values for the variables to recieve their estimated life expectancy at birth. 
Below are the units for each of the variables (copied from the source of the data):
-Year: 
-Adult Mortality: "Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)"
-Alcohol: "Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)" 
-Percentage Expenditure: "Expenditure on health as a percentage of Gross Domestic Product per capita(%)"
-Hepatitis B: "Hepatitis B (HepB) immunization coverage among 1-year-olds (%)"
-Measles: "Measles - number of reported cases per 1000 population"
-BMI: "Average Body Mass Index of entire population" 
-Under-Five Deaths: "Number of under-five deaths per 1000 population"
-Polio:"Polio (Pol3) immunization coverage among 1-year-olds (%)"
-Total Expenditure: "General government expenditure on health as a percentage of total government expenditure (%)"
-Diphtheria: "Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)" 
-HIV/AIDS: "Deaths per 1 000 live births HIV/AIDS (0-4 years)"
-GDP: "Gross Domestic Product per capita (in USD)"
-Population: "Population of the country" 
-Thinness 1-19 Years: "Prevalence of thinness among children and adolescents for Age 10 to 19 (%)"
-Thinness 5-9 Years: "Prevalence of thinness among children for Age 5 to 9(%)"
-Income composition of resources: "Human Development Index in terms of income composition of resources (index ranging from 0 to 1)"
-Schooling: "Number of years of Schooling(years)"
-Continent_AS: Whether or not the area is in Asia (1 if it is, 0 if it is not)
-Continent_EU: Whether or not the area is in Europe (1 if it is, 0 if it is not)
-Continent_AF: Whether or not the area is in Africa (1 if it is, 0 if it is not)
-Continent_SA: Whether or not the area is in South America (1 if it is, 0 if it is not)
-Continent_OC: Whether or not the area is in Oceana (1 if it is, 0 if it is not)
-Status_Developed: Whether or not the area is in a developed country (1 if it is, 0 if it is not)
