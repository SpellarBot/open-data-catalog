# IDES - LAUS County Annual Average 1974-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-laus-county-annual-average-1974-2011-e7c35) |
| Metadata | [Link](https://data.illinois.gov/api/views/mesy-sktx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mesy-sktx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mesy-sktx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mesy-sktx |
| Name | IDES - LAUS County Annual Average 1974-2011 |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides, laus, unemployment, county |
| Created | 2012-05-15T16:29:54Z |
| Publication Date | 2012-05-15T16:33:02Z |

## Description

Annual Average Unemployment Rates by County.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | county            | COUNTY            | text      | text        |
| Yes      | series tag     | fips              | FIPS              | text      | text        |
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
series e:mesy-sktx d:2011-01-01T00:00:00.000Z t:unemployed_number=2,485 t:county="ADAMS COUNTY" t:fips=1 m:unemployed_rate=6.6 m:labor_force=37424 m:employed=34939

series e:mesy-sktx d:2011-01-01T00:00:00.000Z t:unemployed_number=398 t:county="ALEXANDER COUNTY" t:fips=3 m:unemployed_rate=13.1 m:labor_force=3035 m:employed=2637

series e:mesy-sktx d:2011-01-01T00:00:00.000Z t:unemployed_number=780 t:county="BOND COUNTY" t:fips=5 m:unemployed_rate=9.2 m:labor_force=8435 m:employed=7655
```

## Meta Commands

```ls
metric m:labor_force p:long l:"LABOR FORCE" t:dataTypeName=number

metric m:employed p:long l:EMPLOYED t:dataTypeName=number

metric m:unemployed_rate p:float l:"UNEMPLOYED RATE" t:dataTypeName=number

entity e:mesy-sktx l:"IDES - LAUS County Annual Average 1974-2011" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/mesy-sktx

property e:mesy-sktx t:meta.view v:id=mesy-sktx v:category=Economics v:averageRating=0 v:name="IDES - LAUS County Annual Average 1974-2011" v:attribution="IDES - Economic Information and Analysis Division"

property e:mesy-sktx t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:mesy-sktx t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| county           | fips | year | labor_force | employed | unemployed_number | unemployed_rate | 
| ================ | ==== | ==== | =========== | ======== | ================= | =============== | 
| ADAMS COUNTY     | 1    | 2011 | 37,424      | 34,939   | 2,485             | 6.6             | 
| ALEXANDER COUNTY | 3    | 2011 | 3,035       | 2,637    | 398               | 13.1            | 
| BOND COUNTY      | 5    | 2011 | 8,435       | 7,655    | 780               | 9.2             | 
| BOONE COUNTY     | 7    | 2011 | 26,123      | 22,604   | 3,519             | 13.5            | 
| BROWN COUNTY     | 9    | 2011 | 3,606       | 3,438    | 168               | 4.7             | 
| BUREAU COUNTY    | 11   | 2011 | 19,105      | 17,126   | 1,979             | 10.4            | 
| CALHOUN COUNTY   | 13   | 2011 | 2,548       | 2,284    | 264               | 10.4            | 
| CARROLL COUNTY   | 15   | 2011 | 8,080       | 7,290    | 790               | 9.8             | 
| CASS COUNTY      | 17   | 2011 | 7,620       | 7,035    | 585               | 7.7             | 
| CHAMPAIGN COUNTY | 19   | 2011 | 100,761     | 92,289   | 8,472             | 8.4             | 
```