# State Libraries Survey, FY 2001, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2001-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/mem6-3u6k) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/mem6-3u6k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/mem6-3u6k/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | mem6-3u6k |
| Name | State Libraries Survey, FY 2001, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2001, revenue, expenditures |
| Created | 2016-12-20T15:22:09Z |
| Publication Date | 2016-12-20T17:04:31Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                 | Data Type | Render Type |
| ======== | ============== | ========== | ==================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                            | text      | text        |
| Yes      | series tag     | physaddr   | Street                               | text      | text        |
| Yes      | series tag     | physcity   | City                                 | text      | text        |
| Yes      | series tag     | phys_st    | State                                | text      | text        |
| Yes      | series tag     | physzip    | Zip                                  | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                                | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                        | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                          | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                         | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                           | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                         | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                          | text      | text        |
| Yes      | series tag     | fiothsp    | Other fed rev specified              | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                      | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy   | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy     | date      | date        |
| Yes      | numeric metric | lstainc    | LSTA revenue                         | money     | money       |
| Yes      | numeric metric | fioth      | Other federal revenue                | money     | money       |
| Yes      | numeric metric | total_fi   | Total federal revenue                | money     | money       |
| Yes      | numeric metric | sistlaop   | St rev STLA operation                | money     | money       |
| Yes      | numeric metric | siaidlib   | St rev aid to libraries              | money     | money       |
| Yes      | numeric metric | siother    | St rev other                         | money     | money       |
| Yes      | numeric metric | total_si   | St rev TOTAL                         | money     | money       |
| Yes      | numeric metric | othincm    | Other revenue                        | money     | money       |
| Yes      | numeric metric | totincm    | Total revenue                        | money     | money       |
| Yes      | numeric metric | oexpsala   | Salaries federal                     | money     | money       |
| Yes      | numeric metric | oexpsalb   | Salaries state                       | money     | money       |
| Yes      | numeric metric | oexpsalc   | Salaries other                       | money     | money       |
| Yes      | numeric metric | oexpsald   | Salaries TOTAL                       | money     | money       |
| Yes      | numeric metric | oexpbena   | Benefits federal                     | money     | money       |
| Yes      | numeric metric | oexpbenb   | Benefits state                       | money     | money       |
| Yes      | numeric metric | oexpbenc   | Benefits other                       | money     | money       |
| Yes      | numeric metric | oexpbend   | Benefits TOTAL                       | money     | money       |
| Yes      | numeric metric | totoxsta   | Staff Exp federal                    | money     | money       |
| Yes      | numeric metric | totoxstb   | Staff Exp state                      | money     | money       |
| Yes      | numeric metric | totoxstc   | Staff Exp other                      | money     | money       |
| Yes      | numeric metric | totoxstd   | Staff Exp TOTAL                      | money     | money       |
| Yes      | numeric metric | oexpcola   | Collection Exp federal               | money     | money       |
| Yes      | numeric metric | oexpcolb   | Collection Exp state                 | money     | money       |
| Yes      | numeric metric | oexpcolc   | Collection Exp other                 | money     | money       |
| Yes      | numeric metric | oexpcold   | Collection Exp TOTAL                 | money     | money       |
| Yes      | numeric metric | oexpotha   | Other Op Exp federal                 | money     | money       |
| Yes      | numeric metric | oexpothb   | Other Op Exp state                   | money     | money       |
| Yes      | numeric metric | oexpothc   | Other Op Exp other                   | money     | money       |
| Yes      | numeric metric | oexpothd   | Other Op Exp TOTAL                   | money     | money       |
| Yes      | numeric metric | totopexa   | Tot Op Exp federal                   | money     | money       |
| Yes      | numeric metric | totopexb   | Tot Op Exp state                     | money     | money       |
| Yes      | numeric metric | totopexc   | Tot Op Exp other                     | money     | money       |
| Yes      | numeric metric | totopexd   | Tot Op Exp TOTAL                     | money     | money       |
| Yes      | numeric metric | aidipla    | Fin Asst to libraries federal        | money     | money       |
| Yes      | numeric metric | aidiplb    | Fin Asst to libraries state          | money     | money       |
| Yes      | numeric metric | aidiplc    | Fin Asst to libraries other          | money     | money       |
| Yes      | numeric metric | aidipld    | Fin Asst to libraries TOTAL          | money     | money       |
| Yes      | numeric metric | aidplsa    | Fin Asst to coops federal            | money     | money       |
| Yes      | numeric metric | aidplsb    | Fin Asst to coops state              | money     | money       |
| Yes      | numeric metric | aidplsc    | Fin Asst to coops other              | money     | money       |
| Yes      | numeric metric | aidplsd    | Fin Asst to coops TOTAL              | money     | money       |
| Yes      | numeric metric | aidoila    | Fin Asst to other federal            | money     | money       |
| Yes      | numeric metric | aidoilb    | Fin Asst to other state              | money     | money       |
| Yes      | numeric metric | aidoilc    | Fin Asst to other other              | money     | money       |
| Yes      | numeric metric | aidoild    | Fin Asst to other TOTAL              | money     | money       |
| Yes      | numeric metric | aidmlsa    | Fin Asst coops mult federal          | money     | money       |
| Yes      | numeric metric | aidmlsb    | Fin Asst coops mult state            | money     | money       |
| Yes      | numeric metric | aidmlsc    | Fin Asst coops mult other            | money     | money       |
| Yes      | numeric metric | aidmlsd    | Fin Asst coops mult TOTAL            | money     | money       |
| Yes      | numeric metric | aidsala    | Fin Asst libr statewide federal      | money     | money       |
| Yes      | numeric metric | aidsalb    | Fin Asst libr statewide state        | money     | money       |
| Yes      | numeric metric | aidsalc    | Fin Asst libr statewide other        | money     | money       |
| Yes      | numeric metric | aidsald    | Fin Asst libr statewide TOTAL        | money     | money       |
| Yes      | numeric metric | aidlca     | Fin Asst libr constr federal         | money     | money       |
| Yes      | numeric metric | aidlcb     | Fin Asst libr constr state           | money     | money       |
| Yes      | numeric metric | aidlcc     | Fin Asst libr constr other           | money     | money       |
| Yes      | numeric metric | aidlcd     | Fin Asst libr constr TOTAL           | money     | money       |
| Yes      | numeric metric | aidotha    | Fin Asst other federal               | money     | money       |
| Yes      | numeric metric | aidothb    | Fin Asst other state                 | money     | money       |
| Yes      | numeric metric | aidothc    | Fin Asst other other                 | money     | money       |
| Yes      | numeric metric | aidothd    | Fin Asst other TOTAL                 | money     | money       |
| Yes      | numeric metric | totaida    | Fin Asst TOTAL federal               | money     | money       |
| Yes      | numeric metric | totaidb    | Fin Asst TOTAL state                 | money     | money       |
| Yes      | numeric metric | totaidc    | Fin Asst TOTAL other                 | money     | money       |
| Yes      | numeric metric | totaidd    | Fin Asst TOTAL TOTAL                 | money     | money       |
| Yes      | numeric metric | capitala   | Capital outlay federal               | money     | money       |
| Yes      | numeric metric | capitalb   | Capital outlay state                 | money     | money       |
| Yes      | numeric metric | capitalc   | Capital outlay other                 | money     | money       |
| Yes      | numeric metric | capitald   | Capital outlay TOTAL                 | money     | money       |
| Yes      | numeric metric | othexpa    | Other exp federal                    | money     | money       |
| Yes      | numeric metric | othexpb    | Other exp state                      | money     | money       |
| Yes      | numeric metric | othexpc    | Other exp other                      | money     | money       |
| Yes      | numeric metric | othexpd    | Other exp TOTAL                      | money     | money       |
| Yes      | numeric metric | totexpa    | Total exp federal                    | money     | money       |
| Yes      | numeric metric | totexpb    | Total exp state                      | money     | money       |
| Yes      | numeric metric | totexpc    | Total exp other                      | money     | money       |
| Yes      | numeric metric | totexpd    | Total exp TOTAL                      | money     | money       |
| Yes      | numeric metric | swexpt     | LSTA exp statewide svcs              | money     | money       |
| Yes      | numeric metric | grexpt     | LSTA exp grants                      | money     | money       |
| Yes      | numeric metric | admexpt    | LSTA exp LSTA admin                  | money     | money       |
| Yes      | numeric metric | totexpt    | LSTA exp by type/TOTAL               | money     | money       |
| Yes      | numeric metric | netacxu    | LSTA exp electronic networking       | money     | money       |
| Yes      | numeric metric | serdifxu   | LSTA exp svcs to disab               | money     | money       |
| Yes      | numeric metric | serpovxu   | LSTA exp svcs to children in poverty | money     | money       |
| Yes      | numeric metric | admexpu    | LSTA exp by use/LSTA admin           | money     | money       |
| Yes      | numeric metric | totexpu    | LSTA exp by use/TOTAL                | money     | money       |
| Yes      | numeric metric | allopstf   | Oper exp staff total                 | money     | money       |
| Yes      | numeric metric | allopoth   | Oper exp other total                 | money     | money       |
| Yes      | numeric metric | totox_ao   | Oper exp TOTAL                       | money     | money       |
| Yes      | numeric metric | allopcap   | Capital outlay                       | money     | money       |
| Yes      | numeric metric | totexpao   | Total expenditures                   | money     | money       |
| Yes      | numeric metric | popu_st    | Population                           | number    | number      |
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
series e:mem6-3u6k d:2000-07-01T00:00:00.000Z t:physzip4=571 t:physcity=JUNEAU t:mailcity=JUNEAU t:webaddr=WWW.LIBRARY.STATE.AK.US t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571 t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:capitalc=0 m:capitalb=65000 m:capitala=0 m:totaidb=891400 m:siother=221300 m:totaida=501435 m:aidsala=334596 m:capitald=65000 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=741100 m:oexpbena=0 m:oexpbend=741100 m:oexpbenc=0 m:netacxu=186682 m:totincm=4503635 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=501435 m:totexpt=501435 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=4335035 m:allopcap=0 m:totexpa=501435 m:totexpc=0 m:totexpb=3833600 m:sistlaop=2889500 m:aidmlsa=0 m:popu_st=626932 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2032800 m:aidmlsd=0 m:totopexc=0 m:totopexd=2877200 m:totopexa=0 m:aidothd=0 m:totopexb=2877200 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=540100 m:aidotha=0 m:total_fi=501435 m:oexpotha=0 m:oexpothb=540100 m:aidplsc=0 m:aidplsd=0 m:total_si=4002200 m:totoxstb=2032800 m:totoxsta=0 m:serpovxu=0 m:oexpcold=304300 m:lstainc=501435 m:grexpt=501435 m:aidplsa=0 m:oexpcolb=304300 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=314753 m:oexpsalb=1291700 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=717663 m:siaidlib=891400 m:othexpb=0 m:aidipla=80193 m:oexpsala=0 m:aidoila=86646 m:othexpc=0 m:aidiplb=637470 m:aidoilb=178037 m:aidsald=410489 m:totaidd=1392835 m:aidoilc=0 m:totaidc=0 m:oexpsald=1291700 m:aidoild=264683 m:aidsalb=75893 m:aidsalc=0 m:othexpa=0

