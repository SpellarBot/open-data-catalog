# Report Card 2b VSAT Overall Satisfaction Oahu By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2b-vsat-overall-satisfaction-oahu-by-mma-73c58) |
| Metadata | [Link](https://data.hawaii.gov/api/views/j7f6-dpfq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/j7f6-dpfq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/j7f6-dpfq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | j7f6-dpfq |
| Name | Report Card 2b VSAT Overall Satisfaction Oahu By MMA |
| Created | 2012-11-18T23:38:17Z |
| Publication Date | 2012-11-18T23:39:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | time           | year       | Year    | number    | text        |
| Yes      | numeric metric | u_s        | U.S.    | number    | number      |
| Yes      | numeric metric | japan      | Japan   | number    | number      |
| Yes      | numeric metric | europe     | Europe  | number    | number      |
| Yes      | numeric metric | oceania    | Oceania | number    | number      |
| Yes      | numeric metric | canada     | Canada  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j7f6-dpfq d:2002-01-01T00:00:00.000Z m:u_s=0.577 m:japan=0.485 m:europe=0.614 m:canada=0.462

series e:j7f6-dpfq d:2003-01-01T00:00:00.000Z m:u_s=0.601 m:japan=0.551 m:europe=0.588 m:canada=0.594

series e:j7f6-dpfq d:2004-01-01T00:00:00.000Z m:u_s=0.558 m:japan=0.534 m:europe=0.607 m:canada=0.586
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:j7f6-dpfq l:"Report Card 2b VSAT Overall Satisfaction Oahu By MMA" t:url=https://data.hawaii.gov/api/views/j7f6-dpfq

property e:j7f6-dpfq t:meta.view v:id=j7f6-dpfq v:averageRating=0 v:name="Report Card 2b VSAT Overall Satisfaction Oahu By MMA"

property e:j7f6-dpfq t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:j7f6-dpfq t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.57699999999999996 | 0.48499999999999999 | 0.61399999999999999 |                     | 0.46200000000000002 | 
| 2003 | 0.60099999999999998 | 0.55100000000000005 | 0.58799999999999997 |                     | 0.59399999999999997 | 
| 2004 | 0.55800000000000005 | 0.53400000000000003 | 0.60699999999999998 |                     | 0.58599999999999997 | 
| 2005 | 0.55100000000000005 | 0.53700000000000003 | 0.57499999999999996 |                     | 0.54600000000000004 | 
| 2006 | 0.55300000000000005 | 0.53                | 0.55900000000000005 |                     | 0.51900000000000002 | 
| 2007 | 0.57999999999999996 | 0.51100000000000001 | 0.6                 |                     | 0.57899999999999996 | 
| 2008 | 0.55300000000000005 | 0.56599999999999995 | 0.59699999999999998 | 0.65                | 0.54400000000000004 | 
| 2009 | 0.61099999999999999 | 0.59299999999999997 | 0.62                | 0.58099999999999996 | 0.56699999999999995 | 
| 2010 | 0.61899999999999999 | 0.59199999999999997 |                     |                     | 0.6                 | 
| 2011 | 0.622               | 0.627               | 0.54                | 0.58899999999999997 | 0.64                | 
```