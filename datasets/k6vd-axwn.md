# 2013 Proposed Budget, Revenue By Fund And Account

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-revenue-by-fund-and-account-c934c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/k6vd-axwn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/k6vd-axwn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/k6vd-axwn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | k6vd-axwn |
| Name | 2013 Proposed Budget, Revenue By Fund And Account |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-23T02:32:40Z |
| Publication Date | 2012-09-23T02:45:40Z |

## Description

King County budget proposed September 2012 by Executive for 2013, Revenue By Fund and Account. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                               | Data Type | Render Type |
| ======== | ============== | ================================= | ================================== | ========= | =========== |
| Yes      | series tag     | fund                              | Fund                               | text      | text        |
| Yes      | series tag     | fund_name                         | Fund Name                          | text      | text        |
| Yes      | numeric metric | taxes_r3100                       | Taxes (R3100)                      | money     | money       |
| Yes      | numeric metric | licenses_and_permits_r3200        | Licenses And Permits (R3200)       | money     | money       |
| Yes      | numeric metric | intergovern_mental_payments_r3300 | Intergovernmental Payments (R3300) | money     | money       |
| Yes      | numeric metric | charge_for_services_r3400         | Charge For Services (R3400)        | money     | money       |
| Yes      | numeric metric | fines_and_forfeits_r3500          | Fines And Forfeits (R3500)         | money     | money       |
| Yes      | numeric metric | budgeted_fund_balance_r3080       | Budgeted Fund Balance (R3080)      | money     | money       |
| Yes      | numeric metric | miscellaneous_revenue_r3600       | Miscellaneous Revenue (R3600)      | money     | money       |
| Yes      | numeric metric | non_revenue_receipts_r3800        | Non Revenue Receipts (R3800)       | money     | money       |
| Yes      | numeric metric | other_financing_sources_r3900     | Other Financing Sources (R3900)    | money     | money       |
| Yes      | numeric metric | total_revenues                    | Total Revenues                     | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k6vd-axwn d:2013-01-01T00:00:00.000Z t:fund_name="General Fund" t:fund=000000010 m:taxes_r3100=428366863 m:charge_for_services_r3400=118033395 m:other_financing_sources_r3900=345000 m:intergovern_mental_payments_r3300=99087418 m:fines_and_forfeits_r3500=8577719 m:miscellaneous_revenue_r3600=17382944 m:total_revenues=675635747 m:licenses_and_permits_r3200=3842408

series e:k6vd-axwn d:2013-01-01T00:00:00.000Z t:fund_name="Inmate Welfare Fund" t:fund=000000016 m:charge_for_services_r3400=1018266 m:miscellaneous_revenue_r3600=1000 m:total_revenues=1019266

series e:k6vd-axwn d:2013-01-01T00:00:00.000Z t:fund_name="County Road Fund" t:fund=000001030 m:taxes_r3100=64657526 m:charge_for_services_r3400=2132329 m:other_financing_sources_r3900=333203 m:intergovern_mental_payments_r3300=28837169 m:fines_and_forfeits_r3500=11000 m:miscellaneous_revenue_r3600=473313 m:total_revenues=96444540
```

## Meta Commands

```ls
metric m:taxes_r3100 p:integer l:"Taxes (R3100)" t:dataTypeName=money

metric m:licenses_and_permits_r3200 p:integer l:"Licenses And Permits (R3200)" t:dataTypeName=money

metric m:intergovern_mental_payments_r3300 p:integer l:"Intergovernmental Payments (R3300)" t:dataTypeName=money

metric m:charge_for_services_r3400 p:integer l:"Charge For Services (R3400)" t:dataTypeName=money

metric m:fines_and_forfeits_r3500 p:integer l:"Fines And Forfeits (R3500)" t:dataTypeName=money

metric m:budgeted_fund_balance_r3080 p:double l:"Budgeted Fund Balance (R3080)" t:dataTypeName=money

metric m:miscellaneous_revenue_r3600 p:integer l:"Miscellaneous Revenue (R3600)" t:dataTypeName=money

metric m:non_revenue_receipts_r3800 p:double l:"Non Revenue Receipts (R3800)" t:dataTypeName=money

metric m:other_financing_sources_r3900 p:integer l:"Other Financing Sources (R3900)" t:dataTypeName=money

metric m:total_revenues p:integer l:"Total Revenues" t:dataTypeName=money

entity e:k6vd-axwn l:"2013 Proposed Budget, Revenue By Fund And Account" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/k6vd-axwn

property e:k6vd-axwn t:meta.view v:id=k6vd-axwn v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, Revenue By Fund And Account" v:attribution="King County Executive"

property e:k6vd-axwn t:meta.view.license v:name="Public Domain"

property e:k6vd-axwn t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:k6vd-axwn t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| fund      | fund_name                | taxes_r3100 | licenses_and_permits_r3200 | intergovern_mental_payments_r3300 | charge_for_services_r3400 | fines_and_forfeits_r3500 | budgeted_fund_balance_r3080 | miscellaneous_revenue_r3600 | non_revenue_receipts_r3800 | other_financing_sources_r3900 | total_revenues | 
| ========= | ======================== | =========== | ========================== | ================================= | ========================= | ======================== | =========================== | =========================== | ========================== | ============================= | ============== | 
| 000000010 | General Fund             | 428366863   | 3842408                    | 99087418                          | 118033395                 | 8577719                  |                             | 17382944                    |                            | 345000                        | 675635747      | 
| 000000016 | Inmate Welfare Fund      |             |                            |                                   | 1018266                   |                          |                             | 1000                        |                            |                               | 1019266        | 
| 000001030 | County Road Fund         | 64657526    |                            | 28837169                          | 2132329                   | 11000                    |                             | 473313                      |                            | 333203                        | 96444540       | 
| 000001040 | Sw Post Closure Lf Maint |             |                            |                                   |                           |                          |                             | 47614                       |                            |                               | 47614          | 
| 000001060 | Veterans Relief          | 2648529     |                            |                                   | 196848                    |                          |                             | 2100                        |                            |                               | 2847477        | 
| 000001070 | Developmental Disability | 2972018     |                            | 2591312                           | 24555542                  |                          |                             |                             |                            | 102809                        | 30221681       | 
| 000001090 | Recorder's O & M Fund    |             |                            | 515257                            | 983462                    |                          |                             | 4172                        |                            |                               | 1502891        | 
| 000001110 | Emergency Telephone E911 | 23920865    |                            | 43000                             | 724750                    |                          |                             | 71763                       |                            |                               | 24760378       | 
| 000001120 | Mental Health            | 2972018     |                            | 162772763                         | 3451217                   |                          |                             | 1360900                     |                            |                               | 170556898      | 
| 000001135 | MIDD                     | 46110659    |                            |                                   |                           |                          |                             | 56168                       |                            |                               | 46166827       | 
```