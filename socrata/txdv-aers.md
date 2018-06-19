# State Libraries Survey, FY 2002, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2002-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/txdv-aers) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/txdv-aers/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/txdv-aers/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | txdv-aers |
| Name | State Libraries Survey, FY 2002, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2002, revenue, expenditures |
| Created | 2016-12-20T15:23:11Z |
| Publication Date | 2016-12-20T17:04:32Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                 | Data Type | Render Type |
| ======== | ============== | ========== | ==================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                            | text      | text        |
| Yes      | series tag     | physaddr   | Street                               | text      | text        |
| Yes      | series tag     | physcity   | City                                 | text      | text        |
| Yes      | series tag     | phys_st    | State                                | text      | text        |
| Yes      | series tag     | physzip    | Zip                                  | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                                | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                        | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                          | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                         | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                           | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                         | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                          | text      | text        |
| Yes      | series tag     | asf_pub    | Admins state funds                   | text      | text        |
| Yes      | series tag     | asf_ac     | Admins state funds acad              | text      | text        |
| Yes      | series tag     | asf_sch    | Admins state funds school            | text      | text        |
| Yes      | series tag     | asf_sp     | Admins state funds special           | text      | text        |
| Yes      | series tag     | asf_lc     | Admins state funds co-ops            | text      | text        |
| Yes      | series tag     | fiothsp    | Other fed rev specified              | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                      | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy   | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy     | date      | date        |
| Yes      | numeric metric | lstainc    | LSTA revenue                         | money     | money       |
| Yes      | numeric metric | fioth      | Other federal revenue                | money     | money       |
| Yes      | numeric metric | total_fi   | Total federal revenue                | money     | money       |
| Yes      | numeric metric | sistlaop   | St rev STLA operation                | money     | money       |
| Yes      | numeric metric | siaidlib   | St rev aid to libraries              | money     | money       |
| Yes      | numeric metric | siother    | St rev other                         | money     | money       |
| Yes      | numeric metric | total_si   | St rev TOTAL                         | money     | money       |
| Yes      | numeric metric | othincm    | Other revenue                        | money     | money       |
| Yes      | numeric metric | totincm    | Total revenue                        | money     | money       |
| Yes      | numeric metric | oexpsala   | Salaries federal                     | money     | money       |
| Yes      | numeric metric | oexpsalb   | Salaries state                       | money     | money       |
| Yes      | numeric metric | oexpsalc   | Salaries other                       | money     | money       |
| Yes      | numeric metric | oexpsald   | Salaries TOTAL                       | money     | money       |
| Yes      | numeric metric | oexpbena   | Benefits federal                     | money     | money       |
| Yes      | numeric metric | oexpbenb   | Benefits state                       | money     | money       |
| Yes      | numeric metric | oexpbenc   | Benefits other                       | money     | money       |
| Yes      | numeric metric | oexpbend   | Benefits TOTAL                       | money     | money       |
| Yes      | numeric metric | totoxsta   | Staff Exp federal                    | money     | money       |
| Yes      | numeric metric | totoxstb   | Staff Exp state                      | money     | money       |
| Yes      | numeric metric | totoxstc   | Staff Exp other                      | money     | money       |
| Yes      | numeric metric | totoxstd   | Staff Exp TOTAL                      | money     | money       |
| Yes      | numeric metric | oexpcola   | Collection Exp federal               | money     | money       |
| Yes      | numeric metric | oexpcolb   | Collection Exp state                 | money     | money       |
| Yes      | numeric metric | oexpcolc   | Collection Exp other                 | money     | money       |
| Yes      | numeric metric | oexpcold   | Collection Exp TOTAL                 | money     | money       |
| Yes      | numeric metric | oexpotha   | Other Op Exp federal                 | money     | money       |
| Yes      | numeric metric | oexpothb   | Other Op Exp state                   | money     | money       |
| Yes      | numeric metric | oexpothc   | Other Op Exp other                   | money     | money       |
| Yes      | numeric metric | oexpothd   | Other Op Exp TOTAL                   | money     | money       |
| Yes      | numeric metric | totopexa   | Tot Op Exp federal                   | money     | money       |
| Yes      | numeric metric | totopexb   | Tot Op Exp state                     | money     | money       |
| Yes      | numeric metric | totopexc   | Tot Op Exp other                     | money     | money       |
| Yes      | numeric metric | totopexd   | Tot Op Exp TOTAL                     | money     | money       |
| Yes      | numeric metric | aidipla    | Fin Asst to libraries federal        | money     | money       |
| Yes      | numeric metric | aidiplb    | Fin Asst to libraries state          | money     | money       |
| Yes      | numeric metric | aidiplc    | Fin Asst to libraries other          | money     | money       |
| Yes      | numeric metric | aidipld    | Fin Asst to libraries TOTAL          | money     | money       |
| Yes      | numeric metric | aidplsa    | Fin Asst to coops federal            | money     | money       |
| Yes      | numeric metric | aidplsb    | Fin Asst to coops state              | money     | money       |
| Yes      | numeric metric | aidplsc    | Fin Asst to coops other              | money     | money       |
| Yes      | numeric metric | aidplsd    | Fin Asst to coops TOTAL              | money     | money       |
| Yes      | numeric metric | aidoila    | Fin Asst to other federal            | money     | money       |
| Yes      | numeric metric | aidoilb    | Fin Asst to other state              | money     | money       |
| Yes      | numeric metric | aidoilc    | Fin Asst to other other              | money     | money       |
| Yes      | numeric metric | aidoild    | Fin Asst to other TOTAL              | money     | money       |
| Yes      | numeric metric | aidmlsa    | Fin Asst coops mult federal          | money     | money       |
| Yes      | numeric metric | aidmlsb    | Fin Asst coops mult state            | money     | money       |
| Yes      | numeric metric | aidmlsc    | Fin Asst coops mult other            | money     | money       |
| Yes      | numeric metric | aidmlsd    | Fin Asst coops mult TOTAL            | money     | money       |
| Yes      | numeric metric | aidsala    | Fin Asst libr statewide federal      | money     | money       |
| Yes      | numeric metric | aidsalb    | Fin Asst libr statewide state        | money     | money       |
| Yes      | numeric metric | aidsalc    | Fin Asst libr statewide other        | money     | money       |
| Yes      | numeric metric | aidsald    | Fin Asst libr statewide TOTAL        | money     | money       |
| Yes      | numeric metric | aidlca     | Fin Asst libr constr federal         | money     | money       |
| Yes      | numeric metric | aidlcb     | Fin Asst libr constr state           | money     | money       |
| Yes      | numeric metric | aidlcc     | Fin Asst libr constr other           | money     | money       |
| Yes      | numeric metric | aidlcd     | Fin Asst libr constr TOTAL           | money     | money       |
| Yes      | numeric metric | aidotha    | Fin Asst other federal               | money     | money       |
| Yes      | numeric metric | aidothb    | Fin Asst other state                 | money     | money       |
| Yes      | numeric metric | aidothc    | Fin Asst other other                 | money     | money       |
| Yes      | numeric metric | aidothd    | Fin Asst other TOTAL                 | money     | money       |
| Yes      | numeric metric | totaida    | Fin Asst TOTAL federal               | money     | money       |
| Yes      | numeric metric | totaidb    | Fin Asst TOTAL state                 | money     | money       |
| Yes      | numeric metric | totaidc    | Fin Asst TOTAL other                 | money     | money       |
| Yes      | numeric metric | totaidd    | Fin Asst TOTAL TOTAL                 | money     | money       |
| Yes      | numeric metric | capitala   | Capital outlay federal               | money     | money       |
| Yes      | numeric metric | capitalb   | Capital outlay state                 | money     | money       |
| Yes      | numeric metric | capitalc   | Capital outlay other                 | money     | money       |
| Yes      | numeric metric | capitald   | Capital outlay TOTAL                 | money     | money       |
| Yes      | numeric metric | othexpa    | Other exp federal                    | money     | money       |
| Yes      | numeric metric | othexpb    | Other exp state                      | money     | money       |
| Yes      | numeric metric | othexpc    | Other exp other                      | money     | money       |
| Yes      | numeric metric | othexpd    | Other exp TOTAL                      | money     | money       |
| Yes      | numeric metric | totexpa    | Total exp federal                    | money     | money       |
| Yes      | numeric metric | totexpb    | Total exp state                      | money     | money       |
| Yes      | numeric metric | totexpc    | Total exp other                      | money     | money       |
| Yes      | numeric metric | totexpd    | Total exp TOTAL                      | money     | money       |
| Yes      | numeric metric | swexpt     | LSTA exp statewide svcs              | money     | money       |
| Yes      | numeric metric | grexpt     | LSTA exp grants                      | money     | money       |
| Yes      | numeric metric | admexpt    | LSTA exp LSTA admin                  | money     | money       |
| Yes      | numeric metric | totexpt    | LSTA exp by type/TOTAL               | money     | money       |
| Yes      | numeric metric | netacxu    | LSTA exp electronic networking       | money     | money       |
| Yes      | numeric metric | serdifxu   | LSTA exp svcs to disab               | money     | money       |
| Yes      | numeric metric | serpovxu   | LSTA exp svcs to children in poverty | money     | money       |
| Yes      | numeric metric | admexpu    | LSTA exp by use/LSTA admin           | money     | money       |
| Yes      | numeric metric | totexpu    | LSTA exp by use/TOTAL                | money     | money       |
| Yes      | numeric metric | allopstf   | Oper exp staff total                 | money     | money       |
| Yes      | numeric metric | allopoth   | Oper exp other total                 | money     | money       |
| Yes      | numeric metric | totox_ao   | Oper exp TOTAL                       | money     | money       |
| Yes      | numeric metric | allopcap   | Capital outlay                       | money     | money       |
| Yes      | numeric metric | othexpao   | All other exp                        | money     | money       |
| Yes      | numeric metric | totexpao   | Total expenditures                   | money     | money       |
| Yes      | numeric metric | popu_st    | Population                           | number    | number      |
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
series e:txdv-aers d:2001-07-01T00:00:00.000Z t:physcity="DES MOINES" t:mailcity="DES MOINES" t:asf_lc=N t:mail_st=IA t:pub_fips=19 t:physaddr="E. 12TH AND GRAND" t:asf_ac=Y t:phys_st=IA t:mailzip=50319 t:mailzip4=233 t:asf_pub=Y t:mailaddr="E. 12TH AND GRAND" t:stlaname="STATE LIBRARY OF IOWA" t:physzip4=233 t:asf_sch=N t:webaddr=WWW.SILO.LIB.IA.US t:asf_sp=N t:physzip=50319 t:fiothsp="LSCA TITLE II" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=884557 m:siother=221300 m:totaida=849540 m:aidsala=385242 m:capitald=0 m:totox_ao=0 m:admexpt=0 m:swexpt=0 m:admexpu=0 m:oexpbenb=518906 m:oexpbena=0 m:oexpbend=518906 m:oexpbenc=0 m:netacxu=216302 m:totincm=4943138 m:othincm=0 m:aidlcd=161796 m:aidlcc=0 m:totexpu=687744 m:totexpt=687744 m:allopstf=0 m:fioth=161796 m:aidlca=161796 m:aidlcb=0 m:totexpd=4737589 m:allopcap=0 m:totexpa=849540 m:totexpc=0 m:totexpb=3888049 m:othexpao=0 m:sistlaop=2977700 m:aidmlsa=0 m:popu_st=643786 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2076003 m:aidmlsd=0 m:totopexc=0 m:totopexd=3003492 m:totopexa=0 m:aidothd=0 m:totopexb=3003492 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:oexpothd=627727 m:aidotha=0 m:total_fi=852738 m:oexpotha=0 m:oexpothb=627727 m:aidplsc=0 m:aidplsd=0 m:total_si=4090400 m:totoxstb=2076003 m:totoxsta=0 m:serpovxu=0 m:oexpcold=299762 m:lstainc=690942 m:aidplsa=0 m:oexpcolb=299762 m:grexpt=687744 m:aidplsb=0 m:oexpcolc=0 m:allopoth=0 m:serdifxu=471442 m:oexpsalb=1557097 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=853618 m:siaidlib=891400 m:othexpb=0 m:aidipla=155227 m:oexpsala=0 m:aidoila=147275 m:othexpc=0 m:aidiplb=698391 m:aidoilb=3920 m:aidsald=567488 m:totaidd=1734097 m:aidoilc=0 m:totaidc=0 m:oexpsald=1557097 m:aidoild=151195 m:aidsalb=182246 m:aidsalc=0 m:othexpa=0

