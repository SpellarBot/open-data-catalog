# Schools (deprecated 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schools) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kqmn-byj8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kqmn-byj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kqmn-byj8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kqmn-byj8 |
| Name | Schools (deprecated 2012) |
| Attribution | Chicago Public Schools |
| Category | Education |
| Tags | facilities, gis, deprecated, cps, schools |
| Created | 2011-01-19T14:52:03Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

List of schools by name, address, type and grades. Note some facilities house multiple schools.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | school_name               | SCHOOL NAME               | text      | text        |
| Yes      | series tag  | definition                | DEFINITION                | text      | text        |
| No       |             | primary_address           | PRIMARY ADDRESS           | text      | text        |
| No       |             | second_address            | SECOND ADDRESS            | text      | text        |
| Yes      | series tag  | grades                    | GRADES                    | text      | text        |
| Yes      | series tag  | school2_name              | SCHOOL2 NAME              | text      | text        |
| No       |             | school2_primary_address   | SCHOOL2 PRIMARY ADDRESS   | text      | text        |
| No       |             | school2_secondary_address | SCHOOL2 SECONDARY ADDRESS | text      | text        |
| Yes      | series tag  | school2_grades            | SCHOOL2 GRADES            | text      | text        |
| Yes      | series tag  | school2_definition        | SCHOOL2 DEFINITION        | text      | text        |
| Yes      | series tag  | school3_name              | SCHOOL3 NAME              | text      | text        |
| No       |             | school3_primary_address   | SCHOOL3 PRIMARY ADDRESS   | text      | text        |
| No       |             | school3_secondary_address | SCHOOL3 SECONDARY ADDRESS | text      | text        |
| Yes      | series tag  | school3_grades            | SCHOOL3 GRADES            | text      | text        |
| Yes      | series tag  | school3_definition        | SCHOOL3 DEFINITION        | text      | text        |
| Yes      | series tag  | school4_name              | SCHOOL4 NAME              | text      | text        |
| No       |             | school4_primary_address   | SCHOOL4 PRIMARY ADDRESS   | text      | text        |
| No       |             | school4_secondary_address | SCHOOL4 SECONDARY ADDRESS | text      | text        |
| Yes      | series tag  | school4_grades            | SCHOOL4 GRADES            | text      | text        |
| Yes      | series tag  | school4_definition        | SCHOOL4 DEFINITION        | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = primary_address,second_address,school2_primary_address,school2_secondary_address,school3_primary_address,school3_secondary_address,school4_primary_address,school4_secondary_address
```

## Data Commands

```ls
series e:kqmn-byj8 d:2012-01-01T00:00:00.000Z t:school_name="Lawndale Acad" t:definition="Public Schools" t:grades=E m:row_number.kqmn-byj8=1

series e:kqmn-byj8 d:2012-01-01T00:00:00.000Z t:school_name="Joyner CPC" t:definition="Public Schools" t:grades=E m:row_number.kqmn-byj8=2

series e:kqmn-byj8 d:2012-01-01T00:00:00.000Z t:school_name="Armour Br" t:definition="Public Schools" t:grades=E m:row_number.kqmn-byj8=3
```

## Meta Commands

```ls
metric m:row_number.kqmn-byj8 p:long l:"Row Number"

entity e:kqmn-byj8 l:"Schools (deprecated 2012)" t:attribution="Chicago Public Schools" t:url=https://data.cityofchicago.org/api/views/kqmn-byj8

property e:kqmn-byj8 t:meta.view v:id=kqmn-byj8 v:category=Education v:attributionLink=http://www.cps.edu v:averageRating=0 v:name="Schools (deprecated 2012)" v:attribution="Chicago Public Schools"

property e:kqmn-byj8 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:kqmn-byj8 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| school_name           | definition     | primary_address       | second_address | grades | school2_name | school2_primary_address | school2_secondary_address | school2_grades | school2_definition | school3_name | school3_primary_address | school3_secondary_address | school3_grades | school3_definition | school4_name | school4_primary_address | school4_secondary_address | school4_grades | school4_definition | 
| ===================== | ============== | ===================== | ============== | ====== | ============ | ======================= | ========================= | ============== | ================== | ============ | ======================= | ========================= | ============== | ================== | ============ | ======================= | ========================= | ============== | ================== | 
| Lawndale Acad         | Public Schools | 3500 W Douglas Bl     |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Joyner CPC            | Public Schools | 1315 S Blue Island Av |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Armour Br             | Public Schools | 911 W 32nd Pl         |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Johnson               | Public Schools | 1420 S Albany Av      |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Herzl                 | Public Schools | 3711 W Douglas Bl     |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Lathrop               | Public Schools | 1440 S Christiana Av  |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Plamondon             | Public Schools | 2642 W 15th Pl        |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Hughes CE             | Public Schools | 4247 W 15th St        |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Pilsen Community Acad | Public Schools | 1420 W 17th St        |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
| Jungman               | Public Schools | 1746 S Miller St      |                | E      |              |                         |                           |                |                    |              |                         |                           |                |                    |              |                         |                           |                |                    | 
```