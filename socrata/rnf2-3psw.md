# Biomass Tax Credit Program: Producer or Collector: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/biomass-tax-credit-program-producer-or-collector-fy-2014-44a4d) |
| Metadata | [Link](https://data.oregon.gov/api/views/rnf2-3psw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rnf2-3psw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rnf2-3psw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rnf2-3psw |
| Name | Biomass Tax Credit Program: Producer or Collector: FY 2014 |
| Category | Revenue & Expense |
| Tags | tax credit, tax credit program, energy tax credit program, biomass, biomass producer, biomass collector, 2014 |
| Created | 2014-12-31T04:01:53Z |
| Publication Date | 2015-12-27T22:41:16Z |

## Description

Summary:Certificates?Issued?from?July?1,?2013?through?June?30,?2014. For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
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
| Yes      | series tag     | application                     | Application #                   | text          | text          |
```

## Time Field

```ls
Value = date_of_certification
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = business_address,certification_year
```

## Data Commands

```ls
series e:rnf2-3psw d:2013-07-05T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2013 008-1" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type="Woody Biomass" t:certification_units="Bone Dry Tons" t:applicant_name="Biomass Harvesting, LLC" t:units=Tons m:tax_credit_certification_amount=56074.38 m:tax_credit_rate=10 m:certification_month=7 m:certified_amount_of_material=5607.44 m:energy_value_in_million_btu=99812

series e:rnf2-3psw d:2014-03-18T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2013 044-1" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type="Used Oil/Grease" t:certification_units=Gallons t:applicant_name="Baker Commoditites, Inc." t:units=Gallons m:tax_credit_certification_amount=87140.4 m:tax_credit_rate=0.1 m:certification_month=3 m:certified_amount_of_material=871404 m:energy_value_in_million_btu=102974

series e:rnf2-3psw d:2013-08-28T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2013 011-1" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type="Woody Biomass" t:certification_units="Bone Dry Tons" t:applicant_name="Lane Forest Products, Inc." t:units=Tons m:tax_credit_certification_amount=241.76 m:tax_credit_rate=10 m:certification_month=8 m:certified_amount_of_material=24.18 m:energy_value_in_million_btu=430
```

## Meta Commands

```ls
metric m:certification_month p:integer l:"Certification Month" t:dataTypeName=number

metric m:certified_amount_of_material p:float l:"Certified Amount of Material" t:dataTypeName=number

metric m:tax_credit_certification_amount p:double l:"Tax Credit Certification Amount" t:dataTypeName=money

metric m:energy_value_in_million_btu p:integer l:"Energy Value in Million Btu" t:dataTypeName=number

metric m:tax_credit_rate p:double l:"Tax Credit Rate" t:dataTypeName=money

entity e:rnf2-3psw l:"Biomass Tax Credit Program: Producer or Collector: FY 2014" t:url=https://data.oregon.gov/api/views/rnf2-3psw

property e:rnf2-3psw t:meta.view v:id=rnf2-3psw v:category="Revenue & Expense" v:averageRating=0 v:name="Biomass Tax Credit Program: Producer or Collector: FY 2014"

property e:rnf2-3psw t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rnf2-3psw t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | certification_year | certification_month | date_of_certification | applicant_name                         | business_address                      | biomass_material_type | units   | certified_amount_of_material | certification_units | certification_decision | tax_credit_certification_amount | energy_value_in_million_btu | tax_credit_rate | application    | 
| ============================== | ================== | =================== | ===================== | ====================================== | ===================================== | ===================== | ======= | ============================ | =================== | ====================== | =============================== | =========================== | =============== | ============== | 
| Oregon Department of Energy    | 2013               | 7                   | 2013-07-05T00:00:00   | Biomass Harvesting, LLC                | 13820 NW Main Street                  | Woody Biomass         | Tons    | 5607.44                      | Bone Dry Tons       | Approved               | 56074.38                        | 99812                       | 10.00           | BPC 2013 008-1 | 
| Oregon Department of Energy    | 2014               | 3                   | 2014-03-18T00:00:00   | Baker Commoditites, Inc.               | PO Box 58368                          | Used Oil/Grease       | Gallons | 871404.00                    | Gallons             | Approved               | 87140.40                        | 102974                      | 0.10            | BPC 2013 044-1 | 
| Oregon Department of Energy    | 2013               | 8                   | 2013-08-28T00:00:00   | Lane Forest Products, Inc.             | 2111 Prairie Road                     | Woody Biomass         | Tons    | 24.18                        | Bone Dry Tons       | Approved               | 241.76                          | 430                         | 10.00           | BPC 2013 011-1 | 
| Oregon Department of Energy    | 2014               | 2                   | 2014-02-04T00:00:00   | T2, Inc.                               | 44501 Wiley Creek Drive               | Woody Biomass         | Tons    | 1316.15                      | Bone Dry Tons       | Approved               | 13161.50                        | 23427                       | 10.00           | BPC 2013 039-1 | 
| Oregon Department of Energy    | 2014               | 5                   | 2014-05-27T00:00:00   | Forest Fuel Collection, LLC            | PO Box 715                            | Woody Biomass         | Tons    | 443.93                       | Bone Dry Tons       | Approved               | 4439.30                         | 7902                        | 10.00           | BPC 2013 083-1 | 
| Oregon Department of Energy    | 2013               | 9                   | 2013-09-16T00:00:00   | RES- AG FGO, LLC                       | 1615 New Hampshire Ave NW, Suite LL-C | Manure                | Tons    | 7243.00                      | Tons                | Approved               | 36215.00                        | 4346                        | 5.00            | BPC 2013 015-1 | 
| Oregon Department of Energy    | 2013               | 11                  | 2013-11-29T00:00:00   | Fairview Acres Dairy Farms, Inc.       | 7615 Trask River Rd                   | Manure                | Tons    | 2915.00                      | Tons                | Approved               | 14575.00                        | 1749                        | 5.00            | BPC 2013 029-1 | 
| Oregon Department of Energy    | 2013               | 11                  | 2013-11-29T00:00:00   | Custom Excavating by Dean Larson, Inc. | 2060 SE Airport Lane                  | Woody Biomass         | Tons    | 3010.26                      | Bone Dry Tons       | Approved               | 30102.64                        | 53583                       | 10.00           | BPC 2013 022-1 | 
| Oregon Department of Energy    | 2014               | 4                   | 2014-04-01T00:00:00   | Oldenkamp Farms, Inc. - Dairy Farm     | 1450 Schild Road                      | Manure                | Tons    | 1920.00                      | Tons                | Approved               | 9600.00                         | 1152                        | 5.00            | BPC 2013 076-1 | 
| Oregon Department of Energy    | 2014               | 3                   | 2014-03-26T00:00:00   | Stahlbush Island Farms, Inc.           | 3122 Stahlbush Island Road            | Vegetative Biomass    | Tons    | 5277.49                      | Bone Dry Tons       | Approved               | 52774.90                        | 85548                       | 10.00           | BPC 2013 056-1 | 
```