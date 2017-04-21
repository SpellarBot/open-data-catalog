# Contracts: ORPIN: As of June 30, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-orpin-as-of-june-30-2012-bf949) |
| Metadata | [Link](https://data.oregon.gov/api/views/d4yy-zmtu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/d4yy-zmtu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/d4yy-zmtu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | d4yy-zmtu |
| Name | Contracts: ORPIN: As of June 30, 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-13T19:31:45Z |
| Publication Date | 2012-12-13T19:32:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | agency_number                                    | Agency Number                                    | text      | text        |
| Yes      | series tag     | agency_name                                      | Agency Name                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments                        | Award Number w/Amendments                        | text      | text        |
| Yes      | series tag     | award_title                                      | Award Title                                      | text      | text        |
| Yes      | series tag     | award_type                                       | Award Type                                       | text      | text        |
| Yes      | series tag     | contractor_information                           | Contractor Information                           | text      | text        |
| Yes      | series tag     | street_address                                   | Street Address                                   | text      | text        |
| Yes      | series tag     | zip_code                                         | Zip Code                                         | text      | text        |
| No       |                | original_start_dateamendment_dateexpiration_date | Original Start DateAmendment DateExpiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                             | Original Award Value                             | money     | money       |
| Yes      | numeric metric | amendment_value                                  | Amendment Value                                  | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                   | Total Award Value w/Amendments                   | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_dateamendment_dateexpiration_date
```

## Data Commands

```ls
series e:d4yy-zmtu d:2012-01-01T00:00:00.000Z t:zip_code=97123 t:award_number_w_amendments=107-2751-11 t:award_type="One Time Contract" t:award_title="Foster Home Certification File Folders" t:agency_number=100000 t:street_address="2205 SE 67th Ave" t:agency_name="DHS - Department of Human Services" t:contractor_information="Lucky Duck Printing" m:amendment_value=10899 m:total_award_value_w_amendments=10899 m:original_award_value=10899

series e:d4yy-zmtu d:2012-01-01T00:00:00.000Z t:zip_code=97015 t:award_number_w_amendments=DHS-136969-11 t:award_type="Trade Services" t:award_title="DD Housing modification" t:agency_number=100000 t:street_address="PO Box 2342" t:agency_name="DHS - Department of Human Services" t:contractor_information="DRW Contractors LLC" m:amendment_value=5000 m:total_award_value_w_amendments=5000 m:original_award_value=5000

series e:d4yy-zmtu d:2012-01-01T00:00:00.000Z t:zip_code=97015 t:award_number_w_amendments="DHS-136969-11 (1)" t:award_type="Trade Services" t:award_title="DD Housing modification" t:agency_number=100000 t:street_address="PO Box 2342" t:agency_name="DHS - Department of Human Services" t:contractor_information="DRW Contractors LLC" m:amendment_value=0 m:total_award_value_w_amendments=5000 m:original_award_value=5000
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:d4yy-zmtu l:"Contracts: ORPIN: As of June 30, 2012" t:url=https://data.oregon.gov/api/views/d4yy-zmtu

property e:d4yy-zmtu t:meta.view v:id=d4yy-zmtu v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ORPIN: As of June 30, 2012"

property e:d4yy-zmtu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:d4yy-zmtu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                        | award_number_w_amendments | award_title                                              | award_type                              | contractor_information                 | street_address                                               | zip_code   | original_start_dateamendment_dateexpiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | ================================== | ========================= | ======================================================== | ======================================= | ====================================== | ============================================================ | ========== | ================================================ | ==================== | =============== | ============================== | 
| 100000        | DHS - Department of Human Services | 107-2751-11               | Foster Home Certification File Folders                   | One Time Contract                       | Lucky Duck Printing                    | 2205 SE 67th Ave                                             | 97123      | 08/26/2011 08/30/2011 10/04/2011                 | 10899.00             | 10899.00        | 10899.00                       | 
| 100000        | DHS - Department of Human Services | DHS-136969-11             | DD Housing modification                                  | Trade Services                          | DRW Contractors LLC                    | PO Box 2342                                                  | 97015      | 10/17/2011 10/19/2011 01/31/2012                 | 5000.00              | 5000.00         | 5000.00                        | 
| 100000        | DHS - Department of Human Services | DHS-136969-11 (1)         | DD Housing modification                                  | Trade Services                          | DRW Contractors LLC                    | PO Box 2342                                                  | 97015      | 10/17/2011 10/19/2011 03/20/2012                 | 5000.00              | 0.00            | 5000.00                        | 
| 100000        | DHS - Department of Human Services | DHS-136964-11             | Community Housing - Client Home Modification             | Trade Services                          | Kenneth Allen Foster                   | PO Box 9                                                     | 97355      | 10/17/2011 10/19/2011 01/05/2012                 | 17870.00             | 17870.00        | 17870.00                       | 
| 100000        | DHS - Department of Human Services | DHS-136107-11             | Prepare Triennial Maternal and Child Health (MCH) Plan   | Intergovernment Agreement (ORS190)      | Klamath Tribes of Oregon               | Klamath Tribal Health and Family Services 3949 S. 6th Street | 97603      | 07/01/2011 11/02/2011 12/31/2011                 | 5000.00              | 5000.00         | 5000.00                        | 
| 100000        | DHS - Department of Human Services | DHS-132643-11             | QRF Janitorial Services 912 NE Kelly, Gresham, OR        | Qualified Rehabilitation Facility (QRF) | Mt. Angel Developmental Programs (QRF) | PO Box 78                                                    | 97362      | 01/01/2012 12/29/2011 05/31/2013                 | 24507.00             | 24507.00        | 24507.00                       | 
| 100000        | DHS - Department of Human Services | DHS-137619-11             | Janitorial Services 2110 Newmark Ave., Coos Bay, OR      | Trade Services                          | Associated Cleaning Services, Inc.     | P.O. Box 771                                                 | 97365      | 01/01/2012 12/19/2011 12/31/2016                 | 171000.00            | 171000.00       | 171000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-135483-12             | Statistical Analysis                                     | Intergovernment Agreement (ORS190)      | Portland State University (ORCPP)      | PO Box 951                                                   | 97207-0951 | 05/23/2011 01/31/2012 07/31/2011                 | 25000.00             | 25000.00        | 25000.00                       | 
| 100000        | DHS - Department of Human Services | DHS-136690-11 (1)         | QRF janitorial Svcs 500 N Columbia River Hwy, St. Helens | Qualified Rehabilitation Facility (QRF) | Tualatin Valley Workshop, Inc. (QRF)   | 6615 SE Alexander ST.                                        | 97123      | 10/01/2011 02/16/2012 02/28/2014                 | 18530.00             | 89114.00        | 107644.00                      | 
| 100000        | DHS - Department of Human Services | DHS-137468-12             | QRF Janitorial Svcs 15625 Greystone Ct., Beaverton, OR   | Qualified Rehabilitation Facility (QRF) | Tualatin Valley Workshop, Inc. (QRF)   | 6615 SE Alexander ST                                         | 97123      | 04/01/2012 03/16/2012 12/31/2016                 | 453128.00            | 453128.00       | 453128.00                      | 
```