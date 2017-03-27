# State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1997-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/xzhn-73j5) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/xzhn-73j5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/xzhn-73j5/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | xzhn-73j5 |
| Name | State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1997, revenue, expenditures |
| Created | 2016-12-20T15:17:37Z |
| Publication Date | 2016-12-20T17:04:26Z |

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
series e:xzhn-73j5 d:1996-07-01T00:00:00.000Z t:physzip4=571.0 t:physcity=JUNEAU t:mailcity=JUNEAU t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571.0 t:mailaddr="P.O. BOX 110571" t:fiothsp="NEH (NEWSPAPER PROJECT)" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:t1expadm=0 m:totox_ao=0 m:totex123=619028 m:oexpbenb=854037 m:oexpbena=16621 m:oexpbend=870658 m:oexpbenc=0 m:fit3=61512 m:fit2=124343 m:fit1=399336 m:totincm=4804300 m:t1expgrt=128594 m:othincm=0 m:totexpt1=424184 m:totexpt3=75597 m:totexpt2=119247 m:fitott13=585191 m:sistlaop=2878627 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=2674056 m:aidothd=0 m:totopexa=136163 m:aidothc=0 m:totopexb=2537893 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=284724 m:t2expgrt=119247 m:oexpotha=93914 m:oexpothb=190810 m:oexpsalb=1316876 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=25628 m:totaidd=1581502 m:aidsald=491358 m:aidoilb=54044 m:t1expstw=295590 m:totaidc=0 m:aidoilc=0 m:aidsalb=120171 m:aidoild=54044 m:oexpsald=1342504 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=75597 m:capitalb=94676 m:capitala=0 m:totaidb=962474 m:totaida=619028 m:siother=152483 m:capitald=94676 m:aidsala=371187 m:aidlcd=129747 m:aidlcc=0 m:t2expadm=0 m:period_e=607800 m:allopstf=0 m:fioth=262699 m:aidlca=119247 m:aidlcb=10500 m:t3expgrt=0 m:totexpd=4350234 m:allopcap=0 m:totexpa=755191 m:totexpc=0 m:totexpb=3595043 m:totoxstc=0 m:totoxstd=2213162 m:total_fi=847890 m:aidplsc=0 m:aidplsd=0 m:fiotht48=0 m:total_si=3956410 m:totoxstb=2170913 m:totoxsta=42249 m:oexpcold=176170 m:aidplsa=0 m:oexpcolb=176170 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=0 m:aidipld=906353 m:siaidlib=925300 m:aidipla=128594 m:aidiplb=777759

series e:xzhn-73j5 d:1996-10-01T00:00:00.000Z t:physzip4=1.0 t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailzip4=1.0 t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:t1expadm=19325 m:totox_ao=0 m:totex123=2044454 m:oexpbenb=406272 m:oexpbena=0 m:oexpbend=406272 m:oexpbenc=0 m:fit3=288548 m:fit2=459715 m:fit1=1327873 m:totincm=9856831 m:t1expgrt=671299 m:othincm=0 m:totexpt1=1293308 m:totexpt3=288548 m:totexpt2=462598 m:fitott13=2076136 m:sistlaop=2731344 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=3640204 m:aidothd=0 m:totopexa=908860 m:aidothc=0 m:totopexb=2731344 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=1161412 m:t2expgrt=462598 m:oexpotha=572311 m:oexpothb=589101 m:oexpsalb=1726005 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=0 m:totaidd=6184945 m:aidsald=0 m:aidoilb=0 m:t1expstw=602684 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1726005 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=286870 m:capitalb=0 m:capitala=0 m:totaidb=5049351 m:totaida=1135594 m:siother=0 m:capitald=0 m:aidsala=0 m:aidlcd=462598 m:aidlcc=0 m:t2expadm=0 m:period_e=4137511 m:allopstf=0 m:fioth=0 m:aidlca=462598 m:aidlcb=0 m:t3expgrt=1678 m:totexpd=9825149 m:allopcap=0 m:totexpa=2044454 m:totexpc=0 m:totexpb=7780695 m:totoxstc=0 m:totoxstd=2132277 m:total_fi=2076136 m:aidplsc=0 m:aidplsd=1071576 m:fiotht48=0 m:total_si=7780695 m:totoxstb=2132277 m:totoxsta=0 m:oexpcold=346515 m:aidplsa=113286 m:oexpcolb=9966 m:aidplsb=958290 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=336549 m:aidipld=4650771 m:siaidlib=5049351 m:aidipla=559710 m:aidiplb=4091061

