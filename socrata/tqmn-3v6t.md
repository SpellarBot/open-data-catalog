# Performance Metrics - Innovation & Technology - 311 Website Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-innovation-technology-311-website-availability-0bd85) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tqmn-3v6t) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tqmn-3v6t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tqmn-3v6t/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tqmn-3v6t |
| Name | Performance Metrics - Innovation & Technology - 311 Website Availability |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, technology |
| Created | 2011-09-22T18:48:16Z |
| Publication Date | 2011-09-27T23:27:58Z |

## Description

The 311 website allows residents to submit service requests or check the status of existing requests online. The percentage of 311 website uptime, the amount of time the site was available, and the target uptime for each week are available by mousing over columns. The target availability for this site is 99.5%.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | week                          | Week                          | text      | text        |
| Yes      | numeric metric | total_downtime_minutes_       | Total Downtime (minutes)      | number    | number      |
| Yes      | numeric metric | csr_site_uptime_              | CSR Site Uptime (%)           | percent   | percent     |
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
series e:tqmn-3v6t d:2011-04-04T00:00:00.000Z m:target_uptime_=99.5 m:total_downtime_minutes_=0 m:csr_site_uptime_=100

series e:tqmn-3v6t d:2011-04-11T00:00:00.000Z m:target_uptime_=99.5 m:total_downtime_minutes_=60 m:csr_site_uptime_=99.4

series e:tqmn-3v6t d:2011-04-18T00:00:00.000Z m:target_uptime_=99.5 m:total_downtime_minutes_=0 m:csr_site_uptime_=100
```

## Meta Commands

```ls
metric m:total_downtime_minutes_ p:integer l:"Total Downtime (minutes)" t:dataTypeName=number

metric m:csr_site_uptime_ p:double l:"CSR Site Uptime (%)" t:dataTypeName=percent

metric m:target_uptime_ p:float l:"Target Uptime (%)" t:dataTypeName=percent

metric m:weeks_target_was_achieved p:long l:"Weeks Target Was Achieved" t:dataTypeName=number

metric m:weeks_target_was_not_achieved p:long l:"Weeks Target Was Not Achieved" t:dataTypeName=number

entity e:tqmn-3v6t l:"Performance Metrics - Innovation & Technology - 311 Website Availability" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/tqmn-3v6t

property e:tqmn-3v6t t:meta.view v:id=tqmn-3v6t v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Innovation & Technology - 311 Website Availability" v:attribution="City of Chicago"

property e:tqmn-3v6t t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:tqmn-3v6t t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| week                 | total_downtime_minutes_ | csr_site_uptime_ | target_uptime_ | weeks_target_was_achieved | weeks_target_was_not_achieved | 
| ==================== | ======================= | ================ | ============== | ========================= | ============================= | 
| Apr 4-10, 2011       | 0                       | 100              | 99.50          |                           |                               | 
| Apr 11-17, 2011      | 60                      | 99.40            | 99.50          |                           |                               | 
| Apr 18-24, 2011      | 0                       | 100              | 99.50          |                           |                               | 
| Apr 25-30, 2011      | 0                       | 100              | 99.50          |                           |                               | 
| May 2-8, 2011        | 0                       | 100              | 99.50          |                           |                               | 
| May 9-15, 2011       | 0                       | 100              | 99.50          |                           |                               | 
| May 16-22, 2011      | 10                      | 99.90            | 99.50          |                           |                               | 
| May 23-29, 2011      | 20                      | 99.80            | 99.50          |                           |                               | 
| May 30 - Jun 5, 2011 | 0                       | 100              | 99.50          |                           |                               | 
| Jun 06-12, 2011      | 0                       | 100              | 99.50          |                           |                               | 
```