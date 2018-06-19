# Illinois Population, 1991-1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-population-1991-1999-30290) |
| Metadata | [Link](https://data.illinois.gov/api/views/8zr5-fyn8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8zr5-fyn8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8zr5-fyn8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8zr5-fyn8 |
| Name | Illinois Population, 1991-1999 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics |
| Category | Health |
| Tags | population, illinois |
| Created | 2014-08-11T20:53:37Z |
| Publication Date | 2014-08-11T20:55:37Z |

## Description

Data provided by the IL Center for Health Statistics.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 1991       | 1991   | number    | number      |
| Yes      | numeric metric | 1992       | 1992   | number    | number      |
| Yes      | numeric metric | 1993       | 1993   | number    | number      |
| Yes      | numeric metric | 1994       | 1994   | number    | number      |
| Yes      | numeric metric | 1995       | 1995   | number    | number      |
| Yes      | numeric metric | 1996       | 1996   | number    | number      |
| Yes      | numeric metric | 1997       | 1997   | number    | number      |
| Yes      | numeric metric | 1998       | 1998   | number    | number      |
| Yes      | numeric metric | 1999       | 1999   | number    | number      |
```

## Time Field

```ls
Value = 1991
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8zr5-fyn8 d:1991-01-01T00:00:00.000Z t:county=Illinois m:1995=11830000 m:1996=11847000 m:1997=11896000 m:1998=12045000 m:1991=11542800 m:1992=11613000 m:1993=11697000 m:1994=11752000 m:1999=12128000

series e:8zr5-fyn8 d:1991-01-01T00:00:00.000Z t:county=Adams m:1995=67600 m:1996=67200 m:1997=67300 m:1998=67600 m:1991=66400 m:1992=66600 m:1993=67000 m:1994=67500 m:1999=67200

series e:8zr5-fyn8 d:1991-01-01T00:00:00.000Z t:county=Alexander m:1995=10300 m:1996=10200 m:1997=10000 m:1998=10100 m:1991=10600 m:1992=10600 m:1993=10500 m:1994=10300 m:1999=10100
```

## Meta Commands

```ls
metric m:1991 p:integer l:1991 t:dataTypeName=number

metric m:1992 p:integer l:1992 t:dataTypeName=number

metric m:1993 p:integer l:1993 t:dataTypeName=number

metric m:1994 p:integer l:1994 t:dataTypeName=number

metric m:1995 p:integer l:1995 t:dataTypeName=number

metric m:1996 p:integer l:1996 t:dataTypeName=number

metric m:1997 p:integer l:1997 t:dataTypeName=number

metric m:1998 p:integer l:1998 t:dataTypeName=number

metric m:1999 p:integer l:1999 t:dataTypeName=number

entity e:8zr5-fyn8 l:"Illinois Population, 1991-1999" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/8zr5-fyn8

property e:8zr5-fyn8 t:meta.view v:id=8zr5-fyn8 v:category=Health v:averageRating=0 v:name="Illinois Population, 1991-1999" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics"

property e:8zr5-fyn8 t:meta.view.license v:name="Public Domain"

property e:8zr5-fyn8 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:8zr5-fyn8 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1991     | 1992     | 1993     | 1994     | 1995     | 1996     | 1997     | 1998     | 1999     | 
| ========= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| Illinois  | 11542800 | 11613000 | 11697000 | 11752000 | 11830000 | 11847000 | 11896000 | 12045000 | 12128000 | 
| Adams     | 66400    | 66600    | 67000    | 67500    | 67600    | 67200    | 67300    | 67600    | 67200    | 
| Alexander | 10600    | 10600    | 10500    | 10300    | 10300    | 10200    | 10000    | 10100    | 10100    | 
| Bond      | 15000    | 15200    | 15300    | 15200    | 16900    | 16900    | 17000    | 17300    | 17200    | 
| Boone     | 31800    | 32800    | 33700    | 35000    | 36300    | 37400    | 38100    | 39200    | 40100    | 
| Brown     | 5900     | 6200     | 6000     | 6300     | 6300     | 6600     | 6600     | 6700     | 6700     | 
| Bureau    | 35600    | 35700    | 35800    | 35700    | 35700    | 35300    | 35300    | 35300    | 35200    | 
| Calhoun   | 5200     | 5200     | 5100     | 5000     | 4900     | 4900     | 4900     | 4800     | 4800     | 
| Carroll   | 16600    | 16600    | 16600    | 16800    | 16800    | 16800    | 16800    | 16900    | 16800    | 
| Cass      | 13400    | 13300    | 13300    | 13300    | 13300    | 13200    | 13200    | 13300    | 13300    | 
```