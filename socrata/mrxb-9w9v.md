# DYCD after-school programs: NDA Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-nda-youth-employment-programs-791a7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mrxb-9w9v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mrxb-9w9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mrxb-9w9v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mrxb-9w9v |
| Name | DYCD after-school programs: NDA Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T21:00:43Z |
| Publication Date | 2017-09-16T16:06:26Z |

## Description

Facilities in New York City, by agency and site, that offer “NDA Neighborhood Development Area Youth Employment  Program” after-school  job and internship programs for children and young adults ages 14 to 21 in Middle School, in High School, or in all grades.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | program_type              | PROGRAM TYPE              | text      | text        |
| Yes      | series tag     | program                   | PROGRAM                   | text      | text        |
| Yes      | series tag     | site_name                 | SITE NAME                 | text      | text        |
| Yes      | series tag     | borough_community         | BOROUGH / COMMUNITY       | text      | text        |
| Yes      | series tag     | agency                    | AGENCY                    | text      | text        |
| Yes      | series tag     | contact_number            | Contact Number            | text      | text        |
| Yes      | series tag     | grade_level_age_group     | Grade Level / Age Group   | text      | text        |
| Yes      | series tag     | number_and_street_address | Number and Street Address | text      | text        |
| Yes      | series tag     | postcode                  | Postcode                  | text      | number      |
| No       |                | latitude                  | Latitude                  | number    | number      |
| No       |                | longitude                 | Longitude                 | number    | number      |
| Yes      | numeric metric | community_board           | Community Board           | number    | number      |
| Yes      | numeric metric | community_council         | Council District          | number    | number      |
| Yes      | numeric metric | census_tract              | Census Tract              | number    | number      |
| Yes      | numeric metric | bin                       | BIN                       | number    | number      |
| Yes      | numeric metric | bbl                       | BBL                       | number    | number      |
| Yes      | series tag     | nta                       | NTA                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:mrxb-9w9v d:2017-09-16T16:05:52.000Z t:site_name="Afrikan Poetry Theatre" t:program_type="Youth Employment, NDA Youth Employment" t:agency="Afrikan Poetry Theatre" t:borough_community=Queens t:number_and_street_address="176-03 Jamaica Avenue" t:postcode=11432 t:nta=Jamaica t:program="Youth Employment" t:grade_level_age_group=MS/HS t:contact_number=718.523.3312 m:bin=4209975 m:community_board=12 m:bbl=4098120008 m:community_council=27 m:census_tract=468

series e:mrxb-9w9v d:2017-09-16T16:05:52.000Z t:site_name="Alianza Dominicana, Inc. Manhattan" t:program_type="Jobs & Internships, Youth Employment" t:agency="Alianza Dominicana, Inc." t:borough_community=Manhattan t:number_and_street_address="2410 Amsterdam Avenue , 4th Fl" t:postcode=10033 t:nta="Washington Heights South" t:program="Summer Youth Employment" t:grade_level_age_group="14 to 21" t:contact_number=212-740-1960 m:bin=1063604 m:community_board=12 m:bbl=1021520048 m:community_council=10 m:census_tract=261

series e:mrxb-9w9v d:2017-09-16T16:05:52.000Z t:site_name="Alianza Mosaic Beacon" t:program_type="Jobs & Internships, Youth Employment" t:agency="Alianza Dominicana, Inc." t:borough_community=Bronx t:number_and_street_address="1257 Ogden Avenue" t:postcode=10452 t:nta=Highbridge t:program="Summer Youth Employment" t:grade_level_age_group="14 to 21" t:contact_number=212-740-1960 m:bin=2003519 m:community_board=4 m:bbl=2025290081 m:community_council=16 m:census_tract=201
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Council District" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:mrxb-9w9v l:"DYCD after-school programs: NDA Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/mrxb-9w9v

property e:mrxb-9w9v t:meta.view d:2017-09-25T07:28:35.458Z v:averageRating=0 v:name="DYCD after-school programs: NDA Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)" v:id=mrxb-9w9v v:category=Education

