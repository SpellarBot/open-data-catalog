# 311 Infrastructure Maintenance Closure Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-infrastructure-maintenance-closure-rates) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/jj2h-3ijx) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/jj2h-3ijx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/jj2h-3ijx/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | jj2h-3ijx |
| Name | 311 Infrastructure Maintenance Closure Rates |
| Attribution | City of Jackson |
| Category | City Services |
| Tags | 311, action line, mayor's action line, city services, jackson service center |
| Created | 2016-03-09T15:46:17Z |
| Publication Date | 2016-04-11T21:18:34Z |

## Description

This data shows the closure rates for all calls related to infrastructure maintenance in the 311 system. This information is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type     | Render Type   |
| ======== | ============== | ================ | ================== | ============= | ============= |
| Yes      | series tag     | bridges_drainage | BRIDGES & DRAINAGE | text          | text          |
| Yes      | numeric metric | calls_closed     | Calls Closed       | number        | number        |
| Yes      | numeric metric | calls_received   | Calls Received     | number        | number        |
| Yes      | numeric metric | closure_rate     | Closure Rate       | percent       | percent       |
| Yes      | time           | as_of_date       | As of Date:        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jj2h-3ijx d:2016-01-31T00:00:00.000Z t:bridges_drainage="Ditch Maintenance" m:calls_closed=38 m:calls_received=39 m:closure_rate=103

series e:jj2h-3ijx d:2016-01-31T00:00:00.000Z t:bridges_drainage="Drainage Maintenance (inlets, etc)" m:calls_closed=86 m:calls_received=41 m:closure_rate=48

series e:jj2h-3ijx d:2016-02-28T00:00:00.000Z t:bridges_drainage="Ditch Maintenance" m:calls_closed=53 m:calls_received=34 m:closure_rate=64
```

## Meta Commands

```ls
metric m:calls_closed p:integer l:"Calls Closed" t:dataTypeName=number

metric m:calls_received p:integer l:"Calls Received" t:dataTypeName=number

metric m:closure_rate p:float l:"Closure Rate" t:dataTypeName=percent

entity e:jj2h-3ijx l:"311 Infrastructure Maintenance Closure Rates" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/jj2h-3ijx

property e:jj2h-3ijx t:meta.view v:id=jj2h-3ijx v:category="City Services" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="311 Infrastructure Maintenance Closure Rates" v:attribution="City of Jackson"

property e:jj2h-3ijx t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:jj2h-3ijx t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| bridges_drainage                   | calls_closed | calls_received | closure_rate | as_of_date          | 
| ================================== | ============ | ============== | ============ | =================== | 
| Ditch Maintenance                  | 38           | 39             | 103.00       | 2016-01-31T00:00:00 | 
| Drainage Maintenance (inlets, etc) | 86           | 41             | 48.00        | 2016-01-31T00:00:00 | 
| Ditch Maintenance                  | 53           | 34             | 64           | 2016-02-28T00:00:00 | 
| Drainage Maintenance (inlets, etc) | 113          | 41             | 36           | 2016-02-28T00:00:00 | 
| Ditch Maintenance                  | 101          | 49             | 49           | 2016-03-30T00:00:00 | 
| Drainage Maintenance (inlets, etc) | 180          | 48             | 27           | 2016-03-31T00:00:00 | 
```