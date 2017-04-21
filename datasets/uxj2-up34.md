# Performance Metrics - Business Affairs & Consumer Protection - Retail Food Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-business-affairs-consumer-protection-retail-food-licenses-4ae67) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/uxj2-up34) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/uxj2-up34/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/uxj2-up34/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | uxj2-up34 |
| Name | Performance Metrics - Business Affairs & Consumer Protection - Retail Food Licenses |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, business, licenses |
| Created | 2011-09-21T22:21:09Z |
| Publication Date | 2011-10-19T18:54:20Z |

## Description

All restaurants and food stores selling perishable items are required to apply for a Retail Food License (RFL). This metric tracks the average number of days the Department of Business Affairs and Consumer Protection (BACP) takes to issue RFLs. The target response time for processing is within 15 days.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | week                          | Week                          | text      | text        |
| Yes      | numeric metric | total_licenses_issued         | Total Licenses Issued         | number    | number      |
| Yes      | numeric metric | average_days_to_issue_license | Average Days to Issue License | number    | number      |
| Yes      | numeric metric | median_days_to_issue_license  | Median Days to Issue License  | number    | number      |
| Yes      | numeric metric | target_days_to_issue_license  | Target Days to Issue License  | number    | number      |
| No       |                | quarter                       | Quarter                       | text      | text        |
| Yes      | numeric metric | weeks_target_was_achieved     | Weeks Target Was Achieved     | number    | number      |
| Yes      | numeric metric | weeks_target_was_not_achieved | Weeks Target Was Not Achieved | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Series Fields

```ls
Excluded Fields = quarter
```

## Data Commands

```ls
series e:uxj2-up34 d:2011-04-04T00:00:00.000Z m:median_days_to_issue_license=13 m:target_days_to_issue_license=15 m:weeks_target_was_not_achieved=0 m:average_days_to_issue_license=23.9 m:weeks_target_was_achieved=0 m:total_licenses_issued=22

series e:uxj2-up34 d:2011-04-11T00:00:00.000Z m:median_days_to_issue_license=26 m:target_days_to_issue_license=15 m:weeks_target_was_not_achieved=0 m:average_days_to_issue_license=72.5 m:weeks_target_was_achieved=0 m:total_licenses_issued=22

series e:uxj2-up34 d:2011-04-18T00:00:00.000Z m:median_days_to_issue_license=17 m:target_days_to_issue_license=15 m:weeks_target_was_not_achieved=0 m:average_days_to_issue_license=56 m:weeks_target_was_achieved=0 m:total_licenses_issued=34
```

## Meta Commands

```ls
metric m:total_licenses_issued p:integer l:"Total Licenses Issued" t:dataTypeName=number

metric m:average_days_to_issue_license p:float l:"Average Days to Issue License" t:dataTypeName=number

metric m:median_days_to_issue_license p:double l:"Median Days to Issue License" t:dataTypeName=number

metric m:target_days_to_issue_license p:integer l:"Target Days to Issue License" t:dataTypeName=number

metric m:weeks_target_was_achieved p:integer l:"Weeks Target Was Achieved" t:dataTypeName=number

metric m:weeks_target_was_not_achieved p:integer l:"Weeks Target Was Not Achieved" t:dataTypeName=number

entity e:uxj2-up34 l:"Performance Metrics - Business Affairs & Consumer Protection - Retail Food Licenses" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/uxj2-up34

property e:uxj2-up34 t:meta.view v:id=uxj2-up34 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Business Affairs & Consumer Protection - Retail Food Licenses" v:attribution="City of Chicago"

property e:uxj2-up34 t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:uxj2-up34 t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week                 | total_licenses_issued | average_days_to_issue_license | median_days_to_issue_license | target_days_to_issue_license | quarter | weeks_target_was_achieved | weeks_target_was_not_achieved | 
| ==================== | ===================== | ============================= | ============================ | ============================ | ======= | ========================= | ============================= | 
| Apr 4-10, 2011       | 22                    | 23.9                          | 13                           | 15                           | Q1 2011 | 0                         | 0                             | 
| Apr 11-17, 2011      | 22                    | 72.5                          | 26                           | 15                           | Q1 2011 | 0                         | 0                             | 
| Apr 18-24, 2011      | 34                    | 56                            | 17                           | 15                           | Q2 2011 | 0                         | 0                             | 
| Apr 25-30, 2011      | 25                    | 49.6                          | 23                           | 15                           | Q2 2011 | 0                         | 0                             | 
| May 2-8, 2011        | 34                    | 33.7                          | 13                           | 15                           | Q2 2011 | 0                         | 0                             | 
| May 9-15, 2011       | 30                    | 17.6                          | 12                           | 15                           | Q2 2011 | 0                         | 0                             | 
| May 16-22, 2011      | 22                    | 59.9                          | 18.5                         | 15                           | Q2 2011 | 0                         | 0                             | 
| May 23-29, 2011      | 39                    | 33.4                          | 18.5                         | 15                           | Q2 2011 | 0                         | 0                             | 
| May 30 - Jun 5, 2011 | 21                    | 45.3                          | 19                           | 15                           | Q2 2011 | 0                         | 0                             | 
| Jun 06-12, 2011      | 23                    | 52.3                          | 19                           | 15                           | Q2 2011 | 0                         | 0                             | 
```