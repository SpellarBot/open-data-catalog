# Schedule of Debt for Industrial Development Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schedule-of-debt-for-industrial-development-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/dtk8-znku) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dtk8-znku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dtk8-znku/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dtk8-znku |
| Name | Schedule of Debt for Industrial Development Agencies |
| Attribution | Individual Industrial Development Agencies submitted to the Authorities Budget Office |
| Category | Transparency |
| Tags | ida |
| Created | 2015-02-23T19:32:42Z |
| Publication Date | 2016-11-04T14:31:35Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include a schedule of the authorities? debt.  The dataset consists of schedule of debt data reported by Industrial Development Agencies beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | authority_name       | Authority Name       | text          | text          |
| Yes      | time           | fiscal_year_end_date | Fiscal Year End Date | calendar_date | calendar_date |
| Yes      | series tag     | outstanding_debt     | Has Outstanding Debt | text          | text          |
| Yes      | series tag     | type_of_debt         | Type Of Debt         | text          | text          |
| Yes      | series tag     | debt_program         | Debt Program         | text          | text          |
| Yes      | numeric metric | begin_amount_total   | Begin Amount Total   | money         | money         |
| Yes      | numeric metric | new_debt_issuance    | New Debt Issuance    | money         | money         |
| Yes      | numeric metric | amount_retired       | Amount Retired       | money         | money         |
| Yes      | numeric metric | end_amount_total     | End Amount Total     | money         | money         |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dtk8-znku d:2013-12-31T00:00:00.000Z t:authority_name="Essex County Industrial Development Agency" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=9494273.56 m:begin_amount_total=21374580.16 m:new_debt_issuance=0 m:amount_retired=11880306.6

series e:dtk8-znku d:2013-12-31T00:00:00.000Z t:authority_name="Franklin County Industrial Development Agency" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=15253252.18 m:begin_amount_total=19348997.07 m:new_debt_issuance=0 m:amount_retired=4095744.89

series e:dtk8-znku d:2013-12-31T00:00:00.000Z t:authority_name="Genesee County Industrial Development Agency" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=15409601.6 m:begin_amount_total=18481597.6 m:new_debt_issuance=0 m:amount_retired=3071996
```

## Meta Commands

```ls
metric m:begin_amount_total p:double l:"Begin Amount Total" d:"Amount of debt outstanding at the beginning of the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This is a pre-populated field and consists of the End Amount Total from the prior fiscal year. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:new_debt_issuance p:double l:"New Debt Issuance" d:"Amount of debt issued during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:amount_retired p:double l:"Amount Retired" d:"Amount of debt retired during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:end_amount_total p:double l:"End Amount Total" d:"Amount of debt outstanding at the end of the fiscal year. This is a calculated field and consists of the Begin Amount Total plus the New Debt Issuance, less the Amount Retired. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

entity e:dtk8-znku l:"Schedule of Debt for Industrial Development Agencies" t:attribution="Individual Industrial Development Agencies submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/dtk8-znku

property e:dtk8-znku t:meta.view v:id=dtk8-znku v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Schedule of Debt for Industrial Development Agencies" v:attribution="Individual Industrial Development Agencies submitted to the Authorities Budget Office"

property e:dtk8-znku t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dtk8-znku t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dtk8-znku t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                  | fiscal_year_end_date | outstanding_debt | type_of_debt           | debt_program           | begin_amount_total | new_debt_issuance | amount_retired | end_amount_total | 
| =============================================== | ==================== | ================ | ====================== | ====================== | ================== | ================= | ============== | ================ | 
| Essex County Industrial Development Agency      | 2013-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 21374580.16        | 0.00              | 11880306.60    | 9494273.56       | 
| Franklin County Industrial Development Agency   | 2013-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 19348997.07        | 0.00              | 4095744.89     | 15253252.18      | 
| Village of Groton Industrial Development Agency | 2013-05-31T00:00:00  | N                |                        |                        |                    |                   |                |                  | 
| Genesee County Industrial Development Agency    | 2013-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 18481597.60        | 0.00              | 3071996.00     | 15409601.60      | 
| Allegany Industrial Development Agency          | 2012-12-31T00:00:00  |                  | Authority Debt - Other | Other Non-State Funded | 508524.00          | 0.00              | 508524.00      | 0.00             | 
| Greene County Industrial Development Agency     | 2012-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 500000.00          | 0.00              | 216200.00      | 283800.00        | 
| Yonkers Industrial Development Agency           | 2012-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 247255155.00       | 0.00              | 6467953.00     | 240787202.00     | 
| Genesee County Industrial Development Agency    | 2012-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 20920177.60        | 0.00              | 2438580.00     | 18481597.60      | 
| Islip Industrial Development Agency             | 2012-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 54783722.83        | 38310000.00       | 2923941.92     | 90169780.91      | 
| Montgomery County Industrial Development Agency | 2012-12-31T00:00:00  |                  | Conduit Debt           | Conduit Debt           | 36589727.67        | 0.00              | 5257566.00     | 31332161.67      | 
```