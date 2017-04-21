# State Libraries Survey, FY 2012, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2012-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/9j5w-shf3) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/9j5w-shf3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/9j5w-shf3/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 9j5w-shf3 |
| Name | State Libraries Survey, FY 2012, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2012, revenue, expenditures |
| Created | 2016-12-20T15:33:43Z |
| Publication Date | 2016-12-20T17:04:43Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                               | Data Type | Render Type |
| ======== | ============== | ========== | ================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                          | text      | text        |
| Yes      | series tag     | physaddr   | Street                             | text      | text        |
| Yes      | series tag     | physcity   | City                               | text      | text        |
| Yes      | series tag     | phys_st    | State                              | text      | text        |
| Yes      | series tag     | physzip    | Zip                                | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                              | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                      | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                        | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                       | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                         | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                       | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                        | text      | text        |
| Yes      | series tag     | asf_pub    | Admins state funds                 | text      | text        |
| Yes      | series tag     | asf_ac     | Admins state funds acad            | text      | text        |
| Yes      | series tag     | asf_sch    | Admins state funds school          | text      | text        |
| Yes      | series tag     | asf_sp     | Admins state funds special         | text      | text        |
| Yes      | series tag     | asf_lc     | Admins state funds co-ops          | text      | text        |
| Yes      | series tag     | fiothsp    | Other fed rev specified            | text      | text        |
| Yes      | series tag     | fipsst     | FIPS state code                    | text      | text        |
| Yes      | series tag     | obereg     | BEA code                           | text      | text        |
| Yes      | series tag     | rstatus    | Reporting Status                   | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy   | date      | date        |
| Yes      | numeric metric | lstainc    | LSTA revenue                       | money     | money       |
| Yes      | numeric metric | fioth      | Other federal revenue              | money     | money       |
| Yes      | numeric metric | total_fi   | Total federal revenue              | money     | money       |
| Yes      | numeric metric | sistlaop   | St rev STLA operation              | money     | money       |
| Yes      | numeric metric | siaidlib   | St rev aid to libraries            | money     | money       |
| Yes      | numeric metric | siother    | St rev other                       | money     | money       |
| Yes      | numeric metric | total_si   | St rev TOTAL                       | money     | money       |
| Yes      | numeric metric | othincm    | Other revenue                      | money     | money       |
| Yes      | numeric metric | totincm    | Total revenue                      | money     | money       |
| Yes      | numeric metric | oexpsala   | Salaries federal                   | money     | money       |
| Yes      | numeric metric | oexpsalb   | Salaries state                     | money     | money       |
| Yes      | numeric metric | oexpsalc   | Salaries other                     | money     | money       |
| Yes      | numeric metric | oexpsald   | Salaries TOTAL                     | money     | money       |
| Yes      | numeric metric | oexpbena   | Benefits federal                   | money     | money       |
| Yes      | numeric metric | oexpbenb   | Benefits state                     | money     | money       |
| Yes      | numeric metric | oexpbenc   | Benefits other                     | money     | money       |
| Yes      | numeric metric | oexpbend   | Benefits TOTAL                     | money     | money       |
| Yes      | numeric metric | totoxsta   | Staff Exp federal                  | money     | money       |
| Yes      | numeric metric | totoxstb   | Staff Exp state                    | money     | money       |
| Yes      | numeric metric | totoxstc   | Staff Exp other                    | money     | money       |
| Yes      | numeric metric | totoxstd   | Staff Exp TOTAL                    | money     | money       |
| Yes      | numeric metric | oexpcola   | Collection Exp federal             | money     | money       |
| Yes      | numeric metric | oexpcolb   | Collection Exp state               | money     | money       |
| Yes      | numeric metric | oexpcolc   | Collection Exp other               | money     | money       |
| Yes      | numeric metric | oexpcold   | Collection Exp TOTAL               | money     | money       |
| Yes      | numeric metric | oexpotha   | Other Op Exp federal               | money     | money       |
| Yes      | numeric metric | oexpothb   | Other Op Exp state                 | money     | money       |
| Yes      | numeric metric | oexpothc   | Other Op Exp other                 | money     | money       |
| Yes      | numeric metric | oexpothd   | Other Op Exp TOTAL                 | money     | money       |
| Yes      | numeric metric | totopexa   | Tot Op Exp federal                 | money     | money       |
| Yes      | numeric metric | totopexb   | Tot Op Exp state                   | money     | money       |
| Yes      | numeric metric | totopexc   | Tot Op Exp other                   | money     | money       |
| Yes      | numeric metric | totopexd   | Tot Op Exp TOTAL                   | money     | money       |
| Yes      | numeric metric | aidipla    | Fin Asst to libraries federal      | money     | money       |
| Yes      | numeric metric | aidiplb    | Fin Asst to libraries state        | money     | money       |
| Yes      | numeric metric | aidiplc    | Fin Asst to libraries other        | money     | money       |
| Yes      | numeric metric | aidipld    | Fin Asst to libraries TOTAL        | money     | money       |
| Yes      | numeric metric | aidplsa    | Fin Asst to coops federal          | money     | money       |
| Yes      | numeric metric | aidplsb    | Fin Asst to coops state            | money     | money       |
| Yes      | numeric metric | aidplsc    | Fin Asst to coops other            | money     | money       |
| Yes      | numeric metric | aidplsd    | Fin Asst to coops TOTAL            | money     | money       |
| Yes      | numeric metric | aidoila    | Fin Asst to other federal          | money     | money       |
| Yes      | numeric metric | aidoilb    | Fin Asst to other state            | money     | money       |
| Yes      | numeric metric | aidoilc    | Fin Asst to other other            | money     | money       |
| Yes      | numeric metric | aidoild    | Fin Asst to other TOTAL            | money     | money       |
| Yes      | numeric metric | aidmlsa    | Fin Asst coops mult federal        | money     | money       |
| Yes      | numeric metric | aidmlsb    | Fin Asst coops mult state          | money     | money       |
| Yes      | numeric metric | aidmlsc    | Fin Asst coops mult other          | money     | money       |
| Yes      | numeric metric | aidmlsd    | Fin Asst coops mult TOTAL          | money     | money       |
| Yes      | numeric metric | aidsala    | Fin Asst libr statewide federal    | money     | money       |
| Yes      | numeric metric | aidsalb    | Fin Asst libr statewide state      | money     | money       |
| Yes      | numeric metric | aidsalc    | Fin Asst libr statewide other      | money     | money       |
| Yes      | numeric metric | aidsald    | Fin Asst libr statewide TOTAL      | money     | money       |
| Yes      | numeric metric | aidlca     | Fin Asst libr constr federal       | money     | money       |
| Yes      | numeric metric | aidlcb     | Fin Asst libr constr state         | money     | money       |
| Yes      | numeric metric | aidlcc     | Fin Asst libr constr other         | money     | money       |
| Yes      | numeric metric | aidlcd     | Fin Asst libr constr TOTAL         | money     | money       |
| Yes      | numeric metric | aidotha    | Fin Asst other federal             | money     | money       |
| Yes      | numeric metric | aidothb    | Fin Asst other state               | money     | money       |
| Yes      | numeric metric | aidothc    | Fin Asst other other               | money     | money       |
| Yes      | numeric metric | aidothd    | Fin Asst other TOTAL               | money     | money       |
| Yes      | numeric metric | totaida    | Fin Asst TOTAL federal             | money     | money       |
| Yes      | numeric metric | totaidb    | Fin Asst TOTAL state               | money     | money       |
| Yes      | numeric metric | totaidc    | Fin Asst TOTAL other               | money     | money       |
| Yes      | numeric metric | totaidd    | Fin Asst TOTAL TOTAL               | money     | money       |
| Yes      | numeric metric | capitala   | Capital outlay federal             | money     | money       |
| Yes      | numeric metric | capitalb   | Capital outlay state               | money     | money       |
| Yes      | numeric metric | capitalc   | Capital outlay other               | money     | money       |
| Yes      | numeric metric | capitald   | Capital outlay TOTAL               | money     | money       |
| Yes      | numeric metric | othexpa    | Other exp federal                  | money     | money       |
| Yes      | numeric metric | othexpb    | Other exp state                    | money     | money       |
| Yes      | numeric metric | othexpc    | Other exp other                    | money     | money       |
| Yes      | numeric metric | othexpd    | Other exp TOTAL                    | money     | money       |
| Yes      | numeric metric | totexpa    | Total exp federal                  | money     | money       |
| Yes      | numeric metric | totexpb    | Total exp state                    | money     | money       |
| Yes      | numeric metric | totexpc    | Total exp other                    | money     | money       |
| Yes      | numeric metric | totexpd    | Total exp TOTAL                    | money     | money       |
| Yes      | numeric metric | swexpt     | LSTA exp statewide svcs            | money     | money       |
| Yes      | numeric metric | grexpt     | LSTA exp grants                    | money     | money       |
| Yes      | numeric metric | admexpt    | LSTA exp LSTA admin                | money     | money       |
| Yes      | numeric metric | totexpt    | LSTA exp by type/TOTAL             | money     | money       |
| Yes      | numeric metric | techxu     | LSTA exp technology                | money     | money       |
| Yes      | numeric metric | serdifxu   | LSTA exp svcs to disab             | money     | money       |
| Yes      | numeric metric | serllxu    | LSTA exp lifelong learning         | money     | money       |
| Yes      | numeric metric | admexpu    | LSTA exp by use/LSTA admin         | money     | money       |
| Yes      | numeric metric | totexpu    | LSTA exp by use/TOTAL              | money     | money       |
| Yes      | numeric metric | popu_st    | Population                         | number    | number      |
```

## Time Field

```ls
Value = fystart
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fyend
```

## Data Commands

```ls
series e:9j5w-shf3 d:2011-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36117 t:mailzip4=1907 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1907 t:asf_sch=N t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fipsst=1 t:fiothsp=P m:capitalc=0 m:capitalb=224343 m:capitala=0 m:totaidb=4179597 m:siother=0 m:totaida=1099847 m:aidsala=5150 m:capitald=224343 m:admexpt=98543 m:swexpt=1369260 m:admexpu=98543 m:oexpbenb=392246 m:oexpbena=133723 m:oexpbend=525969 m:oexpbenc=0 m:totincm=8906562 m:othincm=9097 m:aidlcd=0 m:aidlcc=0 m:totexpu=2567650 m:totexpt=2567650 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=9396277 m:totexpa=2567727 m:totexpc=9097 m:totexpb=6819453 m:sistlaop=2150218 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=4822023 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=1991244 m:aidmlsd=0 m:serllxu=869053 m:totopexc=0 m:totopexd=3883393 m:totopexa=1467880 m:aidothd=0 m:totopexb=2415513 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=2567650 m:oexpothd=1196941 m:aidotha=0 m:oexpotha=556468 m:oexpothb=640473 m:aidplsc=0 m:aidplsd=1952996 m:total_si=6329815 m:totoxstb=1501580 m:totoxsta=489664 m:oexpcold=695208 m:lstainc=2567650 m:aidplsa=69445 m:oexpcolb=273460 m:grexpt=1099847 m:aidplsb=1883551 m:oexpcolc=0 m:serdifxu=433402 m:oexpsalb=1109334 m:othexpd=9097 m:aidiplc=0 m:oexpcola=421748 m:oexpsalc=0 m:aidipld=3321298 m:siaidlib=4179597 m:othexpb=0 m:aidipla=1025252 m:oexpsala=355941 m:aidoila=0 m:othexpc=9097 m:aidiplb=2296046 m:aidoilb=0 m:aidsald=5150 m:totaidd=5279444 m:aidoilc=0 m:totaidc=0 m:techxu=1166652 m:oexpsald=1465275 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:9j5w-shf3 d:2011-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=N t:mailaddr="P.O. BOX 110571" t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=1770 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99801 t:fipsst=2 t:fiothsp="LAURA BUSH 21ST CENTURY LIBRARIES (IMLS) FOR ALASKA NATIVE LIBRARIES ARCHIVES AND MUSEUMS SUMMIT (ANLAMS) $33,845 AND U.S. DEPT. OF COMMERCE BTOP AWARD FOR ALASKA (ONLINE WITH LIBRARIES) OWL PROJECT F" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=0 m:totaida=1772607 m:aidsala=587814 m:capitald=0 m:admexpt=27852 m:swexpt=0 m:admexpu=27852 m:oexpbenb=1090480 m:oexpbena=48117 m:oexpbend=1138597 m:oexpbenc=0 m:totincm=7497615 m:othincm=870000 m:aidlcd=0 m:aidlcc=0 m:totexpu=960008 m:totexpt=960008 m:fioth=1182565 m:aidlca=0 m:aidlcb=0 m:totexpd=7691219 m:totexpa=2089494 m:totexpc=58181 m:totexpb=5543544 m:sistlaop=3593642 m:aidmlsa=215649 m:aidmlsc=0 m:popu_st=731449 m:aidmlsb=24440 m:totoxstc=0 m:totoxstd=4140694 m:aidmlsd=240089 m:serllxu=275838 m:totopexc=58181 m:totopexd=5027212 m:totopexa=316887 m:aidothd=0 m:totopexb=4652144 m:aidothc=0 m:oexpothc=58181 m:aidothb=0 m:total_fi=2142573 m:oexpothd=758807 m:aidotha=0 m:oexpotha=141750 m:oexpothb=558876 m:aidplsc=0 m:aidplsd=0 m:total_si=4485042 m:totoxstb=3965557 m:totoxsta=175137 m:oexpcold=127711 m:lstainc=960008 m:aidplsa=0 m:oexpcolb=127711 m:grexpt=932156 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=226047 m:oexpsalb=2875077 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=1611580 m:siaidlib=891400 m:othexpb=0 m:aidipla=929233 m:oexpsala=127020 m:aidoila=39911 m:othexpc=0 m:aidiplb=682347 m:aidoilb=3156 m:aidsald=769271 m:totaidd=2664007 m:aidoilc=0 m:totaidc=0 m:techxu=430271 m:oexpsald=3002097 m:aidoild=43067 m:aidsalb=181457 m:aidsalc=0 m:othexpa=0

