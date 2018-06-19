# State Libraries Survey, FY 2000, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2000-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/jwf5-pnss) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/jwf5-pnss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/jwf5-pnss/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | jwf5-pnss |
| Name | State Libraries Survey, FY 2000, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2000, revenue, expenditures |
| Created | 2016-12-20T15:21:19Z |
| Publication Date | 2016-12-20T17:04:29Z |

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
series e:jwf5-pnss d:1999-07-01T00:00:00.000Z t:physzip4=571 t:physcity=JUNEAU t:mailcity=JUNEAU t:webaddr=WWW.STATE.AK.US/LAM/LIBRARY.HTML t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571 t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:capitalc=0 m:capitalb=100000 m:capitala=0 m:totaidb=887792 m:siother=221300 m:totaida=477653 m:aidsala=373228 m:capitald=100000 m:totox_ao=0 m:admexpt=0 m:swexpt=93750 m:admexpu=0 m:oexpbenb=750236 m:oexpbena=0 m:oexpbend=750236 m:oexpbenc=0 m:netacxu=295495 m:totincm=4516603 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=571403 m:totexpt=571403 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=4417236 m:allopcap=0 m:totexpa=571403 m:totexpc=0 m:totexpb=3845833 m:sistlaop=2832500 m:aidmlsa=0 m:popu_st=622000 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=1907057 m:aidmlsd=0 m:totopexc=0 m:totopexd=2858041 m:totopexa=0 m:aidothd=0 m:totopexb=2858041 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=774484 m:aidotha=0 m:total_fi=571403 m:oexpotha=0 m:oexpothb=774484 m:aidplsc=0 m:aidplsd=0 m:total_si=3945200 m:totoxstb=1907057 m:totoxsta=0 m:serpovxu=0 m:oexpcold=176500 m:lstainc=571403 m:grexpt=477653 m:aidplsa=0 m:oexpcolb=176500 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=275908 m:oexpsalb=1156821 m:othexpd=93750 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=754433 m:siaidlib=891400 m:othexpb=0 m:aidipla=76470 m:oexpsala=0 m:aidoila=27955 m:othexpc=0 m:aidiplb=677963 m:aidoilb=125473 m:aidsald=457584 m:totaidd=1365445 m:aidoilc=0 m:totaidc=0 m:oexpsald=1156821 m:aidoild=153428 m:aidsalb=84356 m:aidsalc=0 m:othexpa=93750

