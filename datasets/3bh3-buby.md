# Childhood Lead Poisoning Surveillance Report By County, 1996

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-lead-poisoning-surveillance-report-by-county-1996-5d660) |
| Metadata | [Link](https://data.illinois.gov/api/views/3bh3-buby) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3bh3-buby/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3bh3-buby/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3bh3-buby |
| Name | Childhood Lead Poisoning Surveillance Report By County, 1996 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health |
| Category | Health |
| Tags | health, lead, poisoning, surveillance, children, 1996, lead poisoning, environmental health |
| Created | 2014-08-11T17:55:35Z |
| Publication Date | 2014-08-11T17:56:25Z |

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
Value = 1996
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bh3-buby d:1996-01-01T00:00:00.000Z t:county=ADAMS m:total_tested=730 m:45_mcg_dl=0 m:base_population_of_children_6_and_under=6664 m:20_44_mcg_dl=28 m:15_19_mcg_dl=61

series e:3bh3-buby d:1996-01-01T00:00:00.000Z t:county=ALEXANDER m:total_tested=369 m:45_mcg_dl=1 m:base_population_of_children_6_and_under=1166 m:20_44_mcg_dl=16 m:15_19_mcg_dl=18

series e:3bh3-buby d:1996-01-01T00:00:00.000Z t:county=BOND m:total_tested=291 m:45_mcg_dl=0 m:base_population_of_children_6_and_under=1431 m:20_44_mcg_dl=5 m:15_19_mcg_dl=14
```

## Meta Commands

```ls
metric m:base_population_of_children_6_and_under p:integer l:"BASE POPULATION OF CHILDREN 6 AND UNDER" t:dataTypeName=number

metric m:total_tested p:integer l:"TOTAL TESTED" t:dataTypeName=number

metric m:15_19_mcg_dl p:integer l:"15-19 mcg/dL" t:dataTypeName=number

metric m:20_44_mcg_dl p:integer l:"20-44 mcg/dL" t:dataTypeName=number

metric m:45_mcg_dl p:integer l:"45 mcg/dL" t:dataTypeName=number

entity e:3bh3-buby l:"Childhood Lead Poisoning Surveillance Report By County, 1996" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/3bh3-buby

property e:3bh3-buby t:meta.view v:id=3bh3-buby v:category=Health v:averageRating=0 v:name="Childhood Lead Poisoning Surveillance Report By County, 1996" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Environmental Health"

property e:3bh3-buby t:meta.view.license v:name="Public Domain"

property e:3bh3-buby t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:3bh3-buby t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | base_population_of_children_6_and_under | total_tested | 15_19_mcg_dl | 20_44_mcg_dl | 45_mcg_dl | 
| ========= | ======================================= | ============ | ============ | ============ | ========= | 
| ADAMS     | 6664                                    | 730          | 61           | 28           | 0         | 
| ALEXANDER | 1166                                    | 369          | 18           | 16           | 1         | 
| BOND      | 1431                                    | 291          | 14           | 5            | 0         | 
| BOONE     | 3344                                    | 155          | 5            | 4            | 0         | 
| BROWN     | 465                                     | 66           | 2            | 2            | 0         | 
| BUREAU    | 3516                                    | 229          | 3            | 1            | 1         | 
| CALHOUN   | 544                                     | 119          | 4            | 1            | 0         | 
| CARROLL   | 1522                                    | 128          | 11           | 2            | 0         | 
| CASS      | 1246                                    | 152          | 4            | 3            | 0         | 
| CHAMPAIGN | 16730                                   | 1294         | 15           | 10           | 0         | 
```