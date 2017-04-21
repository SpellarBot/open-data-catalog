# Facilities Management - Closed Cells as of July 8th, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-closed-cells-as-of-july-8th-2011-cf71e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/phn5-wths) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/phn5-wths/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/phn5-wths/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | phn5-wths |
| Name | Facilities Management - Closed Cells as of July 8th, 2011 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2011-10-11T14:29:55Z |
| Publication Date | 2014-10-09T22:28:51Z |

## Description

A recap of how many cells were closed due to the need for structural repair or maintenance during the week of 7/8/2011

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | div                   | DIV                   | text      | text        |
| Yes      | numeric metric | total_cells           | TOTAL CELLS           | number    | number      |
| Yes      | numeric metric | plumbin               | Plumbing              | number    | number      |
| Yes      | numeric metric | electrician           | Electrician           | number    | number      |
| Yes      | numeric metric | carpenter             | Carpenter             | number    | number      |
| Yes      | numeric metric | electrical_technician | Electrical Technician | number    | number      |
| Yes      | numeric metric | tinsmith              | Tinsmith              | number    | number      |
| Yes      | numeric metric | engineer              | Engineer              | number    | number      |
| Yes      | numeric metric | brick_mason           | Brick Mason           | number    | number      |
| Yes      | numeric metric | iron_worker           | Iron Worker           | number    | number      |
| Yes      | numeric metric | miscellaneous         | Miscellaneous         | number    | number      |
| Yes      | numeric metric | glazier               | Glazier               | number    | number      |
| Yes      | numeric metric | total_cells_open      | Total Cells Open      | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:phn5-wths d:2011-01-01T00:00:00.000Z t:div=I m:iron_worker=0 m:electrician=0 m:total_cells_open=0 m:tinsmith=0 m:miscellaneous=0 m:glazier=0 m:carpenter=0 m:brick_mason=0 m:engineer=0 m:plumbin=0 m:electrical_technician=0 m:total_cells=608

series e:phn5-wths d:2011-01-01T00:00:00.000Z t:div=II m:iron_worker=0 m:electrician=0 m:total_cells_open=0 m:tinsmith=0 m:miscellaneous=0 m:glazier=0 m:carpenter=0 m:brick_mason=0 m:engineer=0 m:plumbin=0 m:electrical_technician=0

series e:phn5-wths d:2011-01-01T00:00:00.000Z t:div=III m:iron_worker=0 m:electrician=0 m:total_cells_open=0 m:tinsmith=0 m:miscellaneous=0 m:glazier=0 m:carpenter=0 m:brick_mason=0 m:engineer=0 m:plumbin=0 m:electrical_technician=0 m:total_cells=180
```

## Meta Commands

```ls
metric m:total_cells p:integer l:"TOTAL CELLS" t:dataTypeName=number

metric m:plumbin p:integer l:Plumbing t:dataTypeName=number

metric m:electrician p:integer l:Electrician t:dataTypeName=number

metric m:carpenter p:integer l:Carpenter t:dataTypeName=number

metric m:electrical_technician p:integer l:"Electrical Technician" t:dataTypeName=number

metric m:tinsmith p:integer l:Tinsmith t:dataTypeName=number

metric m:engineer p:integer l:Engineer t:dataTypeName=number

metric m:brick_mason p:integer l:"Brick Mason" t:dataTypeName=number

metric m:iron_worker p:integer l:"Iron Worker" t:dataTypeName=number

metric m:miscellaneous p:integer l:Miscellaneous t:dataTypeName=number

metric m:glazier p:integer l:Glazier t:dataTypeName=number

metric m:total_cells_open p:double l:"Total Cells Open" t:dataTypeName=percent

entity e:phn5-wths l:"Facilities Management - Closed Cells as of July 8th, 2011" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/phn5-wths

property e:phn5-wths t:meta.view v:id=phn5-wths v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Closed Cells as of July 8th, 2011" v:attribution="Cook County Department of Facilities Management"

property e:phn5-wths t:meta.view.license v:name="Public Domain"

property e:phn5-wths t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:phn5-wths t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| div  | total_cells | plumbin | electrician | carpenter | electrical_technician | tinsmith | engineer | brick_mason | iron_worker | miscellaneous | glazier | total_cells_open | 
| ==== | =========== | ======= | =========== | ========= | ===================== | ======== | ======== | =========== | =========== | ============= | ======= | ================ | 
| I    | 608         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| II   |             | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| III  | 180         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| IV   | 320         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| V    | 480         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 1           | 0             | 0       | 1                | 
| VI   | 496         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| VIII |             | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| IX   | 540         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| X    | 384         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
| XI   | 768         | 0       | 0           | 0         | 0                     | 0        | 0        | 0           | 0           | 0             | 0       | 0                | 
```