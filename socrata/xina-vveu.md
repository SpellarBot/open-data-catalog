# Contracts: Agencies: As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-agencies-as-of-june-30-2014-b8e80) |
| Metadata | [Link](https://data.oregon.gov/api/views/xina-vveu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xina-vveu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xina-vveu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xina-vveu |
| Name | Contracts: Agencies: As of June 30, 2014 |
| Category | Revenue & Expense |
| Tags | contracts, agency contracts, state contracts, state contracts 2014, 2014 |
| Created | 2014-12-30T15:31:02Z |
| Publication Date | 2014-12-30T15:39:31Z |

## Description

This report provides information on contracts and amendments to contracts issued from July 1, 2013 - June 30, 2014, for state agencies who are subject to DAS contracting authority. These agencies must report their contracting activity through the Oregon Procurement Information Network (ORPIN) system. The contract values reflected in this report are estimates.

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
series e:xina-vveu d:2013-08-26T00:00:00.000Z t:zip_code=1701 t:award_number_w_amendments=107-3253-13 t:award_type="One Time Contract" t:agency_number=100000 t:award_title="Client File Folders" t:street_address="1 Watson Place" t:agency_name="DHS - Department of Human Services" t:contractor_information="Colortrieve Record Systems" m:amendment_value=6950 m:total_award_value_w_amendments=6950 m:original_award_value=6950

series e:xina-vveu d:2009-07-01T00:00:00.000Z t:award_number_w_amendments="DHS-128289-11 (2)" t:award_type="Intergovernment Agreement (ORS190)" t:agency_number=100000 t:award_title="Foodborne Illness Prevention Program" t:agency_name="DHS - Department of Human Services" t:contractor_information="OHA - Oregon Health Authority (ORCPP)" m:amendment_value=108408 m:total_award_value_w_amendments=302979 m:original_award_value=12161

series e:xina-vveu d:2014-04-21T00:00:00.000Z t:zip_code=98023 t:award_number_w_amendments="DASPS-2195-14 (1)" t:award_type="Personal Services (PSK) Non-IT" t:agency_number=100000 t:award_title="IT Advisory Services" t:street_address="1911 SW Campus Dr. #457" t:agency_name="DHS - Department of Human Services" t:contractor_information="Public Knowledge LLC" m:amendment_value=0 m:total_award_value_w_amendments=92000 m:original_award_value=92000
```

## Meta Commands

```ls
metric m:original_award_value p:integer l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:integer l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:integer l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:xina-vveu l:"Contracts: Agencies: As of June 30, 2014" t:url=https://data.oregon.gov/api/views/xina-vveu

property e:xina-vveu t:meta.view v:id=xina-vveu v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Agencies: As of June 30, 2014"

property e:xina-vveu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:xina-vveu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                                                       | award_number_w_amendments | award_title                                                 | award_type                         | contractor_information                | street_address                                                             | zip_code | original_start_date | amendment_date      | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| ============= | ================================================================= | ========================= | =========================================================== | ================================== | ===================================== | ========================================================================== | ======== | =================== | =================== | =================== | ==================== | =============== | ============================== | 
| 100000        | DHS - Department of Human Services                                | 107-3253-13               | Client File Folders                                         | One Time Contract                  | Colortrieve Record Systems            | 1 Watson Place                                                             | 1701     | 2013-08-26T00:00:00 | 2013-09-03T00:00:00 | 2014-01-03T00:00:00 | 6950                 | 6950            | 6950                           | 
| 100000        | DHS - Department of Human Services                                | DHS-128289-11 (2)         | Foodborne Illness Prevention Program                        | Intergovernment Agreement (ORS190) | OHA - Oregon Health Authority (ORCPP) |                                                                            |          | 2009-07-01T00:00:00 | 2013-07-08T00:00:00 | 2015-06-30T00:00:00 | 12161                | 108408          | 302979                         | 
| 100000        | DHS - Department of Human Services                                | DASPS-2195-14 (1)         | IT Advisory Services                                        | Personal Services (PSK) Non-IT     | Public Knowledge LLC                  | 1911 SW Campus Dr. #457                                                    | 98023    | 2014-04-21T00:00:00 | 2014-04-29T00:00:00 | 2014-07-11T00:00:00 | 92000                | 0               | 92000                          | 
| 100000        | DHS - Department of Human Services                                | DASPS-2195-14 (2)         | IT Advisory Services                                        | Personal Services (PSK) Non-IT     | Public Knowledge LLC                  | 1911 SW Campus Dr. #457                                                    | 98023    | 2014-04-21T00:00:00 | 2014-06-03T00:00:00 | 2014-10-21T00:00:00 | 92000                | 92000           | 184000                         | 
| 100000        | DHS - Department of Human Services                                | 107-3330-14               | Foster Home Certification File Folders                      | One Time Contract                  | Colortrieve Record Systems            | 1 Watson Place                                                             | 1701     | 2014-02-20T00:00:00 | 2014-02-25T00:00:00 | 2014-03-28T00:00:00 | 17925                | 17925           | 17925                          | 
| 100000        | DHS - Department of Human Services                                | DASPS-2195-14             | IT Advisory Services                                        | Personal Services (PSK) Non-IT     | Public Knowledge LLC                  | 1911 SW Campus Dr. #457                                                    | 98023    | 2014-04-21T00:00:00 | 2014-04-23T00:00:00 | 2014-07-11T00:00:00 | 92000                | 92000           | 92000                          | 
| 100020        | DHS - Shared Services                                             | 107-3341-14               | Case File Folders                                           | One Time Contract                  | Colortrieve Record Systems            | 1 Watson Place                                                             | 1701     | 2014-03-17T00:00:00 | 2014-03-17T00:00:00 | 2015-06-02T00:00:00 | 62700                | 62700           | 62700                          | 
| 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation | DHS-143753-14             | Territorial Adoptive Placement                              | Intergovernment Agreement (ORS190) | Government of Guam                    | Department of Public Health and Social Services Division of Public Welfare |          | 2014-03-21T00:00:00 | 2014-04-08T00:00:00 | 2016-01-01T00:00:00 | 0                    | 0               | 0                              | 
| 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation | DHS-145648-14             | Out of State Adoption Placement and Supervision             | Personal Services (PSK) Non-IT     | Randall L. Barlow                     | CMR 467 Box 25                                                             | 9096     | 2014-04-21T00:00:00 | 2014-04-25T00:00:00 | 2016-06-30T00:00:00 | 25000                | 25000           | 25000                          | 
| 100100        | DHS - Child Welfare, Self Sufficiency & Vocational Rehabilitation | DHS-144810-14             | Motivational Ehancement Training (MET)perpetual use license | Personal Services (PSK) Non-IT     | PNA Change Consultants, Inc           | 3590 Rivergate Way, Suite 1202 Ottawa, Ontario                             |          | 2014-03-04T00:00:00 | 2014-03-11T00:00:00 | 2014-08-31T00:00:00 | 55000                | 55000           | 55000                          | 
```