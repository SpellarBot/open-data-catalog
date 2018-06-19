# State Libraries Survey, FY 2014, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2014-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/ega2-r6pd) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ega2-r6pd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ega2-r6pd/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ega2-r6pd |
| Name | State Libraries Survey, FY 2014, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2014, operations, workforce |
| Created | 2016-12-20T15:33:51Z |
| Publication Date | 2016-12-20T17:04:43Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========== | ========================================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                                                  | text      | text        |
| Yes      | series tag     | physaddr   | Street                                                     | text      | text        |
| Yes      | series tag     | physcity   | City                                                       | text      | text        |
| Yes      | series tag     | phys_st    | State                                                      | text      | text        |
| Yes      | series tag     | physzip    | Zip                                                        | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                                                      | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                                              | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                                                | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                                               | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                                                 | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                                               | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                                                | text      | text        |
| Yes      | series tag     | branch     | Branch of government [L]egis/[E]xec                        | text      | text        |
| Yes      | series tag     | indagy     | SLAA reports to [G]overnor/[B]oard                         | text      | text        |
| Yes      | series tag     | appbygov   | Appointed by governor [X]Yes/[P]n/a                        | text      | text        |
| Yes      | series tag     | appbyoth   | Appointed by other official [X]Yes/[P]n/a                  | text      | text        |
| Yes      | series tag     | largerag   | Part of Dept of [E]duc/[C]ult Resrc/[S]tate/[O]ther/[P]n/a | text      | text        |
| Yes      | series tag     | othagsp    | Other agency; [P]n/a                                       | text      | text        |
| Yes      | series tag     | pla_brco   | SLAA is sub-agency, has board [Y]es/[N]o/[P]n/a            | text      | text        |
| Yes      | series tag     | pla_gov    | Board appointed by Governor [X]Yes/[P]n/a                  | text      | text        |
| Yes      | series tag     | pld_oth    | Board appointed by other official [X]Yes/[P]n/a            | text      | text        |
| Yes      | series tag     | starchiv   | State archives                                             | text      | text        |
| Yes      | series tag     | stlegref   | Primary state legislative research organization            | text      | text        |
| Yes      | series tag     | sthstmus   | State history museum/art gallery                           | text      | text        |
| Yes      | series tag     | strecmng   | State records management service                           | text      | text        |
| Yes      | series tag     | othallop   | Other allied operation                                     | text      | text        |
| Yes      | series tag     | othallsp   | Other allied operation; [P]n/a                             | text      | text        |
| Yes      | series tag     | stlacont   | SLAA contracts with local/academic libraries               | text      | text        |
| Yes      | series tag     | stlahost   | SLAA hosts or funds State Center for the Book              | text      | text        |
| Yes      | series tag     | stdeplib   | State depository library                                   | text      | text        |
| Yes      | series tag     | fddeplib   | Federal depository library                                 | text      | text        |
| Yes      | series tag     | regional   | Regional fed dep library                                   | text      | text        |
| Yes      | series tag     | selectiv   | Selective fed dep library                                  | text      | text        |
| Yes      | series tag     | elecplan   | Network planning/monitoring                                | text      | text        |
| Yes      | series tag     | elecoper   | Network operation                                          | text      | text        |
| Yes      | series tag     | elecbibl   | DB/Bibliographic databases                                 | text      | text        |
| Yes      | series tag     | electext   | DB/Full text or data                                       | text      | text        |
| Yes      | series tag     | dig_stla   | Digitization support/STLA                                  | text      | text        |
| Yes      | series tag     | dig_ag     | Digitization support/Other agencies                        | text      | text        |
| Yes      | series tag     | dig_lib    | Digitization support/libraries                             | text      | text        |
| Yes      | series tag     | nettrstf   | Internet access support thru staffing                      | text      | text        |
| Yes      | series tag     | nettrcus   | Internet access support thru st lib end-users              | text      | text        |
| Yes      | series tag     | netsub     | Internet access support thru direct funding                | text      | text        |
| Yes      | series tag     | netequip   | Intenet access support thru prov equip                     | text      | text        |
| Yes      | series tag     | netmount   | Internet access support thru online resrcs                 | text      | text        |
| Yes      | series tag     | netgoph    | Internet access support thru website/server/list mgmt      | text      | text        |
| Yes      | series tag     | pubswdbl   | DBs avail to public libr                                   | text      | text        |
| Yes      | series tag     | acswdbl    | DBs avail to acad libr                                     | text      | text        |
| Yes      | series tag     | schswdbl   | DBs avail to sch libr                                      | text      | text        |
| Yes      | series tag     | spcswdbl   | DBs avail to special libr                                  | text      | text        |
| Yes      | series tag     | lcswdbl    | DBs avail to co-ops                                        | text      | text        |
| Yes      | series tag     | othswdbl   | DBs avail to state agencies                                | text      | text        |
| Yes      | series tag     | remoteac   | DBs avail to remote users                                  | text      | text        |
| Yes      | series tag     | accwbcat   | Union catalog                                              | text      | text        |
| Yes      | series tag     | accoth     | Other access to other libr                                 | text      | text        |
| Yes      | series tag     | othaccsp   | Other access specified                                     | text      | text        |
| Yes      | series tag     | erateapp   | E-rate discount                                            | text      | text        |
| Yes      | series tag     | fipsst     | FIPS state code                                            | text      | text        |
| Yes      | series tag     | obereg     | BEA code                                                   | text      | text        |
| Yes      | series tag     | rstatus    | Reporting Status                                           | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy                         | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy                           | date      | date        |
| Yes      | numeric metric | tothrs     | Hours open typical week                                    | number    | number      |
| Yes      | numeric metric | tothrsce   | Hours open main outlet                                     | number    | number      |
| Yes      | numeric metric | mon2frce   | Hours open M-F after 5pm                                   | number    | number      |
| Yes      | numeric metric | satsunce   | Hours open Sat & Sun                                       | number    | number      |
| Yes      | numeric metric | mainout    | Outlets (main)                                             | number    | number      |
| Yes      | numeric metric | otherout   | Outlets (other)                                            | number    | number      |
| Yes      | numeric metric | bkmobile   | Outlets (bookmobile)                                       | number    | number      |
| Yes      | numeric metric | totalout   | Outlets (TOTAL)                                            | number    | number      |
| Yes      | numeric metric | bphouta    | BPH Outlets (main)                                         | number    | number      |
| Yes      | numeric metric | bphoutb    | BPH Outlets (other)                                        | number    | number      |
| Yes      | numeric metric | bphoutc    | BPH Outlets (bookmobile)                                   | number    | number      |
| Yes      | numeric metric | bphoutd    | BPH Outlets (TOTAL)                                        | number    | number      |
| Yes      | numeric metric | corouta    | Corr Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | coroutb    | Corr Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | coroutc    | Corr Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | coroutd    | Corr Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | otstouta   | Inst Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | otstoutb   | Inst Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | otstoutc   | Inst Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | otstoutd   | Inst Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | gvemouta   | Govt Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | gvemoutb   | Govt Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | gvemoutc   | Govt Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | gvemoutd   | Govt Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | gpouta     | Pub Outlets (main)                                         | number    | number      |
| Yes      | numeric metric | gpoutb     | Pub Outlets (other)                                        | number    | number      |
| Yes      | numeric metric | gpoutc     | Pub Outlets (bookmobile)                                   | number    | number      |
| Yes      | numeric metric | gpoutd     | Pub Outlets (TOTAL)                                        | number    | number      |
| Yes      | numeric metric | bkservol   | Volumes                                                    | number    | number      |
| Yes      | numeric metric | audio      | Audio Materials                                            | number    | number      |
| Yes      | numeric metric | video      | Video Materials                                            | number    | number      |
| Yes      | numeric metric | subscrip   | Serial Subs                                                | number    | number      |
| Yes      | numeric metric | govdoc     | Govt Documents                                             | number    | number      |
| Yes      | numeric metric | circ       | Circulation                                                | number    | number      |
| Yes      | numeric metric | provto     | ILL out                                                    | number    | number      |
| Yes      | numeric metric | recfrom    | ILL in                                                     | number    | number      |
| Yes      | numeric metric | reftrans   | Reference transactions                                     | number    | number      |
| Yes      | numeric metric | libvists   | Library visits                                             | number    | number      |
| Yes      | numeric metric | grantaw    | Grants awarded                                             | number    | number      |
| Yes      | numeric metric | events     | Number of events                                           | number    | number      |
| Yes      | numeric metric | atevents   | Total attendance                                           | number    | number      |
| Yes      | numeric metric | madmin     | Admin ALA-MLS                                              | number    | number      |
| Yes      | numeric metric | nadmin     | Admin non-MLS                                              | number    | number      |
| Yes      | numeric metric | oadmin     | Admin other                                                | number    | number      |
| Yes      | numeric metric | admin      | Admin TOTAL                                                | number    | number      |
| Yes      | numeric metric | mlibdev    | Dev ALA-MLS                                                | number    | number      |
| Yes      | numeric metric | nlibdev    | Dev non-MLS                                                | number    | number      |
| Yes      | numeric metric | olibdev    | Dev other                                                  | number    | number      |
| Yes      | numeric metric | libdev     | Dev TOTAL                                                  | number    | number      |
| Yes      | numeric metric | mlibserv   | Services ALA-MLS                                           | number    | number      |
| Yes      | numeric metric | nlibserv   | Services non-MLS                                           | number    | number      |
| Yes      | numeric metric | olibserv   | Services other                                             | number    | number      |
| Yes      | numeric metric | libserv    | Services TOTAL                                             | number    | number      |
| Yes      | numeric metric | mothserv   | Other ALA-MLS                                              | number    | number      |
| Yes      | numeric metric | nothserv   | Other non-MLS                                              | number    | number      |
| Yes      | numeric metric | oothserv   | Other other                                                | number    | number      |
| Yes      | numeric metric | othserv    | Other TOTAL                                                | number    | number      |
| Yes      | numeric metric | mtotstaf   | Total ALA-MLS                                              | number    | number      |
| Yes      | numeric metric | ntotstaf   | Total non-MLS                                              | number    | number      |
| Yes      | numeric metric | ototstaf   | Total other                                                | number    | number      |
| Yes      | numeric metric | totstaf    | TOTAL STAFF                                                | number    | number      |
| Yes      | numeric metric | pagiw_lo   | Internet access thru lib owned terminals                   | number    | number      |
| Yes      | numeric metric | paiw_oth   | Internet access thru other terminals                       | number    | number      |
| Yes      | numeric metric | swdblica   | DB licensing exp federal                                   | number    | number      |
| Yes      | numeric metric | swdblicb   | DB licensing exp state                                     | number    | number      |
| Yes      | numeric metric | swdblicc   | DB licensing exp other                                     | number    | number      |
| Yes      | numeric metric | swdblicd   | DB licensing exp TOTAL                                     | number    | number      |
| Yes      | numeric metric | popu_st    | Population                                                 | number    | number      |
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
series e:ega2-r6pd d:2013-07-01T00:00:00.000Z t:appbygov=P t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=1770 t:webaddr=WWW.LIBRARY.ALASKA.GOV t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:obereg=8 t:elecbibl=Y t:phys_st=AK t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=Y t:pld_oth=P t:strecmng=Y t:accoth=N t:largerag=E t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=2 t:schswdbl=Y t:nettrstf=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=99801 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=571 t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:libserv=18 m:mainout=1 m:bkservol=113208 m:ototstaf=17.75 m:govdoc=622810 m:othserv=1 m:ntotstaf=0 m:libvists=20505 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=1 m:nlibserv=0 m:oadmin=5.5 m:video=1580 m:otstoutd=0 m:otstoutc=0 m:atevents=1794 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=1 m:totstaf=31.25 m:grantaw=248 m:swdblicd=353480 m:tothrsce=34 m:coroutd=0 m:swdblicb=138200 m:coroutb=0 m:oothserv=1 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=117 m:olibdev=3.75 m:corouta=0 m:swdblica=215280 m:madmin=1 m:gvemoutd=1 m:recfrom=2637 m:gvemoutc=0 m:olibserv=7.5 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=1 m:bphoutb=1 m:bphouta=0 m:provto=725 m:popu_st=736732 m:bphoutd=1 m:mlibdev=2 m:subscrip=280 m:paiw_oth=0 m:reftrans=40374 m:audio=388 m:gpouta=1 m:pagiw_lo=11 m:mlibserv=10.5 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=2 m:circ=875 m:admin=6.5 m:libdev=5.75 m:tothrs=76 m:mtotstaf=13.5

