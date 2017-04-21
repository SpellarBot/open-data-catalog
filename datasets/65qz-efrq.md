# Snow Ice Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snow-ice-routes-0c665) |
| Metadata | [Link](https://data.seattle.gov/api/views/65qz-efrq) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/65qz-efrq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/65qz-efrq/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 65qz-efrq |
| Name | Snow Ice Routes |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | city of seattle, government, transportation, snow routes, streets, de-icing, anti-icing, winter storm |
| Created | 2010-11-04T17:10:38Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

City of Seattle streets covered under SDOT?s Winter Storm Response Plan, showing snow and ice removal routes categorized by targeted level of service.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | route_name  | ROUTE_NAME | text      | text        |
| Yes      | series tag     | si_shop     | SI_SHOP    | text      | text        |
| Yes      | numeric metric | si_los      | SI_LOS     | number    | number      |
| Yes      | numeric metric | si_route    | SI_ROUTE   | number    | number      |
| Yes      | series tag     | geo_area    | GEO_AREA   | text      | text        |
| Yes      | numeric metric | routemiles  | ROUTEMILES | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:65qz-efrq d:2010-11-04T10:10:41.000Z t:si_shop=HL t:route_name="37 - NE - 2 - HL" t:geo_area=NE m:si_route=37 m:si_los=2 m:routemiles=5.77989224

series e:65qz-efrq d:2010-11-04T10:10:41.000Z t:si_shop=CH t:route_name="61 - C/S - 1 - CH" t:geo_area=C/S m:si_route=61 m:si_los=1 m:routemiles=13.15090587

series e:65qz-efrq d:2010-11-04T10:10:41.000Z t:si_shop=HL t:route_name="10 - NW - 1 - HL" t:geo_area=NW m:si_route=10 m:si_los=1 m:routemiles=10.98030678
```

## Meta Commands

```ls
metric m:si_los p:float l:SI_LOS t:dataTypeName=number

metric m:si_route p:float l:SI_ROUTE t:dataTypeName=number

metric m:routemiles p:double l:ROUTEMILES t:dataTypeName=number

entity e:65qz-efrq l:"Snow Ice Routes" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/65qz-efrq

property e:65qz-efrq t:meta.view v:id=65qz-efrq v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation v:averageRating=0 v:name="Snow Ice Routes" v:attribution="Seattle Department of Transportation"

property e:65qz-efrq t:meta.view.license v:name="Public Domain"

property e:65qz-efrq t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:65qz-efrq t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | route_name        | si_shop | si_los | si_route | geo_area | routemiles  | 
| =========== | ================= | ======= | ====== | ======== | ======== | =========== | 
| 1288865441  | 37 - NE - 2 - HL  | HL      | 2.0    | 37.0     | NE       | 5.77989224  | 
| 1288865441  | 61 - C/S - 1 - CH | CH      | 1.0    | 61.0     | C/S      | 13.15090587 | 
| 1288865441  | 10 - NW - 1 - HL  | HL      | 1.0    | 10.0     | NW       | 10.98030678 | 
| 1288865441  | 12 - NW - 2 - HL  | HL      | 2.0    | 12.0     | NW       | 8.91282009  | 
| 1288865441  | 13 - NW - 2 - HL  | HL      | 2.0    | 13.0     | NW       | 6.63741025  | 
| 1288865441  | 14 - NW - 2 - HL  | HL      | 2.0    | 14.0     | NW       | 10.05688339 | 
| 1288865441  | 30 - NE - 1 - HL  | HL      | 1.0    | 30.0     | NE       | 5.41515331  | 
| 1288865441  | 15 - NW - 2 - HL  | HL      | 2.0    | 15.0     | NW       | 11.13748333 | 
| 1288865441  | 80 - SW- 1 - CH   | WS      | 1.0    | 80.0     | SW       | 10.99148364 | 
| 1288865441  | 16 - NW - 2 - HL  | HL      | 2.0    | 16.0     | NW       | 9.76602245  | 
```