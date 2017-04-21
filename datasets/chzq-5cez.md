# Small Town Economic Assistance Program (STEAP) Master Award List from 2005 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/small-town-economic-assistance-program-steap-master-award-list-from-2005-to-present) |
| Metadata | [Link](https://data.ct.gov/api/views/chzq-5cez) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/chzq-5cez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/chzq-5cez/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | chzq-5cez |
| Name | Small Town Economic Assistance Program (STEAP) Master Award List from 2005 to Present |
| Category | Government |
| Tags | steap, opm |
| Created | 2014-12-09T19:08:31Z |
| Publication Date | 2016-11-22T15:15:11Z |

## Description

Small Town Economic Assistance Program (STEAP) Master Award List from 2005 to Present

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | Year                 | number    | text        |
| Yes      | series tag     | town_name            | Town Name            | text      | text        |
| Yes      | series tag     | project_description  | Project Description  | text      | text        |
| Yes      | numeric metric | grant_amount         | Grant Amount         | number    | number      |
| Yes      | series tag     | administering_agency | Administering Agency | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:chzq-5cez d:2012-01-01T00:00:00.000Z t:administering_agency=DECD t:town_name="Northwest Regional Collaboration" t:project_description="Coordinate, marketing and promote local business" m:grant_amount=80000

series e:chzq-5cez d:2014-01-01T00:00:00.000Z t:administering_agency=DECD t:town_name=Plymouth t:project_description="Route 6 streetscape" m:grant_amount=500000

series e:chzq-5cez d:2014-01-01T00:00:00.000Z t:administering_agency=DECD t:town_name=Tolland t:project_description="Public library expansion" m:grant_amount=500000
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=number

entity e:chzq-5cez l:"Small Town Economic Assistance Program (STEAP) Master Award List from 2005 to Present" t:url=https://data.ct.gov/api/views/chzq-5cez

property e:chzq-5cez t:meta.view v:id=chzq-5cez v:category=Government v:averageRating=0 v:name="Small Town Economic Assistance Program (STEAP) Master Award List from 2005 to Present"

property e:chzq-5cez t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:chzq-5cez t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| year | town_name                        | project_description                                                                    | grant_amount | administering_agency | 
| ==== | ================================ | ====================================================================================== | ============ | ==================== | 
| 2012 | Northwest Regional Collaboration | Coordinate, marketing and promote local business                                       | 80000        | DECD                 | 
| 2014 | Plymouth                         | Route 6 streetscape                                                                    | 500000       | DECD                 | 
| 2014 | Tolland                          | Public library expansion                                                               | 500000       | DECD                 | 
| 2014 | Winsted/Winchester               | Redevelop Lambert Kay Building                                                         | 500000       | DECD                 | 
| 2010 | North Branford                   | Development of Swajchuk Park as a centralized recreation facility                      | 200000       | DEEP                 | 
| 2006 | Columbia                         | An addition to Beckish Senior Center                                                   | 500000       | DSS                  | 
| 2008 | Redding                          | Construction of various improvements to the athletic fields at John Read Middle School | 400000       | DEEP                 | 
| 2011 | Middlefield                      | Installation of three solar powered omni directional sirens                            | 52456        | DECD                 | 
| 2005 | Old Lyme                         | Construction and expansion of the Town Woods Playground                                | 20000        | OPM                  | 
| 2006 | Burlington                       | The replacement of the Prospect Street Bridge                                          | 120000       | DOT                  | 
```