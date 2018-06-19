# Main Libraries, Branches, and Bookmobiles: FY 2013 Public Libraries Survey (Outlet)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-libraries-branches-and-bookmobiles-fy-2013-public-libraries-survey-outlet) |
| Metadata | [Link](https://data.imls.gov/api/views/wpw5-huxj) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/wpw5-huxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/wpw5-huxj/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | wpw5-huxj |
| Name | Main Libraries, Branches, and Bookmobiles: FY 2013 Public Libraries Survey (Outlet) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, outlet, 2013 |
| Created | 2015-08-19T15:59:01Z |
| Publication Date | 2015-08-19T16:18:41Z |

## Description

Find key information on main libraries, branches, and bookmobiles, including FSCS IDs and location.<br><br>These data include imputed values for libraries that did not submit information in the FY 2013 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2013 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

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
| Yes      | series tag     | phone      | PHONE    | text      | text        |
| Yes      | series tag     | c_out_ty   | C_OUT_TY | text      | text        |
| Yes      | series tag     | c_msa      | C_MSA    | text      | text        |
| Yes      | numeric metric | sq_feet    | SQ_FEET  | number    | number      |
| Yes      | series tag     | f_sq_ft    | F_SQ_FT  | text      | text        |
| Yes      | numeric metric | l_num_bm   | L_NUM_BM | number    | number      |
| Yes      | series tag     | f_bkmob    | F_BKMOB  | text      | text        |
| Yes      | numeric metric | hours      | HOURS    | number    | number      |
| Yes      | series tag     | f_hours    | F_HOURS  | text      | text        |
| Yes      | numeric metric | wks_open   | WKS_OPEN | number    | number      |
| Yes      | series tag     | f_wksopn   | F_WKSOPN | text      | text        |
| Yes      | numeric metric | yr_sub     | YR_SUB   | number    | number      |
| Yes      | numeric metric | statstru   | STATSTRU | number    | number      |
| Yes      | numeric metric | statname   | STATNAME | number    | number      |
| Yes      | numeric metric | stataddr   | STATADDR | number    | number      |
| No       |                | longitud   | LONGITUD | number    | number      |
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
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = longitud
```

## Data Commands

```ls
series e:wpw5-huxj d:2013-01-01T00:00:00.000Z t:f_wksopn=R_13 t:phone=9072355692 t:postms=NND t:cnty="KENAI PENINSULA" t:stabr=AK t:f_sq_ft=R_13 t:fscs_seq=002 t:fipsco=122 t:f_bkmob=R_13 t:fscskey=AK0001 t:galms=STD t:fipsplac=3110 t:libid=AK0001-002 t:f_hours=R_13 t:c_msa=NO t:cdcode=200 t:libname="ANCHOR POINT PUBLIC LIBRARY" t:gal=house t:c_out_ty=CE t:fipsst=2 m:cbsa=0 m:cntypop=57067 m:microf=0 m:statstru=0 m:sq_feet=1287 m:cenblock=3014 m:statname=0 m:hours=1404 m:l_num_bm=0 m:yr_sub=2014 m:locale=43 m:stataddr=15 m:centract=8 m:wks_open=52

series e:wpw5-huxj d:2013-01-01T00:00:00.000Z t:f_wksopn=R_13 t:phone=9073431530 t:postms=NND t:cnty=ANCHORAGE t:stabr=AK t:f_sq_ft=R_13 t:fscs_seq=007 t:fipsco=20 t:f_bkmob=R_13 t:fscskey=AK0002 t:galms=STD t:fipsplac=3000 t:libid=AK0002-007 t:f_hours=R_13 t:c_msa=CC t:cdcode=200 t:libname="CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY" t:gal=addresspoint t:c_out_ty=BR t:fipsst=2 m:cbsa=11260 m:cntypop=301629 m:microf=0 m:statstru=0 m:sq_feet=17888 m:cenblock=2021 m:statname=0 m:hours=2028 m:l_num_bm=0 m:yr_sub=2014 m:locale=31 m:stataddr=0 m:centract=2.01 m:wks_open=52

series e:wpw5-huxj d:2013-01-01T00:00:00.000Z t:f_wksopn=R_13 t:phone=9073434223 t:postms=NND t:cnty=ANCHORAGE t:stabr=AK t:f_sq_ft=R_13 t:fscs_seq=008 t:fipsco=20 t:f_bkmob=R_13 t:fscskey=AK0002 t:galms=STD t:fipsplac=3000 t:libid=AK0002-008 t:f_hours=R_13 t:c_msa=CC t:cdcode=200 t:libname="MULDOON NEIGHBORHOOD LIBRARY" t:gal=addresspoint t:c_out_ty=BR t:fipsst=2 m:cbsa=11260 m:cntypop=301629 m:microf=0 m:statstru=0 m:sq_feet=8232 m:cenblock=5012 m:statname=0 m:hours=1768 m:l_num_bm=0 m:yr_sub=2014 m:locale=11 m:stataddr=0 m:centract=7.03 m:wks_open=52
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

metric m:centract p:double l:CENTRACT t:dataTypeName=number

metric m:cenblock p:integer l:CENBLOCK t:dataTypeName=number

metric m:cbsa p:integer l:CBSA t:dataTypeName=number

metric m:microf p:integer l:MICROF t:dataTypeName=number

entity e:wpw5-huxj l:"Main Libraries, Branches, and Bookmobiles: FY 2013 Public Libraries Survey (Outlet)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/wpw5-huxj

property e:wpw5-huxj t:meta.view v:id=wpw5-huxj v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Main Libraries, Branches, and Bookmobiles: FY 2013 Public Libraries Survey (Outlet)" v:attribution=IMLS

property e:wpw5-huxj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:wpw5-huxj t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:wpw5-huxj t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:wpw5-huxj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stabr | fscskey | fscs_seq | libid      | libname                                       | cnty              | phone      | c_out_ty | c_msa | sq_feet | f_sq_ft | l_num_bm | f_bkmob | hours | f_hours | wks_open | f_wksopn | yr_sub | statstru | statname | stataddr | longitud     | fipsst | fipsco | fipsplac | cntypop | locale | centract | cenblock | cdcode | cbsa  | microf | gal             | galms | postms | 
| ===== | ======= | ======== | ========== | ============================================= | ================= | ========== | ======== | ===== | ======= | ======= | ======== | ======= | ===== | ======= | ======== | ======== | ====== | ======== | ======== | ======== | ============ | ====== | ====== | ======== | ======= | ====== | ======== | ======== | ====== | ===== | ====== | =============== | ===== | ====== | 
| AK    | AK0001  | 002      | AK0001-002 | ANCHOR POINT PUBLIC LIBRARY                   | KENAI PENINSULA   | 9072355692 | CE       | NO    | 1287    | R_13    | 0        | R_13    | 1404  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 15       | -151.8400068 | 2      | 122    | 3110     | 57067   | 43     | 8        | 3014     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0002  | 007      | AK0002-007 | CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY      | ANCHORAGE         | 9073431530 | BR       | CC    | 17888   | R_13    | 0        | R_13    | 2028  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.572216  | 2      | 20     | 3000     | 301629  | 31     | 2.01     | 2021     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 008      | AK0002-008 | MULDOON NEIGHBORHOOD LIBRARY                  | ANCHORAGE         | 9073434223 | BR       | CC    | 8232    | R_13    | 0        | R_13    | 1768  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.733371  | 2      | 20     | 3000     | 301629  | 11     | 7.03     | 5012     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 010      | AK0002-010 | SCOTT AND WESLEY GERRISH NEIGHBORHOOD LIBRARY | ANCHORAGE         | 9073434024 | BR       | CC    | 3938    | R_13    | 0        | R_13    | 1716  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.126406  | 2      | 20     | 3000     | 301629  | 42     | 29       | 2039     | 200    | 11260 | 0      | postalcode-main | NCF   | POC    | 
| AK    | AK0002  | 011      | AK0002-011 | Z. J. LOUSSAC LIBRARY                         | ANCHORAGE         | 9073432975 | CE       | CC    | 140000  | R_13    | 0        | R_13    | 3328  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.876781  | 2      | 20     | 3000     | 301629  | 11     | 19       | 3002     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0002  | 012      | AK0002-012 | MOUNTAIN VIEW NEIGHBORHOOD LIBRARY            | ANCHORAGE         | 9073432818 | BR       | CC    | 10704   | R_13    | 0        | R_13    | 1768  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.8085248 | 2      | 20     | 3000     | 301629  | 11     | 9.01     | 2000     | 200    | 11260 | 0      | house           | STD   | NND    | 
| AK    | AK0003  | 002      | AK0003-002 | ANDERSON VILLAGE LIBRARY                      | DENALI            | 9075822628 | CE       | NO    | 3041    | R_13    | 0        | R_13    | 600   | R_13    | 50       | R_13     | 2014   | 0        | 0        | 0        | -149.1786346 | 2      | 68     | 3220     | 1933    | 43     | 1        | 1011     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0006  | 002      | AK0006-002 | KUSKOKWIM CONSORTIUM LIBRARY                  | BETHEL            | 9075434516 | CE       | NO    | 3656    | R_13    | 0        | R_13    | 2652  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 15       | -161.8029566 | 2      | 50     | 6520     | 17806   | 33     | 2        | 2011     | 200    | 0     | 0      | street          | DGL   | POC    | 
| AK    | AK0007  | 002      | AK0007-002 | BIG LAKE PUBLIC LIBRARY                       | MATANUSKA-SUSITNA | 9078926475 | CE       | NO    | 6940    | R_13    | 0        | R_13    | 2548  | R_13    | 52       | R_13     | 2014   | 0        | 0        | 0        | -149.818403  | 2      | 170    | 7070     | 95892   | 42     | 5.02     | 1004     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0008  | 002      | AK0008-002 | CANTWELL COMMUNITY LIBRARY                    | DENALI            | 9077682372 | CE       | NO    | 1363    | R_13    | 0        | R_13    | 750   | R_13    | 48       | R_13     | 2014   | 0        | 0        | 0        | -148.757407  | 2      | 68     | 10150    | 1933    | 43     | 1        | 2369     | 200    | 0     | 0      | postalcode-main | NCF   | POC    | 
```