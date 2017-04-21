# Election 2013 May General Polling Place List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2013-may-general-polling-place-list-018ea) |
| Metadata | [Link](https://data.lacity.org/api/views/rnxp-tz2v) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/rnxp-tz2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/rnxp-tz2v/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | rnxp-tz2v |
| Name | Election 2013 May General Polling Place List |
| Category | A Well Run City |
| Created | 2014-05-30T16:36:21Z |
| Publication Date | 2014-05-30T16:40:29Z |

## Description

Listing of the poll place locations for the 2013 May general election. Includes detail listing down to the established precincts with Council District indicator.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | council_district    | COUNCIL DISTRICT    | text      | number      |
| Yes      | series tag     | consolidation       | CONSOLIDATION       | text      | text        |
| Yes      | series tag     | polling_place       | POLLING PLACE       | text      | text        |
| Yes      | series tag     | ballot_group        | BALLOT GROUP        | text      | number      |
| Yes      | series tag     | poll_type           | POLL TYPE           | text      | text        |
| Yes      | series tag     | precinct            | PRECINCT            | text      | text        |
| Yes      | series tag     | handicap_access     | HANDICAP ACCESS     | text      | text        |
| Yes      | series tag     | vbm                 | VBM                 | text      | text        |
| Yes      | series tag     | sample_ballot_group | SAMPLE BALLOT GROUP | text      | number      |
| Yes      | numeric metric | voters              | VOTERS              | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rnxp-tz2v d:2013-01-01T00:00:00.000Z t:precinct=900-1196E t:poll_type=BUS. t:vbm=N t:polling_place="HOLLYWOOD HERITAGE" t:ballot_group=22 t:council_district=4 t:sample_ballot_group=107 t:handicap_access=Y t:consolidation=900-1196A m:voters=292

series e:rnxp-tz2v d:2013-01-01T00:00:00.000Z t:precinct=775-0071B t:poll_type=CHUR1 t:vbm=N t:polling_place="FIRST BAPTIST CHURCH OF B.H." t:ballot_group=5 t:council_district=0 t:sample_ballot_group=301 t:handicap_access=Y t:consolidation=775-0072A m:voters=206

series e:rnxp-tz2v d:2013-01-01T00:00:00.000Z t:precinct=095-0193E t:poll_type=CHUR1 t:vbm=N t:polling_place=SPIRITWORKS t:ballot_group=1 t:council_district=0 t:sample_ballot_group=301 t:handicap_access=Y t:consolidation=095-0194A m:voters=212
```

## Meta Commands

```ls
metric m:voters p:integer l:VOTERS t:dataTypeName=number

entity e:rnxp-tz2v l:"Election 2013 May General Polling Place List" t:url=https://data.lacity.org/api/views/rnxp-tz2v

property e:rnxp-tz2v t:meta.view v:id=rnxp-tz2v v:category="A Well Run City" v:averageRating=0 v:name="Election 2013 May General Polling Place List"

property e:rnxp-tz2v t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rnxp-tz2v t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:rnxp-tz2v t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| council_district | consolidation | polling_place                | ballot_group | poll_type | precinct  | handicap_access | vbm | sample_ballot_group | voters | 
| ================ | ============= | ============================ | ============ | ========= | ========= | =============== | === | =================== | ====== | 
| 4                | 900-1196A     | HOLLYWOOD HERITAGE           | 22           | BUS.      | 900-1196E | Y               | N   | 107                 | 292    | 
| 0                | 775-0072A     | FIRST BAPTIST CHURCH OF B.H. | 5            | CHUR1     | 775-0071B | Y               | N   | 301                 | 206    | 
| 0                | 095-0194A     | SPIRITWORKS                  | 1            | CHUR1     | 095-0193E | Y               | N   | 301                 | 212    | 
| 7                | 900-6224A     | GALPIN HONDA                 | 30           | BUS.      | 900-6224E | Y               | N   | 106                 | 181    | 
| 4                | 900-0231A     | MILLIKAN MIDDLE SCHOOL       | 21           | LAUSD     | 900-0231A | Y               | N   | 107                 | 141    | 
| 1                | 900-0833D     | PILLAR OF FIRE CHURCH HM     | 10           | CHURC     | 900-0477A | Y               | N   | 101                 | 236    | 
| 0                | 285-0005B     | MIDDLETON ST ELEMENTARY SCH  | 6            | LAUSD     | 285-0005J | Y               | N   | 301                 | 158    | 
| 0                | 090-0037A     | MT CALVARY LUTHERAN CHURCH   | 1            | CHURC     | 090-0037A | Y               | N   | 301                 | 163    | 
| 6                | 900-0805A     | VALERIO ST ELEMENTARY SCHOOL | 29           | LAUSD     | 900-2286A | Y               | N   | 102                 | 84     | 
| 0                | 285-0012A     | HUNTINGTON PARK REC CENTER   | 6            | CITYO     | 285-0014B | Y               | N   | 301                 | 132    | 
```