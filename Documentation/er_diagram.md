# Entity-Relationship Diagram

## Entities

Country  
- country_code (Primary Key)  
- country  

CountryYearData  
- country_code (Foreign Key)  
- year  
- life_expectancy  
- mortality_u5  
- fertility_adolescent  

## Relationship

One Country can have many CountryYearData records.

Country (country_code, country)  
        |  
        | 1-to-many  
        |  
CountryYearData (country_code, year, life_expectancy, mortality_u5, fertility_adolescent)  

## Explanation

The country_code field links the country information to the yearly indicator data.  
Each country appears multiple times because data is recorded for multiple years.
