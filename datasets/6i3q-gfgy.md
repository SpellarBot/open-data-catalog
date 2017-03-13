# Summer Low Flow Trend Indicator 1975-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summer-low-flow-trend-indicator-1975-2014) |
| Metadata | [Link](https://data.wa.gov/api/views/6i3q-gfgy) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/6i3q-gfgy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/6i3q-gfgy/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 6i3q-gfgy |
| Name | Summer Low Flow Trend Indicator 1975-2014 |
| Attribution | Washington State Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | flow, indicator, trend, gages, ecology, eap, salmon, puget sound, state-of-the-salmon |
| Created | 2015-04-21T22:33:41Z |
| Publication Date | 2015-04-22T00:21:17Z |
| Rows Updated | 2015-04-22T00:19:06Z |

## Description

Summer Low Flow Trend Indicator results, statewide, updated through Oct 2014 

This information is updated annually with an additional year of flow data. These results are provided to the Puget Sound Partnership for their Vital Signs (http://www.psp.wa.gov/vitalsigns/summer_stream_flows.php) and to the Governor's Salmon Recovery Office for the "State of Salmon in Watersheds" report (http://stateofsalmon.wa.gov/statewide/indicators/water-quantity). 

The attached document "WR Indicator Outcomes Memo - 10-24-10.pdf" describes the methodology for developing these indicators. The attached document "Low Flow Indicator Metadata.pdf" describes the contents of each column. 

Dept. of Ecology home page: http://www.ecy.wa.gov/ 

Disclaimer: 
Information provided by Ecology on this Web site is accurate to the best of Ecology's knowledge and is subject to change on a regular basis, without notice. Ecology cannot and does not warrant that the information on this Web site is absolutely current, although every effort is made to ensure that it is kept as current as possible. Ecology cannot and does not warrant the accuracy of these documents beyond the source documents, although every attempt is made to work from authoritative sources. Links to related sites are provided as a courtesy, but Ecology is not responsible for their availability, content or policies.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | stn_id                 | Stn ID                 | text      | text        |
| Yes      | series tag     | station_name           | Station Name           | text      | text        |
| Yes      | series tag     | salmon_region          | Salmon Region          | text      | text        |
| Yes      | numeric metric | wria                   | WRIA                   | number    | number      |
| Yes      | numeric metric | trib_level             | Trib Level             | number    | number      |
| Yes      | numeric metric | m_k_p                  | M-K p                  | number    | number      |
| Yes      | numeric metric | reg_p                  | Reg p                  | number    | number      |
| Yes      | series tag     | trend_category         | Trend category         | text      | text        |
| Yes      | numeric metric | trend_cfs_yr           | Trend (cfs/yr)         | number    | number      |
| Yes      | numeric metric | trend_year             | Trend (%/year)         | percent   | percent     |
| Yes      | series tag     | cat_change_from_2011   | Cat. Change from 2011  | text      | text        |
| Yes      | series tag     | trend_change_from_2013 | Trend Change from 2013 | text      | text        |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6i3q-gfgy d:1975-01-01T00:00:00.000Z t:trend_change_from_2013=down t:station_name="ANDREWS CREEK NEAR MAZAMA, WA" t:salmon_region=UC t:stn_id=12447390 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.2 m:reg_p=0.728 m:trib_level=4 m:trend_cfs_yr=0.02 m:m_k_p=0.709 m:wria=48

series e:6i3q-gfgy d:1975-01-01T00:00:00.000Z t:trend_change_from_2013=up t:station_name="BIG SOOS CREEK ABOVE HATCHERY NR AUBURN" t:salmon_region=PS t:stn_id=12112600 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.1 m:reg_p=0.837 m:trib_level=2 m:trend_cfs_yr=0.02 m:m_k_p=0.666 m:wria=9

series e:6i3q-gfgy d:1975-01-01T00:00:00.000Z t:trend_change_from_2013=down t:station_name="CHAMOKANE CREEK BELOW FALLS NEAR LONG LAKE, WA" t:salmon_region=NE t:stn_id=12433200 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.1 m:reg_p=0.801 m:trib_level=3 m:trend_cfs_yr=0.02 m:m_k_p=0.619 m:wria=54
```

## Meta Commands

```ls
metric m:wria p:integer l:WRIA t:dataTypeName=number

metric m:trib_level p:integer l:"Trib Level" t:dataTypeName=number

metric m:m_k_p p:float l:"M-K p" t:dataTypeName=number

metric m:reg_p p:float l:"Reg p" t:dataTypeName=number

metric m:trend_cfs_yr p:float l:"Trend (cfs/yr)" t:dataTypeName=number

metric m:trend_year p:float l:"Trend (%/year)" t:dataTypeName=percent

entity e:6i3q-gfgy l:"Summer Low Flow Trend Indicator 1975-2014" t:attribution="Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/6i3q-gfgy

property e:6i3q-gfgy t:meta.view v:id=6i3q-gfgy v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov v:averageRating=0 v:name="Summer Low Flow Trend Indicator 1975-2014" v:attribution="Washington State Department of Ecology"

property e:6i3q-gfgy t:meta.view.license v:name="Public Domain"

property e:6i3q-gfgy t:meta.view.owner v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"

property e:6i3q-gfgy t:meta.view.tableauthor v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"
```