# Report Card 2e VSAT Overall Satisfaction Lanai By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2e-vsat-overall-satisfaction-lanai-by-mma-c1e1b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wyyg-zvvt) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wyyg-zvvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wyyg-zvvt/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wyyg-zvvt |
| Name | Report Card 2e VSAT Overall Satisfaction Lanai By MMA |
| Created | 2012-11-19T00:03:30Z |
| Publication Date | 2012-11-19T00:04:02Z |

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
series e:wyyg-zvvt d:2002-01-01T00:00:00.000Z m:u_s=0.546 m:japan=0.424 m:europe=0.549 m:canada=0.566

series e:wyyg-zvvt d:2003-01-01T00:00:00.000Z m:u_s=0.617 m:japan=0.5 m:europe=0.6 m:canada=0.583

series e:wyyg-zvvt d:2004-01-01T00:00:00.000Z m:u_s=0.609 m:japan=0.191 m:europe=0.547 m:canada=0.522
```

## Meta Commands

```ls
metric m:u_s p:decimal l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:wyyg-zvvt l:"Report Card 2e VSAT Overall Satisfaction Lanai By MMA" t:url=https://data.hawaii.gov/api/views/wyyg-zvvt

property e:wyyg-zvvt t:meta.view v:id=wyyg-zvvt v:averageRating=0 v:name="Report Card 2e VSAT Overall Satisfaction Lanai By MMA"

property e:wyyg-zvvt t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:wyyg-zvvt t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.54600000000000004 | 0.42399999999999999 | 0.54900000000000004 |                     | 0.56599999999999995 | 
| 2003 | 0.61699999999999999 | 0.5                 | 0.6                 |                     | 0.58299999999999996 | 
| 2004 | 0.60899999999999999 | 0.191               | 0.54700000000000004 |                     | 0.52200000000000002 | 
| 2005 | 0.43099999999999999 | 0.34                | 0.47399999999999998 |                     | 0.51800000000000002 | 
| 2006 | 0.65700000000000003 | 0.56299999999999994 | 0.55500000000000005 |                     | 0.57599999999999996 | 
| 2007 | 0.60599999999999998 | 0.86299999999999999 | 0.47299999999999998 |                     | 0.55400000000000005 | 
| 2008 | 0.69                | 0.71                | 0.51900000000000002 | 0.38                | 0.40300000000000002 | 
| 2009 | 0.67600000000000005 | 0.122               | 0.79                | 0.56000000000000005 | 0.76500000000000001 | 
| 2010 | 0.59399999999999997 | 0.31                |                     |                     | 0.59                | 
| 2011 | 0.74400000000000011 | 0.42599999999999999 | 0.35100000000000003 | 0.68500000000000005 | 0.58399999999999996 | 
```