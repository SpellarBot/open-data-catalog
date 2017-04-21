# Funding By Source -- All -- 12212012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funding-by-source-all-12212012-9873f) |
| Metadata | [Link](https://data.wa.gov/api/views/gd2u-b9zp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gd2u-b9zp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gd2u-b9zp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gd2u-b9zp |
| Name | Funding By Source -- All -- 12212012 |
| Created | 2012-11-02T01:01:02Z |
| Publication Date | 2012-12-25T23:48:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | region      | Region      | text      | text        |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | state       | State       | money     | money       |
| Yes      | numeric metric | federal     | Federal     | money     | money       |
| Yes      | numeric metric | local_match | Local Match | money     | money       |
| Yes      | numeric metric | total       | Total       | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gd2u-b9zp d:1999-01-01T00:00:00.000Z t:region="Hood Canal" m:total=2020766 m:local_match=441581 m:federal=984875 m:state=594310

series e:gd2u-b9zp d:2000-01-01T00:00:00.000Z t:region="Hood Canal" m:total=6966787 m:local_match=1929585 m:federal=1863820 m:state=3173382

series e:gd2u-b9zp d:2001-01-01T00:00:00.000Z t:region="Hood Canal" m:total=4800095 m:local_match=1249766 m:federal=1166126 m:state=2384203
```

## Meta Commands

```ls
metric m:state p:double l:State t:dataTypeName=money

metric m:federal p:double l:Federal t:dataTypeName=money

metric m:local_match p:double l:"Local Match" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:gd2u-b9zp l:"Funding By Source -- All -- 12212012" t:url=https://data.wa.gov/api/views/gd2u-b9zp

property e:gd2u-b9zp t:meta.view v:id=gd2u-b9zp v:averageRating=0 v:name="Funding By Source -- All -- 12212012"

property e:gd2u-b9zp t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:gd2u-b9zp t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region     | year | state   | federal | local_match | total    | 
| ========== | ==== | ======= | ======= | =========== | ======== | 
| Hood Canal | 1999 | 594310  | 984875  | 441581      | 2020766  | 
| Hood Canal | 2000 | 3173382 | 1863820 | 1929585     | 6966787  | 
| Hood Canal | 2001 | 2384203 | 1166126 | 1249766     | 4800095  | 
| Hood Canal | 2002 | 1005798 | 736728  | 1366387     | 3108913  | 
| Hood Canal | 2003 | 0.0     | 708926  | 105660      | 814586   | 
| Hood Canal | 2004 | 1720470 | 1162564 | 1566516     | 4449550  | 
| Hood Canal | 2005 | 1017132 | 1041114 | 2213837     | 4272083  | 
| Hood Canal | 2006 | 1164412 | 496274  | 942559      | 2603245  | 
| Hood Canal | 2007 | 9512938 | 875328  | 7015178     | 17403444 | 
| Hood Canal | 2008 | 192124  | 1555594 | 322555      | 2070273  | 
```