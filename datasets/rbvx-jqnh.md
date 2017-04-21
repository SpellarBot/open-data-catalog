# FCRC Annual Concession Plan Franchises

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fcrc-annual-concession-plan-franchises) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rbvx-jqnh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rbvx-jqnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rbvx-jqnh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rbvx-jqnh |
| Name | FCRC Annual Concession Plan Franchises |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Created | 2016-04-22T17:21:28Z |
| Publication Date | 2016-04-22T22:04:44Z |

## Description

The Mayor?s Office of Contract Services oversees and certifies agency compliance with the applicable laws and regulations for franchises and concessions. In certain circumstances, franchises and concessions are also subject to the approval of the Franchise and Concession Review Committee (FCRC).

Franchises are grants of the right to occupy or to use the City?s inalienable property, such as streets or parks, for a public service, e.g., transportation or telecommunications.
Concessions are grants for the private use of city-owned property such as for food sales or recreational activity, with the City?s compensation typically tied to the concessionaire?s revenue. Concessions are also subject to the City's Concession Rules as codified in Title 12 of the Rules of the City of New York.

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                             | Data Type | Render Type |
| ======== | ============== | ============================================================== | ================================================================ | ========= | =========== |
| No       | time           | :updated_at                                                    | updated_at                                                       | meta_data | meta_data   |
| Yes      | series tag     | agency                                                         | Agency                                                           | text      | text        |
| Yes      | series tag     | fy_2015_award_or_transaction_yes_no                            | FY 2015 Award or Transaction (Yes/No)                            | text      | text        |
| Yes      | series tag     | fy_2015_registration_yes_no                                    | FY 2015 Registration (Yes/No)                                    | text      | text        |
| Yes      | series tag     | franchisee                                                     | Franchisee                                                       | text      | text        |
| No       |                | registration_date_or_date_sent_to_comptroller_for_registration | Registration Date (or date sent to Comptroller for registration) | text      | text        |
| Yes      | numeric metric | registration_value_for_fy_2015_transactions                    | Registration Value for FY 2015 Transactions                      | money     | text        |
| Yes      | series tag     | doc_cd_e_g_rct1                                                | DOC_CD (e.g., "RCT1")                                            | text      | text        |
| Yes      | series tag     | doc_agency_code                                                | DOC (agency code)                                                | text      | number      |
| Yes      | numeric metric | doc_id_automatically_generated_contract_id_number_from_fms     | DOC_ID (automatically generated contract ID number from FMS)     | number    | number      |
| Yes      | series tag     | franchise_type_specific_category                               | Franchise Type (Specific Category)                               | text      | text        |
| Yes      | series tag     | franchise_type_general_category                                | Franchise Type (General Category)                                | text      | text        |
| Yes      | series tag     | solicitation_award_method                                      | Solicitation/Award Method                                        | text      | text        |
| No       |                | start_date                                                     | Start Date                                                       | text      | text        |
| No       |                | expiration_date                                                | Expiration Date                                                  | text      | text        |
| Yes      | numeric metric | actual_fee_revenue_collected_in_fy2015                         | Actual Fee/Revenue Collected in FY2015                           | money     | money       |
| No       |                | public_hearing_date_if_applicable                              | Public Hearing Date (if applicable)                              | text      | text        |
| No       |                | public_meeting_date_if_applicable                              | Public Meeting Date (if applicable)                              | text      | text        |
| Yes      | series tag     | brief_description_of_franchise_award_or_fy2015_transaction     | Brief Description of Franchise Award or FY2015 Transaction       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = registration_date_or_date_sent_to_comptroller_for_registration,start_date,expiration_date,public_hearing_date_if_applicable,public_meeting_date_if_applicable
```

## Data Commands

```ls
series e:rbvx-jqnh d:2016-04-22T14:52:15.000Z t:fy_2015_registration_yes_no=No t:franchise_type_specific_category="Bus Service" t:brief_description_of_franchise_award_or_fy2015_transaction="Award of franchise" t:solicitation_award_method=RFP t:franchisee="PRIVATE TRANSPORTATION CORP." t:doc_cd_e_g_rct1=RCT1 t:agency=DOT t:franchise_type_general_category=Transportation t:registration_value_for_fy_2015_transactions=N/A t:fy_2015_award_or_transaction_yes_no=No t:doc_agency_code=841 m:actual_fee_revenue_collected_in_fy2015=27108 m:doc_id_automatically_generated_contract_id_number_from_fms=20128000075

series e:rbvx-jqnh d:2016-04-22T14:52:15.000Z t:fy_2015_registration_yes_no=No t:franchise_type_specific_category="Bus Service" t:brief_description_of_franchise_award_or_fy2015_transaction="Award of franchise" t:solicitation_award_method=RFP t:franchisee="VEOLIA TRANSPORTATION SERVICES, INC." t:doc_cd_e_g_rct1=RCT1 t:agency=DOT t:franchise_type_general_category=Transportation t:registration_value_for_fy_2015_transactions=N/A t:fy_2015_award_or_transaction_yes_no=No t:doc_agency_code=841 m:actual_fee_revenue_collected_in_fy2015=517697 m:doc_id_automatically_generated_contract_id_number_from_fms=20118205446

