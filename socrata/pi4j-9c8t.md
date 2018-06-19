# Substantiated Officers Rank

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/substantiated-officers-rank-9822d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pi4j-9c8t) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pi4j-9c8t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pi4j-9c8t/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pi4j-9c8t |
| Name | Substantiated Officers Rank |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, allegations, substantiated, populations, rank |
| Created | 2013-02-25T21:47:23Z |
| Publication Date | 2013-06-21T20:04:29Z |

## Description

This chat displays the rank of Police Officers against whom Allegations were Substantiated

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | time           | year                           | Year                           | number    | text        |
| Yes      | numeric metric | police_officer                 | Police Officer                 | number    | text        |
| Yes      | numeric metric | detective_1                    | Detective 1                    | number    | text        |
| Yes      | numeric metric | detective_2                    | Detective 2                    | number    | text        |
| Yes      | numeric metric | detective_3                    | Detective 3                    | number    | text        |
| Yes      | numeric metric | detective_specialist           | Detective specialist           | number    | text        |
| Yes      | numeric metric | sergeant                       | Sergeant                       | number    | text        |
| Yes      | numeric metric | lieutenant                     | Lieutenant                     | number    | text        |
| Yes      | numeric metric | lieutenant_commander_detective | Lieutenant commander detective | number    | text        |
| Yes      | numeric metric | captain                        | Captain                        | number    | text        |
| Yes      | numeric metric | deputy_inspector_inspector     | Deputy Inspector/Inspector     | number    | text        |
| Yes      | numeric metric | other_ranks                    | Other ranks                    | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pi4j-9c8t d:2009-01-01T00:00:00.000Z m:detective_specialist=1 m:other_ranks=0 m:detective_2=3 m:detective_3=0 m:deputy_inspector_inspector=0 m:detective_1=11 m:lieutenant=11 m:lieutenant_commander_detective=0 m:police_officer=200 m:sergeant=50 m:captain=0

series e:pi4j-9c8t d:2010-01-01T00:00:00.000Z m:detective_specialist=2 m:other_ranks=0 m:detective_2=3 m:detective_3=0 m:deputy_inspector_inspector=1 m:detective_1=30 m:lieutenant=11 m:lieutenant_commander_detective=2 m:police_officer=263 m:sergeant=59 m:captain=4

series e:pi4j-9c8t d:2011-01-01T00:00:00.000Z m:detective_specialist=0 m:other_ranks=0 m:detective_2=2 m:detective_3=0 m:deputy_inspector_inspector=0 m:detective_1=20 m:lieutenant=9 m:lieutenant_commander_detective=1 m:police_officer=138 m:sergeant=42 m:captain=1
```

## Meta Commands

```ls
metric m:police_officer p:integer l:"Police Officer" t:dataTypeName=number

metric m:detective_1 p:integer l:"Detective 1" t:dataTypeName=number

metric m:detective_2 p:integer l:"Detective 2" t:dataTypeName=number

metric m:detective_3 p:integer l:"Detective 3" t:dataTypeName=number

metric m:detective_specialist p:integer l:"Detective specialist" t:dataTypeName=number

metric m:sergeant p:integer l:Sergeant t:dataTypeName=number

metric m:lieutenant p:integer l:Lieutenant t:dataTypeName=number

metric m:lieutenant_commander_detective p:integer l:"Lieutenant commander detective" t:dataTypeName=number

metric m:captain p:integer l:Captain t:dataTypeName=number

metric m:deputy_inspector_inspector p:integer l:"Deputy Inspector/Inspector" t:dataTypeName=number

metric m:other_ranks p:integer l:"Other ranks" t:dataTypeName=number

entity e:pi4j-9c8t l:"Substantiated Officers Rank" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/pi4j-9c8t

property e:pi4j-9c8t t:meta.view v:id=pi4j-9c8t v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Substantiated Officers Rank" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:pi4j-9c8t t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pi4j-9c8t t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | police_officer | detective_1 | detective_2 | detective_3 | detective_specialist | sergeant | lieutenant | lieutenant_commander_detective | captain | deputy_inspector_inspector | other_ranks | 
| ==== | ============== | =========== | =========== | =========== | ==================== | ======== | ========== | ============================== | ======= | ========================== | =========== | 
| 2009 | 200            | 11          | 3           | 0           | 1                    | 50       | 11         | 0                              | 0       | 0                          | 0           | 
| 2010 | 263            | 30          | 3           | 0           | 2                    | 59       | 11         | 2                              | 4       | 1                          | 0           | 
| 2011 | 138            | 20          | 2           | 0           | 0                    | 42       | 9          | 1                              | 1       | 0                          | 0           | 
```