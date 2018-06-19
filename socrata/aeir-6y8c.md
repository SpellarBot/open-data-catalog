# Contracts: Agencies: As of June 30, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-agencies-as-of-june-30-2011-47513) |
| Metadata | [Link](https://data.oregon.gov/api/views/aeir-6y8c) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/aeir-6y8c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/aeir-6y8c/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | aeir-6y8c |
| Name | Contracts: Agencies: As of June 30, 2011 |
| Category | Revenue & Expense |
| Created | 2011-12-18T22:28:31Z |
| Publication Date | 2011-12-19T21:32:42Z |

## Description

This report provides information on contracts and amendments to contracts issued from July 1, 2010 - June 30, 2011, for state agencies who are subject to DAS contracting authority. These agencies must report their contracting activity through the Oregon Procurement Information Network (ORPIN) system. The contract values reflected in this report are estimates.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | agency_number                                    | Agency Number                                    | text      | number      |
| Yes      | series tag     | agency_name                                      | Agency Name                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments                        | Award Number w/Amendments                        | text      | text        |
| Yes      | series tag     | award_title                                      | Award Title                                      | text      | text        |
| Yes      | series tag     | award_type                                       | Award Type                                       | text      | text        |
| Yes      | series tag     | contractor_information                           | Contractor Information                           | text      | text        |
| Yes      | series tag     | street_address                                   | Street Address                                   | text      | text        |
| Yes      | series tag     | city                                             | City                                             | text      | text        |
| Yes      | series tag     | state                                            | State                                            | text      | text        |
| Yes      | series tag     | zip_code                                         | Zip Code                                         | text      | text        |
| No       |                | original_start_dateamendment_dateexpiration_date | Original Start DateAmendment DateExpiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                             | Original Award Value                             | money     | money       |
| Yes      | numeric metric | amendment_value                                  | Amendment Value                                  | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                   | Total Award Value w/Amendments                   | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_dateamendment_dateexpiration_date
```

## Data Commands

```ls
series e:aeir-6y8c d:2011-01-01T00:00:00.000Z t:zip_code=97303 t:award_number_w_amendments="102-1110-07 (0.3)" t:state=OR t:award_type="Qualified Rehabilitation Facility (QRF)" t:award_title="Janitorial Services for DHS Office, 1899 Willamette St. Eugene" t:agency_number=100000 t:street_address="3334 Industrial Way NE
PO Box 7310" t:agency_name="DHS - Department of Human Services" t:contractor_information="Garten Services, Inc. (QRF)" t:city=Salem m:amendment_value=0 m:total_award_value_w_amendments=257000 m:original_award_value=257000

series e:aeir-6y8c d:2011-01-01T00:00:00.000Z t:zip_code=97501 t:award_number_w_amendments="DHS117456-5 (3)" t:state=OR t:award_type="Qualified Rehabilitation Facility (QRF)" t:award_title="Janitorial Services for DHS Office at 100 E. Main, Medford" t:agency_number=100000 t:street_address="PO Box 1105" t:agency_name="DHS - Department of Human Services" t:contractor_information="Living Opportunities, Inc. (QRF)" t:city=Medford m:amendment_value=8262 m:total_award_value_w_amendments=36147 m:original_award_value=20350

series e:aeir-6y8c d:2011-01-01T00:00:00.000Z t:zip_code=19073 t:award_number_w_amendments=DHS-132689-10 t:state=PA t:award_type="Personal Services (PSK) Non-IT" t:award_title="Temporary ?Extended Placement? Nursing Personnel" t:agency_number=100000 t:street_address="3805 West Chester Pike, Ste 200" t:agency_name="DHS - Department of Human Services" t:contractor_information="MedStaff Inc." t:city="Newtown Square" m:amendment_value=309000 m:total_award_value_w_amendments=309000 m:original_award_value=309000
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:aeir-6y8c l:"Contracts: Agencies: As of June 30, 2011" t:url=https://data.oregon.gov/api/views/aeir-6y8c

property e:aeir-6y8c t:meta.view v:id=aeir-6y8c v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Agencies: As of June 30, 2011"

property e:aeir-6y8c t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:aeir-6y8c t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                        | award_number_w_amendments | award_title                                                    | award_type                              | contractor_information                | street_address                         | city           | state | zip_code | original_start_dateamendment_dateexpiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | ================================== | ========================= | ============================================================== | ======================================= | ===================================== | ====================================== | ============== | ===== | ======== | ================================================ | ==================== | =============== | ============================== | 
| 100000        | DHS - Department of Human Services | 102-1110-07 (0.3)         | Janitorial Services for DHS Office, 1899 Willamette St. Eugene | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)           | 3334 Industrial Way NE PO Box 7310     | Salem          | OR    | 97303    | 05/01/2007 07/20/2010 05/01/2012                 | 257000.00            | 0.00            | 257000.00                      | 
| 100000        | DHS - Department of Human Services | DHS117456-5 (3)           | Janitorial Services for DHS Office at 100 E. Main, Medford     | Qualified Rehabilitation Facility (QRF) | Living Opportunities, Inc. (QRF)      | PO Box 1105                            | Medford        | OR    | 97501    | 06/30/2006 08/02/2010 07/31/2011                 | 20350.00             | 8262.00         | 36147.00                       | 
| 100000        | DHS - Department of Human Services | DHS-132689-10             | Temporary ?Extended Placement? Nursing Personnel               | Personal Services (PSK) Non-IT          | MedStaff Inc.                         | 3805 West Chester Pike, Ste 200        | Newtown Square | PA    | 19073    | 08/13/2010 08/18/2010 06/30/2011                 | 309000.00            | 309000.00       | 309000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-132691-10             | Temporary ?Extended Placement? Nursing Personnel               | Personal Services (PSK) Non-IT          | Worldwide Travel Staffing, Limited    | 2829 Sheridan Dr                       | Tonawanda      | NY    | 14150    | 08/04/2010 08/04/2010 06/30/2012                 | 362000.00            | 362000.00       | 362000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-1076-10               | Budget vs. Actual Phase 2 and 3 Project Management             | Work Order Against ATA                  | nextSource, Inc                       | 9450 SW Commerce Circle Suite 440      | Wilsonville    | OR    | 97070    | 11/10/2010 11/24/2010 12/31/2011                 | 149400.00            | 149400.00       | 149400.00                      | 
| 100000        | DHS - Department of Human Services | DHS-132691-10 (1)         | Temporary ?Extended Placement? Nursing Personnel               | Personal Services (PSK) Non-IT          | Worldwide Travel Staffing, Limited    | 2829 Sheridan Dr                       | Tonawanda      | NY    | 14150    | 08/04/2010 12/09/2010 06/30/2012                 | 362000.00            | 0.00            | 362000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-132690-10 (1)         | Temporary ?Extended Placement? Nursing Personnel               | Personal Services (PSK) Non-IT          | On Assignment Staffing Services, Inc. | 9987 Carver Road Suite 510             | Blue Ash       | OH    | 45242    | 08/02/2010 12/28/2010 06/30/2012                 | 311000.00            | 0.00            | 311000.00                      | 
| 100000        | DHS - Department of Human Services | 4102 (5.2)                | REFERENCE LABORATORY TESTING SERVICES                          | Trade Services                          | Quest Diagnostics Inc.                | 6600 SW Hampton St                     | Portland       | OR    | 97223    | 06/16/2004 01/10/2011 06/15/2012                 | 11000.00             | 0.00            | 2442000.00                     | 
| 100000        | DHS - Department of Human Services | 2101 (9.2)                | TANDEM QUADRUPOLE MASS SPECTROMETER SYSTEMS AND                | Price Agreement                         | Perkinelmer Life Sciences, Inc.       | (Perkinelmer LAS, Inc) 3985 Eastern Rd | Norton         | OH    | 85058    | 04/11/2002 01/25/2011 03/31/2012                 | 726976.90            | 0.00            | 888000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-132692-10 (1)         | Temporary ?Extended Placement? Nursing Personnel               | Personal Services (PSK) Non-IT          | Maxim Healthcare Services             | 600 N Westshore Blvd Suite 600         | Tampa          | FL    | 33609    | 08/30/2010 01/20/2011 06/30/2012                 | 369000.00            | 0.00            | 369000.00                      | 
```