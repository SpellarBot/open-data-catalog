# State Libraries Survey, FY 2009, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2009-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/auqm-gett) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/auqm-gett/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/auqm-gett/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | auqm-gett |
| Name | State Libraries Survey, FY 2009, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2009, revenue, expenditures |
| Created | 2016-12-20T15:31:12Z |
| Publication Date | 2016-12-20T17:04:40Z |

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
series e:auqm-gett d:2008-07-01T00:00:00.000Z t:physcity="BATON ROUGE" t:mailcity="BATON ROUGE" t:asf_lc=Y t:mail_st=LA t:pub_fips=22 t:obereg=8 t:asf_ac=Y t:physaddr="701 NORTH FOURTH STREET" t:phys_st=LA t:mailzip=70821 t:mailzip4=131 t:asf_pub=Y t:mailaddr="P.O. BOX 131" t:stlaname="STATE LIBRARY OF LOUISIANA" t:physzip4=5232 t:asf_sch=Y t:webaddr=WWW.STATE.LIB.LA.US t:asf_sp=Y t:rstatus=1 t:physzip=70802 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=89610 m:totaida=799695 m:aidsala=525344 m:capitald=0 m:admexpt=33321 m:swexpt=0 m:admexpu=33321 m:oexpbenb=920824 m:oexpbena=13328 m:oexpbend=934152 m:oexpbenc=0 m:totincm=5173659 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=833016 m:totexpt=833016 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=5084524 m:totexpa=833016 m:totexpc=475 m:totexpb=4251033 m:sistlaop=3359633 m:aidmlsa=47767 m:aidmlsc=0 m:popu_st=698473 m:aidmlsb=18906 m:totoxstc=0 m:totoxstd=2712821 m:aidmlsd=66673 m:serllxu=311161 m:totopexc=475 m:totopexd=3393429 m:totopexa=33321 m:aidothd=0 m:totopexb=3359633 m:aidothc=0 m:oexpothc=475 m:aidothb=0 m:total_fi=833016 m:oexpothd=510182 m:aidotha=0 m:oexpotha=0 m:oexpothb=509707 m:aidplsc=0 m:aidplsd=143730 m:total_si=4340643 m:totoxstb=2679500 m:totoxsta=33321 m:oexpcold=170426 m:lstainc=833016 m:aidplsa=70893 m:oexpcolb=170426 m:grexpt=799695 m:aidplsb=72837 m:oexpcolc=0 m:serdifxu=219370 m:oexpsalb=1758676 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=775651 m:siaidlib=891400 m:othexpb=0 m:aidipla=107538 m:oexpsala=19993 m:aidoila=48153 m:othexpc=0 m:aidiplb=668113 m:aidoilb=5514 m:aidsald=651374 m:totaidd=1691095 m:aidoilc=0 m:totaidc=0 m:techxu=269164 m:oexpsald=1778669 m:aidoild=53667 m:aidsalb=126030 m:aidsalc=0 m:othexpa=0

