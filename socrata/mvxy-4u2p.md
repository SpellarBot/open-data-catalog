# UC Summary Tables 11-29-2016-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/uc-summary-tables-11-29-2016-2) |
| Metadata | [Link](https://data.wa.gov/api/views/mvxy-4u2p) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mvxy-4u2p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mvxy-4u2p/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mvxy-4u2p |
| Name | UC Summary Tables 11-29-2016-2 |
| Created | 2016-11-29T15:21:20Z |
| Publication Date | 2016-11-29T15:22:22Z |

## Description

Upper Columbia AA summary table for 2016 SOS

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | fish                                       | Fish                                       | text      | text        |
| Yes      | numeric metric | number_of_populations_with_sufficient_data | Number of Populations with Sufficient Data | number    | number      |
| Yes      | series tag     | above_recovery_goal                        | Above Recovery Goal                        | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mvxy-4u2p d:2016-01-01T00:00:00.000Z t:fish="Spring Chinook Salmon" t:above_recovery_goal="0 percent" m:number_of_populations_with_sufficient_data=3

series e:mvxy-4u2p d:2016-01-01T00:00:00.000Z t:fish="Summer Steelhead" t:above_recovery_goal="0 percent" m:number_of_populations_with_sufficient_data=4

series e:mvxy-4u2p d:2016-01-01T00:00:00.000Z t:fish="Bull Trout" t:above_recovery_goal="No goal set" m:number_of_populations_with_sufficient_data=0
```

## Meta Commands

```ls
metric m:number_of_populations_with_sufficient_data p:integer l:"Number of Populations with Sufficient Data" t:dataTypeName=number

entity e:mvxy-4u2p l:"UC Summary Tables 11-29-2016-2" t:url=https://data.wa.gov/api/views/mvxy-4u2p

property e:mvxy-4u2p t:meta.view v:id=mvxy-4u2p v:averageRating=0 v:name="UC Summary Tables 11-29-2016-2"

property e:mvxy-4u2p t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:mvxy-4u2p t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| fish                  | number_of_populations_with_sufficient_data | above_recovery_goal | 
| ===================== | ========================================== | =================== | 
| Spring Chinook Salmon | 3                                          | 0 percent           | 
| Summer Steelhead      | 4                                          | 0 percent           | 
| Bull Trout            | 0                                          | No goal set         | 
```