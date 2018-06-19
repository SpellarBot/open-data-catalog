# IDES - LAUS LWA's Annual Average 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-laus-lwas-annual-average-2000-2011-09212) |
| Metadata | [Link](https://data.illinois.gov/api/views/j4e8-4cec) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/j4e8-4cec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/j4e8-4cec/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | j4e8-4cec |
| Name | IDES - LAUS LWA's Annual Average 2000-2011 |
| Attribution | IDES - Economic Information and Analysis Division |
| Tags | ides, laus, lwa, unemployment, workforce, investment |
| Created | 2012-05-10T18:52:55Z |
| Publication Date | 2012-05-14T15:44:49Z |

## Description

Annual Average Unemployment Rates by Local Workforce Area's.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | area              | AREA              | text      | text        |
| Yes      | time           | year              | YEAR              | number    | text        |
| Yes      | numeric metric | labor_force       | LABOR FORCE       | number    | text        |
| Yes      | numeric metric | employed          | EMPLOYED          | number    | text        |
| Yes      | series tag     | unemployed_number | UNEMPLOYED NUMBER | text      | text        |
| Yes      | numeric metric | unemployed_rate   | UNEMPLOYED RATE   | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j4e8-4cec d:2011-01-01T00:00:00.000Z t:area="LWIA # 1" t:unemployed_number=33,857 m:unemployed_rate=9.4 m:labor_force=358515 m:employed=324658

series e:j4e8-4cec d:2011-01-01T00:00:00.000Z t:area="LWIA # 2" t:unemployed_number=16,357 m:unemployed_rate=9.4 m:labor_force=174781 m:employed=158424

series e:j4e8-4cec d:2011-01-01T00:00:00.000Z t:area="LWIA # 3" t:unemployed_number=21,601 m:unemployed_rate=12.9 m:labor_force=168068 m:employed=146467
```

## Meta Commands

```ls
metric m:labor_force p:long l:"LABOR FORCE" t:dataTypeName=number

metric m:employed p:long l:EMPLOYED t:dataTypeName=number

metric m:unemployed_rate p:float l:"UNEMPLOYED RATE" t:dataTypeName=number

entity e:j4e8-4cec l:"IDES - LAUS LWA's Annual Average 2000-2011" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/j4e8-4cec

property e:j4e8-4cec t:meta.view v:id=j4e8-4cec v:averageRating=0 v:name="IDES - LAUS LWA's Annual Average 2000-2011" v:attribution="IDES - Economic Information and Analysis Division"

property e:j4e8-4cec t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:j4e8-4cec t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| area      | year | labor_force | employed  | unemployed_number | unemployed_rate | 
| ========= | ==== | =========== | ========= | ================= | =============== | 
| LWIA # 1  | 2011 | 358,515     | 324,658   | 33,857            | 9.4             | 
| LWIA # 2  | 2011 | 174,781     | 158,424   | 16,357            | 9.4             | 
| LWIA # 3  | 2011 | 168,068     | 146,467   | 21,601            | 12.9            | 
| LWIA # 4  | 2011 | 101,895     | 91,390    | 10,505            | 10.3            | 
| LWIA # 5  | 2011 | 398,369     | 360,155   | 38,214            | 9.6             | 
| LWIA # 6  | 2011 | 517,675     | 476,382   | 41,293            | 8.0             | 
| LWIA # 7  | 2011 | 731,897     | 653,499   | 78,398            | 10.7            | 
| LWIA # 8  | 2011 | 584,274     | 538,036   | 46,238            | 7.9             | 
| LWIA # 9  | 2011 | 1,259,055   | 1,116,216 | 142,839           | 11.3            | 
| LWIA # 10 | 2011 | 364,982     | 327,954   | 37,028            | 10.1            | 
```