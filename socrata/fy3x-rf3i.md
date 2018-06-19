# SDOT_SIGNALS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-signals-e8185) |
| Metadata | [Link](https://data.seattle.gov/api/views/fy3x-rf3i) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/fy3x-rf3i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/fy3x-rf3i/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | fy3x-rf3i |
| Name | SDOT_SIGNALS |
| Attribution | Seattle City GIS Program |
| Category | Transportation |
| Tags | traffic signals, red lights, stop lights |
| Created | 2011-12-20T18:56:03Z |
| Publication Date | 2011-12-21T19:28:23Z |

## Description

SDOT maintained traffic signals in Seattle

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | objectid_1            | OBJECTID_1            | text      | number      |
| Yes      | series tag     | unitid                | UNITID                | text      | text        |
| Yes      | numeric metric | compkey               | COMPKEY               | number    | number      |
| Yes      | series tag     | comptype              | COMPTYPE              | text      | number      |
| Yes      | numeric metric | intr_compkey          | INTR_COMPKEY          | number    | number      |
| Yes      | series tag     | intr_unitid           | INTR_UNITID           | text      | text        |
| Yes      | numeric metric | intr_distance         | INTR_DISTANCE         | number    | number      |
| Yes      | series tag     | description           | DESCRIPTION           | text      | text        |
| Yes      | numeric metric | seg_compkey           | SEG_COMPKEY           | number    | number      |
| Yes      | series tag     | objectid              | OBJECTID              | text      | number      |
| Yes      | numeric metric | arterialclasscd       | ARTERIALCLASSCD       | number    | text        |
| Yes      | numeric metric | compkey_1             | COMPKEY_1             | number    | number      |
| Yes      | numeric metric | intersectiondetailkey | INTERSECTIONDETAILKEY | number    | number      |
| Yes      | series tag     | signalmaintdistcd     | SIGNALMAINTDISTCD     | text      | text        |
| Yes      | series tag     | signaltypecd          | SIGNALTYPECD          | text      | text        |
| Yes      | numeric metric | dgmapnbr              | DGMAPNBR              | number    | number      |
| Yes      | numeric metric | dgnodenbr             | DGNODENBR             | number    | number      |
| Yes      | time           | adddttm               | ADDDTTM               | date      | date        |
| Yes      | series tag     | addby                 | ADDBY                 | text      | text        |
| Yes      | series tag     | modby                 | MODBY                 | text      | text        |
| No       |                | moddttm               | MODDTTM               | date      | date        |
```

## Time Field

```ls
Value = adddttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = moddttm
```

## Data Commands

```ls
series e:fy3x-rf3i d:2017-04-21T08:07:41.651Z t:unitid=SGL-278 t:description=0 t:objectid_1=1 t:comptype=74 t:intr_unitid=0 m:intr_compkey=0 m:seg_compkey=0 m:intr_distance=0 m:compkey=272753

series e:fy3x-rf3i d:2017-04-21T08:07:41.651Z t:unitid=SGL-669 t:description=0 t:objectid_1=2 t:comptype=74 t:intr_unitid=0 m:intr_compkey=0 m:seg_compkey=0 m:intr_distance=0 m:compkey=272754

series e:fy3x-rf3i d:2017-04-21T08:07:41.651Z t:unitid=SGL-178 t:description=0 t:objectid_1=3 t:comptype=74 t:intr_unitid=0 m:intr_compkey=0 m:seg_compkey=0 m:intr_distance=0 m:compkey=272755
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:intr_compkey p:integer l:INTR_COMPKEY d:INTR_COMPKEY t:dataTypeName=number

metric m:intr_distance p:decimal l:INTR_DISTANCE d:INTR_DISTANCE t:dataTypeName=number

metric m:seg_compkey p:integer l:SEG_COMPKEY d:SEG_COMPKEY t:dataTypeName=number

metric m:arterialclasscd p:integer l:ARTERIALCLASSCD d:ARTERIALCLASSCD t:dataTypeName=number

metric m:compkey_1 p:integer l:COMPKEY_1 d:COMPKEY_1 t:dataTypeName=number

metric m:intersectiondetailkey p:integer l:INTERSECTIONDETAILKEY d:INTERSECTIONDETAILKEY t:dataTypeName=number

metric m:dgmapnbr p:integer l:DGMAPNBR d:DGMAPNBR t:dataTypeName=number

metric m:dgnodenbr p:integer l:DGNODENBR d:DGNODENBR t:dataTypeName=number

entity e:fy3x-rf3i l:SDOT_SIGNALS t:attribution="Seattle City GIS Program" t:url=https://data.seattle.gov/api/views/fy3x-rf3i

property e:fy3x-rf3i t:meta.view v:id=fy3x-rf3i v:category=Transportation v:averageRating=0 v:name=SDOT_SIGNALS v:attribution="Seattle City GIS Program"

property e:fy3x-rf3i t:meta.view.license v:name="Public Domain"

property e:fy3x-rf3i t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:fy3x-rf3i t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid_1 | unitid  | compkey | comptype | intr_compkey | intr_unitid | intr_distance | description | seg_compkey | objectid | arterialclasscd | compkey_1 | intersectiondetailkey | signalmaintdistcd | signaltypecd | dgmapnbr | dgnodenbr | adddttm | addby | modby | moddttm | 
| ========== | ======= | ======= | ======== | ============ | =========== | ============= | =========== | =========== | ======== | =============== | ========= | ===================== | ================= | ============ | ======== | ========= | ======= | ===== | ===== | ======= | 
| 1          | SGL-278 | 272753  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 2          | SGL-669 | 272754  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 3          | SGL-178 | 272755  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 4          | SGL-589 | 272756  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 5          | SGL-022 | 272757  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 6          | SGL-75  | 272758  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 7          | SGL-249 | 272759  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 8          | SGL-263 | 272760  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 9          | SGL-148 | 272761  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
| 10         | SGL-679 | 272762  | 74       | 0            | 0           | 0             | 0           | 0           |          |                 |           |                       |                   |              |          |           |         |       |       |         | 
```