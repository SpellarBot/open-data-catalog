# State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2007-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/9wry-mtm5) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/9wry-mtm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/9wry-mtm5/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 9wry-mtm5 |
| Name | State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2007, revenue, expenditures |
| Created | 2016-12-20T15:28:44Z |
| Publication Date | 2016-12-20T17:04:38Z |

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
series e:9wry-mtm5 d:2006-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=90403 m:totaida=872718 m:aidsala=443008 m:capitald=0 m:admexpt=14735 m:swexpt=0 m:admexpu=14735 m:oexpbenb=852843 m:oexpbena=8105 m:oexpbend=877867 m:oexpbenc=16919 m:totincm=5099564 m:othincm=35300 m:aidlcd=0 m:aidlcc=0 m:totexpu=887453 m:totexpt=887453 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=5073528 m:totexpa=887453 m:totexpc=99667 m:totexpb=4086408 m:sistlaop=3195008 m:aidmlsa=182762 m:aidmlsc=11944 m:popu_st=683478 m:aidmlsb=8785 m:totoxstc=53713 m:totoxstd=2468844 m:aidmlsd=203491 m:serllxu=328659 m:totopexc=53713 m:totopexd=3263456 m:totopexa=14735 m:aidothd=0 m:totopexb=3195008 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=887453 m:oexpothd=586210 m:aidotha=0 m:oexpotha=0 m:oexpothb=586210 m:aidplsc=25000 m:aidplsd=121925 m:total_si=4176811 m:totoxstb=2400396 m:totoxsta=14735 m:oexpcold=208402 m:lstainc=887453 m:aidplsa=96925 m:oexpcolb=208402 m:grexpt=872718 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=269749 m:oexpsalb=1547553 m:othexpd=0 m:aidiplc=2261 m:oexpcola=0 m:oexpsalc=36794 m:aidipld=767959 m:siaidlib=891400 m:othexpb=0 m:aidipla=113388 m:oexpsala=6630 m:aidoila=36635 m:othexpc=0 m:aidiplb=652310 m:aidoilb=85389 m:aidsald=587924 m:totaidd=1810072 m:aidoilc=6749 m:totaidc=45954 m:techxu=274310 m:oexpsald=1590977 m:aidoild=128773 m:aidsalb=144916 m:aidsalc=0 m:othexpa=0

series e:9wry-mtm5 d:2006-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=N t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=8666208 m:siother=3757600 m:totaida=1122311 m:aidsala=86775 m:capitald=0 m:admexpt=104267 m:swexpt=1383970 m:admexpu=104267 m:oexpbenb=701449 m:oexpbena=0 m:oexpbend=702117 m:oexpbenc=668 m:totincm=14724932 m:othincm=550550 m:aidlcd=0 m:aidlcc=0 m:totexpu=2610548 m:totexpt=2610548 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=14542933 m:totexpa=2610549 m:totexpc=550550 m:totexpb=11381834 m:sistlaop=2715626 m:aidmlsa=51200 m:aidmlsc=0 m:popu_st=4627851 m:aidmlsb=0 m:totoxstc=2183 m:totoxstd=2717809 m:aidmlsd=51200 m:serllxu=679733 m:totopexc=65635 m:totopexd=4269499 m:totopexa=1488238 m:aidothd=38705 m:totopexb=2715626 m:aidothc=38705 m:oexpothc=63452 m:aidothb=0 m:total_fi=2610548 m:oexpothd=1527816 m:aidotha=0 m:oexpotha=1464364 m:oexpothb=0 m:aidplsc=0 m:aidplsd=96500 m:total_si=11563834 m:totoxstb=2715626 m:totoxsta=0 m:oexpcold=23874 m:lstainc=2610548 m:aidplsa=96500 m:oexpcolb=0 m:grexpt=1122311 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=523010 m:oexpsalb=2014177 m:othexpd=0 m:aidiplc=446210 m:oexpcola=23874 m:oexpsalc=1515 m:aidipld=6424654 m:siaidlib=5090608 m:othexpb=0 m:aidipla=887836 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=5090608 m:aidoilb=0 m:aidsald=3662375 m:totaidd=10273434 m:aidoilc=0 m:totaidc=484915 m:techxu=1303538 m:oexpsald=2015692 m:aidoild=0 m:aidsalb=3575600 m:aidsalc=0 m:othexpa=0

