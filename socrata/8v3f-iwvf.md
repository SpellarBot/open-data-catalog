# Report Card 2.1g VSAT Recommend Big Island By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-1g-vsat-recommend-big-island-by-mma-914aa) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8v3f-iwvf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8v3f-iwvf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8v3f-iwvf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8v3f-iwvf |
| Name | Report Card 2.1g VSAT Recommend Big Island By MMA |
| Created | 2012-11-19T00:56:55Z |
| Publication Date | 2012-11-19T00:57:23Z |

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
series e:8v3f-iwvf d:2006-01-01T00:00:00.000Z m:u_s=0.625 m:japan=0.513 m:europe=0.535 m:canada=0.603

series e:8v3f-iwvf d:2007-01-01T00:00:00.000Z m:u_s=0.721 m:japan=0.573 m:europe=0.63 m:canada=0.689

series e:8v3f-iwvf d:2008-01-01T00:00:00.000Z m:u_s=0.729 m:oceania=0.739 m:japan=0.614 m:europe=0.629 m:canada=0.732
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:8v3f-iwvf l:"Report Card 2.1g VSAT Recommend Big Island By MMA" t:url=https://data.hawaii.gov/api/views/8v3f-iwvf

property e:8v3f-iwvf t:meta.view v:id=8v3f-iwvf v:averageRating=0 v:name="Report Card 2.1g VSAT Recommend Big Island By MMA"

property e:8v3f-iwvf t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:8v3f-iwvf t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2006 | 0.625               | 0.51300000000000001 | 0.53500000000000003 |                     | 0.60299999999999998 | 
| 2007 | 0.72099999999999997 | 0.57299999999999995 | 0.63                |                     | 0.68899999999999995 | 
| 2008 | 0.72899999999999998 | 0.61399999999999999 | 0.629               | 0.73899999999999999 | 0.73199999999999998 | 
| 2009 | 0.73699999999999999 | 0.60499999999999998 | 0.60899999999999999 | 0.66600000000000004 | 0.73899999999999999 | 
| 2010 | 0.76200000000000001 | 0.63400000000000001 |                     |                     | 0.77100000000000002 | 
| 2011 | 0.755               | 0.629               | 0.73899999999999999 | 0.755               | 0.76500000000000001 | 
```