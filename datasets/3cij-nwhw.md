# State University of New York (SUNY) Campus Locations with Websites, Enrollment and Select Program Offerings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-of-new-york-suny-campus-locations-with-websites-enrollment-and-select-pro) |
| Metadata | [Link](https://data.ny.gov/api/views/3cij-nwhw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/3cij-nwhw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/3cij-nwhw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 3cij-nwhw |
| Name | State University of New York (SUNY) Campus Locations with Websites, Enrollment and Select Program Offerings |
| Attribution | SUNY System Administration |
| Category | Education |
| Tags | suny, website, campus, higher education, instructional programs |
| Created | 2013-04-02T17:42:14Z |
| Publication Date | 2016-09-09T20:51:11Z |

## Description

Campuses which comprise the State University of New York (SUNY) System. Highlights information on Undergraduate and Graduate enrollment as well as some program area offerings.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                     | Data Type | Render Type |
| ======== | ============== | =========================== | ======================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at               | meta_data | meta_data   |
| No       |                | long1                       | Longitude1               | number    | number      |
| No       |                | lat1                        | Latitude1                | number    | number      |
| Yes      | series tag     | college_of_institution_type | Campus Name              | text      | text        |
| Yes      | series tag     | campus                      | Long Campus Name         | text      | text        |
| No       |                | address                     | Address 1                | text      | text        |
| No       |                | address_2                   | Address 2                | text      | text        |
| Yes      | series tag     | city                        | City                     | text      | text        |
| Yes      | series tag     | state                       | State                    | text      | text        |
| Yes      | series tag     | zip                         | Zip                      | text      | text        |
| Yes      | series tag     | county                      | County                   | text      | text        |
| Yes      | series tag     | institution_level           | Institution Level        | text      | text        |
| Yes      | series tag     | institution_type            | Institution Type         | text      | text        |
| Yes      | series tag     | enrollment_as_of            | Enrollment As Of         | text      | text        |
| Yes      | numeric metric | undergrad_enrollment        | Undergraduate Enrollment | number    | number      |
| Yes      | numeric metric | graduate_enrollment         | Graduate Enrollment      | number    | number      |
| Yes      | series tag     | program_1                   | Program 1                | text      | text        |
| Yes      | series tag     | program_2                   | Program 2                | text      | text        |
| Yes      | series tag     | program_3                   | Program 3                | text      | text        |
| Yes      | series tag     | program_4                   | Program 4                | text      | text        |
| Yes      | series tag     | program_5                   | Program 5                | text      | text        |
| Yes      | series tag     | campus_website              | Campus Website           | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = long1,lat1,address,address_2
```

## Data Commands

```ls
series e:3cij-nwhw d:2016-09-09T19:50:10.000Z t:zip=12804 t:state=NY t:city=QUEENSBURY t:program_5="Media Arts" t:program_4="Criminal Justice" t:enrollment_as_of="Fall 2015" t:program_3=Nursing t:institution_level=2-year t:college_of_institution_type=Adirondack t:county=Warren t:institution_type="Community Colleges" t:campus_website=http://www.sunyacc.edu t:program_2="Business Administration" t:program_1="Liberal Arts And Sciences" t:campus="ADIRONDACK COMMUNITY COLLEGE" m:undergrad_enrollment=3993 m:graduate_enrollment=0

series e:3cij-nwhw d:2016-09-09T19:50:10.000Z t:zip=13902 t:state=NY t:city=BINGHAMTON t:program_5="Human Services" t:program_4="Criminal Justice" t:enrollment_as_of="Fall 2015" t:program_3=Nursing t:institution_level=2-year t:college_of_institution_type=Broome t:county=Broome t:institution_type="Community Colleges" t:campus_website=http://www.sunybroome.edu/ t:program_2="Business Administration" t:program_1="Liberal Arts And Sciences" t:campus="BROOME COMMUNITY COLLEGE" m:undergrad_enrollment=5926 m:graduate_enrollment=0

series e:3cij-nwhw d:2016-09-09T19:50:10.000Z t:zip=13021 t:state=NY t:city=AUBURN t:program_5="Studio Art & Design" t:program_4=Nursing t:enrollment_as_of="Fall 2015" t:program_3="Criminal Justice" t:institution_level=2-year t:college_of_institution_type="Cayuga County" t:county=Cayuga t:institution_type="Community Colleges" t:campus_website=http://www.cayuga-cc.edu/ t:program_2="Business Administration" t:program_1="Liberal Arts And Sciences" t:campus="CAYUGA COUNTY COMMUNITY COLLEGE" m:undergrad_enrollment=4184 m:graduate_enrollment=0
```

## Meta Commands

```ls
metric m:undergrad_enrollment p:integer l:"Undergraduate Enrollment" t:dataTypeName=number

metric m:graduate_enrollment p:integer l:"Graduate Enrollment" t:dataTypeName=number

entity e:3cij-nwhw l:"State University of New York (SUNY) Campus Locations with Websites, Enrollment and Select Program Offerings" t:attribution="SUNY System Administration" t:url=https://data.ny.gov/api/views/3cij-nwhw

property e:3cij-nwhw t:meta.view v:id=3cij-nwhw v:category=Education v:averageRating=0 v:name="State University of New York (SUNY) Campus Locations with Websites, Enrollment and Select Program Offerings" v:attribution="SUNY System Administration"

property e:3cij-nwhw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:3cij-nwhw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:3cij-nwhw t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | long1       | lat1       | college_of_institution_type | campus                             | address              | address_2   | city         | state | zip   | county   | institution_level | institution_type   | enrollment_as_of | undergrad_enrollment | graduate_enrollment | program_1                        | program_2               | program_3                              | program_4               | program_5                  | campus_website                      | 
| =========== | =========== | ========== | =========================== | ================================== | ==================== | =========== | ============ | ===== | ===== | ======== | ================= | ================== | ================ | ==================== | =================== | ================================ | ======================= | ====================================== | ======================= | ========================== | =================================== | 
| 1473450610  | -73.656311  | 43.3507652 | Adirondack                  | ADIRONDACK COMMUNITY COLLEGE       | 640 BAY RD           |             | QUEENSBURY   | NY    | 12804 | Warren   | 2-year            | Community Colleges | Fall 2015        | 3993                 | 0                   | Liberal Arts And Sciences        | Business Administration | Nursing                                | Criminal Justice        | Media Arts                 | [http://www.sunyacc.edu, null]      | 
| 1473450610  | -75.8884735 | 42.1678047 | Broome                      | BROOME COMMUNITY COLLEGE           | UPPER FRONT ST       | PO BOX 1017 | BINGHAMTON   | NY    | 13902 | Broome   | 2-year            | Community Colleges | Fall 2015        | 5926                 | 0                   | Liberal Arts And Sciences        | Business Administration | Nursing                                | Criminal Justice        | Human Services             | [http://www.sunybroome.edu/, null]  | 
| 1473450610  | -76.5238113 | 42.9488068 | Cayuga County               | CAYUGA COUNTY COMMUNITY COLLEGE    | 197 FRANKLIN ST      |             | AUBURN       | NY    | 13021 | Cayuga   | 2-year            | Community Colleges | Fall 2015        | 4184                 | 0                   | Liberal Arts And Sciences        | Business Administration | Criminal Justice                       | Nursing                 | Studio Art & Design        | [http://www.cayuga-cc.edu/, null]   | 
| 1473450610  | -73.4672546 | 44.6937408 | Clinton                     | CLINTON COMMUNITY COLLEGE          | 136 CLINTON POINT DR |             | PLATTSBURGH  | NY    | 12901 | Clinton  | 2-year            | Community Colleges | Fall 2015        | 1862                 | 0                   | Liberal Arts And Sciences        | Criminal Justice        | Nursing                                | Business Administration | Human Services             | [http://www.clinton.edu/, null]     | 
| 1473450610  | -73.818367  | 42.2176323 | Columbia-Greene             | COLUMBIA-GREENE COMMUNITY COLLEGE  | 4400 ROUTE 23        |             | HUDSON       | NY    | 12534 | Columbia | 2-year            | Community Colleges | Fall 2015        | 1781                 | 0                   | Liberal Arts And Sciences        | Criminal Justice        | Nursing                                | Business Administration | Fine Arts                  | [http://www.sunycgcc.edu, null]     | 
| 1473450610  | -77.0738907 | 42.1163292 | Corning                     | CORNING COMMUNITY COLLEGE          | 1 ACADEMIC DR        |             | CORNING      | NY    | 14830 | Steuben  | 2-year            | Community Colleges | Fall 2015        | 3972                 | 0                   | Liberal Arts And Sciences        | Nursing                 | Business Administration                | Human Services          | Criminal Justice           | [http://www.corning-cc.edu, null]   | 
| 1473450610  | -73.9061966 | 41.7216949 | Dutchess                    | DUTCHESS COMMUNITY COLLEGE         | 53 PENDELL RD        |             | POUGHKEEPSIE | NY    | 12601 | Dutchess | 2-year            | Community Colleges | Fall 2015        | 9546                 | 0                   | Liberal Arts And Sciences        | Nursing                 | Business Administration                | Criminal Justice        | Human Services             | [http://www.sunydutchess.edu, null] | 
| 1473450610  | -78.8731613 | 42.8819122 | Erie                        | ERIE COMMUNITY COLLEGE-CITY CAMPUS | 121 ELLICOTT ST      |             | BUFFALO      | NY    | 14203 | Erie     | 2-year            | Community Colleges | Fall 2015        | 12022                | 0                   | Liberal Arts And Sciences        | Business Administration | Criminal Justice                       | Nursing                 | Automotive Technology      | [http://www.ecc.edu, null]          | 
| 1473450610  | -73.9851379 | 40.758503  | Fashion Institute           | FASHION INSTITUTE OF TECHNOLOGY    | SEVENTH AVE AT 27 ST |             | NEW YORK     | NY    | 10001 | New York | 4-year            | Community Colleges | Fall 2015        | 9386                 | 179                 | Fashion Merchandising Management | Fashion Design          | Advertising & Marketing Communications | Illustration            | Interior Design            | [http://www.fitnyc.edu, null]       | 
| 1473450610  | -77.2724304 | 42.8767853 | Finger Lakes                | FINGER LAKES COMMUNITY COLLEGE     | 3325 MARVIN SANDS DR |             | CANANDAIGUA  | NY    | 14424 | Ontario  | 2-year            | Community Colleges | Fall 2015        | 6755                 | 0                   | Liberal Arts And Sciences        | Criminal Justice        | Business Administration                | Human Services          | Music Recording Technology | [http://www.flcc.edu, null]         | 
```