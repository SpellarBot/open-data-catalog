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
series e:b6tj-gt35 d:2017-03-15T15:48:02.000Z t:cross_street_2=END t:cross_street_1="02ND ST" t:agent="21ST AMENDMENT" t:permit_number=17TC-0237 t:streetname="DE BOOM ST" t:agentphone="(415) 369-0900" t:contact="Refer to Agent" t:permit_purpose="TEN (10) TABLES AND THIRTY EIGHT (38) CHAIRS ARE AT DE BOOM ALLEY11:00 AM to 10:00 PM -  Monday through Sunday" t:permit_type=TableChair t:permit_zipcode=94107 t:status=APPROVED m:cnn=4624000

series e:b6tj-gt35 d:2017-03-31T14:33:35.000Z t:cross_street_2="CLAYTON ST" t:cross_street_1="ASHBURY ST" t:agent="JMB Construction, Inc." t:permit_number=17EXC-1100 t:streetname="OAK ST" t:agentphone="(415) 740-0269" t:contact="Refer to Agent" t:permit_purpose="San Francisco Recycled Water Pipeline" t:permit_type=Excavation t:permit_zipcode=94117 t:status=APPROVED m:cnn=9767000

series e:b6tj-gt35 d:2016-08-05T13:43:38.000Z t:cross_street_2="PERSIA AVE" t:cross_street_1="BRAZIL AVE" t:agent="Esquivel Grading & Paving, Inc." t:permit_number=16EXC-2736 t:streetname="VIENNA ST" t:agentphone="(415) 468-5700 ext. 57" t:contact="(415) 354-4870" t:permit_purpose="Various Locations Pavement Renovation and Sewer Replacement No. 22 (Contract No. 2503J)" t:inspector="Robin Park" t:permit_type=Excavation t:permit_zipcode=94112 t:status=APPROVED m:cnn=13301000
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:b6tj-gt35 l:"Street-Use Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/b6tj-gt35

property e:b6tj-gt35 t:meta.view d:2017-09-25T07:22:28.886Z v:averageRating=0 v:name="Street-Use Permits" v:attribution="San Francisco Department of Public Works" v:attributionLink=http://www.sfdpw.org v:id=b6tj-gt35 v:category="City Infrastructure"

property e:b6tj-gt35 t:meta.view.license d:2017-09-25T07:22:28.886Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:b6tj-gt35 t:meta.view.owner d:2017-09-25T07:22:28.886Z v:displayName="Public Works" v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:id=rcpp-nrjq v:screenName="Public Works" v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB

