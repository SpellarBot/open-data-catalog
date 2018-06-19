# CCRB: Age of Victims Whose Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-victims-whose-allegations-were-substantiated-2005-2009-bdc17) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xj6i-rnxp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xj6i-rnxp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xj6i-rnxp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xj6i-rnxp |
| Name | CCRB: Age of Victims Whose Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident, report, substantiation, substantiated, victim, ccrb |
| Created | 2011-09-12T19:03:45Z |
| Publication Date | 2011-09-12T19:03:45Z |

## Description

A statistical breakdown of Civilian Complaint Review Board (CCRB) substantiated cases, by year and age of victim, for the years 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                | Data Type | Render Type |
| ======== | ============== | ================================== | =================================== | ========= | =========== |
| Yes      | series tag     | age                                | Age                                 | text      | text        |
| Yes      | numeric metric | 2005_number_of_victims             | 2005 Number of Victims              | number    | number      |
| Yes      | numeric metric | 2005_percent_of_subtotal           | 2005 Percent of Subtotal            | percent   | percent     |
| Yes      | numeric metric | 2006_number_of_victims             | 2006 Number of Victims              | number    | number      |
| Yes      | numeric metric | 2006_percent_of_subtotal           | 2006 Percent of Subtotal            | percent   | percent     |
| Yes      | numeric metric | 2007_number_of_victims             | 2007 Number of Victims              | number    | number      |
| Yes      | numeric metric | 2007_percent_of_subtotal           | 2007 Percent of Subtotal            | percent   | percent     |
| Yes      | numeric metric | 2008_number_of_victims             | 2008 Number of Victims              | number    | number      |
| Yes      | numeric metric | 2008_percent_of_subtotal           | 2008 Percent of Subtotal            | percent   | percent     |
| Yes      | numeric metric | 2009_number_of_victims             | 2009 Number of Victims              | number    | number      |
| Yes      | numeric metric | 2009_percent_of_subtotal           | 2009 Percent of Subtotal            | percent   | percent     |
| Yes      | numeric metric | new_york_city_population           | New York City Population            | number    | text        |
| Yes      | numeric metric | number_of_victims_five_year_totals | Number of Victims, Five-year totals | number    | number      |
| Yes      | numeric metric | percent_of_five_year_subtotals     | Percent of Five-year Subtotals      | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xj6i-rnxp d:2005-01-01T00:00:00.000Z t:age="14 and under" m:2007_number_of_victims=12 m:2006_number_of_victims=8 m:2005_percent_of_subtotal=3.2 m:new_york_city_population=23.200000762939453 m:number_of_victims_five_year_totals=44 m:2006_percent_of_subtotal=2 m:2009_number_of_victims=3 m:percent_of_five_year_subtotals=2.5 m:2005_number_of_victims=13 m:2008_number_of_victims=8 m:2007_percent_of_subtotal=3.2 m:2008_percent_of_subtotal=2.8 m:2009_percent_of_subtotal=0.9

series e:xj6i-rnxp d:2005-01-01T00:00:00.000Z t:age="15 - 24" m:2007_number_of_victims=136 m:2006_number_of_victims=108 m:2005_percent_of_subtotal=31.3 m:new_york_city_population=15.800000190734863 m:number_of_victims_five_year_totals=551 m:2006_percent_of_subtotal=27.1 m:2009_number_of_victims=94 m:percent_of_five_year_subtotals=30.8 m:2005_number_of_victims=129 m:2008_number_of_victims=84 m:2007_percent_of_subtotal=36.7 m:2008_percent_of_subtotal=29.5 m:2009_percent_of_subtotal=29.4

series e:xj6i-rnxp d:2005-01-01T00:00:00.000Z t:age="25 - 34" m:2007_number_of_victims=84 m:2006_number_of_victims=119 m:2005_percent_of_subtotal=27.4 m:new_york_city_population=14.5 m:number_of_victims_five_year_totals=501 m:2006_percent_of_subtotal=29.8 m:2009_number_of_victims=95 m:percent_of_five_year_subtotals=28 m:2005_number_of_victims=113 m:2008_number_of_victims=90 m:2007_percent_of_subtotal=22.6 m:2008_percent_of_subtotal=31.6 m:2009_percent_of_subtotal=29.7
```

## Meta Commands

```ls
metric m:2005_number_of_victims p:integer l:"2005 Number of Victims" t:dataTypeName=number

