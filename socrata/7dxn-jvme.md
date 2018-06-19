# OIP Master UIPA Record Request Year-End Log For FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oip-master-uipa-record-request-year-end-log-for-fy-2013-15098) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7dxn-jvme) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7dxn-jvme/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7dxn-jvme/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7dxn-jvme |
| Name | OIP Master UIPA Record Request Year-End Log For FY 2013 |
| Attribution | Office of Information Practices, State of Hawaii |
| Category | Government-Wide Support |
| Tags | uipa, oip, records, request |
| Created | 2013-07-05T19:39:34Z |
| Publication Date | 2013-10-17T20:29:47Z |

## Description

OIP Master UIPA Record Request Year-End Log For FY 2013 (record requests received July 1, 2012, through June 30, 2013)

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                                | Data Type | Render Type |
| ======== | ============== | ============================================================= | =================================================================== | ========= | =========== |
| Yes      | series tag     | department                                                    | Department                                                          | text      | text        |
| Yes      | series tag     | agency                                                        | Agency                                                              | text      | text        |
| Yes      | numeric metric | of_personal_records_requests                                  | # of Personal Records Requests                                      | number    | number      |
| Yes      | numeric metric | of_requests_received                                          | # of Requests Received                                              | number    | number      |
| Yes      | numeric metric | of_agency_notices_sent                                        | # of Agency Notices Sent                                            | number    | number      |
| Yes      | numeric metric | of_notices_or_acknowledgments_sent_within_10_work_days        | # of Notices or Acknowledgments Sent within 10 Work Days            | number    | number      |
| Yes      | numeric metric | of_complex_cases_that_agency_acknowledged                     | # of Complex Cases that Agency Acknowledged                         | number    | number      |
| Yes      | numeric metric | of_complex_cases_with_incremental_responses                   | # of Complex Cases with Incremental Responses                       | number    | number      |
| Yes      | numeric metric | of_requests_completed                                         | # of Requests Completed                                             | number    | number      |
| Yes      | numeric metric | median_of_weekdays_to_complete                                | Median # of Weekdays to Complete                                    | number    | number      |
| Yes      | numeric metric | of_requests_granted_in_full                                   | # of Requests Granted in Full                                       | number    | number      |
| Yes      | numeric metric | of_requests_denied_in_full                                    | # of Requests Denied in Full                                        | number    | number      |
| Yes      | numeric metric | of_requests_denied_in_part                                    | # of Requests Denied in Part                                        | number    | number      |
| Yes      | numeric metric | of_requests_agency_unable_to_respond                          | # of Requests Agency Unable to Respond                              | number    | number      |
| Yes      | numeric metric | of_requests_withdrawn_by_requester                            | # of Requests Withdrawn by Requester                                | number    | number      |
| Yes      | numeric metric | of_requests_abandoned_or_requester_failed_to_pay              | # of Requests Abandoned or Requester Failed to Pay                  | number    | number      |
| Yes      | numeric metric | of_uipa_lawsuits_filed_against_agency                         | # of UIPA Lawsuits Filed Against Agency                             | number    | number      |
| Yes      | numeric metric | of_actual_search_hours                                        | # of Actual Search Hours                                            | number    | number      |
| Yes      | numeric metric | of_actual_review_segregation_hours                            | # of Actual Review/ Segregation Hours                               | number    | number      |
| Yes      | numeric metric | of_actual_legal_review_hours                                  | # of Actual Legal Review Hours                                      | number    | number      |
| Yes      | numeric metric | total_of_actual_srs_legal_review_hours                        | TOTAL # of Actual SRS & Legal Review Hours                          | number    | number      |
| Yes      | numeric metric | total_of_srs_fees_incurred                                    | TOTAL $ of SRS Fees Incurred                                        | money     | money       |
| Yes      | numeric metric | additional_response_fees_incurred_but_not_chargeable          | Additional Response Fees Incurred But Not Chargeable                | money     | money       |
| Yes      | numeric metric | of_30_fee_waivers                                             | # of $30 Fee Waivers                                                | number    | number      |
| Yes      | numeric metric | of_60_fee_waivers                                             | # of $60 Fee Waivers                                                | number    | number      |
| Yes      | numeric metric | total_of_personal_records_fees_not_chargeable                 | Total $ of Personal Records Fees Not Chargeable                     | money     | money       |
| Yes      | numeric metric | total_net_srs_fees_chargeable                                 | Total $ Net SRS Fees CHARGEABLE                                     | money     | money       |
| Yes      | numeric metric | total_gross_copy_delivery_costs_that_agency_incurred          | Total $ Gross Copy/Delivery Costs that Agency INCURRED              | money     | money       |
| Yes      | numeric metric | total_net_copy_delivery_costs_chargeable_to_requester         | Total $ Net Copy/Delivery Costs CHARGEABLE to Requester             | money     | money       |
| Yes      | numeric metric | total_fees_costs_actually_paid_by_requester                   | TOTAL $ Fees & Costs ACTUALLY PAID by Requester                     | money     | money       |
| Yes      | numeric metric | total_net_fees_costs_chargeable                               | TOTAL $ Net Fees & Costs CHARGEABLE                                 | money     | money       |
| Yes      | numeric metric | total_gross_fees_costs_agency_incurred                        | TOTAL $ Gross Fees & Costs Agency INCURRED                          | money     | money       |
| Yes      | numeric metric | total_gross_fees_costs_incurred_but_not_charged_unrecoverable | TOTAL $ Gross Fees & Costs INCURRED BUT NOT CHARGED (Unrecoverable) | money     | money       |
| Yes      | numeric metric | total_routine_requests                                        | TOTAL ROUTINE REQUESTS                                              | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7dxn-jvme d:2013-01-01T00:00:00.000Z t:department=SOH_ACCOUNTING_AND_GENERAL_SERVICES t:agency="SOH/ ACCOUNTING & GENERAL SERVICES/ ACCESS HAWAII COMMITTEE" m:of_60_fee_waivers=0 m:of_actual_search_hours=0 m:total_of_actual_srs_legal_review_hours=0 m:of_requests_denied_in_part=0 m:of_complex_cases_with_incremental_responses=0 m:of_requests_abandoned_or_requester_failed_to_pay=0 m:total_gross_fees_costs_agency_incurred=0 m:additional_response_fees_incurred_but_not_chargeable=0 m:of_personal_records_requests=0 m:of_requests_granted_in_full=0 m:of_requests_withdrawn_by_requester=0 m:total_of_personal_records_fees_not_chargeable=0 m:of_requests_agency_unable_to_respond=0 m:total_net_srs_fees_chargeable=0 m:of_requests_received=0 m:of_agency_notices_sent=0 m:total_of_srs_fees_incurred=0 m:of_notices_or_acknowledgments_sent_within_10_work_days=0 m:total_net_copy_delivery_costs_chargeable_to_requester=0 m:median_of_weekdays_to_complete=0 m:of_actual_legal_review_hours=0 m:total_fees_costs_actually_paid_by_requester=0 m:of_30_fee_waivers=0 m:total_gross_copy_delivery_costs_that_agency_incurred=0 m:total_net_fees_costs_chargeable=0 m:of_actual_review_segregation_hours=0 m:of_requests_completed=0 m:total_gross_fees_costs_incurred_but_not_charged_unrecoverable=0 m:of_complex_cases_that_agency_acknowledged=0 m:total_routine_requests=0 m:of_uipa_lawsuits_filed_against_agency=0 m:of_requests_denied_in_full=0

