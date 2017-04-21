# 2015 - Contracts: Agencies: As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-contracts-agencies-as-of-june-30-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/ui87-juba) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ui87-juba/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ui87-juba/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ui87-juba |
| Name | 2015 - Contracts: Agencies: As of June 30, 2015 |
| Category | Revenue & Expense |
| Tags | 2015; contracts; agency contracts; state contracts; state contracts 2015; contracts 2015 |
| Created | 2016-01-01T05:26:48Z |
| Publication Date | 2016-01-01T05:36:23Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| No       |                | fiscal_year                    | Fiscal Year                    | number        | number        |
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
Excluded Fields = amendment_date,expiration_date,fiscal_year
```

## Data Commands

```ls
series e:ui87-juba d:2014-08-28T00:00:00.000Z t:award_number_w_amendments=OPRD-7233-14 t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=63400 t:award_title="7233 McKenzie River Maint. Lane County" t:agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:contractor_information="Lane County (pl)" m:amendment_value=115029 m:total_award_value_w_amendments=115029 m:original_award_value=115029

series e:ui87-juba d:2014-07-02T00:00:00.000Z t:award_number_w_amendments=OPRD-7263-14 t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=63400 t:award_title="7263 Clatsop County Law enforcement at Parks" t:agency_name="OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION" t:contractor_information="Clatsop County (pl)" m:amendment_value=193040 m:total_award_value_w_amendments=193040 m:original_award_value=193040

series e:ui87-juba d:2015-05-01T00:00:00.000Z t:award_number_w_amendments=DHS-148432-15 t:award_type="Qualified Rehabilitation Facility (QRF)" t:agency_number=100020 t:award_title="148432 Bay Area Enterprises Coos Bay Office Janitorial" t:agency_name="DHS - Shared Services" t:contractor_information="Bay Area Enterprises, Inc. (QRF)" m:amendment_value=57174 m:total_award_value_w_amendments=57174 m:original_award_value=57174
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:ui87-juba l:"2015 - Contracts: Agencies: As of June 30, 2015" t:url=https://data.oregon.gov/api/views/ui87-juba

property e:ui87-juba t:meta.view v:id=ui87-juba v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - Contracts: Agencies: As of June 30, 2015"

property e:ui87-juba t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ui87-juba t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_number | agency_name                                                         | award_number_w_amendments | award_title                                                 | award_type                              | contractor_information                             | street_address                                 | zip_code | original_start_date | amendment_date      | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| =========== | ============= | =================================================================== | ========================= | =========================================================== | ======================================= | ================================================== | ============================================== | ======== | =================== | =================== | =================== | ==================== | =============== | ============================== | 
| 2015        | 63400         | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION           | OPRD-7233-14              | 7233 McKenzie River Maint. Lane County                      | Intergovernment Agreement (ORS190)      | Lane County (pl)                                   |                                                |          | 2014-08-28T00:00:00 | 2014-09-30T00:00:00 | 2024-12-31T00:00:00 | 115029.00            | 115029.00       | 115029.00                      | 
| 2015        | 63400         | OPRD - Agency - OREGON DEPARTMENT OF PARKS AND RECREATION           | OPRD-7263-14              | 7263 Clatsop County Law enforcement at Parks                | Intergovernment Agreement (ORS190)      | Clatsop County (pl)                                |                                                |          | 2014-07-02T00:00:00 | 2014-07-02T00:00:00 | 2019-07-30T00:00:00 | 193040.00            | 193040.00       | 193040.00                      | 
| 2015        | 100020        | DHS - Shared Services                                               | DHS-148432-15             | 148432 Bay Area Enterprises Coos Bay Office Janitorial      | Qualified Rehabilitation Facility (QRF) | Bay Area Enterprises, Inc. (QRF)                   |                                                |          | 2015-05-01T00:00:00 | 2015-06-12T00:00:00 | 2016-10-31T00:00:00 | 57174.00             | 57174.00        | 57174.00                       | 
| 2015        | 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation   | DHS-144810-14 (1)         | Motivational Ehancement Training (MET)perpetual use license | Personal Services (PSK) Non-IT          | PNA Change Consultants, Inc                        | 3590 Rivergate Way, Suite 1202 Ottawa, Ontario |          | 2014-03-04T00:00:00 | 2014-08-25T00:00:00 | 2014-09-30T00:00:00 | 55000.00             | 0.00            | 55000.00                       | 
| 2015        | 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation   | DHS-147935-15             | JOBS program - job opportunities and basic skills           | Intergovernment Agreement (ORS190)      | Benton County (pl)                                 |                                                |          | 2015-02-01T00:00:00 | 2015-04-02T00:00:00 | 2015-06-30T00:00:00 | 6681.00              | 6681.00         | 6681.00                        | 
| 2015        | 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation   | DHS-144810-14 (2)         | Motivational Ehancement Training (MET)perpetual use license | Personal Services (PSK) Non-IT          | PNA Change Consultants, Inc                        | 3590 Rivergate Way, Suite 1202 Ottawa, Ontario |          | 2014-03-04T00:00:00 | 2014-10-02T00:00:00 | 2014-10-31T00:00:00 | 55000.00             | 0.00            | 55000.00                       | 
| 2015        | 100800        | DHS - Aging & People with Disabilities & Developmental Disabilities | DHS-145025-14 (1)         | Oregon Money Management Program regional sponsor services   | Intergovernment Agreement (ORS190)      | Clackamas County (pl)                              |                                                |          | 2015-02-28T00:00:00 | 2014-07-17T00:00:00 | 2015-07-31T00:00:00 | 58000.00             | 15000.00        | 73000.00                       | 
| 2015        | 100800        | DHS - Aging & People with Disabilities & Developmental Disabilities | DHS-146558-14             | grant for innovative projects & pilots for APD clients      | Intergovernment Agreement (ORS190)      | Clackamas County (pl)                              |                                                |          | 2014-10-13T00:00:00 | 2014-10-14T00:00:00 | 2015-12-31T00:00:00 | 49960.00             | 49960.00        | 49960.00                       | 
| 2015        | 100800        | DHS - Aging & People with Disabilities & Developmental Disabilities | DHS-146812-14             | Nursing Facility Services                                   | Intergovernment Agreement (ORS190)      | Veterans Affairs, Oregon Department of             |                                                |          | 2014-10-20T00:00:00 | 2014-10-20T00:00:00 | 2019-12-31T00:00:00 | 72510900.00          | 72510900.00     | 72510900.00                    | 
| 2015        | 100800        | DHS - Aging & People with Disabilities & Developmental Disabilities | DASPS-2298-14             | Training and Technical Assistance for individuals with DD   | Personal Services (PSK) Non-IT          | The Washington Initiative for Supported Employment | 100 S. King St. Suite 260                      | 98104    | 2014-12-05T00:00:00 | 2014-12-04T00:00:00 | 2016-06-30T00:00:00 | 3497920.00           | 3497920.00      | 3497920.00                     | 
```