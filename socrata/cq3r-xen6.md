# IDPH Births to Unmarried Mothers, State Total, 1950-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-births-to-unmarried-mothers-state-total-1950-2009-7eea9) |
| Metadata | [Link](https://data.illinois.gov/api/views/cq3r-xen6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cq3r-xen6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cq3r-xen6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cq3r-xen6 |
| Name | IDPH Births to Unmarried Mothers, State Total, 1950-2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Created | 2012-01-17T21:47:16Z |
| Publication Date | 2012-01-23T21:47:09Z |

## Description

Per 1,000 live births

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | time           | year                                | Year                                | number    | number      |
| Yes      | numeric metric | total_births                        | Total Births                        | number    | number      |
| Yes      | numeric metric | number_of_births_to_unmarried_women | Number of Births to Unmarried Women | number    | number      |
| Yes      | numeric metric | ratio_of_births_to_unmarried_women  | Ratio of Births to Unmarried Women  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cq3r-xen6 d:2009-01-01T00:00:00.000Z m:number_of_births_to_unmarried_women=69728 m:ratio_of_births_to_unmarried_women=407.6 m:total_births=171077

series e:cq3r-xen6 d:2008-01-01T00:00:00.000Z m:number_of_births_to_unmarried_women=71836 m:ratio_of_births_to_unmarried_women=406.7 m:total_births=176634

series e:cq3r-xen6 d:2007-01-01T00:00:00.000Z m:number_of_births_to_unmarried_women=72385 m:ratio_of_births_to_unmarried_women=401 m:total_births=180530
```

## Meta Commands

```ls
metric m:total_births p:integer l:"Total Births" t:dataTypeName=number

metric m:number_of_births_to_unmarried_women p:integer l:"Number of Births to Unmarried Women" t:dataTypeName=number

metric m:ratio_of_births_to_unmarried_women p:float l:"Ratio of Births to Unmarried Women" t:dataTypeName=number

entity e:cq3r-xen6 l:"IDPH Births to Unmarried Mothers, State Total, 1950-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/cq3r-xen6

property e:cq3r-xen6 t:meta.view v:id=cq3r-xen6 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Births to Unmarried Mothers, State Total, 1950-2009" v:attribution="Illinois Center for Health Statistics"

property e:cq3r-xen6 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:cq3r-xen6 t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| year | total_births | number_of_births_to_unmarried_women | ratio_of_births_to_unmarried_women | 
| ==== | ============ | =================================== | ================================== | 
| 2009 | 171077       | 69728                               | 407.6                              | 
| 2008 | 176634       | 71836                               | 406.7                              | 
| 2007 | 180530       | 72385                               | 401.0                              | 
| 2006 | 180503       | 69912                               | 387.3                              | 
| 2005 | 178872       | 66266                               | 370.5                              | 
| 2004 | 180665       | 65507                               | 362.6                              | 
| 2003 | 182393       | 64358                               | 352.9                              | 
| 2002 | 180555       | 62860                               | 348.1                              | 
| 2001 | 184022       | 63426                               | 344.7                              | 
| 2000 | 185003       | 63823                               | 345.0                              | 
```