series e:7dxn-jvme d:2013-01-01T00:00:00.000Z t:department=SOH_ACCOUNTING_AND_GENERAL_SERVICES t:agency="SOH/ ACCOUNTING & GENERAL SERVICES/ ACCOUNTING DIVISION/ ACCT-0" m:of_60_fee_waivers=6 m:of_actual_search_hours=3.25 m:total_of_actual_srs_legal_review_hours=17.5 m:of_requests_denied_in_part=1 m:of_complex_cases_with_incremental_responses=1 m:of_requests_abandoned_or_requester_failed_to_pay=0 m:total_gross_fees_costs_agency_incurred=451 m:additional_response_fees_incurred_but_not_chargeable=0 m:of_personal_records_requests=0 m:of_requests_granted_in_full=13 m:of_requests_withdrawn_by_requester=0 m:total_of_personal_records_fees_not_chargeable=0 m:of_requests_agency_unable_to_respond=0 m:total_net_srs_fees_chargeable=-42.5 m:of_requests_received=16 m:of_agency_notices_sent=1 m:total_of_srs_fees_incurred=317.5 m:of_notices_or_acknowledgments_sent_within_10_work_days=1 m:total_net_copy_delivery_costs_chargeable_to_requester=0 m:median_of_weekdays_to_complete=8 m:of_actual_legal_review_hours=0 m:total_fees_costs_actually_paid_by_requester=153.5 m:of_30_fee_waivers=0 m:total_gross_copy_delivery_costs_that_agency_incurred=133.5 m:total_net_fees_costs_chargeable=185 m:of_actual_review_segregation_hours=14.25 m:of_requests_completed=16 m:total_gross_fees_costs_incurred_but_not_charged_unrecoverable=297.5 m:of_complex_cases_that_agency_acknowledged=1 m:total_routine_requests=0 m:of_uipa_lawsuits_filed_against_agency=0 m:of_requests_denied_in_full=2

