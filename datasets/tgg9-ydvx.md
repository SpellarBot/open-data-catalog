# 2015- SIP- FY2015- Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-sip-fy2015-report) |
| Metadata | [Link](https://data.oregon.gov/api/views/tgg9-ydvx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tgg9-ydvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tgg9-ydvx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tgg9-ydvx |
| Name | 2015- SIP- FY2015- Report |
| Category | Revenue & Expense |
| Tags | 2015; sip; oregon investment; oregon strategic investment; oregon strategic investment program; |
| Created | 2016-01-02T01:52:15Z |
| Publication Date | 2016-01-02T02:00:30Z |

## Description

Strategic Investment Program Report - Fiscal Year 2015: For more information on this program or economic development go to; http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                                | Fiscal Year                                                | number    | text        |
| Yes      | series tag     | agency_issuing_tax_expenditure                             | Agency Issuing Tax Expenditure                             | text      | text        |
| No       |                | report_period_end_date                                     | Report Period End Date                                     | text      | text        |
| Yes      | series tag     | business_firm_name                                         | Business Firm Name                                         | text      | text        |
| Yes      | series tag     | proposed_project_location                                  | Proposed Project Location                                  | text      | text        |
| Yes      | series tag     | name_of_proposed_project                                   | Name of Proposed Project                                   | text      | text        |
| Yes      | numeric metric | estimated_total_investment                                 | Estimated Total Investment                                 | money     | text        |
| Yes      | numeric metric | anticipated_first_tax_year_of_exemption                    | Anticipated First Tax Year of Exemption                    | number    | text        |
| Yes      | series tag     | property_tax_benefit_not_a_credit                          | Property Tax Benefit (not a credit)                        | text      | text        |
| Yes      | series tag     | specific_outcomes_of_the_program_and_taxpayer_requirements | Specific Outcomes of the Program and Taxpayer Requirements | text      | text        |
| Yes      | series tag     | statistics_and_methodology_employed                        | Statistics and Methodology Employed                        | text      | text        |
| Yes      | series tag     | agency_s_certification_decision                            | Agency's Certification Decision                            | text      | text        |
| No       |                | date_approved                                              | Date Approved                                              | text      | text        |
| Yes      | series tag     | facility_location_county_code                              | Facility Location County Code                              | text      | text        |
| Yes      | series tag     | facility_location_congressional_district                   | Facility Location Congressional District                   | text      | text        |
| No       |                | company_mailing_address                                    | Company Mailing Address                                    | text      | text        |
| Yes      | series tag     | company_location_1                                         | Company Location 1                                         | text      | text        |
| Yes      | series tag     | company_mailing_zip_code                                   | Company Mailing ZIP Code                                   | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = report_period_end_date,date_approved,company_mailing_address
```

## Data Commands

```ls
series e:tgg9-ydvx d:2015-01-01T00:00:00.000Z t:specific_outcomes_of_the_program_and_taxpayer_requirements="Project benefits traded-sector industry; full disclosure of concurrent, statewide employment changes; Investment costs exceed taxable portion.
Local approval pursuant to?public hearing. written agreement with business firm, vote by county governing body." t:company_location_1="Hillsboro, OR" t:agency_issuing_tax_expenditure="County Assessor (Oregon Department of Revenue)" t:business_firm_name="Intel Corporation" t:company_mailing_zip_code=97124 t:proposed_project_location="2501 NW 229th Ave, Hillsboro OR, and
3585 SW 198th Ave, Aloha OR,
Washington County" t:facility_location_county_code=67 t:statistics_and_methodology_employed="Not applicable" t:agency_s_certification_decision="Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence." t:property_tax_benefit_not_a_credit="UNREALIZED - Future project property with market value in excess of taxable portion exempt over as many as 15 years, less community service fee and payments under locally negotiated requirements" t:facility_location_congressional_district=1 t:name_of_proposed_project="SIP 2014" m:anticipated_first_tax_year_of_exemption=2017 m:estimated_total_investment=100000000000
```

## Meta Commands

```ls
metric m:estimated_total_investment p:long l:"Estimated Total Investment" t:dataTypeName=money

metric m:anticipated_first_tax_year_of_exemption p:integer l:"Anticipated First Tax Year of Exemption" t:dataTypeName=number

entity e:tgg9-ydvx l:"2015- SIP- FY2015- Report" t:url=https://data.oregon.gov/api/views/tgg9-ydvx

property e:tgg9-ydvx t:meta.view v:id=tgg9-ydvx v:category="Revenue & Expense" v:averageRating=0 v:name="2015- SIP- FY2015- Report"

property e:tgg9-ydvx t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tgg9-ydvx t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure                 | report_period_end_date | business_firm_name | proposed_project_location                                                           | name_of_proposed_project | estimated_total_investment | anticipated_first_tax_year_of_exemption | property_tax_benefit_not_a_credit                                                                                                                                                                  | specific_outcomes_of_the_program_and_taxpayer_requirements                                                                                                                                                                                                     | statistics_and_methodology_employed | agency_s_certification_decision                                                                                                 | date_approved | facility_location_county_code | facility_location_congressional_district | company_mailing_address | company_location_1 | company_mailing_zip_code | 
| =========== | ============================================== | ====================== | ================== | =================================================================================== | ======================== | ========================== | ======================================= | ================================================================================================================================================================================================== | ============================================================================================================================================================================================================================================================== | =================================== | =============================================================================================================================== | ============= | ============================= | ======================================== | ======================= | ================== | ======================== | 
| 2015        | County Assessor (Oregon Department of Revenue) | 6/30/2015              | Intel Corporation  | 2501 NW 229th Ave, Hillsboro OR, and 3585 SW 198th Ave, Aloha OR, Washington County | SIP 2014                 | $100,000,000,000           | 2017                                    | UNREALIZED - Future project property with market value in excess of taxable portion exempt over as many as 15 years, less community service fee and payments under locally negotiated requirements | Project benefits traded-sector industry; full disclosure of concurrent, statewide employment changes; Investment costs exceed taxable portion. Local approval pursuant to?public hearing. written agreement with business firm, vote by county governing body. | Not applicable                      | Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence. | 9/5/2014      | 67                            | 1                                        | 5200 NE Elam Young Pwky | Hillsboro, OR      | 97124                    | 
```