# Open Budget Application: Capital Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-capital-budget-2fc25) |
| Metadata | [Link](https://data.seattle.gov/api/views/qi2h-j69m) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qi2h-j69m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qi2h-j69m/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qi2h-j69m |
| Name | Open Budget Application: Capital Budget |
| Category | Finance |
| Created | 2014-09-22T22:55:43Z |
| Publication Date | 2015-09-28T19:56:14Z |

## Description

data powering openbudget.seattle.gov

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | fiscal_year     | Fiscal_Year     | number    | number      |
| Yes      | series tag     | service         | Service         | text      | text        |
| Yes      | series tag     | department      | Department      | text      | text        |
| Yes      | series tag     | project         | Project         | text      | text        |
| Yes      | series tag     | project_id      | Project_id      | text      | text        |
| Yes      | series tag     | fund            | Fund            | text      | text        |
| Yes      | series tag     | fund_type       | Fund_Type       | text      | text        |
| Yes      | numeric metric | thru_fy_actuals | Thru_FY_Actuals | number    | number      |
| Yes      | numeric metric | fy_approved     | FY_Approved     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qi2h-j69m d:2016-01-01T00:00:00.000Z t:fund_type="Not Applicable" t:project="Data Analytics Platform - Seattle Police Department" t:department="Finance and Administration" t:project_id=D102TR005 t:service="Department of Information Technology" t:fund="General Subfund" m:thru_fy_actuals=0 m:fy_approved=0

series e:qi2h-j69m d:2016-01-01T00:00:00.000Z t:fund_type="Not Applicable" t:project="Next Generation Data Center" t:department="Finance and Administration" t:project_id=D102TC007 t:service="Department of Information Technology" t:fund="Information Technology Fund" m:thru_fy_actuals=0 m:fy_approved=0

series e:qi2h-j69m d:2016-01-01T00:00:00.000Z t:fund_type="Not Applicable" t:project="Space Planning" t:department="Finance and Administration" t:project_id=D102TC032 t:service="Department of Information Technology" t:fund="Information Technology Fund" m:thru_fy_actuals=0 m:fy_approved=500000
```

## Meta Commands

```ls
metric m:thru_fy_actuals p:integer l:Thru_FY_Actuals t:dataTypeName=number

metric m:fy_approved p:integer l:FY_Approved t:dataTypeName=number

entity e:qi2h-j69m l:"Open Budget Application: Capital Budget" t:url=https://data.seattle.gov/api/views/qi2h-j69m

property e:qi2h-j69m t:meta.view v:id=qi2h-j69m v:category=Finance v:averageRating=0 v:name="Open Budget Application: Capital Budget"

property e:qi2h-j69m t:meta.view.license v:name="Public Domain"

property e:qi2h-j69m t:meta.view.owner v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"

property e:qi2h-j69m t:meta.view.tableauthor v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"
```

## Top Records

```ls
| fiscal_year | service                              | department                          | project                                             | project_id | fund                        | fund_type      | thru_fy_actuals | fy_approved | 
| =========== | ==================================== | =================================== | =================================================== | ========== | =========================== | ============== | =============== | =========== | 
| 2016        | Department of Information Technology | Finance and Administration          | Data Analytics Platform - Seattle Police Department | D102TR005  | General Subfund             | Not Applicable | 0               | 0           | 
| 2016        | Department of Information Technology | Finance and Administration          | Next Generation Data Center                         | D102TC007  | Information Technology Fund | Not Applicable | 0               | 0           | 
| 2016        | Department of Information Technology | Finance and Administration          | Space Planning                                      | D102TC032  | Information Technology Fund | Not Applicable | 0               | 500000      | 
| 2016        | Department of Information Technology | Finance and Administration          | Technology Management Tools                         | D102TC015  | Information Technology Fund | Not Applicable | 0               | 408000      | 
| 2016        | Department of Information Technology | Office of Electronic Communications | Seattle Channel Maintenance and Upgrade             | D404EC001  | Information Technology Fund | Not Applicable | 0               | 466000      | 
| 2016        | Department of Information Technology | Technology Infrastructure           | 800 MHz Radio Network Program                       | D3RNRS     | Information Technology Fund | Not Applicable | 0               | 586000      | 
| 2016        | Department of Information Technology | Technology Infrastructure           | Alternate Data Center                               | D301AR001  | Information Technology Fund | Not Applicable | 0               | 65000       | 
| 2016        | Department of Information Technology | Technology Infrastructure           | Computing Services Architecture                     | D300CSARC  | Information Technology Fund | Not Applicable | 0               | 2549000     | 
| 2016        | Department of Information Technology | Technology Infrastructure           | Data and Telephone Infrastructure                   | COMMINFRA  | Information Technology Fund | Not Applicable | 0               | 2662000     | 
| 2016        | Department of Information Technology | Technology Infrastructure           | Enterprise Computing                                | D301CS001  | Information Technology Fund | Not Applicable | 0               | 526000      | 
```