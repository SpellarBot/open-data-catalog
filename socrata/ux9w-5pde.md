# State Libraries Survey, FY 1996, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1996-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/ux9w-5pde) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ux9w-5pde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ux9w-5pde/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ux9w-5pde |
| Name | State Libraries Survey, FY 1996, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1996, revenue, expenditures |
| Created | 2016-12-20T15:15:54Z |
| Publication Date | 2016-12-20T17:04:25Z |

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
series e:ux9w-5pde d:1995-07-01T00:00:00.000Z t:physzip4=571.0 t:physcity=JUNEAU t:mailcity=JUNEAU t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:physzip=99811 t:mailzip=99811 t:mailzip4=571.0 t:mailaddr="P.O. BOX 110571" t:fiothsp="NEH NEWSPAPER PROJECT" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:t1expadm=0 m:totox_ao=0 m:totex123=494852 m:oexpbenb=832040 m:oexpbena=32143 m:oexpbend=864183 m:oexpbenc=0 m:fit3=75597 m:fit2=124661 m:fit1=384026 m:totincm=4655484 m:t1expgrt=90553 m:othincm=0 m:totexpt1=361821 m:totexpt3=31285 m:totexpt2=101746 m:fitott13=584284 m:sistlaop=2644600 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=2653330 m:aidothd=0 m:totopexa=115917 m:aidothc=0 m:totopexb=2537413 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=398991 m:t2expgrt=101746 m:oexpotha=34212 m:oexpothb=364779 m:oexpsalb=1282721 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=49562 m:totaidd=1382733 m:aidsald=285158 m:aidoilb=120567 m:t1expstw=271268 m:totaidc=0 m:aidoilc=0 m:aidsalb=13890 m:aidoild=120567 m:oexpsald=1332283 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=31285 m:capitalb=0 m:capitala=0 m:totaidb=919166 m:totaida=463567 m:siother=226300 m:capitald=0 m:aidsala=271268 m:aidlcd=101746 m:aidlcc=0 m:t2expadm=0 m:period_e=615900 m:allopstf=0 m:fioth=275000 m:aidlca=101746 m:aidlcb=0 m:t3expgrt=0 m:totexpd=4036063 m:allopcap=0 m:totexpa=579484 m:totexpc=0 m:totexpb=3456579 m:totoxstc=0 m:totoxstd=2196466 m:total_fi=859284 m:aidplsc=0 m:aidplsd=0 m:fiotht48=0 m:total_si=3796200 m:totoxstb=2114761 m:totoxsta=81705 m:oexpcold=57873 m:aidplsa=0 m:oexpcolb=57873 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=0 m:aidipld=875262 m:siaidlib=925300 m:aidipla=90553 m:aidiplb=784709

series e:ux9w-5pde d:1995-10-01T00:00:00.000Z t:physzip4=1.0 t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:physzip=36117 t:mailzip=36130 t:mailzip4=1.0 t:mailaddr="6030 MONTICELLO DRIVE" t:fiothsp="PRIOR YEAR REFUNDS" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:t1expadm=17200 m:totox_ao=0 m:totex123=1909812 m:oexpbenb=403667 m:oexpbena=0 m:oexpbend=403667 m:oexpbenc=0 m:fit3=11274 m:fit2=256083 m:fit1=1270562 m:totincm=8824415 m:t1expgrt=835252 m:othincm=0 m:totexpt1=1275910 m:totexpt3=377820 m:totexpt2=256082 m:fitott13=1537919 m:sistlaop=2731791 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=3403175 m:aidothd=0 m:totopexa=671813 m:aidothc=0 m:totopexb=2731362 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=870983 m:t2expgrt=256082 m:oexpotha=472032 m:oexpothb=398951 m:oexpsalb=1703170 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=0 m:totaidd=5787356 m:aidsald=0 m:aidoilb=0 m:t1expstw=423458 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1703170 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=231155 m:capitalb=0 m:capitala=0 m:totaidb=4549357 m:totaida=1237999 m:siother=0 m:capitald=0 m:aidsala=0 m:aidlcd=256083 m:aidlcc=0 m:t2expadm=0 m:period_e=4137511 m:allopstf=0 m:fioth=5348 m:aidlca=256083 m:aidlcb=0 m:t3expgrt=146665 m:totexpd=9190531 m:allopcap=0 m:totexpa=1909812 m:totexpc=0 m:totexpb=7280719 m:totoxstc=0 m:totoxstd=2106837 m:total_fi=1543267 m:aidplsc=0 m:aidplsd=882982 m:fiotht48=0 m:total_si=7281148 m:totoxstb=2106837 m:totoxsta=0 m:oexpcold=425355 m:aidplsa=19583 m:oexpcolb=225574 m:aidplsb=863399 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=199781 m:aidipld=4648291 m:siaidlib=4549357 m:aidipla=962333 m:aidiplb=3685958

