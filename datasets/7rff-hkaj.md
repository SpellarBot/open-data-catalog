# Report Card 2c VSAT Overall Satisfaction Maui By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2c-vsat-overall-satisfaction-maui-by-mma-f402c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7rff-hkaj) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7rff-hkaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7rff-hkaj/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7rff-hkaj |
| Name | Report Card 2c VSAT Overall Satisfaction Maui By MMA |
| Created | 2012-11-18T23:52:52Z |
| Publication Date | 2012-11-18T23:53:38Z |

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
series e:7rff-hkaj d:2002-01-01T00:00:00.000Z m:u_s=0.701 m:japan=0.519 m:europe=0.638 m:canada=0.635

series e:7rff-hkaj d:2003-01-01T00:00:00.000Z m:u_s=0.736 m:japan=0.537 m:europe=0.656 m:canada=0.667

series e:7rff-hkaj d:2004-01-01T00:00:00.000Z m:u_s=0.703 m:japan=0.53 m:europe=0.67 m:canada=0.69
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:decimal l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:7rff-hkaj l:"Report Card 2c VSAT Overall Satisfaction Maui By MMA" t:url=https://data.hawaii.gov/api/views/7rff-hkaj

property e:7rff-hkaj t:meta.view v:id=7rff-hkaj v:averageRating=0 v:name="Report Card 2c VSAT Overall Satisfaction Maui By MMA"

property e:7rff-hkaj t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:7rff-hkaj t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.70099999999999996 | 0.51900000000000002 | 0.63800000000000001 |                     | 0.63500000000000001 | 
| 2003 | 0.73599999999999999 | 0.53700000000000003 | 0.65600000000000003 |                     | 0.66700000000000004 | 
| 2004 | 0.70299999999999996 | 0.53                | 0.67                |                     | 0.69                | 
| 2005 | 0.73299999999999998 | 0.57799999999999996 | 0.68200000000000005 |                     | 0.68                | 
| 2006 | 0.69099999999999995 | 0.50900000000000001 | 0.63800000000000001 |                     | 0.67700000000000005 | 
| 2007 | 0.68100000000000005 | 0.54                | 0.66200000000000003 |                     | 0.624               | 
| 2008 | 0.73699999999999999 | 0.54300000000000004 | 0.61699999999999999 | 0.61599999999999999 | 0.66700000000000004 | 
| 2009 | 0.73399999999999999 | 0.55700000000000005 | 0.66200000000000003 | 0.64600000000000002 | 0.65900000000000003 | 
| 2010 | 0.72499999999999998 | 0.57399999999999995 |                     |                     | 0.72299999999999998 | 
| 2011 | 0.75800000000000001 | 0.57399999999999995 | 0.7                 | 0.66099999999999992 | 0.71                | 
```