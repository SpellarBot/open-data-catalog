# Families and Education Levy SY2013-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/families-and-education-levy-sy2013-2014-e53c0) |
| Metadata | [Link](https://data.seattle.gov/api/views/hb67-apeb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/hb67-apeb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/hb67-apeb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | hb67-apeb |
| Name | Families and Education Levy SY2013-2014 |
| Category | Education |
| Created | 2014-01-28T17:07:27Z |
| Publication Date | 2014-01-28T17:09:44Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name             | Data Type | Render Type |
| ======== | =========== | ============== | ================ | ========= | =========== |
| Yes      | series tag  | level          | Level            | text      | text        |
| Yes      | series tag  | school         | School           | text      | text        |
| No       |             | address        | Address          | text      | text        |
| Yes      | series tag  | city_state_zip | City, State, Zip | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:hb67-apeb d:2013-01-01T00:00:00.000Z t:city_state_zip="Seattle, WA  98115" t:school="Eckstein Middle School" t:level="Middle School" m:row_number.hb67-apeb=1

series e:hb67-apeb d:2013-01-01T00:00:00.000Z t:city_state_zip="Seattle, WA  98133" t:school="Broadview-Thompson K-8" t:level="Middle School" m:row_number.hb67-apeb=2

series e:hb67-apeb d:2013-01-01T00:00:00.000Z t:city_state_zip="Seattle, WA  98126" t:school="Roxhill Elementary" t:level="Elementary School" m:row_number.hb67-apeb=3
```

## Meta Commands

```ls
metric m:row_number.hb67-apeb p:long l:"Row Number"

entity e:hb67-apeb l:"Families and Education Levy SY2013-2014" t:url=https://data.seattle.gov/api/views/hb67-apeb

property e:hb67-apeb t:meta.view v:id=hb67-apeb v:category=Education v:averageRating=0 v:name="Families and Education Levy SY2013-2014"

property e:hb67-apeb t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:hb67-apeb t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| level             | school                            | address                   | city_state_zip    | 
| ================= | ================================= | ========================= | ================= | 
| Middle School     | Eckstein Middle School            | 3003 NE 75th Street       | Seattle, WA 98115 | 
| Middle School     | Broadview-Thompson K-8            | 13052 Greenwood Ave N     | Seattle, WA 98133 | 
| Elementary School | Roxhill Elementary                | 9430 30th Ave SW          | Seattle, WA 98126 | 
| High School       | Cleveland High School             | 5511 15th Ave S           | Seattle, WA 98108 | 
| Elementary School | Wing Luke Elementary              | 3701 S. Kenyon Street     | Seattle, WA 98118 | 
| High School       | Ingraham High School              | 1819 North 135th Street   | Seattle, WA 98133 | 
| High School       | West Seattle High School          | 3000 California Avenue SW | Seattle, WA 98116 | 
| Middle School     | Denny International Middle School | 2601 SW Kenyon Street     | Seattle, WA 98126 | 
| Middle School     | Jane Addams K-8                   | 11051 34th Ave NE         | Seattle, WA 98125 | 
| Elementary School | Madrona K-8                       | 1121 33rd Ave             | Seattle, WA 98122 | 
```