series e:9j5w-shf3 d:2011-07-01T00:00:00.000Z t:physcity=PHOENIX t:mailcity=PHOENIX t:asf_lc=N t:mail_st=AZ t:obereg=6 t:asf_ac=N t:physaddr="1700 WEST WASHINGTON - SUITE 200" t:phys_st=AZ t:mailzip=85007 t:mailzip4=2896 t:asf_pub=Y t:mailaddr="1700 WEST WASHINGTON, ROOM 200" t:stlaname="ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS" t:physzip4=2896 t:asf_sch=N t:webaddr=WWW.AZLIBRARY.GOV t:asf_sp=N t:rstatus=1 t:physzip=85007 t:fipsst=4 t:fiothsp="NATIONAL DIGITAL NEWSPAPER PROGRAM(NDNP);ARIZONA CONNECTING TO COLLECTIONS(AC2C);NATIONAL HISTORICAL PUBLICATIONS(NHPRC, SNAP, AHRAB);ARRA,PCC,AZ JOB HELP HUBS@YOUR LIBRARY(BTOP1 & BTOP2);PEDALS" m:capitalc=0 m:capitalb=189750 m:capitala=43038 m:totaidb=637907 m:siother=97000 m:totaida=901596 m:aidsala=0 m:capitald=232788 m:admexpt=128162 m:swexpt=2495460 m:admexpu=128162 m:oexpbenb=1352172 m:oexpbena=243997 m:oexpbend=1642931 m:oexpbenc=46762 m:totincm=12021860 m:othincm=1303798 m:aidlcd=129907 m:aidlcc=0 m:totexpu=3410213 m:totexpt=3410213 m:fioth=956097 m:aidlca=0 m:aidlcb=129907 m:totexpd=11599883 m:totexpa=4397635 m:totexpc=1001695 m:totexpb=6200533 m:sistlaop=5603352 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=6553255 m:aidmlsb=0 m:totoxstc=132924 m:totoxstd=5488501 m:aidmlsd=0 m:serllxu=1445353 m:totopexc=999395 m:totopexd=9807293 m:totopexa=3453001 m:aidothd=41125 m:totopexb=5354897 m:aidothc=0 m:oexpothc=863817 m:aidothb=0 m:total_fi=4366310 m:oexpothd=3978426 m:aidotha=41125 m:oexpotha=2353930 m:oexpothb=760679 m:aidplsc=0 m:aidplsd=0 m:total_si=6351752 m:totoxstb=4422571 m:totoxsta=933006 m:oexpcold=340366 m:lstainc=3410213 m:aidplsa=0 m:oexpcolb=171647 m:grexpt=786591 m:aidplsb=0 m:oexpcolc=2654 m:serdifxu=18827 m:oexpsalb=3070399 m:othexpd=23299 m:aidiplc=0 m:oexpcola=166065 m:oexpsalc=86162 m:aidipld=1297703 m:siaidlib=651400 m:othexpb=20999 m:aidipla=792703 m:oexpsala=689009 m:aidoila=67768 m:othexpc=2300 m:aidiplb=505000 m:aidoilb=0 m:aidsald=0 m:totaidd=1539503 m:aidoilc=0 m:totaidc=0 m:techxu=1817871 m:oexpsald=3845570 m:aidoild=67768 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
```

## Meta Commands

```ls
metric m:lstainc p:integer l:"LSTA revenue" t:dataTypeName=money