series e:ux9w-5pde d:1995-07-01T00:00:00.000Z t:physzip4=1081.0 t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL" t:phys_st=AR t:physzip=72201 t:mailzip=72201 t:mailzip4=1081.0 t:mailaddr="ONE CAPITOL MALL" t:stlaname="ARKANSAS STATE LIBRARY" m:t1expadm=8659 m:totox_ao=0 m:totex123=1323016 m:oexpbenb=312517 m:oexpbena=77396 m:oexpbend=389913 m:oexpbenc=0 m:fit3=184007 m:fit2=199765 m:fit1=944470 m:totincm=7079519 m:t1expgrt=199334 m:othincm=0 m:totexpt1=813383 m:totexpt3=228453 m:totexpt2=281180 m:fitott13=1328242 m:sistlaop=2423479 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:totopexd=3176532 m:aidothd=0 m:totopexa=785248 m:aidothc=0 m:totopexb=2391284 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=1048666 m:t2expgrt=281180 m:oexpotha=402040 m:oexpothb=646626 m:oexpsalb=1179679 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=234318 m:totaidd=3809535 m:aidsald=0 m:aidoilb=0 m:t1expstw=605390 m:totaidc=0 m:aidoilc=0 m:aidsalb=0 m:aidoild=0 m:oexpsald=1413997 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:t3expstw=227230 m:capitalb=30083 m:capitala=56032 m:totaidb=3327798 m:totaida=481737 m:siother=0 m:capitald=86115 m:aidsala=0 m:aidlcd=281180 m:aidlcc=0 m:t2expadm=0 m:period_e=2268207 m:allopstf=0 m:fioth=0 m:aidlca=281180 m:aidlcb=0 m:t3expgrt=1223 m:totexpd=7072182 m:allopcap=0 m:totexpa=1323017 m:totexpc=0 m:totexpb=5749165 m:totoxstc=0 m:totoxstd=1803910 m:total_fi=1328242 m:aidplsc=0 m:aidplsd=2823015 m:fiotht48=0 m:total_si=5751277 m:totoxstb=1492196 m:totoxsta=311714 m:oexpcold=323956 m:aidplsa=182849 m:oexpcolb=252462 m:aidplsb=2640166 m:oexpcolc=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=71494 m:aidipld=705340 m:siaidlib=3327798 m:aidipla=17708 m:aidiplb=687632
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

entity e:ux9w-5pde l:"State Libraries Survey, FY 1996, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ux9w-5pde

