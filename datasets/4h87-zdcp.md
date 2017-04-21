# FOIA Request Log - Health

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-health-55b64) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4h87-zdcp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4h87-zdcp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4h87-zdcp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4h87-zdcp |
| Name | FOIA Request Log - Health |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T18:37:47Z |
| Publication Date | 2016-04-08T08:09:15Z |

## Description

FOIA requests received by the Chicago Department of Public Health as of May 1, 2010

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
series e:4h87-zdcp d:2012-03-01T00:00:00.000Z t:description_of_request="food inspection report" t:requestor_name="Danny Round" m:row_number.4h87-zdcp=1

series e:4h87-zdcp d:2012-03-15T00:00:00.000Z t:description_of_request="lead inspection reports" t:requestor_name="Patricia Lewis" m:row_number.4h87-zdcp=2

series e:4h87-zdcp d:2012-03-21T00:00:00.000Z t:description_of_request="lead inspection reports" t:organization="AEI Consultants" t:requestor_name="Jim Miller" m:row_number.4h87-zdcp=3
```

## Meta Commands

```ls
metric m:row_number.4h87-zdcp p:long l:"Row Number"

entity e:4h87-zdcp l:"FOIA Request Log - Health" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/4h87-zdcp

property e:4h87-zdcp t:meta.view v:id=4h87-zdcp v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Health" v:attribution="City of Chicago"

property e:4h87-zdcp t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:4h87-zdcp t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name      | organization                 | description_of_request  | date_received       | due_date            | 
| =================== | ============================ | ======================= | =================== | =================== | 
| Danny Round         |                              | food inspection report  | 2012-03-01T00:00:00 | 2012-03-09T00:00:00 | 
| Patricia Lewis      |                              | lead inspection reports | 2012-03-15T00:00:00 | 2012-03-22T00:00:00 | 
| Jim Miller          | AEI Consultants              | lead inspection reports | 2012-03-21T00:00:00 | 2012-03-28T00:00:00 | 
| Shashona Chau       |                              | food inspection report  | 2012-03-21T00:00:00 | 2012-03-28T00:00:00 | 
| Connie Temple       | Aldermanic Office request    | food inspection report  | 2012-03-22T00:00:00 | 2012-03-30T00:00:00 | 
| George Dickinson    |                              | food inspection report  | 2012-03-23T00:00:00 | 2012-03-30T00:00:00 | 
| Gary Reynolds       | Subway                       | food inspection report  | 2012-03-23T00:00:00 | 2012-03-30T00:00:00 | 
| Adrian Wright       |                              | food inspection report  | 2012-03-26T00:00:00 | 2012-03-30T00:00:00 | 
| Daniel R. Kolodziej | Legal Services Benefits Plan | food inspection report  | 2012-03-23T00:00:00 | 2012-03-30T00:00:00 | 
| Richard Ooms        |                              | medical records         | 2012-04-02T00:00:00 | 2012-04-02T00:00:00 | 
```