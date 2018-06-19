# State Libraries Survey, FY 1999, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1999-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/i95s-tzua) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/i95s-tzua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/i95s-tzua/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | i95s-tzua |
| Name | State Libraries Survey, FY 1999, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1999, revenue, expenditures |
| Created | 2016-12-20T15:20:32Z |
| Publication Date | 2016-12-20T17:04:28Z |

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
series e:i95s-tzua d:1998-07-01T00:00:00.000Z t:physzip4=571 t:physcity=JUNEAU t:mailcity=JUNEAU t:webaddr=WWW.STATE.AK.US/LAM/LIBRARY.HTML t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571 t:mailaddr="P.O. BOX 110571" t:fiothsp="LSCA TITLE II" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:capitalc=0 m:capitalb=100000 m:capitala=0 m:totaidb=962600 m:siother=277500 m:totaida=727508 m:aidsala=453148 m:capitald=100000 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=761883 m:oexpbena=0 m:oexpbend=761883 m:oexpbenc=0 m:netacxu=359448 m:totincm=5282240 m:othincm=0 m:aidlcd=70325 m:aidlcc=0 m:totexpu=657183 m:totexpt=657183 m:allopstf=0 m:fioth=70325 m:aidlca=70325 m:aidlcb=0 m:totexpd=4667356 m:allopcap=0 m:totexpa=739508 m:totexpc=0 m:totexpb=3927848 m:sistlaop=3366900 m:aidmlsa=0 m:popu_st=621400 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=1936633 m:aidmlsd=0 m:totopexc=0 m:totopexd=2877248 m:totopexa=12000 m:aidothd=63431 m:totopexb=2865248 m:aidothc=0 m:aidothb=34605 m:oexpothc=0 m:oexpothd=806453 m:aidotha=28826 m:total_fi=675240 m:oexpotha=12000 m:oexpothb=794453 m:aidplsc=0 m:aidplsd=0 m:total_si=4607000 m:totoxstb=1936633 m:totoxsta=0 m:serpovxu=25280 m:oexpcold=134162 m:lstainc=604915 m:grexpt=657183 m:aidplsa=0 m:oexpcolb=134162 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=272455 m:oexpsalb=1174750 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=839247 m:siaidlib=962600 m:othexpb=0 m:aidipla=37330 m:oexpsala=0 m:aidoila=137879 m:othexpc=0 m:aidiplb=801917 m:aidoilb=71052 m:aidsald=508174 m:totaidd=1690108 m:aidoilc=0 m:totaidc=0 m:oexpsald=1174750 m:aidoild=208931 m:aidsalb=55026 m:aidsalc=0 m:othexpa=0

