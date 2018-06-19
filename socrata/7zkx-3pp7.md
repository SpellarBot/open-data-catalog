# FOIA Request Log - Human Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-human-resources-081f3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7zkx-3pp7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7zkx-3pp7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7zkx-3pp7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7zkx-3pp7 |
| Name | FOIA Request Log - Human Resources |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T18:49:53Z |
| Publication Date | 2015-06-12T21:57:18Z |

## Description

FOIA requests received by Human Resources as of May 1, 2010

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
series e:7zkx-3pp7 d:2010-05-04T00:00:00.000Z t:description_of_request="Information on job opportunities for her father" t:organization=Self t:requestor_name="Maria (no last name given)" m:row_number.7zkx-3pp7=1

series e:7zkx-3pp7 d:2010-05-04T00:00:00.000Z t:description_of_request="Time sheets for City Treasurer employees from 01/01/1998 to 12/31/1998" t:organization=Self t:requestor_name="Victor Crown" m:row_number.7zkx-3pp7=2

series e:7zkx-3pp7 d:2010-05-07T00:00:00.000Z t:description_of_request="Employment verification" t:organization="Cole Taylor Mortgage" t:requestor_name="Peggy Atwell" m:row_number.7zkx-3pp7=3
```

## Meta Commands

```ls
metric m:row_number.7zkx-3pp7 p:long l:"Row Number"

entity e:7zkx-3pp7 l:"FOIA Request Log - Human Resources" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7zkx-3pp7

property e:7zkx-3pp7 t:meta.view v:id=7zkx-3pp7 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Human Resources" v:attribution="City of Chicago"

property e:7zkx-3pp7 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:7zkx-3pp7 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name             | organization         | description_of_request                                                                                                                                                                                                                                          | date_received       | due_date            | 
| ========================== | ==================== | =============================================================================================================================================================================================================================================================== | =================== | =================== | 
| Maria (no last name given) | Self                 | Information on job opportunities for her father                                                                                                                                                                                                                 | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Victor Crown               | Self                 | Time sheets for City Treasurer employees from 01/01/1998 to 12/31/1998                                                                                                                                                                                          | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Peggy Atwell               | Cole Taylor Mortgage | Employment verification                                                                                                                                                                                                                                         | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Kevin Prendergast          | Self                 | Own work history                                                                                                                                                                                                                                                | 2010-05-10T00:00:00 | 2010-05-17T00:00:00 | 
| Don Vance                  | Self                 | Full names and badge numbers for all active duty CPD officers, detectives, and inspectors; personnel classified as law enforcement officers; personnel under contract to perform law enforcement functions; sworn personnel with authority to arrest and detain | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Don Vance                  | Self                 | ACLU MCD and Injunction 2 signed proof of service certification from T. Doherty; T. McDarrah; S. Collier; R. Rockwell; C.Walker; B. Washington; B. Randozzo from 2001 to 2008                                                                                   | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Pam Merema                 | Self                 | Work history for a City of Chicago employee; TIF related studies                                                                                                                                                                                                | 2010-05-14T00:00:00 | 2010-05-21T00:00:00 | 
| Geoff Dougherty            | Chicago Current      | Employee database for 2009 & 2010; overtime or other monies paid in addition to salary for 2009 & 2010                                                                                                                                                          | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Pam Merema                 | Self                 | Employee file for a City of Chicago employee                                                                                                                                                                                                                    | 2010-05-18T00:00:00 | 2010-05-25T00:00:00 | 
| Eric Gatewood              | Self                 | Copies of test scores from CPD's 1993 exam and list of candidates hired.                                                                                                                                                                                        | 2010-05-20T00:00:00 | 2010-05-27T00:00:00 | 
```