# Summer Low Flow Trend Indicator 1975-2014

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/6i3q-gfgy/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/summer-low-flow-trend-indicator-1975-2014)
* [Metadata URL](https://data.wa.gov/api/views/6i3q-gfgy)
* Id = 6i3q-gfgy
* Name = Summer Low Flow Trend Indicator 1975-2014
* Attribution = Washington State Department of Ecology
* [Attribution Link](http://www.ecy.wa.gov)
* Category = Natural Resources & Environment
* Tags = [flow, indicator, trend, gages, ecology, eap, salmon, puget sound, state-of-the-salmon]
* Created = 2015-04-21T22:33:41Z
* Publication Date = 2015-04-22T00:21:17Z
* Rows Updated = 2015-04-22T00:19:06Z

## Description

Summer Low Flow Trend Indicator results, statewide, updated through Oct 2014 

This information is updated annually with an additional year of flow data. These results are provided to the Puget Sound Partnership for their Vital Signs (http://www.psp.wa.gov/vitalsigns/summer_stream_flows.php) and to the Governor's Salmon Recovery Office for the "State of Salmon in Watersheds" report (http://stateofsalmon.wa.gov/statewide/indicators/water-quantity). 

The attached document "WR Indicator Outcomes Memo - 10-24-10.pdf" describes the methodology for developing these indicators. The attached document "Low Flow Indicator Metadata.pdf" describes the contents of each column. 

Dept. of Ecology home page: http://www.ecy.wa.gov/ 

Disclaimer: 
Information provided by Ecology on this Web site is accurate to the best of Ecology's knowledge and is subject to change on a regular basis, without notice. Ecology cannot and does not warrant that the information on this Web site is absolutely current, although every effort is made to ensure that it is kept as current as possible. Ecology cannot and does not warrant the accuracy of these documents beyond the source documents, although every attempt is made to work from authoritative sources. Links to related sites are provided as a courtesy, but Ecology is not responsible for their availability, content or policies.

## Columns

```ls
| Name                   | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| ====================== | ====================== | ========= | =========== | ============== | ======== | 
| updated_at             | :updated_at            | meta_data | meta_data   | time           | No       | 
| Stn ID                 | stn_id                 | text      | text        | series tag     | Yes      | 
| Station Name           | station_name           | text      | text        | series tag     | Yes      | 
| Salmon Region          | salmon_region          | text      | text        | series tag     | Yes      | 
| WRIA                   | wria                   | number    | number      | numeric metric | Yes      | 
| Trib Level             | trib_level             | number    | number      | numeric metric | Yes      | 
| M-K p                  | m_k_p                  | number    | number      | numeric metric | Yes      | 
| Reg p                  | reg_p                  | number    | number      | numeric metric | Yes      | 
| Trend category         | trend_category         | text      | text        | series tag     | Yes      | 
| Trend (cfs/yr)         | trend_cfs_yr           | number    | number      | numeric metric | Yes      | 
| Trend (%/year)         | trend_year             | percent   | percent     | numeric metric | Yes      | 
| Cat. Change from 2011  | cat_change_from_2011   | text      | text        | series tag     | Yes      | 
| Trend Change from 2013 | trend_change_from_2013 | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:6i3q-gfgy d:2015-04-21T17:13:37.000Z t:trend_change_from_2013=down t:station_name="ANDREWS CREEK NEAR MAZAMA, WA" t:salmon_region=UC t:stn_id=12447390 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.2 m:reg_p=0.728 m:trib_level=4 m:trend_cfs_yr=0.02 m:m_k_p=0.709 m:wria=48

series e:6i3q-gfgy d:2015-04-21T17:13:37.000Z t:trend_change_from_2013=up t:station_name="BIG SOOS CREEK ABOVE HATCHERY NR AUBURN" t:salmon_region=PS t:stn_id=12112600 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.1 m:reg_p=0.837 m:trib_level=2 m:trend_cfs_yr=0.02 m:m_k_p=0.666 m:wria=9

series e:6i3q-gfgy d:2015-04-21T17:13:37.000Z t:trend_change_from_2013=down t:station_name="CHAMOKANE CREEK BELOW FALLS NEAR LONG LAKE, WA" t:salmon_region=NE t:stn_id=12433200 t:trend_category="no trend" t:cat_change_from_2011=same m:trend_year=0.1 m:reg_p=0.801 m:trib_level=3 m:trend_cfs_yr=0.02 m:m_k_p=0.619 m:wria=54
```

## Meta Commands

```ls
metric m:wria p:integer l:WRIA t:dataTypeName=number

metric m:trib_level p:integer l:"Trib Level" t:dataTypeName=number

metric m:m_k_p l:"M-K p" t:dataTypeName=number

metric m:reg_p l:"Reg p" t:dataTypeName=number

metric m:trend_cfs_yr l:"Trend (cfs/yr)" t:dataTypeName=number

entity e:6i3q-gfgy l:"Summer Low Flow Trend Indicator 1975-2014" t:attribution="Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/6i3q-gfgy

property e:6i3q-gfgy t:meta.view d:2017-03-07T18:20:29.541Z v:id=6i3q-gfgy v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov v:averageRating=0 v:name="Summer Low Flow Trend Indicator 1975-2014" v:attribution="Washington State Department of Ecology"

property e:6i3q-gfgy t:meta.view.license d:2017-03-07T18:20:29.541Z v:name="Public Domain"

property e:6i3q-gfgy t:meta.view.owner d:2017-03-07T18:20:29.541Z v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"

property e:6i3q-gfgy t:meta.view.tableauthor d:2017-03-07T18:20:29.541Z v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"
```