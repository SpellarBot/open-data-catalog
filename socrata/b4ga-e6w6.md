# PS Summary Tables 11-29-2016-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ps-summary-tables-11-29-2016-2) |
| Metadata | [Link](https://data.wa.gov/api/views/b4ga-e6w6) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/b4ga-e6w6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/b4ga-e6w6/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | b4ga-e6w6 |
| Name | PS Summary Tables 11-29-2016-2 |
| Created | 2016-11-29T15:16:41Z |
| Publication Date | 2016-11-29T15:18:09Z |

## Description

Puget Sound AA summary table for 2016 SOS

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                  | Name                                                                                        | Data Type | Render Type |
| ======== | ============== | =========================================================================================== | =========================================================================================== | ========= | =========== |
| Yes      | series tag     | listed_salmon_populations_esus_or_dpss                                                      | Listed Salmon Populations (E S U or DPSs)                                                   | text      | text        |
| Yes      | numeric metric | number_of_populations_in_the_esus_dps                                                       | Number of Populations in the ESUs/DPS                                                       | number    | number      |
| Yes      | numeric metric | number_of_populations_with_abundance_recovery_goals_and_sufficient_data_to_assess_abundance | Number of Populations with Abundance Recovery Goals and Sufficient Data to Assess Abundance | number    | number      |
| Yes      | series tag     | percent_of_populations_above_abundance_recovery_goals                                       | Percent of Populations Above Abundance Recovery Goals                                       | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b4ga-e6w6 d:2016-01-01T00:00:00.000Z t:listed_salmon_populations_esus_or_dpss="Puget Sound Chinook Salmon" t:percent_of_populations_above_abundance_recovery_goals="0% (a)" m:number_of_populations_with_abundance_recovery_goals_and_sufficient_data_to_assess_abundance=16 m:number_of_populations_in_the_esus_dps=22

series e:b4ga-e6w6 d:2016-01-01T00:00:00.000Z t:listed_salmon_populations_esus_or_dpss="Puget Sound Steelhead" t:percent_of_populations_above_abundance_recovery_goals="No abundance goals (b)" m:number_of_populations_with_abundance_recovery_goals_and_sufficient_data_to_assess_abundance=0 m:number_of_populations_in_the_esus_dps=32
```

## Meta Commands

```ls
metric m:number_of_populations_in_the_esus_dps p:integer l:"Number of Populations in the ESUs/DPS" t:dataTypeName=number

metric m:number_of_populations_with_abundance_recovery_goals_and_sufficient_data_to_assess_abundance p:integer l:"Number of Populations with Abundance Recovery Goals and Sufficient Data to Assess Abundance" t:dataTypeName=number

entity e:b4ga-e6w6 l:"PS Summary Tables 11-29-2016-2" t:url=https://data.wa.gov/api/views/b4ga-e6w6

property e:b4ga-e6w6 t:meta.view v:id=b4ga-e6w6 v:averageRating=0 v:name="PS Summary Tables 11-29-2016-2"

property e:b4ga-e6w6 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:b4ga-e6w6 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| listed_salmon_populations_esus_or_dpss | number_of_populations_in_the_esus_dps | number_of_populations_with_abundance_recovery_goals_and_sufficient_data_to_assess_abundance | percent_of_populations_above_abundance_recovery_goals | 
| ====================================== | ===================================== | =========================================================================================== | ===================================================== | 
| Puget Sound Chinook Salmon             | 22                                    | 16                                                                                          | 0% (a)                                                | 
| Puget Sound Steelhead                  | 32                                    | 0                                                                                           | No abundance goals (b)                                | 
```