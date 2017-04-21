# Election 2015 March Primary Polling Place List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2015-march-primary-polling-place-list) |
| Metadata | [Link](https://data.lacity.org/api/views/h5ci-ugt3) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/h5ci-ugt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/h5ci-ugt3/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | h5ci-ugt3 |
| Name | Election 2015 March Primary Polling Place List |
| Category | A Well Run City |
| Created | 2015-04-20T15:37:01Z |
| Publication Date | 2015-04-21T22:36:57Z |

## Description

Listing of the poll place locations for the 2015 March primary election. Includes detail listing down to the established precincts with Council District indicator.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag  | council_district      | COUNCIL DISTRICT      | text      | number      |
| Yes      | series tag  | consolidation         | CONSOLIDATION         | text      | text        |
| Yes      | series tag  | polling_place         | POLLING PLACE         | text      | text        |
| No       |             | polling_place_address | POLLING PLACE ADDRESS | text      | text        |
| Yes      | series tag  | ballot_group          | BALLOT GROUP          | text      | number      |
| Yes      | series tag  | poll_type             | POLL TYPE             | text      | text        |
| Yes      | series tag  | precinct              | PRECINCT              | text      | text        |
| Yes      | series tag  | handicap_access       | HANDICAP ACCESS       | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = polling_place_address
```

## Data Commands

```ls
series e:h5ci-ugt3 d:2015-01-01T00:00:00.000Z t:precinct=007-0004A t:poll_type=CLUB t:polling_place="MALIBU LAKE MOUNTAIN" t:ballot_group=2 t:council_district=0 t:handicap_access=Y t:consolidation=007-0004A m:row_number.h5ci-ugt3=1

series e:h5ci-ugt3 d:2015-01-01T00:00:00.000Z t:precinct=007-0004B t:poll_type=CLUB t:polling_place="MALIBU LAKE MOUNTAIN" t:ballot_group=2 t:council_district=0 t:handicap_access=Y t:consolidation=007-0004A m:row_number.h5ci-ugt3=2

series e:h5ci-ugt3 d:2015-01-01T00:00:00.000Z t:precinct=007-0004C t:poll_type=CLUB t:polling_place="MALIBU LAKE MOUNTAIN" t:ballot_group=2 t:council_district=0 t:handicap_access=Y t:consolidation=007-0004A m:row_number.h5ci-ugt3=3
```

## Meta Commands

```ls
metric m:row_number.h5ci-ugt3 p:long l:"Row Number"

entity e:h5ci-ugt3 l:"Election 2015 March Primary Polling Place List" t:url=https://data.lacity.org/api/views/h5ci-ugt3

property e:h5ci-ugt3 t:meta.view v:id=h5ci-ugt3 v:category="A Well Run City" v:averageRating=0 v:name="Election 2015 March Primary Polling Place List"

property e:h5ci-ugt3 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:h5ci-ugt3 t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:h5ci-ugt3 t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| council_district | consolidation | polling_place        | polling_place_address                       | ballot_group | poll_type | precinct  | handicap_access | 
| ================ | ============= | ==================== | =========================================== | ============ | ========= | ========= | =============== | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004A | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004B | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004C | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004D | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004E | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004H | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004J | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004K | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004L | Y               | 
| 0                | 007-0004A     | MALIBU LAKE MOUNTAIN | 29033 LAKE VISTA DR, AGOURA HILLS, CA 91301 | 2            | CLUB      | 007-0004M | Y               | 
```