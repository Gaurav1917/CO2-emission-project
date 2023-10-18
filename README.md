# CO2-emission-project
1).Dataset: https://drive.google.com/drive/folders/1RN47O8SqxFfqkGZJS6kpb6GohR6ktdhQ?usp=sharing, https://www.kaggle.com/datasets/lobosi/c02-emission-by-countrys-grouth-and-population
.The dataset is a collection of some big factors that play into C02 Emissions, with everything from the Production and Consumption of each type of major energy source for each country and its pollution rating each year. It also includes each countries GDP, Population, Energy intensity per capita (person), and Energy intensity per GDP (per person GDP). All the data spans all the way from the 1980's to 2020.

2).About project:The ML model is used to predict the CO2 emission(in metric tonnes) by the countries from year 1980-2020.The dataset having 10 features in which CO2 emission is a target column.

     #Features:
     Country - Country in question
     Energy_type - Type of energy source
     Year - Year the data was recorded
     Energy_consumption - Amount of Consumption for the specific energy source, measured (quad Btu)
     Energy_production - Amount of Production for the specific energy source, measured (quad Btu)
     GDP - Countries GDP at purchasing power parities, measured (Billion 2015$ PPP)
     Population - Population of specific Country, measured (Mperson)
     Energy_intensity_per_capita - Energy intensity is a measure of the energy inefficiency of an economy. It is calculated as units of energy per unit of capita (capita = individual person), measured (MMBtu/person)
     Energy_intensity_by_GDP- Energy intensity is a measure of the energy inefficiency of an economy. It is calculated as units of energy per unit of GDP, measred (1000 Btu/2015$ GDP PPP)

     #Target column
     CO2_emission - The amount of C02 emitted, measured (MMtonnes CO2)

3).Algorithms and Accuracy of model: Since it is a regression model so we use r2_score and mean absolute error to look the performance of the model. We uses different algorithms(Linear Regression,Lasso,XGBregressor and Randomforest regressor). The best we get from randomforest regressor.

            #RandomForest regressor:
              1)Training data-
                  r2_score - 0.9986219
                  mean_absolute_error - 1.914
              2)Test data-
                  r2_score-0.993622
                  mean_absolute_error - 5.131
             At last we tune the hyperparameter for more better results.     
