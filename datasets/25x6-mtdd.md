# Interstate Closure Gates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/interstate-closure-gates) |
| Metadata | [Link](https://data.iowa.gov/api/views/25x6-mtdd) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 25x6-mtdd |
| Name | Interstate Closure Gates |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, operations, gates, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-08T19:09:21Z |
| Publication Date | 2016-06-08T19:11:20Z |
| Rows Updated | 2016-06-08T19:09:21Z |

## Description

This is a representation of all gates and barricades that prevent access to the interstates. It consists of mainline barricades (left and right) that are physically located in the median and shoulder of the interstate that can be automatically lowered to prevent travel in the event of a road closure. It also includes ramp barricades that prevent travel onto the interstate by means of the entrance ramps, denoted with a "Road Closed" sign posted on a gate.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | gate_id             | GATE_ID             | text      | text        |
| Yes      | series tag  | district            | DISTRICT            | text      | number      |
| Yes      | series tag  | cost_center         | COST_CENTER         | text      | text        |
| Yes      | series tag  | route               | ROUTE               | text      | number      |
| Yes      | series tag  | dirtravel           | DIRTRAVEL           | text      | text        |
| Yes      | series tag  | sideofroad          | SIDEOFROAD          | text      | text        |
| Yes      | series tag  | milepost            | MILEPOST            | text      | text        |
| No       |             | milepost_offset     | MILEPOST_OFFSET     | number    | number      |
| No       |             | latitude            | LATITUDE            | number    | number      |
| No       |             | longitude           | LONGITUDE           | number    | number      |
| Yes      | series tag  | sign_face_direction | SIGN_FACE_DIRECTION | text      | text        |
| Yes      | series tag  | signtype            | SIGNTYPE            | text      | text        |
| Yes      | series tag  | subcategory         | SUBCATEGORY         | text      | text        |
| Yes      | series tag  | description         | DESCRIPTION         | text      | text        |
| Yes      | series tag  | remarks             | REMARKS             | text      | text        |
| Yes      | series tag  | activation_type     | ACTIVATION_TYPE     | text      | text        |
| Yes      | series tag  | objectid            | OBJECTID            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = milepost_offset,latitude,longitude
```

## Data Commands

```ls
series e:25x6-mtdd d:2017-03-16T21:18:17.118Z t:cost_center=551609 t:gate_id=A91341ADAF9244C890920563507EC3F4 t:activation_type=Manual t:milepost=159 t:description="Ramp Barricade" t:route=35 t:dirtravel=Ramp t:sideofroad=Left t:objectid=1 t:district=1 t:sign_face_direction=N t:signtype=Regulatory m:row_number.25x6-mtdd=1

series e:25x6-mtdd d:2017-03-16T21:18:17.118Z t:cost_center=554810 t:gate_id=0FA20C59470E43D88F65A88F67A49F2E t:activation_type=Remote t:milepost=75 t:description="Right Mainline Barricade" t:subcategory="No Subcategory" t:route=29 t:dirtravel="With Milepost (increasing in number)" t:sideofroad=Right t:objectid=2 t:district=4 t:sign_face_direction=S t:signtype=Guide m:row_number.25x6-mtdd=2

series e:25x6-mtdd d:2017-03-16T21:18:17.118Z t:cost_center=554810 t:gate_id=7EF1FEF2035948EEB2C197E3593193A1 t:activation_type=Manual t:milepost=75 t:description="Ramp Barricade" t:route=29 t:dirtravel=Ramp t:remarks="Sign face SE when gate is CLOSED" t:sideofroad=Right t:objectid=3 t:district=4 t:sign_face_direction=SE t:signtype=Regulatory m:row_number.25x6-mtdd=3
```

## Meta Commands

```ls
metric m:row_number.25x6-mtdd p:long l:"Row Number"

entity e:25x6-mtdd l:"Interstate Closure Gates" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/25x6-mtdd

property e:25x6-mtdd t:meta.view v:id=25x6-mtdd v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Closure_Gates/MapServer/0 v:averageRating=0 v:name="Interstate Closure Gates" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:25x6-mtdd t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:25x6-mtdd t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```