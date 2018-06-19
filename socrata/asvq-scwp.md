# Water and Electric Usage from 2005 - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-and-electric-usage-from-2005-2013-83298) |
| Metadata | [Link](https://data.lacity.org/api/views/asvq-scwp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/asvq-scwp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/asvq-scwp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | asvq-scwp |
| Name | Water and Electric Usage from 2005 - 2013 |
| Category | A Livable and Sustainable City |
| Tags | water and power usage |
| Created | 2014-05-30T21:29:49Z |
| Publication Date | 2014-05-30T21:37:41Z |

## Description

Water Data represents usage in HCF and Power Data is in kWh.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| No       |                | text_date  | Text Date  | text      | text        |
| No       |                | value_date | Value Date | text      | text        |
| Yes      | numeric metric | water_use  | Water Use  | number    | number      |
| Yes      | numeric metric | power_use  | Power Use  | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = text_date,value_date
```

## Data Commands

```ls
series e:asvq-scwp d:2005-01-01T00:00:00.000Z m:water_use=16.7 m:power_use=396

series e:asvq-scwp d:2005-01-01T00:00:00.000Z m:water_use=35.73 m:power_use=1013

series e:asvq-scwp d:2005-01-01T00:00:00.000Z m:water_use=23.53 m:power_use=916
```

## Meta Commands

```ls
metric m:water_use p:float l:"Water Use" t:dataTypeName=number

metric m:power_use p:integer l:"Power Use" t:dataTypeName=number

entity e:asvq-scwp l:"Water and Electric Usage from 2005 - 2013" t:url=https://data.lacity.org/api/views/asvq-scwp

property e:asvq-scwp t:meta.view v:id=asvq-scwp v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Water and Electric Usage from 2005 - 2013"

property e:asvq-scwp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:asvq-scwp t:meta.view.owner v:id=7q7s-tyf3 v:screenName="Steve Baule" v:displayName="Steve Baule"

property e:asvq-scwp t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| text_date | value_date | water_use | power_use | 
| ========= | ========== | ========= | ========= | 
| Mar_2008  | Mar-08     | 16.70     | 396       | 
| Jul_2011  | Jul-11     | 35.73     | 1013      | 
| Apr_2010  | Apr-10     | 23.53     | 916       | 
| Feb_2006  | Feb-06     | 24.33     | 456       | 
| Aug_2011  | Aug-11     | 54.06     | 385       | 
| Oct_2006  | Oct-06     | 30.39     | 309       | 
| Aug_2005  | Aug-05     | 48.05     | 637       | 
| Mar_2011  | Mar-11     | 23.57     | 512       | 
| May_2008  | May-08     | 2694.80   | 0         | 
| Sep_2006  | Sep-06     | 37.03     | 660       | 
```