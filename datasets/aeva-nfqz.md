# Election 2014 August LAUSD District 1 Polling Place List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2014-august-lausd-district-1-polling-place-list-f75b4) |
| Metadata | [Link](https://data.lacity.org/api/views/aeva-nfqz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/aeva-nfqz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/aeva-nfqz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | aeva-nfqz |
| Name | Election 2014 August LAUSD District 1 Polling Place List |
| Category | A Well Run City |
| Created | 2014-08-20T20:37:48Z |
| Publication Date | 2014-08-22T14:08:31Z |

## Description

Listing of the poll place locations for the 2014 August Los Angeles Unified School District 1 Runoff Special Election. Includes detail listing down to the established precincts.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | consolidation   | CONSOLIDATION   | text      | text        |
| Yes      | series tag  | polling_place   | POLLING PLACE   | text      | text        |
| Yes      | series tag  | ballot_group    | BALLOT GROUP    | text      | number      |
| Yes      | series tag  | poll_type       | POLL TYPE       | text      | text        |
| Yes      | series tag  | precinct        | PRECINCT        | text      | text        |
| Yes      | series tag  | handicap_access | HANDICAP ACCESS | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aeva-nfqz d:2014-01-01T00:00:00.000Z t:precinct=900-5318B t:poll_type=COMMU t:polling_place="TOM BRADLEY FAMILY CENTER" t:ballot_group=1 t:handicap_access=Y t:consolidation=900-5317A m:row_number.aeva-nfqz=1

series e:aeva-nfqz d:2014-01-01T00:00:00.000Z t:precinct=900-2484E t:poll_type=CHUR1 t:polling_place="COMMUNITY UNITED PRESB CHR" t:ballot_group=1 t:handicap_access=Y t:consolidation=900-2484B m:row_number.aeva-nfqz=2

series e:aeva-nfqz d:2014-01-01T00:00:00.000Z t:precinct=900-1175A t:poll_type=LACPR t:polling_place="ROBERTSON RECREATION CENTER" t:ballot_group=1 t:handicap_access=Y t:consolidation=900-1175A m:row_number.aeva-nfqz=3
```

## Meta Commands

```ls
metric m:row_number.aeva-nfqz p:long l:"Row Number"

entity e:aeva-nfqz l:"Election 2014 August LAUSD District 1 Polling Place List" t:url=https://data.lacity.org/api/views/aeva-nfqz

property e:aeva-nfqz t:meta.view v:id=aeva-nfqz v:category="A Well Run City" v:averageRating=0 v:name="Election 2014 August LAUSD District 1 Polling Place List"

property e:aeva-nfqz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:aeva-nfqz t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:aeva-nfqz t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| consolidation | polling_place                 | ballot_group | poll_type | precinct  | handicap_access | 
| ============= | ============================= | ============ | ========= | ========= | =============== | 
| 900-5317A     | TOM BRADLEY FAMILY CENTER     | 1            | COMMU     | 900-5318B | Y               | 
| 900-2484B     | COMMUNITY UNITED PRESB CHR    | 1            | CHUR1     | 900-2484E | Y               | 
| 900-1175A     | ROBERTSON RECREATION CENTER   | 1            | LACPR     | 900-1175A | Y               | 
| 900-0282A     | GUIDANCE CHR OF REL SCIENCE   | 1            | CHUR1     | 900-0282A | Y               | 
| 900-2083B     | BRADLEY MAGNET SCHOOL         | 1            | LAUSD     | 900-3050B | Y               | 
| 900-2348A     | WILLIAM GRANT STILL ART CTR   | 1            | MISCP     | 900-5503D | Y               | 
| 250-0002A     | PURCHE AVE ELEMENTARY SCHOOL  | 1            | SCH-P     | 250-0001F | Y               | 
| 900-1502A     | CULVER PALMS CHURCH OF CHRIST | 1            | CHURC     | 900-1502A | Y               | 
| 900-2497A     | ST ANDREWS RECREATION CENTER  | 1            | LACPR     | 900-2497E | Y               | 
| 900-5504C     | MERIDIAN OF CHEVIOT HILLS     | 1            | SRHMS     | 900-5504E | Y               | 
```