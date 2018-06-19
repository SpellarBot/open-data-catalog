# DYCD after-school programs: Reading And Writing Literacy Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-reading-and-writing-literacy-programs-238fc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w9cy-nnma) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w9cy-nnma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w9cy-nnma/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w9cy-nnma |
| Name | DYCD after-school programs: Reading And Writing Literacy Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ... |
| Created | 2011-09-02T18:40:22Z |
| Publication Date | 2017-09-15T20:49:57Z |

## Description

Facilities in New York City, by agency and site, that offer after-school programs and resources for adult and adolescent literacy, family literacy, and English as a Second Language (ESOL) programs.
Update Schedule: Annually

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
| Yes      | numeric metric | community_council         | Community Council         | number    | number      |
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
series e:w9cy-nnma d:2017-09-15T20:49:40.000Z t:site_name="African Services Committee, Inc." t:program_type="Reading & Writing" t:agency="African Services Committee, Inc." t:borough_community="New York" t:number_and_street_address="429 West 127 Street" t:postcode=10027 t:nta=Manhattanville t:program="Adult Literacy" t:grade_level_age_group="At least 16 Years Old or Older" t:contact_number=212.222.3882 m:bin=1084104 m:community_board=9 m:bbl=1019670060 m:community_council=7 m:census_tract=21303

series e:w9cy-nnma d:2017-09-15T20:49:40.000Z t:site_name="Agudath Israel of America Community Services, Inc." t:program_type="Reading & Writing" t:agency="Agudath Israel of America Community Services, Inc." t:borough_community="New York" t:number_and_street_address="225 Broadway, 2nd Floor" t:postcode=10007 t:nta="SoHo-TriBeCa-Civic Center-Little Italy" t:program="Adult Literacy" t:grade_level_age_group="At least 16 Years Old or Older" t:contact_number=212.809.5935 m:bin=1001241 m:community_board=1 m:bbl=1000880018 m:community_council=1 m:census_tract=21

series e:w9cy-nnma d:2017-09-15T20:49:40.000Z t:site_name="Beacon Family Center at IS 8" t:program_type="Reading & Writing" t:agency="SQPA-NY Southern Queens Park Association NY" t:borough_community=Queens t:number_and_street_address="108-35 167th Street" t:postcode=11432 t:nta="South Jamaica" t:program="Adult Literacy" t:grade_level_age_group="At least 16 Years Old or Older" t:contact_number=718.276.4630 m:bin=4216655 m:community_board=12 m:bbl=4101780001 m:community_council=27 m:census_tract=258
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Community Council" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:w9cy-nnma l:"DYCD after-school programs: Reading And Writing Literacy Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/w9cy-nnma

property e:w9cy-nnma t:meta.view d:2017-09-25T07:29:50.678Z v:averageRating=0 v:name="DYCD after-school programs: Reading And Writing Literacy Programs" v:attribution="Department of Youth and Community Development (DYCD)" v:id=w9cy-nnma v:category=Education

property e:w9cy-nnma t:meta.view.owner d:2017-09-25T07:29:50.678Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:w9cy-nnma t:meta.view.tableauthor d:2017-09-25T07:29:50.678Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_type      | program        | site_name                                          | borough_community | agency                                             | contact_number | grade_level_age_group          | number_and_street_address     | postcode | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                                    | 
| =========== | ================= | ============== | ================================================== | ================= | ================================================== | ============== | ============================== | ============================= | ======== | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ====================================== | 
| 1505508580  | Reading & Writing | Adult Literacy | African Services Committee, Inc.                   | New York          | African Services Committee, Inc.                   | 212.222.3882   | At least 16 Years Old or Older | 429 West 127 Street           | 10027    | 40.813002 | -73.953849 | 9               | 7                 | 21303        | 1084104 | 1019670060 | Manhattanville                         | 
| 1505508580  | Reading & Writing | Adult Literacy | Agudath Israel of America Community Services, Inc. | New York          | Agudath Israel of America Community Services, Inc. | 212.809.5935   | At least 16 Years Old or Older | 225 Broadway, 2nd Floor       | 10007    | 40.71187  | -74.008217 | 1               | 1                 | 21           | 1001241 | 1000880018 | SoHo-TriBeCa-Civic Center-Little Italy | 
| 1505508580  | Reading & Writing | Adult Literacy | Beacon Family Center at IS 8                       | Queens            | SQPA-NY Southern Queens Park Association NY        | 718.276.4630   | At least 16 Years Old or Older | 108-35 167th Street           | 11432    | 40.69719  | -73.787192 | 12              | 27                | 258          | 4216655 | 4101780001 | South Jamaica                          | 
| 1505508580  | Reading & Writing | Adult Literacy | Brooklyn Chinese-American Association              | Brooklyn          | Brooklyn Chinese-American Association              | 718.438.0008   | At least 16 Years Old or Older | 5006 8th Avenue               | 11220    | 40.641014 | -74.003834 | 7               | 38                | 108          | 3013419 | 3007940041 | Sunset Park East                       | 
| 1505508580  | Reading & Writing | Adult Literacy | Brooklyn Chinese-American Association              | Brooklyn          | Brooklyn Chinese-American Association              | 718.438.0008   | At least 16 Years Old or Older | 6809 20th Avenue              | 11204    | 40.61468  | -73.987765 | 11              | 47                | 258          | 3135071 | 3055790007 | Bensonhurst West                       | 
| 1505508580  | Reading & Writing | Adult Literacy | CAB Community Center                               | Bronx             | Citizens Advice Bureau                             | 718.508.3132   | At least 16 Years Old or Older | 1130 Grand Concourse          | 10456    | 40.832331 | -73.91959  | 4               | 16                | 18102        | 2002833 | 2024620042 | East Concourse-Concourse Village       | 
| 1505508580  | Reading & Writing | Adult Literacy | CAB Immigration Office                             | Bronx             | Citizens Advice Bureau                             | 718.508.3132   | At least 16 Years Old or Older | 2070 Grand Concourse, Suite 1 | 10457    | 40.853222 | -73.902947 | 5               | 15                | 23502        | 2013631 | 2031560009 | Mount Hope                             | 
| 1505508580  | Reading & Writing | Adult Literacy | CAMBA                                              | Brooklyn          | CAMBA                                              | 718.940.1737   | At least 16 Years Old or Older | 885 Flatbush Avenue           | 11226    | 40.650229 | -73.958658 | 14              | 40                | 794          | 3117223 | 3051030028 | Erasmus                                | 
| 1505508580  | Reading & Writing | Adult Literacy | Catholic Charities Neighborhood Services           | Queens            | Catholic Charities Neighborhood Services           | 718.726.9790   | At least 16 Years Old or Older | 23-40 Astoria Boulevard       | 11102    | 40.771582 | -73.92375  | 1               | 22                | 69           | 4439576 | 4005420008 | Old Astoria                            | 
| 1505508580  | Reading & Writing | Adult Literacy | Chinatown Manpower Project, Inc                    | New York          | Chinatown Manpower Project, Inc                    | 212.571.1691   | At least 16 Years Old or Older | 70 Mulberry Street            | 10013    | 40.716092 | -73.999203 | 3               | 1                 | 29           | 1066494 | 1002000001 | Chinatown                              | 
```