series e:i95s-tzua d:1998-10-01T00:00:00.000Z t:physzip4=1 t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:webaddr=WWW.APLS.STATE.AL.US t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailzip4=1 t:mailaddr="6030 MONTICELLO DRIVE" t:fiothsp="LSCA TITLE II" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4949345 m:siother=0 m:totaida=1888852 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=87925 m:swexpt=919837 m:admexpu=87925 m:oexpbenb=401218 m:oexpbena=0 m:oexpbend=401218 m:oexpbenc=0 m:netacxu=779936 m:totincm=10827453 m:othincm=0 m:aidlcd=636852 m:aidlcc=0 m:totexpu=2259762 m:totexpt=2259762 m:allopstf=0 m:fioth=636852 m:aidlca=636852 m:aidlcb=0 m:totexpd=10827453 m:allopcap=0 m:totexpa=2896614 m:totexpc=0 m:totexpb=7930839 m:sistlaop=2981494 m:aidmlsa=0 m:popu_st=4137511 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2259558 m:aidmlsd=0 m:totopexc=0 m:totopexd=3989256 m:totopexa=1007762 m:aidothd=0 m:totopexb=2981494 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=1180722 m:aidotha=0 m:total_fi=2896614 m:oexpotha=528756 m:oexpothb=651966 m:aidplsc=0 m:aidplsd=943845 m:total_si=7930839 m:totoxstb=2259558 m:totoxsta=0 m:serpovxu=161982 m:oexpcold=548976 m:lstainc=2259762 m:grexpt=1252000 m:aidplsa=56096 m:oexpcolb=69970 m:aidplsb=887749 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1229919 m:oexpsalb=1858340 m:othexpd=0 m:aidiplc=0 m:oexpcola=479006 m:oexpsalc=0 m:aidipld=5257500 m:siaidlib=4949345 m:othexpb=0 m:aidipla=1195904 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=4061596 m:aidoilb=0 m:aidsald=0 m:totaidd=6838197 m:aidoilc=0 m:totaidc=0 m:oexpsald=1858340 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:i95s-tzua d:1998-07-01T00:00:00.000Z t:physzip4=1085 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:webaddr=www.asl.lib.ar.us t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1085 t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:fiothsp="LSCA TITLE I, TITLE II CONSTRUCTION, AND TITLE III" t:stlaname="ARKANSAS STATE LIBRARY" m:capitalc=0 m:capitalb=12000 m:capitala=91145 m:totaidb=3327798 m:siother=0 m:totaida=126480 m:aidsala=0 m:capitald=103145 m:totox_ao=0 m:admexpt=13655 m:swexpt=1129948 m:admexpu=13655 m:oexpbenb=344596 m:oexpbena=88184 m:oexpbend=432780 m:oexpbenc=0 m:netacxu=944926 m:totincm=7314495 m:othincm=0 m:aidlcd=46575 m:aidlcc=0 m:totexpu=1223508 m:totexpt=1223508 m:allopstf=0 m:fioth=574336 m:aidlca=46575 m:aidlcb=0 m:totexpd=7296708 m:allopcap=0 m:totexpa=1270084 m:totexpc=0 m:totexpb=6026624 m:sistlaop=2698825 m:aidmlsa=0 m:popu_st=2538303 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2032255 m:aidmlsd=0 m:totopexc=0 m:totopexd=3738822 m:totopexa=1052459 m:aidothd=0 m:totopexb=2686363 m:aidothc=0 m:aidothb=0 m:oexpothc=0 m:oexpothd=1266211 m:aidotha=0 m:total_fi=1287872 m:oexpotha=595024 m:oexpothb=671187 m:aidplsc=0 m:aidplsd=2591905 m:total_si=6026623 m:totoxstb=1678324 m:totoxsta=353931 m:serpovxu=0 m:oexpcold=440356 m:lstainc=713536 m:grexpt=79905 m:aidplsa=59018 m:oexpcolb=336852 m:aidplsb=2532887 m:oexpcolc=0 m:allopoth=0 m:serdifxu=264927 m:oexpsalb=1333728 m:othexpd=463 m:aidiplc=0 m:oexpcola=103504 m:oexpsalc=0 m:aidipld=815798 m:siaidlib=3327798 m:othexpb=463 m:aidipla=20887 m:oexpsala=265747 m:aidoila=0 m:othexpc=0 m:aidiplb=794911 m:aidoilb=0 m:aidsald=0 m:totaidd=3454278 m:aidoilc=0 m:totaidc=0 m:oexpsald=1599475 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:i95s-tzua l:"State Libraries Survey, FY 1999, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/i95s-tzua

