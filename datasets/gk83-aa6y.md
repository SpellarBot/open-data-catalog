# Update to Submitted State Aid Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/update-to-submitted-state-aid-projects) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gk83-aa6y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gk83-aa6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gk83-aa6y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gk83-aa6y |
| Name | Update to Submitted State Aid Projects |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Created | 2016-02-01T15:43:31Z |
| Publication Date | 2016-02-01T15:49:00Z |

## Description

List of projects in substantial completion with the final aid amount requested.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | project_number          | PROJECT NUMBER          | text      | text        |
| Yes      | series tag     | building_id             | BUILDING ID             | text      | text        |
| Yes      | series tag     | project_description     | PROJECT DESCRIPTION     | text      | text        |
| Yes      | series tag     | school_name             | SCHOOL NAME             | text      | text        |
| No       |                | school_address          | SCHOOL ADDRESS          | text      | text        |
| Yes      | numeric metric | sed_approved_final_cost | SED APPROVED FINAL COST | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = school_address
```

## Data Commands

```ls
series e:gk83-aa6y d:2016-02-01T07:43:49.000Z t:school_name="P.S. 128 - BROOKLYN" t:building_id=K128 t:project_number=LB4 t:project_description="Building System Improvement - Installation of a Low-Voltage Electrical System" m:sed_approved_final_cost=1265146

series e:gk83-aa6y d:2016-02-01T07:43:49.000Z t:school_name="P.S. 163 - MANHATTAN" t:building_id=M163 t:project_number=LB5 t:project_description="Asbestos  abatement" m:sed_approved_final_cost=29441

series e:gk83-aa6y d:2016-02-01T07:43:49.000Z t:school_name="P.S. 132 - BROOKLYN" t:building_id=K132 t:project_number=LB6 t:project_description="Indoor Building Improvement - Reconstruction and replacement of interior flooring" m:sed_approved_final_cost=342760
```

## Meta Commands

```ls
metric m:sed_approved_final_cost p:integer l:"SED APPROVED FINAL COST" t:dataTypeName=number

entity e:gk83-aa6y l:"Update to Submitted State Aid Projects" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/gk83-aa6y

property e:gk83-aa6y t:meta.view v:id=gk83-aa6y v:category=Education v:averageRating=0 v:name="Update to Submitted State Aid Projects" v:attribution="School Construction Authority (SCA)"

property e:gk83-aa6y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gk83-aa6y t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | project_number | building_id | project_description                                                               | school_name                 | school_address        | sed_approved_final_cost | 
| =========== | ============== | =========== | ================================================================================= | =========================== | ===================== | ======================= | 
| 1454312629  | LB4            | K128        | Building System Improvement - Installation of a Low-Voltage Electrical System     | P.S. 128 - BROOKLYN         | 2075 84 STREET        | 1265146                 | 
| 1454312629  | LB5            | M163        | Asbestos abatement                                                                | P.S. 163 - MANHATTAN        | 163 WEST 97 STREET    | 29441                   | 
| 1454312629  | LB6            | K132        | Indoor Building Improvement - Reconstruction and replacement of interior flooring | P.S. 132 - BROOKLYN         | 320 MANHATTAN AVENUE  | 342760                  | 
| 1454312629  | LB7            | M072        | Building Envelope Improvement - Parapet Reconstruction                            | P.S. 72 - MANHATTAN         | 131 EAST 104 STREET   | 881458                  | 
| 1454312629  | LB8            | Q206        | Auditorium Upgrade - replace and upgrade auditorium sound system and lighting.    | P.S. 206 - QUEENS           | 61-21 97TH PLACE      | 965000                  | 
| 1454312629  | LB9            | K307        | Building Envelope Improvement - Parapet Reconstruction                            | P.S. 307 - BROOKLYN         | 209 YORK STREET       | 2909658                 | 
| 1454312629  | LBA            | K307        | Building Envelope Improvement - Parapet Reconstruction                            | P.S. 307 - BROOKLYN         | 209 YORK STREET       | 3728001                 | 
| 1454312629  | LBB            | K293        | Building Envelope Improvement - Parapet Reconstruction                            | SCHOOL FOR INT'L STUD - K   | 284 BALTIC STREET     | 3783032                 | 
| 1454312629  | LBC            | M097        | Building Envelope Improvement - Parapet Reconstruction                            | BARD COLLEGE HS - MANHATTAN | 525 E. HOUSTON STREET | 979054                  | 
| 1454312629  | LBD            | M097        | Building Envelope Improvement - Parapet Reconstruction                            | BARD COLLEGE HS - MANHATTAN | 525 E. HOUSTON STREET | 1508155                 | 
```