series e:9wry-mtm5 d:2006-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1013 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1013 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=73085 m:totaidb=4000000 m:siother=113864 m:totaida=0 m:aidsala=0 m:capitald=73085 m:admexpt=12847 m:swexpt=1777242 m:admexpu=12847 m:oexpbenb=430747 m:oexpbena=116130 m:oexpbend=546877 m:oexpbenc=0 m:totincm=8623376 m:othincm=46800 m:aidlcd=0 m:aidlcc=0 m:totexpu=1790089 m:totexpt=1790089 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=8928842 m:totexpa=1790089 m:totexpc=158741 m:totexpb=6980012 m:sistlaop=2980012 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2834797 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2378113 m:aidmlsd=0 m:serllxu=373110 m:totopexc=39491 m:totopexd=4736507 m:totopexa=1717004 m:aidothd=0 m:totopexb=2980012 m:aidothc=0 m:oexpothc=39491 m:aidothb=0 m:total_fi=1482700 m:oexpothd=1945418 m:aidotha=0 m:oexpotha=945674 m:oexpothb=960253 m:aidplsc=0 m:aidplsd=0 m:total_si=7093876 m:totoxstb=1955210 m:totoxsta=422903 m:oexpcold=412976 m:lstainc=1482700 m:aidplsa=0 m:oexpcolb=64549 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=643485 m:oexpsalb=1524463 m:othexpd=0 m:aidiplc=119250 m:oexpcola=348427 m:oexpsalc=0 m:aidipld=4119250 m:siaidlib=4000000 m:othexpb=0 m:aidipla=0 m:oexpsala=306773 m:aidoila=0 m:othexpc=0 m:aidiplb=4000000 m:aidoilb=0 m:aidsald=0 m:totaidd=4119250 m:aidoilc=0 m:totaidc=119250 m:techxu=760647 m:oexpsald=1831236 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:9wry-mtm5 l:"State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9wry-mtm5

