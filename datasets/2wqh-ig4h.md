# IDPH Death Counts, by County, 2000-2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-death-counts-by-county-2000-2008-cc1ea) |
| Metadata | [Link](https://data.illinois.gov/api/views/2wqh-ig4h) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2wqh-ig4h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2wqh-ig4h/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2wqh-ig4h |
| Name | IDPH Death Counts, by County, 2000-2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Created | 2012-01-17T21:57:21Z |
| Publication Date | 2012-01-23T21:46:23Z |

## Description

* City of Chicago totals may include births occurring to residents of the city of Chicago in DuPage County and appear also in the DuPage County death numbers.

## Columns

```ls
| Included | Schema Type | Field Name | Name   | Data Type | Render Type |
| ======== | =========== | ========== | ====== | ========= | =========== |
| Yes      | series tag  | county     | County | text      | text        |
| No       |             | _1         | 2000   | number    | number      |
| No       |             | _2         | 2001   | number    | number      |
| No       |             | _3         | 2002   | number    | number      |
| No       |             | _4         | 2003   | number    | number      |
| No       |             | _5         | 2004   | number    | number      |
| No       |             | _6         | 2005   | number    | number      |
| No       |             | _7         | 2006   | number    | number      |
| No       |             | _8         | 2007   | number    | number      |
| No       |             | _9         | 2008   | number    | number      |
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
series e:2wqh-ig4h d:2000-01-01T00:00:00.000Z t:county=Adams m:row_number.2wqh-ig4h=1

series e:2wqh-ig4h d:2000-01-01T00:00:00.000Z t:county=Alexander m:row_number.2wqh-ig4h=2

series e:2wqh-ig4h d:2000-01-01T00:00:00.000Z t:county=Bond m:row_number.2wqh-ig4h=3
```

## Meta Commands

```ls
metric m:row_number.2wqh-ig4h p:long l:"Row Number"

entity e:2wqh-ig4h l:"IDPH Death Counts, by County, 2000-2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/2wqh-ig4h

property e:2wqh-ig4h t:meta.view v:id=2wqh-ig4h v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Death Counts, by County, 2000-2008" v:attribution="Illinois Center for Health Statistics"

property e:2wqh-ig4h t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:2wqh-ig4h t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | _1   | _2   | _3   | _4   | _5   | _6   | _7   | _8   | _9   | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Adams     | 845  | 793  | 875  | 854  | 833  | 824  | 808  | 849  | 843  | 
| Alexander | 124  | 113  | 140  | 130  | 137  | 109  | 134  | 106  | 111  | 
| Bond      | 167  | 174  | 193  | 180  | 181  | 138  | 180  | 209  | 156  | 
| Boone     | 308  | 293  | 304  | 286  | 343  | 352  | 348  | 342  | 365  | 
| Brown     | 59   | 47   | 63   | 66   | 68   | 69   | 63   | 50   | 56   | 
| Bureau    | 425  | 379  | 429  | 432  | 396  | 372  | 384  | 398  | 397  | 
| Calhoun   | 58   | 74   | 53   | 72   | 67   | 63   | 62   | 55   | 71   | 
| Carroll   | 192  | 203  | 191  | 193  | 179  | 198  | 206  | 178  | 195  | 
| Cass      | 161  | 149  | 158  | 158  | 163  | 127  | 159  | 189  | 166  | 
| Champaign | 1107 | 1241 | 1150 | 1187 | 1192 | 1218 | 1127 | 1115 | 1147 | 
```