# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.ARRA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-arra-ef7db) |
| Metadata | [Link](https://data.illinois.gov/api/views/cmfb-ymdn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cmfb-ymdn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cmfb-ymdn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cmfb-ymdn |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.ARRA |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T17:22:25Z |
| Publication Date | 2012-01-25T21:59:18Z |

## Description

FY2010 Governor's Report - Applications.ARRA

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | fiscal_year      | FISCAL YEAR      | number    | text        |
| Yes      | series tag     | project_name     | PROJECT NAME     | text      | text        |
| No       |                | project_address  | PROJECT ADDRESS  | text      | text        |
| Yes      | series tag     | project_city     | PROJECT CITY     | text      | text        |
| Yes      | series tag     | project_sponsor  | PROJECT SPONSOR  | text      | text        |
| Yes      | series tag     | type             | TYPE             | text      | text        |
| No       |                | application_date | APPLICATION DATE | text      | text        |
| Yes      | numeric metric | amount_          | AMOUNT           | money     | money       |
| Yes      | numeric metric | units            | UNITS            | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = project_address,application_date
```

## Data Commands

```ls
series e:cmfb-ymdn d:2010-01-01T00:00:00.000Z t:project_sponsor="Bella Partners, L.P." t:project_name="Bella Vista Apartments - Family" t:project_city=Waterloo t:type=ARRA m:amount_=1833072 m:units=44

series e:cmfb-ymdn d:2010-01-01T00:00:00.000Z t:project_sponsor="Bella Partners, L.P." t:project_name="Bella Vista Apartments (Senior)" t:project_city=Waterloo t:type=ARRA m:amount_=1431370 m:units=32

series e:cmfb-ymdn d:2010-01-01T00:00:00.000Z t:project_sponsor="Brookstone Apartments, LP" t:project_name=Brookstone t:project_city=Waukegan t:type=ARRA m:amount_=1213496 m:units=168
```

## Meta Commands

```ls
metric m:amount_ p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:cmfb-ymdn l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.ARRA" t:url=https://data.illinois.gov/api/views/cmfb-ymdn

property e:cmfb-ymdn t:meta.view v:id=cmfb-ymdn v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.ARRA"

property e:cmfb-ymdn t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:cmfb-ymdn t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                    | project_address                                        | project_city     | project_sponsor                                 | type | application_date | amount_ | units | 
| =========== | =============================== | ====================================================== | ================ | =============================================== | ==== | ================ | ======= | ===== | 
| 2010        | Bella Vista Apartments - Family | 100 and 101 Debra Lane                                 | Waterloo         | Bella Partners, L.P.                            | ARRA | 7/1/09           | 1833072 | 44    | 
| 2010        | Bella Vista Apartments (Senior) | 103 Debra Lane                                         | Waterloo         | Bella Partners, L.P.                            | ARRA | 7/1/09           | 1431370 | 32    | 
| 2010        | Brookstone                      | 4247 Hickory Hills Drive                               | Waukegan         | Brookstone Apartments, LP                       | ARRA | 10/5/09          | 1213496 | 168   | 
| 2010        | Carbondale Neighbors            | scattered sites in Northeast Carbondale                | Carbondale       | Carbondale Neighbors, L.P.                      | ARRA | 7/1/09           | 4509119 | 20    | 
| 2010        | Clifton Magnolia                | 4416 N. Clifton Avenue and 4416 N. Magnolia Avenue     | Chicago          | Community Housing Partners X L.P.               | ARRA | 10/5/09          | 3433742 | 59    | 
| 2010        | Colonial Park Apartments        | 748 Sharon Avenue                                      | Park City        | Park City-LCRDC, LP                             | ARRA | 10/5/09          | 5093350 | 240   | 
| 2010        | Cottage Apartments              | West Hovey and South Cottage Ave                       | Normal           | Cottage Apartments L.P.                         | ARRA | 10/5/09          | 1159791 | 50    | 
| 2010        | Crane Meadows Apartments        | 1503-1519 & 1521-1617 Lorelei Drive                    | Zion             | A to-be-formed sole purpose Limited Partnership | ARRA | 10/5/09          | 4250000 | 264   | 
| 2010        | Crestside Village Apartments    | 504 S. Sixth Street and 707 Poplar Street              | Marshall         | Crestside Village L.P.                          | ARRA | 10/5/09          | 801155  | 23    | 
| 2010        | Douglas County Apartments       | 200 Van Vorrhis, 112 E. Daggy St. & 402 S. Main Street | Tuscola & Atwood | Douglas County Partners L.P.                    | ARRA | 7/1/09           | 919470  | 35    | 
```