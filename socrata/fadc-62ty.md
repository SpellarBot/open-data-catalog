# 2015 - Energy Incentive Program: Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-energy-incentive-program-fiscal-year-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/fadc-62ty) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fadc-62ty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fadc-62ty/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fadc-62ty |
| Name | 2015 - Energy Incentive Program: Fiscal Year 2015 |
| Category | Revenue & Expense |
| Tags | 2015; energy; energy incentive; energy incentive program; incentive program; 2015 |
| Created | 2015-12-27T06:37:47Z |
| Publication Date | 2015-12-27T22:14:42Z |

## Description

OREGON DEPARTMENT OF ENERGY 9/23/2015 - ENERGY INCENTIVE PROGRAM (EIP). For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

## Columns

```ls
| Included | Schema Type    | Field Name                                                             | Name                                                                   | Data Type     | Render Type   |
| ======== | ============== | ====================================================================== | ====================================================================== | ============= | ============= |
| No       |                | fiscal_year                                                            | Fiscal Year                                                            | number        | number        |
| Yes      | series tag     | agency_issuing_tax_expenditure                                         | Agency Issuing Tax Expenditure                                         | text          | text          |
| No       |                | final_year                                                             | Final Year                                                             | number        | number        |
| Yes      | numeric metric | final_month                                                            | Final Month                                                            | number        | number        |
| Yes      | time           | date_final_certificate_issued_to_project_owner_or_grant_award_approved | Date Final Certificate Issued to project owner or Grant Award Approved | calendar_date | calendar_date |
| No       |                | date_final_certified_amount_letter_issued                              | Date Final Certified Amount Letter Issued                              | calendar_date | calendar_date |
| Yes      | series tag     | contact_name                                                           | Contact Name                                                           | text          | text          |
| Yes      | series tag     | applicant_business_name                                                | Applicant Business Name                                                | text          | text          |
| Yes      | series tag     | site_city                                                              | Site City                                                              | text          | text          |
| Yes      | series tag     | site_county                                                            | Site County                                                            | text          | text          |
| Yes      | series tag     | project_type                                                           | Project Type                                                           | text          | text          |
| Yes      | series tag     | program                                                                | Program                                                                | text          | text          |
| Yes      | series tag     | system_type                                                            | System Type                                                            | text          | text          |
| Yes      | numeric metric | nominal_capacity_peak_rated_output                                     | Nominal Capacity (Peak Rated Output)                                   | number        | number        |
| Yes      | series tag     | kwh_production_per_year                                                | kWh Production per year                                                | text          | text          |
| Yes      | numeric metric | kwh_savings                                                            | kWh Savings                                                            | number        | number        |
| Yes      | series tag     | therm_savings                                                          | Therm Savings                                                          | text          | text          |
| Yes      | series tag     | propane_savings                                                        | Propane Savings                                                        | text          | text          |
| Yes      | numeric metric | gasoline_gallons_saved_displaced                                       | Gasoline Gallons Saved/Displaced                                       | number        | number        |
| Yes      | numeric metric | diesel_gallons_saved_displaced                                         | Diesel Gallons Saved/Displaced                                         | number        | number        |
| Yes      | series tag     | total_energy_saved_displaced_in_million_btu                            | Total Energy Saved & Displaced in Million Btu                          | text          | text          |
| Yes      | numeric metric | project_cost                                                           | Project Cost                                                           | money         | money         |
| Yes      | numeric metric | final_tax_credit_or_grant_award                                        | Final Tax Credit or Grant Award                                        | money         | money         |
| Yes      | numeric metric | grant_rate                                                             | Grant Rate (%)                                                         | number        | number        |
| Yes      | series tag     | application                                                            | Application #                                                          | text          | text          |
```

## Time Field

```ls
Value = date_final_certificate_issued_to_project_owner_or_grant_award_approved
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_year,date_final_certified_amount_letter_issued,fiscal_year
```

## Data Commands

