# Library Systems: FY 2012 Public Libraries Survey (Administrative Entity)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-systems-fy-2012-public-libraries-survey-administrative-entity) |
| Metadata | [Link](https://data.imls.gov/api/views/9fbc-csi5) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/9fbc-csi5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/9fbc-csi5/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 9fbc-csi5 |
| Name | Library Systems: FY 2012 Public Libraries Survey (Administrative Entity) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, administrative entity, 2012 |
| Created | 2014-08-13T16:13:07Z |
| Publication Date | 2014-08-20T13:59:54Z |

## Description

Find key information on library systems around the United States.<br><br>These data include imputed values for libraries that did not submit information in the FY 2012 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2012 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | stabr      | STABR    | text          | text          |
| Yes      | series tag     | fscskey    | FSCSKEY  | text          | text          |
| Yes      | series tag     | libid      | LIBID    | text          | text          |
| Yes      | series tag     | libname    | LIBNAME  | text          | text          |
| Yes      | series tag     | addres_m   | ADDRES_M | text          | text          |
| Yes      | series tag     | zip4_m     | ZIP4_M   | text          | number        |
| Yes      | series tag     | cnty       | CNTY     | text          | text          |
| Yes      | series tag     | phone      | PHONE    | text          | number        |
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
| Yes      | numeric metric | locgvt     | LOCGVT   | number        | number        |
| Yes      | series tag     | f_locgvt   | F_LOCGVT | text          | text          |
| Yes      | numeric metric | stgvt      | STGVT    | number        | number        |
| Yes      | series tag     | f_stgvt    | F_STGVT  | text          | text          |
| Yes      | numeric metric | fedgvt     | FEDGVT   | number        | number        |
| Yes      | series tag     | f_fedgvt   | F_FEDGVT | text          | text          |
| Yes      | numeric metric | othincm    | OTHINCM  | number        | number        |
| Yes      | series tag     | f_othinc   | F_OTHINC | text          | text          |
| Yes      | numeric metric | totincm    | TOTINCM  | number        | number        |
| Yes      | series tag     | f_totinc   | F_TOTINC | text          | text          |
| Yes      | numeric metric | benefit    | BENEFIT  | number        | number        |
| Yes      | series tag     | f_benx     | F_BENX   | text          | text          |
| Yes      | numeric metric | staffexp   | STAFFEXP | number        | number        |
| Yes      | series tag     | f_tostfx   | F_TOSTFX | text          | text          |
| Yes      | numeric metric | prmatexp   | PRMATEXP | number        | number        |
| Yes      | series tag     | f_prmatx   | F_PRMATX | text          | text          |
| Yes      | numeric metric | elmatexp   | ELMATEXP | number        | number        |
| Yes      | series tag     | f_elmatx   | F_ELMATX | text          | text          |
| Yes      | numeric metric | othmatex   | OTHMATEX | number        | number        |
| Yes      | series tag     | f_otmatx   | F_OTMATX | text          | text          |
| Yes      | numeric metric | totexpco   | TOTEXPCO | number        | number        |
| Yes      | series tag     | f_tocolx   | F_TOCOLX | text          | text          |
| Yes      | numeric metric | othopexp   | OTHOPEXP | number        | number        |
| Yes      | series tag     | f_othopx   | F_OTHOPX | text          | text          |
| Yes      | numeric metric | totopexp   | TOTOPEXP | number        | number        |
| Yes      | series tag     | f_totopx   | F_TOTOPX | text          | text          |
| Yes      | numeric metric | lcap_rev   | LCAP_REV | number        | number        |
| Yes      | series tag     | f_lcaprv   | F_LCAPRV | text          | text          |
| Yes      | numeric metric | scap_rev   | SCAP_REV | number        | number        |
| Yes      | series tag     | f_scaprv   | F_SCAPRV | text          | text          |
| Yes      | numeric metric | fcap_rev   | FCAP_REV | number        | number        |
| Yes      | series tag     | f_fcaprv   | F_FCAPRV | text          | text          |
| Yes      | numeric metric | ocap_rev   | OCAP_REV | number        | number        |
| Yes      | series tag     | f_ocaprv   | F_OCAPRV | text          | text          |
| Yes      | numeric metric | cap_rev    | CAP_REV  | number        | number        |
| Yes      | series tag     | f_tcaprv   | F_TCAPRV | text          | text          |
| Yes      | numeric metric | capital    | CAPITAL  | number        | number        |
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
series e:9fbc-csi5 d:2011-07-01T00:00:00.000Z t:f_enddat=R_12 t:phone=9072355692 t:f_othstf=R_12 t:f_totinc=R_12 t:postms=POC t:f_fcaprv=R_12 t:f_kidcir=R_12 t:c_admin=SO t:c_fscs=Y t:f_bkmob=R_12 t:fipsco=122 t:f_stdat=R_12 t:f_totstf=R_12 t:f_prsub=R_12 t:f_lcaprv=R_12 t:f_prmatx=R_12 t:f_ebook=R_12 t:f_loanfm=R_12 t:othpaid=0 t:f_kidpro=R_12 t:f_tostfx=H_12 t:f_popund=R_12 t:f_tcapx=R_12 t:addres_m="P.O. BOX 129" t:f_locgvt=R_12 t:f_benx=H_12 t:f_othopx=H_12 t:f_loanto=R_12 t:f_othinc=R_12 t:f_tocolx=R_12 t:f_kidatt=R_12 t:f_vid_dl=R_12 t:f_dbase=R_12 t:f_db_l_o=R_12 t:f_master=R_12 t:f_yapro=R_12 t:f_totopx=R_12 t:f_db_st=R_12 t:f_scaprv=R_12 t:f_vid_ph=R_12 t:geocode=CI1 t:f_yaatt=R_12 t:libid=AK0001-002 t:f_pitusr=R_12 t:libname="ANCHOR POINT PUBLIC LIBRARY" t:f_aud_dl=R_12 t:f_otmatx=R_12 t:f_elmatx=R_12 t:gal=street t:fipsst=2 t:f_aud_ph=R_12 t:zip4_m=129 t:f_gpterm=R_12 t:f_bkvol=R_12 t:f_librar=R_12 t:stabr=AK t:f_poplsa=R_12 t:rstatus=1 t:lsabound=N t:f_visits=R_12 t:f_hrs_op=R_12 t:f_fedgvt=R_12 t:f_ocaprv=R_12 t:c_relatn=NO t:f_totcir=R_12 t:f_totatt=R_12 t:cnty="KENAI PENINSULA" t:f_regbor=R_12 t:f_brlib=R_12 t:fscskey=AK0001 t:f_tcaprv=R_12 t:galms=DGL t:fipsplac=3110 t:f_cenlib=R_12 t:f_refer=R_12 t:f_stgvt=R_12 t:cdcode=200 t:f_totpro=R_12 t:c_legbas=NP m:microf=0 m:db_lo_ot=0 m:kidcircl=1344 m:yapro=0 m:bkvol=16433 m:capital=0 m:referenc=600 m:video_ph=4627 m:pitusr=1955 m:video_dl=0 m:statstru=0 m:prmatexp=2206 m:cenblock=3013 m:loanfm=40 m:stataddr=0 m:totexpco=3156 m:totincm=29323 m:totcir=16646 m:othincm=12518 m:lcap_rev=0 m:obereg=8 m:yr_sub=2013 m:fedgvt=3080 m:totatten=346 m:yaatten=0 m:bkmob=0 m:cbsa=0 m:cap_rev=0 m:popu_und=2007 m:kidpro=20 m:totpro=23 m:kidatten=335 m:fcap_rev=0 m:locale=43 m:gpterms=8 m:audio_ph=466 m:ebook=0 m:hrs_open=1415 m:statname=0 m:libraria=0.68 m:subscrip=6 m:elmatexp=0 m:loanto=0 m:branlib=0 m:centlib=1 m:locgvt=7225 m:master=0 m:database=49 m:totopexp=17431 m:cntypop=56884 m:audio_dl=0 m:othmatex=950 m:db_st=49 m:ocap_rev=0 m:regbor=477 m:popu_lsa=2007 m:totstaff=0.68 m:centract=8 m:scap_rev=0 m:stgvt=6500 m:visits=8564

series e:9fbc-csi5 d:2011-01-01T00:00:00.000Z t:f_enddat=R_12 t:phone=9073432982 t:f_othstf=R_12 t:f_totinc=R_12 t:postms=NND t:f_fcaprv=R_12 t:f_kidcir=R_12 t:c_admin=MO t:c_fscs=Y t:f_bkmob=R_12 t:fipsco=20 t:f_stdat=R_12 t:f_totstf=R_12 t:f_prsub=R_12 t:f_lcaprv=R_12 t:f_prmatx=R_12 t:f_ebook=R_12 t:f_loanfm=R_12 t:othpaid=51.33 t:f_kidpro=R_12 t:f_tostfx=R_12 t:f_popund=R_12 t:f_tcapx=R_12 t:addres_m="3600 DENALI STREET" t:f_locgvt=R_12 t:f_benx=R_12 t:f_othopx=R_12 t:f_loanto=R_12 t:f_othinc=R_12 t:f_tocolx=R_12 t:f_kidatt=R_12 t:f_vid_dl=R_12 t:f_dbase=R_12 t:f_db_l_o=R_12 t:f_master=R_12 t:f_yapro=R_12 t:f_totopx=R_12 t:f_db_st=R_12 t:f_scaprv=R_12 t:f_vid_ph=R_12 t:geocode=MA1 t:f_yaatt=R_12 t:libid=AK0002-011 t:f_pitusr=R_12 t:libname="ANCHORAGE PUBLIC LIBRARY" t:f_aud_dl=R_12 t:f_otmatx=R_12 t:f_elmatx=R_12 t:gal=addresspoint t:fipsst=2 t:f_aud_ph=R_12 t:zip4_m=6055 t:f_gpterm=R_12 t:f_bkvol=R_12 t:f_librar=R_12 t:stabr=AK t:f_poplsa=R_12 t:rstatus=1 t:lsabound=N t:f_visits=R_12 t:f_hrs_op=R_12 t:f_fedgvt=R_12 t:f_ocaprv=R_12 t:c_relatn=NO t:f_totcir=R_12 t:f_totatt=R_12 t:cnty=ANCHORAGE t:f_regbor=R_12 t:f_brlib=R_12 t:fscskey=AK0002 t:f_tcaprv=R_12 t:galms=STD t:fipsplac=3000 t:f_cenlib=R_12 t:f_refer=R_12 t:f_stgvt=R_12 t:cdcode=200 t:f_totpro=R_12 t:c_legbas=CO m:staffexp=6279229 m:microf=0 m:benefit=2621241 m:db_lo_ot=17 m:kidcircl=650437 m:yapro=159 m:bkvol=509906 m:capital=0 m:referenc=145964 m:video_ph=59076 m:pitusr=137135 m:statstru=0 m:video_dl=0 m:prmatexp=525401 m:cenblock=3002 m:loanfm=1153 m:stataddr=0 m:totexpco=879820 m:totincm=9995236 m:othincm=263659 m:totcir=1609402 m:lcap_rev=0 m:obereg=8 m:yr_sub=2013 m:totatten=51452 m:fedgvt=109425 m:yaatten=3521 m:bkmob=0 m:cbsa=11260 m:cap_rev=1956000 m:othopexp=3193524 m:popu_und=298842 m:kidatten=33222 m:totpro=1005 m:kidpro=712 m:fcap_rev=0 m:locale=11 m:gpterms=130 m:audio_ph=30791 m:ebook=54298 m:hrs_open=10608 m:statname=0 m:libraria=27.73 m:subscrip=880 m:elmatexp=169568 m:loanto=6092 m:branlib=4 m:centlib=1 m:locgvt=9570884 m:master=22.98 m:totopexp=10352573 m:database=66 m:cntypop=298294 m:audio_dl=7871 m:othmatex=184851 m:db_st=49 m:ocap_rev=0 m:regbor=202827 m:popu_lsa=298842 m:totstaff=79.06 m:centract=19 m:scap_rev=1956000 m:stgvt=51268 m:visits=739884

series e:9fbc-csi5 d:2011-07-01T00:00:00.000Z t:f_enddat=R_12 t:phone=9075822628 t:f_othstf=R_12 t:f_totinc=R_12 t:postms=NND t:f_fcaprv=R_12 t:f_kidcir=R_12 t:c_admin=SO t:c_fscs=Y t:f_bkmob=R_12 t:fipsco=68 t:f_stdat=R_12 t:f_totstf=R_12 t:f_prsub=R_12 t:f_lcaprv=R_12 t:f_prmatx=R_12 t:f_ebook=R_12 t:f_loanfm=R_12 t:othpaid=0.3 t:f_kidpro=R_12 t:f_tostfx=H_12 t:f_popund=R_12 t:f_tcapx=R_12 t:addres_m="P.O. BOX 3078" t:f_locgvt=R_12 t:f_benx=H_12 t:f_othopx=H_12 t:f_loanto=R_12 t:f_othinc=R_12 t:f_tocolx=R_12 t:f_kidatt=R_12 t:f_vid_dl=R_12 t:f_dbase=R_12 t:f_db_l_o=R_12 t:f_master=R_12 t:f_yapro=R_12 t:f_totopx=R_12 t:f_db_st=R_12 t:f_scaprv=R_12 t:f_vid_ph=R_12 t:geocode=CI1 t:f_yaatt=R_12 t:libid=AK0003-002 t:f_pitusr=R_12 t:libname="ANDERSON VILLAGE LIBRARY" t:f_aud_dl=R_12 t:f_otmatx=R_12 t:f_elmatx=R_12 t:gal=house t:fipsst=2 t:f_aud_ph=R_12 t:zip4_m=3078 t:f_gpterm=R_12 t:f_bkvol=R_12 t:f_librar=R_12 t:stabr=AK t:f_poplsa=R_12 t:rstatus=1 t:lsabound=N t:f_visits=R_12 t:f_hrs_op=R_12 t:f_fedgvt=R_12 t:f_ocaprv=R_12 t:c_relatn=NO t:f_totcir=R_12 t:f_totatt=R_12 t:cnty=DENALI t:f_regbor=R_12 t:f_brlib=R_12 t:fscskey=AK0003 t:f_tcaprv=R_12 t:galms=STD t:fipsplac=3220 t:f_cenlib=R_12 t:f_refer=R_12 t:f_stgvt=R_12 t:cdcode=200 t:f_totpro=R_12 t:c_legbas=CI m:microf=0 m:db_lo_ot=0 m:kidcircl=205 m:yapro=1 m:bkvol=14600 m:capital=0 m:referenc=100 m:video_ph=1260 m:pitusr=370 m:video_dl=0 m:statstru=0 m:prmatexp=2119 m:cenblock=1011 m:loanfm=5 m:stataddr=0 m:totexpco=2892 m:totincm=15333 m:totcir=1375 m:othincm=1333 m:lcap_rev=0 m:obereg=8 m:yr_sub=2013 m:fedgvt=0 m:totatten=19 m:yaatten=5 m:bkmob=0 m:cbsa=0 m:cap_rev=0 m:popu_und=240 m:kidpro=2 m:totpro=4 m:kidatten=10 m:fcap_rev=0 m:locale=43 m:gpterms=2 m:audio_ph=48 m:ebook=0 m:hrs_open=612 m:statname=0 m:libraria=0.3 m:subscrip=15 m:elmatexp=0 m:loanto=0 m:branlib=0 m:centlib=1 m:locgvt=7500 m:master=0 m:database=49 m:totopexp=12078 m:cntypop=1860 m:audio_dl=0 m:othmatex=773 m:db_st=49 m:ocap_rev=0 m:regbor=200 m:popu_lsa=240 m:totstaff=0.6 m:centract=1 m:scap_rev=0 m:stgvt=6500 m:visits=1132
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

metric m:locgvt p:integer l:LOCGVT t:dataTypeName=number

metric m:stgvt p:integer l:STGVT t:dataTypeName=number

metric m:fedgvt p:integer l:FEDGVT t:dataTypeName=number

metric m:othincm p:integer l:OTHINCM t:dataTypeName=number

metric m:totincm p:integer l:TOTINCM t:dataTypeName=number

metric m:benefit p:integer l:BENEFIT t:dataTypeName=number

metric m:staffexp p:integer l:STAFFEXP t:dataTypeName=number

metric m:prmatexp p:integer l:PRMATEXP t:dataTypeName=number

metric m:elmatexp p:integer l:ELMATEXP t:dataTypeName=number

metric m:othmatex p:integer l:OTHMATEX t:dataTypeName=number

metric m:totexpco p:integer l:TOTEXPCO t:dataTypeName=number

metric m:othopexp p:integer l:OTHOPEXP t:dataTypeName=number

metric m:totopexp p:integer l:TOTOPEXP t:dataTypeName=number

metric m:lcap_rev p:integer l:LCAP_REV t:dataTypeName=number

metric m:scap_rev p:integer l:SCAP_REV t:dataTypeName=number

metric m:fcap_rev p:integer l:FCAP_REV t:dataTypeName=number

metric m:ocap_rev p:integer l:OCAP_REV t:dataTypeName=number

metric m:cap_rev p:integer l:CAP_REV t:dataTypeName=number

metric m:capital p:integer l:CAPITAL t:dataTypeName=number

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

entity e:9fbc-csi5 l:"Library Systems: FY 2012 Public Libraries Survey (Administrative Entity)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9fbc-csi5

property e:9fbc-csi5 t:meta.view v:id=9fbc-csi5 v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Library Systems: FY 2012 Public Libraries Survey (Administrative Entity)" v:attribution=IMLS

property e:9fbc-csi5 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9fbc-csi5 t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:9fbc-csi5 t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:9fbc-csi5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stabr | fscskey | libid      | libname                          | addres_m           | zip4_m | cnty              | phone      | c_relatn | c_legbas | c_admin | c_fscs | geocode | lsabound | startdat            | f_stdat | enddate             | f_enddat | popu_lsa | f_poplsa | popu_und | f_popund | centlib | f_cenlib | branlib | f_brlib | bkmob | f_bkmob | master | f_master | libraria | f_librar | othpaid | f_othstf | totstaff | f_totstf | locgvt  | f_locgvt | stgvt | f_stgvt | fedgvt | f_fedgvt | othincm | f_othinc | totincm | f_totinc | benefit | f_benx | staffexp | f_tostfx | prmatexp | f_prmatx | elmatexp | f_elmatx | othmatex | f_otmatx | totexpco | f_tocolx | othopexp | f_othopx | totopexp | f_totopx | lcap_rev | f_lcaprv | scap_rev | f_scaprv | fcap_rev | f_fcaprv | ocap_rev | f_ocaprv | cap_rev | f_tcaprv | capital | f_tcapx | bkvol  | f_bkvol | ebook | f_ebook | audio_ph | f_aud_ph | audio_dl | f_aud_dl | video_ph | f_vid_ph | video_dl | f_vid_dl | db_lo_ot | f_db_l_o | db_st | f_db_st | database | f_dbase | subscrip | f_prsub | hrs_open | f_hrs_op | visits | f_visits | referenc | f_refer | regbor | f_regbor | totcir  | f_totcir | kidcircl | f_kidcir | loanto | f_loanto | loanfm | f_loanfm | totpro | f_totpro | kidpro | f_kidpro | yapro | f_yapro | totatten | f_totatt | kidatten | f_kidatt | yaatten | f_yaatt | gpterms | f_gpterm | pitusr | f_pitusr | yr_sub | obereg | rstatus | statstru | statname | stataddr | longitud    | fipsst | fipsco | fipsplac | cntypop | locale | centract | cenblock | cdcode | cbsa  | microf | gal             | galms | postms | 
| ===== | ======= | ========== | ================================ | ================== | ====== | ================= | ========== | ======== | ======== | ======= | ====== | ======= | ======== | =================== | ======= | =================== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ===== | ======= | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ===== | ======= | ====== | ======== | ======= | ======== | ======= | ======== | ======= | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ====== | ======= | ===== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ===== | ======= | ======== | ======= | ======== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ====== | ======== | ======= | ======== | ======== | ======== | ====== | ======== | ====== | ======== | ====== | ======== | ====== | ======== | ===== | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======== | ====== | ======== | ====== | ====== | ======= | ======== | ======== | ======== | =========== | ====== | ====== | ======== | ======= | ====== | ======== | ======== | ====== | ===== | ====== | =============== | ===== | ====== | 
| AK    | AK0001  | AK0001-002 | ANCHOR POINT PUBLIC LIBRARY      | P.O. BOX 129       | 129    | KENAI PENINSULA   | 9072355692 | NO       | NP       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 2007     | R_12     | 2007     | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0.68     | R_12     | 0       | R_12     | 0.68     | R_12     | 7225    | R_12     | 6500  | R_12    | 3080   | R_12     | 12518   | R_12     | 29323   | R_12     |         | H_12   |          | H_12     | 2206     | R_12     | 0        | R_12     | 950      | R_12     | 3156     | R_12     |          | H_12     | 17431    | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 16433  | R_12    | 0     | R_12    | 466      | R_12     | 0        | R_12     | 4627     | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 6        | R_12    | 1415     | R_12     | 8564   | R_12     | 600      | R_12    | 477    | R_12     | 16646   | R_12     | 1344     | R_12     | 0      | R_12     | 40     | R_12     | 23     | R_12     | 20     | R_12     | 0     | R_12    | 346      | R_12     | 335      | R_12     | 0       | R_12    | 8       | R_12     | 1955   | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -151.843873 | 2      | 122    | 3110     | 56884   | 43     | 8        | 3013     | 200    | 0     | 0      | street          | DGL   | POC    | 
| AK    | AK0002  | AK0002-011 | ANCHORAGE PUBLIC LIBRARY         | 3600 DENALI STREET | 6055   | ANCHORAGE         | 9073432982 | NO       | CO       | MO      | Y      | MA1     | N        | 2011-01-01T00:00:00 | R_12    | 2011-12-31T00:00:00 | R_12     | 298842   | R_12     | 298842   | R_12     | 1       | R_12     | 4       | R_12    | 0     | R_12    | 22.98  | R_12     | 27.73    | R_12     | 51.33   | R_12     | 79.06    | R_12     | 9570884 | R_12     | 51268 | R_12    | 109425 | R_12     | 263659  | R_12     | 9995236 | R_12     | 2621241 | R_12   | 6279229  | R_12     | 525401   | R_12     | 169568   | R_12     | 184851   | R_12     | 879820   | R_12     | 3193524  | R_12     | 10352573 | R_12     | 0        | R_12     | 1956000  | R_12     | 0        | R_12     | 0        | R_12     | 1956000 | R_12     | 0       | R_12    | 509906 | R_12    | 54298 | R_12    | 30791    | R_12     | 7871     | R_12     | 59076    | R_12     | 0        | R_12     | 17       | R_12     | 49    | R_12    | 66       | R_12    | 880      | R_12    | 10608    | R_12     | 739884 | R_12     | 145964   | R_12    | 202827 | R_12     | 1609402 | R_12     | 650437   | R_12     | 6092   | R_12     | 1153   | R_12     | 1005   | R_12     | 712    | R_12     | 159   | R_12    | 51452    | R_12     | 33222    | R_12     | 3521    | R_12    | 130     | R_12     | 137135 | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -149.876781 | 2      | 20     | 3000     | 298294  | 11     | 19       | 3002     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0003  | AK0003-002 | ANDERSON VILLAGE LIBRARY         | P.O. BOX 3078      | 3078   | DENALI            | 9075822628 | NO       | CI       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 240      | R_12     | 240      | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0.3      | R_12     | 0.3     | R_12     | 0.6      | R_12     | 7500    | R_12     | 6500  | R_12    | 0      | R_12     | 1333    | R_12     | 15333   | R_12     |         | H_12   |          | H_12     | 2119     | R_12     | 0        | R_12     | 773      | R_12     | 2892     | R_12     |          | H_12     | 12078    | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 14600  | R_12    | 0     | R_12    | 48       | R_12     | 0        | R_12     | 1260     | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 15       | R_12    | 612      | R_12     | 1132   | R_12     | 100      | R_12    | 200    | R_12     | 1375    | R_12     | 205      | R_12     | 0      | R_12     | 5      | R_12     | 4      | R_12     | 2      | R_12     | 1     | R_12    | 19       | R_12     | 10       | R_12     | 5       | R_12    | 2       | R_12     | 370    | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -149.178635 | 2      | 68     | 3220     | 1860    | 43     | 1        | 1011     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0006  | AK0006-002 | KUSKOKWIM CONSORTIUM LIBRARY     | P.O. BOX 368       | 368    | BETHEL            | 9075434516 | NO       | MJ       | SO      | Y      | CI1     | N        | 2011-01-01T00:00:00 | R_12    | 2011-12-31T00:00:00 | R_12     | 6113     | R_12     | 6113     | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 2        | R_12     | 1       | R_12     | 3        | R_12     | 72822   | R_12     | 6500  | R_12    | 0      | R_12     | 202706  | R_12     | 282028  | R_12     | 85591   | R_12   | 260156   | R_12     | 6890     | R_12     | 0        | R_12     | 2804     | R_12     | 9694     | R_12     | 7790     | R_12     | 277640   | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 36042  | R_12    | 163   | R_12    | 843      | R_12     | 0        | R_12     | 2628     | R_12     | 0        | R_12     | 151      | R_12     | 49    | R_12    | 200      | R_12    | 57       | R_12    | 2622     | R_12     | 23920  | R_12     | 624      | R_12    | 3150   | R_12     | 12994   | R_12     | 2359     | R_12     | 52     | R_12     | 100    | R_12     | 151    | R_12     | 95     | R_12     | 1     | R_12    | 1448     | R_12     | 991      | R_12     | 12      | R_12    | 7       | R_12     | 15600  | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -161.760366 | 2      | 50     | 6520     | 17653   | 41     | 2        | 2012     | 200    | 0     | 0      | house           | STD   | NND    | 
| AK    | AK0007  | AK0007-002 | BIG LAKE PUBLIC LIBRARY          | P.O. BOX 520829    | 829    | MATANUSKA-SUSITNA | 9078926475 | NO       | CO       | SO      | Y      | CO1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 9864     | R_12     | 9864     | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 1        | R_12     | 2.32    | R_12     | 3.32     | R_12     | 331340  | R_12     | 6500  | R_12    | 2493   | R_12     | 0       | R_12     | 340333  | R_12     | 78567   | R_12   | 227482   | R_12     | 20737    | R_12     | 0        | R_12     | 0        | R_12     | 20737    | R_12     | 50645    | R_12     | 298864   | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 23318  | R_12    | 6280  | R_12    | 1859     | R_12     | 7871     | R_12     | 2264     | R_12     | 0        | R_12     | 1        | R_12     | 49    | R_12    | 50       | R_12    | 0        | R_12    | 2568     | R_12     | 40696  | R_12     | 8009     | R_12    | 2720   | R_12     | 42568   | R_12     | 21820    | R_12     | 85     | R_12     | 94     | R_12     | 168    | R_12     | 147    | R_12     | 8     | R_12    | 6560     | R_12     | 5171     | R_12     | 1229    | R_12    | 19      | R_12     | 12764  | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -149.818403 | 2      | 170    | 7070     | 93845   | 42     | 5.02     | 1004     | 200    | 11260 | 0      | addresspoint    | STD   | NND    | 
| AK    | AK0008  | AK0008-002 | CANTWELL COMMUNITY LIBRARY       | P.O. BOX 185       | 185    | DENALI            | 9077682372 | NO       | NP       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 207      | R_12     | 207      | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0.38     | R_12     | 0.38    | R_12     | 0.76     | R_12     | 4000    | R_12     | 6500  | R_12    | 7000   | R_12     | 2511    | R_12     | 20011   | R_12     |         | H_12   |          | H_12     | 5190     | R_12     | 0        | R_12     | 567      | R_12     | 5757     | R_12     |          | H_12     | 19602    | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 13503  | R_12    | 0     | R_12    | 493      | R_12     | 0        | R_12     | 689      | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 0        | R_12    | 750      | R_12     | 2871   | R_12     | 400      | R_12    | 189    | R_12     | 4775    | R_12     | 2550     | R_12     | 40     | R_12     | 53     | R_12     | 24     | R_12     | 16     | R_12     | 5     | R_12    | 218      | R_12     | 92       | R_12     | 61      | R_12    | 3       | R_12     | 1000   | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -148.757407 | 2      | 68     | 10150    | 1860    | 43     | 1        | 2369     | 200    | 0     | 0      | postalcode-main | NCF   | POC    | 
| AK    | AK0011  | AK0011-002 | CHINIAK PUBLIC LIBRARY           | P.O. BOX 5610      | 5610   | KODIAK ISLAND     | 9074863022 | NO       | NP       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 44       | R_12     | 44       | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0        | R_12     | 0.1     | R_12     | 0.1      | R_12     | 3000    | R_12     | 6500  | R_12    | 31903  | R_12     | 0       | R_12     | 41403   | R_12     |         | H_12   |          | H_12     | 2474     | R_12     | 0        | R_12     | 1126     | R_12     | 3600     | R_12     |          | H_12     | 47837    | R_12     | 3000     | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 3000    | R_12     | 3000    | R_12    | 3800   | R_12    | 0     | R_12    | 246      | R_12     | 0        | R_12     | 650      | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 24       | R_12    | 672      | R_12     | 960    | R_12     | 125      | R_12    | 44     | R_12     | 625     | R_12     | 150      | R_12     | 0      | R_12     | 2      | R_12     | 50     | R_12     | 20     | R_12     | 0     | R_12    | 435      | R_12     | 215      | R_12     | 0       | R_12    | 4       | R_12     | 256    | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -152.232581 | 2      | 150    | 13860    | 14118   | 43     | 1        | 3123     | 200    | 0     | 0      | street          | DGL   | POC    | 
| AK    | AK0014  | AK0014-002 | COLD BAY PUBLIC LIBRARY          | P.O. BOX 87        | 87     | ALEUTIANS EAST    | 9075322878 | NO       | NP       | SO      | N      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 98       | R_12     | 98       | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0        | R_12     | 0       | R_12     | 0        | R_12     | 3300    | R_12     | 6500  | R_12    | 50568  | R_12     | 0       | R_12     | 60368   | R_12     |         | H_12   |          | H_12     | 2285     | R_12     | 124      | R_12     | 1408     | R_12     | 3817     | R_12     |          | H_12     | 59768    | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 0       | R_12     | 0       | R_12    | 7397   | R_12    | 0     | R_12    | 210      | R_12     | 0        | R_12     | 3197     | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 20       | R_12    | 500      | R_12     | 1626   | R_12     | 75       | R_12    | 137    | R_12     | 2514    | R_12     | 1355     | R_12     | 0      | R_12     | 0      | R_12     | 40     | R_12     | 40     | R_12     | 0     | R_12    | 328      | R_12     | 328      | R_12     | 0       | R_12    | 6       | R_12     | 390    | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -162.713392 | 2      | 13     | 16530    | 3139    | 43     | 1        | 1260     | 200    | 0     | 0      | street          | DGL   | POC    | 
| AK    | AK0015  | AK0015-002 | COOPER LANDING COMMUNITY LIBRARY | P.O. BOX 517       | 517    | KENAI PENINSULA   | 9075951241 | NO       | NP       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 293      | R_12     | 293      | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 0        | R_12     | 0.1     | R_12     | 0.1      | R_12     | 489     | R_12     | 6500  | R_12    | 9195   | R_12     | 21181   | R_12     | 37365   | R_12     |         | H_12   |          | H_12     | 5075     | R_12     | 0        | R_12     | 628      | R_12     | 5703     | R_12     |          | H_12     | 30999    | R_12     | 0        | R_12     | 0        | R_12     | 0        | R_12     | 1400     | R_12     | 1400    | R_12     | 2910    | R_12    | 2897   | R_12    | 0     | R_12    | 231      | R_12     | 0        | R_12     | 680      | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 0        | R_12    | 1116     | R_12     | 3208   | R_12     | 138      | R_12    | 654    | R_12     | 3206    | R_12     | 1119     | R_12     | 0      | R_12     | 80     | R_12     | 91     | R_12     | 55     | R_12     | 0     | R_12    | 944      | R_12     | 668      | R_12     | 0       | R_12    | 3       | R_12     | 327    | R_12     | 2013   | 8      | 1       | 0        | 0        | 0        | -150.010519 | 2      | 122    | 0        | 56884   | 43     | 4        | 1001     | 200    | 0     | 0      | postalcode-main | NCF   | POC    | 
| AK    | AK0016  | AK0016-002 | CORDOVA PUBLIC LIBRARY           | P.O. BOX 1210      | 1210   | VALDEZ-CORDOVA    | 9074246667 | NO       | CI       | SO      | Y      | CI1     | N        | 2011-07-01T00:00:00 | R_12    | 2012-06-30T00:00:00 | R_12     | 2316     | R_12     | 2316     | R_12     | 1       | R_12     | 0       | R_12    | 0     | R_12    | 0      | R_12     | 3.17     | R_12     | 2       | R_12     | 5.17     | R_12     | 324156  | R_12     | 6500  | R_12    | 0      | R_12     | 11969   | R_12     | 342625  | R_12     | 96990   | R_12   | 295079   | R_12     | 12123    | R_12     | 3000     | R_12     | 2536     | R_12     | 17659    | R_12     | 17918    | R_12     | 330656   | R_12     | 870904   | R_12     | 5397994  | R_12     | 609170   | R_12     | 0        | R_12     | 6878068 | R_12     | 6878068 | R_12    | 20690  | R_12    | 6280  | R_12    | 623      | R_12     | 7871     | R_12     | 1480     | R_12     | 0        | R_12     | 0        | R_12     | 49    | R_12    | 49       | R_12    | 53       | R_12    | 2414     | R_12     | 27055  | R_12     | 259      | R_12    | 2189   | R_12     | 12927   | R_12     | 3742     | ID12     | 0      | R_12     | 462    | R_12     | 27     | R_12     | 27     | R_12     | 0     | R_12    | 331      | R_12     | 331      | R_12     | 0       | R_12    | 5       | R_12     | 8139   | R_12     | 2013   | 8      | 2       | 0        | 0        | 0        | -145.766031 | 2      | 261    | 17410    | 9728    | 43     | 2        | 2000     | 200    | 0     | 0      | house           | STD   | NND    | 
```