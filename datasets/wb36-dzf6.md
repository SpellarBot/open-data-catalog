# Childhood Lead Poisoning Surveillance Report By County, 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-2003-2f7b3) |
| Metadata | [Link](https://data.illinois.gov/api/views/wb36-dzf6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wb36-dzf6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wb36-dzf6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wb36-dzf6 |
| Name | Childhood Lead Poisoning Surveillance Report By County, 2003 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 2003, lead poisoning, environmental health |
| Created | 2014-08-11T18:09:08Z |
| Publication Date | 2014-08-11T18:09:57Z |

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
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wb36-dzf6 d:2003-01-01T00:00:00.000Z t:county=Adams m:total_tested=545 m:2000_population_of_children_6_and_under=6006 m:45_mcg_dl=1 m:25_44_mcg_dl=3 m:10_14_mcg_dl=34 m:15_19_mcg_dl=11 m:20_24_mcg_dl=6

series e:wb36-dzf6 d:2003-01-01T00:00:00.000Z t:county=Alexander m:total_tested=110 m:2000_population_of_children_6_and_under=846 m:45_mcg_dl=0 m:25_44_mcg_dl=0 m:10_14_mcg_dl=10 m:15_19_mcg_dl=3 m:20_24_mcg_dl=1

series e:wb36-dzf6 d:2003-01-01T00:00:00.000Z t:county=Bond m:total_tested=262 m:2000_population_of_children_6_and_under=1411 m:45_mcg_dl=0 m:25_44_mcg_dl=0 m:10_14_mcg_dl=5 m:15_19_mcg_dl=2 m:20_24_mcg_dl=0
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

entity e:wb36-dzf6 l:"Childhood Lead Poisoning Surveillance Report By County, 2003" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/wb36-dzf6

property e:wb36-dzf6 t:meta.view v:id=wb36-dzf6 v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 2003" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:wb36-dzf6 t:meta.view.license v:name="Public Domain"

property e:wb36-dzf6 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:wb36-dzf6 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6006                                    | 545          | 34           | 11           | 6            | 3            | 1         | 
| Alexander | 846                                     | 110          | 10           | 3            | 1            | 0            | 0         | 
| Bond      | 1411                                    | 262          | 5            | 2            | 0            | 0            | 0         | 
| Boone     | 4569                                    | 497          | 11           | 3            | 1            | 1            | 1         | 
| Brown     | 398                                     | 40           | 1            | 1            | 0            | 0            | 0         | 
| Bureau    | 3022                                    | 412          | 7            | 6            | 0            | 0            | 0         | 
| Calhoun   | 386                                     | 87           | 5            | 0            | 1            | 0            | 0         | 
| Carroll   | 1331                                    | 270          | 6            | 2            | 1            | 4            | 1         | 
| Cass      | 1293                                    | 267          | 11           | 6            | 0            | 2            | 0         | 
| Champaign | 14575                                   | 1626         | 38           | 14           | 2            | 2            | 0         | 
```