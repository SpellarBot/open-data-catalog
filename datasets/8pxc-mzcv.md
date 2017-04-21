# FOIA Request Log - OEMC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-oemc-b80df) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8pxc-mzcv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8pxc-mzcv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8pxc-mzcv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8pxc-mzcv |
| Name | FOIA Request Log - OEMC |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-30T14:37:18Z |
| Publication Date | 2016-01-08T09:10:51Z |

## Description

FOIA requests received by the Office of Emergency Management and Communications as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | requestor_name | REQUESTOR NAME | text          | text          |
| Yes      | series tag  | request_type   | REQUEST TYPE   | text          | text          |
| Yes      | time        | received_date  | RECEIVED DATE  | calendar_date | calendar_date |
| No       |             | due_date       | DUE DATE       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = received_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:8pxc-mzcv d:2051-12-29T00:00:00.000Z t:requestor_name="MOTAMEDI, M. HOSEIN" t:request_type=Video m:row_number.8pxc-mzcv=1

series e:8pxc-mzcv d:2016-01-07T00:00:00.000Z t:requestor_name="MACK, CHESTER" t:request_type=Other m:row_number.8pxc-mzcv=2

series e:8pxc-mzcv d:2016-01-06T00:00:00.000Z t:requestor_name="DEVEAUX, CLARINDA" t:request_type="CAD Events" m:row_number.8pxc-mzcv=3
```

## Meta Commands

```ls
metric m:row_number.8pxc-mzcv p:long l:"Row Number"

entity e:8pxc-mzcv l:"FOIA Request Log - OEMC" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8pxc-mzcv

property e:8pxc-mzcv t:meta.view v:id=8pxc-mzcv v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - OEMC" v:attribution="City of Chicago"

property e:8pxc-mzcv t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:8pxc-mzcv t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name      | request_type | received_date       | due_date            | 
| =================== | ============ | =================== | =================== | 
| MOTAMEDI, M. HOSEIN | Video        | 2051-12-29T00:00:00 |                     | 
| MACK, CHESTER       | Other        | 2016-01-07T00:00:00 | 2016-01-07T00:00:00 | 
| DEVEAUX, CLARINDA   | CAD Events   | 2016-01-06T00:00:00 | 2015-01-06T00:00:00 | 
| OEMC                | Other        | 2015-12-31T00:00:00 |                     | 
| OEMC                |              | 2015-12-31T00:00:00 | 2015-01-04T00:00:00 | 
| oemc                | Audio        | 2015-12-31T00:00:00 |                     | 
| WISE, JARED         | Audio        | 2015-12-30T00:00:00 |                     | 
| MADHANI, AAMER      | Audio        | 2015-12-29T00:00:00 | 2016-01-06T00:00:00 | 
| MADHANI, AAMER      | Audio        | 2015-12-29T00:00:00 |                     | 
| CAPITANINI, LISA    | Audio        | 2015-12-29T00:00:00 | 2016-01-06T00:00:00 | 
```