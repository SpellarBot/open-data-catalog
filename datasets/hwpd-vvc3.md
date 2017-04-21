# MC Summary Tables 11-29-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mc-summary-tables-11-29-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/hwpd-vvc3) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hwpd-vvc3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hwpd-vvc3/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hwpd-vvc3 |
| Name | MC Summary Tables 11-29-2016 |
| Created | 2016-11-29T15:13:27Z |
| Publication Date | 2016-11-29T18:48:53Z |

## Description

Middle Columbia AA summary table for 2016 SOS

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                 | Data Type | Render Type |
| ======== | ============== | ==================================================== | ==================================================== | ========= | =========== |
| Yes      | series tag     | fish                                                 | Fish                                                 | text      | text        |
| Yes      | numeric metric | number_of_populations                                | Number of Populations                                | number    | text        |
| Yes      | numeric metric | number_of_populations_with_sufficient_data           | Number of Populations with Sufficient Data           | number    | number      |
| Yes      | series tag     | percent_of_populations_above_abundance_recovery_goal | Percent of Populations Above Abundance Recovery Goal | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hwpd-vvc3 d:2016-01-01T00:00:00.000Z t:fish="Chinook Salmon" t:percent_of_populations_above_abundance_recovery_goal="Not listed" m:number_of_populations=7 m:number_of_populations_with_sufficient_data=7

series e:hwpd-vvc3 d:2016-01-01T00:00:00.000Z t:fish="Coho Salmon" t:percent_of_populations_above_abundance_recovery_goal="Not listed" m:number_of_populations=2 m:number_of_populations_with_sufficient_data=2

series e:hwpd-vvc3 d:2016-01-01T00:00:00.000Z t:fish="Mid-Columbia Steelhead" t:percent_of_populations_above_abundance_recovery_goal=50% m:number_of_populations=7 m:number_of_populations_with_sufficient_data=4
```

## Meta Commands

```ls
metric m:number_of_populations p:integer l:"Number of Populations" t:dataTypeName=number

metric m:number_of_populations_with_sufficient_data p:integer l:"Number of Populations with Sufficient Data" t:dataTypeName=number

entity e:hwpd-vvc3 l:"MC Summary Tables 11-29-2016" t:url=https://data.wa.gov/api/views/hwpd-vvc3

property e:hwpd-vvc3 t:meta.view v:id=hwpd-vvc3 v:averageRating=0 v:name="MC Summary Tables 11-29-2016"

property e:hwpd-vvc3 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:hwpd-vvc3 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| fish                   | number_of_populations | number_of_populations_with_sufficient_data | percent_of_populations_above_abundance_recovery_goal | 
| ====================== | ===================== | ========================================== | ==================================================== | 
| Chinook Salmon         | 7                     | 7                                          | Not listed                                           | 
| Coho Salmon            | 2                     | 2                                          | Not listed                                           | 
| Mid-Columbia Steelhead | 7                     | 4                                          | 50%                                                  | 
| Bull Trout             | 14                    | 12                                         | No goal set                                          | 
```