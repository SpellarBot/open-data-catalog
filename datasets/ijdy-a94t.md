# Performance Metrics - Buildings - Time to Issue Developer Services Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-buildings-time-to-issue-developer-services-permits-e7b0b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ijdy-a94t) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ijdy-a94t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ijdy-a94t/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ijdy-a94t |
| Name | Performance Metrics - Buildings - Time to Issue Developer Services Permits |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | buildings, permits, service delivery, performance metrics |
| Created | 2011-09-27T13:38:28Z |
| Publication Date | 2013-12-18T12:11:01Z |

## Description

The Developer Services Review Program is designed to meet the special needs of owners, developers, architects and contractors working on moderately- to highly-complex construction or renovation projects. Eligible projects include high-rise buildings, mercantile buildings with more than 150,000 square feet, other occupancies with more than 80,000 square feet, buildings with foundations deeper than 12 feet, and residential projects that contain more than 25 units. This metric tracks the average number of days DOB takes to process individual Developer Services Permits, grouped by the week the permit was processed. The target average process time is within 89 days. Click here for more information about DOB?s Developer Services Program.

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
series e:ijdy-a94t d:2011-05-30T00:00:00.000Z m:target=89 m:average_days_to_permit=31

series e:ijdy-a94t d:2011-06-06T00:00:00.000Z m:target=89 m:average_days_to_permit=47

series e:ijdy-a94t d:2011-06-13T00:00:00.000Z m:target=89 m:average_days_to_permit=215
```

## Meta Commands

```ls
metric m:average_days_to_permit p:double l:"Average Days to Permit" t:dataTypeName=number

metric m:target p:integer l:Target t:dataTypeName=number

entity e:ijdy-a94t l:"Performance Metrics - Buildings - Time to Issue Developer Services Permits" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ijdy-a94t

property e:ijdy-a94t t:meta.view v:id=ijdy-a94t v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Buildings - Time to Issue Developer Services Permits" v:attribution="City of Chicago"

property e:ijdy-a94t t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ijdy-a94t t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| week                | week_text | average_days_to_permit | target | 
| =================== | ========= | ====================== | ====== | 
| 2011-05-30T00:00:00 | 5/30/2011 | 31                     | 89     | 
| 2011-06-06T00:00:00 | 6/6/2011  | 47                     | 89     | 
| 2011-06-13T00:00:00 | 6/13/2011 | 215                    | 89     | 
| 2011-06-20T00:00:00 | 6/20/2011 | 35                     | 89     | 
| 2011-06-27T00:00:00 | 6/27/2011 | 48.86                  | 89     | 
| 2011-07-04T00:00:00 | 7/4/2011  | 22.33                  | 89     | 
| 2011-07-11T00:00:00 | 7/11/2011 | 27.64                  | 89     | 
| 2011-07-18T00:00:00 | 7/18/2011 | 51.63                  | 89     | 
| 2011-07-25T00:00:00 | 7/25/2011 | 64.38                  | 89     | 
| 2011-08-01T00:00:00 | 8/1/2011  | 45.83                  | 89     | 
```