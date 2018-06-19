# Distribution Of Force Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/distribution-of-force-allegations-2005-2009-482dd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ccab-jb4k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ccab-jb4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ccab-jb4k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ccab-jb4k |
| Name | Distribution Of Force Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T00:21:10Z |
| Publication Date | 2011-09-29T00:22:35Z |

## Description

CCRB: Distribution of Force Allegations 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | type_of_force_allegation | Type of Force Allegation | text      | text        |
| Yes      | series tag     | number_1                 | 2005 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_1       | 2005 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_2                 | 2006 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_2       | 2006 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_3                 | 2007 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_3       | 2007 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_4                 | 2008 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_4       | 2008 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_5                 | 2009 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_5       | 2009 Percent of Total    | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ccab-jb4k d:2005-01-01T00:00:00.000Z t:type_of_force_allegation="Gun fired" t:number_1=18 t:number_3=13 t:number_2=37 t:number_5=24 t:number_4=17 m:percent_of_total_3=0.2 m:percent_of_total_4=0.3 m:percent_of_total_1=0.3 m:percent_of_total_2=0.5 m:percent_of_total_5=0.3

series e:ccab-jb4k d:2005-01-01T00:00:00.000Z t:type_of_force_allegation="Gun pointed" t:number_1=344 t:number_3=485 t:number_2=470 t:number_5=381 t:number_4=372 m:percent_of_total_3=6.6 m:percent_of_total_4=5.5 m:percent_of_total_1=5.7 m:percent_of_total_2=6.4 m:percent_of_total_5=5.1

series e:ccab-jb4k d:2005-01-01T00:00:00.000Z t:type_of_force_allegation="Nightstick as club" t:number_1=255 t:number_3=385 t:number_2=377 t:number_5=401 t:number_4=352 m:percent_of_total_3=5.2 m:percent_of_total_4=5.2 m:percent_of_total_1=4.2 m:percent_of_total_2=5.1 m:percent_of_total_5=5.4
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

entity e:ccab-jb4k l:"Distribution Of Force Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ccab-jb4k

property e:ccab-jb4k t:meta.view v:id=ccab-jb4k v:category="Public Safety" v:averageRating=0 v:name="Distribution Of Force Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ccab-jb4k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ccab-jb4k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_force_allegation       | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ============================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| Gun fired                      | 18       | 0.30               | 37       | 0.50               | 13       | 0.20               | 17       | 0.30               | 24       | 0.30               | 
| Gun pointed                    | 344      | 5.70               | 470      | 6.40               | 485      | 6.60               | 372      | 5.50               | 381      | 5.10               | 
| Nightstick as club             | 255      | 4.20               | 377      | 5.10               | 385      | 5.20               | 352      | 5.20               | 401      | 5.40               | 
| Gun as club                    | 40       | 0.70               | 34       | 0.50               | 38       | 0.50               | 38       | 0.60               | 44       | 0.60               | 
| Police shield                  | 6        | 0.10               | 10       | 0.10               | 13       | 0.20               | 7        | 0.10               | 15       | 0.20               | 
| Vehicle                        | 29       | 0.50               | 26       | 0.40               | 38       | 0.50               | 26       | 0.40               | 29       | 0.40               | 
| Other blunt instrument as club | 61       | 1.00               | 72       | 1.00               | 69       | 0.90               | 56       | 0.80               | 63       | 0.80               | 
| Hit against inanimate object   | 158      | 2.60               | 228      | 3.10               | 191      | 2.60               | 178      | 2.60               | 275      | 3.70               | 
| Chokehold                      | 160      | 2.60               | 213      | 2.90               | 224      | 3.00               | 240      | 3.50               | 298      | 4.00               | 
| Pepper spray                   | 371      | 6.10               | 380      | 5.10               | 363      | 4.90               | 301      | 4.50               | 388      | 5.20               | 
```