# Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schools-61bc3) |
| Metadata | [Link](https://data.sfgov.org/api/views/tpp3-epx2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tpp3-epx2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tpp3-epx2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tpp3-epx2 |
| Name | Schools |
| Category | Economy and Community |
| Tags | public schools, private schools, child development centers, community college |
| Created | 2016-07-11T22:21:47Z |
| Publication Date | 2016-07-11T22:31:15Z |

## Description

Consolidated Infant, Pre-K, and K-14 education points for facilities both public and private.

Point features are intended to be located within a building footprint relevant to each site, so that they can be used to select an appropriate building footprint or parcel as seed for any required buffering.

Buffering may be applied when limiting possible sites for certain businesses or specific individuals, whenever these must remain a minimum distance from school locations.

Sources include: cde.ca.gov  State of California Department of Education
City and County Department of Technology, San Francisco Enterprise Geographic Information System Program

Data current as of December 8, 2015

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | campus_name         | Campus Name         | text      | text        |
| Yes      | series tag     | ccsf_entity         | CCSF Entity         | text      | text        |
| Yes      | numeric metric | lower_grade         | Lower Grade         | number    | number      |
| Yes      | numeric metric | upper_grade         | Upper Grade         | number    | number      |
| Yes      | series tag     | grade_range         | Grade Range         | text      | text        |
| Yes      | series tag     | category            | Category            | text      | text        |
| Yes      | series tag     | map_label           | Map Label           | text      | text        |
| Yes      | numeric metric | lower_age           | Lower Age           | number    | number      |
| Yes      | numeric metric | upper_age           | Upper Age           | number    | number      |
| Yes      | series tag     | general_type        | General Type        | text      | text        |
| Yes      | series tag     | cds_code            | CDS Code            | text      | number      |
| No       |                | campus_address      | Campus Address      | text      | text        |
| Yes      | series tag     | supervisor_district | Supervisor District | text      | number      |
| Yes      | series tag     | county_fips         | County FIPS         | text      | text        |
| Yes      | series tag     | county_name         | County Name         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = campus_address
```

## Data Commands

```ls
series e:tpp3-epx2 d:2016-07-11T15:21:52.000Z t:general_type=PS t:category="USD Grades K-5" t:map_label=PS001 t:county_fips=06075 t:cds_code=38684786040695 t:ccsf_entity=SFUSD t:grade_range=K-5 t:county_name="SAN FRANCISCO" t:campus_name="Alamo Elementary School" t:supervisor_district=1 m:upper_grade=5 m:lower_grade=0 m:upper_age=10 m:lower_age=5

series e:tpp3-epx2 d:2016-07-11T15:21:52.000Z t:general_type=PS t:category="USD Grades K-5" t:map_label=PS002 t:county_fips=06075 t:cds_code=38684786040703 t:ccsf_entity=SFUSD t:grade_range=K-5 t:county_name="SAN FRANCISCO" t:campus_name="Alvarado Elementary School" t:supervisor_district=8 m:upper_grade=5 m:lower_grade=0 m:upper_age=10 m:lower_age=5

series e:tpp3-epx2 d:2016-07-11T15:21:52.000Z t:general_type=PS t:category="USD Grades 6-8" t:map_label=PS003 t:county_fips=06075 t:cds_code=38684786062020 t:ccsf_entity=SFUSD t:grade_range=6-8 t:county_name="SAN FRANCISCO" t:campus_name="Aptos Middle School" t:supervisor_district=7 m:upper_grade=8 m:lower_grade=6 m:upper_age=13 m:lower_age=11
```

## Meta Commands

```ls
metric m:lower_grade p:integer l:"Lower Grade" t:dataTypeName=number

metric m:upper_grade p:integer l:"Upper Grade" t:dataTypeName=number

metric m:lower_age p:integer l:"Lower Age" d:"Low generic age of the site's programs corresponding to grades as below Grade Age Identifier (used for school classification) -4 1 INF (infant care) -3 2 TOD (Toddler care) -2 3 PK1 (pre-Kindergarten year 1 of 2) -1 4 PK2 (pre-Kindergarten year 2 of 2) 0 4 TK (transitional Kindergarten) 0 5 K (Kindergarten) 1 6 (First Grade) 2 7 (Second Grade) 3 8 (Third Grade) 4 9 (Fourth Grade) 5 10 (Fifth Grade) 6 11 (Sixth Grade) 7 12 (Seventh Grade) 8 13 (Eighth Grade) 9 14 (Ninth Grade) 10 15 (Tenth Grade) 11 16 (Elevnth Grade) 12 17 (Twelfth Grade) 13 18 (College Freshman) 14 19 (College Sophomore)" t:dataTypeName=number

metric m:upper_age p:integer l:"Upper Age" t:dataTypeName=number

entity e:tpp3-epx2 l:Schools t:url=https://data.sfgov.org/api/views/tpp3-epx2

property e:tpp3-epx2 t:meta.view v:id=tpp3-epx2 v:category="Economy and Community" v:averageRating=0 v:name=Schools

property e:tpp3-epx2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tpp3-epx2 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:tpp3-epx2 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | campus_name                                                                       | ccsf_entity | lower_grade | upper_grade | grade_range | category               | map_label | lower_age | upper_age | general_type | cds_code       | campus_address                           | supervisor_district | county_fips | county_name   | 
| =========== | ================================================================================= | =========== | =========== | =========== | =========== | ====================== | ========= | ========= | ========= | ============ | ============== | ======================================== | =================== | =========== | ============= | 
| 1468250512  | Alamo Elementary School                                                           | SFUSD       | 0           | 5           | K-5         | USD Grades K-5         | PS001     | 5         | 10        | PS           | 38684786040695 | 250 23RD AVE, San Francisco, CA 94121    | 1                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Alvarado Elementary School                                                        | SFUSD       | 0           | 5           | K-5         | USD Grades K-5         | PS002     | 5         | 10        | PS           | 38684786040703 | 625 DOUGLASS ST, San Francisco, CA 94114 | 8                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Aptos Middle School                                                               | SFUSD       | 6           | 8           | 6-8         | USD Grades 6-8         | PS003     | 11        | 13        | PS           | 38684786062020 | 105 APTOS AVE, San Francisco, CA 94127   | 7                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Argonne Early Education School                                                    | SFUSD       | -2          | 0           | PK-TK       | USD PreK/TK            | PS004     | 3         | 5         | PS           | 384000981      | 750 16TH AVE, San Francisco, CA 94118    | 1                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Argonne Elementary School                                                         | SFUSD       | 0           | 5           | K-5         | USD Grades K-5         | PS005     | 5         | 10        | PS           | 38684786040737 | 680 18TH AVE, San Francisco, CA 94121    | 1                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Asawa, Ruth Asawa San Francisco School Of The Arts / Academy Of Arts And Sciences | SFUSD       | 9           | 12          | 9-12        | USD Grades 9-12        | PS006     | 14        | 17        | PS           | 38684783830387 | 555 PORTOLA DR, SAN FRANCISCO CA, 94131  | 8                   | 06075       | SAN FRANCISCO | 
| 1468250512  | Balboa High School                                                                | SFUSD       | 9           | 12          | 9-12        | USD Grades 9-12        | PS007     | 14        | 17        | PS           | 38684783830288 | 1000 CAYUGA AVE, San Francisco, CA 94112 | 11                  | 06075       | SAN FRANCISCO | 
| 1468250512  | Brown, Willie Brown Jr Middle School                                              | SFUSD       | 6           | 8           | 6-8         | USD Grades 6-8         | PS008     | 11        | 13        | PS           | 38684780132241 | 2055 SILVER AVE, San Francisco, CA 94124 | 10                  | 06075       | SAN FRANCISCO | 
| 1468250512  | Bryant Early Education / Bryant Elementary                                        | SFUSD       | -2          | 5           | PK-5        | USD PreK-5, Grades K-5 | PS009     | 3         | 10        | PS           | 38684786040778 | 2641 25TH ST, San Francisco, CA 94110    | 10                  | 06075       | SAN FRANCISCO | 
| 1468250512  | Buena Vista / Horace Mann                                                         | SFUSD       | 0           | 8           | K-8         | USD Grades K-8         | PS010     | 5         | 13        | PS           | 38684786062046 | 3351 23RD ST, San Francisco, CA 94110    | 9                   | 06075       | SAN FRANCISCO | 
```