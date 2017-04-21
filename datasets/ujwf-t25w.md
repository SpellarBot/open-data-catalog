# 2015 - Residential Energy Tax Credit Program: Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-residential-energy-tax-credit-program-fiscal-year-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/ujwf-t25w) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ujwf-t25w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ujwf-t25w/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ujwf-t25w |
| Name | 2015 - Residential Energy Tax Credit Program: Fiscal Year 2015 |
| Category | Revenue & Expense |
| Tags | 2015; residential energy tax credit program; residential tax credit; energy credit program; energy program; 2015 |
| Created | 2015-12-27T05:44:54Z |
| Publication Date | 2016-01-10T02:23:15Z |

## Description

Oregon Department of Energy (Revised 9/16/15). For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_
		
RESIDENTIAL ENERGY TAX CREDIT PROGRAM							
Projects Receiving a Tax Credit of $2,000 or More.  These projects are Category 2 Alternative Energy Devices (AEDs), according to ORS 469B.100.							
Final Certificates Issued from July 1, 2014 through June 30, 2015 (Fiscal Year 2014-15)

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| No       |                | fiscal_year                    | Fiscal Year                    | number        | number        |
| Yes      | series tag     | agency_issuing_tax_expenditure | Agency Issuing Tax Expenditure | text          | text          |
| No       |                | final_year                     | Final Year                     | number        | number        |
| Yes      | time           | final_date                     | Final Date                     | calendar_date | calendar_date |
| Yes      | series tag     | applicant_name                 | Applicant Name                 | text          | text          |
| Yes      | series tag     | site_city                      | Site City                      | text          | text          |
| Yes      | series tag     | site_zip                       | Site Zip                       | text          | number        |
| Yes      | series tag     | site_county                    | Site County                    | text          | text          |
| Yes      | series tag     | system                         | System                         | text          | text          |
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | money         | money         |
| Yes      | numeric metric | tax_credit                     | Tax Credit                     | money         | money         |
| Yes      | numeric metric | percentage                     | Percentage                     | number        | number        |
| Yes      | numeric metric | net_tax_credit                 | Net Tax Credit                 | money         | money         |
| Yes      | numeric metric | total_energy_million_btu       | Total Energy (Million Btu)     | number        | number        |
| Yes      | numeric metric | units_capacity                 | UNITS CAPACITY                 | number        | number        |
| Yes      | series tag     | units_name                     | UNITS NAME                     | text          | text          |
| Yes      | series tag     | application                    | Application #                  | text          | text          |
| Yes      | series tag     | data_source                    | Data Source                    | text          | text          |
```

## Time Field

```ls
Value = final_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_year,fiscal_year
```

## Data Commands

```ls
series e:ujwf-t25w d:2015-06-24T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=ODOE-010320 t:site_zip=97229 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source=PowerClerk t:units_name=watts t:applicant_name="Ming Meng" m:final_certified_project_cost=15834 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=12.83 m:units_capacity=3640 m:net_tax_credit=6000

series e:ujwf-t25w d:2015-06-02T00:00:00.000Z t:site_city=Bend t:system=Photovoltaic t:application=ODOE-010162 t:site_zip=97701 t:site_county=Desc t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source=PowerClerk t:units_name=watts t:applicant_name="Steven Strong" m:final_certified_project_cost=13343 m:percentage=100 m:tax_credit=4284 m:total_energy_million_btu=11.36 m:units_capacity=2520 m:net_tax_credit=4284

series e:ujwf-t25w d:2015-05-20T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=ODOE-009900 t:site_zip=97215 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source=PowerClerk t:units_name=watts t:applicant_name="Carling Kirk" m:final_certified_project_cost=24200 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=16.39 m:units_capacity=6000 m:net_tax_credit=6000
```

## Meta Commands

```ls
metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=money

metric m:tax_credit p:double l:"Tax Credit" t:dataTypeName=money

metric m:percentage p:integer l:Percentage t:dataTypeName=number

metric m:net_tax_credit p:double l:"Net Tax Credit" t:dataTypeName=money

