# Childhood Lead Poisoning Surveillance Report By County, 1997

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-1997-0d22c) |
| Metadata | [Link](https://data.illinois.gov/api/views/49a7-bxui) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/49a7-bxui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/49a7-bxui/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 49a7-bxui |
| Name | Childhood Lead Poisoning Surveillance Report By County, 1997 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 1997, lead poisoning, environmental health |
| Created | 2014-08-11T17:56:51Z |
| Publication Date | 2014-08-11T17:57:37Z |

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
Value = 1997
Format & Zone = yyyy
```

## Data Commands

```ls
series e:49a7-bxui d:1997-01-01T00:00:00.000Z t:county=Adams m:total_tested=788 m:45_mcg_dl=3 m:25_44_mcg_dl=17 m:1990_population_of_children_6_and_under=6664 m:10_14_mcg_dl=135 m:15_19_mcg_dl=37 m:20_24_mcg_dl=12

series e:49a7-bxui d:1997-01-01T00:00:00.000Z t:county=Alexander m:total_tested=279 m:45_mcg_dl=0 m:25_44_mcg_dl=5 m:1990_population_of_children_6_and_under=1166 m:10_14_mcg_dl=41 m:15_19_mcg_dl=18 m:20_24_mcg_dl=2

series e:49a7-bxui d:1997-01-01T00:00:00.000Z t:county=Bond m:total_tested=219 m:45_mcg_dl=0 m:25_44_mcg_dl=2 m:1990_population_of_children_6_and_under=1431 m:10_14_mcg_dl=19 m:15_19_mcg_dl=8 m:20_24_mcg_dl=3
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

entity e:49a7-bxui l:"Childhood Lead Poisoning Surveillance Report By County, 1997" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/49a7-bxui

property e:49a7-bxui t:meta.view v:id=49a7-bxui v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 1997" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:49a7-bxui t:meta.view.license v:name="Public Domain"

property e:49a7-bxui t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:49a7-bxui t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1990_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6664                                    | 788          | 135          | 37           | 12           | 17           | 3         | 
| Alexander | 1166                                    | 279          | 41           | 18           | 2            | 5            | 0         | 
| Bond      | 1431                                    | 219          | 19           | 8            | 3            | 2            | 0         | 
| Boone     | 3344                                    | 266          | 9            | 7            | 2            | 3            | 0         | 
| Brown     | 465                                     | 47           | 4            | 4            | 2            | 3            | 0         | 
| Bureau    | 3516                                    | 273          | 18           | 7            | 1            | 2            | 0         | 
| Calhoun   | 544                                     | 106          | 8            | 0            | 0            | 1            | 0         | 
| Carroll   | 1522                                    | 128          | 19           | 1            | 3            | 2            | 0         | 
| Cass      | 1246                                    | 177          | 19           | 3            | 2            | 0            | 1         | 
| Champaign | 16730                                   | 1084         | 38           | 22           | 2            | 4            | 0         | 
```