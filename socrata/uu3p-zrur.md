# Report Card 2.1e VSAT Recommend Lanai By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-1e-vsat-recommend-lanai-by-mma-bc906) |
| Metadata | [Link](https://data.hawaii.gov/api/views/uu3p-zrur) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/uu3p-zrur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/uu3p-zrur/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | uu3p-zrur |
| Name | Report Card 2.1e VSAT Recommend Lanai By MMA |
| Created | 2012-11-19T00:45:01Z |
| Publication Date | 2012-11-19T00:45:35Z |

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
series e:uu3p-zrur d:2006-01-01T00:00:00.000Z m:u_s=0.596 m:japan=0.369 m:europe=0.518 m:canada=0.492

series e:uu3p-zrur d:2007-01-01T00:00:00.000Z m:u_s=0.589 m:japan=0.259 m:europe=0.433 m:canada=0.562

series e:uu3p-zrur d:2008-01-01T00:00:00.000Z m:u_s=0.488 m:oceania=0.73 m:japan=0.407 m:europe=0.756 m:canada=0.597
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:uu3p-zrur l:"Report Card 2.1e VSAT Recommend Lanai By MMA" t:url=https://data.hawaii.gov/api/views/uu3p-zrur

property e:uu3p-zrur t:meta.view v:id=uu3p-zrur v:averageRating=0 v:name="Report Card 2.1e VSAT Recommend Lanai By MMA"

property e:uu3p-zrur t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:uu3p-zrur t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2006 | 0.59599999999999997 | 0.36899999999999999 | 0.51800000000000002 |                     | 0.49199999999999999 | 
| 2007 | 0.58899999999999997 | 0.25900000000000001 | 0.433               |                     | 0.56200000000000006 | 
| 2008 | 0.48799999999999999 | 0.40699999999999997 | 0.75600000000000001 | 0.73                | 0.59699999999999998 | 
| 2009 | 0.54100000000000004 | 0.36                | 0.77700000000000002 | 0.88300000000000001 | 0.66300000000000003 | 
| 2010 | 0.60199999999999998 | 0.27500000000000002 |                     |                     | 0.56000000000000005 | 
| 2011 | 0.61399999999999999 | 0.28699999999999998 | 0.751               | 0.69599999999999995 | 0.63500000000000001 | 
```