property e:i95s-tzua t:meta.view v:id=i95s-tzua v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1999, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:i95s-tzua t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:i95s-tzua t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:i95s-tzua t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:i95s-tzua t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                      | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | fiothsp                                            | pub_fips | fystart   | fyend     | lstainc    | fioth     | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd  | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila  | aidoilb | aidoilc | aidoild  | aidmlsa   | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca   | aidlcb    | aidlcc | aidlcd    | aidotha  | aidothb  | aidothc | aidothd  | totaida    | totaidb    | totaidc | totaidd    | capitala | capitalb | capitalc | capitald | othexpa | othexpb  | othexpc | othexpd  | totexpa    | totexpb    | totexpc  | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | netacxu   | serdifxu  | serpovxu  | admexpu  | totexpu    | allopstf  | allopoth | totox_ao  | allopcap | totexpao  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ============================= | =========== | ======= | ======= | ======== | ===================================== | ================================================== | ======== | ========= | ========= | ========== | ========= | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ========= | ========== | ======= | ========== | ========= | ========== | ======= | ========== | ======== | ======= | ======= | ======== | ========= | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ======== | ========= | ====== | ========= | ======== | ======== | ======= | ======== | ========== | ========== | ======= | ========== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ========== | ========== | ======== | ========== | ========= | ========== | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========= | ======== | ========= | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571               | JUNEAU      | AK      | 99811   | 571      | WWW.STATE.AK.US/LAM/LIBRARY.HTML      | LSCA TITLE II                                      | 2        | 899251200 | 930700800 | 604915.0   | 70325.0   | 675240.0   | 3366900.0  | 962600.0   | 277500.0  | 4607000.0  | 0.0       | 5282240.0  | 0.0       | 1174750.0 | 0.0      | 1174750.0 | 0.0      | 761883.0  | 0.0      | 761883.0  | 0.0       | 1936633.0 | 0.0      | 1936633.0 | 0.0      | 134162.0  | 0.0      | 134162.0  | 12000.0   | 794453.0  | 0.0      | 806453.0  | 12000.0   | 2865248.0  | 0.0      | 2877248.0  | 37330.0   | 801917.0   | 0.0     | 839247.0   | 0.0       | 0.0        | 0.0     | 0.0        | 137879.0 | 71052.0 | 0.0     | 208931.0 | 0.0       | 0.0       | 0.0     | 0.0       | 453148.0  | 55026.0   | 0.0     | 508174.0  | 70325.0  | 0.0       | 0.0    | 70325.0   | 28826.0  | 34605.0  | 0.0     | 63431.0  | 727508.0   | 962600.0   | 0.0     | 1690108.0  | 0.0      | 100000.0 | 0.0      | 100000.0 | 0.0     | 0.0      | 0.0     | 0.0      | 739508.0   | 3927848.0  | 0.0      | 4667356.0  | 0.0       | 657183.0   | 0.0      | 657183.0   | 359448.0  | 272455.0  | 25280.0   | 0.0      | 657183.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 621400.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE         | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | LSCA TITLE II                                      | 1        | 907200000 | 938649600 | 2259762.0  | 636852.0  | 2896614.0  | 2981494.0  | 4949345.0  | 0.0       | 7930839.0  | 0.0       | 10827453.0 | 0.0       | 1858340.0 | 0.0      | 1858340.0 | 0.0      | 401218.0  | 0.0      | 401218.0  | 0.0       | 2259558.0 | 0.0      | 2259558.0 | 479006.0 | 69970.0   | 0.0      | 548976.0  | 528756.0  | 651966.0  | 0.0      | 1180722.0 | 1007762.0 | 2981494.0  | 0.0      | 3989256.0  | 1195904.0 | 4061596.0  | 0.0     | 5257500.0  | 56096.0   | 887749.0   | 0.0     | 943845.0   | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 636852.0 | 0.0       | 0.0    | 636852.0  | 0.0      | 0.0      | 0.0     | 0.0      | 1888852.0  | 4949345.0  | 0.0     | 6838197.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 2896614.0  | 7930839.0  | 0.0      | 10827453.0 | 919837.0  | 1252000.0  | 87925.0  | 2259762.0  | 779936.0  | 1229919.0 | 161982.0  | 87925.0  | 2259762.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 4137511.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR | LITTLE ROCK | AR      | 72201   | 1085     | www.asl.lib.ar.us                     | LSCA TITLE I, TITLE II CONSTRUCTION, AND TITLE III | 5        | 899251200 | 930700800 | 713536.0   | 574336.0  | 1287872.0  | 2698825.0  | 3327798.0  | 0.0       | 6026623.0  | 0.0       | 7314495.0  | 265747.0  | 1333728.0 | 0.0      | 1599475.0 | 88184.0  | 344596.0  | 0.0      | 432780.0  | 353931.0  | 1678324.0 | 0.0      | 2032255.0 | 103504.0 | 336852.0  | 0.0      | 440356.0  | 595024.0  | 671187.0  | 0.0      | 1266211.0 | 1052459.0 | 2686363.0  | 0.0      | 3738822.0  | 20887.0   | 794911.0   | 0.0     | 815798.0   | 59018.0   | 2532887.0  | 0.0     | 2591905.0  | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 46575.0  | 0.0       | 0.0    | 46575.0   | 0.0      | 0.0      | 0.0     | 0.0      | 126480.0   | 3327798.0  | 0.0     | 3454278.0  | 91145.0  | 12000.0  | 0.0      | 103145.0 | 0.0     | 463.0    | 0.0     | 463.0    | 1270084.0  | 6026624.0  | 0.0      | 7296708.0  | 1129948.0 | 79905.0    | 13655.0  | 1223508.0  | 944926.0  | 264927.0  | 0.0       | 13655.0  | 1223508.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 2538303.0  | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1100 W WASHINGTON             | PHOENIX     | AZ      | 85007   | 2935     | WWW.LIB.AZ.US                         | LSCA TITLE II; FIVE-STATE NATIVE AMERICAN GRANT    | 4        | 899251200 | 930700800 | 2474108.0  | 169850.0  | 2643958.0  | 6211109.0  | 351400.0   | 77000.0   | 6639509.0  | 219402.0  | 9502869.0  | 43034.0   | 3113741.0 | 58262.0  | 3215037.0 | 8384.0   | 705765.0  | 15737.0  | 729886.0  | 51418.0   | 3819506.0 | 73999.0  | 3944923.0 | 5078.0   | 469200.0  | 0.0      | 474278.0  | 1113785.0 | 1826876.0 | 285494.0 | 3226155.0 | 1170281.0 | 6115582.0  | 359493.0 | 7645356.0  | 922339.0  | 351400.0   | 0.0     | 1273739.0  | 0.0       | 0.0        | 0.0     | 0.0        | 174745.0 | 1000.0  | 0.0     | 175745.0 | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 77000.0   | 0.0     | 77000.0   | 172181.0 | 20000.0   | 0.0    | 192181.0  | 0.0      | 0.0      | 0.0     | 0.0      | 1269265.0  | 449400.0   | 0.0     | 1718665.0  | 215384.0 | 19297.0  | 89057.0  | 323738.0 | 0.0     | 0.0      | 0.0     | 0.0      | 2654930.0  | 6584279.0  | 448550.0 | 9687759.0  | 1193052.0 | 1097084.0  | 92216.0  | 2382352.0  | 1595697.0 | 694439.0  | 0.0       | 92216.0  | 2382352.0  | 1126462.0 | 401918.0 | 1528380.0 | 19297.0  | 1547677.0 | 4600275.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837               | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    |                                                    | 6        | 899251200 | 930700800 | 14263331.0 | 0.0       | 14263331.0 | 14059368.0 | 34590000.0 | 0.0       | 48649368.0 | 408318.0  | 63321017.0 | 1155653.0 | 6196195.0 | 162986.0 | 7514834.0 | 352285.0 | 1544899.0 | 47811.0  | 1944995.0 | 1507938.0 | 7741094.0 | 210797.0 | 9459829.0 | 6401.0   | 2093770.0 | 107107.0 | 2207278.0 | 1318054.0 | 4224504.0 | 90414.0  | 5632972.0 | 2832393.0 | 14059368.0 | 408318.0 | 17300079.0 | 3009405.0 | 31289687.0 | 0.0     | 34299092.0 | 989795.0  | 0.0        | 0.0     | 989795.0   | 177343.0 | 0.0     | 0.0     | 177343.0 | 0.0       | 3160000.0 | 0.0     | 3160000.0 | 6881448.0 | 0.0       | 0.0     | 6881448.0 | 0.0      | 0.0       | 0.0    | 0.0       | 372947.0 | 140313.0 | 0.0     | 513260.0 | 11430938.0 | 34590000.0 | 0.0     | 46020938.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 14263331.0 | 48649368.0 | 408318.0 | 63321017.0 | 2696630.0 | 11430938.0 | 135763.0 | 14263331.0 | 9531550.0 | 3191193.0 | 1404825.0 | 135763.0 | 14263331.0 | 1995506.0 | 701124.0 | 2696630.0 | 0.0      | 2696630.0 | 33252000.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX               | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/library_INDEX.HTM |                                                    | 8        | 899251200 | 930700800 | 1857139.0  | 0.0       | 1857139.0  | 1538126.0  | 4794114.0  | 0.0       | 6332240.0  | 29179.0   | 8218558.0  | 619383.0  | 893199.0  | 7556.0   | 1520138.0 | 135962.0 | 196068.0  | 1659.0   | 333689.0  | 755345.0  | 1089267.0 | 9215.0   | 1853827.0 | 11492.0  | 101899.0  | 0.0      | 113391.0  | 359761.0  | 163272.0  | 8964.0   | 531997.0  | 1126598.0 | 1354438.0  | 18179.0  | 2499215.0  | 17640.0   | 134114.0   | 0.0     | 151754.0   | 30003.0   | 0.0        | 0.0     | 30003.0    | 180350.0 | 0.0     | 0.0     | 180350.0 | 242900.0  | 2449893.0 | 0.0     | 2692793.0 | 270804.0  | 2048101.0 | 0.0     | 2318905.0 | 0.0      | 0.0       | 0.0    | 0.0       | 14750.0  | 162006.0 | 0.0     | 176756.0 | 756447.0   | 4794114.0  | 0.0     | 5550561.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 1883045.0  | 6148552.0  | 18179.0  | 8049776.0  | 1022661.0 | 756447.0   | 78031.0  | 1857139.0  | 996793.0  | 782315.0  | 0.0       | 78031.0  | 1857139.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 3941969.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE            | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | CT NEWSPAPER PROJECT; NEA; LSCA TITLE II           | 9        | 899251200 | 930700800 | 1600000.0  | 1147481.0 | 2747481.0  | 11894186.0 | 4250899.0  | 0.0       | 16145085.0 | 1456560.0 | 20349126.0 | 846787.0  | 5208543.0 | 10196.0  | 6065526.0 | 288016.0 | 0.0       | 3625.0   | 291641.0  | 1134803.0 | 5208543.0 | 13821.0  | 6357167.0 | 86618.0  | 864155.0  | 66840.0  | 1017613.0 | 463523.0  | 5671501.0 | 868078.0 | 7003102.0 | 1684944.0 | 11744199.0 | 948739.0 | 14377882.0 | 176680.0  | 1151611.0  | 0.0     | 1328291.0  | 0.0       | 0.0        | 0.0     | 0.0        | 7000.0   | 0.0     | 0.0     | 7000.0   | 14970.0   | 807829.0  | 0.0     | 822799.0  | 16306.0   | 1047313.0 | 0.0     | 1063619.0 | 304535.0 | 2291459.0 | 0.0    | 2595994.0 | 0.0      | 0.0      | 0.0     | 0.0      | 519491.0   | 5298212.0  | 0.0     | 5817703.0  | 60096.0  | 25000.0  | 0.0      | 85096.0  | 0.0     | 0.0      | 0.0     | 0.0      | 2264531.0  | 17067411.0 | 948739.0 | 20280681.0 | 1463177.0 | 214956.0   | 28230.0  | 1706363.0  | 326229.0  | 1074509.0 | 277395.0  | 28230.0  | 1706363.0  | 988959.0  | 77225.0  | 1066184.0 | 0.0      | 1066184.0 | 3269858.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.            | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     |                                                    | 11       | 907200000 | 938649600 | 671711.0   | 0.0       | 671711.0   | 656630.0   | 0.0        | 0.0       | 656630.0   | 0.0       | 1328341.0  | 210541.0  | 203555.0  | 0.0      | 414096.0  | 47076.0  | 45964.0   | 0.0      | 93040.0   | 257617.0  | 249519.0  | 0.0      | 507136.0  | 45022.0  | 45964.0   | 0.0      | 90986.0   | 369072.0  | 361147.0  | 0.0      | 730219.0  | 671711.0  | 656630.0   | 0.0      | 1328341.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0        | 0.0        | 0.0     | 0.0        | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0     | 0.0      | 671711.0   | 656630.0   | 0.0      | 1328341.0  | 669661.0  | 0.0        | 2050.0   | 671711.0   | 260329.0  | 363207.0  | 46125.0   | 2050.0   | 671711.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 521426.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY       | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         | LSCA TITLES I, II, AND III                         | 10       | 899251200 | 930700800 | 617240.0   | 205361.0  | 822601.0   | 778125.0   | 1621600.0  | 795707.0  | 3195432.0  | 0.0       | 4018033.0  | 344074.0  | 344259.0  | 0.0      | 688333.0  | 84839.0  | 104299.0  | 0.0      | 189138.0  | 428913.0  | 448558.0  | 0.0      | 877471.0  | 8661.0   | 11754.0   | 0.0      | 20415.0   | 310508.0  | 405465.0  | 0.0      | 715973.0  | 748082.0  | 865777.0   | 0.0      | 1613859.0  | 71112.0   | 1219710.0  | 0.0     | 1290822.0  | 0.0       | 2425.0     | 0.0     | 2425.0     | 8232.0   | 0.0     | 0.0     | 8232.0   | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 32204.0  | 501800.0  | 0.0    | 534004.0  | 0.0      | 0.0      | 0.0     | 0.0      | 111548.0   | 1723935.0  | 0.0     | 1835483.0  | 930.0    | 7000.0   | 0.0      | 7930.0   | 0.0     | 629707.0 | 0.0     | 629707.0 | 860560.0   | 3226419.0  | 0.0      | 4086979.0  | 747012.0  | 79344.0    | 2000.0   | 828356.0   | 823356.0  | 3000.0    | 0.0       | 2000.0   | 828356.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 666168.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET     | TALLAHASSEE | FL      | 32399   | 250      | dlis.dos.state.fl.us                  | LSCA TITLE II; NATIONAL RECORDS COMMISSION         | 12       | 899251200 | 930700800 | 6625107.0  | 431139.0  | 7056246.0  | 7882953.0  | 30700000.0 | 7283535.0 | 45866488.0 | 0.0       | 52922734.0 | 407856.0  | 2417623.0 | 0.0      | 2825479.0 | 220153.0 | 1301797.0 | 0.0      | 1521950.0 | 628009.0  | 3719420.0 | 0.0      | 4347429.0 | 185503.0 | 636241.0  | 0.0      | 821744.0  | 629601.0  | 3038227.0 | 0.0      | 3667828.0 | 1443113.0 | 7393888.0  | 0.0      | 8837001.0  | 0.0       | 0.0        | 0.0     | 0.0        | 2710792.0 | 30700000.0 | 0.0     | 33410792.0 | 0.0      | 0.0     | 0.0     | 0.0      | 1650000.0 | 1200000.0 | 0.0     | 2850000.0 | 709627.0  | 0.0       | 0.0     | 709627.0  | 406139.0 | 2638000.0 | 0.0    | 3044139.0 | 111575.0 | 20100.0  | 0.0     | 131675.0 | 5588133.0  | 34558100.0 | 0.0     | 40146233.0 | 0.0      | 10000.0  | 0.0      | 10000.0  | 0.0     | 0.0      | 0.0     | 0.0      | 7031246.0  | 41961988.0 | 0.0      | 48993234.0 | 1363621.0 | 5181994.0  | 79492.0  | 6625107.0  | 5533488.0 | 646215.0  | 365912.0  | 79492.0  | 6625107.0  | 931713.0  | 345922.0 | 1277635.0 | 10000.0  | 1287635.0 | 15000475.0 | 
```