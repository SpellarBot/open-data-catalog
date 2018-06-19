# Middle Snake Low Flow Trend Indicator 2005-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/middle-snake-low-flow-trend-indicator-2005-2013-d4f10) |
| Metadata | [Link](https://data.wa.gov/api/views/g8kr-9vgm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/g8kr-9vgm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/g8kr-9vgm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | g8kr-9vgm |
| Name | Middle Snake Low Flow Trend Indicator 2005-2013 |
| Attribution | Organization |
| Category | Natural Resources & Environment |
| Tags | flow, environment, indicator, salmon |
| Created | 2014-11-20T01:30:31Z |
| Publication Date | 2014-11-20T01:36:56Z |

## Description

Short-term flow trends from an expanded number of stations.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | stn_id         | Stn ID         | text      | text        |
| Yes      | series tag     | station_name   | Station Name   | text      | text        |
| Yes      | numeric metric | wria           | WRIA           | number    | number      |
| Yes      | numeric metric | m_k_p          | M-K p          | number    | number      |
| Yes      | numeric metric | reg_p          | Reg p          | number    | number      |
| Yes      | series tag     | trend_category | Trend category | text      | text        |
| Yes      | numeric metric | trend_cfs_yr   | Trend (cfs/yr) | number    | number      |
| Yes      | numeric metric | trend_year     | Trend (%/year) | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g8kr-9vgm d:2005-01-01T00:00:00.000Z t:station_name="Tucannon River near Marengo" t:stn_id=35B150 t:trend_category="Strong Increasing" m:trend_year=4.7 m:reg_p=0.018 m:trend_cfs_yr=3.219 m:m_k_p=0.016 m:wria=35

series e:g8kr-9vgm d:2005-01-01T00:00:00.000Z t:station_name="Asotin Creek above George Creek" t:stn_id=35D100 t:trend_category="No Trend" m:trend_year=-0.3 m:reg_p=0.717 m:trend_cfs_yr=-0.103 m:m_k_p=0.602 m:wria=35

series e:g8kr-9vgm d:2005-01-01T00:00:00.000Z t:station_name="Walla Walla River near Touchet" t:stn_id=14018500 t:trend_category="Strong Increasing" m:trend_year=20.3 m:reg_p=0.0004 m:trend_cfs_yr=3.91 m:m_k_p=0.002 m:wria=32
```

## Meta Commands

```ls
metric m:wria p:integer l:WRIA t:dataTypeName=number

metric m:m_k_p p:float l:"M-K p" t:dataTypeName=number

metric m:reg_p p:float l:"Reg p" t:dataTypeName=number

metric m:trend_cfs_yr p:float l:"Trend (cfs/yr)" t:dataTypeName=number

metric m:trend_year p:float l:"Trend (%/year)" t:dataTypeName=percent

entity e:g8kr-9vgm l:"Middle Snake Low Flow Trend Indicator 2005-2013" t:attribution=Organization t:url=https://data.wa.gov/api/views/g8kr-9vgm

property e:g8kr-9vgm t:meta.view v:id=g8kr-9vgm v:category="Natural Resources & Environment" v:averageRating=0 v:name="Middle Snake Low Flow Trend Indicator 2005-2013" v:attribution=Organization

property e:g8kr-9vgm t:meta.view.owner v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:displayName="Paul Pickett"

property e:g8kr-9vgm t:meta.view.tableauthor v:id=t29c-4u8y v:profileImageUrlMedium=/api/users/t29c-4u8y/profile_images/THUMB v:profileImageUrlLarge=/api/users/t29c-4u8y/profile_images/LARGE v:screenName="Paul Pickett" v:profileImageUrlSmall=/api/users/t29c-4u8y/profile_images/TINY v:roleName=publisher v:displayName="Paul Pickett"
```

## Top Records

```ls
| stn_id   | station_name                              | wria | m_k_p | reg_p  | trend_category    | trend_cfs_yr | trend_year | 
| ======== | ========================================= | ==== | ===== | ====== | ================= | ============ | ========== | 
| 35B150   | Tucannon River near Marengo               | 35   | 0.016 | 0.018  | Strong Increasing | 3.219        | 4.7        | 
| 35D100   | Asotin Creek above George Creek           | 35   | 0.602 | 0.717  | No Trend          | -0.103       | -0.3       | 
| 14018500 | Walla Walla River near Touchet            | 32   | 0.002 | 0.0004 | Strong Increasing | 3.910        | 20.3       | 
| 13344500 | Tucannon River near Starbuck              | 35   | 0.076 | 0.073  | Strong Increasing | 3.045        | 5.0        | 
| 13335050 | Asotin Creek at Asotin                    | 35   | 0.048 | 0.071  | Strong Increasing | 1.074        | 3.4        | 
| 13334450 | Asotin Creek below Confluence near Asotin | 35   | 1.000 | 0.696  | No Trend          | 0.138        | 0.4        | 
```