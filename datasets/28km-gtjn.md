# Fire Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-stations-61d88) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/28km-gtjn) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/28km-gtjn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/28km-gtjn/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 28km-gtjn |
| Name | Fire Stations |
| Attribution | City of Chicago |
| Category | Public Safety |
| Tags | public safety, facilities, gis |
| Created | 2010-12-22T20:59:06Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Fire station locations

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME       | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | state       | STATE      | text      | text        |
| Yes      | series tag  | zip         | ZIP        | text      | text        |
| Yes      | series tag  | engine      | ENGINE     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:28km-gtjn d:2010-12-22T13:00:27.000Z t:zip=60620 t:engine=E73 t:name=E73 t:state=IL t:city=CHICAGO m:row_number.28km-gtjn=1

series e:28km-gtjn d:2010-12-22T13:00:27.000Z t:zip=60610 t:engine=E4 t:name=E4 t:state=IL t:city=CHICAGO m:row_number.28km-gtjn=2

series e:28km-gtjn d:2010-12-22T13:00:27.000Z t:zip=60652 t:engine=E64 t:name=E64 t:state=IL t:city=CHICAGO m:row_number.28km-gtjn=3
```

## Meta Commands

```ls
metric m:row_number.28km-gtjn p:long l:"Row Number"

entity e:28km-gtjn l:"Fire Stations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/28km-gtjn

property e:28km-gtjn t:meta.view v:id=28km-gtjn v:category="Public Safety" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Fire Stations" v:attribution="City of Chicago"

property e:28km-gtjn t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:28km-gtjn t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | name    | address               | city    | state | zip   | engine | 
| =========== | ======= | ===================== | ======= | ===== | ===== | ====== | 
| 1293022827  | E73     | 8630 S EMERALD AVE    | CHICAGO | IL    | 60620 | E73    | 
| 1293022827  | E4      | 548 W DIVISION ST     | CHICAGO | IL    | 60610 | E4     | 
| 1293022827  | E64     | 7659 S PULASKI RD     | CHICAGO | IL    | 60652 | E64    | 
| 1293022827  | E43     | 2179 N STAVE ST       | CHICAGO | IL    | 60647 | E43    | 
| 1293022827  | E70/E59 | 6030 N CLARK ST       | CHICAGO | IL    | 60660 | E70/59 | 
| 1293022827  | E71     | 6239 N CALIFORNIA AVE | CHICAGO | IL    | 60659 | E71    | 
| 1293022827  | E124    | 4426 N KEDZIE AVE     | CHICAGO | IL    | 60625 | E124   | 
| 1293022827  | E69     | 4017 N TRIPP AVE      | CHICAGO | IL    | 60641 | E69    | 
| 1293022827  | E22     | 605 W ARMITAGE AVE    | CHICAGO | IL    | 60614 | E22    | 
| 1293022827  | E103    | 25 S LAFLIN ST        | CHICAGO | IL    | 60607 | E103   | 
```