series e:7dxn-jvme d:2013-01-01T00:00:00.000Z t:department=SOH_ACCOUNTING_AND_GENERAL_SERVICES t:agency="SOH/ ACCOUNTING & GENERAL SERVICES/ ARCHIVES DIVISION/ ARCH-0" m:of_60_fee_waivers=0 m:of_actual_search_hours=2 m:total_of_actual_srs_legal_review_hours=2 m:of_requests_denied_in_part=0 m:of_complex_cases_with_incremental_responses=1 m:of_requests_abandoned_or_requester_failed_to_pay=0 m:total_gross_fees_costs_agency_incurred=374.9 m:additional_response_fees_incurred_but_not_chargeable=0 m:of_personal_records_requests=0 m:of_requests_granted_in_full=0 m:of_requests_withdrawn_by_requester=0 m:total_of_personal_records_fees_not_chargeable=0 m:of_requests_agency_unable_to_respond=1 m:total_net_srs_fees_chargeable=-10 m:of_requests_received=2 m:of_agency_notices_sent=2 m:total_of_srs_fees_incurred=20 m:of_notices_or_acknowledgments_sent_within_10_work_days=2 m:total_net_copy_delivery_costs_chargeable_to_requester=0 m:median_of_weekdays_to_complete=48 m:of_actual_legal_review_hours=0 m:total_fees_costs_actually_paid_by_requester=354.9 m:of_30_fee_waivers=1 m:total_gross_copy_delivery_costs_that_agency_incurred=354.9 m:total_net_fees_costs_chargeable=0 m:of_actual_review_segregation_hours=0 m:of_requests_completed=1 m:total_gross_fees_costs_incurred_but_not_charged_unrecoverable=20 m:of_complex_cases_that_agency_acknowledged=1 m:total_routine_requests=694 m:of_uipa_lawsuits_filed_against_agency=0 m:of_requests_denied_in_full=0
```

## Meta Commands

```ls
metric m:of_personal_records_requests p:double l:"# of Personal Records Requests" t:dataTypeName=number

metric m:of_requests_received p:integer l:"# of Requests Received" t:dataTypeName=number

metric m:of_agency_notices_sent p:double l:"# of Agency Notices Sent" t:dataTypeName=number

metric m:of_notices_or_acknowledgments_sent_within_10_work_days p:double l:"# of Notices or Acknowledgments Sent within 10 Work Days" t:dataTypeName=number

metric m:of_complex_cases_that_agency_acknowledged p:double l:"# of Complex Cases that Agency Acknowledged" t:dataTypeName=number

metric m:of_complex_cases_with_incremental_responses p:double l:"# of Complex Cases with Incremental Responses" t:dataTypeName=number

metric m:of_requests_completed p:integer l:"# of Requests Completed" t:dataTypeName=number

metric m:median_of_weekdays_to_complete p:double l:"Median # of Weekdays to Complete" t:dataTypeName=number

metric m:of_requests_granted_in_full p:integer l:"# of Requests Granted in Full" t:dataTypeName=number

metric m:of_requests_denied_in_full p:double l:"# of Requests Denied in Full" t:dataTypeName=number

metric m:of_requests_denied_in_part p:double l:"# of Requests Denied in Part" t:dataTypeName=number

metric m:of_requests_agency_unable_to_respond p:double l:"# of Requests Agency Unable to Respond" t:dataTypeName=number

metric m:of_requests_withdrawn_by_requester p:double l:"# of Requests Withdrawn by Requester" t:dataTypeName=number

metric m:of_requests_abandoned_or_requester_failed_to_pay p:double l:"# of Requests Abandoned or Requester Failed to Pay" t:dataTypeName=number

metric m:of_uipa_lawsuits_filed_against_agency p:float l:"# of UIPA Lawsuits Filed Against Agency" t:dataTypeName=number