series e:rbvx-jqnh d:2016-04-22T14:52:15.000Z t:fy_2015_registration_yes_no=No t:franchise_type_specific_category="Bus Service" t:brief_description_of_franchise_award_or_fy2015_transaction=N/A t:solicitation_award_method="Board of Estimate" t:franchisee="LIBERTY LINES TRANSIT" t:doc_cd_e_g_rct1=N/A t:agency=DOT t:franchise_type_general_category=Transportation t:registration_value_for_fy_2015_transactions=N/A t:fy_2015_award_or_transaction_yes_no=No m:actual_fee_revenue_collected_in_fy2015=17840
```

## Meta Commands

```ls
metric m:doc_id_automatically_generated_contract_id_number_from_fms p:long l:"DOC_ID (automatically generated contract ID number from FMS)" t:dataTypeName=number

metric m:actual_fee_revenue_collected_in_fy2015 p:integer l:"Actual Fee/Revenue Collected in FY2015" t:dataTypeName=money

entity e:rbvx-jqnh l:"FCRC Annual Concession Plan Franchises" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/rbvx-jqnh

property e:rbvx-jqnh t:meta.view v:id=rbvx-jqnh v:category="City Government" v:averageRating=0 v:name="FCRC Annual Concession Plan Franchises" v:attribution="Office of the Mayor (OTM)"

property e:rbvx-jqnh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rbvx-jqnh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | fy_2015_award_or_transaction_yes_no | fy_2015_registration_yes_no | franchisee                                | registration_date_or_date_sent_to_comptroller_for_registration | registration_value_for_fy_2015_transactions | doc_cd_e_g_rct1 | doc_agency_code | doc_id_automatically_generated_contract_id_number_from_fms | franchise_type_specific_category                               | franchise_type_general_category | solicitation_award_method | start_date | expiration_date     | actual_fee_revenue_collected_in_fy2015 | public_hearing_date_if_applicable | public_meeting_date_if_applicable | brief_description_of_franchise_award_or_fy2015_transaction | 
| =========== | ====== | =================================== | =========================== | ========================================= | ============================================================== | =========================================== | =============== | =============== | ========================================================== | ============================================================== | =============================== | ========================= | ========== | =================== | ====================================== | ================================= | ================================= | ========================================================== | 
| 1461336735  | DOT    | No                                  | No                          | PRIVATE TRANSPORTATION CORP.              | 7/19/11                                                        | N/A                                         | RCT1            | 841             | 20128000075                                                | Bus Service                                                    | Transportation                  | RFP                       | 7/1/2011   | 6/30/2021           | 27108                                  | 6/6/2011                          | 6/13/2011                         | Award of franchise                                         | 
| 1461336735  | DOT    | No                                  | No                          | VEOLIA TRANSPORTATION SERVICES, INC.      | 6/15/11                                                        | N/A                                         | RCT1            | 841             | 20118205446                                                | Bus Service                                                    | Transportation                  | RFP                       | 7/1/2011   | 6/30/2021           | 517697                                 | 5/9/2011                          | 5/11/2011                         | Award of franchise                                         | 
| 1461336735  | DOT    | No                                  | No                          | LIBERTY LINES TRANSIT                     | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Bus Service                                                    | Transportation                  | Board of Estimate         | 5/6/1905   | Perpetual Agreement | 17840                                  | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | PSE&G for LIPA                            | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Distribution of Gas in Fifth Ward, Staten Island               | Miscellaneous Utilities         | Board of Estimate         | 5/29/1956  | 5/29/2006           | 1747951                                | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | PSE&G for LIPA                            | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Historic Gas and Electric Franchises                           | Miscellaneous Utilities         | Board of Estimate         | 3/9/1905   | Perpetual Agreement |                                        | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | CONSOLIDATED EDISON CO., INC.             | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Historic Gas and Electric Franchises                           | Miscellaneous Utilities         | Board of Estimate         | 12/28/1904 | Perpetual Agreement |                                        | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | CEMUSA                                    | 4/11/05                                                        | N/A                                         | RCT1            | 841             | 20060041570                                                | Maintenance of Bus Stop Shelters, Newsstand and Public Toilets | Street Furniture                | Request for Proposal      | 6/12/2006  | 5/18/2026           | 51368653                               | 5/11/2006                         | 5/15/2006                         | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | NATIONAL RAILROAD PASSENGER CORP (Amtrak) | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Railroad                                                       | Transportation                  | Board of Estimate         | 10/9/1902  | Perpetual Agreement | 142728                                 | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | PORT AUTHORITY OF NY & NJ                 | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Railroad                                                       | Transportation                  | Board of Estimate         | 2/14/1907  | Perpetual Agreement | 140963                                 | N/A                               | N/A                               | N/A                                                        | 
| 1461336735  | DOT    | No                                  | No                          | ROOSEVELT ISLAND OPERATING CORP.          | NOT REGISTERED                                                 | N/A                                         | N/A             |                 |                                                            | Roosevelt Island Tramway (Railroad)                            | Transportation                  | Board of Estimate         | 2/19/1974  | 6/30/1995           | 25330                                  | N/A                               | N/A                               | N/A                                                        | 
```