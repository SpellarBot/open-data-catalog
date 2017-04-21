# State Libraries Survey, FY 2006, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2006-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/4yk9-qksv) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/4yk9-qksv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/4yk9-qksv/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 4yk9-qksv |
| Name | State Libraries Survey, FY 2006, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2006, revenue, expenditures |
| Created | 2016-12-20T15:27:35Z |
| Publication Date | 2016-12-20T17:04:37Z |

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
series e:4yk9-qksv d:2005-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=N t:mail_st=AK t:pub_fips=2 t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:rstatus=1 t:physzip=99811 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=142967 m:totaida=828564 m:aidsala=595623 m:capitald=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=763198 m:oexpbena=0 m:oexpbend=785927 m:oexpbenc=22729 m:totincm=5069149 m:othincm=150093 m:aidlcd=0 m:aidlcc=0 m:totexpu=828563 m:totexpt=828563 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=5148122 m:totexpa=828564 m:totexpc=233919 m:totexpb=4085639 m:sistlaop=3056126 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=670053 m:aidmlsb=0 m:totoxstc=75683 m:totoxstd=2269200 m:aidmlsd=0 m:serllxu=203512 m:totopexc=115801 m:totopexd=3171927 m:totopexa=0 m:aidothd=0 m:totopexb=3056126 m:aidothc=0 m:oexpothc=40118 m:aidothb=0 m:total_fi=828563 m:oexpothd=747804 m:aidotha=0 m:oexpotha=0 m:oexpothb=707686 m:aidplsc=0 m:aidplsd=0 m:total_si=4090493 m:totoxstb=2193517 m:totoxsta=0 m:oexpcold=154923 m:lstainc=828563 m:aidplsa=0 m:oexpcolb=154923 m:grexpt=828563 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=304717 m:oexpsalb=1430319 m:othexpd=138113 m:aidiplc=75400 m:oexpcola=0 m:oexpsalc=52954 m:aidipld=864767 m:siaidlib=891400 m:othexpb=138113 m:aidipla=81153 m:oexpsala=0 m:aidoila=151788 m:othexpc=0 m:aidiplb=708214 m:aidoilb=65684 m:aidsald=713125 m:totaidd=1838082 m:aidoilc=42718 m:totaidc=118118 m:techxu=320334 m:oexpsald=1483273 m:aidoild=260190 m:aidsalb=117502 m:aidsalc=0 m:othexpa=0

series e:4yk9-qksv d:2005-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=N t:mail_st=AL t:pub_fips=1 t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=8483208 m:siother=3757600 m:totaida=1711196 m:aidsala=773596 m:capitald=0 m:admexpt=93091 m:swexpt=752384 m:admexpu=93091 m:oexpbenb=615931 m:oexpbena=4943 m:oexpbend=632684 m:oexpbenc=11810 m:totincm=13933601 m:othincm=376729 m:aidlcd=0 m:aidlcc=0 m:totexpu=2556671 m:totexpt=2556671 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=13933601 m:totexpa=2556671 m:totexpc=376729 m:totexpb=11000201 m:sistlaop=2516993 m:aidmlsa=39500 m:aidmlsc=0 m:popu_st=4599030 m:aidmlsb=0 m:totoxstc=59332 m:totoxstd=2586739 m:aidmlsd=39500 m:serllxu=0 m:totopexc=62968 m:totopexd=3425436 m:totopexa=845475 m:aidothd=0 m:totopexb=2516993 m:aidothc=0 m:oexpothc=3636 m:aidothb=0 m:total_fi=2556671 m:oexpothd=511694 m:aidotha=0 m:oexpotha=508058 m:oexpothb=0 m:aidplsc=0 m:aidplsd=124504 m:total_si=11000201 m:totoxstb=2516993 m:totoxsta=10414 m:oexpcold=327003 m:lstainc=2556671 m:aidplsa=124504 m:oexpcolb=0 m:grexpt=1711196 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=1550570 m:oexpsalb=1901062 m:othexpd=0 m:aidiplc=313761 m:oexpcola=327003 m:oexpsalc=47522 m:aidipld=5812965 m:siaidlib=4725608 m:othexpb=0 m:aidipla=773596 m:oexpsala=5471 m:aidoila=0 m:othexpc=0 m:aidiplb=4725608 m:aidoilb=0 m:aidsald=4531196 m:totaidd=10508165 m:aidoilc=0 m:totaidc=313761 m:techxu=913010 m:oexpsald=1954055 m:aidoild=0 m:aidsalb=3757600 m:aidsalc=0 m:othexpa=0

