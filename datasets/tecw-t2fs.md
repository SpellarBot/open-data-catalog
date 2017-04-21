# Community Legacy 2014 Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-legacy-2014-awards-38156) |
| Metadata | [Link](https://data.maryland.gov/api/views/tecw-t2fs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tecw-t2fs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tecw-t2fs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tecw-t2fs |
| Name | Community Legacy 2014 Awards |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | department of housing & community development, dhcd, cl, community legacy, neighborhood revitalization, nr, sustainable communities, community legacy areas |
| Created | 2014-05-02T16:04:17Z |
| Publication Date | 2014-05-02T16:08:46Z |

## Description

The Community Legacy program provides local governments and community development organizations with funding for essential projects aimed at strengthening communities through activities such as business retention and attraction, encouraging homeownership and commercial revitalization.?

?As a result of the Sustainable Communities Act of 2010?. Community Legacy Areas are now known as Sustainable Communities. Funding, in the form of grants and loans, is available for projects located in these Sustainable Communities, formerly known as Community Legacy Areas, and is meant to compliment and supplement other State funding programs.?

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | fiscal_year         | Fiscal Year         | number    | text        |
| Yes      | series tag     | proj                | Proj #              | text      | text        |
| Yes      | series tag     | awardee             | Awardee             | text      | text        |
| Yes      | series tag     | city                | City                | text      | text        |
| Yes      | series tag     | county              | County              | text      | text        |
| Yes      | series tag     | project_name_awards | Project Name Awards | text      | text        |
| Yes      | numeric metric | amount_awarded      | Amount Awarded      | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tecw-t2fs d:2014-01-01T00:00:00.000Z t:project_name_awards="Upper Story Redevelopment" t:county=Allegany t:proj=142201 t:awardee="Cumberland, City of" t:city=Cumberland m:amount_awarded=100000

series e:tecw-t2fs d:2014-01-01T00:00:00.000Z t:project_name_awards="Neighborhoods Matter" t:county=Allegany t:proj=142203 t:awardee="Cumberland, City of" t:city=Cumberland m:amount_awarded=75000

series e:tecw-t2fs d:2014-01-01T00:00:00.000Z t:project_name_awards="Friends Aware Building Expansion and Renovation Project" t:county=Allegany t:proj=142204 t:awardee="Cumberland, City of" t:city=Cumberland m:amount_awarded=100000
```

## Meta Commands

```ls
metric m:amount_awarded p:integer l:"Amount Awarded" t:dataTypeName=money

entity e:tecw-t2fs l:"Community Legacy 2014 Awards" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/tecw-t2fs

property e:tecw-t2fs t:meta.view v:id=tecw-t2fs v:category=Housing v:attributionLink=http://www.dhcd.maryland.gov/ v:averageRating=0 v:name="Community Legacy 2014 Awards" v:attribution="Department of Housing and Community Development"

property e:tecw-t2fs t:meta.view.license v:name="Public Domain"

property e:tecw-t2fs t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:tecw-t2fs t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| fiscal_year | proj   | awardee                                      | city          | county         | project_name_awards                                       | amount_awarded | 
| =========== | ====== | ============================================ | ============= | ============== | ========================================================= | ============== | 
| 2014        | 142201 | Cumberland, City of                          | Cumberland    | Allegany       | Upper Story Redevelopment                                 | 100000         | 
| 2014        | 142203 | Cumberland, City of                          | Cumberland    | Allegany       | Neighborhoods Matter                                      | 75000          | 
| 2014        | 142204 | Cumberland, City of                          | Cumberland    | Allegany       | Friends Aware Building Expansion and Renovation Project   | 100000         | 
| 2014        | 142205 | Cumberland, City of                          | Cumberland    | Allegany       | Neighborhood Restoration                                  | 85000          | 
| 2014        | 143101 | Frostburg, City of                           | Frostburg     | Allegany       | Facade Restoration Program                                | 50000          | 
| 2014        | 140101 | Arundel Community Development Services, Inc. | Brooklyn Park | Anne Arundel   | Brooklyn Park Acquisition/Rehabilitation Program          | 150000         | 
| 2014        | 140401 | Baltimore Co-Dundalk/Sparrows Point-SC Area  | Dundalk       | Baltimore      | North Point State Battlefield Infrastructure Improvements | 100000         | 
| 2014        | 140501 | Baltimore Development Corp.                  | Baltimore     | Baltimore City | Facade Improvement Grant Funds                            | 100000         | 
| 2014        | 140503 | Baltimore Development Corp.                  | Baltimore     | Baltimore City | Hamilton Fire House Solar Tube Project                    | 50000          | 
| 2014        | 141403 | Central Baltimore Partnership                | Baltimore     | Baltimore City | The Tire Shop                                             | 100000         | 
```