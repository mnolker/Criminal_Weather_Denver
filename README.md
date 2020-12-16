# Criminal_Weather_Denver

Project Title: Criminal Weather

**Team Members:** *(git repository user name)*
>- **Melanie Nolker** *(mnolker)*
>- **Lisa Stroh** *(Lisb020)*
>- **Kathy Nguyen** *(kcknguyen)*
>- **April Lagnevall** *(alagnevall)*
>- **Haifa Najdawi** *(HaifaNajdawi)*

Project Description/Outline: 
>- Does weather have an impact on a crime? Find if there is a correlation in non-traffic crime in the city of Denver compared to various weather conditions.
>>- Hypothesis: Weather has an impact on non-traffic crime in Denver.
>>- Null Hypothesis: Weather does not effect non-traffic crime in Denver.

Research questions to Answer:
>- Is there a correlation between crime & weather?  
>>- What type of offenses will be used to analyze crime rates?
>>- What weather conditions will be used to compare to offenses?

Datasets Used:
>- Violent Crime: https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-crime
>>- Denver city crime from 1-1-2016 to 9-9-20.csv
>>- filter for "Is Crime" = 1
>>- excluded traffic related offenses
>>- Grouped .csv data by: 
>>>- Occurrence_date
>>>- OFFENSE_TYPE_ID
>>>- OFFENSE_CATEGORY_ID
>- Weather API = https://www.worldweatheronline.com/developer/api/docs/historical-weather-api.aspx#qparameter
>>- API and pulls weather data for every day from 1/1/2016 to 8/31/2020
>>- pull muliple weather conditions
>>>- avg temperature (F)
>>>- avg precipitation (inches)
>>>- avg cloud cover (%)
>>>- avg wind speed (mph)

Rough breakdown of Tasks:
>-  Project coordinator / merger - Melanie Nolker

>- Crime dataset anaysis:
>>- Kathy Nguyen
>>- April Lagnevall

>- Weather dataset analysis:
>>- Haifa Najdawi 
>>- Lisa Stroh
