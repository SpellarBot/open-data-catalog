# Combined Asthma Emergency Department and Hospitalizations by Census Tract, Town, Connecticut, 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/combined-asthma-emergency-department-and-hospitalizations-by-census-tract-town-connec-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/javn-ujwr) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/javn-ujwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/javn-ujwr/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | javn-ujwr |
| Name | Combined Asthma Emergency Department and Hospitalizations by Census Tract, Town, Connecticut, 2010-2014 |
| Attribution | CT Department of Public Health, CHIME ED and Hospitalization Data, US Census Bureau (2010) |
| Category | Health and Human Services |
| Tags | asthma, hospitalizations, emergency department |
| Created | 2016-07-18T17:54:48Z |
| Publication Date | 2016-07-19T11:17:53Z |

## Description

Note:  77% of overall reported events were geocoded by census tract level [ESRI ArcGIS], and the remaining 23% of events were equally weighted and redistributed proportionally within each town across the state. Therefore, all numbers and rates are estimates only, and reflect all asthma hospitalizations and ED visits that occurred in Connecticut from 2010-2014.
Rates based on counts fewer than 20 are unstable, and therefore are not presented; cells with less than 6 events are not displayed due to confidentiality regulations.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                            | Data Type | Render Type |
| ======== | ============== | ============================ | =============================== | ========= | =========== |
| Yes      | series tag     | town                         | Town                            | text      | text        |
| Yes      | series tag     | census_tract                 | Census Tract                    | text      | text        |
| Yes      | numeric metric | total_number_of_cases        | Total Number of Cases           | number    | number      |
| Yes      | numeric metric | total_rate_per_10_000        | Total Rate per 10,000           | number    | number      |
| Yes      | numeric metric | number_of_female_cases       | Number of Female Cases          | number    | number      |
| Yes      | numeric metric | female_rate_per_10_000       | Female Rate per 10,000          | number    | number      |
| Yes      | numeric metric | number_of_male_cases         | Number of Male Cases            | number    | number      |
| Yes      | numeric metric | male_rate_per_10_000         | Male Rate per 10,000            | number    | number      |
| Yes      | numeric metric | number_of_cases_19_years_old | Number of Cases <=19 Years Old  | number    | number      |
| Yes      | numeric metric | rate_per_10_000_19_years_old | Rate per 10,000  <=19 Years Old | number    | text        |
| Yes      | numeric metric | number_of_cases_20_years_old | Number of Cases >=20 Years Old  | number    | number      |
| Yes      | numeric metric | rate_per_10_000_20_years_old | Rate per 10,000 >=20 Years Old  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:javn-ujwr d:2010-01-01T00:00:00.000Z t:rate_per_10_000_19_years_old=. t:town=Greenwich t:census_tract=10101 m:total_number_of_cases=39 m:rate_per_10_000_20_years_old=15.2 m:female_rate_per_10_000=17.7 m:number_of_cases_19_years_old=14 m:total_rate_per_10_000=17.4 m:number_of_female_cases=21 m:number_of_cases_20_years_old=25 m:number_of_male_cases=18

series e:javn-ujwr d:2010-01-01T00:00:00.000Z t:rate_per_10_000_19_years_old=. t:town=Greenwich t:census_tract=10102 m:total_number_of_cases=48 m:rate_per_10_000_20_years_old=23.4 m:female_rate_per_10_000=23.9 m:male_rate_per_10_000=20.4 m:number_of_cases_19_years_old=14 m:total_rate_per_10_000=22.2 m:number_of_female_cases=26 m:number_of_cases_20_years_old=34 m:number_of_male_cases=22

series e:javn-ujwr d:2010-01-01T00:00:00.000Z t:rate_per_10_000_19_years_old=. t:town=Greenwich t:census_tract=10201 m:total_number_of_cases=21 m:number_of_cases_19_years_old=13 m:total_rate_per_10_000=12.3 m:number_of_female_cases=9 m:number_of_cases_20_years_old=8 m:number_of_male_cases=12
```

## Meta Commands

```ls
metric m:total_number_of_cases p:integer l:"Total Number of Cases" t:dataTypeName=number

metric m:total_rate_per_10_000 p:float l:"Total Rate per 10,000" t:dataTypeName=number

