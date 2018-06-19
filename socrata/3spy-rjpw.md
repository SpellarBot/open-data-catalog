# Transportable Classroom Units- Buildings Only

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportable-classroom-units-buildings-only) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3spy-rjpw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3spy-rjpw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3spy-rjpw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3spy-rjpw |
| Name | Transportable Classroom Units- Buildings Only |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Created | 2015-03-02T22:08:56Z |
| Publication Date | 2015-03-02T22:10:58Z |

## Description

Transportable Classroom Units- Buildings Only

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | numeric metric | jur_dist         | JUR DIST         | number    | number      |
| Yes      | series tag     | bldg_id          | BLDG ID          | text      | text        |
| Yes      | series tag     | building_name    | BUILDING NAME    | text      | text        |
| No       |                | building_address | BUILDING ADDRESS | text      | text        |
| Yes      | numeric metric | no_of_tcus       | NO OF TCUS       | number    | number      |
| Yes      | numeric metric | enrollment       | ENROLLMENT       | number    | number      |
| Yes      | numeric metric | council_dist     | COUNCIL DIST     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = building_address
```

## Data Commands

```ls
series e:3spy-rjpw d:2015-03-02T14:09:00.000Z t:building_name="P.S. 163 TRANSPORTABLE - M" t:bldg_id=M919 m:council_dist=7 m:jur_dist=3 m:no_of_tcus=2 m:enrollment=120

series e:3spy-rjpw d:2015-03-02T14:09:00.000Z t:building_name="P.S. 48 TRANSPORTABLE - MANHATTAN" t:bldg_id=M902 m:council_dist=10 m:jur_dist=6 m:no_of_tcus=2 m:enrollment=100

series e:3spy-rjpw d:2015-03-02T14:09:00.000Z t:building_name="P.S. 5 TRANSPORTABLE - M" t:bldg_id="M921 **" m:council_dist=10 m:jur_dist=6 m:no_of_tcus=2 m:enrollment=0
```

## Meta Commands

```ls
metric m:jur_dist p:integer l:"JUR DIST" t:dataTypeName=number

metric m:no_of_tcus p:integer l:"NO OF TCUS" t:dataTypeName=number

metric m:enrollment p:integer l:ENROLLMENT t:dataTypeName=number

metric m:council_dist p:integer l:"COUNCIL DIST" t:dataTypeName=number

entity e:3spy-rjpw l:"Transportable Classroom Units- Buildings Only" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/3spy-rjpw

property e:3spy-rjpw t:meta.view v:id=3spy-rjpw v:category=Education v:averageRating=0 v:name="Transportable Classroom Units- Buildings Only" v:attribution="School Construction Authority (SCA)"

property e:3spy-rjpw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3spy-rjpw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jur_dist | bldg_id | building_name                     | building_address      | no_of_tcus | enrollment | council_dist | 
| =========== | ======== | ======= | ================================= | ===================== | ========== | ========== | ============ | 
| 1425305340  | 3        | M919    | P.S. 163 TRANSPORTABLE - M        | 163 WEST 97 STREET    | 2          | 120        | 7            | 
| 1425305340  | 6        | M902    | P.S. 48 TRANSPORTABLE - MANHATTAN | 4360 BROADWAY         | 2          | 100        | 10           | 
| 1425305340  | 6        | M921 ** | P.S. 5 TRANSPORTABLE - M          | 3703 TENTH AVENUE     | 2          | 0          | 10           | 
| 1425305340  | 6        | M965    | I.S. 349 - MANHATTAN              | 549 AUDOBON AVENUE    | 15         | 487        | 10           | 
| 1425305340  | 8        | X915    | P.S. 119 TRANSPORTABLE - X        | 1075 PUGSLEY AVENUE   | 2          | 100        | 18           | 
| 1425305340  | 8        | X938    | P.S. 138 TRANSPORTABLE - X        | 2060 LAFAYETTE AVENUE | 2          | 48         | 18           | 
| 1425305340  | 8        | X947    | P.S. 14 TRANSPORTABLE - X         | 3041 BRUCKNER BLVD.   | 2          | 100        | 13           | 
| 1425305340  | 8        | X948    | P.S. 71 TRANSPORTABLE - X         | 3040 ROBERTS AVENUE   | 2          | 137        | 13           | 
| 1425305340  | 9        | X924    | P.S. 64 TRANSPORTABLE - X         | 1425 WALTON AVENUE    | 2          | 0          | 16           | 
| 1425305340  | 9        | X928 ** | P.S. 28 TRANSPORTABLE - X         | 1861 ANTHONY AVENUE   | 1          | 0          | 15           | 
```