series e:4yk9-qksv d:2005-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:obereg=5 t:asf_ac=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:phys_st=AR t:mailzip=72201 t:mailzip4=1013 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1013 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fiothsp="ARKANSAS HUMANITIES COUNCIL ARTS MIDWEST (FOR THE BIG READ) LIBRARY OF CONGRESS CENTER FOR THE BOOK" m:capitalc=0 m:capitalb=4539 m:capitala=53683 m:totaidb=4013644 m:siother=812144 m:totaida=0 m:aidsala=0 m:capitald=58222 m:admexpt=8213 m:swexpt=1738662 m:admexpu=8213 m:oexpbenb=422212 m:oexpbena=113639 m:oexpbend=535851 m:oexpbenc=0 m:totincm=9531647 m:othincm=973184 m:aidlcd=0 m:aidlcc=0 m:totexpu=1746875 m:totexpt=1746875 m:fioth=32500 m:aidlca=0 m:aidlcb=0 m:totexpd=9431335 m:totexpa=1800558 m:totexpc=664800 m:totexpb=6965977 m:sistlaop=2958785 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2810872 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2339008 m:aidmlsd=0 m:serllxu=856765 m:totopexc=0 m:totopexd=4694669 m:totopexa=1746875 m:aidothd=0 m:totopexb=2947794 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=1787534 m:oexpothd=1878992 m:aidotha=0 m:oexpotha=1007262 m:oexpothb=871730 m:aidplsc=0 m:aidplsd=0 m:total_si=6770929 m:totoxstb=1929831 m:totoxsta=409177 m:oexpcold=476669 m:lstainc=1755034 m:aidplsa=0 m:oexpcolb=146233 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=196656 m:oexpsalb=1507619 m:othexpd=0 m:aidiplc=664800 m:oexpcola=330436 m:oexpsalc=0 m:aidipld=4678444 m:siaidlib=3000000 m:othexpb=0 m:aidipla=0 m:oexpsala=295538 m:aidoila=0 m:othexpc=0 m:aidiplb=4013644 m:aidoilb=0 m:aidsald=0 m:totaidd=4678444 m:aidoilc=0 m:totaidc=664800 m:techxu=685241 m:oexpsald=1803157 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:4yk9-qksv l:"State Libraries Survey, FY 2006, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/4yk9-qksv

