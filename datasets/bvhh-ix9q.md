# State Libraries Survey, FY 2003, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2003-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/bvhh-ix9q) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/bvhh-ix9q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/bvhh-ix9q/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | bvhh-ix9q |
| Name | State Libraries Survey, FY 2003, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2003, revenue, expenditures |
| Created | 2016-12-20T15:25:12Z |
| Publication Date | 2016-12-20T17:04:33Z |

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
| Yes      | series tag     | asf_pub    | Admins state funds                   | text      | text        |
| Yes      | series tag     | asf_ac     | Admins state funds acad              | text      | text        |
| Yes      | series tag     | asf_sch    | Admins state funds school            | text      | text        |
| Yes      | series tag     | asf_sp     | Admins state funds special           | text      | text        |
| Yes      | series tag     | asf_lc     | Admins state funds co-ops            | text      | text        |
| Yes      | series tag     | fiothsp    | Other fed rev specified              | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                      | text      | text        |
| Yes      | series tag     | obereg     | BEA code                             | text      | text        |
| Yes      | series tag     | rstatus    | Reporting Status                     | text      | text        |
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
| Yes      | numeric metric | othexpao   | All other exp                        | money     | money       |
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
series e:bvhh-ix9q d:2002-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=N t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp="FUND FOR IMPROV OF POSTSEC ED (FIPSE) (HIGHER ED ACT OF 1965, TITLE VII)" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=838247 m:siother=221300 m:totaida=627240 m:aidsala=456471 m:capitald=0 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=515065 m:oexpbena=6141 m:oexpbend=521327 m:oexpbenc=121 m:netacxu=162192 m:totincm=4863917 m:othincm=283327 m:aidlcd=0 m:aidlcc=0 m:totexpu=627240 m:totexpt=627240 m:allopstf=0 m:fioth=32950 m:aidlca=0 m:aidlcb=0 m:totexpd=4968077 m:allopcap=0 m:totexpa=660190 m:totexpc=79292 m:totexpb=4228595 m:othexpao=0 m:sistlaop=2807700 m:aidmlsa=0 m:popu_st=648818 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=1011 m:totexpao=0 m:totoxstd=2066559 m:aidmlsd=0 m:totopexc=79292 m:totopexd=3502590 m:totopexa=32950 m:aidothd=94040 m:totopexb=3390348 m:aidothc=0 m:oexpothc=78281 m:aidothb=5000 m:oexpothd=1172286 m:aidotha=89040 m:total_fi=660190 m:oexpotha=8320 m:oexpothb=1085685 m:aidplsc=0 m:aidplsd=0 m:total_si=3920400 m:totoxstb=2040918 m:totoxsta=24630 m:serpovxu=0 m:oexpcold=263745 m:lstainc=627240 m:aidplsa=0 m:oexpcolb=263745 m:grexpt=627240 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=465048 m:oexpsalb=1525853 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=890 m:aidipld=736432 m:siaidlib=891400 m:othexpb=0 m:aidipla=74229 m:oexpsala=18489 m:aidoila=7500 m:othexpc=0 m:aidiplb=662203 m:aidoilb=24322 m:aidsald=603193 m:totaidd=1465487 m:aidoilc=0 m:totaidc=0 m:oexpsald=1545232 m:aidoild=31822 m:aidsalb=146722 m:aidsalc=0 m:othexpa=0

