# FOIA Request Log - Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-compliance-1dfab) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pv55-neb6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pv55-neb6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pv55-neb6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pv55-neb6 |
| Name | FOIA Request Log - Compliance |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T16:06:24Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by the Office of Compliance as of May 1, 2010

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
series e:pv55-neb6 d:2010-05-07T00:00:00.000Z t:description_of_request="Permits for installation and/or removal of USTs (Underground Storage Tanks)." t:organization="Benchmark Environmental" t:requestor_name="Lydia Liniewicz" m:row_number.pv55-neb6=1

series e:pv55-neb6 d:2010-05-14T00:00:00.000Z t:description_of_request="Names of owners and percentage ownership for two companies." t:organization=n/a t:requestor_name="Michael Lewyckyj" m:row_number.pv55-neb6=2

series e:pv55-neb6 d:2010-05-17T00:00:00.000Z t:description_of_request="Pending building code and fire code violations for a City property" t:organization="Shaw Environmental" t:requestor_name="Fadi Maroun" m:row_number.pv55-neb6=3
```

## Meta Commands

```ls
metric m:row_number.pv55-neb6 p:long l:"Row Number"

entity e:pv55-neb6 l:"FOIA Request Log - Compliance" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/pv55-neb6

property e:pv55-neb6 t:meta.view v:id=pv55-neb6 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Compliance" v:attribution="City of Chicago"

property e:pv55-neb6 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:pv55-neb6 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name     | organization                             | description_of_request                                                       | date_received       | due_date            | 
| ================== | ======================================== | ============================================================================ | =================== | =================== | 
| Lydia Liniewicz    | Benchmark Environmental                  | Permits for installation and/or removal of USTs (Underground Storage Tanks). | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Michael Lewyckyj   | n/a                                      | Names of owners and percentage ownership for two companies.                  | 2010-05-14T00:00:00 | 2010-05-21T00:00:00 | 
| Fadi Maroun        | Shaw Environmental                       | Pending building code and fire code violations for a City property           | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Pedro Cervantes    | TGC Partners                             | Documents related to MBE applications for three companies                    | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Karen Cullman      | Capital Markets Consultants              | Business license verification                                                | 2010-05-19T00:00:00 | 2010-05-26T00:00:00 | 
| Catherine Borowski | West Side Only, LLC                      | Building inspection records                                                  | 2010-07-21T00:00:00 | 2010-07-28T00:00:00 | 
| Rita Dolan         | Greenwood Environmental Consulting, INC. | Environmental records for three properties                                   | 2010-07-28T00:00:00 | 2010-08-04T00:00:00 | 
| Joanna Novak       | Stone & Johnson, Chartered               | Speed limit information for US 41 (Lakeshore Drive)                          | 2010-08-16T00:00:00 | 2010-08-23T00:00:00 | 
| Jeff Goeters       | n/a                                      | Documents pertaining to 3014 Palmer Blvd., Chicago, IL 60647                 | 2010-08-18T00:00:00 | 2010-08-25T00:00:00 | 
| Meghan Dwyer       | Stone & Johnson, Chartered               | Documents related to MBE/WBE certification for one company                   | 2010-08-24T00:00:00 | 2010-08-31T00:00:00 | 
```