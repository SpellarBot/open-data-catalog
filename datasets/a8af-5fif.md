# Right of Way Exception Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/right-of-way-exception-codes-c5383) |
| Metadata | [Link](https://data.sfgov.org/api/views/a8af-5fif) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/a8af-5fif/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/a8af-5fif/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | a8af-5fif |
| Name | Right of Way Exception Codes |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | exceptions, street, restrictions, permits |
| Created | 2012-09-25T00:16:42Z |
| Publication Date | 2015-07-17T15:17:15Z |

## Description

a child table of --Right of Way Exception Data--. a look up table for exception code values

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | exceptioncode | ExceptionCode | text      | text        |
| Yes      | series tag  | message       | Message       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a8af-5fif d:2015-07-17T08:17:03.000Z t:message="ASAP Sidewalk Repair Scheduled" t:exceptioncode=ASAP m:row_number.a8af-5fif=1

series e:a8af-5fif d:2015-07-17T08:17:03.000Z t:message="Please refer to Figure 12 of Section 9.4(A) of the DPW Order No. 171,442 for special conditions for excavation in the vicinity of AWSS." t:exceptioncode=AWSS m:row_number.a8af-5fif=2

series e:a8af-5fif d:2015-07-17T08:17:03.000Z t:message="Banners are allowed on this street" t:exceptioncode=BANAL m:row_number.a8af-5fif=3
```

## Meta Commands

```ls
metric m:row_number.a8af-5fif p:long l:"Row Number"

entity e:a8af-5fif l:"Right of Way Exception Codes" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/a8af-5fif

property e:a8af-5fif t:meta.view v:id=a8af-5fif v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Right of Way Exception Codes" v:attribution="San Francisco Department of Public Works"

property e:a8af-5fif t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:a8af-5fif t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:a8af-5fif t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| :updated_at | exceptioncode | message                                                                                                                                                                                                                                                   | 
| =========== | ============= | ========================================================================================================================================================================================================================================================= | 
| 1437121023  | ASAP          | ASAP Sidewalk Repair Scheduled                                                                                                                                                                                                                            | 
| 1437121023  | AWSS          | Please refer to Figure 12 of Section 9.4(A) of the DPW Order No. 171,442 for special conditions for excavation in the vicinity of AWSS.                                                                                                                   | 
| 1437121023  | BANAL         | Banners are allowed on this street                                                                                                                                                                                                                        | 
| 1437121023  | BANSAF        | Safety Concern - No Banners Allowed                                                                                                                                                                                                                       | 
| 1437121023  | BARBC         | Barbary Coast Trail Markers located in sidewalk. For removal and reinstallation of existing Barbary Coast Trail plaques, please contact Daniel Bacon with the SF Historical Society via e-mail at daniel_bacon@prodigy.net or by phone at (415) 454-2355. | 
| 1437121023  | BIKE          | Blocks with Bicycle Route designations require special attention. For details see Section 10 of DPT's Blue Book and Section 6.3 of DPW's Order No. 171.442.                                                                                               | 
| 1437121023  | BSMEX         | Conflict with existing excavation permit. It is mandatory that you coordinate all work for joint paving.                                                                                                                                                  | 
| 1437121023  | BSSP          | StreetSpace Permit Exceptions                                                                                                                                                                                                                             | 
| 1437121023  | BSSTU         | Conflict with existing Street Use Permit.                                                                                                                                                                                                                 | 
| 1437121023  | BSSW          | Sidewalk Repair scheduled                                                                                                                                                                                                                                 | 
```