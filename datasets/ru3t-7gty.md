# Lobbyist Data - Historical - Lobbyist Termination Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-termination-report-7298b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ru3t-7gty) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ru3t-7gty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ru3t-7gty/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ru3t-7gty |
| Name | Lobbyist Data - Historical - Lobbyist Termination Report |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-09-30T08:01:41Z |
| Publication Date | 2012-08-28T08:09:31Z |

## Description

All lobbyist termination fillings submitted to the Board of Ethics beginning with the 2011 reporting period. / 
When a lobbyist terminates all activity that requires registration, the lobbyist must file a termination notice and a final activity report that covers the period between the most recently filed activity report and the date of termination.
Lobbyist termination information is submitted to the Board of Ethics in paper form and is available in its entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. Previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings.
From this point forward, the Board of Ethics will electronically compile more data about lobbyists and their activities and automatically report this information online. / 
Data Owner:  Board of Ethics 
[http://j.mp/kAx6q3] /

Time Period: January 1, 2011 to present /
Frequency:  Data is updated daily /
Related Applications:  Registered Lobbyist List [http://bit.ly/FOctNY], 
2010 Lobbyist Termination Report
[http://j.mp/k3DCxW ]

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| Yes      | time        | filing_year             | FILING YEAR             | number    | number      |
| Yes      | series tag  | lobbyist_last_name      | LOBBYIST LAST NAME      | text      | text        |
| Yes      | series tag  | lobbyist_first_name     | LOBBYIST FIRST NAME     | text      | text        |
| Yes      | series tag  | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
```

## Time Field

```ls
Value = filing_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ru3t-7gty l:"Lobbyist Data - Historical - Lobbyist Termination Report" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ru3t-7gty

property e:ru3t-7gty t:meta.view v:id=ru3t-7gty v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Termination Report" v:attribution="City of Chicago"

property e:ru3t-7gty t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ru3t-7gty t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | 
| =========== | ================== | =================== | ======================= | 
| 2011        | Abbinante          | Anthony             | B                       | 
| 2011        | Adduci             | Catherine           | M                       | 
| 2011        | Ammann             | Nicholas            |                         | 
| 2011        | Anderson           | J. Edward           |                         | 
| 2011        | Archia             | Adrienne            |                         | 
| 2011        | Arnone             | Kym                 |                         | 
| 2011        | Bach               | Philip              |                         | 
| 2011        | Basehart           | Tom                 |                         | 
| 2011        | Batara             | Jeffery             | A                       | 
| 2011        | Bisaillon          | Lawrence            | R                       | 
```