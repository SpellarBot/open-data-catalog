# Election 2015 May General Polling Place List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2015-may-general-polling-place-list) |
| Metadata | [Link](https://data.lacity.org/api/views/i5g3-9vuz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/i5g3-9vuz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/i5g3-9vuz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | i5g3-9vuz |
| Name | Election 2015 May General Polling Place List |
| Category | A Well Run City |
| Created | 2015-06-16T20:51:16Z |
| Publication Date | 2015-06-16T20:55:39Z |

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
series e:i5g3-9vuz d:2015-01-01T00:00:00.000Z t:precinct=045-0001A t:poll_type=RECRE t:polling_place="ATHENS PARK" t:ballot_group=3 t:council_district=0 t:handicap_access=Y t:consolidation=045-0001A m:row_number.i5g3-9vuz=1

series e:i5g3-9vuz d:2015-01-01T00:00:00.000Z t:precinct=045-0001B t:poll_type=RECRE t:polling_place="ATHENS PARK" t:ballot_group=3 t:council_district=0 t:handicap_access=Y t:consolidation=045-0001A m:row_number.i5g3-9vuz=2

series e:i5g3-9vuz d:2015-01-01T00:00:00.000Z t:precinct=045-0001C t:poll_type=RECRE t:polling_place="ATHENS PARK" t:ballot_group=3 t:council_district=0 t:handicap_access=Y t:consolidation=045-0001A m:row_number.i5g3-9vuz=3
```

## Meta Commands

```ls
metric m:row_number.i5g3-9vuz p:long l:"Row Number"

entity e:i5g3-9vuz l:"Election 2015 May General Polling Place List" t:url=https://data.lacity.org/api/views/i5g3-9vuz

property e:i5g3-9vuz t:meta.view v:id=i5g3-9vuz v:category="A Well Run City" v:averageRating=0 v:name="Election 2015 May General Polling Place List"

property e:i5g3-9vuz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:i5g3-9vuz t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:i5g3-9vuz t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| council_district | consolidation | polling_place | polling_place_address                   | ballot_group | poll_type | precinct  | handicap_access | 
| ================ | ============= | ============= | ======================================= | ============ | ========= | ========= | =============== | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0001A | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0001B | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0001C | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002A | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002B | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002C | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002D | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002F | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002G | Y               | 
| 0                | 045-0001A     | ATHENS PARK   | 12603 S BROADWAY, LOS ANGELES, CA 90061 | 3            | RECRE     | 045-0002H | Y               | 
```