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

![line graph by year](/graphs/line_year_by_color.png)

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

![Scatter_offense_vs_temp](/graphs/Scatter_offense_vs_temp.png)

![Scatter_offense_vs_temp](/graphs/Scatter_offense_vs_temp.png)

![Scatter_offense_vs_temp](/graphs/Scatter_offense_vs_temp.png)

![Scatter_offense_vs_temp](/graphs/Scatter_offense_vs_temp.png)

Based on the p-value of # offenses to each weather condition…
> Reject Null Hypothesis:
<ol>
<li>Avg Temp (F) = 9.06 e-42</li>
</li>Cloud Cover (%) = 2.23 e-06</li>
</li>Precipitation (in) = 1.02 e-13</li>
> Failed to Reject Null Hypothesis:
<li>Wind Speed (mph) = 0.89<li>
<ol>
  
Rough breakdown of Tasks by group members:
>-  Project coordinator / merger - Melanie 
>- Crime dataset anaysis:
>>- Kathy 
>>- April 
>- Weather dataset analysis:
>>- Haifa 
>>- Lisa 
