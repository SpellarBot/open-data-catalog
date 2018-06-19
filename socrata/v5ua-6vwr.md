# State Libraries Survey, FY 2005, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2005-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/v5ua-6vwr) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/v5ua-6vwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/v5ua-6vwr/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | v5ua-6vwr |
| Name | State Libraries Survey, FY 2005, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2005, revenue, expenditures |
| Created | 2016-12-20T15:27:01Z |
| Publication Date | 2016-12-20T17:04:36Z |

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
| Yes      | series tag     | pub_fips   | FIPS state code                    | text      | text        |
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
series e:v5ua-6vwr d:2004-07-01T00:00:00.000Z t:mailaddr="P.O. BOX 110571" t:asf_sp=Y t:asf_ac=Y t:fiothsp=P t:asf_lc=N t:asf_sch=Y t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:mailcity=JUNEAU t:mailzip=99811 t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:mail_st=AK t:rstatus=1 t:physcity=JUNEAU t:webaddr=WWW.LIBRARY.STATE.AK.US t:physzip4=571 t:asf_pub=Y t:obereg=8 t:mailzip4=571 t:phys_st=AK t:physzip=99811 m:aidipld=916406 m:aidiplc=0 m:aidiplb=799930 m:aidipla=116476 m:oexpsald=1317069 m:oexpsala=23716 m:siaidlib=891400 m:oexpsalc=0 m:oexpsalb=1293353 m:totexpd=4204992 m:oexpbenb=670098 m:aidoild=136788 m:oexpbena=7024 m:siother=199200 m:capitald=0 m:oexpbend=677122 m:aidoilb=0 m:oexpbenc=0 m:aidoilc=0 m:capitala=0 m:aidoila=136788 m:aidplsd=0 m:capitalc=0 m:aidplsc=0 m:capitalb=0 m:aidplsb=0 m:aidplsa=0 m:totexpu=769497 m:totexpt=769497 m:aidsalb=91470 m:aidsalc=0 m:aidsald=576963 m:swexpt=0 m:techxu=238946 m:oexpcold=0 m:othexpd=0 m:othexpc=0 m:oexpcolb=0 m:othexpb=0 m:oexpcolc=0 m:othexpa=0 m:sistlaop=2340900 m:admexpt=30740 m:totaidb=891400 m:admexpu=30740 m:totaida=738757 m:popu_st=663661 m:oexpcola=0 m:othincm=15000 m:totoxstc=0 m:aidothc=0 m:totoxstd=1994191 m:aidothd=0 m:lstainc=769497 m:aidotha=0 m:aidothb=0 m:totopexc=4000 m:total_fi=769497 m:totopexd=2574835 m:totopexa=30740 m:totopexb=2540095 m:totaidd=1630157 m:totaidc=0 m:fioth=0 m:grexpt=738757 m:aidsala=485493 m:serllxu=166632 m:total_si=3431500 m:serdifxu=333179 m:aidlcc=0 m:aidlcd=0 m:totexpc=4000 m:aidmlsd=0 m:totexpb=3431495 m:aidlca=0 m:totexpa=769497 m:aidlcb=0 m:oexpothd=580644 m:aidmlsa=0 m:oexpothc=4000 m:oexpothb=576644 m:aidmlsc=0 m:oexpotha=0 m:aidmlsb=0 m:totincm=4215997 m:totoxsta=30740 m:totoxstb=1963451

