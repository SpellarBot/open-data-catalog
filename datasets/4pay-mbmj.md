# Lobbyist Data - Lobbyist Agency Report (Deprecated October 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-agency-report-fe0a3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4pay-mbmj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4pay-mbmj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4pay-mbmj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4pay-mbmj |
| Name | Lobbyist Data - Lobbyist Agency Report (Deprecated October 2015) |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, ethics, deprecated |
| Created | 2011-09-30T08:01:31Z |
| Publication Date | 2016-12-06T10:31:18Z |

## Description

OUTDATED. See similar current data at https://data.cityofchicago.org/d/pahz-egmi -- The lobbyist agency report is part of the Lobbyist Activity Report, a notarized disclosure that must be filed twice each year (January 20th and July 20th). Lobbyists must report the name of each City agency lobbied and report whether lobbying involved legislative or administrative action, and give a brief description of the legislative or administrative action promoted or opposed. All lobbyist agency reports are submitted to the Board of Ethics in paper form and are available in their entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. / Data Owner: Board of Ethics [http://j.mp/mbH9BN] / Time Period: January 1, 2011 to present / Frequency: Data is updated daily  / Related Applications: Registered Lobbyist List [http://bit.ly/FOctNY]

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | filing_year             | FILING YEAR             | number    | number      |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST LAST NAME      | text      | text        |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST FIRST NAME     | text      | text        |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
| Yes      | series tag     | agency_name             | AGENCY NAME             | text      | text        |
| Yes      | numeric metric | admin_action            | ADMIN ACTION            | number    | text        |
| Yes      | numeric metric | legislative_action      | LEGISLATIVE ACTION      | number    | text        |
| Yes      | series tag     | action_sought           | ACTION SOUGHT           | text      | text        |
| Yes      | series tag     | client                  | CLIENT                  | text      | text        |
| Yes      | numeric metric | filing_period           | FILING PERIOD           | number    | text        |
```

## Time Field

```ls
Value = filing_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4pay-mbmj d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=Rolando t:client="Lake Loomis LLC" t:action_sought="vacation of alley at Lake, Ogden, Loomis" t:agency_name="CITY COUNCIL" t:lobbyist_last_name=Acosta t:lobbyist_middle_initial=R m:legislative_action=1 m:admin_action=0 m:filing_period=1

series e:4pay-mbmj d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=Rolando t:client="Lake Loomis LLC" t:action_sought="vacation of alley at Lake, Ogden, Loomis" t:agency_name="DEPT OF LAW" t:lobbyist_last_name=Acosta t:lobbyist_middle_initial=R m:legislative_action=1 m:admin_action=0 m:filing_period=1

series e:4pay-mbmj d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=Rolando t:client="Elston Center, LLC" t:action_sought="admin. amendment to 5353 N. Elston PD" t:agency_name="DEPT OF HOUSING" t:lobbyist_last_name=Acosta t:lobbyist_middle_initial=R m:legislative_action=0 m:admin_action=1 m:filing_period=1
```

## Meta Commands

```ls
metric m:admin_action p:integer l:"ADMIN ACTION" t:dataTypeName=number

metric m:legislative_action p:integer l:"LEGISLATIVE ACTION" t:dataTypeName=number

metric m:filing_period p:integer l:"FILING PERIOD" t:dataTypeName=number

entity e:4pay-mbmj l:"Lobbyist Data - Lobbyist Agency Report (Deprecated October 2015)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/4pay-mbmj

property e:4pay-mbmj t:meta.view v:id=4pay-mbmj v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyist Agency Report (Deprecated October 2015)" v:attribution="City of Chicago"

property e:4pay-mbmj t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:4pay-mbmj t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | agency_name     | admin_action | legislative_action | action_sought                                | client                   | filing_period | 
| =========== | ================== | =================== | ======================= | =============== | ============ | ================== | ============================================ | ======================== | ============= | 
| 2011        | Acosta             | Rolando             | R                       | CITY COUNCIL    | 0            | 1                  | vacation of alley at Lake, Ogden, Loomis     | Lake Loomis LLC          | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF LAW     | 0            | 1                  | vacation of alley at Lake, Ogden, Loomis     | Lake Loomis LLC          | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF HOUSING | 1            | 0                  | admin. amendment to 5353 N. Elston PD        | Elston Center, LLC       | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF HOUSING | 0            | 1                  | Sale of property - Cermak & Grove St.        | CORU 465 LLC             | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF LAW     | 0            | 1                  | releast of covenant on property 18th & Canal | Wabash Development Group | 1             | 
| 2011        | Acosta             | Rolando             | R                       | CITY COUNCIL    | 0            | 1                  | releast of covenant on property 18th & Canal | Wabash Development Group | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF HOUSING | 0            | 1                  | releast of covenant on property 18th & Canal | Wabash Development Group | 1             | 
| 2011        | Acosta             | Rolando             | R                       | CITY COUNCIL    | 0            | 1                  | TIF assistance for Logan Theater             | M. Fishman & Co          | 1             | 
| 2011        | Acosta             | Rolando             | R                       | DEPT OF HOUSING | 0            | 1                  | TIF assistance for Logan Theater             | M. Fishman & Co          | 1             | 
| 2011        | Acosta             | Rolando             | R                       | CITY COUNCIL    | 0            | 1                  | sale of propety - 2130 S. Canal              | Lawrence Fisheries       | 1             | 
```