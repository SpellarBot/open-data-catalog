# State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2010-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/mjb9-rsyd) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/mjb9-rsyd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/mjb9-rsyd/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | mjb9-rsyd |
| Name | State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2010, revenue, expenditures |
| Created | 2016-12-20T15:32:24Z |
| Publication Date | 2016-12-20T17:04:41Z |

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
series e:mjb9-rsyd d:2009-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:obereg=2 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=N t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=N t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fipsst=2 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=101570615 m:siother=0 m:totaida=3779717 m:aidsala=0 m:capitald=0 m:admexpt=369346 m:swexpt=5315887 m:admexpu=369346 m:oexpbenb=0 m:oexpbena=1398640 m:oexpbend=1398640 m:oexpbenc=0 m:totincm=122217928 m:othincm=66016 m:aidlcd=14000000 m:aidlcc=0 m:totexpu=9464950 m:totexpt=9464950 m:fioth=0 m:aidlca=0 m:aidlcb=14000000 m:totexpd=120411470 m:totexpa=9482726 m:totexpc=80044 m:totexpb=110848700 m:sistlaop=9484211 m:aidmlsa=73999 m:aidmlsc=0 m:popu_st=19378102 m:aidmlsb=6102313 m:totoxstc=0 m:totoxstd=10443225 m:aidmlsd=6176312 m:serllxu=2115690 m:totopexc=80044 m:totopexd=15061138 m:totopexa=5703009 m:aidothd=10881941 m:totopexb=9278085 m:aidothc=0 m:oexpothc=80044 m:aidothb=7709455 m:total_fi=11491848 m:oexpothd=1201681 m:aidotha=3172486 m:oexpotha=974469 m:oexpothb=147168 m:aidplsc=0 m:aidplsd=27011704 m:total_si=110660064 m:totoxstb=5714685 m:totoxsta=4728540 m:oexpcold=3416232 m:lstainc=11491848 m:aidplsa=362130 m:oexpcolb=3416232 m:grexpt=3779717 m:aidplsb=26649574 m:oexpcolc=0 m:serdifxu=73774 m:oexpsalb=5714685 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=42409901 m:siaidlib=101175853 m:othexpb=0 m:aidipla=171102 m:oexpsala=3329900 m:aidoila=0 m:othexpc=0 m:aidiplb=42238799 m:aidoilb=4870474 m:aidsald=0 m:totaidd=105350332 m:aidoilc=0 m:totaidc=0 m:techxu=6906140 m:oexpsald=9044585 m:aidoild=4870474 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:mjb9-rsyd d:2009-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:obereg=3 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=N t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:asf_sp=N t:rstatus=2 t:physzip=36117 t:fipsst=1 t:fiothsp="IMLS - CONNECTING TO COLLECTIONS -C2C" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=1937663 m:siother=9000 m:totaida=3872381 m:aidsala=2846562 m:capitald=0 m:admexpt=58260 m:swexpt=1497028 m:admexpu=58260 m:oexpbenb=865737 m:oexpbena=140327 m:oexpbend=1180832 m:oexpbenc=174768 m:totincm=22263846 m:othincm=5826807 m:aidlcd=0 m:aidlcc=0 m:totexpu=5427669 m:totexpt=5427669 m:fioth=24200 m:aidlca=0 m:aidlcb=0 m:totexpd=20994486 m:totexpa=5451174 m:totexpc=4722369 m:totexpb=10820943 m:sistlaop=9227079 m:aidmlsa=254030 m:aidmlsc=0 m:popu_st=11536504 m:aidmlsb=582469 m:totoxstc=699070 m:totoxstd=4723327 m:aidmlsd=836499 m:serllxu=230885 m:totopexc=3706419 m:totopexd=14168492 m:totopexa=1578793 m:aidothd=571991 m:totopexb=8883280 m:aidothc=0 m:oexpothc=2507349 m:aidothb=0 m:total_fi=5263297 m:oexpothd=7296753 m:aidotha=571991 m:oexpotha=781694 m:oexpothb=4007710 m:aidplsc=0 m:aidplsd=0 m:total_si=11173742 m:totoxstb=3462946 m:totoxsta=561311 m:oexpcold=2148412 m:lstainc=5239097 m:aidplsa=0 m:oexpcolb=1412624 m:grexpt=3872381 m:aidplsb=0 m:oexpcolc=500000 m:serdifxu=386409 m:oexpsalb=2597209 m:othexpd=0 m:aidiplc=1015950 m:oexpcola=235788 m:oexpsalc=524302 m:aidipld=1269721 m:siaidlib=1937663 m:othexpb=0 m:aidipla=172771 m:oexpsala=420984 m:aidoila=27027 m:othexpc=0 m:aidiplb=81000 m:aidoilb=0 m:aidsald=4120756 m:totaidd=6825994 m:aidoilc=0 m:totaidc=1015950 m:techxu=4752115 m:oexpsald=3542495 m:aidoild=27027 m:aidsalb=1274194 m:aidsalc=0 m:othexpa=0