series e:mem6-3u6k d:2000-10-01T00:00:00.000Z t:physzip4=1 t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:webaddr=WWW.APLS.STATE.AL.US t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailzip4=1 t:mailaddr="6030 MONTICELLO DRIVE" t:fiothsp="LSCA TITLE II" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4583687 m:siother=2814000 m:totaida=1492770 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=84370 m:swexpt=805524 m:admexpu=84370 m:oexpbenb=504125 m:oexpbena=0 m:oexpbend=504125 m:oexpbenc=0 m:netacxu=988031 m:totincm=12779619 m:othincm=82932 m:aidlcd=186670 m:aidlcc=0 m:totexpu=2242894 m:totexpt=2242894 m:allopstf=0 m:fioth=139770 m:aidlca=139770 m:aidlcb=46900 m:totexpd=12779619 m:allopcap=0 m:totexpa=2382664 m:totexpc=82932 m:totexpb=10314023 m:sistlaop=2916336 m:aidmlsa=236202 m:popu_st=4369862 m:aidmlsc=0 m:aidmlsb=1576763 m:totoxstc=0 m:totexpao=0 m:totoxstd=2558614 m:aidmlsd=1812965 m:totopexc=82932 m:totopexd=6703162 m:totopexa=889894 m:aidothd=0 m:totopexb=5730336 m:aidothc=0 m:aidothb=0 m:oexpothc=82932 m:oexpothd=1412610 m:aidotha=0 m:total_fi=2382664 m:oexpotha=695517 m:oexpothb=634161 m:aidplsc=0 m:aidplsd=991356 m:total_si=10314023 m:totoxstb=2558614 m:totoxsta=0 m:serpovxu=22396 m:oexpcold=2731938 m:lstainc=2242894 m:grexpt=1353000 m:aidplsa=279985 m:oexpcolb=2537561 m:aidplsb=711371 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1148097 m:oexpsalb=2054489 m:othexpd=0 m:aidiplc=0 m:oexpcola=194377 m:oexpsalc=0 m:aidipld=3085466 m:siaidlib=4583687 m:othexpb=0 m:aidipla=836813 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=2248653 m:aidoilb=0 m:aidsald=0 m:totaidd=6076457 m:aidoilc=0 m:totaidc=0 m:oexpsald=2054489 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:mem6-3u6k d:2000-07-01T00:00:00.000Z t:physzip4=1085 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:webaddr=WWW.ASL.LIB.AR.US t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1085 t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" m:capitalc=0 m:capitalb=12000 m:capitala=37034 m:totaidb=4900000 m:siother=0 m:totaida=5000 m:aidsala=0 m:capitald=49034 m:totox_ao=0 m:admexpt=10490 m:swexpt=1535209 m:admexpu=10490 m:oexpbenb=359302 m:oexpbena=90595 m:oexpbend=449897 m:oexpbenc=0 m:netacxu=1406139 m:totincm=9522399 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=1550699 m:totexpt=1550699 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=9403206 m:allopcap=0 m:totexpa=1550699 m:totexpc=0 m:totexpb=7852507 m:sistlaop=3017805 m:aidmlsa=0 m:popu_st=2538303 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2114423 m:aidmlsd=0 m:totopexc=0 m:totopexd=4449172 m:totopexa=1508665 m:aidothd=0 m:totopexb=2940507 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=1930590 m:aidotha=0 m:total_fi=1604594 m:oexpotha=1090842 m:oexpothb=839748 m:aidplsc=0 m:aidplsd=3268905 m:total_si=7917805 m:totoxstb=1755520 m:totoxsta=358903 m:serpovxu=0 m:oexpcold=404159 m:lstainc=1604594 m:grexpt=5000 m:aidplsa=5000 m:oexpcolb=345239 m:aidplsb=3263905 m:oexpcolc=0 m:allopoth=0 m:serdifxu=134070 m:oexpsalb=1396218 m:othexpd=0 m:aidiplc=0 m:oexpcola=58920 m:oexpsalc=0 m:aidipld=1636095 m:siaidlib=4900000 m:othexpb=0 m:aidipla=0 m:oexpsala=268308 m:aidoila=0 m:othexpc=0 m:aidiplb=1636095 m:aidoilb=0 m:aidsald=0 m:totaidd=4905000 m:aidoilc=0 m:totaidc=0 m:oexpsald=1664526 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
```

## Meta Commands

```ls
metric m:lstainc p:double l:"LSTA revenue" t:dataTypeName=money

