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
| Rows Updated | 2017-03-21T15:12:01Z |

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