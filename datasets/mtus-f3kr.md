# DPD.ECA_FLOOD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dpd-eca-flood-bb2cd) |
| Metadata | [Link](https://data.seattle.gov/api/views/mtus-f3kr) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/mtus-f3kr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/mtus-f3kr/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | mtus-f3kr |
| Name | DPD.ECA_FLOOD |
| Attribution | Seattle GIS Program |
| Category | Land Base |
| Tags | environmental critical areas, flood, flood prone |
| Created | 2011-12-14T21:40:12Z |
| Publication Date | 2011-12-27T19:57:00Z |

## Description

Critical area designation: flood / flood prone areas

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type  | Render Type |
| ======== | ============== | ============ | ============ | ========== | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data  | meta_data   |
| Yes      | series tag     | objectid     | OBJECTID     | text       | number      |
| Yes      | series tag     | shape        | Shape        | geospatial | geospatial  |
| Yes      | numeric metric | donut        | DONUT        | number     | number      |
| Yes      | numeric metric | flood        | FLOOD        | number     | text        |
| Yes      | numeric metric | area         | AREA         | number     | number      |
| Yes      | numeric metric | len          | LEN          | number     | number      |
| Yes      | numeric metric | shape_length | Shape_Length | number     | number      |
| Yes      | numeric metric | shape_area   | Shape_Area   | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mtus-f3kr d:1970-01-01T00:00:00.000Z t:objectid=1 m:shape_area=85893.31889 m:shape_length=4752.03788 m:area=0 m:flood=6 m:donut=1 m:len=0

series e:mtus-f3kr d:1970-01-01T00:00:00.000Z t:objectid=2 m:shape_area=30767.73211 m:shape_length=6621.49315 m:area=0 m:flood=6 m:donut=1 m:len=0

series e:mtus-f3kr d:1970-01-01T00:00:00.000Z t:objectid=3 m:shape_area=850.18153 m:shape_length=131.76152 m:area=0 m:flood=6 m:donut=1 m:len=0
```

## Meta Commands

```ls
metric m:donut p:integer l:DONUTber

metric m:flood p:integer l:FLOODber

metric m:area p:integer l:AREAer

metric m:len p:integer l:LENr

metric m:shape_length l:Shape_Lengthame=number

metric m:shape_area l:Shape_Areae=number

entity e:mtus-f3kr l:DPD.ECA_FLOOD t:attribution="Seattle GIS Program" t:url=https://data.seattle.gov/api/views/mtus-f3kr

property e:mtus-f3kr t:meta.view v:id=mtus-f3kr v:category="Land Base" v:attributionLink=https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/19 v:averageRating=0 v:name=DPD.ECA_FLOOD v:attribution="Seattle GIS Program"

property e:mtus-f3kr t:meta.view.license v:name="Public Domain"

property e:mtus-f3kr t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"

property e:mtus-f3kr t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```