series e:bvhh-ix9q d:2002-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=WWW.APLS.STATE.AL.US t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp="NCLIS (NCES TECHNICAL TRAINING GRANT)" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4451054 m:siother=2689973 m:totaida=958797 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=84152 m:swexpt=1334571 m:admexpu=84152 m:oexpbenb=496112 m:oexpbena=37575 m:oexpbend=533687 m:oexpbenc=0 m:netacxu=606611 m:totincm=14596068 m:othincm=29246 m:aidlcd=50086 m:aidlcc=0 m:totexpu=2377520 m:totexpt=2377520 m:allopstf=0 m:fioth=5000 m:aidlca=0 m:aidlcb=50086 m:totexpd=11958186 m:allopcap=0 m:totexpa=2382520 m:totexpc=29246 m:totexpb=9546420 m:othexpao=0 m:sistlaop=5095366 m:aidmlsa=0 m:popu_st=4500752 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2568369 m:aidmlsd=0 m:totopexc=29246 m:totopexd=6548335 m:totopexa=1423723 m:aidothd=0 m:totopexb=5095366 m:aidothc=0 m:oexpothc=29246 m:aidothb=0 m:oexpothd=3404104 m:aidotha=0 m:total_fi=2382520 m:oexpotha=684885 m:oexpothb=2689973 m:aidplsc=0 m:aidplsd=2346837 m:total_si=12184302 m:totoxstb=2405393 m:totoxsta=162976 m:serpovxu=176588 m:oexpcold=575862 m:lstainc=2377520 m:aidplsa=28249 m:oexpcolb=0 m:grexpt=958797 m:aidplsb=2318588 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1510169 m:oexpsalb=1909281 m:othexpd=0 m:aidiplc=0 m:oexpcola=575862 m:oexpsalc=0 m:aidipld=2983867 m:siaidlib=4398963 m:othexpb=0 m:aidipla=901487 m:oexpsala=125401 m:aidoila=29061 m:othexpc=0 m:aidiplb=2082380 m:aidoilb=0 m:aidsald=0 m:totaidd=5409851 m:aidoilc=0 m:totaidc=0 m:oexpsald=2034682 m:aidoild=29061 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:bvhh-ix9q d:2002-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1085 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=107258 m:totaidb=500000 m:siother=0 m:totaida=0 m:aidsala=0 m:capitald=107258 m:totox_ao=0 m:admexpt=25324 m:swexpt=1474654 m:admexpu=25324 m:oexpbenb=366796 m:oexpbena=95455 m:oexpbend=462251 m:oexpbenc=0 m:netacxu=1325035 m:totincm=4839151 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=1499978 m:totexpt=1499978 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=4824800 m:allopcap=0 m:totexpa=1499978 m:totexpc=0 m:totexpb=3324822 m:othexpao=0 m:sistlaop=2824822 m:aidmlsa=0 m:popu_st=2725714 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2212941 m:aidmlsd=0 m:totopexc=0 m:totopexd=4217542 m:totopexa=1392720 m:aidothd=0 m:totopexb=2824822 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:oexpothd=1667457 m:aidotha=0 m:total_fi=1514329 m:oexpotha=795710 m:oexpothb=871747 m:aidplsc=0 m:aidplsd=301285 m:total_si=3324822 m:totoxstb=1827761 m:totoxsta=385180 m:serpovxu=0 m:oexpcold=337144 m:lstainc=1514329 m:aidplsa=0 m:oexpcolb=125314 m:grexpt=0 m:aidplsb=301285 m:oexpcolc=0 m:allopoth=0 m:serdifxu=149619 m:oexpsalb=1460965 m:othexpd=0 m:aidiplc=0 m:oexpcola=211830 m:oexpsalc=0 m:aidipld=198715 m:siaidlib=500000 m:othexpb=0 m:aidipla=0 m:oexpsala=289725 m:aidoila=0 m:othexpc=0 m:aidiplb=198715 m:aidoilb=0 m:aidsald=0 m:totaidd=500000 m:aidoilc=0 m:totaidc=0 m:oexpsald=1750690 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

metric m:othexpao p:double l:"All other exp" t:dataTypeName=money

metric m:totexpao p:double l:"Total expenditures" t:dataTypeName=money

metric m:popu_st p:double l:Population t:dataTypeName=number

entity e:bvhh-ix9q l:"State Libraries Survey, FY 2003, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/bvhh-ix9q

