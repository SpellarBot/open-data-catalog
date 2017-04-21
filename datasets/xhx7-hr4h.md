# Port of Los Angeles - Single Audit Report 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-la-single-audit-report-40433) |
| Metadata | [Link](https://data.lacity.org/api/views/xhx7-hr4h) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/xhx7-hr4h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/xhx7-hr4h/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | xhx7-hr4h |
| Name | Port of Los Angeles - Single Audit Report 2013 |
| Attribution | Port of Los Angeles |
| Category | A Well Run City |
| Tags | single audit, federal, port, pola |
| Created | 2014-05-16T17:19:47Z |
| Publication Date | 2014-05-19T21:05:34Z |

## Description

Port of Los Angeles - Single Audit report details (Federal grant usage). Published historical data.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                        | Data Type | Render Type |
| ======== | ============== | ========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | grant_project_description                  | Grant Project Description                   | text      | text        |
| Yes      | series tag     | federal_cfda_number                        | Federal CFDA Number                         | text      | number      |
| Yes      | series tag     | grant_number_pass_through_grantor_s_number | Grant Number/ Pass-through Grantor's Number | text      | text        |
| Yes      | numeric metric | federal_entitlement_amount                 | Federal Entitlement Amount                  | number    | number      |
| Yes      | series tag     | grant_receivable_as_of_7_1_2012            | Grant Receivable as of 7/1/2012             | text      | text        |
| Yes      | series tag     | grant_receivable_prior_year_adjustment     | Grant Receivable Prior Year Adjustment      | text      | text        |
| Yes      | series tag     | grant_revenue_received                     | Grant Revenue Received                      | text      | text        |
| Yes      | series tag     | federal_grant_expenditures                 | Federal Grant Expenditures                  | text      | text        |
| Yes      | series tag     | federal_grant_pass_through_liability       | Federal Grant Pass Through Liability        | text      | text        |
| Yes      | series tag     | grant_receivable_as_of_6_30_2013           | Grant Receivable as of 6/30/2013            | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xhx7-hr4h d:2013-01-01T00:00:00.000Z t:federal_grant_expenditures=- t:grant_receivable_as_of_7_1_2012=- t:grant_revenue_received=- t:federal_cfda_number=97.056 t:grant_receivable_as_of_6_30_2013=CLOSED t:grant_number_pass_through_grantor_s_number=2006-GB-T6-0100 t:grant_project_description="Transportation Workers Identification Credentialing (TWIC) W.O.#6821400" m:federal_entitlement_amount=1058706

series e:xhx7-hr4h d:2013-01-01T00:00:00.000Z t:federal_grant_expenditures=- t:grant_receivable_as_of_7_1_2012=- t:grant_revenue_received=- t:grant_receivable_prior_year_adjustment=- t:federal_grant_pass_through_liability=- t:federal_cfda_number=97.056 t:grant_receivable_as_of_6_30_2013=CLOSED t:grant_number_pass_through_grantor_s_number=2006-GB-T6-0100 t:grant_project_description="Transport. Workers Identi. Credent. WO#6821400 Pass Thru (Non-Operating)" m:federal_entitlement_amount=3587711

series e:xhx7-hr4h d:2013-01-01T00:00:00.000Z t:federal_grant_expenditures=- t:grant_receivable_as_of_7_1_2012=- t:grant_revenue_received=- t:grant_receivable_prior_year_adjustment=- t:federal_cfda_number=97.056 t:grant_receivable_as_of_6_30_2013=CLOSED t:grant_number_pass_through_grantor_s_number=2007-GB-T7-K096 t:grant_project_description="A) Waterside Srvllanc System Enhan.(Detection)WO # 2469000 ] and B) Police Headquarters Surveillance Cameras   W.O.# 6829500  ]" m:federal_entitlement_amount=2596022
```

## Meta Commands

```ls
metric m:federal_entitlement_amount p:integer l:"Federal Entitlement Amount" t:dataTypeName=number

entity e:xhx7-hr4h l:"Port of Los Angeles - Single Audit Report 2013" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/xhx7-hr4h

property e:xhx7-hr4h t:meta.view v:id=xhx7-hr4h v:category="A Well Run City" v:averageRating=0 v:name="Port of Los Angeles - Single Audit Report 2013" v:attribution="Port of Los Angeles"

property e:xhx7-hr4h t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xhx7-hr4h t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:xhx7-hr4h t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| grant_project_description                                                                                                    | federal_cfda_number | grant_number_pass_through_grantor_s_number | federal_entitlement_amount | grant_receivable_as_of_7_1_2012 | grant_receivable_prior_year_adjustment | grant_revenue_received | federal_grant_expenditures | federal_grant_pass_through_liability | grant_receivable_as_of_6_30_2013 | 
| ============================================================================================================================ | =================== | ========================================== | ========================== | =============================== | ====================================== | ====================== | ========================== | ==================================== | ================================ | 
| Transportation Workers Identification Credentialing (TWIC) W.O.#6821400                                                      | 97.056              | 2006-GB-T6-0100                            | 1058706                    | -                               |                                        | -                      | -                          |                                      | CLOSED                           | 
| Transport. Workers Identi. Credent. WO#6821400 Pass Thru (Non-Operating)                                                     | 97.056              | 2006-GB-T6-0100                            | 3587711                    | -                               | -                                      | -                      | -                          | -                                    | CLOSED                           | 
| A) Waterside Srvllanc System Enhan.(Detection)WO # 2469000 ] and B) Police Headquarters Surveillance Cameras W.O.# 6829500 ] | 97.056              | 2007-GB-T7-K096                            | 2596022                    | -                               | -                                      | -                      | -                          |                                      | CLOSED                           | 
| Integrated Command & Control Center System W.O.#2499900                                                                      | 97.056              | 2007-GB-T7-K096                            | 2731830                    | -                               | -                                      | -                      | -                          |                                      | CLOSED                           | 
| Interoperable Communications System Infrastructure WO#2500300                                                                | 97.056              | 2007-GB-T7-K096                            | 1182011                    | 604,270                         | -                                      | 604,270                | -                          |                                      | CLOSED                           | 
| Fiduciary Agent Administration WO# 6824200                                                                                   | 97.056              | 2007-GB-T7-K429                            | 241606                     | 115,879                         | -                                      | 115,879                | -                          |                                      | -                                | 
| Portwide Risk Mitigation Plan WO# 6824300                                                                                    | 97.056              | 2007-GB-T7-K429                            | 1610703                    | -                               | -                                      | 412,464                | 412,464                    |                                      | (0)                              | 
| Mobile Command Post WO# 6824800                                                                                              | 97.056              | 2007-GB-T7-K429                            | 900000                     | -                               | -                                      | -                      | -                          |                                      | -                                | 
| Security System Maintenance W.O # 6829500 (Past #25035)                                                                      | 97.056              | 2007-GB-T7-K429                            | 2550600                    | 1,093,138                       | 870,033                                | 223,105                | -                          |                                      | -                                | 
| Security Sys.Maint.Prog Port of L.B.WO#6828600 PASS THRU (Non-Operating)                                                     | 97.056              | 2007-GB-T7-K429                            | 2550600                    | -                               | -                                      | 1,260,764              | 1,260,764                  | -                                    | -                                | 
```