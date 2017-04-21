# Library Systems: FY 2013 Public Libraries Survey (Administrative Entity)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-systems-fy-2013-public-libraries-survey-administrative-entity) |
| Metadata | [Link](https://data.imls.gov/api/views/ijm6-wnaq) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ijm6-wnaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ijm6-wnaq/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ijm6-wnaq |
| Name | Library Systems: FY 2013 Public Libraries Survey (Administrative Entity) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, administrative entity, 2013 |
| Created | 2015-08-19T16:42:33Z |
| Publication Date | 2015-08-19T17:06:40Z |

## Description

Find key information on library systems around the United States.<br><br>These data include imputed values for libraries that did not submit information in the FY 2013 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2013 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | stabr      | STABR    | text          | text          |
| Yes      | series tag     | fscskey    | FSCSKEY  | text          | text          |
| Yes      | series tag     | libid      | LIBID    | text          | text          |
| Yes      | series tag     | libname    | LIBNAME  | text          | text          |
| Yes      | series tag     | addres_m   | ADDRES_M | text          | text          |
| Yes      | series tag     | zip4_m     | ZIP4_M   | text          | text          |
| Yes      | series tag     | cnty       | CNTY     | text          | text          |
| Yes      | series tag     | phone      | PHONE    | text          | text          |
| Yes      | series tag     | c_relatn   | C_RELATN | text          | text          |
| Yes      | series tag     | c_legbas   | C_LEGBAS | text          | text          |
| Yes      | series tag     | c_admin    | C_ADMIN  | text          | text          |
| Yes      | series tag     | c_fscs     | C_FSCS   | text          | text          |
| Yes      | series tag     | geocode    | GEOCODE  | text          | text          |
| Yes      | series tag     | lsabound   | LSABOUND | text          | text          |
| Yes      | time           | startdat   | STARTDAT | calendar_date | calendar_date |
| Yes      | series tag     | f_stdat    | F_STDAT  | text          | text          |
| No       |                | enddate    | ENDDATE  | calendar_date | calendar_date |
| Yes      | series tag     | f_enddat   | F_ENDDAT | text          | text          |
| Yes      | numeric metric | popu_lsa   | POPU_LSA | number        | number        |
| Yes      | series tag     | f_poplsa   | F_POPLSA | text          | text          |
| Yes      | numeric metric | popu_und   | POPU_UND | number        | number        |
| Yes      | series tag     | f_popund   | F_POPUND | text          | text          |
| Yes      | numeric metric | centlib    | CENTLIB  | number        | number        |
| Yes      | series tag     | f_cenlib   | F_CENLIB | text          | text          |
| Yes      | numeric metric | branlib    | BRANLIB  | number        | number        |
| Yes      | series tag     | f_brlib    | F_BRLIB  | text          | text          |
| Yes      | numeric metric | bkmob      | BKMOB    | number        | number        |
| Yes      | series tag     | f_bkmob    | F_BKMOB  | text          | text          |
| Yes      | numeric metric | master     | MASTER   | number        | number        |
| Yes      | series tag     | f_master   | F_MASTER | text          | text          |
| Yes      | numeric metric | libraria   | LIBRARIA | number        | number        |
| Yes      | series tag     | f_librar   | F_LIBRAR | text          | text          |
| Yes      | series tag     | othpaid    | OTHPAID  | text          | number        |
| Yes      | series tag     | f_othstf   | F_OTHSTF | text          | text          |
| Yes      | numeric metric | totstaff   | TOTSTAFF | number        | number        |
| Yes      | series tag     | f_totstf   | F_TOTSTF | text          | text          |
| Yes      | numeric metric | locgvt     | LOCGVT   | money         | money         |
| Yes      | series tag     | f_locgvt   | F_LOCGVT | text          | text          |
| Yes      | numeric metric | stgvt      | STGVT    | money         | money         |
| Yes      | series tag     | f_stgvt    | F_STGVT  | text          | text          |
| Yes      | numeric metric | fedgvt     | FEDGVT   | money         | money         |
| Yes      | series tag     | f_fedgvt   | F_FEDGVT | text          | text          |
| Yes      | numeric metric | othincm    | OTHINCM  | number        | number        |
| Yes      | series tag     | f_othinc   | F_OTHINC | text          | text          |
| Yes      | numeric metric | totincm    | TOTINCM  | money         | money         |
| Yes      | series tag     | f_totinc   | F_TOTINC | text          | text          |
| Yes      | numeric metric | salaries   | SALARIES | money         | money         |
| Yes      | series tag     | f_salx     | F_SALX   | text          | text          |
| Yes      | numeric metric | benefit    | BENEFIT  | money         | money         |
| Yes      | series tag     | f_benx     | F_BENX   | text          | text          |
| Yes      | numeric metric | staffexp   | STAFFEXP | money         | money         |
| Yes      | series tag     | f_tostfx   | F_TOSTFX | text          | text          |
| Yes      | numeric metric | prmatexp   | PRMATEXP | money         | money         |
| Yes      | series tag     | f_prmatx   | F_PRMATX | text          | text          |
| Yes      | numeric metric | elmatexp   | ELMATEXP | money         | money         |
| Yes      | series tag     | f_elmatx   | F_ELMATX | text          | text          |
| Yes      | numeric metric | othmatex   | OTHMATEX | money         | money         |
| Yes      | series tag     | f_otmatx   | F_OTMATX | text          | text          |
| Yes      | numeric metric | totexpco   | TOTEXPCO | money         | money         |
| Yes      | series tag     | f_tocolx   | F_TOCOLX | text          | text          |
| Yes      | numeric metric | othopexp   | OTHOPEXP | number        | number        |
| Yes      | series tag     | f_othopx   | F_OTHOPX | text          | text          |
| Yes      | numeric metric | totopexp   | TOTOPEXP | money         | money         |
| Yes      | series tag     | f_totopx   | F_TOTOPX | text          | text          |
| Yes      | numeric metric | lcap_rev   | LCAP_REV | money         | money         |
| Yes      | series tag     | f_lcaprv   | F_LCAPRV | text          | text          |
| Yes      | numeric metric | scap_rev   | SCAP_REV | money         | money         |
| Yes      | series tag     | f_scaprv   | F_SCAPRV | text          | text          |
| Yes      | numeric metric | fcap_rev   | FCAP_REV | money         | money         |
| Yes      | series tag     | f_fcaprv   | F_FCAPRV | text          | text          |
| Yes      | numeric metric | ocap_rev   | OCAP_REV | money         | money         |
| Yes      | series tag     | f_ocaprv   | F_OCAPRV | text          | text          |
| Yes      | numeric metric | cap_rev    | CAP_REV  | money         | money         |
| Yes      | series tag     | f_tcaprv   | F_TCAPRV | text          | text          |
| Yes      | numeric metric | capital    | CAPITAL  | money         | money         |
| Yes      | series tag     | f_tcapx    | F_TCAPX  | text          | text          |
| Yes      | numeric metric | bkvol      | BKVOL    | number        | number        |
| Yes      | series tag     | f_bkvol    | F_BKVOL  | text          | text          |
| Yes      | numeric metric | ebook      | EBOOK    | number        | number        |
| Yes      | series tag     | f_ebook    | F_EBOOK  | text          | text          |
| Yes      | numeric metric | audio_ph   | AUDIO_PH | number        | number        |
| Yes      | series tag     | f_aud_ph   | F_AUD_PH | text          | text          |
| Yes      | numeric metric | audio_dl   | AUDIO_DL | number        | number        |
| Yes      | series tag     | f_aud_dl   | F_AUD_DL | text          | text          |
| Yes      | numeric metric | video_ph   | VIDEO_PH | number        | number        |
| Yes      | series tag     | f_vid_ph   | F_VID_PH | text          | text          |
| Yes      | numeric metric | video_dl   | VIDEO_DL | number        | number        |
| Yes      | series tag     | f_vid_dl   | F_VID_DL | text          | text          |
| Yes      | numeric metric | db_lo_ot   | DB_LO_OT | number        | number        |
| Yes      | series tag     | f_db_l_o   | F_DB_L_O | text          | text          |
| Yes      | numeric metric | db_st      | DB_ST    | number        | number        |
| Yes      | series tag     | f_db_st    | F_DB_ST  | text          | text          |
| Yes      | numeric metric | database   | DATABASE | number        | number        |
| Yes      | series tag     | f_dbase    | F_DBASE  | text          | text          |
| Yes      | numeric metric | subscrip   | SUBSCRIP | number        | number        |
| Yes      | series tag     | f_prsub    | F_PRSUB  | text          | text          |
| Yes      | numeric metric | hrs_open   | HRS_OPEN | number        | number        |
| Yes      | series tag     | f_hrs_op   | F_HRS_OP | text          | text          |
| Yes      | numeric metric | visits     | VISITS   | number        | number        |
| Yes      | series tag     | f_visits   | F_VISITS | text          | text          |
| Yes      | numeric metric | referenc   | REFERENC | number        | number        |
| Yes      | series tag     | f_refer    | F_REFER  | text          | text          |
| Yes      | numeric metric | regbor     | REGBOR   | number        | number        |
| Yes      | series tag     | f_regbor   | F_REGBOR | text          | text          |
| Yes      | numeric metric | totcir     | TOTCIR   | number        | number        |
| Yes      | series tag     | f_totcir   | F_TOTCIR | text          | text          |
| Yes      | numeric metric | kidcircl   | KIDCIRCL | number        | number        |
| Yes      | series tag     | f_kidcir   | F_KIDCIR | text          | text          |
| Yes      | numeric metric | elmatcir   | ELMATCIR | number        | number        |
| Yes      | series tag     | f_emtcir   | F_EMTCIR | text          | text          |
| Yes      | numeric metric | loanto     | LOANTO   | number        | number        |
| Yes      | series tag     | f_loanto   | F_LOANTO | text          | text          |
| Yes      | numeric metric | loanfm     | LOANFM   | number        | number        |
| Yes      | series tag     | f_loanfm   | F_LOANFM | text          | text          |
| Yes      | numeric metric | totpro     | TOTPRO   | number        | number        |
| Yes      | series tag     | f_totpro   | F_TOTPRO | text          | text          |
| Yes      | numeric metric | kidpro     | KIDPRO   | number        | number        |
| Yes      | series tag     | f_kidpro   | F_KIDPRO | text          | text          |
| Yes      | numeric metric | yapro      | YAPRO    | number        | number        |
| Yes      | series tag     | f_yapro    | F_YAPRO  | text          | text          |
| Yes      | numeric metric | totatten   | TOTATTEN | number        | number        |
| Yes      | series tag     | f_totatt   | F_TOTATT | text          | text          |
| Yes      | numeric metric | kidatten   | KIDATTEN | number        | number        |
| Yes      | series tag     | f_kidatt   | F_KIDATT | text          | text          |
| Yes      | numeric metric | yaatten    | YAATTEN  | number        | number        |
| Yes      | series tag     | f_yaatt    | F_YAATT  | text          | text          |
| Yes      | numeric metric | gpterms    | GPTERMS  | number        | number        |
| Yes      | series tag     | f_gpterm   | F_GPTERM | text          | text          |
| Yes      | numeric metric | pitusr     | PITUSR   | number        | number        |
| Yes      | series tag     | f_pitusr   | F_PITUSR | text          | text          |
| Yes      | numeric metric | yr_sub     | YR_SUB   | number        | number        |
| Yes      | numeric metric | obereg     | OBEREG   | number        | number        |
| Yes      | series tag     | rstatus    | RSTATUS  | text          | number        |
| Yes      | numeric metric | statstru   | STATSTRU | number        | number        |
| Yes      | numeric metric | statname   | STATNAME | number        | number        |
| Yes      | numeric metric | stataddr   | STATADDR | number        | number        |
| No       |                | longitud   | LONGITUD | number        | number        |
| Yes      | series tag     | fipsst     | FIPSST   | text          | number        |
| Yes      | series tag     | fipsco     | FIPSCO   | text          | number        |
| Yes      | series tag     | fipsplac   | FIPSPLAC | text          | number        |
| Yes      | numeric metric | cntypop    | CNTYPOP  | number        | number        |
| Yes      | numeric metric | locale     | LOCALE   | number        | number        |
| Yes      | numeric metric | centract   | CENTRACT | number        | number        |
| Yes      | numeric metric | cenblock   | CENBLOCK | number        | number        |
| Yes      | series tag     | cdcode     | CDCODE   | text          | number        |
| Yes      | numeric metric | cbsa       | CBSA     | number        | number        |
| Yes      | numeric metric | microf     | MICROF   | number        | number        |
| Yes      | series tag     | gal        | GAL      | text          | text          |
| Yes      | series tag     | galms      | GALMS    | text          | text          |
| Yes      | series tag     | postms     | POSTMS   | text          | text          |
```

## Time Field

```ls
Value = startdat
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddate,longitud
```

## Data Commands

```ls
series e:ijm6-wnaq d:2013-01-01T00:00:00.000Z t:f_enddat=R_13 t:phone=7857942424 t:f_othstf=R_13 t:f_totinc=R_13 t:postms=NND t:f_fcaprv=R_13 t:f_kidcir=R_13 t:c_admin=SO t:c_fscs=Y t:f_bkmob=R_13 t:fipsco=89 t:f_stdat=R_13 t:f_totstf=R_13 t:f_prsub=R_13 t:f_lcaprv=R_13 t:f_prmatx=R_13 t:f_ebook=R_13 t:f_loanfm=R_13 t:othpaid=0 t:f_kidpro=R_13 t:f_emtcir=R_13 t:f_tostfx=H_13 t:f_locgvt=R_13 t:f_popund=R_13 t:f_tcapx=R_13 t:addres_m="P.O. BOX 156" t:f_benx=H_13 t:f_othopx=H_13 t:f_loanto=R_13 t:f_othinc=R_13 t:f_tocolx=R_13 t:f_kidatt=R_13 t:f_vid_dl=R_13 t:f_dbase=R_13 t:f_db_l_o=R_13 t:f_master=R_13 t:f_yapro=R_13 t:f_totopx=R_13 t:f_db_st=R_13 t:f_scaprv=R_13 t:f_vid_ph=R_13 t:geocode=CI1 t:f_yaatt=R_13 t:libid=KS0094 t:f_pitusr=R_13 t:libname="FORMOSO PUBLIC LIBRARY" t:f_aud_dl=R_13 t:f_otmatx=R_13 t:f_elmatx=R_13 t:gal=house t:fipsst=20 t:f_aud_ph=R_13 t:zip4_m=156 t:f_gpterm=R_13 t:f_bkvol=R_13 t:f_librar=R_13 t:stabr=KS t:f_poplsa=R_13 t:rstatus=1 t:lsabound=N t:f_visits=R_13 t:f_hrs_op=R_13 t:f_fedgvt=R_13 t:f_ocaprv=R_13 t:c_relatn=ME t:f_totcir=R_13 t:f_salx=H_13 t:f_totatt=R_13 t:cnty=JEWELL t:f_regbor=R_13 t:f_brlib=R_13 t:fscskey=KS0003 t:f_tcaprv=R_13 t:galms=STD t:fipsplac=23825 t:f_cenlib=R_13 t:f_refer=R_13 t:f_stgvt=R_13 t:cdcode=2001 t:f_totpro=R_13 t:c_legbas=CI m:microf=0 m:db_lo_ot=0 m:kidcircl=326 m:yapro=0 m:bkvol=5308 m:capital=0 m:referenc=107 m:video_ph=93 m:pitusr=542 m:video_dl=0 m:statstru=0 m:prmatexp=207 m:cenblock=2345 m:loanfm=141 m:stataddr=0 m:totexpco=207 m:totincm=8409 m:totcir=1608 m:othincm=0 m:lcap_rev=420 m:obereg=4 m:yr_sub=2014 m:fedgvt=201 m:totatten=270 m:yaatten=0 m:bkmob=0 m:cbsa=0 m:cap_rev=420 m:popu_und=92 m:kidpro=34 m:totpro=45 m:kidatten=151 m:fcap_rev=0 m:locale=43 m:gpterms=7 m:audio_ph=11 m:hrs_open=520 m:ebook=0 m:statname=0 m:libraria=0.25 m:subscrip=40 m:elmatcir=0 m:elmatexp=0 m:loanto=83 m:branlib=0 m:centlib=1 m:locgvt=4842 m:master=0 m:totopexp=7399 m:database=51 m:cntypop=3067 m:audio_dl=0 m:othmatex=0 m:db_st=51 m:ocap_rev=0 m:regbor=276 m:popu_lsa=92 m:totstaff=0.25 m:centract=5761 m:scap_rev=0 m:stgvt=3366 m:visits=1674

series e:ijm6-wnaq d:2013-01-01T00:00:00.000Z t:f_enddat=R_13 t:phone=7856933025 t:f_othstf=R_13 t:f_totinc=R_13 t:postms=POC t:f_fcaprv=R_13 t:f_kidcir=R_13 t:c_admin=SO t:c_fscs=Y t:f_bkmob=R_13 t:fipsco=39 t:f_stdat=R_13 t:f_totstf=R_13 t:f_prsub=R_13 t:f_lcaprv=R_13 t:f_prmatx=R_13 t:f_ebook=R_13 t:f_loanfm=R_13 t:othpaid=0 t:f_kidpro=R_13 t:f_emtcir=R_13 t:f_tostfx=H_13 t:f_locgvt=R_13 t:f_popund=R_13 t:f_tcapx=R_13 t:addres_m="P O BOX 84" t:f_benx=H_13 t:f_othopx=H_13 t:f_loanto=R_13 t:f_othinc=R_13 t:f_tocolx=R_13 t:f_kidatt=R_13 t:f_vid_dl=R_13 t:f_dbase=R_13 t:f_db_l_o=R_13 t:f_master=R_13 t:f_yapro=R_13 t:f_totopx=R_13 t:f_db_st=R_13 t:f_scaprv=R_13 t:f_vid_ph=R_13 t:geocode=CI1 t:f_yaatt=R_13 t:libid=KS0231 t:f_pitusr=R_13 t:libname="NORCATUR PUBLIC LIBRARY" t:f_aud_dl=R_13 t:f_otmatx=R_13 t:f_elmatx=R_13 t:gal=street t:fipsst=20 t:f_aud_ph=R_13 t:zip4_m=84 t:f_gpterm=R_13 t:f_bkvol=R_13 t:f_librar=R_13 t:stabr=KS t:f_poplsa=R_13 t:rstatus=1 t:lsabound=N t:f_visits=R_13 t:f_hrs_op=R_13 t:f_fedgvt=R_13 t:f_ocaprv=R_13 t:c_relatn=ME t:f_totcir=R_13 t:f_salx=H_13 t:f_totatt=R_13 t:cnty=DECATUR t:f_regbor=R_13 t:f_brlib=R_13 t:fscskey=KS0138 t:f_tcaprv=R_13 t:galms=DGL t:fipsplac=50925 t:f_cenlib=R_13 t:f_refer=R_13 t:f_stgvt=R_13 t:cdcode=2001 t:f_totpro=R_13 t:c_legbas=CI m:microf=0 m:db_lo_ot=0 m:kidcircl=500 m:yapro=0 m:bkvol=7780 m:capital=0 m:referenc=0 m:video_ph=30 m:pitusr=25 m:video_dl=0 m:statstru=0 m:prmatexp=1025 m:cenblock=1459 m:loanfm=86 m:stataddr=0 m:totexpco=1525 m:totincm=4571 m:totcir=1700 m:othincm=1000 m:lcap_rev=0 m:obereg=4 m:yr_sub=2014 m:fedgvt=0 m:totatten=320 m:yaatten=0 m:bkmob=0 m:cbsa=0 m:cap_rev=0 m:popu_und=147 m:kidpro=39 m:totpro=55 m:kidatten=200 m:fcap_rev=0 m:locale=43 m:gpterms=2 m:audio_ph=80 m:hrs_open=664 m:ebook=0 m:statname=0 m:libraria=0.12 m:subscrip=0 m:elmatcir=0 m:elmatexp=0 m:loanto=28 m:branlib=0 m:centlib=1 m:locgvt=2511 m:master=0 m:totopexp=3525 m:database=51 m:cntypop=2915 m:audio_dl=0 m:othmatex=500 m:db_st=51 m:ocap_rev=0 m:regbor=100 m:popu_lsa=147 m:totstaff=0.12 m:centract=9511 m:scap_rev=0 m:stgvt=1060 m:visits=370

series e:ijm6-wnaq d:2013-01-01T00:00:00.000Z t:f_enddat=R_13 t:phone=7857362858 t:f_othstf=R_13 t:f_totinc=R_13 t:postms=NND t:f_fcaprv=R_13 t:f_kidcir=R_13 t:c_admin=SO t:c_fscs=Y t:f_bkmob=R_13 t:fipsco=117 t:f_stdat=R_13 t:f_totstf=R_13 t:f_prsub=R_13 t:f_lcaprv=R_13 t:f_prmatx=R_13 t:f_ebook=R_13 t:f_loanfm=R_13 t:othpaid=0 t:f_kidpro=R_13 t:f_emtcir=R_13 t:f_tostfx=H_13 t:f_locgvt=R_13 t:f_popund=R_13 t:f_tcapx=R_13 t:addres_m="401 MAPLE" t:f_benx=H_13 t:f_othopx=H_13 t:f_loanto=R_13 t:f_othinc=R_13 t:f_tocolx=R_13 t:f_kidatt=R_13 t:f_vid_dl=R_13 t:f_dbase=R_13 t:f_db_l_o=R_13 t:f_master=R_13 t:f_yapro=R_13 t:f_totopx=R_13 t:f_db_st=R_13 t:f_scaprv=R_13 t:f_vid_ph=R_13 t:geocode=CI1 t:f_yaatt=R_13 t:libid=KS0014 t:f_pitusr=R_13 t:libname="AXTELL PUBLIC LIBRARY" t:f_aud_dl=R_13 t:f_otmatx=R_13 t:f_elmatx=R_13 t:gal=house t:fipsst=20 t:f_aud_ph=R_13 t:zip4_m=9800 t:f_gpterm=R_13 t:f_bkvol=R_13 t:f_librar=R_13 t:stabr=KS t:f_poplsa=R_13 t:rstatus=1 t:lsabound=N t:f_visits=R_13 t:f_hrs_op=R_13 t:f_fedgvt=R_13 t:f_ocaprv=R_13 t:c_relatn=ME t:f_totcir=R_13 t:f_salx=H_13 t:f_totatt=R_13 t:cnty=MARSHALL t:f_regbor=R_13 t:f_brlib=R_13 t:fscskey=KS0060 t:f_tcaprv=R_13 t:galms=STD t:fipsplac=3600 t:f_cenlib=R_13 t:f_refer=R_13 t:f_stgvt=R_13 t:cdcode=2002 t:f_totpro=R_13 t:c_legbas=CI m:microf=0 m:db_lo_ot=0 m:kidcircl=897 m:yapro=0 m:bkvol=5969 m:capital=0 m:referenc=9 m:video_ph=686 m:pitusr=629 m:video_dl=0 m:statstru=0 m:prmatexp=1250 m:cenblock=3213 m:loanfm=0 m:stataddr=0 m:totexpco=1411 m:totincm=7484 m:totcir=1835 m:othincm=113 m:lcap_rev=0 m:obereg=4 m:yr_sub=2014 m:fedgvt=0 m:totatten=22 m:yaatten=0 m:bkmob=0 m:cbsa=0 m:cap_rev=0 m:popu_und=401 m:kidpro=2 m:totpro=2 m:kidatten=22 m:fcap_rev=0 m:locale=43 m:gpterms=4 m:audio_ph=187 m:hrs_open=624 m:ebook=0 m:statname=0 m:libraria=0.3 m:subscrip=0 m:elmatcir=0 m:elmatexp=0 m:loanto=3 m:branlib=0 m:centlib=1 m:locgvt=5960 m:master=0 m:totopexp=7587 m:database=51 m:cntypop=10028 m:audio_dl=0 m:othmatex=161 m:db_st=51 m:ocap_rev=0 m:regbor=202 m:popu_lsa=401 m:totstaff=0.3 m:centract=901.86 m:scap_rev=0 m:stgvt=1411 m:visits=2070
```

## Meta Commands

```ls
metric m:popu_lsa p:integer l:POPU_LSA t:dataTypeName=number

metric m:popu_und p:integer l:POPU_UND t:dataTypeName=number

metric m:centlib p:integer l:CENTLIB t:dataTypeName=number

metric m:branlib p:integer l:BRANLIB t:dataTypeName=number

metric m:bkmob p:integer l:BKMOB t:dataTypeName=number

metric m:master p:float l:MASTER t:dataTypeName=number

metric m:libraria p:float l:LIBRARIA t:dataTypeName=number

metric m:totstaff p:float l:TOTSTAFF t:dataTypeName=number

metric m:locgvt p:integer l:LOCGVT t:dataTypeName=money

metric m:stgvt p:integer l:STGVT t:dataTypeName=money

metric m:fedgvt p:integer l:FEDGVT t:dataTypeName=money

metric m:othincm p:integer l:OTHINCM t:dataTypeName=number

metric m:totincm p:integer l:TOTINCM t:dataTypeName=money

metric m:salaries p:integer l:SALARIES t:dataTypeName=money

metric m:benefit p:integer l:BENEFIT t:dataTypeName=money

metric m:staffexp p:integer l:STAFFEXP t:dataTypeName=money

metric m:prmatexp p:integer l:PRMATEXP t:dataTypeName=money

metric m:elmatexp p:integer l:ELMATEXP t:dataTypeName=money

metric m:othmatex p:integer l:OTHMATEX t:dataTypeName=money

metric m:totexpco p:integer l:TOTEXPCO t:dataTypeName=money

metric m:othopexp p:integer l:OTHOPEXP t:dataTypeName=number

metric m:totopexp p:integer l:TOTOPEXP t:dataTypeName=money

metric m:lcap_rev p:integer l:LCAP_REV t:dataTypeName=money

metric m:scap_rev p:integer l:SCAP_REV t:dataTypeName=money

metric m:fcap_rev p:integer l:FCAP_REV t:dataTypeName=money

metric m:ocap_rev p:integer l:OCAP_REV t:dataTypeName=money

metric m:cap_rev p:integer l:CAP_REV t:dataTypeName=money

metric m:capital p:integer l:CAPITAL t:dataTypeName=money

metric m:bkvol p:integer l:BKVOL t:dataTypeName=number

metric m:ebook p:integer l:EBOOK t:dataTypeName=number

metric m:audio_ph p:integer l:AUDIO_PH t:dataTypeName=number

metric m:audio_dl p:integer l:AUDIO_DL t:dataTypeName=number

metric m:video_ph p:integer l:VIDEO_PH t:dataTypeName=number

metric m:video_dl p:integer l:VIDEO_DL t:dataTypeName=number

metric m:db_lo_ot p:integer l:DB_LO_OT t:dataTypeName=number

metric m:db_st p:integer l:DB_ST t:dataTypeName=number

metric m:database p:integer l:DATABASE t:dataTypeName=number

metric m:subscrip p:integer l:SUBSCRIP t:dataTypeName=number

metric m:hrs_open p:integer l:HRS_OPEN t:dataTypeName=number

metric m:visits p:integer l:VISITS t:dataTypeName=number

metric m:referenc p:integer l:REFERENC t:dataTypeName=number

metric m:regbor p:integer l:REGBOR t:dataTypeName=number

metric m:totcir p:integer l:TOTCIR t:dataTypeName=number

metric m:kidcircl p:integer l:KIDCIRCL t:dataTypeName=number

metric m:elmatcir p:integer l:ELMATCIR t:dataTypeName=number

metric m:loanto p:integer l:LOANTO t:dataTypeName=number

metric m:loanfm p:integer l:LOANFM t:dataTypeName=number

metric m:totpro p:integer l:TOTPRO t:dataTypeName=number

metric m:kidpro p:integer l:KIDPRO t:dataTypeName=number

metric m:yapro p:integer l:YAPRO t:dataTypeName=number

metric m:totatten p:integer l:TOTATTEN t:dataTypeName=number

metric m:kidatten p:integer l:KIDATTEN t:dataTypeName=number

metric m:yaatten p:integer l:YAATTEN t:dataTypeName=number

metric m:gpterms p:integer l:GPTERMS t:dataTypeName=number

metric m:pitusr p:integer l:PITUSR t:dataTypeName=number

metric m:yr_sub p:integer l:YR_SUB t:dataTypeName=number

metric m:obereg p:integer l:OBEREG t:dataTypeName=number

metric m:statstru p:integer l:STATSTRU t:dataTypeName=number

metric m:statname p:integer l:STATNAME t:dataTypeName=number

metric m:stataddr p:integer l:STATADDR t:dataTypeName=number

metric m:cntypop p:integer l:CNTYPOP t:dataTypeName=number

metric m:locale p:integer l:LOCALE t:dataTypeName=number

metric m:centract p:double l:CENTRACT t:dataTypeName=number

metric m:cenblock p:integer l:CENBLOCK t:dataTypeName=number

metric m:cbsa p:integer l:CBSA t:dataTypeName=number

metric m:microf p:integer l:MICROF t:dataTypeName=number

entity e:ijm6-wnaq l:"Library Systems: FY 2013 Public Libraries Survey (Administrative Entity)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ijm6-wnaq

property e:ijm6-wnaq t:meta.view v:id=ijm6-wnaq v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Library Systems: FY 2013 Public Libraries Survey (Administrative Entity)" v:attribution=IMLS

property e:ijm6-wnaq t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ijm6-wnaq t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ijm6-wnaq t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ijm6-wnaq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stabr | fscskey | libid      | libname                   | addres_m           | zip4_m | cnty       | phone      | c_relatn | c_legbas | c_admin | c_fscs | geocode | lsabound | startdat            | f_stdat | enddate             | f_enddat | popu_lsa | f_poplsa | popu_und | f_popund | centlib | f_cenlib | branlib | f_brlib | bkmob | f_bkmob | master | f_master | libraria | f_librar | othpaid | f_othstf | totstaff | f_totstf | locgvt | f_locgvt | stgvt | f_stgvt | fedgvt | f_fedgvt | othincm | f_othinc | totincm | f_totinc | salaries | f_salx | benefit | f_benx | staffexp | f_tostfx | prmatexp | f_prmatx | elmatexp | f_elmatx | othmatex | f_otmatx | totexpco | f_tocolx | othopexp | f_othopx | totopexp | f_totopx | lcap_rev | f_lcaprv | scap_rev | f_scaprv | fcap_rev | f_fcaprv | ocap_rev | f_ocaprv | cap_rev | f_tcaprv | capital | f_tcapx | bkvol | f_bkvol | ebook | f_ebook | audio_ph | f_aud_ph | audio_dl | f_aud_dl | video_ph | f_vid_ph | video_dl | f_vid_dl | db_lo_ot | f_db_l_o | db_st | f_db_st | database | f_dbase | subscrip | f_prsub | hrs_open | f_hrs_op | visits | f_visits | referenc | f_refer | regbor | f_regbor | totcir | f_totcir | kidcircl | f_kidcir | elmatcir | f_emtcir | loanto | f_loanto | loanfm | f_loanfm | totpro | f_totpro | kidpro | f_kidpro | yapro | f_yapro | totatten | f_totatt | kidatten | f_kidatt | yaatten | f_yaatt | gpterms | f_gpterm | pitusr | f_pitusr | yr_sub | obereg | rstatus | statstru | statname | stataddr | longitud     | fipsst | fipsco | fipsplac | cntypop | locale | centract | cenblock | cdcode | cbsa  | microf | gal          | galms | postms | 
| ===== | ======= | ========== | ========================= | ================== | ====== | ========== | ========== | ======== | ======== | ======= | ====== | ======= | ======== | =================== | ======= | =================== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ===== | ======= | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ====== | ======== | ===== | ======= | ====== | ======== | ======= | ======== | ======= | ======== | ======== | ====== | ======= | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ===== | ======= | ===== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ===== | ======= | ======== | ======= | ======== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ====== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ====== | ======== | ====== | ======== | ====== | ======== | ===== | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======== | ====== | ======== | ====== | ====== | ======= | ======== | ======== | ======== | ============ | ====== | ====== | ======== | ======= | ====== | ======== | ======== | ====== | ===== | ====== | ============ | ===== | ====== | 
| KS    | KS0003  | KS0094     | FORMOSO PUBLIC LIBRARY    | P.O. BOX 156       | 156    | JEWELL     | 7857942424 | ME       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 92       | R_13     | 92       | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.25     | R_13     | 0       | R_13     | 0.25     | R_13     | 4842   | R_13     | 3366  | R_13    | 201    | R_13     | 0       | R_13     | 8409    | R_13     |          | H_13   |         | H_13   |          | H_13     | 207      | R_13     | 0        | R_13     | 0        | R_13     | 207      | R_13     |          | H_13     | 7399     | R_13     | 420      | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 420     | R_13     | 0       | R_13    | 5308  | R_13    | 0     | R_13    | 11       | R_13     | 0        | R_13     | 93       | R_13     | 0        | R_13     | 0        | R_13     | 51    | R_13    | 51       | R_13    | 40       | R_13    | 520      | R_13     | 1674   | R_13     | 107      | R_13    | 276    | R_13     | 1608   | R_13     | 326      | R_13     | 0        | R_13     | 83     | R_13     | 141    | R_13     | 45     | R_13     | 34     | R_13     | 0     | R_13    | 270      | R_13     | 151      | R_13     | 0       | R_13    | 7       | R_13     | 542    | R_13     | 2014   | 4      | 1       | 0        | 0        | 0        | -97.9931789  | 20     | 89     | 23825    | 3067    | 43     | 5761     | 2345     | 2001   | 0     | 0      | house        | STD   | NND    | 
| KS    | KS0138  | KS0231     | NORCATUR PUBLIC LIBRARY   | P O BOX 84         | 84     | DECATUR    | 7856933025 | ME       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 147      | R_13     | 147      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.12     | R_13     | 0       | R_13     | 0.12     | R_13     | 2511   | R_13     | 1060  | R_13    | 0      | R_13     | 1000    | R_13     | 4571    | R_13     |          | H_13   |         | H_13   |          | H_13     | 1025     | R_13     | 0        | R_13     | 500      | R_13     | 1525     | R_13     |          | H_13     | 3525     | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 7780  | R_13    | 0     | R_13    | 80       | R_13     | 0        | R_13     | 30       | R_13     | 0        | R_13     | 0        | R_13     | 51    | R_13    | 51       | R_13    | 0        | R_13    | 664      | R_13     | 370    | R_13     | 0        | R_13    | 100    | R_13     | 1700   | R_13     | 500      | R_13     | 0        | R_13     | 28     | R_13     | 86     | R_13     | 55     | R_13     | 39     | R_13     | 0     | R_13    | 320      | R_13     | 200      | R_13     | 0       | R_13    | 2       | R_13     | 25     | R_13     | 2014   | 4      | 1       | 0        | 0        | 0        | -100.189189  | 20     | 39     | 50925    | 2915    | 43     | 9511     | 1459     | 2001   | 0     | 0      | street       | DGL   | POC    | 
| KS    | KS0060  | KS0014     | AXTELL PUBLIC LIBRARY     | 401 MAPLE          | 9800   | MARSHALL   | 7857362858 | ME       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 401      | R_13     | 401      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.3      | R_13     | 0       | R_13     | 0.3      | R_13     | 5960   | R_13     | 1411  | R_13    | 0      | R_13     | 113     | R_13     | 7484    | R_13     |          | H_13   |         | H_13   |          | H_13     | 1250     | R_13     | 0        | R_13     | 161      | R_13     | 1411     | R_13     |          | H_13     | 7587     | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 5969  | R_13    | 0     | R_13    | 187      | R_13     | 0        | R_13     | 686      | R_13     | 0        | R_13     | 0        | R_13     | 51    | R_13    | 51       | R_13    | 0        | R_13    | 624      | R_13     | 2070   | R_13     | 9        | R_13    | 202    | R_13     | 1835   | R_13     | 897      | R_13     | 0        | R_13     | 3      | R_13     | 0      | R_13     | 2      | R_13     | 2      | R_13     | 0     | R_13    | 22       | R_13     | 22       | R_13     | 0       | R_13    | 4       | R_13     | 629    | R_13     | 2014   | 4      | 1       | 0        | 0        | 0        | -96.2591012  | 20     | 117    | 3600     | 10028   | 43     | 901.86   | 3213     | 2002   | 0     | 0      | house        | STD   | NND    | 
| ME    | ME0292  | 264        | MONROE COMMUNITY LIBRARY  | 8 SWAN LAKE AVENUE | 3505   | WALDO      | 2075253515 | NO       | CI       | SO      | N      | CI2     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 896      | R_13     | 815      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0        | R_13     | 0       | R_13     | 0        | R_13     | 500    | R_13     | 0     | R_13    | 0      | R_13     | 0       | R_13     | 500     | R_13     |          | H_13   |         | H_13   |          | H_13     | 367      | ID13     | 0        | IG12     | 0        | IG12     | 367      | IT13     |          | H_13     | 367      | IT13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 2100  | R_13    | 0     | R_13    | 30       | R_13     | 0        | R_13     | 250      | R_13     | 0        | R_13     | 0        | R_13     | 0     | R_13    | 0        | R_13    | 0        | R_13    | 1664     | R_13     | 600    | R_13     | 658      | IQ13    | 48     | R_13     | 584    | IG12     | 178      | ID13     | 0        | R_13     | 0      | R_13     | 0      | R_13     | 1      | R_13     | 0      | R_13     | 0     | R_13    | 72       | R_13     | 0        | R_13     | 0       | R_13    | 0       | R_13     | 0      | R_13     | 2014   | 1      | 2       | 0        | 0        | 0        | -69.0060583  | 23     | 27     | 0        | 38975   | 42     | 470      | 1094     | 2302   | 0     | 0      | house        | STD   | NND    | 
| ME    | ME0310  | 310        | PALERMO COMMUNITY LIBRARY | PO BOX 102         | 102    | WALDO      | 2079936088 | ME       | NP       | SO      | N      | CI2     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 1542     | R_13     | 1403     | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0        | R_13     | 0       | R_13     | 0        | R_13     | 3712   | IB13     | 0     | IB13    | 0      | IB13     | 2837    | IB13     | 6549    | IG12     |          | H_13   |         | H_13   |          | H_13     | 367      | ID13     | 0        | IG12     | 0        | IG12     | 367      | IT13     |          | H_13     | 2229     | IT13     | 0        | IT13     | 0        | IT13     | 0        | IT13     | 0        | IT13     | 0       | IG12     | 92      | IS13    | 8548  | IG12    | 0     | IG12    | 60       | IP12     | 0        | IS13     | 64       | IG12     | 0        | IS13     | 66       | R_13     | 0     | R_13    | 66       | R_13    | 0        | IG12    | 660      | R_13     | 689    | IG12     | 44       | IG12    | 761    | IG12     | 1302   | IG12     | 397      | ID13     | 0        | R_13     | 2      | ID13     | 5      | IG12     | 18     | ID13     | 11     | IG12     | 2     | IP12    | 135      | IG12     | 81       | ID13     | 10      | IP12    | 3       | IG12     | 1749   | IQ13     | 2014   | 1      | 4       | 0        | 0        | 0        | -69.3948386  | 23     | 27     | 0        | 38975   | 43     | 460.01   | 1051     | 2302   | 0     | 0      | house        | STD   | NND    | 
| ND    | ND0103  | ND0104     | ELGIN PUBLIC LIBRARY      | PO BOX 153         | 153    | GRANT      | 7015842181 | NO       | CI       | SO      | N      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 642      | R_13     | 642      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0        | R_13     | 0       | R_13     | 0        | R_13     | 2300   | R_13     | 431   | R_13    | 0      | R_13     | 10837   | R_13     | 13568   | R_13     |          | H_13   |         | H_13   |          | H_13     | 0        | R_13     | 71       | R_13     | 0        | R_13     | 71       | R_13     |          | H_13     | 6016     | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 9800  | R_13    | 0     | R_13    | 0        | R_13     | 0        | R_13     | 580      | R_13     | 0        | R_13     | 31       | R_13     | 25    | R_13    | 56       | R_13    | 0        | R_13    | 2040     | R_13     | 4029   | R_13     | 1591     | IG11    | 226    | R_13     | 2099   | R_13     | 565      | R_13     | 0        | R_13     | 0      | R_13     | 0      | ID13     | 5      | R_13     | 1      | R_13     | 1     | R_13    | 48       | R_13     | 31       | R_13     | 4       | R_13    | 4       | R_13     | 590    | R_13     | 2014   | 4      | 2       | 0        | 0        | 0        | -101.8455418 | 38     | 37     | 23020    | 2371    | 43     | 9659     | 2846     | 3800   | 0     | 0      | house        | STD   | NND    | 
| NE    | NE0008  | NE0008-003 | ANSLEY TOWNSHIP LIBRARY   | PO BOX 96          | 96     | CUSTER     | -3         | ME       | CI       | SO      | Y      | CI2     | N        | 2012-07-01T00:00:00 | R_13    | 2013-06-30T00:00:00 | R_13     | 586      | R_13     | 586      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | IG11     | 0.24     | IG11     | 0       | IG11     | 0.24     | IT13     | 4492   | IB13     | 0     | IB13    | 0      | IB13     | 223     | IB13     | 4715    | IG11     |          | H_13   |         | H_13   |          | H_13     | 0        | ID13     | 0        | IG11     | 0        | IG11     | 0        | IG11     |          | H_13     | 6486     | IT13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 1827    | IQ13    | 22324 | IG11    | 0     | IG11    | 288      | IP11     | 0        | IS13     | 955      | IG11     | 0        | IS13     | 0        | IB13     | 20    | R_13    | 20       | IP11    | 38       | IG11    | 312      | R_13     | 985    | IG11     | 0        | IG11    | 220    | IG11     | 1193   | IG11     | 355      | ID13     | -1       | U_13     | 0      | ID13     | 0      | IG11     | 8      | ID13     | 6      | IG11     | 0     | IP11    | 87       | IG11     | 71       | ID13     | 0       | IP11    | 5       | IQ13     | 1309   | IQ13     | 2014   | 4      | 4       | 0        | 0        | 0        | -99.3806397  | 31     | 41     | 1535     | 10796   | 43     | 9720     | 2181     | 3103   | 0     | 0      | house        | STD   | NND    | 
| SD    | SD0137  | FSCS 69    | WAGE MEMORIAL LIBRARY     | PO BOX 587         | 587    | BROWN      | 6053978422 | NO       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 1483     | R_13     | 911      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.13     | R_13     | 0       | R_13     | 0.13     | R_13     | 3299   | R_13     | 0     | R_13    | 0      | R_13     | 71      | R_13     | 3370    | R_13     |          | H_13   |         | H_13   |          | H_13     | 458      | R_13     | 0        | R_13     | 185      | R_13     | 643      | R_13     |          | H_13     | 3475     | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 3039  | R_13    | 0     | R_13    | 196      | R_13     | 0        | R_13     | 146      | R_13     | 0        | R_13     | 0        | R_13     | 40    | R_13    | 40       | R_13    | 0        | R_13    | 2340     | R_13     | 800    | R_13     | 0        | R_13    | 1400   | R_13     | 1969   | R_13     | 424      | R_13     | 0        | R_13     | 0      | R_13     | 0      | R_13     | 0      | R_13     | 0      | R_13     | 0     | R_13    | 0        | R_13     | 0        | R_13     | 0       | R_13    | 2       | R_13     | 243    | R_13     | 2014   | 4      | 1       | 0        | 0        | 0        | -98.098644   | 46     | 13     | 26340    | 38162   | 43     | 9519     | 2085     | 4600   | 10100 | 1      | addresspoint | STD   | NND    | 
| SD    | SD0138  | FSCS 73    | TRIPP PUBLIC LIBRARY      | PO BOX 336         | 336    | HUTCHINSON | 6059356222 | NO       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 630      | R_13     | 387      | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.13     | R_13     | 0       | R_13     | 0.13     | R_13     | 4500   | R_13     | 0     | R_13    | 0      | R_13     | 468     | R_13     | 4968    | R_13     |          | H_13   |         | H_13   |          | H_13     | 249      | R_13     | 0        | R_13     | 300      | R_13     | 549      | R_13     |          | H_13     | 4733     | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 6756  | R_13    | 0     | R_13    | 15       | R_13     | 0        | R_13     | 88       | R_13     | 0        | R_13     | 0        | R_13     | 40    | R_13    | 40       | R_13    | 0        | R_13    | 416      | R_13     | 5824   | R_13     | 468      | R_13    | 251    | R_13     | 4089   | R_13     | 2578     | R_13     | 0        | R_13     | 0      | R_13     | 0      | R_13     | 7      | R_13     | 6      | R_13     | 0     | R_13    | 159      | R_13     | 126      | R_13     | 0       | R_13    | 4       | R_13     | 273    | R_13     | 2014   | 4      | 1       | 0        | 0        | 0        | -97.9670374  | 46     | 67     | 64020    | 7170    | 43     | 9688     | 2064     | 4600   | 0     | 0      | house        | STD   | NND    | 
| TX    | TX0077  | 169        | GROVETON PUBLIC LIBRARY   | PO BOX 399         | 399    | TRINITY    | 9366422483 | NO       | CI       | SO      | Y      | CI1     | N        | 2013-01-01T00:00:00 | R_13    | 2013-12-31T00:00:00 | R_13     | 1036     | R_13     | 1036     | R_13     | 1       | R_13     | 0       | R_13    | 0     | R_13    | 0      | R_13     | 0.5      | R_13     | 0.5     | R_13     | 1        | R_13     | 21393  | R_13     | 0     | R_13    | 0      | R_13     | 357     | R_13     | 21750   | R_13     |          | H_13   |         | H_13   |          | H_13     | 915      | R_13     | 0        | R_13     | 0        | R_13     | 915      | R_13     |          | H_13     | 19939    | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0        | R_13     | 0       | R_13     | 0       | R_13    | 7280  | R_13    | 0     | R_13    | 61       | R_13     | 0        | R_13     | 280      | R_13     | 0        | R_13     | 0        | R_13     | 0     | R_13    | 0        | R_13    | 5        | R_13    | 1968     | R_13     | 2998   | R_13     | 494      | R_13    | 593    | R_13     | 2469   | R_13     | 250      | R_13     | 0        | R_13     | 0      | R_13     | 0      | R_13     | 0      | R_13     | 0      | R_13     | 0     | R_13    | 0        | R_13     | 0        | R_13     | 0       | R_13    | 2       | R_13     | 1750   | R_13     | 2014   | 6      | 1       | 0        | 0        | 0        | -95.1366214  | 48     | 455    | 31340    | 14401   | 43     | 9502     | 1020     | 4808   | 26660 | 1      | street       | DGL   | POC    | 
```