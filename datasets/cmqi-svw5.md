# State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2004-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/cmqi-svw5) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/cmqi-svw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/cmqi-svw5/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | cmqi-svw5 |
| Name | State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2004, revenue, expenditures |
| Created | 2016-12-20T15:26:21Z |
| Publication Date | 2016-12-20T17:04:34Z |

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
series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=N t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=N t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp="FUND FOR THE IMPROVEMENT OF POST SECONDARY EDUCATION (FIPSE) (HIGHER EDUCATION ACT OF 1965, TITLE VII)" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=879957 m:siother=221300 m:totaida=623360 m:aidsala=530719 m:capitald=0 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=523084 m:oexpbena=6456 m:oexpbend=529540 m:oexpbenc=0 m:netacxu=113421 m:totincm=4450807 m:othincm=74420 m:aidlcd=0 m:aidlcc=0 m:totexpu=623360 m:totexpt=623360 m:allopstf=0 m:fioth=26412 m:aidlca=0 m:aidlcb=0 m:totexpd=4533494 m:allopcap=0 m:totexpa=649772 m:totexpc=74420 m:totexpb=3809302 m:othexpao=0 m:sistlaop=2619200 m:aidmlsa=0 m:popu_st=655435 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=1956804 m:aidmlsd=0 m:totopexc=74420 m:totopexd=3030177 m:totopexa=26412 m:aidothd=0 m:totopexb=2929345 m:aidothc=0 m:oexpothc=74420 m:aidothb=0 m:oexpothd=836603 m:aidotha=0 m:total_fi=644487 m:oexpotha=2500 m:oexpothb=759683 m:aidplsc=0 m:aidplsd=0 m:total_si=3731900 m:totoxstb=1932892 m:totoxsta=23912 m:serpovxu=0 m:oexpcold=236770 m:lstainc=618075 m:aidplsa=0 m:oexpcolb=236770 m:grexpt=623360 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=509939 m:oexpsalb=1409808 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=784971 m:siaidlib=891400 m:othexpb=0 m:aidipla=92641 m:oexpsala=17456 m:aidoila=0 m:othexpc=0 m:aidiplb=692330 m:aidoilb=0 m:aidsald=718346 m:totaidd=1503317 m:aidoilc=0 m:totaidc=0 m:oexpsald=1427264 m:aidoild=0 m:aidsalb=187627 m:aidsalc=0 m:othexpa=0

series e:cmqi-svw5 d:2003-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=WWW.APLS.STATE.AL.US t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=6678958 m:siother=2534975 m:totaida=1371107 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=80160 m:swexpt=917878 m:admexpu=80160 m:oexpbenb=472397 m:oexpbena=0 m:oexpbend=472397 m:oexpbenc=0 m:netacxu=447176 m:totincm=11613509 m:othincm=255311 m:aidlcd=0 m:aidlcc=0 m:totexpu=2369145 m:totexpt=2369145 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=11456050 m:allopcap=0 m:totexpa=2369145 m:totexpc=126774 m:totexpb=8960131 m:othexpao=0 m:sistlaop=2312470 m:aidmlsa=0 m:popu_st=4530182 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2270036 m:aidmlsd=0 m:totopexc=0 m:totopexd=3279211 m:totopexa=998038 m:aidothd=0 m:totopexb=2281173 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:oexpothd=771522 m:aidotha=0 m:total_fi=2369145 m:oexpotha=760385 m:oexpothb=11137 m:aidplsc=0 m:aidplsd=2509102 m:total_si=8989053 m:totoxstb=2270036 m:totoxsta=0 m:serpovxu=144707 m:oexpcold=237653 m:lstainc=2369145 m:aidplsa=171851 m:oexpcolb=0 m:grexpt=1371107 m:aidplsb=2337251 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1697102 m:oexpsalb=1797639 m:othexpd=0 m:aidiplc=126774 m:oexpcola=237653 m:oexpsalc=0 m:aidipld=3078872 m:siaidlib=4141608 m:othexpb=0 m:aidipla=1145366 m:oexpsala=0 m:aidoila=53890 m:othexpc=0 m:aidiplb=1806732 m:aidoilb=0 m:aidsald=2534975 m:totaidd=8176839 m:aidoilc=0 m:totaidc=126774 m:oexpsald=1797639 m:aidoild=53890 m:aidsalb=2534975 m:aidsalc=0 m:othexpa=0

series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1085 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=553 m:capitala=85405 m:totaidb=2084889 m:siother=158082 m:totaida=0 m:aidsala=0 m:capitald=85958 m:totox_ao=0 m:admexpt=33697 m:swexpt=1578662 m:admexpu=33697 m:oexpbenb=380233 m:oexpbena=98272 m:oexpbend=478505 m:oexpbenc=0 m:netacxu=1431660 m:totincm=6740807 m:othincm=3341 m:aidlcd=0 m:aidlcc=0 m:totexpu=1612359 m:totexpt=1612359 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=6799476 m:allopcap=0 m:totexpa=1612359 m:totexpc=86518 m:totexpb=5100599 m:othexpao=0 m:sistlaop=2942517 m:aidmlsa=0 m:popu_st=2752629 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2261871 m:aidmlsd=0 m:totopexc=1629 m:totopexd=4543740 m:totopexa=1526954 m:aidothd=0 m:totopexb=3015157 m:aidothc=0 m:oexpothc=1629 m:aidothb=0 m:oexpothd=1842984 m:aidotha=0 m:total_fi=1636867 m:oexpotha=809353 m:oexpothb=1032002 m:aidplsc=0 m:aidplsd=1161668 m:total_si=5100599 m:totoxstb=1878173 m:totoxsta=383698 m:serpovxu=0 m:oexpcold=438885 m:lstainc=1636867 m:aidplsa=0 m:oexpcolb=104982 m:grexpt=0 m:aidplsb=1161668 m:oexpcolc=0 m:allopoth=0 m:serdifxu=147002 m:oexpsalb=1497940 m:othexpd=0 m:aidiplc=84889 m:oexpcola=333903 m:oexpsalc=0 m:aidipld=1008110 m:siaidlib=2000000 m:othexpb=0 m:aidipla=0 m:oexpsala=285426 m:aidoila=0 m:othexpc=0 m:aidiplb=923221 m:aidoilb=0 m:aidsald=0 m:totaidd=2169778 m:aidoilc=0 m:totaidc=84889 m:oexpsald=1783366 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:cmqi-svw5 l:"State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/cmqi-svw5

property e:cmqi-svw5 t:meta.view v:id=cmqi-svw5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:cmqi-svw5 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:cmqi-svw5 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```