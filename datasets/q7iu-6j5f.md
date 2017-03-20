# Capital District Transportation Authority (CDTA) Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-district-transportation-authority-cdta-performance-metrics) |
| Metadata | [Link](https://data.ny.gov/api/views/q7iu-6j5f) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q7iu-6j5f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q7iu-6j5f/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q7iu-6j5f |
| Name | Capital District Transportation Authority (CDTA) Performance Metrics |
| Attribution | Capital District Transportation Authority |
| Category | Transportation |
| Tags | transportation, performance, ridership |
| Created | 2013-03-03T18:22:23Z |
| Publication Date | 2016-02-08T17:05:38Z |
| Rows Updated | 2016-02-08T17:04:33Z |

## Description

CDTA is a public transportation authority in the Capital Region.  This dataset presents information that reflects the organizations performance levels.  This dataset includes customer boarding’s, miles operated, accidents, preventative maintenance inspections, and complaints.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | time           | month_year               | Month-Year               | calendar_date | calendar_date |
| Yes      | numeric metric | total_riders             | Total Riders             | number        | number        |
| Yes      | numeric metric | star_riders              | STAR Riders              | number        | number        |
| Yes      | numeric metric | fixed_riders             | Fixed Riders             | number        | number        |
| No       |                | pmi_not_on_time          | PMI-Not on Time          | number        | number        |
| Yes      | numeric metric | pmi_completed            | PMI Completed            | number        | number        |
| Yes      | numeric metric | star_denials             | Star Denials             | number        | number        |
| Yes      | numeric metric | service_interruptions    | Service Interruptions    | number        | number        |
| Yes      | numeric metric | miles                    | Miles                    | number        | number        |
| Yes      | numeric metric | mdbsi                    | MDBSI                    | number        | number        |
| Yes      | numeric metric | prevent_accidents        | Prevent Accidents        | number        | number        |
| Yes      | numeric metric | non_prevent_accidents    | Non-Prevent Accidents    | number        | number        |
| Yes      | numeric metric | fixed_shut_complaints    | Fixed/Shut Complaints    | number        | number        |
| Yes      | numeric metric | other_complaints         | Other Complaints         | number        | number        |
| Yes      | numeric metric | total_complaints         | Total Complaints         | number        | number        |
| Yes      | numeric metric | comp_not_address_10_days | Comp Not Address 10 Days | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = pmi_not_on_time
```

## Data Commands

```ls
series e:q7iu-6j5f d:2015-12-31T00:00:00.000Z m:pmi_completed=148 m:non_prevent_accidents=27 m:fixed_riders=1398444 m:total_riders=1425100 m:comp_not_address_10_days=37 m:other_complaints=118 m:star_denials=37 m:miles=861430 m:star_riders=26656 m:service_interruptions=0 m:total_complaints=354 m:prevent_accidents=16 m:fixed_shut_complaints=236 m:mdbsi=23440.27211

series e:q7iu-6j5f d:2015-11-30T00:00:00.000Z m:pmi_completed=140 m:non_prevent_accidents=23 m:fixed_riders=1412037 m:total_riders=1437740 m:comp_not_address_10_days=37 m:other_complaints=124 m:star_denials=35 m:miles=808316 m:star_riders=25703 m:service_interruptions=0 m:total_complaints=381 m:prevent_accidents=12 m:fixed_shut_complaints=257 m:mdbsi=23261

series e:q7iu-6j5f d:2015-10-31T00:00:00.000Z m:pmi_completed=141 m:non_prevent_accidents=33 m:fixed_riders=1590696 m:total_riders=1619277 m:comp_not_address_10_days=40 m:other_complaints=133 m:star_denials=28 m:miles=860916 m:star_riders=28581 m:service_interruptions=0 m:total_complaints=442 m:prevent_accidents=17 m:fixed_shut_complaints=309 m:mdbsi=30747
```

## Meta Commands

```ls
metric m:total_riders p:integer l:"Total Riders" d:"All vehicle boarding information." t:dataTypeName=number

metric m:star_riders p:integer l:"STAR Riders" d:"Flexible services boarding information." t:dataTypeName=number

metric m:fixed_riders p:integer l:"Fixed Riders" d:"Fixed route boarding information." t:dataTypeName=number

metric m:pmi_completed p:integer l:"PMI Completed" d:"Total number of specific inspection type completed in reporting period." t:dataTypeName=number

metric m:star_denials p:integer l:"Star Denials" d:"The number of trips unavailable one hour before or one hour after requested trip time, due to capacity constraints. Customer refusals are not included in this measure. Customer refusals are defined as when customers are provided with five alternative trip times all of which the customer denies." t:dataTypeName=number

metric m:service_interruptions p:integer l:"Service Interruptions" d:"Delays in service of five minutes or more." t:dataTypeName=number

metric m:miles p:integer l:Miles d:"Total miles operated." t:dataTypeName=number

metric m:mdbsi p:integer l:MDBSI d:"Mean Distance Between Service Interruption – Formula, miles/service interruptions." t:dataTypeName=number

metric m:prevent_accidents p:integer l:"Prevent Accidents" d:"The number of accidents with determination that operator failed to initiate a defensive driving action that may have prevented or reduced the severity of the accident." t:dataTypeName=number

metric m:non_prevent_accidents p:integer l:"Non-Prevent Accidents" d:"The number of accidents with determination that operator did not fail to initiate a defensive driving action that may have prevented or reduced the severity of the accident." t:dataTypeName=number

metric m:fixed_shut_complaints p:integer l:"Fixed/Shut Complaints" d:"Customer complaints relating to fixed and/or shuttle services." t:dataTypeName=number

metric m:other_complaints p:integer l:"Other Complaints" d:"Customer complaints relating to organizational issues outside of fixed and/or shuttle services." t:dataTypeName=number

metric m:total_complaints p:integer l:"Total Complaints" d:"All customer complaints during reporting period." t:dataTypeName=number

metric m:comp_not_address_10_days p:integer l:"Comp Not Address 10 Days" d:"Quantity of complaints that did not receive appropriate attention during expected parameter." t:dataTypeName=number

entity e:q7iu-6j5f l:"Capital District Transportation Authority (CDTA) Performance Metrics" t:attribution="Capital District Transportation Authority" t:url=https://data.ny.gov/api/views/q7iu-6j5f

property e:q7iu-6j5f t:meta.view v:id=q7iu-6j5f v:category=Transportation v:attributionLink="https://www.google.com/fusiontables/DataSource?docid=15Ha6CHeJv3MC0zlTjUSchdS6Otm6B_WCTja0r7k#rows:id=1" v:averageRating=0 v:name="Capital District Transportation Authority (CDTA) Performance Metrics" v:attribution="Capital District Transportation Authority"

property e:q7iu-6j5f t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q7iu-6j5f t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q7iu-6j5f t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```