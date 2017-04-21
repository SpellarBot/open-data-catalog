# FOIA Request Log - Transportation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-transportation-0f2f2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/u9qt-tv7d) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/u9qt-tv7d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/u9qt-tv7d/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | u9qt-tv7d |
| Name | FOIA Request Log - Transportation |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-30T08:00:34Z |
| Publication Date | 2016-05-17T11:26:01Z |

## Description

FOIA requests received by Transportation as of May 1, 2010

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
series e:u9qt-tv7d d:2016-05-16T00:00:00.000Z t:description_of_request="video footage:  Congress Parkway & Michigan on May 9, 2016 between 8:14 am - 8:16 am" t:requestor_name="Kevin Greene" m:row_number.u9qt-tv7d=1

series e:u9qt-tv7d d:2016-05-13T00:00:00.000Z t:description_of_request="RLC video footage:  Diversey & California on April 29, 2016 between 11 am - 12 pm" t:organization="O'Brien & Murphy-Aguilu" t:requestor_name="Sean O'Brien" m:row_number.u9qt-tv7d=2

series e:u9qt-tv7d d:2016-05-13T00:00:00.000Z t:description_of_request="video footage:  State & Ohio on Sept 5, 2014" t:organization="Oak Hill Associates" t:requestor_name="Karen Cecchetti" m:row_number.u9qt-tv7d=3
```

## Meta Commands

```ls
metric m:row_number.u9qt-tv7d p:long l:"Row Number"

entity e:u9qt-tv7d l:"FOIA Request Log - Transportation" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/u9qt-tv7d

property e:u9qt-tv7d t:meta.view v:id=u9qt-tv7d v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Transportation" v:attribution="City of Chicago"

property e:u9qt-tv7d t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:u9qt-tv7d t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization              | description_of_request                                                               | date_received       | due_date            | 
| =============== | ========================= | ==================================================================================== | =================== | =================== | 
| Kevin Greene    |                           | video footage: Congress Parkway & Michigan on May 9, 2016 between 8:14 am - 8:16 am  | 2016-05-16T00:00:00 | 2016-05-23T00:00:00 | 
| Sean O'Brien    | O'Brien & Murphy-Aguilu   | RLC video footage: Diversey & California on April 29, 2016 between 11 am - 12 pm     | 2016-05-13T00:00:00 | 2016-05-20T00:00:00 | 
| Karen Cecchetti | Oak Hill Associates       | video footage: State & Ohio on Sept 5, 2014                                          | 2016-05-13T00:00:00 | 2016-05-20T00:00:00 | 
| Brooke Street   | Farmers Insurance         | RLC video footage: Chicago Ave & Sacramento on April 17, 2016 between 9 am - 9:15 am | 2016-05-13T00:00:00 | 2016-05-20T00:00:00 | 
| Christine Ponce | All State Insurance       | video footage: North Avenue & Lawndale on May 8, 2016 at 12:10 am                    | 2016-05-13T00:00:00 | 2016-05-20T00:00:00 | 
| Helga Becker    | American Family Insurance | video footage: 35th Giles on April 27, 2016 at 12:45 pm                              | 2016-05-12T00:00:00 | 2016-05-19T00:00:00 | 
| Tyann Austin    |                           | maintenance records & other records regarding the ASE camera at 5816 W. Jackson      | 2016-05-12T00:00:00 | 2016-05-19T00:00:00 | 
| Deidre Thomas   | Allstate Insurance        | RLC video footage: Wells & Congress Pkwy on May 11, 2016 between 9:30 pm - 10 pm     | 2016-05-12T00:00:00 | 2016-05-19T00:00:00 | 
| Adam Falkof     | Quarles & Brady           | dedication/acquisition records for Division Street between Noble & Branch            | 2016-05-12T00:00:00 | 2016-05-19T00:00:00 | 
| Rick Stewart    | Hess Martone              | documents regarding Damen/Elston/Fullerton since Jan 1, 2015                         | 2016-05-12T00:00:00 | 2016-05-19T00:00:00 | 
```