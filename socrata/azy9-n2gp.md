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

## Top Records

```ls
| date_rptd           | dr_no     | date_occ            | time_occ | area | area_name | rd   | crm_cd | crm_cd_desc                                    | status | status_desc | location           | cross_street  | 
| =================== | ========= | =================== | ======== | ==== | ========= | ==== | ====== | ============================================== | ====== | =========== | ================== | ============= | 
| 2014-12-31T00:00:00 | 140101527 | 2014-12-30T00:00:00 | 1855     | 01   | Central   | 0176 | 210    | ROBBERY                                        | IC     | Invest Cont | 7TH ST             | MAPLE AV      | 
| 2014-12-31T00:00:00 | 140101528 | 2014-12-31T00:00:00 | 0605     | 01   | Central   | 0156 | 230    | ASSAULT WITH DEADLY WEAPON, AGGRAVATED ASSAULT | AO     | Adult Other | 6TH ST             | SAN JULIAN ST | 
| 2014-12-31T00:00:00 | 140104069 | 2014-12-30T00:00:00 | 1855     | 01   | Central   | 0176 | 210    | ROBBERY                                        | IC     | Invest Cont | 7TH ST             | MAPLE AV      | 
| 2014-12-31T00:00:00 | 140127976 | 2014-08-25T00:00:00 | 1200     | 01   | Central   | 0157 | 649    | DOCUMENT FORGERY / STOLEN FELONY               | IC     | Invest Cont | 500 S SAN PEDRO ST |               | 
| 2014-12-31T00:00:00 | 140128170 | 2014-12-30T00:00:00 | 1630     | 01   | Central   | 0161 | 442    | SHOPLIFTING - PETTY THEFT ($950 & UNDER)       | IC     | Invest Cont | 700 S FIGUEROA ST  |               | 
| 2014-12-31T00:00:00 | 140128171 | 2014-12-30T00:00:00 | 2150     | 01   | Central   | 0142 | 997    | TRAFFIC DR #                                   | IC     | Invest Cont | HOPE ST            | GRAND AV      | 
| 2014-12-31T00:00:00 | 140128172 | 2014-12-30T00:00:00 | 1910     | 01   | Central   | 0192 | 997    | TRAFFIC DR #                                   | IC     | Invest Cont | HOPE ST            | VENICE BL     | 
| 2014-12-31T00:00:00 | 140128178 | 2014-12-30T00:00:00 | 1400     | 01   | Central   | 0143 | 442    | SHOPLIFTING - PETTY THEFT ($950 & UNDER)       | IC     | Invest Cont | 400 S BROADWAY     |               | 
| 2014-12-31T00:00:00 | 140128179 | 2014-12-27T00:00:00 | 1955     | 01   | Central   | 0111 | 997    | TRAFFIC DR #                                   | IC     | Invest Cont | MAIN ST            | ARCADIA ST    | 
| 2014-12-31T00:00:00 | 140128180 | 2014-12-30T00:00:00 | 1200     | 01   | Central   | 0176 | 350    | THEFT, PERSON                                  | IC     | Invest Cont | 7TH ST             | WALL ST       | 
```