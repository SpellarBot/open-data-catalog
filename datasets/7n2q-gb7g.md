# Report Card 2.3a VSAT Expectations Statewide By MMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-2-3a-vsat-expectations-statewide-by-mma-25038) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7n2q-gb7g) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7n2q-gb7g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7n2q-gb7g/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7n2q-gb7g |
| Name | Report Card 2.3a VSAT Expectations Statewide By MMA |
| Created | 2012-11-19T01:10:37Z |
| Publication Date | 2012-11-19T01:11:07Z |

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
series e:7n2q-gb7g d:2002-01-01T00:00:00.000Z m:u_s=0.399 m:japan=0.31 m:europe=0.469 m:canada=0.313

series e:7n2q-gb7g d:2003-01-01T00:00:00.000Z m:u_s=0.386 m:japan=0.313 m:europe=0.552 m:canada=0.383

series e:7n2q-gb7g d:2004-01-01T00:00:00.000Z m:u_s=0.354 m:japan=0.292 m:europe=0.414 m:canada=0.349
```

## Meta Commands

```ls
metric m:u_s p:float l:U.S. t:dataTypeName=number

metric m:japan p:float l:Japan t:dataTypeName=number

metric m:europe p:float l:Europe t:dataTypeName=number

metric m:oceania p:float l:Oceania t:dataTypeName=number

metric m:canada p:float l:Canada t:dataTypeName=number

entity e:7n2q-gb7g l:"Report Card 2.3a VSAT Expectations Statewide By MMA" t:url=https://data.hawaii.gov/api/views/7n2q-gb7g

property e:7n2q-gb7g t:meta.view v:id=7n2q-gb7g v:averageRating=0 v:name="Report Card 2.3a VSAT Expectations Statewide By MMA"

property e:7n2q-gb7g t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:7n2q-gb7g t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | u_s                 | japan               | europe              | oceania             | canada              | 
| ==== | =================== | =================== | =================== | =================== | =================== | 
| 2002 | 0.39900000000000002 | 0.31                | 0.46899999999999997 |                     | 0.313               | 
| 2003 | 0.38600000000000001 | 0.313               | 0.55200000000000005 |                     | 0.38300000000000001 | 
| 2004 | 0.35399999999999998 | 0.29199999999999998 | 0.41399999999999998 |                     | 0.34899999999999998 | 
| 2005 | 0.35199999999999998 | 0.311               | 0.41899999999999998 |                     | 0.34399999999999997 | 
| 2006 | 0.35399999999999998 | 0.29599999999999999 | 0.39900000000000002 |                     | 0.34100000000000003 | 
| 2007 | 0.36599999999999999 | 0.29299999999999998 | 0.435               |                     | 0.40600000000000003 | 
| 2008 | 0.374               | 0.31                | 0.435               | 0.32100000000000001 | 0.32500000000000001 | 
| 2009 | 0.36599999999999999 | 0.32700000000000001 | 0.46300000000000002 | 0.317               | 0.36199999999999999 | 
| 2010 | 0.41099999999999998 | 0.33100000000000002 |                     |                     | 0.39200000000000002 | 
| 2011 | 0.38300000000000001 | 0.35399999999999998 | 0.38700000000000001 | 0.36                | 0.38800000000000001 | 
```