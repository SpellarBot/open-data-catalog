# Strategic Investment Program - Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/strategic-investment-program-fiscal-year-2012-f466a) |
| Metadata | [Link](https://data.oregon.gov/api/views/ctan-zhvv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ctan-zhvv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ctan-zhvv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ctan-zhvv |
| Name | Strategic Investment Program - Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2013-02-07T17:23:04Z |
| Publication Date | 2013-02-07T17:25:55Z |

## Description

Fiscal Year 2012 Approval of Proposed Project to Receive Strategic Investment Program (SIP) Tax Benefit under ORS 307.123; Reporting Agency: Oregon Business Development Department, on behalf of Oregon Business Development Commission*

 * Specially assembled information, not based on existing database that is maintained for equivalent purpose.

   ** For further specificity about process & criteria, see
: 
http://www.oregon4biz.com/The-Oregon-Advantage/Incentives/Strategic-Investment-Program/

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                         | Data Type | Render Type |
| ======== | ============== | ========================================================== | ============================================================ | ========= | =========== |
| Yes      | series tag     | agency_issuing_tax_expenditure                             | Agency Issuing Tax Expenditure                               | text      | text        |
| Yes      | time           | report_period_end_date                                     | Report Period End Date                                       | text      | text        |
| Yes      | series tag     | business_firm_name                                         | Business Firm Name                                           | text      | text        |
| Yes      | series tag     | project_location_county_code                               | Project Location County Code                                 | text      | text        |
| Yes      | series tag     | project_location_congressional_district                    | Project Location Congressional District                      | text      | text        |
| Yes      | series tag     | property_tax_benefit_not_a_credit                          | Property Tax Benefit**(not a credit)                         | text      | text        |
| Yes      | series tag     | specific_outcomes_of_the_program_and_taxpayer_requirements | Specific Outcomes of the Program and Taxpayer Requirements** | text      | text        |
| Yes      | series tag     | statistics_and_methodology_employed                        | Statistics and Methodology Employed                          | text      | text        |
| Yes      | series tag     | agency_s_certification_decision                            | Agency's Certification Decision                              | text      | text        |
| Yes      | series tag     | name_of_proposed_project                                   | Name of Proposed Project                                     | text      | text        |
| Yes      | numeric metric | estimated_total_investment                                 | Estimated Total Investment                                   | money     | text        |
| Yes      | series tag     | anticipated_first_tax_year_of_exemption                    | Anticipated First Tax Year of Exemption                      | text      | text        |
| No       |                | mailing_address                                            | Mailing Address*                                             | text      | text        |
| Yes      | series tag     | city                                                       | City                                                         | text      | text        |
| Yes      | series tag     | state                                                      | State                                                        | text      | text        |
| Yes      | series tag     | zip_code                                                   | ZIP Code                                                     | text      | text        |
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
series e:ctan-zhvv d:2012-06-30T00:00:00.000Z t:project_location_congressional_district=01 t:specific_outcomes_of_the_program_and_taxpayer_requirements="Project benefits traded-sector industry 
Full disclosure of concurrent, statewide employment changes 
Investment costs exceed taxable portion 
Local approval pursuant to?
 - County public hearing 
 - Written agreement with business firm
 - Vote by county governing body" t:zip_code=97204 t:agency_issuing_tax_expenditure="County Assessor (Oregon Department of Revenue)" t:business_firm_name="Portland General Electric Company" t:state=OR t:statistics_and_methodology_employed="Not applicable" t:agency_s_certification_decision="Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence." t:name_of_proposed_project="Port Westward Unit II" t:city=Portland t:anticipated_first_tax_year_of_exemption=2014-15 t:property_tax_benefit_not_a_credit="Project property with market value in excess of taxable portion exempt for 15 years, less community service fee and locally negotiated requirements" t:project_location_county_code=09 m:estimated_total_investment=307
```

## Meta Commands

```ls
metric m:estimated_total_investment p:long l:"Estimated Total Investment" t:dataTypeName=money

entity e:ctan-zhvv l:"Strategic Investment Program - Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/ctan-zhvv

property e:ctan-zhvv t:meta.view v:id=ctan-zhvv v:category="Revenue & Expense" v:averageRating=0 v:name="Strategic Investment Program - Fiscal Year 2012"

property e:ctan-zhvv t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ctan-zhvv t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure                 | report_period_end_date | business_firm_name                | project_location_county_code | project_location_congressional_district | property_tax_benefit_not_a_credit                                                                                                                   | specific_outcomes_of_the_program_and_taxpayer_requirements                                                                                                                                                                                                             | statistics_and_methodology_employed | agency_s_certification_decision                                                                                                 | name_of_proposed_project | estimated_total_investment | anticipated_first_tax_year_of_exemption | mailing_address            | city     | state | zip_code | 
| ============================================== | ====================== | ================================= | ============================ | ======================================= | =================================================================================================================================================== | ====================================================================================================================================================================================================================================================================== | =================================== | =============================================================================================================================== | ======================== | ========================== | ======================================= | ========================== | ======== | ===== | ======== | 
| County Assessor (Oregon Department of Revenue) | 6/30/12                | Portland General Electric Company | 09                           | 01                                      | Project property with market value in excess of taxable portion exempt for 15 years, less community service fee and locally negotiated requirements | Project benefits traded-sector industry Full disclosure of concurrent, statewide employment changes Investment costs exceed taxable portion Local approval pursuant to? - County public hearing - Written agreement with business firm - Vote by county governing body | Not applicable                      | Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence. | Port Westward Unit II    | $307 - 355 million         | 2014-15                                 | 121 SW Salmon St, 1WTC0402 | Portland | OR    | 97204    | 
```