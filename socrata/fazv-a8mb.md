# FOIA Request Log - Mayor's Office for People with Disabilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-mayors-office-for-people-with-disabilities-4e48d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fazv-a8mb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fazv-a8mb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fazv-a8mb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fazv-a8mb |
| Name | FOIA Request Log - Mayor's Office for People with Disabilities |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T16:26:01Z |
| Publication Date | 2013-04-11T20:32:45Z |

## Description

FOIA requests received by the Mayor's Office for People with Disabilities as of May 1, 2010

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
series e:fazv-a8mb d:2012-07-12T19:47:00.000Z t:description_of_request="FOIA request numbers" t:organization=Self t:requestor_name="Bret Angelos" m:row_number.fazv-a8mb=1

series e:fazv-a8mb d:2012-02-14T00:00:00.000Z t:description_of_request="Information regarding Accessible Parking Permit 55332" t:organization="Curcio Law Offices" t:requestor_name="John O'Meara" m:row_number.fazv-a8mb=2

series e:fazv-a8mb d:2012-02-21T00:00:00.000Z t:description_of_request="Information regarding 4646-4658 South Drexel Blvd." t:organization="Charles R. Gryll, Ltd." t:requestor_name="Bryan Gryll" m:row_number.fazv-a8mb=3
```

## Meta Commands

```ls
metric m:row_number.fazv-a8mb p:long l:"Row Number"

entity e:fazv-a8mb l:"FOIA Request Log - Mayor's Office for People with Disabilities" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/fazv-a8mb

property e:fazv-a8mb t:meta.view v:id=fazv-a8mb v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Mayor's Office for People with Disabilities" v:attribution="City of Chicago"

property e:fazv-a8mb t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:fazv-a8mb t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name      | organization                                       | description_of_request                                                             | date_received       | due_date            | 
| =================== | ================================================== | ================================================================================== | =================== | =================== | 
| Bret Angelos        | Self                                               | FOIA request numbers                                                               | 2012-07-12T19:47:00 | 2012-07-20T00:00:00 | 
| John O'Meara        | Curcio Law Offices                                 | Information regarding Accessible Parking Permit 55332                              | 2012-02-14T00:00:00 | 2012-02-22T00:00:00 | 
| Bryan Gryll         | Charles R. Gryll, Ltd.                             | Information regarding 4646-4658 South Drexel Blvd.                                 | 2012-02-21T00:00:00 | 2012-03-22T00:00:00 | 
| Chet Mehta          | AEI Consultant Environmental and Engineering Svcs. | Information regarding 3615 North Central Avenue                                    | 2012-07-20T00:00:00 | 2012-07-27T00:00:00 | 
| Bob Laing           | Self                                               | Whether accessible parking on Lincoln Ave. is open to all people with disabilities | 2012-07-24T00:00:00 | 2012-07-31T00:00:00 | 
| Thomas H. Geoghegan | Despres, Schwartz & Geoghegan, Ltd.                | Documents related to implementation of the new ward map.                           | 2013-04-09T00:00:00 | 2013-04-16T00:00:00 | 
```