metric m:fioth p:integer l:"Other federal revenue" t:dataTypeName=money

metric m:total_fi p:integer l:"Total federal revenue" t:dataTypeName=money

metric m:sistlaop p:integer l:"St rev STLA operation" t:dataTypeName=money

metric m:siaidlib p:integer l:"St rev aid to libraries" t:dataTypeName=money

metric m:siother p:integer l:"St rev other" t:dataTypeName=money

metric m:total_si p:integer l:"St rev TOTAL" t:dataTypeName=money

metric m:othincm p:integer l:"Other revenue" t:dataTypeName=money

metric m:totincm p:integer l:"Total revenue" t:dataTypeName=money

metric m:oexpsala p:integer l:"Salaries federal" t:dataTypeName=money

metric m:oexpsalb p:integer l:"Salaries state" t:dataTypeName=money

metric m:oexpsalc p:integer l:"Salaries other" t:dataTypeName=money

metric m:oexpsald p:integer l:"Salaries TOTAL" t:dataTypeName=money

metric m:oexpbena p:integer l:"Benefits federal" t:dataTypeName=money

metric m:oexpbenb p:integer l:"Benefits state" t:dataTypeName=money

metric m:oexpbenc p:integer l:"Benefits other" t:dataTypeName=money

metric m:oexpbend p:integer l:"Benefits TOTAL" t:dataTypeName=money

