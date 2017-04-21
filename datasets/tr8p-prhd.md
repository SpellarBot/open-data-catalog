# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Multi-Family

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-multi-family-b1c59) |
| Metadata | [Link](https://data.illinois.gov/api/views/tr8p-prhd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tr8p-prhd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tr8p-prhd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tr8p-prhd |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Multi-Family |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T21:28:29Z |
| Publication Date | 2012-01-25T21:58:34Z |

## Description

FY2010 Governor's Report - Applications.Multi-Family

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
series e:tr8p-prhd d:2010-06-15T00:00:00.000Z t:project_sponsor="35th & Morgan Development Corp" t:project_name="Bridgeport Square" t:project_city=Chicago t:type="Tax Exempt Bonds" m:amount_=11200000 m:units=158

series e:tr8p-prhd d:2010-06-15T00:00:00.000Z t:project_sponsor="Partnership 18, LP" t:project_name="Centreville Courts" t:project_city=Centreville t:type="Tax Exempt Bonds" m:amount_=3800000 m:units=102

series e:tr8p-prhd d:2010-06-01T00:00:00.000Z t:project_sponsor=TBD t:project_name="Columbia Lakes Apartments" t:project_city=Columbia t:type="Tax Exempt Bonds" m:amount_=7200000 m:units=138
```

## Meta Commands

```ls
metric m:amount_ p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:tr8p-prhd l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Multi-Family" t:url=https://data.illinois.gov/api/views/tr8p-prhd

property e:tr8p-prhd t:meta.view v:id=tr8p-prhd v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Multi-Family"

property e:tr8p-prhd t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:tr8p-prhd t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                 | project_address                     | project_city             | project_sponsor                            | type             | application_date    | amount_  | units | 
| =========== | ============================ | =================================== | ======================== | ========================================== | ================ | =================== | ======== | ===== | 
| 2010        | Bridgeport Square            | 1038 W. 35th Street                 | Chicago                  | 35th & Morgan Development Corp             | Tax Exempt Bonds | 2010-06-15T00:00:00 | 11200000 | 158   | 
| 2010        | Centreville Courts           | 100 Grambling Court                 | Centreville              | Partnership 18, LP                         | Tax Exempt Bonds | 2010-06-15T00:00:00 | 3800000  | 102   | 
| 2010        | Columbia Lakes Apartments    | 2623 Columbia Lakes Drive           | Columbia                 | TBD                                        | Tax Exempt Bonds | 2010-06-01T00:00:00 | 7200000  | 138   | 
| 2010        | Country Village 1-2-3        | Scattered Sites                     | Anna, Vienna, Metropolis | Regions Bank Trust #22539 dated 08/27/1982 | Tax Exempt Bonds | 2010-05-13T00:00:00 | 2189136  | 104   | 
| 2010        | Eastwood Gardens             | 6501 South Lowe Avenue              | Chicago                  | TBD                                        | Tax Exempt Bonds | 2010-05-26T00:00:00 | 2082236  | 188   | 
| 2010        | Ecologic Loft Apartments     | 2359 North Seely                    | Chicago                  | 2339-59 N. Seeley LLC                      | Tax Exempt Bonds | 2010-05-24T00:00:00 | 20989000 | 94    | 
| 2010        | Garfield Ridge               | 5134 W. 47th Street                 | Chicago                  | Garfield Ridge Senior Residences LLC       | Taxable Bonds    | 2010-05-17T00:00:00 | 1475113  | 82    | 
| 2010        | Heritage Woods of Plainfield | New Van Dyke Road, S. of John Adams | Plainfield               | Plainfield Supportive Living, LLC          | Tax Exempt Bonds | 2010-03-12T00:00:00 | 371465   | 108   | 
| 2010        | Homestead at Morton Grove    | 6406 Lincoln Avenue                 | Morton Grove             | Homestead of Morton Grove, L.L.C.          | Tax Exempt Bonds | 2010-06-01T00:00:00 | 10677665 | 82    | 
| 2010        | Innsbruck Apartments         | 601 Preston Drive                   | Bolingbrook              | Innsbruck Apartments LP                    | Tax Exempt Bonds | 2010-06-01T00:00:00 | 20340000 | 475   | 
```