series e:auqm-gett d:2008-07-01T00:00:00.000Z t:physcity=BOSTON t:mailcity=BOSTON t:asf_lc=N t:mail_st=MA t:pub_fips=25 t:obereg=5 t:asf_ac=N t:physaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:phys_st=MA t:mailzip=2114 t:mailzip4=1933 t:asf_pub=Y t:mailaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:stlaname="MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS" t:physzip4=1933 t:asf_sch=N t:webaddr=MBLC.STATE.MA.US t:asf_sp=N t:rstatus=1 t:physzip=2114 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4837657 m:siother=415842 m:totaida=1201154 m:aidsala=2532 m:capitald=0 m:admexpt=60842 m:swexpt=1300001 m:admexpu=60842 m:oexpbenb=724055 m:oexpbena=0 m:oexpbend=724055 m:oexpbenc=0 m:totincm=10986457 m:othincm=215877 m:aidlcd=205204 m:aidlcc=0 m:totexpu=2561997 m:totexpt=2561997 m:fioth=0 m:aidlca=0 m:aidlcb=205204 m:totexpd=10692371 m:totexpa=2561997 m:totexpc=198127 m:totexpb=7932247 m:sistlaop=2821590 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=4708708 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2735915 m:aidmlsd=0 m:serllxu=802708 m:totopexc=0 m:totopexd=3894433 m:totopexa=1072843 m:aidothd=0 m:totopexb=2821590 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:total_fi=2695491 m:oexpothd=1135631 m:aidotha=0 m:oexpotha=1049956 m:oexpothb=85675 m:aidplsc=0 m:aidplsd=192278 m:total_si=8075089 m:totoxstb=2735915 m:totoxsta=0 m:oexpcold=22887 m:lstainc=2695491 m:aidplsa=192278 m:oexpcolb=0 m:grexpt=1201154 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=158970 m:oexpsalb=2011860 m:othexpd=561000 m:aidiplc=198127 m:oexpcola=22887 m:oexpsalc=0 m:aidipld=5836924 m:siaidlib=4837657 m:othexpb=273000 m:aidipla=1006344 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=4632453 m:aidoilb=0 m:aidsald=2532 m:totaidd=6236938 m:aidoilc=0 m:totaidc=198127 m:techxu=1539477 m:oexpsald=2011860 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=288000

series e:auqm-gett d:2008-07-01T00:00:00.000Z t:physcity=BALTIMORE t:mailcity=BALTIMORE t:asf_lc=N t:mail_st=MD t:pub_fips=24 t:obereg=5 t:asf_ac=N t:physaddr="200 WEST BALTIMORE STREET" t:phys_st=MD t:mailzip=21201 t:mailzip4=2595 t:asf_pub=Y t:mailaddr="200 WEST BALTIMORE STREET" t:stlaname="DIVISION OF LIBRARY DEVELOPMENT AND SERVICES" t:physzip4=2595 t:asf_sch=N t:webaddr=www.marylandpublicschools.org/MSDE/divisions/library t:asf_sp=N t:rstatus=1 t:physzip=21201 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=44890 m:totaidb=4948545 m:siother=215496 m:totaida=0 m:aidsala=0 m:capitald=44890 m:admexpt=54555 m:swexpt=1662417 m:admexpu=54555 m:oexpbenb=436852 m:oexpbena=111383 m:oexpbend=548235 m:oexpbenc=0 m:totincm=10058699 m:othincm=5000 m:aidlcd=0 m:aidlcc=0 m:totexpu=1716972 m:totexpt=1716972 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=9993287 m:totexpa=1716972 m:totexpc=209302 m:totexpb=8067013 m:sistlaop=3118468 m:aidmlsa=0 m:aidmlsc=0 m:popu_st=2889450 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2413443 m:aidmlsd=0 m:serllxu=662375 m:totopexc=84302 m:totopexd=4874852 m:totopexa=1672082 m:aidothd=10429 m:totopexb=3118468 m:aidothc=0 m:oexpothc=84302 m:aidothb=10429 m:total_fi=1819735 m:oexpothd=2026284 m:aidotha=0 m:oexpotha=974379 m:oexpothb=967603 m:aidplsc=0 m:aidplsd=0 m:total_si=8233964 m:totoxstb=1986461 m:totoxsta=426982 m:oexpcold=435125 m:lstainc=1819735 m:aidplsa=0 m:oexpcolb=164404 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=236677 m:oexpsalb=1549609 m:othexpd=0 m:aidiplc=125000 m:oexpcola=270721 m:oexpsalc=0 m:aidipld=5063116 m:siaidlib=4900000 m:othexpb=0 m:aidipla=0 m:oexpsala=315599 m:aidoila=0 m:othexpc=0 m:aidiplb=4938116 m:aidoilb=0 m:aidsald=0 m:totaidd=5073545 m:aidoilc=0 m:totaidc=125000 m:techxu=763365 m:oexpsald=1865208 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

entity e:auqm-gett l:"State Libraries Survey, FY 2009, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/auqm-gett

