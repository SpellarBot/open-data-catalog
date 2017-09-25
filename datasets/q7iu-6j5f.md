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
| Yes      | numeric metric | pmi_not_on_time          | PMI-Not on Time          | number        | number        |
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
| No       |                | comp_not_address_10_days | Comp Not Address 10 Days | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = comp_not_address_10_days
```

## Data Commands

```ls
series e:q7iu-6j5f d:2015-12-31T00:00:00.000Z m:star_riders=26656 m:fixed_riders=1398444 m:other_complaints=118 m:non_prevent_accidents=27 m:star_denials=37 m:fixed_shut_complaints=236 m:miles=861430 m:mdbsi=23440.27211 m:pmi_not_on_time=3 m:total_complaints=354 m:pmi_completed=148 m:service_interruptions=0 m:prevent_accidents=16 m:total_riders=1425100

series e:q7iu-6j5f d:2015-11-30T00:00:00.000Z m:star_riders=25703 m:fixed_riders=1412037 m:other_complaints=124 m:non_prevent_accidents=23 m:star_denials=35 m:fixed_shut_complaints=257 m:miles=808316 m:mdbsi=23261 m:pmi_not_on_time=5 m:total_complaints=381 m:pmi_completed=140 m:service_interruptions=0 m:prevent_accidents=12 m:total_riders=1437740

series e:q7iu-6j5f d:2015-10-31T00:00:00.000Z m:star_riders=28581 m:fixed_riders=1590696 m:other_complaints=133 m:non_prevent_accidents=33 m:star_denials=28 m:fixed_shut_complaints=309 m:miles=860916 m:mdbsi=30747 m:pmi_not_on_time=3 m:total_complaints=442 m:pmi_completed=141 m:service_interruptions=0 m:prevent_accidents=17 m:total_riders=1619277
```

## Meta Commands

```ls
metric m:total_riders p:integer l:"Total Riders" d:"All vehicle boarding information." t:dataTypeName=number

metric m:star_riders p:integer l:"STAR Riders" d:"Flexible services boarding information." t:dataTypeName=number

metric m:fixed_riders p:integer l:"Fixed Riders" d:"Fixed route boarding information." t:dataTypeName=number

metric m:pmi_not_on_time p:integer l:"PMI-Not on Time" d:"Quantity of inspections not completed within threshold." t:dataTypeName=number

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

entity e:q7iu-6j5f l:"Capital District Transportation Authority (CDTA) Performance Metrics" t:attribution="Capital District Transportation Authority" t:url=https://data.ny.gov/api/views/q7iu-6j5f

property e:q7iu-6j5f t:meta.view d:2017-09-25T07:22:28.733Z v:averageRating=0 v:name="Capital District Transportation Authority (CDTA) Performance Metrics" v:attribution="Capital District Transportation Authority" v:attributionLink="https://www.google.com/fusiontables/DataSource?docid=15Ha6CHeJv3MC0zlTjUSchdS6Otm6B_WCTja0r7k#rows:id=1" v:id=q7iu-6j5f v:category=Transportation

property e:q7iu-6j5f t:meta.view.owner d:2017-09-25T07:22:28.733Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:q7iu-6j5f t:meta.view.tableauthor d:2017-09-25T07:22:28.733Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:q7iu-6j5f t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:22:28.733Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| month_year          | total_riders | star_riders | fixed_riders | pmi_not_on_time | pmi_completed | star_denials | service_interruptions | miles  | mdbsi       | prevent_accidents | non_prevent_accidents | fixed_shut_complaints | other_complaints | total_complaints | comp_not_address_10_days | 
| =================== | ============ | =========== | ============ | =============== | ============= | ============ | ===================== | ====== | =========== | ================= | ===================== | ===================== | ================ | ================ | ======================== | 
| 2015-12-31T00:00:00 | 1425100      | 26656       | 1398444      | 3               | 148           | 37           | 0                     | 861430 | 23440.27211 | 16                | 27                    | 236                   | 118              | 354              | 37                       | 
| 2015-11-30T00:00:00 | 1437740      | 25703       | 1412037      | 5               | 140           | 35           | 0                     | 808316 | 23261       | 12                | 23                    | 257                   | 124              | 381              | 37                       | 
| 2015-10-31T00:00:00 | 1619277      | 28581       | 1590696      | 3               | 141           | 28           | 0                     | 860916 | 30747       | 17                | 33                    | 309                   | 133              | 442              | 40                       | 
| 2015-09-30T00:00:00 | 1535299      | 27670       | 1507629      | 0               | 130           | 25           | 0                     | 832236 | 32960       | 16                | 32                    | 301                   | 116              | 417              | 21                       | 
| 2015-08-31T00:00:00 | 1384909      | 26912       | 1357997      | 0               | 131           | 133          | 0                     | 830451 | 6232        | 14                | 18                    | 266                   | 91               | 357              | 51                       | 
| 2015-07-31T00:00:00 | 1325164      | 28409       | 1296755      | 1               | 146           | 38           | 0                     | 881345 | 23193       | 13                | 35                    | 234                   | 78               | 312              | 28                       | 
| 2015-06-30T00:00:00 | 1315776      | 26744       | 1289032      | 3               | 138           | 47           | 0                     | 859454 | 18483       | 12                | 36                    | 221                   | 63               | 284              | 20                       | 
| 2015-05-31T00:00:00 | 1387495      | 26651       | 1360844      | 2               | 131           | 65           | 0                     | 835493 | 12953       | 16                | 23                    | 278                   | 89               | 367              | 38                       | 
| 2015-04-30T00:00:00 | 1507278      | 27787       | 1479491      | 2               | 153           | 73           | 0                     | 839597 | 11462       | 12                | 27                    | 172                   | 72               | 244              | 15                       | 
| 2015-03-31T00:00:00 | 1471333      | 28648       | 1442685      | 0               | 131           | 27           | 0                     | 888616 | 33533       | 18                | 26                    | 206                   | 93               | 299              | 28                       | 
```