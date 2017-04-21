# Performance Metrics - Innovation & Technology - Site Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-innovation-technology-site-availability-2ba2a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zfg3-p7xv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zfg3-p7xv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zfg3-p7xv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zfg3-p7xv |
| Name | Performance Metrics - Innovation & Technology - Site Availability |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, technology |
| Created | 2011-09-28T21:53:38Z |
| Publication Date | 2011-10-07T18:07:44Z |

## Description

The website availability metrics below are derived from an automated monitor that sends a request every two minutes to each website. The website is considered unavailable if the response to any request takes longer than a pre-defined wait time. The monitors run continuously and are not normally disabled during scheduled maintenance or downtime, so the reported metrics incorporate both planned and unplanned downtime.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                     | Data Type | Render Type |
| ======== | ============== | ======================= | ======================== | ========= | =========== |
| No       | time           | :updated_at             | updated_at               | meta_data | meta_data   |
| No       |                | week                    | Week                     | text      | text        |
| Yes      | series tag     | site_name               | Site Name                | text      | text        |
| Yes      | numeric metric | total_downtime_minutes_ | Total Downtime (Minutes) | number    | number      |
| Yes      | numeric metric | site_uptime_            | Site Uptime (%)          | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = week
```

## Data Commands

```ls
series e:zfg3-p7xv d:2011-10-07T11:07:18.000Z t:site_name="City Internet Website Availability" m:total_downtime_minutes_=6 m:site_uptime_=99.94

series e:zfg3-p7xv d:2011-10-07T11:07:18.000Z t:site_name="Explore Chicago Website Availability" m:total_downtime_minutes_=6 m:site_uptime_=99.94

series e:zfg3-p7xv d:2011-10-07T11:07:18.000Z t:site_name="IPI Portal Website Availability" m:total_downtime_minutes_=4 m:site_uptime_=99.96
```

## Meta Commands

```ls
metric m:total_downtime_minutes_ p:float l:"Total Downtime (Minutes)" t:dataTypeName=number

metric m:site_uptime_ p:double l:"Site Uptime (%)" t:dataTypeName=percent

entity e:zfg3-p7xv l:"Performance Metrics - Innovation & Technology - Site Availability" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zfg3-p7xv

property e:zfg3-p7xv t:meta.view v:id=zfg3-p7xv v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=90 v:name="Performance Metrics - Innovation & Technology - Site Availability" v:attribution="City of Chicago"

property e:zfg3-p7xv t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:zfg3-p7xv t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | week                  | site_name                              | total_downtime_minutes_ | site_uptime_ | 
| =========== | ===================== | ====================================== | ======================= | ============ | 
| 1317985638  | 09/26/2011-10/02/2011 | City Internet Website Availability     | 6.0                     | 99.94        | 
| 1317985638  | 09/26/2011-10/02/2011 | Explore Chicago Website Availability   | 6.0                     | 99.94        | 
| 1317985638  | 09/26/2011-10/02/2011 | IPI Portal Website Availability        | 4.0                     | 99.96        | 
| 1317985638  | 09/26/2011-10/02/2011 | CSR Website Availability               | 0.0                     | 100          | 
| 1317985638  | 09/26/2011-10/02/2011 | Map Chicago Website Availability (GIS) | 0.0                     | 100          | 
| 1317985638  | 09/26/2011-10/02/2011 | Zoning Map Website Availability (GIS)  | 0.0                     | 100          | 
| 1318219373  | 10/03/2011-10/09/2011 | Explore Chicago Website Availability   | 20.0                    | 99.802       | 
| 1318219373  | 10/03/2011-10/09/2011 | City Internet Website Availability     | 4.0                     | 99.96        | 
| 1318219373  | 10/03/2011-10/09/2011 | IPI Portal Website Availability        | 4.0                     | 99.96        | 
| 1318219373  | 10/03/2011-10/09/2011 | CSR Website Availability               | 0.0                     | 100          | 
```