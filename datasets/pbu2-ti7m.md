# Performance Dashboard - Department Of Natural Resources - Improving Quality Of Life (updated Annually)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-dashboard-department-of-natural-resources-improving-quality-of-life-updated-an) |
| Metadata | [Link](https://data.maryland.gov/api/views/pbu2-ti7m) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pbu2-ti7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pbu2-ti7m/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pbu2-ti7m |
| Name | Performance Dashboard - Department Of Natural Resources - Improving Quality Of Life (updated Annually) |
| Category | Energy and Environment |
| Created | 2016-07-07T21:06:20Z |
| Publication Date | 2016-10-24T19:40:05Z |

## Description

Data Sources: Water Quality data from MDNR Resource Assessment Service (T. Parham x8633), State Park Visitors from MDNR State Parks, Acres of Protected Lands (http://dnrweb.dnr.state.md.us/gis/plreports/report.asp) CREP, DNR, Forest Legacy, MET, and Rural Legacy data used

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                          | Name                                                                                                | Data Type     | Render Type   |
| ======== | ============== | =================================================================================================== | =================================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                                                | Date                                                                                                | calendar_date | calendar_date |
| No       |                | year                                                                                                | Fiscal Year                                                                                         | number        | text          |
| Yes      | numeric metric | percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen | Percentage of monitoring stations/tributaries reporting improving water quality trends for nitrogen | percent       | percent       |
| Yes      | numeric metric | number_of_visitors_using_state_parks_millions                                                       | Number of visitors using state parks (millions)                                                     | number        | number        |
| Yes      | numeric metric | acres_of_protected_land                                                                             | Acres of protected land (#)                                                                         | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:pbu2-ti7m d:2010-06-30T00:00:00.000Z m:number_of_visitors_using_state_parks_millions=10.1 m:percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen=24 m:acres_of_protected_land=11915

series e:pbu2-ti7m d:2011-06-30T00:00:00.000Z m:number_of_visitors_using_state_parks_millions=10.7 m:percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen=24.8 m:acres_of_protected_land=8828

series e:pbu2-ti7m d:2012-06-30T00:00:00.000Z m:number_of_visitors_using_state_parks_millions=11.08 m:percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen=31.2 m:acres_of_protected_land=9599
```

## Meta Commands

```ls
metric m:percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen p:double l:"Percentage of monitoring stations/tributaries reporting improving water quality trends for nitrogen" t:dataTypeName=percent

metric m:number_of_visitors_using_state_parks_millions p:float l:"Number of visitors using state parks (millions)" t:dataTypeName=number

metric m:acres_of_protected_land p:integer l:"Acres of protected land (#)" t:dataTypeName=number

entity e:pbu2-ti7m l:"Performance Dashboard - Department Of Natural Resources - Improving Quality Of Life (updated Annually)" t:url=https://data.maryland.gov/api/views/pbu2-ti7m

property e:pbu2-ti7m t:meta.view v:id=pbu2-ti7m v:category="Energy and Environment" v:averageRating=0 v:name="Performance Dashboard - Department Of Natural Resources - Improving Quality Of Life (updated Annually)"

property e:pbu2-ti7m t:meta.view.owner v:id=dghr-4bbx v:screenName="Allison Cordell" v:displayName="Allison Cordell"

property e:pbu2-ti7m t:meta.view.tableauthor v:id=dghr-4bbx v:screenName="Allison Cordell" v:roleName=editor v:displayName="Allison Cordell"
```

## Top Records

```ls
| date                | year | percentage_of_monitoring_stations_tributaries_reporting_improving_water_quality_trends_for_nitrogen | number_of_visitors_using_state_parks_millions | acres_of_protected_land | 
| =================== | ==== | =================================================================================================== | ============================================= | ======================= | 
| 2010-06-30T00:00:00 | 2010 | 24.00                                                                                               | 10.1                                          | 11915                   | 
| 2011-06-30T00:00:00 | 2011 | 24.80                                                                                               | 10.7                                          | 8828                    | 
| 2012-06-30T00:00:00 | 2012 | 31.20                                                                                               | 11.08                                         | 9599                    | 
| 2013-06-30T00:00:00 | 2013 | 36.00                                                                                               | 10.09                                         | 4640                    | 
| 2014-06-30T00:00:00 | 2014 | 37                                                                                                  | 10.3                                          | 8704                    | 
| 2015-06-30T00:00:00 | 2015 | 37                                                                                                  | 11.26                                         | 6389                    | 
| 2016-06-30T00:00:00 | 2016 |                                                                                                     | 12.9                                          |                         | 
```