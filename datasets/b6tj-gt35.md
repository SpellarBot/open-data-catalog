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
series e:b6tj-gt35 d:2017-03-28T15:09:59.000Z t:permit_zipcode=94118 t:permit_type=Excavation t:agentphone=415-337-0190 t:inspector="Denny Phan" t:status=APPROVED t:permit_purpose="Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J)" t:contact="(415) 337-0190" t:agent="Shaw Pipeline Inc." t:cross_street_2="CALIFORNIA ST \ CORNWALL ST" t:streetname="07TH AVE" t:cross_street_1="LAKE ST" m:cnn=350000

series e:b6tj-gt35 d:2017-03-28T09:16:46.000Z t:permit_zipcode=94110 t:permit_type=Excavation t:agentphone=510-727-6085 t:inspector="Woojoo Chung" t:status=APPROVED t:permit_purpose="311801 Dig up Cortland and Bennington" t:contact="Refer to Agent: JUDY JONES 415-330-1880" t:agent="SBC - Pacific Bell Engineering" t:cross_street_2="BENNINGTON ST" t:streetname="CORTLAND AVE" t:cross_street_1="BOCANA ST" m:cnn=4423000

series e:b6tj-gt35 d:2017-03-28T15:09:59.000Z t:permit_zipcode=94121 t:permit_type=Excavation t:agentphone=415-337-0190 t:inspector="Denny Phan" t:status=APPROVED t:permit_purpose="Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J)" t:contact="(415) 337-0190" t:agent="Shaw Pipeline Inc." t:cross_street_2="21ST AVE" t:streetname="CABRILLO ST" t:cross_street_1="20TH AVE" m:cnn=3487000
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
| permit_number | streetname   | cross_street_1  | cross_street_2              | permit_type | agent                          | agentphone   | permit_purpose                                                                        | approved_date       | status   | cnn      | permit_zipcode | permit_start_date   | permit_end_date     | permit_address | contact                                 | inspector          | curbrampwork | x             | y             | latitude         | longitude         | 
| ============= | ============ | =============== | =========================== | =========== | ============================== | ============ | ===================================================================================== | =================== | ======== | ======== | ============== | =================== | =================== | ============== | ======================================= | ================== | ============ | ============= | ============= | ================ | ================= | 
|               | 07TH AVE     | LAKE ST         | CALIFORNIA ST \ CORNWALL ST | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 350000   | 94118          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 5993662.23238 | 2114533.0856  | 37.7857399167892 | -122.465696325017 | 
|               | CORTLAND AVE | BOCANA ST       | BENNINGTON ST               | Excavation  | SBC - Pacific Bell Engineering | 510-727-6085 | 311801 Dig up Cortland and Bennington                                                 | 2017-03-28T09:16:46 | APPROVED | 4423000  | 94110          | 2017-03-28T00:00:00 | 2017-04-25T00:00:00 |                | Refer to Agent: JUDY JONES 415-330-1880 | Woojoo Chung       |              | 6007042.09033 | 2097313.81084 | 37.7392224813366 | -122.418184459076 | 
|               | CABRILLO ST  | 20TH AVE        | 21ST AVE                    | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 3487000  | 94121          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 5989587.09036 | 2110582.46403 | 37.7746567112894 | -122.479505856613 | 
|               | 02ND ST      | STEVENSON ST    | JESSIE ST                   | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 130000   | 94105          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 6012497.42657 | 2115196.09802 | 37.788628816444  | -122.400578075724 | 
|               | ANZA ST      | 19TH AVE        | 20TH AVE                    | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 2337000  | 94121          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 5989848.01253 | 2111952.14851 | 37.7784326386785 | -122.478703475959 | 
|               | GEARY BLVD   | 27TH AVE        | 28TH AVE                    | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 6084201  | 94121          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 5987343.18118 | 2112588.83065 | 37.7800350324425 | -122.487415296566 | 
|               | OFARRELL ST  | CYRIL MAGNIN ST | ELWOOD ST                   | Excavation  | San Francisco Water Department | 7139073894   | 266 - 272 O'FARRRELL ST                                                               | 2017-03-14T07:49:21 | ACTIVE   | 9724000  | 94102          | 2017-03-16T00:00:00 | 2017-04-13T00:00:00 |                | Refer to Agent 415 550 4900             | Alejandro DelCalvo |              | 6010007.75879 | 2114388.26294 | 37.786271530867  | -122.409134966811 | 
|               | 01ST ST      | STEVENSON ST    | END                         | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 101000   | 94105          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 6013147.11143 | 2115827.96848 | 37.7903999964569 | -122.39837460091  | 
|               | DOLORES ST   | 26TH ST         |                             | Excavation  | Sonic Telecom, LLC             | 707-791-5391 | 1609 - Cougar - 26th Avenue Trench Across Dolores                                     | 2017-03-28T16:18:18 | APPROVED | 21902000 | 94110          | 2017-04-10T00:00:00 | 2017-04-30T00:00:00 | 3780 26TH ST   | (707) 791-5618                          | Anthony Lee        |              | 6005351.17279 | 2100826.06901 | 37.7487710205805 | -122.424280633114 | 
|               | CLEMENT ST   | 30TH AVE        | 31ST AVE                    | Excavation  | Shaw Pipeline Inc.             | 415-337-0190 | Various Locations No. 24 Pavement Renovation & Sewer Replacement (Contract No. 2709J) | 2017-03-28T15:09:59 | APPROVED | 4180000  | 94121          | 2017-03-28T00:00:00 | 2018-11-17T00:00:00 |                | (415) 337-0190                          | Denny Phan         |              | 5986388.62629 | 2113233.9871  | 37.7817507334476 | -122.490764970241 | 
```