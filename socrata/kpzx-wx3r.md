# FOIA Request Log - Special Events - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-special-events-1f71b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kpzx-wx3r) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kpzx-wx3r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kpzx-wx3r/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kpzx-wx3r |
| Name | FOIA Request Log - Special Events - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T19:19:20Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by Special Events May 1, 2010 - December 31, 2010; for requests made after January 1, 2011, see Cultural Affairs & Special Events FOIA Request Log at https://data.cityofchicago.org/FOIA/FOIA-Request-Log-Cultural-Affairs-Special-Events/hv7d-ut55

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
series e:kpzx-wx3r d:2010-06-08T00:00:00.000Z t:description_of_request="Permit for exterior filming of move Ca$h" t:organization="Reott Law Offices LLC" t:requestor_name="Raymond Reott" m:row_number.kpzx-wx3r=1

series e:kpzx-wx3r d:2010-07-06T00:00:00.000Z t:description_of_request="request information related to any report or study done for or on the behalf of the city of Chicago regarding potential, proposed or existing, helipads or heliports and helicopter operations in the city of Chicago." t:organization="Hinshaw & Culbertson LLP" t:requestor_name="Richard S. Porter" m:row_number.kpzx-wx3r=2

series e:kpzx-wx3r d:2010-06-29T00:00:00.000Z t:description_of_request="Commercial purposes: Contractor who installed temporary fence at Blues Festival and Taste of Chicago and costs so business may be more competitive with future bid." t:organization="Fence Masters Inc" t:requestor_name="Peter Biancardi" m:row_number.kpzx-wx3r=3
```

## Meta Commands

```ls
metric m:row_number.kpzx-wx3r p:long l:"Row Number"

entity e:kpzx-wx3r l:"FOIA Request Log - Special Events - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kpzx-wx3r

property e:kpzx-wx3r t:meta.view v:id=kpzx-wx3r v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Special Events - Historical" v:attribution="City of Chicago"

property e:kpzx-wx3r t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:kpzx-wx3r t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization              | description_of_request                                                                                                                                                                                                 | date_received       | due_date            | 
| ================= | ========================= | ====================================================================================================================================================================================================================== | =================== | =================== | 
| Raymond Reott     | Reott Law Offices LLC     | Permit for exterior filming of move Ca$h                                                                                                                                                                               | 2010-06-08T00:00:00 | 2010-06-15T00:00:00 | 
| Richard S. Porter | Hinshaw & Culbertson LLP  | request information related to any report or study done for or on the behalf of the city of Chicago regarding potential, proposed or existing, helipads or heliports and helicopter operations in the city of Chicago. | 2010-07-06T00:00:00 | 2010-07-13T00:00:00 | 
| Peter Biancardi   | Fence Masters Inc         | Commercial purposes: Contractor who installed temporary fence at Blues Festival and Taste of Chicago and costs so business may be more competitive with future bid.                                                    | 2010-06-29T00:00:00 | 2010-07-29T00:00:00 | 
| Bernard M. Clay   | Introspect Youth Services | A list of Block Club Contacts for Wards 2, 24, 27, 28, 29 and 37.                                                                                                                                                      | 2010-08-12T00:00:00 | 2010-08-19T00:00:00 | 
| Patrick Boylan    | Welles Park Bulldog       | A list of applications for a permit to hold a Black Party                                                                                                                                                              | 2010-08-16T00:00:00 | 2010-08-23T00:00:00 | 
| Walter J. Kugler  | Resident                  | Information on event held on the N. Oakley Block, 1800n to 1890 on August 21, 2010                                                                                                                                     | 2010-08-24T00:00:00 | 2010-08-31T00:00:00 | 
| John Byrne        | Chicago Tribune           | Taste of Chicago net revenues and attendance for the past five years                                                                                                                                                   | 2010-08-27T00:00:00 | 2010-09-03T00:00:00 | 
| Meghan Keyes      | Chronicle                 | Information regarding Transformers 3 filming permits; dates of filming, locations of filming, jobs provided and money involved.                                                                                        | 2010-08-30T00:00:00 | 2010-09-07T00:00:00 | 
| John Byrne        | Chicago Tribune           | Information on the Taste of Chicago: list of how many vendors; process by which musical acts have been booked to perform; budget for entertainment                                                                     | 2010-09-01T00:00:00 | 2010-09-09T00:00:00 | 
| John Byrne        | Chicago Tribune           | How much has the city spent on Taste of Chicago each year                                                                                                                                                              | 2010-09-01T00:00:00 | 2010-09-09T00:00:00 | 
```