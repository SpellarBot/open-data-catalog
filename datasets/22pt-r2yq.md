# IDES - LAUS MSAs Annual Average 1976-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-laus-msas-annual-average-1976-2011-c49a6) |
| Metadata | [Link](https://data.illinois.gov/api/views/22pt-r2yq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/22pt-r2yq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/22pt-r2yq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 22pt-r2yq |
| Name | IDES - LAUS MSAs Annual Average 1976-2011 |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides, laus, msa, economics, metropolitan, statistical |
| Created | 2012-05-10T18:49:13Z |
| Publication Date | 2012-05-14T15:45:01Z |

## Description

Annual Average Unemployment Rates by Metropolitan Statistical Area.

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
series e:22pt-r2yq d:2011-01-01T00:00:00.000Z t:area="BLOOMINGTON-NORMAL MSA" t:unemployed_number=6,575 m:unemployed_rate=7.2 m:labor_force=91405 m:employed=84830

series e:22pt-r2yq d:2011-01-01T00:00:00.000Z t:area="CHAMPAIGN-URBANA MSA" t:unemployed_number=9,775 m:unemployed_rate=8.4 m:labor_force=115770 m:employed=105995

series e:22pt-r2yq d:2011-01-01T00:00:00.000Z t:area="CHICAGO-JOLIET-NAPERVILLE METROPOLITAN DIVISION" t:unemployed_number=403,635 m:unemployed_rate=9.9 m:labor_force=4058731 m:employed=3655096
```

## Meta Commands

```ls
metric m:labor_force p:long l:"LABOR FORCE" t:dataTypeName=number

metric m:employed p:long l:EMPLOYED t:dataTypeName=number

metric m:unemployed_rate p:float l:"UNEMPLOYED RATE" t:dataTypeName=number

entity e:22pt-r2yq l:"IDES - LAUS MSAs Annual Average 1976-2011" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/22pt-r2yq

property e:22pt-r2yq t:meta.view v:id=22pt-r2yq v:category=Economics v:averageRating=0 v:name="IDES - LAUS MSAs Annual Average 1976-2011" v:attribution="IDES - Economic Information and Analysis Division"

property e:22pt-r2yq t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:22pt-r2yq t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| area                                                   | year | labor_force | employed  | unemployed_number | unemployed_rate | 
| ====================================================== | ==== | =========== | ========= | ================= | =============== | 
| BLOOMINGTON-NORMAL MSA                                 | 2011 | 91,405      | 84,830    | 6,575             | 7.2             | 
| CHAMPAIGN-URBANA MSA                                   | 2011 | 115,770     | 105,995   | 9,775             | 8.4             | 
| CHICAGO-JOLIET-NAPERVILLE METROPOLITAN DIVISION        | 2011 | 4,058,731   | 3,655,096 | 403,635           | 9.9             | 
| LAKE COUNTY-KENOSHA COUNTY IL-WI METROPOLITAN DIVISION | 2011 | 444,166     | 402,593   | 41,573            | 9.4             | 
| CHICAGO-JOLIET-NAPERVILLE-IL-IN-WI MSA                 | 2011 | 4,831,443   | 4,355,600 | 475,843           | 9.8             | 
| DANVILLE MSA                                           | 2011 | 36,594      | 32,703    | 3,891             | 10.6            | 
| DAVENPORT-MOLINE-ROCK ISLAND, IA-IL MSA, IL PART       | 2011 | 113,459     | 104,183   | 9,276             | 8.2             | 
| DAVENPORT-MOLINE-ROCK ISLAND, IA-IL MSA                | 2011 | 201,735     | 186,339   | 15,396            | 7.6             | 
| DECATUR MSA                                            | 2011 | 54,585      | 48,818    | 5,767             | 10.6            | 
| KANKAKEE-BRADLEY MSA                                   | 2011 | 55,889      | 49,083    | 6,806             | 12.2            | 
```