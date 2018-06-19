# Report Card 2.1c VSAT Recommend Maui By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-1c-vsat-recommend-maui-by-mma-192f5) |
| Metadata | [Link](https://data.hawaii.gov/api/views/2g7t-6bmg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/2g7t-6bmg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/2g7t-6bmg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 2g7t-6bmg |
| Name | Report Card 2.1c VSAT Recommend Maui By MMA |
| Created | 2012-11-19T00:34:05Z |
| Publication Date | 2012-11-19T00:34:29Z |

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
series e:2g7t-6bmg d:2006-01-01T00:00:00.000Z m:u_s=0.829 m:japan=0.594 m:europe=0.725 m:canada=0.853

series e:2g7t-6bmg d:2007-01-01T00:00:00.000Z m:u_s=0.816 m:japan=0.581 m:europe=0.755 m:canada=0.827

series e:2g7t-6bmg d:2008-01-01T00:00:00.000Z m:u_s=0.856 m:oceania=0.826 m:japan=0.642 m:europe=0.746 m:canada=0.843
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:2g7t-6bmg l:"Report Card 2.1c VSAT Recommend Maui By MMA" t:url=https://data.hawaii.gov/api/views/2g7t-6bmg

property e:2g7t-6bmg t:meta.view v:id=2g7t-6bmg v:averageRating=0 v:name="Report Card 2.1c VSAT Recommend Maui By MMA"

property e:2g7t-6bmg t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:2g7t-6bmg t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2006 | 0.82899999999999996 | 0.59399999999999997 | 0.72499999999999998 |                     | 0.85299999999999998 | 
| 2007 | 0.81599999999999995 | 0.58099999999999996 | 0.755               |                     | 0.82699999999999996 | 
| 2008 | 0.85599999999999998 | 0.64200000000000002 | 0.746               | 0.82599999999999996 | 0.84299999999999997 | 
| 2009 | 0.86399999999999999 | 0.60099999999999998 | 0.76100000000000001 | 0.79300000000000004 | 0.84499999999999997 | 
| 2010 | 0.86199999999999999 | 0.60499999999999998 |                     |                     | 0.874               | 
| 2011 | 0.85599999999999998 | 0.61099999999999999 | 0.747               | 0.752               | 0.85199999999999998 | 
```