series e:txdv-aers d:2001-07-01T00:00:00.000Z t:physcity=FRANKFORT t:mailcity=FRANKFORT t:asf_lc=Y t:mail_st=KY t:pub_fips=21 t:physaddr="300 COFFEE TREE ROAD" t:asf_ac=N t:phys_st=KY t:mailzip=40602 t:mailzip4=537 t:asf_pub=Y t:mailaddr="300 COFFEE TREE ROAD" t:stlaname="KENTUCKY DEPARTMENT FOR LIBRARIES AND ARCHIVES" t:physzip4=537 t:asf_sch=N t:webaddr=WWW.KDLA.KY.GOV t:asf_sp=Y t:physzip=40601 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=4570572 m:siother=2689000 m:totaida=1023304 m:aidsala=0 m:capitald=0 m:totox_ao=0 m:admexpt=91824 m:swexpt=1261498 m:admexpu=91824 m:oexpbenb=512516 m:oexpbena=4062 m:oexpbend=516578 m:oexpbenc=0 m:netacxu=824590 m:totincm=12413485 m:othincm=107138 m:aidlcd=46900 m:aidlcc=0 m:totexpu=2376626 m:totexpt=2376626 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=46900 m:totexpd=12195370 m:allopcap=0 m:totexpa=2376626 m:totexpc=2138 m:totexpb=9816606 m:othexpao=0 m:sistlaop=2557034 m:aidmlsa=17527 m:popu_st=4486508 m:aidmlsc=0 m:aidmlsb=985536 m:totoxstc=0 m:totexpao=0 m:totoxstd=2561096 m:aidmlsd=1003063 m:totopexc=2138 m:totopexd=6601494 m:totopexa=1353322 m:aidothd=21885 m:totopexb=5246034 m:aidothc=0 m:oexpothc=2138 m:aidothb=21885 m:oexpothd=1236378 m:aidotha=0 m:total_fi=2376626 m:oexpotha=1234240 m:oexpothb=0 m:aidplsc=0 m:aidplsd=1118300 m:total_si=9929721 m:totoxstb=2557034 m:totoxsta=4062 m:serpovxu=108462 m:oexpcold=2804020 m:lstainc=2376626 m:aidplsa=60400 m:oexpcolb=2689000 m:grexpt=1023304 m:aidplsb=1057900 m:oexpcolc=0 m:allopoth=0 m:serdifxu=1351750 m:oexpsalb=2044518 m:othexpd=0 m:aidiplc=0 m:oexpcola=115020 m:oexpsalc=0 m:aidipld=3347003 m:siaidlib=4683687 m:othexpb=0 m:aidipla=945377 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=2401626 m:aidoilb=56725 m:aidsald=0 m:totaidd=5593876 m:aidoilc=0 m:totaidc=0 m:oexpsald=2044518 m:aidoild=56725 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:txdv-aers d:2001-07-01T00:00:00.000Z t:physcity="BATON ROUGE" t:mailcity="BATON ROUGE" t:asf_lc=N t:mail_st=LA t:pub_fips=22 t:physaddr="701 NORTH FOURTH STREET" t:asf_ac=N t:phys_st=LA t:mailzip=70821 t:mailzip4=131 t:asf_pub=Y t:mailaddr="P.O. BOX 131" t:stlaname="STATE LIBRARY OF LOUISIANA" t:physzip4=5232 t:asf_sch=N t:webaddr=WWW.STATE.LIB.LA.US t:asf_sp=N t:physzip=70802 t:fiothsp=P m:capitalc=0 m:capitalb=11744 m:capitala=34832 m:totaidb=2000000 m:siother=0 m:totaida=0 m:aidsala=0 m:capitald=46576 m:totox_ao=0 m:admexpt=57400 m:swexpt=1352279 m:admexpu=57400 m:oexpbenb=388123 m:oexpbena=92285 m:oexpbend=480408 m:oexpbenc=0 m:netacxu=1216518 m:totincm=6293771 m:othincm=0 m:aidlcd=0 m:aidlcc=0 m:totexpu=1409679 m:totexpt=1409679 m:allopstf=0 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=6338056 m:allopcap=0 m:totexpa=1409679 m:totexpc=0 m:totexpb=4928377 m:othexpao=0 m:sistlaop=2928377 m:aidmlsa=0 m:popu_st=2710079 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totexpao=0 m:totoxstd=2211200 m:aidmlsd=0 m:totopexc=0 m:totopexd=4291480 m:totopexa=1374847 m:aidothd=0 m:totopexb=2916633 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:oexpothd=1857917 m:aidotha=0 m:total_fi=1365394 m:oexpotha=998694 m:oexpothb=859223 m:aidplsc=0 m:aidplsd=1244474 m:total_si=4928377 m:totoxstb=1835047 m:totoxsta=376153 m:serpovxu=0 m:oexpcold=222363 m:lstainc=1365394 m:aidplsa=0 m:oexpcolb=222363 m:grexpt=0 m:aidplsb=1244474 m:oexpcolc=0 m:allopoth=0 m:serdifxu=135761 m:oexpsalb=1446924 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=755526 m:siaidlib=2000000 m:othexpb=0 m:aidipla=0 m:oexpsala=283868 m:aidoila=0 m:othexpc=0 m:aidiplb=755526 m:aidoilb=0 m:aidsald=0 m:totaidd=2000000 m:aidoilc=0 m:totaidc=0 m:oexpsald=1730792 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
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

