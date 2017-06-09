# Stormwater inlets, drains and catch basins

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stormwater-inlets-drains-and-catch-basins) |
| Metadata | [Link](https://data.sfgov.org/api/views/jtgq-b7c5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jtgq-b7c5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jtgq-b7c5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jtgq-b7c5 |
| Name | Stormwater inlets, drains and catch basins |
| Category | City Infrastructure |
| Tags | catch basin, stormwater, catchment basin, storm drain |
| Created | 2015-10-28T16:14:35Z |
| Publication Date | 2015-10-28T16:31:55Z |

## Description

The catch basin data is collected by SFDPW Hydraulics Engineering and SFPUC Wastewater Enterprise, Collection System Division engineers, drafters and operators.  The data is collected from sewer reference and construction documents and field surveys. You can learn more about how the City's wastewater collection system works here: http://www.sfwater.org/index.aspx?page=399

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | dpw_node_id         | DPW_Node_ID         | text      | number      |
| Yes      | series tag  | puc_maximo_asset_id | PUC_Maximo_Asset_ID | text      | text        |
| Yes      | series tag  | system_use_code     | System_Use_Code     | text      | text        |
| Yes      | series tag  | system_use          | System_Use          | text      | text        |
| Yes      | series tag  | drain_type          | Drain_Type          | text      | text        |
| No       |             | point_x             | POINT_X             | number    | number      |
| No       |             | point_y             | POINT_Y             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=155540 t:puc_maximo_asset_id=N-42990 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:row_number.jtgq-b7c5=1

series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=157534 t:puc_maximo_asset_id=N-43293 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:row_number.jtgq-b7c5=2

series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=155897 t:puc_maximo_asset_id=N-42862 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:row_number.jtgq-b7c5=3
```

## Meta Commands

```ls
metric m:row_number.jtgq-b7c5 p:long l:"Row Number"

entity e:jtgq-b7c5 l:"Stormwater inlets, drains and catch basins" t:url=https://data.sfgov.org/api/views/jtgq-b7c5

property e:jtgq-b7c5 t:meta.view d:2017-06-09T13:51:28.880Z v:id=jtgq-b7c5 v:category="City Infrastructure" v:averageRating=0 v:name="Stormwater inlets, drains and catch basins"

property e:jtgq-b7c5 t:meta.view.license d:2017-06-09T13:51:28.880Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jtgq-b7c5 t:meta.view.owner d:2017-06-09T13:51:28.880Z v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:jtgq-b7c5 t:meta.view.tableauthor d:2017-06-09T13:51:28.880Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | dpw_node_id | puc_maximo_asset_id | system_use_code | system_use                         | drain_type        | point_x          | point_y          | 
| =========== | =========== | =================== | =============== | ================================== | ================= | ================ | ================ | 
| 1482880261  | 155540      | N-42990             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6012451.39499447 | 2113875.27043653 | 
| 1482880261  | 157534      | N-43293             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6014153.27       | 2116375.31       | 
| 1482880261  | 155897      | N-42862             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6006121.10253416 | 2120402.24386018 | 
| 1482880261  | 178604      | N-28248             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6004695.95291749 | 2094300.44745675 | 
| 1482880261  | 254047      | N-290876            | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6013341.12615436 | 2116975.87629157 | 
| 1482880261  | 177759      | N-15629             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6009953.1088     | 2119366.3678     | 
| 1482880261  | 157444      | N-43469             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 6010128.31108148 | 2105524.84103321 | 
| 1482880261  | 155827      | N-42657             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 5993207.46536172 | 2093737.70623419 | 
| 1482880261  | 155511      | N-42514             | STORM           | Storm; even if DS flow is combined | Track Drain       | 6010592.90748695 | 2086222.58181359 | 
| 1482880261  | 198597      | N-40558             | STORM           | Storm; even if DS flow is combined | Catch Basin Drain | 5992511.32821493 | 2097012.53229601 | 
```