property e:mrxb-9w9v t:meta.view.owner d:2017-09-25T07:28:35.458Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:mrxb-9w9v t:meta.view.tableauthor d:2017-09-25T07:28:35.458Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_type                           | program                 | site_name                                        | borough_community | agency                                     | contact_number | grade_level_age_group | number_and_street_address           | postcode | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                               | 
| =========== | ====================================== | ======================= | ================================================ | ================= | ========================================== | ============== | ===================== | =================================== | ======== | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ================================= | 
| 1505577952  | Youth Employment, NDA Youth Employment | Youth Employment        | Afrikan Poetry Theatre                           | Queens            | Afrikan Poetry Theatre                     | 718.523.3312   | MS/HS                 | 176-03 Jamaica Avenue               | 11432    | 40.707941 | -73.784233 | 12              | 27                | 468          | 4209975 | 4098120008 | Jamaica                           | 
| 1505577952  | Jobs & Internships, Youth Employment   | Summer Youth Employment | Alianza Dominicana, Inc. Manhattan               | Manhattan         | Alianza Dominicana, Inc.                   | 212-740-1960   | 14 to 21              | 2410 Amsterdam Avenue , 4th Fl      | 10033    | 40.847177 | -73.93159  | 12              | 10                | 261          | 1063604 | 1021520048 | Washington Heights South          | 
| 1505577952  | Jobs & Internships, Youth Employment   | Summer Youth Employment | Alianza Mosaic Beacon                            | Bronx             | Alianza Dominicana, Inc.                   | 212-740-1960   | 14 to 21              | 1257 Ogden Avenue                   | 10452    | 40.839378 | -73.925714 | 4               | 16                | 201          | 2003519 | 2025290081 | Highbridge                        | 
| 1505577952  | Jobs & Internships, Youth Employment   | Summer Youth Employment | All City Leadership School                       | Brooklyn          | Ridgewood Bushwick Senior Citizens Council | 718-381-9653   | 14 to 21              | 1474 Gates Avenue                   | 11237    | 40.697788 | -73.913906 | 4               | 37                | 433          | 3387654 | 3033440016 | Bushwick North                    | 
| 1505577952  | Jobs & Internships, Youth Employment   | Summer Youth Employment | Asociaciones Dominicanas, Inc - Vulnerable Youth | Brooklyn          | Asociaciones Dominicanas, Inc.             | 718-599-2386   | 14 to 21              | 202 Union Avenue , 2nd flr, ste L&M | 11211    | 40.706403 | -73.950356 | 1               | 34                | 511          | 3325853 | 3030580100 | East Williamsburg                 | 
| 1505577952  | Youth Employment, NDA Youth Employment | Youth Employment        | BCA Education Center                             | Brooklyn          | Brooklyn Chinese American Association      | 718.438.9312   | MS/HS                 | 5000 8th Avenue                     | 11220    | 40.641036 | -74.003809 | 7               | 38                | 108          | 3013418 | 3007940039 | Sunset Park East                  | 
| 1505577952  | Jobs & Internships, Youth Employment   | Summer Youth Employment | Bnos Menachem School                             | Brooklyn          | Henry Street Settlement, Inc. - Brooklyn   | 718-493-1100   | 14 to 21              | 739 East New York Avenue            | 11203    | 40.662347 | -73.938285 | 9               | 41                | 87401        | 3038483 | 3014280047 | Prospect Lefferts Gardens-Wingate | 
| 1505577952  | Youth Employment, NDA Youth Employment | Youth Employment        | Bnos Yakov Educational Center                    | Brooklyn          | Bnos Yakov Educational Center              | 718.963.1212   | MS/HS                 | 62 Harrison Avenue                  | 11211    | 40.704892 | -73.952445 | 1               | 33                | 529          | 3060902 | 3022200038 | Williamsburg                      | 
| 1505577952  | Youth Employment, NDA Youth Employment | Youth Employment        | Boys & Girls Harbor, Inc                         | New York          | Boys & Girls Harbor, Inc                   | 212.427.2244   |                       | 1 East 104th Street                 | 10029    | 40.792888 | -73.951826 | 11              | 8                 | 168          | 1051499 | 1016100001 | East Harlem South                 | 
| 1505577952  | Youth Employment, NDA Youth Employment | Youth Employment        | Bronx Community Resource Center                  | Bronx             | Covenant House/Under 21                    | 718.294. 7182  | HS                    | 81-83C Featherbed Lane              | 10452    | 40.846306 | -73.917755 | 5               | 14                | 21502        | 2008809 | 2028760037 | University Heights-Morris Heights | 
```