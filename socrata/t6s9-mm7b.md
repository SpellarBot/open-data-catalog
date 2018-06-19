# State Libraries Survey, FY 2008, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2008-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/t6s9-mm7b) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/t6s9-mm7b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/t6s9-mm7b/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | t6s9-mm7b |
| Name | State Libraries Survey, FY 2008, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2008, revenue, expenditures |
| Created | 2016-12-20T15:29:24Z |
| Publication Date | 2016-12-20T17:04:39Z |

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
series e:t6s9-mm7b d:2007-07-01T00:00:00.000Z t:physcity="BATON ROUGE" t:mailcity="BATON ROUGE" t:asf_lc=Y t:mail_st=LA t:pub_fips=22 t:obereg=8 t:asf_ac=Y t:physaddr="701 NORTH FOURTH STREET" t:phys_st=LA t:mailzip=70821 t:mailzip4=131 t:asf_pub=Y t:mailaddr="P.O. BOX 131" t:stlaname="STATE LIBRARY OF LOUISIANA" t:physzip4=5232 t:asf_sch=Y t:webaddr=WWW.STATE.LIB.LA.US t:asf_sp=N t:rstatus=1 t:physzip=70802 t:fiothsp="LIBRARY OF CONGRESS PHOTO ORDERS CONNECTING TO COLLECTIONS GRANT FROM IMLS" m:capitalc=0 m:capitalb=4024 m:capitala=0 m:totaidb=891400 m:siother=79583 m:totaida=888219 m:aidsala=596914 m:capitald=4024 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=843670 m:oexpbena=3280 m:oexpbend=846950 m:oexpbenc=0 m:totincm=5264637 m:othincm=72192 m:aidlcd=0 m:aidlcc=0 m:totexpu=888219 m:totexpt=888219 m:fioth=44503 m:aidlca=0 m:aidlcb=0 m:totexpd=5137923 m:totexpa=895548 m:totexpc=83479 m:totexpb=4158896 m:sistlaop=3263472 m:aidmlsa=98649 m:aidmlsc=0 m:popu_st=686293 m:aidmlsb=45698 m:totoxstc=0 m:totoxstd=2465439 m:aidmlsd=144347 m:serllxu=356365 m:totopexc=0 m:totopexd=3270801 m:totopexa=7329 m:aidothd=0 m:totopexb=3263472 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=932716 m:oexpothd=625556 m:aidotha=0 m:oexpotha=0 m:oexpothb=625556 m:aidplsc=28479 m:aidplsd=85152 m:total_si=4259729 m:totoxstb=2458110 m:totoxsta=7329 m:oexpcold=179806 m:lstainc=888213 m:aidplsa=56673 m:oexpcolb=179806 m:grexpt=888219 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=237828 m:oexpsalb=1614440 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=786333 m:siaidlib=916674 m:othexpb=0 m:aidipla=135983 m:oexpsala=4049 m:aidoila=0 m:othexpc=0 m:aidiplb=650350 m:aidoilb=9530 m:aidsald=837736 m:totaidd=1863098 m:aidoilc=0 m:totaidc=83479 m:techxu=294026 m:oexpsald=1618489 m:aidoild=9530 m:aidsalb=185822 m:aidsalc=55000 m:othexpa=0

