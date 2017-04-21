# 2016 ? Residential Energy Tax Credit Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-residential-energy-tax-credit-program) |
| Metadata | [Link](https://data.oregon.gov/api/views/t4ms-wngg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/t4ms-wngg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/t4ms-wngg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | t4ms-wngg |
| Name | 2016 ? Residential Energy Tax Credit Program |
| Category | Revenue & Expense |
| Tags | 2016; residential energy tax credit program; residential tax credit; energy credit program; energy program; |
| Created | 2016-11-28T05:03:26Z |
| Publication Date | 2016-11-28T05:19:27Z |

## Description

Oregon Department of Energy. For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_ For questions regarding the Residential Energy Tax Credit Program, please contact: rachel.wray@state.or.us, Oregon Department of Energy.

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
| Yes      | series tag     | site_zip                       | Site Zip                       | text          | text          |
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
series e:t4ms-wngg d:2016-02-29T00:00:00.000Z t:site_city="Oregon City" t:system=Photovoltaic t:application=851821 t:site_zip=97045 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source="ODOE Database" t:units_name=watts t:applicant_name="Ross Kendall" m:final_certified_project_cost=26775 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=19.07 m:units_capacity=9104 m:net_tax_credit=6000

series e:t4ms-wngg d:2015-07-07T00:00:00.000Z t:site_city=Tigard t:system=Photovoltaic t:application=ODOE-100075 t:site_zip=97224 t:site_county=Wash t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source=PowerClerk t:units_name=watts t:applicant_name="Robert Annenberg" m:final_certified_project_cost=32802 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=36.78 m:units_capacity=9880 m:net_tax_credit=6000

series e:t4ms-wngg d:2015-07-13T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=ODOE-010223 t:site_zip=97229 t:site_county=Clac t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:data_source=PowerClerk t:units_name=watts t:applicant_name="Andy Martwick" m:final_certified_project_cost=11310 m:percentage=100 m:tax_credit=4420 m:total_energy_million_btu=8.97 m:units_capacity=2600 m:net_tax_credit=4420
```

## Meta Commands

```ls
metric m:final_certified_project_cost p:double l:"Final Certified Project Cost" t:dataTypeName=money

metric m:tax_credit p:double l:"Tax Credit" t:dataTypeName=money

metric m:percentage p:integer l:Percentage t:dataTypeName=number

metric m:net_tax_credit p:double l:"Net Tax Credit" t:dataTypeName=money

metric m:total_energy_million_btu p:float l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:units_capacity p:integer l:"UNITS CAPACITY" t:dataTypeName=number

entity e:t4ms-wngg l:"2016 ? Residential Energy Tax Credit Program" t:url=https://data.oregon.gov/api/views/t4ms-wngg

property e:t4ms-wngg t:meta.view v:id=t4ms-wngg v:category="Revenue & Expense" v:averageRating=0 v:name="2016 ? Residential Energy Tax Credit Program"

property e:t4ms-wngg t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:t4ms-wngg t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency_issuing_tax_expenditure | final_year | final_date          | applicant_name       | site_city   | site_zip | site_county | system       | final_certified_project_cost | tax_credit | percentage | net_tax_credit | total_energy_million_btu | units_capacity     | units_name | application | data_source   | 
| =========== | ============================== | ========== | =================== | ==================== | =========== | ======== | =========== | ============ | ============================ | ========== | ========== | ============== | ======================== | ================== | ========== | =========== | ============= | 
| 2016        | Oregon Department of Energy    | 2016       | 2016-02-29T00:00:00 | Ross Kendall         | Oregon City | 97045    | Clac        | Photovoltaic | 26775.00                     | 6000.00    | 100        | 6000.00        | 19.07                    | 9104               | watts      | 851821      | ODOE Database | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-07-07T00:00:00 | Robert Annenberg     | Tigard      | 97224    | Wash        | Photovoltaic | 32802.00                     | 6000.00    | 100        | 6000.00        | 36.78                    | 9880               | watts      | ODOE-100075 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-07-13T00:00:00 | Andy Martwick        | Portland    | 97229    | Clac        | Photovoltaic | 11310.00                     | 4420.00    | 100        | 4420.00        | 8.9700000000000006       | 2600               | watts      | ODOE-010223 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-07-14T00:00:00 | George E Hall        | Mount Angel | 97362    | Mari        | Photovoltaic | 282750.00                    | 6000.00    | 100        | 6000.00        | 19.28                    | 6500               | watts      | ODOE-010331 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-07-17T00:00:00 | Suzette Hester       | Bonanza     | 97623    | Klam        | Photovoltaic | 34701.00                     | 6000.00    | 100        | 6000.00        | 35.99                    | 10260              | watts      | ODOE-010117 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-08-04T00:00:00 | Craig N Butler       | Portland    | 97229    | Clac        | Photovoltaic | 27144.00                     | 6000.00    | 100        | 6000.00        | 21.42                    | 6240               | watts      | ODOE-010441 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-08-06T00:00:00 | Tamsin Breck Lindsay | Beaverton   | 97006    | Wash        | Photovoltaic | 19227.00                     | 6000.00    | 100        | 6000.00        | 13.47                    | 4420               | watts      | ODOE-010444 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-08-07T00:00:00 | Marilyn Hill         | Albany      | 97321    | Linn        | Photovoltaic | 26850.00                     | 5700.00    | 100        | 5700.00        | 12.15                    | 3000               | watts      | ODOE-100102 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-08-24T00:00:00 | Todd Lauble          | Mt Hood     | 97041    | Hood        | Photovoltaic | 16060.00                     | 6000.00    | 100        | 6000.00        | 17.78                    | 4400               | watts      | ODOE-100112 | PowerClerk    | 
| 2016        | Oregon Department of Energy    | 2015       | 2015-09-28T00:00:00 | Kin Kwok             | Beaverton   | 97006    | Wash        | Photovoltaic | 35061.00                     | 6000.00    | 100        | 6000.00        | 25.58                    | 8060.0000000000009 | watts      | ODOE-010653 | PowerClerk    | 
```