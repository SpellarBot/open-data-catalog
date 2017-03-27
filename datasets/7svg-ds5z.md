# Traffic Flow Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-flow-counts-8225e) |
| Metadata | [Link](https://data.seattle.gov/api/views/7svg-ds5z) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7svg-ds5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7svg-ds5z/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7svg-ds5z |
| Name | Traffic Flow Counts |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | seattle, traffic, counts, volumes, transportation |
| Created | 2010-11-04T17:59:40Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Vehicle traffic volumes for arterial streets in Seattle based on spot studies that have been adjusted for seasonal variation.
To provide a high level view of traffic volumes on major streets in Seattle, and compare changes from year to year.
The AAWDT count is a seasonally adjusted average weekday daily total of vehicle traffic for all lanes, i.e. total vehicles in both directions for one average 24-hour business day, Monday through Friday. Only selected arterial streets are included.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | downtown   | DOWNTOWN | checkbox  | checkbox    |
| Yes      | series tag     | stname     | STNAME   | text      | text        |
| Yes      | time           | year       | YEAR     | number    | number      |
| Yes      | numeric metric | aawdt      | AAWDT    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7svg-ds5z d:2009-01-01T00:00:00.000Z t:stname="N 45TH ST" t:downtown=false m:aawdt=22200

series e:7svg-ds5z d:2009-01-01T00:00:00.000Z t:stname="NE 80TH ST" t:downtown=false m:aawdt=9500

series e:7svg-ds5z d:2009-01-01T00:00:00.000Z t:stname="DENNY WAY" t:downtown=true m:aawdt=30200
```

## Meta Commands

```ls
metric m:aawdt p:float l:AAWDT t:dataTypeName=number

entity e:7svg-ds5z l:"Traffic Flow Counts" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/7svg-ds5z

property e:7svg-ds5z t:meta.view v:id=7svg-ds5z v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation v:averageRating=0 v:name="Traffic Flow Counts" v:attribution="Seattle Department of Transportation"

property e:7svg-ds5z t:meta.view.license v:name="Public Domain"

property e:7svg-ds5z t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:7svg-ds5z t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```