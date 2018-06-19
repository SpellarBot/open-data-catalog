# Empire Zones Business Annual Reports: Beginning 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/empire-zones-business-annual-reports-beginning-2001) |
| Metadata | [Link](https://data.ny.gov/api/views/edtu-bdbi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/edtu-bdbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/edtu-bdbi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | edtu-bdbi |
| Name | Empire Zones Business Annual Reports: Beginning 2001 |
| Attribution | Empire State Development |
| Category | Economic Development |
| Tags | empire zones, bars, tax credits |
| Created | 2014-01-14T15:26:31Z |
| Publication Date | 2016-02-16T14:50:08Z |

## Description

Employment, investment and tax credit information reported by businesses certified in the Empire Zones Program.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | name_of_company                         | Name of Company                         | text      | text        |
| Yes      | series tag     | zone_name                               | Zone Name                               | text      | text        |
| Yes      | time           | report_year                             | Report Year                             | number    | number      |
| Yes      | numeric metric | total_jobs                              | Total Jobs                              | number    | number      |
| Yes      | numeric metric | full_time_jobs                          | Full-Time Jobs                          | number    | number      |
| Yes      | numeric metric | part_time_jobs                          | Part-Time Jobs                          | number    | number      |
| Yes      | numeric metric | full_time_equivalents                   | Full-Time Equivalents                   | number    | number      |
| Yes      | numeric metric | gross_wages                             | Gross Wages                             | money     | money       |
| Yes      | numeric metric | total_capital_investment                | Total Capital Investment                | money     | money       |
| Yes      | numeric metric | wage_tax_credit_claimed                 | Wage Tax Credit Claimed                 | money     | money       |
| Yes      | numeric metric | wage_tax_credit_refunded                | Wage Tax Credit Refunded                | money     | money       |
| Yes      | numeric metric | investment_tax_credit_claimed           | Investment Tax Credit Claimed           | money     | money       |
| Yes      | numeric metric | investment_tax_credit_refunded          | Investment Tax Credit Refunded          | money     | money       |
| Yes      | numeric metric | employment_incentive_tax_credit_claimed | Employment Incentive Tax Credit Claimed | money     | money       |
| Yes      | numeric metric | tax_reduction_credit                    | Tax Reduction Credit                    | money     | money       |
| Yes      | numeric metric | sales_tax_credit                        | Sales Tax Credit                        | money     | money       |
| Yes      | numeric metric | real_property_tax_credit                | Real Property Tax Credit                | money     | money       |
| Yes      | numeric metric | real_property_tax_485_e_exemption       | Real Property Tax 485-e Exemption       | money     | money       |
```

## Time Field

```ls
Value = report_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:edtu-bdbi d:2007-01-01T00:00:00.000Z t:zone_name="SUNSET PARK/RED HOOK, SW BROOKLYN" t:name_of_company="01, Inc." m:total_jobs=1.5 m:full_time_equivalents=0 m:tax_reduction_credit=0 m:full_time_jobs=1.5 m:gross_wages=105519.89 m:wage_tax_credit_refunded=0 m:investment_tax_credit_claimed=570 m:part_time_jobs=0.5 m:investment_tax_credit_refunded=0 m:real_property_tax_credit=0 m:total_capital_investment=16775 m:sales_tax_credit=0 m:real_property_tax_485_e_exemption=0 m:employment_incentive_tax_credit_claimed=0 m:wage_tax_credit_claimed=5000

series e:edtu-bdbi d:2008-01-01T00:00:00.000Z t:zone_name="SUNSET PARK/RED HOOK, SW BROOKLYN" t:name_of_company="01, Inc." m:total_jobs=4 m:full_time_equivalents=1 m:tax_reduction_credit=0 m:full_time_jobs=3 m:gross_wages=120244.14 m:wage_tax_credit_refunded=0 m:investment_tax_credit_claimed=90 m:part_time_jobs=2 m:investment_tax_credit_refunded=0 m:real_property_tax_credit=0 m:total_capital_investment=2200 m:sales_tax_credit=400 m:real_property_tax_485_e_exemption=0 m:employment_incentive_tax_credit_claimed=0 m:wage_tax_credit_claimed=6000

series e:edtu-bdbi d:2009-01-01T00:00:00.000Z t:zone_name="SUNSET PARK/RED HOOK, SW BROOKLYN" t:name_of_company="01, Inc." m:total_jobs=4 m:full_time_equivalents=1 m:tax_reduction_credit=0 m:full_time_jobs=3 m:gross_wages=120244.14 m:wage_tax_credit_refunded=0 m:investment_tax_credit_claimed=0 m:part_time_jobs=2 m:investment_tax_credit_refunded=0 m:real_property_tax_credit=0 m:total_capital_investment=2200 m:sales_tax_credit=400 m:real_property_tax_485_e_exemption=0 m:employment_incentive_tax_credit_claimed=0 m:wage_tax_credit_claimed=3698
```

## Meta Commands

```ls
metric m:total_jobs p:double l:"Total Jobs" d:"Total full time jobs as of December 31st of the report year which equals the sum of full-time jobs and full-time equivalent jobs. Note: FTE data was not requested prior to 2004 Business Annual Report." t:dataTypeName=number

metric m:full_time_jobs p:double l:"Full-Time Jobs" d:"Full time jobs as of December 31st of the report year. All employment numbers are calculated by taking an average of the employment for each of the four quarters ending on March 31st, June 30th, September 30th, and December 31st, sometimes resulting in a fraction." t:dataTypeName=number

metric m:part_time_jobs p:double l:"Part-Time Jobs" d:"Part time jobs as of December 31st of the report year." t:dataTypeName=number

metric m:full_time_equivalents p:double l:"Full-Time Equivalents" d:"Full-time equivalent jobs as of December 31st of the report year. FTEs are part-time jobs converted to full-time equivalents. This data was not requested prior to the 2004 Business Annual Report, resulting in blank cells." t:dataTypeName=number

metric m:gross_wages p:double l:"Gross Wages" d:"Wages and benefits paid to employees at zone location during the report year." t:dataTypeName=money

metric m:total_capital_investment p:double l:"Total Capital Investment" d:"Capital Investment made at zone location during the report year" t:dataTypeName=money

metric m:wage_tax_credit_claimed p:double l:"Wage Tax Credit Claimed" d:"Amount of wage tax credit used for report year" t:dataTypeName=money

metric m:wage_tax_credit_refunded p:double l:"Wage Tax Credit Refunded" d:"Amount of wage tax credit refunded for report year" t:dataTypeName=money

metric m:investment_tax_credit_claimed p:double l:"Investment Tax Credit Claimed" d:"Amount of investment tax credit used for report year" t:dataTypeName=money

metric m:investment_tax_credit_refunded p:double l:"Investment Tax Credit Refunded" d:"Amount of investment tax credit refunded for tax year" t:dataTypeName=money

metric m:employment_incentive_tax_credit_claimed p:double l:"Employment Incentive Tax Credit Claimed" d:"Amount of employment incentive tax credit used for report year" t:dataTypeName=money

metric m:tax_reduction_credit p:double l:"Tax Reduction Credit" d:"Amount of tax reduction credit used for report year" t:dataTypeName=money

metric m:sales_tax_credit p:double l:"Sales Tax Credit" d:"Amount of sales tax credit or refund used for report year" t:dataTypeName=money

metric m:real_property_tax_credit p:double l:"Real Property Tax Credit" d:"Amount of real property credit used for report year" t:dataTypeName=money

metric m:real_property_tax_485_e_exemption p:double l:"Real Property Tax 485-e Exemption" d:"Amount of 485-e exemption used for report year" t:dataTypeName=money

entity e:edtu-bdbi l:"Empire Zones Business Annual Reports: Beginning 2001" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/edtu-bdbi

property e:edtu-bdbi t:meta.view v:id=edtu-bdbi v:category="Economic Development" v:attributionLink=http://esd.ny.gov/businessprograms/empirezones.html v:averageRating=0 v:name="Empire Zones Business Annual Reports: Beginning 2001" v:attribution="Empire State Development"

property e:edtu-bdbi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:edtu-bdbi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:edtu-bdbi t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| name_of_company                      | zone_name                                        | report_year | total_jobs | full_time_jobs | part_time_jobs | full_time_equivalents | gross_wages | total_capital_investment | wage_tax_credit_claimed | wage_tax_credit_refunded | investment_tax_credit_claimed | investment_tax_credit_refunded | employment_incentive_tax_credit_claimed | tax_reduction_credit | sales_tax_credit | real_property_tax_credit | real_property_tax_485_e_exemption | 
| ==================================== | ================================================ | =========== | ========== | ============== | ============== | ===================== | =========== | ======================== | ======================= | ======================== | ============================= | ============================== | ======================================= | ==================== | ================ | ======================== | ================================= | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2007        | 1.5        | 1.5            | 0.5            | 0                     | 105519.89   | 16775.00                 | 5000.00                 | 0.00                     | 570.00                        | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2008        | 4          | 3              | 2              | 1                     | 120244.14   | 2200.00                  | 6000.00                 | 0.00                     | 90.00                         | 0.00                           | 0.00                                    | 0.00                 | 400.00           | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2009        | 4          | 3              | 2              | 1                     | 120244.14   | 2200.00                  | 3698.00                 | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 400.00           | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2010        | 6          | 5              | 2              | 1                     | 171626.00   | 2000.00                  | 2748.00                 | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2011        | 7          | 7              | 0              | 0                     | 206494.00   | 7802.00                  | 4209.00                 | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2013        | 7          | 5              | 5              | 2                     | 275548.00   | 8841.00                  | 0.00                    | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 01, Inc.                             | SUNSET PARK/RED HOOK, SW BROOKLYN                | 2012        | 9          | 9              | 0              | 0                     | 298009.00   | 0.00                     | 3625.00                 | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 1 Rewe Street, LLC                   | N. BROOKLYN/BROOKLYN NAVY YARD/EAST WILLIAMSBURG | 2002        | 0          | 0              | 0              |                       | 0.00        | 1267352.00               | 0.00                    | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 1 Rewe Street, LLC                   | N. BROOKLYN/BROOKLYN NAVY YARD/EAST WILLIAMSBURG | 2003        | 0          | 0              | 0              |                       | 0.00        | 0.00                     | 0.00                    | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
| 10 Ellicott Square Court Corporation | BUFFALO                                          | 2001        | 38         | 38             | 1              |                       | 1517870.00  | 17627.00                 | 0.00                    | 0.00                     | 0.00                          | 0.00                           | 0.00                                    | 0.00                 | 0.00             | 0.00                     | 0.00                              | 
```