property e:b6tj-gt35 t:meta.view.tableauthor d:2017-09-25T07:22:28.886Z v:displayName="Public Works" v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:id=rcpp-nrjq v:screenName="Public Works" v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB
```

## Top Records

```ls
| permit_number | streetname  | cross_street_1 | cross_street_2 | permit_type | agent                           | agentphone             | permit_purpose                                                                                                                                                                                                                                                                                                                                                                                                         | approved_date       | status   | cnn      | permit_zipcode | permit_start_date   | permit_end_date     | permit_address  | contact                                | inspector         | curbrampwork | x             | y             | latitude         | longitude         | 
| ============= | =========== | ============== | ============== | =========== | =============================== | ====================== | ====================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | ======== | ======== | ============== | =================== | =================== | =============== | ====================================== | ================= | ============ | ============= | ============= | ================ | ================= | 
| 17TC-0237     | DE BOOM ST  | 02ND ST        | END            | TableChair  | 21ST AMENDMENT                  | (415) 369-0900         | TEN (10) TABLES AND THIRTY EIGHT (38) CHAIRS ARE AT DE BOOM ALLEY11:00 AM to 10:00 PM - Monday through Sunday                                                                                                                                                                                                                                                                                                          | 2017-03-15T15:48:02 | APPROVED | 4624000  | 94107          | 2017-03-16T00:00:00 | 2018-03-15T00:00:00 | 563 02ND ST     | Refer to Agent                         |                   |              | 6014764.2104  | 2112891.04816 | 37.7824258349409 | -122.392573974568 | 
| 17EXC-1100    | OAK ST      | ASHBURY ST     | CLAYTON ST     | Excavation  | JMB Construction, Inc.          | (415) 740-0269         | San Francisco Recycled Water Pipeline                                                                                                                                                                                                                                                                                                                                                                                  | 2017-03-31T14:33:35 | APPROVED | 9767000  | 94117          | 2017-03-31T00:00:00 | 2018-08-19T00:00:00 |                 | Refer to Agent                         |                   |              | 5998630.07072 | 2109342.50761 | 37.7717732299418 | -122.44813520818  | 
| 16EXC-2736    | VIENNA ST   | BRAZIL AVE     | PERSIA AVE     | Excavation  | Esquivel Grading & Paving, Inc. | (415) 468-5700 ext. 57 | Various Locations Pavement Renovation and Sewer Replacement No. 22 (Contract No. 2503J)                                                                                                                                                                                                                                                                                                                                | 2016-08-05T13:43:38 | APPROVED | 13301000 | 94112          | 2016-08-15T00:00:00 | 2018-01-26T00:00:00 |                 | (415) 354-4870                         | Robin Park        |              | 6003540.22195 | 2090841.0073  | 37.7212518862255 | -122.429830777688 | 
| 07IE-0380     | VALENCIA ST | 16TH ST        | 17TH ST        | StrtImprov  | John Sheeraw                    | (510) 533-7407         | Remove & replace curb parking strip and sidewalk. Voluntary improvement. Street Space Included.                                                                                                                                                                                                                                                                                                                        | 2007-06-07T00:00:00 | ACTIVE   | 13060000 | 94110          |                     |                     | 530 VALENCIA ST |                                        |                   |              | 6006129.09545 | 2106482.86347 | 37.7643471606116 | -122.421992368438 | 
| 17EXC-0068    | ANZA ST     | 40TH AVE       |                | Excavation  | Shaw Pipeline Inc.              | 415-337-0190           | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J)                                                                                                                                                                                                                                                                                                                                  | 2017-03-28T15:09:59 | APPROVED | 27905000 |                | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                 | (415) 337-0190                         | Denny Phan        |              | 5983496.09537 | 2111723.97273 | 37.7774352788071 | -122.500659916062 | 
| 15EXC-6425    | POTRERO AVE | 17TH ST        | MARIPOSA ST    | Excavation  | A. Ruiz Construction Co.        | (415) 559-2938         | Potrero Avenue Roadway Improvements (Contract No. 2127J)Construction Work: Sewer, Water, Curb Ramps, Bus Pads, Paving, Concrete Base, AWSS, Bulb Out, Catch Basins, Man Holes, Electric, Landscape, and other.Affected Areas: On Potrero Street from Alameda St to Highway 101/Cesar Chavez and Around SF General Hospital (22nd St to Vermont // Vermont between 22nd and 23rd // 23rd St between Vermont and Potrero | 2015-11-19T14:21:13 | APPROVED | 10662000 | 94110          | 2015-11-20T00:00:00 | 2018-02-16T00:00:00 |                 | Victor Alvarez (415) 559-2938          | Ben Wu            |              | 6010353.44238 | 2106210.91791 | 37.7638378022279 | -122.407362292315 | 
| 17EXC-0074    | EDDY ST     | TAYLOR ST      |                | Excavation  | Bay Area Lightworks             | 415-822-2336           | Eddy & Ellis Traffic Calming Improvement Project, Contract No. 2478                                                                                                                                                                                                                                                                                                                                                    | 2017-02-22T08:53:14 | APPROVED | 24925000 |                | 2017-02-22T00:00:00 | 2017-10-23T00:00:00 |                 | Bay Area Lightworks, Inc. 415-822-2336 | Robin Park        |              | 6009467.05684 | 2113623.36504 | 37.7841409987623 | -122.410951618378 | 
| 17TC-0282     | HAYES ST    | GOUGH ST       | OCTAVIA ST     | TableChair  | Papito West                     | 415-902-8177           | OUTDOOR RESTAURANT SEATING                                                                                                                                                                                                                                                                                                                                                                                             | 2017-03-24T11:09:47 | APPROVED | 6816000  | 94102          | 2017-03-16T00:00:00 | 2018-03-15T00:00:00 | 425 HAYES ST    | Jocelyn Bulow: 415-902-8177            | Mari Anderson     |              | 6005808.34183 | 2110988.57033 | 37.7767006565059 | -122.423422104533 | 
| 03IE-791      | 19TH ST     | EUREKA ST      | DOUGLASS ST    | StrtImprov  | Sanders Pitman Designs          | (415) 431-5709         | Reconstruct new curb and sidewalk to City Standards. Saw-cut 2' of AC gutter and replace with 2in ACWS on 8in concrete base as directed by BSM inspector.                                                                                                                                                                                                                                                              | 2003-12-02T00:00:00 | ACTIVE   | 988000   | 94114          |                     |                     | 4432 19TH ST    |                                        | Cheryl Duperrault |              | 6001251.73545 | 2104693.16167 | 37.759156793619  | -122.438733502348 | 
| 16EXC-0612    | IRVING ST   | 20TH AVE       | 21ST AVE       | Excavation  | Shaw Pipeline Inc.              | 415-337-0190           | Irving Streetscape Improvements (Contract# 2123J)                                                                                                                                                                                                                                                                                                                                                                      | 2016-08-17T19:41:39 | APPROVED | 7297000  | 94122          | 2016-02-22T00:00:00 | 2017-12-22T00:00:00 |                 | Andrew Mellon (415) 740-8008           | Daniel Brugmann   |              | 5989725.70808 | 2106512.98133 | 37.7634910734876 | -122.478728672183 | 
```