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
series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=N t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=N t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp="FUND FOR THE IMPROVEMENT OF POST SECONDARY EDUCATION (FIPSE) (HIGHER EDUCATION ACT OF 1965, TITLE VII)" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=879957 m:siother=221300 m:totaida=623360 m:aidsala=530719 m:capitald=0 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=523084 m:oexpbena=6456 m:oexpbend=529540 m:oexpbenc=0 m:netacxu=113421 m:totincm=4450807 m:othincm=74420 m:aidlcd=0 m:aidlcc=0 m:totexpu=623360 m:totexpt=623360 m:allopstf=0 m:fioth=26412 m:aidlca=0 m:aidlcb=0 m:totexpd=4533494 m:allopcap=0 m:totexpa=649772 m:totexpc=74420 m:totexpb=3809302 m:othexpao=0 m:sistlaop=2619200 m:aidmlsa=0 m:popu_st=655435 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=1956804 m:aidmlsd=0 m:totopexc=74420 m:totopexd=3030177 m:totopexa=26412 m:aidothd=0 m:totopexb=2929345 m:aidothc=0 m:aidothb=0 m:oexpothc=74420 m:total_fi=644487 m:aidotha=0 m:oexpothd=836603 m:oexpotha=2500 m:oexpothb=759683 m:aidplsc=0 m:aidplsd=0 m:total_si=3731900 m:totoxstb=1932892 m:totoxsta=23912 m:serpovxu=0 m:oexpcold=236770 m:lstainc=618075 m:grexpt=623360 m:oexpcolb=236770 m:aidplsa=0 m:allopoth=0 m:oexpcolc=0 m:aidplsb=0 m:oexpcola=0 m:aidiplc=0 m:othexpd=0 m:oexpsalb=1409808 m:serdifxu=509939 m:siaidlib=891400 m:aidipld=784971 m:oexpsalc=0 m:aidipla=92641 m:othexpb=0 m:aidiplb=692330 m:othexpc=0 m:aidoila=0 m:oexpsala=17456 m:totaidd=1503317 m:aidsald=718346 m:aidoilb=0 m:totaidc=0 m:aidoilc=0 m:aidsalb=187627 m:aidoild=0 m:oexpsald=1427264 m:aidsalc=0 m:othexpa=0

series e:cmqi-svw5 d:2003-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=WWW.APLS.STATE.AL.US t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=6678958 m:siother=2534975 m:totaida=1371107 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=80160 m:swexpt=917878 m:admexpu=80160 m:oexpbenb=472397 m:oexpbena=0 m:oexpbend=472397 m:oexpbenc=0 m:netacxu=447176 m:totincm=11613509 m:othincm=255311 m:aidlcd=0 m:aidlcc=0 m:totexpu=2369145 m:totexpt=2369145 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=11456050 m:allopcap=0 m:totexpa=2369145 m:totexpc=126774 m:totexpb=8960131 m:othexpao=0 m:sistlaop=2312470 m:aidmlsa=0 m:popu_st=4530182 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2270036 m:aidmlsd=0 m:totopexc=0 m:totopexd=3279211 m:totopexa=998038 m:aidothd=0 m:totopexb=2281173 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:total_fi=2369145 m:aidotha=0 m:oexpothd=771522 m:oexpotha=760385 m:oexpothb=11137 m:aidplsc=0 m:aidplsd=2509102 m:total_si=8989053 m:totoxstb=2270036 m:totoxsta=0 m:serpovxu=144707 m:oexpcold=237653 m:lstainc=2369145 m:grexpt=1371107 m:oexpcolb=0 m:aidplsa=171851 m:allopoth=0 m:oexpcolc=0 m:aidplsb=2337251 m:oexpcola=237653 m:aidiplc=126774 m:othexpd=0 m:oexpsalb=1797639 m:serdifxu=1697102 m:siaidlib=4141608 m:aidipld=3078872 m:oexpsalc=0 m:aidipla=1145366 m:othexpb=0 m:aidiplb=1806732 m:othexpc=0 m:aidoila=53890 m:oexpsala=0 m:totaidd=8176839 m:aidsald=2534975 m:aidoilb=0 m:totaidc=126774 m:aidoilc=0 m:aidsalb=2534975 m:aidoild=53890 m:oexpsald=1797639 m:aidsalc=0 m:othexpa=0