series e:xzhn-73j5 d:1996-07-01T00:00:00.000Z t:physzip4=1081.0 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1081.0 t:mailaddr="ONE CAPITOL MALL" t:stlaname="ARKANSAS STATE LIBRARY" m:t1expadm=12018 m:totox_ao=0 m:totex123=1356431 m:oexpbenb=320846 m:oexpbena=80437 m:oexpbend=401283 m:oexpbenc=0 m:fit3=128516 m:fit2=200163 m:fit1=1020226 m:totincm=7130238 m:t1expgrt=203141 m:othincm=0 m:totexpt1=875505 m:totexpt3=165515 m:totexpt2=315411 m:fitott13=1348905 m:sistlaop=2453535 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=3213037 m:aidothd=2649 m:totopexa=784607 m:aidothc=0 m:totopexb=2428430 m:aidothb=0 m:oexpothc=0 m:aidotha=2649 m:oexpothd=966613 m:t2expgrt=315411 m:oexpotha=316427 m:oexpothb=650186 m:oexpsalb=1215368 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=238595 m:totaidd=4167761 m:aidsald=3000 m:aidoilb=0 m:t1expstw=660346 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1453963 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=159515 m:capitalb=25014 m:capitala=47272 m:totaidb=3327798 m:totaida=839963 m:siother=0 m:capitald=72286 m:aidsala=3000 m:aidlcd=315411 m:aidlcc=0 m:t2expadm=0 m:period_e=2264510 m:allopstf=0 m:fioth=0 m:aidlca=315411 m:aidlcb=0 m:t3expgrt=6000 m:totexpd=7453084 m:allopcap=0 m:totexpa=1671842 m:totexpc=0 m:totexpb=5781242 m:totoxstc=0 m:totoxstd=1855246 m:total_fi=1348905 m:aidplsc=0 m:aidplsd=3061719 m:fiotht48=0 m:total_si=5781333 m:totoxstb=1536214 m:totoxsta=319032 m:oexpcold=391178 m:aidplsa=442173 m:oexpcolb=242030 m:aidplsb=2619546 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=149148 m:aidipld=784982 m:siaidlib=3327798 m:aidipla=76730 m:aidiplb=708252
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

metric m:t1expstw p:double l:"Title I exp statwide" t:dataTypeName=money

metric m:t1expgrt p:double l:"Title I exp grants" t:dataTypeName=money

metric m:t1expadm p:double l:"Title I exp LSCA admin" t:dataTypeName=money

metric m:totexpt1 p:double l:"Title I exp TOTAL" t:dataTypeName=money

metric m:t2expgrt p:double l:"Title II exp grants" t:dataTypeName=money

metric m:t2expadm p:double l:"Title II exp LSCA admin" t:dataTypeName=money

metric m:totexpt2 p:double l:"Title II exp TOTAL" t:dataTypeName=money

metric m:t3expstw p:double l:"Title III exp statewide" t:dataTypeName=money

metric m:t3expgrt p:double l:"Title III exp grants" t:dataTypeName=money

metric m:totexpt3 p:double l:"Title III exp TOTAL" t:dataTypeName=money

metric m:totex123 p:double l:"Titles I-III exp TOTAL" t:dataTypeName=money

metric m:allopstf p:double l:"Oper exp staff total" t:dataTypeName=money

metric m:allopoth p:double l:"Oper exp other total" t:dataTypeName=money

metric m:totox_ao p:double l:"Oper exp TOTAL" t:dataTypeName=money

metric m:allopcap p:double l:"Capital outlay" t:dataTypeName=money

metric m:totexpao p:double l:"Total expenditures" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:xzhn-73j5 l:"State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/xzhn-73j5

property e:xzhn-73j5 t:meta.view v:id=xzhn-73j5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:xzhn-73j5 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:xzhn-73j5 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:xzhn-73j5 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:xzhn-73j5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```