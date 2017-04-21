# Contracts: ESD: Multnomah: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-multnomah-fy-2013-0aed2) |
| Metadata | [Link](https://data.oregon.gov/api/views/w6be-e3w2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/w6be-e3w2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/w6be-e3w2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | w6be-e3w2 |
| Name | Contracts: ESD: Multnomah: FY 2013 |
| Category | Revenue & Expense |
| Tags | esd, esd contracts, multnomah esd contracts, mesd, mesd contracts |
| Created | 2013-12-02T22:48:03Z |
| Publication Date | 2013-12-02T22:50:22Z |

## Description

Summary of contracts for Multnomah ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                   | Data Type | Render Type |
| ======== | ============== | ================================================== | ====================================================== | ========= | =========== |
| Yes      | numeric metric | esd                                                | ESD#                                                   | number    | number      |
| Yes      | series tag     | esd_name                                           | ESD Name                                               | text      | text        |
| Yes      | series tag     | contract                                           | Contract #                                             | text      | text        |
| Yes      | series tag     | award_title                                        | Award Title                                            | text      | text        |
| Yes      | series tag     | award_type                                         | Award Type                                             | text      | text        |
| Yes      | series tag     | secondary_type_reference                           | Secondary Type Reference                               | text      | text        |
| Yes      | series tag     | contractor                                         | Contractor                                             | text      | text        |
| No       |                | original_start_last_amendment_date_expiration_date | Original Start / Last Amendment Date / Expiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                               | Original Award Value                                   | number    | number      |
| Yes      | numeric metric | amendment_value                                    | Amendment Value                                        | number    | number      |
| Yes      | numeric metric | total_value                                        | Total Value                                            | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_last_amendment_date_expiration_date
```

## Data Commands

```ls
series e:w6be-e3w2 d:2013-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:contractor="Soliant Health Inc" t:contract=C00153 t:award_type="Vendor/Other Agency Provided Service" t:award_title="Soliant Temporarty Staffing SPED" m:amendment_value=300000 m:esd=2148 m:original_award_value=100000 m:total_value=400000

series e:w6be-e3w2 d:2013-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:contractor="Career Staff Unlimited Inc" t:contract=C00158 t:award_type="Vendor/Other Agency Provided Service" t:award_title="Temporary Staff- Career Staff Unlimited, Inc." m:amendment_value=200000 m:esd=2148 m:original_award_value=100000 m:total_value=300000

series e:w6be-e3w2 d:2013-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:contractor="COMPHEALTH MEDICAL STAFFING" t:contract=C00347 t:award_type="Vendor/Other Agency Provided Service" t:award_title="Temporary Staffing Agency-SPED staffing CompHealth" m:amendment_value=500000 m:esd=2148 m:original_award_value=500000 m:total_value=1000000
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=number

metric m:amendment_value p:float l:"Amendment Value" t:dataTypeName=number

metric m:total_value p:float l:"Total Value" t:dataTypeName=number

entity e:w6be-e3w2 l:"Contracts: ESD: Multnomah: FY 2013" t:url=https://data.oregon.gov/api/views/w6be-e3w2

property e:w6be-e3w2 t:meta.view v:id=w6be-e3w2 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Multnomah: FY 2013"

property e:w6be-e3w2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:w6be-e3w2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name      | contract | award_title                                        | award_type                           | secondary_type_reference       | contractor                                | original_start_last_amendment_date_expiration_date | original_award_value | amendment_value | total_value | 
| ==== | ============= | ======== | ================================================== | ==================================== | ============================== | ========================================= | ================================================== | ==================== | =============== | =========== | 
| 2148 | Multnomah ESD | C00153   | Soliant Temporarty Staffing SPED                   | Vendor/Other Agency Provided Service |                                | Soliant Health Inc                        | 7/1/2011 / 7/25/2012 / 6/30/2013                   | 100000.00            | 300000.00       | 400000.00   | 
| 2148 | Multnomah ESD | C00158   | Temporary Staff- Career Staff Unlimited, Inc.      | Vendor/Other Agency Provided Service |                                | Career Staff Unlimited Inc                | 7/13/2011 / 6/18/2012 / 6/30/2013                  | 100000.00            | 200000.00       | 300000.00   | 
| 2148 | Multnomah ESD | C00347   | Temporary Staffing Agency-SPED staffing CompHealth | Vendor/Other Agency Provided Service |                                | COMPHEALTH MEDICAL STAFFING               | 5/25/2011 / 6/19/2012 / 6/30/2013                  | 500000.00            | 500000.00       | 1000000.00  | 
| 2148 | Multnomah ESD | C00385   | Ardor Health Solutions temporary staffing          | Vendor/Other Agency Provided Service | Personal/Professional Services | Ardor Health Solutions                    | 7/1/2011 / 8/14/2012 / 6/30/2013                   | 200000.00            | 100000.00       | 300000.00   | 
| 2148 | Multnomah ESD | C00417   | EBS Temporary Staffing                             | Vendor/Other Agency Provided Service |                                | EBS Healthcare                            | 7/1/2011 / 9/23/2013 / 6/30/2014                   | 1000000.00           | 2000000.00      | 3000000.00  | 
| 2148 | Multnomah ESD | C00418   | SHC (Supplemental Health Care) Temporary Staffing  | Vendor/Other Agency Provided Service |                                | SHC Services Inc                          | 7/1/2011 / 6/19/2012 / 6/30/2013                   | 200000.00            | 200000.00       | 400000.00   | 
| 2148 | Multnomah ESD | C00423   | DHS ISRS contract July-Oct,2011                    | Vendor/Other Agency Provided Service |                                | Options Counseling Services of Oregon Inc | 7/1/2011 / 7/6/2012 / 7/14/2012                    | 30901.00             | 129090.55       | 159991.55   | 
| 2148 | Multnomah ESD | C00426   | subcontract for ISRS                               | Vendor/Other Agency Provided Service | Personal/Professional Services | SELF ENHANCEMENT INC                      | 7/1/2011 / 7/11/2012 / 7/14/2012                   | 60000.00             | 194376.15       | 254376.15   | 
| 2148 | Multnomah ESD | C00431   | subcontractor for ISRS                             | Vendor/Other Agency Provided Service | Personal/Professional Services | BLACK PARENT INITIATIVE                   | 7/1/2011 / 7/2/2012 / 7/14/2012                    | 17500.00             | 71361.32        | 88861.32    | 
| 2148 | Multnomah ESD | C00432   | In-Home Reunification Services                     | Vendor/Other Agency Provided Service | Personal/Professional Services | Give Us This Day Inc                      | 7/1/2011 / 7/5/2012 / 7/14/2012                    | 31408.00             | 68312.00        | 99720.00    | 
```