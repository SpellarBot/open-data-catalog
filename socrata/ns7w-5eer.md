# Business Energy Tax Credit Program - Updated December 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-energy-tax-credit-program-update-as-of-december-2012-b4cd0) |
| Metadata | [Link](https://data.oregon.gov/api/views/ns7w-5eer) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ns7w-5eer/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ns7w-5eer/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ns7w-5eer |
| Name | Business Energy Tax Credit Program - Updated December 2012 |
| Category | Revenue & Expense |
| Created | 2013-02-07T18:28:47Z |
| Publication Date | 2015-12-27T22:32:58Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | agency_issuing_tax_expenditure | Agency Issuing Tax Expenditure | text      | text        |
| Yes      | time           | final_year                     | Final Year                     | number    | text        |
| No       |                | final_date                     | Final Date                     | text      | text        |
| Yes      | series tag     | applicant_business_name        | Applicant Business Name        | text      | text        |
| No       |                | site_address                   | Site Address                   | text      | text        |
| Yes      | series tag     | site_city                      | Site City                      | text      | text        |
| Yes      | series tag     | site_zip                       | Site Zip                       | text      | text        |
| Yes      | series tag     | site_county                    | Site County                    | text      | text        |
| Yes      | series tag     | system                         | System                         | text      | text        |
| Yes      | series tag     | system_name                    | System Name                    | text      | text        |
| Yes      | numeric metric | final_month                    | Final Month                    | number    | text        |
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | money     | money       |
| Yes      | numeric metric | final_tax_credit               | Final Tax Credit               | money     | money       |
| Yes      | series tag     | total_energy_mmbtu             | Total Energy (MMBtu)           | text      | text        |
| Yes      | series tag     | tax_credit_rate                | Tax Credit Rate                | text      | text        |
| Yes      | series tag     | application                    | Application #                  | text      | number      |
```

## Time Field

```ls
Value = final_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = final_date,site_address
```

## Data Commands

```ls
series e:ns7w-5eer d:2012-01-01T00:00:00.000Z t:site_city=Corvallis t:applicant_business_name="SOO OSU Kelly College of Engineering" t:system=Conservation t:application=11140 t:site_zip=97331 t:site_county=Bent t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:tax_credit_rate=35% t:total_energy_mmbtu="* 5,386" t:system_name="HVAC System" m:final_certified_project_cost=918013 m:final_month=6 m:final_tax_credit=321305

series e:ns7w-5eer d:2012-01-01T00:00:00.000Z t:site_city=Wilsonville t:applicant_business_name="Xzeres Wind Corp." t:system="RD&D - Renewable" t:application=11695 t:site_zip=97070 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:tax_credit_rate=50% t:total_energy_mmbtu=0.0 t:system_name="RD&D - Renewable" m:final_certified_project_cost=80527 m:final_month=1 m:final_tax_credit=40264

series e:ns7w-5eer d:2012-01-01T00:00:00.000Z t:site_city=Portland t:applicant_business_name="12W RPO, LLC" t:system="Sustainable Building" t:application=16261 t:site_zip=97204 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:tax_credit_rate=35% t:total_energy_mmbtu=0.0 t:system_name="USGBC LEED (NC) Platinum" m:final_certified_project_cost=2757731 m:final_month=1 m:final_tax_credit=965206
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=money

metric m:final_tax_credit p:integer l:"Final Tax Credit" t:dataTypeName=money

entity e:ns7w-5eer l:"Business Energy Tax Credit Program - Updated December 2012" t:url=https://data.oregon.gov/api/views/ns7w-5eer

property e:ns7w-5eer t:meta.view v:id=ns7w-5eer v:category="Revenue & Expense" v:averageRating=0 v:name="Business Energy Tax Credit Program - Updated December 2012"

property e:ns7w-5eer t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ns7w-5eer t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | final_year | final_date | applicant_business_name                           | site_address                 | site_city   | site_zip | site_county | system                          | system_name                           | final_month | final_certified_project_cost | final_tax_credit | total_energy_mmbtu | tax_credit_rate | application | 
| ============================== | ========== | ========== | ================================================= | ============================ | =========== | ======== | =========== | =============================== | ===================================== | =========== | ============================ | ================ | ================== | =============== | =========== | 
| Oregon Department of Energy    | 2012       | 6/25/12    | SOO OSU Kelly College of Engineering              | 2500 SW Monroe Ave. Bldg B-1 | Corvallis   | 97331    | Bent        | Conservation                    | HVAC System                           | 6           | 918013                       | 321305           | * 5,386            | 35%             | 11140       | 
| Oregon Department of Energy    | 2012       | 1/23/12    | Xzeres Wind Corp.                                 | 9026 SW Hillman, Suite 3126  | Wilsonville | 97070    | Clac        | RD&D - Renewable                | RD&D - Renewable                      | 1           | 80527                        | 40264            | 0.0                | 50%             | 11695       | 
| Oregon Department of Energy    | 2012       | 1/10/12    | 12W RPO, LLC                                      | 431 SW 12th Ave              | Portland    | 97204    | Mult        | Sustainable Building            | USGBC LEED (NC) Platinum              | 1           | 2757731                      | 965206           | 0.0                | 35%             | 16261       | 
| Oregon Department of Energy    | 2011       | 9/23/11    | Legacy Health System Corporate Office             | 1919 NW Lovejoy St           | Portland    | 97209    | Mult        | Transportation                  | Transit Passes                        | 9           | 238471                       | 83465            | * 24,414           | 35%             | 17421       | 
| Oregon Department of Energy    | 2011       | 7/26/11    | AJL Enterprises, LLC                              | 1539 NW 19th Ave             | Portland    | 97209    | Mult        | Conservation                    | HVAC System                           | 7           | 121350                       | 42473            | * 475              | 35%             | 17863       | 
| Oregon Department of Energy    | 2011       | 7/26/11    | AJL Enterprises, LLC                              | 1919 NW Quimby St            | Portland    | 97209    | Mult        | Conservation                    | HVAC System                           | 7           | 193634                       | 67772            | * 495              | 35%             | 17864       | 
| Oregon Department of Energy    | 2011       | 12/15/11   | Power Resources Cooperative-Transfered to Holzman | 29160 Coffin Butte Rd        | Corvallis   | 97401    | Bent        | Biomass                         | Landfill Gas                          | 12          | 5000000                      | 2500000          | * 86,427           | 50%             | 18093       | 
| Oregon Department of Energy    | 2011       | 10/18/11   | PaTu Wind Farm /formerly Oregon Trail Wind Farm   | North Klondike Road          | Wasco       | 97065    | Sher        | Wind                            | Windfarm                              | 10          | 16241393                     | 8120697          | * 12,366           | 50%             | 18169       | 
| Oregon Department of Energy    | 2012       | 1/16/12    | SOO OSU Campus                                    | OSU Campus                   | Corvallis   | 97331    | Bent        | Co-Generation - High-Efficiency | High-Efficiency Combined Heat & Power | 1           | 8118705                      | 4059353          | * 106,203          | 50%             | 18217       | 
| Oregon Department of Energy    | 2011       | 7/5/11     | Providence Health System                          | 4805 NE Glisan Street        | Portland    | 97213    | Mult        | Transportation                  | Transit Shuttle                       | 7           | 137778                       | 48222            | * 1,439            | 35%             | 18512       | 
```