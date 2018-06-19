# Gasoline Retail Prices Weekly Average by Region: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gasoline-retail-prices-weekly-average-by-region-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/nqur-w4p7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nqur-w4p7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nqur-w4p7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nqur-w4p7 |
| Name | Gasoline Retail Prices Weekly Average by Region: Beginning 2007 |
| Attribution | New York State Energy Research and Development Authority Performance Management and Evaluation Services Group |
| Category | Energy & Environment |
| Tags | gasoline, energy prices, transportation fuels |
| Created | 2014-08-27T21:38:13Z |
| Publication Date | 2017-04-07T22:01:12Z |

## Description

Gasoline retail prices weekly average by region dataset provides the weekly average retail gasoline prices for New York State and eight New York metropolitan regions in U.S. dollars per gallon.  Data is a weekly average from October 2007 through current.

Average daily retail gasoline prices are collected from the American Automobile Association (AAA) Daily Fuel Gauge Report.  The AAA Daily Fuel Gauge Report prices are averaged to produce a weekly average retail price for New York State and each metropolitan region.

The New York State metropolitan regions in the dataset are Albany (Albany-Schenectady-Troy), Binghamton, Buffalo (Buffalo-Niagara Falls), Nassau (Nassau-Suffolk), New York City, Rochester, Syracuse, and Utica (Utica-Rome).

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                           | Data Type     | Render Type   |
| ======== | ============== | ========================== | ============================== | ============= | ============= |
| Yes      | time           | date                       | Date                           | calendar_date | calendar_date |
| Yes      | numeric metric | new_york_state_average_gal | New York State Average ($/gal) | number        | number        |
| Yes      | numeric metric | albany_average_gal         | Albany Average ($/gal)         | number        | number        |
| Yes      | numeric metric | binghamton_average_gal     | Binghamton Average ($/gal)     | number        | number        |
| Yes      | numeric metric | buffalo_average_gal        | Buffalo Average ($/gal)        | number        | number        |
| Yes      | numeric metric | nassau_average_gal         | Nassau Average ($/gal)         | number        | number        |
| Yes      | numeric metric | new_york_city_average_gal  | New York City Average ($/gal)  | number        | number        |
| Yes      | numeric metric | rochester_average_gal      | Rochester Average ($/gal)      | number        | number        |
| Yes      | numeric metric | syracuse_average_gal       | Syracuse Average ($/gal)       | number        | number        |
| Yes      | numeric metric | utica_average_gal          | Utica Average ($/gal)          | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nqur-w4p7 d:2017-03-27T00:00:00.000Z m:rochester_average_gal=2.34 m:nassau_average_gal=2.42 m:new_york_city_average_gal=2.58 m:albany_average_gal=2.31 m:new_york_state_average_gal=2.42 m:binghamton_average_gal=2.37 m:syracuse_average_gal=2.29 m:utica_average_gal=2.36 m:buffalo_average_gal=2.4

series e:nqur-w4p7 d:2017-03-20T00:00:00.000Z m:rochester_average_gal=2.35 m:nassau_average_gal=2.44 m:new_york_city_average_gal=2.59 m:albany_average_gal=2.31 m:new_york_state_average_gal=2.43 m:binghamton_average_gal=2.37 m:syracuse_average_gal=2.3 m:utica_average_gal=2.37 m:buffalo_average_gal=2.41

series e:nqur-w4p7 d:2017-03-13T00:00:00.000Z m:rochester_average_gal=2.35 m:nassau_average_gal=2.45 m:new_york_city_average_gal=2.59 m:albany_average_gal=2.31 m:new_york_state_average_gal=2.44 m:binghamton_average_gal=2.38 m:syracuse_average_gal=2.31 m:utica_average_gal=2.38 m:buffalo_average_gal=2.41
```

## Meta Commands

```ls
metric m:new_york_state_average_gal p:float l:"New York State Average ($/gal)" d:"Weekly average regular grade gasoline price for New York State ($/gallon)." t:dataTypeName=number

