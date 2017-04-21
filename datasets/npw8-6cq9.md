# FOIA Request Log - Cultural Affairs - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-cultural-affairs-cfdad) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/npw8-6cq9) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/npw8-6cq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/npw8-6cq9/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | npw8-6cq9 |
| Name | FOIA Request Log - Cultural Affairs - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T16:10:13Z |
| Publication Date | 2017-02-02T21:12:33Z |

## Description

FOIA requests received by Cultural Affairs from May 1, 2010 -  December 31, 2010;  for requests made after January 1, 2011, see Cultural Affairs & Special Events FOIA Request Log at https://data.cityofchicago.org/FOIA/FOIA-Request-Log-Cultural-Affairs-Special-Events/hv7d-ut55

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
series e:npw8-6cq9 d:2010-06-20T00:00:00.000Z t:description_of_request="Building permit documents for 1217 S. Kolin Ave." t:organization="Great Street Properties" t:requestor_name="Christiane Irwin" m:row_number.npw8-6cq9=1

series e:npw8-6cq9 d:2010-06-20T00:00:00.000Z t:description_of_request="Building permit documents for 1037 W. Madison" t:organization="Great Street Properties" t:requestor_name="Christiane Irwin" m:row_number.npw8-6cq9=2

series e:npw8-6cq9 d:2010-06-20T00:00:00.000Z t:description_of_request="Building permit documents for 4324 N. Kostner" t:organization="Great Street Properties" t:requestor_name="Christiane Irwin" m:row_number.npw8-6cq9=3
```

## Meta Commands

```ls
metric m:row_number.npw8-6cq9 p:long l:"Row Number"

entity e:npw8-6cq9 l:"FOIA Request Log - Cultural Affairs - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/npw8-6cq9

property e:npw8-6cq9 t:meta.view v:id=npw8-6cq9 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Cultural Affairs - Historical" v:attribution="City of Chicago"

property e:npw8-6cq9 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:npw8-6cq9 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name   | organization            | description_of_request                                     | date_received       | due_date            | 
| ================ | ======================= | ========================================================== | =================== | =================== | 
| Christiane Irwin | Great Street Properties | Building permit documents for 1217 S. Kolin Ave.           | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 1037 W. Madison              | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 4324 N. Kostner              | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 1133 W. 71st St.             | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 4832 S. Hrmitage Ave.        | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 10211 S. Lowe Ave.           | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 7915 S. Phillips Ave.        | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 1840 W. 23rd St.             | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 1338 S. Oakley Ave.          | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
| Christiane Irwin | Great Street Properties | Building permit documents for 474 N. Lake Shore Dr., #4406 | 2010-06-20T00:00:00 | 2010-06-27T00:00:00 | 
```