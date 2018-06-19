# Report Card 2d VSAT Overall Satisfaction Molokai By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2d-vsat-overall-satisfaction-molokai-by-mma-ea4f8) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3exa-uvbq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3exa-uvbq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3exa-uvbq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3exa-uvbq |
| Name | Report Card 2d VSAT Overall Satisfaction Molokai By MMA |
| Created | 2012-11-18T23:58:38Z |
| Publication Date | 2012-11-18T23:59:19Z |

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
series e:3exa-uvbq d:2002-01-01T00:00:00.000Z m:u_s=0.461 m:japan=0.131 m:europe=0.203 m:canada=0.101

series e:3exa-uvbq d:2003-01-01T00:00:00.000Z m:u_s=0.536 m:japan=0.417 m:europe=0.5 m:canada=0.593

series e:3exa-uvbq d:2004-01-01T00:00:00.000Z m:u_s=0.578 m:japan=0.497 m:europe=0.44 m:canada=0.316
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:3exa-uvbq l:"Report Card 2d VSAT Overall Satisfaction Molokai By MMA" t:url=https://data.hawaii.gov/api/views/3exa-uvbq

property e:3exa-uvbq t:meta.view v:id=3exa-uvbq v:averageRating=0 v:name="Report Card 2d VSAT Overall Satisfaction Molokai By MMA"

property e:3exa-uvbq t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:3exa-uvbq t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.46100000000000002 | 0.13100000000000001 | 0.20300000000000001 |                     | 0.10100000000000001 | 
| 2003 | 0.53600000000000003 | 0.41699999999999998 | 0.5                 |                     | 0.59299999999999997 | 
| 2004 | 0.57799999999999996 | 0.497               | 0.44                |                     | 0.316               | 
| 2005 | 0.65900000000000003 | 0.57399999999999995 | 0.63300000000000001 |                     | 0.51800000000000002 | 
| 2006 | 0.60399999999999998 | 0.42499999999999999 | 0.56200000000000006 |                     | 0.57399999999999995 | 
| 2007 | 0.53600000000000003 | 0.64300000000000002 | 0.46100000000000002 |                     | 0.65600000000000003 | 
| 2008 | 0.58199999999999996 | 0.47499999999999998 | 0.626               | 0.47                | 0.433               | 
| 2009 | 0.51                | 0.434               | 0.443               | 0.73699999999999999 | 0.437               | 
| 2010 | 0.52200000000000002 | 0.14899999999999999 |                     |                     | 0.622               | 
| 2011 | 0.621               | 0.28299999999999997 | 0.45799999999999996 | 0.435               | 0.59799999999999998 | 
```