# Contracts: ORPIN: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-orpin-as-of-june-30-2010-f91ed) |
| Metadata | [Link](https://data.oregon.gov/api/views/br2t-dc7x) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/br2t-dc7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/br2t-dc7x/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | br2t-dc7x |
| Name | Contracts: ORPIN: As of June 30, 2010 |
| Attribution | State of Oregon - Department of Administrative Services |
| Category | Revenue & Expense |
| Tags | contract, procurement, oregon, transparency, data, data.oregon.gov, state, agency |
| Created | 2011-02-08T01:25:27Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

This report provides information on contracts and amendments to contracts issued from July 1, 2009 - June 30, 2010, for state agencies who are subject to DAS contracting authority. These agencies must report their contracting activity through the Oregon Procurement Information Network (ORPIN) system. The contract values reflected in this report are estimates. 
For more detail on this and other state of Oregon Contracts files, visit the Oregon Transparency Website Contracts/Procurements page:

Note: The ORPIN Contracts Report is for period ending June 30, 2010. However, the file was updated on July 26, 2011 to reflect a modification to Price Agreement #8605.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================== | ================================================== | ========= | =========== |
| Yes      | series tag     | agency_number                                      | Agency Number                                      | text      | text        |
| Yes      | series tag     | agency_name                                        | Agency Name                                        | text      | text        |
| Yes      | series tag     | award_number_w_amendments                          | Award Number w/Amendments                          | text      | text        |
| Yes      | series tag     | award_title                                        | Award Title                                        | text      | text        |
| Yes      | series tag     | award_type                                         | Award Type                                         | text      | text        |
| Yes      | series tag     | contractor_information                             | Contractor Information                             | text      | text        |
| No       |                | original_start_date_amendment_date_expiration_date | Original Start Date Amendment Date Expiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                               | Original Award Value                               | money     | money       |
| Yes      | numeric metric | amendment_value                                    | Amendment Value                                    | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                     | Total Award Value w/Amendments                     | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_date_amendment_date_expiration_date
```

## Data Commands

```ls
series e:br2t-dc7x d:2010-01-01T00:00:00.000Z t:award_number_w_amendments=DHS-121544-09 t:award_type="Intergovernment Agreement (ORS190)" t:award_title="Youth Transition Services" t:agency_number=100000 t:agency_name="DHS - Department of Human Services" t:contractor_information="Hillsboro School District 1J (ORCPP)
Hillsboro
OR
97124-6009" m:amendment_value=108787 m:total_award_value_w_amendments=108787 m:original_award_value=108787

series e:br2t-dc7x d:2010-01-01T00:00:00.000Z t:award_number_w_amendments="DHS-121544-09 (0.1)" t:award_type="Intergovernment Agreement (ORS190)" t:award_title="Youth Transition Services" t:agency_number=100000 t:agency_name="DHS - Department of Human Services" t:contractor_information="Hillsboro School District 1J (ORCPP)
Hillsboro
OR
97124-6009" m:amendment_value=54393 m:total_award_value_w_amendments=163180 m:original_award_value=108787

series e:br2t-dc7x d:2010-01-01T00:00:00.000Z t:award_number_w_amendments="DHS-129412-09 (0.1)" t:award_type="Personal Services (PSK) Non-IT" t:award_title="Professional counselor providing professional staff coaching" t:agency_number=100000 t:agency_name="DHS - Department of Human Services" t:contractor_information="Matthew J. Modrcin, Ph.D.
Lake Oswego
OR
97034" m:amendment_value=0 m:total_award_value_w_amendments=1881 m:original_award_value=1881
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:br2t-dc7x l:"Contracts: ORPIN: As of June 30, 2010" t:attribution="State of Oregon - Department of Administrative Services" t:url=https://data.oregon.gov/api/views/br2t-dc7x

property e:br2t-dc7x t:meta.view v:id=br2t-dc7x v:category="Revenue & Expense" v:attributionLink=http://oregon.gov/transparency/contracts.page v:averageRating=0 v:name="Contracts: ORPIN: As of June 30, 2010" v:attribution="State of Oregon - Department of Administrative Services"

property e:br2t-dc7x t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:br2t-dc7x t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                        | award_number_w_amendments | award_title                                                  | award_type                              | contractor_information                                       | original_start_date_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | ================================== | ========================= | ============================================================ | ======================================= | ============================================================ | ================================================== | ==================== | =============== | ============================== | 
| Agency Number | Agency Name                        | Award Number w/Amendments | Award Title                                                  | Award Type                              | Contractor Information                                       | Original Start Date Amendment Date Expiration Date |                      |                 |                                | 
| 100000        | DHS - Department of Human Services | DHS-121544-09             | Youth Transition Services                                    | Intergovernment Agreement (ORS190)      | Hillsboro School District 1J (ORCPP) Hillsboro OR 97124-6009 | 07/01/2007 07/10/2009 06/30/2009                   | 108787.00            | 108787.00       | 108787.00                      | 
| 100000        | DHS - Department of Human Services | DHS-121544-09 (0.1)       | Youth Transition Services                                    | Intergovernment Agreement (ORS190)      | Hillsboro School District 1J (ORCPP) Hillsboro OR 97124-6009 | 07/01/2007 07/10/2009 06/30/2009                   | 108787.00            | 54393.00        | 163180.00                      | 
| 100000        | DHS - Department of Human Services | DHS-129412-09 (0.1)       | Professional counselor providing professional staff coaching | Personal Services (PSK) Non-IT          | Matthew J. Modrcin, Ph.D. Lake Oswego OR 97034               | 07/22/2009 07/21/2009 09/30/2009                   | 1881.00              | 0.00            | 1881.00                        | 
| 100000        | DHS - Department of Human Services | DHS116854-5 (1)           | Janitorial Services for DHS 2990 & 3020 Broadway, North Bend | Qualified Rehabilitation Facility (QRF) | Bay Area Enterprises, Inc. (QRF) Coos Bay OR 97420           | 06/30/2006 03/03/2010 02/28/2011                   | 87651.00             | 28538.00        | 116189.00                      | 
| 100000        | DHS - Department of Human Services | DHS-128608-09             | Alternate Format Communication Conversions                   | Personal Services (PSK) Non-IT          | Braille Plus, Inc. Salem OR 97302                            | 08/03/2009 08/03/2009 07/31/2011                   | 500000.00            | 500000.00       | 500000.00                      | 
| 100000        | DHS - Department of Human Services | DHS-118043-06 (1)         | Janitorial Services for the DHS Office at Durham Rd. Tigard  | Trade Services                          | Port City Development (QRF) Portland OR 97227                | 10/17/2006 07/20/2009 07/31/2009                   | 20383.00             | 11118.00        | 31501.00                       | 
| 100000        | DHS - Department of Human Services | DHS-121552-09 (1)         | Youth Transition Program services provided for OVRS          | Intergovernment Agreement (ORS190)      | St Helens School District 502 St. Helens OR 97051-1340       | 07/01/2007 07/14/2009 06/30/2009                   | 194474.00            | 0.00            | 194474.00                      | 
| 100000        | DHS - Department of Human Services | DHS-121543-09 (1)         | Youth Transition Program services provided for OVRS          | Intergovernment Agreement (ORS190)      | Grant County School District Canyon City OR 97820            | 07/01/2007 07/14/2009 06/30/2009                   | 69768.00             | 0.00            | 69768.00                       | 
| 100000        | DHS - Department of Human Services | DHS-121570-09             | Youth Transition Program services for OVRS                   | Intergovernment Agreement (ORS190)      | Central Point School District 6 Central Point OR 97502-2279  | 07/01/2008 07/20/2009 06/30/2009                   | 97989.00             | 97989.00        | 97989.00                       | 
```