property e:auqm-gett t:meta.view v:id=auqm-gett v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2009, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:auqm-gett t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:auqm-gett t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:auqm-gett t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:auqm-gett t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                     | physaddr                              | physcity       | phys_st | physzip | physzip4 | mailaddr                              | mailcity       | mail_st | mailzip | mailzip4 | webaddr                                                                       | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                                                                 | pub_fips | obereg | rstatus | fystart    | fyend      | lstainc    | fioth    | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | oexpsala  | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd   | totopexa  | totopexb   | totopexc | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa  | aidplsb   | aidplsc | aidplsd   | aidoila  | aidoilb  | aidoilc | aidoild  | aidmlsa  | aidmlsb   | aidmlsc | aidmlsd   | aidsala   | aidsalb  | aidsalc | aidsald   | aidlca   | aidlcb    | aidlcc    | aidlcd    | aidotha  | aidothb | aidothc | aidothd  | totaida    | totaidb    | totaidc   | totaidd    | capitala | capitalb  | capitalc | capitald  | othexpa  | othexpb  | othexpc   | othexpd   | totexpa    | totexpb    | totexpc   | totexpd    | swexpt    | grexpt     | admexpt  | totexpt    | techxu    | serdifxu  | serllxu   | admexpu  | totexpu    | popu_st    | 
| ============================================ | ===================================== | ============== | ======= | ======= | ======== | ===================================== | ============== | ======= | ======= | ======== | ============================================================================= | ======= | ====== | ======= | ====== | ====== | ======================================================================================================================= | ======== | ====== | ======= | ========== | ========== | ========== | ======== | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========== | ========= | ========== | ======== | ========== | ========= | ========== | ======== | ========== | ======== | ========= | ======= | ========= | ======== | ======== | ======= | ======== | ======== | ========= | ======= | ========= | ========= | ======== | ======= | ========= | ======== | ========= | ========= | ========= | ======== | ======= | ======= | ======== | ========== | ========== | ========= | ========== | ======== | ========= | ======== | ========= | ======== | ======== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ========= | ========= | ======== | ========== | ========== | 
| STATE LIBRARY OF LOUISIANA                   | 701 NORTH FOURTH STREET               | BATON ROUGE    | LA      | 70802   | 5232     | P.O. BOX 131                          | BATON ROUGE    | LA      | 70821   | 131      | WWW.STATE.LIB.LA.US                                                           | Y       | Y      | Y       | Y      | Y      | P                                                                                                                       | 22       | 8      | 1       | 1214870400 | 1246320000 | 833016.0   | 0.0      | 833016.0   | 3359633.0  | 891400.0   | 89610.0   | 4340643.0  | 0.0       | 5173659.0  | 19993.0   | 1758676.0 | 0.0      | 1778669.0 | 13328.0  | 920824.0  | 0.0      | 934152.0  | 33321.0   | 2679500.0 | 0.0      | 2712821.0  | 0.0      | 170426.0  | 0.0      | 170426.0  | 0.0       | 509707.0  | 475.0    | 510182.0   | 33321.0   | 3359633.0  | 475.0    | 3393429.0  | 107538.0  | 668113.0   | 0.0      | 775651.0   | 70893.0  | 72837.0   | 0.0     | 143730.0  | 48153.0  | 5514.0   | 0.0     | 53667.0  | 47767.0  | 18906.0   | 0.0     | 66673.0   | 525344.0  | 126030.0 | 0.0     | 651374.0  | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 799695.0   | 891400.0   | 0.0       | 1691095.0  | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 0.0       | 833016.0   | 4251033.0  | 475.0     | 5084524.0  | 0.0       | 799695.0   | 33321.0  | 833016.0   | 269164.0  | 219370.0  | 311161.0  | 33321.0  | 833016.0   | 698473.0   | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | MBLC.STATE.MA.US                                                              | Y       | N      | N       | N      | N      | P                                                                                                                       | 25       | 5      | 1       | 1214870400 | 1246320000 | 2695491.0  | 0.0      | 2695491.0  | 2821590.0  | 4837657.0  | 415842.0  | 8075089.0  | 215877.0  | 10986457.0 | 0.0       | 2011860.0 | 0.0      | 2011860.0 | 0.0      | 724055.0  | 0.0      | 724055.0  | 0.0       | 2735915.0 | 0.0      | 2735915.0  | 22887.0  | 0.0       | 0.0      | 22887.0   | 1049956.0 | 85675.0   | 0.0      | 1135631.0  | 1072843.0 | 2821590.0  | 0.0      | 3894433.0  | 1006344.0 | 4632453.0  | 198127.0 | 5836924.0  | 192278.0 | 0.0       | 0.0     | 192278.0  | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 2532.0    | 0.0      | 0.0     | 2532.0    | 0.0      | 205204.0  | 0.0       | 205204.0  | 0.0      | 0.0     | 0.0     | 0.0      | 1201154.0  | 4837657.0  | 198127.0  | 6236938.0  | 0.0      | 0.0       | 0.0      | 0.0       | 288000.0 | 273000.0 | 0.0       | 561000.0  | 2561997.0  | 7932247.0  | 198127.0  | 10692371.0 | 1300001.0 | 1201154.0  | 60842.0  | 2561997.0  | 1539477.0 | 158970.0  | 802708.0  | 60842.0  | 2561997.0  | 4708708.0  | 
| DIVISION OF LIBRARY DEVELOPMENT AND SERVICES | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | www.marylandpublicschools.org/MSDE/divisions/library                          | Y       | N      | N       | N      | N      | P                                                                                                                       | 24       | 5      | 1       | 1214870400 | 1246320000 | 1819735.0  | 0.0      | 1819735.0  | 3118468.0  | 4900000.0  | 215496.0  | 8233964.0  | 5000.0    | 10058699.0 | 315599.0  | 1549609.0 | 0.0      | 1865208.0 | 111383.0 | 436852.0  | 0.0      | 548235.0  | 426982.0  | 1986461.0 | 0.0      | 2413443.0  | 270721.0 | 164404.0  | 0.0      | 435125.0  | 974379.0  | 967603.0  | 84302.0  | 2026284.0  | 1672082.0 | 3118468.0  | 84302.0  | 4874852.0  | 0.0       | 4938116.0  | 125000.0 | 5063116.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 10429.0 | 0.0     | 10429.0  | 0.0        | 4948545.0  | 125000.0  | 5073545.0  | 44890.0  | 0.0       | 0.0      | 44890.0   | 0.0      | 0.0      | 0.0       | 0.0       | 1716972.0  | 8067013.0  | 209302.0  | 9993287.0  | 1662417.0 | 0.0        | 54555.0  | 1716972.0  | 763365.0  | 236677.0  | 662375.0  | 54555.0  | 1716972.0  | 2889450.0  | 
| MAINE STATE LIBRARY                          | 230 STATE STREET                      | AUGUSTA        | ME      | 4333    | 64       | 64 STATE HOUSE STATION                | AUGUSTA        | ME      | 4333    | 64       | www.maine.gov/msl/                                                            | Y       | Y      | N       | N      | Y      | PERSISTENT DIGITAL ARCHIVES LIB SYSTEMS, NHPRC NATIONAL HISTORICAL PUBLICATIONS,NEH NATIONAL DIGITAL NEWSPAPER PROJECT  | 23       | 6      | 1       | 1214870400 | 1246320000 | 3451184.0  | 363826.0 | 3815010.0  | 5593600.0  | 630100.0   | 97000.0   | 6320700.0  | 269117.0  | 10404827.0 | 375046.0  | 3630720.0 | 56519.0  | 4062285.0 | 123790.0 | 1366751.0 | 21384.0  | 1511925.0 | 498836.0  | 4997471.0 | 77903.0  | 5574210.0  | 705120.0 | 117885.0  | 6160.0   | 829165.0  | 1464484.0 | 472330.0  | 250180.0 | 2186994.0  | 2668440.0 | 5587686.0  | 334243.0 | 8590369.0  | 492367.0  | 517942.0   | 0.0      | 1010309.0  | 309061.0 | 52010.0   | 0.0     | 361071.0  | 22544.0  | 179435.0 | 0.0     | 201979.0 | 0.0      | 0.0       | 0.0     | 0.0       | 4605.0    | 0.0      | 0.0     | 4605.0    | 0.0      | 0.0       | 0.0       | 0.0       | 272725.0 | 0.0     | 0.0     | 272725.0 | 1101302.0  | 749387.0   | 0.0       | 1850689.0  | 86421.0  | 0.0       | 5000.0   | 91421.0   | 0.0      | 9000.0   | 107200.0  | 116200.0  | 3856163.0  | 6346073.0  | 446443.0  | 10648679.0 | 2212547.0 | 1101302.0  | 137335.0 | 3451184.0  | 1810497.0 | 95328.0   | 1408024.0 | 137335.0 | 3451184.0  | 6595778.0  | 
| LIBRARY OF MICHIGAN                          | 702 WEST KALAMAZOO STREET             | LANSING        | MI      | 48909   | 7507     | P.O. BOX 30007                        | LANSING        | MI      | 48909   | 7507     | www.michigan.gov/libraryofmichigan                                            | Y       | N      | N       | N      | Y      | P                                                                                                                       | 26       | 8      | 2       | 1222819200 | 1254268800 | 16431277.0 | 0.0      | 16431277.0 | 16107670.0 | 30390000.0 | 1783000.0 | 48280670.0 | 501507.0  | 65213454.0 | 2272495.0 | 5020854.0 | 270178.0 | 7563527.0 | 852493.0 | 2035923.0 | 103252.0 | 2991668.0 | 3124988.0 | 7056777.0 | 373430.0 | 10555195.0 | 524042.0 | 370713.0  | 0.0      | 894755.0  | 2606160.0 | 8680180.0 | 128077.0 | 11414417.0 | 6255190.0 | 16107670.0 | 501507.0 | 22864367.0 | 3035196.0 | 27664000.0 | 0.0      | 30699196.0 | 0.0      | 0.0       | 0.0     | 0.0       | 137090.0 | 0.0      | 0.0     | 137090.0 | 98635.0  | 2726000.0 | 0.0     | 2824635.0 | 6905166.0 | 0.0      | 0.0     | 6905166.0 | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 10176087.0 | 30390000.0 | 0.0       | 40566087.0 | 0.0      | 1783000.0 | 0.0      | 1783000.0 | 0.0      | 0.0      | 0.0       | 0.0       | 16431277.0 | 48280670.0 | 501507.0  | 65213454.0 | 6093464.0 | 10176087.0 | 161726.0 | 16431277.0 | 8763309.0 | 2695549.0 | 4810693.0 | 161726.0 | 16431277.0 | 36961664.0 | 
| STATE LIBRARY SERVICES                       | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4266     | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4035     | http://education.state.mn.us/MDE/Learning_Support/Library_Services/index.html | N       | N      | N       | N      | Y      | P                                                                                                                       | 27       | 7      | 1       | 1214870400 | 1246320000 | 2612765.0  | 0.0      | 2612765.0  | 985341.0   | 2351551.0  | 550000.0  | 3886892.0  | 197956.0  | 6697613.0  | 1256188.0 | 713557.0  | 80471.0  | 2050216.0 | 297346.0 | 137334.0  | 19048.0  | 453728.0  | 1553534.0 | 850891.0  | 99519.0  | 2503944.0  | 25062.0  | 0.0       | 0.0      | 25062.0   | 144987.0  | 124189.0  | 98437.0  | 367613.0   | 1723583.0 | 975080.0   | 197956.0 | 2896619.0  | 144162.0  | 0.0        | 0.0      | 144162.0   | 0.0      | 0.0       | 0.0     | 0.0       | 69921.0  | 0.0      | 0.0     | 69921.0  | 0.0      | 2000000.0 | 0.0     | 2000000.0 | 580044.0  | 351551.0 | 0.0     | 931595.0  | 0.0      | 0.0       | 0.0       | 0.0       | 43586.0  | 0.0     | 0.0     | 43586.0  | 837713.0   | 2351551.0  | 0.0       | 3189264.0  | 51469.0  | 10261.0   | 0.0      | 61730.0   | 0.0      | 550000.0 | 0.0       | 550000.0  | 2612765.0  | 3886892.0  | 197956.0  | 6697613.0  | 1670542.0 | 837713.0   | 104510.0 | 2612765.0  | 674757.0  | 690733.0  | 1142765.0 | 104510.0 | 2612765.0  | 5024748.0  | 
| MISSOURI STATE LIBRARY                       | 600 WEST MAIN STREET, 2ND FLOOR       | JEFFERSON CITY | MO      | 65101   | 1592     | PO BOX 387                            | JEFFERSON CITY | MO      | 65102   | 387      | WWW.SOS.MO.GOV/LIBRARY/                                                       | Y       | N      | N       | N      | Y      | CONNECTING TO COLLECTIONS STATEWIDE PLANNING GRANTS                                                                     | 29       | 1      | 2       | 1214870400 | 1246320000 | 2098142.0  | 7813.0   | 2105955.0  | 11297215.0 | 8833687.0  | 0.0       | 20130902.0 | 1420086.0 | 23656943.0 | 862627.0  | 6339978.0 | 246646.0 | 7449251.0 | 508935.0 | 0.0       | 138004.0 | 646939.0  | 1371562.0 | 6339978.0 | 384650.0 | 8096190.0  | 28031.0  | 1141996.0 | 37374.0  | 1207401.0 | 444686.0  | 3712668.0 | 268336.0 | 4425690.0  | 1844279.0 | 11194642.0 | 690360.0 | 13729281.0 | 87243.0   | 1573137.0  | 0.0      | 1660380.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 332500.0 | 0.0     | 332500.0  | 0.0      | 3340550.0 | 0.0       | 3340550.0 | 0.0      | 0.0     | 0.0     | 0.0      | 87243.0    | 5246187.0  | 0.0       | 5333430.0  | 0.0      | 90134.0   | 0.0      | 90134.0   | 0.0      | 0.0      | 1590088.0 | 1590088.0 | 1931522.0  | 16530963.0 | 2280448.0 | 20742933.0 | 1807502.0 | 87243.0    | 28964.0  | 1923709.0  | 650772.0  | 674213.0  | 569760.0  | 28964.0  | 1923709.0  | 3518288.0  | 
| MISSISSIPPI LIBRARY COMMISSION               | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | WWW.MLC.LIB.MS.US                                                             | N       | N      | N       | N      | N      | NEH RECOVERY OF THE PEABODY COLLECTION, LSCA GRANT AND NEH FOREVER FREE: ABRAHAM LINCOLN'S JOURNEY TO EMANCIPATION      | 28       | 2      | 1       | 1214870400 | 1246320000 | 794432.0   | 469116.0 | 1263548.0  | 44864691.0 | 0.0        | 0.0       | 44864691.0 | 597311.0  | 46725550.0 | 376209.0  | 213918.0  | 0.0      | 590127.0  | 69909.0  | 28316.0   | 0.0      | 98225.0   | 446118.0  | 242234.0  | 0.0      | 688352.0   | 0.0      | 0.0       | 0.0      | 0.0       | 213210.0  | 33074.0   | 0.0      | 246284.0   | 659328.0  | 275308.0   | 0.0      | 934636.0   | 154534.0  | 44484443.0 | 459594.0 | 45098571.0 | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 449533.0 | 0.0       | 0.0       | 449533.0  | 0.0      | 0.0     | 0.0     | 0.0      | 604067.0   | 44484443.0 | 459594.0  | 45548104.0 | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 0.0       | 1263395.0  | 44759751.0 | 459594.0  | 46482740.0 | 634199.0  | 154534.0   | 5699.0   | 794432.0   | 0.0       | 102613.0  | 686120.0  | 5699.0   | 794432.0   | 599657.0   | 
| MONTANA STATE LIBRARY                        | 1515 EAST 6TH AVENUE                  | HELENA         | MT      | 59620   | 1800     | PO BOX 201800                         | HELENA         | MT      | 59620   | 1800     | msl.mt.gov                                                                    | Y       | Y      | N       | Y      | Y      | CENTER FOR THE BOOK PROGRAMS-THE BIG READ, LETTERS ABOUT LITERATURE                                                     | 30       | 2      | 1       | 1214870400 | 1246320000 | 846341.0   | 16900.0  | 863241.0   | 2367690.0  | 7256709.0  | 1640023.0 | 11264422.0 | 7470841.0 | 19598504.0 | 287045.0  | 491616.0  | 0.0      | 778661.0  | 109533.0 | 213183.0  | 0.0      | 322716.0  | 396578.0  | 704799.0  | 0.0      | 1101377.0  | 0.0      | 65000.0   | 0.0      | 65000.0   | 1197570.0 | 2568966.0 | 0.0      | 3766536.0  | 1594148.0 | 3338765.0  | 0.0      | 4932913.0  | 0.0       | 1327743.0  | 0.0      | 1327743.0  | 0.0      | 2874807.0 | 0.0     | 2874807.0 | 0.0      | 11000.0  | 0.0     | 11000.0  | 0.0      | 0.0       | 0.0     | 0.0       | 30963.0   | 0.0      | 0.0     | 30963.0   | 0.0      | 3054159.0 | 6190824.0 | 9244983.0 | 16900.0  | 0.0     | 7632.0  | 24532.0  | 47863.0    | 7267709.0  | 6198456.0 | 13514028.0 | 0.0      | 0.0       | 0.0      | 0.0       | 0.0      | 949600.0 | 0.0       | 949600.0  | 1642011.0  | 11556074.0 | 6198456.0 | 19396541.0 | 1590804.0 | 30963.0    | 3344.0   | 1625111.0  | 167011.0  | 71412.0   | 1383344.0 | 3344.0   | 1625111.0  | 885122.0   | 
| STATE LIBRARY OF NORTH CAROLINA              | 109 EAST JONES STREET                 | RALEIGH        | NC      | 27601   | 2807     | 4640 MAIL SERVICE CENTER              | RALEIGH        | NC      | 27699   | 4640     | STATELIBRARY.NCDCR.GOV                                                        | Y       | N      | N       | N      | Y      | P                                                                                                                       | 37       | 5      | 1       | 1214870400 | 1246320000 | 8850816.0  | 0.0      | 8850816.0  | 4836465.0  | 24919001.0 | 1922122.0 | 31677588.0 | 0.0       | 40528404.0 | 970798.0  | 2965923.0 | 0.0      | 3936721.0 | 330071.0 | 1008413.0 | 0.0      | 1338484.0 | 1300869.0 | 3974336.0 | 0.0      | 5275205.0  | 531786.0 | 265508.0  | 0.0      | 797294.0  | 3706755.0 | 2688755.0 | 0.0      | 6395510.0  | 5539410.0 | 6928599.0  | 0.0      | 12468009.0 | 1032678.0 | 18175587.0 | 0.0      | 19208265.0 | 130678.0 | 5304414.0 | 0.0     | 5435092.0 | 0.0      | 0.0      | 0.0     | 0.0      | 942575.0 | 1440000.0 | 0.0     | 2382575.0 | 1000764.0 | 0.0      | 0.0     | 1000764.0 | 0.0      | 0.0       | 0.0       | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 3106695.0  | 24920001.0 | 0.0       | 28026696.0 | 36054.0  | 31221.0   | 0.0      | 67275.0   | 0.0      | 0.0      | 0.0       | 0.0       | 8682159.0  | 31879821.0 | 0.0       | 40561980.0 | 4981870.0 | 3106695.0  | 337023.0 | 8425588.0  | 6573818.0 | 916468.0  | 598279.0  | 337023.0 | 8425588.0  | 18537969.0 | 
```