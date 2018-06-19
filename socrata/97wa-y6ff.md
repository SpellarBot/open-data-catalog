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
series e:97wa-y6ff d:2014-05-02T00:00:00.000Z t:license=94026 t:renewed=05/2016 t:driver_type=Taxi t:city=ROSEMONT t:license_type=PERMANENT t:sex=MALE t:record_number=10-00180783 t:name="ABDALLAH OU ALI, OMAR AIT" t:state=IL t:status=ACTIVE m:row_number.97wa-y6ff=1

series e:97wa-y6ff d:2016-03-09T00:00:00.000Z t:license=97941 t:renewed=02/2017 t:driver_type="Livery Only" t:city=PALATINE t:license_type=PERMANENT t:sex=MALE t:record_number=12-01919041 t:name="ZAPATA, RICARDO R" t:state=IL t:status=ACTIVE m:row_number.97wa-y6ff=2

series e:97wa-y6ff d:2016-02-23T00:00:00.000Z t:license=82901 t:renewed=02/2017 t:driver_type=Taxi t:city=CHICAGO t:license_type=PERMANENT t:sex=MALE t:record_number=06-00189240 t:name="BENYAMINA, MOHAMMED" t:state=IL t:status=ACTIVE m:row_number.97wa-y6ff=3
```

## Meta Commands

```ls
metric m:row_number.97wa-y6ff p:long l:"Row Number"

entity e:97wa-y6ff l:"Public Chauffeurs" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/97wa-y6ff

property e:97wa-y6ff t:meta.view d:2017-09-25T07:26:25.583Z v:averageRating=0 v:name="Public Chauffeurs" v:attribution="City of Chicago" v:attributionLink=http://www.cityofchicago.org v:id=97wa-y6ff v:category="Community & Economic Development"

property e:97wa-y6ff t:meta.view.owner d:2017-09-25T07:26:25.583Z v:displayName=cocadmin v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:id=scy9-9wg4 v:screenName=cocadmin v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB

property e:97wa-y6ff t:meta.view.tableauthor d:2017-09-25T07:26:25.583Z v:displayName=cocadmin v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:id=scy9-9wg4 v:screenName=cocadmin v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB
```

## Top Records

```ls
| license | renewed | status | status_date         | driver_type | license_type | issue_date          | name                      | sex  | city        | state | record_number | 
| ======= | ======= | ====== | =================== | =========== | ============ | =================== | ========================= | ==== | =========== | ===== | ============= | 
| 94026   | 05/2016 | ACTIVE | 2014-05-02T00:00:00 | Taxi        | PERMANENT    | 2012-05-17T00:00:00 | ABDALLAH OU ALI, OMAR AIT | MALE | ROSEMONT    | IL    | 10-00180783   | 
| 97941   | 02/2017 | ACTIVE | 2016-03-09T00:00:00 | Livery Only | PERMANENT    | 2013-01-16T00:00:00 | ZAPATA, RICARDO R         | MALE | PALATINE    | IL    | 12-01919041   | 
| 82901   | 02/2017 | ACTIVE | 2016-02-23T00:00:00 | Taxi        | PERMANENT    | 2002-11-21T00:00:00 | BENYAMINA, MOHAMMED       | MALE | CHICAGO     | IL    | 06-00189240   | 
| 56870   | 05/2016 | ACTIVE | 2015-04-28T00:00:00 | Taxi        | PERMANENT    | 1989-09-28T00:00:00 | ATIEMOH, ADDO A           | MALE | CHICAGO     | IL    | 06-00238147   | 
| 103247  | 02/2017 | ACTIVE | 2016-03-10T00:00:00 | Taxi        | PERMANENT    | 2016-03-10T00:00:00 | MASOOD, MUZZAMIL          | MALE | BOLINGBROOK | IL    | 16-01565506   | 
| 83493   | 02/2017 | ACTIVE | 2016-02-29T00:00:00 | Taxi        | PERMANENT    | 2003-06-05T00:00:00 | JAHANGIR, MALIK           | MALE | CHICAGO     | IL    | 06-00184579   | 
| 103332  |         | ACTIVE | 2016-05-09T00:00:00 | Livery Only | PERMANENT    |                     | SACAN, HUSEYIN            | MALE | DES PLAINES | IL    | 16-03004596   | 
| 102778  | 04/2016 | ACTIVE | 2016-05-09T00:00:00 | Taxi        | PERMANENT    | 2015-08-12T00:00:00 | AMANTE, WAKSHUM G         | MALE | CHICAGO     | IL    | 15-03920586   | 
| 103924  |         | ACTIVE | 2017-02-16T00:00:00 | Livery Only | PERMANENT    | 2017-02-24T00:00:00 | KISACIK, HAKAN            | MALE | CHICAGO     | IL    | 17-00862380   | 
| 100792  | 05/2016 | ACTIVE | 2015-05-12T00:00:00 | Taxi        | PERMANENT    | 2014-05-20T00:00:00 | TUVSHINJARGAL, DAMPIL     | MALE | CHICAGO     | IL    | 14-00712759   | 
```