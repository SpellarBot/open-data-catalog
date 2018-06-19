# IPERS Service Purchases by Membership Group and Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ipers-service-purchases-by-membership-group-and-location) |
| Metadata | [Link](https://data.iowa.gov/api/views/ia29-w2ai) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ia29-w2ai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ia29-w2ai/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ia29-w2ai |
| Name | IPERS Service Purchases by Membership Group and Location |
| Attribution | Iowa Public Employees' Retirement System |
| Category | Communities & People |
| Tags | ipers, service purchases |
| Created | 2016-12-30T23:19:35Z |
| Publication Date | 2017-03-14T21:38:18Z |

## Description

Dollar amounts paid by IPERS members to purchase IPERS service.

Membership groups
?	Regular: Most IPERS members are Regular members, or those who are not working in a sheriff/deputy or protection occupation job.
?	Special service: A small minority of IPERS members are Special service members, or those who work as sheriffs/deputies or in a protection occupation (jailers, police and firefighters, and others in public safety positions).

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                    | Data Type | Render Type |
| ======== | ============== | ================ | ======================= | ========= | =========== |
| Yes      | time           | fyear            | FISCAL YEAR             | number    | number      |
| Yes      | series tag     | state_fips_code  | State FIPS Code         | text      | number      |
| Yes      | series tag     | state_name       | State                   | text      | text        |
| Yes      | series tag     | fips_county_code | County FIPS Code        | text      | text        |
| Yes      | series tag     | county           | County                  | text      | text        |
| Yes      | series tag     | membership_group | Membership Group        | text      | text        |
| Yes      | numeric metric | service_purchase | Service Purchase Amount | money     | money       |
```

## Time Field

```ls
Value = fyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ia29-w2ai d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:state_fips_code=4 t:state_name=Arizona m:service_purchase=158306.54

series e:ia29-w2ai d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:state_fips_code=6 t:state_name=California m:service_purchase=318250.16

series e:ia29-w2ai d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:state_fips_code=8 t:state_name=Colorado m:service_purchase=24580.68
```

## Meta Commands

```ls
metric m:service_purchase p:double l:"Service Purchase Amount" t:dataTypeName=money

entity e:ia29-w2ai l:"IPERS Service Purchases by Membership Group and Location" t:attribution="Iowa Public Employees' Retirement System" t:url=https://data.iowa.gov/api/views/ia29-w2ai

property e:ia29-w2ai t:meta.view v:id=ia29-w2ai v:category="Communities & People" v:averageRating=0 v:name="IPERS Service Purchases by Membership Group and Location" v:attribution="Iowa Public Employees' Retirement System"

property e:ia29-w2ai t:meta.view.owner v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:displayName="Iowa Public Employees' Retirement System"

property e:ia29-w2ai t:meta.view.tableauthor v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:roleName=editor v:displayName="Iowa Public Employees' Retirement System"
```

## Top Records

```ls
| fyear | state_fips_code | state_name | fips_county_code | county  | membership_group | service_purchase | 
| ===== | =============== | ========== | ================ | ======= | ================ | ================ | 
| 2015  | 4               | Arizona    |                  |         | REGULAR          | 158306.54        | 
| 2015  | 6               | California |                  |         | REGULAR          | 318250.16        | 
| 2015  | 8               | Colorado   |                  |         | REGULAR          | 24580.68         | 
| 2015  | 12              | Florida    |                  |         | REGULAR          | 44135.00         | 
| 2015  | 19              | Iowa       | 19015            | BOONE   | REGULAR          | 226042.34        | 
| 2015  | 19              | Iowa       | 19179            | WAPELLO | REGULAR          | 187875.16        | 
| 2015  | 19              | Iowa       | 19025            | CALHOUN | REGULAR          | 8931.81          | 
| 2015  | 19              | Iowa       | 19071            | FREMONT | SPECIAL SERVICE  | 20471.70         | 
| 2015  | 19              | Iowa       | 19065            | FAYETTE | REGULAR          | 82926.20         | 
| 2015  | 19              | Iowa       | 19099            | JASPER  | SPECIAL SERVICE  | 5570.04          | 
```