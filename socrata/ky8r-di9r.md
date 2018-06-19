# 2014 Traffic Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-traffic-log) |
| Metadata | [Link](https://data.ct.gov/api/views/ky8r-di9r) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ky8r-di9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ky8r-di9r/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ky8r-di9r |
| Name | 2014 Traffic Log |
| Attribution | Traffic Count Section of the Bureau of Policy and Planning, CT Department of Transportation |
| Category | Transportation |
| Tags | 2014 traffic log |
| Created | 2015-10-13T13:36:54Z |
| Publication Date | 2015-10-13T14:06:08Z |

## Description

2014 Traffic Log

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | town       | Town       | number    | number      |
| Yes      | series tag     | route      | Route      | text      | number      |
| Yes      | series tag     | from       | From       | text      | text        |
| Yes      | numeric metric | beg_mile   | Beg Mile   | number    | number      |
| No       |                | to         | To         | text      | text        |
| Yes      | numeric metric | end_mile   | End Mile   | number    | number      |
| Yes      | numeric metric | fun_class  | Fun Class  | number    | number      |
| Yes      | numeric metric | length     | Length     | number    | number      |
| Yes      | numeric metric | dvmt       | DVMT       | number    | number      |
| Yes      | numeric metric | adt        | ADT        | number    | number      |
| Yes      | numeric metric | year       | Year       | number    | number      |
| Yes      | series tag     | route_id   | Route ID   | text      | number      |
| Yes      | time           | cycle_year | Cycle Year | number    | number      |
```

## Time Field

```ls
Value = cycle_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = to
```

## Data Commands

```ls
series e:ky8r-di9r d:2014-01-01T00:00:00.000Z t:route=1 t:route_id=1 t:from="NEW YORK SL" m:dvmt=834 m:fun_class=3 m:length=0.03 m:year=2014 m:town=56 m:beg_mile=0 m:adt=27800 m:end_mile=0.03

series e:ky8r-di9r d:2014-01-01T00:00:00.000Z t:route=1 t:route_id=1 t:from="NB-BYRAM RD(NB)" m:dvmt=1296 m:fun_class=3 m:length=0.06 m:year=2014 m:town=56 m:beg_mile=0.03 m:adt=21600 m:end_mile=0.09

series e:ky8r-di9r d:2014-01-01T00:00:00.000Z t:route=1 t:route_id=1 t:from="SB-PEMBERWICK RD" m:dvmt=2124 m:fun_class=3 m:length=0.12 m:year=2014 m:town=56 m:beg_mile=0.09 m:adt=17700 m:end_mile=0.21
```

## Meta Commands

```ls
metric m:town p:integer l:Town t:dataTypeName=number

metric m:beg_mile p:float l:"Beg Mile" t:dataTypeName=number

metric m:end_mile p:float l:"End Mile" t:dataTypeName=number

metric m:fun_class p:integer l:"Fun Class" t:dataTypeName=number

metric m:length p:float l:Length t:dataTypeName=number

metric m:dvmt p:integer l:DVMT t:dataTypeName=number

metric m:adt p:integer l:ADT t:dataTypeName=number

metric m:year p:integer l:Year t:dataTypeName=number

entity e:ky8r-di9r l:"2014 Traffic Log" t:attribution="Traffic Count Section of the Bureau of Policy and Planning, CT Department of Transportation" t:url=https://data.ct.gov/api/views/ky8r-di9r

property e:ky8r-di9r t:meta.view v:id=ky8r-di9r v:category=Transportation v:averageRating=0 v:name="2014 Traffic Log" v:attribution="Traffic Count Section of the Bureau of Policy and Planning, CT Department of Transportation"

property e:ky8r-di9r t:meta.view.owner v:id=krit-g9ue v:screenName="James Spencer" v:displayName="James Spencer"

property e:ky8r-di9r t:meta.view.tableauthor v:id=krit-g9ue v:screenName="James Spencer" v:roleName=editor v:displayName="James Spencer"
```

## Top Records

```ls
| town | route | from             | beg_mile | to               | end_mile | fun_class | length | dvmt  | adt   | year | route_id | cycle_year | 
| ==== | ===== | ================ | ======== | ================ | ======== | ========= | ====== | ===== | ===== | ==== | ======== | ========== | 
| 56   | 1     | NEW YORK SL      | 0.00     | NB-BYRAM RD(NB)  | 0.03     | 3         | 0.03   | 834   | 27800 | 2014 | 1        | 2014       | 
| 56   | 1     | NB-BYRAM RD(NB)  | 0.03     | SB-PEMBERWICK RD | 0.09     | 3         | 0.06   | 1296  | 21600 | 2014 | 1        | 2014       | 
| 56   | 1     | SB-PEMBERWICK RD | 0.09     | BYRAM TERRACE DR | 0.21     | 3         | 0.12   | 2124  | 17700 | 2014 | 1        | 2014       | 
| 56   | 1     | BYRAM TERRACE DR | 0.21     | PROSPECT ST #2   | 1.43     | 3         | 1.22   | 25376 | 20800 | 2014 | 1        | 2014       | 
| 56   | 1     | PROSPECT ST #2   | 1.43     | BROOKSIDE DR     | 1.59     | 3         | 0.16   | 3104  | 19400 | 2014 | 1        | 2014       | 
| 56   | 1     | BROOKSIDE DR     | 1.59     | FIELD POINT RD   | 1.75     | 3         | 0.16   | 3280  | 20500 | 2014 | 1        | 2014       | 
| 56   | 1     | FIELD POINT RD   | 1.75     | MAPLE AVE #2     | 2.34     | 3         | 0.59   | 10266 | 17400 | 2014 | 1        | 2014       | 
| 56   | 1     | MAPLE AVE #2     | 2.34     | OLD CHURCH RD    | 2.66     | 3         | 0.32   | 6464  | 20200 | 2014 | 1        | 2014       | 
| 56   | 1     | OLD CHURCH RD    | 2.66     | BROOKRIDGE DR    | 3.14     | 3         | 0.48   | 10320 | 21500 | 2014 | 1        | 2014       | 
| 56   | 1     | BROOKRIDGE DR    | 3.14     | INDIAN FIELD RD  | 3.21     | 3         | 0.07   | 1841  | 26300 | 2014 | 1        | 2014       | 
```