property e:ux9w-5pde t:meta.view v:id=ux9w-5pde v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1996, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:ux9w-5pde t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ux9w-5pde t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:ux9w-5pde t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:ux9w-5pde t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | fiothsp                                            | pub_fips | fystart   | fyend     | fioth     | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm    | fit1      | fit2      | fit3      | fitott13   | fiotht48 | fit4 | fit5 | fit6 | fit7 | fit8 | oexpsala | oexpsalb  | oexpsalc | oexpsald  | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb  | totoxstc | totoxstd  | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc | oexpothd  | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc | aidipld    | aidplsa   | aidplsb   | aidplsc | aidplsd   | aidoila  | aidoilb  | aidoilc | aidoild  | aidmlsa  | aidmlsb   | aidmlsc | aidmlsd   | aidsala  | aidsalb   | aidsalc | aidsald   | aidlca    | aidlcb    | aidlcc | aidlcd    | aidotha  | aidothb  | aidothc | aidothd  | totaida    | totaidb    | totaidc | totaidd    | capitala | capitalb | capitalc | capitald | othexpa | othexpb  | othexpc  | othexpd  | totexpa    | totexpb    | totexpc   | totexpd    | t1expstw  | t1expgrt  | t1expadm | totexpt1  | t2expgrt  | t2expadm | totexpt2  | t3expstw | t3expgrt  | totexpt3  | totex123   | allopstf  | allopoth | totox_ao  | allopcap | totexpao  | period_e   | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ================================================== | ======== | ========= | ========= | ========= | ========== | ========== | ========== | ========= | ========== | ========= | ========== | ========= | ========= | ========= | ========== | ======== | ==== | ==== | ==== | ==== | ==== | ======== | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ========= | ========= | ======== | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ======= | ========== | ========= | ========= | ======= | ========= | ======== | ======== | ======= | ======== | ======== | ========= | ======= | ========= | ======== | ========= | ======= | ========= | ========= | ========= | ====== | ========= | ======== | ======== | ======= | ======== | ========== | ========== | ======= | ========== | ======== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ========== | ========== | ========= | ========== | ========= | ========= | ======== | ========= | ========= | ======== | ========= | ======== | ========= | ========= | ========== | ========= | ======== | ========= | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    | NEH NEWSPAPER PROJECT                              | 2        | 804556800 | 836092800 | 275000.0  | 859284.0   | 2644600.0  | 925300.0   | 226300.0  | 3796200.0  | 0.0       | 4655484.0  | 384026.0  | 124661.0  | 75597.0   | 584284.0   | 0.0      |      |      |      |      |      | 49562.0  | 1282721.0 | 0.0      | 1332283.0 | 32143.0  | 832040.0  | 0.0      | 864183.0  | 81705.0   | 2114761.0 | 0.0      | 2196466.0 | 0.0      | 57873.0   | 0.0      | 57873.0   | 34212.0   | 364779.0  | 0.0      | 398991.0  | 115917.0  | 2537413.0  | 0.0       | 2653330.0  | 90553.0   | 784709.0   | 0.0     | 875262.0   | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 120567.0 | 0.0     | 120567.0 | 0.0      | 0.0       | 0.0     | 0.0       | 271268.0 | 13890.0   | 0.0     | 285158.0  | 101746.0  | 0.0       | 0.0    | 101746.0  | 0.0      | 0.0      | 0.0     | 0.0      | 463567.0   | 919166.0   | 0.0     | 1382733.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0      | 579484.0   | 3456579.0  | 0.0       | 4036063.0  | 271268.0  | 90553.0   | 0.0      | 361821.0  | 101746.0  | 0.0      | 101746.0  | 31285.0  | 0.0       | 31285.0   | 494852.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 615900.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1.0      | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   | 1.0      | PRIOR YEAR REFUNDS                                 | 1        | 812505600 | 844041600 | 5348.0    | 1543267.0  | 2731791.0  | 4549357.0  | 0.0       | 7281148.0  | 0.0       | 8824415.0  | 1270562.0 | 256083.0  | 11274.0   | 1537919.0  | 0.0      |      |      |      |      |      | 0.0      | 1703170.0 | 0.0      | 1703170.0 | 0.0      | 403667.0  | 0.0      | 403667.0  | 0.0       | 2106837.0 | 0.0      | 2106837.0 | 199781.0 | 225574.0  | 0.0      | 425355.0  | 472032.0  | 398951.0  | 0.0      | 870983.0  | 671813.0  | 2731362.0  | 0.0       | 3403175.0  | 962333.0  | 3685958.0  | 0.0     | 4648291.0  | 19583.0   | 863399.0  | 0.0     | 882982.0  | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 256083.0  | 0.0       | 0.0    | 256083.0  | 0.0      | 0.0      | 0.0     | 0.0      | 1237999.0  | 4549357.0  | 0.0     | 5787356.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0      | 1909812.0  | 7280719.0  | 0.0       | 9190531.0  | 423458.0  | 835252.0  | 17200.0  | 1275910.0 | 256082.0  | 0.0      | 256082.0  | 231155.0 | 146665.0  | 377820.0  | 1909812.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 4137511.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLE ROCK | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLE ROCK | AR      | 72201   | 1081.0   |                                                    | 5        | 804556800 | 836092800 | 0.0       | 1328242.0  | 2423479.0  | 3327798.0  | 0.0       | 5751277.0  | 0.0       | 7079519.0  | 944470.0  | 199765.0  | 184007.0  | 1328242.0  | 0.0      |      |      |      |      |      | 234318.0 | 1179679.0 | 0.0      | 1413997.0 | 77396.0  | 312517.0  | 0.0      | 389913.0  | 311714.0  | 1492196.0 | 0.0      | 1803910.0 | 71494.0  | 252462.0  | 0.0      | 323956.0  | 402040.0  | 646626.0  | 0.0      | 1048666.0 | 785248.0  | 2391284.0  | 0.0       | 3176532.0  | 17708.0   | 687632.0   | 0.0     | 705340.0   | 182849.0  | 2640166.0 | 0.0     | 2823015.0 | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 281180.0  | 0.0       | 0.0    | 281180.0  | 0.0      | 0.0      | 0.0     | 0.0      | 481737.0   | 3327798.0  | 0.0     | 3809535.0  | 56032.0  | 30083.0  | 0.0      | 86115.0  | 0.0     | 0.0      | 0.0      | 0.0      | 1323017.0  | 5749165.0  | 0.0       | 7072182.0  | 605390.0  | 199334.0  | 8659.0   | 813383.0  | 281180.0  | 0.0      | 281180.0  | 227230.0 | 1223.0    | 228453.0  | 1323016.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 2268207.0  | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   | NEH - NEWSPAPER PROJECT                            | 4        | 804556800 | 836092800 | 125510.0  | 2107449.0  | 4763400.0  | 452000.0   | 60000.0   | 5275400.0  | 180330.0  | 7563179.0  | 1436919.0 | 265757.0  | 279263.0  | 1981939.0  | 0.0      |      |      |      |      |      | 75125.0  | 2665490.0 | 0.0      | 2740615.0 | 14968.0  | 608439.0  | 0.0      | 623407.0  | 90093.0   | 3273929.0 | 0.0      | 3364022.0 | 4057.0   | 463408.0  | 0.0      | 467465.0  | 290878.0  | 896563.0  | 0.0      | 1187441.0 | 385028.0  | 4633900.0  | 0.0       | 5018928.0  | 215020.0  | 452600.0   | 0.0     | 667620.0   | 0.0       | 0.0       | 0.0     | 0.0       | 5655.0   | 60000.0  | 0.0     | 65655.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 180217.0  | 0.0       | 0.0    | 180217.0  | 0.0      | 0.0      | 0.0     | 0.0      | 400892.0   | 512600.0   | 0.0     | 913492.0   | 21936.0  | 128900.0 | 0.0      | 150836.0 | 21939.0 | 0.0      | 173676.0 | 195615.0 | 829795.0   | 5275400.0  | 173676.0  | 6278871.0  | 19394.0   | 198841.0  | 90093.0  | 308328.0  | 180217.0  | 0.0      | 180217.0  | 270918.0 | 48396.0   | 319314.0  | 807859.0   | 90093.0   | 14528.0  | 104621.0  | 21936.0  | 126557.0  | 4021832.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      |                                                    | 6        | 804556800 | 836092800 | 0.0       | 11924725.0 | 13940276.0 | 22287433.0 | 0.0       | 36227709.0 | 610406.0  | 48762840.0 | 8660825.0 | 1378473.0 | 1885427.0 | 11924725.0 | 0.0      |      |      |      |      |      | 935150.0 | 5502386.0 | 316172.0 | 6753708.0 | 252146.0 | 1655288.0 | 51664.0  | 1959098.0 | 1187296.0 | 7157674.0 | 367836.0 | 8712806.0 | 414942.0 | 1051836.0 | 117134.0 | 1583912.0 | 1168813.0 | 5730766.0 | 125436.0 | 7025015.0 | 2771051.0 | 13940276.0 | 610406.0  | 17321733.0 | 4593420.0 | 19022945.0 | 0.0     | 23616365.0 | 3011425.0 | 0.0       | 0.0     | 3011425.0 | 645752.0 | 0.0      | 0.0     | 645752.0 | 0.0      | 3160000.0 | 0.0     | 3160000.0 | 404042.0 | 0.0       | 0.0     | 404042.0  | 1547000.0 | 0.0       | 0.0    | 1547000.0 | 0.0      | 104488.0 | 0.0     | 104488.0 | 10201639.0 | 22287433.0 | 0.0     | 32489072.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0      | 12972690.0 | 36227709.0 | 610406.0  | 49810805.0 | 2639864.0 | 5818968.0 | 201993.0 | 8660825.0 | 1546989.0 | 0.0      | 1546989.0 | 0.0      | 2555267.0 | 2555267.0 | 12763081.0 | 1792643.0 | 717053.0 | 2509696.0 | 0.0      | 2509696.0 | 32323595.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   | USDOE/MULTITYPELIBRARY AND CHAPTER 2,COMMERCE/NTIA | 8        | 804556800 | 836092800 | 1467149.0 | 3226539.0  | 1146666.0  | 3398559.0  | 235000.0  | 4780225.0  | 45021.0   | 8051785.0  | 1166685.0 | 265325.0  | 327380.0  | 1759390.0  | 0.0      |      |      |      |      |      | 793704.0 | 779479.0  | 34878.0  | 1608061.0 | 140066.0 | 137555.0  | 6155.0   | 283776.0  | 933770.0  | 917034.0  | 41033.0  | 1891837.0 | 11000.0  | 66849.0   | 0.0      | 77849.0   | 588652.0  | 162783.0  | 3988.0   | 755423.0  | 1533422.0 | 1146666.0  | 45021.0   | 2725109.0  | 422753.0  | 134114.0   | 0.0     | 556867.0   | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 40059.0  | 1850654.0 | 0.0     | 1890713.0 | 0.0      | 1251785.0 | 0.0     | 1251785.0 | 222827.0  | 0.0       | 0.0    | 222827.0  | 595066.0 | 162006.0 | 0.0     | 757072.0 | 1280705.0  | 3398559.0  | 0.0     | 4679264.0  | 79551.0  | 0.0      | 0.0      | 79551.0  | 52879.0 | 0.0      | 0.0      | 52879.0  | 2946557.0  | 4545225.0  | 45021.0   | 7536803.0  | 618778.0  | 507175.0  | 40732.0  | 1166685.0 | 222827.0  | 42498.0  | 265325.0  | 127371.0 | 200009.0  | 327380.0  | 1759390.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 3746235.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   | CT NEWSPAPER PROJ CATALOG                          | 9        | 804556800 | 836092800 | 239775.0  | 1934455.0  | 9125153.0  | 4583772.0  | 0.0       | 13708925.0 | 3092263.0 | 18735643.0 | 1194152.0 | 233224.0  | 232304.0  | 1659680.0  | 35000.0  |      |      | X    |      |      | 629452.0 | 4473844.0 | 9140.0   | 5112436.0 | 249157.0 | 0.0       | 3657.0   | 252814.0  | 878609.0  | 4473844.0 | 12797.0  | 5365250.0 | 67076.0  | 703423.0  | 541268.0 | 1311767.0 | 940799.0  | 3809396.0 | 877937.0 | 5628132.0 | 1886484.0 | 8986663.0  | 1432002.0 | 12305149.0 | 138316.0  | 1151611.0  | 0.0     | 1289927.0  | 0.0       | 0.0       | 0.0     | 0.0       | 13498.0  | 0.0      | 0.0     | 13498.0  | 82094.0  | 807829.0  | 0.0     | 889923.0  | 60000.0  | 0.0       | 0.0     | 60000.0   | 197601.0  | 2624332.0 | 0.0    | 2821933.0 | 0.0      | 0.0      | 0.0     | 0.0      | 491509.0   | 4583772.0  | 0.0     | 5075281.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0      | 2377993.0  | 13570435.0 | 1432002.0 | 17380430.0 | 871708.0  | 251171.0  | 1459.0   | 1124338.0 | 197601.0  | 0.0      | 197601.0  | 410064.0 | 39850.0   | 449914.0  | 1771853.0  | 799742.0  | 62949.0  | 862691.0  | 0.0      | 862691.0  | 3275251.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   |                                                    | 11       | 812505600 | 844041600 | 0.0       | 518459.0   | 1913000.0  | 0.0        | 0.0       | 1913000.0  | 0.0       | 2431459.0  | 309000.0  | 123192.0  | 51267.0   | 483459.0   | 35000.0  |      |      | X    |      |      | 242151.0 | 1396947.0 | 0.0      | 1639098.0 | 40949.0  | 73524.0   | 0.0      | 114473.0  | 283100.0  | 1470471.0 | 0.0      | 1753571.0 | 125431.0 | 136543.0  | 0.0      | 261974.0  | 153133.0  | 143547.0  | 0.0      | 296680.0  | 561664.0  | 1750561.0  | 0.0       | 2312225.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0       | 0.0    | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 0.0        | 0.0        | 0.0     | 0.0        | 0.0      | 162439.0 | 0.0      | 162439.0 | 0.0     | 0.0      | 0.0      | 0.0      | 561664.0   | 1913000.0  | 0.0       | 2474664.0  | 0.0       | 272306.0  | 4451.0   | 276757.0  | 191567.0  | 0.0      | 191567.0  | 0.0      | 51267.0   | 51267.0   | 519591.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 606900.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   | DEPT OF AGRICULTURE - FSCS                         | 10       | 804556800 | 836092800 | 1397.0    | 555276.0   | 589500.0   | 1171600.0  | 1779000.0 | 3540100.0  | 0.0       | 4095376.0  | 364488.0  | 128731.0  | 60660.0   | 553879.0   | 0.0      |      |      |      |      |      | 247910.0 | 274679.0  | 0.0      | 522589.0  | 69614.0  | 86140.0   | 0.0      | 155754.0  | 317524.0  | 360819.0  | 0.0      | 678343.0  | 21516.0  | 28483.0   | 0.0      | 49999.0   | 72558.0   | 133504.0  | 0.0      | 206062.0  | 411598.0  | 522806.0   | 0.0       | 934404.0   | 22204.0   | 1173293.0  | 0.0     | 1195497.0  | 289642.0  | 305485.0  | 0.0     | 595127.0  | 12772.0  | 0.0      | 0.0     | 12772.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0      | 0.0       | 0.0     | 0.0       | 185212.0  | 157267.0  | 0.0    | 342479.0  | 0.0      | 0.0      | 0.0     | 0.0      | 509830.0   | 1636045.0  | 0.0     | 2145875.0  | 16117.0  | 1557.0   | 0.0      | 17674.0  | 0.0     | 264353.0 | 0.0      | 264353.0 | 937545.0   | 2424761.0  | 0.0       | 3362306.0  | 310816.0  | 19077.0   | 0.0      | 329893.0  | 489098.0  | 60000.0  | 549098.0  | 34417.0  | 24137.0   | 58554.0   | 937545.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0       | 666168.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    | NATIONAL ARCHIVES                                  | 12       | 804556800 | 836092800 | 25000.0   | 5986892.0  | 7254353.0  | 25000003.0 | 600000.0  | 32854356.0 | 0.0       | 38841248.0 | 4435130.0 | 667540.0  | 859222.0  | 5961892.0  | 0.0      |      |      |      |      |      | 418234.0 | 2453781.0 | 0.0      | 2872015.0 | 146381.0 | 858823.0  | 0.0      | 1005204.0 | 564615.0  | 3312604.0 | 0.0      | 3877219.0 | 262737.0 | 360753.0  | 0.0      | 623490.0  | 570521.0  | 2830996.0 | 0.0      | 3401517.0 | 1397873.0 | 6504353.0  | 0.0       | 7902226.0  | 2646287.0 | 25000000.0 | 0.0     | 27646287.0 | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0      | 0.0     | 0.0      | 862134.0 | 750000.0  | 0.0     | 1612134.0 | 0.0      | 0.0       | 0.0     | 0.0       | 815413.0  | 2122485.0 | 0.0    | 2937898.0 | 0.0      | 0.0      | 0.0     | 0.0      | 4323834.0  | 27872485.0 | 0.0     | 32196319.0 | 48493.0  | 0.0      | 0.0      | 48493.0  | 0.0     | 0.0      | 0.0      | 0.0      | 5770200.0  | 34376838.0 | 0.0       | 40147038.0 | 1399994.0 | 2329925.0 | 82898.0  | 3812817.0 | 815413.0  | 0.0      | 815413.0  | 332847.0 | 809123.0  | 1141970.0 | 5770200.0  | 1424888.0 | 674428.0 | 2099316.0 | 48493.0  | 2147809.0 | 14149317.0 | 
```