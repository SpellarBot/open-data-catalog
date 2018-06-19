# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Home

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-home-4dfeb) |
| Metadata | [Link](https://data.illinois.gov/api/views/uyuj-n4h5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/uyuj-n4h5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/uyuj-n4h5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | uyuj-n4h5 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Home |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-24T23:13:22Z |
| Publication Date | 2012-01-25T22:01:21Z |

## Description

FY2010 Governor's Report - Closings.Home

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| No       |                | fiscal_year     | FISCAL YEAR     | number        | text          |
| Yes      | series tag     | project_name    | PROJECT NAME    | text          | text          |
| No       |                | project_address | PROJECT ADDRESS | text          | text          |
| Yes      | series tag     | project_city    | PROJECT CITY    | text          | text          |
| Yes      | series tag     | owner           | OWNER           | text          | text          |
| Yes      | time           | closing_date    | CLOSING DATE    | calendar_date | calendar_date |
| Yes      | numeric metric | amount          | AMOUNT          | money         | money         |
| Yes      | numeric metric | units           | UNITS           | number        | number        |
| Yes      | numeric metric | home_units      | HOME UNITS      | number        | number        |
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
series e:uyuj-n4h5 d:2009-12-02T00:00:00.000Z t:project_name="Maple Ridge Apartments" t:owner="Maple Ridge Affordable Housing Limited Partnership" t:project_city=Paris m:amount=2250000 m:home_units=50 m:units=50

series e:uyuj-n4h5 d:2010-06-30T00:00:00.000Z t:project_name="Monmouth Farms" t:owner="DDG Monmouth L.P." t:project_city=Monmouth m:amount=1200000 m:home_units=5 m:units=40

series e:uyuj-n4h5 d:2010-05-27T00:00:00.000Z t:project_name="Prairie Meadows Homes" t:owner="Prairie Meadows Homes, L.P." t:project_city=Hoopeston m:amount=2000000 m:home_units=25 m:units=25
```

## Meta Commands

```ls
metric m:amount p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:home_units p:integer l:"HOME UNITS" t:dataTypeName=number

entity e:uyuj-n4h5 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Home" t:url=https://data.illinois.gov/api/views/uyuj-n4h5

property e:uyuj-n4h5 t:meta.view v:id=uyuj-n4h5 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Home"

property e:uyuj-n4h5 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:uyuj-n4h5 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                                | project_address                                      | project_city  | owner                                              | closing_date        | amount  | units | home_units | 
| =========== | =========================================== | ==================================================== | ============= | ================================================== | =================== | ======= | ===== | ========== | 
| 2010        | Maple Ridge Apartments                      | 1000 East of Intersection of E. Court St. & U.S. 150 | Paris         | Maple Ridge Affordable Housing Limited Partnership | 2009-12-02T00:00:00 | 2250000 | 50    | 50         | 
| 2010        | Monmouth Farms                              | 2050 75th Street                                     | Monmouth      | DDG Monmouth L.P.                                  | 2010-06-30T00:00:00 | 1200000 | 40    | 5          | 
| 2010        | Prairie Meadows Homes                       | Cornjerker and S. Market Avenue                      | Hoopeston     | Prairie Meadows Homes, L.P.                        | 2010-05-27T00:00:00 | 2000000 | 25    | 25         | 
| 2010        | Shorewood Horizon Senior Living Community   | Northeast Corner of Black Road & Shorewood Drive     | Shorewood     | Shorewood Horizon Limited Partnership              | 2010-03-31T00:00:00 | 2000000 | 51    | 14         | 
| 2010        | Spring Valley Senior Housing Phase II       | 210 West Fourth Street                               | Spring Valley | Spring Valley Senior Housing L.P. II               | 2010-02-16T00:00:00 | 2000000 | 52    | 50         | 
| 2010        | St. James Senior Estates II                 | 1251 E. Richton Rd.                                  | Crete         | Crete Senior Housing, LLC                          | 2009-12-18T00:00:00 | 2500000 | 45    | 36         | 
| 2010        | The Suites of Autumn Green at Wright Campus | 4255 North Oak Park Avenue                           | Chicago       | Senior Suites Chicago Wright Campus, LLC           | 2010-02-08T00:00:00 | 1402386 | 36    | 32         | 
| 2010        | Twenty First Homes                          | Scattered Sites                                      | Granite City  | Twenty First Homes, LP                             | 2010-03-31T00:00:00 | 670000  | 20    | 20         | 
| 2010        | Wilmington Senior Housing Phase II          | Becky Avenue and Vista Drive                         | Wilmington    | Wilmington Senior Housing L.P. II                  | 2009-12-04T00:00:00 | 2000000 | 42    | 40         | 
```