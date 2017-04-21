# Summary of Expired Contracts - As of December 31, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-of-expired-contracts-as-of-december-31-2011-661df) |
| Metadata | [Link](https://data.oregon.gov/api/views/qcm5-94wv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qcm5-94wv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qcm5-94wv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qcm5-94wv |
| Name | Summary of Expired Contracts - As of December 31, 2011 |
| Category | Revenue & Expense |
| Created | 2012-01-04T19:33:18Z |
| Publication Date | 2012-01-04T21:27:41Z |

## Description

The following data is provided as an extract from the Statewide Procurement System (Oregon Procurement Information Network - ORPIN). It is a complete list of contracts that expired on or before December 31, 2011 and represents the full extent of electronic records of expired contracts that are tracked within ORPIN. The contract values reflected in the report are estimates only. 

Note: A number of contracts may indicate an ?Amendment Date? that may exceed the ?Expiration Date?.  In these instances, the ?Amendment Date? reflects an automated system time/date stamp that the system appends to the contract when the electronic version was accessed or modified, not necessarily when the legal instrument (the contract itself) was modified. 

Note: This report may not include contract information for the Oregon Judicial Department, Oregon State Lottery, Oregon University System, Oregon State Treasurer, or semi-independent state agencies, boards, and commissions. Some executive branch agencies have independent contracting authority for specific goods and services (e.g., Transportation, Secretary of State, State Treasurer, Human Services, Fish and Wildlife, Parks and Recreation, Aviation, Economic and Community Development, Housing, Corrections, Veterans Affairs, Military, Education, and state agencies "specifically authorized" by any law outside the Code to "enter into a contract"). Thus, the ORPIN system may not capture contract information about those activities.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | agency_number                     | Agency Number                     | text      | text        |
| Yes      | series tag     | agency_name                       | Agency Name                       | text      | text        |
| Yes      | series tag     | award_number_w_amendments         | Award Number w/Amendments         | text      | text        |
| Yes      | series tag     | award_title                       | Award Title                       | text      | text        |
| Yes      | series tag     | award_type                        | Award Type                        | text      | text        |
| Yes      | series tag     | contractor_information            | Contractor Information            | text      | text        |
| Yes      | series tag     | street_address                    | Street Address                    | text      | text        |
| Yes      | series tag     | city                              | City                              | text      | text        |
| Yes      | series tag     | state                             | State                             | text      | text        |
| Yes      | series tag     | zip_code                          | Zip Code                          | text      | number      |
| No       |                | original_start_dateamendment_date | Original Start DateAmendment Date | text      | text        |
| No       |                | expiration_date                   | Expiration Date                   | text      | text        |
| Yes      | numeric metric | original_award_value              | Original Award Value              | money     | money       |
| Yes      | numeric metric | amendment_value                   | Amendment Value                   | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments    | Total Award Value w/Amendments    | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_dateamendment_date,expiration_date
```

## Data Commands

```ls
series e:qcm5-94wv d:2011-01-01T00:00:00.000Z t:zip_code=97470 t:award_number_w_amendments=100000DHS116598-5 t:state=OR t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=100100 t:award_title="SOC Tribal Grant - Child Welfare" t:street_address="2371 Stephens
Suite 100" t:agency_name="DHS - Children, Adults, and Families" t:contractor_information="Cow Creek Band of Umpqua Indians" t:city=Roseburg m:amendment_value=15160 m:total_award_value_w_amendments=15160 m:original_award_value=15160

series e:qcm5-94wv d:2011-01-01T00:00:00.000Z t:zip_code=97459 t:award_number_w_amendments=100000DHS116599-5 t:state=OR t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=100100 t:award_title="SOC Tribal Grant" t:street_address="PO Box 783" t:agency_name="DHS - Children, Adults, and Families" t:contractor_information="Coquille Indian Tribe (ORCPP)" t:city="North Bend" m:amendment_value=6361 m:total_award_value_w_amendments=6361 m:original_award_value=6361

series e:qcm5-94wv d:2011-01-01T00:00:00.000Z t:zip_code=97801 t:award_number_w_amendments=100000DHS116602-5 t:state=OR t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=100100 t:award_title="SOC Tribal Grant" t:street_address="PO Box 638" t:agency_name="DHS - Children, Adults, and Families" t:contractor_information="Confederated Tribes of Umatilla (ORCPP)" t:city=Pendleton m:amendment_value=44357 m:total_award_value_w_amendments=44357 m:original_award_value=44357
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:qcm5-94wv l:"Summary of Expired Contracts - As of December 31, 2011" t:url=https://data.oregon.gov/api/views/qcm5-94wv

property e:qcm5-94wv t:meta.view v:id=qcm5-94wv v:category="Revenue & Expense" v:averageRating=0 v:name="Summary of Expired Contracts - As of December 31, 2011"

property e:qcm5-94wv t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:qcm5-94wv t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                          | award_number_w_amendments | award_title                                                     | award_type                         | contractor_information                                        | street_address          | city         | state | zip_code | original_start_dateamendment_date | expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | ==================================== | ========================= | =============================================================== | ================================== | ============================================================= | ======================= | ============ | ===== | ======== | ================================= | =============== | ==================== | =============== | ============================== | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116598-5         | SOC Tribal Grant - Child Welfare                                | Intergovernment Agreement (ORS190) | Cow Creek Band of Umpqua Indians                              | 2371 Stephens Suite 100 | Roseburg     | OR    | 97470    | 04/04/2006 04/05/2006             | 12/31/2011      | 15160.00             | 15160.00        | 15160.00                       | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116599-5         | SOC Tribal Grant                                                | Intergovernment Agreement (ORS190) | Coquille Indian Tribe (ORCPP)                                 | PO Box 783              | North Bend   | OR    | 97459    | 04/03/2006 04/04/2006             | 12/31/2011      | 6361.00              | 6361.00         | 6361.00                        | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116602-5         | SOC Tribal Grant                                                | Intergovernment Agreement (ORS190) | Confederated Tribes of Umatilla (ORCPP)                       | PO Box 638              | Pendleton    | OR    | 97801    | 04/25/2006 04/27/2006             | 12/31/2011      | 44357.00             | 44357.00        | 44357.00                       | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116603-5         | SOC Grant to Tribes                                             | Intergovernment Agreement (ORS190) | Confederated Tribes of Warm Springs - Tribal PD               | PO Box 1329             | Warm Springs | OR    | 97761    | 03/23/2006 04/03/2006             | 12/31/2011      | 0.00                 | 0.00            | 0.00                           | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116610-5         | SOC Tribal Grant                                                | Intergovernment Agreement (ORS190) | Burns-Paiute Tribe (ORCPP)                                    | HC 71 100 Pasigo Street | Burns        | OR    | 97720    | 04/25/2006 04/27/2006             | 12/31/2011      | 2445.00              | 2445.00         | 2445.00                        | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116600-5         | SOC Tribal Grant                                                | Intergovernment Agreement (ORS190) | Confederated Tribes of Coos, Lower Umpqua and Siuslaw (ORCPP) | 1245 Fulton Avenue      | Coos Bay     | OR    | 97420    | 04/14/2006 04/14/2006             | 12/31/2011      | 15258.00             | 15258.00        | 15258.00                       | 
| 100100        | DHS - Children, Adults, and Families | 100000DHS116596-5         | SOC Grant - Child Welfare                                       | Intergovernment Agreement (ORS190) | Klamath Tribes of Oregon                                      | PO Box 436              | Chiloquin    | OR    | 97624    | 03/17/2006 03/20/2006             | 12/31/2011      | 28462.00             | 28462.00        | 28462.00                       | 
| 730000-SSB    | ODOT - Support Services              | 730000-23100-IGA-5        | Wildlife Damage/Conflict Management Assistance-Time & Materials | Intergovernment Agreement (ORS190) | Agriculture, Department of                                    |                         |              |       |          | 03/03/2006 03/17/2006             | 12/31/2011      | 2000000.00           | 2000000.00      | 2000000.00                     | 
| 730000-SSB    | ODOT - Support Services              | 730000-23128-IGA-5        | Wildlife Damage/Conflict Management Provided by APHIS Liaison   | Intergovernment Agreement (ORS190) | Agriculture, Department of                                    |                         |              |       |          | 03/06/2006 03/17/2006             | 12/31/2011      | 515000.00            | 515000.00       | 515000.00                      | 
| 100100        | DHS - Children, Adults, and Families | DHS116597-5               | SOC Tribal Grant                                                | Intergovernment Agreement (ORS190) | Confederated Tribes of Grand Ronde (ORCPP)                    | 9615 Grand Ronde RD     | Grande Ronde | OR    | 97347    | 07/12/2006 07/31/2006             | 12/31/2011      | 54782.00             | 54782.00        | 54782.00                       | 
```