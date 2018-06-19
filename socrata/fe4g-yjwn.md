# Summary of Expired Contracts - As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-of-expired-contracts-as-of-june-30-2014-e4ba0) |
| Metadata | [Link](https://data.oregon.gov/api/views/fe4g-yjwn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fe4g-yjwn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fe4g-yjwn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fe4g-yjwn |
| Name | Summary of Expired Contracts - As of June 30, 2014 |
| Category | Revenue & Expense |
| Tags | contracts, expired contracts, agency expired contracts |
| Created | 2014-12-30T15:20:25Z |
| Publication Date | 2014-12-30T15:28:56Z |

## Description

The following data is provided as an extract from the Statewide Procurement System (Oregon Procurement Information Network - ORPIN). It is a complete list of contracts that expired on or before June 30, 2014 and represents the full extent of electronic records of expired contracts that are tracked within ORPIN. The contract values reflected in the report are estimates only. Note: A number of contracts may indicate an ?Amendment Date? that may exceed the ?Expiration Date?. In these instances, the ?Amendment Date? reflects an automated system time/date stamp that the system appends to the contract when the electronic version was accessed or modified, not necessarily when the legal instrument (the contract itself) was modified. Note: This report may not include contract information for the Oregon Judicial Department, Oregon State Lottery, Oregon University System, Oregon State Treasurer, or semi-independent state agencies, boards, and commissions. Some executive branch agencies have independent contracting authority for specific goods and services (e.g., Transportation, Secretary of State, State Treasurer, Human Services, Fish and Wildlife, Parks and Recreation, Aviation, Economic and Community Development, Housing, Corrections, Veterans Affairs, Military, Education, and state agencies "specifically authorized" by any law outside the Code to "enter into a contract"). Thus, the ORPIN system may not capture contract information about those activities.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | issued_for_agency_number       | Issued For Agency Number       | text          | text          |
| Yes      | series tag     | issued_for_agency_name         | Issued For Agency Name         | text          | text          |
| Yes      | series tag     | issued_by_agency_name          | Issued By Agency Name          | text          | text          |
| Yes      | series tag     | award_number_w_amendments      | Award Number w/Amendments      | text          | text          |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | series tag     | street_address                 | Street Address                 | text          | text          |
| Yes      | series tag     | zip_code                       | Zip Code                       | text          | number        |
| Yes      | time           | original_start_date            | Original Start Date            | calendar_date | calendar_date |
| No       |                | expiration_date                | Expiration Date                | calendar_date | calendar_date |
| Yes      | numeric metric | original_award_value           | Original Award Value           | money         | money         |
| Yes      | numeric metric | total_award_value_w_amendments | Total Award Value w/Amendments | money         | money         |
```

## Time Field

```ls
Value = original_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:fe4g-yjwn d:2013-02-15T00:00:00.000Z t:issued_for_agency_number=107121 t:issued_by_agency_name="Administrative Services, Department Of - Facilities" t:award_number_w_amendments=107-IA00395-13 t:issued_for_agency_name="Administrative Services, Department Of - Facilities" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="Project Management Svcs GSB Risk Security Office Remodel" t:contractor_information="Administrative Services, Department of - Risk Management" m:total_award_value_w_amendments=0 m:original_award_value=0

series e:fe4g-yjwn d:2013-02-19T00:00:00.000Z t:issued_for_agency_number=107121 t:issued_by_agency_name="Administrative Services, Department Of - Facilities" t:award_number_w_amendments=107-IA00396-13 t:issued_for_agency_name="Administrative Services, Department Of - Facilities" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="Project Mgmt Services for General Services Building Reconfigure" t:contractor_information="Administrative Services, Department of - State Procurement Office" m:total_award_value_w_amendments=0 m:original_award_value=0

series e:fe4g-yjwn d:2011-04-18T00:00:00.000Z t:issued_for_agency_number=730531 t:issued_by_agency_name="ODOT - Agency - Transportation Commission" t:zip_code=98023 t:award_number_w_amendments="730-29109W3-11 (5)" t:issued_for_agency_name="ODOT - Agency - Transportation Commission" t:award_type="Work Order Against ATA" t:award_title="Work Order Contract T&Cs for PA 9930 ODOT WOC 29109W3" t:street_address="1911 SW Campus Dr. #457" t:contractor_information="Public Knowledge LLC" m:total_award_value_w_amendments=113600 m:original_award_value=71000
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:fe4g-yjwn l:"Summary of Expired Contracts - As of June 30, 2014" t:url=https://data.oregon.gov/api/views/fe4g-yjwn

property e:fe4g-yjwn t:meta.view v:id=fe4g-yjwn v:category="Revenue & Expense" v:averageRating=0 v:name="Summary of Expired Contracts - As of June 30, 2014"

property e:fe4g-yjwn t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:fe4g-yjwn t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| issued_for_agency_number | issued_for_agency_name                                           | issued_by_agency_name                               | award_number_w_amendments | award_title                                                     | award_type                         | contractor_information                                            | street_address             | zip_code | original_start_date | expiration_date     | original_award_value | total_award_value_w_amendments | 
| ======================== | ================================================================ | =================================================== | ========================= | =============================================================== | ================================== | ================================================================= | ========================== | ======== | =================== | =================== | ==================== | ============================== | 
| 107121                   | Administrative Services, Department Of - Facilities              | Administrative Services, Department Of - Facilities | 107-IA00395-13            | Project Management Svcs GSB Risk Security Office Remodel        | Intergovernment Agreement (ORS190) | Administrative Services, Department of - Risk Management          |                            |          | 2013-02-15T00:00:00 | 2013-07-30T00:00:00 | 0.00                 | 0.00                           | 
| 107121                   | Administrative Services, Department Of - Facilities              | Administrative Services, Department Of - Facilities | 107-IA00396-13            | Project Mgmt Services for General Services Building Reconfigure | Intergovernment Agreement (ORS190) | Administrative Services, Department of - State Procurement Office |                            |          | 2013-02-19T00:00:00 | 2013-07-30T00:00:00 | 0.00                 | 0.00                           | 
| 730531                   | ODOT - Agency - Transportation Commission                        | ODOT - Agency - Transportation Commission           | 730-29109W3-11 (5)        | Work Order Contract T&Cs for PA 9930 ODOT WOC 29109W3           | Work Order Against ATA             | Public Knowledge LLC                                              | 1911 SW Campus Dr. #457    | 98023    | 2011-04-18T00:00:00 | 2013-07-31T00:00:00 | 71000.00             | 113600.00                      | 
| 730531                   | ODOT - Agency - Transportation Commission                        | ODOT - Agency - Transportation Commission           | 730-29109W2-12            | Work Order Contract for Price & Services Agreement 9930         | Work Order Against ATA             | Public Knowledge LLC                                              | 1911 SW Campus Dr. #457    | 98023    | 2011-09-26T00:00:00 | 2013-07-31T00:00:00 | 149120.00            | 149120.00                      | 
| 107100                   | Administrative Services, Department of - State Services Division | Administrative Services, Department of              | 53660 (1)                 | Pinkerton & English Settlement                                  | Intergovernment Agreement (ORS190) | PERS - Public Employees Retirement System, Oregon                 |                            |          | 2011-10-21T00:00:00 | 2013-07-31T00:00:00 | 34806.00             | 40653.00                       | 
| 257000                   | Police, Oregon State                                             | Police, Oregon State                                | 257-1618-13               | ORS 190 GSA Award for Avatar II robot package                   | One Time Contract                  | Robotex, Inc.                                                     | 1400 Page Mill Rd. Ste 100 | 94304    | 2013-04-01T00:00:00 | 2013-07-31T00:00:00 | 18331.00             | 18331.00                       | 
| 730531                   | ODOT - Agency - Transportation Commission                        | ODOT - Agency - Transportation Commission           | 730-B31466-13             | Infill and Narrowbanding Antenna Install Batch 10               | One Time Contract                  | Tower Time Wireless                                               | 15760 Burgess Rd           | 97739    | 2013-06-11T00:00:00 | 2013-08-01T00:00:00 | 48900.00             | 48900.00                       | 
| 257000                   | Police, Oregon State                                             | Office of State Fire Marshal                        | IGA-290-2012              | Hazardous Material Mitigation Plan and Training                 | Intergovernment Agreement (ORS190) | Clackamas County (pl)                                             |                            |          | 2012-11-01T00:00:00 | 2013-08-01T00:00:00 | 15688.00             | 15688.00                       | 
| 459000                   | PERS - Public Employees Retirement System, Oregon                | PERS -FSD-Contracts and Procurement Section         | PERS-1021-11              | Halogen Software License and Services Agreement                 | Personal Services (PSK) IT         | Halogen Software Inc.                                             | 495 March Road             | 20001    | 2011-05-01T00:00:00 | 2013-08-01T00:00:00 | 55000.00             | 55000.00                       | 
| 291004                   | DOC Central Distribution Center                                  | DOC Central Distribution Center                     | 291-1095-08 (5)           | INMATE STOCKING CAPS & WEBBED BELT W/BUCKLE                     | Price Agreement                    | pacific link international corp                                   | 64 commercial ave          | 11530    | 2008-08-19T00:00:00 | 2013-08-18T00:00:00 | 48307.00             | 48307.00                       | 
```