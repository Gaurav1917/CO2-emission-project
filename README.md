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

## The Aim of our study is to answer the below research questions:

#### a) How CO2 emission changes with Year?.
#### b) Does GDP and Population affect CO2 emission?.
#### c) How energy consumption related to CO2 emission?.
#### d) Which energy type has more CO2 emission?.
#### e) Which energy type consume and produce more Energy?.
#### f) How energy consumption varies with Year?.
#### g) How GDP affect Energy consumption?.



### a) How CO2 emission changes with Year?.

 ![download (12)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/d161d01e-ce96-44d1-aca9-3fd5f4866bb7)
 
 Yes! CO2 emission changes with year.

            From graph-
            #) The Co2 emission is Minimum before 1980.
            #) From 1980-1982 there is a slight increase in CO2 emission.
            #) The slight variation in graph is occuring in following Years:
                  (1993-1995,2008-2010,2018-2019)
            #) If we ignore the variation given above, the trend in graph is almost linearly i.e CO2 emission increases with year.


### b) Does GDP and Population affect CO2 emission?.

![download (2)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/27d7e1a3-caf0-4011-93bf-25668e145d86)

![download (3)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/0844bc30-66eb-4fd4-8f99-2ead0de679be)

GDP and Population affect CO2 emission:

         From Graph-
         1) GDP:
                #)The slight Variation in starting but after 300000(in GDP) the CO2 emission increases with increase in 
                GDP.
          2) Population:
                #)Variations:
                   a)Peak- The first peak occurs when the population is 310000
                           The second peak occurs when the population is 1410000
                           Third peak occurs at the population 4510000
                      during the population given above the CO2 emission is maximum.
                      After Third peak the CO2 emission varies almost linearly(increases with population) with population.


### c) How energy consumption related to CO2 emission?.  

![download (1)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/ab0c51c0-353f-4a0c-8655-eac094527038)


Energy consumption related to CO2 emission:

         #) From the graph we see that the variation of CO2 emission is linearly with Energy consumption.
         #) If country consumes more energy than also the country emmit more CO2.


### d) Which energy type has more CO2 emission?.

![download](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/2f81af9b-6ce0-4314-af30-29b0772893b2)

From Bar plot:

          #) All energy types has largest emitter of CO2.
          #) After All energy types the variation in consumption is
             (Petroleum > Coal > natural gas)
          petroleum is the second largest emitter of CO2.

          
                 
### e) Which energy type consume and produce more Energy?.

![download (4)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/cd6c5e59-27ce-4111-9ed8-72a70cdbf575)

![download (5)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/24b64591-a310-41e3-b8ec-bc40201698f6)

Energy consumption and Production.

        #) Majority of Energy is Producing and Consuming by the countries from All energy types.
        #) After All energy types , the countries Consuming and producing more energy from Petroleum and other liquids.
        #) The Consumption and production is minimum from renewables and other.
     (Petroleum > Nuclear > Coal > Natural gas > Renewables)
     

### f) How energy consumption varies with Year?.    

![download (6)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/af1f224a-9cab-421e-a927-a374fea25ae1)

Energy Consumption Varies with Year.

      #Starting from 1980s there is not a proper trend in Consumption and 
      also a slight increasing,decreasing trend.
      #)But after 2010 the energy consumption is increases almost linearly.

      Variations in Graph-
      a) 1980-1992
      b) 1995-2009
      c) 2010-2019

### g) How GDP affect Energy consumption?.   

 ![download (7)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/fa0a700c-d521-4f48-b6b4-019f41e17091)



 



## 5).Drive link to download a large files: https://drive.google.com/drive/folders/1RN47O8SqxFfqkGZJS6kpb6GohR6ktdhQ?usp=sharing

## 6).Sample 1:

![Screenshot (10)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/be626210-a677-4559-8217-084bb26d703e)

## 7).Sample 2:

![Screenshot (11)](https://github.com/Gaurav1917/CO2-emission-project/assets/146158309/6e2aa902-5be0-4f7a-9223-04a0f0d9a568)

             
             
