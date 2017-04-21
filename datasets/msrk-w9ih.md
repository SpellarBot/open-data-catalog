# Cooling Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cooling-centers-eb867) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/msrk-w9ih) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/msrk-w9ih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/msrk-w9ih/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | msrk-w9ih |
| Name | Cooling Centers |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | cooling centers, sustainability, human services, family and support services |
| Created | 2012-07-05T22:43:11Z |
| Publication Date | 2012-07-05T22:51:22Z |

## Description

Cooling Centers offer residents air-conditioned refuge from oppressive summer heat. The Chicago Department of Family and Support Services operates six Cooling 
Centers during the summer months.  Additional facilities are opened as needed in 
libraries, Park District buildings, senior centers and other community venues.
You may call 311 to locate a Cooling Center in your area, or go to http://bit.ly/kIhHPj for more information.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | site_type          | SITE TYPE          | text      | text        |
| Yes      | series tag  | site_name          | SITE NAME          | text      | text        |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | state              | STATE              | text      | text        |
| Yes      | series tag  | zip                | ZIP                | text      | number      |
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
series e:msrk-w9ih d:2012-07-05T15:50:53.000Z t:zip=60625 t:phone=312-744-0784 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m." t:state=IL t:site_type="Regional Senior Center" t:site_name=Northeast t:city=Chicago m:row_number.msrk-w9ih=1

series e:msrk-w9ih d:2012-07-05T15:50:53.000Z t:zip=60618 t:phone=312-744-6681 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m" t:state=IL t:site_type="Regional Senior Center" t:site_name=Northwest t:city=Chicago m:row_number.msrk-w9ih=2

series e:msrk-w9ih d:2012-07-05T15:51:02.000Z t:zip=60649 t:phone=312-747-0189 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m" t:state=IL t:site_type="Regional Senior Center" t:site_name=Southeast t:city=Chicago m:row_number.msrk-w9ih=3
```

## Meta Commands

```ls
metric m:row_number.msrk-w9ih p:long l:"Row Number"

entity e:msrk-w9ih l:"Cooling Centers" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/msrk-w9ih

property e:msrk-w9ih t:meta.view v:id=msrk-w9ih v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org/city/en/depts/fss/provdrs/serv/svcs/how_to_find_weatherreliefinchicago.html v:averageRating=0 v:name="Cooling Centers" v:attribution="City of Chicago"

property e:msrk-w9ih t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:msrk-w9ih t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | site_type                | site_name           | hours_of_operation                                               | address                  | city    | state | zip   | phone        | 
| =========== | ======================== | =================== | ================================================================ | ======================== | ======= | ===== | ===== | ============ | 
| 1341503453  | Regional Senior Center   | Northeast           | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m.      | 2019 W. Lawrence Avenue  | Chicago | IL    | 60625 | 312-744-0784 | 
| 1341503453  | Regional Senior Center   | Northwest           | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m | 3160 N. Milwaukee Avenue | Chicago | IL    | 60618 | 312-744-6681 | 
| 1341503462  | Regional Senior Center   | Southeast           | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat - Sun 9:00 a.m. to 4:00 p.m | 1767 E. 79th Street      | Chicago | IL    | 60649 | 312-747-0189 | 
| 1341503462  | Community Service Center | Garfield Center     | M-F Open 24 Hours                                                | 10 S. Kedzie Avenue      | Chicago | IL    | 60612 | 312-746-5400 | 
| 1341503462  | Regional Senior Center   | Central West        | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 2102 W. Ogden Avenue     | Chicago | IL    | 60612 | 312-746-5300 | 
| 1341503469  | Regional Senior Center   | Renaissance Court   | Mon - Fri 8:30 a.m. to 4:30 p.m.                                 | 78 E. Washington Street  | Chicago | IL    | 60602 | 312-744-4550 | 
| 1341503469  | Regional Senior Center   | Southwest           | Mon - Fri 8:30 a.m. to 4:30 p.m. Sat 9:00 a.m. to 4:00 p.m.      | 6117 S. Kedzie Avenue    | Chicago | IL    | 60629 | 312-747-0440 | 
| 1341503476  | Community Service Center | King Center         | M.T.Th. F 9am-5pm Wed. 11am-7pm                                  | 4314 S. Cottage Grove    | Chicago | IL    | 60653 | 312-747-2300 | 
| 1341503476  | Community Service Center | North Area Center   | M.T.Th. F 9am-5pm Wed. 11am-7pm                                  | 4740 N. Sheridan Road    | Chicago | IL    | 60640 | 312-744-2580 | 
| 1341503476  | Community Service Center | Trina Davila Center | M.T.Th. F 9am-5pm Wed. 11am-7pm                                  | 4357 W. Armitage Avenue  | Chicago | IL    | 60639 | 312-744-2014 | 
```