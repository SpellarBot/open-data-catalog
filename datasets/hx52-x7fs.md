# 2015 - Summary of Expired Contracts - As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-summary-of-expired-contracts-as-of-june-30-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/hx52-x7fs) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hx52-x7fs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hx52-x7fs/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hx52-x7fs |
| Name | 2015 - Summary of Expired Contracts - As of June 30, 2015 |
| Category | Revenue & Expense |
| Tags | 2015; contracts; expired contracts; agency expired contracts; 2015 expired contracts |
| Created | 2016-01-01T04:47:11Z |
| Publication Date | 2016-01-01T05:02:05Z |

## Description

The following data is provided as an extract from the Statewide Procurement System (Oregon Procurement Information Network - ORPIN). For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| No       |                | fiscal_year                    | Fiscal Year                    | number        | number        |
| Yes      | series tag     | issued_for_agency_number       | Issued For Agency Number       | text          | number        |
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
Excluded Fields = expiration_date,fiscal_year
```

## Data Commands

```ls
series e:hx52-x7fs d:2014-06-17T00:00:00.000Z t:issued_for_agency_number=63400 t:issued_by_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_number_w_amendments="OPRD-7069-14 (1)" t:issued_for_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="7069 Law Enforcement Services Snowy Plover Recovery Area" t:contractor_information="Coos County (pl)" m:total_award_value_w_amendments=10000 m:original_award_value=10000

series e:hx52-x7fs d:2014-06-17T00:00:00.000Z t:issued_for_agency_number=63400 t:issued_by_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_number_w_amendments=OPRD-7069-14 t:issued_for_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="7069 Law Enforcement Services Snowy Plover Recovery Area" t:contractor_information="Coos County (pl)" m:total_award_value_w_amendments=10000 m:original_award_value=10000

series e:hx52-x7fs d:2011-03-25T00:00:00.000Z t:issued_for_agency_number=63400 t:issued_by_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_number_w_amendments=OPRD-5949-11 t:issued_for_agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="5949 Tillamook Co. Sheriff Law Enforcement Cape Lookout" t:contractor_information="Tillamook County (pl)" m:total_award_value_w_amendments=64000 m:original_award_value=64000
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:hx52-x7fs l:"2015 - Summary of Expired Contracts - As of June 30, 2015" t:url=https://data.oregon.gov/api/views/hx52-x7fs

property e:hx52-x7fs t:meta.view v:id=hx52-x7fs v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - Summary of Expired Contracts - As of June 30, 2015"

property e:hx52-x7fs t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:hx52-x7fs t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | issued_for_agency_number | issued_for_agency_name                                    | issued_by_agency_name                                     | award_number_w_amendments | award_title                                              | award_type                         | contractor_information | street_address          | zip_code | original_start_date | expiration_date     | original_award_value | total_award_value_w_amendments | 
| =========== | ======================== | ========================================================= | ========================================================= | ========================= | ======================================================== | ================================== | ====================== | ======================= | ======== | =================== | =================== | ==================== | ============================== | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-7069-14 (1)          | 7069 Law Enforcement Services Snowy Plover Recovery Area | Intergovernment Agreement (ORS190) | Coos County (pl)       |                         |          | 2014-06-17T00:00:00 | 2014-09-15T00:00:00 | 10000.00             | 10000.00                       | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-7069-14              | 7069 Law Enforcement Services Snowy Plover Recovery Area | Intergovernment Agreement (ORS190) | Coos County (pl)       |                         |          | 2014-06-17T00:00:00 | 2014-09-15T00:00:00 | 10000.00             | 10000.00                       | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-5949-11              | 5949 Tillamook Co. Sheriff Law Enforcement Cape Lookout  | Intergovernment Agreement (ORS190) | Tillamook County (pl)  |                         |          | 2011-03-25T00:00:00 | 2014-12-31T00:00:00 | 64000.00             | 64000.00                       | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-5320-10              | 5320 Jefferson Co. law enforcement services              | Intergovernment Agreement (ORS190) | Jefferson County (pl)  |                         |          | 2010-04-01T00:00:00 | 2015-04-01T00:00:00 | 100000.00            | 100000.00                      | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-7108-14              | 7108 Rogue River Greenway Trail                          | Intergovernment Agreement (ORS190) | Jackson County (pl)    |                         |          | 2013-12-20T00:00:00 | 2015-06-30T00:00:00 | 134500.00            | 134500.00                      | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-6619-12              | 6619 Lane County Scenic Bikeway Signs                    | Intergovernment Agreement (ORS190) | Lane County (pl)       |                         |          | 2012-08-16T00:00:00 | 2015-06-30T00:00:00 | 2000.00              | 2000.00                        | 
| 2015        | 63400                    | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION | OPRD-6586-12              | 6586 Union County Bikeway Sign Installation              | Intergovernment Agreement (ORS190) | Union County (pl)      |                         |          | 2012-08-13T00:00:00 | 2015-06-30T00:00:00 | 3584.00              | 3584.00                        | 
| 2015        | 100000                   | DHS - Department of Human Services                        | DAS Procurement Services                                  | DASPS-2195-14             | IT Advisory Services                                     | Personal Services (PSK) Non-IT     | Public Knowledge LLC   | 1911 SW Campus Dr. #457 | 98023    | 2014-04-21T00:00:00 | 2014-07-11T00:00:00 | 92000.00             | 92000.00                       | 
| 2015        | 100000                   | DHS - Department of Human Services                        | DAS Procurement Services                                  | DASPS-2195-14 (1)         | IT Advisory Services                                     | Personal Services (PSK) Non-IT     | Public Knowledge LLC   | 1911 SW Campus Dr. #457 | 98023    | 2014-04-21T00:00:00 | 2014-07-11T00:00:00 | 92000.00             | 92000.00                       | 
| 2015        | 100000                   | DHS - Department of Human Services                        | DAS Procurement Services                                  | DASPS-2195-14 (2)         | IT Advisory Services                                     | Personal Services (PSK) Non-IT     | Public Knowledge LLC   | 1911 SW Campus Dr. #457 | 98023    | 2014-04-21T00:00:00 | 2014-10-21T00:00:00 | 92000.00             | 184000.00                      | 
```