# Performance Metrics - Buildings - Time to Issue Easy Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-buildings-time-to-issue-easy-permits-cce65) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7ray-xvet) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7ray-xvet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7ray-xvet/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7ray-xvet |
| Name | Performance Metrics - Buildings - Time to Issue Easy Permits |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, buildings, permits |
| Created | 2011-09-27T13:35:54Z |
| Publication Date | 2013-12-18T12:10:20Z |

## Description

The Easy Permit Process allows home and building owners to obtain a permit to repair or replace the same or existing elements of a building, without making any changes to the structure of the building. Eligible projects include repairing or replacing drywall, flooring, fences, sheds or garages. This metric tracks the average number of days DOB takes to process individual Easy Permits, grouped by the week the permit was processed. The target process time is within 1.3 days. For more information about the Easy Permitting process, go to http://www.cityofchicago.org/city/en/depts/bldgs/provdrs/permit_proc.html.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | week                   | Week                   | calendar_date | calendar_date |
| No       |                | week_text              | Week - Text            | text          | text          |
| Yes      | numeric metric | average_days_to_permit | Average Days to Permit | number        | number        |
| Yes      | numeric metric | target                 | Target                 | number        | number        |
```

## Time Field

```ls
Value = week
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = week_text
```

## Data Commands

```ls
series e:7ray-xvet d:2011-05-30T00:00:00.000Z m:target=1.3 m:average_days_to_permit=0.91

series e:7ray-xvet d:2011-06-06T00:00:00.000Z m:target=1.3 m:average_days_to_permit=0.19

series e:7ray-xvet d:2011-06-13T00:00:00.000Z m:target=1.3 m:average_days_to_permit=0.98
```

## Meta Commands

```ls
metric m:average_days_to_permit p:float l:"Average Days to Permit" t:dataTypeName=number

metric m:target p:float l:Target t:dataTypeName=number

entity e:7ray-xvet l:"Performance Metrics - Buildings - Time to Issue Easy Permits" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7ray-xvet

property e:7ray-xvet t:meta.view v:id=7ray-xvet v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Buildings - Time to Issue Easy Permits" v:attribution="City of Chicago"

property e:7ray-xvet t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:7ray-xvet t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| week                | week_text | average_days_to_permit | target | 
| =================== | ========= | ====================== | ====== | 
| 2011-05-30T00:00:00 | 5/30/2011 | 0.91                   | 1.3    | 
| 2011-06-06T00:00:00 | 6/6/2011  | 0.19                   | 1.3    | 
| 2011-06-13T00:00:00 | 6/13/2011 | 0.98                   | 1.3    | 
| 2011-06-20T00:00:00 | 6/20/2011 | 0.3                    | 1.3    | 
| 2011-06-27T00:00:00 | 6/27/2011 | 0.62                   | 1.3    | 
| 2011-07-04T00:00:00 | 7/4/2011  | 0.4                    | 1.3    | 
| 2011-07-11T00:00:00 | 7/11/2011 | 0.74                   | 1.3    | 
| 2011-07-18T00:00:00 | 7/18/2011 | 0.9                    | 1.3    | 
| 2011-07-25T00:00:00 | 7/25/2011 | 0.49                   | 1.3    | 
| 2011-08-01T00:00:00 | 8/1/2011  | 0.53                   | 1.3    | 
```