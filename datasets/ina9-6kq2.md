# Lobbyist Data - Historical - Lobbyist Compensation Report - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-compensation-report-2010-ef49d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ina9-6kq2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ina9-6kq2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ina9-6kq2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ina9-6kq2 |
| Name | Lobbyist Data - Historical - Lobbyist Compensation Report - 2010 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-06-07T17:01:07Z |
| Publication Date | 2011-06-07T17:01:07Z |

## Description

The lobbyist compensation report is part of the Lobbyist Activity Report, a notarized disclosure that lobbyists were required to file twice during 2010 (January 20th and July 20th).
Lobbyists were required to report all lobbying related compensation received during each reporting period, rounded to the nearest $1,000 on Form C Part 3 Section G (http://bit.ly/q2lRTh).
In 2010, all lobbyist compensation reports are submitted to the Board of Ethics in paper form and are available in their entirety in the Board's offices.  Data for the 2010 reporting period is limited because previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings.  
Data Owner:  Board of Ethics 
[http://j.mp/mbH9BN] /
Time Period: January 1, 2010 to December 31, 2010 / 
Related Applications:  Registered Lobbyist List [http://j.mp/l8LwAq ]

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST LAST NAME      | text      | text        |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST FIRST NAME     | text      | text        |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
| Yes      | series tag     | client                  | CLIENT                  | text      | text        |
| Yes      | numeric metric | compensation            | COMPENSATION            | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ina9-6kq2 d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:client="Diageo NA" t:lobbyist_last_name=Abbinante t:lobbyist_middle_initial=B m:compensation=3000

series e:ina9-6kq2 d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:client="Diageo NA" t:lobbyist_last_name=Abbinante t:lobbyist_middle_initial=B m:compensation=3000

series e:ina9-6kq2 d:2010-01-01T00:00:00.000Z t:lobbyist_first_name=Anthony t:client="108 West Germania Place, LLC" t:lobbyist_last_name=Abboud t:lobbyist_middle_initial=L m:compensation=0
```

## Meta Commands

```ls
metric m:compensation p:integer l:COMPENSATION t:dataTypeName=money

entity e:ina9-6kq2 l:"Lobbyist Data - Historical - Lobbyist Compensation Report - 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ina9-6kq2

property e:ina9-6kq2 t:meta.view v:id=ina9-6kq2 v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Compensation Report - 2010" v:attribution="City of Chicago"

property e:ina9-6kq2 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ina9-6kq2 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | client                       | compensation | 
| ================== | =================== | ======================= | ============================ | ============ | 
| Abbinante          | Anthony             | B                       | Diageo NA                    | 3000         | 
| Abbinante          | Anthony             | B                       | Diageo NA                    | 3000         | 
| Abboud             | Anthony             | L                       | 108 West Germania Place, LLC | 0            | 
| Abboud             | Anthony             | L                       | 108 West Germania Place, LLC | 0            | 
| Abboud             | Anthony             | L                       | Tracfone Wireless, Inc       | 0            | 
| Abboud             | Anthony             | L                       | 108 West Germania Place, LLC | 6000         | 
| Acosta             | Rolando             | R                       | Logan Square Kitchen         | 1000         | 
| Acosta             | Rolando             | R                       | East Lake/West End, LLC      | 17000        | 
| Acosta             | Rolando             | R                       | East Lake/West End, LLC      | 15000        | 
| Acosta             | Rolando             | R                       | Lazo's Tacos Inc             | 1000         | 
```