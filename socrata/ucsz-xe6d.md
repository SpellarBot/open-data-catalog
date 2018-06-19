# FOIA Request Log - Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-buildings-51c84) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ucsz-xe6d) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ucsz-xe6d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ucsz-xe6d/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ucsz-xe6d |
| Name | FOIA Request Log - Buildings |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-26T20:40:25Z |
| Publication Date | 2016-11-22T18:58:53Z |

## Description

FOIA requests received by Buildings as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| No       |             | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| Yes      | time        | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = due_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_received
```

## Data Commands

```ls
series e:ucsz-xe6d d:2010-01-11T00:00:00.000Z t:description_of_request=permits t:requestor_name="cynthia inch" m:row_number.ucsz-xe6d=1

series e:ucsz-xe6d d:2011-01-13T00:00:00.000Z t:description_of_request=permits,vio,units t:organization="remax signature" t:requestor_name="stephany olivers" m:row_number.ucsz-xe6d=2

series e:ucsz-xe6d d:2010-01-18T00:00:00.000Z t:description_of_request=permits,vio,units t:requestor_name="rick v" m:row_number.ucsz-xe6d=3
```

## Meta Commands

```ls
metric m:row_number.ucsz-xe6d p:long l:"Row Number"

entity e:ucsz-xe6d l:"FOIA Request Log - Buildings" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ucsz-xe6d

property e:ucsz-xe6d t:meta.view v:id=ucsz-xe6d v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Buildings" v:attribution="City of Chicago"

property e:ucsz-xe6d t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ucsz-xe6d t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name   | organization                | description_of_request | date_received       | due_date            | 
| ================ | =========================== | ====================== | =================== | =================== | 
| cynthia inch     |                             | permits                | 2010-01-11T00:00:00 | 2010-01-11T00:00:00 | 
| stephany olivers | remax signature             | permits,vio,units      | 2010-01-13T00:00:00 | 2011-01-13T00:00:00 | 
| rick v           |                             | permits,vio,units      | 2010-01-18T00:00:00 | 2010-01-18T00:00:00 | 
| julie brown      | kprg & associates,inc       | permits,vio            | 2010-01-18T00:00:00 | 2010-01-18T00:00:00 | 
| sean mcLellan    | mostardi platt enviromental | permits                | 2010-01-19T00:00:00 | 2011-01-19T00:00:00 | 
| mark j kupiec    | mark j kupiec & assoc       | permits                | 2010-01-19T00:00:00 | 2011-01-19T00:00:00 | 
| simona ardelean  |                             | vio,permits            | 2010-01-21T00:00:00 | 2011-01-21T00:00:00 | 
| peter sterniuk   | stern group                 | permits,vio,units      | 2010-01-26T00:00:00 | 2011-01-26T00:00:00 | 
| yvonne slosarski | illinois tenants union      | violations             | 2010-04-30T00:00:00 | 2010-05-03T00:00:00 | 
| antonio collins  |                             | vio's                  | 2010-04-30T00:00:00 | 2010-05-03T00:00:00 | 
```