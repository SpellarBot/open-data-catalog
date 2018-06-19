# State Libraries Survey, FY 1995, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1995-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/yam5-caqd) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/yam5-caqd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/yam5-caqd/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | yam5-caqd |
| Name | State Libraries Survey, FY 1995, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1995, revenue, expenditures |
| Created | 2016-12-20T15:14:37Z |
| Publication Date | 2016-12-20T17:04:23Z |

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
| Yes      | series tag     | fiothsp    | Other fed rev specified            | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                    | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy   | date      | date        |
| Yes      | numeric metric | fioth      | Other federal revenue              | money     | money       |
| Yes      | numeric metric | total_fi   | Total federal revenue              | money     | money       |
| Yes      | numeric metric | sistlaop   | St rev STLA operation              | money     | money       |
| Yes      | numeric metric | siaidlib   | St rev aid to libraries            | money     | money       |
| Yes      | numeric metric | siother    | St rev other                       | money     | money       |
| Yes      | numeric metric | total_si   | St rev TOTAL                       | money     | money       |
| Yes      | numeric metric | othincm    | Other revenue                      | money     | money       |
| Yes      | numeric metric | totincm    | Total revenue                      | money     | money       |
| Yes      | numeric metric | fit1       | Fed inc LSCA Title I               | money     | money       |
| Yes      | numeric metric | fit2       | Fed inc LSCA Title II              | money     | money       |
| Yes      | numeric metric | fit3       | Fed inc LSCA Title III             | money     | money       |
| Yes      | numeric metric | fitott13   | Total fed inc LSCA Titles I-III    | money     | money       |
| Yes      | numeric metric | fiotht48   | Other fed inc Titles IV-VIII       | money     | money       |
| Yes      | series tag     | fit4       | Fed inc Title IV                   | text      | text        |
| Yes      | series tag     | fit5       | Fed inc Title V                    | text      | text        |
| Yes      | series tag     | fit6       | Fed inc Title VI                   | text      | text        |
| Yes      | series tag     | fit7       | Fed inc Title VII                  | text      | text        |
| Yes      | series tag     | fit8       | Fed inc Title VIII                 | text      | text        |
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
| Yes      | numeric metric | t1expstw   | Title I exp statwide               | money     | money       |
| Yes      | numeric metric | t1expgrt   | Title I exp grants                 | money     | money       |
| Yes      | numeric metric | t1expadm   | Title I exp LSCA admin             | money     | money       |
| Yes      | numeric metric | totexpt1   | Title I exp TOTAL                  | money     | money       |
| Yes      | numeric metric | t2expgrt   | Title II exp grants                | money     | money       |
| Yes      | numeric metric | t2expadm   | Title II exp LSCA admin            | money     | money       |
| Yes      | numeric metric | totexpt2   | Title II exp TOTAL                 | money     | money       |
| Yes      | numeric metric | t3expstw   | Title III exp statewide            | money     | money       |
| Yes      | numeric metric | t3expgrt   | Title III exp grants               | money     | money       |
| Yes      | numeric metric | totexpt3   | Title III exp TOTAL                | money     | money       |
| Yes      | numeric metric | totex123   | Titles I-III exp TOTAL             | money     | money       |
| Yes      | numeric metric | allopstf   | Oper exp staff total               | money     | money       |
| Yes      | numeric metric | allopoth   | Oper exp other total               | money     | money       |
| Yes      | numeric metric | totox_ao   | Oper exp TOTAL                     | money     | money       |
| Yes      | numeric metric | allopcap   | Capital outlay                     | money     | money       |
| Yes      | numeric metric | totexpao   | Total expenditures                 | money     | money       |
| Yes      | numeric metric | period_e   | Population estimate NCES           | number    | number      |
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
series e:yam5-caqd d:1994-07-01T00:00:00.000Z t:physzip4=571.0 t:physcity=JUNEAU t:mailcity=JUNEAU t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571.0 t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:t1expadm=0 m:totox_ao=0 m:totex123=833348 m:oexpbenb=404868 m:oexpbena=93366 m:oexpbend=498234 m:oexpbenc=0 m:fit3=139887 m:fit2=157463 m:fit1=535998 m:totincm=3035930 m:t1expgrt=0 m:othincm=38662 m:totexpt1=535998 m:totexpt3=139887 m:totexpt2=157463 m:fitott13=833348 m:sistlaop=1913920 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=210000 m:totexpao=0 m:aidmlsd=210000 m:totopexc=38662 m:totopexd=2773164 m:aidothd=0 m:totopexa=820582 m:aidothc=0 m:totopexb=1913920 m:aidothb=0 m:oexpothc=38662 m:aidotha=0 m:oexpothd=649376 m:t2expgrt=147663 m:oexpotha=468012 m:oexpothb=142702 m:oexpsalb=1321350 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=259204 m:totaidd=397663 m:aidsald=0 m:aidoilb=0 m:t1expstw=535998 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1580554 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=124887 m:capitalb=0 m:capitala=0 m:totaidb=250000 m:totaida=147663 m:siother=0 m:capitald=0 m:aidsala=0 m:aidlcd=147663 m:aidlcc=0 m:t2expadm=9800 m:period_e=1079516 m:allopstf=0 m:fioth=0 m:aidlca=147663 m:aidlcb=0 m:t3expgrt=15000 m:totexpd=3170827 m:allopcap=0 m:totexpa=968245 m:totexpc=38662 m:totexpb=2163920 m:totoxstc=0 m:totoxstd=2078788 m:total_fi=833348 m:aidplsc=0 m:aidplsd=0 m:fiotht48=0 m:total_si=2163920 m:totoxstb=1726218 m:totoxsta=352570 m:oexpcold=45000 m:aidplsa=0 m:oexpcolb=45000 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=0 m:aidipld=40000 m:siaidlib=250000 m:aidipla=0 m:aidiplb=40000

