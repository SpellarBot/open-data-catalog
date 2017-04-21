# Performance Metrics - Innovation & Technology - Zoning Map Website Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-innovation-technology-zoning-map-website-availability-2e2c9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vqj9-rmbv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vqj9-rmbv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vqj9-rmbv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vqj9-rmbv |
| Name | Performance Metrics - Innovation & Technology - Zoning Map Website Availability |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, technology |
| Created | 2011-09-22T18:53:58Z |
| Publication Date | 2011-09-27T23:31:07Z |

## Description

The Zoning Map website is an interactive mapping site that allows users to determine the zoning classification for any area of the City. The percentage of the Zoning map website uptime, the amount of time the site was available, and the target uptime for each week are available by mousing over columns. The target availability for this site is 99.5%.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | week                          | Week                          | text      | text        |
| Yes      | numeric metric | total_downtime_minutes_       | Total Downtime (minutes)      | number    | number      |
| Yes      | numeric metric | zoning_map_site_uptime_       | Zoning Map Site Uptime (%)    | percent   | percent     |
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
series e:vqj9-rmbv d:2011-04-04T00:00:00.000Z m:zoning_map_site_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0

series e:vqj9-rmbv d:2011-04-11T00:00:00.000Z m:zoning_map_site_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0

series e:vqj9-rmbv d:2011-04-18T00:00:00.000Z m:zoning_map_site_uptime_=100 m:target_uptime_=99.5 m:total_downtime_minutes_=0
```

## Meta Commands

```ls
metric m:total_downtime_minutes_ p:integer l:"Total Downtime (minutes)" t:dataTypeName=number

metric m:zoning_map_site_uptime_ p:integer l:"Zoning Map Site Uptime (%)" t:dataTypeName=percent

metric m:target_uptime_ p:float l:"Target Uptime (%)" t:dataTypeName=percent

metric m:weeks_target_was_achieved p:long l:"Weeks Target Was Achieved" t:dataTypeName=number

metric m:weeks_target_was_not_achieved p:long l:"Weeks Target Was Not Achieved" t:dataTypeName=number

entity e:vqj9-rmbv l:"Performance Metrics - Innovation & Technology - Zoning Map Website Availability" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/vqj9-rmbv

property e:vqj9-rmbv t:meta.view v:id=vqj9-rmbv v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Innovation & Technology - Zoning Map Website Availability" v:attribution="City of Chicago"

property e:vqj9-rmbv t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:vqj9-rmbv t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| week                 | total_downtime_minutes_ | zoning_map_site_uptime_ | target_uptime_ | weeks_target_was_achieved | weeks_target_was_not_achieved | 
| ==================== | ======================= | ======================= | ============== | ========================= | ============================= | 
| Apr 4-10, 2011       | 0                       | 100                     | 99.50          |                           |                               | 
| Apr 11-17, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
| Apr 18-24, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
| Apr 25-30, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
| May 2-8, 2011        | 0                       | 100                     | 99.50          |                           |                               | 
| May 9-15, 2011       | 0                       | 100                     | 99.50          |                           |                               | 
| May 16-22, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
| May 23-29, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
| May 30 - Jun 5, 2011 | 0                       | 100                     | 99.50          |                           |                               | 
| Jun 06-12, 2011      | 0                       | 100                     | 99.50          |                           |                               | 
```