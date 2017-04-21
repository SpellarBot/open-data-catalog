# Performance Metrics - Innovation & Technology - City Website Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-innovation-technology-city-website-availability-3ce40) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/icwn-eia9) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/icwn-eia9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/icwn-eia9/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | icwn-eia9 |
| Name | Performance Metrics - Innovation & Technology - City Website Availability |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, technology |
| Created | 2011-09-22T18:51:07Z |
| Publication Date | 2011-09-27T23:29:14Z |

## Description

The City's Internet site allows residents to access City services online, learn more about the City of Chicago, and find other pertinent information. The percentage of the City?s Internet website uptime, the amount of time the site was available, and the target uptime for each week are available by mousing over columns. The target availability for this site is 99.5%.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | week                          | Week                          | text      | text        |
| Yes      | numeric metric | total_downtime_minutes_       | Total Downtime (minutes)      | number    | number      |
| Yes      | numeric metric | city_website_uptime_          | City Website Uptime (%)       | percent   | percent     |
| Yes      | numeric metric | target_uptime_                | Target Uptime (%)             | percent   | percent     |
| Yes      | numeric metric | weeks_target_was_achieved     | Weeks Target Was Achieved     | number    | number      |
| Yes      | numeric metric | weeks_target_was_not_achieved | Weeks Target Was Not Achieved | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:icwn-eia9 d:2011-04-04T00:00:00.000Z m:city_website_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0

series e:icwn-eia9 d:2011-04-11T00:00:00.000Z m:city_website_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0

series e:icwn-eia9 d:2011-04-18T00:00:00.000Z m:city_website_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0
```

## Meta Commands

```ls
metric m:total_downtime_minutes_ p:integer l:"Total Downtime (minutes)" t:dataTypeName=number

metric m:city_website_uptime_ p:double l:"City Website Uptime (%)" t:dataTypeName=percent

metric m:target_uptime_ p:float l:"Target Uptime (%)" t:dataTypeName=percent

metric m:weeks_target_was_achieved p:long l:"Weeks Target Was Achieved" t:dataTypeName=number

metric m:weeks_target_was_not_achieved p:long l:"Weeks Target Was Not Achieved" t:dataTypeName=number

entity e:icwn-eia9 l:"Performance Metrics - Innovation & Technology - City Website Availability" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/icwn-eia9

property e:icwn-eia9 t:meta.view v:id=icwn-eia9 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Innovation & Technology - City Website Availability" v:attribution="City of Chicago"

property e:icwn-eia9 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:icwn-eia9 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| week                 | total_downtime_minutes_ | city_website_uptime_ | target_uptime_ | weeks_target_was_achieved | weeks_target_was_not_achieved | 
| ==================== | ======================= | ==================== | ============== | ========================= | ============================= | 
| Apr 04-10, 2011      | 0                       | 100                  | 99.50          |                           |                               | 
| Apr 11-17, 2011      | 0                       | 100                  | 99.50          |                           |                               | 
| Apr 18-24, 2011      | 0                       | 100                  | 99.50          |                           |                               | 
| Apr 25-30, 2011      | 10                      | 99.90                | 99.50          |                           |                               | 
| May 02-8, 2011       | 10                      | 99.90                | 99.50          |                           |                               | 
| May 09-15, 2011      | 100                     | 99                   | 99.50          |                           |                               | 
| May 16-22, 2011      | 0                       | 100                  | 99.50          |                           |                               | 
| May 23-29, 2011      | 0                       | 100                  | 99.50          |                           |                               | 
| May 30 - Jun 5, 2011 | 20                      | 99.80                | 99.50          |                           |                               | 
| Jun 06-12, 2011      | 20                      | 99.80                | 99.50          |                           |                               | 
```