series e:yam5-caqd d:1994-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailaddr="6030 MONTICELLO DRIVE" t:fiothsp="NATIONAL ENDOWMENT FOR THE HUMANITIES, MICHIGAN NEWSPAPER PROJECT" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:t1expadm=34350 m:totox_ao=0 m:totex123=4917242 m:oexpbenb=1402534 m:oexpbena=0 m:oexpbend=1402534 m:oexpbenc=0 m:fit3=785040 m:fit2=739977 m:fit1=3392225 m:totincm=34628365 m:t1expgrt=3262710 m:othincm=155000 m:totexpt1=3392225 m:totexpt3=785040 m:totexpt2=739977 m:fitott13=4917242 m:sistlaop=7382300 m:aidmlsa=785040 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=785040 m:totopexc=0 m:totopexd=7416650 m:aidothd=0 m:totopexa=34350 m:aidothc=0 m:totopexb=7382300 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=1746564 m:t2expgrt=739977 m:oexpotha=34350 m:oexpothb=1712214 m:oexpsalb=3443213 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=95165 m:oexpsala=0 m:totaidd=17817292 m:aidsald=0 m:aidoilb=0 m:t1expstw=95165 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=95165 m:oexpsald=3443213 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=14011 m:capitalb=0 m:capitala=0 m:totaidb=12934400 m:totaida=4882892 m:siother=3058300 m:capitald=0 m:aidsala=0 m:aidlcd=739977 m:aidlcc=0 m:t2expadm=0 m:period_e=9332515 m:allopstf=0 m:fioth=11523 m:aidlca=739977 m:aidlcb=0 m:t3expgrt=771029 m:totexpd=25233942 m:allopcap=0 m:totexpa=4917242 m:totexpc=0 m:totexpb=20316700 m:totoxstc=0 m:totoxstd=4845747 m:total_fi=4928765 m:aidplsc=0 m:aidplsd=5931775 m:fiotht48=0 m:total_si=29544600 m:totoxstb=4845747 m:totoxsta=0 m:oexpcold=824339 m:aidplsa=1404904 m:oexpcolb=824339 m:aidplsb=4526871 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=0 m:aidipld=10265335 m:siaidlib=19104000 m:aidipla=1857806 m:aidiplb=8407529