series e:ega2-r6pd d:2013-10-01T00:00:00.000Z t:appbygov=X t:physaddr="6030 MONTICELLO DRIVE" t:stlacont=N t:mailzip=36130 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=AL t:obereg=5 t:elecbibl=Y t:phys_st=AL t:pla_gov=P t:netsub=N t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=1 t:schswdbl=Y t:nettrstf=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:elecoper=N t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=36117 t:dig_stla=N t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=6000 t:othaccsp=P t:netequip=Y t:pla_brco=P t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=Y m:libserv=12 m:mainout=1 m:bkservol=90425 m:ototstaf=19 m:govdoc=0 m:othserv=2 m:ntotstaf=0 m:libvists=260 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=0 m:oadmin=9 m:video=0 m:otstoutd=0 m:otstoutc=0 m:atevents=3154 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:totstaf=31 m:grantaw=115 m:swdblicd=987868 m:tothrsce=40 m:coroutd=0 m:swdblicb=269800 m:coroutb=0 m:oothserv=2 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=66 m:olibdev=0 m:corouta=0 m:swdblica=718068 m:madmin=2 m:gvemoutd=1 m:recfrom=1207 m:gvemoutc=0 m:olibserv=8 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=1 m:bphoutb=0 m:bphouta=1 m:provto=523 m:popu_st=4849377 m:bphoutd=1 m:mlibdev=6 m:subscrip=25 m:paiw_oth=0 m:reftrans=520 m:audio=0 m:gpouta=0 m:pagiw_lo=0 m:mlibserv=4 m:gpoutb=0 m:gpoutc=0 m:gpoutd=0 m:totalout=1 m:circ=800 m:admin=11 m:libdev=6 m:tothrs=40 m:mtotstaf=12

