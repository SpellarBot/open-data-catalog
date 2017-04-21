# Report Card 2g VSAT Overall Satisfaction Hawaii Island By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2g-vsat-overall-satisfaction-hawaii-island-by-mma-3d940) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qqa6-5vvy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qqa6-5vvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qqa6-5vvy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qqa6-5vvy |
| Name | Report Card 2g VSAT Overall Satisfaction Hawaii Island By MMA |
| Created | 2012-11-19T00:12:11Z |
| Publication Date | 2012-11-19T00:12:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | time           | year       | Year    | html      | html        |
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
series e:qqa6-5vvy d:2002-01-01T00:00:00.000Z m:u_s=0.655 m:japan=0.556 m:europe=0.613 m:canada=0.562

series e:qqa6-5vvy d:2003-01-01T00:00:00.000Z m:u_s=0.651 m:japan=0.573 m:europe=0.66 m:canada=0.614

series e:qqa6-5vvy d:2004-01-01T00:00:00.000Z m:u_s=0.632 m:japan=0.577 m:europe=0.631 m:canada=0.566
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:qqa6-5vvy l:"Report Card 2g VSAT Overall Satisfaction Hawaii Island By MMA" t:url=https://data.hawaii.gov/api/views/qqa6-5vvy

property e:qqa6-5vvy t:meta.view v:id=qqa6-5vvy v:averageRating=0 v:name="Report Card 2g VSAT Overall Satisfaction Hawaii Island By MMA"

property e:qqa6-5vvy t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:qqa6-5vvy t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.65500000000000003 | 0.55600000000000005 | 0.61299999999999999 |                     | 0.56200000000000006 | 
| 2003 | 0.65100000000000002 | 0.57299999999999995 | 0.66                |                     | 0.61399999999999999 | 
| 2004 | 0.63200000000000001 | 0.57699999999999996 | 0.63100000000000001 |                     | 0.56599999999999995 | 
| 2005 | 0.51600000000000001 | 0.46600000000000003 | 0.47699999999999998 |                     | 0.438               | 
| 2006 | 0.52800000000000002 | 0.49099999999999999 | 0.47899999999999998 |                     | 0.45100000000000001 | 
| 2007 | 0.62                | 0.56599999999999995 | 0.60099999999999998 |                     | 0.57599999999999996 | 
| 2008 | 0.622               | 0.57299999999999995 | 0.57499999999999996 | 0.59499999999999997 | 0.59499999999999997 | 
| 2009 | 0.623               | 0.56699999999999995 | 0.57799999999999996 | 0.55900000000000005 | 0.63500000000000001 | 
| 2010 | 0.67600000000000005 | 0.59699999999999998 |                     |                     | 0.66300000000000003 | 
| 2011 | 0.67500000000000004 | 0.62                | 0.622               | 0.57199999999999995 | 0.64599999999999991 | 
```