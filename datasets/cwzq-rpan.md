# Report Card 2.2a VSAT Return Statewide By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-2a-vsat-return-statewide-by-mma-febe1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cwzq-rpan) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cwzq-rpan/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cwzq-rpan/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cwzq-rpan |
| Name | Report Card 2.2a VSAT Return Statewide By MMA |
| Created | 2012-11-19T01:03:07Z |
| Publication Date | 2012-11-19T01:03:38Z |

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
series e:cwzq-rpan d:2002-01-01T00:00:00.000Z m:u_s=0.692 m:japan=0.523 m:europe=0.44 m:canada=0.531

series e:cwzq-rpan d:2003-01-01T00:00:00.000Z m:u_s=0.667 m:japan=0.564 m:europe=0.376 m:canada=0.52

series e:cwzq-rpan d:2004-01-01T00:00:00.000Z m:u_s=0.654 m:japan=0.489 m:europe=0.359 m:canada=0.528
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:cwzq-rpan l:"Report Card 2.2a VSAT Return Statewide By MMA" t:url=https://data.hawaii.gov/api/views/cwzq-rpan

property e:cwzq-rpan t:meta.view v:id=cwzq-rpan v:averageRating=0 v:name="Report Card 2.2a VSAT Return Statewide By MMA"

property e:cwzq-rpan t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:cwzq-rpan t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.69199999999999995 | 0.52300000000000002 | 0.44                |                     | 0.53100000000000003 | 
| 2003 | 0.66700000000000004 | 0.56399999999999995 | 0.376               |                     | 0.52                | 
| 2004 | 0.65400000000000003 | 0.48899999999999999 | 0.35899999999999999 |                     | 0.52800000000000002 | 
| 2005 | 0.63800000000000001 | 0.49399999999999999 | 0.35199999999999998 |                     | 0.51200000000000001 | 
| 2006 | 0.65500000000000003 | 0.495               | 0.35699999999999998 |                     | 0.53700000000000003 | 
| 2007 | 0.65700000000000003 | 0.46100000000000002 | 0.34699999999999998 |                     | 0.53400000000000003 | 
| 2008 | 0.65200000000000002 | 0.504               | 0.36399999999999999 | 0.46899999999999997 | 0.58799999999999997 | 
| 2009 | 0.67700000000000005 | 0.55800000000000005 | 0.39700000000000002 | 0.45600000000000002 | 0.624               | 
| 2010 | 0.68600000000000005 | 0.56999999999999995 |                     |                     | 0.627               | 
| 2011 | 0.67200000000000004 | 0.51900000000000002 | 0.35299999999999998 | 0.495               | 0.63900000000000001 | 
```