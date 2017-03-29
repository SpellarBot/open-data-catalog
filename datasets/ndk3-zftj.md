# Public Health Statistics- Tuberculosis cases and average annual incidence rate, Chicago, 2007- 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-tuberculosis-cases-and-average-annual-incidence-rate-chicago-2007-4fe37) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ndk3-zftj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ndk3-zftj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ndk3-zftj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ndk3-zftj |
| Name | Public Health Statistics- Tuberculosis cases and average annual incidence rate, Chicago, 2007- 2011 |
| Attribution | Public Health |
| Category | Health & Human Services |
| Created | 2012-02-29T21:06:31Z |
| Publication Date | 2014-04-11T17:03:08Z |

## Description

The annual number of new cases of tuberculosis and average annual tuberculosis incidence rate (new cases per 100,000 residents) with corresponding 95% confidence intervals, by Chicago community area, for the years 2007 – 2011.  See the full description at https://data.cityofchicago.org/api/assets/E0205898-C378-4299-97C1-F9F89AAF603C.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                             | Data Type | Render Type |
| ======== | ============== | ======================================= | ================================================ | ========= | =========== |
| Yes      | series tag     | community_area                          | Community Area                                   | text      | number      |
| Yes      | series tag     | community_area_name                     | Community Area Name                              | text      | text        |
| Yes      | numeric metric | cases_2006                              | Cases 2007                                       | number    | number      |
| Yes      | numeric metric | cases_2007                              | Cases 2008                                       | number    | number      |
| Yes      | numeric metric | cases_2008                              | Cases 2009                                       | number    | number      |
| Yes      | numeric metric | cases_2009                              | Cases 2010                                       | number    | number      |
| Yes      | numeric metric | cases_2010                              | Cases 2011                                       | number    | number      |
| Yes      | numeric metric | cases_2006_2010                         | Cases 2007 - 2011                                | number    | number      |
| Yes      | numeric metric | average_annual_incidence_rate_2006_2010 | Average Annual Incidence Rate 2007-2011          | number    | number      |
| Yes      | numeric metric | incidence_rate_lower_ci                 | Average Annual Incidence Rate 2007-2011 Lower CI | number    | number      |
| Yes      | numeric metric | incidence_rate_upper_ci                 | Average Annual Incidence Rate 2007-2011 Upper CI | number    | number      |
| Yes      | series tag     | warning                                 | WARNING                                          | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ndk3-zftj d:2007-01-01T00:00:00.000Z t:community_area_name="Rogers Park" t:community_area=1 m:incidence_rate_upper_ci=16.1 m:cases_2006=8 m:cases_2006_2010=32 m:cases_2007=7 m:cases_2008=4 m:cases_2009=6 m:incidence_rate_lower_ci=7.8 m:cases_2010=7 m:average_annual_incidence_rate_2006_2010=11.4

series e:ndk3-zftj d:2007-01-01T00:00:00.000Z t:community_area_name="West Ridge" t:community_area=2 m:incidence_rate_upper_ci=12.5 m:cases_2006=8 m:cases_2006_2010=32 m:cases_2007=7 m:cases_2008=5 m:cases_2009=3 m:incidence_rate_lower_ci=6.1 m:cases_2010=9 m:average_annual_incidence_rate_2006_2010=8.9

series e:ndk3-zftj d:2007-01-01T00:00:00.000Z t:community_area_name=Uptown t:community_area=3 m:incidence_rate_upper_ci=18.6 m:cases_2006=6 m:cases_2006_2010=39 m:cases_2007=8 m:cases_2008=13 m:cases_2009=2 m:incidence_rate_lower_ci=9.7 m:cases_2010=10 m:average_annual_incidence_rate_2006_2010=13.6
```

## Meta Commands

```ls
metric m:cases_2006 p:integer l:"Cases 2007" t:dataTypeName=number

metric m:cases_2007 p:integer l:"Cases 2008" t:dataTypeName=number

metric m:cases_2008 p:integer l:"Cases 2009" t:dataTypeName=number

metric m:cases_2009 p:integer l:"Cases 2010" t:dataTypeName=number

metric m:cases_2010 p:integer l:"Cases 2011" t:dataTypeName=number

metric m:cases_2006_2010 p:integer l:"Cases 2007 - 2011" t:dataTypeName=number

metric m:average_annual_incidence_rate_2006_2010 p:float l:"Average Annual Incidence Rate 2007-2011" t:dataTypeName=number

metric m:incidence_rate_lower_ci p:float l:"Average Annual Incidence Rate 2007-2011 Lower CI" t:dataTypeName=number

metric m:incidence_rate_upper_ci p:float l:"Average Annual Incidence Rate 2007-2011 Upper CI" t:dataTypeName=number

entity e:ndk3-zftj l:"Public Health Statistics- Tuberculosis cases and average annual incidence rate, Chicago, 2007- 2011" t:attribution="Public Health" t:url=https://data.cityofchicago.org/api/views/ndk3-zftj

property e:ndk3-zftj t:meta.view v:id=ndk3-zftj v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics- Tuberculosis cases and average annual incidence rate, Chicago, 2007- 2011" v:attribution="Public Health"

property e:ndk3-zftj t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:ndk3-zftj t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area | community_area_name | cases_2006 | cases_2007 | cases_2008 | cases_2009 | cases_2010 | cases_2006_2010 | average_annual_incidence_rate_2006_2010 | incidence_rate_lower_ci | incidence_rate_upper_ci | warning                                                                                                                             | 
| ============== | =================== | ========== | ========== | ========== | ========== | ========== | =============== | ======================================= | ======================= | ======================= | =================================================================================================================================== | 
| 1              | Rogers Park         | 8          | 7          | 4          | 6          | 7          | 32              | 11.4                                    | 7.8                     | 16.1                    |                                                                                                                                     | 
| 2              | West Ridge          | 8          | 7          | 5          | 3          | 9          | 32              | 8.9                                     | 6.1                     | 12.5                    |                                                                                                                                     | 
| 3              | Uptown              | 6          | 8          | 13         | 2          | 10         | 39              | 13.6                                    | 9.7                     | 18.6                    |                                                                                                                                     | 
| 4              | Lincoln Square      | 5          | 3          | 6          | 2          | 1          | 17              | 8.5                                     | 4.9                     | 13.6                    |                                                                                                                                     | 
| 5              | North Center        | 0          | 0          | 2          | 0          | 1          | 3               | 1.9                                     | 0.4                     | 5.5                     | Rate and confidence interval estimates are unreliable due to the very low number of reported tuberculosis cases during this period. | 
| 6              | Lake View           | 6          | 2          | 1          | 4          | 2          | 15              | 3.2                                     | 1.8                     | 5.2                     |                                                                                                                                     | 
| 7              | Lincoln Park        | 1          | 2          | 0          | 1          | 0          | 4               | 1.2                                     | 0.3                     | 3.2                     | Rate and confidence interval estimates are unreliable due to the very low number of reported tuberculosis cases during this period. | 
| 8              | Near North Side     | 5          | 5          | 9          | 1          | 2          | 22              | 5.5                                     | 3.5                     | 8.4                     |                                                                                                                                     | 
| 9              | Edison Park         | 0          | 0          | 1          | 0          | 0          | 1               | 1.8                                     | 0                       | 10                      | Rate and confidence interval estimates are unreliable due to the very low number of reported tuberculosis cases during this period. | 
| 10             | Norwood Park        | 1          | 1          | 0          | 1          | 0          | 3               | 1.6                                     | 0.3                     | 4.7                     | Rate and confidence interval estimates are unreliable due to the very low number of reported tuberculosis cases during this period. | 
```