# CCRB: Attribution of Complaints to Patrol Borough Staten Island 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-staten-island-2005-2009-3d3e3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d8cz-kh5x) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d8cz-kh5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d8cz-kh5x/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d8cz-kh5x |
| Name | CCRB: Attribution of Complaints to Patrol Borough Staten Island 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T19:45:59Z |
| Publication Date | 2011-09-14T19:45:59Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | staten_island | Staten Island | text      | text        |
| Yes      | numeric metric | 2005          | 2005          | number    | number      |
| Yes      | numeric metric | 2006          | 2006          | number    | number      |
| Yes      | numeric metric | 2007          | 2007          | number    | number      |
| Yes      | numeric metric | 2008          | 2008          | number    | number      |
| Yes      | numeric metric | 2009          | 2009          | number    | number      |
| Yes      | numeric metric | total         | Total         | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d8cz-kh5x d:2005-01-01T00:00:00.000Z t:staten_island="120th Precinct" m:2008=50 m:total=296 m:2009=61 m:2006=68 m:2007=74 m:2005=43

series e:d8cz-kh5x d:2005-01-01T00:00:00.000Z t:staten_island="122nd Precinct" m:2008=25 m:total=144 m:2009=26 m:2006=37 m:2007=27 m:2005=29

series e:d8cz-kh5x d:2005-01-01T00:00:00.000Z t:staten_island="123rd Precinct" m:2008=10 m:total=60 m:2009=11 m:2006=17 m:2007=11 m:2005=11
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:d8cz-kh5x l:"CCRB: Attribution of Complaints to Patrol Borough Staten Island 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/d8cz-kh5x

property e:d8cz-kh5x t:meta.view v:id=d8cz-kh5x v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Staten Island 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:d8cz-kh5x t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d8cz-kh5x t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| staten_island                      | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 120th Precinct                     | 43   | 68   | 74   | 50   | 61   | 296   | 
| 122nd Precinct                     | 29   | 37   | 27   | 25   | 26   | 144   | 
| 123rd Precinct                     | 11   | 17   | 11   | 10   | 11   | 60    | 
| Precincts Total                    | 83   | 122  | 112  | 85   | 98   | 500   | 
| Task Force                         | 9    | 6    | 3    | 1    | 5    | 24    | 
| Borough HQ                         | 1    | 0    | 0    | 1    | 4    | 6     | 
| Anti-Crime Unit                    | 2    | 6    | 1    | 2    | 1    | 12    | 
| Housing                            | 5    | 2    | 0    | 0    | 0    | 7     | 
| Court                              | 0    | 0    | 2    | 1    | 2    | 5     | 
| Patrol Borough Staten Island Total | 100  | 136  | 118  | 90   | 110  | 554   | 
```