```ls
series e:fadc-62ty d:2014-08-21T00:00:00.000Z t:site_city=Salem t:total_energy_saved_displaced_in_million_btu="* 86.66" t:system_type="Building Envelope" t:applicant_business_name="Lien Nguyen" t:application="CS 552" t:site_county=Marion t:propane_savings="* 13" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Small Premium Project (SPP)" t:kwh_production_per_year="* 22,504" t:therm_savings="* 87" t:contact_name="Lien Nguyen" t:project_type=Conservation m:project_cost=16158 m:final_month=8 m:gasoline_gallons_saved_displaced=0 m:diesel_gallons_saved_displaced=0 m:grant_rate=0.3499814333457111 m:kwh_savings=0 m:final_tax_credit_or_grant_award=5655

series e:fadc-62ty d:2015-12-26T22:37:50.000Z t:site_city=Tillamook t:total_energy_saved_displaced_in_million_btu="* 308" t:system_type="EV Charging Station" t:applicant_business_name="Lease-it, Inc." t:application="AF 007" t:site_county=Tillamook t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Alternate Fuel Vehicle Infrastruture" t:contact_name="William Emberlin" t:project_type=Transportation m:project_cost=124000 m:final_month=9 m:final_tax_credit_or_grant_award=43400

series e:fadc-62ty d:2014-10-03T00:00:00.000Z t:site_city=Salem t:total_energy_saved_displaced_in_million_btu="* 307" t:system_type="Building Envelope" t:applicant_business_name="Waldo Street, LLC." t:application="CB 15" t:site_county=Marion t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Commercial Building Envelope" t:contact_name="CE Tichinin" t:project_type=Conservation m:project_cost=110737 m:final_month=10 m:grant_rate=0.35000045152026876 m:final_tax_credit_or_grant_award=38758
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:nominal_capacity_peak_rated_output p:float l:"Nominal Capacity (Peak Rated Output)" t:dataTypeName=number

metric m:kwh_savings p:float l:"kWh Savings" t:dataTypeName=number

metric m:gasoline_gallons_saved_displaced p:float l:"Gasoline Gallons Saved/Displaced" t:dataTypeName=number

metric m:diesel_gallons_saved_displaced p:float l:"Diesel Gallons Saved/Displaced" t:dataTypeName=number

metric m:project_cost p:integer l:"Project Cost" t:dataTypeName=money

metric m:final_tax_credit_or_grant_award p:integer l:"Final Tax Credit or Grant Award" t:dataTypeName=money

metric m:grant_rate p:double l:"Grant Rate (%)" t:dataTypeName=number

entity e:fadc-62ty l:"2015 - Energy Incentive Program: Fiscal Year 2015" t:url=https://data.oregon.gov/api/views/fadc-62ty

property e:fadc-62ty t:meta.view v:id=fadc-62ty v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - Energy Incentive Program: Fiscal Year 2015"

property e:fadc-62ty t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:fadc-62ty t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure | final_year | final_month | date_final_certificate_issued_to_project_owner_or_grant_award_approved | date_final_certified_amount_letter_issued | contact_name                 | applicant_business_name      | site_city | site_county | project_type   | program                              | system_type         | nominal_capacity_peak_rated_output | kwh_production_per_year | kwh_savings | therm_savings | propane_savings | gasoline_gallons_saved_displaced | diesel_gallons_saved_displaced | total_energy_saved_displaced_in_million_btu | project_cost | final_tax_credit_or_grant_award | grant_rate          | application | 
| =========== | ============================== | ========== | =========== | ====================================================================== | ========================================= | ============================ | ============================ | ========= | =========== | ============== | ==================================== | =================== | ================================== | ======================= | =========== | ============= | =============== | ================================ | ============================== | =========================================== | ============ | =============================== | =================== | =========== | 
| 2015        | Oregon Department of Energy    | 2014       | 8           | 2014-08-21T00:00:00                                                    |                                           | Lien Nguyen                  | Lien Nguyen                  | Salem     | Marion      | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 22,504                | 0.0         | * 87          | * 13            | 0.0                              | 0.0                            | * 86.66                                     | 16158        | 5655                            | 0.34998143334571108 | CS 552      | 
| 2015        | Oregon Department of Energy    | 2014       | 9           |                                                                        | 2014-09-29T00:00:00                       | William Emberlin             | Lease-it, Inc.               | Tillamook | Tillamook   | Transportation | Alternate Fuel Vehicle Infrastruture | EV Charging Station |                                    |                         |             |               |                 |                                  |                                | * 308                                       | 124000       | 43400                           |                     | AF 007      | 
| 2015        | Oregon Department of Energy    | 2014       | 10          | 2014-10-03T00:00:00                                                    |                                           | CE Tichinin                  | Waldo Street, LLC.           | Salem     | Marion      | Conservation   | Commercial Building Envelope         | Building Envelope   |                                    |                         |             |               |                 |                                  |                                | * 307                                       | 110737       | 38758                           | 0.35000045152026876 | CB 15       | 
| 2015        | Oregon Department of Energy    | 2014       | 8           | 2014-08-19T00:00:00                                                    |                                           | Gay A. Hart                  | GKH Holdings, LLC            | Portland  | Multnomah   | Conservation   | Commercial Building Envelope         | Building Envelope   |                                    |                         |             |               |                 |                                  |                                | * 307                                       | 109006       | 38152                           | 0.34999908261930535 | CB 8        | 
| 2015        | Oregon Department of Energy    | 2014       | 9           | 2014-09-05T00:00:00                                                    |                                           | Russell Lester & Terry Lemon | Russell Lester & Terry Lemon | La Grande | Union       | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 4,990                 | 0.0         | * 19          | * 3             | 0.0                              | 0.0                            | * 19.22                                     | 3583         | 1254                            | 0.34998604521350823 | CS 470      | 
| 2015        | Oregon Department of Energy    | 2014       | 9           | 2014-09-05T00:00:00                                                    |                                           | Russell Lester & Terry Lemon | Russell Lester & Terry Lemon | La Grande | Union       | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 3,820                 | 0.0         | * 15          | * 2             | 0.0                              | 0.0                            | * 14.71                                     | 2743         | 960                             | 0.34998177178271966 | CS 471      | 
| 2015        | Oregon Department of Energy    | 2014       | 9           | 2014-09-05T00:00:00                                                    |                                           | Russell Lester & Terry Lemon | Russell Lester & Terry Lemon | La Grande | Union       | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 4,565                 | 0.0         | * 18          | * 3             | 0.0                              | 0.0                            | * 17.58                                     | 3278         | 1147                            | 0.34990848078096398 | CS 472      | 
| 2015        | Oregon Department of Energy    | 2014       | 7           | 2014-07-23T00:00:00                                                    |                                           | Doug Jacobson                | Doug Jacobson                | Portland  | Multnomah   | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 11,195                | 0.0         | * 43          | * 6             | 0.0                              | 0.0                            | * 43.11                                     | 8038         | 2813                            | 0.3499626772829062  | CS 493      | 
| 2015        | Oregon Department of Energy    | 2015       | 1           | 2015-01-30T00:00:00                                                    |                                           | Timothy Dahle                | Dahle Orchards LLC           | Aurora    | Marion      | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 13,252                | 0.0         | * 51          | * 7             | 0.0                              | 0.0                            | * 51.03                                     | 9515         | 3330                            | 0.34997372569626906 | CS 495      | 
| 2015        | Oregon Department of Energy    | 2014       | 8           | 2014-08-21T00:00:00                                                    |                                           | Jim McCain                   | Jim McCain                   | Salem     | Marion      | Conservation   | Small Premium Project (SPP)          | Building Envelope   |                                    | * 3,164                 | 0.0         | * 12          | * 2             | 0.0                              | 0.0                            | * 12.19                                     | 2272         | 795                             | 0.34991197183098594 | CS 527      | 
```