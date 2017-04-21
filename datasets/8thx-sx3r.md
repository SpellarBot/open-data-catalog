# Biomass Tax Credit Program: Producer or Collector: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/biomass-tax-credit-program-producer-or-collector-fy-2013-6d49b) |
| Metadata | [Link](https://data.oregon.gov/api/views/8thx-sx3r) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8thx-sx3r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8thx-sx3r/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8thx-sx3r |
| Name | Biomass Tax Credit Program: Producer or Collector: FY 2013 |
| Category | Revenue & Expense |
| Tags | tax credit, tax credit program, energy tax credit program, biomass, biomass producer, biomass collector |
| Created | 2013-11-07T16:36:52Z |
| Publication Date | 2013-11-07T23:06:54Z |

## Description

Summary of Certificates?Issued?from?July?1,?2012?through?June?30,?2013 (Fiscal?Year?2013)

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
series e:8thx-sx3r d:2013-02-22T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2012 048-2" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:applicant_name="Farm Power Tillamook, LLC." t:units=Tons m:tax_credit_certification_amount=11715 m:tax_credit_rate=5 m:certification_month=2 m:certified_amount_of_material=2343 m:energy_value_in_million_btu=1406

series e:8thx-sx3r d:2013-02-22T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2012 048-3" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:applicant_name="Farm Power Tillamook, LLC." t:units=Tons m:tax_credit_certification_amount=19065 m:tax_credit_rate=5 m:certification_month=2 m:certified_amount_of_material=3813 m:energy_value_in_million_btu=2288

series e:8thx-sx3r d:2013-02-22T00:00:00.000Z t:certification_decision=Approved t:application="BPC 2012 048-4" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:applicant_name="Farm Power Tillamook, LLC." t:units=Tons m:tax_credit_certification_amount=30460 m:tax_credit_rate=5 m:certification_month=2 m:certified_amount_of_material=6092 m:energy_value_in_million_btu=3655
```

## Meta Commands

```ls
metric m:certification_month p:integer l:"Certification Month" t:dataTypeName=number

metric m:certified_amount_of_material p:float l:"Certified Amount of Material" t:dataTypeName=number

metric m:tax_credit_certification_amount p:double l:"Tax Credit Certification Amount" t:dataTypeName=money

metric m:energy_value_in_million_btu p:integer l:"Energy Value in Million Btu" t:dataTypeName=number

metric m:tax_credit_rate p:double l:"Tax Credit Rate" t:dataTypeName=money

entity e:8thx-sx3r l:"Biomass Tax Credit Program: Producer or Collector: FY 2013" t:url=https://data.oregon.gov/api/views/8thx-sx3r

property e:8thx-sx3r t:meta.view v:id=8thx-sx3r v:category="Revenue & Expense" v:averageRating=0 v:name="Biomass Tax Credit Program: Producer or Collector: FY 2013"

property e:8thx-sx3r t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:8thx-sx3r t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | certification_year | certification_month | date_of_certification | applicant_name                   | business_address    | biomass_material_type | units   | certified_amount_of_material | certification_units | certification_decision | tax_credit_certification_amount | energy_value_in_million_btu | tax_credit_rate | application    | 
| ============================== | ================== | =================== | ===================== | ================================ | =================== | ===================== | ======= | ============================ | =================== | ====================== | =============================== | =========================== | =============== | ============== | 
| Oregon Department of Energy    | 2013               | 2                   | 2013-02-22T00:00:00   | Farm Power Tillamook, LLC.       | 1934 Southwall St   | Manure                | Tons    | 2343.00                      | Tons                | Approved               | 11715.00                        | 1406                        | 5.00            | BPC 2012 048-2 | 
| Oregon Department of Energy    | 2013               | 2                   | 2013-02-22T00:00:00   | Farm Power Tillamook, LLC.       | 1934 Southwall St   | Manure                | Tons    | 3813.00                      | Tons                | Approved               | 19065.00                        | 2288                        | 5.00            | BPC 2012 048-3 | 
| Oregon Department of Energy    | 2013               | 2                   | 2013-02-22T00:00:00   | Farm Power Tillamook, LLC.       | 1934 Southwall St   | Manure                | Tons    | 6092.00                      | Tons                | Approved               | 30460.00                        | 3655                        | 5.00            | BPC 2012 048-4 | 
| Oregon Department of Energy    | 2013               | 2                   | 2013-02-22T00:00:00   | Farm Power Tillamook, LLC.       | 1934 Southwall St   | Manure                | Tons    | 1041.00                      | Tons                | Approved               | 5205.00                         | 625                         | 5.00            | BPC 2012 048-5 | 
| Oregon Department of Energy    | 2013               | 2                   | 2013-02-14T00:00:00   | Bar Seven A Companies, Inc.      | PO Box 890          | Woody Biomass         | Tons    | 6037.17                      | Green Tons          | Approved               | 60371.65                        | 60179                       | 10.00           | BPC 2012 051-3 | 
| Oregon Department of Energy    | 2012               | 10                  | 2012-10-18T00:00:00   | Baker Commoditites, Inc.         | 5795 S. 130th Pl    | Used Oil/Grease       | Gallons | 380541.00                    | Gallons             | Approved               | 38054.10                        | 44969                       | 0.10            | BPC 2012 017-1 | 
| Oregon Department of Energy    | 2013               | 3                   | 2013-03-21T00:00:00   | Lane Forest Products, Inc.       | 2111 Prairie Road   | Woody Biomass         | Tons    | 11495.07                     | Green Tons          | Approved               | 114950.70                       | 114583                      | 10.00           | BPC 2012 028-7 | 
| Oregon Department of Energy    | 2013               | 4                   | 2013-04-08T00:00:00   | Fairview Acres Dairy Farms, Inc. | 7615 Trask River Rd | Manure                | Tons    | 7066.00                      | Tons                | Approved               | 35330.00                        | 4240                        | 5.00            | BPC 2012 077-1 | 
| Oregon Department of Energy    | 2013               | 4                   | 2013-04-12T00:00:00   | Evergreen West, Inc.             | PO Box 663          | Woody Biomass         | Tons    | 263.01                       | Green Tons          | Approved               | 2630.10                         | 2622                        | 10.00           | BPC 2012 049-2 | 
| Oregon Department of Energy    | 2013               | 3                   | 2013-03-21T00:00:00   | Lane Forest Products, Inc.       | 2111 Prairie Road   | Woody Biomass         | Tons    | 38.69                        | Green Tons          | Approved               | 386.90                          | 386                         | 10.00           | BPC 2012 028-3 | 
```