# Chicago Public Schools - School Admissions Information SY1617

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-public-schools-school-admissions-information-sy1617) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2i3t-vn5b) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2i3t-vn5b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2i3t-vn5b/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2i3t-vn5b |
| Name | Chicago Public Schools - School Admissions Information SY1617 |
| Attribution | Chicago Public Schools |
| Category | Education |
| Tags | cps, schools, metrics, report cards, 2016, 2017 |
| Created | 2016-09-14T21:32:41Z |
| Publication Date | 2016-11-22T22:39:08Z |

## Description

School admissions information for all Chicago Public Schools for the academic year 2016-2017.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | school_id                | School_ID                | text      | number      |
| Yes      | series tag  | short_name               | Short_Name               | text      | text        |
| Yes      | series tag  | long_name                | Long_Name                | text      | text        |
| Yes      | series tag  | school_type              | School_Type              | text      | text        |
| Yes      | series tag  | primary_category         | Primary_Category         | text      | text        |
| No       |             | address                  | Address                  | text      | text        |
| Yes      | series tag  | city                     | City                     | text      | text        |
| Yes      | series tag  | state                    | State                    | text      | text        |
| Yes      | series tag  | zip                      | Zip                      | text      | text        |
| Yes      | series tag  | phone                    | Phone                    | text      | number      |
| Yes      | series tag  | fax                      | Fax                      | text      | number      |
| Yes      | series tag  | cps_school_profile       | CPS_School_Profile       | url       | url         |
| Yes      | series tag  | website                  | Website                  | url       | url         |
| Yes      | series tag  | program_type             | Program_Type             | text      | text        |
| Yes      | series tag  | application_requirements | Application_Requirements | text      | text        |
| Yes      | series tag  | program_selections       | Program_Selections       | text      | text        |
| Yes      | series tag  | subprograms              | Subprograms              | text      | text        |
| Yes      | series tag  | how_to_apply             | How_To_Apply             | text      | text        |
| Yes      | series tag  | deadline                 | Deadline                 | text      | text        |
| No       |             | school_latitude          | School_Latitude          | number    | number      |
| No       |             | school_longitude         | School_Longitude         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,school_latitude,school_longitude
```

## Data Commands

```ls
series e:2i3t-vn5b d:2016-11-22T22:38:09.000Z t:school_type=Charter t:application_requirements="Not Applicable" t:zip=60632 t:program_type="Charter School" t:program_selections="Applicants are selected through a lottery process. Contact school for more details." t:phone=7735821100 t:fax=7735821101 t:website=http://www.agcchicago.org t:state=Illinois t:how_to_apply="Contact school" t:short_name="GLOBAL CITIZENSHIP" t:school_id=400009 t:city=Chicago t:long_name="Academy for Global Citizenship Charter School" t:primary_category=ES t:cps_school_profile="http://cps.edu/Schools/Pages/school.aspx?SchoolID=400009" t:deadline="Contact school" m:row_number.2i3t-vn5b=1

series e:2i3t-vn5b d:2016-11-22T22:38:09.000Z t:school_type=Charter t:application_requirements="Not Applicable" t:zip=60609 t:program_type=Charter t:program_selections="If the school receives more applications than there are seats available, students are randomly selected through a computerized lottery.  Priority is given to siblings of students enrolled in the campus." t:phone=7735488705 t:fax=7735488706 t:website=http://www.acetechnical.org t:state=Illinois t:how_to_apply="Contact school" t:short_name="ACE TECH HS" t:school_id=400010 t:city=Chicago t:long_name="ACE Technical Charter School" t:primary_category=HS t:cps_school_profile="http://cps.edu/Schools/Pages/school.aspx?SchoolID=400010" t:deadline="Contact school" m:row_number.2i3t-vn5b=2

series e:2i3t-vn5b d:2016-11-22T22:38:09.000Z t:school_type=Charter t:application_requirements="Not Applicable" t:zip=60612 t:program_type="Charter School" t:program_selections="Applicants are selected through a lottery process. Contact school for more details." t:phone=7732657232 t:fax=7732657258 t:website=http://www.alainlocke.org t:state=Illinois t:how_to_apply="Contact school" t:short_name="LOCKE A" t:school_id=400011 t:city=Chicago t:long_name="Alain Locke Charter School" t:primary_category=ES t:cps_school_profile="http://cps.edu/Schools/Pages/school.aspx?SchoolID=400011" t:deadline="Contact school" m:row_number.2i3t-vn5b=3
```

## Meta Commands

```ls
metric m:row_number.2i3t-vn5b p:long l:"Row Number"

entity e:2i3t-vn5b l:"Chicago Public Schools - School Admissions Information SY1617" t:attribution="Chicago Public Schools" t:url=https://data.cityofchicago.org/api/views/2i3t-vn5b

property e:2i3t-vn5b t:meta.view v:id=2i3t-vn5b v:category=Education v:attributionLink=http://cps.edu v:averageRating=0 v:name="Chicago Public Schools - School Admissions Information SY1617" v:attribution="Chicago Public Schools"

property e:2i3t-vn5b t:meta.view.license v:name="Public Domain"

property e:2i3t-vn5b t:meta.view.owner v:id=juii-ka42 v:profileImageUrlMedium=/api/users/juii-ka42/profile_images/THUMB v:profileImageUrlLarge=/api/users/juii-ka42/profile_images/LARGE v:screenName="Ted Canji" v:profileImageUrlSmall=/api/users/juii-ka42/profile_images/TINY v:displayName="Ted Canji"

