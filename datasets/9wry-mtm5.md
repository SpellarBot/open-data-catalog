# State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures

## Dataset

* [Dataset URL](https://data.imls.gov/api/views/9wry-mtm5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/state-libraries-survey-fy-2007-part-3-revenue-expenditures)
* [Metadata URL](https://data.imls.gov/api/views/9wry-mtm5)
* Id = 9wry-mtm5
* Name = State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures
* Attribution = IMLS
* [Attribution Link](https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey)
* Category = State Library Administrative Agencies Survey
* Tags = [state library, slaa, 2007, revenue, expenditures]
* Created = 2016-12-20T15:28:44Z
* Publication Date = 2016-12-20T17:04:38Z
* Rows Updated = 2016-12-20T17:22:38Z

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
| Zip                                | physzip    | text      | text        | series tag     | Yes      | 
| Zip+4                              | physzip4   | text      | text        | series tag     | Yes      | 
| Street (mail)                      | mailaddr   | text      | text        | series tag     | Yes      | 
| City (mail)                        | mailcity   | text      | text        | series tag     | Yes      | 
| State (mail)                       | mail_st    | text      | text        | series tag     | Yes      | 
| Zip (mail)                         | mailzip    | text      | text        | series tag     | Yes      | 
| Zip+4 (mail)                       | mailzip4   | text      | text        | series tag     | Yes      | 
| Web Address                        | webaddr    | text      | text        | series tag     | Yes      | 
| Admins state funds                 | asf_pub    | number    | text        | numeric metric | Yes      | 
| Admins state funds acad            | asf_ac     | number    | text        | numeric metric | Yes      | 
| Admins state funds school          | asf_sch    | number    | text        | numeric metric | Yes      | 
| Admins state funds special         | asf_sp     | number    | text        | numeric metric | Yes      | 
| Admins state funds co-ops          | asf_lc     | number    | text        | numeric metric | Yes      | 
| Other fed rev specified            | fiothsp    | text      | text        | series tag     | Yes      | 
| FIPS state code                    | pub_fips   | text      | text        | series tag     | Yes      | 
| BEA code                           | obereg     | number    | text        | numeric metric | Yes      | 
| Reporting Status                   | rstatus    | number    | text        | numeric metric | Yes      | 
| Fiscal year start date, mm/dd/yyyy | fystart    | date      | date        | time           | Yes      | 
| Fiscal year end date, mm/dd/yyyy   | fyend      | date      | date        |                | No       | 
| LSTA revenue                       | lstainc    | money     | money       | numeric metric | Yes      | 
| Other federal revenue              | fioth      | money     | money       | numeric metric | Yes      | 
| Total federal revenue              | total_fi   | money     | money       | numeric metric | Yes      | 
| St rev STLA operation              | sistlaop   | money     | money       | numeric metric | Yes      | 
| St rev aid to libraries            | siaidlib   | money     | money       | numeric metric | Yes      | 
| St rev other                       | siother    | money     | money       | numeric metric | Yes      | 
| St rev TOTAL                       | total_si   | money     | money       | numeric metric | Yes      | 
| Other revenue                      | othincm    | money     | money       | numeric metric | Yes      | 
| Total revenue                      | totincm    | money     | money       | numeric metric | Yes      | 
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
| LSTA exp statewide svcs            | swexpt     | money     | money       | numeric metric | Yes      | 
| LSTA exp grants                    | grexpt     | money     | money       | numeric metric | Yes      | 
| LSTA exp LSTA admin                | admexpt    | money     | money       | numeric metric | Yes      | 
| LSTA exp by type/TOTAL             | totexpt    | money     | money       | numeric metric | Yes      | 
| LSTA exp technology                | techxu     | money     | money       | numeric metric | Yes      | 
| LSTA exp svcs to disab             | serdifxu   | money     | money       | numeric metric | Yes      | 
| LSTA exp lifelong learning         | serllxu    | money     | money       | numeric metric | Yes      | 
| LSTA exp by use/LSTA admin         | admexpu    | money     | money       | numeric metric | Yes      | 
| LSTA exp by use/TOTAL              | totexpu    | money     | money       | numeric metric | Yes      | 
| Population                         | popu_st    | number    | number      | numeric metric | Yes      | 
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
series e:9wry-mtm5 d:2006-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:pub_fips=2 t:physaddr="333 WILLOUGHBY AVENUE" t:asf_ac=Y t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:physzip=99811 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=891400 m:siother=90403 m:totaida=872718 m:aidsala=443008 m:capitald=0 m:admexpt=14735 m:swexpt=0 m:admexpu=14735 m:oexpbenb=852843 m:oexpbena=8105 m:oexpbend=877867 m:oexpbenc=16919 m:totincm=5099564 m:othincm=35300 m:obereg=8 m:aidlcd=0 m:aidlcc=0 m:totexpu=887453 m:totexpt=887453 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=5073528 m:totexpa=887453 m:totexpc=99667 m:totexpb=4086408 m:sistlaop=3195008 m:aidmlsa=182762 m:popu_st=683478 m:aidmlsc=11944 m:aidmlsb=8785 m:totoxstc=53713 m:totoxstd=2468844 m:rstatus=1 m:aidmlsd=203491 m:serllxu=328659 m:totopexc=53713 m:totopexd=3263456 m:totopexa=14735 m:aidothd=0 m:totopexb=3195008 m:aidothc=0 m:oexpothc=0 m:aidothb=0 m:oexpothd=586210 m:aidotha=0 m:total_fi=887453 m:oexpotha=0 m:oexpothb=586210 m:aidplsc=25000 m:aidplsd=121925 m:total_si=4176811 m:totoxstb=2400396 m:totoxsta=14735 m:oexpcold=208402 m:lstainc=887453 m:aidplsa=96925 m:oexpcolb=208402 m:grexpt=872718 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=269749 m:oexpsalb=1547553 m:othexpd=0 m:aidiplc=2261 m:oexpcola=0 m:oexpsalc=36794 m:aidipld=767959 m:siaidlib=891400 m:othexpb=0 m:aidipla=113388 m:oexpsala=6630 m:aidoila=36635 m:othexpc=0 m:aidiplb=652310 m:aidoilb=85389 m:aidsald=587924 m:totaidd=1810072 m:aidoilc=6749 m:totaidc=45954 m:techxu=274310 m:oexpsald=1590977 m:aidoild=128773 m:aidsalb=144916 m:aidsalc=0 m:othexpa=0

series e:9wry-mtm5 d:2006-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=N t:mail_st=AL t:pub_fips=1 t:physaddr="6030 MONTICELLO DRIVE" t:asf_ac=N t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:asf_sp=N t:physzip=36117 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=8666208 m:siother=3757600 m:totaida=1122311 m:aidsala=86775 m:capitald=0 m:admexpt=104267 m:swexpt=1383970 m:admexpu=104267 m:oexpbenb=701449 m:oexpbena=0 m:oexpbend=702117 m:oexpbenc=668 m:totincm=14724932 m:othincm=550550 m:obereg=5 m:aidlcd=0 m:aidlcc=0 m:totexpu=2610548 m:totexpt=2610548 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=14542933 m:totexpa=2610549 m:totexpc=550550 m:totexpb=11381834 m:sistlaop=2715626 m:aidmlsa=51200 m:popu_st=4627851 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=2183 m:totoxstd=2717809 m:rstatus=1 m:aidmlsd=51200 m:serllxu=679733 m:totopexc=65635 m:totopexd=4269499 m:totopexa=1488238 m:aidothd=38705 m:totopexb=2715626 m:aidothc=38705 m:oexpothc=63452 m:aidothb=0 m:oexpothd=1527816 m:aidotha=0 m:total_fi=2610548 m:oexpotha=1464364 m:oexpothb=0 m:aidplsc=0 m:aidplsd=96500 m:total_si=11563834 m:totoxstb=2715626 m:totoxsta=0 m:oexpcold=23874 m:lstainc=2610548 m:aidplsa=96500 m:oexpcolb=0 m:grexpt=1122311 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=523010 m:oexpsalb=2014177 m:othexpd=0 m:aidiplc=446210 m:oexpcola=23874 m:oexpsalc=1515 m:aidipld=6424654 m:siaidlib=5090608 m:othexpb=0 m:aidipla=887836 m:oexpsala=0 m:aidoila=0 m:othexpc=0 m:aidiplb=5090608 m:aidoilb=0 m:aidsald=3662375 m:totaidd=10273434 m:aidoilc=0 m:totaidc=484915 m:techxu=1303538 m:oexpsald=2015692 m:aidoild=0 m:aidsalb=3575600 m:aidsalc=0 m:othexpa=0

series e:9wry-mtm5 d:2006-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:pub_fips=5 t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:asf_ac=N t:phys_st=AR t:mailzip=72201 t:mailzip4=1013 t:asf_pub=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1013 t:asf_sch=N t:webaddr=WWW.ASL.LIB.AR.US t:asf_sp=N t:physzip=72201 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=73085 m:totaidb=4000000 m:siother=113864 m:totaida=0 m:aidsala=0 m:capitald=73085 m:admexpt=12847 m:swexpt=1777242 m:admexpu=12847 m:oexpbenb=430747 m:oexpbena=116130 m:oexpbend=546877 m:oexpbenc=0 m:totincm=8623376 m:othincm=46800 m:obereg=5 m:aidlcd=0 m:aidlcc=0 m:totexpu=1790089 m:totexpt=1790089 m:fioth=0 m:aidlca=0 m:aidlcb=0 m:totexpd=8928842 m:totexpa=1790089 m:totexpc=158741 m:totexpb=6980012 m:sistlaop=2980012 m:aidmlsa=0 m:popu_st=2834797 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=0 m:totoxstd=2378113 m:rstatus=1 m:aidmlsd=0 m:serllxu=373110 m:totopexc=39491 m:totopexd=4736507 m:totopexa=1717004 m:aidothd=0 m:totopexb=2980012 m:aidothc=0 m:oexpothc=39491 m:aidothb=0 m:oexpothd=1945418 m:aidotha=0 m:total_fi=1482700 m:oexpotha=945674 m:oexpothb=960253 m:aidplsc=0 m:aidplsd=0 m:total_si=7093876 m:totoxstb=1955210 m:totoxsta=422903 m:oexpcold=412976 m:lstainc=1482700 m:aidplsa=0 m:oexpcolb=64549 m:grexpt=0 m:aidplsb=0 m:oexpcolc=0 m:serdifxu=643485 m:oexpsalb=1524463 m:othexpd=0 m:aidiplc=119250 m:oexpcola=348427 m:oexpsalc=0 m:aidipld=4119250 m:siaidlib=4000000 m:othexpb=0 m:aidipla=0 m:oexpsala=306773 m:aidoila=0 m:othexpc=0 m:aidiplb=4000000 m:aidoilb=0 m:aidsald=0 m:totaidd=4119250 m:aidoilc=0 m:totaidc=119250 m:techxu=760647 m:oexpsald=1831236 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
```

## Meta Commands

```ls
metric m:obereg p:integer l:"BEA code" t:dataTypeName=number

metric m:rstatus p:integer l:"Reporting Status" t:dataTypeName=number

metric m:popu_st l:Population t:dataTypeName=number

entity e:9wry-mtm5 l:"State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9wry-mtm5

property e:9wry-mtm5 t:meta.view d:2017-03-07T23:55:13.655Z v:id=9wry-mtm5 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2007, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:9wry-mtm5 t:meta.view.license d:2017-03-07T23:55:13.655Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9wry-mtm5 t:meta.view.owner d:2017-03-07T23:55:13.655Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9wry-mtm5 t:meta.view.tableauthor d:2017-03-07T23:55:13.655Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9wry-mtm5 t:meta.view.metadata.custom_fields.common_core d:2017-03-07T23:55:13.655Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```