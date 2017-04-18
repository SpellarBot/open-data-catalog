# Street-Use Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-use-permits-7b50a) |
| Metadata | [Link](https://data.sfgov.org/api/views/b6tj-gt35) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/b6tj-gt35/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/b6tj-gt35/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | b6tj-gt35 |
| Name | Street-Use Permits |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | permits, tables, chairs, mobile, food, truck, display, surface, mounted, excavation, temporary, occupancy, row, banner, bicycle |
| Created | 2012-09-24T23:30:54Z |
| Publication Date | 2015-07-17T15:43:31Z |

## Description

Active Street use permits issued by DPW

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | permit_number     | permit_number     | text          | text          |
| Yes      | series tag     | streetname        | streetname        | text          | text          |
| Yes      | series tag     | cross_street_1    | Cross Street 1    | text          | text          |
| Yes      | series tag     | cross_street_2    | Cross Street 2    | text          | text          |
| Yes      | series tag     | permit_type       | Permit Type       | text          | text          |
| Yes      | series tag     | agent             | Agent             | text          | text          |
| Yes      | series tag     | agentphone        | AgentPhone        | text          | text          |
| Yes      | series tag     | permit_purpose    | Permit Purpose    | text          | text          |
| Yes      | time           | approved_date     | Approved Date     | calendar_date | calendar_date |
| Yes      | series tag     | status            | Status            | text          | text          |
| Yes      | numeric metric | cnn               | cnn               | number        | number        |
| Yes      | series tag     | permit_zipcode    | permit_zipcode    | text          | number        |
| No       |                | permit_start_date | permit_start_date | calendar_date | calendar_date |
| No       |                | permit_end_date   | permit_end_date   | calendar_date | calendar_date |
| No       |                | permit_address    | permit_address    | text          | text          |
| Yes      | series tag     | contact           | 24/7 Contact      | text          | text          |
| Yes      | series tag     | inspector         | Inspector         | text          | text          |
| Yes      | series tag     | curbrampwork      | CurbRampWork      | checkbox      | checkbox      |
| No       |                | x                 | X                 | number        | number        |
| No       |                | y                 | Y                 | number        | number        |
| No       |                | latitude          | Latitude          | number        | number        |
| No       |                | longitude         | Longitude         | number        | number        |
```

## Time Field

```ls
Value = approved_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_start_date,permit_end_date,permit_address,x,y,latitude,longitude
```

## Data Commands

```ls
series e:b6tj-gt35 d:2016-02-05T17:23:21.000Z t:permit_number=15EXC-7487 t:permit_zipcode=94115 t:permit_type=Excavation t:agentphone=415-716-8363 t:inspector="Melinda Hespen" t:status=APPROVED t:permit_purpose="Webster Street Pavement Renovation, Traffic Signal Modification, Water Main Installation, and Sewer Replacement and Repair Project (2386J)" t:contact=415-740-8008 t:agent="Shaw Pipeline Inc." t:cross_street_2="WEBSTER ST" t:streetname="CALIFORNIA ST" t:cross_street_1="BUCHANAN ST" m:cnn=3555000

series e:b6tj-gt35 d:2016-10-12T14:58:22.000Z t:permit_number=16EXC-5626 t:permit_zipcode=94127 t:permit_type=Excavation t:agentphone="(408) 717-2588" t:inspector="Joe Castro" t:status=APPROVED t:permit_purpose="Haight-Ashbury/Tenderloin/Diamond Heights Districts Sewer Replacement and Pavement Renovation (Contract No. WW-622/2644J)" t:contact="415 606-5694" t:agent="Hernandez Engineering" t:streetname="WOODSIDE AVE" t:cross_street_1="BALCETA AVE" m:cnn=22855000

series e:b6tj-gt35 d:2017-03-23T14:45:29.000Z t:permit_number=17EXC-1425 t:permit_zipcode=94122 t:permit_type=Excavation t:agentphone=415-695-3454 t:inspector="Rich Rozzi" t:status=APPROVED t:curbrampwork=true t:permit_purpose="3RD AVE @ PARNASSUS AVE" t:contact=415-695-3500 t:agent="Pacific Gas & Electric" t:streetname="PARNASSUS AVE" t:cross_street_1="03RD AVE" m:cnn=27065000
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:b6tj-gt35 l:"Street-Use Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/b6tj-gt35

property e:b6tj-gt35 t:meta.view v:id=b6tj-gt35 v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Street-Use Permits" v:attribution="San Francisco Department of Public Works"

property e:b6tj-gt35 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:b6tj-gt35 t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:b6tj-gt35 t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit_number | streetname    | cross_street_1 | cross_street_2 | permit_type | agent                               | agentphone             | permit_purpose                                                                                                                             | approved_date       | status   | cnn      | permit_zipcode | permit_start_date   | permit_end_date     | permit_address   | contact              | inspector      | curbrampwork | x             | y             | latitude         | longitude         | 
| ============= | ============= | ============== | ============== | =========== | =================================== | ====================== | ========================================================================================================================================== | =================== | ======== | ======== | ============== | =================== | =================== | ================ | ==================== | ============== | ============ | ============= | ============= | ================ | ================= | 
| 15EXC-7487    | CALIFORNIA ST | BUCHANAN ST    | WEBSTER ST     | Excavation  | Shaw Pipeline Inc.                  | 415-716-8363           | Webster Street Pavement Renovation, Traffic Signal Modification, Water Main Installation, and Sewer Replacement and Repair Project (2386J) | 2016-02-05T17:23:21 | APPROVED | 3555000  | 94115          | 2016-02-05T00:00:00 | 2017-05-23T00:00:00 |                  | 415-740-8008         | Melinda Hespen |              | 6003604.72999 | 2115593.43914 | 37.7892198531823 | -122.431373840518 | 
| 16EXC-5626    | WOODSIDE AVE  | BALCETA AVE    |                | Excavation  | Hernandez Engineering               | (408) 717-2588         | Haight-Ashbury/Tenderloin/Diamond Heights Districts Sewer Replacement and Pavement Renovation (Contract No. WW-622/2644J)                  | 2016-10-12T14:58:22 | APPROVED | 22855000 | 94127          | 2016-10-17T00:00:00 | 2017-10-11T00:00:00 | 100 WOODSIDE AVE | 415 606-5694         | Joe Castro     |              | 5995899.12116 | 2100200.73102 | 37.746515746369  | -122.45692035669  | 
| 17EXC-1425    | PARNASSUS AVE | 03RD AVE       |                | Excavation  | Pacific Gas & Electric              | 415-695-3454           | 3RD AVE @ PARNASSUS AVE                                                                                                                    | 2017-03-23T14:45:29 | APPROVED | 27065000 | 94122          | 2017-04-03T00:00:00 | 2017-05-01T00:00:00 | 1362 03RD AVE    | 415-695-3500         | Rich Rozzi     | true         | 5995228.1061  | 2106381.76885 | 37.7634487495175 | -122.459688261499 | 
| 17TC-0237     | DE BOOM ST    | 02ND ST        | END            | TableChair  | 21ST AMENDMENT                      | (415) 369-0900         | TEN (10) TABLES AND THIRTY EIGHT (38) CHAIRS ARE AT DE BOOM ALLEY11:00 AM to 10:00 PM - Monday through Sunday                              | 2017-03-15T15:48:02 | APPROVED | 4624000  | 94107          | 2017-03-16T00:00:00 | 2018-03-15T00:00:00 | 563 02ND ST      | Refer to Agent       |                |              | 6014764.2104  | 2112891.04816 | 37.7824258349409 | -122.392573974568 | 
| 16EXC-6273    | QUINTARA ST   | SUNSET BLVD    |                | Excavation  | Bay Area Lightworks                 | 415-822-2336           | Various Locations Traffic Signal Pole & Conduit Contract No. 1, #2821J                                                                     | 2016-11-04T09:13:20 | APPROVED | 23418000 |                | 2016-11-07T00:00:00 | 2017-08-31T00:00:00 |                  | Jim Lau 415-806-8166 | Peter Chin     |              | 5984948.81284 | 2100905.91809 | 37.747817108294  | -122.494836748235 | 
| 16EXC-8363    | IRVING ST     | 20TH AVE       | 21ST AVE       | Excavation  | D'Arcy and Harty Construction,Inc.  | (415) 726-3052         | WW-618/2628J - Richmond/Sunset Districts Sewer Replacement and Pavement Renovation                                                         | 2017-02-08T15:07:38 | APPROVED | 7297000  | 94122          | 2017-02-06T00:00:00 | 2017-10-13T00:00:00 |                  | 4157263052           | Robin Park     |              | 5989725.70808 | 2106512.98133 | 37.7634910734876 | -122.478728672183 | 
| 17EXC-1100    | OAK ST        | ASHBURY ST     | CLAYTON ST     | Excavation  | JMB Construction, Inc.              | (415) 740-0269         | San Francisco Recycled Water Pipeline                                                                                                      | 2017-03-31T14:33:35 | APPROVED | 9767000  | 94117          | 2017-03-31T00:00:00 | 2018-08-19T00:00:00 |                  | Refer to Agent       |                |              | 5998630.07072 | 2109342.50761 | 37.7717732299418 | -122.44813520818  | 
| 16EXC-2736    | VIENNA ST     | BRAZIL AVE     | PERSIA AVE     | Excavation  | Esquivel Grading & Paving, Inc.     | (415) 468-5700 ext. 57 | Various Locations Pavement Renovation and Sewer Replacement No. 22 (Contract No. 2503J)                                                    | 2016-08-05T13:43:38 | APPROVED | 13301000 | 94112          | 2016-08-15T00:00:00 | 2018-01-26T00:00:00 |                  | (415) 354-4870       | Robin Park     |              | 6003540.22195 | 2090841.0073  | 37.7212518862255 | -122.429830777688 | 
| 07IE-0380     | VALENCIA ST   | 16TH ST        | 17TH ST        | StrtImprov  | John Sheeraw                        | (510) 533-7407         | Remove & replace curb parking strip and sidewalk. Voluntary improvement. Street Space Included.                                            | 2007-06-07T00:00:00 | ACTIVE   | 13060000 | 94110          |                     |                     | 530 VALENCIA ST  |                      |                |              | 6006129.09545 | 2106482.86347 | 37.7643471606116 | -122.421992368438 | 
| 17EXC-0483    | 18TH ST       | LAPIDGE ST     | DEARBORN ST    | Excavation  | Balfour Beatty Infrastructure, Inc. | 650-537-0379           | 33 Stanyan Pole Replacement and Overhead Reconstruction Project Phase 2 SFMTA CN#1292                                                      | 2017-02-03T09:31:53 | APPROVED | 882000   | 94110          | 2017-02-06T00:00:00 | 2017-08-31T00:00:00 |                  | 650-537-0379         |                |              | 6005935.2114  | 2105500.59548 | 37.7616391474652 | -122.422593154832 | 
```