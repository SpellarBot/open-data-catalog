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
| Rows Updated | 2017-03-04T15:26:52Z |

## Description

The catch basin data is collected by SFDPW Hydraulics Engineering and SFPUC Wastewater Enterprise, Collection System Division engineers, drafters and operators.  The data is collected from sewer reference and construction documents and field surveys. You can learn more about how the City's wastewater collection system works here: http://www.sfwater.org/index.aspx?page=399

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | dpw_node_id         | DPW_Node_ID         | text      | number      |
| Yes      | series tag     | puc_maximo_asset_id | PUC_Maximo_Asset_ID | text      | text        |
| Yes      | series tag     | system_use_code     | System_Use_Code     | text      | text        |
| Yes      | series tag     | system_use          | System_Use          | text      | text        |
| Yes      | series tag     | drain_type          | Drain_Type          | text      | text        |
| Yes      | numeric metric | point_x             | POINT_X             | number    | number      |
| Yes      | numeric metric | point_y             | POINT_Y             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=155487 t:puc_maximo_asset_id=N-42109 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:point_x=6008875.9 m:point_y=2098204.47897

series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=155540 t:puc_maximo_asset_id=N-42990 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:point_x=6012451.39499 m:point_y=2113875.27044

series e:jtgq-b7c5 d:2016-12-27T23:11:01.000Z t:system_use_code=STORM t:dpw_node_id=157534 t:puc_maximo_asset_id=N-43293 t:drain_type="Catch Basin Drain" t:system_use="Storm; even if DS flow is combined" m:point_x=6014153.27 m:point_y=2116375.31
```

## Meta Commands

```ls
metric m:point_x l:POINT_X t:dataTypeName=number

metric m:point_y l:POINT_Y t:dataTypeName=number

entity e:jtgq-b7c5 l:"Stormwater inlets, drains and catch basins" t:url=https://data.sfgov.org/api/views/jtgq-b7c5

property e:jtgq-b7c5 t:meta.view d:2017-03-10T16:00:38.052Z v:id=jtgq-b7c5 v:category="City Infrastructure" v:averageRating=0 v:name="Stormwater inlets, drains and catch basins"

property e:jtgq-b7c5 t:meta.view.license d:2017-03-10T16:00:38.052Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jtgq-b7c5 t:meta.view.owner d:2017-03-10T16:00:38.052Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:jtgq-b7c5 t:meta.view.tableauthor d:2017-03-10T16:00:38.052Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```