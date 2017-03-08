# Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/rzct-chc3/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/business-energy-tax-credit-program-fiscal-year-2014-0e49c)
* [Metadata URL](https://data.oregon.gov/api/views/rzct-chc3)
* Id = rzct-chc3
* Name = Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)
* Category = Revenue & Expense
* Tags = [tax credit, busiess energy tax credit, tax credit program 2014, 2014]
* Created = 2014-12-31T03:21:39Z
* Publication Date = 2015-12-27T22:27:10Z
* Rows Updated = 2015-12-27T22:25:29Z

## Description

Business Energy Tax Credit Program?Oregon Department of Energy  The Business Energy Tax Credit program ended July 1, 2014  (HB 3672 in 2011 and HB 4079 in 2012) and tax credits are no longer being awarded under this program.  
For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Department_of_Revenue_%28DOR%29_-_Reports_and_Resource_Links%C2%A0_

------------------
Historical Info
--------------------
?	This spreadsheet covers July 1, 2013 through June 30, 2014.
?	Per statute, this list does not include final certificates issued for Combined Heat and Power or High Performance Homes projects. Withdrawn, Denied, Inactive, Rejected, and Revoked Projects are also excluded.
?	Every effort has been made to ensure the data are complete, but these records reflect information reported to this agency by others. The Oregon Department of Energy is not responsible for data that is misinterpreted or altered in any way.
?	If errors are discovered after publication of the records, the data are corrected in the electronic files.  It is estimated that there is a margin of error of less than one percent.

## Columns

```ls
| Name                           | Field Name                     | Data Type     | Render Type   | Schema Type    | Included | 
| ============================== | ============================== | ============= | ============= | ============== | ======== | 
| Agency Issuing Tax Expenditure | agency_issuing_tax_expenditure | text          | text          | series tag     | Yes      | 
| Final Year                     | final_year                     | number        | number        |                | No       | 
| Final Date                     | final_date                     | calendar_date | calendar_date | time           | Yes      | 
| Applicant Business Name        | applicant_business_name        | text          | text          | series tag     | Yes      | 
| Site City                      | site_city                      | text          | text          | series tag     | Yes      | 
| Site Zip                       | site_zip                       | text          | number        | series tag     | Yes      | 
| Site County                    | site_county                    | text          | text          | series tag     | Yes      | 
| System                         | system                         | text          | text          | series tag     | Yes      | 
| System Name                    | system_name                    | text          | text          | series tag     | Yes      | 
| Final Month                    | final_month                    | number        | number        | numeric metric | Yes      | 
| Final Certified Project Cost   | final_certified_project_cost   | money         | money         | numeric metric | Yes      | 
| Final Tax Credit               | final_tax_credit               | money         | money         | numeric metric | Yes      | 
| Total Energy (Million Btu)     | total_energy_million_btu       | number        | number        | numeric metric | Yes      | 
| Tax Credit Rate                | tax_credit_ratepercentage      | number        | number        | numeric metric | Yes      | 
| Application #                  | application                    | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = final_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = final_year
Annotation Fields = 
```

## Data Commands

```ls
series e:rzct-chc3 d:2014-06-06T00:00:00.000Z t:site_city=Portland t:applicant_business_name="SOO Portland State University" t:system=Conservation t:site_zip=97201 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="HVAC System" m:final_certified_project_cost=243600 m:final_month=6 m:application=32077 m:tax_credit_ratepercentage=0.35 m:final_tax_credit=85260 m:total_energy_million_btu=2352

series e:rzct-chc3 d:2013-07-01T00:00:00.000Z t:site_city=Portland t:applicant_business_name="Northwest Evaluation Association" t:system="Sustainable Building" t:site_zip=97209 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="USGBC LEED (CI) Gold" m:final_certified_project_cost=123995 m:final_month=7 m:application=30191 m:tax_credit_ratepercentage=0.35 m:final_tax_credit=43398 m:total_energy_million_btu=0

series e:rzct-chc3 d:2013-07-31T00:00:00.000Z t:site_city=Tualatin t:applicant_business_name="Stafford Hills Racquet & Fitness Club" t:system="Sustainable Building" t:site_zip=97062 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:system_name="USGBC LEED (NC) Silver" m:final_certified_project_cost=375736 m:final_month=7 m:application=30849 m:tax_credit_ratepercentage=0.35 m:final_tax_credit=131508 m:total_energy_million_btu=0
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:total_energy_million_btu p:integer l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:tax_credit_ratepercentage l:"Tax Credit Rate" t:dataTypeName=number

metric m:application p:integer l:"Application #" t:dataTypeName=number

entity e:rzct-chc3 l:"Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)" t:url=https://data.oregon.gov/api/views/rzct-chc3

property e:rzct-chc3 t:meta.view d:2017-03-07T23:59:34.827Z v:id=rzct-chc3 v:category="Revenue & Expense" v:averageRating=0 v:name="Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)"

property e:rzct-chc3 t:meta.view.owner d:2017-03-07T23:59:34.827Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:rzct-chc3 t:meta.view.tableauthor d:2017-03-07T23:59:34.827Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```