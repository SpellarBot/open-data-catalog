# Choose Maryland: Compare Counties - Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-workforce) |
| Metadata | [Link](https://data.maryland.gov/api/views/q7q7-usgm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/q7q7-usgm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/q7q7-usgm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | q7q7-usgm |
| Name | Choose Maryland: Compare Counties - Workforce |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, county, compare, workforce, labor, employment, workers, wage, salary, earnings, industry |
| Created | 2013-11-15T16:35:24Z |
| Publication Date | 2016-12-08T16:56:09Z |

## Description

Workforce summary - employment, unemployment, participation rates, earnings, establishments

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                                | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | county                                                     | County                                                     | text      | text        |
| Yes      | numeric metric | labor_force                                                | Labor Force                                                | number    | number      |
| Yes      | numeric metric | employment                                                 | Employment                                                 | number    | number      |
| Yes      | numeric metric | unemployment                                               | Unemployment                                               | number    | number      |
| Yes      | numeric metric | unemployment_rate                                          | Unemployment Rate (%)                                      | percent   | percent     |
| Yes      | numeric metric | labor_force_participation_rate_total                       | Labor Force Participation Rate, Total (%)                  | percent   | percent     |
| Yes      | numeric metric | average_annual_employment_total                            | Average Annual Employment, Total                           | number    | number      |
| Yes      | numeric metric | average_weekly_wage_total_dollars                          | Average Weekly Wage, Total ($ Dollars)                     | number    | number      |
| Yes      | numeric metric | number_of_business_establishments                          | Number of Business Establishments                          | number    | number      |
| Yes      | numeric metric | number_of_business_establishments_with_100_or_more_workers | Number of Business Establishments with 100 or More Workers | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q7q7-usgm d:2016-12-08T16:55:41.000Z t:county="Allegany County" m:unemployment_rate=7.1 m:number_of_business_establishments=1534 m:employment=30421 m:unemployment=2311 m:labor_force_participation_rate_total=53.3 m:average_weekly_wage_total_dollars=707 m:average_annual_employment_total=29003 m:labor_force=32732 m:number_of_business_establishments_with_100_or_more_workers=34

series e:q7q7-usgm d:2016-12-08T16:55:41.000Z t:county="Anne Arundel County" m:unemployment_rate=4.5 m:number_of_business_establishments=14714 m:employment=286525 m:unemployment=13543 m:labor_force_participation_rate_total=70.9 m:average_weekly_wage_total_dollars=1072 m:average_annual_employment_total=260458 m:labor_force=300068 m:number_of_business_establishments_with_100_or_more_workers=344

series e:q7q7-usgm d:2016-12-08T16:55:41.000Z t:county="Baltimore City" m:unemployment_rate=7.7 m:number_of_business_establishments=13291 m:employment=272756 m:unemployment=22726 m:labor_force_participation_rate_total=61.9 m:average_weekly_wage_total_dollars=1196 m:average_annual_employment_total=334066 m:labor_force=295482 m:number_of_business_establishments_with_100_or_more_workers=402
```

## Meta Commands

```ls
metric m:labor_force p:integer l:"Labor Force" t:dataTypeName=number

metric m:employment p:integer l:Employment t:dataTypeName=number

metric m:unemployment p:integer l:Unemployment t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate (%)" t:dataTypeName=percent

metric m:labor_force_participation_rate_total p:float l:"Labor Force Participation Rate, Total (%)" t:dataTypeName=percent

metric m:average_annual_employment_total p:integer l:"Average Annual Employment, Total" t:dataTypeName=number

metric m:average_weekly_wage_total_dollars p:integer l:"Average Weekly Wage, Total ($ Dollars)" t:dataTypeName=number

metric m:number_of_business_establishments p:integer l:"Number of Business Establishments" t:dataTypeName=number

metric m:number_of_business_establishments_with_100_or_more_workers p:integer l:"Number of Business Establishments with 100 or More Workers" t:dataTypeName=number

entity e:q7q7-usgm l:"Choose Maryland:  Compare Counties - Workforce" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/q7q7-usgm

property e:q7q7-usgm t:meta.view v:id=q7q7-usgm v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Workforce" v:attribution="Maryland Department of Commerce"

property e:q7q7-usgm t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:q7q7-usgm t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | labor_force | employment | unemployment | unemployment_rate | labor_force_participation_rate_total | average_annual_employment_total | average_weekly_wage_total_dollars | number_of_business_establishments | number_of_business_establishments_with_100_or_more_workers | 
| =========== | =================== | =========== | ========== | ============ | ================= | ==================================== | =============================== | ================================= | ================================= | ========================================================== | 
| 1481216141  | Allegany County     | 32732       | 30421      | 2311         | 7.1               | 53.3                                 | 29003                           | 707                               | 1534                              | 34                                                         | 
| 1481216141  | Anne Arundel County | 300068      | 286525     | 13543        | 4.5               | 70.9                                 | 260458                          | 1072                              | 14714                             | 344                                                        | 
| 1481216141  | Baltimore City      | 295482      | 272756     | 22726        | 7.7               | 61.9                                 | 334066                          | 1196                              | 13291                             | 402                                                        | 
| 1481216141  | Baltimore County    | 444854      | 420626     | 24228        | 5.4               | 66.6                                 | 370665                          | 1007                              | 21012                             | 519                                                        | 
| 1481216141  | Calvert County      | 47681       | 45466      | 2215         | 4.6               | 70.3                                 | 22579                           | 914                               | 1794                              | 20                                                         | 
| 1481216141  | Caroline County     | 17461       | 16486      | 975          | 5.6               | 65.4                                 | 9185                            | 767                               | 627                               | 12                                                         | 
| 1481216141  | Carroll County      | 93569       | 89535      | 4034         | 4.3               | 68.9                                 | 56765                           | 795                               | 4461                              | 66                                                         | 
| 1481216141  | Cecil County        | 53245       | 50042      | 3203         | 6.0               | 65.7                                 | 30603                           | 864                               | 1879                              | 36                                                         | 
| 1481216141  | Charles County      | 80945       | 76849      | 4096         | 5.1               | 69.5                                 | 42064                           | 828                               | 2791                              | 39                                                         | 
| 1481216141  | Dorchester County   | 15849       | 14683      | 1166         | 7.4               | 65.0                                 | 11087                           | 736                               | 699                               | 17                                                         | 
```