# 2010 Population By Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-population-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/vnar-mt35) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/vnar-mt35/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/vnar-mt35/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | vnar-mt35 |
| Name | 2010 Population By Town |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | population, town, cities, census |
| Created | 2015-02-04T15:32:22Z |
| Publication Date | 2015-02-04T15:33:36Z |

## Description

Population by town in Connecticut based on the 2010 census

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | town_num        | Town Num        | text      | number      |
| Yes      | series tag     | town            | TOWN            | text      | text        |
| Yes      | numeric metric | 2010_population | 2010 Population | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vnar-mt35 d:2010-01-01T00:00:00.000Z t:town_num=1 t:town=Andover m:2010_population=3303

series e:vnar-mt35 d:2010-01-01T00:00:00.000Z t:town_num=2 t:town=Ansonia m:2010_population=19249

series e:vnar-mt35 d:2010-01-01T00:00:00.000Z t:town_num=3 t:town=Ashford m:2010_population=4317
```

## Meta Commands

```ls
metric m:2010_population p:integer l:"2010 Population" t:dataTypeName=number

entity e:vnar-mt35 l:"2010 Population By Town" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/vnar-mt35

property e:vnar-mt35 t:meta.view v:id=vnar-mt35 v:category=Government v:averageRating=0 v:name="2010 Population By Town" v:attribution="Office of Policy and Management"

property e:vnar-mt35 t:meta.view.license v:name="Public Domain"

property e:vnar-mt35 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:vnar-mt35 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_num | town         | 2010_population | 
| ======== | ============ | =============== | 
| 1        | Andover      | 3303            | 
| 2        | Ansonia      | 19249           | 
| 3        | Ashford      | 4317            | 
| 4        | Avon         | 18098           | 
| 5        | Barkhamsted  | 3799            | 
| 6        | Beacon Falls | 6049            | 
| 7        | Berlin       | 19866           | 
| 8        | Bethany      | 5563            | 
| 9        | Bethel       | 18584           | 
| 10       | Bethlehem    | 3607            | 
```