series e:yam5-caqd d:1994-07-01T00:00:00.000Z t:physzip4=1081.0 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1081.0 t:mailaddr="ONE CAPITOL MALL" t:fiothsp="FEDERAL INDIRECT COST" t:stlaname="ARKANSAS STATE LIBRARY" m:t1expadm=52538 m:totox_ao=0 m:totex123=2184266 m:oexpbenb=44957 m:oexpbena=8439 m:oexpbend=53396 m:oexpbenc=0 m:fit3=404058 m:fit2=309436 m:fit1=1424612 m:totincm=12893563 m:t1expgrt=1410435 m:othincm=14683 m:totexpt1=1462973 m:totexpt3=337995 m:totexpt2=383298 m:fitott13=2138106 m:sistlaop=954324 m:aidmlsa=337995 m:aidmlsc=0 m:aidmlsb=527000 m:totexpao=0 m:aidmlsd=864995 m:totopexc=24683 m:totopexd=1177917 m:aidothd=55912 m:totopexa=198910 m:aidothc=0 m:totopexb=954324 m:aidothb=0 m:oexpothc=14683 m:aidotha=55912 m:oexpothd=136089 m:t2expgrt=383298 m:oexpotha=6279 m:oexpothb=115127 m:oexpsalb=776240 m:othexpd=0 m:oexpsalc=10000 m:othexpb=0 m:othexpc=0 m:aidoila=55912 m:oexpsala=144192 m:totaidd=10787539 m:aidsald=662623 m:aidoilb=0 m:t1expstw=0 m:totaidc=0 m:aidoilc=0 m:aidsalb=662623 m:aidoild=55912 m:oexpsald=930432 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=0 m:capitalb=0 m:capitala=0 m:totaidb=8599899 m:totaida=2187640 m:siother=44000 m:capitald=0 m:aidsala=0 m:aidlcd=383298 m:aidlcc=0 m:t2expadm=0 m:period_e=4515118 m:allopstf=0 m:fioth=141450 m:aidlca=383298 m:aidlcb=0 m:t3expgrt=337995 m:totexpd=11965456 m:allopcap=0 m:totexpa=2386550 m:totexpc=24683 m:totexpb=9554223 m:totoxstc=10000 m:totoxstd=983828 m:total_fi=2279556 m:aidplsc=0 m:aidplsd=5794346 m:fiotht48=0 m:total_si=10599324 m:totoxstb=821197 m:totoxsta=152631 m:oexpcold=58000 m:aidplsa=890766 m:oexpcolb=18000 m:aidplsb=4903580 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=40000 m:aidipld=2970453 m:siaidlib=9601000 m:aidipla=463757 m:aidiplb=2506696
```

## Meta Commands

```ls
metric m:fioth p:double l:"Other federal revenue" t:dataTypeName=money

metric m:total_fi p:double l:"Total federal revenue" t:dataTypeName=money

metric m:sistlaop p:double l:"St rev STLA operation" t:dataTypeName=money

metric m:siaidlib p:double l:"St rev aid to libraries" t:dataTypeName=money

metric m:siother p:double l:"St rev other" t:dataTypeName=money

metric m:total_si p:double l:"St rev TOTAL" t:dataTypeName=money

metric m:othincm p:double l:"Other revenue" t:dataTypeName=money

metric m:totincm p:double l:"Total revenue" t:dataTypeName=money

metric m:fit1 p:double l:"Fed inc LSCA Title I" t:dataTypeName=money

metric m:fit2 p:double l:"Fed inc LSCA Title II" t:dataTypeName=money

metric m:fit3 p:double l:"Fed inc LSCA Title III" t:dataTypeName=money

metric m:fitott13 p:double l:"Total fed inc LSCA Titles I-III" t:dataTypeName=money

metric m:fiotht48 p:double l:"Other fed inc Titles IV-VIII" t:dataTypeName=money

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

metric m:t1expstw p:integer l:"Title I exp statwide" t:dataTypeName=money

metric m:t1expgrt p:integer l:"Title I exp grants" t:dataTypeName=money

metric m:t1expadm p:integer l:"Title I exp LSCA admin" t:dataTypeName=money

