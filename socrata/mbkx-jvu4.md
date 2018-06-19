# Contracts: ESD: Southern Oregon: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-southern-oregon-fy-2013-7a788) |
| Metadata | [Link](https://data.oregon.gov/api/views/mbkx-jvu4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mbkx-jvu4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mbkx-jvu4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mbkx-jvu4 |
| Name | Contracts: ESD: Southern Oregon: FY 2013 |
| Category | Revenue & Expense |
| Created | 2013-11-12T19:25:43Z |
| Publication Date | 2013-11-12T19:30:10Z |

## Description

Summary of contracts for Southern Oregon ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | numeric metric | esd                     | ESD #                   | number    | number      |
| Yes      | series tag     | esd_name                | ESD Name                | text      | text        |
| Yes      | series tag     | award_number            | Award Number            | text      | text        |
| Yes      | series tag     | award_title             | Award Title             | text      | text        |
| Yes      | series tag     | award_type              | Award Type              | text      | text        |
| Yes      | series tag     | type_of_contract        | Type of Contract        | text      | text        |
| Yes      | series tag     | contractor_name         | Contractor Name         | text      | text        |
| No       |                | contractor_address      | Contractor Address      | text      | text        |
| Yes      | series tag     | contractor_city         | Contractor City         | text      | text        |
| Yes      | series tag     | contractor_state        | Contractor State        | text      | text        |
| Yes      | series tag     | contractor_zip          | Contractor Zip          | text      | number      |
| No       |                | contract_start_end_date | Contract Start/End Date | text      | text        |
| Yes      | series tag     | orginal_award_value     | Orginal Award Value     | text      | text        |
| Yes      | numeric metric | amendment_value         | Amendment Value         | money     | money       |
| Yes      | series tag     | total_award_value       | Total Award Value       | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,contract_start_end_date
```

## Data Commands

```ls
series e:mbkx-jvu4 d:2013-01-01T00:00:00.000Z t:esd_name="Southern Oregon ESD" t:type_of_contract=Material t:orginal_award_value=$1,200.00 t:contractor_name="Bethany Presbyterian Church" t:contractor_state=OR t:total_award_value=$1,200.00 t:contractor_city="GRANTS PASS" t:award_type=Facilities t:award_title=Lease t:contractor_zip=97526 m:esd=2025

series e:mbkx-jvu4 d:2013-01-01T00:00:00.000Z t:esd_name="Southern Oregon ESD" t:type_of_contract=Professional t:orginal_award_value=$1,320.00 t:contractor_name="CPI Qualified Plan Consultants" t:contractor_state=KS t:total_award_value=$1,320.00 t:contractor_city="GREAT BEND" t:award_type="Professional Services" t:award_title="403(b) Management Services" t:contractor_zip=67530 m:esd=2025

series e:mbkx-jvu4 d:2013-01-01T00:00:00.000Z t:esd_name="Southern Oregon ESD" t:type_of_contract=Professional t:orginal_award_value=$15,082.00 t:contractor_name=CRS t:contractor_state=PA t:total_award_value=$15,082.00 t:contractor_city=MONTOURSVILLE t:award_type="Trade Services" t:award_title="Management Software" t:contractor_zip=17754 m:esd=2025
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

entity e:mbkx-jvu4 l:"Contracts: ESD: Southern Oregon: FY 2013" t:url=https://data.oregon.gov/api/views/mbkx-jvu4

property e:mbkx-jvu4 t:meta.view v:id=mbkx-jvu4 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Southern Oregon: FY 2013"

property e:mbkx-jvu4 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:mbkx-jvu4 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name            | award_number | award_title                      | award_type            | type_of_contract | contractor_name                       | contractor_address   | contractor_city | contractor_state | contractor_zip | contract_start_end_date | orginal_award_value | amendment_value | total_award_value  | 
| ==== | =================== | ============ | ================================ | ===================== | ================ | ===================================== | ==================== | =============== | ================ | ============== | ======================= | =================== | =============== | ================== | 
| 2025 | Southern Oregon ESD |              | Lease                            | Facilities            | Material         | Bethany Presbyterian Church           | 741 NW 4TH STREET    | GRANTS PASS     | OR               | 97526          | 7/1/2012 - 6/30/2013    | $1,200.00           |                 | $1,200.00          | 
| 2025 | Southern Oregon ESD |              | 403(b) Management Services       | Professional Services | Professional     | CPI Qualified Plan Consultants        | PO BOX 110           | GREAT BEND      | KS               | 67530          | Annual                  | $1,320.00           |                 | $1,320.00          | 
| 2025 | Southern Oregon ESD |              | Management Software              | Trade Services        | Professional     | CRS                                   | 926 PLAZA DR         | MONTOURSVILLE   | PA               | 17754          | Annual                  | $15,082.00          |                 | $15,082.00         | 
| 2025 | Southern Oregon ESD |              | Membership Fee                   | Participation Fee     | Professional     | Department of Administrative Services | 1225 FERRY ST. SE    | SALEM           | OR               | 97310          | Annual                  | $2,000.00           |                 | $2,000.00          | 
| 2025 | Southern Oregon ESD |              | Medicaid Administrative Claiming | Trade Services        | Professional     | Department of Administrative Services | 1225 FERRY ST. SE    | SALEM           | OR               | 97310          | 7/1/2008 - 12/31/2014   | Varies Per Billing  |                 | Varies Per Billing | 
| 2025 | Southern Oregon ESD |              | Media Materials                  | Educational Materials | Material         | Disney Education Products             | 105 TERRY DR STE 120 | NEWTOWN         | PA               | 18940          | 7/1/2012 - 6/30/2013    | $3,587.00           |                 | $3,587.00          | 
| 2025 | Southern Oregon ESD |              | Nursing Services                 | Professional Services | Professional     | Douglas Education Service District    | 1871 NE STEPHENS     | ROSEBURG        | OR               | 97470          | 7/1/2012 - 6/30/2013    | $17,556.00          |                 | $17,556.00         | 
| 2025 | Southern Oregon ESD |              | Regional Program Services        | Professional Services | Professional     | Douglas Education Service District    | 1871 NE STEPHENS     | ROSEBURG        | OR               | 97470          | 7/1/2012 - 6/30/2013    | $376,046.00         |                 | $376,046.00        | 
| 2025 | Southern Oregon ESD |              | Consulting Services              | Professional Services | Professional     | ECONorthwest                          | 99 WEST 10TH AVE     | EUGENE          | OR               | 97401          | 7/1/2012 - 6/30/2013    | $15,000.00          |                 | $15,000.00         | 
| 2025 | Southern Oregon ESD |              | Lease                            | Facilities            | Material         | Family Solutions                      | 322 NW "F" STREET    | GRANTS PASS     | OR               | 97526          | 7/1/2012 - 6/30/2013    | $11,280.00          |                 | $11,280.00         | 
```