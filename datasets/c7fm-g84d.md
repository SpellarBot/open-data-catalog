# Tuition Assistance Program (TAP) Fall Headcount By College, Sector Group, and Level of Study: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tuition-assistance-program-tap-fall-headcount-by-college-sector-group-and-level-of-study-2) |
| Metadata | [Link](https://data.ny.gov/api/views/c7fm-g84d) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c7fm-g84d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c7fm-g84d/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c7fm-g84d |
| Name | Tuition Assistance Program (TAP) Fall Headcount By College, Sector Group, and Level of Study: Beginning 2000 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | tap, postsecondary schools, education |
| Created | 2013-06-07T17:25:56Z |
| Publication Date | 2017-01-27T21:38:29Z |

## Description

The Tuition Assistance Program (TAP), New York's largest student financial aid grant program, helps eligible New York residents attending in-state post-secondary institutions pay for tuition.  TAP grants are based on the applicant?s and his or her family?s New York State taxable income.  This data includes the number of recipients as measured by students receiving a TAP award for the fall semester beginning academic year 2000.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | academic_year       | Academic Year       | number    | number      |
| Yes      | series tag     | tap_college_code    | TAP College Code    | text      | number      |
| Yes      | series tag     | federal_school_code | Federal School Code | text      | number      |
| Yes      | series tag     | level               | Level               | text      | text        |
| Yes      | series tag     | tap_level_of_study  | TAP Level of Study  | text      | text        |
| Yes      | series tag     | tap_college_name    | TAP College Name    | text      | text        |
| Yes      | series tag     | sector_type         | Sector Type         | text      | text        |
| Yes      | series tag     | tap_sector_group    | TAP Sector Group    | text      | text        |
| Yes      | numeric metric | tap_fall_headcount  | TAP Fall Headcount  | number    | number      |
```

## Time Field

```ls
Value = academic_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c7fm-g84d d:2015-01-01T00:00:00.000Z t:tap_level_of_study="2 yr Undergrad" t:level=U t:federal_school_code=8611 t:sector_type=PUBLIC t:tap_sector_group="2-CUNY CC" t:tap_college_name="CUNY HOSTOS CC" t:tap_college_code=1401 m:tap_fall_headcount=2660

series e:c7fm-g84d d:2015-01-01T00:00:00.000Z t:tap_level_of_study="5 yr Undergrad" t:level=U t:federal_school_code=2667 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="DOWLING COLLEGE  4YR UNDERGRAD" t:tap_college_code=11 m:tap_fall_headcount=6

series e:c7fm-g84d d:2015-01-01T00:00:00.000Z t:tap_level_of_study="5 yr Undergrad" t:level=U t:federal_school_code=2668 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="ALFRED UNIVERSITY 4YR UNDERGRAD" t:tap_college_code=20 m:tap_fall_headcount=12
```

## Meta Commands

```ls
metric m:tap_fall_headcount p:integer l:"TAP Fall Headcount" d:"Number of recipients as measured by students receiving a TAP award for the fall semester of study." t:dataTypeName=number

entity e:c7fm-g84d l:"Tuition Assistance Program (TAP) Fall Headcount By College, Sector Group, and Level of Study:  Beginning 2000" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/c7fm-g84d

property e:c7fm-g84d t:meta.view v:id=c7fm-g84d v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/About_TAP v:averageRating=0 v:name="Tuition Assistance Program (TAP) Fall Headcount By College, Sector Group, and Level of Study:  Beginning 2000" v:attribution="New York State Higher Education Services Corporation"

property e:c7fm-g84d t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c7fm-g84d t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:c7fm-g84d t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_college_code | federal_school_code | level | tap_level_of_study | tap_college_name                 | sector_type | tap_sector_group | tap_fall_headcount | 
| ============= | ================ | =================== | ===== | ================== | ================================ | =========== | ================ | ================== | 
| 2015          | 1401             | 8611                | U     | 2 yr Undergrad     | CUNY HOSTOS CC                   | PUBLIC      | 2-CUNY CC        | 2660               | 
| 2015          | 11               | 2667                | U     | 5 yr Undergrad     | DOWLING COLLEGE 4YR UNDERGRAD    | PRIVATE     | 5-INDEPENDENT    | 6                  | 
| 2015          | 20               | 2668                | U     | 5 yr Undergrad     | ALFRED UNIVERSITY 4YR UNDERGRAD  | PRIVATE     | 5-INDEPENDENT    | 12                 | 
| 2015          | 210              | 6448                | U     | 2 yr Undergrad     | THE BELANGER SCHOOL OF NURSING   | PRIVATE     | 5-INDEPENDENT    | 14                 | 
| 2015          | 175              | 2711                | U     | 5 yr Undergrad     | CORNELL UNIVERSITY               | PRIVATE     | 5-INDEPENDENT    | 4                  | 
| 2015          | 8272             | 31292               | U     | 5 yr Undergrad     | RABBINICAL COLLEGE OF OHR SHIMON | PRIVATE     | 9-CHAPTER XXII   | 17                 | 
| 2015          | 560              | 2788                | U     | 5 yr Undergrad     | NIAGARA UNIVERSITY 4YR UNDERGRAD | PRIVATE     | 5-INDEPENDENT    | 3                  | 
| 2015          | 840              | 9248                | U     | 2 yr Undergrad     | SAMARITAN HOSP SCH OF NURSING    | PRIVATE     | 5-INDEPENDENT    | 3                  | 
| 2015          | 1045             | 2900                | U     | 4 yr Undergrad     | WEBB INST OF NAVAL ARCH.         | PRIVATE     | 5-INDEPENDENT    | 2                  | 
| 2015          | 1410             | 2687                | U     | 4 yr Undergrad     | CUNY BROOKLYN COLLEGE            | PUBLIC      | 1-CUNY SR        | 5258               | 
```