series e:ega2-r6pd d:2013-07-01T00:00:00.000Z t:appbygov=P t:physaddr="900 WEST CAPITOL, SUITE 100" t:stlacont=N t:mailzip=72201 t:netmount=Y t:mailaddr="900 WEST CAPITOL, SUITE 100" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=3108 t:webaddr=WWW.LIBRARY.ARKANSAS.GOV t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=N t:mail_st=AR t:obereg=5 t:elecbibl=Y t:phys_st=AR t:pla_gov=X t:netsub=N t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=E t:dig_lib=N t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=5 t:schswdbl=Y t:nettrstf=Y t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=72201 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=3108 t:othaccsp=P t:netequip=N t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:stlegref=N t:selectiv=N t:indagy=P t:acswdbl=Y m:libserv=32.5 m:mainout=1 m:bkservol=51157 m:ototstaf=31.5 m:govdoc=0 m:othserv=0 m:ntotstaf=0 m:libvists=3267 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=0 m:oadmin=10 m:video=135 m:otstoutd=0 m:otstoutc=0 m:atevents=594 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:totstaf=51.5 m:grantaw=0 m:swdblicd=966816 m:tothrsce=45 m:coroutd=0 m:swdblicb=165000 m:coroutb=0 m:oothserv=0 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=41 m:olibdev=1 m:corouta=0 m:swdblica=801816 m:madmin=2 m:gvemoutd=1 m:recfrom=201 m:gvemoutc=0 m:olibserv=20.5 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=1 m:bphoutb=0 m:bphouta=1 m:provto=1156 m:popu_st=2966369 m:bphoutd=1 m:mlibdev=6 m:subscrip=459 m:paiw_oth=0 m:reftrans=2314 m:audio=124 m:gpouta=1 m:pagiw_lo=10 m:mlibserv=12 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=1 m:circ=2578 m:admin=12 m:libdev=7 m:tothrs=45 m:mtotstaf=20
```

## Meta Commands

```ls
metric m:tothrs p:integer l:"Hours open typical week" t:dataTypeName=number

