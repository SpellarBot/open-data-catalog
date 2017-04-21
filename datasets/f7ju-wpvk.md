# Schedule of Debt for State Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schedule-of-debt-for-state-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/f7ju-wpvk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/f7ju-wpvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/f7ju-wpvk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | f7ju-wpvk |
| Name | Schedule of Debt for State Authorities |
| Attribution | Individual State Authorities submitted to the Authorities Budget Office |
| Category | Transparency |
| Tags | state authorties |
| Created | 2015-02-23T19:37:43Z |
| Publication Date | 2016-11-04T14:31:36Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include a schedule of the authorities? debt.  The dataset consists of schedule of debt data reported by State Authorities beginning with fiscal years ending in 2011.

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
series e:f7ju-wpvk d:2011-03-31T00:00:00.000Z t:authority_name="Dormitory Authority of the State of New York" t:type_of_debt="State Supported" t:debt_program="DASNY MENTAL HEALTH SERVICES" m:end_amount_total=3942415000 m:begin_amount_total=3881765000 m:new_debt_issuance=274085000 m:amount_retired=213435000

series e:f7ju-wpvk d:2011-03-31T00:00:00.000Z t:authority_name="Dormitory Authority of the State of New York" t:type_of_debt="State Supported" t:debt_program="DASNY CULTURAL EDUCATION STORAGE FACILITY" m:end_amount_total=9135000 m:begin_amount_total=9310000 m:new_debt_issuance=0 m:amount_retired=175000

series e:f7ju-wpvk d:2014-03-31T00:00:00.000Z t:authority_name="Dormitory Authority of the State of New York" t:type_of_debt="State Supported" t:debt_program="DASNY COURT HOUSE IMPROVEMENTS AND TRAINING FACILITIES (2007)" m:end_amount_total=13190000 m:begin_amount_total=14705000 m:new_debt_issuance=0 m:amount_retired=1515000
```

## Meta Commands

```ls
metric m:begin_amount_total p:double l:"Begin Amount Total" d:"Amount of debt outstanding at the beginning of the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This is a pre-populated field and consists of the End Amount Total from the prior fiscal year. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:new_debt_issuance p:double l:"New Debt Issuance" d:"Amount of debt issued during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:amount_retired p:double l:"Amount Retired" d:"Amount of debt retired during the fiscal year. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

metric m:end_amount_total p:double l:"End Amount Total" d:"Amount of debt outstanding at the end of the fiscal year. This is a calculated field and consists of the Begin Amount Total plus the New Debt Issuance, less the Amount Retired. This amount is specific to the type of debt indicated in the ""Type of Debt"" field. This field is blank when the authority reported having no outstanding debt." t:dataTypeName=money

entity e:f7ju-wpvk l:"Schedule of Debt for State Authorities" t:attribution="Individual State Authorities submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/f7ju-wpvk

property e:f7ju-wpvk t:meta.view v:id=f7ju-wpvk v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Schedule of Debt for State Authorities" v:attribution="Individual State Authorities submitted to the Authorities Budget Office"

property e:f7ju-wpvk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:f7ju-wpvk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:f7ju-wpvk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                               | fiscal_year_end_date | has_outstanding_debt | type_of_debt    | debt_program                                                  | begin_amount_total | new_debt_issuance | amount_retired | end_amount_total | 
| ============================================ | ==================== | ==================== | =============== | ============================================================= | ================== | ================= | ============== | ================ | 
| Dormitory Authority of the State of New York | 2011-03-31T00:00:00  |                      | State Supported | DASNY MENTAL HEALTH SERVICES                                  | 3881765000.00      | 274085000.00      | 213435000.00   | 3942415000.00    | 
| Dormitory Authority of the State of New York | 2011-03-31T00:00:00  |                      | State Supported | DASNY CULTURAL EDUCATION STORAGE FACILITY                     | 9310000.00         | 0.00              | 175000.00      | 9135000.00       | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | DASNY COURT HOUSE IMPROVEMENTS AND TRAINING FACILITIES (2007) | 14705000.00        | 0.00              | 1515000.00     | 13190000.00      | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | UDC SPORTS FACILITIES                                         | 4200000.00         | 0.00              | 0.00           | 4200000.00       | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | UDC STATE POLICE FACILITIES                                   | 220000.00          | 0.00              | 0.00           | 220000.00        | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | UDC ELK STREET PARKING GARAGE                                 | 10060000.00        | 0.00              | 0.00           | 10060000.00      | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | DASNY LIBRARY FACILITIES                                      | 63715000.00        | 12290000.00       | 5655000.00     | 70350000.00      | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | DASNY STATE UNIVERSITY ATHLETIC FACILITIES                    | 14675000.00        | 0.00              | 860000.00      | 13815000.00      | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | DASNY GEN EMPLOY. THROUGH NY SCIENCE - ECO DEV & HOUSING      | 59675000.00        | 0.00              | 21290000.00    | 38385000.00      | 
| Dormitory Authority of the State of New York | 2014-03-31T00:00:00  |                      | State Supported | DASNY OGS PARKING GARAGE                                      | 28050000.00        | 5265000.00        | 8540000.00     | 24775000.00      | 
```