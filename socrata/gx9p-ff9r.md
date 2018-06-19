# State Libraries Survey, FY 2014, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2014-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/gx9p-ff9r) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/gx9p-ff9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/gx9p-ff9r/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | gx9p-ff9r |
| Name | State Libraries Survey, FY 2014, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2014, revenue, expenditures |
| Created | 2016-12-20T15:34:10Z |
| Publication Date | 2016-12-20T17:04:44Z |

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
series e:gx9p-ff9r d:2013-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:obereg=8 t:asf_ac=Y t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=N t:mailaddr="P.O. BOX 110571" t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=1770 t:asf_sch=Y t:webaddr=WWW.LIBRARY.ALASKA.GOV t:asf_sp=Y t:rstatus=1 t:physzip=99801 t:fipsst=2 t:fiothsp="US DEPARTMENT OF COMMERCE BTOP - ALASKA OWL, LAURA BUSH" m:capitalc=0 m:capitalb=65726 m:capitala=134373 m:totaidb=1039594 m:totaida=1335947 m:siother=709911 m:aidsala=661270 m:capitald=200099 m:admexpt=11544 m:swexpt=0 m:oexpbenb=877742 m:oexpbena=58081 m:oexpbend=935823 m:oexpbenc=0 m:totincm=7831967 m:othincm=188039 m:aidlcd=0 m:aidlcc=0 m:totexpt=941340 m:fioth=1097477 m:aidlca=0 m:aidlcb=0 m:totexpd=7949475 m:totexpa=2038817 m:totexpc=14839 m:totexpb=5895819 m:sistlaop=4003800 m:aidmlsa=146560 m:aidmlsc=0 m:popu_st=736732 m:aidmlsb=101532 m:totoxstc=0 m:totoxstd=3403333 m:aidmlsd=248092 m:totopexc=14839 m:totopexd=5373835 m:totopexa=568497 m:aidothd=0 m:totopexb=4790499 m:aidothc=0 m:oexpothc=14839 m:aidothb=0 m:total_fi=2038817 m:oexpothd=1720864 m:aidotha=0 m:oexpotha=338221 m:oexpothb=1367804 m:aidplsc=0 m:aidplsd=0 m:total_si=5605111 m:totoxstb=3191930 m:totoxsta=211403 m:oexpcold=249638 m:lstainc=941340 m:aidplsa=0 m:oexpcolb=230765 m:grexpt=929796 m:aidplsb=0 m:oexpcolc=0 m:oexpsalb=2314188 m:othexpd=0 m:aidiplc=0 m:oexpcola=18873 m:oexpsalc=0 m:aidipld=1161536 m:siaidlib=891400 m:othexpb=0 m:aidipla=458140 m:oexpsala=153322 m:aidoila=69977 m:othexpc=0 m:aidiplb=703396 m:aidoilb=2928 m:aidsald=893008 m:totaidd=2375541 m:aidoilc=0 m:totaidc=0 m:oexpsald=2467510 m:aidoild=72905 m:aidsalb=231738 m:aidsalc=0 m:othexpa=0