metric m:fioth p:double l:"Other federal revenue" t:dataTypeName=money

metric m:total_fi p:double l:"Total federal revenue" t:dataTypeName=money

metric m:sistlaop p:double l:"St rev STLA operation" t:dataTypeName=money

metric m:siaidlib p:double l:"St rev aid to libraries" t:dataTypeName=money

metric m:siother p:double l:"St rev other" t:dataTypeName=money

metric m:total_si p:double l:"St rev TOTAL" t:dataTypeName=money

metric m:othincm p:double l:"Other revenue" t:dataTypeName=money

metric m:totincm p:double l:"Total revenue" t:dataTypeName=money

metric m:oexpsala p:double l:"Salaries federal" t:dataTypeName=money

metric m:oexpsalb p:double l:"Salaries state" t:dataTypeName=money

metric m:oexpsalc p:double l:"Salaries other" t:dataTypeName=money

metric m:oexpsald p:double l:"Salaries TOTAL" t:dataTypeName=money

metric m:oexpbena p:double l:"Benefits federal" t:dataTypeName=money

metric m:oexpbenb p:double l:"Benefits state" t:dataTypeName=money

metric m:oexpbenc p:double l:"Benefits other" t:dataTypeName=money

metric m:oexpbend p:double l:"Benefits TOTAL" t:dataTypeName=money

