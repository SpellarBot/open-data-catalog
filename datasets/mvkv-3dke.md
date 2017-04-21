# Report Card 2f VSAT Overall Satisfaction Kauai By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2f-vsat-overall-satisfaction-kauai-by-mma-81f01) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mvkv-3dke) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mvkv-3dke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mvkv-3dke/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mvkv-3dke |
| Name | Report Card 2f VSAT Overall Satisfaction Kauai By MMA |
| Created | 2012-11-19T00:07:46Z |
| Publication Date | 2012-11-19T00:08:23Z |

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
series e:mvkv-3dke d:2002-01-01T00:00:00.000Z m:u_s=0.755 m:japan=0.455 m:europe=0.697 m:canada=0.643

series e:mvkv-3dke d:2003-01-01T00:00:00.000Z m:u_s=0.764 m:japan=0.416 m:europe=0.713 m:canada=0.73

series e:mvkv-3dke d:2004-01-01T00:00:00.000Z m:u_s=0.733 m:japan=0.463 m:europe=0.72 m:canada=0.664
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:mvkv-3dke l:"Report Card 2f VSAT Overall Satisfaction Kauai By MMA" t:url=https://data.hawaii.gov/api/views/mvkv-3dke

property e:mvkv-3dke t:meta.view v:id=mvkv-3dke v:averageRating=0 v:name="Report Card 2f VSAT Overall Satisfaction Kauai By MMA"

property e:mvkv-3dke t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:mvkv-3dke t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.755               | 0.45500000000000002 | 0.69699999999999995 |                     | 0.64300000000000002 | 
| 2003 | 0.76400000000000001 | 0.41599999999999998 | 0.71299999999999997 |                     | 0.73                | 
| 2004 | 0.73299999999999998 | 0.46300000000000002 | 0.72                |                     | 0.66400000000000003 | 
| 2005 | 0.70599999999999996 | 0.47899999999999998 | 0.69899999999999995 |                     | 0.65300000000000002 | 
| 2006 | 0.66900000000000004 | 0.42                | 0.67700000000000005 |                     | 0.63                | 
| 2007 | 0.72399999999999998 | 0.48                | 0.72299999999999998 |                     | 0.69699999999999995 | 
| 2008 | 0.749               | 0.52700000000000002 | 0.76                | 0.64800000000000002 | 0.64800000000000002 | 
| 2009 | 0.72499999999999998 | 0.53                | 0.69                | 0.64                | 0.65900000000000003 | 
| 2010 | 0.749               | 0.42799999999999999 |                     |                     | 0.72399999999999998 | 
| 2011 | 0.77300000000000002 | 0.53500000000000003 | 0.68299999999999994 | 0.8                 | 0.70700000000000007 | 
```