metric m:of_actual_search_hours p:float l:"# of Actual Search Hours" t:dataTypeName=number

metric m:of_actual_review_segregation_hours p:float l:"# of Actual Review/ Segregation Hours" t:dataTypeName=number

metric m:of_actual_legal_review_hours p:float l:"# of Actual Legal Review Hours" t:dataTypeName=number

metric m:total_of_actual_srs_legal_review_hours p:float l:"TOTAL # of Actual SRS & Legal Review Hours" t:dataTypeName=number

metric m:total_of_srs_fees_incurred p:double l:"TOTAL $ of SRS Fees Incurred" t:dataTypeName=money

metric m:additional_response_fees_incurred_but_not_chargeable p:double l:"Additional Response Fees Incurred But Not Chargeable" t:dataTypeName=money

metric m:of_30_fee_waivers p:double l:"# of $30 Fee Waivers" t:dataTypeName=number

metric m:of_60_fee_waivers p:double l:"# of $60 Fee Waivers" t:dataTypeName=number

metric m:total_of_personal_records_fees_not_chargeable p:double l:"Total $ of Personal Records Fees Not Chargeable" t:dataTypeName=money

metric m:total_net_srs_fees_chargeable p:double l:"Total $ Net SRS Fees CHARGEABLE" t:dataTypeName=money

metric m:total_gross_copy_delivery_costs_that_agency_incurred p:double l:"Total $ Gross Copy/Delivery Costs that Agency INCURRED" t:dataTypeName=money

metric m:total_net_copy_delivery_costs_chargeable_to_requester p:double l:"Total $ Net Copy/Delivery Costs CHARGEABLE to Requester" t:dataTypeName=money

metric m:total_fees_costs_actually_paid_by_requester p:double l:"TOTAL $ Fees & Costs ACTUALLY PAID by Requester" t:dataTypeName=money

metric m:total_net_fees_costs_chargeable p:double l:"TOTAL $ Net Fees & Costs CHARGEABLE" t:dataTypeName=money

metric m:total_gross_fees_costs_agency_incurred p:double l:"TOTAL $ Gross Fees & Costs Agency INCURRED" t:dataTypeName=money

metric m:total_gross_fees_costs_incurred_but_not_charged_unrecoverable p:double l:"TOTAL $ Gross Fees & Costs INCURRED BUT NOT CHARGED (Unrecoverable)" t:dataTypeName=money

metric m:total_routine_requests p:integer l:"TOTAL ROUTINE REQUESTS" t:dataTypeName=number

entity e:7dxn-jvme l:"OIP Master UIPA Record Request Year-End Log For FY 2013" t:attribution="Office of Information Practices, State of Hawaii" t:url=https://data.hawaii.gov/api/views/7dxn-jvme

property e:7dxn-jvme t:meta.view v:id=7dxn-jvme v:category="Government-Wide Support" v:attributionLink=http://oip.hawaii.gov v:averageRating=0 v:name="OIP Master UIPA Record Request Year-End Log For FY 2013" v:attribution="Office of Information Practices, State of Hawaii"

property e:7dxn-jvme t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7dxn-jvme t:meta.view.owner v:id=8bi5-4k2n v:screenName="Michael Little" v:displayName="Michael Little"

