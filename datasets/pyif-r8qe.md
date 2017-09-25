# DYCD after-school programs: Beacon Satellite At NYCHA Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-beacon-satellite-at-nycha-programs-e7307) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pyif-r8qe) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pyif-r8qe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pyif-r8qe/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pyif-r8qe |
| Name | DYCD after-school programs: Beacon Satellite At NYCHA Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, nycha, new york city housing authority, beacon satellite, beacon, lifelong learning |
| Created | 2011-09-01T16:20:02Z |
| Publication Date | 2017-09-16T14:47:22Z |

## Description

Facilities in New York City, by agency and site, that offer “Beacon Satellite at NYCHA Programs” after-school programs. Update Schedule: Annually

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
series e:pyif-r8qe d:2017-09-16T14:47:01.000Z t:site_name="NYCHA BAY VIEW HOUSES" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:agency="Sesame Flyers  @Bayview Community Center" t:borough_community=Brooklyn t:number_and_street_address="5985 Shore Parkway" t:postcode=11236 t:nta=Canarsie t:program="Beacon Satellite" t:grade_level_age_group="6 and up" t:contact_number="(718) 968-9621" m:bin=3331443 m:community_board=18 m:bbl=3083290225 m:community_council=46 m:census_tract=1034

series e:pyif-r8qe d:2017-09-16T14:47:01.000Z t:site_name="NYCHA BETANCES HOUSES" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:agency="Aspira of New York @Dr. Ramon E. Betances VI Community Center" t:borough_community=Bronx t:number_and_street_address="465 St. Ann's Avenue" t:postcode=10455 t:nta="Mott Haven-Port Morris" t:program="Beacon Satellite" t:grade_level_age_group="6 and up" t:contact_number="(718) 585-5040" m:bin=2093910 m:community_board=1 m:bbl=2022720119 m:community_council=8 m:census_tract=43

series e:pyif-r8qe d:2017-09-16T14:47:01.000Z t:site_name="NYCHA BRONX RIVER HOUSES" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:agency="Phipps Community Development Corporation @Bronx River Community Center" t:borough_community=Bronx t:number_and_street_address="1619 East 174th St" t:postcode=10472 t:nta="West Farms-Bronx River" t:program="Beacon Satellite" t:grade_level_age_group="6 and up" t:contact_number="(718) 589-0555" m:bin=2092909 m:community_board=9 m:bbl=2038860002 m:community_council=18 m:census_tract=62
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Council District" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:pyif-r8qe l:"DYCD after-school programs: Beacon Satellite At NYCHA Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/pyif-r8qe

property e:pyif-r8qe t:meta.view d:2017-09-25T07:30:18.124Z v:averageRating=0 v:name="DYCD after-school programs: Beacon Satellite At NYCHA Programs" v:attribution="Department of Youth and Community Development (DYCD)" v:id=pyif-r8qe v:category=Education

property e:pyif-r8qe t:meta.view.owner d:2017-09-25T07:30:18.124Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:pyif-r8qe t:meta.view.tableauthor d:2017-09-25T07:30:18.124Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_type                               | program          | site_name                             | borough_community | agency                                                                 | contact_number | grade_level_age_group | number_and_street_address | postcode | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                                              | 
| =========== | ========================================== | ================ | ===================================== | ================= | ====================================================================== | ============== | ===================== | ========================= | ======== | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ================================================ | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA BAY VIEW HOUSES                 | Brooklyn          | Sesame Flyers @Bayview Community Center                                | (718) 968-9621 | 6 and up              | 5985 Shore Parkway        | 11236    | 40.632639 | -73.883788 | 18              | 46                | 1034         | 3331443 | 3083290225 | Canarsie                                         | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA BETANCES HOUSES                 | Bronx             | Aspira of New York @Dr. Ramon E. Betances VI Community Center          | (718) 585-5040 | 6 and up              | 465 St. Ann's Avenue      | 10455    | 40.812488 | -73.914357 | 1               | 8                 | 43           | 2093910 | 2022720119 | Mott Haven-Port Morris                           | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA BRONX RIVER HOUSES              | Bronx             | Phipps Community Development Corporation @Bronx River Community Center | (718) 589-0555 | 6 and up              | 1619 East 174th St        | 10472    | 40.83395  | -73.876147 | 9               | 18                | 62           | 2092909 | 2038860002 | West Farms-Bronx River                           | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA BUSHWICK/HYLAN HOUSES           | Brooklyn          | YMCA-Eastern District @ Bushwick/Hylan Community Center                | (718) 453-8116 | 6 and up              | 50 Humboldt Street        | 11206    | 40.703179 | -73.940761 | 1               | 34                | 489          | 3338434 | 3031290001 | Bushwick South                                   | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA CONEY ISLAND I SURFSIDE GARDENS | Brooklyn          | Heartshare @Coney Island Surfside Community Center                     | (718) 449-2897 | 6 and up              | 2947 West 28th Street     | 11224    | 40.574453 | -73.994089 | 13              | 47                | 342          | 3385303 | 3070530014 | Seagate-Coney Island                             | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA CYPRESS HILLS HOUSES            | Brooklyn          | Police Athletic League @Cypress Hills Community Center                 | (718) 277-6641 | 6 and up              | 475 Fountain Avenue       | 11208    | 40.668288 | -73.873005 | 5               | 42                | 1210         | 3337041 | 3042920061 | East New York                                    | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA DYCKMAN HOUSES                  | Manhattan         | Alianza Dominicana, Inc. @Dyckman Community Center                     | (212) 567-8782 | 6 and up              | 3782 Tenth Avenue         | 10034    | 40.861366 | -73.921207 | 12              | 10                | 299          | 1080033 | 1022160001 | Marble Hill-Inwood                               | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA EASTCHESTER GARDENS             | Bronx             | Mosholu Montefiore @Eastchester Gardens Community Center               | (718) 231-3894 | 6 and up              | 3016 Yates Avenue         | 10469    | 40.870125 | -73.854588 | 11              | 12                | 348          | 2093503 | 2045810001 | Allerton-Pelham Gardens                          | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA EDENWALD HOUSES                 | Bronx             | Mosholu Montefiore @Edenwald Community Center                          | (718) 652-0246 | 6 and up              | 1150 East 229th Street    | 10466    | 40.886175 | -73.845107 | 12              | 12                | 458          | 2094178 | 2049050001 | Eastchester-Edenwald-Baychester                  | 
| 1505573221  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA FARRAGUT HOUSES                 | Brooklyn          | Goodwill Industries @ David G. Farragut Community Center               | (718) 852-6347 | 6 and up              | 228 York Street           | 11201    | 40.701304 | -73.981762 | 2               | 35                | 23           | 3325909 | 3000710001 | DUMBO-Vinegar Hill-Downtown Brooklyn-Boerum Hill | 
```