property e:4yk9-qksv t:meta.view v:id=4yk9-qksv v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2006, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:4yk9-qksv t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:4yk9-qksv t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:4yk9-qksv t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:4yk9-qksv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                     | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                          | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola  | oexpcolb | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa  | aidplsb   | aidplsc  | aidplsd   | aidoila  | aidoilb | aidoilc | aidoild  | aidmlsa   | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca | aidlcb     | aidlcc | aidlcd     | aidotha | aidothb | aidothc | aidothd | totaida    | totaidb    | totaidc   | totaidd    | capitala | capitalb | capitalc | capitald | othexpa   | othexpb   | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | =========================================== | ======= | ====== | ======= | ====== | ====== | ================================================================================================================ | ======== | ====== | ======= | ========== | ========== | ========== | ======== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ========= | ========== | ======== | ========== | ======== | ========= | ======== | ========= | ======== | ======= | ======= | ======== | ========= | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ====== | ========== | ====== | ========== | ======= | ======= | ======= | ======= | ========== | ========== | ========= | ========== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                     | Y       | Y      | Y       | Y      | N      | P                                                                                                                | 2        | 8      | 1       | 1120176000 | 1151625600 | 828563.0   | 0.0      | 828563.0   | 3056126.0  | 891400.0   | 142967.0  | 4090493.0  | 150093.0  | 5069149.0  | 0.0       | 1430319.0 | 52954.0  | 1483273.0 | 0.0      | 763198.0  | 22729.0  | 785927.0  | 0.0       | 2193517.0 | 75683.0  | 2269200.0  | 0.0       | 154923.0 | 0.0      | 154923.0  | 0.0       | 707686.0  | 40118.0  | 747804.0  | 0.0       | 3056126.0  | 115801.0 | 3171927.0  | 81153.0   | 708214.0   | 75400.0  | 864767.0   | 0.0      | 0.0       | 0.0      | 0.0       | 151788.0 | 65684.0 | 42718.0 | 260190.0 | 0.0       | 0.0       | 0.0     | 0.0       | 595623.0  | 117502.0  | 0.0     | 713125.0  | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 828564.0   | 891400.0   | 118118.0  | 1838082.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 138113.0  | 0.0       | 138113.0  | 828564.0   | 4085639.0  | 233919.0  | 5148122.0  | 0.0       | 828563.0   | 0.0      | 828563.0   | 320334.0  | 304717.0  | 203512.0  | 0.0      | 828563.0   | 670053.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | statelibrary.alabama.gov/Content/Index.aspx | Y       | N      | N       | N      | N      | P                                                                                                                | 1        | 5      | 1       | 1128124800 | 1159574400 | 2556671.0  | 0.0      | 2556671.0  | 2516993.0  | 4725608.0  | 3757600.0 | 11000201.0 | 376729.0  | 13933601.0 | 5471.0    | 1901062.0 | 47522.0  | 1954055.0 | 4943.0   | 615931.0  | 11810.0  | 632684.0  | 10414.0   | 2516993.0 | 59332.0  | 2586739.0  | 327003.0  | 0.0      | 0.0      | 327003.0  | 508058.0  | 0.0       | 3636.0   | 511694.0  | 845475.0  | 2516993.0  | 62968.0  | 3425436.0  | 773596.0  | 4725608.0  | 313761.0 | 5812965.0  | 124504.0 | 0.0       | 0.0      | 124504.0  | 0.0      | 0.0     | 0.0     | 0.0      | 39500.0   | 0.0       | 0.0     | 39500.0   | 773596.0  | 3757600.0 | 0.0     | 4531196.0 | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 1711196.0  | 8483208.0  | 313761.0  | 10508165.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 2556671.0  | 11000201.0 | 376729.0  | 13933601.0 | 752384.0  | 1711196.0  | 93091.0  | 2556671.0  | 913010.0  | 1550570.0 | 0.0       | 93091.0  | 2556671.0  | 4599030.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1013     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1013     | WWW.ASL.LIB.AR.US                           | Y       | N      | N       | N      | N      | ARKANSAS HUMANITIES COUNCIL ARTS MIDWEST (FOR THE BIG READ) LIBRARY OF CONGRESS CENTER FOR THE BOOK              | 5        | 5      | 1       | 1120176000 | 1151625600 | 1755034.0  | 32500.0  | 1787534.0  | 2958785.0  | 3000000.0  | 812144.0  | 6770929.0  | 973184.0  | 9531647.0  | 295538.0  | 1507619.0 | 0.0      | 1803157.0 | 113639.0 | 422212.0  | 0.0      | 535851.0  | 409177.0  | 1929831.0 | 0.0      | 2339008.0  | 330436.0  | 146233.0 | 0.0      | 476669.0  | 1007262.0 | 871730.0  | 0.0      | 1878992.0 | 1746875.0 | 2947794.0  | 0.0      | 4694669.0  | 0.0       | 4013644.0  | 664800.0 | 4678444.0  | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 0.0        | 4013644.0  | 664800.0  | 4678444.0  | 53683.0  | 4539.0   | 0.0      | 58222.0  | 0.0       | 0.0       | 0.0       | 0.0       | 1800558.0  | 6965977.0  | 664800.0  | 9431335.0  | 1738662.0 | 0.0        | 8213.0   | 1746875.0  | 685241.0  | 196656.0  | 856765.0  | 8213.0   | 1746875.0  | 2810872.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                               | Y       | N      | N       | N      | N      | IMLS NATIONAL LEADERSHIP GRANT, NHPRC (NATIONAL HISTORICAL PUBLICATIONS AND RECORDS COMMISSION) GRANT            | 4        | 6      | 1       | 1120176000 | 1151625600 | 3508728.0  | 26319.0  | 3535047.0  | 6411200.0  | 651400.0   | 97000.0   | 7159600.0  | 1170544.0 | 11865191.0 | 170791.0  | 4052791.0 | 325250.0 | 4548832.0 | 44585.0  | 1260810.0 | 97492.0  | 1402887.0 | 215376.0  | 5313601.0 | 422742.0 | 5951719.0  | 2586.0    | 279913.0 | 2438.0   | 284937.0  | 0.0       | 847320.0  | 392544.0 | 1239864.0 | 217962.0  | 6440834.0  | 817724.0 | 7476520.0  | 917067.0  | 533617.0   | 0.0      | 1450684.0  | 98614.0  | 0.0       | 0.0      | 98614.0   | 201849.0 | 0.0     | 0.0     | 201849.0 | 0.0       | 0.0       | 0.0     | 0.0       | 168464.0  | 0.0       | 0.0     | 168464.0  | 0.0    | 144856.0   | 0.0    | 144856.0   | 0.0     | 0.0     | 0.0     | 0.0     | 1385994.0  | 678473.0   | 0.0       | 2064467.0  | 0.0      | 81676.0  | 11573.0  | 93249.0  | 1931091.0 | 0.0       | 0.0       | 1931091.0 | 3535047.0  | 7200983.0  | 829297.0  | 11565327.0 | 2001075.0 | 1385994.0  | 121659.0 | 3508728.0  | 2125903.0 | 165100.0  | 1096066.0 | 121659.0 | 3508728.0  | 6166318.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                          | Y       | N      | N       | N      | Y      | P                                                                                                                | 6        | 8      | 2       | 1120176000 | 1151625600 | 16557920.0 | 0.0      | 16557920.0 | 12966572.0 | 33766000.0 | 0.0       | 46732572.0 | 450217.0  | 63740709.0 | 1505843.0 | 6216422.0 | 304498.0 | 8026763.0 | 669202.0 | 2064184.0 | 111939.0 | 2845325.0 | 2175045.0 | 8280606.0 | 416437.0 | 10872088.0 | 292878.0  | 471862.0 | 0.0      | 764740.0  | 4080631.0 | 4214104.0 | 33780.0  | 8328515.0 | 6548554.0 | 12966572.0 | 450217.0 | 19965343.0 | 2410479.0 | 30883750.0 | 0.0      | 33294229.0 | 0.0      | 0.0       | 0.0      | 0.0       | 374438.0 | 0.0     | 0.0     | 374438.0 | 554575.0  | 2882250.0 | 0.0     | 3436825.0 | 7856762.0 | 0.0       | 0.0     | 7856762.0 | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 11196254.0 | 33766000.0 | 0.0       | 44962254.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 17744808.0 | 46732572.0 | 450217.0  | 64927597.0 | 5251783.0 | 11196254.0 | 109883.0 | 16557920.0 | 8744348.0 | 2539464.0 | 5164225.0 | 109883.0 | 16557920.0 | 36457549.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM       | N       | N      | N       | N      | Y      | P                                                                                                                | 8        | 7      | 1       | 1120176000 | 1151625600 | 2579074.0  | 0.0      | 2579074.0  | 857879.0   | 959796.0   | 190000.0  | 2007675.0  | 242803.0  | 4829552.0  | 995868.0  | 632640.0  | 111516.0 | 1740024.0 | 185676.0 | 110736.0  | 22044.0  | 318456.0  | 1181544.0 | 743376.0  | 133560.0 | 2058480.0  | 0.0       | 0.0      | 0.0      | 0.0       | 199659.0  | 114503.0  | 109243.0 | 423405.0  | 1381203.0 | 857879.0   | 242803.0 | 2481885.0  | 34588.0   | 0.0        | 0.0      | 34588.0    | 0.0      | 0.0       | 0.0      | 0.0       | 74785.0  | 0.0     | 0.0     | 74785.0  | 371157.0  | 600000.0  | 0.0     | 971157.0  | 594179.0  | 359796.0  | 0.0     | 953975.0  | 0.0    | 0.0        | 0.0    | 0.0        | 20000.0 | 0.0     | 0.0     | 20000.0 | 1094709.0  | 959796.0   | 0.0       | 2054505.0  | 0.0      | 0.0      | 0.0      | 0.0      | 103162.0  | 190000.0  | 0.0       | 293162.0  | 2579074.0  | 2007675.0  | 242803.0  | 4829552.0  | 1381203.0 | 1094709.0  | 103162.0 | 2579074.0  | 990360.0  | 577248.0  | 908304.0  | 103162.0 | 2579074.0  | 4753377.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                               | Y       | N      | N       | N      | Y      | P                                                                                                                | 9        | 1      | 1       | 1120176000 | 1151625600 | 2629385.0  | 0.0      | 2629385.0  | 9892092.0  | 4823137.0  | 0.0       | 14715229.0 | 2043993.0 | 19388607.0 | 928705.0  | 5501531.0 | 397667.0 | 6827903.0 | 543551.0 | 0.0       | 220798.0 | 764349.0  | 1472256.0 | 5501531.0 | 618465.0 | 7592252.0  | 146429.0  | 859683.0 | 27815.0  | 1033927.0 | 567538.0  | 3508419.0 | 172322.0 | 4248279.0 | 2186223.0 | 9869633.0  | 818602.0 | 12874458.0 | 286995.0  | 1023137.0  | 0.0      | 1310132.0  | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 300000.0  | 0.0     | 300000.0  | 0.0    | 2028885.0  | 0.0    | 2028885.0  | 0.0     | 0.0     | 0.0     | 0.0     | 286995.0   | 3352022.0  | 0.0       | 3639017.0  | 0.0      | 180526.0 | 0.0      | 180526.0 | 0.0       | 0.0       | 1281540.0 | 1281540.0 | 2473218.0  | 13402181.0 | 2100142.0 | 17975541.0 | 2171010.0 | 286995.0   | 15213.0  | 2473218.0  | 543937.0  | 1844084.0 | 69984.0   | 15213.0  | 2473218.0  | 3504809.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                           | Y       | N      | N       | N      | N      | NATIONAL HISTORICAL PUBLICATIONS AND RECORDS COMMISSION (NHPRC)GRANT - PRESERVE WASHINGTON STAR OVERSIZE PHOTOS. | 11       | 2      | 1       | 1128124800 | 1159574400 | 790234.0   | 36147.0  | 826381.0   | 34501765.0 | 0.0        | 0.0       | 34501765.0 | 1356724.0 | 36684870.0 | 378422.0  | 155571.0  | 0.0      | 533993.0  | 62074.0  | 14781.0   | 0.0      | 76855.0   | 440496.0  | 170352.0  | 0.0      | 610848.0   | 0.0       | 0.0      | 0.0      | 0.0       | 242059.0  | 50903.0   | 0.0      | 292962.0  | 682555.0  | 221255.0   | 0.0      | 903810.0   | 143826.0  | 34243328.0 | 631707.0 | 35018861.0 | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0    | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 143826.0   | 34243328.0 | 631707.0  | 35018861.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 0.0       | 826381.0   | 34464583.0 | 631707.0  | 35922671.0 | 613833.0  | 143826.0   | 32575.0  | 790234.0   | 0.0       | 84523.0   | 673136.0  | 32575.0  | 790234.0   | 581530.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                         | Y       | N      | N       | N      | Y      | P                                                                                                                | 10       | 2      | 1       | 1120176000 | 1151625600 | 853984.0   | 0.0      | 853984.0   | 2241591.0  | 3869500.0  | 3949450.0 | 10060541.0 | 50000.0   | 10964525.0 | 367140.0  | 555022.0  | 0.0      | 922162.0  | 136364.0 | 64304.0   | 0.0      | 200668.0  | 503504.0  | 619326.0  | 0.0      | 1122830.0  | 1531.0    | 8413.0   | 0.0      | 9944.0    | 757745.0  | 872195.0  | 0.0      | 1629940.0 | 1262780.0 | 1499934.0  | 0.0      | 2762714.0  | 67405.0   | 3482550.0  | 0.0      | 3549955.0  | 0.0      | 510000.0  | 0.0      | 510000.0  | 0.0      | 0.0     | 0.0     | 0.0      | 0.0       | 0.0       | 0.0     | 0.0       | 22000.0   | 0.0       | 50000.0 | 72000.0   | 0.0    | 1306239.0  | 0.0    | 1306239.0  | 0.0     | 0.0     | 0.0     | 0.0     | 89405.0    | 5298789.0  | 50000.0   | 5438194.0  | 0.0      | 8677.0   | 0.0      | 8677.0   | 0.0       | 1041000.0 | 0.0       | 1041000.0 | 1352185.0  | 7848400.0  | 50000.0   | 9250585.0  | 1260357.0 | 89405.0    | 2423.0   | 1352185.0  | 1429.0    | 141355.0  | 1206978.0 | 2423.0   | 1352185.0  | 853476.0   | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                        | Y       | N      | N       | N      | Y      | NATIONAL HISTORICAL PUBLICATIONS AND RECORDS COMMISSION GRANT PROGRAM                                            | 12       | 5      | 1       | 1120176000 | 1151625600 | 8242938.0  | 100300.0 | 8343238.0  | 5400254.0  | 43790899.0 | 2060983.0 | 51252136.0 | 1234575.0 | 60829949.0 | 1010015.0 | 2678399.0 | 0.0      | 3688414.0 | 323205.0 | 857087.0  | 0.0      | 1180292.0 | 1333220.0 | 3535486.0 | 0.0      | 4868706.0  | 2202409.0 | 543265.0 | 0.0      | 2745674.0 | 1224409.0 | 3316445.0 | 0.0      | 4540854.0 | 4760038.0 | 7395196.0  | 0.0      | 12155234.0 | 702877.0  | 29593002.0 | 945000.0 | 31240879.0 | 174468.0 | 2456231.0 | 202500.0 | 2833199.0 | 0.0      | 0.0     | 0.0     | 0.0      | 1460900.0 | 1800000.0 | 29850.0 | 3290750.0 | 1222692.0 | 0.0       | 57225.0 | 1279917.0 | 0.0    | 10000000.0 | 0.0    | 10000000.0 | 0.0     | 0.0     | 0.0     | 0.0     | 3560937.0  | 43849233.0 | 1234575.0 | 48644745.0 | 4677.0   | 66041.0  | 0.0      | 70718.0  | 0.0       | 0.0       | 0.0       | 0.0       | 8325652.0  | 51310470.0 | 1234575.0 | 60870697.0 | 4429546.0 | 3560937.0  | 182330.0 | 8172813.0  | 5103340.0 | 2711261.0 | 175882.0  | 182330.0 | 8172813.0  | 18089888.0 | 
```