property e:7dxn-jvme t:meta.view.tableauthor v:id=8bi5-4k2n v:screenName="Michael Little" v:roleName=publisher v:displayName="Michael Little"
```

## Top Records

```ls
| department                          | agency                                                                            | of_personal_records_requests | of_requests_received | of_agency_notices_sent | of_notices_or_acknowledgments_sent_within_10_work_days | of_complex_cases_that_agency_acknowledged | of_complex_cases_with_incremental_responses | of_requests_completed | median_of_weekdays_to_complete | of_requests_granted_in_full | of_requests_denied_in_full | of_requests_denied_in_part | of_requests_agency_unable_to_respond | of_requests_withdrawn_by_requester | of_requests_abandoned_or_requester_failed_to_pay | of_uipa_lawsuits_filed_against_agency | of_actual_search_hours | of_actual_review_segregation_hours | of_actual_legal_review_hours | total_of_actual_srs_legal_review_hours | total_of_srs_fees_incurred | additional_response_fees_incurred_but_not_chargeable | of_30_fee_waivers | of_60_fee_waivers | total_of_personal_records_fees_not_chargeable | total_net_srs_fees_chargeable | total_gross_copy_delivery_costs_that_agency_incurred | total_net_copy_delivery_costs_chargeable_to_requester | total_fees_costs_actually_paid_by_requester | total_net_fees_costs_chargeable | total_gross_fees_costs_agency_incurred | total_gross_fees_costs_incurred_but_not_charged_unrecoverable | total_routine_requests | 
| =================================== | ================================================================================= | ============================ | ==================== | ====================== | ====================================================== | ========================================= | =========================================== | ===================== | ============================== | =========================== | ========================== | ========================== | ==================================== | ================================== | ================================================ | ===================================== | ====================== | ================================== | ============================ | ====================================== | ========================== | ==================================================== | ================= | ================= | ============================================= | ============================= | ==================================================== | ===================================================== | =========================================== | =============================== | ====================================== | ============================================================= | ====================== | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ ACCESS HAWAII COMMITTEE                       | 0                            | 0                    | 0                      | 0                                                      | 0                                         | 0                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ ACCOUNTING DIVISION/ ACCT-0                   | 0                            | 16                   | 1                      | 1                                                      | 1                                         | 1                                           | 16                    | 8                              | 13                          | 2                          | 1                          | 0                                    | 0                                  | 0                                                | 0                                     | 3.25                   | 14.25                              | 0                            | 17.5                                   | 317.50                     | 0.00                                                 | 0                 | 6                 | 0.00                                          | -42.50                        | 133.50                                               | 0.00                                                  | 153.50                                      | 185.00                          | 451.00                                 | 297.50                                                        | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ ARCHIVES DIVISION/ ARCH-0                     | 0                            | 2                    | 2                      | 2                                                      | 1                                         | 1                                           | 1                     | 48                             | 0                           | 0                          | 0                          | 1                                    | 0                                  | 0                                                | 0                                     | 2                      | 0                                  | 0                            | 2                                      | 20.00                      | 0.00                                                 | 1                 | 0                 | 0.00                                          | -10.00                        | 354.90                                               | 0.00                                                  | 354.90                                      | 0.00                            | 374.90                                 | 20.00                                                         | 694                    | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ AUDIT DIVISION                                | 0                            | 11                   | 11                     | 4                                                      | 1                                         | 1                                           | 11                    | 4                              | 6                           | 0                          | 1                          | 4                                    | 0                                  | 0                                                | 0                                     | 14.5                   | 18.5                               | 0                            | 33                                     | 515.00                     | 0.00                                                 | 0                 | 0                 | 0.00                                          | 515.00                        | 250.00                                               | 250.00                                                | 639.00                                      | 765.00                          | 765.00                                 | 126.00                                                        | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ AUTOMOTIVE MANAGEMENT DIVISION                | 0                            | 0                    | 0                      | 0                                                      | 0                                         | 0                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ CAMPAIGN SPENDING COMMISSION                  | 0                            | 1                    | 1                      | 1                                                      | 1                                         | 1                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 1                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ CENTRAL SERVICES DIVISION                     | 0                            | 0                    | 0                      | 0                                                      | 0                                         | 0                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ COMPTROLLERS & ADMINISTRATIVE SERVICES OFFICE | 0                            | 0                    | 0                      | 0                                                      | 0                                         | 0                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ ENHANCED 911 BOARD                            | 0                            | 1                    | 1                      | 1                                                      | 0                                         | 0                                           | 1                     | 5                              | 1                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 1                      | 0                                  | 0                            | 1                                      | 10.00                      | 0.00                                                 | 0                 | 0                 | 0.00                                          | 10.00                         | 0.00                                                 | 0.00                                                  | 0.00                                        | 10.00                           | 10.00                                  | 10.00                                                         | 0                      | 
| SOH_ACCOUNTING_AND_GENERAL_SERVICES | SOH/ ACCOUNTING & GENERAL SERVICES/ HAWAII DISTRICT OFFICE                        | 0                            | 0                    | 0                      | 0                                                      | 0                                         | 0                                           | 0                     | 0                              | 0                           | 0                          | 0                          | 0                                    | 0                                  | 0                                                | 0                                     | 0                      | 0                                  | 0                            | 0                                      | 0.00                       | 0.00                                                 | 0                 | 0                 | 0.00                                          | 0.00                          | 0.00                                                 | 0.00                                                  | 0.00                                        | 0.00                            | 0.00                                   | 0.00                                                          | 0                      | 
```