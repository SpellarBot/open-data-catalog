# Childhood Lead Poisoning Surveillance Report By County, 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-2002-bf4ba) |
| Metadata | [Link](https://data.illinois.gov/api/views/263f-wyus) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/263f-wyus/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/263f-wyus/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 263f-wyus |
| Name | Childhood Lead Poisoning Surveillance Report By County, 2002 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 2002, lead poisoning, environmental health |
| Created | 2014-08-11T18:07:59Z |
| Publication Date | 2014-08-11T18:08:49Z |

## Description

In 1993, state-mandated screening for childhood lead poisoning in children 6 years of age and younger began. Physicians and other health care providers have conducted 2.4 million lead tests and reported about 270,000 children with elevated lead levels. The numbers of elevated and normal test results are used to identify areas where effort is needed to combat lead poisoning.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | county                                  | County                                  | text      | text        |
| Yes      | numeric metric | 2000_population_of_children_6_and_under | 2000 Population of Children 6 and Under | number    | number      |
| Yes      | numeric metric | total_tested                            | Total Tested                            | number    | number      |
| Yes      | numeric metric | 10_14_mcg_dl                            | 10-14 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 15_19_mcg_dl                            | 15-19 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 20_24_mcg_dl                            | 20-24 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 25_44_mcg_dl                            | 25-44 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 45_mcg_dl                               | 45+ mcg/dL                              | number    | number      |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:263f-wyus d:2002-01-01T00:00:00.000Z t:county=Adams m:total_tested=502 m:2000_population_of_children_6_and_under=6006 m:45_mcg_dl=0 m:25_44_mcg_dl=5 m:10_14_mcg_dl=27 m:15_19_mcg_dl=12 m:20_24_mcg_dl=5

series e:263f-wyus d:2002-01-01T00:00:00.000Z t:county=Alexander m:total_tested=141 m:2000_population_of_children_6_and_under=846 m:45_mcg_dl=0 m:25_44_mcg_dl=1 m:10_14_mcg_dl=16 m:15_19_mcg_dl=2 m:20_24_mcg_dl=2

series e:263f-wyus d:2002-01-01T00:00:00.000Z t:county=Bond m:total_tested=267 m:2000_population_of_children_6_and_under=1411 m:45_mcg_dl=0 m:25_44_mcg_dl=0 m:10_14_mcg_dl=7 m:15_19_mcg_dl=0 m:20_24_mcg_dl=0
```

## Meta Commands

```ls
metric m:2000_population_of_children_6_and_under p:integer l:"2000 Population of Children 6 and Under" t:dataTypeName=number

metric m:total_tested p:integer l:"Total Tested" t:dataTypeName=number

metric m:10_14_mcg_dl p:integer l:"10-14 mcg/dL" t:dataTypeName=number

metric m:15_19_mcg_dl p:integer l:"15-19 mcg/dL" t:dataTypeName=number

metric m:20_24_mcg_dl p:integer l:"20-24 mcg/dL" t:dataTypeName=number

metric m:25_44_mcg_dl p:integer l:"25-44 mcg/dL" t:dataTypeName=number

metric m:45_mcg_dl p:integer l:"45+ mcg/dL" t:dataTypeName=number

entity e:263f-wyus l:"Childhood Lead Poisoning Surveillance Report By County, 2002" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/263f-wyus

property e:263f-wyus t:meta.view v:id=263f-wyus v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 2002" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:263f-wyus t:meta.view.license v:name="Public Domain"

property e:263f-wyus t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:263f-wyus t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6006                                    | 502          | 27           | 12           | 5            | 5            | 0         | 
| Alexander | 846                                     | 141          | 16           | 2            | 2            | 1            | 0         | 
| Bond      | 1411                                    | 267          | 7            | 0            | 0            | 0            | 0         | 
| Boone     | 4569                                    | 411          | 12           | 7            | 1            | 0            | 0         | 
| Brown     | 398                                     | 18           | 0            | 0            | 0            | 0            | 0         | 
| Bureau    | 3022                                    | 419          | 13           | 3            | 2            | 0            | 0         | 
| Calhoun   | 386                                     | 64           | 2            | 0            | 1            | 0            | 0         | 
| Carroll   | 1331                                    | 280          | 10           | 4            | 2            | 0            | 1         | 
| Cass      | 1293                                    | 268          | 16           | 5            | 2            | 2            | 0         | 
| Champaign | 14575                                   | 1631         | 33           | 10           | 6            | 2            | 0         | 
```