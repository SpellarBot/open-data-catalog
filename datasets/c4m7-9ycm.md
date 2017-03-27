# RAMS - Adjacent County Number

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-adjacent-county-number) |
| Metadata | [Link](https://data.iowa.gov/api/views/c4m7-9ycm) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/c4m7-9ycm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/c4m7-9ycm/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | c4m7-9ycm |
| Name | RAMS - Adjacent County Number |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, adjacent county number, asset, inventory |
| Created | 2016-12-06T16:36:24Z |
| Publication Date | 2016-12-06T16:38:35Z |

## Description

Adjacent County Number data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type  | Render Type |
| ======== | ============== | ====================== | ====================== | ========== | =========== |
| Yes      | series tag     | event_id               | EVENT_ID               | text       | text        |
| Yes      | series tag     | route_id               | ROUTE_ID               | text       | text        |
| Yes      | numeric metric | to_measure             | TO_MEASURE             | number     | number      |
| Yes      | numeric metric | from_measure           | FROM_MEASURE           | number     | number      |
| Yes      | time           | business_date          | BUSINESS_DATE          | date       | date        |
| No       |                | effective_start_date   | EFFECTIVE_START_DATE   | date       | date        |
| No       |                | effective_end_date     | EFFECTIVE_END_DATE     | date       | date        |
| Yes      | series tag     | user_create            | USER_CREATE            | text       | text        |
| Yes      | series tag     | user_mod               | USER_MOD               | text       | text        |
| No       |                | system_create_date     | SYSTEM_CREATE_DATE     | date       | date        |
| No       |                | system_mod_date        | SYSTEM_MOD_DATE        | date       | date        |
| Yes      | series tag     | adjacent_county_number | ADJACENT_COUNTY_NUMBER | text       | number      |
| Yes      | series tag     | locerror               | LOCERROR               | text       | text        |
| Yes      | numeric metric | shape_len              | SHAPE.LEN              | number     | number      |
| Yes      | series tag     | objectid               | OBJECTID               | text       | number      |
| No       |                | shape                  | SHAPE                  | geospatial | geospatial  |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_start_date,effective_end_date,system_create_date,system_mod_date,shape
```

## Data Commands

```ls
series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:shape.longitude=-91.83137915399999 t:shape.needs_recoding=false t:route_id=C005741000N t:event_id=0000000234 t:user_create=RWYLLIE t:adjacent_county_number=6 t:locerror="NO ERROR" t:shape.latitude=41.86184920900007 t:user_mod=RAMS t:objectid=1 m:to_measure=0.941668 m:from_measure=0

series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:shape.longitude=-91.83238547199994 t:shape.needs_recoding=false t:route_id=C005747595E t:event_id=0000000141 t:user_create=RWYLLIE t:adjacent_county_number=6 t:locerror="NO ERROR" t:shape.latitude=42.22467723200003 t:user_mod=RAMS t:objectid=2 m:to_measure=0.12024 m:from_measure=0

series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:shape.longitude=-91.48514197599997 t:shape.needs_recoding=false t:route_id=C005841000N t:event_id=0000000164 t:user_create=RWYLLIE t:adjacent_county_number=92 t:locerror="NO ERROR" t:shape.latitude=41.27143059800005 t:user_mod=RAMS t:objectid=3 m:to_measure=11.533598999999999 m:from_measure=7.020397999999999
```

## Meta Commands

```ls
metric m:to_measure p:decimal l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:from_measure p:decimal l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:c4m7-9ycm l:"RAMS - Adjacent County Number" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/c4m7-9ycm

property e:c4m7-9ycm t:meta.view v:id=c4m7-9ycm v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Adjacent County Number" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:c4m7-9ycm t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:c4m7-9ycm t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```