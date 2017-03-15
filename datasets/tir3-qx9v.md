# Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-new-markets-tax-credit-nmtc-program-2014-update-1-26-15-bc90e) |
| Metadata | [Link](https://data.oregon.gov/api/views/tir3-qx9v) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tir3-qx9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tir3-qx9v/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tir3-qx9v |
| Name | Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15) |
| Category | Revenue & Expense |
| Tags | oregon new markets tax credit program, 2014, oregon nmtc, nmtc 2014 |
| Created | 2015-01-26T21:38:18Z |
| Publication Date | 2015-01-26T22:00:14Z |
| Rows Updated | 2015-01-26T21:49:38Z |

## Description

(1.26.15 update) The Oregon Low Income Community Jobs Initiative (Oregon New Markets Tax Credit, or NMTC) program helps finance investments and create jobs in low-income communities; delivers below-market-rate investment options to Oregon businesses; attracts additional Federal New Market Tax Credit investments in Oregon; and sparks revitalization in Oregon’s low-income communities. The program is available to Community Development Entities (CDEs) serving Oregon that have been allocated Federal New Market Tax Credits. The Oregon new market tax credits are then provided to investors who make qualified equity investments in community development entities that in turn invest in projects located in low-income communities. Investments can only be made in qualified, existing low-income community businesses located in Oregon as defined by section 45D of the Internal Revenue Code. If you have additional questions, please contact Laura Engstrom at laura.engstrom@oregon.gov

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                 | Name                                                                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================================================================== | ========================================================================================== | ============= | ============= |
| Yes      | series tag     | issuing_agency                                                                             | Issuing Agency                                                                             | text          | text          |
| Yes      | time           | report_period_end_date                                                                     | Report Period End Date                                                                     | calendar_date | calendar_date |
| Yes      | series tag     | eligibility_determination_made_by_community_development_entity                             | Eligibility Determination made by Community Development Entity                             | text          | text          |
| Yes      | series tag     | quality_active_low_income_community_business                                               | Quality Active Low Income Community Business                                               | text          | text          |
| Yes      | series tag     | project_location                                                                           | Project Location                                                                           | text          | text          |
| Yes      | series tag     | project_location_county_code                                                               | Project Location County Code                                                               | text          | number        |
| Yes      | series tag     | project_location_congressional_district                                                    | Project Location Congressional District                                                    | text          | number        |
| Yes      | series tag     | number_of_employment_for_created_jobs                                                      | Number of Employment for Created Jobs                                                      | text          | text          |
| Yes      | series tag     | number_of_employment_for_retained_jobs                                                     | Number of Employment for Retained Jobs                                                     | text          | text          |
| Yes      | numeric metric | number_of_employment_created_and_or_retained_jobs_with_health_benefits                     | Number of Employment (created and/or retained) Jobs with Health Benefits                   | number        | number        |
| Yes      | numeric metric | average_annual_salary_of_employment                                                        | Average Annual Salary of Employment                                                        | money         | text          |
| Yes      | series tag     | investment_satisfied_documentation_complete_subject_to_confidentiality_laws                | Investment Satisfied/Documentation Complete (subject to confidentiality laws)              | text          | text          |
| Yes      | numeric metric | total_project_costs                                                                        | Total Project Costs                                                                        | number        | number        |
| Yes      | numeric metric | total_amount_of_state_new_market_tax_allocation                                            | Total Amount of State New Market Tax Allocation                                            | number        | number        |
| Yes      | numeric metric | total_amount_of_federal_new_market_tax_allocation                                          | Total Amount of Federal New Market Tax Allocation                                          | number        | number        |
| Yes      | numeric metric | total_costs_of_professional_fees_note_cde_does_not_charge_fees                             | Total Costs of Professional Fees(note: *CDE does not charge fees)                          | number        | number        |
| Yes      | series tag     | meets_green_project_requirements_per_oar_123_630_0090_2_a_b                                | Meets Green Project Requirements per OAR 123-630-0090(2)(a)(b)                             | text          | text          |
| Yes      | series tag     | other_social_community_and_or_economic_impacts                                             | Other Social, Community and/or Economic Impacts                                            | text          | text          |
| Yes      | series tag     | tax_credit_recipient_quality_equity_investor                                               | Tax Credit Recipient Quality Equity Investor                                               | text          | text          |
| No       |                | maximum_amount_of_tax_credit_made_available_to_quality_equity_investor_in_current_tax_year | Maximum Amount of Tax Credit Made Available to Quality Equity Investor in Current Tax Year | number        | number        |
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = maximum_amount_of_tax_credit_made_available_to_quality_equity_investor_in_current_tax_year
```

## Data Commands

```ls
series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:other_social_community_and_or_economic_impacts="Providing a local customer for woody biomass created by the local forest industry, IBR reduces the environmental impact and cost of transporting biomass outside of the region." t:project_location_congressional_district=2 t:quality_active_low_income_community_business="Integrated Biomass Resources LLC" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:project_location=Wallowa t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=Yes t:issuing_agency="Business Oregon" t:number_of_employment_for_retained_jobs="15 Full-time, 2 Part-time" t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=32 t:number_of_employment_for_created_jobs="8-10 Full-time, 2-4 Part-time" m:total_amount_of_state_new_market_tax_allocation=3750000 m:average_annual_salary_of_employment=24960 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=121269 m:total_project_costs=3750000 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=0

