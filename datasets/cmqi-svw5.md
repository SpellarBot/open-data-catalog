# State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures

## Dataset

* [Dataset URL](https://data.imls.gov/api/views/cmqi-svw5/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/state-libraries-survey-fy-2004-part-3-revenue-expenditures)
* Id = cmqi-svw5
* Name = State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures
* Attribution = IMLS
* Attribution Link = https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey
* Category = State Library Administrative Agencies Survey
* Tags = [state library, slaa, 2004, revenue, expenditures]
* Created = 2016-12-20T15:26:21Z
* Publication Date = 2016-12-20T17:04:34Z
* Rows Updated = 2016-12-20T17:20:59Z

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Name                                 | Field Name | Data Type | Render Type | Schema Type    | Included | 
| ==================================== | ========== | ========= | =========== | ============== | ======== | 
| STLA Name                            | stlaname   | text      | text        | series tag     | Yes      | 
| Street                               | physaddr   | text      | text        | series tag     | Yes      | 
| City                                 | physcity   | text      | text        | series tag     | Yes      | 
| State                                | phys_st    | text      | text        | series tag     | Yes      | 
| Zip                                  | physzip    | number    | text        | numeric metric | Yes      | 
| Zip+4                                | physzip4   | number    | text        | numeric metric | Yes      | 
| Street (mail)                        | mailaddr   | text      | text        | series tag     | Yes      | 
| City (mail)                          | mailcity   | text      | text        | series tag     | Yes      | 
| State (mail)                         | mail_st    | text      | text        | series tag     | Yes      | 
| Zip (mail)                           | mailzip    | number    | text        | numeric metric | Yes      | 
| Zip+4 (mail)                         | mailzip4   | number    | text        | numeric metric | Yes      | 
| Web Address                          | webaddr    | text      | text        | series tag     | Yes      | 
| Admins state funds                   | asf_pub    | number    | text        | numeric metric | Yes      | 
| Admins state funds acad              | asf_ac     | number    | text        | numeric metric | Yes      | 
| Admins state funds school            | asf_sch    | number    | text        | numeric metric | Yes      | 
| Admins state funds special           | asf_sp     | number    | text        | numeric metric | Yes      | 
| Admins state funds co-ops            | asf_lc     | number    | text        | numeric metric | Yes      | 
| Other fed rev specified              | fiothsp    | text      | text        | series tag     | Yes      | 
| FIPS state code                      | pub_fips   | number    | text        | numeric metric | Yes      | 
| BEA code                             | obereg     | number    | text        | numeric metric | Yes      | 
| Reporting Status                     | rstatus    | number    | text        | numeric metric | Yes      | 
| Fiscal year start date, mm/dd/yyyy   | fystart    | date      | date        | time           | Yes      | 
| Fiscal year end date, mm/dd/yyyy     | fyend      | date      | date        |                | No       | 
| LSTA revenue                         | lstainc    | money     | money       | numeric metric | Yes      | 
| Other federal revenue                | fioth      | money     | money       | numeric metric | Yes      | 
| Total federal revenue                | total_fi   | money     | money       | numeric metric | Yes      | 
| St rev STLA operation                | sistlaop   | money     | money       | numeric metric | Yes      | 
| St rev aid to libraries              | siaidlib   | money     | money       | numeric metric | Yes      | 
| St rev other                         | siother    | money     | money       | numeric metric | Yes      | 
| St rev TOTAL                         | total_si   | money     | money       | numeric metric | Yes      | 
| Other revenue                        | othincm    | money     | money       | numeric metric | Yes      | 
| Total revenue                        | totincm    | money     | money       | numeric metric | Yes      | 
| Salaries federal                     | oexpsala   | money     | money       | numeric metric | Yes      | 
| Salaries state                       | oexpsalb   | money     | money       | numeric metric | Yes      | 
| Salaries other                       | oexpsalc   | money     | money       | numeric metric | Yes      | 
| Salaries TOTAL                       | oexpsald   | money     | money       | numeric metric | Yes      | 
| Benefits federal                     | oexpbena   | money     | money       | numeric metric | Yes      | 
| Benefits state                       | oexpbenb   | money     | money       | numeric metric | Yes      | 
| Benefits other                       | oexpbenc   | money     | money       | numeric metric | Yes      | 
| Benefits TOTAL                       | oexpbend   | money     | money       | numeric metric | Yes      | 
| Staff Exp federal                    | totoxsta   | money     | money       | numeric metric | Yes      | 
| Staff Exp state                      | totoxstb   | money     | money       | numeric metric | Yes      | 
| Staff Exp other                      | totoxstc   | money     | money       | numeric metric | Yes      | 
| Staff Exp TOTAL                      | totoxstd   | money     | money       | numeric metric | Yes      | 
| Collection Exp federal               | oexpcola   | money     | money       | numeric metric | Yes      | 
| Collection Exp state                 | oexpcolb   | money     | money       | numeric metric | Yes      | 
| Collection Exp other                 | oexpcolc   | money     | money       | numeric metric | Yes      | 
| Collection Exp TOTAL                 | oexpcold   | money     | money       | numeric metric | Yes      | 
| Other Op Exp federal                 | oexpotha   | money     | money       | numeric metric | Yes      | 
| Other Op Exp state                   | oexpothb   | money     | money       | numeric metric | Yes      | 
| Other Op Exp other                   | oexpothc   | money     | money       | numeric metric | Yes      | 
| Other Op Exp TOTAL                   | oexpothd   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp federal                   | totopexa   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp state                     | totopexb   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp other                     | totopexc   | money     | money       | numeric metric | Yes      | 
| Tot Op Exp TOTAL                     | totopexd   | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries federal        | aidipla    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries state          | aidiplb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries other          | aidiplc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to libraries TOTAL          | aidipld    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops federal            | aidplsa    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops state              | aidplsb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops other              | aidplsc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to coops TOTAL              | aidplsd    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other federal            | aidoila    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other state              | aidoilb    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other other              | aidoilc    | money     | money       | numeric metric | Yes      | 
| Fin Asst to other TOTAL              | aidoild    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult federal          | aidmlsa    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult state            | aidmlsb    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult other            | aidmlsc    | money     | money       | numeric metric | Yes      | 
| Fin Asst coops mult TOTAL            | aidmlsd    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide federal      | aidsala    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide state        | aidsalb    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide other        | aidsalc    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr statewide TOTAL        | aidsald    | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr federal         | aidlca     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr state           | aidlcb     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr other           | aidlcc     | money     | money       | numeric metric | Yes      | 
| Fin Asst libr constr TOTAL           | aidlcd     | money     | money       | numeric metric | Yes      | 
| Fin Asst other federal               | aidotha    | money     | money       | numeric metric | Yes      | 
| Fin Asst other state                 | aidothb    | money     | money       | numeric metric | Yes      | 
| Fin Asst other other                 | aidothc    | money     | money       | numeric metric | Yes      | 
| Fin Asst other TOTAL                 | aidothd    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL federal               | totaida    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL state                 | totaidb    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL other                 | totaidc    | money     | money       | numeric metric | Yes      | 
| Fin Asst TOTAL TOTAL                 | totaidd    | money     | money       | numeric metric | Yes      | 
| Capital outlay federal               | capitala   | money     | money       | numeric metric | Yes      | 
| Capital outlay state                 | capitalb   | money     | money       | numeric metric | Yes      | 
| Capital outlay other                 | capitalc   | money     | money       | numeric metric | Yes      | 
| Capital outlay TOTAL                 | capitald   | money     | money       | numeric metric | Yes      | 
| Other exp federal                    | othexpa    | money     | money       | numeric metric | Yes      | 
| Other exp state                      | othexpb    | money     | money       | numeric metric | Yes      | 
| Other exp other                      | othexpc    | money     | money       | numeric metric | Yes      | 
| Other exp TOTAL                      | othexpd    | money     | money       | numeric metric | Yes      | 
| Total exp federal                    | totexpa    | money     | money       | numeric metric | Yes      | 
| Total exp state                      | totexpb    | money     | money       | numeric metric | Yes      | 
| Total exp other                      | totexpc    | money     | money       | numeric metric | Yes      | 
| Total exp TOTAL                      | totexpd    | money     | money       | numeric metric | Yes      | 
| LSTA exp statewide svcs              | swexpt     | money     | money       | numeric metric | Yes      | 
| LSTA exp grants                      | grexpt     | money     | money       | numeric metric | Yes      | 
| LSTA exp LSTA admin                  | admexpt    | money     | money       | numeric metric | Yes      | 
| LSTA exp by type/TOTAL               | totexpt    | money     | money       | numeric metric | Yes      | 
| LSTA exp electronic networking       | netacxu    | money     | money       | numeric metric | Yes      | 
| LSTA exp svcs to disab               | serdifxu   | money     | money       | numeric metric | Yes      | 
| LSTA exp svcs to children in poverty | serpovxu   | money     | money       | numeric metric | Yes      | 
| LSTA exp by use/LSTA admin           | admexpu    | money     | money       | numeric metric | Yes      | 
| LSTA exp by use/TOTAL                | totexpu    | money     | money       | numeric metric | Yes      | 
| Oper exp staff total                 | allopstf   | money     | money       | numeric metric | Yes      | 
| Oper exp other total                 | allopoth   | money     | money       | numeric metric | Yes      | 
| Oper exp TOTAL                       | totox_ao   | money     | money       | numeric metric | Yes      | 
| Capital outlay                       | allopcap   | money     | money       | numeric metric | Yes      | 
| All other exp                        | othexpao   | money     | money       | numeric metric | Yes      | 
| Total expenditures                   | totexpao   | money     | money       | numeric metric | Yes      | 
| Population                           | popu_st    | number    | number      | numeric metric | Yes      | 
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
series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:mail_st=AK t:asf_lc=N t:physaddr="333 WILLOUGHBY AVENUE" t:asf_ac=Y t:phys_st=AK t:mailaddr="P.O. BOX 110571" t:asf_pub=Y t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:asf_sch=N t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:fiothsp="FUND FOR THE IMPROVEMENT OF POST SECONDARY EDUCATION (FIPSE) (HIGHER EDUCATION ACT OF 1965, TITLE VII)" m:mailzip=99811 m:totox_ao=0 m:physzip4=571 m:admexpt=0 m:admexpu=0 m:oexpbenb=523084 m:oexpbena=6456 m:oexpbend=529540 m:oexpbenc=0 m:totincm=4450807 m:othincm=74420 m:obereg=8 m:othexpao=0 m:sistlaop=2619200 m:aidmlsa=0 m:popu_st=655435 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:rstatus=1 m:aidmlsd=0 m:physzip=99811 m:totopexc=74420 m:totopexd=3030177 m:aidothd=0 m:totopexa=26412 m:aidothc=0 m:totopexb=2929345 m:aidothb=0 m:oexpothc=74420 m:aidotha=0 m:oexpothd=836603 m:oexpotha=2500 m:oexpothb=759683 m:othexpd=0 m:oexpsalb=1409808 m:serdifxu=509939 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=17456 m:totaidd=1503317 m:aidsald=718346 m:aidoilb=0 m:totaidc=0 m:aidoilc=0 m:oexpsald=1427264 m:aidoild=0 m:aidsalb=187627 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=879957 m:siother=221300 m:totaida=623360 m:aidsala=530719 m:capitald=0 m:swexpt=0 m:netacxu=113421 m:aidlcd=0 m:aidlcc=0 m:totexpu=623360 m:totexpt=623360 m:allopstf=0 m:fioth=26412 m:aidlca=0 m:aidlcb=0 m:totexpd=4533494 m:allopcap=0 m:totexpa=649772 m:totexpc=74420 m:totexpb=3809302 m:pub_fips=2 m:totoxstc=0 m:totoxstd=1956804 m:total_fi=644487 m:aidplsc=0 m:aidplsd=0 m:total_si=3731900 m:totoxstb=1932892 m:totoxsta=23912 m:mailzip4=571 m:serpovxu=0 m:oexpcold=236770 m:lstainc=618075 m:grexpt=623360 m:oexpcolb=236770 m:aidplsa=0 m:allopoth=0 m:oexpcolc=0 m:aidplsb=0 m:oexpcola=0 m:aidiplc=0 m:aidipld=784971 m:siaidlib=891400 m:aidipla=92641 m:aidiplb=692330

series e:cmqi-svw5 d:2003-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:mail_st=AL t:asf_lc=Y t:physaddr="6030 MONTICELLO DRIVE" t:asf_ac=N t:phys_st=AL t:mailaddr="6030 MONTICELLO DRIVE" t:asf_pub=Y t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:asf_sch=N t:webaddr=WWW.APLS.STATE.AL.US t:asf_sp=N t:fiothsp=P m:mailzip=36130 m:totox_ao=0 m:physzip4=1 m:admexpt=80160 m:admexpu=80160 m:oexpbenb=472397 m:oexpbena=0 m:oexpbend=472397 m:oexpbenc=0 m:totincm=11613509 m:othincm=255311 m:obereg=5 m:othexpao=0 m:sistlaop=2312470 m:aidmlsa=0 m:popu_st=4530182 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:rstatus=1 m:aidmlsd=0 m:physzip=36117 m:totopexc=0 m:totopexd=3279211 m:aidothd=0 m:totopexa=998038 m:aidothc=0 m:totopexb=2281173 m:aidothb=0 m:oexpothc=0 m:aidotha=0 m:oexpothd=771522 m:oexpotha=760385 m:oexpothb=11137 m:othexpd=0 m:oexpsalb=1797639 m:serdifxu=1697102 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=53890 m:oexpsala=0 m:totaidd=8176839 m:aidsald=2534975 m:aidoilb=0 m:totaidc=126774 m:aidoilc=0 m:oexpsald=1797639 m:aidoild=53890 m:aidsalb=2534975 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=6678958 m:siother=2534975 m:totaida=1371107 m:aidsala=0 m:capitald=0 m:swexpt=917878 m:netacxu=447176 m:aidlcd=0 m:aidlcc=0 m:totexpu=2369145 m:totexpt=2369145 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=11456050 m:allopcap=0 m:totexpa=2369145 m:totexpc=126774 m:totexpb=8960131 m:pub_fips=1 m:totoxstc=0 m:totoxstd=2270036 m:total_fi=2369145 m:aidplsc=0 m:aidplsd=2509102 m:total_si=8989053 m:totoxstb=2270036 m:totoxsta=0 m:mailzip4=1 m:serpovxu=144707 m:oexpcold=237653 m:lstainc=2369145 m:grexpt=1371107 m:oexpcolb=0 m:aidplsa=171851 m:allopoth=0 m:oexpcolc=0 m:aidplsb=2337251 m:oexpcola=237653 m:aidiplc=126774 m:aidipld=3078872 m:siaidlib=4141608 m:aidipla=1145366 m:aidiplb=1806732

series e:cmqi-svw5 d:2003-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:mail_st=AR t:asf_lc=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:asf_ac=N t:phys_st=AR t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:asf_pub=Y t:stlaname="ARKANSAS STATE LIBRARY" t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:fiothsp=P m:mailzip=72201 m:totox_ao=0 m:physzip4=1085 m:admexpt=33697 m:admexpu=33697 m:oexpbenb=380233 m:oexpbena=98272 m:oexpbend=478505 m:oexpbenc=0 m:totincm=6740807 m:othincm=3341 m:obereg=5 m:othexpao=0 m:sistlaop=2942517 m:aidmlsa=0 m:popu_st=2752629 m:aidmlsc=0 m:aidmlsb=0 m:totexpao=0 m:rstatus=1 m:aidmlsd=0 m:physzip=72201 m:totopexc=1629 m:totopexd=4543740 m:aidothd=0 m:totopexa=1526954 m:aidothc=0 m:totopexb=3015157 m:aidothb=0 m:oexpothc=1629 m:aidotha=0 m:oexpothd=1842984 m:oexpotha=809353 m:oexpothb=1032002 m:othexpd=0 m:oexpsalb=1497940 m:serdifxu=147002 m:oexpsalc=0 m:othexpb=0 m:othexpc=0 m:aidoila=0 m:oexpsala=285426 m:totaidd=2169778 m:aidsald=0 m:aidoilb=0 m:totaidc=84889 m:aidoilc=0 m:oexpsald=1783366 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0 m:capitalc=0 m:capitalb=553 m:capitala=85405 m:totaidb=2084889 m:siother=158082 m:totaida=0 m:aidsala=0 m:capitald=85958 m:swexpt=1578662 m:netacxu=1431660 m:aidlcd=0 m:aidlcc=0 m:totexpu=1612359 m:totexpt=1612359 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=6799476 m:allopcap=0 m:totexpa=1612359 m:totexpc=86518 m:totexpb=5100599 m:pub_fips=5 m:totoxstc=0 m:totoxstd=2261871 m:total_fi=1636867 m:aidplsc=0 m:aidplsd=1161668 m:total_si=5100599 m:totoxstb=1878173 m:totoxsta=383698 m:mailzip4=1085 m:serpovxu=0 m:oexpcold=438885 m:lstainc=1636867 m:grexpt=0 m:oexpcolb=104982 m:aidplsa=0 m:allopoth=0 m:oexpcolc=0 m:aidplsb=1161668 m:oexpcola=333903 m:aidiplc=84889 m:aidipld=1008110 m:siaidlib=2000000 m:aidipla=0 m:aidiplb=923221
```

## Meta Commands

```ls
metric m:physzip p:integer l:Zip t:dataTypeName=number

metric m:physzip4 p:integer l:Zip+4 t:dataTypeName=number

metric m:mailzip p:integer l:"Zip (mail)" t:dataTypeName=number

metric m:mailzip4 p:integer l:"Zip+4 (mail)" t:dataTypeName=number

metric m:pub_fips p:integer l:"FIPS state code" t:dataTypeName=number

metric m:obereg p:integer l:"BEA code" t:dataTypeName=number

metric m:rstatus p:integer l:"Reporting Status" t:dataTypeName=number

metric m:popu_st l:Population t:dataTypeName=number

entity e:cmqi-svw5 l:"State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/cmqi-svw5

property e:cmqi-svw5 t:meta.view d:2017-03-03T14:05:33.140Z v:id=cmqi-svw5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2004, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:cmqi-svw5 t:meta.view.license d:2017-03-03T14:05:33.140Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:cmqi-svw5 t:meta.view.owner d:2017-03-03T14:05:33.140Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.tableauthor d:2017-03-03T14:05:33.140Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:cmqi-svw5 t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:05:33.140Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```