# Contracts: Agencies: As of June 30, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-agencies-as-of-june-30-2013-7b10e) |
| Metadata | [Link](https://data.oregon.gov/api/views/ef3h-wxwx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ef3h-wxwx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ef3h-wxwx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ef3h-wxwx |
| Name | Contracts: Agencies: As of June 30, 2013 |
| Category | Revenue & Expense |
| Tags | contracts, agency contracts, state contracts |
| Created | 2013-11-06T19:50:52Z |
| Publication Date | 2013-11-06T20:00:15Z |

## Description

This report provides information on contracts and amendments to contracts issued from July 1, 2012 - June 30, 2013, for state agencies who are subject to DAS contracting authority. These agencies must report their contracting activity through the Oregon Procurement Information Network (ORPIN) system. The contract values reflected in this report are estimates.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | agency_number                  | Agency Number                  | text          | number        |
| Yes      | series tag     | agency_name                    | Agency Name                    | text          | text          |
| Yes      | series tag     | award_number_w_amendments      | Award Number w/Amendments      | text          | text          |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | series tag     | street_address                 | Street Address                 | text          | text          |
| Yes      | series tag     | zip_code                       | Zip Code                       | text          | number        |
| Yes      | time           | original_start_date            | Original Start Date            | calendar_date | calendar_date |
| No       |                | amendment_date                 | Amendment Date                 | calendar_date | calendar_date |
| No       |                | expiration_date                | Expiration Date                | calendar_date | calendar_date |
| Yes      | numeric metric | original_award_value           | Original Award Value           | money         | money         |
| Yes      | numeric metric | amendment_value                | Amendment Value                | money         | money         |
| Yes      | numeric metric | total_award_value_w_amendments | Total Award Value w/Amendments | money         | money         |
```

## Time Field

```ls
Value = original_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = amendment_date,expiration_date
```

## Data Commands

```ls
series e:ef3h-wxwx d:2012-08-27T00:00:00.000Z t:zip_code=97330 t:award_number_w_amendments=165-130017-12 t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=6000 t:award_title="Agreement to Produce Joint Voters Pamphlet 2012 General Election" t:street_address="Elections Division
120 NW 4th Street" t:agency_name=Elections t:contractor_information="Benton County (pl)" m:amendment_value=0 m:total_award_value_w_amendments=0 m:original_award_value=0

series e:ef3h-wxwx d:2012-11-28T00:00:00.000Z t:zip_code=72956 t:award_number_w_amendments=165-1136-12 t:award_type="Trade Services" t:agency_number=2000 t:award_title="Contractor Use of the 2013 Oregon Revised Statutes" t:street_address="105 North 28th Street" t:agency_name=Archives t:contractor_information="Loislaw Inc." m:amendment_value=5000 m:total_award_value_w_amendments=5000 m:original_award_value=5000

series e:ef3h-wxwx d:2012-10-08T00:00:00.000Z t:zip_code=97317 t:award_number_w_amendments=165-1119-12 t:award_type="Trade Services" t:agency_number=2000 t:award_title="Service of Fire Extingishers at the State Records Center" t:street_address="3062 Wiltsey Street SE" t:agency_name=Archives t:contractor_information="All Out Fire" m:amendment_value=1500 m:total_award_value_w_amendments=1500 m:original_award_value=1500
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:ef3h-wxwx l:"Contracts: Agencies: As of June 30, 2013" t:url=https://data.oregon.gov/api/views/ef3h-wxwx

property e:ef3h-wxwx t:meta.view v:id=ef3h-wxwx v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Agencies: As of June 30, 2013"

property e:ef3h-wxwx t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ef3h-wxwx t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name     | award_number_w_amendments | award_title                                                      | award_type                              | contractor_information                       | street_address                                     | zip_code | original_start_date | amendment_date      | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | =============== | ========================= | ================================================================ | ======================================= | ============================================ | ================================================== | ======== | =================== | =================== | =================== | ==================== | =============== | ============================== | 
| 6000          | Elections       | 165-130017-12             | Agreement to Produce Joint Voters Pamphlet 2012 General Election | Intergovernment Agreement (ORS190)      | Benton County (pl)                           | Elections Division 120 NW 4th Street               | 97330    | 2012-08-27T00:00:00 | 2012-08-30T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00            | 0.00                           | 
| 2000          | Archives        | 165-1136-12               | Contractor Use of the 2013 Oregon Revised Statutes               | Trade Services                          | Loislaw Inc.                                 | 105 North 28th Street                              | 72956    | 2012-11-28T00:00:00 | 2012-11-28T00:00:00 | 2013-12-31T00:00:00 | 5000.00              | 5000.00         | 5000.00                        | 
| 2000          | Archives        | 165-1119-12               | Service of Fire Extingishers at the State Records Center         | Trade Services                          | All Out Fire                                 | 3062 Wiltsey Street SE                             | 97317    | 2012-10-08T00:00:00 | 2012-10-08T00:00:00 | 2020-10-01T00:00:00 | 1500.00              | 1500.00         | 1500.00                        | 
| 6000          | Elections       | 165-130021-12             | Agreement to Produce Joint Voters Pamphlet 2012 General Election | Intergovernment Agreement (ORS190)      | Multnomah County (pl)                        | Multnomah County Elections 1040 SE Morrison Street | 97214    | 2012-08-27T00:00:00 | 2012-08-30T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00            | 0.00                           | 
| 3000          | Audits          | 165-1139-12               | Audits Training Constructing Findings Class                      | Trade Services                          | Eric Spivak                                  | 1700 19th St NE                                    | 97301    | 2012-12-27T00:00:00 | 2012-12-28T00:00:00 | 2013-03-30T00:00:00 | 3750.00              | 3750.00         | 3750.00                        | 
| 4300          | Human Resources | 107-3124-12               | Transformational Coaching                                        | Personal Services (PSK) Non-IT          | RABINER RESOURCES                            | 536 SW WESTWOOD DRIVE                              | 97201    | 2012-09-18T00:00:00 | 2012-12-12T00:00:00 | 2012-11-02T00:00:00 | 3800.00              | 3800.00         | 3800.00                        | 
| 6000          | Elections       | 165-1114-12               | Desktop Publishing for the Oregon Voters Pamphlet General Elect  | Trade Services                          | Ryder Graphics / Ryder Election Services LLC | 370 SW Columbia St.                                | 97702    | 2012-08-10T00:00:00 | 2012-08-10T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00         | 5000.00                        | 
| 2000          | Archives        | 165-1134-12               | Use of 2013 Oregon Administrative Rule                           | Trade Services                          | LexisNexis                                   | 701 E. Clear Water ST                              | 22902    | 2012-11-09T00:00:00 | 2012-12-26T00:00:00 | 2013-12-31T00:00:00 | 5000.00              | 5000.00         | 5000.00                        | 
| 6000          | Elections       | 165-130025-12             | Agreement to Produce a joint Voters Pamphlet 2012 General Elec   | Intergovernment Agreement (ORS190)      | Yamhill County (pl)                          | County Elections 414 NE Evans Street               | 97128    | 2012-09-17T00:00:00 | 2012-09-19T00:00:00 | 2012-11-06T00:00:00 | 0.00                 | 0.00            | 0.00                           | 
| 2000          | Archives        | 165-1074-11 (1.2)         | Janitorial Services for the Records Center                       | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)                  | 3334 Industrial Way NE PO Box 7310                 | 97303    | 2011-09-28T00:00:00 | 2012-07-18T00:00:00 | 2013-09-30T00:00:00 | 2000.00              | 0.00            | 2000.00                        | 
```