metric m:albany_average_gal p:float l:"Albany Average ($/gal)" d:"Weekly average regular grade gasoline price for Albany-Schenectady-Troy Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:binghamton_average_gal p:float l:"Binghamton Average ($/gal)" d:"Weekly average regular grade gasoline price for Binghamton Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:buffalo_average_gal p:float l:"Buffalo Average ($/gal)" d:"Weekly average regular grade gasoline price for Buffalo-Niagara Falls Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:nassau_average_gal p:float l:"Nassau Average ($/gal)" d:"Weekly average regular grade gasoline price for Nassau-Suffolk Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:new_york_city_average_gal p:float l:"New York City Average ($/gal)" d:"Weekly average regular grade gasoline price for New York City Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:rochester_average_gal p:float l:"Rochester Average ($/gal)" d:"Weekly average regular grade gasoline price for Rochester Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:syracuse_average_gal p:float l:"Syracuse Average ($/gal)" d:"Weekly average regular grade gasoline price for Syracuse Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:utica_average_gal p:float l:"Utica Average ($/gal)" d:"Weekly average regular grade gasoline price for Utica-Rome Metropolitan Area ($/gallon)." t:dataTypeName=number

entity e:nqur-w4p7 l:"Gasoline Retail Prices Weekly Average by Region: Beginning 2007" t:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group" t:url=https://data.ny.gov/api/views/nqur-w4p7

property e:nqur-w4p7 t:meta.view v:id=nqur-w4p7 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/EA-Reports-and-Studies/Weekly-Transportation-Fuels-Report.aspx v:averageRating=0 v:name="Gasoline Retail Prices Weekly Average by Region: Beginning 2007" v:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group"

property e:nqur-w4p7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nqur-w4p7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | new_york_state_average_gal | albany_average_gal | binghamton_average_gal | buffalo_average_gal | nassau_average_gal | new_york_city_average_gal | rochester_average_gal | syracuse_average_gal | utica_average_gal | 
| =================== | ========================== | ================== | ====================== | =================== | ================== | ========================= | ===================== | ==================== | ================= | 
| 2017-03-27T00:00:00 | 2.42                       | 2.31               | 2.37                   | 2.40                | 2.42               | 2.58                      | 2.34                  | 2.29                 | 2.36              | 
| 2017-03-20T00:00:00 | 2.43                       | 2.31               | 2.37                   | 2.41                | 2.44               | 2.59                      | 2.35                  | 2.30                 | 2.37              | 
| 2017-03-13T00:00:00 | 2.44                       | 2.31               | 2.38                   | 2.41                | 2.45               | 2.59                      | 2.35                  | 2.31                 | 2.38              | 
| 2017-03-06T00:00:00 | 2.45                       | 2.32               | 2.39                   | 2.42                | 2.47               | 2.61                      | 2.36                  | 2.33                 | 2.39              | 
| 2017-02-27T00:00:00 | 2.47                       | 2.34               | 2.4                    | 2.43                | 2.49               | 2.62                      | 2.37                  | 2.34                 | 2.41              | 
| 2017-02-20T00:00:00 | 2.48                       | 2.36               | 2.41                   | 2.44                | 2.51               | 2.63                      | 2.39                  | 2.35                 | 2.41              | 
| 2017-02-13T00:00:00 | 2.48                       | 2.36               | 2.41                   | 2.44                | 2.51               | 2.64                      | 2.4                   | 2.33                 | 2.41              | 
| 2017-02-06T00:00:00 | 2.5                        | 2.38               | 2.43                   | 2.46                | 2.52               | 2.65                      | 2.42                  | 2.36                 | 2.42              | 
| 2017-01-30T00:00:00 | 2.51                       | 2.4                | 2.46                   | 2.46                | 2.54               | 2.66                      | 2.45                  | 2.38                 | 2.45              | 
| 2017-01-23T00:00:00 | 2.53                       | 2.43               | 2.48                   | 2.47                | 2.56               | 2.66                      | 2.47                  | 2.42                 | 2.46              | 
```