property e:bvhh-ix9q t:meta.view v:id=bvhh-ix9q v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2003, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:bvhh-ix9q t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:bvhh-ix9q t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:bvhh-ix9q t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:bvhh-ix9q t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                  | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth     | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc  | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc  | oexpothd  | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila   | aidoilb | aidoilc | aidoild   | aidmlsa   | aidmlsb   | aidmlsc  | aidmlsd   | aidsala   | aidsalb  | aidsalc | aidsald   | aidlca | aidlcb    | aidlcc | aidlcd    | aidotha  | aidothb | aidothc | aidothd  | totaida    | totaidb    | totaidc  | totaidd    | capitala | capitalb | capitalc | capitald | othexpa  | othexpb  | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt     | admexpt | totexpt    | netacxu    | serdifxu  | serpovxu  | admexpu | totexpu    | allopstf  | allopoth | totox_ao  | allopcap | othexpao  | totexpao  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | ===================================== | ======= | ====== | ======= | ====== | ====== | ======================================================================== | ======== | ====== | ======= | ========== | ========== | ========== | ========= | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ========= | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========== | ======= | ========== | ========= | ======= | ======= | ========= | ========= | ========= | ======== | ========= | ========= | ======== | ======= | ========= | ====== | ========= | ====== | ========= | ======== | ======= | ======= | ======== | ========== | ========== | ======== | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========== | ======= | ========== | ========== | ========= | ========= | ======= | ========== | ========= | ======== | ========= | ======== | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US               | Y       | Y      | Y       | Y      | N      | FUND FOR IMPROV OF POSTSEC ED (FIPSE) (HIGHER ED ACT OF 1965, TITLE VII) | 2        | 8      | 1       | 1025481600 | 1056931200 | 627240.0   | 32950.0   | 660190.0   | 2807700.0  | 891400.0   | 221300.0  | 3920400.0  | 283327.0  | 4863917.0  | 18489.0   | 1525853.0 | 890.0    | 1545232.0 | 6141.0   | 515065.0  | 121.0    | 521327.0  | 24630.0   | 2040918.0 | 1011.0    | 2066559.0  | 0.0      | 263745.0  | 0.0      | 263745.0  | 8320.0    | 1085685.0 | 78281.0   | 1172286.0 | 32950.0   | 3390348.0  | 79292.0   | 3502590.0  | 74229.0   | 662203.0   | 0.0      | 736432.0   | 0.0       | 0.0        | 0.0     | 0.0        | 7500.0    | 24322.0 | 0.0     | 31822.0   | 0.0       | 0.0       | 0.0      | 0.0       | 456471.0  | 146722.0 | 0.0     | 603193.0  | 0.0    | 0.0       | 0.0    | 0.0       | 89040.0  | 5000.0  | 0.0     | 94040.0  | 627240.0   | 838247.0   | 0.0      | 1465487.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 660190.0   | 4228595.0  | 79292.0   | 4968077.0  | 0.0       | 627240.0   | 0.0     | 627240.0   | 162192.0   | 465048.0  | 0.0       | 0.0     | 627240.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 648818.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | Y       | N      | N       | N      | Y      | NCLIS (NCES TECHNICAL TRAINING GRANT)                                    | 1        | 5      | 1       | 1033430400 | 1064880000 | 2377520.0  | 5000.0    | 2382520.0  | 5095366.0  | 4398963.0  | 2689973.0 | 12184302.0 | 29246.0   | 14596068.0 | 125401.0  | 1909281.0 | 0.0      | 2034682.0 | 37575.0  | 496112.0  | 0.0      | 533687.0  | 162976.0  | 2405393.0 | 0.0       | 2568369.0  | 575862.0 | 0.0       | 0.0      | 575862.0  | 684885.0  | 2689973.0 | 29246.0   | 3404104.0 | 1423723.0 | 5095366.0  | 29246.0   | 6548335.0  | 901487.0  | 2082380.0  | 0.0      | 2983867.0  | 28249.0   | 2318588.0  | 0.0     | 2346837.0  | 29061.0   | 0.0     | 0.0     | 29061.0   | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0    | 50086.0   | 0.0    | 50086.0   | 0.0      | 0.0     | 0.0     | 0.0      | 958797.0   | 4451054.0  | 0.0      | 5409851.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 2382520.0  | 9546420.0  | 29246.0   | 11958186.0 | 1334571.0 | 958797.0   | 84152.0 | 2377520.0  | 606611.0   | 1510169.0 | 176588.0  | 84152.0 | 2377520.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 4500752.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     | Y       | N      | N       | N      | N      | P                                                                        | 5        | 5      | 1       | 1025481600 | 1056931200 | 1514329.0  | 0.0       | 1514329.0  | 2824822.0  | 500000.0   | 0.0       | 3324822.0  | 0.0       | 4839151.0  | 289725.0  | 1460965.0 | 0.0      | 1750690.0 | 95455.0  | 366796.0  | 0.0      | 462251.0  | 385180.0  | 1827761.0 | 0.0       | 2212941.0  | 211830.0 | 125314.0  | 0.0      | 337144.0  | 795710.0  | 871747.0  | 0.0       | 1667457.0 | 1392720.0 | 2824822.0  | 0.0       | 4217542.0  | 0.0       | 198715.0   | 0.0      | 198715.0   | 0.0       | 301285.0   | 0.0     | 301285.0   | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0        | 500000.0   | 0.0      | 500000.0   | 107258.0 | 0.0      | 0.0      | 107258.0 | 0.0      | 0.0      | 0.0       | 0.0       | 1499978.0  | 3324822.0  | 0.0       | 4824800.0  | 1474654.0 | 0.0        | 25324.0 | 1499978.0  | 1325035.0  | 149619.0  | 0.0       | 25324.0 | 1499978.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2725714.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                         | Y       | N      | N       | N      | N      | IMLS - NATIONAL LEADERSHIP GRANT                                         | 4        | 6      | 1       | 1025481600 | 1056931200 | 2892831.0  | 39376.0   | 2932207.0  | 6057300.0  | 651400.0   | 97000.0   | 6805700.0  | 902471.0  | 10640378.0 | 46556.0   | 3671559.0 | 213193.0 | 3931308.0 | 11639.0  | 847817.0  | 56983.0  | 916439.0  | 58195.0   | 4519376.0 | 270176.0  | 4847747.0  | 33441.0  | 100000.0  | 246909.0 | 380350.0  | 774568.0  | 1437924.0 | 211735.0  | 2424227.0 | 866204.0  | 6057300.0  | 728820.0  | 7652324.0  | 334659.0  | 669000.0   | 0.0      | 1003659.0  | 362494.0  | 0.0        | 0.0     | 362494.0   | 231316.0  | 0.0     | 0.0     | 231316.0  | 5856.0    | 0.0       | 0.0      | 5856.0    | 0.0       | 0.0      | 0.0     | 0.0       | 0.0    | 0.0       | 0.0    | 0.0       | 236900.0 | 0.0     | 0.0     | 236900.0 | 1171225.0  | 669000.0   | 0.0      | 1840225.0  | 0.0      | 0.0      | 0.0      | 0.0      | 855402.0 | 0.0      | 0.0       | 855402.0  | 2892831.0  | 6726300.0  | 728820.0  | 10347951.0 | 1648707.0 | 1171225.0  | 72899.0 | 2892831.0  | 1851411.0  | 761973.0  | 206548.0  | 72899.0 | 2892831.0  | 1557523.0 | 469582.0 | 2027105.0 | 0.0      | 0.0       | 2027105.0 | 5580811.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    | Y       | N      | N       | N      | Y      | P                                                                        | 6        | 8      | 2       | 1025481600 | 1056931200 | 16222180.0 | 0.0       | 16222180.0 | 15892631.0 | 52037773.0 | 0.0       | 67930404.0 | 492549.0  | 84645133.0 | 2290870.0 | 7134293.0 | 310795.0 | 9735958.0 | 568413.0 | 1826059.0 | 94926.0  | 2489398.0 | 2859283.0 | 8960352.0 | 405721.0  | 12225356.0 | 489779.0 | 1417964.0 | 0.0      | 1907743.0 | 2024746.0 | 5514317.0 | 86828.0   | 7625891.0 | 5373808.0 | 15892633.0 | 492549.0  | 21758990.0 | 2278151.0 | 48721791.0 | 0.0      | 50999942.0 | 0.0       | 0.0        | 0.0     | 0.0        | 1675982.0 | 0.0     | 0.0     | 1675982.0 | 270694.0  | 3315982.0 | 0.0      | 3586676.0 | 6623545.0 | 0.0      | 0.0     | 6623545.0 | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 10848372.0 | 52037773.0 | 0.0      | 62886145.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 16222180.0 | 67930406.0 | 492549.0  | 84645135.0 | 5284312.0 | 10848372.0 | 89496.0 | 16222180.0 | 11867159.0 | 3230824.0 | 1034701.0 | 89496.0 | 16222180.0 | 2233811.0 | 756942.0 | 2990753.0 | 0.0      | 0.0       | 2990753.0 | 35484453.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX                       | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM | N       | N      | N       | N      | Y      | P                                                                        | 8        | 7      | 1       | 1025481600 | 1056931200 | 2657954.0  | 0.0       | 2657954.0  | 1626701.0  | 2565380.0  | 93800.0   | 4285881.0  | 266472.0  | 7210307.0  | 1042222.0 | 1157946.0 | 78112.0  | 2278280.0 | 228781.0 | 254183.0  | 17147.0  | 500111.0  | 1271003.0 | 1412129.0 | 95259.0   | 2778391.0  | 8400.0   | 119256.0  | 0.0      | 127656.0  | 387499.0  | 95316.0   | 38708.0   | 521523.0  | 1666902.0 | 1626701.0  | 133967.0  | 3427570.0  | 37005.0   | 0.0        | 0.0      | 37005.0    | 0.0       | 0.0        | 0.0     | 0.0        | 187995.0  | 0.0     | 0.0     | 187995.0  | 320000.0  | 2565038.0 | 0.0      | 2885038.0 | 337000.0  | 0.0      | 0.0     | 337000.0  | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 882000.0   | 2565038.0  | 0.0      | 3447038.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 2548902.0  | 4191739.0  | 133967.0  | 6874608.0  | 1574474.0 | 882000.0   | 92428.0 | 2548902.0  | 777033.0   | 1679441.0 | 0.0       | 92428.0 | 2548902.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 4550688.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | Y       | N      | N       | N      | N      | NEWSPAPER PROJECT, NHPRC, NEA PARTNERSHIP GRANT                          | 9        | 1      | 1       | 1025481600 | 1056931200 | 2280321.0  | 1377086.0 | 3657407.0  | 11833373.0 | 4123137.0  | 0.0       | 15956510.0 | 2373818.0 | 21987735.0 | 952503.0  | 6111661.0 | 132647.0 | 7196811.0 | 378412.0 | 0.0       | 49622.0  | 428034.0  | 1330915.0 | 6111661.0 | 182269.0  | 7624845.0  | 131190.0 | 779676.0  | 69535.0  | 980401.0  | 994159.0  | 4777003.0 | 1126649.0 | 6897811.0 | 2456264.0 | 11668340.0 | 1378453.0 | 15503057.0 | 188094.0  | 1023137.0  | 0.0      | 1211231.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 600000.0 | 0.0     | 600000.0  | 0.0    | 1343389.0 | 0.0    | 1343389.0 | 0.0      | 0.0     | 0.0     | 0.0      | 188094.0   | 2966526.0  | 0.0      | 3154620.0  | 4341.0   | 277621.0 | 7469.0   | 289431.0 | 0.0      | 0.0      | 1025860.0 | 1025860.0 | 2648699.0  | 14912487.0 | 2411782.0 | 19972968.0 | 1699518.0 | 188094.0   | 8506.0  | 1896118.0  | 458100.0   | 1398933.0 | 30579.0   | 8506.0  | 1896118.0  | 1254809.0 | 126363.0 | 1381172.0 | 18852.0  | 1025860.0 | 2425884.0 | 3483372.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | HTTP://DCLIBRARY.ORG                  | Y       | N      | N       | N      | N      | P                                                                        | 11       | 2      | 1       | 1033430400 | 1064880000 | 601621.0   | 0.0       | 601621.0   | 26021886.0 | 0.0        | 0.0       | 26021886.0 | 537000.0  | 27160507.0 | 288505.0  | 243645.0  | 0.0      | 532150.0  | 53045.0  | 41294.0   | 0.0      | 94339.0   | 341550.0  | 284939.0  | 0.0       | 626489.0   | 0.0      | 0.0       | 0.0      | 0.0       | 260171.0  | 25233.0   | 0.0       | 285404.0  | 601721.0  | 310172.0   | 0.0       | 911893.0   | 0.0       | 25711714.0 | 537000.0 | 26248714.0 | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0        | 25711714.0 | 537000.0 | 26248714.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 601721.0   | 26021886.0 | 537000.0  | 27160607.0 | 601621.0  | 0.0        | 0.0     | 601621.0   | 146029.0   | 355880.0  | 99712.0   | 0.0     | 601621.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 563384.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         | Y       | N      | N       | N      | N      | P                                                                        | 10       | 2      | 1       | 1025481600 | 1056931200 | 559747.0   | 0.0       | 559747.0   | 1215612.0  | 2569500.0  | 2811859.0 | 6596971.0  | 146375.0  | 7303093.0  | 264278.0  | 376273.0  | 0.0      | 640551.0  | 73225.0  | 130426.0  | 0.0      | 203651.0  | 337503.0  | 506699.0  | 0.0       | 844202.0   | 6605.0   | 7219.0    | 0.0      | 13824.0   | 136426.0  | 395653.0  | 0.0       | 532079.0  | 480534.0  | 909571.0   | 0.0       | 1390105.0  | 191745.0  | 2364652.0  | 0.0      | 2556397.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 25000.0  | 0.0     | 25000.0   | 0.0    | 3651305.0 | 0.0    | 3651305.0 | 2344.0   | 0.0     | 0.0     | 2344.0   | 194089.0   | 6040957.0  | 0.0      | 6235046.0  | 16582.0  | 7000.0   | 0.0      | 23582.0  | 0.0      | 666716.0 | 12307.0   | 679023.0  | 691205.0   | 7624244.0  | 12307.0   | 8327756.0  | 449164.0  | 194089.0   | 2358.0  | 645611.0   | 423855.0   | 194089.0  | 25309.0   | 2358.0  | 645611.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 817491.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | Y       | N      | N       | N      | Y      | P                                                                        | 12       | 5      | 2       | 1025481600 | 1056931200 | 7319422.0  | 0.0       | 7319422.0  | 5757852.0  | 32400000.0 | 6635297.0 | 44793149.0 | 1534845.0 | 53647416.0 | 390694.0  | 2368278.0 | 798399.0 | 3557371.0 | 100874.0 | 596277.0  | 231098.0 | 928249.0  | 491568.0  | 2964555.0 | 1029497.0 | 4485620.0  | 235966.0 | 10343.0   | 0.0      | 246309.0  | 755440.0  | 2782954.0 | 311098.0  | 3849492.0 | 1482974.0 | 5757852.0  | 1340595.0 | 8581421.0  | 0.0       | 0.0        | 0.0      | 0.0        | 1813424.0 | 32400000.0 | 0.0     | 34213424.0 | 565108.0  | 0.0     | 0.0     | 565108.0  | 2963121.0 | 1200000.0 | 189711.0 | 4352832.0 | 741200.0  | 0.0      | 0.0     | 741200.0  | 0.0    | 5380337.0 | 0.0    | 5380337.0 | 0.0      | 0.0     | 4539.0  | 4539.0   | 6082853.0  | 38980337.0 | 194250.0 | 45257440.0 | 0.0      | 54960.0  | 0.0      | 54960.0  | 0.0      | 0.0      | 0.0       | 0.0       | 7565827.0  | 44793149.0 | 1534845.0 | 53893821.0 | 1462675.0 | 6082853.0  | 20299.0 | 7565827.0  | 5048394.0  | 1861934.0 | 635200.0  | 20299.0 | 7565827.0  | 1029497.0 | 311098.0 | 1340595.0 | 0.0      | 0.0       | 1340595.0 | 17019068.0 | 
```