property e:2i3t-vn5b t:meta.view.tableauthor v:id=juii-ka42 v:profileImageUrlMedium=/api/users/juii-ka42/profile_images/THUMB v:profileImageUrlLarge=/api/users/juii-ka42/profile_images/LARGE v:screenName="Ted Canji" v:profileImageUrlSmall=/api/users/juii-ka42/profile_images/TINY v:roleName=editor v:displayName="Ted Canji"
```

## Top Records

```ls
| :updated_at | school_id | short_name                | long_name                                         | school_type | primary_category | address                | city    | state    | zip   | phone      | fax        | cps_school_profile                                               | website                                            | program_type             | application_requirements                                                                                                                                                                                                                                                                                                          | program_selections                                                                                                                                                                                                                           | subprograms | how_to_apply                                       | deadline       | school_latitude | school_longitude | 
| =========== | ========= | ========================= | ================================================= | =========== | ================ | ====================== | ======= | ======== | ===== | ========== | ========== | ================================================================ | ================================================== | ======================== | ================================================================================================================================================================================================================================================================================================================================= | ============================================================================================================================================================================================================================================ | =========== | ================================================== | ============== | =============== | ================ | 
| 1479854289  | 400009    | GLOBAL CITIZENSHIP        | Academy for Global Citizenship Charter School     | Charter     | ES               | 4647 W 47TH ST         | Chicago | Illinois | 60632 | 7735821100 | 7735821101 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400009, null] | [http://www.agcchicago.org, null]                  | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.807579       | -87.740097       | 
| 1479854289  | 400010    | ACE TECH HS               | ACE Technical Charter School                      | Charter     | HS               | 5410 S STATE ST        | Chicago | Illinois | 60609 | 7735488705 | 7735488706 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400010, null] | [http://www.acetechnical.org, null]                | Charter                  | Not Applicable                                                                                                                                                                                                                                                                                                                    | If the school receives more applications than there are seats available, students are randomly selected through a computerized lottery. Priority is given to siblings of students enrolled in the campus.                                    |             | Contact school                                     | Contact school | 41.796122       | -87.625849       | 
| 1479854289  | 400011    | LOCKE A                   | Alain Locke Charter School                        | Charter     | ES               | 3141 W JACKSON BLVD    | Chicago | Illinois | 60612 | 7732657232 | 7732657258 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400011, null] | [http://www.alainlocke.org, null]                  | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.877248       | -87.705235       | 
| 1479854289  | 400013    | ASPIRA - EARLY COLLEGE HS | ASPIRA Charter School - Early College High School | Charter     | HS               | 3986 W BARRY AVE       | Chicago | Illinois | 60618 | 7732520970 | 7732673568 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400013, null] | [http://aspirail.org/domain/96, null]              | Charter                  | Not Applicable                                                                                                                                                                                                                                                                                                                    | If the school receives more applications than there are seats available, students are randomly selected through a computerized lottery. Priority is given to siblings of students enrolled in the campus.                                    |             | Contact school                                     | Contact school | 41.937298       | -87.727096       | 
| 1479854289  | 400017    | ASPIRA - HAUGAN           | ASPIRA Charter School - Haugan Middle School      | Charter     | MS               | 3729 W LELAND AVE      | Chicago | Illinois | 60625 | 7732520970 | 7732673568 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400017, null] | [http://www.haugan.aspirail.org, null]             | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.966406       | -87.721825       | 
| 1479854289  | 400021    | CATALYST - CIRCLE ROCK    | Catalyst Elementary Charter School - Circle Rock  | Charter     | ES               | 5608 W WASHINGTON BLVD | Chicago | Illinois | 60644 | 7739455025 | 7736262345 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400021, null] | [http://www.catalystschools.org/circle-rock, null] | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.882322       | -87.765322       | 
| 1479854289  | 400022    | CHICAGO ARTS HS           | Chicago High School for the Arts                  | Contract    | HS               | 2714 W AUGUSTA BLVD    | Chicago | Illinois | 60622 | 7735349710 | 7735349720 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400022, null] | [http://www.chiarts.org, null]                     | Fine and Performing Arts | Minimum percentile score of 24 in both reading and math on NWEA MAP.

IEP students: Minimum total percentile score of 48 in reading and math (e.g., 28 in reading and 20 in math).

Other nationally norm-referenced tests (e.g., ITBS, ISAT, Terra Nova) may be considered. No more than 10 unexcused absences during 7th grade. | Selections are based solely on auditions in five different areas (music, dance, theater, visual arts, and creative writing). Students may audition for NO MORE than two areas.

Students may not switch majors once accepted into a program. |             | Applications are online at: http://www.chiarts.org | Contact school | 41.899377       | -87.694945       | 
| 1479854289  | 400023    | CICS - AVALON/SOUTH SHORE | CICS - Avalon/South Shore                         | Charter     | ES               | 1501 E 83RD PL         | Chicago | Illinois | 60619 | 7737210858 | 7737310142 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400023, null] | [http://www.cicsavalon.org, null]                  | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.743179       | -87.587928       | 
| 1479854289  | 400024    | CICS - BASIL              | CICS - Basil                                      | Charter     | ES               | 1816 W GARFIELD BLVD   | Chicago | Illinois | 60609 | 7737789455 | 7737789456 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400024, null] | [http://meditatemotivategraduate.org, null]        | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.794043       | -87.670243       | 
| 1479854289  | 400025    | CICS - BUCKTOWN           | CICS - Bucktown                                   | Charter     | ES               | 2235 N HAMILTON AVE    | Chicago | Illinois | 60647 | 7736453321 | 7736453327 | [http://cps.edu/Schools/Pages/school.aspx?SchoolID=400025, null] | [http://www.cicsbucktown.org/, null]               | Charter School           | Not Applicable                                                                                                                                                                                                                                                                                                                    | Applicants are selected through a lottery process. Contact school for more details.                                                                                                                                                          |             | Contact school                                     | Contact school | 41.922415       | -87.681358       | 
```