metric m:tothrsce p:integer l:"Hours open main outlet" t:dataTypeName=number

metric m:mon2frce p:integer l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:satsunce p:integer l:"Hours open Sat & Sun" t:dataTypeName=number

metric m:mainout p:integer l:"Outlets (main)" t:dataTypeName=number

metric m:otherout p:integer l:"Outlets (other)" t:dataTypeName=number

metric m:bkmobile p:integer l:"Outlets (bookmobile)" t:dataTypeName=number

metric m:totalout p:integer l:"Outlets (TOTAL)" t:dataTypeName=number

metric m:bphouta p:integer l:"BPH Outlets (main)" t:dataTypeName=number

metric m:bphoutb p:integer l:"BPH Outlets (other)" t:dataTypeName=number

metric m:bphoutc p:integer l:"BPH Outlets (bookmobile)" t:dataTypeName=number

metric m:bphoutd p:integer l:"BPH Outlets (TOTAL)" t:dataTypeName=number

metric m:corouta p:integer l:"Corr Outlets (main)" t:dataTypeName=number

metric m:coroutb p:integer l:"Corr Outlets (other)" t:dataTypeName=number

metric m:coroutc p:integer l:"Corr Outlets (bookmobile)" t:dataTypeName=number

metric m:coroutd p:integer l:"Corr Outlets (TOTAL)" t:dataTypeName=number