series e:gx9p-ff9r d:2013-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:obereg=5 t:asf_ac=N t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailzip=36130 t:mailzip4=6000 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:asf_sp=N t:rstatus=1 t:physzip=36117 t:fipsst=1 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4628690 m:totaida=1028377 m:siother=0 m:aidsala=11676 m:capitald=0 m:admexpt=77440 m:swexpt=1310888 m:oexpbenb=439950 m:oexpbena=122824 m:oexpbend=562774 m:oexpbenc=0 m:totincm=9246222 m:othincm=36780 m:aidlcd=0 m:aidlcc=0 m:totexpt=2416705 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=9130503 m:totexpa=2416705 m:totexpc=0 m:totexpb=6713798 m:sistlaop=2164097 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=4849377 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=1969077 m:aidmlsd=0 m:totopexc=0 m:totopexd=3473436 m:totopexa=1388328 m:aidothd=0 m:totopexb=2085108 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=2416705 m:oexpothd=393603 m:aidotha=0 m:oexpotha=187945 m:oexpothb=205658 m:aidplsc=0 m:aidplsd=2206459 m:total_si=6792737 m:totoxstb=1548833 m:totoxsta=420244 m:oexpcold=1110756 m:lstainc=2416705 m:aidplsa=142604 m:oexpcolb=330617 m:grexpt=1028377 m:aidplsb=2063855 m:oexpcolc=0 m:oexpsalb=1108883 m:othexpd=0 m:aidiplc=0 m:oexpcola=780139 m:oexpsalc=0 m:aidipld=3438932 m:siaidlib=4628640 m:othexpb=0 m:aidipla=874097 m:oexpsala=297420 m:aidoila=0 m:othexpc=0 m:aidiplb=2564835 m:aidoilb=0 m:aidsald=11676 m:totaidd=5657067 m:aidoilc=0 m:totaidc=0 m:oexpsald=1406303 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:gx9p-ff9r d:2013-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:obereg=5 t:asf_ac=N t:physaddr="900 WEST CAPITOL, SUITE 100" t:phys_st=AR t:mailzip=72201 t:mailzip4=3108 t:asf_pub=Y t:mailaddr="900 WEST CAPITOL, SUITE 100" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=3108 t:asf_sch=N t:webaddr=WWW.LIBRARY.ARKANSAS.GOV t:asf_sp=N t:rstatus=1 t:physzip=72201 t:fipsst=5 t:fiothsp="LIBRARY OF CONGRESS CENTER FOR THE BOOK" m:capitalc=0 m:capitalb=9598 m:capitala=59757 m:totaidb=5700000 m:totaida=0 m:siother=185000 m:aidsala=0 m:capitald=69355 m:admexpt=40514 m:swexpt=1774691 m:oexpbenb=538675 m:oexpbena=171066 m:oexpbend=709741 m:oexpbenc=0 m:totincm=11222792 m:othincm=54 m:aidlcd=0 m:aidlcc=0 m:totexpt=1815205 m:fioth=900 m:aidlca=0 m:aidlcb=0 m:totexpd=11037058 m:totexpa=1877752 m:totexpc=54 m:totexpb=9159252 m:sistlaop=3459252 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2966369 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2647186 m:aidmlsd=0 m:totopexc=0 m:totopexd=5267649 m:totopexa=1817995 m:aidothd=166500 m:totopexb=3449654 m:aidothc=0 m:oexpothc=0 m:aidothb=166500 m:total_fi=1878486 m:oexpothd=1656897 m:aidotha=0 m:oexpotha=513228 m:oexpothb=1143669 m:aidplsc=0 m:aidplsd=0 m:total_si=9344252 m:totoxstb=2083235 m:totoxsta=563951 m:oexpcold=963566 m:lstainc=1877586 m:aidplsa=0 m:oexpcolb=222750 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:oexpsalb=1544560 m:othexpd=0 m:aidiplc=54 m:oexpcola=740816 m:oexpsalc=0 m:aidipld=5533554 m:siaidlib=5700000 m:othexpb=0 m:aidipla=0 m:oexpsala=392885 m:aidoila=0 m:othexpc=0 m:aidiplb=5533500 m:aidoilb=0 m:aidsald=0 m:totaidd=5700054 m:aidoilc=0 m:totaidc=54 m:oexpsald=1937445 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
```

## Meta Commands

```ls
metric m:lstainc p:integer l:"LSTA revenue" t:dataTypeName=money

metric m:fioth p:integer l:"Other federal revenue" t:dataTypeName=money

metric m:total_fi p:integer l:"Total federal revenue" t:dataTypeName=money

metric m:sistlaop p:integer l:"St rev STLA operation" t:dataTypeName=money

metric m:siaidlib p:integer l:"St rev aid to libraries" t:dataTypeName=money

metric m:siother p:integer l:"St rev other" t:dataTypeName=money

metric m:total_si p:integer l:"St rev TOTAL" t:dataTypeName=money

metric m:othincm p:integer l:"Other revenue" t:dataTypeName=money

metric m:totincm p:integer l:"Total revenue" t:dataTypeName=money

metric m:oexpsala p:integer l:"Salaries federal" t:dataTypeName=money

metric m:oexpsalb p:integer l:"Salaries state" t:dataTypeName=money

metric m:oexpsalc p:integer l:"Salaries other" t:dataTypeName=money

metric m:oexpsald p:integer l:"Salaries TOTAL" t:dataTypeName=money

metric m:oexpbena p:integer l:"Benefits federal" t:dataTypeName=money

metric m:oexpbenb p:integer l:"Benefits state" t:dataTypeName=money

metric m:oexpbenc p:integer l:"Benefits other" t:dataTypeName=money

metric m:oexpbend p:integer l:"Benefits TOTAL" t:dataTypeName=money

