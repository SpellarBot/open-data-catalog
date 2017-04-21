# Main Libraries, Branches, and Bookmobiles: FY 2012 Public Libraries Survey (Outlet)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-libraries-branches-and-bookmobiles-fy-2012-public-libraries-survey-outlet) |
| Metadata | [Link](https://data.imls.gov/api/views/ewqs-tfck) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ewqs-tfck/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ewqs-tfck/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ewqs-tfck |
| Name | Main Libraries, Branches, and Bookmobiles: FY 2012 Public Libraries Survey (Outlet) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, outlet, 2012 |
| Created | 2014-08-13T16:03:56Z |
| Publication Date | 2014-08-20T14:00:54Z |

## Description

Find key information on main libraries, branches, and bookmobiles, including FSCS IDs, square footage, and locale codes.<br><br>These data include imputed values for libraries that did not submit information in the FY 2012 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2012 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | stabr      | STABR    | text      | text        |
| Yes      | series tag     | fscskey    | FSCSKEY  | text      | text        |
| Yes      | series tag     | fscs_seq   | FSCS_SEQ | text      | text        |
| Yes      | series tag     | libid      | LIBID    | text      | text        |
| Yes      | series tag     | libname    | LIBNAME  | text      | text        |
| Yes      | series tag     | cnty       | CNTY     | text      | text        |
| Yes      | series tag     | phone      | PHONE    | text      | number      |
| Yes      | series tag     | c_out_ty   | C_OUT_TY | text      | text        |
| Yes      | series tag     | c_msa      | C_MSA    | text      | text        |
| Yes      | numeric metric | sq_feet    | SQ_FEET  | number    | number      |
| Yes      | numeric metric | l_num_bm   | L_NUM_BM | number    | number      |
| Yes      | numeric metric | hours      | HOURS    | number    | number      |
| Yes      | numeric metric | wks_open   | WKS_OPEN | number    | number      |
| Yes      | numeric metric | yr_sub     | YR_SUB   | number    | number      |
| Yes      | numeric metric | statstru   | STATSTRU | number    | number      |
| Yes      | numeric metric | statname   | STATNAME | number    | number      |
| Yes      | numeric metric | stataddr   | STATADDR | number    | number      |
| Yes      | series tag     | fipsst     | FIPSST   | text      | number      |
| Yes      | series tag     | fipsco     | FIPSCO   | text      | number      |
| Yes      | series tag     | fipsplac   | FIPSPLAC | text      | number      |
| Yes      | numeric metric | cntypop    | CNTYPOP  | number    | number      |
| Yes      | numeric metric | locale     | LOCALE   | number    | number      |
| Yes      | numeric metric | centract   | CENTRACT | number    | number      |
| Yes      | numeric metric | cenblock   | CENBLOCK | number    | number      |
| Yes      | series tag     | cdcode     | CDCODE   | text      | number      |
| Yes      | numeric metric | cbsa       | CBSA     | number    | number      |
| Yes      | numeric metric | microf     | MICROF   | number    | number      |
| Yes      | series tag     | gal        | GAL      | text      | text        |
| Yes      | series tag     | galms      | GALMS    | text      | text        |
| Yes      | series tag     | postms     | POSTMS   | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ewqs-tfck d:2012-01-01T00:00:00.000Z t:phone=9072355692 t:postms=POC t:cnty="KENAI PENINSULA" t:stabr=AK t:fscs_seq=002 t:fipsco=122 t:fscskey=AK0001 t:galms=DGL t:fipsplac=3110 t:c_msa=NO t:libid=AK0001-002 t:cdcode=200 t:libname="ANCHOR POINT PUBLIC LIBRARY" t:gal=street t:c_out_ty=CE t:fipsst=2 m:cbsa=0 m:cntypop=56884 m:microf=0 m:statstru=0 m:sq_feet=1287 m:cenblock=3013 m:statname=0 m:hours=1415 m:l_num_bm=0 m:yr_sub=2013 m:locale=43 m:stataddr=0 m:centract=8 m:wks_open=52

series e:ewqs-tfck d:2012-01-01T00:00:00.000Z t:phone=9073431530 t:postms=NND t:cnty=ANCHORAGE t:stabr=AK t:fscs_seq=007 t:fipsco=20 t:fscskey=AK0002 t:galms=STD t:fipsplac=3000 t:c_msa=CC t:libid=AK0002-007 t:cdcode=200 t:libname="CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY" t:gal=addresspoint t:c_out_ty=BR t:fipsst=2 m:cbsa=11260 m:cntypop=298294 m:microf=0 m:statstru=0 m:sq_feet=17888 m:cenblock=2021 m:statname=6 m:hours=2028 m:l_num_bm=0 m:yr_sub=2013 m:locale=31 m:stataddr=0 m:centract=2.01 m:wks_open=52

series e:ewqs-tfck d:2012-01-01T00:00:00.000Z t:phone=9073434223 t:postms=NND t:cnty=ANCHORAGE t:stabr=AK t:fscs_seq=008 t:fipsco=20 t:fscskey=AK0002 t:galms=STD t:fipsplac=3000 t:c_msa=CC t:libid=AK0002-008 t:cdcode=200 t:libname="MULDOON NEIGHBORHOOD LIBRARY" t:gal=addresspoint t:c_out_ty=BR t:fipsst=2 m:cbsa=11260 m:cntypop=298294 m:microf=0 m:statstru=0 m:sq_feet=8232 m:cenblock=5012 m:statname=6 m:hours=1768 m:l_num_bm=0 m:yr_sub=2013 m:locale=11 m:stataddr=0 m:centract=7.03 m:wks_open=52
```

## Meta Commands

```ls
metric m:sq_feet p:integer l:SQ_FEET t:dataTypeName=number

metric m:l_num_bm p:integer l:L_NUM_BM t:dataTypeName=number

metric m:hours p:integer l:HOURS t:dataTypeName=number

metric m:wks_open p:integer l:WKS_OPEN t:dataTypeName=number

metric m:yr_sub p:integer l:YR_SUB t:dataTypeName=number

metric m:statstru p:integer l:STATSTRU t:dataTypeName=number

metric m:statname p:integer l:STATNAME t:dataTypeName=number

metric m:stataddr p:integer l:STATADDR t:dataTypeName=number

metric m:cntypop p:integer l:CNTYPOP t:dataTypeName=number

metric m:locale p:integer l:LOCALE t:dataTypeName=number

metric m:centract p:integer l:CENTRACT t:dataTypeName=number

metric m:cenblock p:integer l:CENBLOCK t:dataTypeName=number

metric m:cbsa p:integer l:CBSA t:dataTypeName=number

metric m:microf p:integer l:MICROF t:dataTypeName=number

entity e:ewqs-tfck l:"Main Libraries, Branches, and Bookmobiles: FY 2012 Public Libraries Survey (Outlet)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ewqs-tfck

property e:ewqs-tfck t:meta.view v:id=ewqs-tfck v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Main Libraries, Branches, and Bookmobiles: FY 2012 Public Libraries Survey (Outlet)" v:attribution=IMLS

property e:ewqs-tfck t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ewqs-tfck t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ewqs-tfck t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ewqs-tfck t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stabr | fscskey | fscs_seq | libid      | libname                                       | cnty              | phone      | c_out_ty | c_msa | sq_feet | l_num_bm | hours | wks_open | yr_sub | statstru | statname | stataddr | fipsst | fipsco | fipsplac | cntypop | locale | centract | cenblock | cdcode | cbsa  | microf | gal             | galms | postms | 
| ===== | ======= | ======== | ========== | ============================================= | ================= | ========== | ======== | ===== | ======= | ======== | ===== | ======== | ====== | ======== | ======== | ======== | ====== | ====== | ======== | ======= | ====== | ======== | ======== | ====== | ===== | ====== | =============== | ===== | ====== | 
| AK    | AK0001  | 002      | AK0001-002 | ANCHOR POINT PUBLIC LIBRARY                   | KENAI PENINSULA   | 9072355692 | CE       | NO    | 1287    | 0        | 1415  | 52       | 2013   | 0        | 0        | 0        | 2      | 122    | 3110     | 56884   | 43     | 8        | 3013     | 200    | 0     | 0      | street          | DGL   | POC    | 
| AK    | AK0002  | 007      | AK0002-007 | CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY      | ANCHORAGE         | 9073431530 | BR       | CC    | 17888   | 0        | 2028  | 52       | 2013   | 0        | 6        | 0        | 2      | 20     | 3000     | 298294  | 31     | 2.01     | 2021     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 008      | AK0002-008 | MULDOON NEIGHBORHOOD LIBRARY                  | ANCHORAGE         | 9073434223 | BR       | CC    | 8232    | 0        | 1768  | 52       | 2013   | 0        | 6        | 0        | 2      | 20     | 3000     | 298294  | 11     | 7.03     | 5012     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 010      | AK0002-010 | SCOTT AND WESLEY GERRISH NEIGHBORHOOD LIBRARY | ANCHORAGE         | 9073434024 | BR       | CC    | 3938    | 0        | 1716  | 52       | 2013   | 0        | 6        | 0        | 2      | 20     | 3000     | 298294  | 42     | 29       | 2039     | 200    | 11260 | 0      | postalcode-main | NCF   | POC    | 
| AK    | AK0002  | 011      | AK0002-011 | Z. J. LOUSSAC LIBRARY                         | ANCHORAGE         | 9073432982 | CE       | CC    | 140000  | 0        | 3328  | 52       | 2013   | 0        | 0        | 0        | 2      | 20     | 3000     | 298294  | 11     | 19       | 3002     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 012      | AK0002-012 | MOUNTAIN VIEW NEIGHBORHOOD LIBRARY            | ANCHORAGE         | 9073432818 | BR       | CC    | 10704   | 0        | 1768  | 52       | 2013   | 0        | 6        | 0        | 2      | 20     | 3000     | 298294  | 11     | 9.01     | 2000     | 200    | 11260 | 0      | house           | STD   | NND    | 
| AK    | AK0003  | 002      | AK0003-002 | ANDERSON VILLAGE LIBRARY                      | DENALI            | 9075822628 | CE       | NO    | 3041    | 0        | 612   | 50       | 2013   | 0        | 0        | 0        | 2      | 68     | 3220     | 1860    | 43     | 1        | 1011     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0006  | 002      | AK0006-002 | KUSKOKWIM CONSORTIUM LIBRARY                  | BETHEL            | 9075434516 | CE       | NO    | 3656    | 0        | 2622  | 52       | 2013   | 0        | 0        | 0        | 2      | 50     | 6520     | 17653   | 41     | 2        | 2012     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0007  | 002      | AK0007-002 | BIG LAKE PUBLIC LIBRARY                       | MATANUSKA-SUSITNA | 9078926475 | CE       | NO    | 6940    | 0        | 2568  | 52       | 2013   | 0        | 0        | 0        | 2      | 170    | 7070     | 93845   | 42     | 5.02     | 1004     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0008  | 002      | AK0008-002 | CANTWELL COMMUNITY LIBRARY                    | DENALI            | 9077682372 | CE       | NO    | 1363    | 0        | 750   | 48       | 2013   | 0        | 0        | 0        | 2      | 68     | 10150    | 1860    | 43     | 1        | 2369     | 200    | 0     | 0      | postalcode-main | NCF   | POC    | 
```