series e:t6s9-mm7b d:2007-07-01T00:00:00.000Z t:physcity=BOSTON t:mailcity=BOSTON t:asf_lc=N t:mail_st=MA t:pub_fips=25 t:obereg=5 t:asf_ac=N t:physaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:phys_st=MA t:mailzip=2114 t:mailzip4=1933 t:asf_pub=Y t:mailaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:stlaname="MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS" t:physzip4=1933 t:asf_sch=N t:webaddr=MBLC.STATE.MA.US t:asf_sp=N t:rstatus=1 t:physzip=2114 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=9088986 m:siother=3638378 m:totaida=1448862 m:aidsala=518024 m:capitald=0 m:admexpt=67731 m:swexpt=1086342 m:admexpu=67731 m:oexpbenb=740698 m:oexpbena=0 m:oexpbend=753176 m:oexpbenc=12478 m:totincm=14993127 m:othincm=494572 m:aidlcd=848378 m:aidlcc=0 m:totexpu=2602935 m:totexpt=2602935 m:fioth=0 m:aidlca=0 m:aidlcb=848378 m:totexpd=14993127 m:totexpa=2602935 m:totexpc=494572 m:totexpb=11895620 m:sistlaop=2806634 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=4661900 m:aidmlsb=0 m:totoxstc=58485 m:totoxstd=2862344 m:aidmlsd=0 m:serllxu=844307 m:totopexc=58485 m:totopexd=4019192 m:totopexa=1154073 m:aidothd=0 m:totopexb=2806634 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=2602935 m:oexpothd=1137609 m:aidotha=0 m:oexpotha=1134834 m:oexpothb=2775 m:aidplsc=0 m:aidplsd=76322 m:total_si=11895620 m:totoxstb=2803859 m:totoxsta=0 m:oexpcold=19239 m:lstainc=2602935 m:aidplsa=76322 m:oexpcolb=0 m:grexpt=1448862 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=180512 m:oexpsalb=2063161 m:othexpd=0 m:aidiplc=436087 m:oexpcola=19239 m:oexpsalc=46007 m:aidipld=6741211 m:siaidlib=5450608 m:othexpb=0 m:aidipla=854516 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=5450608 m:aidoilb=0 m:aidsald=3308024 m:totaidd=10973935 m:aidoilc=0 m:totaidc=436087 m:techxu=1510385 m:oexpsald=2109168 m:aidoild=0 m:aidsalb=2790000 m:aidsalc=0 m:othexpa=0

series e:t6s9-mm7b d:2007-07-01T00:00:00.000Z t:physcity=BALTIMORE t:mailcity=BALTIMORE t:asf_lc=N t:mail_st=MD t:pub_fips=24 t:obereg=5 t:asf_ac=N t:physaddr="200 WEST BALTIMORE STREET" t:phys_st=MD t:mailzip=21201 t:mailzip4=2595 t:asf_pub=Y t:mailaddr="200 WEST BALTIMORE STREET" t:stlaname="DIVISION OF LIBRARY DEVELOPMENT AND SERVICES" t:physzip4=2595 t:asf_sch=N t:webaddr=www.marylandpublicschools.org/MSDE/divisions/library t:asf_sp=N t:rstatus=1 t:physzip=21201 t:fiothsp="LIBRARY OF CONGRESS CENTER FOR THE BOOK" m:capitalc=0 m:capitalb=0 m:capitala=165718 m:totaidb=5025000 m:siother=250857 m:totaida=0 m:aidsala=0 m:capitald=165718 m:admexpt=70873 m:swexpt=1746375 m:admexpu=70873 m:oexpbenb=432610 m:oexpbena=120191 m:oexpbend=552801 m:oexpbenc=0 m:totincm=9992950 m:othincm=9011 m:aidlcd=0 m:aidlcc=0 m:totexpu=1817248 m:totexpt=1817248 m:fioth=1700 m:aidlca=0 m:aidlcb=0 m:totexpd=9960461 m:totexpa=1817248 m:totexpc=86904 m:totexpb=8056309 m:sistlaop=3031309 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2855390 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2324714 m:aidmlsd=0 m:serllxu=719988 m:totopexc=86904 m:totopexd=4769743 m:totopexa=1651530 m:aidothd=0 m:totopexb=3031309 m:aidothc=0 m:oexpothc=86904 m:aidothb=0 m:total_fi=1801773 m:oexpothd=2070434 m:aidotha=0 m:oexpotha=1066670 m:oexpothb=916860 m:aidplsc=0 m:aidplsd=0 m:total_si=8182166 m:totoxstb=1901146 m:totoxsta=423568 m:oexpcold=374595 m:lstainc=1800073 m:aidplsa=0 m:oexpcolb=213303 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=216114 m:oexpsalb=1468536 m:othexpd=0 m:aidiplc=0 m:oexpcola=161292 m:oexpsalc=0 m:aidipld=5025000 m:siaidlib=4900000 m:othexpb=0 m:aidipla=0 m:oexpsala=303377 m:aidoila=0 m:othexpc=0 m:aidiplb=5025000 m:aidoilb=0 m:aidsald=0 m:totaidd=5025000 m:aidoilc=0 m:totaidc=0 m:techxu=810273 m:oexpsald=1771913 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:t6s9-mm7b l:"State Libraries Survey, FY 2008, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/t6s9-mm7b

