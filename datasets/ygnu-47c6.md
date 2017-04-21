# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Trust Fund

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-trust-fund-93cd8) |
| Metadata | [Link](https://data.illinois.gov/api/views/ygnu-47c6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ygnu-47c6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ygnu-47c6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ygnu-47c6 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Trust Fund |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T16:49:53Z |
| Publication Date | 2012-01-25T22:00:29Z |

## Description

FY2010 Governor's Report - Closings.Trust Fund

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| No       |                | fiscal_year     | FISCAL YEAR     | number        | text          |
| Yes      | series tag     | project_name    | PROJECT NAME    | text          | text          |
| No       |                | project_address | PROJECT ADDRESS | text          | text          |
| Yes      | series tag     | project_city    | PROJECT CITY    | text          | text          |
| Yes      | series tag     | owner           | OWNER           | text          | text          |
| Yes      | series tag     | loan_grant      | LOAN/GRANT      | text          | text          |
| Yes      | time           | closing_date    | CLOSING DATE    | calendar_date | calendar_date |
| Yes      | numeric metric | amount          | AMOUNT          | money         | money         |
| Yes      | numeric metric | units           | UNITS           | number        | number        |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:ygnu-47c6 d:2009-12-31T00:00:00.000Z t:loan_grant=Loan t:project_name="Parkside Nine, Phase I" t:owner="Parkside Nine Phase I, LP" t:project_city=Chicago m:amount=750000 m:units=111

series e:ygnu-47c6 d:2010-03-31T00:00:00.000Z t:loan_grant=Loan t:project_name="Shorewood Horizon Senior Living Community" t:owner="Shorewood Horizon Limited Partnership" t:project_city=Shorewood m:amount=1250000 m:units=51

series e:ygnu-47c6 d:2010-02-08T00:00:00.000Z t:loan_grant=Loan t:project_name="The Suites of Autumn Green at Wright Campus" t:owner="Senior Suites Chicago Wright Campus, LLC" t:project_city=Chicago m:amount=1250000 m:units=36
```

## Meta Commands

```ls
metric m:amount p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:ygnu-47c6 l:"IHDA - Illinois Housing Dev Auth  - FY2010 Governor's Report - Closings.Trust Fund" t:url=https://data.illinois.gov/api/views/ygnu-47c6

property e:ygnu-47c6 t:meta.view v:id=ygnu-47c6 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth  - FY2010 Governor's Report - Closings.Trust Fund"

property e:ygnu-47c6 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:ygnu-47c6 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                                | project_address                                  | project_city             | owner                                                   | loan_grant | closing_date        | amount  | units | 
| =========== | =========================================== | ================================================ | ======================== | ======================================================= | ========== | =================== | ======= | ===== | 
| 2010        | Parkside Nine, Phase I                      | 545 West Division                                | Chicago                  | Parkside Nine Phase I, LP                               | Loan       | 2009-12-31T00:00:00 | 750000  | 111   | 
| 2010        | Shorewood Horizon Senior Living Community   | Northeast Corner of Black Road & Shorewood Drive | Shorewood                | Shorewood Horizon Limited Partnership                   | Loan       | 2010-03-31T00:00:00 | 1250000 | 51    | 
| 2010        | The Suites of Autumn Green at Wright Campus | 4255 North Oak Park Avenue                       | Chicago                  | Senior Suites Chicago Wright Campus, LLC                | Loan       | 2010-02-08T00:00:00 | 1250000 | 36    | 
| 2010        | Wilmington Senior Housing Phase II          | Becky Avenue and Vista Drive                     | Wilmington               | Wilmington Senior Housing L.P. II                       | Loan       | 2009-12-04T00:00:00 | 1055000 | 42    | 
| 2010        | Woodlawn Center South Apartments            | 6222 South Cottage Grove Avenue                  | Chicago                  | WCS Preservation Associates L.P.                        | Loan       | 2010-04-19T00:00:00 | 1000000 | 67    | 
| 2010        | Charles Street Supportive Housing           | 3595 N. Charles Street                           | Decatur                  | Woodford Homes, Inc.                                    | Loan       | 2009-12-07T00:00:00 | 1500000 | 12    | 
| 2010        | Sandstone Hills                             | 2728 E. 13000 South Road                         | Hopkins Park             | Sandstone Hills, L.P.                                   | Loan       | 2010-02-04T00:00:00 | 1500000 | 29    | 
| 2010        | Willow Heights Apartments                   | 1460 Wellington Way                              | Decatur                  | Willow Heights Apartment Associates Limited Partnership | Loan       | 2010-02-16T00:00:00 | 900000  | 64    | 
| 2010        | Golden Oaks Senior Apts.                    | 1121 North Van Buren and 214 North Broad         | Litchfield and Hillsboro | Golden Oaks Senior Apts. L.P.                           | Loan       | 2010-06-30T00:00:00 | 750000  | 32    | 
| 2010        | Corporation for Supportive Housing (CSH)    | Scattered Sites                                  | Various                  | Corporation for Supportive Housing                      | Grant      | 2009-09-23T00:00:00 | 500000  | 0     | 
```