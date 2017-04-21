# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Neighborhood Stabilization Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-neighborhood-stabilization-ab48e) |
| Metadata | [Link](https://data.illinois.gov/api/views/54us-trtn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/54us-trtn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/54us-trtn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 54us-trtn |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Neighborhood Stabilization Program |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T21:33:14Z |
| Publication Date | 2012-01-25T21:58:00Z |

## Description

FY2010 Governor's Report - Closing.Neighborhood Stabilization Program

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| No       |                | fiscal_year_    | FISCAL YEAR     | number        | text          |
| Yes      | series tag     | project_sponsor | PROJECT SPONSOR | text          | text          |
| No       |                | project_address | PROJECT ADDRESS | text          | text          |
| Yes      | series tag     | type            | TYPE            | text          | text          |
| Yes      | time           | closing_date    | CLOSING DATE    | calendar_date | calendar_date |
| Yes      | numeric metric | grant_total     | GRANT TOTAL     | money         | money         |
| Yes      | numeric metric | units           | UNITS           | number        | number        |
| Yes      | series tag     | pid_            | PID #           | text          | text          |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year_
```

## Data Commands

```ls
series e:54us-trtn d:2010-04-06T00:00:00.000Z t:project_sponsor="Will County Land Use Department" t:type=Grant t:pid_=75010 m:grant_total=2500000 m:units=123

series e:54us-trtn d:2010-04-07T00:00:00.000Z t:project_sponsor="The Springfield Project" t:type=Grant t:pid_=75014 m:grant_total=1416660 m:units=8

series e:54us-trtn d:2010-04-27T00:00:00.000Z t:project_sponsor="New Mom's, Inc." t:type=Grant t:pid_=75004 m:grant_total=6216548 m:units=40
```

## Meta Commands

```ls
metric m:grant_total p:integer l:"GRANT TOTAL" t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:54us-trtn l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Neighborhood Stabilization Program" t:url=https://data.illinois.gov/api/views/54us-trtn

property e:54us-trtn t:meta.view v:id=54us-trtn v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Neighborhood Stabilization Program"

property e:54us-trtn t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:54us-trtn t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year_ | project_sponsor                           | project_address                                                           | type  | closing_date        | grant_total | units | pid_  | 
| ============ | ========================================= | ========================================================================= | ===== | =================== | =========== | ===== | ===== | 
| 2010         | Will County Land Use Department           | Scattered Sites in Will County, City of Joliet and Village of Bolingbrook | Grant | 2010-04-06T00:00:00 | 2500000     | 123   | 75010 | 
| 2010         | The Springfield Project                   | Scattered Sites in East Springfield                                       | Grant | 2010-04-07T00:00:00 | 1416660     | 8     | 75014 | 
| 2010         | New Mom's, Inc.                           | Scattered Sites in the Chicago neighborhood of Austin                     | Grant | 2010-04-27T00:00:00 | 6216548     | 40    | 75004 | 
| 2010         | Madison County Community Development      | Scattered Sites in Madison County                                         | Grant | 2010-04-27T00:00:00 | 2600000     | 29    | 75018 | 
| 2010         | IFF Housing                               | Scattered Sites in the counties of Cook, LaSalle, Kane and Whiteside      | Grant | 2010-04-06T00:00:00 | 5133000     | 24    | 75003 | 
| 2010         | Habitat for Humanity                      | Scattered Sites in Cities of Zion, North Chicago and Waukegan             | Grant | 2010-05-20T00:00:00 | 1880000     | 12    | 75009 | 
| 2010         | City of Champaign                         | Scattered Sites in the City of Champaign                                  | Grant | 2010-05-20T00:00:00 | 1789700     | 15    | 75012 | 
| 2010         | Proviso Township Mental Health Commission | Scattered Sites in Proviso Township                                       | Grant | 2010-04-08T00:00:00 | 2500000     | 13    | 75002 | 
| 2010         | City of Quincy                            | Scattered Sites in the City of Quincy                                     | Grant | 2010-04-12T00:00:00 | 1900000     | 13    | 75016 | 
| 2010         | City of East St. Louis                    | Scattered Sites in the City of East St. Louis                             | Grant | 2010-04-14T00:00:00 | 2500000     | 17    | 75017 | 
```