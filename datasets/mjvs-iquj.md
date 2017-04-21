# 2015 - Biomass Tax Credit Program: Producer or Collector: FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-biomass-tax-credit-program-producer-or-collector-fy-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/mjvs-iquj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mjvs-iquj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mjvs-iquj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mjvs-iquj |
| Name | 2015 - Biomass Tax Credit Program: Producer or Collector: FY 2015 |
| Category | Revenue & Expense |
| Tags | 2015; tax credit; tax credit program; energy tax credit program; biomass; biomass producer; biomass collector; 2015 |
| Created | 2015-12-27T06:18:10Z |
| Publication Date | 2015-12-27T22:14:20Z |

## Description

Summary of Certificates?Issued?from?July?1,?2014?through?June?30,?2015 (Fiscal?Year?2015) For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

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
| Yes      | series tag     | energy_value_in_million_btu     | Energy Value in Million Btu     | text          | text          |
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
Excluded Fields = certification_year,business_address,fiscal_year
```

## Data Commands

```ls
series e:mjvs-iquj d:2014-09-08T00:00:00.000Z t:certification_decision=Approved t:application="BI 13-5" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:energy_value_in_million_btu="* 1,542" t:applicant_name="Farm Power Tillamook, LLC" t:units=Tons m:tax_credit_certification_amount=15545.05 m:tax_credit_rate=5 m:certification_month=9 m:certified_amount_of_material=3109.01

series e:mjvs-iquj d:2014-08-01T00:00:00.000Z t:certification_decision=Approved t:application="BI 9-1" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type=Manure t:certification_units=Tons t:energy_value_in_million_btu="* 64,265" t:applicant_name="TMF Biofuels, LLC" t:units=Tons m:tax_credit_certification_amount=647828 m:tax_credit_rate=5 m:certification_month=8 m:certified_amount_of_material=129565.6

series e:mjvs-iquj d:2015-04-02T00:00:00.000Z t:certification_decision=Approved t:application=BI62-1 t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:biomass_material_type="Used Oil/Grease" t:certification_units=Gallons t:energy_value_in_million_btu="* 44,966" t:applicant_name="Farm Power Tillamook, LLC" t:units=Gallons m:tax_credit_certification_amount=35687.3 m:tax_credit_rate=0.1 m:certification_month=4 m:certified_amount_of_material=356873
```

## Meta Commands

```ls
metric m:certification_month p:integer l:"Certification Month" t:dataTypeName=number

metric m:certified_amount_of_material p:double l:"Certified Amount of Material" t:dataTypeName=number

metric m:tax_credit_certification_amount p:double l:"Tax Credit Certification Amount" t:dataTypeName=money

metric m:tax_credit_rate p:double l:"Tax Credit Rate" t:dataTypeName=money

entity e:mjvs-iquj l:"2015 - Biomass Tax Credit Program: Producer or Collector: FY 2015" t:url=https://data.oregon.gov/api/views/mjvs-iquj

property e:mjvs-iquj t:meta.view v:id=mjvs-iquj v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - Biomass Tax Credit Program: Producer or Collector: FY 2015"

property e:mjvs-iquj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:mjvs-iquj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure | certification_year | certification_month | date_of_certification | applicant_name                       | business_address             | biomass_material_type | units   | certified_amount_of_material | certification_units | certification_decision | tax_credit_certification_amount | energy_value_in_million_btu | tax_credit_rate | application | 
| =========== | ============================== | ================== | =================== | ===================== | ==================================== | ============================ | ===================== | ======= | ============================ | =================== | ====================== | =============================== | =========================== | =============== | =========== | 
| 2015        | Oregon Department of Energy    | 2014               | 9                   | 2014-09-08T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall Street       | Manure                | Tons    | 3109.01                      | Tons                | Approved               | 15545.05                        | * 1,542                     | 5.00            | BI 13-5     | 
| 2015        | Oregon Department of Energy    | 2014               | 8                   | 2014-08-01T00:00:00   | TMF Biofuels, LLC                    | 75906 Threemile Road         | Manure                | Tons    | 129565.6                     | Tons                | Approved               | 647828.00                       | * 64,265                    | 5.00            | BI 9-1      | 
| 2015        | Oregon Department of Energy    | 2015               | 4                   | 2015-04-02T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall St           | Used Oil/Grease       | Gallons | 356873                       | Gallons             | Approved               | 35687.30                        | * 44,966                    | 0.10            | BI62-1      | 
| 2015        | Oregon Department of Energy    | 2014               | 9                   | 2014-09-08T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall Street       | Manure                | Tons    | 5113.0600000000004           | Tons                | Approved               | 25565.30                        | * 2,536                     | 5.00            | BI 12-4     | 
| 2015        | Oregon Department of Energy    | 2015               | 2                   | 2015-02-25T00:00:00   | TMF Biofuels LLC                     | 75906 Threemile Road         | Manure                | Tons    | 140018.20000000001           | Tons                | Approved               | 700091.00                       | * 69,449                    | 5.00            | BI29-1      | 
| 2015        | Oregon Department of Energy    | 2014               | 10                  | 2014-10-31T00:00:00   | Encore Oils, LLC.                    | 3333 NW 35th Ave, Building C | Used Oil/Grease       | Gallons | 24647                        | Gallons             | Approved               | 2464.70                         | * 3,106                     | 0.10            | BI 15-2     | 
| 2015        | Oregon Department of Energy    | 2015               | 4                   | 2015-04-02T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall St           | Manure                | Tons    | 3427.1                       | Tons                | Approved               | 17135.50                        | * 1,700                     | 5.00            | BI52-3      | 
| 2015        | Oregon Department of Energy    | 2015               | 4                   | 2015-04-06T00:00:00   | Custom Excavating by Dean Larson Inc | 2060 SE Airport Lane         | Woody Biomass         | Tons    | 1480                         | Bone Dry Tons       | Approved               | 14800.00                        | * 25,870                    | 10.00           | BI57- 1     | 
| 2015        | Oregon Department of Energy    | 2014               | 9                   | 2014-09-08T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall Street       | Manure                | Tons    | 2793.02                      | Tons                | Approved               | 13965.10                        | * 1,385                     | 5.00            | BI 13-1     | 
| 2015        | Oregon Department of Energy    | 2015               | 4                   | 2015-04-02T00:00:00   | Farm Power Tillamook, LLC            | 1934 South Wall St           | Used Oil/Grease       | Gallons | 298300                       | Gallons             | Approved               | 29830.00                        | * 37,586                    | 0.10            | BI56-1      | 
```