metric m:number_of_female_cases p:integer l:"Number of Female Cases" t:dataTypeName=number

metric m:female_rate_per_10_000 p:float l:"Female Rate per 10,000" t:dataTypeName=number

metric m:number_of_male_cases p:integer l:"Number of Male Cases" t:dataTypeName=number

metric m:male_rate_per_10_000 p:float l:"Male Rate per 10,000" t:dataTypeName=number

metric m:number_of_cases_19_years_old p:integer l:"Number of Cases <=19 Years Old" t:dataTypeName=number

metric m:number_of_cases_20_years_old p:integer l:"Number of Cases >=20 Years Old" t:dataTypeName=number

metric m:rate_per_10_000_20_years_old p:float l:"Rate per 10,000 >=20 Years Old" t:dataTypeName=number

entity e:javn-ujwr l:"Combined Asthma Emergency Department and Hospitalizations by Census Tract, Town, Connecticut, 2010-2014" t:attribution="CT Department of Public Health, CHIME ED and Hospitalization Data, US Census Bureau (2010)" t:url=https://data.ct.gov/api/views/javn-ujwr

property e:javn-ujwr t:meta.view v:id=javn-ujwr v:category="Health and Human Services" v:averageRating=0 v:name="Combined Asthma Emergency Department and Hospitalizations by Census Tract, Town, Connecticut, 2010-2014" v:attribution="CT Department of Public Health, CHIME ED and Hospitalization Data, US Census Bureau (2010)"

property e:javn-ujwr t:meta.view.license v:name="Public Domain"

property e:javn-ujwr t:meta.view.owner v:id=dby8-627v v:screenName="Gary Archambault" v:displayName="Gary Archambault"

property e:javn-ujwr t:meta.view.tableauthor v:id=dby8-627v v:screenName="Gary Archambault" v:roleName=editor v:displayName="Gary Archambault"
```

## Top Records

```ls
| town      | census_tract | total_number_of_cases | total_rate_per_10_000 | number_of_female_cases | female_rate_per_10_000 | number_of_male_cases | male_rate_per_10_000 | number_of_cases_19_years_old | rate_per_10_000_19_years_old | number_of_cases_20_years_old | rate_per_10_000_20_years_old | 
| ========= | ============ | ===================== | ===================== | ====================== | ====================== | ==================== | ==================== | ============================ | ============================ | ============================ | ============================ | 
| Greenwich | 10101        | 39                    | 17.399999999999999    | 21                     | 17.7                   | 18                   |                      | 14                           | .                            | 25                           | 15.2                         | 
| Greenwich | 10102        | 48                    | 22.2                  | 26                     | 23.9                   | 22                   | 20.399999999999999   | 14                           | .                            | 34                           | 23.4                         | 
| Greenwich | 10201        | 21                    | 12.3                  | 9                      |                        | 12                   |                      | 13                           | .                            | 8                            |                              | 
| Greenwich | 10202        | 108                   | 40.299999999999997    | 59                     | 41.9                   | 50                   | 39.299999999999997   | 51                           | 62.8                         | 57                           | 30.5                         | 
| Greenwich | 10300        | 54                    | 26.9                  | 22                     | 21.2                   | 31                   | 32                   | 18                           | .                            | 35                           | 25                           | 
| Greenwich | 10400        | 102                   | 38.6                  | 47                     | 33.700000000000003     | 55                   | 44                   | 48                           | 79.900000000000006           | 54                           | 26.4                         | 
| Greenwich | 10500        | 291                   | 105.9                 | 153                    | 104.1                  | 138                  | 108                  | 94                           | 151.4                        | 197                          | 92.7                         | 
| Greenwich | 10700        | 145                   | 81                    | 77                     | 76                     | 68                   | 87.6                 | 38                           | 94.8                         | 107                          | 77.099999999999994           | 
| Greenwich | 10800        | 21                    | 12.4                  | 14                     |                        | 7                    |                      | 10                           | .                            | 10                           |                              | 
| Greenwich | 10900        | 86                    | 35.299999999999997    | 59                     | 46.4                   | 27                   | 23.2                 | 40                           | 55                           | 46                           | 26.9                         | 
```