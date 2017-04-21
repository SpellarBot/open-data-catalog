# Childhood Lead Poisoning Surveillance Report By County, 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-2000-56cb6) |
| Metadata | [Link](https://data.illinois.gov/api/views/2gd6-gdgp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2gd6-gdgp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2gd6-gdgp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2gd6-gdgp |
| Name | Childhood Lead Poisoning Surveillance Report By County, 2000 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 2000, lead poisoning, environmental health |
| Created | 2014-08-11T18:05:24Z |
| Publication Date | 2014-08-11T18:06:21Z |

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
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2gd6-gdgp d:2000-01-01T00:00:00.000Z t:county=Adams m:total_tested=566 m:45_mcg_dl=0 m:25_44_mcg_dl=5 m:1990_population_of_children_6_and_under=6664 m:10_14_mcg_dl=54 m:15_19_mcg_dl=9 m:20_24_mcg_dl=4

series e:2gd6-gdgp d:2000-01-01T00:00:00.000Z t:county=Alexander m:total_tested=130 m:45_mcg_dl=0 m:25_44_mcg_dl=0 m:1990_population_of_children_6_and_under=1166 m:10_14_mcg_dl=13 m:15_19_mcg_dl=5 m:20_24_mcg_dl=2

series e:2gd6-gdgp d:2000-01-01T00:00:00.000Z t:county=Bond m:total_tested=307 m:45_mcg_dl=0 m:25_44_mcg_dl=1 m:1990_population_of_children_6_and_under=1431 m:10_14_mcg_dl=18 m:15_19_mcg_dl=6 m:20_24_mcg_dl=2
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

entity e:2gd6-gdgp l:"Childhood Lead Poisoning Surveillance Report By County, 2000" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/2gd6-gdgp

property e:2gd6-gdgp t:meta.view v:id=2gd6-gdgp v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 2000" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:2gd6-gdgp t:meta.view.license v:name="Public Domain"

property e:2gd6-gdgp t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:2gd6-gdgp t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1990_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 6664                                    | 566          | 54           | 9            | 4            | 5            | 0         | 
| Alexander | 1166                                    | 130          | 13           | 5            | 2            | 0            | 0         | 
| Bond      | 1431                                    | 307          | 18           | 6            | 2            | 1            | 0         | 
| Boone     | 3344                                    | 286          | 10           | 5            | 2            | 0            | 0         | 
| Brown     | 465                                     | 22           | 2            | 2            | 0            | 0            | 0         | 
| Bureau    | 3516                                    | 359          | 3            | 10           | 0            | 2            | 0         | 
| Calhoun   | 544                                     | 34           | 4            | 1            | 1            | 0            | 0         | 
| Carroll   | 1522                                    | 239          | 10           | 4            | 2            | 0            | 0         | 
| Cass      | 1246                                    | 123          | 5            | 3            | 0            | 2            | 0         | 
| Champaign | 16730                                   | 1567         | 45           | 6            | 2            | 1            | 2         | 
```