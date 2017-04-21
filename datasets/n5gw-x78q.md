# Donations to Recreation and Parks Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rpd-donations) |
| Metadata | [Link](https://data.sfgov.org/api/views/n5gw-x78q) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/n5gw-x78q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/n5gw-x78q/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | n5gw-x78q |
| Name | Donations to Recreation and Parks Department |
| Attribution | San Francisco Recreation & Parks Department |
| Category | Culture and Recreation |
| Created | 2016-05-23T23:53:24Z |
| Publication Date | 2016-05-25T23:29:28Z |

## Description

Donations to the San Francisco Recreation & Parks Department

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | time           | close_date   | Close Date   | calendar_date | calendar_date |
| Yes      | series tag     | account_name | Account Name | text          | text          |
| Yes      | series tag     | description  | Description  | text          | text          |
| Yes      | numeric metric | amount       | Amount       | money         | money         |
| Yes      | series tag     | type         | Type         | text          | text          |
```

## Time Field

```ls
Value = close_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:n5gw-x78q d:2014-07-08T00:00:00.000Z t:description="To support botanical signs at the Sunnyside Conservatory." t:type=Cash t:account_name="Glen Park Association" m:amount=500

series e:n5gw-x78q d:2014-07-09T00:00:00.000Z t:description="To support HITS tennis programming and provide tennis equipment for youth ages 10 and under." t:type=Cash t:account_name="USTA NorCAL" m:amount=2050

series e:n5gw-x78q d:2014-08-21T00:00:00.000Z t:description="To support grounds maintenance at the Walter S. Johnson Park, Palace of Fine Arts." t:type=Cash t:account_name="Walter S. Johnson Foundation" m:amount=5000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:n5gw-x78q l:"Donations to Recreation and Parks Department" t:attribution="San Francisco Recreation & Parks Department" t:url=https://data.sfgov.org/api/views/n5gw-x78q

property e:n5gw-x78q t:meta.view v:id=n5gw-x78q v:category="Culture and Recreation" v:attributionLink=http://sfrecpark.org/ v:averageRating=0 v:name="Donations to Recreation and Parks Department" v:attribution="San Francisco Recreation & Parks Department"

property e:n5gw-x78q t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:n5gw-x78q t:meta.view.owner v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:displayName="Eric Pawlowsky"

property e:n5gw-x78q t:meta.view.tableauthor v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:roleName=editor v:displayName="Eric Pawlowsky"
```

## Top Records

```ls
| close_date          | account_name                        | description                                                                                                                                                                                                                               | amount   | type    | 
| =================== | =================================== | ========================================================================================================================================================================================================================================= | ======== | ======= | 
| 2014-07-08T00:00:00 | Glen Park Association               | To support botanical signs at the Sunnyside Conservatory.                                                                                                                                                                                 | 500.00   | Cash    | 
| 2014-07-09T00:00:00 | USTA NorCAL                         | To support HITS tennis programming and provide tennis equipment for youth ages 10 and under.                                                                                                                                              | 2050.00  | Cash    | 
| 2014-08-21T00:00:00 | Walter S. Johnson Foundation        | To support grounds maintenance at the Walter S. Johnson Park, Palace of Fine Arts.                                                                                                                                                        | 5000.00  | Cash    | 
| 2014-09-04T00:00:00 | Kaiser Permanente                   | To support the Golden Gate Park Senior Center garden.                                                                                                                                                                                     | 1000.00  | Cash    | 
| 2014-09-08T00:00:00 | San Francisco Parks Alliance (SFPA) | To support landscape improvements to Kezar Triangle in Golden Gate Park. This project is generously funded and supported by the Friends of Kezar Triangle and the Carla and David Crane Foundation.                                       | 1732.08  | Cash    | 
| 2014-09-19T00:00:00 | National Fitness Campaign           | Repairs to the Marina Green Fitness Court.                                                                                                                                                                                                | 10000.00 | In-kind | 
| 2014-09-24T00:00:00 | Salesforce                          | To provide RPD with a salesforce.com database system.                                                                                                                                                                                     | 15000.00 | In-kind | 
| 2014-10-09T00:00:00 | San Francisco Parks Alliance (SFPA) | To support a Community Opportunity Fund capital improvement project to repair and upgrade Lawn Bowling Green #1. San Francisco Lawn Bowling Club generously supported this fundraising effort.                                            | 16626.00 | Cash    | 
| 2014-10-09T00:00:00 | San Francisco Parks Alliance (SFPA) | To support a Community Opportunity Fund capital improvement project to improve and beautify the Lincoln Park steps and benches. Friends of Lincoln Park generously supported this fundraising effort.                                     | 5000.00  | Cash    | 
| 2014-10-10T00:00:00 | People of Parkside Sunset (POPS)    | To support an electrical upgrade project in McCoppin Square Park. This project was generously funded by a grant from Office of Economic Workforce Development, Invest in Neighborhood Initiative to the People of Parkside Sunset (POPS). | 14985.00 | In-kind | 
```