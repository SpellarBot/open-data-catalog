# Facilities Management - Closed Cells as of Jul 29, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-closed-cells-as-of-jul-29-2011-cc4d2) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ufgv-zh73) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ufgv-zh73/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ufgv-zh73/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ufgv-zh73 |
| Name | Facilities Management - Closed Cells as of Jul 29, 2011 |
| Attribution | Cook County Department of Facilities Management |
| Category | Public Safety |
| Created | 2011-10-12T22:14:41Z |
| Publication Date | 2014-10-09T23:05:52Z |

## Description

A Chart showing Cook County Department of Corrections Closed Cells as of Jul 29, 2011

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | division      | DIVISION      | text      | text        |
| Yes      | numeric metric | total_cells   | TOTAL CELLS   | number    | number      |
| Yes      | numeric metric | plumbing_     | PLUMBING      | number    | number      |
| Yes      | numeric metric | electrical    | ELECTRICAL    | number    | number      |
| Yes      | numeric metric | carpentry     | CARPENTRY     | number    | number      |
| Yes      | numeric metric | elec_tech     | ELEC TECH     | number    | number      |
| Yes      | numeric metric | tin           | TIN           | number    | number      |
| Yes      | numeric metric | engineering   | ENGINEERING   | number    | number      |
| Yes      | numeric metric | brick         | BRICK         | number    | number      |
| Yes      | numeric metric | iron          | IRON          | number    | number      |
| Yes      | numeric metric | misc          | MISC          | number    | number      |
| Yes      | numeric metric | glaze         | GLAZE         | number    | number      |
| Yes      | numeric metric | total_percent | TOTAL PERCENT | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ufgv-zh73 d:2011-01-01T00:00:00.000Z t:division=I m:plumbing_=0 m:electrical=0 m:carpentry=0 m:brick=0 m:total_percent=0 m:tin=0 m:engineering=0 m:total_cells=608 m:iron=0 m:glaze=0 m:misc=0 m:elec_tech=0

series e:ufgv-zh73 d:2011-01-01T00:00:00.000Z t:division=II m:plumbing_=0 m:electrical=0 m:carpentry=0 m:brick=0 m:total_percent=0 m:tin=0 m:engineering=0 m:total_cells=0 m:iron=0 m:glaze=0 m:misc=0 m:elec_tech=0

series e:ufgv-zh73 d:2011-01-01T00:00:00.000Z t:division=III m:plumbing_=0 m:electrical=0 m:carpentry=0 m:brick=0 m:total_percent=0 m:tin=0 m:engineering=0 m:total_cells=180 m:iron=0 m:glaze=0 m:misc=0 m:elec_tech=0
```

## Meta Commands

```ls
metric m:total_cells p:integer l:"TOTAL CELLS" t:dataTypeName=number

metric m:plumbing_ p:integer l:PLUMBING t:dataTypeName=number

metric m:electrical p:integer l:ELECTRICAL t:dataTypeName=number

metric m:carpentry p:integer l:CARPENTRY t:dataTypeName=number

metric m:elec_tech p:integer l:"ELEC TECH" t:dataTypeName=number

metric m:tin p:integer l:TIN t:dataTypeName=number

metric m:engineering p:integer l:ENGINEERING t:dataTypeName=number

metric m:brick p:integer l:BRICK t:dataTypeName=number

metric m:iron p:integer l:IRON t:dataTypeName=number

metric m:misc p:integer l:MISC t:dataTypeName=number

metric m:glaze p:integer l:GLAZE t:dataTypeName=number

metric m:total_percent p:double l:"TOTAL PERCENT" t:dataTypeName=percent

entity e:ufgv-zh73 l:"Facilities Management - Closed Cells as of Jul 29, 2011" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/ufgv-zh73

property e:ufgv-zh73 t:meta.view v:id=ufgv-zh73 v:category="Public Safety" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Closed Cells as of Jul 29, 2011" v:attribution="Cook County Department of Facilities Management"

property e:ufgv-zh73 t:meta.view.license v:name="Public Domain"

property e:ufgv-zh73 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:ufgv-zh73 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| division | total_cells | plumbing_ | electrical | carpentry | elec_tech | tin | engineering | brick | iron | misc | glaze | total_percent | 
| ======== | =========== | ========= | ========== | ========= | ========= | === | =========== | ===== | ==== | ==== | ===== | ============= | 
| I        | 608         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| II       | 0           | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| III      | 180         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| IV       | 320         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| V        | 480         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| VI       | 496         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| VIII     | 0           | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| IX       | 540         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| X        | 384         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
| XI       | 768         | 0         | 0          | 0         | 0         | 0   | 0           | 0     | 0    | 0    | 0     | 0             | 
```