# LAPD Crime and Collision Raw Data for 2014

## Dataset

* [Dataset URL](https://data.lacity.org/api/views/azy9-n2gp/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/lapd-crime-and-collision-raw-data-for-2014)
* [Metadata URL](https://data.lacity.org/api/views/azy9-n2gp)
* Id = azy9-n2gp
* Name = LAPD Crime and Collision Raw Data for 2014
* Category = A Safe City
* Tags = [police, crime, collisions, lapd, traffic, safety]
* Created = 2015-01-19T21:26:28Z
* Publication Date = 2015-12-04T21:29:36Z
* Rows Updated = 2015-01-19T21:35:52Z

## Description



## Columns

```ls
| Name         | Field Name   | Data Type     | Render Type   | Schema Type    | Included | 
| ============ | ============ | ============= | ============= | ============== | ======== | 
| Date Rptd    | date_rptd    | calendar_date | calendar_date | time           | Yes      | 
| DR NO        | dr_no        | number        | text          | numeric metric | Yes      | 
| DATE OCC     | date_occ     | calendar_date | calendar_date |                | No       | 
| TIME OCC     | time_occ     | number        | text          | numeric metric | Yes      | 
| AREA         | area         | number        | text          | numeric metric | Yes      | 
| AREA NAME    | area_name    | text          | text          | series tag     | Yes      | 
| RD           | rd           | number        | text          |                | No       | 
| Crm Cd       | crm_cd       | number        | text          | numeric metric | Yes      | 
| Crm Cd Desc  | crm_cd_desc  | text          | text          | series tag     | Yes      | 
| Status       | status       | text          | text          | series tag     | Yes      | 
| Status Desc  | status_desc  | text          | text          | series tag     | Yes      | 
| LOCATION     | location     | text          | text          | series tag     | Yes      | 
| Cross Street | cross_street | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = date_rptd
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = date_occ,rd
Annotation Fields = 
```

## Data Commands

```ls
series e:azy9-n2gp d:2014-12-31T00:00:00.000Z t:crm_cd_desc=ROBBERY t:location="7TH                          ST" t:status=IC t:cross_street="MAPLE                        AV" t:status_desc="Invest Cont" t:area_name=Central m:area=1 m:time_occ=1855 m:crm_cd=210 m:dr_no=140101527

series e:azy9-n2gp d:2014-12-31T00:00:00.000Z t:crm_cd_desc="ASSAULT WITH DEADLY WEAPON, AGGRAVATED ASSAULT" t:location="6TH                          ST" t:status=AO t:cross_street="SAN JULIAN                   ST" t:status_desc="Adult Other" t:area_name=Central m:area=1 m:time_occ=605 m:crm_cd=230 m:dr_no=140101528

series e:azy9-n2gp d:2014-12-31T00:00:00.000Z t:crm_cd_desc=ROBBERY t:location="7TH                          ST" t:status=IC t:cross_street="MAPLE                        AV" t:status_desc="Invest Cont" t:area_name=Central m:area=1 m:time_occ=1855 m:crm_cd=210 m:dr_no=140104069
```

## Meta Commands

```ls
metric m:dr_no p:integer l:"DR NO" t:dataTypeName=number

metric m:time_occ p:integer l:"TIME OCC" t:dataTypeName=number

metric m:area p:integer l:AREA t:dataTypeName=number

metric m:crm_cd p:integer l:"Crm Cd" t:dataTypeName=number

entity e:azy9-n2gp l:"LAPD Crime and Collision Raw Data for 2014" t:url=https://data.lacity.org/api/views/azy9-n2gp

property e:azy9-n2gp t:meta.view d:2017-03-08T01:44:16.035Z v:id=azy9-n2gp v:category="A Safe City" v:averageRating=0 v:name="LAPD Crime and Collision Raw Data for 2014"

property e:azy9-n2gp t:meta.view.license d:2017-03-08T01:44:16.035Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:azy9-n2gp t:meta.view.owner d:2017-03-08T01:44:16.035Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"

property e:azy9-n2gp t:meta.view.tableauthor d:2017-03-08T01:44:16.035Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"
```