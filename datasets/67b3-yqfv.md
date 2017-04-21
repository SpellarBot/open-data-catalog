# S Summary Tables 11-29-2016-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/s-summary-tables-11-29-2016-2) |
| Metadata | [Link](https://data.wa.gov/api/views/67b3-yqfv) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/67b3-yqfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/67b3-yqfv/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 67b3-yqfv |
| Name | S Summary Tables 11-29-2016-2 |
| Created | 2016-11-29T15:19:13Z |
| Publication Date | 2016-12-05T21:12:40Z |

## Description

Snake AA summary table for 2016 SOS

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
series e:67b3-yqfv d:2016-01-01T00:00:00.000Z t:fish="Spring Chinook Salmon" t:above_recovery_goal="0 percent" m:number_of_populations_with_sufficient_data=1

series e:67b3-yqfv d:2016-01-01T00:00:00.000Z t:fish="Fall Chinook Salmon" t:above_recovery_goal="Yes but no final goal set" m:number_of_populations_with_sufficient_data=1

series e:67b3-yqfv d:2016-01-01T00:00:00.000Z t:fish="Summer Steelhead" t:above_recovery_goal="33 percent" m:number_of_populations_with_sufficient_data=3
```

## Meta Commands

```ls
metric m:number_of_populations_with_sufficient_data p:integer l:"Number of Populations with Sufficient Data" t:dataTypeName=number

entity e:67b3-yqfv l:"S Summary Tables 11-29-2016-2" t:url=https://data.wa.gov/api/views/67b3-yqfv

property e:67b3-yqfv t:meta.view v:id=67b3-yqfv v:averageRating=0 v:name="S Summary Tables 11-29-2016-2"

property e:67b3-yqfv t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:67b3-yqfv t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| fish                  | number_of_populations_with_sufficient_data | above_recovery_goal       | 
| ===================== | ========================================== | ========================= | 
| Spring Chinook Salmon | 1                                          | 0 percent                 | 
| Fall Chinook Salmon   | 1                                          | Yes but no final goal set | 
| Summer Steelhead      | 3                                          | 33 percent                | 
| Bull Trout            | 0                                          | No goal set               | 
```