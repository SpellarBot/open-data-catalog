# Report Card 2.1b VSAT Recommend Oahu By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-1b-vsat-recommend-oahu-by-mma-a5ab7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ajhw-3huu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ajhw-3huu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ajhw-3huu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ajhw-3huu |
| Name | Report Card 2.1b VSAT Recommend Oahu By MMA |
| Created | 2012-11-19T00:28:03Z |
| Publication Date | 2012-11-19T00:28:42Z |

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
series e:ajhw-3huu d:2006-01-01T00:00:00.000Z m:u_s=0.673 m:japan=0.643 m:europe=0.641 m:canada=0.679

series e:ajhw-3huu d:2007-01-01T00:00:00.000Z m:u_s=0.683 m:japan=0.626 m:europe=0.684 m:canada=0.727

series e:ajhw-3huu d:2008-01-01T00:00:00.000Z m:u_s=0.669 m:oceania=0.796 m:japan=0.695 m:europe=0.674 m:canada=0.697
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:ajhw-3huu l:"Report Card 2.1b VSAT Recommend Oahu By MMA" t:url=https://data.hawaii.gov/api/views/ajhw-3huu

property e:ajhw-3huu t:meta.view v:id=ajhw-3huu v:averageRating=0 v:name="Report Card 2.1b VSAT Recommend Oahu By MMA"

property e:ajhw-3huu t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:ajhw-3huu t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2006 | 0.67300000000000004 | 0.64300000000000002 | 0.64100000000000001 |                     | 0.67900000000000005 | 
| 2007 | 0.68300000000000005 | 0.626               | 0.68400000000000005 |                     | 0.72699999999999998 | 
| 2008 | 0.66900000000000004 | 0.69499999999999995 | 0.67400000000000004 | 0.79600000000000004 | 0.69699999999999995 | 
| 2009 | 0.71899999999999997 | 0.68899999999999995 | 0.67800000000000005 | 0.74099999999999999 | 0.71799999999999997 | 
| 2010 | 0.71899999999999997 | 0.71                |                     |                     | 0.749               | 
| 2011 | 0.72799999999999998 | 0.71799999999999997 | 0.67200000000000004 | 0.75                | 0.76800000000000002 | 
```