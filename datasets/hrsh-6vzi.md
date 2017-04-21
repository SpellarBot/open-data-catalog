# OASAS Medicaid Trend Detailed Recipient Summary Profile: Current 3 Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oasas-medicaid-trend-detailed-recipient-summary-profile-current-3-year-window) |
| Metadata | [Link](https://data.ny.gov/api/views/hrsh-6vzi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hrsh-6vzi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hrsh-6vzi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hrsh-6vzi |
| Name | OASAS Medicaid Trend Detailed Recipient Summary Profile: Current 3 Year Window |
| Attribution | New York State Office of Alcoholism and Substance Abuse Services (OASAS) |
| Category | Human Services |
| Tags | medicaid, chemical dependence, substance abuse, claims |
| Created | 2014-12-02T22:35:09Z |
| Publication Date | 2017-02-06T23:10:24Z |

## Description

This profile shows a detailed summary of recipients, units of service, paid claim dollars, dollars per individual and dollars per units of service for services reimbursed by the Medicaid Fee-for-Service billing system by type of chemical dependence and non-chemical dependence services received for the current consecutive 3 state fiscal year window for which data is available and analyzed.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                          | Data Type | Render Type |
| ======== | ============== | ===================== | ============================= | ========= | =========== |
| No       | time           | :updated_at           | updated_at                    | meta_data | meta_data   |
| Yes      | numeric metric | claims                | Claims                        | number    | number      |
| Yes      | series tag     | county                | County                        | text      | text        |
| Yes      | numeric metric | dollars               | Dollars                       | money     | money       |
| Yes      | numeric metric | dollars_per_claims    | Average Dollars per Claims    | money     | money       |
| Yes      | numeric metric | dollars_per_recipient | Average Dollars per Recipient | money     | money       |
| Yes      | numeric metric | recipients            | Recipients                    | number    | number      |
| Yes      | numeric metric | sfy                   | SFY                           | number    | number      |
| Yes      | series tag     | services              | Services                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hrsh-6vzi d:2017-02-06T23:10:11.000Z t:services="All Medicaid Services" t:county=Albany m:claims=254548 m:dollars_per_claims=128.23 m:recipients=2414 m:dollars=32640270.5 m:dollars_per_recipient=13521.24 m:sfy=2014

series e:hrsh-6vzi d:2017-02-06T23:10:11.000Z t:services="All Medicaid Services" t:county=Albany m:claims=288092 m:dollars_per_claims=130.37 m:recipients=2693 m:dollars=37559680.87 m:dollars_per_recipient=13947.15 m:sfy=2015

series e:hrsh-6vzi d:2017-02-06T23:10:11.000Z t:services="All Medicaid Services" t:county=Albany m:claims=324517 m:dollars_per_claims=123.13 m:recipients=2810 m:dollars=39957571.43 m:dollars_per_recipient=14219.78 m:sfy=2016
```

## Meta Commands

```ls
metric m:claims p:integer l:Claims d:"The number of service units (e.g. days, visits, weeks) for which Medicaid Fee-for-service (FFS) paid during the state fiscal year" t:dataTypeName=number

metric m:dollars p:double l:Dollars d:"The dollar amount paid by Medicaid FFS for services rendered during the state fiscal year based on date of service" t:dataTypeName=money

metric m:dollars_per_claims p:double l:"Average Dollars per Claims" d:"The dollar amount paid by Medicaid FFS for services rendered divided by the number of claims submitted during the state fiscal year." t:dataTypeName=money

metric m:dollars_per_recipient p:double l:"Average Dollars per Recipient" d:"The dollar amount paid by Medicaid FFS for services rendered divided by the number of recipients who received services during the state fiscal year" t:dataTypeName=money

metric m:recipients p:integer l:Recipients d:"Number of unique Medicaid enrollees for whom a claim was paid for a type of service received during the state fiscal year" t:dataTypeName=number

metric m:sfy p:integer l:SFY d:"4-digit State Fiscal Year, which runs from April 1st through March 31st. For example, the SFY for 2011 (11) is April 1, 2010 to March 31, 2011." t:dataTypeName=number

entity e:hrsh-6vzi l:"OASAS Medicaid Trend Detailed Recipient Summary Profile: Current 3 Year Window" t:attribution="New York State Office of Alcoholism and Substance Abuse Services (OASAS)" t:url=https://data.ny.gov/api/views/hrsh-6vzi

property e:hrsh-6vzi t:meta.view v:id=hrsh-6vzi v:category="Human Services" v:attributionLink=http://www.oasas.ny.gov/admin/hcf/index.cfm v:averageRating=0 v:name="OASAS Medicaid Trend Detailed Recipient Summary Profile: Current 3 Year Window" v:attribution="New York State Office of Alcoholism and Substance Abuse Services (OASAS)"

property e:hrsh-6vzi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hrsh-6vzi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:hrsh-6vzi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | claims | county | dollars     | dollars_per_claims | dollars_per_recipient | recipients | sfy  | services                                | 
| =========== | ====== | ====== | =========== | ================== | ===================== | ========== | ==== | ======================================= | 
| 1486422611  | 254548 | Albany | 32640270.50 | 128.23             | 13521.24              | 2414       | 2014 | All Medicaid Services                   | 
| 1486422611  | 288092 | Albany | 37559680.87 | 130.37             | 13947.15              | 2693       | 2015 | All Medicaid Services                   | 
| 1486422611  | 324517 | Albany | 39957571.43 | 123.13             | 14219.78              | 2810       | 2016 | All Medicaid Services                   | 
| 1486422611  | 78290  | Albany | 8643512.07  | 110.40             | 3580.58               | 2414       | 2014 |   All Chemical Dependence (CD) Services | 
| 1486422611  | 85857  | Albany | 9725462.32  | 113.28             | 3611.39               | 2693       | 2015 |   All Chemical Dependence (CD) Services | 
| 1486422611  | 101709 | Albany | 10534737.92 | 103.58             | 3749.02               | 2810       | 2016 |   All Chemical Dependence (CD) Services | 
| 1486422611  | 176258 | Albany | 23996758.43 | 136.15             | 9940.66               | 2414       | 2014 |   All Non CD Services                   | 
| 1486422611  | 202235 | Albany | 27834218.55 | 137.63             | 10335.77              | 2693       | 2015 |   All Non CD Services                   | 
| 1486422611  | 222808 | Albany | 29422833.51 | 132.05             | 10470.76              | 2810       | 2016 |   All Non CD Services                   | 
| 1486422611  | 840    | Albany | 483143.56   | 575.17             | 2156.89               | 224        | 2014 |     All Detoxification Services         | 
```