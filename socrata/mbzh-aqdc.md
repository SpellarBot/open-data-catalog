# Renewable Resource Equipment Manufacturing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/renewable-resource-equipment-manufacturing-9921f) |
| Metadata | [Link](https://data.oregon.gov/api/views/mbzh-aqdc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mbzh-aqdc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mbzh-aqdc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mbzh-aqdc |
| Name | Renewable Resource Equipment Manufacturing |
| Category | Revenue & Expense |
| Created | 2013-02-07T18:01:02Z |
| Publication Date | 2013-02-07T18:10:38Z |

## Description

Information Link: http://www.oregon4biz.com/The-Oregon-Advantage/Incentives/Business-Energy-Tax-Credit

## Columns

```ls
| Included | Schema Type    | Field Name                                                  | Name                                                        | Data Type | Render Type |
| ======== | ============== | =========================================================== | =========================================================== | ========= | =========== |
| Yes      | series tag     | issuing_agency                                              | Issuing Agency                                              | text      | text        |
| Yes      | time           | report_period_end_date                                      | Report Period End Date                                      | text      | text        |
| Yes      | series tag     | project_owner_taxpayer_approved_for_allowance_of_tax_credit | Project Owner/Taxpayer Approved For Allowance of Tax Credit | text      | text        |
| Yes      | series tag     | project_location_congressional_district                     | Project Location Congressional District                     | text      | text        |
| Yes      | series tag     | income_tax_benefit                                          | Income Tax Benefit                                          | text      | text        |
| Yes      | series tag     | outcomes                                                    | Outcomes                                                    | text      | text        |
| Yes      | series tag     | qualification_for_approval                                  | Qualification for Approval                                  | text      | text        |
| Yes      | series tag     | application                                                 | Application #                                               | text      | text        |
| Yes      | series tag     | project_type                                                | Project Type                                                | text      | text        |
| Yes      | series tag     | preliminary_certification_issued                            | Preliminary Certification Issued                            | text      | text        |
| Yes      | series tag     | final_certified_amount_letter_issued                        | Final Certified Amount Letter Issued                        | text      | text        |
| Yes      | numeric metric | final_certified_project_cost_amount                         | Final Certified Project Cost Amount                         | money     | text        |
| Yes      | numeric metric | final_certified_tax_credit_amount                           | Final Certified Tax Credit Amount                           | money     | text        |
| Yes      | numeric metric | tax_certificate_amount_issued_fiscal_year_2012              | Tax Certificate Amount Issued Fiscal Year 2012              | money     | text        |
| Yes      | series tag     | jobs_reported                                               | Jobs Reported                                               | text      | text        |
| No       |                | project_site_address                                        | Project Site Address                                        | text      | text        |
| Yes      | series tag     | city                                                        | City                                                        | text      | text        |
| Yes      | series tag     | state                                                       | State                                                       | text      | text        |
| Yes      | series tag     | zip                                                         | Zip                                                         | text      | text        |
| Yes      | series tag     | project_location_county_code                                | Project Location County Code                                | text      | text        |
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = project_site_address
```

## Data Commands

```ls
series e:mbzh-aqdc d:2012-06-30T00:00:00.000Z t:project_location_congressional_district=1 t:income_tax_benefit="Qualified Oregon facilities that manufacture renewable energy resource equipment may be eligible for a tax credit equal to 50% of maximum eligible cost under provisions established in ORS 285C.540 to 285C.559." t:outcomes="Qualified business recruitment or expansion project that creates/retains Oregon jobs, and manufactures products for the harvest/generation of renewable energy or electric vehicles and component parts." t:zip=97124 t:preliminary_certification_issued=12/31/08 t:application=26000 t:final_certified_amount_letter_issued=9/13/11 t:jobs_reported="Confidential Oregon Employment Department data." t:issuing_agency=OBDD t:state=OR t:project_owner_taxpayer_approved_for_allowance_of_tax_credit="SolarWorld Industries America, Inc." t:qualification_for_approval="Received preliminary certification after technical and due diligence review of financial model and plan;  signed performance agreement; completed and opened facility; received approval for final certification; tax credit certificate issued." t:project_location_county_code=34F t:project_type="Solar Manufacturing" t:city=Hillsboro m:final_certified_project_cost_amount=40000000 m:tax_certificate_amount_issued_fiscal_year_2012=15392184 m:final_certified_tax_credit_amount=20000000
```

## Meta Commands

```ls
metric m:final_certified_project_cost_amount p:long l:"Final Certified Project Cost Amount" t:dataTypeName=money

metric m:final_certified_tax_credit_amount p:long l:"Final Certified Tax Credit Amount" t:dataTypeName=money

metric m:tax_certificate_amount_issued_fiscal_year_2012 p:long l:"Tax Certificate Amount Issued Fiscal Year 2012" t:dataTypeName=money

entity e:mbzh-aqdc l:"Renewable Resource Equipment Manufacturing" t:url=https://data.oregon.gov/api/views/mbzh-aqdc

property e:mbzh-aqdc t:meta.view v:id=mbzh-aqdc v:category="Revenue & Expense" v:averageRating=0 v:name="Renewable Resource Equipment Manufacturing"

property e:mbzh-aqdc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:mbzh-aqdc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| issuing_agency | report_period_end_date | project_owner_taxpayer_approved_for_allowance_of_tax_credit | project_location_congressional_district | income_tax_benefit                                                                                                                                                                                                | outcomes                                                                                                                                                                                                 | qualification_for_approval                                                                                                                                                                                                                      | application | project_type        | preliminary_certification_issued | final_certified_amount_letter_issued | final_certified_project_cost_amount | final_certified_tax_credit_amount | tax_certificate_amount_issued_fiscal_year_2012 | jobs_reported                                   | project_site_address  | city      | state | zip   | project_location_county_code | 
| ============== | ====================== | =========================================================== | ======================================= | ================================================================================================================================================================================================================= | ======================================================================================================================================================================================================== | =============================================================================================================================================================================================================================================== | =========== | =================== | ================================ | ==================================== | =================================== | ================================= | ============================================== | =============================================== | ===================== | ========= | ===== | ===== | ============================ | 
| OBDD           | 6/30/12                | SolarWorld Industries America, Inc.                         | 1                                       | Qualified Oregon facilities that manufacture renewable energy resource equipment may be eligible for a tax credit equal to 50% of maximum eligible cost under provisions established in ORS 285C.540 to 285C.559. | Qualified business recruitment or expansion project that creates/retains Oregon jobs, and manufactures products for the harvest/generation of renewable energy or electric vehicles and component parts. | Received preliminary certification after technical and due diligence review of financial model and plan; signed performance agreement; completed and opened facility; received approval for final certification; tax credit certificate issued. | 26000       | Solar Manufacturing | 12/31/08                         | 9/13/11                              | $40,000,000                         | $20,000,000                       | $15,392,184                                    | Confidential Oregon Employment Department data. | 25300 NW Evergreen Rd | Hillsboro | OR    | 97124 | 34F                          | 
```