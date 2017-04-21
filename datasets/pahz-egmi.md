# Lobbyist Data - Lobbying Activity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbying-activity) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pahz-egmi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pahz-egmi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pahz-egmi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pahz-egmi |
| Name | Lobbyist Data - Lobbying Activity |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-08T21:29:28Z |
| Publication Date | 2015-10-20T22:02:52Z |

## Description

List of each City agency lobbied, whether it involved legislative or administrative action (or both) and a brief description of the action promoted or opposed, as reported by registered lobbyists. See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | lobbying_activity_id    | LOBBYING_ACTIVITY_ID    | text          | number        |
| Yes      | time        | period_start            | PERIOD_START            | calendar_date | calendar_date |
| No       |             | period_end              | PERIOD_END              | calendar_date | calendar_date |
| Yes      | series tag  | action                  | ACTION                  | text          | text          |
| Yes      | series tag  | action_sought           | ACTION_SOUGHT           | text          | text          |
| Yes      | series tag  | department              | DEPARTMENT              | text          | text          |
| Yes      | series tag  | client_id               | CLIENT_ID               | text          | number        |
| Yes      | series tag  | client_name             | CLIENT_NAME             | text          | text          |
| Yes      | series tag  | lobbyist_id             | LOBBYIST_ID             | text          | number        |
| Yes      | series tag  | lobbyist_first_name     | LOBBYIST_FIRST_NAME     | text          | text          |
| Yes      | series tag  | lobbyist_middle_initial | LOBBYIST_MIDDLE_INITIAL | text          | text          |
| Yes      | series tag  | lobbyist_last_name      | LOBBYIST_LAST_NAME      | text          | text          |
| No       |             | created_date            | CREATED_DATE            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_end,created_date
```

## Data Commands

```ls
series e:pahz-egmi d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Richard t:lobbyist_id=5860 t:department="MAYORS OFFICE" t:lobbying_activity_id=46 t:action=Administrative t:client_id=12550 t:action_sought="Building Maintenance and Construction issues at 205 E. Randolph Dr." t:lobbyist_last_name=Ingram t:client_name="Music and Dance Theater Chicago" t:lobbyist_middle_initial=L m:row_number.pahz-egmi=1

series e:pahz-egmi d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Richard t:lobbyist_id=5860 t:department="HOUSING AND ECONOMIC DEVELOPMENT" t:lobbying_activity_id=54 t:action=Administrative t:client_id=12553 t:action_sought="MetraMarket Redevelopment Agreement" t:lobbyist_last_name=Ingram t:client_name="U.S. Equities Realty LLC" t:lobbyist_middle_initial=L m:row_number.pahz-egmi=2

series e:pahz-egmi d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Adrienne t:lobbyist_id=5982 t:department="CITY COUNCIL / ALDERMEN" t:lobbying_activity_id=64 t:action="Both (Administrative and Legislative)" t:client_id=12815 t:action_sought="opposition to changes in CPL hours, page layoffs" t:lobbyist_last_name=Alexander t:client_name="AFSCME Council 31" t:lobbyist_middle_initial=M m:row_number.pahz-egmi=3
```

## Meta Commands

```ls
metric m:row_number.pahz-egmi p:long l:"Row Number"

entity e:pahz-egmi l:"Lobbyist Data - Lobbying Activity" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/pahz-egmi

property e:pahz-egmi t:meta.view v:id=pahz-egmi v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbying Activity" v:attribution="City of Chicago"

property e:pahz-egmi t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:pahz-egmi t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| lobbying_activity_id | period_start        | period_end          | action                                | action_sought                                                       | department                       | client_id | client_name                     | lobbyist_id | lobbyist_first_name | lobbyist_middle_initial | lobbyist_last_name | created_date        | 
| ==================== | =================== | =================== | ===================================== | =================================================================== | ================================ | ========= | =============================== | =========== | =================== | ======================= | ================== | =================== | 
| 46                   | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Administrative                        | Building Maintenance and Construction issues at 205 E. Randolph Dr. | MAYORS OFFICE                    | 12550     | Music and Dance Theater Chicago | 5860        | Richard             | L                       | Ingram             | 2012-08-02T00:00:00 | 
| 54                   | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Administrative                        | MetraMarket Redevelopment Agreement                                 | HOUSING AND ECONOMIC DEVELOPMENT | 12553     | U.S. Equities Realty LLC        | 5860        | Richard             | L                       | Ingram             | 2012-08-02T00:00:00 | 
| 64                   | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | opposition to changes in CPL hours, page layoffs                    | CITY COUNCIL / ALDERMEN          | 12815     | AFSCME Council 31               | 5982        | Adrienne            | M                       | Alexander          | 2012-08-03T00:00:00 | 
| 234                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Administrative                        | Housing / Banking Issues                                            | BUILDINGS                        | 13107     | JP Morgan Chase                 | 6123        | Amy                 | S                       | Brennan            | 2012-08-06T00:00:00 | 
| 247                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | Discussed a pilot program regarding self inspections of restaurants | HEALTH DEPARTMENT                | 12226     | Illinois Restaurant Association | 5737        | Mary Kay            |                         | Bonoma             | 2012-08-06T00:00:00 | 
| 248                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | Discussed a pilot program regarding self inspections of restaurants | MAYORS OFFICE                    | 12226     | Illinois Restaurant Association | 5737        | Mary Kay            |                         | Bonoma             | 2012-08-06T00:00:00 | 
| 343                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | inculding Planned Dev. Minor Changes and Part II approvals.         | BUDGET AND MANAGEMENT            | 12565     | Target Corporation              | 6972        | Danielle            |                         | Cassel             | 2012-08-07T00:00:00 | 
| 104                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | zoning, Planned Development, Condemnation re: 73rd & Universit      | PLANNING COMMISSION              | 11794     | RCHD, LLC                       | 7094        | Lenny               | D                       | Asaro              | 2012-08-03T00:00:00 | 
| 105                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Both (Administrative and Legislative) | zoning, Planned Development, Condemnation re: 73rd & Universit      | LAW DEPARTMENT                   | 11794     | RCHD, LLC                       | 7094        | Lenny               | D                       | Asaro              | 2012-08-03T00:00:00 | 
| 188                  | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | Administrative                        | Potential energy monitoring pilot project for CPS                   | CHICAGO PUBLIC SCHOOLS           | 11822     | Learn Green LLC                 | 5601        | Myles               | D                       | Berman             | 2012-08-06T00:00:00 | 
```