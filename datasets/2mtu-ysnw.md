# Lobbyist Data - Historical - Lobbyist Termination Report - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-termination-report-2010-e6558) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2mtu-ysnw) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2mtu-ysnw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2mtu-ysnw/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2mtu-ysnw |
| Name | Lobbyist Data - Historical - Lobbyist Termination Report - 2010 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-06-07T17:46:06Z |
| Publication Date | 2011-06-07T17:46:06Z |

## Description

All lobbyist termination fillings submitted to the Board of Ethics and electronically transcribed by Board of Ethics employees during the 2010 reporting period. / 
When a lobbyist terminates all activity that requires registration, the lobbyist must file a termination notice and a final activity report that covers the period between the most recently filed activity report and the date of termination.
Data for the 2010 reporting period is limited because previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings. /  
Data Owner:  Board of Ethics 
[http://j.mp/mbH9BN] /
Time Period: January 1, 2010 to December 31, 2010 /
Related Applications:  Registered Lobbyist List [http://j.mp/l8LwAq], 
2011 Lobbyist Termination Report
[http://j.mp/kT56zH]

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | lobbyist_last_name  | LOBBYIST LAST NAME  | text          | text          |
| Yes      | series tag  | lobbyist_first_name | LOBBYIST FIRST NAME | text          | text          |
| Yes      | time        | termination_date    | TERMINATION DATE    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = termination_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2mtu-ysnw d:2010-01-22T00:00:00.000Z t:lobbyist_first_name=Anthony t:lobbyist_last_name=Aiello m:row_number.2mtu-ysnw=1

series e:2mtu-ysnw d:2010-02-11T00:00:00.000Z t:lobbyist_first_name=Michael t:lobbyist_last_name=Alexander m:row_number.2mtu-ysnw=2

series e:2mtu-ysnw d:2010-01-07T00:00:00.000Z t:lobbyist_first_name=Mary t:lobbyist_last_name=Ammermann m:row_number.2mtu-ysnw=3
```

## Meta Commands

```ls
metric m:row_number.2mtu-ysnw p:long l:"Row Number"

entity e:2mtu-ysnw l:"Lobbyist Data - Historical - Lobbyist Termination Report - 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2mtu-ysnw

property e:2mtu-ysnw t:meta.view v:id=2mtu-ysnw v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Termination Report - 2010" v:attribution="City of Chicago"

property e:2mtu-ysnw t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:2mtu-ysnw t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| lobbyist_last_name | lobbyist_first_name | termination_date    | 
| ================== | =================== | =================== | 
| Aiello             | Anthony             | 2010-01-22T00:00:00 | 
| Alexander          | Michael             | 2010-02-11T00:00:00 | 
| Ammermann          | Mary                | 2010-01-07T00:00:00 | 
| Anderson           | Bridget             | 2010-07-30T00:00:00 | 
| Asmar              | Christian           | 2010-07-15T00:00:00 | 
| Balcer             | Jerome              | 2010-03-08T00:00:00 | 
| Barbe              | Jana                | 2010-01-22T00:00:00 | 
| Barnett            | Cornell             | 2010-11-10T00:00:00 | 
| Bell               | M'Lou               | 2010-01-12T00:00:00 | 
| Benway             | Allison             | 2010-01-26T00:00:00 | 
```