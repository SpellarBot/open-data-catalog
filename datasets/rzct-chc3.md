# Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-energy-tax-credit-program-fiscal-year-2014-0e49c) |
| Metadata | [Link](https://data.oregon.gov/api/views/rzct-chc3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rzct-chc3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rzct-chc3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rzct-chc3 |
| Name | Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14) |
| Category | Revenue & Expense |
| Tags | tax credit, busiess energy tax credit, tax credit program 2014, 2014 |
| Created | 2014-12-31T03:21:39Z |
| Publication Date | 2015-12-27T22:27:10Z |
| Rows Updated | 2015-12-27T22:25:29Z |

## Description

Business Energy Tax Credit Program—Oregon Department of Energy  The Business Energy Tax Credit program ended July 1, 2014  (HB 3672 in 2011 and HB 4079 in 2012) and tax credits are no longer being awarded under this program.  
For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Department_of_Revenue_%28DOR%29_-_Reports_and_Resource_Links%C2%A0_

------------------
Historical Info
--------------------
•	This spreadsheet covers July 1, 2013 through June 30, 2014.
•	Per statute, this list does not include final certificates issued for Combined Heat and Power or High Performance Homes projects. Withdrawn, Denied, Inactive, Rejected, and Revoked Projects are also excluded.
•	Every effort has been made to ensure the data are complete, but these records reflect information reported to this agency by others. The Oregon Department of Energy is not responsible for data that is misinterpreted or altered in any way.
•	If errors are discovered after publication of the records, the data are corrected in the electronic files.  It is estimated that there is a margin of error of less than one percent.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type   |
| ======== | ============== | ============================== | ============================== | ========= | ============= |
| Yes      | series tag     | agency_issuing_tax_expenditure | Agency Issuing Tax Expenditure | text      | text          |
| Yes      | time           | final_year                     | Final Year                     | number    | number        |
| No       |                | final_date                     | Final Date                     | text      | calendar_date |
| Yes      | series tag     | applicant_business_name        | Applicant Business Name        | text      | text          |
| Yes      | series tag     | site_city                      | Site City                      | text      | text          |
| Yes      | series tag     | site_zip                       | Site Zip                       | text      | number        |
| Yes      | series tag     | site_county                    | Site County                    | text      | text          |
| Yes      | series tag     | system                         | System                         | text      | text          |
| Yes      | series tag     | system_name                    | System Name                    | text      | text          |
| Yes      | numeric metric | final_month                    | Final Month                    | number    | number        |
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | money     | money         |
| Yes      | numeric metric | final_tax_credit               | Final Tax Credit               | money     | money         |
| Yes      | numeric metric | total_energy_million_btu       | Total Energy (Million Btu)     | number    | number        |
| Yes      | numeric metric | tax_credit_ratepercentage      | Tax Credit Rate                | number    | number        |
| Yes      | series tag     | application                    | Application #                  | text      | number        |
```

## Time Field

```ls
Value = final_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = final_date
```

## Data Commands

```ls
series e:rzct-chc3 d:2014-01-01T00:00:00.000Z t:site_city=Portland t:applicant_business_name="SOO Portland State University" t:system=Conservation t:application=32077 t:site_zip=97201 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="HVAC System" m:final_certified_project_cost=243600 m:final_month=6 m:tax_credit_ratepercentage=0.35 m:final_tax_credit=85260 m:total_energy_million_btu=2352

series e:rzct-chc3 d:2013-01-01T00:00:00.000Z t:site_city=Portland t:applicant_business_name="Northwest Evaluation Association" t:system="Sustainable Building" t:application=30191 t:site_zip=97209 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="USGBC LEED (CI) Gold" m:final_certified_project_cost=123995 m:final_month=7 m:tax_credit_ratepercentage=0.34999798378966895 m:final_tax_credit=43398 m:total_energy_million_btu=0

series e:rzct-chc3 d:2013-01-01T00:00:00.000Z t:site_city=Tualatin t:applicant_business_name="Stafford Hills Racquet & Fitness Club" t:system="Sustainable Building" t:application=30849 t:site_zip=97062 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="USGBC LEED (NC) Silver" m:final_certified_project_cost=375736 m:final_month=7 m:tax_credit_ratepercentage=0.3500010645772564 m:final_tax_credit=131508 m:total_energy_million_btu=0
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=money

metric m:final_tax_credit p:integer l:"Final Tax Credit" t:dataTypeName=money

metric m:total_energy_million_btu p:integer l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:tax_credit_ratepercentage p:decimal l:"Tax Credit Rate" t:dataTypeName=number

entity e:rzct-chc3 l:"Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)" t:url=https://data.oregon.gov/api/views/rzct-chc3

property e:rzct-chc3 t:meta.view v:id=rzct-chc3 v:category="Revenue & Expense" v:averageRating=0 v:name="Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)"

property e:rzct-chc3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:rzct-chc3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```