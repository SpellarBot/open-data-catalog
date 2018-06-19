# FOIA Request Log - Graphics and Reproduction Center - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-graphics-and-reproduction-center-4283e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/57s6-wkzs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/57s6-wkzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/57s6-wkzs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 57s6-wkzs |
| Name | FOIA Request Log - Graphics and Reproduction Center - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T17:51:51Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by the Graphics and Reproduction Center from May 1, 2010 - December 31, 2010; for requests made January 1, 2011 or later, see https://data.cityofchicago.org/FOIA/FOIA-Request-Log-General-Services/aehc-sg39

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
series e:57s6-wkzs d:2010-03-05T00:00:00.000Z t:description_of_request="Any information pertaining to the property located at 2152 W. North Ave.,Chicago IL 60647." t:requestor_name="Lauren Thomas" m:row_number.57s6-wkzs=1

series e:57s6-wkzs d:2010-06-09T00:00:00.000Z t:description_of_request="Requesting Bid information that was proposed by Xerox, OCE and Canon for specification # 25827" t:organization="Canon Business Solutions" t:requestor_name="Charlene Roderick" m:row_number.57s6-wkzs=2

series e:57s6-wkzs d:2010-09-30T00:00:00.000Z t:description_of_request="Aerial photograph of the South Filtration Plant" t:organization="Noble & Associates Inc." t:requestor_name="George Noble" m:row_number.57s6-wkzs=3
```

## Meta Commands

```ls
metric m:row_number.57s6-wkzs p:long l:"Row Number"

entity e:57s6-wkzs l:"FOIA Request Log - Graphics and Reproduction Center - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/57s6-wkzs

property e:57s6-wkzs t:meta.view v:id=57s6-wkzs v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Graphics and Reproduction Center - Historical" v:attribution="City of Chicago"

property e:57s6-wkzs t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:57s6-wkzs t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization             | description_of_request                                                                                | date_received       | due_date            | 
| ================= | ======================== | ===================================================================================================== | =================== | =================== | 
| Lauren Thomas     |                          | Any information pertaining to the property located at 2152 W. North Ave.,Chicago IL 60647.            | 2010-02-26T00:00:00 | 2010-03-05T00:00:00 | 
| Charlene Roderick | Canon Business Solutions | Requesting Bid information that was proposed by Xerox, OCE and Canon for specification # 25827        | 2010-06-02T00:00:00 | 2010-06-09T00:00:00 | 
| George Noble      | Noble & Associates Inc.  | Aerial photograph of the South Filtration Plant                                                       | 2010-09-23T00:00:00 | 2010-09-30T00:00:00 | 
| Wrina E. Sellers  |                          | Requesting details on a signage that was posted by the City of Chicago                                |                     | 2010-10-22T00:00:00 | 
| Charlene Roderick | Canon Business Solutions | Second request of Bid information that was proposed by Xerox, OCE and Canon for specification # 25827 | 2010-10-25T00:00:00 | 2010-11-01T00:00:00 | 
```