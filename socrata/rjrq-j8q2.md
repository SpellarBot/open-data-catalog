# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.LIHTC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-lihtc-03660) |
| Metadata | [Link](https://data.illinois.gov/api/views/rjrq-j8q2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rjrq-j8q2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rjrq-j8q2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rjrq-j8q2 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.LIHTC |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-24T23:26:41Z |
| Publication Date | 2012-01-25T22:01:09Z |

## Description

FY2010 Governor's Report - Closings.LIHTC

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| No       |                | fiscal_year_                        | FISCAL YEAR                         | number        | text          |
| Yes      | series tag     | project_name                        | PROJECT NAME                        | text          | text          |
| No       |                | project_address                     | PROJECT ADDRESS                     | text          | text          |
| Yes      | series tag     | project_city                        | PROJECT CITY                        | text          | text          |
| Yes      | series tag     | owner                               | OWNER                               | text          | text          |
| Yes      | series tag     | credit_type                         | CREDIT TYPE                         | text          | percent       |
| Yes      | time           | reservation_date                    | RESERVATION DATE                    | calendar_date | calendar_date |
| Yes      | numeric metric | credits_allocated_                  | CREDITS ALLOCATED                   | number        | number        |
| Yes      | numeric metric | equity_amount                       | EQUITY AMOUNT                       | money         | money         |
| Yes      | numeric metric | units                               | UNITS                               | number        | number        |
| Yes      | numeric metric | low_income_housing_tax_credit_units | LOW INCOME HOUSING TAX CREDIT UNITS | number        | number        |
```

## Time Field

```ls
Value = reservation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year_
```

## Data Commands

```ls
series e:rjrq-j8q2 d:2009-08-14T00:00:00.000Z t:project_name="Clifton Magnolia" t:owner="Community Housing Partners X L.P." t:project_city=Chicago t:credit_type=9 m:credits_allocated_=953085 m:equity_amount=6289732 m:low_income_housing_tax_credit_units=59 m:units=59

series e:rjrq-j8q2 d:2009-08-17T00:00:00.000Z t:project_name="Cottage Apartments" t:owner="Cottage Apartments L.P." t:project_city=Normal t:credit_type=9 m:credits_allocated_=690000 m:equity_amount=4277572 m:low_income_housing_tax_credit_units=50 m:units=50

series e:rjrq-j8q2 d:2009-09-21T00:00:00.000Z t:project_name="Faust Landmark Apartments" t:owner="Rockford Faust Limited Partnership" t:project_city=Rockford t:credit_type=9 m:credits_allocated_=1675127 m:equity_amount=11892212 m:low_income_housing_tax_credit_units=200 m:units=201
```

## Meta Commands

```ls
metric m:credits_allocated_ p:integer l:"CREDITS ALLOCATED" t:dataTypeName=number

metric m:equity_amount p:integer l:"EQUITY AMOUNT" t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:low_income_housing_tax_credit_units p:integer l:"LOW INCOME HOUSING TAX CREDIT UNITS" t:dataTypeName=number

entity e:rjrq-j8q2 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.LIHTC" t:url=https://data.illinois.gov/api/views/rjrq-j8q2

property e:rjrq-j8q2 t:meta.view v:id=rjrq-j8q2 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.LIHTC"

property e:rjrq-j8q2 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:rjrq-j8q2 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year_ | project_name                     | project_address                                                                                    | project_city             | owner                                              | credit_type | reservation_date    | credits_allocated_ | equity_amount | units | low_income_housing_tax_credit_units | 
| ============ | ================================ | ================================================================================================== | ======================== | ================================================== | =========== | =================== | ================== | ============= | ===== | =================================== | 
| 2010         | Clifton Magnolia                 | 4416 N. Clifton Avenue and 4416 N. Magnolia Avenue                                                 | Chicago                  | Community Housing Partners X L.P.                  | 9           | 2009-08-14T00:00:00 | 953085             | 6289732       | 59    | 59                                  | 
| 2010         | Cottage Apartments               | West Hovey and South Cottage Ave                                                                   | Normal                   | Cottage Apartments L.P.                            | 9           | 2009-08-17T00:00:00 | 690000             | 4277572       | 50    | 50                                  | 
| 2010         | Faust Landmark Apartments        | 630 East State Street                                                                              | Rockford                 | Rockford Faust Limited Partnership                 | 9           | 2009-09-21T00:00:00 | 1675127            | 11892212      | 201   | 200                                 | 
| 2010         | Golden Oaks Senior Apts.         | 1121 North Van Buren and 214 North Broad                                                           | Litchfield and Hillsboro | Golden Oaks Senior Apts. L.P.                      | 9           | 2009-12-29T00:00:00 | 1000               | 8500          | 32    | 32                                  | 
| 2010         | Hope Manor Apartments            | 3045 W. Franklin Blvd, 442 N. Whipple St, 443 N. Albany Ave                                        | Chicago                  | West Side Veterans Housing L.P.                    | 9           | 2009-09-21T00:00:00 | 1303413            | 873224        | 50    | 50                                  | 
| 2010         | Independence Apartments          | SE Corner of Independence Blvd. & Arthington Street                                                | Chicago                  | Westside Village Phase V L.P.                      | 9           | 2009-09-08T00:00:00 | 695672             | 4759092       | 42    | 33                                  | 
| 2010         | Legends South Phase A-2          | 11-41 W. 43rd Street, 2-100 W. 45th Street, 4302-4506 S. State St. and 4301-4507 S. Federal Street | Chicago                  | Legends A-2, LLC                                   | 9           | 2009-07-28T00:00:00 | 1500000            | 28629200      | 138   | 110                                 | 
| 2010         | Liberty Meadows Estates Phase II | Southwest Corner of Briggs and Rosalind                                                            | Joliet                   | Liberty Meadow Estates Phase II                    | 9           | 2009-09-21T00:00:00 | 627995             | 3636083       | 42    | 35                                  | 
| 2010         | Lynwood Senior Housing Phase II  | 195th and Crescent                                                                                 | Lynwood                  | Lynwood Senior Housing L.P. II                     | 9           | 2009-08-17T00:00:00 | 1035861            | 7383617       | 67    | 65                                  | 
| 2010         | Maple Ridge Apartments           | 1000 East of Intersection of E. Court St. & U.S. 150                                               | Paris                    | Maple Ridge Affordable Housing Limited Partnership | 9           | 2009-11-02T00:00:00 | 3846               | 20350         |       |                                     | 
```