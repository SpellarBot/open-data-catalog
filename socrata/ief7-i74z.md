# Choose Maryland: Compare Counties - Transportation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-transportation) |
| Metadata | [Link](https://data.maryland.gov/api/views/ief7-i74z) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ief7-i74z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ief7-i74z/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ief7-i74z |
| Name | Choose Maryland: Compare Counties - Transportation |
| Attribution | Maryland Department of Commerce |
| Category | Transportation |
| Tags | maryland, county, compare, transportation, commute, travel time, airport |
| Created | 2013-08-23T14:48:54Z |
| Publication Date | 2016-12-08T19:55:42Z |

## Description

Workforce travel habits - commute times and destinations.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                                                        | Data Type | Render Type |
| ======== | ============== | ================================ | =========================================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                                                  | meta_data | meta_data   |
| Yes      | series tag     | county                           | County                                                      | text      | text        |
| Yes      | numeric metric | distance_commercial_airport      | Distance to Nearest Primary Commercial Airport (mi.)        | number    | number      |
| Yes      | numeric metric | avg_work_commute                 | Average Travel Time to Work (Minutes)                       | number    | number      |
| Yes      | numeric metric | workers_commuting_into_cnty      | Workers Commuting Into the County                           | number    | number      |
| Yes      | numeric metric | workers_commuting_out_cnty       | Workers Commuting Out of the County                         | number    | number      |
| Yes      | numeric metric | workers_commuting_in_out_cnty    | Net Workers Commuting Into/Out of the County                | number    | number      |
| Yes      | numeric metric | residents_work_own_cnty          | Residents Who Work in Own County                            | number    | number      |
| Yes      | numeric metric | perc_residents_employed_own_cnty | Percentage of Employed Residents Who Work in Own County (%) | percent   | percent     |
| Yes      | numeric metric | perc_cnty_jobs_residents         | Percentage of County Jobs Held by Residents (%)             | percent   | percent     |
| Yes      | numeric metric | perc_cnty_jobs_non_residents     | Percentage of County Jobs Held by Non-Residents (%)         | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ief7-i74z d:2016-12-08T19:54:56.000Z t:county="Allegany County" m:distance_commercial_airport=139.3 m:perc_cnty_jobs_residents=75.1 m:avg_work_commute=20.7 m:perc_residents_employed_own_cnty=83.9 m:perc_cnty_jobs_non_residents=24.9 m:workers_commuting_out_cnty=4674 m:workers_commuting_into_cnty=8054 m:residents_work_own_cnty=24334 m:workers_commuting_in_out_cnty=3380

series e:ief7-i74z d:2016-12-08T19:54:56.000Z t:county="Anne Arundel County" m:distance_commercial_airport=23.2 m:perc_cnty_jobs_residents=59.4 m:avg_work_commute=29.7 m:perc_residents_employed_own_cnty=58.3 m:perc_cnty_jobs_non_residents=40.6 m:workers_commuting_out_cnty=121032 m:workers_commuting_into_cnty=115214 m:residents_work_own_cnty=168876 m:workers_commuting_in_out_cnty=-5818

series e:ief7-i74z d:2016-12-08T19:54:56.000Z t:county="Baltimore City" m:distance_commercial_airport=9.8 m:perc_cnty_jobs_residents=43.8 m:avg_work_commute=30.5 m:perc_residents_employed_own_cnty=61.4 m:perc_cnty_jobs_non_residents=56.2 m:workers_commuting_out_cnty=102543 m:workers_commuting_into_cnty=208950 m:residents_work_own_cnty=163042 m:workers_commuting_in_out_cnty=106407
```

## Meta Commands

```ls
metric m:distance_commercial_airport p:float l:"Distance to Nearest Primary Commercial Airport (mi.)" t:dataTypeName=number

metric m:avg_work_commute p:float l:"Average Travel Time to Work (Minutes)" t:dataTypeName=number

metric m:workers_commuting_into_cnty p:integer l:"Workers Commuting Into the County" t:dataTypeName=number

metric m:workers_commuting_out_cnty p:integer l:"Workers Commuting Out of the County" t:dataTypeName=number

metric m:workers_commuting_in_out_cnty p:integer l:"Net Workers Commuting Into/Out of the County" t:dataTypeName=number

metric m:residents_work_own_cnty p:integer l:"Residents Who Work in Own County" t:dataTypeName=number

metric m:perc_residents_employed_own_cnty p:float l:"Percentage of Employed Residents Who Work in Own County (%)" t:dataTypeName=percent

metric m:perc_cnty_jobs_residents p:float l:"Percentage of County Jobs Held by Residents (%)" t:dataTypeName=percent

metric m:perc_cnty_jobs_non_residents p:float l:"Percentage of County Jobs Held by Non-Residents (%)" t:dataTypeName=percent

entity e:ief7-i74z l:"Choose Maryland:  Compare Counties - Transportation" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/ief7-i74z

property e:ief7-i74z t:meta.view v:id=ief7-i74z v:category=Transportation v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Transportation" v:attribution="Maryland Department of Commerce"

property e:ief7-i74z t:meta.view.license v:name="Public Domain"

property e:ief7-i74z t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:ief7-i74z t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | distance_commercial_airport | avg_work_commute | workers_commuting_into_cnty | workers_commuting_out_cnty | workers_commuting_in_out_cnty | residents_work_own_cnty | perc_residents_employed_own_cnty | perc_cnty_jobs_residents | perc_cnty_jobs_non_residents | 
| =========== | =================== | =========================== | ================ | =========================== | ========================== | ============================= | ======================= | ================================ | ======================== | ============================ | 
| 1481226896  | Allegany County     | 139.3                       | 20.7             | 8054                        | 4674                       | 3380                          | 24334                   | 83.9                             | 75.1                     | 24.9                         | 
| 1481226896  | Anne Arundel County | 23.2                        | 29.7             | 115214                      | 121032                     | -5818                         | 168876                  | 58.3                             | 59.4                     | 40.6                         | 
| 1481226896  | Baltimore City      | 9.8                         | 30.5             | 208950                      | 102543                     | 106407                        | 163042                  | 61.4                             | 43.8                     | 56.2                         | 
| 1481226896  | Baltimore County    | 17.8                        | 29.1             | 148140                      | 201150                     | -53010                        | 203094                  | 50.2                             | 57.8                     | 42.2                         | 
| 1481226896  | Calvert County      | 55.7                        | 40.1             | 6514                        | 27776                      | -21262                        | 17276                   | 38.3                             | 72.6                     | 27.4                         | 
| 1481226896  | Caroline County     | 64.9                        | 32.9             | 2963                        | 9271                       | -6308                         | 5756                    | 38.3                             | 66.0                     | 34.0                         | 
| 1481226896  | Carroll County      | 36.9                        | 35.2             | 17455                       | 47185                      | -29730                        | 39419                   | 45.5                             | 69.3                     | 30.7                         | 
| 1481226896  | Cecil County        | 41.7                        | 28.8             | 10955                       | 25187                      | -14232                        | 22821                   | 47.5                             | 67.6                     | 32.4                         | 
| 1481226896  | Charles County      | 33.9                        | 42.8             | 13926                       | 47490                      | -33564                        | 28979                   | 37.9                             | 67.5                     | 32.5                         | 
| 1481226896  | Dorchester County   | 80.1                        | 24.8             | 3646                        | 5589                       | -1943                         | 9436                    | 62.8                             | 72.1                     | 27.9                         | 
```