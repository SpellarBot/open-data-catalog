# IDPH Birth Counts, by County, 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-birth-counts-by-county-2009-9b481) |
| Metadata | [Link](https://data.illinois.gov/api/views/gja4-da4w) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/gja4-da4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/gja4-da4w/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | gja4-da4w |
| Name | IDPH Birth Counts, by County, 2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | birth |
| Created | 2012-01-18T22:04:27Z |
| Publication Date | 2012-01-23T21:15:53Z |

## Description

* City of Chicago totals may include births occurring to residents of the city of Chicago in DuPage County and appear also in the DuPage County birth numbers.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | html      | html        |
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
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:gja4-da4w d:2009-01-01T00:00:00.000Z t:county=Adams m:_10=804

series e:gja4-da4w d:2009-01-01T00:00:00.000Z t:county=Alexander m:_10=114

series e:gja4-da4w d:2009-01-01T00:00:00.000Z t:county=Bond m:_10=198
```

## Meta Commands

```ls
metric m:_10 p:integer l:2009 t:dataTypeName=number

entity e:gja4-da4w l:"IDPH Birth Counts, by County, 2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/gja4-da4w

property e:gja4-da4w t:meta.view v:id=gja4-da4w v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Birth Counts, by County, 2009" v:attribution="Illinois Center for Health Statistics"

property e:gja4-da4w t:meta.view.owner v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"

property e:gja4-da4w t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | _1   | _2   | _3   | _4   | _5   | _6   | _7   | _8   | _9   | _10  | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Adams     | 825  | 866  | 760  | 794  | 802  | 883  | 805  | 890  | 817  | 804  | 
| Alexander | 132  | 138  | 129  | 141  | 126  | 122  | 112  | 136  | 120  | 114  | 
| Bond      | 184  | 196  | 172  | 239  | 209  | 189  | 215  | 185  | 173  | 198  | 
| Boone     | 587  | 629  | 629  | 668  | 646  | 744  | 737  | 736  | 676  | 622  | 
| Brown     | 63   | 57   | 54   | 76   | 56   | 54   | 57   | 60   | 64   | 65   | 
| Calhoun   | 51   | 49   | 48   | 58   | 51   | 58   | 55   | 49   | 59   | 53   | 
| Carroll   | 170  | 147  | 191  | 154  | 151  | 160  | 140  | 163  | 142  | 123  | 
| Cass      | 181  | 215  | 185  | 208  | 181  | 199  | 177  | 195  | 200  | 164  | 
| Champaign | 2260 | 2312 | 2226 | 2288 | 2291 | 2490 | 2455 | 2508 | 2482 | 2407 | 
| Christian | 404  | 396  | 396  | 393  | 424  | 403  | 416  | 444  | 403  | 406  | 
```