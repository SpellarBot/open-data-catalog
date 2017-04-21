# Summary of Expired Contracts - As of June 30, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-of-expired-contracts-as-of-june-30-2013-197da) |
| Metadata | [Link](https://data.oregon.gov/api/views/tama-bhrk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tama-bhrk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tama-bhrk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tama-bhrk |
| Name | Summary of Expired Contracts - As of June 30, 2013 |
| Category | Revenue & Expense |
| Tags | contracts, expired contracts, agency expired contracts |
| Created | 2013-11-06T20:17:17Z |
| Publication Date | 2013-11-06T20:21:19Z |

## Description

The following data is provided as an extract from the Statewide Procurement System (Oregon Procurement Information Network - ORPIN). It is a complete list of contracts that expired on or before June 30, 2013 and represents the full extent of electronic records of expired contracts that are tracked within ORPIN. The contract values reflected in the report are estimates only. Note: A number of contracts may indicate an ?Amendment Date? that may exceed the ?Expiration Date?. In these instances, the ?Amendment Date? reflects an automated system time/date stamp that the system appends to the contract when the electronic version was accessed or modified, not necessarily when the legal instrument (the contract itself) was modified. Note: This report may not include contract information for the Oregon Judicial Department, Oregon State Lottery, Oregon University System, Oregon State Treasurer, or semi-independent state agencies, boards, and commissions. Some executive branch agencies have independent contracting authority for specific goods and services (e.g., Transportation, Secretary of State, State Treasurer, Human Services, Fish and Wildlife, Parks and Recreation, Aviation, Economic and Community Development, Housing, Corrections, Veterans Affairs, Military, Education, and state agencies "specifically authorized" by any law outside the Code to "enter into a contract"). Thus, the ORPIN system may not capture contract information about those activities.

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
series e:tama-bhrk d:2012-12-27T00:00:00.000Z t:issued_for_agency_number=3000 t:issued_by_agency_name="Administrative Division" t:zip_code=97301 t:award_number_w_amendments=165-1139-12 t:issued_for_agency_name=Audits t:award_type="Trade Services" t:award_title="Audits Training Constructing Findings Class" t:street_address="1700 19th St NE" t:contractor_information="Eric Spivak" m:total_award_value_w_amendments=3750 m:original_award_value=3750

series e:tama-bhrk d:2011-11-29T00:00:00.000Z t:issued_for_agency_number=2000 t:issued_by_agency_name="Administrative Division" t:award_number_w_amendments=165-1055-12 t:issued_for_agency_name=Archives t:award_type="Agreement to Agree" t:award_title="Use of 2012 OAR Licensing agreement" t:street_address="4025 W Peterson Ave" t:contractor_information="CCH Incorporated" m:total_award_value_w_amendments=5000 m:original_award_value=5000

series e:tama-bhrk d:2012-09-17T00:00:00.000Z t:issued_for_agency_number=6000 t:issued_by_agency_name="Administrative Division" t:zip_code=97128 t:award_number_w_amendments=165-130025-12 t:issued_for_agency_name=Elections t:award_type="Intergovernment Agreement (ORS190)" t:award_title="Agreement to Produce a joint Voters Pamphlet 2012 General Elec" t:street_address="County Elections" t:contractor_information="Yamhill County (pl)" m:total_award_value_w_amendments=0 m:original_award_value=0
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:tama-bhrk l:"Summary of Expired Contracts - As of June 30, 2013" t:url=https://data.oregon.gov/api/views/tama-bhrk

property e:tama-bhrk t:meta.view v:id=tama-bhrk v:category="Revenue & Expense" v:averageRating=0 v:name="Summary of Expired Contracts - As of June 30, 2013"

property e:tama-bhrk t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tama-bhrk t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| issued_for_agency_number | issued_for_agency_name | issued_by_agency_name   | award_number_w_amendments | award_title                                                      | award_type                              | contractor_information                 | street_address             | zip_code | original_start_date | expiration_date     | original_award_value | total_award_value_w_amendments | 
| ======================== | ====================== | ======================= | ========================= | ================================================================ | ======================================= | ====================================== | ========================== | ======== | =================== | =================== | ==================== | ============================== | 
| 3000                     | Audits                 | Administrative Division | 165-1139-12               | Audits Training Constructing Findings Class                      | Trade Services                          | Eric Spivak                            | 1700 19th St NE            | 97301    | 2012-12-27T00:00:00 | 2013-03-30T00:00:00 | 3750.00              | 3750.00                        | 
| 2000                     | Archives               | Administrative Division | 165-1055-12               | Use of 2012 OAR Licensing agreement                              | Agreement to Agree                      | CCH Incorporated                       | 4025 W Peterson Ave        |          | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 6000                     | Elections              | Administrative Division | 165-130025-12             | Agreement to Produce a joint Voters Pamphlet 2012 General Elec   | Intergovernment Agreement (ORS190)      | Yamhill County (pl)                    | County Elections           | 97128    | 2012-09-17T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00                           | 
| 3000                     | Audits                 | Administrative Division | 165-1055-11               | Licenses, Maintenance and Support for Nuance PDF Convertor 7 Ent | Trade Services                          | SHI International Corp.                | 33 Knightsbridge Rd        | 8854     | 2011-09-12T00:00:00 | 2012-09-11T00:00:00 | 7000.00              | 7000.00                        | 
| 6000                     | Elections              | Administrative Division | 165-130021-12             | Agreement to Produce Joint Voters Pamphlet 2012 General Election | Intergovernment Agreement (ORS190)      | Multnomah County (pl)                  | Multnomah County Elections | 97214    | 2012-08-27T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00                           | 
| 2000                     | Archives               | Administrative Division | 165-1056-12               | 2012 OAR Licensing Agreement                                     | Agreement to Agree                      | LexisNexis a division of Reed Elseiver | 4717 194th Ave SE          | 98027    | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Secretary of State      | 165-1000-11               | Records Center Janitorial Services                               | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)            | 3334 Industrial Way NE     | 97303    | 2011-09-28T00:00:00 | 2012-09-27T00:00:00 | 2000.00              | 2000.00                        | 
| 6000                     | Elections              | Administrative Division | 165-130018-12             | Agreement for Joint Voters Pamphlet 2012 General Election        | Intergovernment Agreement (ORS190)      | Jackson County (pl)                    | Elections Division         | 97501    | 2012-09-12T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00                           | 
| 6000                     | Elections              | Administrative Division | 165-130023-12             | Agreement to Produce a Joint Voters Pamphlet for 2012 General El | Intergovernment Agreement (ORS190)      | Josephine County (pl)                  | Elections                  | 97528    | 2012-09-05T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00                           | 
| 6000                     | Elections              | Administrative Division | 165-130026-12             | Agreement to Produce Joint Voters Pamphlet 2012 General Elec     | Intergovernment Agreement (ORS190)      | Clackamas County (pl)                  | Elections                  | 97045    | 2012-08-27T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00                           | 
```