# Map Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/map-data-502c2) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/3xee-dwpd) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/3xee-dwpd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/3xee-dwpd/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 3xee-dwpd |
| Name | Map Data |
| Created | 2013-10-31T20:05:41Z |
| Publication Date | 2017-03-31T22:36:09Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | name              | Name              | text      | text        |
| Yes      | series tag  | category          | Category          | text      | text        |
| Yes      | series tag  | description       | Description       | text      | text        |
| Yes      | series tag  | data_type         | Data Type         | text      | text        |
| Yes      | series tag  | link              | Link              | url       | url         |
| Yes      | series tag  | map_icon          | Map Icon          | photo     | photo       |
| Yes      | series tag  | hide_from_sidebar | Hide from sidebar | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3xee-dwpd d:2014-02-03T12:20:09.000Z t:category=Health t:data_type=Map t:description="Public health centers for Seattle, Kent, Auburn, Federal Way, Northshore, Eastgate." t:link=https://data.kingcounty.gov/Health/Public-Health-Clinics-map/d8a2-jkmg t:name="Public Health Centers" m:row_number.3xee-dwpd=1

series e:3xee-dwpd d:2014-03-03T16:38:12.000Z t:category=Money/Finance t:data_type="Raw Data" t:description="Biennial budgets, 2013-2014" t:link=https://data.kingcounty.gov/Budget/2013-2014-Budgets-biennial-only-table/mvnk-3qt2 t:name="King County biennial budgets" m:row_number.3xee-dwpd=2

series e:3xee-dwpd d:2014-03-03T16:38:43.000Z t:category=Money/Finance t:data_type="Raw Data" t:description="Fiscal Year 2013-2014" t:link=https://data.kingcounty.gov/Budget/Sub-fund-for-FY13-and-FY14/x2mq-w24x t:name="Capital Improvements budget by sub-fund," m:row_number.3xee-dwpd=3
```

## Meta Commands

```ls
metric m:row_number.3xee-dwpd p:long l:"Row Number"

entity e:3xee-dwpd l:"Map Data" t:url=https://data.kingcounty.gov/api/views/3xee-dwpd

property e:3xee-dwpd t:meta.view v:id=3xee-dwpd v:averageRating=0 v:name="Map Data"

property e:3xee-dwpd t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:3xee-dwpd t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | name                                                           | category              | description                                                                         | data_type | link                                                                                                            | map_icon                                    | hide_from_sidebar | 
| =========== | ============================================================== | ===================== | =================================================================================== | ========= | =============================================================================================================== | =========================================== | ================= | 
| 1391430009  | Public Health Centers                                          | Health                | Public health centers for Seattle, Kent, Auburn, Federal Way, Northshore, Eastgate. | Map       | [https://data.kingcounty.gov/Health/Public-Health-Clinics-map/d8a2-jkmg, null]                                  |                                             |                   | 
| 1393864692  | King County biennial budgets                                   | Money/Finance         | Biennial budgets, 2013-2014                                                         | Raw Data  | [https://data.kingcounty.gov/Budget/2013-2014-Budgets-biennial-only-table/mvnk-3qt2, null]                      |                                             |                   | 
| 1393864723  | Capital Improvements budget by sub-fund,                       | Money/Finance         | Fiscal Year 2013-2014                                                               | Raw Data  | [https://data.kingcounty.gov/Budget/Sub-fund-for-FY13-and-FY14/x2mq-w24x, null]                                 |                                             |                   | 
| 1393865127  | Law enforcement call response times                            | Law, Safety & Justice |                                                                                     | Raw Data  | [https://data.kingcounty.gov/Public-Safety/Law-enforcement-call-response-times/rr7t-2iaj, null]                 |                                             |                   | 
| 1393866214  | Jail bookings                                                  | Law, Safety & Justice | Search the jail rosters                                                             | Raw Data  | [https://data.kingcounty.gov/Jail/Adult-Jail-Booking-Nov-1-2012-to-Oct-31-2013-as-of/j56h-zgnm, null]           |                                             |                   | 
| 1393866233  | Critical 911 call response times                               | Law, Safety & Justice | Countywide response times for 911 calls                                             | Chart     | [https://data.kingcounty.gov/Public-Safety/Critical-law-enforcement-calls-response-time/yqdr-edy8, null]        |                                             |                   | 
| 1393866280  | Food establishment inspection data                             | Health                | Restaurant health inspection results                                                | Raw Data  | [https://data.kingcounty.gov/dataset/Food-Establishment-Inspection-Data/f29f-zza5, null]                        |                                             |                   | 
| 1393866371  | Youth marijuana use                                            | Health                | Breakdown by age, gender, region, and race                                          | Chart     | [https://data.kingcounty.gov/Health/Youth-Marijuana-Data/fpi6-c9pt, null]                                       |                                             |                   | 
| 1393866440  | West Seattle Water Taxi ridership averages, each run, each day | Transportation        | Ridership for each sailing of the West Seattle Water Taxi                           | Chart     | [https://data.kingcounty.gov/Transportation/West-Seattle-ridership-averages-each-run-each-day-/jpjv-tw88, null] | sASWBbvNdZe5ir67eBadE1DTcwysd_NE_PXWux97JwA |                   | 
| 1393866468  | West Seattle Water Taxi ridership                              | Transportation        | Overall Water Taxi ridership numbers, West Seattle                                  | Chart     | [https://data.kingcounty.gov/Transportation/West-Seattle-ridership-2012-compared-to-2011-chart/rc3x-bdim, null] | sASWBbvNdZe5ir67eBadE1DTcwysd_NE_PXWux97JwA |                   | 
```