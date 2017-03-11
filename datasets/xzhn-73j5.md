# State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures

## Dataset

* [Dataset URL](https://data.imls.gov/api/views/xzhn-73j5/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/state-libraries-survey-fy-1997-part-3-revenue-expenditures)
* Id = xzhn-73j5
* Name = State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures
* Attribution = IMLS
* Attribution Link = https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey
* Category = State Library Administrative Agencies Survey
* Tags = [state library, slaa, 1997, revenue, expenditures]
* Created = 2016-12-20T15:17:37Z
* Publication Date = 2016-12-20T17:04:26Z
* Rows Updated = 2016-12-20T17:17:14Z

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Name                               | Field Name | Data Type | Render Type | Schema Type    | Included | 
| ================================== | ========== | ========= | =========== | ============== | ======== | 
| STLA Name                          | stlaname   | text      | text        | series tag     | Yes      | 
| Street                             | physaddr   | text      | text        | series tag     | Yes      | 
| City                               | physcity   | text      | text        | series tag     | Yes      | 
| State                              | phys_st    | text      | text        | series tag     | Yes      | 
| Zip                                | physzip    | number    | text        | numeric metric | Yes      | 
| Zip+4                              | physzip4   | number    | text        | numeric metric | Yes      | 
| Street (mail)                      | mailaddr   | text      | text        | series tag     | Yes      | 
| City (mail)                        | mailcity   | text      | text        | series tag     | Yes      | 
| State (mail)                       | mail_st    | text      | text        | series tag     | Yes      | 
| Zip (mail)                         | mailzip    | number    | text        | numeric metric | Yes      | 
| Zip+4 (mail)                       | mailzip4   | number    | text        | numeric metric | Yes      | 
| Other fed rev specified            | fiothsp    | text      | text        | series tag     | Yes      | 
| FIPS state code                    | pub_fips   | number    | text        | numeric metric | Yes      | 
| Fiscal year start date, mm/dd/yyyy | fystart    | date      | date        | time           | Yes      | 
| Fiscal year end date, mm/dd/yyyy   | fyend      | date      | date        |                | No       | 
| Other federal revenue              | fioth      | money     | money       | numeric metric | Yes      | 
| Total federal revenue              | total_fi   | money     | money       | numeric metric | Yes      | 
| St rev STLA operation              | sistlaop   | money     | money       | numeric metric | Yes      | 
| St rev aid to libraries            | siaidlib   | money     | money       | numeric metric | Yes      | 
| St rev other                       | siother    | money     | money       | numeric metric | Yes      | 
| St rev TOTAL                       | total_si   | money     | money       | numeric metric | Yes      | 
| Other revenue                      | othincm    | money     | money       | numeric metric | Yes      | 
| Total revenue                      | totincm    | money     | money       | numeric metric | Yes      | 
| Fed inc LSCA Title I               | fit1       | money     | money       | numeric metric | Yes      | 
| Fed inc LSCA Title II              | fit2       | money     | money       | numeric metric | Yes      | 
| Fed inc LSCA Title III             | fit3       | money     | money       | numeric metric | Yes      | 
| Total fed inc LSCA Titles I-III    | fitott13   | money     | money       | numeric metric | Yes      | 
| Other fed inc Titles IV-VIII       | fiotht48   | money     | money       | numeric metric | Yes      | 
| Fed inc Title IV                   | fit4       | text      | text        | series tag     | Yes      | 
| Fed inc Title V                    | fit5       | text      | text        | series tag     | Yes      | 
| Fed inc Title VI                   | fit6       | number    | text        | numeric metric | Yes      | 
| Fed inc Title VII                  | fit7       | text      | text        | series tag     | Yes      | 
| Fed inc Title VIII                 | fit8       | text      | text        | series tag     | Yes      | 
| Salaries federal                   | oexpsala   | money     | money       | numeric metric | Yes      | 
| Salaries state                     | oexpsalb   | money     | money       | numeric metric | Yes      | 
| Salaries other                     | oexpsalc   | money     | money       | numeric metric | Yes      | 
| Salaries TOTAL                     | oexpsald   | money     | money       | numeric metric | Yes      | 
| Benefits federal                   | oexpbena   | money     | money       | numeric metric | Yes      | 
| Benefits state                     | oexpbenb   | money     | money       | numeric metric | Yes      | 
| Benefits other                     | oexpbenc   | money     | money       | numeric metric | Yes      | 
| Benefits TOTAL                     | oexpbend   | money     | money       | numeric metric | Yes      | 
| Staff Exp federal                  | totoxsta   | money     | money       | numeric metric | Yes      | 
| Staff Exp state                    | totoxstb   | money     | money       | numeric metric | Yes      | 
| Staff Exp other                    | totoxstc   | money     | money       | numeric metric | Yes      | 
| Staff Exp TOTAL                    | totoxstd   | money     | money       | numeric metric | Yes      | 
| Collection Exp federal             | oexpcola   | money     | money       | numeric metric | Yes      | 
| Collection Exp state               | oexpcolb   | money     | money       | numeric metric | Yes      | 
| Collection Exp other               | oexpcolc   | money     | money       | numeric metric | Yes      | 
| Collection Exp TOTAL               | oexpcold   | money     | money       | numeric metric | Yes      | 
| Other Op Exp federal               | oexpotha   | money     | money       | numeric metric | Yes      | 
| Other Op Exp state                 | oexpothb   | money     | money       | numeric metric | Yes      | 
| Other Op Exp other                 | oexpothc   | money     | money       | numeric metric | Yes      | 
| Other Op Exp TOTAL                 | oexpothd   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp federal                 | totopexa   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp state                   | totopexb   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp other                   | totopexc   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp TOTAL                   | totopexd   | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries federal      | aidipla    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries state        | aidiplb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries other        | aidiplc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries TOTAL        | aidipld    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops federal          | aidplsa    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops state            | aidplsb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops other            | aidplsc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops TOTAL            | aidplsd    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other federal          | aidoila    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other state            | aidoilb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other other            | aidoilc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other TOTAL            | aidoild    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult federal        | aidmlsa    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult state          | aidmlsb    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult other          | aidmlsc    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult TOTAL          | aidmlsd    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide federal    | aidsala    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide state      | aidsalb    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide other      | aidsalc    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide TOTAL      | aidsald    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr federal       | aidlca     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr state         | aidlcb     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr other         | aidlcc     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr TOTAL         | aidlcd     | money     | money       | numeric metric | Yes      | 
| Fin Asst other federal             | aidotha    | money     | money       | numeric metric | Yes      | 
| Fin Asst other state               | aidothb    | money     | money       | numeric metric | Yes      | 
| Fin Asst other other               | aidothc    | money     | money       | numeric metric | Yes      | 
| Fin Asst other TOTAL               | aidothd    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL federal             | totaida    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL state               | totaidb    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL other               | totaidc    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL TOTAL               | totaidd    | money     | money       | numeric metric | Yes      | 
| Capital outlay federal             | capitala   | money     | money       | numeric metric | Yes      | 
| Capital outlay state               | capitalb   | money     | money       | numeric metric | Yes      | 
| Capital outlay other               | capitalc   | money     | money       | numeric metric | Yes      | 
| Capital outlay TOTAL               | capitald   | money     | money       | numeric metric | Yes      | 
| Other exp federal                  | othexpa    | money     | money       | numeric metric | Yes      | 
| Other exp state                    | othexpb    | money     | money       | numeric metric | Yes      | 
| Other exp other                    | othexpc    | money     | money       | numeric metric | Yes      | 
| Other exp TOTAL                    | othexpd    | money     | money       | numeric metric | Yes      | 
| Total exp federal                  | totexpa    | money     | money       | numeric metric | Yes      | 
| Total exp state                    | totexpb    | money     | money       | numeric metric | Yes      | 
| Total exp other                    | totexpc    | money     | money       | numeric metric | Yes      | 
| Total exp TOTAL                    | totexpd    | money     | money       | numeric metric | Yes      | 
| Title I exp statwide               | t1expstw   | money     | money       | numeric metric | Yes      | 
| Title I exp grants                 | t1expgrt   | money     | money       | numeric metric | Yes      | 
| Title I exp LSCA admin             | t1expadm   | money     | money       | numeric metric | Yes      | 
| Title I exp TOTAL                  | totexpt1   | money     | money       | numeric metric | Yes      | 
| Title II exp grants                | t2expgrt   | money     | money       | numeric metric | Yes      | 
| Title II exp LSCA admin            | t2expadm   | money     | money       | numeric metric | Yes      | 
| Title II exp TOTAL                 | totexpt2   | money     | money       | numeric metric | Yes      | 
| Title III exp statewide            | t3expstw   | money     | money       | numeric metric | Yes      | 
| Title III exp grants               | t3expgrt   | money     | money       | numeric metric | Yes      | 
| Title III exp TOTAL                | totexpt3   | money     | money       | numeric metric | Yes      | 
| Titles I-III exp TOTAL             | totex123   | money     | money       | numeric metric | Yes      | 
| Oper exp staff total               | allopstf   | money     | money       | numeric metric | Yes      | 
| Oper exp other total               | allopoth   | money     | money       | numeric metric | Yes      | 
| Oper exp TOTAL                     | totox_ao   | money     | money       | numeric metric | Yes      | 
| Capital outlay                     | allopcap   | money     | money       | numeric metric | Yes      | 
| Total expenditures                 | totexpao   | money     | money       | numeric metric | Yes      | 
| Population estimate NCES           | period_e   | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fystart
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = fyend
Annotation Fields = 
```

## Data Commands

```ls
series e:xzhn-73j5 d:1996-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:mail_st=AK t:physaddr="333 WILLOUGHBY AVENUE" t:phys_st=AK t:mailaddr="P.O. BOX 110571" t:fiothsp="NEH (NEWSPAPER PROJECT)" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" m:mailzip=99811 m:t1expadm=0 m:totox_ao=0 m:physzip4=571 m:totex123=619028 m:oexpbenb=854037 m:oexpbena=16621 m:oexpbend=870658 m:oexpbenc=0 m:fit3=61512 m:fit2=124343 m:fit1=399336 m:totincm=4804300 m:t1expgrt=128594 m:othincm=0 m:totexpt1=424184 m:totexpt3=75597 m:totexpt2=119247 m:fitott13=585191 m:sistlaop=2878627 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:physzip=99811 m:totopexd=2674056 m:aidothd=0 m:totopexa=136163 m:aidothc=0 m:totopexb=2537893 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=284724 m:t2expgrt=119247 m:oexpotha=93914 m:oexpothb=190810 m:oexpsalb=1316876 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=25628 m:t1expstw=295590 m:aidoilb=54044 m:totaidd=1581502 m:aidsald=491358 m:aidoilc=0 m:totaidc=0 m:oexpsald=1342504 m:aidoild=54044 m:aidsalb=120171 m:aidsalc=0 m:othexpa=0 m:t3expstw=75597 m:capitalc=0 m:capitalb=94676 m:capitala=0 m:totaidb=962474 m:siother=152483 m:totaida=619028 m:aidsala=371187 m:capitald=94676 m:aidlcd=129747 m:t2expadm=0 m:aidlcc=0 m:period_e=607800 m:allopstf=0 m:fioth=262699 m:aidlca=119247 m:aidlcb=10500 m:t3expgrt=0 m:totexpd=4350234 m:allopcap=0 m:totexpa=755191 m:totexpc=0 m:totexpb=3595043 m:pub_fips=2 m:totoxstc=0 m:totoxstd=2213162 m:total_fi=847890 m:aidplsc=0 m:aidplsd=0 m:fiotht48=0 m:total_si=3956410 m:totoxstb=2170913 m:totoxsta=42249 m:mailzip4=571 m:oexpcold=176170 m:oexpcolb=176170 m:aidplsa=0 m:oexpcolc=0 m:aidplsb=0 m:allopoth=0 m:aidiplc=0 m:oexpcola=0 m:aidipld=906353 m:siaidlib=925300 m:aidipla=128594 m:aidiplb=777759

series e:xzhn-73j5 d:1996-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:mail_st=AL t:physaddr="6030 MONTICELLO DRIVE" t:phys_st=AL t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" m:mailzip=36130 m:t1expadm=19325 m:totox_ao=0 m:physzip4=1 m:totex123=2044454 m:oexpbenb=406272 m:oexpbena=0 m:oexpbend=406272 m:oexpbenc=0 m:fit3=288548 m:fit2=459715 m:fit1=1327873 m:totincm=9856831 m:t1expgrt=671299 m:othincm=0 m:totexpt1=1293308 m:totexpt3=288548 m:totexpt2=462598 m:fitott13=2076136 m:sistlaop=2731344 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:physzip=36117 m:totopexd=3640204 m:aidothd=0 m:totopexa=908860 m:aidothc=0 m:totopexb=2731344 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=1161412 m:t2expgrt=462598 m:oexpotha=572311 m:oexpothb=589101 m:oexpsalb=1726005 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=0 m:t1expstw=602684 m:aidoilb=0 m:totaidd=6184945 m:aidsald=0 m:aidoilc=0 m:totaidc=0 m:oexpsald=1726005 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0 m:t3expstw=286870 m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=5049351 m:siother=0 m:totaida=1135594 m:aidsala=0 m:capitald=0 m:aidlcd=462598 m:t2expadm=0 m:aidlcc=0 m:period_e=4137511 m:allopstf=0 m:fioth=0 m:aidlca=462598 m:aidlcb=0 m:t3expgrt=1678 m:totexpd=9825149 m:allopcap=0 m:totexpa=2044454 m:totexpc=0 m:totexpb=7780695 m:pub_fips=1 m:totoxstc=0 m:totoxstd=2132277 m:total_fi=2076136 m:aidplsc=0 m:aidplsd=1071576 m:fiotht48=0 m:total_si=7780695 m:totoxstb=2132277 m:totoxsta=0 m:mailzip4=1 m:oexpcold=346515 m:oexpcolb=9966 m:aidplsa=113286 m:oexpcolc=0 m:aidplsb=958290 m:allopoth=0 m:aidiplc=0 m:oexpcola=336549 m:aidipld=4650771 m:siaidlib=5049351 m:aidipla=559710 m:aidiplb=4091061

series e:xzhn-73j5 d:1996-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:mail_st=AR t:physaddr="ONE CAPITOL MALL" t:phys_st=AR t:mailaddr="ONE CAPITOL MALL" t:stlaname="ARKANSAS STATE LIBRARY" m:mailzip=72201 m:t1expadm=12018 m:totox_ao=0 m:physzip4=1081 m:totex123=1356431 m:oexpbenb=320846 m:oexpbena=80437 m:oexpbend=401283 m:oexpbenc=0 m:fit3=128516 m:fit2=200163 m:fit1=1020226 m:totincm=7130238 m:t1expgrt=203141 m:othincm=0 m:totexpt1=875505 m:totexpt3=165515 m:totexpt2=315411 m:fitott13=1348905 m:sistlaop=2453535 m:aidmlsa=0 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:aidmlsd=0 m:totopexc=0 m:physzip=72201 m:totopexd=3213037 m:aidothd=2649 m:totopexa=784607 m:aidothc=0 m:totopexb=2428430 m:aidothb=0 m:oexpothc=0 m:aidotha=2649 m:oexpothd=966613 m:t2expgrt=315411 m:oexpotha=316427 m:oexpothb=650186 m:oexpsalb=1215368 m:othexpd=0 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=238595 m:t1expstw=660346 m:aidoilb=0 m:totaidd=4167761 m:aidsald=3000 m:aidoilc=0 m:totaidc=0 m:oexpsald=1453963 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0 m:t3expstw=159515 m:capitalc=0 m:capitalb=25014 m:capitala=47272 m:totaidb=3327798 m:siother=0 m:totaida=839963 m:aidsala=3000 m:capitald=72286 m:aidlcd=315411 m:t2expadm=0 m:aidlcc=0 m:period_e=2264510 m:allopstf=0 m:fioth=0 m:aidlca=315411 m:aidlcb=0 m:t3expgrt=6000 m:totexpd=7453084 m:allopcap=0 m:totexpa=1671842 m:totexpc=0 m:totexpb=5781242 m:pub_fips=5 m:totoxstc=0 m:totoxstd=1855246 m:total_fi=1348905 m:aidplsc=0 m:aidplsd=3061719 m:fiotht48=0 m:total_si=5781333 m:totoxstb=1536214 m:totoxsta=319032 m:mailzip4=1081 m:oexpcold=391178 m:oexpcolb=242030 m:aidplsa=442173 m:oexpcolc=0 m:aidplsb=2619546 m:allopoth=0 m:aidiplc=0 m:oexpcola=149148 m:aidipld=784982 m:siaidlib=3327798 m:aidipla=76730 m:aidiplb=708252
```

## Meta Commands

```ls
metric m:physzip p:integer l:Zip t:dataTypeName=number

metric m:physzip4 l:Zip+4 t:dataTypeName=number

metric m:mailzip p:integer l:"Zip (mail)" t:dataTypeName=number

metric m:mailzip4 l:"Zip+4 (mail)" t:dataTypeName=number

metric m:pub_fips p:integer l:"FIPS state code" t:dataTypeName=number

metric m:period_e l:"Population estimate NCES" t:dataTypeName=number

entity e:xzhn-73j5 l:"State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/xzhn-73j5

property e:xzhn-73j5 t:meta.view d:2017-03-03T13:59:35.402Z v:id=xzhn-73j5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1997, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:xzhn-73j5 t:meta.view.license d:2017-03-03T13:59:35.402Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:xzhn-73j5 t:meta.view.owner d:2017-03-03T13:59:35.402Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:xzhn-73j5 t:meta.view.tableauthor d:2017-03-03T13:59:35.402Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:xzhn-73j5 t:meta.view.metadata.custom_fields.common_core d:2017-03-03T13:59:35.402Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```