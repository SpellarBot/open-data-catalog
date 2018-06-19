# Open Data ARR 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-arr-2015) |
| Metadata | [Link](https://data.lacity.org/api/views/d4vt-ypi8) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/d4vt-ypi8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/d4vt-ypi8/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | d4vt-ypi8 |
| Name | Open Data ARR 2015 |
| Category | A Safe City |
| Tags | lapd, arrests |
| Created | 2016-03-10T17:30:42Z |
| Publication Date | 2016-04-28T22:56:37Z |

## Description

Arrests made in the City of Los Angeles

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | time           | arst_date   | ARST DATE   | calendar_date | calendar_date |
| Yes      | series tag     | time        | TIME        | text          | text          |
| Yes      | series tag     | rpt_id      | RPT_ID      | text          | text          |
| Yes      | series tag     | area        | AREA        | text          | text          |
| Yes      | series tag     | area_desc   | AREA_DESC   | text          | text          |
| No       |                | rd          | RD          | text          | text          |
| Yes      | numeric metric | age         | AGE         | number        | text          |
| Yes      | series tag     | sex_cd      | SEX_CD      | text          | text          |
| Yes      | series tag     | descent_cd  | DESCENT_CD  | text          | text          |
| Yes      | series tag     | chrg_grp_cd | CHRG_GRP_CD | text          | text          |
| Yes      | series tag     | grp_desc    | GRP_DESC    | text          | text          |
| Yes      | series tag     | arst_typ_cd | ARST_TYP_CD | text          | text          |
| Yes      | series tag     | charge      | CHARGE      | text          | text          |
| Yes      | series tag     | chrg_desc   | CHRG_DESC   | text          | text          |
| Yes      | series tag     | location    | LOCATION    | text          | text          |
| Yes      | series tag     | crsst       | CRSST       | text          | text          |
```

## Time Field

```ls
Value = arst_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rd
```

## Data Commands

```ls
series e:d4vt-ypi8 d:2015-12-31T00:00:00.000Z t:grp_desc="Driving Under Influence" t:arst_typ_cd=M t:area_desc=Pacific t:descent_cd=H t:time=2345 t:charge=23152(A)VC t:area=14 t:location="3500    MCLAUGHLIN                   AV" t:chrg_grp_cd=22 t:rpt_id=4538991 t:sex_cd=M t:chrg_desc="DRUNK DRIVING ALCOHOL/DRUGS" m:age=43

series e:d4vt-ypi8 d:2015-12-31T00:00:00.000Z t:grp_desc="Aggravated Assault" t:arst_typ_cd=F t:area_desc=Central t:descent_cd=W t:time=2330 t:charge=273.5(A)PC t:area=01 t:location="900    FIGUEROA                     TR" t:chrg_grp_cd=04 t:rpt_id=4538996 t:sex_cd=M t:chrg_desc="CORPORAL INJURY ON SPOUSE/COHABITANT/ETC" m:age=27

series e:d4vt-ypi8 d:2015-12-31T00:00:00.000Z t:grp_desc="Narcotic Drug Laws" t:arst_typ_cd=M t:area_desc=Hollywood t:descent_cd=W t:time=2320 t:charge=11350(A)HS t:area=06 t:location="6300    HOLLYWOOD                    BL" t:chrg_grp_cd=16 t:rpt_id=4539142 t:sex_cd=M t:chrg_desc="POSSESSION OF CONTROLLED SUBSTANCE" m:age=31
```

## Meta Commands

```ls
metric m:age p:integer l:AGE t:dataTypeName=number

entity e:d4vt-ypi8 l:"Open Data ARR 2015" t:url=https://data.lacity.org/api/views/d4vt-ypi8

property e:d4vt-ypi8 t:meta.view v:id=d4vt-ypi8 v:category="A Safe City" v:averageRating=0 v:name="Open Data ARR 2015"

property e:d4vt-ypi8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:d4vt-ypi8 t:meta.view.owner v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"

property e:d4vt-ypi8 t:meta.view.tableauthor v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"
```

## Top Records

```ls
| arst_date           | time | rpt_id  | area | area_desc   | rd   | age | sex_cd | descent_cd | chrg_grp_cd | grp_desc                       | arst_typ_cd | charge      | chrg_desc                                 | location           | crsst        | 
| =================== | ==== | ======= | ==== | =========== | ==== | === | ====== | ========== | =========== | ============================== | =========== | =========== | ========================================= | ================== | ============ | 
| 2015-12-31T00:00:00 | 2345 | 4538991 | 14   | Pacific     | 1435 | 43  | M      | H          | 22          | Driving Under Influence        | M           | 23152(A)VC  | DRUNK DRIVING ALCOHOL/DRUGS               | 3500 MCLAUGHLIN AV |              | 
| 2015-12-31T00:00:00 | 2330 | 4538996 | 01   | Central     | 0101 | 27  | M      | W          | 04          | Aggravated Assault             | F           | 273.5(A)PC  | CORPORAL INJURY ON SPOUSE/COHABITANT/ETC  | 900 FIGUEROA TR    |              | 
| 2015-12-31T00:00:00 | 2320 | 4539142 | 06   | Hollywood   | 0646 | 31  | M      | W          | 16          | Narcotic Drug Laws             | M           | 11350(A)HS  | POSSESSION OF CONTROLLED SUBSTANCE        | 6300 HOLLYWOOD BL  |              | 
| 2015-12-31T00:00:00 | 2319 | 4538947 | 21   | Topanga     | 2189 | 28  | M      | H          | 22          | Driving Under Influence        | M           | 23152(A)VC  | DRUNK DRIVING ALCOHOL/DRUGS               | VENTURA FY         | WINNETKA     | 
| 2015-12-31T00:00:00 | 2316 | 4538938 | 17   | Devonshire  | 1739 | 29  | M      | B          | 16          | Narcotic Drug Laws             | F           | 11351HS     | POSSESS/PURCHASE CONTROLLED SUBS FOR SALE | 10800 WOODLEY AV   |              | 
| 2015-12-31T00:00:00 | 2315 | 4539107 | 02   | Rampart     | 0201 | 27  | M      | H          | 08          | Other Assaults                 | M           | 148(A)(1)PC | OBSTRUCT/ETC PUB OFCR/ETC                 | COMMONWEALTH       | SANTA MONICA | 
| 2015-12-31T00:00:00 | 2310 | 4538978 | 13   | Newton      | 1362 | 43  | M      | B          | 12          | Weapon (carry/poss)            | F           | 29800(A)1PC | POSS F/ARM BY CONVICTED FELON/ADDICT/ETC  | 51ST ST            | AVALON       | 
| 2015-12-31T00:00:00 | 2310 | 4538979 | 10   | West Valley | 1039 | 62  | F      | W          | 22          | Driving Under Influence        | M           | 23152(A)VC  | DRUNK DRIVING ALCOHOL/DRUGS               | VANOWEN            | WOODLEY AV   | 
| 2015-12-31T00:00:00 | 2310 | 4538936 | 06   | Hollywood   | 0663 | 27  | M      | H          | 23          | Moving Traffic Violations      | M           | 14601.2AVC  | DRIVE W/LIC SUSPEND/REVOKE 4 DRUGS/ALCOHL | SEWARD             | WILLOUGHBY   | 
| 2015-12-31T00:00:00 | 2310 | 4539025 | 02   | Rampart     | 0233 | 65  | M      | O          | 24          | Miscellaneous Other Violations | M           | 594(A)PC    | VANDALISM                                 | CARONDELET         | TEMPLE       | 
```