metric m:totoxsta p:integer l:"Staff Exp federal" t:dataTypeName=money

metric m:totoxstb p:integer l:"Staff Exp state" t:dataTypeName=money

metric m:totoxstc p:integer l:"Staff Exp other" t:dataTypeName=money

metric m:totoxstd p:integer l:"Staff Exp TOTAL" t:dataTypeName=money

metric m:oexpcola p:integer l:"Collection Exp federal" t:dataTypeName=money

metric m:oexpcolb p:integer l:"Collection Exp state" t:dataTypeName=money

metric m:oexpcolc p:integer l:"Collection Exp other" t:dataTypeName=money

metric m:oexpcold p:integer l:"Collection Exp TOTAL" t:dataTypeName=money

metric m:oexpotha p:integer l:"Other Op Exp federal" t:dataTypeName=money

metric m:oexpothb p:integer l:"Other Op Exp state" t:dataTypeName=money

metric m:oexpothc p:integer l:"Other Op Exp other" t:dataTypeName=money

metric m:oexpothd p:integer l:"Other Op Exp TOTAL" t:dataTypeName=money

metric m:totopexa p:integer l:"Tot Op Exp federal" t:dataTypeName=money

metric m:totopexb p:integer l:"Tot Op Exp state" t:dataTypeName=money

metric m:totopexc p:integer l:"Tot Op Exp other" t:dataTypeName=money

metric m:totopexd p:integer l:"Tot Op Exp TOTAL" t:dataTypeName=money

metric m:aidipla p:integer l:"Fin Asst to libraries federal" t:dataTypeName=money

metric m:aidiplb p:integer l:"Fin Asst to libraries state" t:dataTypeName=money

metric m:aidiplc p:integer l:"Fin Asst to libraries other" t:dataTypeName=money

metric m:aidipld p:integer l:"Fin Asst to libraries TOTAL" t:dataTypeName=money