property e:9wry-mtm5 t:meta.view v:id=9wry-mtm5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:9wry-mtm5 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9wry-mtm5 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:9wry-mtm5 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9wry-mtm5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                         | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                     | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                       | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth  | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd   | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc   | aidipld    | aidplsa | aidplsb  | aidplsc  | aidplsd  | aidoila  | aidoilb | aidoilc | aidoild  | aidmlsa  | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca | aidlcb    | aidlcc | aidlcd    | aidotha  | aidothb  | aidothc | aidothd  | totaida   | totaidb    | totaidc   | totaidd    | capitala | capitalb | capitalc | capitald | othexpa   | othexpb   | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt    | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ================================================== | ================================ | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | =========================================== | ======= | ====== | ======= | ====== | ====== | ============================================================================================================= | ======== | ====== | ======= | ========== | ========== | ========== | ====== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ========== | ======== | ========== | ========= | ========== | ========= | ========== | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ====== | ========= | ====== | ========= | ======== | ======== | ======= | ======== | ========= | ========== | ========= | ========== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========= | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE            | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                     | Y       | Y      | Y       | Y      | Y      | P                                                                                                             | 2        | 8      | 1       | 1151712000 | 1183161600 | 887453.0   | 0.0    | 887453.0   | 3195008.0  | 891400.0   | 90403.0   | 4176811.0  | 35300.0   | 5099564.0  | 6630.0    | 1547553.0 | 36794.0  | 1590977.0 | 8105.0   | 852843.0  | 16919.0  | 877867.0  | 14735.0   | 2400396.0 | 53713.0  | 2468844.0  | 0.0      | 208402.0  | 0.0      | 208402.0  | 0.0       | 586210.0  | 0.0      | 586210.0   | 14735.0   | 3195008.0  | 53713.0  | 3263456.0  | 113388.0  | 652310.0   | 2261.0    | 767959.0   | 96925.0 | 0.0      | 25000.0  | 121925.0 | 36635.0  | 85389.0 | 6749.0  | 128773.0 | 182762.0 | 8785.0    | 11944.0 | 203491.0  | 443008.0  | 144916.0  | 0.0     | 587924.0  | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 872718.0  | 891400.0   | 45954.0   | 1810072.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 887453.0   | 4086408.0  | 99667.0   | 5073528.0  | 0.0       | 872718.0  | 14735.0  | 887453.0   | 274310.0  | 269749.0  | 328659.0  | 14735.0  | 887453.0   | 683478.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | statelibrary.alabama.gov/Content/Index.aspx | Y       | N      | N       | N      | N      | P                                                                                                             | 1        | 5      | 1       | 1159660800 | 1191110400 | 2610548.0  | 0.0    | 2610548.0  | 2715626.0  | 5090608.0  | 3757600.0 | 11563834.0 | 550550.0  | 14724932.0 | 0.0       | 2014177.0 | 1515.0   | 2015692.0 | 0.0      | 701449.0  | 668.0    | 702117.0  | 0.0       | 2715626.0 | 2183.0   | 2717809.0  | 23874.0  | 0.0       | 0.0      | 23874.0   | 1464364.0 | 0.0       | 63452.0  | 1527816.0  | 1488238.0 | 2715626.0  | 65635.0  | 4269499.0  | 887836.0  | 5090608.0  | 446210.0  | 6424654.0  | 96500.0 | 0.0      | 0.0      | 96500.0  | 0.0      | 0.0     | 0.0     | 0.0      | 51200.0  | 0.0       | 0.0     | 51200.0   | 86775.0   | 3575600.0 | 0.0     | 3662375.0 | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 38705.0 | 38705.0  | 1122311.0 | 8666208.0  | 484915.0  | 10273434.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 2610549.0  | 11381834.0 | 550550.0  | 14542933.0 | 1383970.0 | 1122311.0 | 104267.0 | 2610548.0  | 1303538.0 | 523010.0  | 679733.0  | 104267.0 | 2610548.0  | 4627851.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR    | LITTLE ROCK | AR      | 72201   | 1013     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1013     | WWW.ASL.LIB.AR.US                           | Y       | N      | N       | N      | N      | P                                                                                                             | 5        | 5      | 1       | 1151712000 | 1183161600 | 1482700.0  | 0.0    | 1482700.0  | 2980012.0  | 4000000.0  | 113864.0  | 7093876.0  | 46800.0   | 8623376.0  | 306773.0  | 1524463.0 | 0.0      | 1831236.0 | 116130.0 | 430747.0  | 0.0      | 546877.0  | 422903.0  | 1955210.0 | 0.0      | 2378113.0  | 348427.0 | 64549.0   | 0.0      | 412976.0  | 945674.0  | 960253.0  | 39491.0  | 1945418.0  | 1717004.0 | 2980012.0  | 39491.0  | 4736507.0  | 0.0       | 4000000.0  | 119250.0  | 4119250.0  | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | 4000000.0  | 119250.0  | 4119250.0  | 73085.0  | 0.0      | 0.0      | 73085.0  | 0.0       | 0.0       | 0.0       | 0.0       | 1790089.0  | 6980012.0  | 158741.0  | 8928842.0  | 1777242.0 | 0.0       | 12847.0  | 1790089.0  | 760647.0  | 643485.0  | 373110.0  | 12847.0  | 1790089.0  | 2834797.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                               | Y       | N      | N       | N      | N      | NATIONAL HISTORICAL PUBLICATIONS & RECORDS COMMISSION (NHPRC) GRANT                                           | 4        | 6      | 1       | 1151712000 | 1183161600 | 2712222.0  | 5355.0 | 2717577.0  | 6792200.0  | 651400.0   | 97000.0   | 7540600.0  | 429976.0  | 10688153.0 | 271865.0  | 4167035.0 | 315457.0 | 4754357.0 | 84548.0  | 1382169.0 | 121138.0 | 1587855.0 | 356413.0  | 5549204.0 | 436595.0 | 6342212.0  | 24105.0  | 251736.0  | 25506.0  | 301347.0  | 0.0       | 804828.0  | 0.0      | 804828.0   | 380518.0  | 6605768.0  | 462101.0 | 7448387.0  | 669169.0  | 559636.0   | 0.0       | 1228805.0  | 22972.0 | 0.0      | 0.0      | 22972.0  | 80569.0  | 0.0     | 0.0     | 80569.0  | 0.0      | 0.0       | 0.0     | 0.0       | 149066.0  | 0.0       | 0.0     | 149066.0  | 0.0    | 83021.0   | 0.0    | 83021.0   | 8355.0   | 0.0      | 0.0     | 8355.0   | 930131.0  | 642657.0   | 0.0       | 1572788.0  | 0.0      | 66000.0  | 0.0      | 66000.0  | 1409928.0 | 0.0       | 0.0       | 1409928.0 | 2720577.0  | 7314425.0  | 462101.0  | 10497103.0 | 1675355.0 | 930131.0  | 106736.0 | 2712222.0  | 1268223.0 | 1098784.0 | 238479.0  | 106736.0 | 2712222.0  | 6338755.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                 | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                          | Y       | N      | N       | N      | Y      | P                                                                                                             | 6        | 8      | 2       | 1151712000 | 1183161600 | 16506165.0 | 0.0    | 16506165.0 | 16268350.0 | 47766000.0 | 0.0       | 64034350.0 | 416132.0  | 80956647.0 | 2198577.0 | 6346048.0 | 281259.0 | 8825884.0 | 805833.0 | 2275788.0 | 110637.0 | 3192258.0 | 3004410.0 | 8621836.0 | 391896.0 | 12018142.0 | 365458.0 | 1401552.0 | 0.0      | 1767010.0 | 6136799.0 | 6244962.0 | 24236.0  | 12405997.0 | 9506667.0 | 16268350.0 | 416132.0 | 26191149.0 | 1687656.0 | 44806332.0 | 0.0       | 46493988.0 | 0.0     | 0.0      | 0.0      | 0.0      | 321148.0 | 0.0     | 0.0     | 321148.0 | 163598.0 | 2959668.0 | 0.0     | 3123266.0 | 4832850.0 | 0.0       | 0.0     | 4832850.0 | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 7005252.0 | 47766000.0 | 0.0       | 54771252.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 16511919.0 | 64034350.0 | 416132.0  | 80962401.0 | 9378277.0 | 7005252.0 | 122636.0 | 16506165.0 | 9189042.0 | 2541347.0 | 4653140.0 | 122636.0 | 16506165.0 | 36553215.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM       | N       | N      | N       | N      | Y      | P                                                                                                             | 8        | 7      | 1       | 1151712000 | 1183161600 | 2642220.0  | 0.0    | 2642220.0  | 943430.0   | 1347554.0  | 217952.0  | 2508936.0  | 212877.0  | 5364033.0  | 1231549.0 | 609279.0  | 110189.0 | 1951017.0 | 216838.0 | 105711.0  | 21654.0  | 344203.0  | 1448387.0 | 714990.0  | 131843.0 | 2295220.0  | 21612.0  | 0.0       | 0.0      | 21612.0   | 156401.0  | 228440.0  | 81034.0  | 465875.0   | 1626400.0 | 943430.0   | 212877.0 | 2782707.0  | 105550.0  | 0.0        | 0.0       | 105550.0   | 0.0     | 0.0      | 0.0      | 0.0      | 115989.0 | 0.0     | 0.0     | 115989.0 | 125200.0 | 1000000.0 | 0.0     | 1125200.0 | 459984.0  | 347554.0  | 0.0     | 807538.0  | 0.0    | 0.0       | 0.0    | 0.0       | 56275.0  | 0.0      | 0.0     | 56275.0  | 862998.0  | 1347554.0  | 0.0       | 2210552.0  | 47134.0  | 17952.0  | 0.0      | 65086.0  | 105688.0  | 200000.0  | 0.0       | 305688.0  | 2642220.0  | 2508936.0  | 212877.0  | 5364033.0  | 1673534.0 | 862998.0  | 105688.0 | 2642220.0  | 966752.0  | 780151.0  | 789629.0  | 105688.0 | 2642220.0  | 4861515.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                               | Y       | N      | N       | N      | Y      | P                                                                                                             | 9        | 1      | 1       | 1151712000 | 1183161600 | 2434263.0  | 0.0    | 2434263.0  | 10265097.0 | 5123137.0  | 0.0       | 15388234.0 | 1972879.0 | 19795376.0 | 887781.0  | 5935759.0 | 415781.0 | 7239321.0 | 522003.0 | 0.0       | 222281.0 | 744284.0  | 1409784.0 | 5935759.0 | 638062.0 | 7983605.0  | 118811.0 | 965213.0  | 3928.0   | 1087952.0 | 601551.0  | 3270860.0 | 181375.0 | 4053786.0  | 2130146.0 | 10171832.0 | 823365.0 | 13125343.0 | 155210.0  | 1323137.0  | 0.0       | 1478347.0  | 50000.0 | 0.0      | 0.0      | 50000.0  | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 300000.0  | 0.0     | 300000.0  | 0.0    | 3324133.0 | 0.0    | 3324133.0 | 0.0      | 0.0      | 0.0     | 0.0      | 205210.0  | 4947270.0  | 0.0       | 5152480.0  | 0.0      | 175075.0 | 0.0      | 175075.0 | 0.0       | 0.0       | 1472829.0 | 1472829.0 | 2335356.0  | 15294177.0 | 2296194.0 | 19925727.0 | 2117179.0 | 205210.0  | 12967.0  | 2335356.0  | 978496.0  | 810752.0  | 533141.0  | 12967.0  | 2335356.0  | 3502309.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                           | Y       | N      | N       | N      | N      | NATIONAL HISTORICAL PUBLICATION AND RECORDS COMMISSION (NHPRC) GRANT-PRESERVE WASHINGTON STAR OVERSIZE PHOTOS | 11       | 2      | 1       | 1159660800 | 1191110400 | 842132.0   | 5853.0 | 847985.0   | 42829173.0 | 0.0        | 0.0       | 42829173.0 | 1325631.0 | 45002789.0 | 396869.0  | 214095.0  | 0.0      | 610964.0  | 73305.0  | 22056.0   | 0.0      | 95361.0   | 470174.0  | 236151.0  | 0.0      | 706325.0   | 0.0      | 0.0       | 0.0      | 0.0       | 249447.0  | 59129.0   | 0.0      | 308576.0   | 719621.0  | 295280.0   | 0.0      | 1014901.0  | 188779.0  | 41642383.0 | 1162345.0 | 42993507.0 | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 188779.0  | 41642383.0 | 1162345.0 | 42993507.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 908400.0   | 41937663.0 | 1162345.0 | 44008408.0 | 631415.0  | 188779.0  | 21836.0  | 842030.0   | 0.0       | 93746.0   | 726448.0  | 21836.0  | 842030.0   | 588292.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                         | Y       | N      | N       | N      | Y      | P                                                                                                             | 10       | 2      | 1       | 1151712000 | 1183161600 | 986568.0   | 0.0    | 986568.0   | 3184240.0  | 4022550.0  | 9243950.0 | 16450740.0 | 683660.0  | 18120968.0 | 383914.0  | 455861.0  | 0.0      | 839775.0  | 149036.0 | 189909.0  | 0.0      | 338945.0  | 532950.0  | 645770.0  | 0.0      | 1178720.0  | 9280.0   | 5687.0    | 0.0      | 14967.0   | 963835.0  | 1628777.0 | 0.0      | 2592612.0  | 1506065.0 | 2280234.0  | 0.0      | 3786299.0  | 137000.0  | 2916578.0  | 0.0       | 3053578.0  | 0.0     | 451983.0 | 364326.0 | 816309.0 | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 4109912.0 | 0.0    | 4109912.0 | 0.0      | 441902.0 | 0.0     | 441902.0 | 137000.0  | 7920375.0  | 364326.0  | 8421701.0  | 0.0      | 7000.0   | 0.0      | 7000.0   | 0.0       | 1088900.0 | 269963.0  | 1358863.0 | 1643065.0  | 11296509.0 | 634289.0  | 13573863.0 | 1502987.0 | 137000.0  | 3078.0   | 1643065.0  | 19800.0   | 150142.0  | 1470045.0 | 3078.0   | 1643065.0  | 864764.0   | 
| WASHINGTON STATE LIBRARY                           | 6880 CAPITOL BLVD S              | TUMWATER    | WA      | 98501   | 5513     | PO BOX 42460                          | OLYMPIA     | WA      | 98504   | 2460     | WWW.SECSTATE.WA.GOV/LIBRARY                 | N       | N      | N       | Y      | N      | P                                                                                                             | 53       | 8      | 1       | 1151712000 | 1183161600 | 3023313.0  | 0.0    | 3023313.0  | 5749293.0  | 1022000.0  | 366793.0  | 7138086.0  | 232833.0  | 10394232.0 | 802979.0  | 2935731.0 | 32743.0  | 3771453.0 | 220356.0 | 890408.0  | 10153.0  | 1120917.0 | 1023335.0 | 3826139.0 | 42896.0  | 4892370.0  | 99562.0  | 407544.0  | 1992.0   | 509098.0  | 1200636.0 | 1741738.0 | 247412.0 | 3189786.0  | 2323533.0 | 5975421.0  | 292300.0 | 8591254.0  | 95090.0   | 0.0        | 0.0       | 95090.0    | 0.0     | 0.0      | 0.0      | 0.0      | 140173.0 | 0.0     | 0.0     | 140173.0 | 0.0      | 0.0       | 0.0     | 0.0       | 328000.0  | 1022000.0 | 0.0     | 1350000.0 | 0.0    | 0.0       | 0.0    | 0.0       | 136517.0 | 0.0      | 2706.0  | 139223.0 | 699780.0  | 1022000.0  | 2706.0    | 1724486.0  | 0.0      | 140665.0 | 0.0      | 140665.0 | 0.0       | 0.0       | 0.0       | 0.0       | 3023313.0  | 7138086.0  | 295006.0  | 10456405.0 | 2173166.0 | 699780.0  | 150367.0 | 3023313.0  | 1110210.0 | 1432026.0 | 330710.0  | 150367.0 | 3023313.0  | 6468424.0  | 
```