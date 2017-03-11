# State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2010-part-3-revenue-expenditures) |
| Metadata | [Link](https://data.imls.gov/api/views/mjb9-rsyd) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/mjb9-rsyd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/mjb9-rsyd/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | mjb9-rsyd |
| Name | State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2010, revenue, expenditures |
| Created | 2016-12-20T15:32:24Z |
| Publication Date | 2016-12-20T17:04:41Z |
| Rows Updated | 2016-12-20T17:24:15Z |

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
| Yes      | numeric metric | asf_pub    | Admins state funds                 | number    | text        |
| Yes      | numeric metric | asf_ac     | Admins state funds acad            | number    | text        |
| Yes      | numeric metric | asf_sch    | Admins state funds school          | number    | text        |
| Yes      | numeric metric | asf_sp     | Admins state funds special         | number    | text        |
| Yes      | numeric metric | asf_lc     | Admins state funds co-ops          | number    | text        |
| Yes      | series tag     | fiothsp    | Other fed rev specified            | text      | text        |
| Yes      | series tag     | fipsst     | FIPS state code                    | text      | text        |
| Yes      | numeric metric | obereg     | BEA code                           | number    | text        |
| Yes      | numeric metric | rstatus    | Reporting Status                   | number    | text        |
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
series e:mjb9-rsyd d:2009-07-01T00:00:00.000Z t:physcity=JUNEAU t:mailcity=JUNEAU t:asf_lc=Y t:mail_st=AK t:physaddr="333 WILLOUGHBY AVENUE" t:asf_ac=Y t:phys_st=AK t:mailzip=99811 t:mailzip4=571 t:asf_pub=N t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:asf_sch=N t:webaddr=WWW.LIBRARY.STATE.AK.US t:asf_sp=Y t:physzip=99811 t:fipsst=2 t:fiothsp=P m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=101570615 m:siother=0 m:totaida=3779717 m:aidsala=0 m:capitald=0 m:admexpt=369346 m:swexpt=5315887 m:admexpu=369346 m:oexpbenb=0 m:oexpbena=1398640 m:oexpbend=1398640 m:oexpbenc=0 m:totincm=122217928 m:othincm=66016 m:obereg=2 m:aidlcd=14000000 m:aidlcc=0 m:totexpu=9464950 m:totexpt=9464950 m:fioth=0 m:aidlca=0 m:aidlcb=14000000 m:totexpd=120411470 m:totexpa=9482726 m:totexpc=80044 m:totexpb=110848700 m:sistlaop=9484211 m:aidmlsa=73999 m:popu_st=19378102 m:aidmlsc=0 m:aidmlsb=6102313 m:totoxstc=0 m:totoxstd=10443225 m:rstatus=1 m:aidmlsd=6176312 m:serllxu=2115690 m:totopexc=80044 m:totopexd=15061138 m:totopexa=5703009 m:aidothd=10881941 m:totopexb=9278085 m:aidothc=0 m:oexpothc=80044 m:aidothb=7709455 m:oexpothd=1201681 m:aidotha=3172486 m:total_fi=11491848 m:oexpotha=974469 m:oexpothb=147168 m:aidplsc=0 m:aidplsd=27011704 m:total_si=110660064 m:totoxstb=5714685 m:totoxsta=4728540 m:oexpcold=3416232 m:lstainc=11491848 m:aidplsa=362130 m:oexpcolb=3416232 m:grexpt=3779717 m:aidplsb=26649574 m:oexpcolc=0 m:serdifxu=73774 m:oexpsalb=5714685 m:othexpd=0 m:aidiplc=0 m:oexpcola=0 m:oexpsalc=0 m:aidipld=42409901 m:siaidlib=101175853 m:othexpb=0 m:aidipla=171102 m:oexpsala=3329900 m:aidoila=0 m:othexpc=0 m:aidiplb=42238799 m:aidoilb=4870474 m:aidsald=0 m:totaidd=105350332 m:aidoilc=0 m:totaidc=0 m:techxu=6906140 m:oexpsald=9044585 m:aidoild=4870474 m:aidsalb=0 m:aidsalc=0 m:othexpa=0

series e:mjb9-rsyd d:2009-10-01T00:00:00.000Z t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:asf_lc=Y t:mail_st=AL t:physaddr="6030 MONTICELLO DRIVE" t:asf_ac=N t:phys_st=AL t:mailzip=36130 t:mailzip4=1 t:asf_pub=N t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:asf_sch=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:asf_sp=N t:physzip=36117 t:fipsst=1 t:fiothsp="IMLS - CONNECTING TO COLLECTIONS -C2C" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=1937663 m:siother=9000 m:totaida=3872381 m:aidsala=2846562 m:capitald=0 m:admexpt=58260 m:swexpt=1497028 m:admexpu=58260 m:oexpbenb=865737 m:oexpbena=140327 m:oexpbend=1180832 m:oexpbenc=174768 m:totincm=22263846 m:othincm=5826807 m:obereg=3 m:aidlcd=0 m:aidlcc=0 m:totexpu=5427669 m:totexpt=5427669 m:fioth=24200 m:aidlca=0 m:aidlcb=0 m:totexpd=20994486 m:totexpa=5451174 m:totexpc=4722369 m:totexpb=10820943 m:sistlaop=9227079 m:aidmlsa=254030 m:popu_st=11536504 m:aidmlsc=0 m:aidmlsb=582469 m:totoxstc=699070 m:totoxstd=4723327 m:rstatus=2 m:aidmlsd=836499 m:serllxu=230885 m:totopexc=3706419 m:totopexd=14168492 m:totopexa=1578793 m:aidothd=571991 m:totopexb=8883280 m:aidothc=0 m:oexpothc=2507349 m:aidothb=0 m:oexpothd=7296753 m:aidotha=571991 m:total_fi=5263297 m:oexpotha=781694 m:oexpothb=4007710 m:aidplsc=0 m:aidplsd=0 m:total_si=11173742 m:totoxstb=3462946 m:totoxsta=561311 m:oexpcold=2148412 m:lstainc=5239097 m:aidplsa=0 m:oexpcolb=1412624 m:grexpt=3872381 m:aidplsb=0 m:oexpcolc=500000 m:serdifxu=386409 m:oexpsalb=2597209 m:othexpd=0 m:aidiplc=1015950 m:oexpcola=235788 m:oexpsalc=524302 m:aidipld=1269721 m:siaidlib=1937663 m:othexpb=0 m:aidipla=172771 m:oexpsala=420984 m:aidoila=27027 m:othexpc=0 m:aidiplb=81000 m:aidoilb=0 m:aidsald=4120756 m:totaidd=6825994 m:aidoilc=0 m:totaidc=1015950 m:techxu=4752115 m:oexpsald=3542495 m:aidoild=27027 m:aidsalb=1274194 m:aidsalc=0 m:othexpa=0

series e:mjb9-rsyd d:2009-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:asf_lc=N t:mail_st=AR t:physaddr="900 WEST CAPITOL, SUITE 100" t:asf_ac=N t:phys_st=AR t:mailzip=72201 t:mailzip4=3108 t:asf_pub=Y t:mailaddr="900 WEST CAPITOL, SUITE 100" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=3108 t:asf_sch=N t:webaddr=WWW.library.arkansas.gov t:asf_sp=N t:physzip=72201 t:fipsst=5 t:fiothsp="NATIONAL LEADERSHIP GRANT/IMLSNATIONAL HISTORICAL & RECORDS COMMISSIONTANF - TEMPORARY ASSISTANCE TO NEEDY FAMILIES" m:capitalc=0 m:capitalb=0 m:capitala=0 m:totaidb=2259454 m:siother=0 m:totaida=1010629 m:aidsala=52701 m:capitald=0 m:admexpt=16793 m:swexpt=1763641 m:admexpu=16793 m:oexpbenb=994649 m:oexpbena=122120 m:oexpbend=1132087 m:oexpbenc=15318 m:totincm=9730343 m:othincm=336653 m:obereg=6 m:aidlcd=0 m:aidlcc=0 m:totexpu=2033214 m:totexpt=2033214 m:fioth=861572 m:aidlca=0 m:aidlcb=0 m:totexpd=9738477 m:totexpa=3026773 m:totexpc=320235 m:totexpb=6391469 m:sistlaop=4261818 m:aidmlsa=0 m:popu_st=3751351 m:aidmlsc=0 m:aidmlsb=0 m:totoxstc=59097 m:totoxstd=3467489 m:rstatus=1 m:aidmlsd=0 m:serllxu=264852 m:totopexc=320235 m:totopexd=6468394 m:totopexa=2016144 m:aidothd=705148 m:totopexb=4132015 m:aidothc=0 m:oexpothc=255587 m:aidothb=0 m:oexpothd=1451216 m:aidotha=705148 m:total_fi=2894787 m:oexpotha=621295 m:oexpothb=574334 m:aidplsc=0 m:aidplsd=0 m:total_si=6498903 m:totoxstb=3048762 m:totoxsta=359630 m:oexpcold=1549689 m:lstainc=2033215 m:aidplsa=0 m:oexpcolb=508919 m:grexpt=252780 m:aidplsb=0 m:oexpcolc=5551 m:serdifxu=202289 m:oexpsalb=2054113 m:othexpd=0 m:aidiplc=0 m:oexpcola=1035219 m:oexpsalc=43779 m:aidipld=2512234 m:siaidlib=2237085 m:othexpb=0 m:aidipla=252780 m:oexpsala=237510 m:aidoila=0 m:othexpc=0 m:aidiplb=2259454 m:aidoilb=0 m:aidsald=52701 m:totaidd=3270083 m:aidoilc=0 m:totaidc=0 m:techxu=1549280 m:oexpsald=2335402 m:aidoild=0 m:aidsalb=0 m:aidsalc=0 m:othexpa=0
```

## Meta Commands

```ls
metric m:obereg p:integer l:"BEA code" t:dataTypeName=number

metric m:rstatus p:integer l:"Reporting Status" t:dataTypeName=number

metric m:popu_st l:Population t:dataTypeName=number

entity e:mjb9-rsyd l:"State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures" t:attribution=IMLS t:url=https://data.imls.gov/api/views/mjb9-rsyd

property e:mjb9-rsyd t:meta.view v:id=mjb9-rsyd v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2010, Part 3: Revenue & Expenditures" v:attribution=IMLS

property e:mjb9-rsyd t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:mjb9-rsyd t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:mjb9-rsyd t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:mjb9-rsyd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```