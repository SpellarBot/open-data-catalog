# Linear Assets Maintained by the Recreation and Parks Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/linear-assets-maintained-by-the-recreation-and-parks-department) |
| Metadata | [Link](https://data.sfgov.org/api/views/hi3g-ejcy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hi3g-ejcy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hi3g-ejcy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hi3g-ejcy |
| Name | Linear Assets Maintained by the Recreation and Parks Department |
| Category | Culture and Recreation |
| Tags | sfrpd, gis, asset records, gates, handrails, fences |
| Created | 2016-03-02T22:45:44Z |
| Publication Date | 2016-04-20T22:19:52Z |

## Description

Assets maintained by Rec and Park, represented as lines. These include gates, handrails, fences, etc.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | object_id          | Object ID          | text      | number      |
| Yes      | series tag     | map_label          | Map Label          | text      | text        |
| Yes      | series tag     | asset_id           | Asset ID           | text      | number      |
| Yes      | numeric metric | length             | Length             | number    | number      |
| Yes      | series tag     | functional_area_id | Functional Area ID | text      | number      |
| Yes      | series tag     | floor_id           | Floor ID           | text      | number      |
| Yes      | series tag     | facility_id        | Facility ID        | text      | number      |
| Yes      | series tag     | property_id        | Property ID        | text      | number      |
| Yes      | series tag     | asset_name         | Asset Name         | text      | text        |
| Yes      | numeric metric | quantity           | Quantity           | number    | number      |
| Yes      | series tag     | asset_type         | Asset Type         | text      | text        |
| Yes      | series tag     | asset_subtype      | Asset Subtype      | text      | text        |
| No       |                | geom               | Geom               | line      | line        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = geom
```

## Data Commands

```ls
series e:hi3g-ejcy d:2016-08-16T23:47:08.000Z t:property_id=95 t:asset_id=980591 t:asset_subtype="Chain Link" t:map_label="Single Chain Link Gate 6" t:asset_name="Single Chain Link Gate 6" t:asset_type=Gate t:functional_area_id=1257054 t:facility_id=12460 m:quantity=1

series e:hi3g-ejcy d:2016-08-16T23:47:08.000Z t:property_id=61 t:asset_id=980663 t:asset_subtype=Metal t:map_label="Access Ramp (south) Metal Handrail" t:asset_name="Access Ramp (south) Metal Handrail" t:asset_type=Handrail t:functional_area_id=1257076 t:facility_id=36263 m:quantity=1

series e:hi3g-ejcy d:2016-08-16T23:47:08.000Z t:property_id=95 t:asset_id=980588 t:asset_subtype="Chain Link" t:map_label="Single Chain Link Gate 3" t:asset_name="Single Chain Link Gate 3" t:asset_type=Gate t:functional_area_id=98548 t:facility_id=12460 m:quantity=1
```

## Meta Commands

```ls
metric m:length p:long l:Length t:dataTypeName=number

metric m:quantity p:long l:Quantity t:dataTypeName=number

entity e:hi3g-ejcy l:"Linear Assets Maintained by the Recreation and Parks Department" t:url=https://data.sfgov.org/api/views/hi3g-ejcy

property e:hi3g-ejcy t:meta.view v:id=hi3g-ejcy v:category="Culture and Recreation" v:averageRating=0 v:name="Linear Assets Maintained by the Recreation and Parks Department"

property e:hi3g-ejcy t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hi3g-ejcy t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:hi3g-ejcy t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | map_label                          | asset_id | length | functional_area_id | floor_id | facility_id | property_id | asset_name                         | quantity | asset_type | asset_subtype | geom                                                                                                                                                                                                             | 
| =========== | ========= | ================================== | ======== | ====== | ================== | ======== | =========== | =========== | ================================== | ======== | ========== | ============= | ================================================================================================================================================================================================================ | 
| 1471391228  |           | Single Chain Link Gate 6           | 980591   |        | 1257054            |          | 12460       | 95          | Single Chain Link Gate 6           | 1        | Gate       | Chain Link    | LINESTRING (-122.49834713864976 37.77314628899716, -122.49834655858187 37.77313734687738)                                                                                                                        | 
| 1471391228  |           | Access Ramp (south) Metal Handrail | 980663   |        | 1257076            |          | 36263       | 61          | Access Ramp (south) Metal Handrail | 1        | Handrail   | Metal         | LINESTRING (-122.42253116049852 37.75932226330659, -122.42241856690757 37.75932993616827)                                                                                                                        | 
| 1471391228  |           | Single Chain Link Gate 3           | 980588   |        | 98548              |          | 12460       | 95          | Single Chain Link Gate 3           | 1        | Gate       | Chain Link    | LINESTRING (-122.49832885428619 37.77307133603682, -122.49832797225864 37.773058386743735)                                                                                                                       | 
| 1471391228  |           | Single Chain Link Gate - 10ft      | 980322   |        | 18506              |          | 18505       | 96          | Fulton 10' Single Chain Link Gate  | 3        | Gate       | Chain Link    | LINESTRING (-122.48711610867198 37.773192035722566, -122.48711535313257 37.77318263780159)                                                                                                                       | 
| 1471391228  |           | Single Chain Link Gate - 6ft       | 980321   |        | 18506              |          | 18505       | 96          | Fulton 6' Single Chain Link Gate   | 2        | Gate       | Chain Link    | LINESTRING (-122.4867817254771 37.77357463795925, -122.48676806996494 37.77357526645118)                                                                                                                         | 
| 1471391228  |           | Perimeter Chain Link Fence         | 980593   |        | 12462              |          | 12460       | 95          | Perimeter Chain Link Fence         | 1        | Fence      | Chain Link    | LINESTRING (-122.49874570675644 37.77305173355849, -122.49874562047364 37.773050510244914, -122.49915803121365 37.77303175397405)                                                                                | 
| 1471391228  |           | Metal Handrail                     | 980388   |        | 1256952            |          | 18497       | 30          | Metal Handrail                     | 2        | Handrail   | Metal         | LINESTRING (-122.40944927441068 37.72904670668199, -122.40948028190601 37.72903879787677)                                                                                                                        | 
| 1471391228  |           | Chain Link Fence - 10'             | 980370   |        | 1256993            |          | 657         | 30          | Chain Link Fence - 10'             |          | Fence      | Chain Link    | LINESTRING (-122.41027660256427 37.728656800052484, -122.4104506775392 37.728611252194106, -122.41058071863661 37.72892604211079, -122.41022302391951 37.729018971662875, -122.41022216359028 37.72901688756608) | 
| 1471391228  |           | Single Gate with ISA Sign - 10ft   | 980326   |        | 1256939            |          | 18505       | 96          | Fulton 10' Single Metal Gate       | 1        | Gate       | Metal         | LINESTRING (-122.48653911532418 37.77343193321208, -122.48653981776187 37.773441852941595)                                                                                                                       | 
| 1471391228  |           | Metal Handrail                     | 980390   |        | 1256957            |          | 18497       | 30          | Metal Handrail                     | 2        | Handrail   | Metal         | LINESTRING (-122.40940126204956 37.728945068110434, -122.40942365310589 37.72899957974845)                                                                                                                       | 
```