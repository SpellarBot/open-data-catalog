# FOIA Request Log - Fire

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-fire-40461) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/un3c-ixb7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/un3c-ixb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/un3c-ixb7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | un3c-ixb7 |
| Name | FOIA Request Log - Fire |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-22T16:30:34Z |
| Publication Date | 2017-04-06T23:07:25Z |

## Description

FOIA requests received by the Chicago Fire Department as of May 1, 2010

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
series e:un3c-ixb7 d:2017-04-13T00:00:00.000Z t:description_of_request=INSPECTION t:organization="Pioneer Engineering & Environmental" t:requestor_name="Lauren Zangl" m:row_number.un3c-ixb7=1

series e:un3c-ixb7 d:2017-04-13T00:00:00.000Z t:description_of_request=INSPECTION t:organization="NOVA Consulting Group" t:requestor_name="Matthew Jesberg" m:row_number.un3c-ixb7=2

series e:un3c-ixb7 d:2017-04-13T00:00:00.000Z t:description_of_request=INSPECTION t:organization="Aspen Environmental Services" t:requestor_name="Tim Tuzik" m:row_number.un3c-ixb7=3
```

## Meta Commands

```ls
metric m:row_number.un3c-ixb7 p:long l:"Row Number"

entity e:un3c-ixb7 l:"FOIA Request Log - Fire" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/un3c-ixb7

property e:un3c-ixb7 t:meta.view v:id=un3c-ixb7 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Fire" v:attribution="City of Chicago"

property e:un3c-ixb7 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:un3c-ixb7 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization                        | description_of_request | date_received       | due_date            | 
| =============== | =================================== | ====================== | =================== | =================== | 
| Lauren Zangl    | Pioneer Engineering & Environmental | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Matthew Jesberg | NOVA Consulting Group               | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Tim Tuzik       | Aspen Environmental Services        | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Karen Zelzer    | Carnow & Conibear                   | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Beth Cole       | Pioneer Engineering & Environmental | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Suzanne Griffin | Bock & Clark Corporation            | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Natalie Baldwin | EPS Environmental Services          | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Dina Ledbetter  | K-Plus Engineering                  | INSPECTION             | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Ann Freund      | John Agosti & Associates            | OFI/REC                | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
| Joseph Mazzone  | Mazzone Investigations              | OFI/REC                | 2017-04-06T00:00:00 | 2017-04-13T00:00:00 | 
```