metric m:netacxu p:double l:"LSTA exp electronic networking" t:dataTypeName=money

metric m:serdifxu p:double l:"LSTA exp svcs to disab" t:dataTypeName=money

metric m:serpovxu p:double l:"LSTA exp svcs to children in poverty" t:dataTypeName=money

metric m:admexpu p:double l:"LSTA exp by use/LSTA admin" t:dataTypeName=money

metric m:totexpu p:double l:"LSTA exp by use/TOTAL" t:dataTypeName=money

metric m:allopstf p:double l:"Oper exp staff total" t:dataTypeName=money

metric m:allopoth p:double l:"Oper exp other total" t:dataTypeName=money

metric m:totox_ao p:double l:"Oper exp TOTAL" t:dataTypeName=money

metric m:allopcap p:double l:"Capital outlay" t:dataTypeName=money

metric m:othexpao p:double l:"All other exp" t:dataTypeName=money

metric m:totexpao p:double l:"Total expenditures" t:dataTypeName=money

metric m:popu_st p:double l:Population t:dataTypeName=number

entity e:txdv-aers l:"State Libraries Survey, FY 2002, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/txdv-aers

property e:txdv-aers t:meta.view v:id=txdv-aers v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2002, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:txdv-aers t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:txdv-aers t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:txdv-aers t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:txdv-aers t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                       | physaddr                        | physcity       | phys_st | physzip | physzip4 | mailaddr                  | mailcity       | mail_st | mailzip | mailzip4 | webaddr                                         | asf_pub | asf_ac | asf_sch | asf_sp | asf_lc | fiothsp                                                                         | pub_fips | fystart   | fyend      | lstainc    | fioth     | total_fi   | sistlaop   | siaidlib   | siother   | total_si   | othincm   | totincm     | oexpsala  | oexpsalb  | oexpsalc | oexpsald   | oexpbena | oexpbenb  | oexpbenc | oexpbend  | totoxsta  | totoxstb   | totoxstc | totoxstd   | oexpcola | oexpcolb  | oexpcolc | oexpcold  | oexpotha  | oexpothb  | oexpothc  | oexpothd   | totopexa  | totopexb   | totopexc  | totopexd   | aidipla   | aidiplb    | aidiplc  | aidipld    | aidplsa  | aidplsb   | aidplsc | aidplsd   | aidoila   | aidoilb  | aidoilc | aidoild   | aidmlsa   | aidmlsb    | aidmlsc | aidmlsd    | aidsala   | aidsalb   | aidsalc | aidsald   | aidlca   | aidlcb     | aidlcc | aidlcd     | aidotha | aidothb | aidothc | aidothd | totaida    | totaidb    | totaidc  | totaidd    | capitala | capitalb | capitalc | capitald | othexpa  | othexpb   | othexpc  | othexpd   | totexpa    | totexpb    | totexpc   | totexpd     | swexpt    | grexpt     | admexpt  | totexpt    | netacxu    | serdifxu  | serpovxu | admexpu  | totexpu    | allopstf  | allopoth | totox_ao  | allopcap | othexpao | totexpao  | popu_st    | 
| ============================================== | =============================== | ============== | ======= | ======= | ======== | ========================= | ============== | ======= | ======= | ======== | =============================================== | ======= | ====== | ======= | ====== | ====== | =============================================================================== | ======== | ========= | ========== | ========== | ========= | ========== | ========== | ========== | ========= | ========== | ========= | =========== | ========= | ========= | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========== | ======== | ========== | ======== | ========= | ======== | ========= | ========= | ========= | ========= | ========== | ========= | ========== | ========= | ========== | ========= | ========== | ======== | ========== | ======== | ========= | ======= | ========= | ========= | ======== | ======= | ========= | ========= | ========== | ======= | ========== | ========= | ========= | ======= | ========= | ======== | ========== | ====== | ========== | ======= | ======= | ======= | ======= | ========== | ========== | ======== | ========== | ======== | ======== | ======== | ======== | ======== | ========= | ======== | ========= | ========== | ========== | ========= | =========== | ========= | ========== | ======== | ========== | ========== | ========= | ======== | ======== | ========== | ========= | ======== | ========= | ======== | ======== | ========= | ========== | 
| STATE LIBRARY OF IOWA                          | E. 12TH AND GRAND               | DES MOINES     | IA      | 50319   | 233      | E. 12TH AND GRAND         | DES MOINES     | IA      | 50319   | 233      | WWW.SILO.LIB.IA.US                              | Y       | Y      | N       | N      | N      | LSCA TITLE II                                                                   | 19       | 993945600 | 1025395200 | 690942.0   | 161796.0  | 852738.0   | 2977700.0  | 891400.0   | 221300.0  | 4090400.0  | 0.0       | 4943138.0   | 0.0       | 1557097.0 | 0.0      | 1557097.0  | 0.0      | 518906.0  | 0.0      | 518906.0  | 0.0       | 2076003.0  | 0.0      | 2076003.0  | 0.0      | 299762.0  | 0.0      | 299762.0  | 0.0       | 627727.0  | 0.0       | 627727.0   | 0.0       | 3003492.0  | 0.0       | 3003492.0  | 155227.0  | 698391.0   | 0.0      | 853618.0   | 0.0      | 0.0       | 0.0     | 0.0       | 147275.0  | 3920.0   | 0.0     | 151195.0  | 0.0       | 0.0        | 0.0     | 0.0        | 385242.0  | 182246.0  | 0.0     | 567488.0  | 161796.0 | 0.0        | 0.0    | 161796.0   | 0.0     | 0.0     | 0.0     | 0.0     | 849540.0   | 884557.0   | 0.0      | 1734097.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 849540.0   | 3888049.0  | 0.0       | 4737589.0   | 0.0       | 687744.0   | 0.0      | 687744.0   | 216302.0   | 471442.0  | 0.0      | 0.0      | 687744.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 643786.0   | 
| KENTUCKY DEPARTMENT FOR LIBRARIES AND ARCHIVES | 300 COFFEE TREE ROAD            | FRANKFORT      | KY      | 40601   | 537      | 300 COFFEE TREE ROAD      | FRANKFORT      | KY      | 40602   | 537      | WWW.KDLA.KY.GOV                                 | Y       | N      | N       | Y      | Y      | P                                                                               | 21       | 993945600 | 1025395200 | 2376626.0  | 0.0       | 2376626.0  | 2557034.0  | 4683687.0  | 2689000.0 | 9929721.0  | 107138.0  | 12413485.0  | 0.0       | 2044518.0 | 0.0      | 2044518.0  | 4062.0   | 512516.0  | 0.0      | 516578.0  | 4062.0    | 2557034.0  | 0.0      | 2561096.0  | 115020.0 | 2689000.0 | 0.0      | 2804020.0 | 1234240.0 | 0.0       | 2138.0    | 1236378.0  | 1353322.0 | 5246034.0  | 2138.0    | 6601494.0  | 945377.0  | 2401626.0  | 0.0      | 3347003.0  | 60400.0  | 1057900.0 | 0.0     | 1118300.0 | 0.0       | 56725.0  | 0.0     | 56725.0   | 17527.0   | 985536.0   | 0.0     | 1003063.0  | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 46900.0    | 0.0    | 46900.0    | 0.0     | 21885.0 | 0.0     | 21885.0 | 1023304.0  | 4570572.0  | 0.0      | 5593876.0  | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 2376626.0  | 9816606.0  | 2138.0    | 12195370.0  | 1261498.0 | 1023304.0  | 91824.0  | 2376626.0  | 824590.0   | 1351750.0 | 108462.0 | 91824.0  | 2376626.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 4486508.0  | 
| STATE LIBRARY OF LOUISIANA                     | 701 NORTH FOURTH STREET         | BATON ROUGE    | LA      | 70802   | 5232     | P.O. BOX 131              | BATON ROUGE    | LA      | 70821   | 131      | WWW.STATE.LIB.LA.US                             | Y       | N      | N       | N      | N      | P                                                                               | 22       | 993945600 | 1025395200 | 1365394.0  | 0.0       | 1365394.0  | 2928377.0  | 2000000.0  | 0.0       | 4928377.0  | 0.0       | 6293771.0   | 283868.0  | 1446924.0 | 0.0      | 1730792.0  | 92285.0  | 388123.0  | 0.0      | 480408.0  | 376153.0  | 1835047.0  | 0.0      | 2211200.0  | 0.0      | 222363.0  | 0.0      | 222363.0  | 998694.0  | 859223.0  | 0.0       | 1857917.0  | 1374847.0 | 2916633.0  | 0.0       | 4291480.0  | 0.0       | 755526.0   | 0.0      | 755526.0   | 0.0      | 1244474.0 | 0.0     | 1244474.0 | 0.0       | 0.0      | 0.0     | 0.0       | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 0.0        | 2000000.0  | 0.0      | 2000000.0  | 34832.0  | 11744.0  | 0.0      | 46576.0  | 0.0      | 0.0       | 0.0      | 0.0       | 1409679.0  | 4928377.0  | 0.0       | 6338056.0   | 1352279.0 | 0.0        | 57400.0  | 1409679.0  | 1216518.0  | 135761.0  | 0.0      | 57400.0  | 1409679.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 2710079.0  | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS   | 648 BEACON STREET               | BOSTON         | MA      | 2215    | 2002     | 648 BEACON STREET         | BOSTON         | MA      | 2215    | 2002     | WWW.MLIN.LIB.MA.US                              | Y       | N      | N       | N      | N      | LSCA TITLE II, NEH, NHPRC, LSTA NLG                                             | 25       | 993945600 | 1025395200 | 2354216.0  | 399410.0  | 2753626.0  | 7125100.0  | 651400.0   | 97000.0   | 7873500.0  | 317662.0  | 10944788.0  | 141405.0  | 3573572.0 | 23880.0  | 3738857.0  | 30908.0  | 810117.0  | 6334.0   | 847359.0  | 172313.0  | 4383689.0  | 30214.0  | 4586216.0  | 53531.0  | 354082.0  | 38892.0  | 446505.0  | 1280748.0 | 2323845.0 | 138403.0  | 3742996.0  | 1506592.0 | 7061616.0  | 207509.0  | 8775717.0  | 429401.0  | 621053.0   | 0.0      | 1050454.0  | 0.0      | 0.0       | 0.0     | 0.0       | 267272.0  | 0.0      | 0.0     | 267272.0  | 0.0       | 0.0        | 0.0     | 0.0        | 547792.0  | 0.0       | 0.0     | 547792.0  | 34044.0  | 21594.0    | 0.0    | 55638.0    | 49841.0 | 0.0     | 0.0     | 49841.0 | 1328350.0  | 642647.0   | 0.0      | 1970997.0  | 5271.0   | 27371.0  | 0.0      | 32642.0  | 0.0      | 0.0       | 0.0      | 0.0       | 2840213.0  | 7731634.0  | 207509.0  | 10779356.0  | 1121130.0 | 1202054.0  | 66333.0  | 2389517.0  | 1553518.0  | 20901.0   | 748765.0 | 66333.0  | 2389517.0  | 1426283.0 | 543901.0 | 1970184.0 | 15491.0  | 0.0      | 1985675.0 | 5456453.0  | 
| DIVISION OF LIBRARY DEVELOPMENT AND SERVICES   | 200 WEST BALTIMORE STREET       | BALTIMORE      | MD      | 21201   | 2595     | 200 WEST BALTIMORE STREET | BALTIMORE      | MD      | 21201   | 2595     | WWW.MARYLANDPUBLICSCHOOLS.ORG/DIVISIONS/LDS     | Y       | N      | N       | N      | Y      | P                                                                               | 24       | 993945600 | 1025395200 | 15858909.0 | 0.0       | 15858909.0 | 18827790.0 | 74082807.0 | 0.0       | 92910597.0 | 525065.0  | 109294571.0 | 1387185.0 | 8604792.0 | 339774.0 | 10331751.0 | 335333.0 | 1791737.0 | 77545.0  | 2204615.0 | 1722518.0 | 10396529.0 | 417319.0 | 12536366.0 | 294181.0 | 1509460.0 | 93511.0  | 1897152.0 | 1675413.0 | 6921801.0 | 14235.0   | 8611449.0  | 3692112.0 | 18827790.0 | 525065.0  | 23044967.0 | 2200000.0 | 70856807.0 | 0.0      | 73056807.0 | 200000.0 | 0.0       | 0.0     | 200000.0  | 3500000.0 | 0.0      | 0.0     | 3500000.0 | 300000.0  | 3226000.0  | 0.0     | 3526000.0  | 5966797.0 | 0.0       | 0.0     | 5966797.0 | 0.0      | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 12166797.0 | 74082807.0 | 0.0      | 86249604.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 15858909.0 | 92910597.0 | 525065.0  | 109294571.0 | 3558016.0 | 12166797.0 | 134096.0 | 15858909.0 | 10000000.0 | 5000000.0 | 724813.0 | 134096.0 | 15858909.0 | 1599450.0 | 996065.0 | 2595515.0 | 0.0      | 0.0      | 2595515.0 | 35116033.0 | 
| IDAHO STATE LIBRARY                            | 325 WEST STATE STREET           | BOISE          | ID      | 83702   | 6072     | 325 WEST STATE STREET     | BOISE          | ID      | 83702   | 6072     | WWW.LILI.ORG/ISL                                | Y       | Y      | Y       | Y      | Y      | P                                                                               | 16       | 993945600 | 1025395200 | 2012001.0  | 0.0       | 2012001.0  | 1648589.0  | 6869772.0  | 0.0       | 8518361.0  | 322225.0  | 10852587.0  | 981921.0  | 1119976.0 | 58466.0  | 2160363.0  | 215544.0 | 245848.0  | 12834.0  | 474226.0  | 1197465.0 | 1365824.0  | 71300.0  | 2634589.0  | 8400.0   | 100880.0  | 7500.0   | 116780.0  | 297971.0  | 162829.0  | 80962.0   | 541762.0   | 1503836.0 | 1629533.0  | 159762.0  | 3293131.0  | 64720.0   | 1434328.0  | 0.0      | 1499048.0  | 0.0      | 0.0       | 0.0     | 0.0       | 149405.0  | 789671.0 | 0.0     | 939076.0  | 323100.0  | 2425394.0  | 0.0     | 2748494.0  | 268775.0  | 2169878.0 | 0.0     | 2438653.0 | 0.0      | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 806000.0   | 6819271.0  | 0.0      | 7625271.0  | 0.0      | 0.0      | 8700.0   | 8700.0   | 0.0      | 0.0       | 0.0      | 0.0       | 2309836.0  | 8448804.0  | 168462.0  | 10927102.0  | 1411442.0 | 806000.0   | 92394.0  | 2309836.0  | 1106264.0  | 1027884.0 | 83294.0  | 92394.0  | 2309836.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 4506542.0  | 
| ILLINOIS STATE LIBRARY                         | 300 SOUTH SECOND                | SPRINGFIELD    | IL      | 62701   | 1796     | 300 SOUTH SECOND          | SPRINGFIELD    | IL      | 62701   | 1796     | WWW.CYBERDRIVEILLINOIS.COM/LIBRARY/ISL/ISL.HTML | Y       | N      | N       | N      | N      | NEWSPAPER PROJ,LSCA TITLE II,NHPRC,SSBG ARTS & AFTER SCHL INIT,NEA PARTNSHP GR. | 17       | 993945600 | 1025395200 | 2789597.0  | 1064932.0 | 3854529.0  | 15825865.0 | 3941108.0  | 0.0       | 19766973.0 | 4484996.0 | 28106498.0  | 1033834.0 | 6344691.0 | 111034.0 | 7489559.0  | 424885.0 | 0.0       | 43664.0  | 468549.0  | 1458719.0 | 6344691.0  | 154698.0 | 7958108.0  | 116452.0 | 891999.0  | 65215.0  | 1073666.0 | 1027715.0 | 7861117.0 | 1374674.0 | 10263506.0 | 2602886.0 | 15097807.0 | 1594587.0 | 19295280.0 | 186210.0  | 1123137.0  | 0.0      | 1309347.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 817971.0 | 0.0     | 817971.0  | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 2207187.0  | 0.0    | 2207187.0  | 0.0     | 0.0     | 0.0     | 0.0     | 186210.0   | 4148295.0  | 0.0      | 4334505.0  | 0.0      | 802726.0 | 3186.0   | 805912.0 | 0.0      | 0.0       | 424710.0 | 424710.0  | 2789096.0  | 20048828.0 | 2022483.0 | 24860407.0  | 1679262.0 | 186210.0   | 20218.0  | 1885690.0  | 394319.0   | 1413405.0 | 57748.0  | 20218.0  | 1885690.0  | 1346132.0 | 87954.0  | 1434086.0 | 3186.0   | 424710.0 | 1861982.0 | 3460503.0  | 
| MINNESOTA LIBRARY DEVELOPMENT AND SERVICES     | 1500 HIGHWAY 36 WEST            | ROSEVILLE      | MN      | 55113   | 4266     | 1500 HIGHWAY 36 WEST      | ROSEVILLE      | MN      | 55113   | 4266     | CFL.STATE.MN.US/LIBRARY                         | Y       | N      | N       | N      | N      | P                                                                               | 27       | 993945600 | 1025395200 | 445806.0   | 0.0       | 445806.0   | 26377586.0 | 0.0        | 0.0       | 26377586.0 | 572000.0  | 27395392.0  | 234343.0  | 185208.0  | 0.0      | 419551.0   | 40283.0  | 30716.0   | 0.0      | 70999.0   | 274626.0  | 215924.0   | 0.0      | 490550.0   | 0.0      | 0.0       | 0.0      | 0.0       | 171180.0  | 94189.0   | 0.0       | 265369.0   | 445806.0  | 310113.0   | 0.0       | 755919.0   | 0.0       | 26067473.0 | 572000.0 | 26639473.0 | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 0.0        | 0.0    | 0.0        | 0.0     | 0.0     | 0.0     | 0.0     | 0.0        | 26067473.0 | 572000.0 | 26639473.0 | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0      | 0.0       | 445806.0   | 26377586.0 | 572000.0  | 27395392.0  | 423406.0  | 0.0        | 22400.0  | 445806.0   | 130718.0   | 270509.0  | 22179.0  | 22400.0  | 445806.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 570898.0   | 
| MISSOURI STATE LIBRARY                         | 600 WEST MAIN STREET, 2ND FLOOR | JEFFERSON CITY | MO      | 65102   | 387      | PO BOX 387                | JEFFERSON CITY | MO      | 65102   | 387      | WWW.SOS.STATE.MO.US/LIBRARY/                    | Y       | N      | N       | N      | N      | P                                                                               | 29       | 993945600 | 1025395200 | 644471.0   | 0.0       | 644471.0   | 1207118.0  | 2319500.0  | 815215.0  | 4341833.0  | 12344.0   | 4998648.0   | 270147.0  | 484638.0  | 0.0      | 754785.0   | 72265.0  | 149104.0  | 0.0      | 221369.0  | 342412.0  | 633742.0   | 0.0      | 976154.0   | 7678.0   | 12083.0   | 0.0      | 19761.0   | 96647.0   | 177350.0  | 0.0       | 273997.0   | 446737.0  | 823175.0   | 0.0       | 1269912.0  | 93620.0   | 2262583.0  | 0.0      | 2356203.0  | 0.0      | 0.0       | 0.0     | 0.0       | 0.0       | 0.0      | 0.0     | 0.0       | 0.0       | 0.0        | 0.0     | 0.0        | 0.0       | 0.0       | 0.0     | 0.0       | 0.0      | 4713722.0  | 0.0    | 4713722.0  | 61636.0 | 0.0     | 0.0     | 61636.0 | 155256.0   | 6976305.0  | 0.0      | 7131561.0  | 6842.0   | 19998.0  | 0.0      | 26840.0  | 0.0      | 1152549.0 | 12344.0  | 1164893.0 | 608835.0   | 8972027.0  | 12344.0   | 9593206.0   | 450753.0  | 155256.0   | 2826.0   | 608835.0   | 592983.0   | 0.0       | 13026.0  | 2826.0   | 608835.0   | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 807385.0   | 
| STATE LIBRARY OF OHIO                          | 274 E. 1ST AVE                  | COLUMBUS       | OH      | 43201   | 3673     | 274 E. 1ST AVE.           | COLUMBUS       | OH      | 43201   | 3673     | WINSLO.STATE.OH.US                              | Y       | Y      | N       | N      | Y      | P                                                                               | 39       | 993945600 | 1025395200 | 3711759.0  | 0.0       | 3711759.0  | 1225614.0  | 52350782.0 | 740823.0  | 54317219.0 | 0.0       | 58028978.0  | 466941.0  | 1010562.0 | 0.0      | 1477503.0  | 101883.0 | 0.0       | 0.0      | 101883.0  | 568824.0  | 1010562.0  | 0.0      | 1579386.0  | 27354.0  | 0.0       | 0.0      | 27354.0   | 368063.0  | 215052.0  | 0.0       | 583115.0   | 964241.0  | 1225614.0  | 0.0       | 2189855.0  | 779717.0  | 9212758.0  | 0.0      | 9992475.0  | 0.0      | 0.0       | 0.0     | 0.0       | 332443.0  | 0.0      | 0.0     | 332443.0  | 1227697.0 | 14680597.0 | 0.0     | 15908294.0 | 0.0       | 9429223.0 | 0.0     | 9429223.0 | 0.0      | 18883250.0 | 0.0    | 18883250.0 | 0.0     | 0.0     | 0.0     | 0.0     | 2339857.0  | 52205828.0 | 0.0      | 54545685.0 | 0.0      | 0.0      | 0.0      | 0.0      | 212743.0 | 740823.0  | 0.0      | 953566.0  | 3516841.0  | 54172265.0 | 0.0       | 57689106.0  | 1047077.0 | 2339857.0  | 129907.0 | 3516841.0  | 1670583.0  | 1716351.0 | 0.0      | 129907.0 | 3516841.0  | 0.0       | 0.0      | 0.0       | 0.0      | 0.0      | 0.0       | 6427801.0  | 
```