series e:v5ua-6vwr d:2004-10-01T00:00:00.000Z t:mailaddr="6030 MONTICELLO DRIVE" t:asf_sp=N t:asf_ac=N t:fiothsp=P t:asf_lc=N t:asf_sch=N t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:mailcity=MONTGOMERY t:mailzip=36130 t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:mail_st=AL t:rstatus=1 t:physcity=MONTGOMERY t:webaddr=WWW.APLS.STATE.AL.US t:physzip4=1 t:asf_pub=Y t:obereg=5 t:mailzip4=1 t:phys_st=AL t:physzip=36117 m:aidipld=5240981 m:aidiplc=51600 m:aidiplb=4141608 m:aidipla=1047773 m:oexpsald=1748012 m:oexpsala=11724 m:siaidlib=4141608 m:oexpsalc=0 m:oexpsalb=1736288 m:totexpd=12543071 m:oexpbenb=573502 m:aidoild=41024 m:oexpbena=3464 m:siother=3532600 m:capitald=0 m:oexpbend=576966 m:aidoilb=0 m:oexpbenc=0 m:aidoilc=0 m:capitala=0 m:aidoila=41024 m:aidplsd=123961 m:capitalc=0 m:aidplsc=0 m:capitalb=0 m:aidplsb=0 m:aidplsa=123961 m:totexpu=2507472 m:totexpt=2507472 m:aidsalb=3532600 m:aidsalc=0 m:aidsald=3532600 m:swexpt=1202607 m:techxu=488547 m:oexpcold=530277 m:othexpd=0 m:othexpc=0 m:oexpcolb=0 m:othexpb=0 m:oexpcolc=0 m:othexpa=0 m:sistlaop=2311239 m:admexpt=92107 m:totaidb=7674208 m:admexpu=92107 m:totaida=1212758 m:popu_st=4557808 m:oexpcola=530277 m:othincm=51600 m:totoxstc=0 m:aidothc=0 m:totoxstd=2324978 m:aidothd=0 m:lstainc=2507472 m:aidotha=0 m:aidothb=0 m:totopexc=0 m:total_fi=2507472 m:totopexd=3604505 m:totopexa=1294715 m:totopexb=2309790 m:totaidd=8938566 m:totaidc=51600 m:fioth=0 m:grexpt=1212758 m:aidsala=0 m:serllxu=0 m:total_si=9985447 m:serdifxu=1926818 m:aidlcc=0 m:aidlcd=0 m:totexpc=51600 m:aidmlsd=0 m:totexpb=9983998 m:aidlca=0 m:totexpa=2507473 m:aidlcb=0 m:oexpothd=749250 m:aidmlsa=0 m:oexpothc=0 m:oexpothb=0 m:aidmlsc=0 m:oexpotha=749250 m:aidmlsb=0 m:totincm=12544519 m:totoxsta=15188 m:totoxstb=2309790

series e:v5ua-6vwr d:2004-07-01T00:00:00.000Z t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:asf_sp=N t:asf_ac=N t:fiothsp=P t:asf_lc=Y t:asf_sch=N t:pub_fips=5 t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:mailcity="LITTLE ROCK" t:mailzip=72201 t:stlaname="ARKANSAS STATE LIBRARY" t:mail_st=AR t:rstatus=1 t:physcity="LITTLE ROCK" t:webaddr=WWW.ASL.LIB.AR.US t:physzip4=1085 t:asf_pub=Y t:obereg=5 t:mailzip4=1085 t:phys_st=AR t:physzip=72201 m:aidipld=1456804 m:aidiplc=501000 m:aidiplb=955804 m:aidipla=0 m:oexpsald=1797472 m:oexpsala=294586 m:siaidlib=2000000 m:oexpsalc=0 m:oexpsalb=1502886 m:totexpd=6967558 m:oexpbenb=390879 m:aidoild=0 m:oexpbena=102503 m:siother=95540 m:capitald=59347 m:oexpbend=493382 m:aidoilb=0 m:oexpbenc=0 m:aidoilc=0 m:capitala=59347 m:aidoila=0 m:aidplsd=1139736 m:capitalc=0 m:aidplsc=0 m:capitalb=0 m:aidplsb=1139736 m:aidplsa=0 m:totexpu=1556894 m:totexpt=1556894 m:aidsalb=0 m:aidsalc=0 m:aidsald=0 m:swexpt=1543599 m:techxu=630518 m:oexpcold=319147 m:othexpd=19898 m:othexpc=0 m:oexpcolb=122724 m:othexpb=0 m:oexpcolc=0 m:othexpa=19898 m:sistlaop=2942789 m:admexpt=13295 m:totaidb=2095540 m:admexpu=13295 m:totaida=0 m:popu_st=2779154 m:oexpcola=196423 m:othincm=555440 m:totoxstc=0 m:aidothc=0 m:totoxstd=2290854 m:aidothd=0 m:lstainc=1072788 m:aidotha=0 m:aidothb=0 m:totopexc=0 m:total_fi=1072788 m:totopexd=4291773 m:totopexa=1477649 m:totopexb=2814124 m:totaidd=2596540 m:totaidc=501000 m:fioth=0 m:grexpt=0 m:aidsala=0 m:serllxu=759407 m:total_si=5038329 m:serdifxu=153674 m:aidlcc=0 m:aidlcd=0 m:totexpc=501000 m:aidmlsd=0 m:totexpb=4909664 m:aidlca=0 m:totexpa=1556894 m:aidlcb=0 m:oexpothd=1681772 m:aidmlsa=0 m:oexpothc=0 m:oexpothb=797635 m:aidmlsc=0 m:oexpotha=884137 m:aidmlsb=0 m:totincm=6666557 m:totoxsta=397089 m:totoxstb=1893765
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