metric m:aidplsa p:integer l:"Fin Asst to coops federal" t:dataTypeName=money

metric m:aidplsb p:integer l:"Fin Asst to coops state" t:dataTypeName=money

metric m:aidplsc p:integer l:"Fin Asst to coops other" t:dataTypeName=money

metric m:aidplsd p:integer l:"Fin Asst to coops TOTAL" t:dataTypeName=money

metric m:aidoila p:integer l:"Fin Asst to other federal" t:dataTypeName=money

metric m:aidoilb p:integer l:"Fin Asst to other state" t:dataTypeName=money

metric m:aidoilc p:integer l:"Fin Asst to other other" t:dataTypeName=money

metric m:aidoild p:integer l:"Fin Asst to other TOTAL" t:dataTypeName=money

metric m:aidmlsa p:integer l:"Fin Asst coops mult federal" t:dataTypeName=money

metric m:aidmlsb p:integer l:"Fin Asst coops mult state" t:dataTypeName=money

metric m:aidmlsc p:integer l:"Fin Asst coops mult other" t:dataTypeName=money

metric m:aidmlsd p:integer l:"Fin Asst coops mult TOTAL" t:dataTypeName=money

metric m:aidsala p:integer l:"Fin Asst libr statewide federal" t:dataTypeName=money

metric m:aidsalb p:integer l:"Fin Asst libr statewide state" t:dataTypeName=money

metric m:aidsalc p:integer l:"Fin Asst libr statewide other" t:dataTypeName=money

metric m:aidsald p:integer l:"Fin Asst libr statewide TOTAL" t:dataTypeName=money

metric m:aidlca p:integer l:"Fin Asst libr constr federal" t:dataTypeName=money

metric m:aidlcb p:integer l:"Fin Asst libr constr state" t:dataTypeName=money

metric m:aidlcc p:integer l:"Fin Asst libr constr other" t:dataTypeName=money

metric m:aidlcd p:integer l:"Fin Asst libr constr TOTAL" t:dataTypeName=money

metric m:aidotha p:integer l:"Fin Asst other federal" t:dataTypeName=money

metric m:aidothb p:integer l:"Fin Asst other state" t:dataTypeName=money

metric m:aidothc p:integer l:"Fin Asst other other" t:dataTypeName=money

metric m:aidothd p:integer l:"Fin Asst other TOTAL" t:dataTypeName=money

metric m:totaida p:integer l:"Fin Asst TOTAL federal" t:dataTypeName=money

metric m:totaidb p:integer l:"Fin Asst TOTAL state" t:dataTypeName=money

metric m:totaidc p:integer l:"Fin Asst TOTAL other" t:dataTypeName=money

metric m:totaidd p:integer l:"Fin Asst TOTAL TOTAL" t:dataTypeName=money

metric m:capitala p:integer l:"Capital outlay federal" t:dataTypeName=money

metric m:capitalb p:integer l:"Capital outlay state" t:dataTypeName=money

metric m:capitalc p:integer l:"Capital outlay other" t:dataTypeName=money

metric m:capitald p:integer l:"Capital outlay TOTAL" t:dataTypeName=money

metric m:othexpa p:integer l:"Other exp federal" t:dataTypeName=money

metric m:othexpb p:integer l:"Other exp state" t:dataTypeName=money

metric m:othexpc p:integer l:"Other exp other" t:dataTypeName=money

metric m:othexpd p:integer l:"Other exp TOTAL" t:dataTypeName=money

metric m:totexpa p:integer l:"Total exp federal" t:dataTypeName=money

metric m:totexpb p:integer l:"Total exp state" t:dataTypeName=money

metric m:totexpc p:integer l:"Total exp other" t:dataTypeName=money

metric m:totexpd p:integer l:"Total exp TOTAL" t:dataTypeName=money

metric m:swexpt p:integer l:"LSTA exp statewide svcs" t:dataTypeName=money

metric m:grexpt p:integer l:"LSTA exp grants" t:dataTypeName=money

metric m:admexpt p:integer l:"LSTA exp LSTA admin" t:dataTypeName=money

metric m:totexpt p:integer l:"LSTA exp by type/TOTAL" t:dataTypeName=money

metric m:techxu p:integer l:"LSTA exp technology" t:dataTypeName=money

metric m:serdifxu p:integer l:"LSTA exp svcs to disab" t:dataTypeName=money

metric m:serllxu p:integer l:"LSTA exp lifelong learning" t:dataTypeName=money

metric m:admexpu p:integer l:"LSTA exp by use/LSTA admin" t:dataTypeName=money

metric m:totexpu p:integer l:"LSTA exp by use/TOTAL" t:dataTypeName=money

metric m:popu_st p:integer l:Population t:dataTypeName=number

entity e:9j5w-shf3 l:"State Libraries Survey, FY 2012, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9j5w-shf3