metric m:totoxsta p:integer l:"Staff Exp federal" t:dataTypeName=money

metric m:totoxstb p:integer l:"Staff Exp state" t:dataTypeName=money

metric m:totoxstc p:integer l:"Staff Exp other" t:dataTypeName=money

metric m:totoxstd p:integer l:"Staff Exp TOTAL" t:dataTypeName=money

metric m:oexpcola p:integer l:"Collection Exp federal" t:dataTypeName=money

metric m:oexpcolb p:integer l:"Collection Exp state" t:dataTypeName=money

metric m:oexpcolc p:integer l:"Collection Exp other" t:dataTypeName=money

metric m:oexpcold p:integer l:"Collection Exp TOTAL" t:dataTypeName=money

metric m:oexpotha p:integer l:"Other Op Exp federal" t:dataTypeName=money

metric m:oexpothb p:integer l:"Other Op Exp state" t:dataTypeName=money

metric m:oexpothc p:integer l:"Other Op Exp other" t:dataTypeName=money

metric m:oexpothd p:integer l:"Other Op Exp TOTAL" t:dataTypeName=money

metric m:totopexa p:integer l:"Tot Op Exp federal" t:dataTypeName=money

metric m:totopexb p:integer l:"Tot Op Exp state" t:dataTypeName=money

metric m:totopexc p:integer l:"Tot Op Exp other" t:dataTypeName=money

metric m:totopexd p:integer l:"Tot Op Exp TOTAL" t:dataTypeName=money

metric m:aidipla p:integer l:"Fin Asst to libraries federal" t:dataTypeName=money

metric m:aidiplb p:integer l:"Fin Asst to libraries state" t:dataTypeName=money

metric m:aidiplc p:integer l:"Fin Asst to libraries other" t:dataTypeName=money

metric m:aidipld p:integer l:"Fin Asst to libraries TOTAL" t:dataTypeName=money

metric m:aidplsa p:integer l:"Fin Asst to coops federal" t:dataTypeName=money

metric m:aidplsb p:integer l:"Fin Asst to coops state" t:dataTypeName=money

metric m:aidplsc p:integer l:"Fin Asst to coops other" t:dataTypeName=money

metric m:aidplsd p:integer l:"Fin Asst to coops TOTAL" t:dataTypeName=money

metric m:aidoila p:integer l:"Fin Asst to other federal" t:dataTypeName=money

metric m:aidoilb p:integer l:"Fin Asst to other state" t:dataTypeName=money

metric m:aidoilc p:integer l:"Fin Asst to other other" t:dataTypeName=money

metric m:aidoild p:integer l:"Fin Asst to other TOTAL" t:dataTypeName=money

metric m:aidmlsa p:integer l:"Fin Asst coops mult federal" t:dataTypeName=money

metric m:aidmlsb p:integer l:"Fin Asst coops mult state" t:dataTypeName=money

metric m:aidmlsc p:integer l:"Fin Asst coops mult other" t:dataTypeName=money

metric m:aidmlsd p:integer l:"Fin Asst coops mult TOTAL" t:dataTypeName=money

metric m:aidsala p:integer l:"Fin Asst libr statewide federal" t:dataTypeName=money

metric m:aidsalb p:integer l:"Fin Asst libr statewide state" t:dataTypeName=money

metric m:aidsalc p:integer l:"Fin Asst libr statewide other" t:dataTypeName=money

metric m:aidsald p:integer l:"Fin Asst libr statewide TOTAL" t:dataTypeName=money

metric m:aidlca p:integer l:"Fin Asst libr constr federal" t:dataTypeName=money

metric m:aidlcb p:integer l:"Fin Asst libr constr state" t:dataTypeName=money

metric m:aidlcc p:integer l:"Fin Asst libr constr other" t:dataTypeName=money

metric m:aidlcd p:integer l:"Fin Asst libr constr TOTAL" t:dataTypeName=money

metric m:aidotha p:integer l:"Fin Asst other federal" t:dataTypeName=money

metric m:aidothb p:integer l:"Fin Asst other state" t:dataTypeName=money

metric m:aidothc p:integer l:"Fin Asst other other" t:dataTypeName=money

metric m:aidothd p:integer l:"Fin Asst other TOTAL" t:dataTypeName=money

metric m:totaida p:integer l:"Fin Asst TOTAL federal" t:dataTypeName=money

