# IDPH Divorces and Annulments, by County, 2000-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-divorces-and-annulments-by-county-2000-2009-887ce) |
| Metadata | [Link](https://data.illinois.gov/api/views/arq9-rjtk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/arq9-rjtk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/arq9-rjtk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | arq9-rjtk |
| Name | IDPH Divorces and Annulments, by County, 2000-2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | divorces, divorce, annulment |
| Created | 2012-01-17T22:02:08Z |
| Publication Date | 2012-01-23T21:45:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| No       |                | _1         | 2000   | number    | number      |
| No       |                | _2         | 2001   | number    | number      |
| No       |                | _3         | 2002   | number    | number      |
| No       |                | _4         | 2003   | number    | number      |
| No       |                | _5         | 2004   | number    | number      |
| No       |                | _6         | 2005   | number    | number      |
| No       |                | _7         | 2006   | number    | number      |
| No       |                | _8         | 2007   | number    | number      |
| No       |                | _9         | 2008   | number    | number      |
| Yes      | numeric metric | _10        | 2009   | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:arq9-rjtk d:2000-01-01T00:00:00.000Z t:county=Adams m:_10=287

series e:arq9-rjtk d:2000-01-01T00:00:00.000Z t:county=Alexander m:_10=1

series e:arq9-rjtk d:2000-01-01T00:00:00.000Z t:county=Bond m:_10=74
```

## Meta Commands

```ls
metric m:_10 p:integer l:2009 t:dataTypeName=number

entity e:arq9-rjtk l:"IDPH Divorces and Annulments, by County, 2000-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/arq9-rjtk

property e:arq9-rjtk t:meta.view v:id=arq9-rjtk v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Divorces and Annulments, by County, 2000-2009" v:attribution="Illinois Center for Health Statistics"

property e:arq9-rjtk t:meta.view.owner v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"

property e:arq9-rjtk t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | _1  | _2  | _3  | _4  | _5  | _6  | _7  | _8  | _9  | _10 | 
| ========= | === | === | === | === | === | === | === | === | === | === | 
| Adams     | 315 | 313 | 285 | 307 | 286 | 279 | 273 | 266 | 285 | 287 | 
| Alexander | 17  | 28  | 6   | 8   | 5   | 6   | 1   | 4   | 6   | 1   | 
| Bond      | 48  | 63  | 59  | 61  | 51  | 99  | 46  | 70  | 76  | 74  | 
| Boone     | 142 | 152 | 143 | 131 | 117 | 135 | 129 | 171 | 171 | 163 | 
| Brown     | 33  | 26  | 30  | 26  | 27  | 23  | 29  | 27  | 22  | 25  | 
| Bureau    | 120 | 129 | 139 | 120 | 102 | 94  | 93  | 95  | 86  | 111 | 
| Calhoun   | 10  | 6   | 14  | 6   | 14  | 11  | 12  | 15  | 2   | 5   | 
| Carroll   | 68  | 58  | 41  | 39  | 23  | 44  | 36  | 34  | 39  | 31  | 
| Cass      | 72  | 66  | 68  | 62  | 51  | 45  | 52  | 66  | 58  | 72  | 
| Champaign | 647 | 597 | 529 | 507 | 505 | 528 | 512 | 558 | 549 | 490 | 
```