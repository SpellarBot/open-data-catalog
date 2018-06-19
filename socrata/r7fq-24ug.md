# IEMA Federal Disaster Declarations by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-federal-disaster-declarations-by-county-a8bb6) |
| Metadata | [Link](https://data.illinois.gov/api/views/r7fq-24ug) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/r7fq-24ug/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/r7fq-24ug/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | r7fq-24ug |
| Name | IEMA Federal Disaster Declarations by County |
| Category | Reference |
| Tags | disaster, declaration, federal, fema, county |
| Created | 2011-10-03T20:21:11Z |
| Publication Date | 2011-10-21T21:02:28Z |

## Description

A list of Federally Declared Disaster by Illinois County since 1965.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | county           | County           | text      | text        |
| Yes      | numeric metric | fema_            | FEMA#            | number    | number      |
| Yes      | time           | declaration_date | Declaration Date | date      | date        |
| Yes      | series tag     | type_of_disaster | Type of Disaster | text      | text        |
```

## Time Field

```ls
Value = declaration_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:r7fq-24ug d:1965-04-25T08:00:00.000Z t:county=Adams t:type_of_disaster="Flooding, Severe Storms, Tornado" m:fema_=194

series e:r7fq-24ug d:1969-06-06T07:00:00.000Z t:county=Adams t:type_of_disaster=Flooding m:fema_=262

series e:r7fq-24ug d:1973-04-26T08:00:00.000Z t:county=Adams t:type_of_disaster="Flooding, Severe Storms" m:fema_=373
```

## Meta Commands

```ls
metric m:fema_ p:integer l:FEMA# t:dataTypeName=number

entity e:r7fq-24ug l:"IEMA Federal Disaster Declarations by County" t:url=https://data.illinois.gov/api/views/r7fq-24ug

property e:r7fq-24ug t:meta.view v:id=r7fq-24ug v:category=Reference v:averageRating=0 v:name="IEMA Federal Disaster Declarations by County"

property e:r7fq-24ug t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:r7fq-24ug t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| county | fema_ | declaration_date | type_of_disaster                                                 | 
| ====== | ===== | ================ | ================================================================ | 
| Adams  | 194   | -147888000       | Flooding, Severe Storms, Tornado                                 | 
| Adams  | 262   | -18032400        | Flooding                                                         | 
| Adams  | 373   | 104659200        | Flooding, Severe Storms                                          | 
| Adams  | 438   | 140079600        | Flooding, Severe Storms                                          | 
| Adams  | 735   | 480931200        | Excessive Rainfall, Flooding, Ice Jam, Severe Storms             | 
| Adams  | 776   | 529052400        | Flash Floods, Torrential Rains                                   | 
| Adams  | 871   | 646038000        | Flooding, Severe Winds, Tornado, Thunderstorms, Torrential Rains | 
| Adams  | 997   | 742201200        | Great Midwest Flood                                              | 
| Adams  | 1112  | 831366000        | Severe Storms, Severe Winds, Torrential Rains                    | 
| Adams  | 3134  | 915782400        | Snow Emergency                                                   | 
```