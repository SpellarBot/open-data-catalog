# Contracts: ESD: Lane ESD: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-lane-esd-fiscal-year-2014-4547b) |
| Metadata | [Link](https://data.oregon.gov/api/views/cz2e-ihje) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cz2e-ihje/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cz2e-ihje/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cz2e-ihje |
| Name | Contracts: ESD: Lane ESD: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, contracts, lane esd, lane esd contracts 2014 |
| Created | 2014-12-16T16:55:12Z |
| Publication Date | 2014-12-29T05:58:40Z |

## Description

Contracts: ESD: Lane ESD: Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | numeric metric | esd                                    | ESD#                                   | number    | number      |
| Yes      | series tag     | esd_name                               | ESD Name                               | text      | text        |
| Yes      | series tag     | award                                  | Award #                                | text      | text        |
| Yes      | series tag     | award_title                            | Award Title                            | text      | text        |
| Yes      | series tag     | award_type                             | Award Type                             | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract           | Type of Contract/ Subcontract          | text      | text        |
| Yes      | series tag     | contractor_information                 | Contractor Information                 | text      | text        |
| No       |                | contractor_address                     | Contractor Address                     | text      | text        |
| Yes      | series tag     | contractor_city                        | Contractor City                        | text      | text        |
| Yes      | series tag     | contractor_state                       | Contractor State                       | text      | text        |
| Yes      | series tag     | contractor_zip                         | Contractor Zip                         | text      | number      |
| No       |                | original_start_amended_expiration_date | Original Start/Amended/Expiration Date | text      | text        |
| Yes      | numeric metric | original_awardvalue                    | Original AwardValue                    | money     | money       |
| Yes      | numeric metric | amendmentvalue                         | AmendmentValue                         | money     | money       |
| Yes      | numeric metric | total_awardvalue                       | Total AwardValue                       | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amended_expiration_date
```

## Data Commands

```ls
series e:cz2e-ihje d:2014-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Contract t:award=- t:contractor_city="Cottage Grove" t:award_type="Price Agreement" t:award_title="Data circuit" t:contractor_information="City of Cottage Grove" t:contractor_zip=97424 m:original_awardvalue=14400 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=14400

series e:cz2e-ihje d:2014-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Contract t:award=- t:contractor_city=Eugene t:award_type="Price Agreement" t:award_title="District & family support services" t:contractor_information="Direction Service" t:contractor_zip=97405 m:original_awardvalue=84256 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=84256

series e:cz2e-ihje d:2014-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Sub-Contract t:award=- t:contractor_city=Eugene t:award_type=Sub-Contract t:award_title="Regional services - HI/VI/OI" t:contractor_information="Eugene School District" t:contractor_zip=97402 m:original_awardvalue=1040223 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=1040223
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:original_awardvalue p:integer l:"Original AwardValue" t:dataTypeName=money

metric m:amendmentvalue p:double l:AmendmentValue t:dataTypeName=money

metric m:total_awardvalue p:integer l:"Total AwardValue" t:dataTypeName=money

entity e:cz2e-ihje l:"Contracts: ESD: Lane ESD: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/cz2e-ihje

property e:cz2e-ihje t:meta.view v:id=cz2e-ihje v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Lane ESD: Fiscal Year 2014"

property e:cz2e-ihje t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cz2e-ihje t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | award | award_title                        | award_type      | type_of_contract_subcontract | contractor_information      | contractor_address           | contractor_city | contractor_state | contractor_zip | original_start_amended_expiration_date | original_awardvalue | amendmentvalue | total_awardvalue | 
| ==== | =============================== | ===== | ================================== | =============== | ============================ | =========================== | ============================ | =============== | ================ | ============== | ====================================== | =================== | ============== | ================ | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Data circuit                       | Price Agreement | Contract                     | City of Cottage Grove       | 400 East Main Street         | Cottage Grove   | OR               | 97424          | 07/01/13 - / / - 06/30/14              | 14400               | 0.0            | 14400            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | District & family support services | Price Agreement | Contract                     | Direction Service           | P.O. Box 51360               | Eugene          | OR               | 97405          | 07/01/13 - / / - 06/30/14              | 84256               | 0              | 84256            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Regional services - HI/VI/OI       | Sub-Contract    | Sub-Contract                 | Eugene School District      | 200 N Monroe Street          | Eugene          | OR               | 97402          | 07/01/13 - / / - 06/30/14              | 1040223             | 0              | 1040223          | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Physical/Occupational therapy      | Price Agreement | Contract                     | Eugene School District      | 200 N Monroe Street          | Eugene          | OR               | 97402          | 07/01/13 - / / - 06/30/14              | 163144              | 0              | 163144           | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Food service                       | Price Agreement | Contract                     | Eugene School District      | 200 N Monroe Street          | Eugene          | OR               | 97402          | 07/01/13 - / / - 06/30/14              | 25448               | 0              | 25448            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Webfiltering                       | Price Agreement | Contract                     | Fortnet Security            | 7411 Carnoustie Court        | Gilroy          | CA               | 95020          | 07/01/13 - / / - 06/30/14              | 9945                | 0              | 9945             | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Substitute/attendance system       | Price Agreement | Contract                     | Frontline Technologies      | 397 Eagleview Blvd.          | Exton           | PA               | 19341          | 07/01/13 - / / - 06/30/14              | 6249                | 0              | 6249             | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Teaching artist                    | Price Agreement | Contract                     | Lane Arts Council           | 1590 Willamette St #200      | Eugene          | OR               | 97401          | 07/01/13 - / / - 06/30/14              | 24730               | 0              | 24730            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Telecom management                 | Price Agreement | Contract                     | Lane Council of Governments | 859 Willamette St. Suite 500 | Eugene          | OR               | 97401          | 07/01/13 - / / - 06/30/14              | 13978               | 0              | 13978            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | MLK Jr Ed Center Staffing          | Price Agreement | Contract                     | Lane County                 | 151 West 7th Avenue          | Eugene          | OR               | 97401          | 07/01/13 - / / - 06/30/14              | 31100               | 0              | 31100            | 
```