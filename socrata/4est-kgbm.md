# Local Government Infrastructure Financing FY 2011-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-government-infrastructure-financing-fy-2011-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/4est-kgbm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4est-kgbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4est-kgbm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4est-kgbm |
| Name | Local Government Infrastructure Financing FY 2011-2016 |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, lgif, department of housing & community development, local government infrastructure financing, local government, local govt, municipal government |
| Created | 2016-07-21T16:41:44Z |
| Publication Date | 2017-02-27T21:26:06Z |

## Description

Local Government Infrastructure Financing offers Maryland counties and municipalities a cost effective way to finance public purpose capital projects; enabling the delivery of essential services to support communities and the people they serve.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       |                | project_address           | Project Address           | text      | text        |
| Yes      | series tag     | project_city              | Project City              | text      | text        |
| Yes      | series tag     | project_zip_code          | Project Zip Code          | text      | text        |
| Yes      | series tag     | project_county            | Project County            | text      | text        |
| Yes      | series tag     | local_govt                | Local Govt                | text      | text        |
| Yes      | numeric metric | number_of_comm_served     | Number of Comm. Served    | number    | number      |
| Yes      | numeric metric | number_of_projects_funded | Number of Projects Funded | number    | number      |
| No       |                | fy                        | FY                        | number    | text        |
| Yes      | series tag     | projecttype               | ProjectType               | text      | text        |
| Yes      | numeric metric | total_loan_amount         | Total Loan Amount ($)     | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = project_address,fy
```

## Data Commands

```ls
series e:4est-kgbm d:2011-01-01T00:00:00.000Z t:project_zip_code=21001 t:project_county=Harford t:projecttype="Water capital purchase" t:project_city=Aberdeen t:local_govt="City of Aberdeen" m:total_loan_amount=5093428 m:number_of_comm_served=1 m:number_of_projects_funded=1

series e:4est-kgbm d:2011-01-01T00:00:00.000Z t:project_zip_code=20732 t:project_county=Calvert t:projecttype="Water storage tank and production" t:project_city="Chesapeake Beach" t:local_govt="Town of Chesapeake Beach" m:total_loan_amount=2164385 m:number_of_comm_served=1 m:number_of_projects_funded=1

series e:4est-kgbm d:2011-01-01T00:00:00.000Z t:project_zip_code=20781 t:project_county="Prince George's" t:projecttype="Street & sidewalk improvements, As built plans" t:project_city=Hyattsville t:local_govt="City of Hyattsville" m:total_loan_amount=4144062 m:number_of_comm_served=1 m:number_of_projects_funded=4
```

## Meta Commands

```ls
metric m:number_of_comm_served p:integer l:"Number of Comm. Served" t:dataTypeName=number

metric m:number_of_projects_funded p:integer l:"Number of Projects Funded" t:dataTypeName=number

metric m:total_loan_amount p:double l:"Total Loan Amount ($)" t:dataTypeName=money

entity e:4est-kgbm l:"Local Government Infrastructure Financing FY 2011-2016" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/4est-kgbm

property e:4est-kgbm t:meta.view v:id=4est-kgbm v:category=Housing v:attributionLink=http://dhcd.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Local Government Infrastructure Financing FY 2011-2016" v:attribution="Department of Housing and Community Development"

property e:4est-kgbm t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:4est-kgbm t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| project_address         | project_city     | project_zip_code | project_county  | local_govt                         | number_of_comm_served | number_of_projects_funded | fy   | projecttype                                                                        | total_loan_amount | 
| ======================= | ================ | ================ | =============== | ================================== | ===================== | ========================= | ==== | ================================================================================== | ================= | 
| 60 North Parke Street   | Aberdeen         | 21001            | Harford         | City of Aberdeen                   | 1                     | 1                         | 2011 | Water capital purchase                                                             | 5093428.00        | 
| 8200 Bayside Road       | Chesapeake Beach | 20732            | Calvert         | Town of Chesapeake Beach           | 1                     | 1                         | 2011 | Water storage tank and production                                                  | 2164385.00        | 
| 4310 Gallatin Street    | Hyattsville      | 20781            | Prince George's | City of Hyattsville                | 1                     | 4                         | 2011 | Street & sidewalk improvements, As built plans                                     | 4144062.00        | 
| 31 W. Main Street       | Middletown       | 21769            | Frederick       | Town of Middletown                 | 1                     | 1                         | 2011 | Refinance FHA Loan                                                                 | 347885.00         | 
| 15 S. Third Street      | Oakland          | 21550            | Garrett         | Town of Oakland                    | 1                     | 5                         | 2011 | Refinance debt, community center improvements, water system byproduct improvements | 2916278.00        | 
| 23121 Camden Way        | California       | 20619            | St. Mary's      | St. Mary's Metropolitan Commission | 3                     | 1                         | 2011 | Water and sewer system improvements                                                | 12613963.00       | 
| 57 North Liberty Street | Cumberland       | 21502            | Allegany        | City of Cumberland                 | 1                     | 1                         | 2012 | Refinance bank loans                                                               | 11415000.00       | 
| 10 William Street       | Berlin           | 21811            | Worcester       | Town of Berlin                     | 1                     | 4                         | 2012 | Refinance existing debt                                                            | 4776406.00        | 
| 101 Lawyer's Row        | Centreville      | 21617            | Queen Anne's    | Town of Centreville                | 1                     | 3                         | 2012 | Street improvements, water distribution system, refinance existing debt            | 2555540.00        | 
| 241 Market Street       | Charlestown      | 21914            | Cecil           | Town of Charlestown                | 1                     | 2                         | 2012 | Refinance existing debt, drainage and water basin installation                     | 798580.00         | 
```