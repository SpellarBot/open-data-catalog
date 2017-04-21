# Senior Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/senior-centers-92ce5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qhfc-4cw2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qhfc-4cw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qhfc-4cw2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qhfc-4cw2 |
| Name | Senior Centers |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | facilities, gis, human services, family and support services |
| Created | 2011-01-05T19:00:29Z |
| Publication Date | 2015-05-05T16:44:33Z |

## Description

Senior Center locations, hours of operation and contact information.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | program            | PROGRAM            | text      | text        |
| Yes      | series tag  | site_name          | SITE NAME          | text      | text        |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | state              | STATE              | text      | text        |
| Yes      | series tag  | zip                | ZIP                | text      | text        |
| Yes      | series tag  | phone              | PHONE              | text      | text        |
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
series e:qhfc-4cw2 d:2015-05-05T09:40:17.000Z t:zip=60625 t:phone=312-744-0784 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m." t:program="Regional Senior Center" t:state=IL t:site_name=Northeast t:city=Chicago m:row_number.qhfc-4cw2=1

series e:qhfc-4cw2 d:2015-05-05T09:40:17.000Z t:zip=60629 t:phone=312-747-0440 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m." t:program="Regional Senior Center" t:state=IL t:site_name=Southwest t:city=Chicago m:row_number.qhfc-4cw2=2

series e:qhfc-4cw2 d:2015-05-05T09:40:17.000Z t:zip=60618 t:phone=312-744-6681 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m" t:program="Regional Senior Center" t:state=IL t:site_name=Northwest t:city=Chicago m:row_number.qhfc-4cw2=3
```

## Meta Commands

```ls
metric m:row_number.qhfc-4cw2 p:long l:"Row Number"

entity e:qhfc-4cw2 l:"Senior Centers" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/qhfc-4cw2

property e:qhfc-4cw2 t:meta.view v:id=qhfc-4cw2 v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Senior Centers" v:attribution="City of Chicago"

property e:qhfc-4cw2 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:qhfc-4cw2 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | program                 | site_name         | hours_of_operation                                               | address                  | city    | state | zip   | phone        | 
| =========== | ======================= | ================= | ================================================================ | ======================== | ======= | ===== | ===== | ============ | 
| 1430818817  | Regional Senior Center  | Northeast         | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m.      | 2019 W. Lawrence Avenue  | Chicago | IL    | 60625 | 312-744-0784 | 
| 1430818817  | Regional Senior Center  | Southwest         | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m.      | 6117 S. Kedzie Avenue    | Chicago | IL    | 60629 | 312-747-0440 | 
| 1430818817  | Regional Senior Center  | Northwest         | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m | 3160 N. Milwaukee Avenue | Chicago | IL    | 60618 | 312-744-6681 | 
| 1430818817  | Regional Senior Center  | Central West      | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 2102 W. Ogden Avenue     | Chicago | IL    | 60612 | 312-746-5300 | 
| 1430818817  | Regional Senior Center  | Southeast         | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m | 1767 E. 79th Street      | Chicago | IL    | 60649 | 312-747-0189 | 
| 1430818817  | Regional Senior Center  | Renaissance Court | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 78 E. Washington Street  | Chicago | IL    | 60602 | 312-744-4550 | 
| 1430818817  | Satellite Senior Center | Abbott Park       | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 49 East 95th Street      | Chicago | IL    | 60619 | 312-745-3493 | 
| 1430818817  | Satellite Senior Center | Edgewater         | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 5917 N. Broadway Street  | Chicago | IL    | 60660 | 312-744-4016 | 
| 1430818817  | Satellite Senior Center | Englewood         | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 653-657 W. 63rd Street   | Chicago | IL    | 60621 | 312-745-3328 | 
| 1430818817  | Satellite Senior Center | West Town         | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 1613 W. Chicago Avenue   | Chicago | IL    | 60622 | 312-743-1016 | 
```