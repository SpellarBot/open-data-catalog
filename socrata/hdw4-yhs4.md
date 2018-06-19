# Summer Low Flow Trend Indicator 1975-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summer-low-flow-trend-indicator-1975-2013-b0aa0) |
| Metadata | [Link](https://data.wa.gov/api/views/hdw4-yhs4) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hdw4-yhs4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hdw4-yhs4/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hdw4-yhs4 |
| Name | Summer Low Flow Trend Indicator 1975-2013 |
| Attribution | Washington State Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | flow, indicator, trend, gages, ecology, eap, salmon, puget sound, state-of-the-salmon |
| Created | 2014-04-09T00:51:09Z |
| Publication Date | 2014-09-23T18:49:25Z |

## Description

Summer Low Flow Trend Indicator results, statewide, updated through Oct 2013. 

This information is updated annually with an additional year of flow data. These results are provided to the Puget Sound Partnership for their Vital Signs (http://www.psp.wa.gov/vitalsigns/summer_stream_flows.php) and to the Governor's Salmon Recovery Office for the "State of Salmon in WAtersheds" report (http://stateofsalmon.wa.gov/statewide/indicators/water-quantity). 

The attached document "WR Indicator Outcomes Memo - 10-24-10.pdf" describes the methodology for developing these indicators. 

The attached document "Low Flow Indicator Metadata.pdf" describes the contents of each column. 

Dept. of Ecology home page: http://www.ecy.wa.gov/ 

Disclaimer: 
Information provided by Ecology on this Web site is accurate to the best of Ecology's knowledge and is subject to change on a regular basis, without notice. Ecology cannot and does not warrant that the information on this Web site is absolutely current, although every effort is made to ensure that it is kept as current as possible. Ecology cannot and does not warrant the accuracy of these documents beyond the source documents, although every attempt is made to work from authoritative sources. Links to related sites are provided as a courtesy, but Ecology is not responsible for their availability, content or policies.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| Yes      | series tag     | stn_id               | Stn ID                | text      | text        |
| Yes      | series tag     | station_name         | Station Name          | text      | text        |
| Yes      | series tag     | salmon_region        | Salmon Region         | text      | text        |
| Yes      | numeric metric | wria                 | WRIA                  | number    | number      |
| Yes      | numeric metric | trib_level           | Trib Level            | number    | number      |
| Yes      | numeric metric | m_k_p                | M-K p                 | number    | number      |
| Yes      | numeric metric | reg_p                | Reg p                 | number    | number      |
| Yes      | series tag     | trend_category       | Trend category        | text      | text        |
| Yes      | numeric metric | trend_cfs_yr         | Trend (cfs/yr)        | number    | number      |
| Yes      | numeric metric | trend_year           | Trend (%/year)        | percent   | percent     |
| Yes      | series tag     | cat_change_from_2011 | Cat. Change from 2011 | text      | text        |
| Yes      | series tag     | change_from_2012     | Change from 2012      | text      | text        |
```

## Time Field

```ls
Value = 1975
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hdw4-yhs4 d:1975-01-01T00:00:00.000Z t:station_name="DUCKABUSH RIVER NR BRINNON" t:change_from_2012=up t:salmon_region="Hood Canal" t:stn_id=12054000 t:trend_category="No Trend" t:cat_change_from_2011=wi->nt m:trend_year=0.2 m:reg_p=0.712 m:trib_level=1 m:trend_cfs_yr=0.2 m:m_k_p=0.529 m:wria=16

series e:hdw4-yhs4 d:1975-01-01T00:00:00.000Z t:station_name="NF SKOKOMISH RIVER BLW STAIRCASE RPDS" t:change_from_2012=up t:salmon_region="Hood Canal" t:stn_id=12056500 t:trend_category="No Trend" t:cat_change_from_2011=wd??->nt m:trend_year=-0.3 m:reg_p=0.676 m:trib_level=2 m:trend_cfs_yr=-0.2 m:m_k_p=0.514 m:wria=16

series e:hdw4-yhs4 d:1975-01-01T00:00:00.000Z t:station_name="KLICKITAT RIVER NEAR PITT" t:change_from_2012=up t:salmon_region="Middle Columbia" t:stn_id=14113000 t:trend_category="No Trend" t:cat_change_from_2011=same m:trend_year=0.2 m:reg_p=0.555 m:trib_level=2 m:trend_cfs_yr=1.3 m:m_k_p=0.611 m:wria=30
```

## Meta Commands

```ls
metric m:wria p:integer l:WRIA t:dataTypeName=number

metric m:trib_level p:integer l:"Trib Level" t:dataTypeName=number

metric m:m_k_p p:float l:"M-K p" t:dataTypeName=number

metric m:reg_p p:float l:"Reg p" t:dataTypeName=number

metric m:trend_cfs_yr p:float l:"Trend (cfs/yr)" t:dataTypeName=number

metric m:trend_year p:float l:"Trend (%/year)" t:dataTypeName=percent

entity e:hdw4-yhs4 l:"Summer Low Flow Trend Indicator 1975-2013" t:attribution="Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/hdw4-yhs4

property e:hdw4-yhs4 t:meta.view v:id=hdw4-yhs4 v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov v:averageRating=80 v:name="Summer Low Flow Trend Indicator 1975-2013" v:attribution="Washington State Department of Ecology"

property e:hdw4-yhs4 t:meta.view.license v:name="Public Domain"

property e:hdw4-yhs4 t:meta.view.owner v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:displayName="Paul Pickett"

property e:hdw4-yhs4 t:meta.view.tableauthor v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"
```

## Top Records

```ls
| stn_id   | station_name                                   | salmon_region        | wria | trib_level | m_k_p | reg_p | trend_category | trend_cfs_yr | trend_year | cat_change_from_2011 | change_from_2012 | 
| ======== | ============================================== | ==================== | ==== | ========== | ===== | ===== | ============== | ============ | ========== | ==================== | ================ | 
| 12054000 | DUCKABUSH RIVER NR BRINNON                     | Hood Canal           | 16   | 1          | 0.529 | 0.712 | No Trend       | 0.2          | 0.2        | wi->nt               | up               | 
| 12056500 | NF SKOKOMISH RIVER BLW STAIRCASE RPDS          | Hood Canal           | 16   | 2          | 0.514 | 0.676 | No Trend       | -0.2         | -0.3       | wd??->nt             | up               | 
| 14113000 | KLICKITAT RIVER NEAR PITT                      | Middle Columbia      | 30   | 2          | 0.611 | 0.555 | No Trend       | 1.3          | 0.2        | same                 | up               | 
| TNAW     | TEANAWAY RIVER AT FORKS NEAR CLE ELUM          | Middle Columbia      | 39   | 3          | 0.981 | 0.716 | No Trend       | -0.03        | -0.2       | wd->nt               | up               | 
| 12397100 | OUTLET CREEK NEAR METALINE FALLS, WA           | Northeast Washington | 62   | 4          | 0.570 | 0.967 | No Trend       | -0.004       | -0.02      | wd->nt               | up               | 
| 12433200 | CHAMOKANE CREEK BELOW FALLS NEAR LONG LAKE, WA | Northeast Washington | 54   | 3          | 0.583 | 0.766 | No Trend       | 0.03         | 0.1        | same                 | down             | 
| 12213100 | NOOKSACK RIVER AT FERNDALE                     | Puget Sound          | 1    | 1          | 0.514 | 0.669 | No Trend       | -2.1         | -0.2       | wd->nt               | up               | 
| 12113000 | GREEN RIVER NEAR AUBURN                        | Puget Sound          | 9    | 1          | 0.578 | 0.981 | No Trend       | 0.02         | 0.01       | same                 | up               | 
| 12039500 | QUINAULT RIVER AT QUINAULT LAKE                | Washington Coast     | 21   | 1          | 0.611 | 0.911 | No Trend       | 0.3          | 0.1        | same                 | up               | 
| 12447390 | ANDREWS CREEK NEAR MAZAMA, WA                  | Upper Columbia       | 48   | 4          | 0.799 | 0.724 | No Trend       | 0.02         | 0.3        | wd->nt               | up               | 
```