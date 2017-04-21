# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HTF

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-htf-4b93c) |
| Metadata | [Link](https://data.illinois.gov/api/views/butq-62sh) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/butq-62sh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/butq-62sh/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | butq-62sh |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HTF |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T21:14:00Z |
| Publication Date | 2012-01-25T21:58:57Z |

## Description

FY2010 Governor's Report - Applications.HTF

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
series e:butq-62sh d:2010-06-23T00:00:00.000Z t:project_sponsor=TBD t:project_name="15th and Bowman Elderly Residency" t:project_city="East St. Louis" t:type="Trust Fund" m:amount_=750000 m:units=74

series e:butq-62sh d:2010-05-17T00:00:00.000Z t:project_sponsor="DDG Boeger, L.P." t:project_name="Boeger Place Apartments" t:project_city="Arlington Heights" t:type="Trust Fund" m:amount_=1500000 m:units=30

series e:butq-62sh d:2010-06-29T00:00:00.000Z t:project_sponsor="Community Housing Association of DuPage (CHAD)" t:project_name="Brandon Courts Apartments" t:project_city="Glen Ellyn" t:type="Trust Fund" m:amount_=750000 m:units=6
```

## Meta Commands

```ls
metric m:amount_ p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:butq-62sh l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HTF" t:url=https://data.illinois.gov/api/views/butq-62sh

property e:butq-62sh t:meta.view v:id=butq-62sh v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.HTF"

property e:butq-62sh t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:butq-62sh t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                       | project_address                   | project_city       | project_sponsor                                | type       | application_date    | amount_ | units | 
| =========== | ================================== | ================================= | ================== | ============================================== | ========== | =================== | ======= | ===== | 
| 2010        | 15th and Bowman Elderly Residency  | N. 15th Street and Bowman Avenue  | East St. Louis     | TBD                                            | Trust Fund | 2010-06-23T00:00:00 | 750000  | 74    | 
| 2010        | Boeger Place Apartments            | 120 Boeger Drive                  | Arlington Heights  | DDG Boeger, L.P.                               | Trust Fund | 2010-05-17T00:00:00 | 1500000 | 30    | 
| 2010        | Brandon Courts Apartments          | 16-34 Greenwood Street            | Glen Ellyn         | Community Housing Association of DuPage (CHAD) | Trust Fund | 2010-06-29T00:00:00 | 750000  | 6     | 
| 2010        | Canterbury House of Dixon Phase II | 1501 Lowell Park Road             | Dixon              | Canterbury House II - Dixon, L.P.              | Trust Fund | 2010-05-17T00:00:00 | 1500000 | 58    | 
| 2010        | Cicero & George Elderly Housing    | 2900-12 N. Cicero                 | Chicago            | Cicero & George L.P.                           | Trust Fund | 2010-05-17T00:00:00 | 1000000 | 72    | 
| 2010        | Conrad Apartments                  | 4845 & 4831 Conrad                | Skokie             | Conrad LP                                      | Trust Fund | 2010-05-31T00:00:00 | 500000  | 23    | 
| 2010        | Copley Redevelopment Phase I       | 502 S. Lincoln Avenue             | Aurora             | Aurora Senior Apartments, L.P.                 | Trust Fund | 2010-05-17T00:00:00 | 1250000 | 80    | 
| 2010        | Country Club Hills Wellness Center | W. 167th Street & S. Pulaski Road | Country Club Hills | Country Club Hills Wellness Center, LP         | Trust Fund | 2010-05-17T00:00:00 | 1500000 | 77    | 
| 2010        | Emerson Square                     | 1600 West Foster Street           | Evanston           | EmSq, LLC                                      | Trust Fund | 2010-05-17T00:00:00 | 750000  | 30    | 
| 2010        | G&A Senior Residences at Kedzie    | 4054 North Kedzie Avenue          | Chicago            | Kedzie Partners, L.P.                          | Trust Fund | 2010-05-17T00:00:00 | 125000  | 50    | 
```