series e:jwf5-pnss d:1999-10-01T00:00:00.000Z t:physzip4=1 t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:webaddr=WWW.APLS.STATE.AL.US t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailzip4=1 t:mailaddr="6030 MONTICELLO DRIVE" t:fiothsp="LSCA, TITLE II" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4983347 m:siother=0 m:totaida=1216466 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=86076 m:swexpt=974108 m:admexpu=86076 m:oexpbenb=464903 m:oexpbena=0 m:oexpbend=464903 m:oexpbenc=0 m:netacxu=504137 m:totincm=13116293 m:othincm=1527 m:aidlcd=124744 m:aidlcc=0 m:totexpu=2151906 m:totexpt=2151906 m:allopstf=0 m:fioth=124744 m:aidlca=124744 m:aidlcb=0 m:totexpd=13116293 m:allopcap=0 m:totexpa=2276650 m:totexpc=1527 m:totexpb=10838116 m:sistlaop=5854769 m:aidmlsa=20000 m:popu_st=4351999 m:aidmlsc=0 m:aidmlsb=734374 m:totoxstc=0 m:totexpao=0 m:totoxstd=2428754 m:aidmlsd=754374 m:totopexc=1527 m:totopexd=6916480 m:totopexa=1060184 m:aidothd=0 m:totopexb=5854769 m:aidothc=0 m:aidothb=0 m:oexpothc=1527 m:oexpothd=1118901 m:aidotha=0 m:total_fi=2276650 m:oexpotha=472968 m:oexpothb=644406 m:aidplsc=0 m:aidplsd=789494 m:total_si=10838116 m:totoxstb=2428754 m:totoxsta=0 m:serpovxu=48397 m:oexpcold=3368825 m:lstainc=2151906 m:grexpt=1091722 m:aidplsa=133243 m:oexpcolb=2781609 m:aidplsb=656251 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1513296 m:oexpsalb=1963851 m:othexpd=0 m:aidiplc=0 m:oexpcola=587216 m:oexpsalc=0 m:aidipld=4531201 m:siaidlib=4983347 m:othexpb=0 m:aidipla=938479 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=3592722 m:aidoilb=0 m:aidsald=0 m:totaidd=6199813 m:aidoilc=0 m:totaidc=0 m:oexpsald=1963851 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:jwf5-pnss d:1999-07-01T00:00:00.000Z t:physzip4=1085 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:webaddr=WWW.ASL.LIB.AR.US t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1085 t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" m:capitalc=0 m:capitalb=12000 m:capitala=40610 m:totaidb=4828990 m:siother=0 m:totaida=0 m:aidsala=0 m:capitald=52610 m:totox_ao=0 m:admexpt=12947 m:swexpt=1148720 m:admexpu=12947 m:oexpbenb=371732 m:oexpbena=89804 m:oexpbend=461536 m:oexpbenc=0 m:netacxu=1034361 m:totincm=8953119 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=1161667 m:totexpt=1161667 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=8954447 m:allopcap=0 m:totexpa=1161667 m:totexpc=0 m:totexpb=7792780 m:sistlaop=2963789 m:aidmlsa=0 m:popu_st=2538303 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2123545 m:aidmlsd=0 m:totopexc=0 m:totopexd=4071909 m:totopexa=1121057 m:aidothd=0 m:totopexb=2950852 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=1620423 m:aidotha=0 m:total_fi=1160340 m:oexpotha=727071 m:oexpothb=893352 m:aidplsc=0 m:aidplsd=3217801 m:total_si=7792779 m:totoxstb=1773044 m:totoxsta=350501 m:serpovxu=0 m:oexpcold=327941 m:lstainc=1160340 m:grexpt=0 m:aidplsa=0 m:oexpcolb=284456 m:aidplsb=3217801 m:oexpcolc=0 m:allopoth=0 m:serdifxu=114359 m:oexpsalb=1401312 m:othexpd=938 m:aidiplc=0 m:oexpcola=43485 m:oexpsalc=0 m:aidipld=1611189 m:siaidlib=4828990 m:othexpb=938 m:aidipla=0 m:oexpsala=260697 m:aidoila=0 m:othexpc=0 m:aidiplb=1611189 m:aidoilb=0 m:aidsald=0 m:totaidd=4828990 m:aidoilc=0 m:totaidc=0 m:oexpsald=1662009 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:jwf5-pnss l:"State Libraries Survey, FY 2000, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/jwf5-pnss