metric m:total_energy_million_btu p:float l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:units_capacity p:integer l:"UNITS CAPACITY" t:dataTypeName=number

entity e:ujwf-t25w l:"2015 - Residential Energy Tax Credit Program: Fiscal Year 2015" t:url=https://data.oregon.gov/api/views/ujwf-t25w

property e:ujwf-t25w t:meta.view v:id=ujwf-t25w v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - Residential Energy Tax Credit Program: Fiscal Year 2015"

property e:ujwf-t25w t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ujwf-t25w t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure | final_year | final_date          | applicant_name   | site_city     | site_zip | site_county | system       | final_certified_project_cost | tax_credit | percentage | net_tax_credit | total_energy_million_btu | units_capacity | units_name | application | data_source   | 
| =========== | ============================== | ========== | =================== | ================ | ============= | ======== | =========== | ============ | ============================ | ========== | ========== | ============== | ======================== | ============== | ========== | =========== | ============= | 
| 2015        | Oregon Department of Energy    | 2015       | 2015-06-24T00:00:00 | Ming Meng        | Portland      | 97229    | Clac        | Photovoltaic | 15834                        | 6000       | 100        | 6000           | 12.83                    | 3640           | watts      | ODOE-010320 | PowerClerk    | 
| 2015        | Oregon Department of Energy    | 2015       | 2015-06-02T00:00:00 | Steven Strong    | Bend          | 97701    | Desc        | Photovoltaic | 13343                        | 4284       | 100        | 4284           | 11.36                    | 2520           | watts      | ODOE-010162 | PowerClerk    | 
| 2015        | Oregon Department of Energy    | 2015       | 2015-05-20T00:00:00 | Carling Kirk     | Portland      | 97215    | Clac        | Photovoltaic | 24200                        | 6000       | 100        | 6000           | 16.39                    | 6000           | watts      | ODOE-009900 | PowerClerk    | 
| 2015        | Oregon Department of Energy    | 2015       | 2015-03-06T00:00:00 | Ann Marek        | Corvallis     | 97330    | Bent        | Photovoltaic | 12540                        | 6000       | 100        | 6000           | 13.89                    | 3300           | watts      | ODOE-100030 | PowerClerk    | 
| 2015        | Oregon Department of Energy    | 2014       | 2014-11-07T00:00:00 | Ron Ochs         | Madras        | 97741    | Jeff        | Photovoltaic | 5546                         | 2773       | 100        | 2773           | 19.100000000000001       | 1500           | watts      | 842652      | ODOE Database | 
| 2015        | Oregon Department of Energy    | 2014       | 2014-07-29T00:00:00 | Kristin Roach    | Beaverton     | 97005    | Wash        | Photovoltaic | 14250                        | 5700       | 100        | 5700           | 19.100000000000001       | 3000           | watts      | 843701      | ODOE Database | 
| 2015        | Oregon Department of Energy    | 2015       | 2015-01-15T00:00:00 | Jeromy Brown     | Oregon City   | 97045    | Clac        | Photovoltaic | 31500                        | 6000       | 100        | 6000           | 19.100000000000001       | 6630           | watts      | 844640      | ODOE Database | 
| 2015        | Oregon Department of Energy    | 2014       | 2014-07-31T00:00:00 | Virginia Kimball | Central Point | 97502    | Jack        | Photovoltaic | 12536                        | 5852       | 100        | 5852           | 19.100000000000001       | 3080           | watts      | 845353      | ODOE Database | 
| 2015        | Oregon Department of Energy    | 2014       | 2014-08-08T00:00:00 | Steve Hoyt       | Powell Butte  | 97753    | Croo        | Photovoltaic | 18500                        | 6000       | 100        | 6000           | 19.100000000000001       | 4400           | watts      | 845582      | ODOE Database | 
| 2015        | Oregon Department of Energy    | 2014       | 2014-10-24T00:00:00 | Scott Reamer     | Happy Valley  | 97086    | Clac        | Photovoltaic | 30855                        | 6000       | 100        | 6000           | 19.100000000000001       | 5610           | watts      | 845646      | ODOE Database | 
```