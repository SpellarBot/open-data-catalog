# Childhood Lead Poisoning Surveillance Report By County, 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-1999-fff42) |
| Metadata | [Link](https://data.illinois.gov/api/views/efei-wcw7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/efei-wcw7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/efei-wcw7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | efei-wcw7 |
| Name | Childhood Lead Poisoning Surveillance Report By County, 1999 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 1999, lead poisoning, environmental health |
| Created | 2014-08-11T18:01:12Z |
| Publication Date | 2014-08-11T18:02:11Z |

## Description

In 1993, state-mandated screening for childhood lead poisoning in children 6 years of age and younger began. Physicians and other health care providers have conducted 2.4 million lead tests and reported about 270,000 children with elevated lead levels. The numbers of elevated and normal test results are used to identify areas where effort is needed to combat lead poisoning.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | county                                  | County                                  | text      | text        |
| Yes      | numeric metric | 1990_population_of_children_6_and_under | 1990 Population of Children 6 and Under | number    | number      |
| Yes      | numeric metric | total_tested                            | Total Tested                            | number    | number      |
| Yes      | numeric metric | 10_14_mcg_dl                            | 10-14 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 15_19_mcg_dl                            | 15-19 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 20_24_mcg_dl                            | 20-24 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 25_44_mcg_dl                            | 25-44 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 45_mcg_dl                               | 45+ mcg/dL                              | number    | number      |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Data Commands

```ls
series e:efei-wcw7 d:1999-01-01T00:00:00.000Z t:county=Adams m:total_tested=614 m:45_mcg_dl=2 m:25_44_mcg_dl=6 m:1990_population_of_children_6_and_under=6664 m:10_14_mcg_dl=57 m:15_19_mcg_dl=19 m:20_24_mcg_dl=7

series e:efei-wcw7 d:1999-01-01T00:00:00.000Z t:county=Alexander m:total_tested=137 m:45_mcg_dl=0 m:25_44_mcg_dl=4 m:1990_population_of_children_6_and_under=1166 m:10_14_mcg_dl=16 m:15_19_mcg_dl=6 m:20_24_mcg_dl=6

series e:efei-wcw7 d:1999-01-01T00:00:00.000Z t:county=Bond m:total_tested=294 m:45_mcg_dl=0 m:25_44_mcg_dl=2 m:1990_population_of_children_6_and_under=1431 m:10_14_mcg_dl=14 m:15_19_mcg_dl=5 m:20_24_mcg_dl=1
```

## Meta Commands

```ls
metric m:1990_population_of_children_6_and_under p:integer l:"1990 Population of Children 6 and Under" t:dataTypeName=number

metric m:total_tested p:integer l:"Total Tested" t:dataTypeName=number

metric m:10_14_mcg_dl p:integer l:"10-14 mcg/dL" t:dataTypeName=number

metric m:15_19_mcg_dl p:integer l:"15-19 mcg/dL" t:dataTypeName=number

metric m:20_24_mcg_dl p:integer l:"20-24 mcg/dL" t:dataTypeName=number

metric m:25_44_mcg_dl p:integer l:"25-44 mcg/dL" t:dataTypeName=number

metric m:45_mcg_dl p:integer l:"45+ mcg/dL" t:dataTypeName=number

entity e:efei-wcw7 l:"Childhood Lead Poisoning Surveillance Report By County, 1999" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/efei-wcw7

property e:efei-wcw7 t:meta.view v:id=efei-wcw7 v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 1999" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:efei-wcw7 t:meta.view.license v:name="Public Domain"

property e:efei-wcw7 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:efei-wcw7 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1990_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6664                                    | 614          | 57           | 19           | 7            | 6            | 2         | 
| Alexander | 1166                                    | 137          | 16           | 6            | 6            | 4            | 0         | 
| Bond      | 1431                                    | 294          | 14           | 5            | 1            | 2            | 0         | 
| Boone     | 3344                                    | 361          | 19           | 12           | 0            | 2            | 1         | 
| Brown     | 465                                     | 12           | 1            | 1            | 0            | 0            | 0         | 
| Bureau    | 3516                                    | 421          | 4            | 5            | 3            | 1            | 1         | 
| Calhoun   | 544                                     | 52           | 5            | 0            | 1            | 0            | 0         | 
| Carroll   | 1522                                    | 227          | 15           | 4            | 0            | 0            | 0         | 
| Cass      | 1246                                    | 134          | 10           | 3            | 1            | 1            | 0         | 
| Champaign | 16730                                   | 962          | 33           | 6            | 2            | 0            | 0         | 
```