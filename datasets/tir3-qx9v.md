# Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/tir3-qx9v/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/oregon-new-markets-tax-credit-nmtc-program-2014-update-1-26-15-bc90e)
* [Metadata URL](https://data.oregon.gov/api/views/tir3-qx9v)
* Id = tir3-qx9v
* Name = Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)
* Category = Revenue & Expense
* Tags = [oregon new markets tax credit program, 2014, oregon nmtc, nmtc 2014]
* Created = 2015-01-26T21:38:18Z
* Publication Date = 2015-01-26T22:00:14Z
* Rows Updated = 2015-01-26T21:49:38Z

## Description

(1.26.15 update) The Oregon Low Income Community Jobs Initiative (Oregon New Markets Tax Credit, or NMTC) program helps finance investments and create jobs in low-income communities; delivers below-market-rate investment options to Oregon businesses; attracts additional Federal New Market Tax Credit investments in Oregon; and sparks revitalization in Oregon?s low-income communities. The program is available to Community Development Entities (CDEs) serving Oregon that have been allocated Federal New Market Tax Credits. The Oregon new market tax credits are then provided to investors who make qualified equity investments in community development entities that in turn invest in projects located in low-income communities. Investments can only be made in qualified, existing low-income community businesses located in Oregon as defined by section 45D of the Internal Revenue Code. If you have additional questions, please contact Laura Engstrom at laura.engstrom@oregon.gov

## Columns

```ls
| Name                                                                                       | Field Name                                                                                 | Data Type     | Render Type   | Schema Type    | Included | 
| ========================================================================================== | ========================================================================================== | ============= | ============= | ============== | ======== | 
| Issuing Agency                                                                             | issuing_agency                                                                             | text          | text          | series tag     | Yes      | 
| Report Period End Date                                                                     | report_period_end_date                                                                     | calendar_date | calendar_date | time           | Yes      | 
| Eligibility Determination made by Community Development Entity                             | eligibility_determination_made_by_community_development_entity                             | text          | text          | series tag     | Yes      | 
| Quality Active Low Income Community Business                                               | quality_active_low_income_community_business                                               | text          | text          | series tag     | Yes      | 
| Project Location                                                                           | project_location                                                                           | text          | text          | series tag     | Yes      | 
| Project Location County Code                                                               | project_location_county_code                                                               | text          | number        | series tag     | Yes      | 
| Project Location Congressional District                                                    | project_location_congressional_district                                                    | text          | number        | series tag     | Yes      | 
| Number of Employment for Created Jobs                                                      | number_of_employment_for_created_jobs                                                      | text          | text          | series tag     | Yes      | 
| Number of Employment for Retained Jobs                                                     | number_of_employment_for_retained_jobs                                                     | text          | text          | series tag     | Yes      | 
| Number of Employment (created and/or retained) Jobs with Health Benefits                   | number_of_employment_created_and_or_retained_jobs_with_health_benefits                     | number        | number        | numeric metric | Yes      | 
| Average Annual Salary of Employment                                                        | average_annual_salary_of_employment                                                        | text          | text          | series tag     | Yes      | 
| Investment Satisfied/Documentation Complete (subject to confidentiality laws)              | investment_satisfied_documentation_complete_subject_to_confidentiality_laws                | text          | text          | series tag     | Yes      | 
| Total Project Costs                                                                        | total_project_costs                                                                        | number        | number        | numeric metric | Yes      | 
| Total Amount of State New Market Tax Allocation                                            | total_amount_of_state_new_market_tax_allocation                                            | number        | number        | numeric metric | Yes      | 
| Total Amount of Federal New Market Tax Allocation                                          | total_amount_of_federal_new_market_tax_allocation                                          | number        | number        | numeric metric | Yes      | 
| Total Costs of Professional Fees(note: *CDE does not charge fees)                          | total_costs_of_professional_fees_note_cde_does_not_charge_fees                             | number        | number        | numeric metric | Yes      | 
| Meets Green Project Requirements per OAR 123-630-0090(2)(a)(b)                             | meets_green_project_requirements_per_oar_123_630_0090_2_a_b                                | text          | text          | series tag     | Yes      | 
| Other Social, Community and/or Economic Impacts                                            | other_social_community_and_or_economic_impacts                                             | text          | text          | series tag     | Yes      | 
| Tax Credit Recipient Quality Equity Investor                                               | tax_credit_recipient_quality_equity_investor                                               | text          | text          | series tag     | Yes      | 
| Maximum Amount of Tax Credit Made Available to Quality Equity Investor in Current Tax Year | maximum_amount_of_tax_credit_made_available_to_quality_equity_investor_in_current_tax_year | number        | number        |                | No       | 
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = maximum_amount_of_tax_credit_made_available_to_quality_equity_investor_in_current_tax_year
Annotation Fields = 
```

