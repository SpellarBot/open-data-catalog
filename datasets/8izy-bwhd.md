# ORPIN - Expired Contracts Report: FY 2010-2016 - Composite Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/orpin-expired-contracts-report-fy-2010-2016-composite-dataset) |
| Metadata | [Link](https://data.oregon.gov/api/views/8izy-bwhd) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8izy-bwhd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8izy-bwhd/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8izy-bwhd |
| Name | ORPIN - Expired Contracts Report: FY 2010-2016 - Composite Dataset |
| Category | Revenue & Expense |
| Tags | expired contracts, agency contracts, state contracts, agency expired contracts, state contracts 2009 - 2016, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009 |
| Created | 2016-12-30T04:51:01Z |
| Publication Date | 2016-12-31T02:09:42Z |

## Description

This is a composite dataset that contains a listing of ORPIN contracts that expired between July 1, 2009 and June 30, 2016, and is sorted by agency number. Note: Within the ORPIN system, the contract start date may be different than the contract issued date, which is the date the data entry was completed and the contract was entered in the ORPIN system. For more information go to the Oregon Transparency Website. http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | issued_for_agency_number       | Issued For Agency Number       | text          | number        |
| Yes      | series tag     | issued_for_agency_name         | Issued For Agency Name         | text          | text          |
| Yes      | series tag     | issued_by_agency_name          | Issued By Agency Name          | text          | text          |
| Yes      | series tag     | document_number                | Document Number                | text          | text          |
| Yes      | series tag     | amendment_number               | Amendment Number               | text          | number        |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | series tag     | street_address                 | Street Address                 | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | state                          | State                          | text          | text          |
| Yes      | series tag     | zip_code                       | Zip Code                       | text          | text          |
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
series e:8izy-bwhd d:2010-10-01T00:00:00.000Z t:issued_for_agency_number=287 t:document_number=ED-1782-10 t:issued_by_agency_name="OED - Employment Department, Oregon" t:zip_code=97051 t:amendment_number=0 t:state=OR t:issued_for_agency_name="OED - Tualatin" t:award_type="Personal Services (PSK) Non-IT" t:award_title="OED #11-023, Experience Works Partner Service Sharing Agreement" t:street_address="2005 St Helens Street" t:contractor_information="Experience Works, Inc." t:city="Saint Helens" m:total_award_value_w_amendments=658 m:original_award_value=658

series e:8izy-bwhd d:2012-05-04T00:00:00.000Z t:issued_for_agency_number=2000 t:document_number=165-1109-12 t:issued_by_agency_name="Administrative Division" t:zip_code=97814 t:amendment_number=0 t:state=OR t:issued_for_agency_name=Archives t:award_type="Personal Services (PSK) IT" t:award_title="Chaves Consulting Ramp Up Operating costs" t:street_address="1705 MAIN ST STE 400" t:contractor_information="CHAVES CONSULTING, INC." t:city="Baker City" m:total_award_value_w_amendments=150000 m:original_award_value=150000

series e:8izy-bwhd d:2011-09-28T00:00:00.000Z t:issued_for_agency_number=2000 t:document_number=165-1074-11 t:issued_by_agency_name="Secretary of State" t:zip_code=97303 t:amendment_number=0 t:state=OR t:issued_for_agency_name=Archives t:award_type="Qualified Rehabilitation Facility (QRF)" t:award_title="Janitorial Services for the Records Center" t:street_address="3334 Industrial Way NE" t:contractor_information="Garten Services, Inc. (QRF)" t:city=Salem m:total_award_value_w_amendments=2000 m:original_award_value=2000
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:8izy-bwhd l:"ORPIN - Expired Contracts Report: FY 2010-2016 - Composite Dataset" t:url=https://data.oregon.gov/api/views/8izy-bwhd

property e:8izy-bwhd t:meta.view v:id=8izy-bwhd v:category="Revenue & Expense" v:averageRating=0 v:name="ORPIN - Expired Contracts Report: FY 2010-2016 - Composite Dataset"

property e:8izy-bwhd t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:8izy-bwhd t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| issued_for_agency_number | issued_for_agency_name | issued_by_agency_name               | document_number | amendment_number | award_title                                                     | award_type                              | contractor_information                 | street_address         | city         | state | zip_code   | original_start_date | expiration_date     | original_award_value | total_award_value_w_amendments | 
| ======================== | ====================== | =================================== | =============== | ================ | =============================================================== | ======================================= | ====================================== | ====================== | ============ | ===== | ========== | =================== | =================== | ==================== | ============================== | 
| 287                      | OED - Tualatin         | OED - Employment Department, Oregon | ED-1782-10      | 0                | OED #11-023, Experience Works Partner Service Sharing Agreement | Personal Services (PSK) Non-IT          | Experience Works, Inc.                 | 2005 St Helens Street  | Saint Helens | OR    | 97051      | 2010-10-01T00:00:00 | 2011-06-30T00:00:00 | 658.00               | 658.00                         | 
| 2000                     | Archives               | Administrative Division             | 165-1109-12     | 0                | Chaves Consulting Ramp Up Operating costs                       | Personal Services (PSK) IT              | CHAVES CONSULTING, INC.                | 1705 MAIN ST STE 400   | Baker City   | OR    | 97814      | 2012-05-04T00:00:00 | 2012-06-01T00:00:00 | 150000.00            | 150000.00                      | 
| 2000                     | Archives               | Secretary of State                  | 165-1074-11     | 0                | Janitorial Services for the Records Center                      | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)            | 3334 Industrial Way NE | Salem        | OR    | 97303      | 2011-09-28T00:00:00 | 2012-09-27T00:00:00 | 2000.00              | 2000.00                        | 
| 2000                     | Archives               | Secretary of State                  | 165-1074-11     | 1                | Janitorial Services for the Records Center                      | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)            | 3334 Industrial Way NE | Salem        | OR    | 97303      | 2011-09-28T00:00:00 | 2012-09-27T00:00:00 | 2000.00              | 2000.00                        | 
| 2000                     | Archives               | Administrative Division             | 165-1055-12     | 0                | Use of 2012 OAR Licensing agreement                             | Agreement to Agree                      | CCH Incorporated                       | 4025 W Peterson Ave    | Chicago      | IL    | 60646-6085 | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Administrative Division             | 165-1102-12     | 0                | 2012 OAR Licensing Agreement                                    | Trade Services                          | Thomson Reuters                        | 610 Opperman Drive     | Eagan        | MN    | 55123      | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Administrative Division             | 165-1102-12     | 1                | 2012 OAR Licensing Agreement                                    | Trade Services                          | Thomson Reuters                        | 610 Opperman Drive     | Eagan        | MN    | 55123      | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Administrative Division             | 165-1056-12     | 0                | 2012 OAR Licensing Agreement                                    | Agreement to Agree                      | LexisNexis a division of Reed Elseiver | 4717 194th Ave SE      | Issaquah     | WA    | 98027      | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Administrative Division             | 165-1101-12     | 0                | 2012 OAR Licensing Agreement                                    | Trade Services                          | Bloomberg Finance                      | 731 Lexington Ave      | New York     | NY    | 10022      | 2011-11-29T00:00:00 | 2012-12-31T00:00:00 | 5000.00              | 5000.00                        | 
| 2000                     | Archives               | Secretary of State                  | 165-1074-11     | 1000             | Janitorial Services for the Records Center                      | Qualified Rehabilitation Facility (QRF) | Garten Services, Inc. (QRF)            | 3334 Industrial Way NE | Salem        | OR    | 97303      | 2011-09-28T00:00:00 | 2013-09-30T00:00:00 | 2000.00              | 2000.00                        | 
```