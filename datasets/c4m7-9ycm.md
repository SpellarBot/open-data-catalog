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
| Rows Updated | 2016-12-06T16:36:24Z |

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
| Yes      | numeric metric | adjacent_county_number | ADJACENT_COUNTY_NUMBER | number     | number      |
| Yes      | series tag     | locerror               | LOCERROR               | text       | text        |
| Yes      | numeric metric | shape_len              | SHAPE.LEN              | number     | number      |
| Yes      | series tag     | objectid               | OBJECTID               | text       | number      |
| Yes      | series tag     | shape                  | SHAPE                  | geospatial | geospatial  |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_end_date,system_mod_date,system_create_date,effective_start_date
```

## Data Commands

```ls
series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:route_id=C005741000N t:event_id=0000000234 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=1 m:to_measure=0.94167 m:adjacent_county_number=6 m:from_measure=0

series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:route_id=C005747595E t:event_id=0000000141 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=2 m:to_measure=0.12024 m:adjacent_county_number=6 m:from_measure=0

series e:c4m7-9ycm d:2016-01-01T06:00:00.000Z t:route_id=C005841000N t:event_id=0000000164 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=3 m:to_measure=11.5336 m:adjacent_county_number=92 m:from_measure=7.0204
```

## Meta Commands

```ls
metric m:to_measure l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:from_measure l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:adjacent_county_number p:integer l:ADJACENT_COUNTY_NUMBER d:"Adjacent County Number" t:dataTypeName=number

metric m:shape_len l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:c4m7-9ycm l:"RAMS - Adjacent County Number" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/c4m7-9ycm

property e:c4m7-9ycm t:meta.view d:2017-03-10T14:40:17.506Z v:id=c4m7-9ycm v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Adjacent County Number" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:c4m7-9ycm t:meta.view.owner d:2017-03-10T14:40:17.506Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:c4m7-9ycm t:meta.view.tableauthor d:2017-03-10T14:40:17.506Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```