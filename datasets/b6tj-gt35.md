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
series e:b6tj-gt35 d:2016-12-21T14:00:23.000Z t:permit_zipcode=94112 t:permit_type=Excavation t:agentphone=707-577-7232 t:status=APPROVED t:permit_purpose="RECONDUCTOR POPE STREET PROJECT" t:contact=415-695-3500 t:agent="Pacific Gas & Electric" t:cross_street_2="PRAGUE ST \ WINDING WAY" t:streetname="POPE ST" t:cross_street_1="HANOVER ST" m:cnn=10597000

series e:b6tj-gt35 d:2016-12-21T16:40:58.000Z t:permit_zipcode=94110 t:permit_type=TableChair t:agentphone="(415) 487-2600" t:inspector="Mari Anderson" t:status=APPROVED t:permit_purpose="TWO (2) TABLES AND FOUR (4) CHAIRS ON GUERRERO STREETSIX (6) TABLES AND EIGHTEEN (18) CHAIRS ON 18TH STREET" t:contact="Refer to Agent" t:agent="TARTINE BAKERY" t:cross_street_2="19TH ST" t:streetname="GUERRERO ST" t:cross_street_1="18TH ST" m:cnn=6580201

series e:b6tj-gt35 d:2016-12-21T14:00:23.000Z t:permit_type=Excavation t:agentphone=707-577-7232 t:status=APPROVED t:permit_purpose="RECONDUCTOR POPE STREET PROJECT" t:contact=415-695-3500 t:agent="Pacific Gas & Electric" t:streetname="POPE ST" t:cross_street_1="CROSS ST" m:cnn=21472000
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
| permit_number | streetname   | cross_street_1          | cross_street_2          | permit_type | agent                  | agentphone     | permit_purpose                                                                                              | approved_date       | status   | cnn      | permit_zipcode | permit_start_date   | permit_end_date     | permit_address  | contact        | inspector     | curbrampwork | x             | y             | latitude         | longitude         | 
| ============= | ============ | ======================= | ======================= | =========== | ====================== | ============== | =========================================================================================================== | =================== | ======== | ======== | ============== | =================== | =================== | =============== | ============== | ============= | ============ | ============= | ============= | ================ | ================= | 
|               | POPE ST      | HANOVER ST              | PRAGUE ST \ WINDING WAY | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 10597000 | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000652.02022 | 2086841.17984 | 37.7101052778941 | -122.439527858622 | 
|               | GUERRERO ST  | 18TH ST                 | 19TH ST                 | TableChair  | TARTINE BAKERY         | (415) 487-2600 | TWO (2) TABLES AND FOUR (4) CHAIRS ON GUERRERO STREETSIX (6) TABLES AND EIGHTEEN (18) CHAIRS ON 18TH STREET | 2016-12-21T16:40:58 | APPROVED | 6580201  | 94110          | 2016-11-16T00:00:00 | 2017-11-15T00:00:00 | 600 GUERRERO ST | Refer to Agent | Mari Anderson |              | 6005435.77827 | 2105392.63041 | 37.7613145119878 | -122.42431281394  | 
|               | POPE ST      | CROSS ST                |                         | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 21472000 |                | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000209.9843  | 2088244.21301 | 37.7139325254462 | -122.441156213729 | 
|               | POPE ST      | MORSE ST                | BRUNSWICK ST            | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 10595000 | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000427.28179 | 2087558.34004 | 37.712061646799  | -122.440355995445 | 
|               | BRUNSWICK ST | POPE ST                 | UNNAMED 069             | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 3251000  | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000420.41677 | 2087321.50369 | 37.7114109561255 | -122.440362748419 | 
|               | POPE ST      | MISSION ST              | HOLLYWOOD CT            | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 10592000 | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000078.46816 | 2088657.37684 | 37.7150594880962 | -122.441640414003 | 
|               | MISSION ST   | NIAGARA AVE             | POPE ST                 | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 9180000  | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000051.46912 | 2088818.79802 | 37.7155011759424 | -122.441745311986 | 
|               | CROSS ST     | POPE ST                 |                         | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 21472000 |                | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000209.9843  | 2088244.21301 | 37.7139325254462 | -122.441156213729 | 
|               | POPE ST      | BALTIMORE WAY           |                         | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 21447000 |                | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000617.99862 | 2086636.1772  | 37.7095404496988 | -122.439630756777 | 
|               | POPE ST      | PRAGUE ST \ WINDING WAY | BALTIMORE WAY           | Excavation  | Pacific Gas & Electric | 707-577-7232   | RECONDUCTOR POPE STREET PROJECT                                                                             | 2016-12-21T14:00:23 | APPROVED | 10598000 | 94112          | 2017-02-06T00:00:00 | 2017-06-05T00:00:00 |                 | 415-695-3500   |               |              | 6000657.40242 | 2086709.57927 | 37.7097442382295 | -122.439499829135 | 
```