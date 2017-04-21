# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HOME

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-home-45093) |
| Metadata | [Link](https://data.illinois.gov/api/views/8zbq-e3e9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8zbq-e3e9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8zbq-e3e9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8zbq-e3e9 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HOME |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T21:10:33Z |
| Publication Date | 2012-01-25T21:59:07Z |

## Description

FY2010 Governor's Report - Applications.HOME

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| No       |                | fiscal_year      | FISCAL YEAR      | number        | text          |
| Yes      | series tag     | project_name     | PROJECT NAME     | text          | text          |
| No       |                | project_address  | PROJECT ADDRESS  | text          | text          |
| Yes      | series tag     | project_city     | PROJECT CITY     | text          | text          |
| Yes      | series tag     | project_sponsor  | PROJECT SPONSOR  | text          | text          |
| Yes      | series tag     | type             | TYPE             | text          | text          |
| Yes      | time           | application_date | APPLICATION DATE | calendar_date | calendar_date |
| Yes      | numeric metric | amount_          | AMOUNT           | money         | money         |
| Yes      | numeric metric | units            | UNITS            | number        | number        |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:8zbq-e3e9 d:2010-05-17T00:00:00.000Z t:project_sponsor="DDG Boeger, L.P." t:project_name="Boeger Place Apartments" t:project_city="Arlington Heights" t:type=HOME m:amount_=1477919 m:units=30

series e:8zbq-e3e9 d:2010-05-17T00:00:00.000Z t:project_sponsor="Canterbury House II - Dixon, L.P." t:project_name="Canterbury House of Dixon Phase II" t:project_city=Dixon t:type=HOME m:amount_=2000000 m:units=58

series e:8zbq-e3e9 d:2010-05-17T00:00:00.000Z t:project_sponsor="Carlinville Properties, L.P." t:project_name="Carlinville Heights" t:project_city=Carlinville t:type=HOME m:amount_=584745 m:units=20
```

## Meta Commands

```ls
metric m:amount_ p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:8zbq-e3e9 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HOME" t:url=https://data.illinois.gov/api/views/8zbq-e3e9

property e:8zbq-e3e9 t:meta.view v:id=8zbq-e3e9 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HOME"

property e:8zbq-e3e9 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:8zbq-e3e9 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                       | project_address                                         | project_city      | project_sponsor                          | type | application_date    | amount_ | units | 
| =========== | ================================== | ======================================================= | ================= | ======================================== | ==== | =================== | ======= | ===== | 
| 2010        | Boeger Place Apartments            | 120 Boeger Drive                                        | Arlington Heights | DDG Boeger, L.P.                         | HOME | 2010-05-17T00:00:00 | 1477919 | 30    | 
| 2010        | Canterbury House of Dixon Phase II | 1501 Lowell Park Road                                   | Dixon             | Canterbury House II - Dixon, L.P.        | HOME | 2010-05-17T00:00:00 | 2000000 | 58    | 
| 2010        | Carlinville Heights                | 310 Spruce Street                                       | Carlinville       | Carlinville Properties, L.P.             | HOME | 2010-05-17T00:00:00 | 584745  | 20    | 
| 2010        | Cicero & George Elderly Housing    | 2900-12 N. Cicero                                       | Chicago           | Cicero & George L.P.                     | HOME | 2010-05-17T00:00:00 | 1976000 | 72    | 
| 2010        | Conrad Apartments                  | 4845 & 4831 Conrad                                      | Skokie            | Conrad LP                                | HOME | 2010-05-31T00:00:00 | 1100000 | 23    | 
| 2010        | Copley Redevelopment Phase I       | 502 S. Lincoln Avenue                                   | Aurora            | Aurora Senior Apartments, L.P.           | HOME | 2010-05-17T00:00:00 | 2000000 | 80    | 
| 2010        | Courts of Cicero                   | 1638 S. 51st , 1801 S. 50th, 5700 W. 35th, 5741 W. 35th | Cicero            | Courts of Cicero, LLC                    | HOME | 2010-06-23T00:00:00 | 1945480 | 54    | 
| 2010        | Eastwood Gardens                   | 6501 South Lowe Avenue                                  | Chicago           | TBD                                      | HOME | 2010-05-26T00:00:00 | 2082236 | 188   | 
| 2010        | Elgin Artspace Lofts               | 51 South Spring Street                                  | Elgin             | Elgin Artspace Lofts Limited Partnership | HOME | 2010-05-17T00:00:00 | 1350000 | 55    | 
| 2010        | Emerson Square                     | 1600 West Foster Street                                 | Evanston          | EmSq, LLC                                | HOME | 2010-05-17T00:00:00 | 1538377 | 30    | 
```