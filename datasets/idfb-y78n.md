# Recreational Boating Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreational-boating-permits-121b6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/idfb-y78n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/idfb-y78n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/idfb-y78n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | idfb-y78n |
| Name | Recreational Boating Permits |
| Attribution | Department of Environmental Protection (DEP) |
| Tags | recreational boating permits, dep, boating |
| Created | 2014-01-08T18:18:03Z |
| Publication Date | 2016-11-14T22:20:48Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | text        |
| Yes      | series tag     | company_name   | Basin          | text      | text        |
| Yes      | numeric metric | permits_issued | Permits Issued | number    | text        |
| Yes      | numeric metric | seasonal_tags  | Seasonal Tags  | number    | text        |
| Yes      | numeric metric | temporary_tags | Temporary Tags | number    | text        |
| Yes      | numeric metric | canoes         | Canoes         | number    | text        |
| Yes      | numeric metric | kayaks         | Kayaks         | number    | text        |
| Yes      | numeric metric | rowboats       | Rowboats       | number    | text        |
| Yes      | numeric metric | sailboats      | Sailboats      | number    | text        |
| Yes      | numeric metric | sculls         | Sculls         | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Cannonsville m:permits_issued=103 m:temporary_tags=45 m:seasonal_tags=58 m:sailboats=4 m:sculls=1 m:kayaks=53 m:rowboats=11 m:canoes=34

series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Neversink m:permits_issued=122 m:temporary_tags=59 m:seasonal_tags=63 m:sailboats=6 m:sculls=0 m:kayaks=91 m:rowboats=5 m:canoes=20

series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Pepacton m:permits_issued=457 m:temporary_tags=238 m:seasonal_tags=219 m:sailboats=10 m:sculls=1 m:kayaks=311 m:rowboats=15 m:canoes=120
```

## Meta Commands

```ls
metric m:permits_issued p:integer l:"Permits Issued" t:dataTypeName=number

metric m:seasonal_tags p:integer l:"Seasonal Tags" t:dataTypeName=number

metric m:temporary_tags p:integer l:"Temporary Tags" t:dataTypeName=number

metric m:canoes p:integer l:Canoes t:dataTypeName=number

metric m:kayaks p:integer l:Kayaks t:dataTypeName=number

metric m:rowboats p:integer l:Rowboats t:dataTypeName=number

metric m:sailboats p:integer l:Sailboats t:dataTypeName=number

metric m:sculls p:integer l:Sculls t:dataTypeName=number

entity e:idfb-y78n l:"Recreational Boating Permits" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/idfb-y78n

property e:idfb-y78n t:meta.view v:id=idfb-y78n v:averageRating=0 v:name="Recreational Boating Permits" v:attribution="Department of Environmental Protection (DEP)"

property e:idfb-y78n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:idfb-y78n t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | company_name | permits_issued | seasonal_tags | temporary_tags | canoes | kayaks | rowboats | sailboats | sculls | 
| ==== | ============ | ============== | ============= | ============== | ====== | ====== | ======== | ========= | ====== | 
| 2013 | Cannonsville | 103            | 58            | 45             | 34     | 53     | 11       | 4         | 1      | 
| 2013 | Neversink    | 122            | 63            | 59             | 20     | 91     | 5        | 6         | 0      | 
| 2013 | Pepacton     | 457            | 219           | 238            | 120    | 311    | 15       | 10        | 1      | 
| 2013 | Schoharie    | 62             | 42            | 20             | 14     | 40     | 1        | 4         | 3      | 
| 2013 | Totals       | 744            | 382           | 362            | 188    | 495    | 32       | 24        | 5      | 
| 2014 | Cannonsville | 92             | 41            | 51             | 32     | 44     | 14       | 2         | 0      | 
| 2014 | Neversink    | 104            | 57            | 47             | 23     | 70     | 8        | 3         | 0      | 
| 2014 | Pepacton     | 535            | 219           | 316            | 155    | 356    | 17       | 7         | 0      | 
| 2014 | Schoharie    | 62             | 40            | 22             | 10     | 48     | 3        | 1         | 0      | 
| 2014 | Totals       | 793            | 357           | 436            | 220    | 518    | 42       | 13        | 0      | 
```