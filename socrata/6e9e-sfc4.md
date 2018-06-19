# ORPIN - Contracts Report: FY 2010-2016 - Composite Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/orpin-contracts-report-fy-2010-2016-composite-dataset) |
| Metadata | [Link](https://data.oregon.gov/api/views/6e9e-sfc4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6e9e-sfc4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6e9e-sfc4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6e9e-sfc4 |
| Name | ORPIN - Contracts Report: FY 2010-2016 - Composite Dataset |
| Category | Revenue & Expense |
| Tags | orpin, orpin contracts, contracts, agency contracts, state contracts, state contracts 2009 - 2016, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, composite dataset, composite data set |
| Created | 2016-12-10T10:22:49Z |
| Publication Date | 2016-12-10T10:45:44Z |

## Description

This is a composite dataset that contains all versions of contracts and amendments issued in ORPIN from July 1, 2009 through June 30, 2016, and is sorted by agency number.  Note: Within the ORPIN system, the contract start date may be different than the contract issued date, which is the date the data entry was completed and the contract was entered in the ORPIN system.
For more information go to the Oregon Transparency Website. http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | agency_number                  | Agency Number                  | text          | number        |
| Yes      | series tag     | agency_name                    | Agency Name                    | text          | text          |
| Yes      | series tag     | document_number                | Document Number                | text          | text          |
| Yes      | series tag     | amendment_number               | Amendment Number               | text          | number        |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | series tag     | street_address                 | Street Address                 | text          | text          |
| Yes      | series tag     | street_address_line_2          | Street Address Line 2          | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | state                          | State                          | text          | text          |
| Yes      | series tag     | zip_code                       | Zip Code                       | text          | text          |
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
series e:6e9e-sfc4 d:2013-12-19T00:00:00.000Z t:document_number=165-1146-13 t:zip_code=97020 t:amendment_number=1001 t:state=OR t:award_type="Trade Services" t:agency_number=2000 t:award_title="Records Center Warehouse Shelving Project" t:street_address="21150 Butteville Rd. Ne" t:agency_name=Archives t:contractor_information="Material Flow & Conveyor Systems Inc." t:city=Donald m:amendment_value=0 m:total_award_value_w_amendments=39000 m:original_award_value=39000

series e:6e9e-sfc4 d:2012-10-08T00:00:00.000Z t:document_number=165-1119-12 t:zip_code=97317 t:amendment_number=2 t:state=OR t:award_type="Trade Services" t:agency_number=2000 t:award_title="Service of Fire Extingishers at the State Records Center" t:street_address="3062 Wiltsey Street SE" t:agency_name=Archives t:contractor_information="All Out Fire" t:city=Salem m:amendment_value=0 m:total_award_value_w_amendments=1500 m:original_award_value=1500

series e:6e9e-sfc4 d:2014-08-07T00:00:00.000Z t:document_number=165-150032-14 t:zip_code=97301 t:amendment_number=1000 t:state=OR t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=2000 t:award_title="Electronic Records Management Services" t:street_address="155 Cottage Street NE, 5th Floor" t:agency_name=Archives t:contractor_information="Administrative Services, Department of - Director's Office" t:city=Salem m:amendment_value=0 m:total_award_value_w_amendments=0 m:original_award_value=0
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:6e9e-sfc4 l:"ORPIN - Contracts Report: FY 2010-2016 - Composite Dataset" t:url=https://data.oregon.gov/api/views/6e9e-sfc4

property e:6e9e-sfc4 t:meta.view v:id=6e9e-sfc4 v:category="Revenue & Expense" v:averageRating=0 v:name="ORPIN - Contracts Report: FY 2010-2016 - Composite Dataset"

property e:6e9e-sfc4 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6e9e-sfc4 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name | document_number | amendment_number | award_title                                                      | award_type                              | contractor_information                                     | street_address                   | street_address_line_2 | city     | state | zip_code   | original_start_date | amendment_date      | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | =========== | =============== | ================ | ================================================================ | ======================================= | ========================================================== | ================================ | ===================== | ======== | ===== | ========== | =================== | =================== | =================== | ==================== | =============== | ============================== | 
| 2000          | Archives    | 165-1146-13     | 1001             | Records Center Warehouse Shelving Project                        | Trade Services                          | Material Flow & Conveyor Systems Inc.                      | 21150 Butteville Rd. Ne          |                       | Donald   | OR    | 97020      | 2013-12-19T00:00:00 | 2014-10-22T00:00:00 | 2014-12-31T00:00:00 | 39000                | 0.0000          | 39000                          | 
| 2000          | Archives    | 165-1119-12     | 2                | Service of Fire Extingishers at the State Records Center         | Trade Services                          | All Out Fire                                               | 3062 Wiltsey Street SE           |                       | Salem    | OR    | 97317      | 2012-10-08T00:00:00 | 2015-03-30T00:00:00 | 2020-10-01T00:00:00 | 1500                 | 0.0000          | 1500                           | 
| 2000          | Archives    | 165-150032-14   | 1000             | Electronic Records Management Services                           | Intergovernment Agreement (ORS190)      | Administrative Services, Department of - Director's Office | 155 Cottage Street NE, 5th Floor |                       | Salem    | OR    | 97301      | 2014-08-07T00:00:00 | 2016-06-21T00:00:00 | 2017-06-30T00:00:00 | 0.0000               | 0.0000          | 0.0000                         | 
| 2000          | Archives    | 165-150051-14   | 0                | ORMS Between Secretary of State and Construction Contractors Boa | Intergovernment Agreement (ORS190)      | Construction Contractors Board                             | 700 Summer St NE                 |                       | Salem    | OR    | 97309      | 2014-12-19T00:00:00 | 2014-12-22T00:00:00 | 2016-06-30T00:00:00 | 0.0000               | 0.0000          | 0.0000                         | 
| 2000          | Archives    | 165-150049-14   | 0                | IAA Secretary of State and Port of Coos Bay ORMS                 | Intergovernment Agreement (ORS190)      | Port of Coos Bay (ORCPP)                                   | P.O. Box 1215                    |                       | Coos Bay | OR    | 97420      | 2014-12-19T00:00:00 | 2014-12-22T00:00:00 | 2016-06-30T00:00:00 | 0.0000               | 0.0000          | 0.0000                         | 
| 2000          | Archives    | 165-1074-11     | 3001             | Janitorial Services for the Records Center                       | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)                                | PO Box 13970                     |                       | Salem    | OR    | 97309      | 2011-09-28T00:00:00 | 2015-04-01T00:00:00 | 2015-09-30T00:00:00 | 2000                 | 0.0000          | 7989                           | 
| 2000          | Archives    | 165-1146-13     | 0                | Records Center Warehouse Shelving Project                        | Trade Services                          | Material Flow & Conveyor Systems Inc.                      | 21150 Butteville Rd. Ne          |                       | Donald   | OR    | 97020      | 2013-12-19T00:00:00 | 2013-12-20T00:00:00 | 2014-12-31T00:00:00 | 39000                | 39000           | 39000                          | 
| 2000          | Archives    | 165-1065-14     | 0                | The use of Oregon Revised Statutes (OAR's)                       | Agreement to Agree                      | CCH Incorporated                                           | 4025 W Peterson Ave              |                       | Chicago  | IL    | 60646-6085 | 2014-03-07T00:00:00 | 2014-03-19T00:00:00 | 2015-12-31T00:00:00 | 10000                | 10000           | 10000                          | 
| 2000          | Archives    | 165-1074-11     | 2001             | Janitorial Services for the Records Center                       | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)                                | 3334 Industrial Way NE           | PO Box 7310           | Salem    | OR    | 97303      | 2011-09-28T00:00:00 | 2014-04-04T00:00:00 | 2014-09-30T00:00:00 | 2000                 | 0.0000          | 4016                           | 
| 2000          | Archives    | 165-1119-12     | 1                | Service of Fire Extingishers at the State Records Center         | Trade Services                          | All Out Fire                                               | 3062 Wiltsey Street SE           |                       | Salem    | OR    | 97317      | 2012-10-08T00:00:00 | 2015-03-23T00:00:00 | 2020-10-01T00:00:00 | 1500                 | 0.0000          | 1500                           | 
```