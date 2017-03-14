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
| Rows Updated | 2016-12-20T17:21:33Z |

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
series e:v5ua-6vwr d:2004-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=N t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=199200 m:totaida=738757 m:aidsala=485493 m:capitald=0 m:admexpt=30740 m:swexpt=0 m:admexpu=30740 m:oexpbenb=670098 m:oexpbena=7024 m:oexpbend=677122 m:oexpbenc=0 m:totincm=4215997 m:othincm=15000 m:aidlcd=0 m:aidlcc=0 m:totexpu=769497 m:totexpt=769497 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=4204992 m:totexpa=769497 m:totexpc=4000 m:totexpb=3431495 m:sistlaop=2340900 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=663661 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=1994191 m:aidmlsd=0 m:serllxu=166632 m:totopexc=4000 m:totopexd=2574835 m:totopexa=30740 m:aidothd=0 m:totopexb=2540095 m:aidothc=0 m:oexpothc=4000 m:aidothb=0 m:total_fi=769497 m:oexpothd=580644 m:aidotha=0 m:oexpotha=0 m:oexpothb=576644 m:aidplsc=0 m:aidplsd=0 m:total_si=3431500 m:totoxstb=1963451 m:totoxsta=30740 m:oexpcold=0 m:lstainc=769497 m:aidplsa=0 m:oexpcolb=0 m:grexpt=738757 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=333179 m:oexpsalb=1293353 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=916406 m:siaidlib=891400 m:othexpb=0 m:aidipla=116476 m:oexpsala=23716 m:aidoila=136788 m:othexpc=0 m:aidiplb=799930 m:aidoilb=0 m:aidsald=576963 m:totaidd=1630157 m:aidoilc=0 m:totaidc=0 m:techxu=238946 m:oexpsald=1317069 m:aidoild=136788 m:aidsalb=91470 m:aidsalc=0 m:othexpa=0

series e:v5ua-6vwr d:2004-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=N t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=WWW.APLS.STATE.AL.US t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=7674208 m:siother=3532600 m:totaida=1212758 m:aidsala=0 m:capitald=0 m:admexpt=92107 m:swexpt=1202607 m:admexpu=92107 m:oexpbenb=573502 m:oexpbena=3464 m:oexpbend=576966 m:oexpbenc=0 m:totincm=12544519 m:othincm=51600 m:aidlcd=0 m:aidlcc=0 m:totexpu=2507472 m:totexpt=2507472 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=12543071 m:totexpa=2507473 m:totexpc=51600 m:totexpb=9983998 m:sistlaop=2311239 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=4557808 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2324978 m:aidmlsd=0 m:serllxu=0 m:totopexc=0 m:totopexd=3604505 m:totopexa=1294715 m:aidothd=0 m:totopexb=2309790 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=2507472 m:oexpothd=749250 m:aidotha=0 m:oexpotha=749250 m:oexpothb=0 m:aidplsc=0 m:aidplsd=123961 m:total_si=9985447 m:totoxstb=2309790 m:totoxsta=15188 m:oexpcold=530277 m:lstainc=2507472 m:aidplsa=123961 m:oexpcolb=0 m:grexpt=1212758 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=1926818 m:oexpsalb=1736288 m:othexpd=0 m:aidiplc=51600 m:oexpcola=530277 m:oexpsalc=0 m:aidipld=5240981 m:siaidlib=4141608 m:othexpb=0 m:aidipla=1047773 m:oexpsala=11724 m:aidoila=41024 m:othexpc=0 m:aidiplb=4141608 m:aidoilb=0 m:aidsald=3532600 m:totaidd=8938566 m:aidoilc=0 m:totaidc=51600 m:techxu=488547 m:oexpsald=1748012 m:aidoild=41024 m:aidsalb=3532600 m:aidsalc=0 m:othexpa=0

series e:v5ua-6vwr d:2004-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=Y t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1085 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=59347 m:totaidb=2095540 m:siother=95540 m:totaida=0 m:aidsala=0 m:capitald=59347 m:admexpt=13295 m:swexpt=1543599 m:admexpu=13295 m:oexpbenb=390879 m:oexpbena=102503 m:oexpbend=493382 m:oexpbenc=0 m:totincm=6666557 m:othincm=555440 m:aidlcd=0 m:aidlcc=0 m:totexpu=1556894 m:totexpt=1556894 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=6967558 m:totexpa=1556894 m:totexpc=501000 m:totexpb=4909664 m:sistlaop=2942789 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2779154 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2290854 m:aidmlsd=0 m:serllxu=759407 m:totopexc=0 m:totopexd=4291773 m:totopexa=1477649 m:aidothd=0 m:totopexb=2814124 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=1072788 m:oexpothd=1681772 m:aidotha=0 m:oexpotha=884137 m:oexpothb=797635 m:aidplsc=0 m:aidplsd=1139736 m:total_si=5038329 m:totoxstb=1893765 m:totoxsta=397089 m:oexpcold=319147 m:lstainc=1072788 m:aidplsa=0 m:oexpcolb=122724 m:grexpt=0 m:aidplsb=1139736 m:oexpcolc=0 m:serdifxu=153674 m:oexpsalb=1502886 m:othexpd=19898 m:aidiplc=501000 m:oexpcola=196423 m:oexpsalc=0 m:aidipld=1456804 m:siaidlib=2000000 m:othexpb=0 m:aidipla=0 m:oexpsala=294586 m:aidoila=0 m:othexpc=0 m:aidiplb=955804 m:aidoilb=0 m:aidsald=0 m:totaidd=2596540 m:aidoilc=0 m:totaidc=501000 m:techxu=630518 m:oexpsald=1797472 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=19898
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

property e:v5ua-6vwr t:meta.view v:id=v5ua-6vwr v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2005, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:v5ua-6vwr t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:v5ua-6vwr t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:v5ua-6vwr t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:v5ua-6vwr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```