metric m:totoxsta p:double l:"Staff Exp federal" t:dataTypeName=money

metric m:totoxstb p:double l:"Staff Exp state" t:dataTypeName=money

metric m:totoxstc p:double l:"Staff Exp other" t:dataTypeName=money

metric m:totoxstd p:double l:"Staff Exp TOTAL" t:dataTypeName=money

metric m:oexpcola p:double l:"Collection Exp federal" t:dataTypeName=money

metric m:oexpcolb p:double l:"Collection Exp state" t:dataTypeName=money

metric m:oexpcolc p:double l:"Collection Exp other" t:dataTypeName=money

metric m:oexpcold p:double l:"Collection Exp TOTAL" t:dataTypeName=money

metric m:oexpotha p:double l:"Other Op Exp federal" t:dataTypeName=money

metric m:oexpothb p:double l:"Other Op Exp state" t:dataTypeName=money

metric m:oexpothc p:double l:"Other Op Exp other" t:dataTypeName=money

metric m:oexpothd p:double l:"Other Op Exp TOTAL" t:dataTypeName=money

metric m:totopexa p:double l:"Tot Op Exp federal" t:dataTypeName=money

metric m:totopexb p:double l:"Tot Op Exp state" t:dataTypeName=money

metric m:totopexc p:double l:"Tot Op Exp other" t:dataTypeName=money

metric m:totopexd p:double l:"Tot Op Exp TOTAL" t:dataTypeName=money

metric m:aidipla p:double l:"Fin Asst to libraries federal" t:dataTypeName=money

metric m:aidiplb p:double l:"Fin Asst to libraries state" t:dataTypeName=money

metric m:aidiplc p:double l:"Fin Asst to libraries other" t:dataTypeName=money

metric m:aidipld p:double l:"Fin Asst to libraries TOTAL" t:dataTypeName=money

metric m:aidplsa p:double l:"Fin Asst to coops federal" t:dataTypeName=money

metric m:aidplsb p:double l:"Fin Asst to coops state" t:dataTypeName=money

metric m:aidplsc p:double l:"Fin Asst to coops other" t:dataTypeName=money

metric m:aidplsd p:double l:"Fin Asst to coops TOTAL" t:dataTypeName=money

metric m:aidoila p:double l:"Fin Asst to other federal" t:dataTypeName=money

metric m:aidoilb p:double l:"Fin Asst to other state" t:dataTypeName=money

metric m:aidoilc p:double l:"Fin Asst to other other" t:dataTypeName=money

metric m:aidoild p:double l:"Fin Asst to other TOTAL" t:dataTypeName=money

metric m:aidmlsa p:double l:"Fin Asst coops mult federal" t:dataTypeName=money

metric m:aidmlsb p:double l:"Fin Asst coops mult state" t:dataTypeName=money

metric m:aidmlsc p:double l:"Fin Asst coops mult other" t:dataTypeName=money

