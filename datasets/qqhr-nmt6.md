# Childhood Lead Poisoning Surveillance Report By County, 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-2006-e2aca) |
| Metadata | [Link](https://data.illinois.gov/api/views/qqhr-nmt6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qqhr-nmt6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qqhr-nmt6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qqhr-nmt6 |
| Name | Childhood Lead Poisoning Surveillance Report By County, 2006 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 2006, lead poisoning, environmental health |
| Created | 2014-08-11T18:13:33Z |
| Publication Date | 2014-08-11T18:14:25Z |

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
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qqhr-nmt6 d:2006-01-01T00:00:00.000Z t:county=Adams m:total_tested=959 m:2000_population_of_children_6_and_under=5652 m:45_mcg_dl=0 m:25_44_mcg_dl=1 m:10_14_mcg_dl=22 m:15_19_mcg_dl=9 m:20_24_mcg_dl=2

series e:qqhr-nmt6 d:2006-01-01T00:00:00.000Z t:county=Alexander m:total_tested=190 m:2000_population_of_children_6_and_under=889 m:45_mcg_dl=0 m:25_44_mcg_dl=1 m:10_14_mcg_dl=4 m:15_19_mcg_dl=0 m:20_24_mcg_dl=0

series e:qqhr-nmt6 d:2006-01-01T00:00:00.000Z t:county=Bond m:total_tested=292 m:2000_population_of_children_6_and_under=1425 m:45_mcg_dl=0 m:25_44_mcg_dl=1 m:10_14_mcg_dl=4 m:15_19_mcg_dl=0 m:20_24_mcg_dl=1
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

entity e:qqhr-nmt6 l:"Childhood Lead Poisoning Surveillance Report By County, 2006" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/qqhr-nmt6

property e:qqhr-nmt6 t:meta.view v:id=qqhr-nmt6 v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 2006" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:qqhr-nmt6 t:meta.view.license v:name="Public Domain"

property e:qqhr-nmt6 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:qqhr-nmt6 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000_population_of_children_6_and_under | total_tested | 10_14_mcg_dl | 15_19_mcg_dl | 20_24_mcg_dl | 25_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ============ | ============ | ========= | 
| Adams     | 5652                                    | 959          | 22           | 9            | 2            | 1            | 0         | 
| Alexander | 889                                     | 190          | 4            | 0            | 0            | 1            | 0         | 
| Bond      | 1425                                    | 292          | 4            | 0            | 1            | 1            | 0         | 
| Boone     | 4735                                    | 735          | 17           | 3            | 0            | 4            | 0         | 
| Brown     | 410                                     | 75           | 1            | 0            | 0            | 0            | 0         | 
| Bureau    | 3015                                    | 352          | 8            | 1            | 0            | 1            | 0         | 
| Calhoun   | 373                                     | 80           | 0            | 0            | 0            | 0            | 0         | 
| Carroll   | 1159                                    | 306          | 6            | 5            | 1            | 0            | 0         | 
| Cass      | 1376                                    | 346          | 10           | 7            | 2            | 1            | 0         | 
| Champaign | 15229                                   | 1880         | 35           | 4            | 0            | 2            | 1         | 
```