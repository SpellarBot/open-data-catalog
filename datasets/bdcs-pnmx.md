# WSSC Grid [arcgis_rest_services_general_wssc_grid_MapServer_0]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/washington-suburban-sanitary-commission-map-grids) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/bdcs-pnmx) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/bdcs-pnmx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/bdcs-pnmx/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | bdcs-pnmx |
| Name | WSSC Grid [arcgis_rest_services_general_wssc_grid_MapServer_0] |
| Category | Environment |
| Tags | technology, map, geographic, business, urban, district;washington suburban sanitary commission map grids |
| Created | 2014-12-17T16:37:44Z |
| Publication Date | 2014-12-17T16:37:56Z |

## Description

https://gis3.montgomerycountymd.gov/arcgis/rest/services/general/wssc_grid/MapServer/0

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type  | Render Type |
| ======== | ============== | =========== | ========== | ========== | =========== |
| No       | time           | :updated_at | updated_at | meta_data  | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text       | number      |
| Yes      | numeric metric | numyc       | NUMYC      | number     | text        |
| Yes      | numeric metric | numxc       | NUMXC      | number     | text        |
| Yes      | series tag     | quad        | QUAD       | text       | text        |
| Yes      | series tag     | taxmap      | TAXMAP     | text       | text        |
| Yes      | series tag     | grid        | GRID       | text       | text        |
| Yes      | series tag     | shape       | SHAPE      | geospatial | geospatial  |
| Yes      | numeric metric | shape_area  | SHAPE.AREA | number     | number      |
| Yes      | numeric metric | shape_len   | SHAPE.LEN  | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bdcs-pnmx d:1970-01-01T00:00:00.000Z t:taxmap=GZ123 t:quad=NW t:grid=243NW08 t:objectid=1 m:shape_area=23998704.7293 m:numyc=243 m:numxc=8

series e:bdcs-pnmx d:1970-01-01T00:00:00.000Z t:taxmap=FZ562 t:quad=NW t:grid=242NW09 t:objectid=2 m:shape_area=23998641.41004 m:numyc=242 m:numxc=9

series e:bdcs-pnmx d:1970-01-01T00:00:00.000Z t:taxmap=GZ122 t:quad=NW t:grid=242NW08 t:objectid=3 m:shape_area=23998643.38078 m:numyc=242 m:numxc=8
```

## Meta Commands

```ls
metric m:numyc p:integer l:NUMYC d:NUMYC t:dataTypeName=number

metric m:numxc p:integer l:NUMXC d:NUMXC t:dataTypeName=number

metric m:shape_area l:SHAPE.AREA d:SHAPE.AREA t:dataTypeName=number

metric m:shape_len l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

entity e:bdcs-pnmx l:"WSSC Grid [arcgis_rest_services_general_wssc_grid_MapServer_0]" t:url=https://data.montgomerycountymd.gov/api/views/bdcs-pnmx

property e:bdcs-pnmx t:meta.view d:2017-03-10T16:21:21.928Z v:id=bdcs-pnmx v:category=Environment v:averageRating=0 v:name="WSSC Grid [arcgis_rest_services_general_wssc_grid_MapServer_0]"

property e:bdcs-pnmx t:meta.view.owner d:2017-03-10T16:21:21.928Z v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan

property e:bdcs-pnmx t:meta.view.tableauthor d:2017-03-10T16:21:21.928Z v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```