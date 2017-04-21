# Election 2013 March Primary Polling Place List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2013-march-primary-polling-place-list-e9a64) |
| Metadata | [Link](https://data.lacity.org/api/views/hkig-2qjq) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/hkig-2qjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/hkig-2qjq/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | hkig-2qjq |
| Name | Election 2013 March Primary Polling Place List |
| Category | A Well Run City |
| Created | 2014-05-30T15:03:56Z |
| Publication Date | 2014-05-30T16:30:20Z |

## Description

Listing of the poll place locations for the 2013 March primary election. Includes detail listing down to the established precincts with Council District indicator.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | council_distrct | COUNCIL DISTRCT | number    | number      |
| Yes      | series tag     | consolidation   | CONSOLIDATION   | text      | text        |
| Yes      | series tag     | polling_place   | POLLING PLACE   | text      | text        |
| Yes      | series tag     | ballot_group    | BALLOT GROUP    | text      | number      |
| Yes      | series tag     | poll_type       | POLL TYPE       | text      | text        |
| Yes      | series tag     | precinct        | PRECINCT        | text      | text        |
| Yes      | series tag     | handicap_access | HANDICAP ACCESS | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hkig-2qjq d:2013-01-01T00:00:00.000Z t:precinct=900-0543D t:poll_type=CHUR1 t:polling_place="FIRST SOUTHERN BAPTIST CHURCH" t:ballot_group=14 t:handicap_access=Y t:consolidation=900-0531A m:council_distrct=2

series e:hkig-2qjq d:2013-01-01T00:00:00.000Z t:precinct=767-0023A t:poll_type=CHUR1 t:polling_place="FAITH UNITED METHODIST CHURCH" t:ballot_group=3 t:handicap_access=Y t:consolidation=767-0023A m:council_distrct=0

series e:hkig-2qjq d:2013-01-01T00:00:00.000Z t:precinct=445-0013D t:poll_type=BUS. t:polling_place="AMF BEVERLY LANES" t:ballot_group=1 t:handicap_access=Y t:consolidation=445-0014A m:council_distrct=0
```

## Meta Commands

```ls
metric m:council_distrct p:integer l:"COUNCIL DISTRCT" t:dataTypeName=number

entity e:hkig-2qjq l:"Election 2013 March Primary Polling Place List" t:url=https://data.lacity.org/api/views/hkig-2qjq

property e:hkig-2qjq t:meta.view v:id=hkig-2qjq v:category="A Well Run City" v:averageRating=0 v:name="Election 2013 March Primary Polling Place List"

property e:hkig-2qjq t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hkig-2qjq t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:hkig-2qjq t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| council_distrct | consolidation | polling_place                 | ballot_group | poll_type | precinct  | handicap_access | 
| =============== | ============= | ============================= | ============ | ========= | ========= | =============== | 
| 2               | 900-0531A     | FIRST SOUTHERN BAPTIST CHURCH | 14           | CHUR1     | 900-0543D | Y               | 
| 0               | 767-0023A     | FAITH UNITED METHODIST CHURCH | 3            | CHUR1     | 767-0023A | Y               | 
| 0               | 445-0014A     | AMF BEVERLY LANES             | 1            | BUS.      | 445-0013D | Y               | 
| 11              | 900-1374A     | FIRE STATION #69              | 43           | MISCP     | 900-5925B | Y               | 
| 8               | 900-2132A     | RESIDENCE                     | 32           | RES       | 900-0651C | Y               | 
| 2               | 900-0116A     | KRIESTEL BANQUET HALL         | 14           | BUS.      | 900-0116G | Y               | 
| 5               | 900-2280A     | WRITERS GUILD OF AMERICA      | 26           | BUS.      | 900-2280E | Y               | 
| 0               | 200-0005A     | CASA LUCERNA                  | 7            | SRHMS     | 200-0027A | Y               | 
| 8               | 900-0296A     | COMMUNITY CHURCH OF L A       | 32           | CHUR1     | 900-2510B | Y               | 
| 7               | 900-0069A     | RESIDENCE                     | 31           | RES       | 900-0069C | Y               | 
```