metric m:techxu p:double l:"LSTA exp technology" t:dataTypeName=money

metric m:serdifxu p:double l:"LSTA exp svcs to disab" t:dataTypeName=money

metric m:serllxu p:double l:"LSTA exp lifelong learning" t:dataTypeName=money

metric m:admexpu p:double l:"LSTA exp by use/LSTA admin" t:dataTypeName=money

metric m:totexpu p:double l:"LSTA exp by use/TOTAL" t:dataTypeName=money

metric m:popu_st p:double l:Population t:dataTypeName=number

entity e:v5ua-6vwr l:"State Libraries Survey, FY 2005, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/v5ua-6vwr

property e:v5ua-6vwr t:meta.view d:2017-09-25T07:27:47.512Z v:averageRating=0 v:name="State Libraries Survey, FY 2005, Part 3: Revenue & Expenditures" v:attribution=IMLS v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:id=v5ua-6vwr v:category="State Library Administrative Agencies Survey"

property e:v5ua-6vwr t:meta.view.license d:2017-09-25T07:27:47.512Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:v5ua-6vwr t:meta.view.owner d:2017-09-25T07:27:47.512Z v:displayName="Jason Enos" v:lastNotificationSeenAt=1504290350 v:id=xhhh-dddv v:screenName="Jason Enos"

property e:v5ua-6vwr t:meta.view.tableauthor d:2017-09-25T07:27:47.512Z v:displayName="Jason Enos" v:lastNotificationSeenAt=1504290350 v:roleName=administrator v:id=xhhh-dddv v:screenName="Jason Enos"