## Data Commands

```ls
series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:project_location_congressional_district=2 t:other_social_community_and_or_economic_impacts="Providing a local customer for woody biomass created by the local forest industry, IBR reduces the environmental impact and cost of transporting biomass outside of the region." t:project_location=Wallowa t:issuing_agency="Business Oregon" t:quality_active_low_income_community_business="Integrated Biomass Resources LLC" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:average_annual_salary_of_employment="$24,960 Created and $27,040 Retained" t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=Yes t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:number_of_employment_for_retained_jobs="15 Full-time, 2 Part-time" t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=32 t:number_of_employment_for_created_jobs="8-10 Full-time, 2-4 Part-time" m:total_amount_of_state_new_market_tax_allocation=3750000 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=121269 m:total_project_costs=3750000 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=0

series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:project_location_congressional_district=3 t:other_social_community_and_or_economic_impacts="New employees paying payroll taxes to the state.  City of Portland / County of Multnomah collection of business taxes for community services" t:project_location=Portland t:issuing_agency="Business Oregon" t:quality_active_low_income_community_business="Hog Wild LLC" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:average_annual_salary_of_employment="$50,775 Created" t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=No t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:number_of_employment_for_retained_jobs="16 Full-time" t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=26 t:number_of_employment_for_created_jobs="12-14 Full-time" m:total_amount_of_state_new_market_tax_allocation=2105900 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=77022 m:total_project_costs=2105900 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=30

series e:tir3-qx9v d:2014-06-30T00:00:00.000Z t:project_location_congressional_district=3 t:other_social_community_and_or_economic_impacts="Purchasing local products and utilizing services from the community.  Trucks burn biodiesel produced by SeQuential Biofuels located in Salem OR." t:project_location=Portland t:issuing_agency="Business Oregon" t:quality_active_low_income_community_business="Brew Dr. Kombucha" t:eligibility_determination_made_by_community_development_entity="Advantage Capital" t:average_annual_salary_of_employment="$33,000 Created" t:meets_green_project_requirements_per_oar_123_630_0090_2_a_b=No t:investment_satisfied_documentation_complete_subject_to_confidentiality_laws=Yes t:number_of_employment_for_retained_jobs="13 Full-time,  6 Part-time" t:tax_credit_recipient_quality_equity_investor="AC Small Business Fund III, LLC" t:project_location_county_code=26 t:number_of_employment_for_created_jobs="12 Full-time, 4 Part-time" m:total_amount_of_state_new_market_tax_allocation=1873000 m:total_amount_of_federal_new_market_tax_allocation=13600000 m:total_costs_of_professional_fees_note_cde_does_not_charge_fees=0 m:total_project_costs=2447600 m:number_of_employment_created_and_or_retained_jobs_with_health_benefits=25
```

## Meta Commands

```ls
metric m:number_of_employment_created_and_or_retained_jobs_with_health_benefits p:integer l:"Number of Employment (created and/or retained) Jobs with Health Benefits" t:dataTypeName=number

metric m:total_project_costs l:"Total Project Costs" t:dataTypeName=number

metric m:total_amount_of_state_new_market_tax_allocation p:integer l:"Total Amount of State New Market Tax Allocation" t:dataTypeName=number

metric m:total_amount_of_federal_new_market_tax_allocation p:integer l:"Total Amount of Federal New Market Tax Allocation" t:dataTypeName=number

metric m:total_costs_of_professional_fees_note_cde_does_not_charge_fees p:integer l:"Total Costs of Professional Fees(note: *CDE does not charge fees)" t:dataTypeName=number

entity e:tir3-qx9v l:"Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)" t:url=https://data.oregon.gov/api/views/tir3-qx9v

property e:tir3-qx9v t:meta.view d:2017-03-08T01:17:24.257Z v:id=tir3-qx9v v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon New Markets Tax Credit (NMTC) Program: 2014 (update 1.26.15)"

property e:tir3-qx9v t:meta.view.owner d:2017-03-08T01:17:24.257Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:tir3-qx9v t:meta.view.tableauthor d:2017-03-08T01:17:24.257Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```