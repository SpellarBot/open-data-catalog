# FOIA Request Log - Zoning and Land Use Planning - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-zoning-and-land-use-planning-b686f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2nra-kpzu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2nra-kpzu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2nra-kpzu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2nra-kpzu |
| Name | FOIA Request Log - Zoning and Land Use Planning - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T19:30:19Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by Zoning and Land Use Planning from May 1, 2010-December 31, 2010; For requests made after January 1, 2011, please see Housing & Economic Development FOIA Request Log  at https://data.cityofchicago.org/Government/FOIA-Request-Log-Housing-And-Economic-Development/5ztz-espx

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
series e:2nra-kpzu d:2010-08-04T00:00:00.000Z t:description_of_request="contents of PD 917" t:organization=Centerstone t:requestor_name="Anita Goyal" m:row_number.2nra-kpzu=1

series e:2nra-kpzu d:2010-09-30T00:00:00.000Z t:description_of_request=questionnaire t:organization="Permit Place" t:requestor_name="Alec Rutledge" m:row_number.2nra-kpzu=2

series e:2nra-kpzu d:2010-10-25T00:00:00.000Z t:requestor_name="Darryl Messer" m:row_number.2nra-kpzu=3
```

## Meta Commands

```ls
metric m:row_number.2nra-kpzu p:long l:"Row Number"

entity e:2nra-kpzu l:"FOIA Request Log - Zoning and Land Use Planning - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2nra-kpzu

property e:2nra-kpzu t:meta.view v:id=2nra-kpzu v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Zoning and Land Use Planning - Historical" v:attribution="City of Chicago"

property e:2nra-kpzu t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:2nra-kpzu t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization         | description_of_request                           | date_received       | due_date            | 
| =============== | ==================== | ================================================ | =================== | =================== | 
| Anita Goyal     | Centerstone          | contents of PD 917                               | 2010-08-04T00:00:00 | 2010-08-11T00:00:00 | 
| Alec Rutledge   | Permit Place         | questionnaire                                    | 2010-09-30T00:00:00 | 2010-10-07T00:00:00 | 
| Darryl Messer   |                      |                                                  | 2010-10-25T00:00:00 | 2010-11-01T00:00:00 | 
| Paul Bauch      | Bauch & Michaels     | all records re : Wrigley Landmark, signs & PD368 | 2010-05-03T00:00:00 | 2010-05-07T00:00:00 | 
| Agnes Plecka    | Citizen              | Water Records 5126 N .Avers                      | 2010-05-03T00:00:00 | 2010-05-07T00:00:00 | 
| Charles Doerr   | Legal Runners Inc.   | Water Records 1353 N.Campbell                    | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Jay Ogorzalek   | Terracon Consultants | zoning analysis on 650 W. Lake                   | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Scott Saef      | Sidley Austin        | review of PD # 70 document file                  | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| George Nugent   | Developer            | request for copy of PD 931                       | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| MaryAnn Collins | Owners               | Water records for 6545 N. Natoma                 | 2010-05-06T00:00:00 | 2010-05-13T00:00:00 | 
```