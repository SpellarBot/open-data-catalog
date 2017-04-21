# Parking Signs / Street Space Permit Photos

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-signs-street-space-permit-photos) |
| Metadata | [Link](https://data.sfgov.org/api/views/pigs-fac7) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pigs-fac7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pigs-fac7/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pigs-fac7 |
| Name | Parking Signs / Street Space Permit Photos |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | permits, construction, buildings, sidewalk, sfmta, tow, verification, photos, street, space, parking, signs |
| Created | 2017-01-12T22:29:47Z |
| Publication Date | 2017-01-13T23:22:26Z |

## Description

Posting Photos of Parking Signs / Street Space Permits. Related parking sign/ street space permit data is here: https://data.sfgov.org/d/sftu-nd43

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | series tag  | permit     | Permit    | text          | text          |
| Yes      | time        | dateadded  | DateAdded | calendar_date | calendar_date |
| Yes      | series tag  | filename   | FileName  | text          | text          |
```

## Time Field

```ls
Value = dateadded
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pigs-fac7 d:2017-04-07T10:14:27.000Z t:permit=M771230 t:filename=http://bsm.sfdpw.org/StreetSpaceUpload/M771230_20170407_100651.jpg m:row_number.pigs-fac7=1

series e:pigs-fac7 d:2017-01-11T12:54:03.000Z t:permit=M753387 t:filename=http://bsm.sfdpw.org/StreetSpaceUpload/M753387_ProShot_20170111_122528.jpg m:row_number.pigs-fac7=2

series e:pigs-fac7 d:2017-01-11T12:54:03.000Z t:permit=M753387 t:filename=http://bsm.sfdpw.org/StreetSpaceUpload/M753387_ProShot_20170111_122528.jpg m:row_number.pigs-fac7=3
```

## Meta Commands

```ls
metric m:row_number.pigs-fac7 p:long l:"Row Number"

entity e:pigs-fac7 l:"Parking Signs / Street Space Permit Photos" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/pigs-fac7

property e:pigs-fac7 t:meta.view v:id=pigs-fac7 v:category="City Infrastructure" v:attributionLink=http://www.sfpublicworks.org v:averageRating=0 v:name="Parking Signs / Street Space Permit Photos" v:attribution="San Francisco Department of Public Works"

property e:pigs-fac7 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pigs-fac7 t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:pigs-fac7 t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit       | dateadded           | filename                                                                         | 
| ============ | =================== | ================================================================================ | 
| M771230      | 2017-04-07T10:14:27 | http://bsm.sfdpw.org/StreetSpaceUpload/M771230_20170407_100651.jpg               | 
| M753387      | 2017-01-11T12:54:03 | http://bsm.sfdpw.org/StreetSpaceUpload/M753387_ProShot_20170111_122528.jpg       | 
| M753387      | 2017-01-11T12:54:03 | http://bsm.sfdpw.org/StreetSpaceUpload/M753387_ProShot_20170111_122528.jpg       | 
| 201704063378 | 2017-04-07T20:22:40 | http://bsm.sfdpw.org/StreetSpaceUpload/201704063378_IMG_1327.JPG                 | 
| m751207      | 2017-01-11T11:35:15 | http://bsm.sfdpw.org/StreetSpaceUpload/m751207_IMG_1084.JPG                      | 
| m751207      | 2017-01-11T11:35:15 | http://bsm.sfdpw.org/StreetSpaceUpload/m751207_IMG_1084.JPG                      | 
| M751707      | 2017-01-10T18:01:55 | http://bsm.sfdpw.org/StreetSpaceUpload/M751707_IMG_20170110_153442.jpg           | 
| 201511243561 | 2017-01-07T23:01:45 | http://bsm.sfdpw.org/StreetSpaceUpload/201511243561_1483738524883-1065663808.jpg | 
| 201701056572 | 2017-01-09T18:45:32 | http://bsm.sfdpw.org/StreetSpaceUpload/201701056572_IMG_03251.jpg                | 
| 201511243561 | 2017-01-06T13:32:32 | http://bsm.sfdpw.org/StreetSpaceUpload/201511243561_1483738326614845529196.jpg   | 
```