property e:9j5w-shf3 t:meta.view v:id=9j5w-shf3 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2012, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:9j5w-shf3 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9j5w-shf3 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:9j5w-shf3 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9j5w-shf3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                                                  | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                                  | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                             | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                                                                                                                  | fipsst | obereg | rstatus | fystart    | fyend      | lstainc  | fioth   | total_fi | sistlaop | siaidlib | siother | total_si | othincm | totincm  | oexpsala | oexpsalb | oexpsalc | oexpsald | oexpbena | oexpbenb | oexpbenc | oexpbend | totoxsta | totoxstb | totoxstc | totoxstd | oexpcola | oexpcolb | oexpcolc | oexpcold | oexpotha | oexpothb | oexpothc | oexpothd | totopexa | totopexb | totopexc | totopexd | aidipla | aidiplb  | aidiplc | aidipld  | aidplsa | aidplsb | aidplsc | aidplsd | aidoila | aidoilb | aidoilc | aidoild | aidmlsa | aidmlsb | aidmlsc | aidmlsd | aidsala | aidsalb | aidsalc | aidsald | aidlca | aidlcb  | aidlcc  | aidlcd  | aidotha | aidothb | aidothc | aidothd | totaida  | totaidb  | totaidc | totaidd  | capitala | capitalb | capitalc | capitald | othexpa | othexpb | othexpc | othexpd | totexpa  | totexpb  | totexpc | totexpd  | swexpt  | grexpt   | admexpt | totexpt  | techxu  | serdifxu | serllxu | admexpu | totexpu  | popu_st  | 
| ========================================================================= | ============================================= | =========== | ======= | ======= | ======== | ========================================= | =========== | ======= | ======= | ======== | =================================================== | ======= | ====== | ======= | ====== | ====== | ======================================================================================================================================================================================================== | ====== | ====== | ======= | ========== | ========== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======= | ======== | ======= | ======== | ======= | ======== | ======= | ======== | ======= | ======= | ======== | ======== | 
| ALABAMA PUBLIC LIBRARY SERVICE                                            | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1907     | 6030 MONTICELLO DRIVE                     | MONTGOMERY  | AL      | 36117   | 1907     | HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ | Y       | N      | N       | N      | Y      | P                                                                                                                                                                                                        | 1      | 5      | 1       | 1317427200 | 1348963200 | 2567650  | 0       | 2567650  | 2150218  | 4179597  | 0       | 6329815  | 9097    | 8906562  | 355941   | 1109334  | 0        | 1465275  | 133723   | 392246   | 0        | 525969   | 489664   | 1501580  | 0        | 1991244  | 421748   | 273460   | 0        | 695208   | 556468   | 640473   | 0        | 1196941  | 1467880  | 2415513  | 0        | 3883393  | 1025252 | 2296046  | 0       | 3321298  | 69445   | 1883551 | 0       | 1952996 | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 5150    | 0       | 0       | 5150    | 0      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1099847  | 4179597  | 0       | 5279444  | 0        | 224343   | 0        | 224343   | 0       | 0       | 9097    | 9097    | 2567727  | 6819453  | 9097    | 9396277  | 1369260 | 1099847  | 98543   | 2567650  | 1166652 | 433402   | 869053  | 98543   | 2567650  | 4822023  | 
| ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99801   | 1770     | P.O. BOX 110571                           | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                             | N       | Y      | Y       | Y      | Y      | LAURA BUSH 21ST CENTURY LIBRARIES (IMLS) FOR ALASKA NATIVE LIBRARIES ARCHIVES AND MUSEUMS SUMMIT (ANLAMS) $33,845 AND U.S. DEPT. OF COMMERCE BTOP AWARD FOR ALASKA (ONLINE WITH LIBRARIES) OWL PROJECT F | 2      | 8      | 1       | 1309478400 | 1341014400 | 960008   | 1182565 | 2142573  | 3593642  | 891400   | 0       | 4485042  | 870000  | 7497615  | 127020   | 2875077  | 0        | 3002097  | 48117    | 1090480  | 0        | 1138597  | 175137   | 3965557  | 0        | 4140694  | 0        | 127711   | 0        | 127711   | 141750   | 558876   | 58181    | 758807   | 316887   | 4652144  | 58181    | 5027212  | 929233  | 682347   | 0       | 1611580  | 0       | 0       | 0       | 0       | 39911   | 3156    | 0       | 43067   | 215649  | 24440   | 0       | 240089  | 587814  | 181457  | 0       | 769271  | 0      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1772607  | 891400   | 0       | 2664007  | 0        | 0        | 0        | 0        | 0       | 0       | 0       | 0       | 2089494  | 5543544  | 58181   | 7691219  | 0       | 932156   | 27852   | 960008   | 430271  | 226047   | 275838  | 27852   | 960008   | 731449   | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS                        | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON, ROOM 200            | PHOENIX     | AZ      | 85007   | 2896     | WWW.AZLIBRARY.GOV                                   | Y       | N      | N       | N      | N      | NATIONAL DIGITAL NEWSPAPER PROGRAM(NDNP);ARIZONA CONNECTING TO COLLECTIONS(AC2C);NATIONAL HISTORICAL PUBLICATIONS(NHPRC, SNAP, AHRAB);ARRA,PCC,AZ JOB HELP HUBS@YOUR LIBRARY(BTOP1 & BTOP2);PEDALS       | 4      | 6      | 1       | 1309478400 | 1341014400 | 3410213  | 956097  | 4366310  | 5603352  | 651400   | 97000   | 6351752  | 1303798 | 12021860 | 689009   | 3070399  | 86162    | 3845570  | 243997   | 1352172  | 46762    | 1642931  | 933006   | 4422571  | 132924   | 5488501  | 166065   | 171647   | 2654     | 340366   | 2353930  | 760679   | 863817   | 3978426  | 3453001  | 5354897  | 999395   | 9807293  | 792703  | 505000   | 0       | 1297703  | 0       | 0       | 0       | 0       | 67768   | 0       | 0       | 67768   | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 129907  | 0       | 129907  | 41125   | 0       | 0       | 41125   | 901596   | 637907   | 0       | 1539503  | 43038    | 189750   | 0        | 232788   | 0       | 20999   | 2300    | 23299   | 4397635  | 6200533  | 1001695 | 11599883 | 2495460 | 786591   | 128162  | 3410213  | 1817871 | 18827    | 1445353 | 128162  | 3410213  | 6553255  | 
| ARKANSAS STATE LIBRARY                                                    | 900 WEST CAPITOL, SUITE 100                   | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100               | LITTLE ROCK | AR      | 72201   | 3108     | WWW.LIBRARY.ARKANSAS.GOV                            | Y       | N      | N       | N      | N      | LIBRARY OF CONGRESS CENTER FOR THE BOOK                                                                                                                                                                  | 5      | 5      | 1       | 1309478400 | 1341014400 | 1812546  | 900     | 1813446  | 3464873  | 5700000  | 208000  | 9372873  | 5492    | 11191811 | 334407   | 1718534  | 0        | 2052941  | 138613   | 522950   | 0        | 661563   | 473020   | 2241484  | 0        | 2714504  | 429114   | 152770   | 0        | 581884   | 924314   | 1070610  | 0        | 1994924  | 1826448  | 3464864  | 0        | 5291312  | 0       | 5588400  | 45000   | 5633400  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0       | 0       | 0       | 0       | 111600  | 0       | 111600  | 0        | 5700000  | 45000   | 5745000  | 43377    | 0        | 0        | 43377    | 0       | 0       | 0       | 0       | 1869825  | 9164864  | 45000   | 11079689 | 1813926 | 0        | 55899   | 1869825  | 826767  | 225931   | 761228  | 55899   | 1869825  | 2949131  | 
| CALIFORNIA STATE LIBRARY                                                  | 900 N ST                                      | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                           | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                                  | N       | N      | N       | N      | N      |                                                                                                                                                                                                          | 6      | 8      | 2       | 1309478400 | 1341014400 | 15497372 | 0       | 15497372 | 14108240 | 0        | 0       | 14108240 | 553006  | 30158618 | 1934935  | 5154195  | 298980   | 7388110  | 835700   | 1949687  | 138429   | 2923816  | 2770635  | 7103882  | 437409   | 10311926 | 306120   | 388011   | 0        | 694131   | 2150477  | 6616347  | 115697   | 8882521  | 5227232  | 14108240 | 553106   | 19888578 | 2710885 | 0        | 0       | 2710885  | 0       | 0       | 0       | 0       | 261955  | 0       | 0       | 261995  | 5735122 | 0       | 0       | 5735122 | 2551208 | 0       | 0       | 2551208 | 0      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 11259170 | 0        | 0       | 11259170 | 0        | 945347   | 0        | 945347   | 0       | 0       | 0       | 0       | 16486402 | 14108240 | 553106  | 31147748 | 3618429 | 11259170 | 619773  | 15497372 | 6365967 | 3317247  | 5194385 | 619773  | 15497372 | 38041430 | 
| COLORADO STATE LIBRARY                                                    | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX AVENUE, ROOM 309          | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/CDELIB/                         | N       | N      | N       | N      | Y      | AMERICAN RECOVERY AND REINVESTMENT ACT/ BROADBAND TECHNOLOGY OPPORTUNITIES PROGRAM (BTOP)                                                                                                                | 8      | 7      | 1       | 1309478400 | 1341014400 | 2434644  | 1046462 | 3481106  | 1277408  | 1000000  | 250000  | 2527408  | 613966  | 6622480  | 1306731  | 678136   | 80007    | 2064874  | 316476   | 159703   | 22665    | 498844   | 1623207  | 837839   | 102672   | 2563718  | 24480    | 0        | 0        | 24480    | 876176   | 79773    | 218629   | 1174578  | 2523863  | 917612   | 321301   | 3762776  | 688184  | 0        | 283564  | 971748   | 0       | 0       | 0       | 0       | 9640    | 0       | 0       | 61741   | 125000  | 1000000 | 0       | 1125000 | 0       | 359796  | 0       | 359796  | 0      | 0       | 0       | 0       | 134419  | 0       | 9101    | 143520  | 957243   | 1359796  | 292665  | 2609704  | 0        | 0        | 0        | 0        | 0       | 250000  | 0       | 250000  | 3481106  | 2527408  | 613966  | 6622480  | 2031042 | 306216   | 97386   | 2434644  | 821907  | 522161   | 993190  | 97386   | 2434644  | 5187582  | 
| CONNECTICUT STATE LIBRARY                                                 | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                        | HARTFORD    | CT      | 6106    | 1537     | WWW.CTSTATELIBRARY.ORG                              | Y       | N      | N       | N      | Y      | CONNECTING TO COLLECTIONS                                                                                                                                                                                | 9      | 1      | 1       | 1309478400 | 1341014400 | 2264908  | 61889   | 2326797  | 9554379  | 1540192  | 0       | 11094571 | 1639864 | 15061232 | 888231   | 5168179  | 156577   | 6212987  | 575650   | 0        | 99870    | 675520   | 1463881  | 5168179  | 256447   | 6888507  | 72401    | 777850   | 0        | 850251   | 563040   | 3041701  | 387094   | 3991835  | 2099322  | 8987730  | 643541   | 11730593 | 116423  | 1207692  | 0       | 1324115  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 332500  | 0       | 332500  | 0       | 0       | 0       | 0       | 0      | 2127392 | 0       | 2127392 | 0       | 0       | 0       | 0       | 116423   | 3667584  | 0       | 3784007  | 0        | 204766   | 0        | 204766   | 0       | 0       | 0       | 0       | 2215745  | 12860080 | 643541  | 15719366 | 1890389 | 116423   | 83617   | 2090429  | 907665  | 849414   | 249733  | 83617   | 2090429  | 3590347  | 
| DELAWARE DIVISION OF LIBRARIES                                            | 121 MARTIN LUTHER KING JR. BLVD. NORTH        | DOVER       | DE      | 19901   | 7430     | 121 MARTIN LUTHER KING JR. BLVD. NORTH    | DOVER       | DE      | 19901   | 7430     | LIBRARIES.DELAWARE.GOV                              | Y       | N      | N       | N      | N      | BROADBAND TECHNOLOGY OPPORTUNITY PROJECT (BTOP), DELAWARE COLLECTION STEWARDSHIP IMPLEMENTATION PROJECT (CONNECTING TO COLLECTIONS)                                                                      | 10     | 2      | 1       | 1309478400 | 1341014400 | 698359   | 743358  | 1441717  | 1130700  | 3867300  | 2435000 | 7433000  | 7282900 | 16157617 | 288740   | 383671   | 0        | 672411   | 132409   | 171039   | 0        | 303448   | 421149   | 554710   | 0        | 975859   | 0        | 104846   | 0        | 104846   | 530096   | 3111115  | 430221   | 4071432  | 951245   | 3770671  | 430221   | 5152137  | 0       | 3840231  | 0       | 3840231  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0       | 6367941 | 6367941 | 0       | 0       | 0       | 0       | 0        | 3840231  | 6367941 | 10208172 | 0        | 0        | 0        | 0        | 0       | 828855  | 600     | 829455  | 951245   | 8439757  | 6798762 | 16189764 | 946796  | 0        | 4449    | 951245   | 92875   | 39279    | 814642  | 4449    | 951245   | 917092   | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                                       | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                        | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                                   | Y       | N      | N       | N      | N      | ARRA (STIMULUS) DC COMPUTIN RESOURCE GRANT                                                                                                                                                               | 11     | 2      | 1       | 1317427200 | 1348963200 | 920394   | 373199  | 1293593  | 35348597 | 0        | 0       | 35348597 | 1178572 | 37820762 | 249367   | 245381   | 0        | 494748   | 56605    | 34503    | 0        | 91108    | 305972   | 279884   | 0        | 585856   | 0        | 0        | 0        | 0        | 926203   | 20000    | 0        | 946203   | 1232175  | 299884   | 0        | 1532059  | 61418   | 35009544 | 1102335 | 36173297 | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 61418    | 35009544 | 1102335 | 36173297 | 0        | 0        | 0        | 0        | 0       | 0       | 0       | 0       | 1293593  | 35309428 | 1102335 | 37705356 | 846270  | 61418    | 12706   | 920394   | 0       | 53842    | 853846  | 12706   | 920394   | 632323   | 
| DIVISION OF LIBRARY AND INFORMATION SERVICES                              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | R.A. GRAY BUILDING 500 S. BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | HTTP://INFO.FLORIDA.GOV/                            | Y       | N      | N       | N      | Y      | NATIONAL HISTORICAL PUBLICATION & RECORDS COMM GRANT, NATIONAL ARCHIVES & RECORDS, NTIA BROADBAND GRANT                                                                                                  | 12     | 5      | 1       | 1309478400 | 1341014400 | 8111592  | 608784  | 8720376  | 4870798  | 22300000 | 2012393 | 29183191 | 937803  | 38841370 | 927538   | 1623203  | 641765   | 3192506  | 328067   | 548997   | 217056   | 1094120  | 1255605  | 2172200  | 858821   | 4286626  | 2737835  | 431174   | 0        | 3169009  | 2099180  | 2202548  | 78369    | 4380097  | 6092620  | 4805922  | 937190   | 11835732 | 674259  | 18441802 | 0       | 19116061 | 112776  | 2858198 | 0       | 2970974 | 53839   | 0       | 0       | 53839   | 800621  | 1000000 | 0       | 1800621 | 945832  | 0       | 0       | 945832  | 0      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 2587327  | 22300000 | 0       | 24887327 | 40429    | 17242    | 613      | 58284    | 0       | 0       | 0       | 0       | 8720376  | 27123164 | 937803  | 36781343 | 5199801 | 2587327  | 324464  | 8111592  | 3833306 | 2682068  | 1271754 | 324464  | 8111592  | 19317568 | 
```