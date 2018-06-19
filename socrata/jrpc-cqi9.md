# IDES - LAUS EDRs Annual Average 1990-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-laus-edrs-annual-average-1990-2011-955ec) |
| Metadata | [Link](https://data.illinois.gov/api/views/jrpc-cqi9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jrpc-cqi9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jrpc-cqi9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jrpc-cqi9 |
| Name | IDES - LAUS EDRs Annual Average 1990-2011 |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides, laus, unemployment, edr, region |
| Created | 2012-05-15T16:35:06Z |
| Publication Date | 2012-05-15T16:37:30Z |

## Description

Annual Average Unemployment Rates by Economic Development Region.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | area              | AREA              | text      | text        |
| Yes      | series tag     | region            | REGION #          | text      | text        |
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
series e:jrpc-cqi9 d:2011-01-01T00:00:00.000Z t:region=1 t:area="CENTRAL REGION" t:unemployed_number=25,701 m:unemployed_rate=9 m:labor_force=285333 m:employed=259632

series e:jrpc-cqi9 d:2011-01-01T00:00:00.000Z t:region=2 t:area="EAST CENTRAL REGION" t:unemployed_number=16,052 m:unemployed_rate=9 m:labor_force=179082 m:employed=163030

series e:jrpc-cqi9 d:2011-01-01T00:00:00.000Z t:region=3 t:area="NORTH CENTRAL REGION" t:unemployed_number=29,470 m:unemployed_rate=8.5 m:labor_force=347752 m:employed=318282
```

## Meta Commands

```ls
metric m:labor_force p:long l:"LABOR FORCE" t:dataTypeName=number

metric m:employed p:long l:EMPLOYED t:dataTypeName=number

metric m:unemployed_rate p:float l:"UNEMPLOYED RATE" t:dataTypeName=number

entity e:jrpc-cqi9 l:"IDES - LAUS EDRs Annual Average 1990-2011" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/jrpc-cqi9

property e:jrpc-cqi9 t:meta.view v:id=jrpc-cqi9 v:category=Economics v:averageRating=0 v:name="IDES - LAUS EDRs Annual Average 1990-2011" v:attribution="IDES - Economic Information and Analysis Division"

property e:jrpc-cqi9 t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:jrpc-cqi9 t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| area                      | region | year | labor_force | employed  | unemployed_number | unemployed_rate | 
| ========================= | ====== | ==== | =========== | ========= | ================= | =============== | 
| CENTRAL REGION            | 1      | 2011 | 285,333     | 259,632   | 25,701            | 9.0             | 
| EAST CENTRAL REGION       | 2      | 2011 | 179,082     | 163,030   | 16,052            | 9.0             | 
| NORTH CENTRAL REGION      | 3      | 2011 | 347,752     | 318,282   | 29,470            | 8.5             | 
| NORTHEAST REGION          | 4      | 2011 | 4,473,135   | 4,028,837 | 444,298           | 9.9             | 
| NORTHERN STATELINE REGION | 5      | 2011 | 219,302     | 191,922   | 27,380            | 12.5            | 
| NORTHWEST REGION          | 6      | 2011 | 263,269     | 238,352   | 24,917            | 9.5             | 
| SOUTHEASTERN REGION       | 7      | 2011 | 140,956     | 127,596   | 13,360            | 9.5             | 
| SOUTHERN REGION           | 8      | 2011 | 188,808     | 171,229   | 17,579            | 9.3             | 
| SOUTHWESTERN REGION       | 9      | 2011 | 349,335     | 316,836   | 32,499            | 9.3             | 
| WEST CENTRAL REGION       | 10     | 2011 | 118,535     | 109,438   | 9,097             | 7.7             | 
```