property e:t6s9-mm7b t:meta.view v:id=t6s9-mm7b v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2008, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:t6s9-mm7b t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:t6s9-mm7b t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:t6s9-mm7b t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:t6s9-mm7b t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                     | physaddr                              | physcity       | phys_st | physzip | physzip4 | mailaddr                              | mailcity       | mail_st | mailzip | mailzip4 | webaddr                                                                       | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                                  | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc   | aidipld    | aidplsa  | aidplsb   | aidplsc | aidplsd   | aidoila  | aidoilb | aidoilc | aidoild  | aidmlsa  | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca   | aidlcb    | aidlcc | aidlcd    | aidotha | aidothb | aidothc | aidothd | totaida   | totaidb    | totaidc   | totaidd    | capitala | capitalb | capitalc | capitald | othexpa   | othexpb  | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt    | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ============================================ | ===================================== | ============== | ======= | ======= | ======== | ===================================== | ============== | ======= | ======= | ======== | ============================================================================= | ======= | ====== | ======= | ====== | ====== | ======================================================================================================================== | ======== | ====== | ======= | ========== | ========== | ========== | ======== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ========= | ========== | ========= | ========== | ======== | ========= | ======= | ========= | ======== | ======= | ======= | ======== | ======== | ========= | ======= | ========= | ========= | ========= | ======= | ========= | ======== | ========= | ====== | ========= | ======= | ======= | ======= | ======= | ========= | ========== | ========= | ========== | ======== | ======== | ======== | ======== | ========= | ======== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========= | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| STATE LIBRARY OF LOUISIANA                   | 701 NORTH FOURTH STREET               | BATON ROUGE    | LA      | 70802   | 5232     | P.O. BOX 131                          | BATON ROUGE    | LA      | 70821   | 131      | WWW.STATE.LIB.LA.US                                                           | Y       | Y      | Y       | N      | Y      | LIBRARY OF CONGRESS PHOTO ORDERS CONNECTING TO COLLECTIONS GRANT FROM IMLS                                               | 22       | 8      | 1       | 1183248000 | 1214784000 | 888213.0   | 44503.0  | 932716.0   | 3263472.0  | 916674.0   | 79583.0   | 4259729.0  | 72192.0   | 5264637.0  | 4049.0    | 1614440.0 | 0.0      | 1618489.0 | 3280.0   | 843670.0  | 0.0      | 846950.0  | 7329.0    | 2458110.0 | 0.0      | 2465439.0  | 0.0      | 179806.0  | 0.0      | 179806.0  | 0.0       | 625556.0  | 0.0      | 625556.0  | 7329.0    | 3263472.0  | 0.0      | 3270801.0  | 135983.0  | 650350.0   | 0.0       | 786333.0   | 56673.0  | 0.0       | 28479.0 | 85152.0   | 0.0      | 9530.0  | 0.0     | 9530.0   | 98649.0  | 45698.0   | 0.0     | 144347.0  | 596914.0  | 185822.0  | 55000.0 | 837736.0  | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 888219.0  | 891400.0   | 83479.0   | 1863098.0  | 0.0      | 4024.0   | 0.0      | 4024.0   | 0.0       | 0.0      | 0.0       | 0.0       | 895548.0   | 4158896.0  | 83479.0   | 5137923.0  | 0.0       | 888219.0  | 0.0      | 888219.0   | 294026.0  | 237828.0  | 356365.0  | 0.0      | 888219.0   | 686293.0   | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | MBLC.STATE.MA.US                                                              | Y       | N      | N       | N      | N      | P                                                                                                                        | 25       | 5      | 1       | 1183248000 | 1214784000 | 2602935.0  | 0.0      | 2602935.0  | 2806634.0  | 5450608.0  | 3638378.0 | 11895620.0 | 494572.0  | 14993127.0 | 0.0       | 2063161.0 | 46007.0  | 2109168.0 | 0.0      | 740698.0  | 12478.0  | 753176.0  | 0.0       | 2803859.0 | 58485.0  | 2862344.0  | 19239.0  | 0.0       | 0.0      | 19239.0   | 1134834.0 | 2775.0    | 0.0      | 1137609.0 | 1154073.0 | 2806634.0  | 58485.0  | 4019192.0  | 854516.0  | 5450608.0  | 436087.0  | 6741211.0  | 76322.0  | 0.0       | 0.0     | 76322.0   | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 518024.0  | 2790000.0 | 0.0     | 3308024.0 | 0.0      | 848378.0  | 0.0    | 848378.0  | 0.0     | 0.0     | 0.0     | 0.0     | 1448862.0 | 9088986.0  | 436087.0  | 10973935.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 2602935.0  | 11895620.0 | 494572.0  | 14993127.0 | 1086342.0 | 1448862.0 | 67731.0  | 2602935.0  | 1510385.0 | 180512.0  | 844307.0  | 67731.0  | 2602935.0  | 4661900.0  | 
| DIVISION OF LIBRARY DEVELOPMENT AND SERVICES | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | www.marylandpublicschools.org/MSDE/divisions/library                          | Y       | N      | N       | N      | N      | LIBRARY OF CONGRESS CENTER FOR THE BOOK                                                                                  | 24       | 5      | 1       | 1183248000 | 1214784000 | 1800073.0  | 1700.0   | 1801773.0  | 3031309.0  | 4900000.0  | 250857.0  | 8182166.0  | 9011.0    | 9992950.0  | 303377.0  | 1468536.0 | 0.0      | 1771913.0 | 120191.0 | 432610.0  | 0.0      | 552801.0  | 423568.0  | 1901146.0 | 0.0      | 2324714.0  | 161292.0 | 213303.0  | 0.0      | 374595.0  | 1066670.0 | 916860.0  | 86904.0  | 2070434.0 | 1651530.0 | 3031309.0  | 86904.0  | 4769743.0  | 0.0       | 5025000.0  | 0.0       | 5025000.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 0.0       | 5025000.0  | 0.0       | 5025000.0  | 165718.0 | 0.0      | 0.0      | 165718.0 | 0.0       | 0.0      | 0.0       | 0.0       | 1817248.0  | 8056309.0  | 86904.0   | 9960461.0  | 1746375.0 | 0.0       | 70873.0  | 1817248.0  | 810273.0  | 216114.0  | 719988.0  | 70873.0  | 1817248.0  | 2855390.0  | 
| MAINE STATE LIBRARY                          | 230 STATE STREET                      | AUGUSTA        | ME      | 4333    | 64       | 64 STATE HOUSE STATION                | AUGUSTA        | ME      | 4333    | 64       | www.maine.gov/msl/                                                            | Y       | N      | N       | N      | N      | LIBRARY OF CONGRESS PERSISTENT DIGITAL ARCHIVES                                                                          | 23       | 6      | 1       | 1183248000 | 1214784000 | 3337188.0  | 40000.0  | 3377188.0  | 6785300.0  | 651400.0   | 97000.0   | 7533700.0  | 305563.0  | 11216451.0 | 385853.0  | 4036597.0 | 56271.0  | 4478721.0 | 87074.0  | 1463913.0 | 27860.0  | 1578847.0 | 472927.0  | 5500510.0 | 84131.0  | 6057568.0  | 743482.0 | 225972.0  | 2501.0   | 971955.0  | 45981.0   | 1036822.0 | 209906.0 | 1292709.0 | 1262390.0 | 6763304.0  | 296538.0 | 8322232.0  | 564099.0  | 729920.0   | 0.0       | 1294019.0  | 111953.0 | 0.0       | 0.0     | 111953.0  | 95100.0  | 0.0     | 0.0     | 95100.0  | 0.0      | 0.0       | 0.0     | 0.0       | 87846.0   | 0.0       | 0.0     | 87846.0   | 0.0      | 0.0       | 0.0    | 0.0       | 70074.0 | 0.0     | 0.0     | 70074.0 | 929072.0  | 729920.0   | 0.0       | 1658992.0  | 0.0      | 0.0      | 0.0      | 0.0      | 1029725.0 | 15132.0  | 128303.0  | 1173160.0 | 3221187.0  | 7508356.0  | 424841.0  | 11154384.0 | 2148830.0 | 925391.0  | 127445.0 | 3201666.0  | 1992710.0 | 86882.0   | 994629.0  | 127445.0 | 3201666.0  | 6500180.0  | 
| LIBRARY OF MICHIGAN                          | 702 WEST KALAMAZOO STREET             | LANSING        | MI      | 48909   | 7507     | P.O. BOX 30007                        | LANSING        | MI      | 48909   | 7507     | www.michigan.gov/libraryofmichigan                                            | Y       | N      | N       | N      | Y      | P                                                                                                                        | 26       | 8      | 2       | 1191196800 | 1222732800 | 16431277.0 | 0.0      | 16431277.0 | 16430224.0 | 33766000.0 | 0.0       | 50196224.0 | 419399.0  | 67046900.0 | 2384296.0 | 6339954.0 | 287142.0 | 9011392.0 | 837769.0 | 2290021.0 | 107684.0 | 3235474.0 | 3222065.0 | 8629975.0 | 394826.0 | 12246866.0 | 404835.0 | 1132906.0 | 0.0      | 1537741.0 | 3235885.0 | 6667343.0 | 24573.0  | 9927801.0 | 6862785.0 | 16430224.0 | 419399.0 | 23712408.0 | 3152085.0 | 31040000.0 | 0.0       | 34192085.0 | 0.0      | 0.0       | 0.0     | 0.0       | 200715.0 | 0.0     | 0.0     | 200715.0 | 363237.0 | 2726000.0 | 0.0     | 3089237.0 | 5927343.0 | 0.0       | 0.0     | 5927343.0 | 0.0      | 0.0       | 0.0    | 0.0       | 0.0     | 0.0     | 0.0     | 0.0     | 9643380.0 | 33766000.0 | 0.0       | 43409380.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 16506165.0 | 50196224.0 | 419399.0  | 67121788.0 | 6665772.0 | 9643380.0 | 122125.0 | 16431277.0 | 8554115.0 | 2979724.0 | 4775313.0 | 122125.0 | 16431277.0 | 36756666.0 | 
| STATE LIBRARY SERVICES                       | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4266     | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4035     | http://education.state.mn.us/MDE/Learning_Support/Library_Services/index.html | N       | N      | N       | N      | Y      | P                                                                                                                        | 27       | 7      | 1       | 1183248000 | 1214784000 | 2650213.0  | 0.0      | 2650213.0  | 884847.0   | 1362053.0  | 200000.0  | 2446900.0  | 203984.0  | 5301097.0  | 1131007.0 | 636439.0  | 62484.0  | 1829930.0 | 241052.0 | 131427.0  | 14559.0  | 387038.0  | 1372059.0 | 767866.0  | 77043.0  | 2216968.0  | 20727.0  | 0.0       | 0.0      | 20727.0   | 186771.0  | 115955.0  | 126941.0 | 429667.0  | 1579557.0 | 883821.0   | 203984.0 | 2667362.0  | 158362.0  | 0.0        | 0.0       | 158362.0   | 0.0      | 0.0       | 0.0     | 0.0       | 55718.0  | 0.0     | 0.0     | 55718.0  | 155000.0 | 1000000.0 | 0.0     | 1155000.0 | 622597.0  | 362053.0  | 0.0     | 984650.0  | 0.0      | 0.0       | 0.0    | 0.0       | 50075.0 | 0.0     | 0.0     | 50075.0 | 1041752.0 | 1362053.0  | 0.0       | 2403805.0  | 28904.0  | 1026.0   | 0.0      | 29930.0  | 0.0       | 200000.0 | 0.0       | 200000.0  | 2650213.0  | 2446900.0  | 203984.0  | 5301097.0  | 1502453.0 | 1041752.0 | 106008.0 | 2650213.0  | 1059722.0 | 664936.0  | 819547.0  | 106008.0 | 2650213.0  | 4939456.0  | 
| MISSOURI STATE LIBRARY                       | 600 WEST MAIN STREET, 2ND FLOOR       | JEFFERSON CITY | MO      | 65101   | 1592     | PO BOX 387                            | JEFFERSON CITY | MO      | 65102   | 387      | WWW.SOS.MO.GOV/LIBRARY/                                                       | Y       | N      | N       | N      | Y      | P                                                                                                                        | 29       | 1      | 1       | 1183248000 | 1214784000 | 2154648.0  | 0.0      | 2154648.0  | 11407809.0 | 5423137.0  | 0.0       | 16830946.0 | 1721921.0 | 20707515.0 | 842145.0  | 6173239.0 | 370686.0 | 7386070.0 | 487296.0 | 0.0       | 197268.0 | 684564.0  | 1329441.0 | 6173239.0 | 567954.0 | 8070634.0  | 48769.0  | 1201954.0 | 1060.0   | 1251783.0 | 434215.0  | 3949674.0 | 140031.0 | 4523920.0 | 1812425.0 | 11324867.0 | 709045.0 | 13846337.0 | 119228.0  | 1573137.0  | 0.0       | 1692365.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 350000.0  | 0.0     | 350000.0  | 0.0      | 2235855.0 | 0.0    | 2235855.0 | 0.0     | 0.0     | 0.0     | 0.0     | 119228.0  | 4158992.0  | 0.0       | 4278220.0  | 0.0      | 141757.0 | 0.0      | 141757.0 | 0.0       | 0.0      | 1513807.0 | 1513807.0 | 1931653.0  | 15625616.0 | 2222852.0 | 19780121.0 | 1790517.0 | 119228.0  | 21908.0  | 1931653.0  | 607381.0  | 573481.0  | 728883.0  | 21908.0  | 1931653.0  | 3501252.0  | 
| MISSISSIPPI LIBRARY COMMISSION               | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | WWW.MLC.LIB.MS.US                                                             | N       | N      | N       | N      | N      | NATIONAL ENDOWMENT FOR THE HUMANITIES - RECOVERY OF THE PEABODY COLLECTION AND LIBRARY SERVICES & CONSTRUCTION ACT GRANT | 28       | 2      | 1       | 1183248000 | 1214784000 | 838393.0   | 120353.0 | 958746.0   | 45239346.0 | 0.0        | 0.0       | 45239346.0 | 1291983.0 | 47490075.0 | 335282.0  | 212554.0  | 0.0      | 547836.0  | 55669.0  | 27136.0   | 0.0      | 82805.0   | 390951.0  | 239690.0  | 0.0      | 630641.0   | 0.0      | 0.0       | 0.0      | 0.0       | 194847.0  | 33708.0   | 0.0      | 228555.0  | 585798.0  | 273398.0   | 0.0      | 859196.0   | 227218.0  | 44289230.0 | 1072617.0 | 45589065.0 | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0     | 0.0       | 110232.0 | 0.0       | 0.0    | 110232.0  | 0.0     | 0.0     | 0.0     | 0.0     | 337450.0  | 44289230.0 | 1072617.0 | 45699297.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 0.0       | 923248.0   | 44562628.0 | 1072617.0 | 46558493.0 | 585798.0  | 207833.0  | 0.0      | 793631.0   | 49212.0   | 101150.0  | 643269.0  | 0.0      | 793631.0   | 591833.0   | 
| MONTANA STATE LIBRARY                        | 1515 EAST 6TH AVENUE                  | HELENA         | MT      | 59620   | 1800     | PO BOX 201800                         | HELENA         | MT      | 59620   | 1800     | msl.mt.gov                                                                    | Y       | Y      | N       | Y      | Y      | COLLABORATIVE COLLECTION PRESERVATION GRANT                                                                              | 30       | 2      | 1       | 1183248000 | 1214784000 | 1227817.0  | 40000.0  | 1267817.0  | 2444098.0  | 4302550.0  | 1462231.0 | 8208879.0  | 1154024.0 | 10630720.0 | 435834.0  | 453388.0  | 0.0      | 889222.0  | 155203.0 | 190906.0  | 0.0      | 346109.0  | 591037.0  | 644294.0  | 0.0      | 1235331.0  | 1093.0   | 9693.0    | 0.0      | 10786.0   | 611948.0  | 3207878.0 | 0.0      | 3819826.0 | 1204078.0 | 3861865.0  | 0.0      | 5065943.0  | 4750.0    | 3155542.0  | 0.0       | 3160292.0  | 0.0      | 161089.0  | 0.0     | 161089.0  | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 22000.0   | 0.0       | 0.0     | 22000.0   | 0.0      | 4153305.0 | 0.0    | 4153305.0 | 42592.0 | 16814.0 | 0.0     | 59406.0 | 69342.0   | 7486750.0  | 0.0       | 7556092.0  | 0.0      | 19164.0  | 0.0      | 19164.0  | 0.0       | 0.0      | 14390.0   | 14390.0   | 1273420.0  | 11367779.0 | 14390.0   | 12655589.0 | 1200595.0 | 69342.0   | 3483.0   | 1273420.0  | 103785.0  | 146549.0  | 1019603.0 | 3483.0   | 1273420.0  | 873092.0   | 
| STATE LIBRARY OF NORTH CAROLINA              | 109 EAST JONES STREET                 | RALEIGH        | NC      | 27601   | 2807     | 4640 MAIL SERVICE CENTER              | RALEIGH        | NC      | 27699   | 4640     | STATELIBRARY.DCR.STATE.NC.US                                                  | Y       | N      | N       | N      | Y      | NHPRC                                                                                                                    | 37       | 5      | 1       | 1183248000 | 1214784000 | 8429449.0  | 2500.0   | 8431949.0  | 5273493.0  | 38119264.0 | 1872402.0 | 45265159.0 | 386173.0  | 54083281.0 | 983325.0  | 2947111.0 | 0.0      | 3930436.0 | 360792.0 | 1075676.0 | 0.0      | 1436468.0 | 1344117.0 | 4022787.0 | 0.0      | 5366904.0  | 656637.0 | 510085.0  | 0.0      | 1166722.0 | 3401111.0 | 2645097.0 | 386173.0 | 6432381.0 | 5401865.0 | 7177969.0  | 386173.0 | 12966007.0 | 86789.0   | 21441984.0 | 0.0       | 21528773.0 | 371838.0 | 9373280.0 | 0.0     | 9745118.0 | 0.0      | 0.0     | 0.0     | 0.0      | 825237.0 | 2304000.0 | 0.0     | 3129237.0 | 1921675.0 | 0.0       | 0.0     | 1921675.0 | 0.0      | 5000000.0 | 0.0    | 5000000.0 | 0.0     | 0.0     | 0.0     | 0.0     | 3205539.0 | 38119264.0 | 0.0       | 41324803.0 | 5118.0   | 24109.0  | 0.0      | 29227.0  | 2500.0    | 0.0      | 0.0       | 2500.0    | 8615022.0  | 45321342.0 | 386173.0  | 54322537.0 | 5037714.0 | 3205539.0 | 186196.0 | 8429449.0  | 6641342.0 | 498621.0  | 1103290.0 | 186196.0 | 8429449.0  | 18328340.0 | 
```