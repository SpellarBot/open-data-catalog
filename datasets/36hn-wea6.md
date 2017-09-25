# DYCD after-school programs: OSY Out Of School Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-osy-out-of-school-youth-employment-programs-b0b82) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/36hn-wea6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 36hn-wea6 |
| Name | DYCD after-school programs: OSY Out Of School Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T20:39:32Z |
| Publication Date | 2017-09-14T19:39:34Z |

## Description

Facilities in New York City, by agency and site, that offer “Out-Of -School Youth Employment (OSY) Program” after-school  job and internship programs for young adults ages 16 to 21.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| No       | time           | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | program_type          | PROGRAM TYPE            | text      | text        |
| Yes      | series tag     | program               | PROGRAM                 | text      | text        |
| Yes      | series tag     | site_name             | SITE NAME               | text      | text        |
| Yes      | series tag     | number_and_street     | Number and Street       | text      | text        |
| Yes      | series tag     | postcode              | Postcode                | text      | number      |
| Yes      | series tag     | borough_community     | BOROUGH / COMMUNITY     | text      | text        |
| Yes      | series tag     | agency                | AGENCY                  | text      | text        |
| Yes      | series tag     | contact_number        | Contact Number          | text      | text        |
| Yes      | series tag     | grade_level_age_group | Grade Level / Age Group | text      | text        |
| No       |                | latitude              | Latitude                | number    | number      |
| No       |                | longitude             | Longitude               | number    | number      |
| Yes      | numeric metric | community_board       | Community Board         | number    | number      |
| Yes      | numeric metric | community_council     | Community Council       | number    | number      |
| Yes      | numeric metric | census_tract          | Census Tract            | number    | number      |
| Yes      | numeric metric | bin                   | BIN                     | number    | number      |
| Yes      | numeric metric | bbl                   | BBL                     | number    | number      |
| Yes      | series tag     | nta                   | NTA                     | text      | text        |
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
series e:36hn-wea6 d:2017-09-14T19:36:00.000Z t:site_name="Brooklyn Job Corps Academy" t:program_type="Jobs & Internships" t:agency="Arbor Employment and Training" t:borough_community=Brooklyn t:postcode=11205 t:nta=Bedford t:program="Out-of-School Youth Employment (OSY)" t:grade_level_age_group="16 to 21" t:number_and_street=Brooklyn t:contact_number=718.623.4031 m:bin=3049016 m:community_board=3 m:bbl=3017640001 m:community_council=33 m:census_tract=241

series e:36hn-wea6 d:2017-09-14T19:36:00.000Z t:site_name="Career Development Institute" t:program_type="Jobs & Internships" t:agency="Federation Employment & Guidance Services (FEGS)" t:borough_community=Bronx t:postcode=10455 t:nta="Mott Haven-Port Morris" t:program="Out-of-School Youth Employment (OSY)" t:grade_level_age_group="16 to 21" t:number_and_street=Bronx t:contact_number=718.742.3499 m:bin=2000506 m:community_board=1 m:bbl=2022910012 m:community_council=8 m:census_tract=43

series e:36hn-wea6 d:2017-09-14T19:36:00.000Z t:site_name="Catholic Charities Neighborhood Services" t:program_type="Jobs & Internships" t:agency="Catholic Charities Neighborhood Services" t:borough_community=Queens t:postcode=11102 t:nta="Old Astoria" t:program="Out-of-School Youth Employment (OSY)" t:grade_level_age_group="16 to 21" t:number_and_street=Queens t:contact_number="718.726.9790 ext.127" m:bin=4439576 m:community_board=1 m:bbl=4005420008 m:community_council=22 m:census_tract=69
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Community Council" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:36hn-wea6 l:"DYCD after-school programs: OSY Out Of School Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/36hn-wea6

property e:36hn-wea6 t:meta.view d:2017-09-25T07:27:58.373Z v:averageRating=0 v:name="DYCD after-school programs: OSY Out Of School Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)" v:id=36hn-wea6 v:category=Education

property e:36hn-wea6 t:meta.view.owner d:2017-09-25T07:27:58.373Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:36hn-wea6 t:meta.view.tableauthor d:2017-09-25T07:27:58.373Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_type       | program                              | site_name                                                      | number_and_street | postcode | borough_community | agency                                                        | contact_number        | grade_level_age_group | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                                  | 
| =========== | ================== | ==================================== | ============================================================== | ================= | ======== | ================= | ============================================================= | ===================== | ===================== | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ==================================== | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Bronx Community College                                        | Bronx             | 10453    | Bronx             | Henkels & McCoy, Inc.                                         | 917.856.2368          | 16 to 21              |           |            |                 |                   |              |         |            |                                      | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Brooklyn Job Corps Academy                                     | Brooklyn          | 11205    | Brooklyn          | Arbor Employment and Training                                 | 718.623.4031          | 16 to 21              | 40.691223 | -73.952765 | 3               | 33                | 241          | 3049016 | 3017640001 | Bedford                              | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Career Development Institute                                   | Bronx             | 10455    | Bronx             | Federation Employment & Guidance Services (FEGS)              | 718.742.3499          | 16 to 21              | 40.814478 | -73.918076 | 1               | 8                 | 43           | 2000506 | 2022910012 | Mott Haven-Port Morris               | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Catholic Charities Neighborhood Services                       | Queens            | 11102    | Queens            | Catholic Charities Neighborhood Services                      | 718.726.9790 ext.127  | 16 to 21              | 40.771582 | -73.92375  | 1               | 22                | 69           | 4439576 | 4005420008 | Old Astoria                          | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Chinatown Manpower Project, Inc.                               | New York          | 10013    | New York          | Chinatown Manpower Project, Inc.                              | 212.571.1690          | 16 to 21              | 40.716092 | -73.999203 | 3               | 1                 | 29           | 1066494 | 1002000001 | Chinatown                            | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Church Avenue Merchants Block Association, Inc.                | Brooklyn          | 11226    | Brooklyn          | Church Avenue Merchant Block Association                      | 718.462.4244          | 16 to 21              | 40.650424 | -73.958175 | 14              | 40                | 79602        | 3116881 | 3050890071 | Prospect Lefferts Gardens-Wingate    | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Henkels & McCoy, Inc.                                          | Queens            | 11101    | Queens            | CUNY Catch at LaGuardia Community College                     | 917.856.2368          | 16 to 21              | 40.745216 | -73.937602 | 2               | 26                | 1            | 4003516 | 4002730001 | Hunters Point-Sunnyside-West Maspeth | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Henry Street Settlement Workforce Development Center           | New York          | 10002    | New York          | Henry Street Settlement                                       | 212.478.5400 ext. 210 | 16 to 21              | 40.718943 | -73.988012 | 3               | 1                 | 18           | 1087565 | 1004100064 | Chinatown                            | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | International Sheet Metal Workers Local Union 28 (intake site) | New York          | 10016    | New York          | International Sheet Metal Workers Local Union 28              | 212.732.7897          | 16 to 21              | 40.745492 | -73.982515 | 5               | 2                 | 74           | 1080788 | 1008610044 | Midtown-Midtown South                | 
| 1505417760  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Medgar Evers College                                           | Brooklyn          | 11225    | Brooklyn          | Research Foundation of CUNY on behalf of Medgar Evers College | 718.270.6474          | 16 to 21              | 40.667253 | -73.952195 | 9               | 35                | 321          | 3337869 | 3012890025 | Crown Heights South                  | 
```