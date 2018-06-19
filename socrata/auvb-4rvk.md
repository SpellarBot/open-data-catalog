# WDFW-Coded Wire Tag Fish Recoveries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-coded-wire-tag-fish-recoveries-7d4ef) |
| Metadata | [Link](https://data.wa.gov/api/views/auvb-4rvk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/auvb-4rvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/auvb-4rvk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | auvb-4rvk |
| Name | WDFW-Coded Wire Tag Fish Recoveries |
| Attribution | WDFW |
| Category | Natural Resources & Environment |
| Tags | wdfw, salmon, cwt |
| Created | 2012-12-04T22:09:36Z |
| Publication Date | 2014-12-30T19:12:18Z |

## Description

New data (unverified) within this dataset is preliminary and subject to change per the verification process.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                           | Data Type     | Render Type   |
| ======== | ============== | ======================== | ============================== | ============= | ============= |
| No       |                | returnyear               | Return Year                    | number        | number        |
| No       |                | verifieddate             | Verified Date                  | calendar_date | calendar_date |
| Yes      | series tag     | species                  | Species                        | text          | text          |
| Yes      | series tag     | run                      | Run                            | text          | text          |
| Yes      | series tag     | locationname             | Location Name                  | text          | text          |
| Yes      | series tag     | psc_code                 | PSC Code                       | text          | text          |
| Yes      | series tag     | locationcode             | Location Code                  | text          | text          |
| Yes      | series tag     | processproject           | Process Project                | text          | text          |
| Yes      | series tag     | recoverygeartype         | Recovery Gear Type             | text          | text          |
| Yes      | series tag     | psnet_recoverygeartype   | PSNET Recovery Gear Type       | text          | text          |
| Yes      | series tag     | baglabel                 | Bag Label                      | text          | text          |
| Yes      | series tag     | headnumber               | Head Number                    | text          | number        |
| Yes      | time           | recoverydate             | Recovery Date                  | calendar_date | calendar_date |
| Yes      | series tag     | sampletype               | Sample Type                    | text          | text          |
| Yes      | series tag     | tagresult                | Tag Result                     | text          | text          |
| Yes      | series tag     | tagcode                  | Tag Code                       | text          | text          |
| Yes      | numeric metric | forklength_cm            | Fork Length (cm)               | number        | number        |
| Yes      | series tag     | sex                      | Sex                            | text          | text          |
| Yes      | series tag     | fishertype               | Fisher Type                    | text          | text          |
| Yes      | series tag     | maturity                 | Maturity                       | text          | text          |
| Yes      | series tag     | mark                     | Mark                           | text          | text          |
| Yes      | series tag     | projectfishnumber        | Project Fish Number            | text          | text          |
| Yes      | series tag     | samplecardnumber         | Sample Card Number             | text          | text          |
| Yes      | series tag     | samplecardrecordnumber   | Sample Card Record Number      | text          | text          |
| Yes      | series tag     | scalecardnumber          | Scale Card Number              | text          | text          |
| Yes      | series tag     | scalecardlinenumber      | Scale Card Line Number         | text          | text          |
| Yes      | series tag     | otolithnumber            | Otolith Number                 | text          | text          |
| No       |                | broodyear                | Brood Year                     | number        | number        |
| No       |                | firstreleasedate         | First Release Date             | calendar_date | calendar_date |
| No       |                | lastreleasedate          | Last Release Date              | calendar_date | calendar_date |
| Yes      | series tag     | releasesite              | Release Site                   | text          | text          |
| Yes      | series tag     | rearinghatchery          | Rearing Hatchery               | text          | text          |
| Yes      | series tag     | stockname                | Stock Name                     | text          | text          |
| Yes      | series tag     | releaserun               | Release Run                    | text          | text          |
| Yes      | series tag     | releaseagency            | Release Agency                 | text          | text          |
| Yes      | series tag     | baglabelcomments         | Bag Label Comments             | text          | text          |
| Yes      | series tag     | fishcomments             | Fish Comments                  | text          | text          |
| Yes      | series tag     | releasecomments          | Release Comments               | text          | text          |
| Yes      | numeric metric | releasedtagadclipcnt     | Released Tag Adclip Count      | number        | number        |
| Yes      | numeric metric | releasedtagnoadclipcnt   | Released Tag No Adclip Count   | number        | number        |
| Yes      | numeric metric | releaseduntagadclipcnt   | Released Untag Adclip Count    | number        | number        |
| Yes      | numeric metric | releaseduntagnoadclipcnt | Released Untag No Adclip Count | number        | number        |
```

## Time Field

```ls
Value = recoverydate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = verifieddate,broodyear,firstreleasedate,lastreleasedate,returnyear
```

## Data Commands

```ls
series e:auvb-4rvk d:2012-09-11T00:00:00.000Z t:baglabel=17321 t:sex=Male t:releasesite="VOIGHT CR    10.0414" t:maturity=Adult t:species=Coho t:headnumber=37 t:releasecomments="BO=MIXED(HxW) RELEASED ON HIGH WATER" t:recoverygeartype="Mixed GN" t:processproject="WDFW Tag Lab" t:stockname="VOIGHT CR    10.0414" t:locationcode="100021 R" t:rearinghatchery="VOIGHTS CR HATCHERY" t:releaseagency=WDFW t:mark="AD Fin Clp" t:psnet_recoverygeartype=MixGNet t:sampletype="Random WDFW Sample" t:tagresult="Decoded Tag" t:tagcode=635384 t:locationname="PUYALLUP R   10.0021" t:psc_code="3F10511  100021 R" t:fishertype=Treaty m:releasedtagadclipcnt=44302 m:releasedtagnoadclipcnt=765 m:releaseduntagadclipcnt=765 m:releaseduntagnoadclipcnt=0 m:forklength_cm=63

series e:auvb-4rvk d:2012-09-11T00:00:00.000Z t:baglabel=17321 t:sex=Male t:releasesite="VOIGHT CR    10.0414" t:maturity=Adult t:species=Coho t:headnumber=38 t:releasecomments="BO=MIXED(HxW) RELEASED ON HIGH WATER" t:recoverygeartype="Mixed GN" t:processproject="WDFW Tag Lab" t:stockname="VOIGHT CR    10.0414" t:locationcode="100021 R" t:rearinghatchery="VOIGHTS CR HATCHERY" t:releaseagency=WDFW t:mark=Unmarked t:psnet_recoverygeartype=MixGNet t:sampletype="Random WDFW Sample" t:tagresult="Decoded Tag" t:tagcode=635383 t:locationname="PUYALLUP R   10.0021" t:psc_code="3F10511  100021 R" t:fishertype=Treaty m:releasedtagadclipcnt=0 m:releasedtagnoadclipcnt=43632 m:releaseduntagadclipcnt=0 m:releaseduntagnoadclipcnt=2422 m:forklength_cm=57

series e:auvb-4rvk d:2012-09-11T00:00:00.000Z t:baglabel=17321 t:sex=Female t:releasesite="COWSKULL ACCLIM POND" t:maturity=Adult t:species=Coho t:headnumber=39 t:releasecomments="CV = 1.24845E-05" t:recoverygeartype="Mixed GN" t:processproject="WDFW Tag Lab" t:stockname="VOIGHT CR    10.0414" t:locationcode="100021 R" t:rearinghatchery="VOIGHTS CR HATCHERY" t:releaseagency=PUYA t:mark="AD Fin Clp" t:releaserun="Type S" t:psnet_recoverygeartype=MixGNet t:sampletype="Random WDFW Sample" t:tagresult="Decoded Tag" t:tagcode=210927 t:locationname="PUYALLUP R   10.0021" t:psc_code="3F10511  100021 R" t:fishertype=Treaty m:releasedtagadclipcnt=98010 m:releasedtagnoadclipcnt=198 m:releaseduntagadclipcnt=992 m:releaseduntagnoadclipcnt=0 m:forklength_cm=55
```

## Meta Commands

```ls
metric m:forklength_cm p:integer l:"Fork Length (cm)" d:"Measured fork length in centimeters" t:dataTypeName=number

metric m:releasedtagadclipcnt p:integer l:"Released Tag Adclip Count" d:"Calculated number of tagged fish released with an adipose fin clip mark. Not an imported field from PSC." t:dataTypeName=number

metric m:releasedtagnoadclipcnt p:integer l:"Released Tag No Adclip Count" d:"Calculated number of tagged fish released without an adipose fin clip mark. Not an imported field from PSC." t:dataTypeName=number

metric m:releaseduntagadclipcnt p:integer l:"Released Untag Adclip Count" d:"Calculated number of untagged fish released with an adipose fin clip mark. Not an imported field from PSC." t:dataTypeName=number

metric m:releaseduntagnoadclipcnt p:integer l:"Released Untag No Adclip Count" d:"Calculated number of untagged fish released without an adipose fin clip mark. Not an imported field from PSC." t:dataTypeName=number

entity e:auvb-4rvk l:"WDFW-Coded Wire Tag Fish Recoveries" t:attribution=WDFW t:url=https://data.wa.gov/api/views/auvb-4rvk

property e:auvb-4rvk t:meta.view v:id=auvb-4rvk v:category="Natural Resources & Environment" v:averageRating=40 v:name="WDFW-Coded Wire Tag Fish Recoveries" v:attribution=WDFW

property e:auvb-4rvk t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:auvb-4rvk t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| returnyear | verifieddate        | species | run | locationname       | psc_code         | locationcode | processproject | recoverygeartype | psnet_recoverygeartype | baglabel | headnumber | recoverydate        | sampletype         | tagresult   | tagcode | forklength_cm | sex    | fishertype | maturity | mark       | projectfishnumber | samplecardnumber | samplecardrecordnumber | scalecardnumber | scalecardlinenumber | otolithnumber | broodyear | firstreleasedate    | lastreleasedate     | releasesite          | rearinghatchery      | stockname           | releaserun | releaseagency | baglabelcomments                | fishcomments | releasecomments                      | releasedtagadclipcnt | releasedtagnoadclipcnt | releaseduntagadclipcnt | releaseduntagnoadclipcnt | 
| ========== | =================== | ======= | === | ================== | ================ | ============ | ============== | ================ | ====================== | ======== | ========== | =================== | ================== | =========== | ======= | ============= | ====== | ========== | ======== | ========== | ================= | ================ | ====================== | =============== | =================== | ============= | ========= | =================== | =================== | ==================== | ==================== | =================== | ========== | ============= | =============================== | ============ | ==================================== | ==================== | ====================== | ====================== | ======================== | 
| 2012       | 2013-01-30T10:29:51 | Coho    |     | PUYALLUP R 10.0021 | 3F10511 100021 R | 100021 R     | WDFW Tag Lab   | Mixed GN         | MixGNet                | 17321    | 37         | 2012-09-11T00:00:00 | Random WDFW Sample | Decoded Tag | 635384  | 63            | Male   | Treaty     | Adult    | AD Fin Clp |                   |                  |                        |                 |                     |               | 2009      | 2011-04-01T00:00:00 | 2011-04-13T00:00:00 | VOIGHT CR 10.0414    | VOIGHTS CR HATCHERY  | VOIGHT CR 10.0414   |            | WDFW          |                                 |              | BO=MIXED(HxW) RELEASED ON HIGH WATER | 44302                | 765                    | 765                    | 0                        | 
| 2012       | 2013-01-30T10:29:58 | Coho    |     | PUYALLUP R 10.0021 | 3F10511 100021 R | 100021 R     | WDFW Tag Lab   | Mixed GN         | MixGNet                | 17321    | 38         | 2012-09-11T00:00:00 | Random WDFW Sample | Decoded Tag | 635383  | 57            | Male   | Treaty     | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 2009      | 2011-04-01T00:00:00 | 2011-04-13T00:00:00 | VOIGHT CR 10.0414    | VOIGHTS CR HATCHERY  | VOIGHT CR 10.0414   |            | WDFW          |                                 |              | BO=MIXED(HxW) RELEASED ON HIGH WATER | 0                    | 43632                  | 0                      | 2422                     | 
| 2012       | 2013-01-30T10:30:05 | Coho    |     | PUYALLUP R 10.0021 | 3F10511 100021 R | 100021 R     | WDFW Tag Lab   | Mixed GN         | MixGNet                | 17321    | 39         | 2012-09-11T00:00:00 | Random WDFW Sample | Decoded Tag | 210927  | 55            | Female | Treaty     | Adult    | AD Fin Clp |                   |                  |                        |                 |                     |               | 2009      | 2011-02-20T00:00:00 | 2011-02-22T00:00:00 | COWSKULL ACCLIM POND | VOIGHTS CR HATCHERY  | VOIGHT CR 10.0414   | Type S     | PUYA          |                                 |              | CV = 1.24845E-05                     | 98010                | 198                    | 992                    | 0                        | 
| 2001       | 2002-02-04T19:38:00 | Coho    |     | WALLACE R HATCHERY | 3F10308 070943 H | 070943 H     | WDFW Tag Lab   | Hat Rack         |                        | 027826   | 136        | 2001-12-04T00:00:00 | Random WDFW Sample | Decoded Tag | 631238  | 57            | Male   |            | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 1998      | 2000-05-02T00:00:00 | 2000-05-02T00:00:00 | WALLACE R 07.0940    | WALLACE R HATCHERY   | SKYKOMISH R 07.0012 |            | WDFW          | #270-MT CORE, #216-ROCK         |              |                                      | 0                    | 23049                  | 0                      | 422                      | 
| 2012       | 2013-01-30T10:30:12 | Coho    |     | PUYALLUP R 10.0021 | 3F10511 100021 R | 100021 R     | WDFW Tag Lab   | Mixed GN         | MixGNet                | 17321    | 40         | 2012-09-11T00:00:00 | Random WDFW Sample | Decoded Tag | 635383  | 57            | Male   | Treaty     | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 2009      | 2011-04-01T00:00:00 | 2011-04-13T00:00:00 | VOIGHT CR 10.0414    | VOIGHTS CR HATCHERY  | VOIGHT CR 10.0414   |            | WDFW          |                                 |              | BO=MIXED(HxW) RELEASED ON HIGH WATER | 0                    | 43632                  | 0                      | 2422                     | 
| 2012       | 2013-01-30T08:36:57 | Chinook |     | CLAY BANKS         | 3M11411 872081   | 112081       | WDFW Tag Lab   | Mar Spt          |                        | 08697    | 1          | 2012-07-02T00:00:00 | Random WDFW Sample | Decoded Tag | 635573  | 57            | Female |            | Adult    | AD Fin Clp |                   |                  |                        |                 |                     |               | 2009      | 2011-04-04T00:00:00 | 2011-07-11T00:00:00 | CASCADE R 03.1411    | MARBLEMOUNT HATCHERY | SKAGIT R 03.0176    | Spring     | WDFW          |                                 |              |                                      | 80500                | 0                      | 0                      | 0                        | 
| 1979       |                     | Coho    |     | MARINE AREA 3      | 3M32303          |              | WDFW Tag Lab   | Troll            |                        | 27181    | 1          | 1979-07-08T00:00:00 | Random WDFW Sample | Decoded Tag | 022124  | 48            |        |            |          | AD Fin Clp |                   |                  |                        |                 |                     |               | 1976      |                     |                     | R-Vedder R           |                      | S-Vedder R          |            | CDFO          |                                 |              |                                      | 36035                | 0                      | 115                    | 0                        | 
| 2001       | 2002-01-18T13:56:00 | Coho    |     | WALLACE R HATCHERY | 3F10308 070943 H | 070943 H     | WDFW Tag Lab   | Hat Rack         |                        | 027841   | 130        | 2001-12-03T00:00:00 | Random WDFW Sample | Decoded Tag | 631238  | 71            | Female |            | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 1998      | 2000-05-02T00:00:00 | 2000-05-02T00:00:00 | WALLACE R 07.0940    | WALLACE R HATCHERY   | SKYKOMISH R 07.0012 |            | WDFW          | #34-hook, #415-rock, #405-REMAG |              |                                      | 0                    | 23049                  | 0                      | 422                      | 
| 2001       | 2002-02-04T19:38:00 | Coho    |     | WALLACE R HATCHERY | 3F10308 070943 H | 070943 H     | WDFW Tag Lab   | Hat Rack         |                        | 027826   | 137        | 2001-12-04T00:00:00 | Random WDFW Sample | Decoded Tag | 631236  | 72            | Male   |            | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 1998      | 2000-05-02T00:00:00 | 2000-05-02T00:00:00 | WALLACE R 07.0940    | WALLACE R HATCHERY   | SKYKOMISH R 07.0012 |            | WDFW          | #270-MT CORE, #216-ROCK         |              |                                      | 0                    | 22524                  | 0                      | 413                      | 
| 2012       | 2013-01-30T10:30:22 | Coho    |     | PUYALLUP R 10.0021 | 3F10511 100021 R | 100021 R     | WDFW Tag Lab   | Mixed GN         | MixGNet                | 17321    | 41         | 2012-09-11T00:00:00 | Random WDFW Sample | Decoded Tag | 635383  | 52            | Female | Treaty     | Adult    | Unmarked   |                   |                  |                        |                 |                     |               | 2009      | 2011-04-01T00:00:00 | 2011-04-13T00:00:00 | VOIGHT CR 10.0414    | VOIGHTS CR HATCHERY  | VOIGHT CR 10.0414   |            | WDFW          |                                 |              | BO=MIXED(HxW) RELEASED ON HIGH WATER | 0                    | 43632                  | 0                      | 2422                     | 
```