metric m:totaidb p:integer l:"Fin Asst TOTAL state" t:dataTypeName=money

metric m:totaidc p:integer l:"Fin Asst TOTAL other" t:dataTypeName=money

metric m:totaidd p:integer l:"Fin Asst TOTAL TOTAL" t:dataTypeName=money

metric m:capitala p:integer l:"Capital outlay federal" t:dataTypeName=money

metric m:capitalb p:integer l:"Capital outlay state" t:dataTypeName=money

metric m:capitalc p:integer l:"Capital outlay other" t:dataTypeName=money

metric m:capitald p:integer l:"Capital outlay TOTAL" t:dataTypeName=money

metric m:othexpa p:integer l:"Other exp federal" t:dataTypeName=money

metric m:othexpb p:integer l:"Other exp state" t:dataTypeName=money

metric m:othexpc p:integer l:"Other exp other" t:dataTypeName=money

metric m:othexpd p:integer l:"Other exp TOTAL" t:dataTypeName=money

metric m:totexpa p:integer l:"Total exp federal" t:dataTypeName=money

metric m:totexpb p:integer l:"Total exp state" t:dataTypeName=money

metric m:totexpc p:integer l:"Total exp other" t:dataTypeName=money

metric m:totexpd p:integer l:"Total exp TOTAL" t:dataTypeName=money

metric m:swexpt p:integer l:"LSTA exp statewide svcs" t:dataTypeName=money

metric m:grexpt p:integer l:"LSTA exp grants" t:dataTypeName=money

metric m:admexpt p:integer l:"LSTA exp LSTA admin" t:dataTypeName=money

metric m:totexpt p:integer l:"LSTA exp by type/TOTAL" t:dataTypeName=money

metric m:popu_st p:integer l:Population t:dataTypeName=number

entity e:gx9p-ff9r l:"State Libraries Survey, FY 2014, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/gx9p-ff9r