metric m:totexpt1 p:integer l:"Title I exp TOTAL" t:dataTypeName=money

metric m:t2expgrt p:integer l:"Title II exp grants" t:dataTypeName=money

metric m:t2expadm p:integer l:"Title II exp LSCA admin" t:dataTypeName=money

metric m:totexpt2 p:integer l:"Title II exp TOTAL" t:dataTypeName=money

metric m:t3expstw p:integer l:"Title III exp statewide" t:dataTypeName=money

metric m:t3expgrt p:integer l:"Title III exp grants" t:dataTypeName=money

metric m:totexpt3 p:integer l:"Title III exp TOTAL" t:dataTypeName=money

metric m:totex123 p:integer l:"Titles I-III exp TOTAL" t:dataTypeName=money

metric m:allopstf p:integer l:"Oper exp staff total" t:dataTypeName=money

metric m:allopoth p:integer l:"Oper exp other total" t:dataTypeName=money

metric m:totox_ao p:integer l:"Oper exp TOTAL" t:dataTypeName=money

metric m:allopcap p:integer l:"Capital outlay" t:dataTypeName=money

metric m:totexpao p:integer l:"Total expenditures" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:yam5-caqd l:"State Libraries Survey, FY 1995, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/yam5-caqd

property e:yam5-caqd t:meta.view v:id=yam5-caqd v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1995, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:yam5-caqd t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:yam5-caqd t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:yam5-caqd t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:yam5-caqd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | fiothsp                                                           | pub_fips | fystart   | fyend     | fioth    | total_fi  | sistlaop  | siaidlib   | siother   | total_si   | othincm  | totincm    | fit1      | fit2     | fit3     | fitott13  | fiotht48 | fit4 | fit5 | fit6 | fit7 | fit8 | oexpsala | oexpsalb | oexpsalc | oexpsald | oexpbena | oexpbenb | oexpbenc | oexpbend | totoxsta | totoxstb | totoxstc | totoxstd | oexpcola | oexpcolb | oexpcolc | oexpcold | oexpotha | oexpothb | oexpothc | oexpothd | totopexa | totopexb | totopexc | totopexd | aidipla | aidiplb  | aidiplc | aidipld  | aidplsa | aidplsb | aidplsc | aidplsd | aidoila | aidoilb | aidoilc | aidoild | aidmlsa | aidmlsb | aidmlsc | aidmlsd | aidsala | aidsalb | aidsalc | aidsald | aidlca | aidlcb | aidlcc | aidlcd | aidotha | aidothb | aidothc | aidothd | totaida | totaidb  | totaidc | totaidd  | capitala | capitalb | capitalc | capitald | othexpa | othexpb | othexpc | othexpd | totexpa   | totexpb    | totexpc  | totexpd    | t1expstw | t1expgrt | t1expadm | totexpt1 | t2expgrt | t2expadm | totexpt2 | t3expstw | t3expgrt | totexpt3 | totex123 | allopstf | allopoth | totox_ao | allopcap | totexpao | period_e  | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ================================================================= | ======== | ========= | ========= | ======== | ========= | ========= | ========== | ========= | ========== | ======== | ========== | ========= | ======== | ======== | ========= | ======== | ==== | ==== | ==== | ==== | ==== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ========= | ========== | ======== | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    |                                                                   | 2        | 773020800 | 804470400 | 0.0      | 833348.0  | 1913920.0 | 250000.0   | 0.0       | 2163920.0  | 38662.0  | 3035930.0  | 535998.0  | 157463.0 | 139887.0 | 833348.0  | 0.0      |      |      |      |      |      | 259204   | 1321350  | 0        | 1580554  | 93366    | 404868   | 0        | 498234   | 352570   | 1726218  | 0        | 2078788  | 0        | 45000    | 0        | 45000    | 468012   | 142702   | 38662    | 649376   | 820582   | 1913920  | 38662    | 2773164  | 0       | 40000    | 0       | 40000    | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 210000  | 0       | 210000  | 0       | 0       | 0       | 0       | 147663 | 0      | 0      | 147663 | 0       | 0       | 0       | 0       | 147663  | 250000   | 0       | 397663   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 968245.0  | 2163920.0  | 38662.0  | 3170827.0  | 535998   | 0        | 0        | 535998   | 147663   | 9800     | 157463   | 124887   | 15000    | 139887   | 833348   | 0        | 0        | 0        | 0        | 0        | 1079516.0 | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   |          | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   |          | NATIONAL ENDOWMENT FOR THE HUMANITIES, MICHIGAN NEWSPAPER PROJECT | 1        | 780969600 | 812419200 | 11523.0  | 4928765.0 | 7382300.0 | 19104000.0 | 3058300.0 | 29544600.0 | 155000.0 | 34628365.0 | 3392225.0 | 739977.0 | 785040.0 | 4917242.0 | 0.0      |      |      |      |      |      | 0        | 3443213  | 0        | 3443213  | 0        | 1402534  | 0        | 1402534  | 0        | 4845747  | 0        | 4845747  | 0        | 824339   | 0        | 824339   | 34350    | 1712214  | 0        | 1746564  | 34350    | 7382300  | 0        | 7416650  | 1857806 | 8407529  | 0       | 10265335 | 1404904 | 4526871 | 0       | 5931775 | 95165   | 0       | 0       | 95165   | 785040  | 0       | 0       | 785040  | 0       | 0       | 0       | 0       | 739977 | 0      | 0      | 739977 | 0       | 0       | 0       | 0       | 4882892 | 12934400 | 0       | 17817292 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 4917242.0 | 20316700.0 | 0.0      | 25233942.0 | 95165    | 3262710  | 34350    | 3392225  | 739977   | 0        | 739977   | 14011    | 771029   | 785040   | 4917242  | 0        | 0        | 0        | 0        | 0        | 9332515.0 | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLE ROCK | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLE ROCK | AR      | 72201   | 1081.0   | FEDERAL INDIRECT COST                                             | 5        | 773020800 | 804470400 | 141450.0 | 2279556.0 | 954324.0  | 9601000.0  | 44000.0   | 10599324.0 | 14683.0  | 12893563.0 | 1424612.0 | 309436.0 | 404058.0 | 2138106.0 | 0.0      |      |      |      |      |      | 144192   | 776240   | 10000    | 930432   | 8439     | 44957    | 0        | 53396    | 152631   | 821197   | 10000    | 983828   | 40000    | 18000    | 0        | 58000    | 6279     | 115127   | 14683    | 136089   | 198910   | 954324   | 24683    | 1177917  | 463757  | 2506696  | 0       | 2970453  | 890766  | 4903580 | 0       | 5794346 | 55912   | 0       | 0       | 55912   | 337995  | 527000  | 0       | 864995  | 0       | 662623  | 0       | 662623  | 383298 | 0      | 0      | 383298 | 55912   | 0       | 0       | 55912   | 2187640 | 8599899  | 0       | 10787539 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 2386550.0 | 9554223.0  | 24683.0  | 11965456.0 | 0        | 1410435  | 52538    | 1462973  | 383298   | 0        | 383298   | 0        | 337995   | 337995   | 2184266  | 0        | 0        | 0        | 0        | 0        | 4515118.0 | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   | NATIONAL LITERACY ACT                                             | 4        | 773020800 | 804470400 | 182572.0 | 2536785.0 | 1488864.0 | 1964448.0  | 0.0       | 3453312.0  | 0.0      | 5990097.0  | 1287489.0 | 532310.0 | 534414.0 | 2354213.0 | 0.0      |      |      |      |      |      | 244844   | 814781   | 0        | 1059625  | 67186    | 223579   | 0        | 290765   | 312030   | 1038360  | 0        | 1350390  | 114517   | 230101   | 0        | 344618   | 259037   | 220403   | 0        | 479440   | 685584   | 1488864  | 0        | 2174448  | 618800  | 1964448  | 0       | 2583248  | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 700091  | 0       | 0       | 700091  | 532310 | 0      | 0      | 532310 | 0       | 0       | 0       | 0       | 1851201 | 1964448  | 0       | 3815649  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 2536785.0 | 3453312.0  | 0.0      | 5990097.0  | 709514   | 544345   | 33630    | 1287489  | 532310   | 0        | 532310   | 477314   | 57100    | 534414   | 2354213  | 0        | 0        | 0        | 0        | 0        | 5277640.0 | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      |                                                                   | 6        | 773020800 | 804470400 | 0.0      | 1444769.0 | 2442880.0 | 5073168.0  | 0.0       | 7516048.0  | 0.0      | 8960817.0  | 820774.0  | 375301.0 | 248694.0 | 1444769.0 | 0.0      |      |      |      |      |      | 372459   | 1074450  | 0        | 1446909  | 92105    | 261455   | 0        | 353560   | 464564   | 1335905  | 0        | 1800469  | 81125    | 378272   | 0        | 459397   | 313026   | 728703   | 0        | 1041729  | 858715   | 2442880  | 0        | 3301595  | 0       | 0        | 0       | 0        | 137656  | 5073168 | 0       | 5210824 | 71951   | 0       | 0       | 71951   | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 375301 | 0      | 0      | 375301 | 1146    | 0       | 0       | 1146    | 586054  | 5073168  | 0       | 5659222  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 1444769.0 | 7516048.0  | 0.0      | 8960817.0  | 674530   | 96720    | 49524    | 820774   | 375301   | 0        | 375301   | 134661   | 114033   | 248694   | 1444769  | 0        | 0        | 0        | 0        | 0        | 2573216.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   | STATE LITERACY RESOURCE CENTER ($2,677) & NRIS-VARIOUS ($165,133) | 8        | 773020800 | 804470400 | 167810.0 | 805258.0  | 1157757.0 | 507331.0   | 0.0       | 1665088.0  | 207713.0 | 2678059.0  | 414816.0  | 150538.0 | 72094.0  | 637448.0  | 0.0      |      |      |      |      |      | 318171   | 438986   | 120815   | 877972   | 84273    | 116274   | 32000    | 232547   | 402444   | 555260   | 152815   | 1110519  | 14155    | 95227    | 0        | 109382   | 155727   | 463357   | 42855    | 661939   | 572326   | 1113844  | 195670   | 1881840  | 95635   | 0        | 0       | 95635    | 0       | 307331  | 0       | 307331  | 7445    | 0       | 0       | 7445    | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 208221 | 0      | 0      | 208221 | 0       | 200000  | 0       | 200000  | 311301  | 507331   | 0       | 818632   | 32030.0  | 18997.0  | 16720.0  | 67747.0  | 11038.0 | 0.0     | 0.0     | 11038.0 | 926695.0  | 1640172.0  | 212390.0 | 2779257.0  | 346855   | 24883    | 43078    | 414816   | 208221   | 1308     | 209529   | 5795     | 72670    | 78465    | 702810   | 382160   | 298558   | 680718   | 43742    | 724460   | 822347.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   | NEH/US NEWSPAPER PROJECT; LIBRARY OF CONGRESS/LEADERS ARE READERS | 9        | 773020800 | 804470400 | 201939.0 | 2753780.0 | 3754743.0 | 10986669.0 | 50785.0   | 14792197.0 | 211353.0 | 17757330.0 | 1913369.0 | 195079.0 | 443393.0 | 2551841.0 | 0.0      |      |      |      |      |      | 247842   | 2429864  | 0        | 2677706  | 63143    | 687506   | 0        | 750649   | 310985   | 3117370  | 0        | 3428355  | 69968    | 264542   | 1107     | 335617   | 571339   | 393860   | 206853   | 1172052  | 952292   | 3775772  | 207960   | 4936024  | 1170334 | 10949669 | 0       | 12120003 | 0       | 0       | 0       | 0       | 46000   | 37000   | 0       | 83000   | 0       | 0       | 0       | 0       | 314531  | 0       | 0       | 314531  | 195079 | 0      | 0      | 195079 | 800     | 0       | 0       | 800     | 1726744 | 10986669 | 0       | 12713413 | 74744.0  | 29756.0  | 3393.0   | 107893.0 | 0.0     | 0.0     | 0.0     | 0.0     | 2753780.0 | 14792197.0 | 211353.0 | 17757330.0 | 343202   | 1530865  | 39302    | 1913369  | 195079   | 0        | 195079   | 442593   | 800      | 443393   | 2551841  | 0        | 0        | 0        | 0        | 0        | 6631836.0 | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   |                                                                   | 11       | 780969600 | 812419200 | 0.0      | 592729.0  | 845931.0  | 442397.0   | 24359.0   | 1312687.0  | 10000.0  | 1915416.0  | 372123.0  | 129437.0 | 91169.0  | 592729.0  | 0.0      |      |      |      |      |      | 239022   | 399892   | 0        | 638914   | 47002    | 123539   | 0        | 170541   | 286024   | 523431   | 0        | 809455   | 65118    | 33441    | 2424     | 100983   | 76386    | 243256   | 9061     | 328703   | 427528   | 800128   | 11485    | 1239141  | 0       | 442397   | 0       | 442397   | 0       | 0       | 0       | 0       | 36620   | 0       | 0       | 36620   | 0       | 50000   | 0       | 50000   | 0       | 0       | 0       | 0       | 129437 | 0      | 0      | 129437 | 0       | 0       | 0       | 0       | 166057  | 492397   | 0       | 658454   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 593585.0  | 1292525.0  | 11485.0  | 1897595.0  | 311503   | 36620    | 24000    | 372123   | 129437   | 0        | 129437   | 91169    | 0        | 91169    | 592729   | 0        | 0        | 0        | 0        | 0        | 643042.0  | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   |                                                                   | 10       | 773020800 | 804470400 | 0.0      | 942432.0  | 1823704.0 | 862254.0   | 0.0       | 2685958.0  | 136189.0 | 3764579.0  | 640009.0  | 155624.0 | 146799.0 | 942432.0  | 0.0      |      |      |      |      |      | 206923   | 911202   | 58516    | 1176641  | 44552    | 209103   | 11824    | 265479   | 251475   | 1120305  | 70340    | 1442120  | 63       | 83926    | 0        | 83989    | 147793   | 518432   | 57090    | 723315   | 399331   | 1722663  | 127430   | 2249424  | 48597   | 362592   | 0       | 411189   | 0       | 0       | 0       | 0       | 18600   | 132795  | 0       | 151395  | 173541  | 424608  | 0       | 598149  | 70116   | 135837  | 0       | 205953  | 125501 | 0      | 0      | 125501 | 590     | 0       | 0       | 590     | 436945  | 1055832  | 0       | 1492777  | 21001.0  | 150509.0 | 20041.0  | 191551.0 | 0.0     | 0.0     | 0.0     | 0.0     | 857277.0  | 2929004.0  | 147471.0 | 3933752.0  | 366754   | 162438   | 36142    | 565334   | 125501   | 0        | 125501   | 18026    | 148416   | 166442   | 857277   | 0        | 0        | 0        | 0        | 0        | 1580976.0 | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    | NEH-PRESERVATION                                                  | 12       | 773020800 | 804470400 | 30116.0  | 922812.0  | 1606413.0 | 80000.0    | 0.0       | 1686413.0  | 31712.0  | 2640937.0  | 505057.0  | 152171.0 | 130688.0 | 787916.0  | 104780.0 |      |      | X    |      |      | 237002   | 1015540  | 0        | 1252542  | 75476    | 285892   | 0        | 361368   | 312478   | 1301432  | 0        | 1613910  | 8742     | 135000   | 4103     | 147845   | 604240   | 123250   | 34144    | 761634   | 925460   | 1559682  | 38247    | 2523389  | 0       | 0        | 0       | 0        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 80000   | 0       | 80000   | 0       | 0       | 0       | 0       | 175451 | 0      | 0      | 175451 | 0       | 0       | 0       | 0       | 175451  | 80000    | 0       | 255451   | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0     | 0.0     | 1100911.0 | 1639682.0  | 38247.0  | 2778840.0  | 551986   | 26225    | 30000    | 608211   | 175451   | 17660    | 193111   | 111058   | 17000    | 128058   | 929380   | 0        | 0        | 0        | 0        | 0        | 1125000.0 | 
```