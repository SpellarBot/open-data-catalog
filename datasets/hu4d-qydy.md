# Lobbyist Data - Lobbyist Compensation Report (Deprecated October 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-compensation-report-993f3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hu4d-qydy) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hu4d-qydy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hu4d-qydy/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hu4d-qydy |
| Name | Lobbyist Data - Lobbyist Compensation Report (Deprecated October 2015) |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, ethics, deprecated |
| Created | 2011-09-30T08:00:54Z |
| Publication Date | 2016-12-06T10:30:19Z |

## Description

OUTDATED. See similar current data at https://data.cityofchicago.org/d/dw2f-w78u --The lobbyist compensation report is part of the Lobbyist Activity Report, a notarized disclosure that must be filed twice each year (January 20th and July 20th). Lobbyists must report compensation any lobbying-related compensation received during each reporting period from a particular client, rounded to the nearest $1,000 on Form C Part 3 Section G (http://bit.ly/q2lRTh). Lobbyist activity reports are submitted to the Board of Ethics in paper form and are available in their entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. Previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings.  
Data Owner:  Board of Ethics 
[http://www.cityofchicago.org/city/en/depts/ethics.html] /
Time Period: January 1, 2011 to present /
Frequency: Data is updated daily /
Related Applications: http://bit.ly/FOctNY

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | filing_year             | FILING YEAR             | number    | number      |
| Yes      | series tag     | last_name               | LAST NAME               | text      | text        |
| Yes      | series tag     | first_name              | FIRST NAME              | text      | text        |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
| Yes      | series tag     | client                  | CLIENT                  | text      | text        |
| Yes      | numeric metric | compensation            | COMPENSATION            | money     | money       |
| Yes      | numeric metric | filing_period           | FILING PERIOD           | number    | text        |
```

## Time Field

```ls
Value = filing_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hu4d-qydy d:2011-01-01T00:00:00.000Z t:first_name=Anthony t:client="Diageo NA" t:last_name=Abbinante t:lobbyist_middle_initial=B m:compensation=0 m:filing_period=1

series e:hu4d-qydy d:2011-01-01T00:00:00.000Z t:first_name=Rolando t:client="M. Fishman & Co" t:last_name=Acosta t:lobbyist_middle_initial=R m:compensation=5000 m:filing_period=1

series e:hu4d-qydy d:2011-01-01T00:00:00.000Z t:first_name=Rolando t:client="Elston Center, LLC" t:last_name=Acosta t:lobbyist_middle_initial=R m:compensation=0 m:filing_period=1
```

## Meta Commands

```ls
metric m:compensation p:integer l:COMPENSATION t:dataTypeName=money

metric m:filing_period p:integer l:"FILING PERIOD" t:dataTypeName=number

entity e:hu4d-qydy l:"Lobbyist Data - Lobbyist Compensation Report (Deprecated October 2015)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hu4d-qydy

property e:hu4d-qydy t:meta.view v:id=hu4d-qydy v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyist Compensation Report (Deprecated October 2015)" v:attribution="City of Chicago"

property e:hu4d-qydy t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:hu4d-qydy t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | last_name | first_name | lobbyist_middle_initial | client                      | compensation | filing_period | 
| =========== | ========= | ========== | ======================= | =========================== | ============ | ============= | 
| 2011        | Abbinante | Anthony    | B                       | Diageo NA                   | 0            | 1             | 
| 2011        | Acosta    | Rolando    | R                       | M. Fishman & Co             | 5000         | 1             | 
| 2011        | Acosta    | Rolando    | R                       | Elston Center, LLC          | 0            | 1             | 
| 2011        | Acosta    | Rolando    | R                       | Lake Loomis LLC             | 0            | 1             | 
| 2011        | Acosta    | Rolando    | R                       | CORU 465 LLC                | 0            | 1             | 
| 2011        | Acosta    | Rolando    | R                       | Lawrence Fisheries          | 0            | 1             | 
| 2011        | Acosta    | Rolando    | R                       | Wabash Development Group    | 5000         | 1             | 
| 2011        | Aldrete   | Sylvia     |                         | AT&T Illinois               | 0            | 1             | 
| 2011        | Anderson  | Jane       | F                       | Yellow Services, Inc        | 1000         | 1             | 
| 2011        | Archia    | Adrienne   |                         | Rice Financial Products Co. | 0            | 1             | 
```