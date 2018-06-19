# EMS - FY2016 Response Time Performance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-fy2016-response-time-performance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/akcn-m4jp) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/akcn-m4jp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/akcn-m4jp/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | akcn-m4jp |
| Name | EMS - FY2016 Response Time Performance |
| Category | Public Safety |
| Tags | ems, atcems, response time performance, fy2016, operations |
| Created | 2016-10-31T14:16:23Z |
| Publication Date | 2016-10-31T16:10:23Z |

## Description

** Static Data Set ** This table shows ATCEMS compliance with response time goals for Fiscal Year 2016.  Performance is broken out by response zone (City of Austin vs. Travis County) and response priority.  See the attached PDF for more information on the data contained in this table. THE DATA IN THIS TABLE WILL NOT BE UPDATED.*

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | incident_priority | Incident Priority | text      | text        |
| Yes      | numeric metric | city_of_austin    | City of Austin    | percent   | percent     |
| Yes      | numeric metric | travis_county     | Travis County     | percent   | percent     |
| Yes      | numeric metric | system_wide       | System-Wide       | percent   | percent     |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:akcn-m4jp d:2016-01-01T00:00:00.000Z t:incident_priority="Priority 1" m:travis_county=76.73 m:city_of_austin=91.45 m:system_wide=89.16

series e:akcn-m4jp d:2016-01-01T00:00:00.000Z t:incident_priority="Priority 2" m:travis_county=86.13 m:city_of_austin=94.55 m:system_wide=93.06

series e:akcn-m4jp d:2016-01-01T00:00:00.000Z t:incident_priority="Priority 3" m:travis_county=91.52 m:city_of_austin=97.09 m:system_wide=96.33
```

## Meta Commands

```ls
metric m:city_of_austin p:float l:"City of Austin" d:"Response time goal compliance within the full-purpose jurisdiction of the City of Austin, expressed as a percentage of all incidents. Limited purpose jurisdictions are not included in this measure." t:dataTypeName=percent

metric m:travis_county p:float l:"Travis County" d:"Response time goal compliance in Travis County, outside the full purpose jurisdiction of the City of Austin, expressed as a percentage of all incidents. This area includes Austin?s limited purpose jurisdictions." t:dataTypeName=percent

metric m:system_wide p:float l:System-Wide d:"Response time goal compliance for City of Austin and Travis County, combined, expressed as a percentage of all incidents." t:dataTypeName=percent

entity e:akcn-m4jp l:"EMS - FY2016 Response Time Performance" t:url=https://data.austintexas.gov/api/views/akcn-m4jp

property e:akcn-m4jp t:meta.view v:id=akcn-m4jp v:category="Public Safety" v:averageRating=0 v:name="EMS - FY2016 Response Time Performance"

property e:akcn-m4jp t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:akcn-m4jp t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| incident_priority | city_of_austin | travis_county | system_wide | 
| ================= | ============== | ============= | =========== | 
| Priority 1        | 91.45          | 76.73         | 89.16       | 
| Priority 2        | 94.55          | 86.13         | 93.06       | 
| Priority 3        | 97.09          | 91.52         | 96.33       | 
| Priority 4        | 97.41          | 95.48         | 97.12       | 
| Priority 5        | 93.73          | 91.06         | 93.35       | 
| All Priorities    | 95.68          | 89.97         | 94.80       | 
```