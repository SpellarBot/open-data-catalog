# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.1602

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-1602-3ddb6) |
| Metadata | [Link](https://data.illinois.gov/api/views/9wtu-vcix) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9wtu-vcix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9wtu-vcix/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9wtu-vcix |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.1602 |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-24T23:02:30Z |
| Publication Date | 2012-01-25T22:02:00Z |

## Description

FY2010 Governor's Report - Closings.1602

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
series e:9wtu-vcix d:2010-01-15T00:00:00.000Z t:loan_grant=Grant t:project_name="Bella Vista Apartments - Family" t:owner="Bella Partners, L.P." t:project_city=Waterloo m:amount=785629 m:units=44

series e:9wtu-vcix d:2010-01-15T00:00:00.000Z t:loan_grant=Grant t:project_name="Bella Vista Apartments (Senior)" t:owner="Bella Partners, L.P." t:project_city=Waterloo m:amount=626577 m:units=32

series e:9wtu-vcix d:2010-03-16T00:00:00.000Z t:loan_grant=Grant t:project_name="Carbondale Neighbors" t:owner="Carbondale Neighbors, L.P." t:project_city=Carbondale m:amount=4808634 m:units=20
```

## Meta Commands

```ls
metric m:amount p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:9wtu-vcix l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.1602" t:url=https://data.illinois.gov/api/views/9wtu-vcix

property e:9wtu-vcix t:meta.view v:id=9wtu-vcix v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.1602"

property e:9wtu-vcix t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:9wtu-vcix t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                    | project_address                                        | project_city             | owner                                              | loan_grant | closing_date        | amount  | units | 
| =========== | =============================== | ====================================================== | ======================== | ================================================== | ========== | =================== | ======= | ===== | 
| 2010        | Bella Vista Apartments - Family | 100 and 101 Debra Lane                                 | Waterloo                 | Bella Partners, L.P.                               | Grant      | 2010-01-15T00:00:00 | 785629  | 44    | 
| 2010        | Bella Vista Apartments (Senior) | 103 Debra Lane                                         | Waterloo                 | Bella Partners, L.P.                               | Grant      | 2010-01-15T00:00:00 | 626577  | 32    | 
| 2010        | Carbondale Neighbors            | Scattered Sites in Northeast Carbondale                | Carbondale               | Carbondale Neighbors, L.P.                         | Grant      | 2010-03-16T00:00:00 | 4808634 | 20    | 
| 2010        | Douglas County Apartments       | 200 Van Vorrhis, 112 E. Daggy St. & 402 S. Main Street | Tuscola & Atwood         | Douglas County Partners L.P.                       | Grant      | 2010-02-11T00:00:00 | 504616  | 35    | 
| 2010        | Faust Landmark Apartments       | 630 East State Street                                  | Rockford                 | Rockford Faust Limited Partnership                 | Grant      | 2010-06-30T00:00:00 | 646584  | 201   | 
| 2010        | Golden Oaks Senior Apts.        | 1121 North Van Buren and 214 North Broad               | Litchfield and Hillsboro | Golden Oaks Senior Apts. L.P.                      | Grant      | 2010-06-30T00:00:00 | 1824703 | 32    | 
| 2010        | Hancock House                   | 12045 S. Emerald                                       | Chicago                  | Hancock House LP                                   | Grant      | 2010-05-28T00:00:00 | 4168406 | 89    | 
| 2010        | Hometown Harbor East Moline     | 11the Street & 48th Avenue                             | East Moline              | Hometown Harbor East Moline Limited Partnership    | Grant      | 2010-03-31T00:00:00 | 9474975 | 82    | 
| 2010        | Maple Ridge Apartments          | 1000 East of Intersection of E. Court St. & U.S. 150   | Paris                    | Maple Ridge Affordable Housing Limited Partnership | Grant      | 2009-12-02T00:00:00 | 2143991 | 50    | 
| 2010        | Monmouth Farms                  | 2050 75th Street                                       | Monmouth                 | DDG Monmouth L.P.                                  | Grant      | 2010-06-30T00:00:00 | 6014643 | 40    | 
```