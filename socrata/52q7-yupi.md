# FOIA Request Log - Human Relations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-human-relations-d64f2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/52q7-yupi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/52q7-yupi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/52q7-yupi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 52q7-yupi |
| Name | FOIA Request Log - Human Relations |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T18:42:46Z |
| Publication Date | 2017-04-20T15:08:07Z |

## Description

FOIA requests received by the Commission on Human Relations as of May 1, 2010

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
series e:52q7-yupi d:2010-05-03T00:00:00.000Z t:description_of_request="Complaints filed by Billy Molden" t:organization=None t:requestor_name="Yasmeen Saleh" m:row_number.52q7-yupi=1

series e:52q7-yupi d:2010-06-15T00:00:00.000Z t:description_of_request="01-PA-69/90/91 Documents" t:organization="Chicago Park District" t:requestor_name="Brian J. Flores" m:row_number.52q7-yupi=2

series e:52q7-yupi d:2010-06-15T00:00:00.000Z t:description_of_request="04-E-76 Documents" t:organization="Chicago Park District" t:requestor_name="Brian J. Flores" m:row_number.52q7-yupi=3
```

## Meta Commands

```ls
metric m:row_number.52q7-yupi p:long l:"Row Number"

entity e:52q7-yupi l:"FOIA Request Log - Human Relations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/52q7-yupi

property e:52q7-yupi t:meta.view v:id=52q7-yupi v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Human Relations" v:attribution="City of Chicago"

property e:52q7-yupi t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:52q7-yupi t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization                      | description_of_request                                      | date_received       | due_date            | 
| ================= | ================================= | =========================================================== | =================== | =================== | 
| Yasmeen Saleh     | None                              | Complaints filed by Billy Molden                            | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Brian J. Flores   | Chicago Park District             | 01-PA-69/90/91 Documents                                    | 2010-06-15T00:00:00 | 2010-06-22T00:00:00 | 
| Brian J. Flores   | Chicago Park District             | 04-E-76 Documents                                           | 2010-06-15T00:00:00 | 2010-06-22T00:00:00 | 
| Brian J. Flores   | Chicago Park District             | 04-H-54 Documents                                           | 2010-06-15T00:00:00 | 2010-06-22T00:00:00 | 
| Amy E. Keller     | Wexler Wallace LLP                | health care payment records                                 | 2010-07-06T00:00:00 | 2010-07-13T00:00:00 | 
| Kevin G. Costello | Zukowski, Rogers, Flood & McArdle | Complaints of Ayo Maat & IMPRUVE                            | 2010-07-07T00:00:00 | 2010-07-14T00:00:00 | 
| Vincent           | none                              | CPS personnel statistics                                    | 2010-07-09T00:00:00 | 2010-07-16T00:00:00 | 
| Kevin G. Costello | Zukowski, Rogers, Flood & McArdle | Complaints of William Crosby, Jeanette Exom, Harold Bellamy | 2010-07-16T00:00:00 | 2010-07-23T00:00:00 | 
| James Kottaras    | Law Ofc of James Kottaras         | Complaints of Letitia Johnson-Swain and/or Annette Flanagan | 2010-08-03T00:00:00 | 2010-08-10T00:00:00 | 
| Rose Jones        | None                              | Complaints against 3517 N. Marmora                          | 2010-09-12T00:00:00 | 2010-09-20T00:00:00 | 
```