metric m:aidmlsd p:double l:"Fin Asst coops mult TOTAL" t:dataTypeName=money

metric m:aidsala p:double l:"Fin Asst libr statewide federal" t:dataTypeName=money

metric m:aidsalb p:double l:"Fin Asst libr statewide state" t:dataTypeName=money

metric m:aidsalc p:double l:"Fin Asst libr statewide other" t:dataTypeName=money

metric m:aidsald p:double l:"Fin Asst libr statewide TOTAL" t:dataTypeName=money

metric m:aidlca p:double l:"Fin Asst libr constr federal" t:dataTypeName=money

metric m:aidlcb p:double l:"Fin Asst libr constr state" t:dataTypeName=money

metric m:aidlcc p:double l:"Fin Asst libr constr other" t:dataTypeName=money

metric m:aidlcd p:double l:"Fin Asst libr constr TOTAL" t:dataTypeName=money

metric m:aidotha p:double l:"Fin Asst other federal" t:dataTypeName=money

metric m:aidothb p:double l:"Fin Asst other state" t:dataTypeName=money

metric m:aidothc p:double l:"Fin Asst other other" t:dataTypeName=money

metric m:aidothd p:double l:"Fin Asst other TOTAL" t:dataTypeName=money

metric m:totaida p:double l:"Fin Asst TOTAL federal" t:dataTypeName=money

metric m:totaidb p:double l:"Fin Asst TOTAL state" t:dataTypeName=money

metric m:totaidc p:double l:"Fin Asst TOTAL other" t:dataTypeName=money

metric m:totaidd p:double l:"Fin Asst TOTAL TOTAL" t:dataTypeName=money

metric m:capitala p:double l:"Capital outlay federal" t:dataTypeName=money

metric m:capitalb p:double l:"Capital outlay state" t:dataTypeName=money

metric m:capitalc p:double l:"Capital outlay other" t:dataTypeName=money

metric m:capitald p:double l:"Capital outlay TOTAL" t:dataTypeName=money

metric m:othexpa p:double l:"Other exp federal" t:dataTypeName=money

metric m:othexpb p:double l:"Other exp state" t:dataTypeName=money

metric m:othexpc p:double l:"Other exp other" t:dataTypeName=money

metric m:othexpd p:double l:"Other exp TOTAL" t:dataTypeName=money

metric m:totexpa p:double l:"Total exp federal" t:dataTypeName=money

metric m:totexpb p:double l:"Total exp state" t:dataTypeName=money

metric m:totexpc p:double l:"Total exp other" t:dataTypeName=money

metric m:totexpd p:double l:"Total exp TOTAL" t:dataTypeName=money

metric m:swexpt p:double l:"LSTA exp statewide svcs" t:dataTypeName=money

metric m:grexpt p:double l:"LSTA exp grants" t:dataTypeName=money

metric m:admexpt p:double l:"LSTA exp LSTA admin" t:dataTypeName=money

metric m:totexpt p:double l:"LSTA exp by type/TOTAL" t:dataTypeName=money

metric m:netacxu p:double l:"LSTA exp electronic networking" t:dataTypeName=money

metric m:serdifxu p:double l:"LSTA exp svcs to disab" t:dataTypeName=money

metric m:serpovxu p:double l:"LSTA exp svcs to children in poverty" t:dataTypeName=money

metric m:admexpu p:double l:"LSTA exp by use/LSTA admin" t:dataTypeName=money

metric m:totexpu p:double l:"LSTA exp by use/TOTAL" t:dataTypeName=money

metric m:allopstf p:double l:"Oper exp staff total" t:dataTypeName=money

metric m:allopoth p:double l:"Oper exp other total" t:dataTypeName=money

metric m:totox_ao p:double l:"Oper exp TOTAL" t:dataTypeName=money

metric m:allopcap p:double l:"Capital outlay" t:dataTypeName=money

metric m:totexpao p:double l:"Total expenditures" t:dataTypeName=money

metric m:popu_st p:float l:Population t:dataTypeName=number

entity e:mem6-3u6k l:"State Libraries Survey, FY 2001, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/mem6-3u6k

