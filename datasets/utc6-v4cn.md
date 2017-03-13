# Schedule of Debt for Local Development Corporations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schedule-of-debt-for-local-development-corporations) |
| Metadata | [Link](https://data.ny.gov/api/views/utc6-v4cn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/utc6-v4cn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/utc6-v4cn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | utc6-v4cn |
| Name | Schedule of Debt for Local Development Corporations |
| Attribution | Individual Local Development Corporations submitted to the Authorities Budget Office |
| Category | Transparency |
| Tags | ldc |
| Created | 2015-02-23T19:35:45Z |
| Publication Date | 2016-11-04T14:31:39Z |
| Rows Updated | 2016-11-03T22:04:54Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include a schedule of the authorities? debt.  The dataset consists of schedule of debt data reported by Local Development Corporations beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | authority_name       | Authority Name       | text          | text          |
| Yes      | time           | fiscal_year_end_date | Fiscal Year End Date | calendar_date | calendar_date |
| Yes      | series tag     | has_outstanding_debt | Has Outstanding Debt | text          | text          |
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
series e:utc6-v4cn d:2011-12-31T00:00:00.000Z t:authority_name="ATC of Buffalo and Erie County, Inc." t:type_of_debt="Authority Debt - Other" t:debt_program="Other Non-State Funded" m:end_amount_total=0 m:begin_amount_total=4588557 m:new_debt_issuance=0 m:amount_retired=4588557

series e:utc6-v4cn d:2014-12-31T00:00:00.000Z t:authority_name="Albany County Capital Resource Corporation" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=87953506 m:begin_amount_total=0 m:new_debt_issuance=88000000 m:amount_retired=46494

series e:utc6-v4cn d:2015-12-31T00:00:00.000Z t:authority_name="Albany County Capital Resource Corporation" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=178592467 m:begin_amount_total=87953506 m:new_debt_issuance=90638961 m:amount_retired=0
```

## Meta Commands

```ls
metric m:begin_amount_total p:double l:"Begin Amount Total" d:"Amount of debt outstanding at the beginning of the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This is a pre-populated field and consists of the End Amount Total from the prior fiscal year. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:new_debt_issuance p:double l:"New Debt Issuance" d:"Amount of debt issued during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:amount_retired p:double l:"Amount Retired" d:"Amount of debt retired during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:end_amount_total p:double l:"End Amount Total" d:"Amount of debt outstanding at the end of the fiscal year. This is a calculated field and consists of the Begin Amount Total plus the New Debt Issuance, less the Amount Retired. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

entity e:utc6-v4cn l:"Schedule of Debt for Local Development Corporations" t:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/utc6-v4cn

property e:utc6-v4cn t:meta.view v:id=utc6-v4cn v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Schedule of Debt for Local Development Corporations" v:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office"

property e:utc6-v4cn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:utc6-v4cn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:utc6-v4cn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```