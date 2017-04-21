# Subdivisions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/subdivisions) |
| Metadata | [Link](https://data.brla.gov/api/views/px43-apna) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/px43-apna/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/px43-apna/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | px43-apna |
| Name | Subdivisions |
| Attribution | City-Parish Planning Commission |
| Category | Housing and Development |
| Tags | subdivision; property; lot; cadastral |
| Created | 2015-05-20T01:20:09Z |
| Publication Date | 2015-07-12T01:24:44Z |

## Description

This dataset is an official listing of all approved and recorded subdivisions in East Baton Rouge Parish, Louisiana.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name              | Data Type     | Render Type   |
| ======== | ============== | ===================== | ================= | ============= | ============= |
| Yes      | series tag     | subd_id               | SUBDIVISION ID    | text          | number        |
| Yes      | series tag     | subd_name             | SUBDIVISION NAME  | text          | text          |
| Yes      | series tag     | subd_description      | DESCRIPTION       | text          | text          |
| Yes      | series tag     | subd_type             | TYPE              | text          | text          |
| Yes      | numeric metric | subd_lot_count        | LOT COUNT         | number        | number        |
| No       |                | subd_perl_date        | PRELIMINARY DATE  | text          | text          |
| Yes      | time           | subd_final_date       | FINAL DATE        | calendar_date | calendar_date |
| Yes      | numeric metric | subd_plan_dist        | PLANNING DISTRICT | number        | number        |
| Yes      | numeric metric | subd_sub_area         | SUBAREA           | number        | number        |
| Yes      | series tag     | subd_rc               | RES OR COMM       | text          | text          |
| Yes      | series tag     | subd_notation         | NOTATION          | text          | text          |
| Yes      | series tag     | subd_map_key          | MAP KEY           | text          | text          |
| Yes      | numeric metric | subd_census_tract_num | CENSUS TRACT      | number        | text          |
```

## Time Field

```ls
Value = subd_final_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = subd_perl_date
```

## Data Commands

```ls
series e:px43-apna d:1111-11-11T00:00:00.000Z t:subd_description=UNKNOWN t:subd_rc=NONE t:subd_name="LAWRENCE LASAGE (DO NOT USE)" t:subd_type=NONE t:subd_map_key=UNKNOWN t:subd_id=2546 m:subd_census_tract_num=43.03 m:subd_plan_dist=99 m:subd_sub_area=99

series e:px43-apna d:2003-03-05T00:00:00.000Z t:subd_description=UNKNOWN t:subd_rc=R t:subd_name="BEAU BOIS AT WORTHINGTON LAKE" t:subd_type=NONE t:subd_map_key=R-7 t:subd_id=2767 m:subd_census_tract_num=40.05 m:subd_plan_dist=14 m:subd_lot_count=40 m:subd_sub_area=3

series e:px43-apna d:1941-11-01T00:00:00.000Z t:subd_description=UNKNOWN t:subd_rc=R t:subd_name="BANK ADDITION" t:subd_type=NONE t:subd_map_key=E-4 t:subd_id=19 m:subd_census_tract_num=33 m:subd_plan_dist=4 m:subd_lot_count=1645 m:subd_sub_area=3
```

## Meta Commands

```ls
metric m:subd_lot_count p:integer l:"LOT COUNT" d:"Number of lots included in the final plat" t:dataTypeName=number

metric m:subd_plan_dist p:integer l:"PLANNING DISTRICT" d:"Planning district number in which the subdivision is located" t:dataTypeName=number

metric m:subd_sub_area p:integer l:SUBAREA d:"Subarea number of the planning district in which the subdivision is located" t:dataTypeName=number

metric m:subd_census_tract_num p:float l:"CENSUS TRACT" d:"The Census 2000 tract number in which the subdivision is located" t:dataTypeName=number

entity e:px43-apna l:Subdivisions t:attribution="City-Parish Planning Commission" t:url=https://data.brla.gov/api/views/px43-apna

property e:px43-apna t:meta.view v:id=px43-apna v:category="Housing and Development" v:attributionLink=http://brgov.com/dept/planning v:averageRating=0 v:name=Subdivisions v:attribution="City-Parish Planning Commission"

property e:px43-apna t:meta.view.license v:name="Public Domain"

property e:px43-apna t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:px43-apna t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| subd_id | subd_name                     | subd_description | subd_type | subd_lot_count | subd_perl_date | subd_final_date     | subd_plan_dist | subd_sub_area | subd_rc | subd_notation | subd_map_key | subd_census_tract_num | 
| ======= | ============================= | ================ | ========= | ============== | ============== | =================== | ============== | ============= | ======= | ============= | ============ | ===================== | 
| 2546    | LAWRENCE LASAGE (DO NOT USE)  | UNKNOWN          | NONE      |                | UNKNOWN        | 1111-11-11T00:00:00 | 99             | 99            | NONE    |               | UNKNOWN      | 43.03                 | 
| 2767    | BEAU BOIS AT WORTHINGTON LAKE | UNKNOWN          | NONE      | 40             | UNKNOWN        | 2003-03-05T00:00:00 | 14             | 3             | R       |               | R-7          | 40.05                 | 
| 19      | BANK ADDITION                 | UNKNOWN          | NONE      | 1645           | UNKNOWN        | 1941-11-01T00:00:00 | 4              | 3             | R       |               | E-4          | 33.00                 | 
| 13094   | SIX OAKS ESTATES              | UNKNOWN          | NONE      | 8              | UNKNOWN        | 2013-06-21T00:00:00 | 16             | 4             | R       |               | M-9          | 38.05                 | 
| 1394    | MEADOW LEA                    | 2ND FILING       | NONE      | 20             | 07/14/1953     | 1957-07-15T00:00:00 | 14             | 3             | R       |               | N-6          | 26.02                 | 
| 928     | HENRY PLACE                   | UNKNOWN          | NONE      | 6              | 09/30/1989     | 1993-10-01T00:00:00 | 10             | 3             | R       |               | K-7,8        | 19.00                 | 
| 1062    | IBERVILLE TERRACE             | 3RD FILING       | NONE      | 170            | 04/19/1968     | 1972-04-20T00:00:00 | 16             | 3             | R       |               | R-8          | 40.02                 | 
| 1775    | QUARTER, THE                  | UNKNOWN          | NONE      | 13             | 01/27/1976     | 1980-01-28T00:00:00 | 14             | 1             | R       |               | L-9          | 38.02                 | 
| 1385    | MC CLURE PLACE                | UNKNOWN          | NONE      | 69             | 03/06/1950     | 1950-03-07T00:00:00 | 3              | 2             | R       |               | A-1          | 42.03                 | 
| 13180   | PECUE LANE ESTATES            | UNKNOWN          | NONE      | 11             | UNKNOWN        | 2016-04-14T00:00:00 | 16             | 3             | R       |               | UNKNOWN      | 40.09                 | 
```