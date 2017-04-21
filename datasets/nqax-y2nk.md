# Community Legacy 2013 Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-legacy-2013-awards-549d9) |
| Metadata | [Link](https://data.maryland.gov/api/views/nqax-y2nk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nqax-y2nk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nqax-y2nk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nqax-y2nk |
| Name | Community Legacy 2013 Awards |
| Attribution | Maryland Department of Housing and Community Development |
| Category | Housing |
| Tags | local governments, community development, grants, loans home ownership, commercial, revitalization, business retention, economic development, sustainable, smart growth, neighborhood, housing |
| Created | 2014-05-02T15:43:29Z |
| Publication Date | 2014-05-02T15:54:29Z |

## Description

COMMUNITY LEGACY (CL) provides local governments and community development organizations with funding for essential projects aimed at strengthening communities through activities such as business retention and attraction, encouraging homeownership and commercial revitalization. 
As a result of the Sustainable Communities Act of 2010. Community Legacy Areas are now known as Sustainable Communities. Funding, in the form of grants and loans, is available for projects located in these Sustainable Communities, formerly known as Community Legacy Areas, and is meant to compliment and supplement other State funding programs.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | Fiscal Year    | number    | text        |
| Yes      | series tag     | proj           | Proj #         | text      | text        |
| Yes      | series tag     | awardee        | Awardee        | text      | text        |
| Yes      | series tag     | city           | City           | text      | text        |
| Yes      | series tag     | county         | County         | text      | text        |
| Yes      | series tag     | project_name   | Project Name   | text      | text        |
| Yes      | numeric metric | amount_awarded | Amount Awarded | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nqax-y2nk d:2013-01-01T00:00:00.000Z t:project_name="South Cumberland Revitalization - Special Initiative Fund" t:county=Allegany t:proj=135001 t:awardee="Allegany County Human Resources Development Commission, Inc." t:city=Cumberland m:amount_awarded=150000

series e:nqax-y2nk d:2013-01-01T00:00:00.000Z t:project_name="19 Frederick Street Rehabilitation" t:county=Allegany t:proj=131801 t:awardee="Cumberland, City of" t:city=Cumberland m:amount_awarded=100000

series e:nqax-y2nk d:2013-01-01T00:00:00.000Z t:project_name="Residential Shade Tree Planting Program" t:county=Allegany t:proj=131803 t:awardee="Cumberland, City of" t:city=Cumberland m:amount_awarded=16000
```

## Meta Commands

```ls
metric m:amount_awarded p:integer l:"Amount Awarded" t:dataTypeName=money

entity e:nqax-y2nk l:"Community Legacy 2013 Awards" t:attribution="Maryland Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/nqax-y2nk

property e:nqax-y2nk t:meta.view v:id=nqax-y2nk v:category=Housing v:attributionLink=http://www.dhcd.maryland.gov v:averageRating=0 v:name="Community Legacy 2013 Awards" v:attribution="Maryland Department of Housing and Community Development"

property e:nqax-y2nk t:meta.view.license v:name="Public Domain"

property e:nqax-y2nk t:meta.view.owner v:id=2iss-uk5d v:screenName="Virginia Tepper" v:displayName="Virginia Tepper"

property e:nqax-y2nk t:meta.view.tableauthor v:id=2iss-uk5d v:screenName="Virginia Tepper" v:roleName=editor v:displayName="Virginia Tepper"
```

## Top Records

```ls
| fiscal_year | proj   | awardee                                                      | city       | county         | project_name                                              | amount_awarded | 
| =========== | ====== | ============================================================ | ========== | ============== | ========================================================= | ============== | 
| 2013        | 135001 | Allegany County Human Resources Development Commission, Inc. | Cumberland | Allegany       | South Cumberland Revitalization - Special Initiative Fund | 150000         | 
| 2013        | 131801 | Cumberland, City of                                          | Cumberland | Allegany       | 19 Frederick Street Rehabilitation                        | 100000         | 
| 2013        | 131803 | Cumberland, City of                                          | Cumberland | Allegany       | Residential Shade Tree Planting Program                   | 16000          | 
| 2013        | 132201 | Frostburg, City of                                           | Frostburg  | Allegany       | Facade and Restoration                                    | 50000          | 
| 2013        | 130001 | Annapolis, City of - Clay Street                             | Annapolis  | Anne Arundel   | Bates Heritage Youth Development Park                     | 50000          | 
| 2013        | 130401 | Baltimore Development Corp.                                  | Baltimore  | Baltimore City | Baltimore Main Streets Design Funds                       | 150000         | 
| 2013        | 130405 | Baltimore Development Corp.                                  | Baltimore  | Baltimore City | Highlandtown Streetscape Placemaking Project              | 100000         | 
| 2013        | 131201 | Central Baltimore Partnership                                | Baltimore  | Baltimore City | Load of Fun Improvements & Stabilization                  | 100000         | 
| 2013        | 131202 | Central Baltimore Partnership                                | Baltimore  | Baltimore City | 10 E. North Avenue                                        | 100000         | 
| 2013        | 131203 | Central Baltimore Partnership                                | Baltimore  | Baltimore City | Baltimore Design School                                   | 100000         | 
```