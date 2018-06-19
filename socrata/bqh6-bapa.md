# Museum Universe Data File FY 2015 Q1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/museum-universe-data-file-fy-2015-q1) |
| Metadata | [Link](https://data.imls.gov/api/views/bqh6-bapa) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/bqh6-bapa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/bqh6-bapa/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | bqh6-bapa |
| Name | Museum Universe Data File FY 2015 Q1 |
| Attribution | IMLS |
| Category | Museum Universe Data File |
| Tags | museums, mudf |
| Created | 2015-02-10T21:31:43Z |
| Publication Date | 2016-05-19T16:04:00Z |

## Description

Browse a list of known museums and related organizations in the United States as of the first quarter of FY 2015. This list contains descriptive information about museums in the 50 states and the District of Columbia based on public records and administrative data.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | mid        | MID        | text      | text        |
| Yes      | series tag     | legalname  | LEGALNAME  | text      | text        |
| Yes      | series tag     | altname    | ALTNAME    | text      | text        |
| Yes      | series tag     | akadba     | AKADBA     | text      | text        |
| Yes      | series tag     | commonname | COMMONNAME | text      | text        |
| Yes      | series tag     | phone      | PHONE      | text      | text        |
| Yes      | series tag     | weburl     | WEBURL     | text      | text        |
| Yes      | series tag     | discipl    | DISCIPL    | text      | text        |
| Yes      | series tag     | ein        | EIN        | text      | text        |
| Yes      | series tag     | nteec      | NTEEC      | text      | text        |
| Yes      | numeric metric | taxper     | TAXPER     | number    | number      |
| Yes      | numeric metric | income     | INCOME     | money     | money       |
| Yes      | numeric metric | revenue    | REVENUE    | money     | money       |
| Yes      | numeric metric | incomecd   | INCOMECD   | number    | number      |
| Yes      | numeric metric | aamreg     | AAMREG     | number    | number      |
| Yes      | numeric metric | locale4    | LOCALE4    | number    | number      |
| Yes      | series tag     | fipsst     | FIPSST     | text      | number      |
| Yes      | series tag     | fipsco     | FIPSCO     | text      | number      |
| Yes      | numeric metric | tract      | TRACT      | number    | number      |
| Yes      | series tag     | block      | BLOCK      | text      | number      |
| Yes      | series tag     | fipsmin    | FIPSMIN    | text      | number      |
| Yes      | series tag     | fipsplac   | FIPSPLAC   | text      | number      |
| Yes      | series tag     | cbsacode   | CBSACODE   | text      | number      |
| Yes      | numeric metric | metrodiv   | METRODIV   | number    | number      |
| Yes      | numeric metric | microf     | MICROF     | number    | number      |
| Yes      | numeric metric | irs990_f   | IRS990_F   | number    | number      |
| Yes      | numeric metric | imlsad_f   | IMLSAD_F   | number    | number      |
| Yes      | numeric metric | fct3p_f    | FCT3P_F    | number    | number      |
| Yes      | numeric metric | pfnd_f     | PFND_F     | number    | number      |
| Yes      | numeric metric | user_f     | USER_F     | number    | number      |
| Yes      | numeric metric | opstatus_f | OPSTATUS_F | number    | number      |
| Yes      | numeric metric | review_f   | REVIEW_F   | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bqh6-bapa d:2015-01-01T00:00:00.000Z t:fipsplac=3076 t:phone=3345012963 t:discipl=GMU t:weburl="HTTP://WWW.AUBURNALABAMA.ORG/ARTS/DEFAULT.ASPX%3FPAGEID=449" t:legalname="JAN DEMPSEY ARTS CENTER" t:cbsacode=12220 t:block=3003 t:commonname="JAN DEMPSEY ARTS CENTER" t:fipsmin=90162 t:mid=8400100045 t:fipsst=1 t:fipsco=81 m:locale4=1 m:fct3p_f=1 m:microf=0 m:user_f=0 m:review_f=0 m:tract=40902 m:pfnd_f=0 m:imlsad_f=0 m:aamreg=3 m:irs990_f=0

series e:bqh6-bapa d:2015-01-01T00:00:00.000Z t:fipsplac=32272 t:phone=2519681473 t:discipl=GMU t:legalname="GULF SHORES MUSEUM" t:cbsacode=19300 t:block=3036 t:commonname="GULF SHORES MUSEUM" t:fipsmin=91152 t:mid=8400100047 t:fipsst=1 t:fipsco=3 m:locale4=3 m:fct3p_f=1 m:microf=0 m:user_f=0 m:review_f=0 m:tract=11407 m:pfnd_f=0 m:imlsad_f=0 m:aamreg=3 m:irs990_f=0

series e:bqh6-bapa d:2015-01-01T00:00:00.000Z t:fipsplac=57048 t:phone=3347417776 t:discipl=GMU t:legalname="GEORGE P MANN OUTDOORS IN" t:cbsacode=12220 t:block=3015 t:commonname="GEORGE P MANN OUTDOORS IN" t:fipsmin=90162 t:mid=8400100048 t:fipsst=1 t:fipsco=81 m:locale4=4 m:fct3p_f=1 m:microf=0 m:user_f=0 m:review_f=1 m:tract=41700 m:pfnd_f=0 m:imlsad_f=0 m:aamreg=3 m:irs990_f=0
```

## Meta Commands

```ls
metric m:taxper p:integer l:TAXPER t:dataTypeName=number

metric m:income p:long l:INCOME t:dataTypeName=money

metric m:revenue p:long l:REVENUE t:dataTypeName=money

metric m:incomecd p:integer l:INCOMECD t:dataTypeName=number

metric m:aamreg p:integer l:AAMREG t:dataTypeName=number

metric m:locale4 p:integer l:LOCALE4 t:dataTypeName=number

metric m:tract p:integer l:TRACT t:dataTypeName=number

metric m:metrodiv p:integer l:METRODIV t:dataTypeName=number

metric m:microf p:integer l:MICROF t:dataTypeName=number

metric m:irs990_f p:integer l:IRS990_F t:dataTypeName=number

metric m:imlsad_f p:integer l:IMLSAD_F t:dataTypeName=number

metric m:fct3p_f p:integer l:FCT3P_F t:dataTypeName=number

metric m:pfnd_f p:integer l:PFND_F t:dataTypeName=number

metric m:user_f p:integer l:USER_F t:dataTypeName=number

metric m:opstatus_f p:integer l:OPSTATUS_F t:dataTypeName=number

metric m:review_f p:integer l:REVIEW_F t:dataTypeName=number

entity e:bqh6-bapa l:"Museum Universe Data File FY 2015 Q1" t:attribution=IMLS t:url=https://data.imls.gov/api/views/bqh6-bapa

property e:bqh6-bapa t:meta.view v:id=bqh6-bapa v:category="Museum Universe Data File" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/museum-universe-data-file v:averageRating=0 v:name="Museum Universe Data File FY 2015 Q1" v:attribution=IMLS

property e:bqh6-bapa t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:bqh6-bapa t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:bqh6-bapa t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:bqh6-bapa t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| mid        | legalname                               | altname                                 | akadba | commonname                              | phone      | weburl                                                                              | discipl | ein | nteec | taxper | income | revenue | incomecd | aamreg | locale4 | fipsst | fipsco | tract  | block | fipsmin | fipsplac | cbsacode | metrodiv | microf | irs990_f | imlsad_f | fct3p_f | pfnd_f | user_f | opstatus_f | review_f | 
| ========== | ======================================= | ======================================= | ====== | ======================================= | ========== | =================================================================================== | ======= | === | ===== | ====== | ====== | ======= | ======== | ====== | ======= | ====== | ====== | ====== | ===== | ======= | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ====== | ====== | ========== | ======== | 
| 8400100045 | JAN DEMPSEY ARTS CENTER                 |                                         |        | JAN DEMPSEY ARTS CENTER                 | 3345012963 | HTTP://WWW.AUBURNALABAMA.ORG/ARTS/DEFAULT.ASPX%3FPAGEID=449                         | GMU     |     |       |        |        |         |          | 3      | 1       | 1      | 81     | 40902  | 3003  | 90162   | 3076     | 12220    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 0        | 
| 8400100047 | GULF SHORES MUSEUM                      |                                         |        | GULF SHORES MUSEUM                      | 2519681473 |                                                                                     | GMU     |     |       |        |        |         |          | 3      | 3       | 1      | 3      | 11407  | 3036  | 91152   | 32272    | 19300    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 0        | 
| 8400100048 | GEORGE P MANN OUTDOORS IN               |                                         |        | GEORGE P MANN OUTDOORS IN               | 3347417776 |                                                                                     | GMU     |     |       |        |        |         |          | 3      | 4       | 1      | 81     | 41700  | 3015  | 90162   | 57048    | 12220    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 1        | 
| 8400100049 | GREENE MUSEUM                           |                                         |        | GREENE MUSEUM                           | 3342985413 |                                                                                     | GMU     |     |       |        |        |         |          | 3      | 2       | 1      | 113    | 30200  | 1010  | 92538   | 59472    | 17980    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 1        | 
| 8400100050 | FOLEY MUSEUM AND ARCHIVES               |                                         |        | FOLEY MUSEUM AND ARCHIVES               | 2519431818 | HTTP://WWW.FOLEYRAILROADMUSEUM.COM                                                  | GMU     |     |       |        |        |         |          | 3      | 3       | 1      | 3      | 11501  | 1130  | 91152   | 26992    | 19300    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 0        | 
| 8400100051 | GUNTERSVILLE MUSEUM                     |                                         |        | GUNTERSVILLE MUSEUM                     | 2565717597 | HTTP://WWW.GUNTERSVILLEMUSEUM.ORG                                                   | GMU     |     |       |        |        |         |          | 3      | 3       | 1      | 95     | 30702  | 3042  | 91458   | 32416    | 10700    |          | 1      | 0        | 0        | 1       | 0      | 0      |            | 0        | 
| 8400100052 | GUNTERSVILLE MUSEUM AND CULTURAL CENTER | GUNTERSVILLE MUSEUM AND CULTURAL CENTER |        | GUNTERSVILLE MUSEUM AND CULTURAL CENTER | 2055717597 |                                                                                     | GMU     |     |       |        |        |         |          | 3      | 3       | 1      | 95     | 30702  | 3042  | 91458   | 32416    | 10700    |          | 1      | 0        | 1        | 0       | 0      | 0      |            | 0        | 
| 8400100053 | FITZGERALD AND FITZGERALD MUSEUM        |                                         |        | FITZGERALD AND FITZGERALD MUSEUM        | 3342644222 | HTTP://WWW.FITZGERALDMUSEUM.NET                                                     | GMU     |     |       |        |        |         |          | 3      | 1       | 1      | 101    | 1400   | 4001  | 92214   | 51000    | 33860    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 1        | 
| 8400100054 | GAINESWOOD                              | GAINESWOOD                              |        | GAINESWOOD                              | 3342894846 |                                                                                     | GMU     |     |       |        |        |         |          | 3      | 3       | 1      | 91     | 972900 | 2025  | 90873   | 20296    |          |          | 0      | 0        | 1        | 0       | 0      | 0      |            | 0        | 
| 8400100055 | HANDY W C MUSEUM                        |                                         |        | HANDY W C MUSEUM                        | 2567606434 | HTTP://WWW.FLORENCEAL.ORG/COMMUNITY_ARTS/ART_MUSEUMS/ART_GALLERIES_MUSEUMS/WC_HANDY | GMU     |     |       |        |        |         |          | 3      | 1       | 1      | 77     | 10300  | 3002  | 91143   | 26896    | 22520    |          | 0      | 0        | 0        | 1       | 0      | 0      |            | 1        | 
```