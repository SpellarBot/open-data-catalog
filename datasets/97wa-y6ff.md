# Public Chauffeurs

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/97wa-y6ff/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/public-chauffeurs-39a87)
* Id = 97wa-y6ff
* Name = Public Chauffeurs
* Attribution = City of Chicago
* Attribution Link = http://www.cityofchicago.org
* Category = Community & Economic Development
* Tags = [licenses, transportation]
* Created = 2013-02-06T18:42:30Z
* Publication Date = 2016-02-16T17:38:59Z
* Rows Updated = 2017-03-02T16:54:31Z

## Description

List of City of Chicago licensed Public Chauffeurs, who may operate a licensed Taxicab, Livery, or Horse-Drawn Carriage. For questions or issues regarding this dataset, please e-mail BACPPV@cityofchicago.org with chauffeur name, number, and question or issue. For more information on the Public Chauffeur program, please see http://www.cityofchicago.org/city/en/depts/bacp/supp_info/public_chauffeurinformation.html.

## Columns

```ls
| Name                | Field Name    | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | ============= | ============= | ============= | ============== | ======== | 
| License Number      | license       | number        | number        | numeric metric | Yes      | 
| Renewed             | renewed       | text          | text          | series tag     | Yes      | 
| Status              | status        | text          | text          | series tag     | Yes      | 
| Status Date         | status_date   | calendar_date | calendar_date | time           | Yes      | 
| Driver Type         | driver_type   | text          | text          | series tag     | Yes      | 
| License Type        | license_type  | text          | text          | series tag     | Yes      | 
| Original Issue Date | issue_date    | calendar_date | calendar_date |                | No       | 
| Name                | name          | text          | text          | series tag     | Yes      | 
| Sex                 | sex           | text          | text          | series tag     | Yes      | 
| Chauffeur City      | city          | text          | text          | series tag     | Yes      | 
| Chauffeur State     | state         | text          | text          | series tag     | Yes      | 
| Record Number       | record_number | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = issue_date
Annotation Fields = 
```

## Data Commands

```ls
series e:97wa-y6ff d:2015-05-18T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="RICE, WENDELL C" t:state=IL t:driver_type="Livery Only" t:record_number=08-00563280 t:city=CHICAGO m:license=91227

series e:97wa-y6ff d:2016-05-09T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="HABTU, KIDANE M" t:state=IL t:driver_type=Taxi t:record_number=13-00393656 t:city=CHICAGO m:license=98363

series e:97wa-y6ff d:2014-05-02T00:00:00.000Z t:renewed=05/2016 t:sex=MALE t:license_type=PERMANENT t:status=ACTIVE t:name="ABDALLAH OU ALI, OMAR AIT" t:state=IL t:driver_type=Taxi t:record_number=10-00180783 t:city=ROSEMONT m:license=94026
```

## Meta Commands

```ls
metric m:license p:integer l:"License Number" d:"The Public Chauffeur license number issued to the licensee." t:dataTypeName=number

entity e:97wa-y6ff l:"Public Chauffeurs" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/97wa-y6ff

property e:97wa-y6ff t:meta.view d:2017-03-03T14:20:46.004Z v:id=97wa-y6ff v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Public Chauffeurs" v:attribution="City of Chicago"

property e:97wa-y6ff t:meta.view.owner d:2017-03-03T14:20:46.004Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false

property e:97wa-y6ff t:meta.view.tableauthor d:2017-03-03T14:20:46.004Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```