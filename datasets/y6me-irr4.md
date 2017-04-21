# Childhood Lead Poisoning Surveillance Report By County, 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-2001-31c59) |
| Metadata | [Link](https://data.illinois.gov/api/views/y6me-irr4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/y6me-irr4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/y6me-irr4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | y6me-irr4 |
| Name | Childhood Lead Poisoning Surveillance Report By County, 2001 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 2001 lead poisoning, environmental health |
| Created | 2014-08-11T18:06:44Z |
| Publication Date | 2014-08-11T18:07:40Z |

## Description

In 1993, state-mandated screening for childhood lead poisoning in children 6 years of age and younger began. Physicians and other health care providers have conducted 2.4 million lead tests and reported about 270,000 children with elevated lead levels. The numbers of elevated and normal test results are used to identify areas where effort is needed to combat lead poisoning.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | county                                 | County                                 | text      | text        |
| Yes      | numeric metric | 2000population_of_children_6_and_under | 2000Population of Children 6 and Under | number    | number      |
| Yes      | numeric metric | total_tested                           | Total Tested                           | number    | number      |
| Yes      | numeric metric | 10_14_mcg_dl                           | 10-14 mcg/dL                           | number    | number      |
| Yes      | numeric metric | 15_19_mcg_dl                           | 15-19 mcg/dL                           | number    | number      |
| Yes      | numeric metric | 20_24_mcg_dl                           | 20-24 mcg/dL                           | number    | number      |
| Yes      | numeric metric | 25_44_mcg_dl                           | 25-44 mcg/dL                           | number    | number      |
| Yes      | numeric metric | 45_mcg_dl                              | 45+ mcg/dL                             | number    | number      |
```

## Time Field

```ls
Value = 2001
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y6me-irr4 d:2001-01-01T00:00:00.000Z t:county=Adams m:total_tested=611 m:45_mcg_dl=1 m:25_44_mcg_dl=7 m:10_14_mcg_dl=59 m:2000population_of_children_6_and_under=6006 m:15_19_mcg_dl=12 m:20_24_mcg_dl=6

series e:y6me-irr4 d:2001-01-01T00:00:00.000Z t:county=Alexander m:total_tested=161 m:45_mcg_dl=0 m:25_44_mcg_dl=2 m:10_14_mcg_dl=8 m:2000population_of_children_6_and_under=846 m:15_19_mcg_dl=6 m:20_24_mcg_dl=2

series e:y6me-irr4 d:2001-01-01T00:00:00.000Z t:county=Bond m:total_tested=286 m:45_mcg_dl=0 m:25_44_mcg_dl=0 m:10_14_mcg_dl=4 m:2000population_of_children_6_and_under=1411 m:15_19_mcg_dl=3 m:20_24_mcg_dl=0
```

## Meta Commands

```ls
metric m:2000population_of_children_6_and_under p:integer l:"2000Population of Children 6 and Under" t:dataTypeName=number

metric m:total_tested p:integer l:"Total Tested" t:dataTypeName=number

metric m:10_14_mcg_dl p:integer l:"10-14 mcg/dL" t:dataTypeName=number

metric m:15_19_mcg_dl p:integer l:"15-19 mcg/dL" t:dataTypeName=number

metric m:20_24_mcg_dl p:integer l:"20-24 mcg/dL" t:dataTypeName=number

metric m:25_44_mcg_dl p:integer l:"25-44 mcg/dL" t:dataTypeName=number

metric m:45_mcg_dl p:integer l:"45+ mcg/dL" t:dataTypeName=number

entity e:y6me-irr4 l:"Childhood Lead Poisoning Surveillance Report By County, 2001" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/y6me-irr4

property e:y6me-irr4 t:meta.view v:id=y6me-irr4 v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 2001" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:y6me-irr4 t:meta.view.license v:name="Public Domain"

property e:y6me-irr4 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:y6me-irr4 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ====================================== | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6006                                   | 611          | 59           | 12           | 6            | 7            | 1         | 
| Alexander | 846                                    | 161          | 8            | 6            | 2            | 2            | 0         | 
| Bond      | 1411                                   | 286          | 4            | 3            | 0            | 0            | 0         | 
| Boone     | 4569                                   | 330          | 7            | 9            | 2            | 1            | 0         | 
| Brown     | 398                                    | 38           | 3            | 1            | 0            | 0            | 0         | 
| Bureau    | 3022                                   | 345          | 2            | 0            | 1            | 1            | 0         | 
| Calhoun   | 386                                    | 59           | 2            | 0            | 0            | 0            | 0         | 
| Carroll   | 1331                                   | 299          | 16           | 6            | 1            | 1            | 0         | 
| Cass      | 1293                                   | 282          | 16           | 3            | 0            | 3            | 0         | 
| Champaign | 14575                                  | 1646         | 35           | 6            | 3            | 6            | 0         | 
```