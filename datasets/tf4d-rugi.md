# Facilities Management - Closed Cells as of September 9th, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-closed-cells-as-of-september-9th-2011-3f4cc) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/tf4d-rugi) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tf4d-rugi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tf4d-rugi/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | tf4d-rugi |
| Name | Facilities Management - Closed Cells as of September 9th, 2011 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2011-11-23T17:16:17Z |
| Publication Date | 2014-10-09T22:31:02Z |

## Description

A Chart showing Cook County Department of Corrections -- Closed Cells. A closed cell is unable to house inmates.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | division_facility | Division Facility | text      | text        |
| Yes      | numeric metric | cells             | Cells             | number    | number      |
| Yes      | numeric metric | plumbing          | Plumbing          | number    | number      |
| Yes      | numeric metric | electrician       | Electrician       | number    | number      |
| Yes      | numeric metric | carpenter         | Carpenter         | number    | number      |
| Yes      | numeric metric | electrician_tech  | Electrician Tech  | number    | number      |
| Yes      | numeric metric | tinsmith          | Tinsmith          | number    | number      |
| Yes      | numeric metric | engineer          | Engineer          | number    | number      |
| Yes      | numeric metric | brickworker       | Brickworker       | number    | number      |
| Yes      | numeric metric | ironworker        | Ironworker        | number    | number      |
| Yes      | numeric metric | miscellaneous     | Miscellaneous     | number    | number      |
| Yes      | numeric metric | glazier           | Glazier           | number    | number      |
| Yes      | numeric metric | total_cells       | TOTAL CELLS       | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tf4d-rugi d:2011-01-01T00:00:00.000Z t:division_facility=I m:electrician=0 m:cells=608 m:tinsmith=0 m:ironworker=0 m:miscellaneous=0 m:electrician_tech=0 m:brickworker=0 m:glazier=0 m:carpenter=0 m:plumbing=2 m:engineer=0 m:total_cells=2

series e:tf4d-rugi d:2011-01-01T00:00:00.000Z t:division_facility=II m:electrician=0 m:tinsmith=0 m:ironworker=0 m:miscellaneous=0 m:electrician_tech=0 m:brickworker=0 m:glazier=0 m:carpenter=0 m:plumbing=0 m:engineer=0 m:total_cells=0

series e:tf4d-rugi d:2011-01-01T00:00:00.000Z t:division_facility=III m:electrician=0 m:cells=180 m:tinsmith=0 m:ironworker=0 m:miscellaneous=0 m:electrician_tech=0 m:brickworker=0 m:glazier=0 m:carpenter=0 m:plumbing=0 m:engineer=0 m:total_cells=0
```

## Meta Commands

```ls
metric m:cells p:integer l:Cells t:dataTypeName=number

metric m:plumbing p:integer l:Plumbing t:dataTypeName=number

metric m:electrician p:integer l:Electrician t:dataTypeName=number

metric m:carpenter p:integer l:Carpenter t:dataTypeName=number

metric m:electrician_tech p:integer l:"Electrician Tech" t:dataTypeName=number

metric m:tinsmith p:integer l:Tinsmith t:dataTypeName=number

metric m:engineer p:integer l:Engineer t:dataTypeName=number

metric m:brickworker p:integer l:Brickworker t:dataTypeName=number

metric m:ironworker p:integer l:Ironworker t:dataTypeName=number

metric m:miscellaneous p:integer l:Miscellaneous t:dataTypeName=number

metric m:glazier p:integer l:Glazier t:dataTypeName=number

metric m:total_cells p:double l:"TOTAL CELLS" t:dataTypeName=percent

entity e:tf4d-rugi l:"Facilities Management - Closed Cells as of September 9th, 2011" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/tf4d-rugi

property e:tf4d-rugi t:meta.view v:id=tf4d-rugi v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Closed Cells as of September 9th, 2011" v:attribution="Cook County Department of Facilities Management"

property e:tf4d-rugi t:meta.view.license v:name="Public Domain"

property e:tf4d-rugi t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:tf4d-rugi t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| division_facility | cells | plumbing | electrician | carpenter | electrician_tech | tinsmith | engineer | brickworker | ironworker | miscellaneous | glazier | total_cells | 
| ================= | ===== | ======== | =========== | ========= | ================ | ======== | ======== | =========== | ========== | ============= | ======= | =========== | 
| I                 | 608   | 2        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 2           | 
| II                |       | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| III               | 180   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| IV                | 320   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| V                 | 480   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| VI                | 496   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| VIII              |       | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| IX                | 540   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| X                 | 384   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
| XI                | 768   | 0        | 0           | 0         | 0                | 0        | 0        | 0           | 0          | 0             | 0       | 0           | 
```