# Public Chauffeurs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-chauffeurs-39a87) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/97wa-y6ff) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/97wa-y6ff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/97wa-y6ff/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 97wa-y6ff |
| Name | Public Chauffeurs |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | licenses, transportation |
| Created | 2013-02-06T18:42:30Z |
| Publication Date | 2016-02-16T17:38:59Z |

## Description

List of City of Chicago licensed Public Chauffeurs, who may operate a licensed Taxicab, Livery, or Horse-Drawn Carriage. For questions or issues regarding this dataset, please e-mail BACPPV@cityofchicago.org with chauffeur name, number, and question or issue. For more information on the Public Chauffeur program, please see http://www.cityofchicago.org/city/en/depts/bacp/supp_info/public_chauffeurinformation.html.

## Columns

```ls
| Included | Schema Type | Field Name    | Name                | Data Type     | Render Type   |
| ======== | =========== | ============= | =================== | ============= | ============= |
| Yes      | series tag  | license       | License Number      | text          | number        |
| Yes      | series tag  | renewed       | Renewed             | text          | text          |
| Yes      | series tag  | status        | Status              | text          | text          |
| Yes      | time        | status_date   | Status Date         | calendar_date | calendar_date |
| Yes      | series tag  | driver_type   | Driver Type         | text          | text          |
| Yes      | series tag  | license_type  | License Type        | text          | text          |
| No       |             | issue_date    | Original Issue Date | calendar_date | calendar_date |
| Yes      | series tag  | name          | Name                | text          | text          |
| Yes      | series tag  | sex           | Sex                 | text          | text          |
| Yes      | series tag  | city          | Chauffeur City      | text          | text          |
| Yes      | series tag  | state         | Chauffeur State     | text          | text          |
| Yes      | series tag  | record_number | Record Number       | text          | text          |
```

## Time Field

```ls
Value = status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issue_date
```

## Data Commands

```ls
series e:97wa-y6ff d:2015-05-18T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="RICE, WENDELL C" t:state=IL t:license=91227 t:driver_type="Livery Only" t:record_number=08-00563280 t:city=CHICAGO m:row_number.97wa-y6ff=1

series e:97wa-y6ff d:2016-05-09T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="HABTU, KIDANE M" t:state=IL t:license=98363 t:driver_type=Taxi t:record_number=13-00393656 t:city=CHICAGO m:row_number.97wa-y6ff=2

series e:97wa-y6ff d:2014-05-02T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="ABDALLAH OU ALI, OMAR AIT" t:state=IL t:license=94026 t:driver_type=Taxi t:record_number=10-00180783 t:city=ROSEMONT m:row_number.97wa-y6ff=3
```

## Meta Commands

```ls
metric m:row_number.97wa-y6ff p:long l:"Row Number"

entity e:97wa-y6ff l:"Public Chauffeurs" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/97wa-y6ff

property e:97wa-y6ff t:meta.view v:id=97wa-y6ff v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Public Chauffeurs" v:attribution="City of Chicago"

property e:97wa-y6ff t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:97wa-y6ff t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| license | renewed | status | status_date         | driver_type | license_type | issue_date          | name                      | sex  | city        | state | record_number | 
| ======= | ======= | ====== | =================== | =========== | ============ | =================== | ========================= | ==== | =========== | ===== | ============= | 
| 91227   | 05/2016 | ACTIVE | 2015-05-18T00:00:00 | Livery Only | PERMANENT    | 2008-05-14T00:00:00 | RICE, WENDELL C           | MALE | CHICAGO     | IL    | 08-00563280   | 
| 98363   | 05/2016 | ACTIVE | 2016-05-09T00:00:00 | Taxi        | PERMANENT    | 2013-04-18T00:00:00 | HABTU, KIDANE M           | MALE | CHICAGO     | IL    | 13-00393656   | 
| 94026   | 05/2016 | ACTIVE | 2014-05-02T00:00:00 | Taxi        | PERMANENT    | 2012-05-17T00:00:00 | ABDALLAH OU ALI, OMAR AIT | MALE | ROSEMONT    | IL    | 10-00180783   | 
| 102147  | 04/2016 | ACTIVE | 2015-04-28T00:00:00 | Taxi        | PERMANENT    | 2015-02-09T00:00:00 | MOHAMMED, BURHAUDDIN      | MALE | CHICAGO     | IL    | 15-00228440   | 
| 97941   | 02/2017 | ACTIVE | 2016-03-09T00:00:00 | Livery Only | PERMANENT    | 2013-01-16T00:00:00 | ZAPATA, RICARDO R         | MALE | PALATINE    | IL    | 12-01919041   | 
| 82901   | 02/2017 | ACTIVE | 2016-02-23T00:00:00 | Taxi        | PERMANENT    | 2002-11-21T00:00:00 | BENYAMINA, MOHAMMED       | MALE | CHICAGO     | IL    | 06-00189240   | 
| 56870   | 05/2016 | ACTIVE | 2015-04-28T00:00:00 | Taxi        | PERMANENT    | 1989-09-28T00:00:00 | ATIEMOH, ADDO A           | MALE | CHICAGO     | IL    | 06-00238147   | 
| 103947  |         | ACTIVE | 2017-02-24T00:00:00 | Taxi        | TRAINEE      |                     | AFZAL, RASHID             | MALE | AURORA      | IL    | 17-01035949   | 
| 103247  | 02/2017 | ACTIVE | 2016-03-10T00:00:00 | Taxi        | PERMANENT    | 2016-03-10T00:00:00 | MASOOD, MUZZAMIL          | MALE | BOLINGBROOK | IL    | 16-01565506   | 
| 83493   | 02/2017 | ACTIVE | 2016-02-29T00:00:00 | Taxi        | PERMANENT    | 2003-06-05T00:00:00 | JAHANGIR, MALIK           | MALE | CHICAGO     | IL    | 06-00184579   | 
```