property e:mem6-3u6k t:meta.view v:id=mem6-3u6k v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2001, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:mem6-3u6k t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:mem6-3u6k t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:mem6-3u6k t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:mem6-3u6k t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | fiothsp                                                                       | pub_fips | fystart   | fyend      | lstainc    | fioth     | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm     | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc  | oexpothd  | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila   | aidoilb   | aidoilc | aidoild   | aidmlsa  | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca   | aidlcb    | aidlcc | aidlcd    | aidotha  | aidothb  | aidothc | aidothd  | totaida    | totaidb    | totaidc  | totaidd    | capitala | capitalb | capitalc | capitald | othexpa  | othexpb  | othexpc | othexpd  | totexpa    | totexpb    | totexpc   | totexpd     | swexpt    | grexpt     | admexpt  | totexpt    | netacxu    | serdifxu  | serpovxu | admexpu  | totexpu    | allopstf  | allopoth | totox_ao  | allopcap | totexpao  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | ===================================== | ============================================================================= | ======== | ========= | ========== | ========== | ========= | ========== | ========== | ========== | ========= | ========== | ========= | =========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========== | ======= | ========== | ========= | ========= | ======= | ========= | ======== | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ======== | ========= | ====== | ========= | ======== | ======== | ======= | ======== | ========== | ========== | ======== | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ========== | ========== | ========= | =========== | ========= | ========== | ======== | ========== | ========== | ========= | ======== | ======== | ========== | ========= | ======== | ========= | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US               |                                                                               | 2        | 962409600 | 993859200  | 501435.0   | 0.0       | 501435.0   | 2889500.0  | 891400.0   | 221300.0  | 4002200.0  | 0.0       | 4503635.0   | 0.0       | 1291700.0 | 0.0      | 1291700.0 | 0.0      | 741100.0  | 0.0      | 741100.0  | 0.0       | 2032800.0 | 0.0      | 2032800.0  | 0.0      | 304300.0  | 0.0      | 304300.0  | 0.0       | 540100.0  | 0.0       | 540100.0  | 0.0       | 2877200.0  | 0.0       | 2877200.0  | 80193.0   | 637470.0   | 0.0      | 717663.0   | 0.0       | 0.0        | 0.0     | 0.0        | 86646.0   | 178037.0  | 0.0     | 264683.0  | 0.0      | 0.0       | 0.0     | 0.0       | 334596.0  | 75893.0   | 0.0     | 410489.0  | 0.0      | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 501435.0   | 891400.0   | 0.0      | 1392835.0  | 0.0      | 65000.0  | 0.0      | 65000.0  | 0.0      | 0.0      | 0.0     | 0.0      | 501435.0   | 3833600.0  | 0.0       | 4335035.0   | 0.0       | 501435.0   | 0.0      | 501435.0   | 186682.0   | 314753.0  | 0.0      | 0.0      | 501435.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 626932.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | LSCA TITLE II                                                                 | 1        | 970358400 | 1001808000 | 2242894.0  | 139770.0  | 2382664.0  | 2916336.0  | 4583687.0  | 2814000.0 | 10314023.0 | 82932.0   | 12779619.0  | 0.0       | 2054489.0 | 0.0      | 2054489.0 | 0.0      | 504125.0  | 0.0      | 504125.0  | 0.0       | 2558614.0 | 0.0      | 2558614.0  | 194377.0 | 2537561.0 | 0.0      | 2731938.0 | 695517.0  | 634161.0  | 82932.0   | 1412610.0 | 889894.0  | 5730336.0  | 82932.0   | 6703162.0  | 836813.0  | 2248653.0  | 0.0      | 3085466.0  | 279985.0  | 711371.0   | 0.0     | 991356.0   | 0.0       | 0.0       | 0.0     | 0.0       | 236202.0 | 1576763.0 | 0.0     | 1812965.0 | 0.0       | 0.0       | 0.0     | 0.0       | 139770.0 | 46900.0   | 0.0    | 186670.0  | 0.0      | 0.0      | 0.0     | 0.0      | 1492770.0  | 4583687.0  | 0.0      | 6076457.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 2382664.0  | 10314023.0 | 82932.0   | 12779619.0  | 805524.0  | 1353000.0  | 84370.0  | 2242894.0  | 988031.0   | 1148097.0 | 22396.0  | 84370.0  | 2242894.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 4369862.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     |                                                                               | 5        | 962409600 | 993859200  | 1604594.0  | 0.0       | 1604594.0  | 3017805.0  | 4900000.0  | 0.0       | 7917805.0  | 0.0       | 9522399.0   | 268308.0  | 1396218.0 | 0.0      | 1664526.0 | 90595.0  | 359302.0  | 0.0      | 449897.0  | 358903.0  | 1755520.0 | 0.0      | 2114423.0  | 58920.0  | 345239.0  | 0.0      | 404159.0  | 1090842.0 | 839748.0  | 0.0       | 1930590.0 | 1508665.0 | 2940507.0  | 0.0       | 4449172.0  | 0.0       | 1636095.0  | 0.0      | 1636095.0  | 5000.0    | 3263905.0  | 0.0     | 3268905.0  | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 5000.0     | 4900000.0  | 0.0      | 4905000.0  | 37034.0  | 12000.0  | 0.0      | 49034.0  | 0.0      | 0.0      | 0.0     | 0.0      | 1550699.0  | 7852507.0  | 0.0       | 9403206.0   | 1535209.0 | 5000.0     | 10490.0  | 1550699.0  | 1406139.0  | 134070.0  | 0.0      | 10490.0  | 1550699.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 2538303.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                         | LSCA TITLE II; NLG; NHPRC; NEH                                                | 4        | 962409600 | 993859200  | 1986480.0  | 258419.0  | 2244899.0  | 7144600.0  | 651400.0   | 77000.0   | 7873000.0  | 170088.0  | 10287987.0  | 98790.0   | 3448282.0 | 16649.0  | 3563721.0 | 18799.0  | 723600.0  | 3741.0   | 746140.0  | 117589.0  | 4171882.0 | 20390.0  | 4309861.0  | 6218.0   | 386447.0  | 0.0      | 392665.0  | 50639.0   | 1949647.0 | 138771.0  | 2139057.0 | 174446.0  | 6507976.0  | 159161.0  | 6841583.0  | 984513.0  | 628496.0   | 0.0      | 1613009.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 137109.0  | 77000.0   | 0.0     | 214109.0  | 5397.0   | 0.0       | 0.0    | 5397.0    | 0.0      | 0.0      | 0.0     | 0.0      | 1127019.0  | 705496.0   | 0.0      | 1832515.0  | 91424.0  | 0.0      | 52318.0  | 143742.0 | 852010.0 | 0.0      | 0.0     | 852010.0 | 2244899.0  | 7213472.0  | 211479.0  | 9669850.0   | 787866.0  | 1121622.0  | 71595.0  | 1981083.0  | 1809488.0  | 20000.0   | 80000.0  | 71595.0  | 1981083.0  | 1297254.0 | 493434.0 | 1790688.0 | 6372.0   | 1797060.0 | 4924350.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    |                                                                               | 6        | 962409600 | 993859200  | 15852102.0 | 0.0       | 15852102.0 | 19937185.0 | 76697897.0 | 0.0       | 96635082.0 | 596746.0  | 113083930.0 | 1357128.0 | 8122822.0 | 330930.0 | 9810880.0 | 249877.0 | 1446385.0 | 61083.0  | 1757345.0 | 1607005.0 | 9569207.0 | 392013.0 | 11568225.0 | 491.0    | 2853589.0 | 121386.0 | 2975466.0 | 1526478.0 | 7514389.0 | 83347.0   | 9124214.0 | 3133974.0 | 19937185.0 | 596746.0  | 23667905.0 | 2262742.0 | 73512897.0 | 0.0      | 75775639.0 | 164303.0  | 0.0        | 0.0     | 164303.0   | 3434336.0 | 0.0       | 0.0     | 3434336.0 | 631751.0 | 3185000.0 | 0.0     | 3816751.0 | 6224996.0 | 0.0       | 0.0     | 6224996.0 | 0.0      | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 12718128.0 | 76697897.0 | 0.0      | 89416025.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 15852102.0 | 96635082.0 | 596746.0  | 113083930.0 | 3058286.0 | 12718128.0 | 75688.0  | 15852102.0 | 10345510.0 | 4675674.0 | 755230.0 | 75688.0  | 15852102.0 | 2384770.0 | 965707.0 | 3350477.0 | 0.0      | 3350477.0 | 34366000.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX                       | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/LIBRARY_INDEX.HTM |                                                                               | 8        | 962409600 | 993859200  | 2112516.0  | 0.0       | 2112516.0  | 1600833.0  | 6911309.0  | 0.0       | 8512142.0  | 0.0       | 10624658.0  | 794099.0  | 1090525.0 | 0.0      | 1884624.0 | 174315.0 | 239384.0  | 0.0      | 413699.0  | 968414.0  | 1329909.0 | 0.0      | 2298323.0  | 15000.0  | 101899.0  | 0.0      | 116899.0  | 573877.0  | 167026.0  | 0.0       | 740903.0  | 1557291.0 | 1598834.0  | 0.0       | 3156125.0  | 74288.0   | 134114.0   | 0.0      | 208402.0   | 0.0       | 0.0        | 0.0     | 0.0        | 80113.0   | 1950000.0 | 0.0     | 2030113.0 | 60474.0  | 2449893.0 | 0.0     | 2510367.0 | 152400.0  | 2201296.0 | 0.0     | 2353696.0 | 0.0      | 0.0       | 0.0    | 0.0       | 187950.0 | 162006.0 | 0.0     | 349956.0 | 555225.0   | 6897309.0  | 0.0      | 7452534.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 2112516.0  | 8496143.0  | 0.0       | 10608659.0  | 1474240.0 | 555225.0   | 83051.0  | 2112516.0  | 734157.0   | 1285308.0 | 10000.0  | 83051.0  | 2112516.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 4301261.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | NEWSPAPER PROJECT,LSCA TITLE II, NHPRC,NEA-STATE & REGIONAL PARTNERSHIP GRANT | 9        | 962409600 | 993859200  | 2188075.0  | 1419452.0 | 3607527.0  | 13261742.0 | 3997403.0  | 0.0       | 17259145.0 | 2673404.0 | 23540076.0  | 927754.0  | 5993661.0 | 61537.0  | 6982952.0 | 356632.0 | 0.0       | 23807.0  | 380439.0  | 1284386.0 | 5993661.0 | 85344.0  | 7363391.0  | 96623.0  | 838573.0  | 73174.0  | 1008370.0 | 1006529.0 | 5711774.0 | 1246521.0 | 7964824.0 | 2387538.0 | 12544008.0 | 1405039.0 | 16336585.0 | 231835.0  | 1198137.0  | 0.0      | 1429972.0  | 0.0       | 0.0        | 0.0     | 0.0        | 6000.0    | 0.0       | 0.0     | 6000.0    | 4200.0   | 799266.0  | 0.0     | 803466.0  | 0.0       | 358080.0  | 0.0     | 358080.0  | 72159.0  | 1768288.0 | 0.0    | 1840447.0 | 0.0      | 0.0      | 0.0     | 0.0      | 314194.0   | 4123771.0  | 0.0      | 4437965.0  | 0.0      | 281220.0 | 0.0      | 281220.0 | 0.0      | 0.0      | 0.0     | 0.0      | 2701732.0  | 16948999.0 | 1405039.0 | 21055770.0  | 1622763.0 | 242035.0   | 33626.0  | 1898424.0  | 578852.0   | 1194150.0 | 91796.0  | 33626.0  | 1898424.0  | 1203905.0 | 62816.0  | 1266721.0 | 0.0      | 1266721.0 | 3274069.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     |                                                                               | 11       | 970358400 | 1001808000 | 389331.0   | 0.0       | 389331.0   | 26655271.0 | 0.0        | 0.0       | 26655271.0 | 178324.0  | 27222926.0  | 269175.0  | 190437.0  | 0.0      | 459612.0  | 45849.0  | 43947.0   | 0.0      | 89796.0   | 315024.0  | 234384.0  | 0.0      | 549408.0   | 0.0      | 0.0       | 0.0      | 0.0       | 37167.0   | 29498.0   | 0.0       | 66665.0   | 352191.0  | 263882.0   | 0.0       | 616073.0   | 37140.0   | 26391389.0 | 178324.0 | 26606853.0 | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 37140.0    | 26391389.0 | 178324.0 | 26606853.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 389331.0   | 26655271.0 | 178324.0  | 27222926.0  | 351691.0  | 37140.0    | 500.0    | 389331.0   | 232936.0   | 116372.0  | 39523.0  | 500.0    | 389331.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 572059.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         |                                                                               | 10       | 962409600 | 993859200  | 698909.0   | 0.0       | 698909.0   | 1137900.0  | 2121600.0  | 724000.0  | 3983500.0  | 0.0       | 4682409.0   | 278770.0  | 424199.0  | 0.0      | 702969.0  | 69444.0  | 123551.0  | 0.0      | 192995.0  | 348214.0  | 547750.0  | 0.0      | 895964.0   | 15023.0  | 7902.0    | 0.0      | 22925.0   | 83720.0   | 378222.0  | 0.0       | 461942.0  | 446957.0  | 933874.0   | 0.0       | 1380831.0  | 34764.0   | 1868915.0  | 0.0      | 1903679.0  | 0.0       | 0.0        | 0.0     | 0.0        | 54363.0   | 22420.0   | 0.0     | 76783.0   | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 909186.0  | 0.0    | 909186.0  | 0.0      | 0.0      | 0.0     | 0.0      | 89127.0    | 2800521.0  | 0.0      | 2889648.0  | 23476.0  | 797.0    | 0.0      | 24273.0  | 0.0      | 723911.0 | 0.0     | 723911.0 | 559560.0   | 4459103.0  | 0.0       | 5018663.0   | 470433.0  | 89127.0    | 0.0      | 559560.0   | 555919.0   | 3641.0    | 0.0      | 0.0      | 559560.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 783600.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | LSCA TITLE II                                                                 | 12       | 962409600 | 993859200  | 7060456.0  | 750000.0  | 7810456.0  | 11211205.0 | 33400000.0 | 4056682.0 | 48667887.0 | 0.0       | 56478343.0  | 490108.0  | 2328032.0 | 0.0      | 2818140.0 | 171538.0 | 814811.0  | 0.0      | 986349.0  | 661646.0  | 3142843.0 | 0.0      | 3804489.0  | 192268.0 | 619917.0  | 0.0      | 812185.0  | 772448.0  | 3241824.0 | 0.0       | 4014272.0 | 1626362.0 | 7004584.0  | 0.0       | 8630946.0  | 0.0       | 0.0        | 0.0      | 0.0        | 5433390.0 | 33650000.0 | 0.0     | 39083390.0 | 0.0       | 700000.0  | 0.0     | 700000.0  | 0.0      | 1200000.0 | 0.0     | 1200000.0 | 0.0       | 0.0       | 0.0     | 0.0       | 750000.0 | 372000.0  | 0.0    | 1122000.0 | 0.0      | 90000.0  | 0.0     | 90000.0  | 6183390.0  | 36012000.0 | 0.0      | 42195390.0 | 704.0    | 40099.0  | 0.0      | 40803.0  | 0.0      | 0.0      | 0.0     | 0.0      | 7810456.0  | 43056683.0 | 0.0       | 50867139.0  | 1452353.0 | 5433390.0  | 174713.0 | 7060456.0  | 4876195.0  | 1475635.0 | 533913.0 | 174713.0 | 7060456.0  | 984769.0  | 417507.0 | 1402276.0 | 0.0      | 1402276.0 | 15982378.0 | 
```