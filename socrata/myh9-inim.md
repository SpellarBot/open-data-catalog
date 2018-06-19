# Performance Metrics - Ethics - Lobbyists Registrations and Activity Reports Received, Reviewed and Made Available for Public Inspection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-ethics-lobbyists-registrations-and-activity-reports-received-reviewed--d61e9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/myh9-inim) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/myh9-inim/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/myh9-inim/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | myh9-inim |
| Name | Performance Metrics - Ethics - Lobbyists Registrations and Activity Reports Received, Reviewed and Made Available for Public Inspection |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, ethics, lobbyists |
| Created | 2011-09-21T21:36:24Z |
| Publication Date | 2012-04-16T19:59:01Z |

## Description

Number Of Lobbyist Registrations And Activity Reports Received, Reviewed And Made Available For Public Inspection

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                         | Data Type | Render Type |
| ======== | ============== | ========================================================== | ============================================================ | ========= | =========== |
| Yes      | time           | week                                                       | Week                                                         | text      | text        |
| No       |                | registration_year                                          | Registration Year                                            | number    | text        |
| Yes      | numeric metric | number_of_lobbyist_registrations_and_activity_reports      | Number of lobbyist registrations and activity reports        | number    | number      |
| Yes      | numeric metric | total_number_of_registered_lobbyists_target_600_by_dec_31_ | Total Number of Registered Lobbyists (Target: 600 by Dec 31) | number    | number      |
| Yes      | numeric metric | total_fees_collected                                       | Total Fees Collected                                         | money     | money       |
| Yes      | series tag     | target_registration                                        | Target Registration                                          | text      | text        |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Series Fields

```ls
Excluded Fields = registration_year
```

## Data Commands

```ls
series e:myh9-inim d:2011-05-26T00:00:00.000Z t:target_registration="600 by Dec 31" m:total_number_of_registered_lobbyists_target_600_by_dec_31_=579 m:number_of_lobbyist_registrations_and_activity_reports=3

series e:myh9-inim d:2011-06-02T00:00:00.000Z t:target_registration="600 by Dec 31" m:total_number_of_registered_lobbyists_target_600_by_dec_31_=580 m:total_fees_collected=250425 m:number_of_lobbyist_registrations_and_activity_reports=1

series e:myh9-inim d:2011-06-09T00:00:00.000Z t:target_registration="600 by Dec 31" m:total_number_of_registered_lobbyists_target_600_by_dec_31_=581 m:total_fees_collected=255225 m:number_of_lobbyist_registrations_and_activity_reports=1
```

## Meta Commands

```ls
metric m:number_of_lobbyist_registrations_and_activity_reports p:integer l:"Number of lobbyist registrations and activity reports" t:dataTypeName=number

metric m:total_number_of_registered_lobbyists_target_600_by_dec_31_ p:integer l:"Total Number of Registered Lobbyists (Target: 600 by Dec 31)" t:dataTypeName=number

metric m:total_fees_collected p:double l:"Total Fees Collected" t:dataTypeName=money

entity e:myh9-inim l:"Performance Metrics - Ethics - Lobbyists Registrations and Activity Reports Received, Reviewed and Made Available for Public Inspection" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/myh9-inim

property e:myh9-inim t:meta.view v:id=myh9-inim v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Ethics - Lobbyists Registrations and Activity Reports Received, Reviewed and Made Available for Public Inspection" v:attribution="City of Chicago"

property e:myh9-inim t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:myh9-inim t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week                | registration_year | number_of_lobbyist_registrations_and_activity_reports | total_number_of_registered_lobbyists_target_600_by_dec_31_ | total_fees_collected | target_registration | 
| =================== | ================= | ===================================================== | ========================================================== | ==================== | =================== | 
| May 26-Jun 1, 2011  | 2011              | 3                                                     | 579                                                        |                      | 600 by Dec 31       | 
| Jun 2-8, 2011       | 2011              | 1                                                     | 580                                                        | 250425.00            | 600 by Dec 31       | 
| Jun 9-15, 2011      | 2011              | 1                                                     | 581                                                        | 255225.00            | 600 by Dec 31       | 
| Jun 16-22, 2011     | 2011              | 3                                                     | 584                                                        | 256025.00            | 600 by Dec 31       | 
| Jun 23-29, 2011     | 2011              | 2                                                     | 586                                                        | 256800.00            | 600 by Dec 31       | 
| Jun 30-Jul 6, 2011  | 2011              | 3                                                     | 589                                                        | 257950.00            | 600 by Dec 31       | 
| Jul 7-Jul 13, 2011  | 2011              | 13                                                    | 602                                                        | 263250.00            | 600 by Dec 31       | 
| Jul 14-Jul 20, 2011 | 2011              | 3                                                     | 604                                                        | 264000.00            | 600 by Dec 31       | 
| Jul 21-Jul 28, 2011 | 2011              | 5                                                     | 609                                                        | 264800.00            | 600 by Dec 31       | 
| Jul 29-Aug 3, 2011  | 2011              | 3                                                     | 612                                                        | 265750.00            | 600 by Dec 31       | 
```