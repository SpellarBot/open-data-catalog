# Schedule of Debt for Local Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schedule-of-debt-for-local-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/vfju-zm9q) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vfju-zm9q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vfju-zm9q/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vfju-zm9q |
| Name | Schedule of Debt for Local Authorities |
| Attribution | Individual Local Authorities submitted to the Authorities Budget Office |
| Category | Transparency |
| Tags | local authority |
| Created | 2015-02-23T19:34:47Z |
| Publication Date | 2016-11-04T14:31:33Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include a schedule of the authorities? debt.  The dataset consists of schedule of debt data reported by Local Authorities beginning with fiscal years ending in 2011.

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
series e:vfju-zm9q d:2014-06-30T00:00:00.000Z t:authority_name="Yonkers Community Development Agency" t:type_of_debt="Authority Debt - Other" t:debt_program="Other Non-State Funded" m:end_amount_total=341770 m:begin_amount_total=341770 m:new_debt_issuance=0 m:amount_retired=0

series e:vfju-zm9q d:2014-12-31T00:00:00.000Z t:authority_name="Albany Municipal Water Finance Authority" t:type_of_debt="Authority Debt - General Obligation" t:debt_program="General Obligation" m:end_amount_total=46970561 m:begin_amount_total=51454105 m:new_debt_issuance=0 m:amount_retired=4483544

series e:vfju-zm9q d:2015-05-31T00:00:00.000Z t:authority_name="Nyack Parking Authority" t:type_of_debt="Authority Debt - General Obligation" t:debt_program="General Obligation" m:end_amount_total=129893 m:begin_amount_total=174208 m:new_debt_issuance=0 m:amount_retired=44315
```

## Meta Commands

```ls
metric m:begin_amount_total p:double l:"Begin Amount Total" d:"Amount of debt outstanding at the beginning of the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This is a pre-populated field and consists of the End Amount Total from the prior fiscal year. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:new_debt_issuance p:double l:"New Debt Issuance" d:"Amount of debt issued during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:amount_retired p:double l:"Amount Retired" d:"Amount of debt retired during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:end_amount_total p:double l:"End Amount Total" d:"Amount of debt outstanding at the end of the fiscal year. This is a calculated field and consists of the Begin Amount Total plus the New Debt Issuance, less the Amount Retired. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

entity e:vfju-zm9q l:"Schedule of Debt for Local Authorities" t:attribution="Individual Local Authorities submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/vfju-zm9q

property e:vfju-zm9q t:meta.view v:id=vfju-zm9q v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Schedule of Debt for Local Authorities" v:attribution="Individual Local Authorities submitted to the Authorities Budget Office"

property e:vfju-zm9q t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vfju-zm9q t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vfju-zm9q t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                  | fiscal_year_end_date | has_outstanding_debt | type_of_debt                        | debt_program                          | begin_amount_total | new_debt_issuance | amount_retired | end_amount_total | 
| =============================================== | ==================== | ==================== | =================================== | ===================================== | ================== | ================= | ============== | ================ | 
| Yonkers Community Development Agency            | 2014-06-30T00:00:00  |                      | Authority Debt - Other              | Other Non-State Funded                | 341770.00          | 0.00              | 0.00           | 341770.00        | 
| Albany Water Board                              | 2013-12-31T00:00:00  | N                    |                                     |                                       |                    |                   |                |                  | 
| Albany Municipal Water Finance Authority        | 2014-12-31T00:00:00  |                      | Authority Debt - General Obligation | General Obligation                    | 51454105.00        | 0.00              | 4483544.00     | 46970561.00      | 
| Harrison Parking Authority                      | 2014-12-31T00:00:00  | N                    |                                     |                                       |                    |                   |                |                  | 
| Niagara Falls Urban Renewal Agency              | 2015-12-31T00:00:00  | N                    |                                     |                                       |                    |                   |                |                  | 
| Nyack Parking Authority                         | 2015-05-31T00:00:00  |                      | Authority Debt - General Obligation | General Obligation                    | 174208.00          | 0.00              | 44315.00       | 129893.00        | 
| Islip Resource Recovery Authority               | 2011-12-31T00:00:00  |                      | Authority Debt - General Obligation | General Obligation                    | 25925000.00        | 0.00              | 25925000.00    | 0.00             | 
| New York City Municipal Water Finance Authority | 2012-06-30T00:00:00  |                      | Authority Debt - Other              | Other Non-State Funded                | 452409769.66       | 0.00              | 0.00           | 452409769.66     | 
| New York City Transitional Finance Authority    | 2011-06-30T00:00:00  |                      | Authority Debt - Revenue            |                                       | 15872495000.00     | 4249425000.00     | 1031995000.00  | 19089925000.00   | 
| New York City Transitional Finance Authority    | 2012-06-30T00:00:00  |                      | Other State-Funded                  | MBBA SPECIAL PURPOSE SCHOOL AID BONDS | 4729850000.00      | 650000000.00      | 71190000.00    | 5308660000.00    | 
```