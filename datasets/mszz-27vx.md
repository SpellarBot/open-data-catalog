# IDPH Marriages, Divorces, and Annulments, State Total, 1958-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-marriages-divorces-and-annulments-state-total-1958-2009-73085) |
| Metadata | [Link](https://data.illinois.gov/api/views/mszz-27vx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mszz-27vx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mszz-27vx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mszz-27vx |
| Name | IDPH Marriages, Divorces, and Annulments, State Total, 1958-2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | marriage, divorce, anullment |
| Created | 2012-01-18T21:38:06Z |
| Publication Date | 2012-01-23T21:16:20Z |

## Description

Rate is per 1,000 population * Reporting known to be incomplete

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | text      | text        |
| Yes      | numeric metric | marriages                  | Marriages                  | number    | number      |
| Yes      | numeric metric | marriage_rate              | Marriage Rate              | number    | number      |
| Yes      | numeric metric | divorces_and_annulments    | Divorces and Annulments    | number    | number      |
| Yes      | numeric metric | divorce_and_annulment_rate | Divorce and Annulment Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mszz-27vx d:2009-01-01T00:00:00.000Z m:divorces_and_annulments=32460 m:marriage_rate=5.6 m:divorce_and_annulment_rate=2.5 m:marriages=72821

series e:mszz-27vx d:2008-01-01T00:00:00.000Z m:divorces_and_annulments=32497 m:marriage_rate=5.8 m:divorce_and_annulment_rate=2.5 m:marriages=74935

series e:mszz-27vx d:2007-01-01T00:00:00.000Z m:divorces_and_annulments=32782 m:marriage_rate=6 m:divorce_and_annulment_rate=2.6 m:marriages=76608
```

## Meta Commands

```ls
metric m:marriages p:integer l:Marriages t:dataTypeName=number

metric m:marriage_rate p:float l:"Marriage Rate" t:dataTypeName=number

metric m:divorces_and_annulments p:integer l:"Divorces and Annulments" t:dataTypeName=number

metric m:divorce_and_annulment_rate p:float l:"Divorce and Annulment Rate" t:dataTypeName=number

entity e:mszz-27vx l:"IDPH Marriages, Divorces, and Annulments, State Total, 1958-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/mszz-27vx

property e:mszz-27vx t:meta.view v:id=mszz-27vx v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Marriages, Divorces, and Annulments, State Total, 1958-2009" v:attribution="Illinois Center for Health Statistics"

property e:mszz-27vx t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:mszz-27vx t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| year | marriages | marriage_rate | divorces_and_annulments | divorce_and_annulment_rate | 
| ==== | ========= | ============= | ======================= | ========================== | 
| 2009 | 72821     | 5.6           | 32460                   | 2.5                        | 
| 2008 | 74935     | 5.8           | 32497                   | 2.5                        | 
| 2007 | 76608     | 6.0           | 32782                   | 2.6                        | 
| 2006 | 77959     | 6.1           | 32141                   | 2.5                        | 
| 2005 | 77419     | 6.1           | 33380                   | 2.6                        | 
| 2004 | 81157     | 6.4           | 33575                   | 2.6                        | 
| 2003 | 82889     | 6.6           | 35037                   | 2.8                        | 
| 2002 | 84288     | 6.7           | 37670                   | 3.0                        | 
| 2001 | 89469     | 7.2           | 37294                   | 3.0                        | 
| 2000 | 85799     | 6.9           | 39524                   | 3.2                        | 
```