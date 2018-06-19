# Facilities Managment - Closed Cells as of Aug 5, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-managment-closed-cells-as-of-aug-5-2011-e5199) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/t4g9-dzi8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t4g9-dzi8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t4g9-dzi8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | t4g9-dzi8 |
| Name | Facilities Managment - Closed Cells as of Aug 5, 2011 |
| Attribution | Cook County Department of Facilities Management |
| Category | Public Safety |
| Created | 2011-10-12T22:31:10Z |
| Publication Date | 2014-10-09T23:06:19Z |

## Description

A chart showing Cook County Department of Corrections Closed Cells as of August 5, 2011

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | division    | DIVISION    | text      | text        |
| Yes      | numeric metric | total_cells | TOTAL CELLS | number    | number      |
| Yes      | numeric metric | plumbing    | PLUMBING    | number    | number      |
| Yes      | numeric metric | electrical  | ELECTRICAL  | number    | number      |
| Yes      | numeric metric | carpentry   | CARPENTRY   | number    | number      |
| Yes      | numeric metric | elec_tech   | ELEC TECH   | number    | number      |
| Yes      | numeric metric | tin         | TIN         | number    | number      |
| Yes      | numeric metric | enginering  | ENGINERING  | number    | number      |
| Yes      | numeric metric | brick       | BRICK       | number    | number      |
| Yes      | numeric metric | iron        | IRON        | number    | number      |
| Yes      | numeric metric | misc        | MISC        | number    | number      |
| Yes      | numeric metric | glaz        | GLAZ        | number    | number      |
| Yes      | numeric metric | open_cells  | OPEN CELLS  | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t4g9-dzi8 d:2011-01-01T00:00:00.000Z t:division=I m:open_cells=0 m:electrical=0 m:carpentry=0 m:brick=0 m:glaz=0 m:plumbing=0 m:enginering=0 m:tin=0 m:total_cells=608 m:iron=0 m:misc=0 m:elec_tech=0

series e:t4g9-dzi8 d:2011-01-01T00:00:00.000Z t:division=II m:open_cells=0 m:electrical=0 m:carpentry=0 m:brick=0 m:glaz=0 m:plumbing=0 m:enginering=0 m:tin=0 m:total_cells=0 m:iron=0 m:misc=0 m:elec_tech=0

series e:t4g9-dzi8 d:2011-01-01T00:00:00.000Z t:division=III m:open_cells=0 m:electrical=0 m:carpentry=0 m:brick=0 m:glaz=0 m:plumbing=0 m:enginering=0 m:tin=0 m:total_cells=180 m:iron=0 m:misc=0 m:elec_tech=0
```

## Meta Commands

```ls
metric m:total_cells p:integer l:"TOTAL CELLS" t:dataTypeName=number

metric m:plumbing p:integer l:PLUMBING t:dataTypeName=number

metric m:electrical p:integer l:ELECTRICAL t:dataTypeName=number

metric m:carpentry p:integer l:CARPENTRY t:dataTypeName=number

metric m:elec_tech p:integer l:"ELEC TECH" t:dataTypeName=number

metric m:tin p:integer l:TIN t:dataTypeName=number

metric m:enginering p:integer l:ENGINERING t:dataTypeName=number

metric m:brick p:integer l:BRICK t:dataTypeName=number

metric m:iron p:integer l:IRON t:dataTypeName=number

metric m:misc p:integer l:MISC t:dataTypeName=number

metric m:glaz p:integer l:GLAZ t:dataTypeName=number

metric m:open_cells p:double l:"OPEN CELLS" t:dataTypeName=percent

entity e:t4g9-dzi8 l:"Facilities Managment - Closed Cells as of Aug 5, 2011" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/t4g9-dzi8

property e:t4g9-dzi8 t:meta.view v:id=t4g9-dzi8 v:category="Public Safety" v:averageRating=0 v:name="Facilities Managment - Closed Cells as of Aug 5, 2011" v:attribution="Cook County Department of Facilities Management"

property e:t4g9-dzi8 t:meta.view.license v:name="Public Domain"

property e:t4g9-dzi8 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:t4g9-dzi8 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| division | total_cells | plumbing | electrical | carpentry | elec_tech | tin | enginering | brick | iron | misc | glaz | open_cells | 
| ======== | =========== | ======== | ========== | ========= | ========= | === | ========== | ===== | ==== | ==== | ==== | ========== | 
| I        | 608         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| II       | 0           | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| III      | 180         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| IV       | 320         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| V        | 480         | 1        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 1          | 
| VI       | 496         | 1        | 0          | 0         | 0         | 0   | 1          | 0     | 0    | 0    | 0    | 2          | 
| VIII     | 0           | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| IX       | 540         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| X        | 384         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
| XI       | 768         | 0        | 0          | 0         | 0         | 0   | 0          | 0     | 0    | 0    | 0    | 0          | 
```