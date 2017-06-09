# Strategic Investment Program (SIP): FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/strategic-investment-program-sip-fy2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/tmti-aa3m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tmti-aa3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tmti-aa3m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tmti-aa3m |
| Name | Strategic Investment Program (SIP): FY2016 |
| Attribution | Business Oregon |
| Category | Revenue & Expense |
| Tags | transparency, strategic investment program, fiscal year 2016 report |
| Created | 2016-10-05T23:12:09Z |
| Publication Date | 2016-10-06T18:16:47Z |

## Description

Determination of Eligible Project by Oregon Business Development Commission under ORS 285C.606, for which information is not otherwise maintained in a database. For more information visit www.oregon4biz.com/Oregon-Business/Tax-Incentives/SIP/

## Columns

```ls
| Included | Schema Type | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | =========== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | time        | fiscal_year                                                | Fiscal Year                                                | number    | text        |
| Yes      | series tag  | agency_issuing_tax_expenditure                             | Agency Issuing Tax Expenditure                             | text      | text        |
| No       |             | report_period_end_date                                     | Report Period End Date                                     | text      | text        |
| Yes      | series tag  | business_firm_name                                         | Business Firm Name                                         | text      | text        |
| Yes      | series tag  | proposed_project_location                                  | Proposed Project Location                                  | text      | text        |
| Yes      | series tag  | name_of_proposed_project                                   | Name of Proposed Project                                   | text      | text        |
| Yes      | series tag  | estimated_total_investment                                 | Estimated Total Investment                                 | text      | text        |
| Yes      | series tag  | anticipated_first_tax_year_of_exemption                    | Anticipated First Tax Year of Exemption                    | text      | text        |
| Yes      | series tag  | property_tax_benefit_not_a_credit                          | Property Tax Benefit (not a credit)                        | text      | text        |
| Yes      | series tag  | specific_outcomes_of_the_program_and_taxpayer_requirements | Specific Outcomes of the Program and Taxpayer Requirements | text      | text        |
| Yes      | series tag  | statistics_and_methodology_employed                        | Statistics and Methodology Employed                        | text      | text        |
| Yes      | series tag  | agency_s_certification_decision                            | Agency's Certification Decision                            | text      | text        |
| No       |             | date_approved                                              | Date Approved                                              | text      | text        |
| Yes      | series tag  | facility_location_county_code                              | Facility Location County Code                              | text      | text        |
| Yes      | series tag  | facility_location_congressional_district                   | Facility Location Congressional District                   | text      | text        |
| No       |             | company_mailing_address_w_zip                              | Company Mailing Address (w/ZIP)                            | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = report_period_end_date,date_approved,company_mailing_address_w_zip
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:tmti-aa3m l:"Strategic Investment Program (SIP): FY2016" t:attribution="Business Oregon" t:url=https://data.oregon.gov/api/views/tmti-aa3m

property e:tmti-aa3m t:meta.view d:2017-06-09T13:55:23.632Z v:id=tmti-aa3m v:category="Revenue & Expense" v:attributionLink=http://www.oregon4biz.com/ v:averageRating=0 v:name="Strategic Investment Program (SIP): FY2016" v:attribution="Business Oregon"

property e:tmti-aa3m t:meta.view.owner d:2017-06-09T13:55:23.632Z v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:displayName=carmens

property e:tmti-aa3m t:meta.view.tableauthor d:2017-06-09T13:55:23.632Z v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:roleName=editor v:displayName=carmens
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure                 | report_period_end_date | business_firm_name                               | proposed_project_location | name_of_proposed_project | estimated_total_investment | anticipated_first_tax_year_of_exemption | property_tax_benefit_not_a_credit                                                                                                                                                       | specific_outcomes_of_the_program_and_taxpayer_requirements                                                                                                                               | statistics_and_methodology_employed | agency_s_certification_decision                                                                                                  | date_approved | facility_location_county_code | facility_location_congressional_district | company_mailing_address_w_zip | 
| =========== | ============================================== | ====================== | ================================================ | ========================= | ======================== | ========================== | ======================================= | ======================================================================================================================================================================================= | ======================================================================================================================================================================================== | =================================== | ================================================================================================================================ | ============= | ============================= | ======================================== | ============================= | 
| 2016        | County Assessor (Oregon Department of Revenue) | 6/30/16                | [No approvals were made during this fiscal year] | n/a                       | n/a                      | n/a                        | n/a                                     | (Future project property with market value in excess of taxable portion exempt over as many as 15 years, less community service fee and payments under locally negotiated requirements) | (Project benefits traded-sector industry; full disclosure of concurrent, statewide employment changes; investment costs exceed taxable portion, and local approval pursuant to statutes) | n/a                                 | (Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence) | n/a           | n/a                           | n/a                                      | n/a                           | 
```