property e:gx9p-ff9r t:meta.view v:id=gx9p-ff9r v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2014, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:gx9p-ff9r t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:gx9p-ff9r t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:gx9p-ff9r t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:gx9p-ff9r t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                                                  | physaddr                               | physcity    | phys_st | physzip | physzip4 | mailaddr                               | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                             | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                                                                              | fipsst | obereg | rstatus | fystart    | fyend      | lstainc  | fioth   | total_fi | sistlaop | siaidlib | siother | total_si | othincm  | totincm  | oexpsala | oexpsalb | oexpsalc | oexpsald | oexpbena | oexpbenb | oexpbenc | oexpbend | totoxsta | totoxstb | totoxstc | totoxstd | oexpcola | oexpcolb | oexpcolc | oexpcold | oexpotha | oexpothb | oexpothc | oexpothd | totopexa | totopexb | totopexc | totopexd | aidipla | aidiplb  | aidiplc | aidipld  | aidplsa | aidplsb | aidplsc | aidplsd | aidoila | aidoilb | aidoilc | aidoild | aidmlsa | aidmlsb | aidmlsc | aidmlsd | aidsala | aidsalb | aidsalc | aidsald | aidlca | aidlcb   | aidlcc  | aidlcd   | aidotha | aidothb | aidothc | aidothd | totaida | totaidb  | totaidc | totaidd  | capitala | capitalb | capitalc | capitald | othexpa | othexpb | othexpc | othexpd | totexpa  | totexpb  | totexpc | totexpd  | swexpt  | grexpt  | admexpt | totexpt  | popu_st  | 
| ========================================================================= | ====================================== | =========== | ======= | ======= | ======== | ====================================== | =========== | ======= | ======= | ======== | =================================================== | ======= | ====== | ======= | ====== | ====== | ==================================================================================================================================================================== | ====== | ====== | ======= | ========== | ========== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ====== | ======== | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======= | ======== | ======= | ======= | ======= | ======== | ======== | 
| ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS | 333 WILLOUGHBY AVENUE                  | JUNEAU      | AK      | 99801   | 1770     | P.O. BOX 110571                        | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.ALASKA.GOV                              | N       | Y      | Y       | Y      | Y      | US DEPARTMENT OF COMMERCE BTOP - ALASKA OWL, LAURA BUSH                                                                                                              | 2      | 8      | 1       | 1372636800 | 1404086400 | 941340   | 1097477 | 2038817  | 4003800  | 891400   | 709911  | 5605111  | 188039   | 7831967  | 153322   | 2314188  | 0        | 2467510  | 58081    | 877742   | 0        | 935823   | 211403   | 3191930  | 0        | 3403333  | 18873    | 230765   | 0        | 249638   | 338221   | 1367804  | 14839    | 1720864  | 568497   | 4790499  | 14839    | 5373835  | 458140  | 703396   | 0       | 1161536  | 0       | 0       | 0       | 0       | 69977   | 2928    | 0       | 72905   | 146560  | 101532  | 0       | 248092  | 661270  | 231738  | 0       | 893008  | 0      | 0        | 0       | 0        | 0       | 0       | 0       | 0       | 1335947 | 1039594  | 0       | 2375541  | 134373   | 65726    | 0        | 200099   | 0       | 0       | 0       | 0       | 2038817  | 5895819  | 14839   | 7949475  | 0       | 929796  | 11544   | 941340   | 736732   | 
| ALABAMA PUBLIC LIBRARY SERVICE                                            | 6030 MONTICELLO DRIVE                  | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                  | MONTGOMERY  | AL      | 36130   | 6000     | HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ | Y       | N      | N       | N      | Y      | P                                                                                                                                                                    | 1      | 5      | 1       | 1380585600 | 1412035200 | 2416705  | 0       | 2416705  | 2164097  | 4628640  | 0       | 6792737  | 36780    | 9246222  | 297420   | 1108883  | 0        | 1406303  | 122824   | 439950   | 0        | 562774   | 420244   | 1548833  | 0        | 1969077  | 780139   | 330617   | 0        | 1110756  | 187945   | 205658   | 0        | 393603   | 1388328  | 2085108  | 0        | 3473436  | 874097  | 2564835  | 0       | 3438932  | 142604  | 2063855 | 0       | 2206459 | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 11676   | 0       | 0       | 11676   | 0      | 0        | 0       | 0        | 0       | 0       | 0       | 0       | 1028377 | 4628690  | 0       | 5657067  | 0        | 0        | 0        | 0        | 0       | 0       | 0       | 0       | 2416705  | 6713798  | 0       | 9130503  | 1310888 | 1028377 | 77440   | 2416705  | 4849377  | 
| ARKANSAS STATE LIBRARY                                                    | 900 WEST CAPITOL, SUITE 100            | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100            | LITTLE ROCK | AR      | 72201   | 3108     | WWW.LIBRARY.ARKANSAS.GOV                            | Y       | N      | N       | N      | N      | LIBRARY OF CONGRESS CENTER FOR THE BOOK                                                                                                                              | 5      | 5      | 1       | 1372636800 | 1404086400 | 1877586  | 900     | 1878486  | 3459252  | 5700000  | 185000  | 9344252  | 54       | 11222792 | 392885   | 1544560  | 0        | 1937445  | 171066   | 538675   | 0        | 709741   | 563951   | 2083235  | 0        | 2647186  | 740816   | 222750   | 0        | 963566   | 513228   | 1143669  | 0        | 1656897  | 1817995  | 3449654  | 0        | 5267649  | 0       | 5533500  | 54      | 5533554  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0        | 0       | 0        | 0       | 166500  | 0       | 166500  | 0       | 5700000  | 54      | 5700054  | 59757    | 9598     | 0        | 69355    | 0       | 0       | 0       | 0       | 1877752  | 9159252  | 54      | 11037058 | 1774691 | 0       | 40514   | 1815205  | 2966369  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS                        | 1700 WEST WASHINGTON - SUITE 200       | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON, ROOM 200         | PHOENIX     | AZ      | 85007   | 2896     | WWW.AZLIBRARY.GOV                                   | Y       | N      | N       | N      | N      | NATIONAL DIGITAL NEWSPAPER PROGRAM; NATIONAL HISTORICAL PUBLICATIONS (SNAP); PROMOTION OF THE HUMANITIES FEDERAL/STATE PARTNERSHIP (AZ WOMEN: HIDING IN PLAIN SIGHT) | 4      | 6      | 1       | 1372636800 | 1404086400 | 3737670  | 196506  | 3934176  | 7246608  | 651400   | 97000   | 7995008  | 1600546  | 13529730 | 601595   | 3148679  | 495895   | 4246169  | 200983   | 1404340  | 255955   | 1861278  | 802578   | 4553019  | 751850   | 6107447  | 125478   | 127919   | 3829     | 257226   | 1573614  | 2476192  | 752493   | 4802299  | 2501670  | 7157130  | 1508172  | 11166972 | 1180895 | 550891   | 13784   | 1745570  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 85900    | 0       | 85900    | 0       | 0       | 0       | 0       | 1180895 | 636791   | 13784   | 1831470  | 45120    | 28253    | 95826    | 169199   | 0       | 0       | 0       | 0       | 3727685  | 7822174  | 1617782 | 13167641 | 2254641 | 1172616 | 75320   | 3502577  | 6731484  | 
| CALIFORNIA STATE LIBRARY                                                  | 900 N ST                               | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                        | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                                  | N       | N      | N       | N      | Y      | P                                                                                                                                                                    | 6      | 8      | 2       | 1372636800 | 1404086400 | 14309664 | 0       | 14309664 | 20127061 | 4700000  | 0       | 24827061 | 401916   | 39538641 | 2065054  | 5100442  | 257240   | 7422736  | 951885   | 2183872  | 107683   | 3243440  | 3016939  | 7284314  | 364923   | 10666176 | 463516   | 838804   | 0        | 1302320  | 1857362  | 12003943 | 36993    | 13898298 | 5337817  | 20127061 | 401916   | 25866794 | 1780828 | 2820000  | 0       | 4600828  | 0       | 1880000 | 0       | 1880000 | 480270  | 0       | 0       | 480270  | 3457335 | 0       | 0       | 3457335 | 3253414 | 0       | 0       | 3253414 | 0      | 0        | 0       | 0        | 0       | 0       | 0       | 0       | 8971847 | 4700000  | 0       | 13671847 | 0        | 0        | 0        | 0        | 0       | 0       | 0       | 0       | 14309664 | 24827061 | 401916  | 39538641 | 5089304 | 8971847 | 248513  | 14309664 | 38802500 | 
| COLORADO STATE LIBRARY                                                    | 201 EAST COLFAX AVENUE, #309           | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX AVENUE, ROOM 309       | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/CDELIB/                         | Y       | Y      | Y       | N      | Y      | IMLS- NATIONAL LEADERSHIP GRANTSPELL: SUPPORTING PARENTS IN EARLY LITERACY THROUGH LIBRARIES                                                                         | 8      | 7      | 1       | 1372636800 | 1404086400 | 2749905  | 34029   | 2783934  | 1438744  | 2934115  | 350000  | 4722859  | 240942   | 7747735  | 1303465  | 743408   | 145668   | 2192541  | 413082   | 215888   | 47906    | 676876   | 1716547  | 959296   | 193574   | 2869417  | 113197   | 18028    | 0        | 131225   | 686405   | 461420   | 47368    | 1195193  | 2516149  | 1438744  | 240942   | 4195835  | 239267  | 1274962  | 0       | 1514229  | 0       | 0       | 0       | 0       | 15182   | 94115   | 0       | 109297  | 0       | 1000000 | 0       | 1000000 | 0       | 0       | 0       | 0       | 0      | 0        | 0       | 0        | 13336   | 565038  | 0       | 578374  | 267785  | 2934115  | 0       | 3201900  | 0        | 0        | 0        | 0        | 0       | 350000  | 0       | 350000  | 2783934  | 4722859  | 240942  | 7747735  | 2372124 | 267785  | 109996  | 2749905  | 5355866  | 
| CONNECTICUT STATE LIBRARY                                                 | 231 CAPITOL AVENUE                     | HARTFORD    | CT      | 6160    | 1537     | 231 CAPITOL AVENUE                     | HARTFORD    | CT      | 6106    | 1537     | WWW.CTSTATELIBRARY.ORG                              | Y       | N      | N       | N      | Y      | SNAP GRANT - NAT'L ARCHIVESCONSERVATION CONNECTION - IMLSDIGITAL NEWSPAPER PROJECT - NAT'L ENDOWMENT FOR THE HUMANITIES                                              | 9      | 1      | 2       | 1372636800 | 1404086400 | 2038047  | 73655   | 2111702  | 10267651 | 4372012  | 0       | 14639663 | 1124915  | 17876280 | 845368   | 4875091  | 157463   | 5877922  | 689991   | 0        | 111210   | 801201   | 1535359  | 4875091  | 268673   | 6679123  | 84422    | 786573   | 0        | 870995   | 486815   | 4463990  | 72357    | 5023162  | 2106596  | 10125654 | 341030   | 12573280 | 52262   | 1203569  | 0       | 1255831  | 0       | 0       | 0       | 0       | 4670    | 0       | 0       | 4670    | 0       | 332500  | 0       | 332500  | 0       | 0       | 0       | 0       | 0      | 2835943  | 0       | 2835943  | 0       | 0       | 0       | 0       | 56932   | 4372012  | 0       | 4428944  | 0        | 204766   | 0        | 204766   | 0       | 0       | 0       | 0       | 2163528  | 14702432 | 341030  | 17206990 | 1838886 | 56932   | 78992   | 1974810  | 3596677  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                                       | 901 G STREET, N.W.                     | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                     | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                                   | Y       | N      | N       | N      | N      | 41 GED/14 GRANT AND ARRA (STIMULUS)                                                                                                                                  | 11     | 2      | 1       | 1380585600 | 1412035200 | 903472   | 9199    | 912671   | 53466083 | 0        | 0       | 53466083 | 283368   | 54662122 | 200074   | 185208   | 0        | 385282   | 43034    | 22503    | 0        | 65537    | 243108   | 207711   | 0        | 450819   | 0        | 0        | 0        | 0        | 633607   | 21280    | 0        | 654887   | 876715   | 228991   | 0        | 1105706  | 35956   | 52866231 | 407916  | 53310103 | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0        | 0       | 0        | 0       | 0       | 0       | 0       | 35956   | 52866231 | 407916  | 53310103 | 0        | 0        | 0        | 0        | 0       | 0       | 0       | 0       | 912671   | 53095222 | 407916  | 54415809 | 853236  | 35956   | 14280   | 903472   | 658893   | 
| DELAWARE DIVISION OF LIBRARIES                                            | 121 MARTIN LUTHER KING JR. BLVD. NORTH | DOVER       | DE      | 19901   | 7430     | 121 MARTIN LUTHER KING JR. BLVD. NORTH | DOVER       | DE      | 19901   | 7430     | LIBRARIES.DELAWARE.GOV                              | Y       | N      | N       | N      | N      | BTOP GRANT                                                                                                                                                           | 10     | 2      | 1       | 1372636800 | 1404086400 | 668283   | 325720  | 994003   | 4346266  | 4296900  | 571089  | 9214255  | 10208258 | 20416516 | 320096   | 396941   | 0        | 717037   | 163304   | 190177   | 0        | 353481   | 483400   | 587118   | 0        | 1070518  | 0        | 231829   | 0        | 231829   | 292777   | 281197   | 70685    | 644659   | 776177   | 1100144  | 70685    | 1947006  | 0       | 3867240  | 0       | 3867240  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0      | 0        | 7211562 | 7211562  | 0       | 0       | 0       | 0       | 0       | 3867240  | 7211562 | 11078802 | 5197     | 1076524  | 4229     | 1085950  | 180620  | 2339425 | 20579   | 2540624 | 961994   | 8383333  | 7307055 | 16652382 | 642665  | 0       | 26777   | 669442   | 935614   | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS                              | 98 NORTH WASHINGTON STREET, SUITE 401  | BOSTON      | MA      | 2114    | 1933     | 98 NORTH WASHINGTON STREET, SUITE 401  | BOSTON      | MA      | 2114    | 1933     | MBLC.STATE.MA.US                                    | Y       | N      | N       | N      | Y      | P                                                                                                                                                                    | 25     | 1      | 1       | 1372636800 | 1404086400 | 3062100  | 0       | 3062100  | 1012047  | 41229172 | 0       | 42241219 | 0        | 45303319 | 721554   | 755220   | 0        | 1476774  | 198950   | 10991    | 0        | 209941   | 920504   | 766211   | 0        | 1686715  | 21354    | 0        | 0        | 21354    | 335789   | 188505   | 0        | 524294   | 1277647  | 954716   | 0        | 2232363  | 266223  | 6823657  | 0       | 7089880  | 0       | 0       | 0       | 0       | 36332   | 0       | 0       | 36332   | 643674  | 4826040 | 0       | 5469714 | 26600   | 9579475 | 0       | 9606075 | 0      | 20000000 | 0       | 20000000 | 0       | 0       | 0       | 0       | 972829  | 41229172 | 0       | 42202001 | 0        | 0        | 0        | 0        | 811624  | 0       | 0       | 811624  | 3062100  | 42183888 | 0       | 45245988 | 1966787 | 972829  | 122484  | 3062100  | 6745408  | 
```