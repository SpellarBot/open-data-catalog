# CCRB: Age of Alleged Victims Compared to New York City Demographics 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-alleged-victims-compared-to-new-york-city-demographics-2005-2009-5f38d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c4pu-cif5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c4pu-cif5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c4pu-cif5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c4pu-cif5 |
| Name | CCRB: Age of Alleged Victims Compared to New York City Demographics 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, victim, alleged victim, demographics 2005, 2006, 2007, 2008, 2009 |
| Created | 2011-09-12T17:44:10Z |
| Publication Date | 2011-09-12T17:44:10Z |

## Description

A statistical breakdown, by age and year, of alleged victims compared to New York City demographics 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | age                              | Age                              | text      | text        |
| Yes      | series tag     | 2005_number                      | 2005 Number                      | text      | number      |
| Yes      | numeric metric | 2005_percent_of_subtotal         | 2005 Percent of Subtotal         | percent   | percent     |
| Yes      | series tag     | 2006_number                      | 2006 Number                      | text      | number      |
| Yes      | numeric metric | 2006_percent_of_subtotal         | 2006 Percent of Subtotal         | percent   | percent     |
| Yes      | series tag     | 2007_number                      | 2007 Number                      | text      | number      |
| Yes      | numeric metric | 2007_percent_of_subtotal         | 2007 Percent of Subtotal         | percent   | percent     |
| Yes      | series tag     | 2008_number                      | 2008 Number                      | text      | number      |
| Yes      | numeric metric | 2008_percent_of_subtotal         | 2008 Percent of Subtotal         | percent   | percent     |
| Yes      | series tag     | 2009_number                      | 2009 Number                      | text      | number      |
| Yes      | numeric metric | 2009_percent_of_subtotal         | 2009 Percent of Subtotal         | percent   | percent     |
| Yes      | series tag     | 5_year_total_number              | 5-year Total Number              | text      | number      |
| Yes      | numeric metric | 5_year_total_percent_of_subtotal | 5-year Total Percent of Subtotal | percent   | percent     |
| Yes      | numeric metric | new_york_city_population         | New York City Population         | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c4pu-cif5 d:2005-01-01T00:00:00.000Z t:2007_number=277 t:2005_number=253 t:2008_number=217 t:age="14 and under" t:5_year_total_number=1259 t:2006_number=295 t:2009_number=217 m:2005_percent_of_subtotal=3.5 m:new_york_city_population=23.2 m:2006_percent_of_subtotal=3.5 m:5_year_total_percent_of_subtotal=3.2 m:2007_percent_of_subtotal=3.3 m:2008_percent_of_subtotal=2.9 m:2009_percent_of_subtotal=2.9

series e:c4pu-cif5 d:2005-01-01T00:00:00.000Z t:2007_number=2808 t:2005_number=2325 t:2008_number=2417 t:age=15-24 t:5_year_total_number=13022 t:2006_number=2943 t:2009_number=2529 m:2005_percent_of_subtotal=32.2 m:new_york_city_population=15.8 m:2006_percent_of_subtotal=35.2 m:5_year_total_percent_of_subtotal=33.4 m:2007_percent_of_subtotal=33.8 m:2008_percent_of_subtotal=32.3 m:2009_percent_of_subtotal=33.3

series e:c4pu-cif5 d:2005-01-01T00:00:00.000Z t:2007_number=2234 t:2005_number=1899 t:2008_number=2062 t:age=25-34 t:5_year_total_number=10494 t:2006_number=2125 t:2009_number=2174 m:2005_percent_of_subtotal=26.3 m:new_york_city_population=14.5 m:2006_percent_of_subtotal=25.4 m:5_year_total_percent_of_subtotal=26.9 m:2007_percent_of_subtotal=26.9 m:2008_percent_of_subtotal=27.6 m:2009_percent_of_subtotal=28.6
```

## Meta Commands

```ls
metric m:2005_percent_of_subtotal p:float l:"2005 Percent of Subtotal" t:dataTypeName=percent

metric m:2006_percent_of_subtotal p:float l:"2006 Percent of Subtotal" t:dataTypeName=percent

metric m:2007_percent_of_subtotal p:float l:"2007 Percent of Subtotal" t:dataTypeName=percent

metric m:2008_percent_of_subtotal p:float l:"2008 Percent of Subtotal" t:dataTypeName=percent

metric m:2009_percent_of_subtotal p:float l:"2009 Percent of Subtotal" t:dataTypeName=percent

metric m:5_year_total_percent_of_subtotal p:float l:"5-year Total Percent of Subtotal" t:dataTypeName=percent

metric m:new_york_city_population p:float l:"New York City Population" t:dataTypeName=percent

entity e:c4pu-cif5 l:"CCRB: Age of Alleged Victims Compared to New York City Demographics 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/c4pu-cif5

property e:c4pu-cif5 t:meta.view v:id=c4pu-cif5 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Alleged Victims Compared to New York City Demographics 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:c4pu-cif5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c4pu-cif5 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age          | 2005_number | 2005_percent_of_subtotal | 2006_number | 2006_percent_of_subtotal | 2007_number | 2007_percent_of_subtotal | 2008_number | 2008_percent_of_subtotal | 2009_number | 2009_percent_of_subtotal | 5_year_total_number | 5_year_total_percent_of_subtotal | new_york_city_population | 
| ============ | =========== | ======================== | =========== | ======================== | =========== | ======================== | =========== | ======================== | =========== | ======================== | =================== | ================================ | ======================== | 
| 14 and under | 253         | 3.50                     | 295         | 3.50                     | 277         | 3.30                     | 217         | 2.90                     | 217         | 2.90                     | 1259                | 3.20                             | 23.20                    | 
| 15-24        | 2325        | 32.20                    | 2943        | 35.20                    | 2808        | 33.80                    | 2417        | 32.30                    | 2529        | 33.30                    | 13022               | 33.40                            | 15.80                    | 
| 25-34        | 1899        | 26.30                    | 2125        | 25.40                    | 2234        | 26.90                    | 2062        | 27.60                    | 2174        | 28.60                    | 10494               | 26.90                            | 14.50                    | 
| 35-44        | 1504        | 20.90                    | 1612        | 19.30                    | 1595        | 19.20                    | 1429        | 19.10                    | 1355        | 17.80                    | 7495                | 19.20                            | 14.50                    | 
| 45-54        | 835         | 11.60                    | 959         | 11.50                    | 931         | 11.20                    | 947         | 12.70                    | 942         | 12.40                    | 4614                | 11.80                            | 12.60                    | 
| 55-64        | 287         | 4.00                     | 292         | 3.50                     | 341         | 4.10                     | 291         | 3.90                     | 279         | 3.70                     | 1490                | 3.80                             | 8.90                     | 
| 65 and over  | 110         | 1.50                     | 134         | 1.60                     | 134         | 1.60                     | 113         | 1.50                     | 97          | 1.30                     | 588                 | 1.50                             | 10.50                    | 
| Subtotal     | 7213        | 100.00                   | 8360        | 100.00                   | 8320        | 100.00                   | 7476        | 100.00                   | 7593        | 100.00                   | 38962               | 100.00                           | 100.00                   | 
| Unknown      | 2832        |                          | 3606        |                          | 3946        |                          | 3868        |                          | 4230        |                          | 18482               |                                  |                          | 
| Total        | 10045       |                          | 11966       |                          | 12266       |                          | 11344       |                          | 11823       |                          | 57444               |                                  |                          | 
```