metric m:2005_percent_of_subtotal p:float l:"2005 Percent of Subtotal" t:dataTypeName=percent

metric m:2006_number_of_victims p:integer l:"2006 Number of Victims" t:dataTypeName=number

metric m:2006_percent_of_subtotal p:float l:"2006 Percent of Subtotal" t:dataTypeName=percent

metric m:2007_number_of_victims p:integer l:"2007 Number of Victims" t:dataTypeName=number

metric m:2007_percent_of_subtotal p:float l:"2007 Percent of Subtotal" t:dataTypeName=percent

metric m:2008_number_of_victims p:integer l:"2008 Number of Victims" t:dataTypeName=number

metric m:2008_percent_of_subtotal p:float l:"2008 Percent of Subtotal" t:dataTypeName=percent

metric m:2009_number_of_victims p:integer l:"2009 Number of Victims" t:dataTypeName=number

metric m:2009_percent_of_subtotal p:float l:"2009 Percent of Subtotal" t:dataTypeName=percent

metric m:new_york_city_population p:long l:"New York City Population" t:dataTypeName=number

metric m:number_of_victims_five_year_totals p:integer l:"Number of Victims, Five-year totals" t:dataTypeName=number

metric m:percent_of_five_year_subtotals p:float l:"Percent of Five-year Subtotals" t:dataTypeName=percent

entity e:xj6i-rnxp l:"CCRB: Age of Victims Whose Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/xj6i-rnxp

property e:xj6i-rnxp t:meta.view v:id=xj6i-rnxp v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Victims Whose Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:xj6i-rnxp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xj6i-rnxp t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age          | 2005_number_of_victims | 2005_percent_of_subtotal | 2006_number_of_victims | 2006_percent_of_subtotal | 2007_number_of_victims | 2007_percent_of_subtotal | 2008_number_of_victims | 2008_percent_of_subtotal | 2009_number_of_victims | 2009_percent_of_subtotal | new_york_city_population | number_of_victims_five_year_totals | percent_of_five_year_subtotals | 
| ============ | ====================== | ======================== | ====================== | ======================== | ====================== | ======================== | ====================== | ======================== | ====================== | ======================== | ======================== | ================================== | ============================== | 
| 14 and under | 13                     | 3.20                     | 8                      | 2.00                     | 12                     | 3.20                     | 8                      | 2.80                     | 3                      | 0.90                     | 23.20%                   | 44                                 | 2.50                           | 
| 15 - 24      | 129                    | 31.30                    | 108                    | 27.10                    | 136                    | 36.70                    | 84                     | 29.50                    | 94                     | 29.40                    | 15.80%                   | 551                                | 30.80                          | 
| 25 - 34      | 113                    | 27.40                    | 119                    | 29.80                    | 84                     | 22.60                    | 90                     | 31.60                    | 95                     | 29.70                    | 14.50%                   | 501                                | 28.00                          | 
| 35 - 44      | 94                     | 22.80                    | 97                     | 24.30                    | 85                     | 22.90                    | 57                     | 20.00                    | 80                     | 25.00                    | 14.50%                   | 413                                | 23.10                          | 
| 45 - 54      | 41                     | 10.00                    | 45                     | 11.30                    | 38                     | 10.20                    | 35                     | 12.30                    | 36                     | 11.30                    | 12.60%                   | 195                                | 10.90                          | 
| 55 - 64      | 20                     | 4.90                     | 19                     | 4.80                     | 11                     | 3.00                     | 7                      | 2.50                     | 9                      | 2.80                     | 8.90%                    | 66                                 | 3.70                           | 
| 65 and over  | 2                      | 0.50                     | 3                      | 0.80                     | 5                      | 1.30                     | 4                      | 1.40                     | 3                      | 0.90                     | 10.50%                   | 17                                 | 1.00                           | 
| Subtotal     | 412                    | 100.00                   | 399                    | 100.00                   | 371                    | 100.00                   | 285                    | 100.00                   | 320                    | 100.00                   | 100.00%                  | 1787                               | 100.00                         | 
| Unknown      | 41                     |                          | 48                     |                          | 70                     |                          | 58                     |                          | 52                     |                          |                          | 269                                |                                | 
| Total        | 453                    |                          | 447                    |                          | 441                    |                          | 343                    |                          | 372                    |                          |                          | 2056                               |                                | 
```