series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1085 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=553 m:capitala=85405 m:totaidb=2084889 m:siother=158082 m:totaida=0 m:aidsala=0 m:capitald=85958 m:totox_ao=0 m:admexpt=33697 m:swexpt=1578662 m:admexpu=33697 m:oexpbenb=380233 m:oexpbena=98272 m:oexpbend=478505 m:oexpbenc=0 m:netacxu=1431660 m:totincm=6740807 m:othincm=3341 m:aidlcd=0 m:aidlcc=0 m:totexpu=1612359 m:totexpt=1612359 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=6799476 m:allopcap=0 m:totexpa=1612359 m:totexpc=86518 m:totexpb=5100599 m:othexpao=0 m:sistlaop=2942517 m:aidmlsa=0 m:popu_st=2752629 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2261871 m:aidmlsd=0 m:totopexc=1629 m:totopexd=4543740 m:totopexa=1526954 m:aidothd=0 m:totopexb=3015157 m:aidothc=0 m:aidothb=0 m:oexpothc=1629 m:total_fi=1636867 m:aidotha=0 m:oexpothd=1842984 m:oexpotha=809353 m:oexpothb=1032002 m:aidplsc=0 m:aidplsd=1161668 m:total_si=5100599 m:totoxstb=1878173 m:totoxsta=383698 m:serpovxu=0 m:oexpcold=438885 m:lstainc=1636867 m:grexpt=0 m:oexpcolb=104982 m:aidplsa=0 m:allopoth=0 m:oexpcolc=0 m:aidplsb=1161668 m:oexpcola=333903 m:aidiplc=84889 m:othexpd=0 m:oexpsalb=1497940 m:serdifxu=147002 m:siaidlib=2000000 m:aidipld=1008110 m:oexpsalc=0 m:aidipla=0 m:othexpb=0 m:aidiplb=923221 m:othexpc=0 m:aidoila=0 m:oexpsala=285426 m:totaidd=2169778 m:aidsald=0 m:aidoilb=0 m:totaidc=84889 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1783366 m:aidsalc=0 m:othexpa=0
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

