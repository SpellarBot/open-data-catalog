# Diesel Retail Price Weekly Average by Region: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/diesel-retail-price-weekly-average-by-region-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/dtfv-pchi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dtfv-pchi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dtfv-pchi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dtfv-pchi |
| Name | Diesel Retail Price Weekly Average by Region: Beginning 2007 |
| Attribution | New York State Energy Research and Development Authority Performance Management and Evaluation Services Group |
| Category | Energy & Environment |
| Tags | diesel, energy prices, transportation fuels |
| Created | 2014-08-27T21:23:11Z |
| Publication Date | 2017-04-07T22:01:55Z |

## Description

Diesel retail prices weekly average by region dataset provides the weekly average retail diesel prices for New York State and eight New York metropolitan regions in U.S. dollars per gallon.  Data is a weekly average from October 2007 through current. Average daily retail diesel prices are collected from the American Automobile Association (AAA) Daily Fuel Gauge Report. The AAA Daily Fuel Gauge Report prices are averaged to produce a weekly average retail price for New York State and each metropolitan region. The New York State metropolitan regions in the dataset are Albany (Albany-Schenectady-Troy), Binghamton, Buffalo (Buffalo-Niagara Falls), Nassau (Nassau-Suffolk), New York City, Rochester, Syracuse, and Utica (Utica-Rome).

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
series e:dtfv-pchi d:2017-03-27T00:00:00.000Z m:rochester_average_gal=2.59 m:nassau_average_gal=2.74 m:new_york_city_average_gal=2.92 m:albany_average_gal=2.63 m:new_york_state_average_gal=2.71 m:binghamton_average_gal=2.72 m:syracuse_average_gal=2.6 m:utica_average_gal=2.63 m:buffalo_average_gal=2.59

series e:dtfv-pchi d:2017-03-20T00:00:00.000Z m:rochester_average_gal=2.59 m:nassau_average_gal=2.75 m:new_york_city_average_gal=2.92 m:albany_average_gal=2.63 m:new_york_state_average_gal=2.72 m:binghamton_average_gal=2.73 m:syracuse_average_gal=2.61 m:utica_average_gal=2.63 m:buffalo_average_gal=2.59

series e:dtfv-pchi d:2017-03-13T00:00:00.000Z m:rochester_average_gal=2.59 m:nassau_average_gal=2.75 m:new_york_city_average_gal=2.91 m:albany_average_gal=2.64 m:new_york_state_average_gal=2.72 m:binghamton_average_gal=2.73 m:syracuse_average_gal=2.62 m:utica_average_gal=2.64 m:buffalo_average_gal=2.59
```

## Meta Commands

```ls
metric m:new_york_state_average_gal p:float l:"New York State Average ($/gal)" d:"Weekly average retail diesel price for New York State ($/gallon)." t:dataTypeName=number

metric m:albany_average_gal p:float l:"Albany Average ($/gal)" t:dataTypeName=number

metric m:binghamton_average_gal p:float l:"Binghamton Average ($/gal)" d:"Weekly average retail diesel price for Binghamton Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:buffalo_average_gal p:float l:"Buffalo Average ($/gal)" d:"Weekly average retail diesel price for Buffalo-Niagara Falls Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:nassau_average_gal p:float l:"Nassau Average ($/gal)" d:"Weekly average retail diesel price for Nassau-Suffolk Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:new_york_city_average_gal p:float l:"New York City Average ($/gal)" d:"Weekly average retail diesel price for New York City Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:rochester_average_gal p:float l:"Rochester Average ($/gal)" d:"Weekly average retail diesel price for Rochester Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:syracuse_average_gal p:float l:"Syracuse Average ($/gal)" d:"Weekly average retail diesel price for Syracuse Metropolitan Area ($/gallon)." t:dataTypeName=number

metric m:utica_average_gal p:float l:"Utica Average ($/gal)" d:"Weekly average retail diesel price for Utica-Rome Metropolitan Area ($/gallon)." t:dataTypeName=number

entity e:dtfv-pchi l:"Diesel Retail Price Weekly Average by Region: Beginning 2007" t:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group" t:url=https://data.ny.gov/api/views/dtfv-pchi

property e:dtfv-pchi t:meta.view v:id=dtfv-pchi v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/EA-Reports-and-Studies/Weekly-Transportation-Fuels-Report.aspx. v:averageRating=0 v:name="Diesel Retail Price Weekly Average by Region: Beginning 2007" v:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group"

property e:dtfv-pchi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dtfv-pchi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | new_york_state_average_gal | albany_average_gal | binghamton_average_gal | buffalo_average_gal | nassau_average_gal | new_york_city_average_gal | rochester_average_gal | syracuse_average_gal | utica_average_gal | 
| =================== | ========================== | ================== | ====================== | =================== | ================== | ========================= | ===================== | ==================== | ================= | 
| 2017-03-27T00:00:00 | 2.71                       | 2.63               | 2.72                   | 2.59                | 2.74               | 2.92                      | 2.59                  | 2.60                 | 2.63              | 
| 2017-03-20T00:00:00 | 2.72                       | 2.63               | 2.73                   | 2.59                | 2.75               | 2.92                      | 2.59                  | 2.61                 | 2.63              | 
| 2017-03-13T00:00:00 | 2.72                       | 2.64               | 2.73                   | 2.59                | 2.75               | 2.91                      | 2.59                  | 2.62                 | 2.64              | 
| 2017-03-06T00:00:00 | 2.73                       | 2.64               | 2.74                   | 2.60                | 2.76               | 2.91                      | 2.60                  | 2.62                 | 2.64              | 
| 2017-02-27T00:00:00 | 2.73                       | 2.64               | 2.74                   | 2.6                 | 2.76               | 2.92                      | 2.61                  | 2.62                 | 2.65              | 
| 2017-02-20T00:00:00 | 2.73                       | 2.64               | 2.75                   | 2.6                 | 2.76               | 2.93                      | 2.61                  | 2.62                 | 2.64              | 
| 2017-02-13T00:00:00 | 2.73                       | 2.65               | 2.74                   | 2.6                 | 2.76               | 2.93                      | 2.61                  | 2.62                 | 2.63              | 
| 2017-02-06T00:00:00 | 2.74                       | 2.65               | 2.75                   | 2.6                 | 2.77               | 2.93                      | 2.62                  | 2.62                 | 2.64              | 
| 2017-01-30T00:00:00 | 2.75                       | 2.67               | 2.77                   | 2.61                | 2.77               | 2.93                      | 2.64                  | 2.65                 | 2.66              | 
| 2017-01-23T00:00:00 | 2.75                       | 2.68               | 2.77                   | 2.61                | 2.78               | 2.93                      | 2.65                  | 2.67                 | 2.68              | 
```