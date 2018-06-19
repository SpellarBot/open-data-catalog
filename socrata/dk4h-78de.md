# 2016 ? Biomass Tax Credit Program - Producer Or Collector

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-biomass-tax-credit-program-producer-or-collector) |
| Metadata | [Link](https://data.oregon.gov/api/views/dk4h-78de) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dk4h-78de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dk4h-78de/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dk4h-78de |
| Name | 2016 ? Biomass Tax Credit Program - Producer Or Collector |
| Category | Revenue & Expense |
| Tags | 2016; tax credit; tax credit program; energy tax credit program; biomass; biomass producer; biomass collector; |
| Created | 2016-11-28T05:47:31Z |
| Publication Date | 2016-11-28T06:00:26Z |

## Description

Oregon Department of Energy - Biomass Tax Credit Program - Producer Or Collector. For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_ For questions regarding the Biomass Tax Credit Program, please contact: rachel.wray@state.or.us, Oregon Department of Energy.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| No       |                | fiscal_year                     | Fiscal Year                     | number        | number        |
| Yes      | series tag     | agency_issuing_tax_expenditure  | Agency Issuing Tax Expenditure  | text          | text          |
| No       |                | certification_year              | Certification Year              | number        | number        |
| Yes      | numeric metric | certification_month             | Certification Month             | number        | number        |
| Yes      | time           | date_of_certification           | Date of Certification           | calendar_date | calendar_date |
| Yes      | series tag     | applicant_name                  | Applicant Name                  | text          | text          |
| No       |                | business_address                | Business Address                | text          | text          |
| Yes      | series tag     | biomass_material_type           | Biomass Material Type           | text          | text          |
| Yes      | series tag     | units                           | Units                           | text          | text          |
| Yes      | numeric metric | certified_amount_of_material    | Certified Amount of Material    | number        | number        |
| Yes      | series tag     | certification_units             | Certification Units             | text          | text          |
| Yes      | series tag     | certification_decision          | Certification Decision          | text          | text          |
| Yes      | numeric metric | tax_credit_certification_amount | Tax Credit Certification Amount | money         | money         |
| Yes      | numeric metric | energy_value_in_million_btu     | Energy Value in Million Btu     | number        | number        |
| Yes      | numeric metric | tax_credit_rate                 | Tax Credit Rate                 | money         | money         |
| Yes      | series tag     | appl_no                         | Appl No.                        | text          | text          |
| Yes      | numeric metric | sufffix                         | Sufffix                         | number        | number        |
| Yes      | series tag     | application                     | Application #                   | text          | text          |
```

## Time Field

```ls
Value = date_of_certification
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = certification_year,business_address,fiscal_year
```

## Data Commands

```ls
series e:dk4h-78de d:2015-09-30T00:00:00.000Z t:certification_decision=Approved t:application=BI81-2 t:appl_no="BI 81" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:applicant_name="Farm Power Tillamook, LLC" t:units=Tons m:tax_credit_certification_amount=26 m:sufffix=2 m:tax_credit_rate=5 m:certification_month=9 m:certified_amount_of_material=5.3 m:energy_value_in_million_btu=3

series e:dk4h-78de d:2016-03-21T00:00:00.000Z t:certification_decision=Approved t:appl_no="BI 124" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type="Used Oil/Grease" t:certification_units=Gallons t:applicant_name="VeggieScout Oil LLC" t:units=Gallons m:tax_credit_certification_amount=2371 m:sufffix=1 m:tax_credit_rate=0.1 m:certification_month=3 m:certified_amount_of_material=23714 m:energy_value_in_million_btu=2988

series e:dk4h-78de d:2015-09-30T00:00:00.000Z t:certification_decision=Approved t:application=BI81-3 t:appl_no="BI 81" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:applicant_name="Farm Power Tillamook, LLC" t:units=Tons m:tax_credit_certification_amount=7928 m:sufffix=3 m:tax_credit_rate=5 m:certification_month=9 m:certified_amount_of_material=1585.58 m:energy_value_in_million_btu=786
```

## Meta Commands

```ls
metric m:certification_month p:integer l:"Certification Month" t:dataTypeName=number

metric m:certified_amount_of_material p:double l:"Certified Amount of Material" t:dataTypeName=number

metric m:tax_credit_certification_amount p:double l:"Tax Credit Certification Amount" t:dataTypeName=money

metric m:energy_value_in_million_btu p:integer l:"Energy Value in Million Btu" t:dataTypeName=number

metric m:tax_credit_rate p:double l:"Tax Credit Rate" t:dataTypeName=money

metric m:sufffix p:integer l:Sufffix t:dataTypeName=number

entity e:dk4h-78de l:"2016 ? Biomass Tax Credit Program - Producer Or Collector" t:url=https://data.oregon.gov/api/views/dk4h-78de

property e:dk4h-78de t:meta.view v:id=dk4h-78de v:category="Revenue & Expense" v:averageRating=0 v:name="2016 ? Biomass Tax Credit Program - Producer Or Collector"

property e:dk4h-78de t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:dk4h-78de t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure | certification_year | certification_month | date_of_certification | applicant_name               | business_address      | biomass_material_type | units   | certified_amount_of_material | certification_units | certification_decision | tax_credit_certification_amount | energy_value_in_million_btu | tax_credit_rate | appl_no | sufffix | application | 
| =========== | ============================== | ================== | =================== | ===================== | ============================ | ===================== | ===================== | ======= | ============================ | =================== | ====================== | =============================== | =========================== | =============== | ======= | ======= | =========== | 
| 2016        | Oregon Department of Energy    | 2015               | 9                   | 2015-09-30T00:00:00   | Farm Power Tillamook, LLC    | 1934 South Wall St    | Manure                | Tons    | 5.3                          | Tons                | Approved               | 26.00                           | 3                           | 5.00            | BI 81   | 2       | BI81-2      | 
| 2016        | Oregon Department of Energy    | 2016               | 3                   | 2016-03-21T00:00:00   | VeggieScout Oil LLC          | PO Box 452            | Used Oil/Grease       | Gallons | 23714                        | Gallons             | Approved               | 2371.00                         | 2988                        | 0.10            | BI 124  | 1       |             | 
| 2016        | Oregon Department of Energy    | 2015               | 9                   | 2015-09-30T00:00:00   | Farm Power Tillamook, LLC    | 1934 South Wall St    | Manure                | Tons    | 1585.58                      | Tons                | Approved               | 7928.00                         | 786                         | 5.00            | BI 81   | 3       | BI81-3      | 
| 2016        | Oregon Department of Energy    | 2015               | 12                  | 2015-12-10T00:00:00   | T2, Inc.                     | 44501 Wiley Creek Dr  | Woody Biomass         | Tons    | 39.409999999999997           | Bone Dry Tons       | Approved               | 394.00                          | 689                         | 10.00           | BI 89   | 4       | BI89-4      | 
| 2016        | Oregon Department of Energy    | 2016               | 4                   | 2016-04-01T00:00:00   | Victory Dairy                | 2805 Old Latimer Road | Manure                | Tons    | 8926.91                      | Tons                | Approved               | 44635.00                        | 4428                        | 5.00            | BI 112  | 1       |             | 
| 2016        | Oregon Department of Energy    | 2016               | 4                   | 2016-04-01T00:00:00   | Alpine Vue Dairy             | 3800 Darby Road       | Manure                | Tons    | 7241.51                      | Tons                | Approved               | 37108.00                        | 3592                        | 5.00            | BI 114  | 1       |             | 
| 2016        | Oregon Department of Energy    | 2015               | 9                   | 2015-09-30T00:00:00   | Farm Power Misty Meadow, LLC | 1934 South Wall St    | Manure                | Tons    | 19385.759999999998           | Tons                | Approved               | 96929.00                        | 9615                        | 5.00            | BI 80   | 3       | BI80-3      | 
| 2016        | Oregon Department of Energy    | 2016               | 5                   | 2016-05-05T00:00:00   | TMF Biofuels, LLC            | 75906 Threemile Road  | Manure                | Tons    | 126520                       | Tons                | Approved               | 632600.00                       | 62754                       | 5.00            | BI 133  | 1       |             | 
| 2016        | Oregon Department of Energy    | 2015               | 12                  | 2015-12-10T00:00:00   | Biomass One, LP              | 2350 Avenue G         | Woody Biomass         | Tons    | 4632.53                      | Bone Dry Tons       | Approved               | 46325.00                        | 80977                       | 10.00           | BI 87   | 1       | BI87-1      | 
| 2016        | Oregon Department of Energy    | 2016               | 3                   | 2016-03-11T00:00:00   | Rogue Biofuels               | PO Box 3422           | Used Oil/Grease       | Gallons | 338411                       | Gallons             | Approved               | 33841.00                        | 42640                       | 0.10            | BI 129  | 1       |             | 
```