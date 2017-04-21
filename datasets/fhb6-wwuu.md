# FOIA Request Log - Ethics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-ethics-5bba2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fhb6-wwuu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fhb6-wwuu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fhb6-wwuu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fhb6-wwuu |
| Name | FOIA Request Log - Ethics |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-26T16:00:15Z |
| Publication Date | 2017-03-24T16:51:47Z |

## Description

FOIA requests received by Ethics as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name                                               | Name                                                       | Data Type     | Render Type   |
| ======== | =========== | ======================================================== | ========================================================== | ============= | ============= |
| Yes      | series tag  | requestor_name                                           | REQUESTOR NAME                                             | text          | text          |
| Yes      | series tag  | organization                                             | ORGANIZATION                                               | text          | text          |
| Yes      | time        | date_received                                            | DATE RECEIVED                                              | calendar_date | calendar_date |
| No       |             | due_date                                                 | DUE DATE                                                   | calendar_date | calendar_date |
| Yes      | series tag  | description_of_request_statements_of_financial_interests | DESCRIPTION OF REQUEST - STATEMENTS OF FINANCIAL INTERESTS | text          | text          |
| Yes      | series tag  | description_of_request_lobbyists_filings                 | DESCRIPTION OF REQUEST - LOBBYISTS FILINGS                 | text          | text          |
| Yes      | series tag  | description_of_request_other                             | DESCRIPTION OF REQUEST - OTHER                             | text          | text          |
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
series e:fhb6-wwuu d:2010-05-07T00:00:00.000Z t:organization="Illinois Gaming Board" t:requestor_name="A. Jones" t:description_of_request_lobbyists_filings="J. Montgomery Sr. 2003-10 available" m:row_number.fhb6-wwuu=1

series e:fhb6-wwuu d:2010-05-12T00:00:00.000Z t:description_of_request_statements_of_financial_interests="Dennis Redmond all forms; all available" t:organization=Tribune t:requestor_name="J. Chase" m:row_number.fhb6-wwuu=2

series e:fhb6-wwuu d:2010-05-18T00:00:00.000Z t:description_of_request_statements_of_financial_interests="Richard Rodriguez 2006-09 all available; John Vasilj 2006-09 none available" t:organization="Carpenters Local Union #58" t:requestor_name="Ian Main" m:row_number.fhb6-wwuu=3
```

## Meta Commands

```ls
metric m:row_number.fhb6-wwuu p:long l:"Row Number"

entity e:fhb6-wwuu l:"FOIA Request Log - Ethics" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/fhb6-wwuu

property e:fhb6-wwuu t:meta.view v:id=fhb6-wwuu v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Ethics" v:attribution="City of Chicago"

property e:fhb6-wwuu t:meta.view.owner v:id=3jms-nzc3 v:profileImageUrlMedium=/api/users/3jms-nzc3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3jms-nzc3/profile_images/LARGE v:screenName=ethicsfoia v:profileImageUrlSmall=/api/users/3jms-nzc3/profile_images/TINY v:displayName=ethicsfoia

property e:fhb6-wwuu t:meta.view.tableauthor v:id=3jms-nzc3 v:profileImageUrlMedium=/api/users/3jms-nzc3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3jms-nzc3/profile_images/LARGE v:screenName=ethicsfoia v:profileImageUrlSmall=/api/users/3jms-nzc3/profile_images/TINY v:roleName=editor v:displayName=ethicsfoia
```

## Top Records

```ls
| requestor_name | organization               | date_received       | due_date            | description_of_request_statements_of_financial_interests                    | description_of_request_lobbyists_filings                                                                                                                                              | description_of_request_other                     | 
| ============== | ========================== | =================== | =================== | =========================================================================== | ===================================================================================================================================================================================== | ================================================ | 
| A. Jones       | Illinois Gaming Board      | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 |                                                                             | J. Montgomery Sr. 2003-10 available                                                                                                                                                   |                                                  | 
| J. Chase       | Tribune                    | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | Dennis Redmond all forms; all available                                     |                                                                                                                                                                                       |                                                  | 
| Ian Main       | Carpenters Local Union #58 | 2010-05-18T00:00:00 | 2010-05-25T00:00:00 | Richard Rodriguez 2006-09 all available; John Vasilj 2006-09 none available |                                                                                                                                                                                       |                                                  | 
| Merema         |                            | 2010-06-01T00:00:00 | 2010-06-08T00:00:00 |                                                                             | Laube 2009-2010 all were available, and provided                                                                                                                                      |                                                  | 
| T. Novak       | Sun Times                  | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 |                                                                             | All lobbyists for Higgins Development 6 files available and provided; Walsh-Higgins none available; Fred Latsko- Structure Management 1 available and produced; John George 2003-6    |                                                  | 
| T. Novak       | Sun Times                  | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 |                                                                             | All lobbyists for Higgins Development 6 files available and provided; Walsh-Higgins none available; Fred Latsko- Structure Management 1 available and produced; Altheimer & Gray 2003 |                                                  | 
| T. Novak       | Sun Times                  | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 |                                                                             | All lobbyists for Higgins Development 6 files available and provided; Walsh-Higgins none available; Fred Latsko- Structure Management 1 available and produced; James Banks 2009      |                                                  | 
| T. Novak       | Sun Times                  | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 |                                                                             | All lobbyists for Higgins Development 6 files available and provided; Walsh-Higgins none available; Fred Latsko- Structure Management 1 available and produced; Dennis Austik 2006    |                                                  | 
| J. Sabel       | ETS Environmental          | 2010-06-07T00:00:00 | 2010-06-14T00:00:00 |                                                                             |                                                                                                                                                                                       | environmental records re Faith Tabernacle Church | 
| T. Novak       | Sun Times                  | 2010-06-08T00:00:00 | 2010-06-15T00:00:00 |                                                                             | E. Kruse 2007-9 all available, produced re Structured Dev.; Lake & Waller                                                                                                             |                                                  | 
```