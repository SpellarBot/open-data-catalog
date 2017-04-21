# State University of New York (SUNY) Trends in Enrollment of Students by Race/Ethnicity and by SUNY Sector: Beginning Fall 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-of-new-york-suny-trends-in-enrollment-of-students-by-race-ethnicity-and-b) |
| Metadata | [Link](https://data.ny.gov/api/views/ms8i-dzsk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ms8i-dzsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ms8i-dzsk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ms8i-dzsk |
| Name | State University of New York (SUNY) Trends in Enrollment of Students by Race/Ethnicity and by SUNY Sector: Beginning Fall 2002 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, enrollment, race, ethnicity, higher education |
| Created | 2014-01-09T18:11:08Z |
| Publication Date | 2016-09-12T14:48:43Z |

## Description

Enrollment trends by SUNY Sector for home institution students by their racial/ethnic group beginning Fall 2002.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | term                                      | Term                                      | text      | text        |
| Yes      | series tag     | institution_sector                        | Institution Sector                        | text      | text        |
| Yes      | numeric metric | total_enrollment                          | Total Enrollment                          | number    | number      |
| Yes      | numeric metric | white                                     | White                                     | number    | number      |
| Yes      | numeric metric | black_or_african_american                 | Black or African American                 | number    | number      |
| Yes      | numeric metric | hispanic_latino                           | Hispanic/Latino                           | number    | number      |
| Yes      | numeric metric | american_indian_or_alaska_native          | American Indian or Alaska Native          | number    | number      |
| Yes      | numeric metric | native_hawaiian_or_other_pacific_islander | Native Hawaiian or Other Pacific Islander | number    | number      |
| Yes      | numeric metric | two_or_more_race                          | Two or More Races                         | number    | number      |
| Yes      | numeric metric | asian                                     | Asian                                     | number    | number      |
| Yes      | numeric metric | non_resident_alien                        | Non-resident Alien                        | number    | number      |
| Yes      | numeric metric | unknown                                   | Unknown                                   | number    | number      |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ms8i-dzsk d:2002-01-01T00:00:00.000Z t:term="Fall 2002" t:institution_sector="Doctoral Degree Granting Institutions" m:black_or_african_american=6129 m:hispanic_latino=4320 m:non_resident_alien=8464 m:native_hawaiian_or_other_pacific_islander=0 m:total_enrollment=92295 m:white=51827 m:american_indian_or_alaska_native=285 m:unknown=11716 m:two_or_more_race=0 m:asian=9554

series e:ms8i-dzsk d:2002-01-01T00:00:00.000Z t:term="Fall 2002" t:institution_sector="Comprehensive Colleges" m:black_or_african_american=5414 m:hispanic_latino=3699 m:non_resident_alien=1867 m:native_hawaiian_or_other_pacific_islander=0 m:total_enrollment=88899 m:white=68727 m:american_indian_or_alaska_native=388 m:unknown=6987 m:two_or_more_race=0 m:asian=1817

series e:ms8i-dzsk d:2002-01-01T00:00:00.000Z t:term="Fall 2002" t:institution_sector="Technology Colleges" m:black_or_african_american=2108 m:hispanic_latino=1215 m:non_resident_alien=513 m:native_hawaiian_or_other_pacific_islander=0 m:total_enrollment=23223 m:white=17517 m:american_indian_or_alaska_native=137 m:unknown=1182 m:two_or_more_race=0 m:asian=551
```

## Meta Commands

```ls
metric m:total_enrollment p:integer l:"Total Enrollment" t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:black_or_african_american p:integer l:"Black or African American" t:dataTypeName=number

metric m:hispanic_latino p:integer l:Hispanic/Latino t:dataTypeName=number

metric m:american_indian_or_alaska_native p:integer l:"American Indian or Alaska Native" t:dataTypeName=number

metric m:native_hawaiian_or_other_pacific_islander p:integer l:"Native Hawaiian or Other Pacific Islander" t:dataTypeName=number

metric m:two_or_more_race p:integer l:"Two or More Races" t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:non_resident_alien p:integer l:"Non-resident Alien" t:dataTypeName=number

metric m:unknown p:integer l:Unknown t:dataTypeName=number

entity e:ms8i-dzsk l:"State University of New York (SUNY) Trends in Enrollment of Students by Race/Ethnicity and by SUNY Sector: Beginning Fall 2002" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/ms8i-dzsk

property e:ms8i-dzsk t:meta.view v:id=ms8i-dzsk v:category=Education v:attributionLink=http://www.suny.edu v:averageRating=0 v:name="State University of New York (SUNY) Trends in Enrollment of Students by Race/Ethnicity and by SUNY Sector: Beginning Fall 2002" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:ms8i-dzsk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ms8i-dzsk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ms8i-dzsk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| term      | institution_sector                    | total_enrollment | white  | black_or_african_american | hispanic_latino | american_indian_or_alaska_native | native_hawaiian_or_other_pacific_islander | two_or_more_race | asian | non_resident_alien | unknown | 
| ========= | ===================================== | ================ | ====== | ========================= | =============== | ================================ | ========================================= | ================ | ===== | ================== | ======= | 
| Fall 2002 | Doctoral Degree Granting Institutions | 92295            | 51827  | 6129                      | 4320            | 285                              | 0                                         | 0                | 9554  | 8464               | 11716   | 
| Fall 2002 | Comprehensive Colleges                | 88899            | 68727  | 5414                      | 3699            | 388                              | 0                                         | 0                | 1817  | 1867               | 6987    | 
| Fall 2002 | Technology Colleges                   | 23223            | 17517  | 2108                      | 1215            | 137                              | 0                                         | 0                | 551   | 513                | 1182    | 
| Fall 2002 | Community Colleges                    | 198522           | 145595 | 18700                     | 12099           | 1104                             | 0                                         | 0                | 6003  | 4119               | 10902   | 
| Fall 2003 | Doctoral Degree Granting Institutions | 94041            | 53050  | 6150                      | 4464            | 261                              | 0                                         | 0                | 9758  | 8590               | 11768   | 
| Fall 2003 | Comprehensive Colleges                | 87543            | 66356  | 5369                      | 3765            | 379                              | 0                                         | 0                | 1836  | 2153               | 7685    | 
| Fall 2003 | Technology Colleges                   | 23809            | 17841  | 2122                      | 1239            | 117                              | 0                                         | 0                | 606   | 550                | 1334    | 
| Fall 2003 | Community Colleges                    | 204487           | 148061 | 19869                     | 12623           | 1046                             | 0                                         | 0                | 6224  | 3735               | 12929   | 
| Fall 2004 | Doctoral Degree Granting Institutions | 92737            | 51876  | 6069                      | 4555            | 282                              | 0                                         | 0                | 9680  | 8513               | 11762   | 
| Fall 2004 | Comprehensive Colleges                | 86808            | 64591  | 5441                      | 3930            | 345                              | 0                                         | 0                | 1853  | 2268               | 8380    | 
```