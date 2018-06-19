# FOIA Request Log - Chicago Treasurer's Office

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-chicago-treasurers-office-8c63a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8gyi-fawp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8gyi-fawp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8gyi-fawp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8gyi-fawp |
| Name | FOIA Request Log - Chicago Treasurer's Office |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-30T15:58:40Z |
| Publication Date | 2015-01-12T18:39:58Z |

## Description

FOIA requests received by the Chicago Treasurer's Office as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:8gyi-fawp d:2010-05-12T00:00:00.000Z t:description_of_request="Seeking all records for travel and expenses for City Treasurer Police detail." t:organization="Chicago Sun Times" t:requestor_name="Chris Fusco" m:row_number.8gyi-fawp=1

series e:8gyi-fawp d:2010-05-27T00:00:00.000Z t:description_of_request="Looking for refund for overpayment on property taxes in the amount of $1, 049.79." t:organization=Person t:requestor_name="Sharon Wheaton" m:row_number.8gyi-fawp=2

series e:8gyi-fawp d:2010-06-15T00:00:00.000Z t:description_of_request="Regarding Municipal Depositories and various transaction details." t:organization="Chicago Sun Times" t:requestor_name="Tim Novak" m:row_number.8gyi-fawp=3
```

## Meta Commands

```ls
metric m:row_number.8gyi-fawp p:long l:"Row Number"

entity e:8gyi-fawp l:"FOIA Request Log - Chicago Treasurer's Office" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8gyi-fawp

property e:8gyi-fawp t:meta.view v:id=8gyi-fawp v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Chicago Treasurer's Office" v:attribution="City of Chicago"

property e:8gyi-fawp t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:8gyi-fawp t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization      | description_of_request                                                                                                                                                                                                                                                                                                                                                                                             | date_received       | due_date            | 
| =============== | ================= | ================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Chris Fusco     | Chicago Sun Times | Seeking all records for travel and expenses for City Treasurer Police detail.                                                                                                                                                                                                                                                                                                                                      | 2010-05-12T00:00:00 | 2010-05-25T00:00:00 | 
| Sharon Wheaton  | Person            | Looking for refund for overpayment on property taxes in the amount of $1, 049.79.                                                                                                                                                                                                                                                                                                                                  | 2010-05-27T00:00:00 | 2010-06-02T00:00:00 | 
| Tim Novak       | Chicago Sun Times | Regarding Municipal Depositories and various transaction details.                                                                                                                                                                                                                                                                                                                                                  | 2010-06-15T00:00:00 | 2010-06-22T00:00:00 | 
| Tim Novak       | Chicago Sun Times | Seeking records showing any deposits the city has made with Belmont Bank & Trust since Jan. 2007.                                                                                                                                                                                                                                                                                                                  | 2010-06-29T00:00:00 | 2010-07-07T00:00:00 | 
| Beatrice Ricca  | Person            | Seeking information on claims department                                                                                                                                                                                                                                                                                                                                                                           | 2010-07-06T00:00:00 | 2010-07-07T00:00:00 | 
| Chris Fusco     | Chicago Sun Times | Seeking copies of all RFP and other documents submitted by companies/lenders/financial institutions that sought to be lending institutions in the city's Small Business Development Loan Program.                                                                                                                                                                                                                  | 2010-08-31T00:00:00 | 2010-09-08T00:00:00 | 
| Brad Austin     | Person            | Requesting records showing payee names, vendor numbers, check issue dates, check identification numbers, and dollar amount of uncashed vendor checks greater than $1000 issued in the city before Sept 1, 2009                                                                                                                                                                                                     | 2010-09-06T00:00:00 | 2010-09-13T00:00:00 | 
| Elizabeth Allen | CTO               | Requesting bank reconciliations on the S-Drive. The Bank reconciliations list the names of the banks and list the initials of the person who reconciled the account for each month of the corresponding year.                                                                                                                                                                                                      | 2010-09-23T00:00:00 | 2010-09-29T00:00:00 | 
| Ruth Abraham    | Person            | Requesting the names of all persons working within or without the office of Alderman Bernard Stone, working on behalf of alderman Bernard Stone, being paid from City of Chicago monies within the time period of May 1, 207 to the present. Names of all persons working exclusively for the 50th ward of Chicago being paid from the City of Chicago monies within the time period of May 1, 207 to the present. | 2010-10-14T00:00:00 | 2010-10-27T00:00:00 | 
| Ruth Abraham    | Person            | Requesting current balance of the accounts associated with the following Tax Increment Financing (TIF) District which are wholly or partially within the boundaries of the 50th Ward of Chicago.                                                                                                                                                                                                                   | 2010-10-14T00:00:00 | 2010-10-25T00:00:00 | 
```