property e:cmqi-svw5 t:meta.view d:2017-06-09T13:51:06.072Z v:id=cmqi-svw5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:cmqi-svw5 t:meta.view.license d:2017-06-09T13:51:06.072Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:cmqi-svw5 t:meta.view.owner d:2017-06-09T13:51:06.072Z v:id=xhhh-dddv v:screenName="Jason Enos" v:lastNotificationSeenAt=1495633902 v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.tableauthor d:2017-06-09T13:51:06.072Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:lastNotificationSeenAt=1495633902 v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:51:06.072Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola  | oexpcolb | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila   | aidoilb | aidoilc | aidoild   | aidmlsa   | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca  | aidlcb    | aidlcc | aidlcd    | aidotha | aidothb | aidothc | aidothd | totaida    | totaidb    | totaidc  | totaidd    | capitala | capitalb | capitalc | capitald | othexpa   | othexpb  | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | netacxu    | serdifxu  | serpovxu  | admexpu  | totexpu    | allopstf  | allopoth | totox_ao  | allopcap | othexpao  | totexpao  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | ===================================== | ======= | ====== | ======= | ====== | ====== | ====================================================================================================== | ======== | ====== | ======= | ========== | ========== | ========== | ======== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========== | ======= | ========== | ========= | ======= | ======= | ========= | ========= | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ======= | ========= | ====== | ========= | ======= | ======= | ======= | ======= | ========== | ========== | ======== | ========== | ======== | ======== | ======== | ======== | ========= | ======== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========== | ========= | ========= | ======== | ========== | ========= | ======== | ========= | ======== | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US               | Y       | Y      | N       | Y      | N      | FUND FOR THE IMPROVEMENT OF POST SECONDARY EDUCATION (FIPSE) (HIGHER EDUCATION ACT OF 1965, TITLE VII) | 2        | 8      | 1       | 1057017600 | 1088553600 | 618075.0   | 26412.0  | 644487.0   | 2619200.0  | 891400.0   | 221300.0  | 3731900.0  | 74420.0   | 4450807.0  | 17456.0   | 1409808.0 | 0.0      | 1427264.0 | 6456.0   | 523084.0  | 0.0      | 529540.0  | 23912.0   | 1932892.0 | 0.0      | 1956804.0  | 0.0       | 236770.0 | 0.0      | 236770.0  | 2500.0    | 759683.0  | 74420.0  | 836603.0  | 26412.0   | 2929345.0  | 74420.0   | 3030177.0  | 92641.0   | 692330.0   | 0.0      | 784971.0   | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 530719.0  | 187627.0  | 0.0     | 718346.0  | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 623360.0   | 879957.0   | 0.0      | 1503317.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 649772.0   | 3809302.0  | 74420.0   | 4533494.0  | 0.0       | 623360.0   | 0.0      | 623360.0   | 113421.0   | 509939.0  | 0.0       | 0.0      | 623360.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 655435.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | Y       | N      | N       | N      | Y      | P                                                                                                      | 1        | 5      | 1       | 1064966400 | 1096502400 | 2369145.0  | 0.0      | 2369145.0  | 2312470.0  | 4141608.0  | 2534975.0 | 8989053.0  | 255311.0  | 11613509.0 | 0.0       | 1797639.0 | 0.0      | 1797639.0 | 0.0      | 472397.0  | 0.0      | 472397.0  | 0.0       | 2270036.0 | 0.0      | 2270036.0  | 237653.0  | 0.0      | 0.0      | 237653.0  | 760385.0  | 11137.0   | 0.0      | 771522.0  | 998038.0  | 2281173.0  | 0.0       | 3279211.0  | 1145366.0 | 1806732.0  | 126774.0 | 3078872.0  | 171851.0  | 2337251.0  | 0.0     | 2509102.0  | 53890.0   | 0.0     | 0.0     | 53890.0   | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 2534975.0 | 0.0     | 2534975.0 | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 1371107.0  | 6678958.0  | 126774.0 | 8176839.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2369145.0  | 8960131.0  | 126774.0  | 11456050.0 | 917878.0  | 1371107.0  | 80160.0  | 2369145.0  | 447176.0   | 1697102.0 | 144707.0  | 80160.0  | 2369145.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 4530182.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     | Y       | N      | N       | N      | N      | P                                                                                                      | 5        | 5      | 1       | 1057017600 | 1088553600 | 1636867.0  | 0.0      | 1636867.0  | 2942517.0  | 2000000.0  | 158082.0  | 5100599.0  | 3341.0    | 6740807.0  | 285426.0  | 1497940.0 | 0.0      | 1783366.0 | 98272.0  | 380233.0  | 0.0      | 478505.0  | 383698.0  | 1878173.0 | 0.0      | 2261871.0  | 333903.0  | 104982.0 | 0.0      | 438885.0  | 809353.0  | 1032002.0 | 1629.0   | 1842984.0 | 1526954.0 | 3015157.0  | 1629.0    | 4543740.0  | 0.0       | 923221.0   | 84889.0  | 1008110.0  | 0.0       | 1161668.0  | 0.0     | 1161668.0  | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 0.0        | 2084889.0  | 84889.0  | 2169778.0  | 85405.0  | 553.0    | 0.0      | 85958.0  | 0.0       | 0.0      | 0.0       | 0.0       | 1612359.0  | 5100599.0  | 86518.0   | 6799476.0  | 1578662.0 | 0.0        | 33697.0  | 1612359.0  | 1431660.0  | 147002.0  | 0.0       | 33697.0  | 1612359.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2752629.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                         | Y       | N      | N       | N      | N      | IMLS NATIONAL LEADERSHIP GRANT, NHPRC (NATIONAL HISTORICAL PUBLICATIONS AND RECORDS COMMISSION) GRANT  | 4        | 6      | 1       | 1057017600 | 1088553600 | 2937400.0  | 100500.0 | 3037900.0  | 6565800.0  | 651400.0   | 97000.0   | 7314200.0  | 891900.0  | 11244000.0 | 55574.0   | 3586378.0 | 265030.0 | 3906982.0 | 10565.0  | 935346.0  | 76889.0  | 1022800.0 | 66139.0   | 4521724.0 | 341919.0 | 4929782.0  | 7560.0    | 200095.0 | 99990.0  | 307645.0  | 549697.0  | 1581945.0 | 278130.0 | 2409772.0 | 623396.0  | 6303764.0  | 720039.0  | 7647199.0  | 349221.0  | 562543.0   | 0.0      | 911764.0   | 460139.0  | 0.0        | 0.0     | 460139.0   | 75700.0   | 0.0     | 0.0     | 75700.0   | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0     | 8543.0    | 0.0    | 8543.0    | 30000.0 | 0.0     | 0.0     | 30000.0 | 915060.0   | 571086.0   | 0.0      | 1486146.0  | 0.0      | 3675.0   | 22607.0  | 26282.0  | 1507695.0 | 0.0      | 0.0       | 1507695.0 | 3046151.0  | 6878525.0  | 742646.0  | 10667322.0 | 1933056.0 | 915060.0   | 89284.0  | 2937400.0  | 1468923.0  | 877074.0  | 502119.0  | 89284.0  | 2937400.0  | 1624628.0 | 507258.0 | 2131886.0 | 18959.0  | 0.0       | 2150845.0 | 5743834.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    | Y       | N      | N       | N      | Y      | P                                                                                                      | 6        | 8      | 2       | 1057017600 | 1088553600 | 16360507.0 | 0.0      | 16360507.0 | 11940744.0 | 36263407.0 | 0.0       | 48204151.0 | 393394.0  | 64958052.0 | 2204078.0 | 5722786.0 | 175852.0 | 8102716.0 | 677538.0 | 1879711.0 | 114944.0 | 2672193.0 | 2881616.0 | 7602497.0 | 290796.0 | 10774909.0 | 233738.0  | 702997.0 | 66406.0  | 1003141.0 | 2854130.0 | 3635250.0 | 36192.0  | 6525572.0 | 5969484.0 | 11940744.0 | 393394.0  | 18303622.0 | 2623482.0 | 33225474.0 | 0.0      | 35848956.0 | 0.0       | 0.0        | 0.0     | 0.0        | 1218479.0 | 0.0     | 0.0     | 1218479.0 | 436122.0  | 3037933.0 | 0.0     | 3474055.0 | 6112940.0 | 0.0       | 0.0     | 6112940.0 | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 10391023.0 | 36263407.0 | 0.0      | 46654430.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 16360507.0 | 48204151.0 | 393394.0  | 64958052.0 | 5855003.0 | 10391023.0 | 114481.0 | 16360507.0 | 12710960.0 | 2477562.0 | 1057504.0 | 114481.0 | 16360507.0 | 1961739.0 | 412183.0 | 2373922.0 | 0.0      | 0.0       | 2373922.0 | 35893799.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX                       | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM | N       | N      | N       | N      | Y      | P                                                                                                      | 8        | 7      | 1       | 1057017600 | 1088553600 | 2268085.0  | 0.0      | 2268085.0  | 1340905.0  | 600000.0   | 93800.0   | 2034705.0  | 292545.0  | 4595335.0  | 952882.0  | 993518.0  | 60765.0  | 2007165.0 | 209169.0 | 218089.0  | 13339.0  | 440597.0  | 1162051.0 | 1211607.0 | 74104.0  | 2447762.0  | 52900.0   | 0.0      | 0.0      | 52900.0   | 517409.0  | 129298.0  | 77090.0  | 723797.0  | 1732360.0 | 1340905.0  | 151194.0  | 3224459.0  | 36780.0   | 0.0        | 102421.0 | 139201.0   | 0.0       | 0.0        | 0.0     | 0.0        | 186060.0  | 0.0     | 0.0     | 186060.0  | 225988.0  | 600000.0  | 0.0     | 825988.0  | 47168.0   | 93800.0   | 0.0     | 140968.0  | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 495996.0   | 693800.0   | 102421.0 | 1292217.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2228356.0  | 2034705.0  | 253615.0  | 4516676.0  | 1639010.0 | 495996.0   | 93350.0  | 2228356.0  | 827543.0   | 1307463.0 | 0.0       | 93350.0  | 2228356.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 4601403.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | Y       | N      | N       | N      | N      | LSCA TITLE II, NATIONAL HISTORICAL PUBLICATION AND RECORDS GRANT, JUDICIAL RECORDS PROJECT             | 9        | 1      | 1       | 1057017600 | 1088553600 | 1780106.0  | 80595.0  | 1860701.0  | 9051763.0  | 3673137.0  | 0.0       | 12724900.0 | 2503323.0 | 17088924.0 | 824245.0  | 5257513.0 | 210726.0 | 6292484.0 | 384986.0 | 0.0       | 87489.0  | 472475.0  | 1209231.0 | 5257513.0 | 298215.0 | 6764959.0  | 134080.0  | 685204.0 | 32458.0  | 851742.0  | 496801.0  | 6009761.0 | 445633.0 | 6952195.0 | 1840112.0 | 11952478.0 | 776306.0  | 14568896.0 | 36330.0   | 1023137.0  | 0.0      | 1059467.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 150000.0  | 0.0     | 150000.0  | 40480.0 | 1241908.0 | 0.0    | 1282388.0 | 0.0     | 0.0     | 0.0     | 0.0     | 76810.0    | 2415045.0  | 0.0      | 2491855.0  | 0.0      | 0.0      | 15017.0  | 15017.0  | 0.0       | 0.0      | 1363657.0 | 1363657.0 | 1916922.0  | 14367523.0 | 2154980.0 | 18439425.0 | 1627536.0 | 36330.0    | 24929.0  | 1688795.0  | 291287.0   | 1366759.0 | 5820.0    | 24929.0  | 1688795.0  | 1033798.0 | 122888.0 | 1156686.0 | 0.0      | 1363657.0 | 2520343.0 | 3503604.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     | Y       | N      | N       | N      | N      | P                                                                                                      | 11       | 2      | 1       | 1064966400 | 1096502400 | 598204.0   | 0.0      | 598204.0   | 28655450.0 | 0.0        | 0.0       | 28655450.0 | 946323.0  | 30199977.0 | 286421.0  | 243645.0  | 0.0      | 530066.0  | 54556.0  | 41294.0   | 0.0      | 95850.0   | 340977.0  | 284939.0  | 0.0      | 625916.0   | 0.0       | 0.0      | 0.0      | 0.0       | 257227.0  | 25233.0   | 0.0      | 282460.0  | 598204.0  | 310172.0   | 0.0       | 908376.0   | 0.0       | 26981748.0 | 946323.0 | 27928071.0 | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0     | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0     | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 0.0        | 26981748.0 | 946323.0 | 27928071.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 598204.0   | 27291920.0 | 946323.0  | 28836447.0 | 598204.0  | 0.0        | 0.0      | 598204.0   | 143201.0   | 351541.0  | 103462.0  | 0.0      | 598204.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 553523.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                   | Y       | N      | N       | N      | N      | P                                                                                                      | 10       | 2      | 1       | 1057017600 | 1088553600 | 619246.0   | 0.0      | 619246.0   | 1210178.0  | 2869500.0  | 5661365.0 | 9741043.0  | 481538.0  | 10841827.0 | 313828.0  | 364285.0  | 0.0      | 678113.0  | 100424.0 | 133899.0  | 0.0      | 234323.0  | 414252.0  | 498184.0  | 0.0      | 912436.0   | 960.0     | 6378.0   | 0.0      | 7338.0    | 59819.0   | 545496.0  | 233564.0 | 838879.0  | 475031.0  | 1050058.0  | 233564.0  | 1758653.0  | 110360.0  | 2566205.0  | 0.0      | 2676565.0  | 0.0       | 221099.0   | 0.0     | 221099.0   | 54437.0   | 0.0     | 0.0     | 54437.0   | 0.0       | 0.0       | 0.0     | 0.0       | 79145.0   | 369337.0  | 0.0     | 448482.0  | 0.0     | 1887822.0 | 0.0    | 1887822.0 | 0.0     | 0.0     | 0.0     | 0.0     | 243942.0   | 5044463.0  | 0.0      | 5288405.0  | 0.0      | 7000.0   | 0.0      | 7000.0   | 0.0       | 656710.0 | 0.0       | 656710.0  | 718973.0   | 6758231.0  | 233564.0  | 7710768.0  | 468164.0  | 243942.0   | 3447.0   | 715553.0   | 448960.0   | 244966.0  | 18180.0   | 3447.0   | 715553.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 830364.0   | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | Y       | N      | N       | N      | Y      | P                                                                                                      | 12       | 5      | 1       | 1057017600 | 1088553600 | 8826055.0  | 0.0      | 8826055.0  | 7147224.0  | 36475738.0 | 1481274.0 | 45104236.0 | 1481605.0 | 55411896.0 | 349635.0  | 2152936.0 | 644399.0 | 3146970.0 | 101278.0 | 594429.0  | 208605.0 | 904312.0  | 450913.0  | 2747365.0 | 853004.0 | 4051282.0  | 1730063.0 | 606815.0 | 0.0      | 2336878.0 | 1779876.0 | 2544315.0 | 590646.0 | 4914837.0 | 3960852.0 | 5898495.0  | 1443650.0 | 11302997.0 | 0.0       | 0.0        | 0.0      | 0.0        | 1163963.0 | 31849233.0 | 0.0     | 33013196.0 | 141800.0  | 0.0     | 0.0     | 141800.0  | 1603636.0 | 1200000.0 | 0.0     | 2803636.0 | 643367.0  | 0.0       | 0.0     | 643367.0  | 0.0     | 4626505.0 | 0.0    | 4626505.0 | 0.0     | 0.0     | 0.0     | 0.0     | 3552766.0  | 37675738.0 | 0.0      | 41228504.0 | 31040.0  | 48728.0  | 37955.0  | 117723.0 | 0.0       | 0.0      | 0.0       | 0.0       | 7544658.0  | 43622961.0 | 1481605.0 | 52649224.0 | 3915727.0 | 3552766.0  | 75943.0  | 7544436.0  | 4456996.0  | 2705686.0 | 305811.0  | 75943.0  | 7544436.0  | 853004.0  | 590646.0 | 1443650.0 | 37955.0  | 0.0       | 1481605.0 | 17397161.0 | 
```