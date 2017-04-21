# Assets Maintained by the Recreation and Parks Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assets-maintained-by-the-recreation-and-parks-department) |
| Metadata | [Link](https://data.sfgov.org/api/views/ays8-rxxc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ays8-rxxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ays8-rxxc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ays8-rxxc |
| Name | Assets Maintained by the Recreation and Parks Department |
| Category | Culture and Recreation |
| Tags | picnic tables, benches, trash cans, sheds |
| Created | 2016-03-16T00:08:30Z |
| Publication Date | 2016-04-15T18:48:47Z |

## Description

The locations of assets like trash cans, picnic tables, benches, etc, operated and maintained by Rec and Park.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | object_id          | Object ID          | text      | number      |
| Yes      | series tag     | asset_id           | Asset ID           | text      | number      |
| Yes      | series tag     | map_label          | Map Label          | text      | text        |
| Yes      | series tag     | asset_name         | Asset Name         | text      | text        |
| Yes      | series tag     | asset_type         | Asset Type         | text      | text        |
| Yes      | series tag     | asset_subtype      | Asset Subtype      | text      | text        |
| Yes      | numeric metric | quantity           | Quantity           | number    | number      |
| Yes      | series tag     | functional_area_id | Functional Area ID | text      | number      |
| Yes      | series tag     | property_id        | Property ID        | text      | number      |
| Yes      | series tag     | facility_id        | Facility ID        | text      | number      |
| Yes      | series tag     | floor_id           | Floor ID           | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ays8-rxxc d:2016-04-15T12:37:31.000Z t:property_id=7 t:asset_id=148839 t:map_label="Trash Can" t:asset_name="Turf Trash Can" t:asset_type="Trash Can" t:object_id=1 t:functional_area_id=11951 t:facility_id=11820 m:quantity=2

series e:ays8-rxxc d:2016-04-15T12:37:31.000Z t:property_id=7 t:asset_id=148303 t:map_label=Bench t:asset_name="Concrete Pathway Benches" t:asset_type=Bench t:object_id=2 t:functional_area_id=12496 t:facility_id=12495 m:quantity=18

series e:ays8-rxxc d:2016-04-15T12:37:31.000Z t:property_id=7 t:asset_id=148302 t:map_label="Drinking Fountain" t:asset_name="Perennial Bed Drinking Fountains" t:asset_type="Drinking Fountain" t:object_id=3 t:functional_area_id=74740 t:facility_id=11820 m:quantity=1
```

## Meta Commands

```ls
metric m:quantity p:integer l:Quantity t:dataTypeName=number

entity e:ays8-rxxc l:"Assets Maintained by the Recreation and Parks Department" t:url=https://data.sfgov.org/api/views/ays8-rxxc

property e:ays8-rxxc t:meta.view v:id=ays8-rxxc v:category="Culture and Recreation" v:averageRating=0 v:name="Assets Maintained by the Recreation and Parks Department"

property e:ays8-rxxc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ays8-rxxc t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ays8-rxxc t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | asset_id | map_label         | asset_name                       | asset_type        | asset_subtype | quantity | functional_area_id | property_id | facility_id | floor_id | 
| =========== | ========= | ======== | ================= | ================================ | ================= | ============= | ======== | ================== | =========== | =========== | ======== | 
| 1460723851  | 1         | 148839   | Trash Can         | Turf Trash Can                   | Trash Can         |               | 2        | 11951              | 7           | 11820       |          | 
| 1460723851  | 2         | 148303   | Bench             | Concrete Pathway Benches         | Bench             |               | 18       | 12496              | 7           | 12495       |          | 
| 1460723851  | 3         | 148302   | Drinking Fountain | Perennial Bed Drinking Fountains | Drinking Fountain |               | 1        | 74740              | 7           | 11820       |          | 
| 1460723851  | 8         | 149769   | Trash Can         | Turf Trash Cans                  | Trash Can         |               | 3        | 19160              | 63          | 11808       |          | 
| 1460723851  | 9         | 149710   | Bench             | Turf Benches                     | Bench             |               | 9        | 19160              | 63          | 11808       |          | 
| 1460723851  | 10        | 149765   | Trash Can         | Concrete Pathway Trash Cans      | Trash Can         |               | 7        | 12635              | 63          | 12633       |          | 
| 1460723851  | 11        | 149741   | Picnic Table      | Picnic Area 2 Tables             | Table             |               | 2        | 460                | 63          | 418         |          | 
| 1460723851  | 12        | 149741   | Picnic Table      | Picnic Area 2 Tables             | Table             |               | 2        | 460                | 63          | 418         |          | 
| 1460723851  | 13        | 149745   | Picnic Table      | Picnic Area 4 Tables             | Table             |               | 5        | 72895              | 63          | 418         |          | 
| 1460723851  | 14        | 149745   | Picnic Table      | Picnic Area 4 Tables             | Table             |               | 5        | 72895              | 63          | 418         |          | 
```