property e:v5ua-6vwr t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:27:47.512Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Program_Code=000:000 v:Bureau_Code=474:00
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                               | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola  | oexpcolb | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa  | aidplsb   | aidplsc | aidplsd   | aidoila  | aidoilb | aidoilc | aidoild  | aidmlsa   | aidmlsb   | aidmlsc  | aidmlsd   | aidsala   | aidsalb   | aidsalc  | aidsald   | aidlca | aidlcb     | aidlcc | aidlcd     | aidotha | aidothb | aidothc  | aidothd  | totaida    | totaidb    | totaidc   | totaidd    | capitala | capitalb | capitalc | capitald | othexpa   | othexpb  | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | ===================================== | ======= | ====== | ======= | ====== | ====== | ===================================================================================================== | ======== | ====== | ======= | ========== | ========== | ========== | ======== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ========= | ========== | ======== | ========== | ======== | ========= | ======= | ========= | ======== | ======= | ======= | ======== | ========= | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ====== | ========== | ====== | ========== | ======= | ======= | ======== | ======== | ========== | ========== | ========= | ========== | ======== | ======== | ======== | ======== | ========= | ======== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US               | Y       | Y      | Y       | Y      | N      | P                                                                                                     | 2        | 8      | 1       | 1088640000 | 1120089600 | 769497.0   | 0.0      | 769497.0   | 2340900.0  | 891400.0   | 199200.0  | 3431500.0  | 15000.0   | 4215997.0  | 23716.0   | 1293353.0 | 0.0      | 1317069.0 | 7024.0   | 670098.0  | 0.0      | 677122.0  | 30740.0   | 1963451.0 | 0.0      | 1994191.0  | 0.0       | 0.0      | 0.0      | 0.0       | 0.0       | 576644.0  | 4000.0   | 580644.0  | 30740.0   | 2540095.0  | 4000.0   | 2574835.0  | 116476.0  | 799930.0   | 0.0      | 916406.0   | 0.0      | 0.0       | 0.0     | 0.0       | 136788.0 | 0.0     | 0.0     | 136788.0 | 0.0       | 0.0       | 0.0      | 0.0       | 485493.0  | 91470.0   | 0.0      | 576963.0  | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0      | 0.0      | 738757.0   | 891400.0   | 0.0       | 1630157.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 769497.0   | 3431495.0  | 4000.0    | 4204992.0  | 0.0       | 738757.0   | 30740.0  | 769497.0   | 238946.0  | 333179.0  | 166632.0  | 30740.0  | 769497.0   | 663661.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | Y       | N      | N       | N      | N      | P                                                                                                     | 1        | 5      | 1       | 1096588800 | 1128038400 | 2507472.0  | 0.0      | 2507472.0  | 2311239.0  | 4141608.0  | 3532600.0 | 9985447.0  | 51600.0   | 12544519.0 | 11724.0   | 1736288.0 | 0.0      | 1748012.0 | 3464.0   | 573502.0  | 0.0      | 576966.0  | 15188.0   | 2309790.0 | 0.0      | 2324978.0  | 530277.0  | 0.0      | 0.0      | 530277.0  | 749250.0  | 0.0       | 0.0      | 749250.0  | 1294715.0 | 2309790.0  | 0.0      | 3604505.0  | 1047773.0 | 4141608.0  | 51600.0  | 5240981.0  | 123961.0 | 0.0       | 0.0     | 123961.0  | 41024.0  | 0.0     | 0.0     | 41024.0  | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 3532600.0 | 0.0      | 3532600.0 | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0      | 0.0      | 1212758.0  | 7674208.0  | 51600.0   | 8938566.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2507473.0  | 9983998.0  | 51600.0   | 12543071.0 | 1202607.0 | 1212758.0  | 92107.0  | 2507472.0  | 488547.0  | 1926818.0 | 0.0       | 92107.0  | 2507472.0  | 4557808.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     | Y       | N      | N       | N      | Y      | P                                                                                                     | 5        | 5      | 1       | 1088640000 | 1120089600 | 1072788.0  | 0.0      | 1072788.0  | 2942789.0  | 2000000.0  | 95540.0   | 5038329.0  | 555440.0  | 6666557.0  | 294586.0  | 1502886.0 | 0.0      | 1797472.0 | 102503.0 | 390879.0  | 0.0      | 493382.0  | 397089.0  | 1893765.0 | 0.0      | 2290854.0  | 196423.0  | 122724.0 | 0.0      | 319147.0  | 884137.0  | 797635.0  | 0.0      | 1681772.0 | 1477649.0 | 2814124.0  | 0.0      | 4291773.0  | 0.0       | 955804.0   | 501000.0 | 1456804.0  | 0.0      | 1139736.0 | 0.0     | 1139736.0 | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0      | 0.0      | 0.0        | 2095540.0  | 501000.0  | 2596540.0  | 59347.0  | 0.0      | 0.0      | 59347.0  | 19898.0   | 0.0      | 0.0       | 19898.0   | 1556894.0  | 4909664.0  | 501000.0  | 6967558.0  | 1543599.0 | 0.0        | 13295.0  | 1556894.0  | 630518.0  | 153674.0  | 759407.0  | 13295.0  | 1556894.0  | 2779154.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                         | Y       | N      | N       | N      | N      | IMLS NATIONAL LEADERSHIP GRANT, NHPRC (NATIONAL HISTORICAL PUBLICATIONS AND RECORDS COMMISSION) GRANT | 4        | 6      | 1       | 1088640000 | 1120089600 | 2695257.0  | 173035.0 | 2868292.0  | 5975700.0  | 651400.0   | 97000.0   | 6724100.0  | 988373.0  | 10580765.0 | 164190.0  | 3688425.0 | 262888.0 | 4115503.0 | 35128.0  | 1045068.0 | 77770.0  | 1157966.0 | 199318.0  | 4733493.0 | 340658.0 | 5273469.0  | 1450.0    | 199389.0 | 21520.0  | 222359.0  | 0.0       | 822174.0  | 0.0      | 822174.0  | 200768.0  | 5755056.0  | 362178.0 | 6318002.0  | 409985.0  | 536000.0   | 0.0      | 945985.0   | 214776.0 | 0.0       | 0.0     | 214776.0  | 96329.0  | 0.0     | 0.0     | 96329.0  | 228614.0  | 0.0       | 0.0      | 228614.0  | 0.0       | 0.0       | 0.0      | 0.0       | 0.0    | 22476.0    | 0.0    | 22476.0    | 0.0     | 0.0     | 0.0      | 0.0      | 949704.0   | 558476.0   | 0.0       | 1508180.0  | 0.0      | 0.0      | 60785.0  | 60785.0  | 1717820.0 | 0.0      | 0.0       | 1717820.0 | 2868292.0  | 6313532.0  | 422963.0  | 9604787.0  | 1645902.0 | 949704.0   | 99651.0  | 2695257.0  | 1330585.0 | 92240.0   | 1172781.0 | 99651.0  | 2695257.0  | 5939292.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    | Y       | N      | N       | N      | Y      | P                                                                                                     | 6        | 8      | 2       | 1088640000 | 1120089600 | 16457012.0 | 0.0      | 16457012.0 | 12701957.0 | 34842428.0 | 0.0       | 47544385.0 | 436376.0  | 64437773.0 | 1736019.0 | 5789562.0 | 272930.0 | 7798511.0 | 596810.0 | 2011352.0 | 128277.0 | 2736439.0 | 2332829.0 | 7800914.0 | 401207.0 | 10534950.0 | 598030.0  | 690792.0 | 0.0      | 1288822.0 | 3405161.0 | 4210251.0 | 35169.0  | 7650581.0 | 6336020.0 | 12701957.0 | 436376.0 | 19474353.0 | 4524966.0 | 31799289.0 | 0.0      | 36324255.0 | 0.0      | 0.0       | 0.0     | 0.0       | 827738.0 | 0.0     | 0.0     | 827738.0 | 4009350.0 | 3043139.0 | 0.0      | 7052489.0 | 1414813.0 | 0.0       | 0.0      | 1414813.0 | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0      | 0.0      | 10776867.0 | 34842428.0 | 0.0       | 45619295.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 17112887.0 | 47544385.0 | 436376.0  | 65093648.0 | 5478015.0 | 10776867.0 | 202130.0 | 16457012.0 | 8565606.0 | 12672.0   | 7676604.0 | 202130.0 | 16457012.0 | 36132147.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM | N       | N      | N       | N      | Y      | P                                                                                                     | 8        | 7      | 1       | 1088640000 | 1120089600 | 2516533.0  | 0.0      | 2516533.0  | 924679.0   | 959796.0   | 93800.0   | 1978275.0  | 321420.0  | 4816228.0  | 1009415.0 | 653412.0  | 163500.0 | 1826327.0 | 169408.0 | 106176.0  | 28896.0  | 304480.0  | 1178823.0 | 759588.0  | 192396.0 | 2130807.0  | 48000.0   | 0.0      | 0.0      | 48000.0   | 426845.0  | 165091.0  | 129024.0 | 720960.0  | 1653668.0 | 924679.0   | 321420.0 | 2899767.0  | 72088.0   | 0.0        | 0.0      | 72088.0    | 0.0      | 0.0       | 0.0     | 0.0       | 50000.0  | 0.0     | 0.0     | 50000.0  | 404976.0  | 600000.0  | 0.0      | 1004976.0 | 262042.0  | 359796.0  | 0.0      | 621838.0  | 0.0    | 0.0        | 0.0    | 0.0        | 56259.0 | 0.0     | 0.0      | 56259.0  | 845365.0   | 959796.0   | 0.0       | 1805161.0  | 17500.0  | 0.0      | 0.0      | 17500.0  | 0.0       | 93800.0  | 0.0       | 93800.0   | 2516533.0  | 1978275.0  | 321420.0  | 4816228.0  | 1570507.0 | 845365.0   | 100661.0 | 2516533.0  | 916098.0  | 686234.0  | 813540.0  | 100661.0 | 2516533.0  | 4665177.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | Y       | N      | N       | N      | N      | P                                                                                                     | 9        | 1      | 1       | 1088640000 | 1120089600 | 2854291.0  | 0.0      | 2854291.0  | 8865284.0  | 4823137.0  | 0.0       | 13688421.0 | 2252994.0 | 18795706.0 | 897604.0  | 5183678.0 | 310540.0 | 6391822.0 | 489977.0 | 0.0       | 150426.0 | 640403.0  | 1387581.0 | 5183678.0 | 460966.0 | 7032225.0  | 148744.0  | 786506.0 | 34421.0  | 969671.0  | 478820.0  | 3429885.0 | 404068.0 | 4312773.0 | 2015145.0 | 9400069.0  | 899455.0 | 12314669.0 | 279842.0  | 1023137.0  | 0.0      | 1302979.0  | 0.0      | 0.0       | 0.0     | 0.0       | 45042.0  | 0.0     | 0.0     | 45042.0  | 0.0       | 0.0       | 0.0      | 0.0       | 16169.0   | 300000.0  | 0.0      | 316169.0  | 0.0    | 1397307.0  | 0.0    | 1397307.0  | 0.0     | 0.0     | 0.0      | 0.0      | 341053.0   | 2720444.0  | 0.0       | 3061497.0  | 0.0      | 86507.0  | 0.0      | 86507.0  | 0.0       | 0.0      | 1273365.0 | 1273365.0 | 2356198.0  | 12207020.0 | 2172820.0 | 16736038.0 | 1878134.0 | 341053.0   | 31134.0  | 2250321.0  | 365213.0  | 1757371.0 | 96603.0   | 31134.0  | 2250321.0  | 3510297.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     | Y       | N      | N       | N      | N      | NHPRC, NARA                                                                                           | 11       | 2      | 1       | 1096588800 | 1128038400 | 732955.0   | 75000.0  | 807955.0   | 30793361.0 | 0.0        | 0.0       | 30793361.0 | 1245486.0 | 32846802.0 | 425045.0  | 123264.0  | 0.0      | 548309.0  | 86715.0  | 21836.0   | 0.0      | 108551.0  | 511760.0  | 145100.0  | 0.0      | 656860.0   | 0.0       | 0.0      | 0.0      | 0.0       | 221195.0  | 52989.0   | 0.0      | 274184.0  | 732955.0  | 198089.0   | 0.0      | 931044.0   | 75000.0   | 28743535.0 | 622543.0 | 29441078.0 | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0      | 0.0      | 75000.0    | 28743535.0 | 622543.0  | 29441078.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 807955.0   | 28941624.0 | 622543.0  | 30372122.0 | 703637.0  | 0.0        | 29318.0  | 732955.0   | 0.0       | 94440.0   | 609197.0  | 29318.0  | 732955.0   | 550521.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                   | Y       | N      | N       | N      | Y      | P                                                                                                     | 10       | 2      | 1       | 1088640000 | 1120089600 | 774663.0   | 0.0      | 774663.0   | 1704910.0  | 3369500.0  | 5543906.0 | 10618316.0 | 50000.0   | 11442979.0 | 277527.0  | 364415.0  | 0.0      | 641942.0  | 120296.0 | 137021.0  | 0.0      | 257317.0  | 397823.0  | 501436.0  | 0.0      | 899259.0   | 2877.0    | 4166.0   | 0.0      | 7043.0    | 155251.0  | 866539.0  | 0.0      | 1021790.0 | 555951.0  | 1372141.0  | 0.0      | 1928092.0  | 68389.0   | 3037627.0  | 0.0      | 3106016.0  | 0.0      | 0.0       | 0.0     | 0.0       | 31532.0  | 0.0     | 0.0     | 31532.0  | 0.0       | 62423.0   | 0.0      | 62423.0   | 22000.0   | 0.0       | 50000.0  | 72000.0   | 0.0    | 1122220.0  | 0.0    | 1122220.0  | 0.0     | 0.0     | 0.0      | 0.0      | 121921.0   | 4222270.0  | 50000.0   | 4394191.0  | 0.0      | 5322.0   | 0.0      | 5322.0   | 0.0       | 802186.0 | 0.0       | 802186.0  | 677872.0   | 6401919.0  | 50000.0   | 7129791.0  | 552243.0  | 121921.0   | 3708.0   | 677872.0   | 3217.0    | 97875.0   | 573072.0  | 3708.0   | 677872.0   | 843524.0   | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | Y       | N      | N       | N      | Y      | P                                                                                                     | 12       | 5      | 1       | 1088640000 | 1120089600 | 8037303.0  | 0.0      | 8037303.0  | 5943304.0  | 45321808.0 | 0.0       | 51265112.0 | 1068000.0 | 60370415.0 | 963516.0  | 2823560.0 | 0.0      | 3787076.0 | 295441.0 | 923593.0  | 0.0      | 1219034.0 | 1258957.0 | 3747153.0 | 0.0      | 5006110.0  | 1572626.0 | 464915.0 | 0.0      | 2037541.0 | 2310526.0 | 1714367.0 | 0.0      | 4024893.0 | 5142109.0 | 5926435.0  | 0.0      | 11068544.0 | 967663.0  | 24066448.0 | 199200.0 | 25233311.0 | 440700.0 | 7882785.0 | 51600.0 | 8375085.0 | 0.0      | 0.0     | 0.0     | 0.0      | 1864903.0 | 1500000.0 | 120000.0 | 3484903.0 | 400119.0  | 0.0       | 163200.0 | 563319.0  | 0.0    | 11872575.0 | 0.0    | 11872575.0 | 0.0     | 0.0     | 534000.0 | 534000.0 | 3673385.0  | 45321808.0 | 1068000.0 | 50063193.0 | 7486.0   | 37189.0  | 0.0      | 44675.0  | 0.0       | 0.0      | 0.0       | 0.0       | 8822980.0  | 51285432.0 | 1068000.0 | 61176412.0 | 4216053.0 | 3673385.0  | 147865.0 | 8037303.0  | 4804988.0 | 3084450.0 | 0.0       | 147865.0 | 8037303.0  | 17789864.0 | 
```