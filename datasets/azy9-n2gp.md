# LAPD Crime and Collision Raw Data for 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lapd-crime-and-collision-raw-data-for-2014) |
| Metadata | [Link](https://data.lacity.org/api/views/azy9-n2gp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/azy9-n2gp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/azy9-n2gp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | azy9-n2gp |
| Name | LAPD Crime and Collision Raw Data for 2014 |
| Category | A Safe City |
| Tags | police, crime, collisions, lapd, traffic, safety |
| Created | 2015-01-19T21:26:28Z |
| Publication Date | 2015-12-04T21:29:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| No       |                | date_rptd    | Date Rptd    | calendar_date | calendar_date |
| Yes      | series tag     | dr_no        | DR NO        | text          | text          |
| No       |                | date_occ     | DATE OCC     | calendar_date | calendar_date |
| No       |                | time_occ     | TIME OCC     | text          | text          |
| Yes      | series tag     | area         | AREA         | text          | text          |
| Yes      | series tag     | area_name    | AREA NAME    | text          | text          |
| No       |                | rd           | RD           | text          | text          |
| Yes      | numeric metric | crm_cd       | Crm Cd       | number        | text          |
| Yes      | series tag     | crm_cd_desc  | Crm Cd Desc  | text          | text          |
| Yes      | series tag     | status       | Status       | text          | text          |
| Yes      | series tag     | status_desc  | Status Desc  | text          | text          |
| Yes      | series tag     | location     | LOCATION     | text          | text          |
| Yes      | series tag     | cross_street | Cross Street | text          | text          |
```

## Time Field

```ls
Value = date_occ-time_occ
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-HHmm
```

## Series Fields

```ls
Excluded Fields = date_occ,rd,date_rptd,time_occ
```

## Data Commands

```ls
series e:azy9-n2gp d:2014-12-30T18:55:00.000Z t:crm_cd_desc=ROBBERY t:area=01 t:location="7TH                          ST" t:status=IC t:cross_street="MAPLE                        AV" t:status_desc="Invest Cont" t:area_name=Central t:dr_no=140101527 m:crm_cd=210

series e:azy9-n2gp d:2014-12-31T06:05:00.000Z t:crm_cd_desc="ASSAULT WITH DEADLY WEAPON, AGGRAVATED ASSAULT" t:area=01 t:location="6TH                          ST" t:status=AO t:cross_street="SAN JULIAN                   ST" t:status_desc="Adult Other" t:area_name=Central t:dr_no=140101528 m:crm_cd=230

series e:azy9-n2gp d:2014-12-30T18:55:00.000Z t:crm_cd_desc=ROBBERY t:area=01 t:location="7TH                          ST" t:status=IC t:cross_street="MAPLE                        AV" t:status_desc="Invest Cont" t:area_name=Central t:dr_no=140104069 m:crm_cd=210
```

## Meta Commands

```ls
metric m:crm_cd p:integer l:"Crm Cd" t:dataTypeName=number

entity e:azy9-n2gp l:"LAPD Crime and Collision Raw Data for 2014" t:url=https://data.lacity.org/api/views/azy9-n2gp

property e:azy9-n2gp t:meta.view v:id=azy9-n2gp v:category="A Safe City" v:averageRating=0 v:name="LAPD Crime and Collision Raw Data for 2014"

property e:azy9-n2gp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:azy9-n2gp t:meta.view.owner v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:displayName="LAPD OpenData"

property e:azy9-n2gp t:meta.view.tableauthor v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"
```