# Lobbyist Data - Historical - Lobbyist Agency Report - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-agency-report-2010-70839) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2g5r-pikx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2g5r-pikx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2g5r-pikx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2g5r-pikx |
| Name | Lobbyist Data - Historical - Lobbyist Agency Report - 2010 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-06-07T16:57:26Z |
| Publication Date | 2011-06-07T16:57:26Z |

## Description

The lobbyist agency report is part of the Lobbyist Activity Report, a notarized disclosure that lobbyists were required to file twice during 2010 (January 20th and July 20th).
Lobbyists were required to report the name of each City agency lobbied and report whether lobbying involved legislative or administrative action, and give a brief description of the legislative or administrative action promoted or opposed.
Data for the 2010 reporting period is limited because previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings. 
Data Owner:  Board of Ethics 
[http://j.mp/mbH9BN] /
Time Period: January 1, 2010 to December 31, 2010 / 
Related Applications:  Registered Lobbyist List [http://j.mp/l8LwAq]

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST LAST NAME      | text      | text        |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST FIRST NAME     | text      | text        |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
| Yes      | series tag     | agency_name             | AGENCY NAME             | text      | text        |
| Yes      | numeric metric | admin_action            | ADMIN ACTION            | number    | text        |
| Yes      | numeric metric | legislative_action      | LEGISLATIVE ACTION      | number    | text        |
| Yes      | series tag     | action_sought           | ACTION SOUGHT           | text      | text        |
| Yes      | series tag     | client_name             | CLIENT NAME             | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2g5r-pikx d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:action_sought="permit review" t:agency_name="DEPT OF ZONING AND LAND USE POLICY" t:client_name="108 West Germania Place, LLC" t:lobbyist_last_name=Abboud t:lobbyist_middle_initial=L m:legislative_action=0 m:admin_action=1

series e:2g5r-pikx d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:action_sought="permit review" t:agency_name="CITY COUNCIL" t:client_name="108 West Germania Place, LLC" t:lobbyist_last_name=Abboud t:lobbyist_middle_initial=L m:legislative_action=0 m:admin_action=1

series e:2g5r-pikx d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:action_sought=landmark t:agency_name="DEPT OF ZONING AND LAND USE POLICY" t:client_name="108 West Germania Place, LLC" t:lobbyist_last_name=Abboud t:lobbyist_middle_initial=L m:legislative_action=0 m:admin_action=1
```

## Meta Commands

```ls
metric m:admin_action p:integer l:"ADMIN ACTION" t:dataTypeName=number

metric m:legislative_action p:integer l:"LEGISLATIVE ACTION" t:dataTypeName=number

entity e:2g5r-pikx l:"Lobbyist Data - Historical - Lobbyist Agency Report - 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2g5r-pikx

property e:2g5r-pikx t:meta.view v:id=2g5r-pikx v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Agency Report - 2010" v:attribution="City of Chicago"

property e:2g5r-pikx t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:2g5r-pikx t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | agency_name                        | admin_action | legislative_action | action_sought | client_name                  | 
| ================== | =================== | ======================= | ================================== | ============ | ================== | ============= | ============================ | 
| Abboud             | Anthony             | L                       | DEPT OF ZONING AND LAND USE POLICY | 1            | 0                  | permit review | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | CITY COUNCIL                       | 1            | 0                  | permit review | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | DEPT OF ZONING AND LAND USE POLICY | 1            | 0                  | landmark      | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | CITY COUNCIL                       | 0            | 1                  | landmark      | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | CITY COUNCIL                       | 1            | 0                  | landmark      | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | DEPT OF REVENUE                    | 1            | 1                  | 911 fees      | Tracfone Wireless, Inc       | 
| Abboud             | Anthony             | L                       | DEPT OF ZONING AND LAND USE POLICY | 1            | 0                  | landmark      | 108 West Germania Place, LLC | 
| Abboud             | Anthony             | L                       | CITY COUNCIL                       | 1            | 1                  | 911 fees      | Tracfone Wireless, Inc       | 
| Abboud             | Anthony             | L                       | COMMITTEE ON FINANCE               | 1            | 1                  | 911 fees      | Tracfone Wireless, Inc       | 
| Abboud             | Anthony             | L                       | DEPT OF LAW                        | 1            | 1                  | 911 fees      | Tracfone Wireless, Inc       | 
```