metric m:otstouta p:integer l:"Inst Outlets (main)" t:dataTypeName=number

metric m:otstoutb p:integer l:"Inst Outlets (other)" t:dataTypeName=number

metric m:otstoutc p:integer l:"Inst Outlets (bookmobile)" t:dataTypeName=number

metric m:otstoutd p:integer l:"Inst Outlets (TOTAL)" t:dataTypeName=number

metric m:gvemouta p:integer l:"Govt Outlets (main)" t:dataTypeName=number

metric m:gvemoutb p:integer l:"Govt Outlets (other)" t:dataTypeName=number

metric m:gvemoutc p:integer l:"Govt Outlets (bookmobile)" t:dataTypeName=number

metric m:gvemoutd p:integer l:"Govt Outlets (TOTAL)" t:dataTypeName=number

metric m:gpouta p:integer l:"Pub Outlets (main)" t:dataTypeName=number

metric m:gpoutb p:integer l:"Pub Outlets (other)" t:dataTypeName=number

metric m:gpoutc p:integer l:"Pub Outlets (bookmobile)" t:dataTypeName=number

metric m:gpoutd p:integer l:"Pub Outlets (TOTAL)" t:dataTypeName=number

metric m:bkservol p:integer l:Volumes t:dataTypeName=number

metric m:audio p:integer l:"Audio Materials" t:dataTypeName=number

metric m:video p:integer l:"Video Materials" t:dataTypeName=number

metric m:subscrip p:integer l:"Serial Subs" t:dataTypeName=number

metric m:govdoc p:integer l:"Govt Documents" t:dataTypeName=number

metric m:circ p:integer l:Circulation t:dataTypeName=number

metric m:provto p:integer l:"ILL out" t:dataTypeName=number

metric m:recfrom p:integer l:"ILL in" t:dataTypeName=number

metric m:reftrans p:integer l:"Reference transactions" t:dataTypeName=number

metric m:libvists p:integer l:"Library visits" t:dataTypeName=number

metric m:grantaw p:integer l:"Grants awarded" t:dataTypeName=number

metric m:events p:integer l:"Number of events" t:dataTypeName=number

metric m:atevents p:integer l:"Total attendance" t:dataTypeName=number

metric m:madmin p:float l:"Admin ALA-MLS" t:dataTypeName=number

metric m:nadmin p:float l:"Admin non-MLS" t:dataTypeName=number

metric m:oadmin p:float l:"Admin other" t:dataTypeName=number

metric m:admin p:float l:"Admin TOTAL" t:dataTypeName=number

metric m:mlibdev p:float l:"Dev ALA-MLS" t:dataTypeName=number

metric m:nlibdev p:float l:"Dev non-MLS" t:dataTypeName=number

metric m:olibdev p:float l:"Dev other" t:dataTypeName=number

metric m:libdev p:float l:"Dev TOTAL" t:dataTypeName=number

metric m:mlibserv p:float l:"Services ALA-MLS" t:dataTypeName=number

metric m:nlibserv p:float l:"Services non-MLS" t:dataTypeName=number