series e:mjb9-rsyd d:2009-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:obereg=6 t:asf_ac=N t:physaddr="900 WEST CAPITOL, SUITE 100" t:phys_st=AR t:mailzip=72201 t:mailzip4=3108 t:asf_pub=Y t:mailaddr="900 WEST CAPITOL, SUITE 100" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=3108 t:asf_sch=N t:webaddr=WWW.library.arkansas.gov t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fipsst=5 t:fiothsp="NATIONAL LEADERSHIP GRANT/IMLSNATIONAL HISTORICAL & RECORDS COMMISSIONTANF - TEMPORARY ASSISTANCE TO NEEDY FAMILIES" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=2259454 m:siother=0 m:totaida=1010629 m:aidsala=52701 m:capitald=0 m:admexpt=16793 m:swexpt=1763641 m:admexpu=16793 m:oexpbenb=994649 m:oexpbena=122120 m:oexpbend=1132087 m:oexpbenc=15318 m:totincm=9730343 m:othincm=336653 m:aidlcd=0 m:aidlcc=0 m:totexpu=2033214 m:totexpt=2033214 m:fioth=861572 m:aidlca=0 m:aidlcb=0 m:totexpd=9738477 m:totexpa=3026773 m:totexpc=320235 m:totexpb=6391469 m:sistlaop=4261818 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=3751351 m:aidmlsb=0 m:totoxstc=59097 m:totoxstd=3467489 m:aidmlsd=0 m:serllxu=264852 m:totopexc=320235 m:totopexd=6468394 m:totopexa=2016144 m:aidothd=705148 m:totopexb=4132015 m:aidothc=0 m:oexpothc=255587 m:aidothb=0 m:total_fi=2894787 m:oexpothd=1451216 m:aidotha=705148 m:oexpotha=621295 m:oexpothb=574334 m:aidplsc=0 m:aidplsd=0 m:total_si=6498903 m:totoxstb=3048762 m:totoxsta=359630 m:oexpcold=1549689 m:lstainc=2033215 m:aidplsa=0 m:oexpcolb=508919 m:grexpt=252780 m:aidplsb=0 m:oexpcolc=5551 m:serdifxu=202289 m:oexpsalb=2054113 m:othexpd=0 m:aidiplc=0 m:oexpcola=1035219 m:oexpsalc=43779 m:aidipld=2512234 m:siaidlib=2237085 m:othexpb=0 m:aidipla=252780 m:oexpsala=237510 m:aidoila=0 m:othexpc=0 m:aidiplb=2259454 m:aidoilb=0 m:aidsald=52701 m:totaidd=3270083 m:aidoilc=0 m:totaidc=0 m:techxu=1549280 m:oexpsald=2335402 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

metric m:popu_st p:float l:Population t:dataTypeName=number

entity e:mjb9-rsyd l:"State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/mjb9-rsyd

