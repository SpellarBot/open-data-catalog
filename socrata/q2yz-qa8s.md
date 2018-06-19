# Energy Incentive Program: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-incentive-program-fiscal-year-2014-69bad) |
| Metadata | [Link](https://data.oregon.gov/api/views/q2yz-qa8s) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/q2yz-qa8s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/q2yz-qa8s/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | q2yz-qa8s |
| Name | Energy Incentive Program: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | energy, energy incentive, energy incentive program, incentive program, 2014 |
| Created | 2014-12-31T04:26:04Z |
| Publication Date | 2015-12-27T22:43:40Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ================================================= | ================================================= | ============= | ============= |
| Yes      | series tag     | agency_issuing_tax_expenditure                    | Agency Issuing Tax Expenditure                    | text          | text          |
| No       |                | final_year                                        | Final Year                                        | number        | number        |
| Yes      | numeric metric | final_month                                       | Final Month                                       | number        | number        |
| Yes      | time           | final_certificate_or_certified_amount_letter_date | Final Certificate or Certified Amount Letter Date | calendar_date | calendar_date |
| Yes      | series tag     | contact_name                                      | Contact Name                                      | text          | text          |
| Yes      | series tag     | applicant_business_name                           | Applicant Business Name                           | text          | text          |
| Yes      | series tag     | site_city                                         | Site City                                         | text          | text          |
| Yes      | series tag     | site_county                                       | Site County                                       | text          | text          |
| Yes      | series tag     | project_type                                      | Project Type                                      | text          | text          |
| Yes      | series tag     | program                                           | Program                                           | text          | text          |
| Yes      | series tag     | system_type                                       | System Type                                       | text          | text          |
| Yes      | numeric metric | nominal_capacity_peak_rated_output                | Nominal Capacity (Peak Rated Output)              | number        | number        |
| Yes      | series tag     | kwh_production_per_year                           | kWh Production per year                           | text          | text          |
| Yes      | series tag     | kwh_savings                                       | kWh Savings                                       | text          | text          |
| Yes      | series tag     | therm_savings                                     | Therm Savings                                     | text          | text          |
| Yes      | series tag     | propane_savings                                   | Propane Savings                                   | text          | text          |
| Yes      | series tag     | gasoline_gallons_saved_displaced                  | Gasoline Gallons Saved/Displaced                  | text          | text          |
| Yes      | series tag     | diesel_gallons_saved_displaced                    | Diesel Gallons Saved/Displaced                    | text          | text          |
| Yes      | numeric metric | project_cost                                      | Project Cost                                      | money         | money         |
| Yes      | numeric metric | final_tax_credit_or_grant_award                   | Final Tax Credit or Grant Award                   | money         | money         |
| Yes      | series tag     | grant_rate                                        | Grant Rate                                        | text          | text          |
| Yes      | series tag     | application                                       | Application #                                     | text          | text          |
```

## Time Field

```ls
Value = final_certificate_or_certified_amount_letter_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_year
```

## Data Commands

```ls
series e:q2yz-qa8s d:2013-07-09T00:00:00.000Z t:site_city=Turner t:applicant_business_name="Santiam Valley Ranch" t:system_type=Photovoltaic t:application="RG 004" t:site_county=Marion t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Renewable Energy Development Grants" t:kwh_production_per_year="* 21,900" t:contact_name="Kathy Lynne Bridges" t:grant_rate=0.35 t:project_type=Renewable m:project_cost=81619 m:final_month=7 m:nominal_capacity_peak_rated_output=20.4 m:final_tax_credit_or_grant_award=27965

series e:q2yz-qa8s d:2013-08-01T00:00:00.000Z t:site_city=Portland t:applicant_business_name="St. Johns Quality Homes" t:system_type="Solar Thermal Water Heating" t:application="CS 104" t:site_county=Multnomah t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Small Premium Project (SPP)" t:contact_name="Carl Vander Zanden" t:grant_rate=NA t:project_type=Conservation m:project_cost=15231.43 m:final_month=8 m:final_tax_credit_or_grant_award=5331

series e:q2yz-qa8s d:2013-08-01T00:00:00.000Z t:site_city=Salem t:applicant_business_name="Valsetz Development, LLC" t:system_type="Building Envelope" t:application="CS 255" t:site_county=Marion t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:program="Small Premium Project (SPP)" t:contact_name="Alan B. Koloen" t:grant_rate=NA t:project_type=Conservation m:project_cost=3102.86 m:final_month=8 m:final_tax_credit_or_grant_award=1086
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:nominal_capacity_peak_rated_output p:float l:"Nominal Capacity (Peak Rated Output)" t:dataTypeName=number

metric m:project_cost p:double l:"Project Cost" t:dataTypeName=money

metric m:final_tax_credit_or_grant_award p:double l:"Final Tax Credit or Grant Award" t:dataTypeName=money

entity e:q2yz-qa8s l:"Energy Incentive Program: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/q2yz-qa8s

property e:q2yz-qa8s t:meta.view v:id=q2yz-qa8s v:category="Revenue & Expense" v:averageRating=0 v:name="Energy Incentive Program: Fiscal Year 2014"

property e:q2yz-qa8s t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:q2yz-qa8s t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | final_year | final_month | final_certificate_or_certified_amount_letter_date | contact_name        | applicant_business_name     | site_city | site_county | project_type | program                             | system_type                 | nominal_capacity_peak_rated_output | kwh_production_per_year | kwh_savings | therm_savings | propane_savings | gasoline_gallons_saved_displaced | diesel_gallons_saved_displaced | project_cost | final_tax_credit_or_grant_award | grant_rate | application | 
| ============================== | ========== | =========== | ================================================= | =================== | =========================== | ========= | =========== | ============ | =================================== | =========================== | ================================== | ======================= | =========== | ============= | =============== | ================================ | ============================== | ============ | =============================== | ========== | =========== | 
| Oregon Department of Energy    | 2013       | 7           | 2013-07-09T00:00:00                               | Kathy Lynne Bridges | Santiam Valley Ranch        | Turner    | Marion      | Renewable    | Renewable Energy Development Grants | Photovoltaic                | 20.4                               | * 21,900                |             |               |                 |                                  |                                | 81619.00     | 27965.00                        | 0.35       | RG 004      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Carl Vander Zanden  | St. Johns Quality Homes     | Portland  | Multnomah   | Conservation | Small Premium Project (SPP)         | Solar Thermal Water Heating |                                    |                         |             |               |                 |                                  |                                | 15231.43     | 5331.00                         | NA         | CS 104      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Alan B. Koloen      | Valsetz Development, LLC    | Salem     | Marion      | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 3102.86      | 1086.00                         | NA         | CS 255      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Robbin Bull         | Robbin Bull                 | Dallas    | Polk        | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 965.71       | 338.00                          | NA         | CS 276      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | John Graham         | John Graham                 | Salem     | Marion      | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 771.43       | 270.00                          | NA         | CS 282      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | James Brown         | James Brown                 | Salem     | Polk        | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 3531.43      | 1236.00                         | NA         | CS 287      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Chris Holenstein    | Chris Holenstein            | Milwaukie | Clackamas   | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 18171.43     | 6360.00                         | NA         | CS 29       | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Chris Schumacher    | Chris Schumacher            | Salem     | Polk        | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 3165.71      | 1108.00                         | NA         | CS 316      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Larry Conrad        | Larry Conrad                | Salem     | Polk        | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 2374.29      | 831.00                          | NA         | CS 317      | 
| Oregon Department of Energy    | 2013       | 8           | 2013-08-01T00:00:00                               | Douglas T. Nelson   | Dorchester Properties, Ltd. | Salem     | Marion      | Conservation | Small Premium Project (SPP)         | Building Envelope           |                                    |                         |             |               |                 |                                  |                                | 740.00       | 259.00                          | NA         | CS 334      | 
```