metric m:olibserv p:float l:"Services other" t:dataTypeName=number

metric m:libserv p:float l:"Services TOTAL" t:dataTypeName=number

metric m:mothserv p:float l:"Other ALA-MLS" t:dataTypeName=number

metric m:nothserv p:float l:"Other non-MLS" t:dataTypeName=number

metric m:oothserv p:float l:"Other other" t:dataTypeName=number

metric m:othserv p:float l:"Other TOTAL" t:dataTypeName=number

metric m:mtotstaf p:float l:"Total ALA-MLS" t:dataTypeName=number

metric m:ntotstaf p:float l:"Total non-MLS" t:dataTypeName=number

metric m:ototstaf p:float l:"Total other" t:dataTypeName=number

metric m:totstaf p:float l:"TOTAL STAFF" t:dataTypeName=number

metric m:pagiw_lo p:integer l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:integer l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:popu_st p:integer l:Population t:dataTypeName=number

entity e:ega2-r6pd l:"State Libraries Survey, FY 2014, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ega2-r6pd

property e:ega2-r6pd t:meta.view v:id=ega2-r6pd v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2014, Part 1: Operations & Workforce" v:attribution=IMLS

property e:ega2-r6pd t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ega2-r6pd t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:ega2-r6pd t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:ega2-r6pd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                                                  | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                                  | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                             | branch | indagy | appbygov | appbyoth | largerag | othagsp | pla_brco | pla_gov | pld_oth | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                    | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | dig_stla | dig_ag | dig_lib | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | accwbcat | accoth | othaccsp                       | erateapp | fipsst | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol | audio | video | subscrip | govdoc  | circ   | provto | recfrom | reftrans | libvists | grantaw | events | atevents | madmin | nadmin | oadmin | admin | mlibdev | nlibdev | olibdev | libdev | mlibserv | nlibserv | olibserv | libserv | mothserv | nothserv | oothserv | othserv | mtotstaf | ntotstaf | ototstaf | totstaf | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | popu_st  | 
| ========================================================================= | ============================================= | =========== | ======= | ======= | ======== | ========================================= | =========== | ======= | ======= | ======== | =================================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =========================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ====== | ============================== | ======== | ====== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ======== | ===== | ===== | ======== | ======= | ====== | ====== | ======= | ======== | ======== | ======= | ====== | ======== | ====== | ====== | ====== | ===== | ======= | ======= | ======= | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99801   | 1770     | P.O. BOX 110571                           | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.ALASKA.GOV                              | E      | P      | P        | P        | E        | P       | Y        | X       | P       | Y        | N        | Y        | Y        | N        | P                           | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 2      | 8      | 1       | 1372636800 | 1404086400 | 76     | 34       | 1        | 0        | 1       | 1        | 0        | 2        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 113208   | 388   | 1580  | 280      | 622810  | 875    | 725    | 2637    | 40374    | 20505    | 248     | 117    | 1794     | 1.0    | 0.0    | 5.5    | 6.5   | 2.0     | 0.0     | 3.75    | 5.75   | 10.5     | 0.0      | 7.5      | 18.0    | 0.0      | 0.0      | 1.0      | 1.0     | 13.5     | 0.0      | 17.75    | 31.25   | 11       | 0        | 215280   | 138200   | 0        | 353480   | 736732   | 
| ALABAMA PUBLIC LIBRARY SERVICE                                            | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                     | MONTGOMERY  | AL      | 36130   | 6000     | HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | N        | N        | N        | N        | Y        | N        | Y        | Y        | N        | N      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 1      | 5      | 1       | 1380585600 | 1412035200 | 40     | 40       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 0      | 0      | 0      | 0      | 90425    | 0     | 0     | 25       | 0       | 800    | 523    | 1207    | 520      | 260      | 115     | 66     | 3154     | 2.0    | 0.0    | 9.0    | 11.0  | 6.0     | 0.0     | 0.0     | 6.0    | 4.0      | 0.0      | 8.0      | 12.0    | 0.0      | 0.0      | 2.0      | 2.0     | 12.0     | 0.0      | 19.0     | 31.0    | 0        | 0        | 718068   | 269800   | 0        | 987868   | 4849377  | 
| ARKANSAS STATE LIBRARY                                                    | 900 WEST CAPITOL, SUITE 100                   | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100               | LITTLE ROCK | AR      | 72201   | 3108     | WWW.LIBRARY.ARKANSAS.GOV                            | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 5      | 5      | 1       | 1372636800 | 1404086400 | 45     | 45       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 51157    | 124   | 135   | 459      | 0       | 2578   | 1156   | 201     | 2314     | 3267     | 0       | 41     | 594      | 2.0    | 0.0    | 10.0   | 12.0  | 6.0     | 0.0     | 1.0     | 7.0    | 12.0     | 0.0      | 20.5     | 32.5    | 0.0      | 0.0      | 0.0      | 0.0     | 20.0     | 0.0      | 31.5     | 51.5    | 10       | 0        | 801816   | 165000   | 0        | 966816   | 2966369  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS                        | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON, ROOM 200            | PHOENIX     | AZ      | 85007   | 2896     | WWW.AZLIBRARY.GOV                                   | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | Y        | Y        | Y        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | N        | N        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | N        | N        | Y       | Y        | Y        | N        | Y      | OCLC ILL FEES                  | Y        | 4      | 6      | 1       | 1372636800 | 1404086400 | 90     | 45       | 0        | 0        | 1       | 1        | 0        | 2        | 0       | 1       | 0       | 1       | 1       | 1       | 0       | 2       | 0        | 1        | 0        | 1        | 1        | 1        | 0        | 2        | 1      | 1      | 0      | 2      | 494589   | 69497 | 5394  | 1717     | 481231  | 22740  | 747    | 401     | 9357     | 6495     | 72      | 109    | 3468     | 4.0    | 1.0    | 14.75  | 19.75 | 4.0     | 2.0     | 3.0     | 9.0    | 18.0     | 2.0      | 18.75    | 38.75   | 2.0      | 0.0      | 41.0     | 43.0    | 28.0     | 5.0      | 77.5     | 110.5   | 10       | 0        | 445491   | 13626    | 435      | 459552   | 6731484  | 
| CALIFORNIA STATE LIBRARY                                                  | 900 N ST                                      | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                           | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                                  | E      | G      | P        | P        | P        | P       | P        | P       | P       | N        | Y        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | Y        | N      | P                              | N        | 6      | 8      | 2       | 1372636800 | 1404086400 | 140    | 33       | 0        | 0        | 1       | 3        | 0        | 4        | 0       | 1       | 0       | 1       | 1       | 1       | 0       | 2       | 0        | 1        | 0        | 1        | 1        | 3        | 0        | 4        | 1      | 2      | 0      | 3      | 945282   | 1003  | 2356  | 1671     | 4737152 | 6909   | 7754   | 127     | 18270    | 131252   | 97      | 911    | 31363    | 1.0    | 1.0    | 24.0   | 26.0  | 7.0     | 0.0     | 6.0     | 13.0   | 27.0     | 0.0      | 38.0     | 65.0    | 5.0      | 0.0      | 23.0     | 28.0    | 40.0     | 1.0      | 91.0     | 132.0   | 32       | 0        | 0        | 0        | 0        | 0        | 38802500 | 
| COLORADO STATE LIBRARY                                                    | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX AVENUE, ROOM 309          | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/CDELIB/                         | E      | P      | P        | P        | E        | P       | N        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | Y        | 8      | 7      | 1       | 1372636800 | 1404086400 | 90     | 0        | 0        | 0        | 0       | 2        | 0        | 2        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 1        | 0      | 2      | 0      | 2      | 147461   | 5478  | 882   | 26       | 0       | 744403 | 337    | 544     | 22907    | 485      | 349     | 95     | 2199     | 5.5    | 0.5    | 1.85   | 7.85  | 12.0    | 2.0     | 1.5     | 15.5   | 7.0      | 2.0      | 8.0      | 17.0    | 0.0      | 0.0      | 0.0      | 0.0     | 24.5     | 4.5      | 11.35    | 40.35   | 2        | 0        | 0        | 0        | 0        | 0        | 5355866  | 
| CONNECTICUT STATE LIBRARY                                                 | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6160    | 1537     | 231 CAPITOL AVENUE                        | HARTFORD    | CT      | 6106    | 1537     | WWW.CTSTATELIBRARY.ORG                              | E      | B      | X        | X        | P        | P       | P        | P       | P       | Y        | N        | Y        | Y        | N        | P                           | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 9      | 1      | 2       | 1372636800 | 1404086400 | 139    | 37       | 0        | 5        | 1       | 3        | 0        | 4        | 0       | 1       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 1        | 0        | 2        | 1        | 2        | 0        | 3        | 1      | 3      | 0      | 4      | 1509645  | 12233 | 8678  | 8830     | 3156774 | 1027   | 53030  | 143     | 18726    | 41357    | 348     | 136    | 637      | 2.0    | 0.0    | 7.96   | 9.96  | 10.0    | 0.0     | 3.75    | 13.75  | 20.95    | 0.0      | 24.73    | 45.68   | 4.88     | 0.0      | 15.01    | 19.89   | 37.83    | 0.0      | 51.45    | 89.28   | 28       | 0        | 0        | 1553863  | 0        | 1553863  | 3596677  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                                       | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                        | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                                   | E      | B      | P        | X        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | N        | Y        | N        | N        | N        | N        | N        | N      | N       | Y        | N        | N      | Y        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N      | P                              | N        | 11     | 2      | 1       | 1380585600 | 1412035200 | 40     | 0        | 0        | 0        | 0       | 1        | 0        | 1        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0      | 0      | 0      | 0      | 0        | 0     | 0     | 0        | 0       | 0      | 0      | 0       | 0        | 0        | 2       | 0      | 0        | 0.0    | 0.0    | 1.0    | 1.0   | 0.0     | 0.0     | 0.0     | 0.0    | 0.0      | 4.0      | 0.0      | 4.0     | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 4.0      | 1.0      | 5.0     | 0        | 0        | 0        | 0        | 0        | 0        | 658893   | 
| DELAWARE DIVISION OF LIBRARIES                                            | 121 MARTIN LUTHER KING JR. BLVD. NORTH        | DOVER       | DE      | 19901   | 7430     | 121 MARTIN LUTHER KING JR. BLVD. NORTH    | DOVER       | DE      | 19901   | 7430     | LIBRARIES.DELAWARE.GOV                              | E      | P      | P        | P        | S        | P       | Y        | X       | X       | N        | N        | N        | N        | N        | P                           | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | N       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | N       | N        | Y        | Y        | Y      | WEB PAGE ACCESS, STATEWIDE ILS | Y        | 10     | 2      | 1       | 1372636800 | 1404086400 | 42     | 42       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 638      | 9     | 3     | 14       | 0       | 2032   | 0      | 0       | 1464     | 2215     | 0       | 56     | 446      | 1.88   | 0.0    | 1.88   | 3.76  | 1.88    | 1.88    | 0.0     | 3.76   | 3.75     | 0.0      | 0.94     | 4.69    | 0.0      | 0.0      | 1.88     | 1.88    | 7.51     | 1.88     | 4.7      | 14.09   | 0        | 0        | 27352    | 900681   | 0        | 928033   | 935614   | 
| DIVISION OF LIBRARY AND INFORMATION SERVICES                              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | R.A. GRAY BUILDING 500 S. BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | HTTP://INFO.FLORIDA.GOV/                            | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | N        | N        | Y        | Y        | FLORIDA ADMINISTRATIVE CODE | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 12     | 5      | 1       | 1372636800 | 1404086400 | 75     | 38       | 0        | 0        | 1       | 1        | 0        | 2        | 1       | 1       | 0       | 2       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 1        | 1        | 0        | 2        | 1      | 1      | 0      | 2      | 509894   | 72974 | 2337  | 206      | 10096   | 8162   | 2709   | 6590    | 40228    | 11905    | 132     | 478    | 9840     | 1.0    | 0.0    | 4.0    | 5.0   | 9.0     | 0.0     | 7.0     | 16.0   | 9.0      | 2.0      | 2.0      | 13.0    | 0.0      | 0.0      | 31.0     | 31.0    | 19.0     | 2.0      | 44.0     | 65.0    | 9        | 0        | 3066577  | 0        | 0        | 3066577  | 19893297 | 
```