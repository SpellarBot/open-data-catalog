# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.TCAP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-tcap-d0b7d) |
| Metadata | [Link](https://data.illinois.gov/api/views/y73p-kwm7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/y73p-kwm7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/y73p-kwm7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | y73p-kwm7 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.TCAP |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T16:46:31Z |
| Publication Date | 2012-01-25T22:00:39Z |

## Description

FY2010 Governor's Report - Closings.TCAP

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
series e:y73p-kwm7 d:2009-12-29T00:00:00.000Z t:loan_grant=Loan t:project_name="Knollwood Retirement Center St. Clair" t:owner="St. Clair Supportive Living LP" t:project_city=Caseyville m:amount=1656251 m:units=98

series e:y73p-kwm7 d:2010-01-15T00:00:00.000Z t:loan_grant=Loan t:project_name="Bella Vista Apartments - Family" t:owner="Bella Partners, L.P." t:project_city=Waterloo m:amount=1178444 m:units=44

series e:y73p-kwm7 d:2010-01-15T00:00:00.000Z t:loan_grant=Loan t:project_name="Bella Vista Apartments (Senior)" t:owner="Bella Partners, L.P." t:project_city=Waterloo m:amount=939865 m:units=32
```

## Meta Commands

```ls
metric m:amount p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:y73p-kwm7 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.TCAP" t:url=https://data.illinois.gov/api/views/y73p-kwm7

property e:y73p-kwm7 t:meta.view v:id=y73p-kwm7 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.TCAP"

property e:y73p-kwm7 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:y73p-kwm7 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                          | project_address                                        | project_city             | owner                                              | loan_grant | closing_date        | amount  | units | 
| =========== | ===================================== | ====================================================== | ======================== | ================================================== | ========== | =================== | ======= | ===== | 
| 2010        | Knollwood Retirement Center St. Clair | 1000 S. Main (Hwy 157)                                 | Caseyville               | St. Clair Supportive Living LP                     | Loan       | 2009-12-29T00:00:00 | 1656251 | 98    | 
| 2010        | Bella Vista Apartments - Family       | 100 and 101 Debra Lane                                 | Waterloo                 | Bella Partners, L.P.                               | Loan       | 2010-01-15T00:00:00 | 1178444 | 44    | 
| 2010        | Bella Vista Apartments (Senior)       | 103 Debra Lane                                         | Waterloo                 | Bella Partners, L.P.                               | Loan       | 2010-01-15T00:00:00 | 939865  | 32    | 
| 2010        | Carbondale Neighbors                  | Scattered Sites in Northeast Carbondale                | Carbondale               | Carbondale Neighbors, L.P.                         | Loan       | 2010-03-16T00:00:00 | 500000  | 20    | 
| 2010        | Crane Meadows Apartments              | 1503-1519 & 1521-1617 Lorelei Drive                    | Zion                     | A to-be-formed sole purpose Limited Partnership    | Loan       | 2010-03-29T00:00:00 | 4439052 | 264   | 
| 2010        | Douglas County Apartments             | 200 Van Vorrhis, 112 E. Daggy St. & 402 S. Main Street | Tuscola & Atwood         | Douglas County Partners L.P.                       | Loan       | 2010-02-11T00:00:00 | 693587  | 35    | 
| 2010        | Faust Landmark Apartments             | 630 East State Street                                  | Rockford                 | Rockford Faust Limited Partnership                 | Loan       | 2010-06-30T00:00:00 | 969877  | 201   | 
| 2010        | Golden Oaks Senior Apts.              | 1121 North Van Buren and 214 North Broad               | Litchfield and Hillsboro | Golden Oaks Senior Apts. L.P.                      | Loan       | 2010-06-30T00:00:00 | 516507  | 32    | 
| 2010        | Hancock House                         | 12045 S. Emerald                                       | Chicago                  | Hancock House LP                                   | Loan       | 2010-05-28T00:00:00 | 4168406 | 89    | 
| 2010        | Maple Ridge Apartments                | 1000 East of Intersection of E. Court St. & U.S. 150   | Paris                    | Maple Ridge Affordable Housing Limited Partnership | Loan       | 2009-12-02T00:00:00 | 3132292 | 50    | 
```