series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:other_social_community_and_or_economic_impacts="New employees paying payroll taxes to the state.  City of Portland / County of Multnomah collection of business taxes for community services" t:project_location_congressional_district=3 t:quality_active_low_income_community_business="Hog Wild LLC" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:project_location=Portland t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=No t:issuing_agency="Business Oregon" t:number_of_employment_for_retained_jobs="16 Full-time" t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=26 t:number_of_employment_for_created_jobs="12-14 Full-time" m:total_amount_of_state_new_market_tax_allocation=2105900 m:average_annual_salary_of_employment=50775 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=77022 m:total_project_costs=2105900 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=30

series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:other_social_community_and_or_economic_impacts="Purchasing local products and utilizing services from the community.  Trucks burn biodiesel produced by SeQuential Biofuels located in Salem OR." t:project_location_congressional_district=3 t:quality_active_low_income_community_business="Brew Dr. Kombucha" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:project_location=Portland t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=No t:issuing_agency="Business Oregon" t:number_of_employment_for_retained_jobs="13 Full-time,  6 Part-time" t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=26 t:number_of_employment_for_created_jobs="12 Full-time, 4 Part-time" m:total_amount_of_state_new_market_tax_allocation=1873000 m:average_annual_salary_of_employment=33000 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=0 m:total_project_costs=2447600 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=25
```

## Meta Commands

```ls
metric m:number_of_employment_created_and_or_retained_jobs_with_health_benefits p:double l:"Number of Employment (created and/or retained) Jobs with Health Benefits" t:dataTypeName=number

metric m:average_annual_salary_of_employment p:long l:"Average Annual Salary of Employment" t:dataTypeName=money

metric m:total_project_costs p:double l:"Total Project Costs" t:dataTypeName=number

metric m:total_amount_of_state_new_market_tax_allocation p:integer l:"Total Amount of State New Market Tax Allocation" t:dataTypeName=number

metric m:total_amount_of_federal_new_market_tax_allocation p:integer l:"Total Amount of Federal New Market Tax Allocation" t:dataTypeName=number

metric m:total_costs_of_professional_fees_note_cde_does_not_charge_fees p:integer l:"Total Costs of Professional Fees(note: *CDE does not charge fees)" t:dataTypeName=number

entity e:tir3-qx9v l:"Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)" t:url=https://data.oregon.gov/api/views/tir3-qx9v

property e:tir3-qx9v t:meta.view v:id=tir3-qx9v v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)"

property e:tir3-qx9v t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:tir3-qx9v t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```