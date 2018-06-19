# Childhood Lead Poisoning Surveillance Report By County, 1993

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-1993-548e4) |
| Metadata | [Link](https://data.illinois.gov/api/views/uv4i-3vjj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/uv4i-3vjj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/uv4i-3vjj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | uv4i-3vjj |
| Name | Childhood Lead Poisoning Surveillance Report By County, 1993 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 1993, lead poisoning |
| Created | 2014-08-08T15:34:03Z |
| Publication Date | 2014-08-08T15:39:06Z |

## Description

In 1993, state-mandated screening for childhood lead poisoning in children 6 years of age and younger began. Physicians and other health care providers have conducted 2.4 million lead tests and reported about 270,000 children with elevated lead levels. The numbers of elevated and normal test results are used to identify areas where effort is needed to combat lead poisoning.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | county                                  | County                                  | text      | text        |
| Yes      | numeric metric | base_population_of_children_6_and_under | BASE POPULATION OF CHILDREN 6 AND UNDER | number    | number      |
| Yes      | numeric metric | total_tested                            | TOTAL TESTED                            | number    | number      |
| Yes      | numeric metric | 15_19_mcg_dl                            | 15-19 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 20_44_mcg_dl                            | 20-44 mcg/dL                            | number    | number      |
| Yes      | numeric metric | 45_mcg_dl                               | 45 mcg/dL                               | number    | number      |
```

## Time Field

```ls
Value = 1993
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uv4i-3vjj d:1993-01-01T00:00:00.000Z t:county=ADAMS m:total_tested=1069 m:45_mcg_dl=1 m:base_population_of_children_6_and_under=6664 m:20_44_mcg_dl=28 m:15_19_mcg_dl=27

series e:uv4i-3vjj d:1993-01-01T00:00:00.000Z t:county=ALEXANDER m:total_tested=263 m:45_mcg_dl=0 m:base_population_of_children_6_and_under=1166 m:20_44_mcg_dl=2 m:15_19_mcg_dl=5

series e:uv4i-3vjj d:1993-01-01T00:00:00.000Z t:county=BOND m:total_tested=74 m:45_mcg_dl=1 m:base_population_of_children_6_and_under=1431 m:20_44_mcg_dl=1 m:15_19_mcg_dl=0
```

## Meta Commands

```ls
metric m:base_population_of_children_6_and_under p:integer l:"BASE POPULATION OF CHILDREN 6 AND UNDER" t:dataTypeName=number

metric m:total_tested p:integer l:"TOTAL TESTED" t:dataTypeName=number

metric m:15_19_mcg_dl p:integer l:"15-19 mcg/dL" t:dataTypeName=number

metric m:20_44_mcg_dl p:integer l:"20-44 mcg/dL" t:dataTypeName=number

metric m:45_mcg_dl p:integer l:"45 mcg/dL" t:dataTypeName=number

entity e:uv4i-3vjj l:"Childhood Lead Poisoning Surveillance Report By County, 1993" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/uv4i-3vjj

property e:uv4i-3vjj t:meta.view v:id=uv4i-3vjj v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 1993" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:uv4i-3vjj t:meta.view.license v:name="Public Domain"

property e:uv4i-3vjj t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:uv4i-3vjj t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | base_population_of_children_6_and_under | total_tested | 15_19_mcg_dl | 20_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ========= | 
| ADAMS     | 6664                                    | 1069         | 27           | 28           | 1         | 
| ALEXANDER | 1166                                    | 263          | 5            | 2            | 0         | 
| BOND      | 1431                                    | 74           | 0            | 1            | 1         | 
| BOONE     | 3344                                    | 151          | 3            | 5            | 0         | 
| BROWN     | 465                                     | 51           | 2            | 0            | 0         | 
| BUREAU    | 3516                                    | 370          | 3            | 8            | 0         | 
| CALHOUN   | 544                                     | 234          | 4            | 2            | 1         | 
| CARROLL   | 1522                                    | 289          | 1            | 0            | 1         | 
| CASS      | 1246                                    | 220          | 3            | 4            | 2         | 
| CHAMPAIGN | 16730                                   | 1263         | 11           | 6            | 0         | 
```