property e:mjb9-rsyd t:meta.view v:id=mjb9-rsyd v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:mjb9-rsyd t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:mjb9-rsyd t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:mjb9-rsyd t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:mjb9-rsyd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                     | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                                  | fipsst | obereg | rstatus | fystart    | fyend      | lstainc    | fioth     | total_fi   | sistlaop   | siaidlib    | siother   | total_si    | othincm   | totincm     | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena  | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola  | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc  | oexpothd  | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc   | aidipld    | aidplsa   | aidplsb    | aidplsc | aidplsd    | aidoila  | aidoilb   | aidoilc | aidoild   | aidmlsa   | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca | aidlcb     | aidlcc | aidlcd     | aidotha   | aidothb   | aidothc | aidothd    | totaida   | totaidb     | totaidc   | totaidd     | capitala | capitalb | capitalc | capitald | othexpa   | othexpb   | othexpc   | othexpd    | totexpa    | totexpb     | totexpc   | totexpd     | swexpt    | grexpt    | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | =========================================== | ======= | ====== | ======= | ====== | ====== | ======================================================================================================================== | ====== | ====== | ======= | ========== | ========== | ========== | ========= | ========== | ========== | =========== | ========= | =========== | ========= | =========== | ========= | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ========= | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ========= | ========== | ========= | ========== | ======= | ========== | ======== | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ====== | ========== | ====== | ========== | ========= | ========= | ======= | ========== | ========= | =========== | ========= | =========== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ========== | ========== | =========== | ========= | =========== | ========= | ========= | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                     | N       | Y      | N       | Y      | Y      | P                                                                                                                        | 2      | 2      | 1       | 1246406400 | 1277856000 | 11491848.0 | 0.0       | 11491848.0 | 9484211.0  | 101175853.0 | 0.0       | 110660064.0 | 66016.0   | 122217928.0 | 3329900.0 | 5714685.0 | 0.0      | 9044585.0 | 1398640.0 | 0.0       | 0.0      | 1398640.0 | 4728540.0 | 5714685.0 | 0.0      | 10443225.0 | 0.0       | 3416232.0 | 0.0      | 3416232.0 | 974469.0  | 147168.0  | 80044.0   | 1201681.0 | 5703009.0 | 9278085.0  | 80044.0   | 15061138.0 | 171102.0  | 42238799.0 | 0.0       | 42409901.0 | 362130.0  | 26649574.0 | 0.0     | 27011704.0 | 0.0      | 4870474.0 | 0.0     | 4870474.0 | 73999.0   | 6102313.0 | 0.0     | 6176312.0 | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 14000000.0 | 0.0    | 14000000.0 | 3172486.0 | 7709455.0 | 0.0     | 10881941.0 | 3779717.0 | 101570615.0 | 0.0       | 105350332.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 9482726.0  | 110848700.0 | 80044.0   | 120411470.0 | 5315887.0 | 3779717.0 | 369346.0 | 9464950.0  | 6906140.0 | 73774.0   | 2115690.0 | 369346.0 | 9464950.0  | 19378102.0 | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | statelibrary.alabama.gov/Content/Index.aspx | N       | N      | N       | N      | Y      | IMLS - CONNECTING TO COLLECTIONS -C2C                                                                                    | 1      | 3      | 2       | 1254355200 | 1285804800 | 5239097.0  | 24200.0   | 5263297.0  | 9227079.0  | 1937663.0   | 9000.0    | 11173742.0  | 5826807.0 | 22263846.0  | 420984.0  | 2597209.0 | 524302.0 | 3542495.0 | 140327.0  | 865737.0  | 174768.0 | 1180832.0 | 561311.0  | 3462946.0 | 699070.0 | 4723327.0  | 235788.0  | 1412624.0 | 500000.0 | 2148412.0 | 781694.0  | 4007710.0 | 2507349.0 | 7296753.0 | 1578793.0 | 8883280.0  | 3706419.0 | 14168492.0 | 172771.0  | 81000.0    | 1015950.0 | 1269721.0  | 0.0       | 0.0        | 0.0     | 0.0        | 27027.0  | 0.0       | 0.0     | 27027.0   | 254030.0  | 582469.0  | 0.0     | 836499.0  | 2846562.0 | 1274194.0 | 0.0     | 4120756.0 | 0.0    | 0.0        | 0.0    | 0.0        | 571991.0  | 0.0       | 0.0     | 571991.0   | 3872381.0 | 1937663.0   | 1015950.0 | 6825994.0   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 5451174.0  | 10820943.0  | 4722369.0 | 20994486.0  | 1497028.0 | 3872381.0 | 58260.0  | 5427669.0  | 4752115.0 | 386409.0  | 230885.0  | 58260.0  | 5427669.0  | 11536504.0 | 
| ARKANSAS STATE LIBRARY                             | 900 WEST CAPITOL, SUITE 100                   | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100           | LITTLE ROCK | AR      | 72201   | 3108     | WWW.library.arkansas.gov                    | Y       | N      | N       | N      | N      | NATIONAL LEADERSHIP GRANT/IMLSNATIONAL HISTORICAL & RECORDS COMMISSIONTANF - TEMPORARY ASSISTANCE TO NEEDY FAMILIES      | 5      | 6      | 1       | 1246406400 | 1277856000 | 2033215.0  | 861572.0  | 2894787.0  | 4261818.0  | 2237085.0   | 0.0       | 6498903.0   | 336653.0  | 9730343.0   | 237510.0  | 2054113.0 | 43779.0  | 2335402.0 | 122120.0  | 994649.0  | 15318.0  | 1132087.0 | 359630.0  | 3048762.0 | 59097.0  | 3467489.0  | 1035219.0 | 508919.0  | 5551.0   | 1549689.0 | 621295.0  | 574334.0  | 255587.0  | 1451216.0 | 2016144.0 | 4132015.0  | 320235.0  | 6468394.0  | 252780.0  | 2259454.0  | 0.0       | 2512234.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 52701.0   | 0.0       | 0.0     | 52701.0   | 0.0    | 0.0        | 0.0    | 0.0        | 705148.0  | 0.0       | 0.0     | 705148.0   | 1010629.0 | 2259454.0   | 0.0       | 3270083.0   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 3026773.0  | 6391469.0   | 320235.0  | 9738477.0   | 1763641.0 | 252780.0  | 16793.0  | 2033214.0  | 1549280.0 | 202289.0  | 264852.0  | 16793.0  | 2033214.0  | 3751351.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                               | Y       | N      | N       | N      | Y      | P                                                                                                                        | 4      | 8      | 1       | 1246406400 | 1277856000 | 1798972.0  | 0.0       | 1798972.0  | 3726088.0  | 720103.0    | 0.0       | 4446191.0   | 241787.0  | 6486950.0   | 221909.0  | 1661916.0 | 46952.0  | 1930777.0 | 101741.0  | 821735.0  | 26507.0  | 949983.0  | 323650.0  | 2483651.0 | 73459.0  | 2880760.0  | 9994.0    | 76652.0   | 0.0      | 86646.0   | 400054.0  | 1105050.0 | 74266.0   | 1579370.0 | 733698.0  | 3665353.0  | 147725.0  | 4546776.0  | 217092.0  | 630471.0   | 0.0       | 847563.0   | 85018.0   | 89632.0    | 0.0     | 174650.0   | 344018.0 | 0.0       | 0.0     | 344018.0  | 149914.0  | 0.0       | 0.0     | 149914.0  | 356741.0  | 0.0       | 0.0     | 356741.0  | 0.0    | 0.0        | 0.0    | 0.0        | 0.0       | 0.0       | 0.0     | 0.0        | 1152783.0 | 720103.0    | 0.0       | 1872886.0   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 1886481.0  | 4385456.0   | 147725.0  | 6419662.0   | 646082.0  | 1152783.0 | 87616.0  | 1886481.0  | 909353.0  | 176417.0  | 713095.0  | 87616.0  | 1886481.0  | 3831074.0  | 
| CALIFORNIA STATE LIBRARY                           | 900 N ST                                      | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                          | Y       | Y      | Y       | Y      | Y      | LAURA BUSH FUNDS                                                                                                         | 6      | 2      | 1       | 1246406400 | 1277856000 | 3851940.0  | 337615.0  | 4189555.0  | 2372000.0  | 60000000.0  | 8944162.0 | 71316162.0  | 0.0       | 75505717.0  | 840063.0  | 1850118.0 | 0.0      | 2690181.0 | 361036.0  | 655733.0  | 0.0      | 1016769.0 | 1201099.0 | 2505851.0 | 0.0      | 3706950.0  | 524546.0  | 212057.0  | 0.0      | 736603.0  | 123640.0  | 341778.0  | 0.0       | 465418.0  | 1849285.0 | 3059686.0  | 0.0       | 4908971.0  | 748931.0  | 26070386.0 | 0.0       | 26819317.0 | 29412.0   | 31178880.0 | 0.0     | 31208292.0 | 333911.0 | 0.0       | 0.0     | 333911.0  | 68650.0   | 0.0       | 0.0     | 68650.0   | 503946.0  | 7260048.0 | 0.0     | 7763994.0 | 0.0    | 3077162.0  | 0.0    | 3077162.0  | 655420.0  | 670000.0  | 0.0     | 1325420.0  | 2340270.0 | 68256476.0  | 0.0       | 70596746.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 4189555.0  | 71316162.0  | 0.0       | 75505717.0  | 1820695.0 | 2002656.0 | 28589.0  | 3851940.0  | 1729117.0 | 675120.0  | 1419114.0 | 28589.0  | 3851940.0  | 12702379.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | www.cde.state.co.us/cdelib/                 | Y       | Y      | N       | Y      | N      | CONNECTING TO COLLECTIONS PLANNING GRANT: PROTECTING THE PAST- RI                                                        | 8      | 1      | 1       | 1246406400 | 1277856000 | 919540.0   | 29610.0   | 949150.0   | 832239.0   | 11512511.0  | 0.0       | 12344750.0  | 172.0     | 13294072.0  | 318390.0  | 442823.0  | 0.0      | 761213.0  | 160236.0  | 211447.0  | 0.0      | 371683.0  | 478626.0  | 654270.0  | 0.0      | 1132896.0  | 10281.0   | 0.0       | 0.0      | 10281.0   | 287494.0  | 117969.0  | 172.0     | 405635.0  | 776401.0  | 772239.0   | 172.0     | 1548812.0  | 20496.0   | 7698413.0  | 0.0       | 7718909.0  | 0.0       | 0.0        | 0.0     | 0.0        | 6454.0   | 37732.0   | 0.0     | 44186.0   | 0.0       | 0.0       | 0.0     | 0.0       | 131018.0  | 1036878.0 | 0.0     | 1167896.0 | 0.0    | 2739488.0  | 0.0    | 2739488.0  | 0.0       | 0.0       | 0.0     | 0.0        | 157968.0  | 11512511.0  | 0.0       | 11670479.0  | 6018.0   | 0.0      | 0.0      | 6018.0   | 0.0       | 0.0       | 0.0       | 0.0        | 940387.0   | 12284750.0  | 172.0     | 13225309.0  | 732970.0  | 157968.0  | 28602.0  | 919540.0   | 356375.0  | 347466.0  | 187097.0  | 28602.0  | 919540.0   | 1052567.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                               | Y       | N      | N       | N      | N      | ARRA STATE STABILIZATION PROGRAM FUNDS                                                                                   | 9      | 5      | 1       | 1246406400 | 1277856000 | 1892160.0  | 1685045.0 | 3577205.0  | 4173361.0  | 5853050.0   | 0.0       | 10026411.0  | 34306.0   | 13637922.0  | 681237.0  | 862362.0  | 0.0      | 1543599.0 | 215236.0  | 253895.0  | 0.0      | 469131.0  | 896473.0  | 1116257.0 | 0.0      | 2012730.0  | 23833.0   | 64891.0   | 0.0      | 88724.0   | 1272430.0 | 2991267.0 | 0.0       | 4263697.0 | 2192736.0 | 4172415.0  | 0.0       | 6365151.0  | 1992866.0 | 5853050.0  | 0.0       | 7845916.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 133168.0  | 0.0       | 0.0     | 133168.0  | 0.0    | 0.0        | 0.0    | 0.0        | 0.0       | 0.0       | 0.0     | 0.0        | 2126034.0 | 5853050.0   | 0.0       | 7979084.0   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 4318770.0  | 10025465.0  | 0.0       | 14344235.0  | 2087387.0 | 440989.0  | 105349.0 | 2633725.0  | 997016.0  | 1025857.0 | 505503.0  | 105349.0 | 2633725.0  | 4625364.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                           | N       | N      | N       | N      | N      | P                                                                                                                        | 11     | 4      | 1       | 1254355200 | 1285804800 | 985842.0   | 0.0       | 985842.0   | 2138943.0  | 0.0         | 0.0       | 2138943.0   | 135690.0  | 3260475.0   | 190171.0  | 867680.0  | 2100.0   | 1059951.0 | 71544.0   | 258879.0  | 551.0    | 330974.0  | 261715.0  | 1126559.0 | 2651.0   | 1390925.0  | 385538.0  | 26570.0   | 0.0      | 412108.0  | 354541.0  | 985814.0  | 11.0      | 1340366.0 | 1001794.0 | 2138943.0  | 2662.0    | 3143399.0  | 5624.0    | 0.0        | 86538.0   | 92162.0    | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0       | 0.0       | 0.0     | 0.0        | 5624.0    | 0.0         | 86538.0   | 92162.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 1007418.0  | 2138943.0   | 89200.0   | 3235561.0   | 966130.0  | 5624.0    | 35664.0  | 1007418.0  | 522052.0  | 438251.0  | 11451.0   | 35664.0  | 1007418.0  | 814180.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 121 DUKE OF YORK STREET                       | DOVER       | DE      | 19901   | 7430     | 121 DUKE OF YORK STREET               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                         | Y       | N      | N       | N      | N      | NHPRC - 9,500 IMLS - CONNECTING TO COLLECTIONS - 17,329                                                                  | 10     | 5      | 1       | 1246406400 | 1277856000 | 3417184.0  | 26829.0   | 3444013.0  | 13374044.0 | 452000.0    | 365047.0  | 14191091.0  | 650553.0  | 18285657.0  | 517128.0  | 6675102.0 | 0.0      | 7192230.0 | 183592.0  | 3080475.0 | 0.0      | 3264067.0 | 700720.0  | 9755577.0 | 0.0      | 10456297.0 | 1673745.0 | 1294668.0 | 0.0      | 2968413.0 | 538836.0  | 3377881.0 | 0.0       | 3916717.0 | 2913301.0 | 14428126.0 | 0.0       | 17341427.0 | 401401.0  | 452000.0   | 0.0       | 853401.0   | 0.0       | 0.0        | 0.0     | 0.0        | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 26829.0   | 64000.0   | 0.0     | 90829.0    | 428230.0  | 516000.0    | 0.0       | 944230.0    | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0        | 3341531.0  | 14944126.0  | 0.0       | 18285657.0  | 2778000.0 | 401401.0  | 135301.0 | 3314702.0  | 2463818.0 | 577117.0  | 138466.0  | 135301.0 | 3314702.0  | 6346105.0  | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                        | Y       | N      | N       | N      | Y      | NATIONAL HISTORICAL PUBLICATIONS & RECORDS COMMISSION (ARIS)IMLS-NLG MUSEUM-CONNECTING TO COLLECTIONSIMLS-LIBRARIANS FOR | 12     | 6      | 1       | 1246406400 | 1277856000 | 11275657.0 | 251294.0  | 11526951.0 | 14401366.0 | 8080415.0   | 3552564.0 | 26034345.0  | 1732900.0 | 39294196.0  | 426734.0  | 6513200.0 | 16179.0  | 6956113.0 | 88397.0   | 1745285.0 | 0.0      | 1833682.0 | 515131.0  | 8258485.0 | 16179.0  | 8789795.0  | 0.0       | 60743.0   | 37081.0  | 97824.0   | 515116.0  | 3233551.0 | 70273.0   | 3818940.0 | 1030247.0 | 11552779.0 | 123533.0  | 12706559.0 | 741153.0  | 7362642.0  | 0.0       | 8103795.0  | 4689400.0 | 663190.0   | 57756.0 | 5410346.0  | 120210.0 | 0.0       | 0.0     | 120210.0  | 2057420.0 | 0.0       | 0.0     | 2057420.0 | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0       | 0.0       | 0.0     | 0.0        | 7608183.0 | 8025832.0   | 57756.0   | 15691771.0  | 35438.0  | 22468.0  | 18887.0  | 76793.0  | 2853083.0 | 6399130.0 | 1532724.0 | 10784937.0 | 11526951.0 | 26000209.0  | 1732900.0 | 39260060.0  | 3219283.0 | 7608183.0 | 448191.0 | 11275657.0 | 6899232.0 | 1485695.0 | 2442539.0 | 448191.0 | 11275657.0 | 25145561.0 | 
```