property e:jwf5-pnss t:meta.view v:id=jwf5-pnss v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2000, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:jwf5-pnss t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:jwf5-pnss t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:jwf5-pnss t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:jwf5-pnss t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                      | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | fiothsp                                                                          | pub_fips | fystart   | fyend     | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother    | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila  | aidoilb  | aidoilc | aidoild  | aidmlsa   | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca   | aidlcb    | aidlcc | aidlcd    | aidotha | aidothb  | aidothc | aidothd  | totaida    | totaidb    | totaidc | totaidd    | capitala | capitalb | capitalc | capitald | othexpa | othexpb  | othexpc | othexpd  | totexpa    | totexpb    | totexpc  | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | netacxu   | serdifxu  | serpovxu | admexpu  | totexpu    | allopstf  | allopoth  | totox_ao  | allopcap | totexpao  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ============================= | =========== | ======= | ======= | ======== | ===================================== | ================================================================================ | ======== | ========= | ========= | ========== | ======== | ========== | ========== | ========== | ========== | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ========= | ========== | ======= | ========== | ========= | ========== | ======= | ========== | ======== | ======== | ======= | ======== | ========= | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ======== | ========= | ====== | ========= | ======= | ======== | ======= | ======== | ========== | ========== | ======= | ========== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ========== | ========== | ======== | ========== | ========= | ========== | ======== | ========== | ========= | ========= | ======== | ======== | ========== | ========= | ========= | ========= | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571               | JUNEAU      | AK      | 99811   | 571      | WWW.STATE.AK.US/LAM/LIBRARY.HTML      |                                                                                  | 2        | 930787200 | 962323200 | 571403.0   | 0.0      | 571403.0   | 2832500.0  | 891400.0   | 221300.0   | 3945200.0  | 0.0       | 4516603.0  | 0.0       | 1156821.0 | 0.0      | 1156821.0 | 0.0      | 750236.0  | 0.0      | 750236.0  | 0.0       | 1907057.0 | 0.0      | 1907057.0  | 0.0      | 176500.0  | 0.0      | 176500.0  | 0.0       | 774484.0  | 0.0      | 774484.0  | 0.0       | 2858041.0  | 0.0      | 2858041.0  | 76470.0   | 677963.0   | 0.0     | 754433.0   | 0.0       | 0.0        | 0.0     | 0.0        | 27955.0  | 125473.0 | 0.0     | 153428.0 | 0.0       | 0.0       | 0.0     | 0.0       | 373228.0  | 84356.0   | 0.0     | 457584.0  | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0      | 0.0     | 0.0      | 477653.0   | 887792.0   | 0.0     | 1365445.0  | 0.0      | 100000.0 | 0.0      | 100000.0 | 93750.0 | 0.0      | 0.0     | 93750.0  | 571403.0   | 3845833.0  | 0.0      | 4417236.0  | 93750.0   | 477653.0   | 0.0      | 571403.0   | 295495.0  | 275908.0  | 0.0      | 0.0      | 571403.0   | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 622000.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE         | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | LSCA, TITLE II                                                                   | 1        | 938736000 | 970272000 | 2151906.0  | 124744.0 | 2276650.0  | 5854769.0  | 4983347.0  | 0.0        | 10838116.0 | 1527.0    | 13116293.0 | 0.0       | 1963851.0 | 0.0      | 1963851.0 | 0.0      | 464903.0  | 0.0      | 464903.0  | 0.0       | 2428754.0 | 0.0      | 2428754.0  | 587216.0 | 2781609.0 | 0.0      | 3368825.0 | 472968.0  | 644406.0  | 1527.0   | 1118901.0 | 1060184.0 | 5854769.0  | 1527.0   | 6916480.0  | 938479.0  | 3592722.0  | 0.0     | 4531201.0  | 133243.0  | 656251.0   | 0.0     | 789494.0   | 0.0      | 0.0      | 0.0     | 0.0      | 20000.0   | 734374.0  | 0.0     | 754374.0  | 0.0       | 0.0       | 0.0     | 0.0       | 124744.0 | 0.0       | 0.0    | 124744.0  | 0.0     | 0.0      | 0.0     | 0.0      | 1216466.0  | 4983347.0  | 0.0     | 6199813.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 2276650.0  | 10838116.0 | 1527.0   | 13116293.0 | 974108.0  | 1091722.0  | 86076.0  | 2151906.0  | 504137.0  | 1513296.0 | 48397.0  | 86076.0  | 2151906.0  | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 4351999.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     |                                                                                  | 5        | 930787200 | 962323200 | 1160340.0  | 0.0      | 1160340.0  | 2963789.0  | 4828990.0  | 0.0        | 7792779.0  | 0.0       | 8953119.0  | 260697.0  | 1401312.0 | 0.0      | 1662009.0 | 89804.0  | 371732.0  | 0.0      | 461536.0  | 350501.0  | 1773044.0 | 0.0      | 2123545.0  | 43485.0  | 284456.0  | 0.0      | 327941.0  | 727071.0  | 893352.0  | 0.0      | 1620423.0 | 1121057.0 | 2950852.0  | 0.0      | 4071909.0  | 0.0       | 1611189.0  | 0.0     | 1611189.0  | 0.0       | 3217801.0  | 0.0     | 3217801.0  | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0      | 0.0     | 0.0      | 0.0        | 4828990.0  | 0.0     | 4828990.0  | 40610.0  | 12000.0  | 0.0      | 52610.0  | 0.0     | 938.0    | 0.0     | 938.0    | 1161667.0  | 7792780.0  | 0.0      | 8954447.0  | 1148720.0 | 0.0        | 12947.0  | 1161667.0  | 1034361.0 | 114359.0  | 0.0      | 12947.0  | 1161667.0  | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 2538303.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1100 WEST WASHINGTON STREET   | PHOENIX     | AZ      | 85007   | 2935     | WWW.LIB.AZ.US                         | LSCA TITLE II; 5-STATE NATIVE AMERICAN GRANT                                     | 4        | 930787200 | 962323200 | 1944541.0  | 121104.0 | 2065645.0  | 6565000.0  | 351400.0   | 77000.0    | 6993400.0  | 675475.0  | 9734520.0  | 42585.0   | 3319719.0 | 78983.0  | 3441287.0 | 7204.0   | 698368.0  | 18849.0  | 724421.0  | 49789.0   | 4018087.0 | 97832.0  | 4165708.0  | 9724.0   | 475000.0  | 0.0      | 484724.0  | 1342942.0 | 1823693.0 | 159949.0 | 3326584.0 | 1402455.0 | 6316780.0  | 257781.0 | 7977016.0  | 83541.0   | 351400.0   | 0.0     | 434941.0   | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 373355.0  | 77000.0   | 0.0     | 450355.0  | 33000.0  | 0.0       | 0.0    | 33000.0   | 88104.0 | 0.0      | 0.0     | 88104.0  | 578000.0   | 428400.0   | 0.0     | 1006400.0  | 158523.0 | 202138.0 | 14159.0  | 374820.0 | 0.0     | 0.0      | 0.0     | 0.0      | 2138978.0  | 6947318.0  | 271940.0 | 9358236.0  | 1311254.0 | 545000.0   | 88287.0  | 1944541.0  | 1438254.0 | 30000.0   | 388000.0 | 88287.0  | 1944541.0  | 1180815.0 | 499690.0  | 1680505.0 | 0.0      | 1680505.0 | 4678500.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837               | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    |                                                                                  | 6        | 930787200 | 962323200 | 14623319.0 | 0.0      | 14623319.0 | 17505079.0 | 55896000.0 | 0.0        | 73401079.0 | 502555.0  | 88526953.0 | 1287869.0 | 7169759.0 | 234165.0 | 8691793.0 | 248587.0 | 1300440.0 | 51053.0  | 1600080.0 | 1536456.0 | 8470199.0 | 285218.0 | 10291873.0 | 0.0      | 2154410.0 | 141293.0 | 2295703.0 | 1528111.0 | 6880470.0 | 75944.0  | 8484525.0 | 3064567.0 | 17505079.0 | 502455.0 | 21072101.0 | 2146761.0 | 52565664.0 | 0.0     | 54712425.0 | 849532.0  | 0.0        | 0.0     | 849532.0   | 845161.0 | 0.0      | 0.0     | 845161.0 | 271752.0  | 3185000.0 | 0.0     | 3456752.0 | 7445546.0 | 0.0       | 0.0     | 7445546.0 | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 145336.0 | 0.0     | 145336.0 | 11558752.0 | 55896000.0 | 0.0     | 67454752.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 14623319.0 | 73401079.0 | 502455.0 | 88526853.0 | 2963567.0 | 11558752.0 | 101000.0 | 14623319.0 | 9284221.0 | 4938642.0 | 299456.0 | 101000.0 | 14623319.0 | 1536456.0 | 1232264.0 | 2768720.0 | 0.0      | 2768720.0 | 33773000.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX               | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/LIBRARY_INDEX.HTM |                                                                                  | 8        | 930787200 | 962323200 | 1892001.0  | 0.0      | 1892001.0  | 1351698.0  | 5071602.0  | 0.0        | 6423300.0  | 32465.0   | 8347766.0  | 666279.0  | 908829.0  | 0.0      | 1575108.0 | 146256.0 | 199499.0  | 0.0      | 345755.0  | 812535.0  | 1108328.0 | 0.0      | 1920863.0  | 15000.0  | 101899.0  | 0.0      | 116899.0  | 406091.0  | 141471.0  | 16321.0  | 563883.0  | 1233626.0 | 1351698.0  | 16321.0  | 2601645.0  | 65808.0   | 134114.0   | 0.0     | 199922.0   | 0.0       | 0.0        | 0.0     | 0.0        | 270578.0 | 0.0      | 0.0     | 270578.0 | 218837.0  | 2449893.0 | 0.0     | 2668730.0 | 103162.0  | 2325589.0 | 0.0     | 2428751.0 | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 162006.0 | 0.0     | 162006.0 | 658385.0   | 5071602.0  | 0.0     | 5729987.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 1892011.0  | 6423300.0  | 16321.0  | 8331632.0  | 1157946.0 | 658385.0   | 75680.0  | 1892011.0  | 707429.0  | 1108902.0 | 0.0      | 75680.0  | 1892011.0  | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 4154269.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE            | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | CT NEWSPAPER PROJ NEA BASIC,LSCA TITLE II, HISTORIC PUBS & RECORDS, ARTS ENHANCE | 9        | 930787200 | 962323200 | 1915532.0  | 346873.0 | 2262405.0  | 12284249.0 | 3427609.0  | 0.0        | 15711858.0 | 1365927.0 | 19340190.0 | 898231.0  | 5550040.0 | 10478.0  | 6458749.0 | 362037.0 | 0.0       | 4325.0   | 366362.0  | 1260268.0 | 5550040.0 | 14803.0  | 6825111.0  | 86873.0  | 829672.0  | 87270.0  | 1003815.0 | 1135199.0 | 5631835.0 | 28204.0  | 6795238.0 | 2482340.0 | 12011547.0 | 130277.0 | 14624164.0 | 280280.0  | 1174644.0  | 0.0     | 1454924.0  | 0.0       | 0.0        | 0.0     | 0.0        | 10756.0  | 0.0      | 0.0     | 10756.0  | 350.0     | 782787.0  | 0.0     | 783137.0  | 0.0       | 1464840.0 | 0.0     | 1464840.0 | 317016.0 | 1470178.0 | 0.0    | 1787194.0 | 0.0     | 0.0      | 0.0     | 0.0      | 608402.0   | 4892449.0  | 0.0     | 5500851.0  | 1542.0   | 1000.0   | 0.0      | 2542.0   | 0.0     | 0.0      | 0.0     | 0.0      | 3092284.0  | 16904996.0 | 130277.0 | 20127557.0 | 1620882.0 | 291386.0   | 27095.0  | 1939363.0  | 505448.0  | 1263636.0 | 143184.0 | 27095.0  | 1939363.0  | 1145709.0 | 75171.0   | 1220880.0 | 0.0      | 1220880.0 | 3282031.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.            | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     |                                                                                  | 11       | 938736000 | 970272000 | 751363.0   | 0.0      | 751363.0   | 677042.0   | 0.0        | 0.0        | 677042.0   | 0.0       | 1428405.0  | 301429.0  | 236965.0  | 0.0      | 538394.0  | 54324.0  | 54163.0   | 0.0      | 108487.0  | 355753.0  | 291128.0  | 0.0      | 646881.0   | 19454.0  | 13541.0   | 0.0      | 32995.0   | 376156.0  | 372373.0  | 0.0      | 748529.0  | 751363.0  | 677042.0   | 0.0      | 1428405.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0      | 0.0     | 0.0      | 0.0        | 0.0        | 0.0     | 0.0        | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 751363.0   | 677042.0   | 0.0      | 1428405.0  | 748129.0  | 0.0        | 3234.0   | 751363.0   | 335472.0  | 346481.0  | 66176.0  | 3234.0   | 751363.0   | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 519000.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY       | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         | LSCA TITLE II                                                                    | 10       | 930787200 | 962323200 | 572769.0   | 19474.0  | 592243.0   | 959402.0   | 1871600.0  | 747800.0   | 3578802.0  | 0.0       | 4171045.0  | 284503.0  | 349376.0  | 0.0      | 633879.0  | 68132.0  | 95313.0   | 0.0      | 163445.0  | 352635.0  | 444689.0  | 0.0      | 797324.0   | 15715.0  | 6234.0    | 0.0      | 21949.0   | 389755.0  | 389419.0  | 0.0      | 779174.0  | 758105.0  | 840342.0   | 0.0      | 1598447.0  | 132168.0  | 1670562.0  | 0.0     | 1802730.0  | 0.0       | 0.0        | 0.0     | 0.0        | 25000.0  | 0.0      | 0.0     | 25000.0  | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 1365940.0 | 0.0    | 1365940.0 | 0.0     | 0.0      | 0.0     | 0.0      | 157168.0   | 3036502.0  | 0.0     | 3193670.0  | 102496.0 | 7000.0   | 0.0      | 109496.0 | 0.0     | 747655.0 | 0.0     | 747655.0 | 1017769.0  | 4631499.0  | 0.0      | 5649268.0  | 858601.0  | 157168.0   | 2000.0   | 1017769.0  | 1012769.0 | 3000.0    | 0.0      | 2000.0   | 1017769.0  | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 753538.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET     | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | LSCA TITLE II                                                                    | 12       | 930787200 | 962323200 | 6816933.0  | 370623.0 | 7187556.0  | 8322317.0  | 31400000.0 | 14150970.0 | 53873287.0 | 0.0       | 61060843.0 | 481299.0  | 2815694.0 | 0.0      | 3296993.0 | 144495.0 | 813429.0  | 0.0      | 957924.0  | 625794.0  | 3629123.0 | 0.0      | 4254917.0  | 200428.0 | 610368.0  | 0.0      | 810796.0  | 643671.0  | 3688928.0 | 0.0      | 4332599.0 | 1469893.0 | 7928419.0  | 0.0      | 9398312.0  | 0.0       | 0.0        | 0.0     | 0.0        | 1847673.0 | 31400000.0 | 0.0     | 33247673.0 | 370214.0 | 0.0      | 0.0     | 370214.0 | 1733510.0 | 1200000.0 | 0.0     | 2933510.0 | 1766236.0 | 0.0       | 0.0     | 1766236.0 | 370623.0 | 3890641.0 | 0.0    | 4261264.0 | 0.0     | 499809.0 | 0.0     | 499809.0 | 6088256.0  | 36990450.0 | 0.0     | 43078706.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 7558149.0  | 44918869.0 | 0.0      | 52477018.0 | 1207622.0 | 5386402.0  | 68953.0  | 6662977.0  | 5086277.0 | 1082432.0 | 425315.0 | 68953.0  | 6662977.0  | 852093.0  | 534185.0  | 1386278.0 | 0.0      | 1386278.0 | 15322040.0 | 
```