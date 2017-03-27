# Federal, Institutional, and Park Lands

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/federal-institutional-and-park-lands) |
| Metadata | [Link](https://data.iowa.gov/api/views/rfvm-5n7x) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rfvm-5n7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rfvm-5n7x/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rfvm-5n7x |
| Name | Federal, Institutional, and Park Lands |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | boundary, reference, federal, iowa, federal land, land use, park, boundaries, institution, iowa department of transportation |
| Created | 2016-06-07T22:39:40Z |
| Publication Date | 2016-06-07T22:51:44Z |

## Description

This data is comprised of various federal, institutional, and park land boundaries used on a daily basis at the DOT. The data is current as of 2013.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type  | Render Type |
| ======== | ============== | ============ | ============ | ========== | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data  | meta_data   |
| Yes      | series tag     | landuse_id   | LANDUSE_ID   | text       | number      |
| Yes      | series tag     | landuse_name | LANDUSE_NAME | text       | text        |
| Yes      | series tag     | landuse_type | LANDUSE_TYPE | text       | text        |
| Yes      | numeric metric | shape_area   | SHAPE.AREA   | number     | number      |
| Yes      | numeric metric | shape_len    | SHAPE.LEN    | number     | number      |
| Yes      | series tag     | objectid     | OBJECTID     | text       | number      |
| No       |                | shape        | SHAPE        | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:rfvm-5n7x d:2016-06-07T22:39:40.000Z t:shape.longitude=-94.48906240799994 t:shape.needs_recoding=false t:landuse_id=3481 t:shape.latitude=42.674573131000045 t:objectid=1 t:landuse_type="WILDLIFE MANAGEMENT AREA" t:landuse_name="Lizard Lake WMA" m:shape_area=1410472.0011003

series e:rfvm-5n7x d:2016-06-07T22:39:40.000Z t:shape.longitude=-94.40007323099996 t:shape.needs_recoding=false t:landuse_id=3501 t:shape.latitude=42.79007121500007 t:objectid=2 t:landuse_type="WILDLIFE MANAGEMENT AREA" t:landuse_name="Bradgate WMA" m:shape_area=513228.020415319

series e:rfvm-5n7x d:2016-06-07T22:39:40.000Z t:shape.longitude=-95.94411355899996 t:shape.needs_recoding=false t:landuse_id=2371 t:shape.latitude=41.83821600700003 t:objectid=3 t:landuse_type="STATE FOREST" t:landuse_name="Loess Hills State Forest" m:shape_area=16745052.2586382
```

## Meta Commands

```ls
metric m:shape_area p:decimal l:SHAPE.AREA d:"Area (SqM)" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Perimeter (Meter)" t:dataTypeName=number

entity e:rfvm-5n7x l:"Federal, Institutional, and Park Lands" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/rfvm-5n7x

property e:rfvm-5n7x t:meta.view v:id=rfvm-5n7x v:category="Transportation & Utilities" v:averageRating=0 v:name="Federal, Institutional, and Park Lands" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:rfvm-5n7x t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:rfvm-5n7x t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```