# Strategic Investment Program - Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/strategic-investment-program-fiscal-year-2014-6d3fd) |
| Metadata | [Link](https://data.oregon.gov/api/views/m5xp-nzqp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/m5xp-nzqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/m5xp-nzqp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | m5xp-nzqp |
| Name | Strategic Investment Program - Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | oregon investment, oregon strategic investment, oregon strategic investment program, 2014 |
| Created | 2014-12-30T23:56:04Z |
| Publication Date | 2014-12-31T00:22:37Z |
| Rows Updated | 2014-12-30T23:57:16Z |

## Columns

```ls
| Included | Schema Type | Field Name                                                 | Name                                                         | Data Type | Render Type |
| ======== | =========== | ========================================================== | ============================================================ | ========= | =========== |
| Yes      | series tag  | agency_issuing_tax_expenditure                             | Agency Issuing Tax Expenditure                               | text      | text        |
| Yes      | time        | report_period_end_date                                     | Report Period End Date                                       | text      | text        |
| Yes      | series tag  | business_firm_name                                         | Business Firm Name                                           | text      | text        |
| No       |             | mailing_address                                            | Mailing Address                                              | text      | text        |
| Yes      | series tag  | zip_code                                                   | ZIP Code                                                     | text      | text        |
| Yes      | series tag  | project_location_county_code                               | Project Location County Code                                 | text      | text        |
| Yes      | series tag  | project_location_congressional_district                    | Project Location Congressional District                      | text      | text        |
| Yes      | series tag  | name_of_proposed_project                                   | Name of Proposed Project                                     | text      | text        |
| Yes      | series tag  | estimated_total_investment                                 | Estimated Total Investment                                   | text      | text        |
| Yes      | series tag  | anticipated_first_tax_year_of_exemption                    | Anticipated First Tax Year of Exemption                      | text      | text        |
| Yes      | series tag  | property_tax_benefit_not_a_credit                          | Property Tax Benefit**(not a credit)                         | text      | text        |
| Yes      | series tag  | specific_outcomes_of_the_program_and_taxpayer_requirements | Specific Outcomes of the Program and Taxpayer Requirements** | text      | text        |
| Yes      | series tag  | statistics_and_methodology_employed                        | Statistics and Methodology Employed                          | text      | text        |
| Yes      | series tag  | agency_s_certification_decision                            | Agency's Certification Decision                              | text      | text        |
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:m5xp-nzqp d:2014-06-30T00:00:00.000Z t:project_location_congressional_district=n/a t:specific_outcomes_of_the_program_and_taxpayer_requirements="Project benefits traded-sector industry 
Full disclosure of concurrent, statewide employment changes 
Investment costs exceed taxable portion 
Local approval pursuant to—
 - County public hearing 
 - Written agreement with business firm
 - Vote by county governing body" t:zip_code=n/a t:agency_issuing_tax_expenditure="County Assessor (Oregon Department of Revenue)" t:business_firm_name="NO APPROVALS WERE MADE DURING PRECEDING FISCAL YEAR" t:anticipated_first_tax_year_of_exemption=n/a t:statistics_and_methodology_employed="Not applicable" t:agency_s_certification_decision="Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence." t:project_location_county_code=n/a t:property_tax_benefit_not_a_credit="UNREALIZED - Project property with market value in excess of taxable portion exempt for 15 years, less community service fee and locally negotiated requirements" t:estimated_total_investment=n/a t:name_of_proposed_project=n/a m:row_number.m5xp-nzqp=1
```

## Meta Commands

```ls
metric m:row_number.m5xp-nzqp p:long l:"Row Number"

entity e:m5xp-nzqp l:"Strategic Investment Program - Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/m5xp-nzqp

property e:m5xp-nzqp t:meta.view v:id=m5xp-nzqp v:category="Revenue & Expense" v:averageRating=0 v:name="Strategic Investment Program - Fiscal Year 2014"

property e:m5xp-nzqp t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:m5xp-nzqp t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```