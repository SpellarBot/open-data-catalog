# Department of Corrections Quarterly Average Facilty Population

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doc-quarterly-average-facilty-population-and-bed-capacity) |
| Metadata | [Link](https://data.ct.gov/api/views/f8ar-pgu4) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/f8ar-pgu4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/f8ar-pgu4/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | f8ar-pgu4 |
| Name | Department of Corrections Quarterly Average Facilty Population |
| Attribution | Department of Correction |
| Category | Public Safety |
| Tags | prison population, inmate population |
| Created | 2016-03-11T14:29:23Z |
| Publication Date | 2017-04-13T14:32:26Z |

## Description

CT Department of Correction quarterly average inmate population in State of Connecticut correctional facilities.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | time           | end_quarter_date                 | End Quarter Date                 | calendar_date | calendar_date |
| Yes      | series tag     | facility_name                    | Facility Name                    | text          | text          |
| Yes      | numeric metric | average_inmate_population        | Average Inmate Population        | number        | number        |
| Yes      | numeric metric | average_number_of_permanent_beds | Average Number of Permanent Beds | number        | number        |
| Yes      | numeric metric | inmate_population_density        | Inmate Population Density        | percent       | percent       |
```

## Time Field

```ls
Value = end_quarter_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:f8ar-pgu4 d:2009-09-30T00:00:00.000Z t:facility_name=Bergin m:average_inmate_population=1034 m:average_number_of_permanent_beds=962 m:inmate_population_density=107.48

series e:f8ar-pgu4 d:2009-09-30T00:00:00.000Z t:facility_name=Bridgeport m:average_inmate_population=941 m:average_number_of_permanent_beds=1040 m:inmate_population_density=90.48

series e:f8ar-pgu4 d:2009-09-30T00:00:00.000Z t:facility_name=Brooklyn m:average_inmate_population=455 m:average_number_of_permanent_beds=456 m:inmate_population_density=99.78
```

## Meta Commands

```ls
metric m:average_inmate_population p:integer l:"Average Inmate Population" t:dataTypeName=number

metric m:average_number_of_permanent_beds p:integer l:"Average Number of Permanent Beds" t:dataTypeName=number

metric m:inmate_population_density p:float l:"Inmate Population Density" t:dataTypeName=percent

entity e:f8ar-pgu4 l:"Department of Corrections Quarterly Average Facilty Population" t:attribution="Department of Correction" t:url=https://data.ct.gov/api/views/f8ar-pgu4

property e:f8ar-pgu4 t:meta.view v:id=f8ar-pgu4 v:category="Public Safety" v:attributionLink=http://www.ct.gov/doc v:averageRating=0 v:name="Department of Corrections Quarterly Average Facilty Population" v:attribution="Department of Correction"

property e:f8ar-pgu4 t:meta.view.license v:name="Public Domain"

property e:f8ar-pgu4 t:meta.view.owner v:id=qb87-kyg8 v:screenName="Peiti Lee" v:displayName="Peiti Lee"

property e:f8ar-pgu4 t:meta.view.tableauthor v:id=qb87-kyg8 v:screenName="Peiti Lee" v:displayName="Peiti Lee"
```

## Top Records

```ls
| end_quarter_date    | facility_name      | average_inmate_population | average_number_of_permanent_beds | inmate_population_density | 
| =================== | ================== | ========================= | ================================ | ========================= | 
| 2009-09-30T00:00:00 | Bergin             | 1034                      | 962                              | 107.48                    | 
| 2009-09-30T00:00:00 | Bridgeport         | 941                       | 1040                             | 90.48                     | 
| 2009-09-30T00:00:00 | Brooklyn           | 455                       | 456                              | 99.78                     | 
| 2009-09-30T00:00:00 | Cheshire           | 1343                      | 1456                             | 92.24                     | 
| 2009-09-30T00:00:00 | Corrigan-Radgowski | 1537                      | 1489                             | 103.22                    | 
| 2009-09-30T00:00:00 | CRCI               | 1459                      | 1549                             | 94.19                     | 
| 2009-09-30T00:00:00 | Enfield            | 719                       | 724                              | 99.31                     | 
| 2009-09-30T00:00:00 | Garner             | 605                       | 748                              | 80.88                     | 
| 2009-09-30T00:00:00 | Gates              | 884                       | 1139                             | 77.61                     | 
| 2009-09-30T00:00:00 | Hartford           | 1160                      | 984                              | 117.89                    | 
```