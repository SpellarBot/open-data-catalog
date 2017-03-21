# State Libraries Survey, FY 2012, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2012-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/2sms-kv74) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/2sms-kv74/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/2sms-kv74/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 2sms-kv74 |
| Name | State Libraries Survey, FY 2012, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2012, operations, workforce |
| Created | 2016-12-20T15:32:51Z |
| Publication Date | 2016-12-20T17:04:42Z |
| Rows Updated | 2016-12-20T17:24:25Z |

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
series e:2sms-kv74 d:2011-10-01T00:00:00.000Z t:appbygov=X t:physaddr="6030 MONTICELLO DRIVE" t:stlacont=N t:mailzip=36117 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1907 t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=AL t:obereg=5 t:elecbibl=Y t:phys_st=AL t:pla_gov=P t:netsub=Y t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=1 t:schswdbl=Y t:nettrstf=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:elecoper=N t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=36117 t:dig_stla=N t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=1907 t:othaccsp=P t:netequip=N t:pla_brco=P t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=Y m:libserv=11 m:mainout=1 m:bkservol=64302 m:ototstaf=18 m:govdoc=0 m:othserv=4 m:ntotstaf=0 m:libvists=525 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=0 m:oadmin=7 m:video=0 m:otstoutd=0 m:otstoutc=0 m:atevents=4946 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:totstaf=30 m:grantaw=108 m:swdblicd=1100399 m:tothrsce=40 m:coroutd=0 m:swdblicb=269800 m:coroutb=0 m:oothserv=4 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=75 m:olibdev=0 m:corouta=0 m:swdblica=830599 m:madmin=1 m:gvemoutd=1 m:recfrom=187 m:gvemoutc=0 m:olibserv=7 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=1 m:bphoutb=0 m:bphouta=1 m:provto=1025 m:popu_st=4822023 m:bphoutd=1 m:mlibdev=7 m:subscrip=310 m:paiw_oth=0 m:reftrans=461 m:audio=0 m:gpouta=0 m:pagiw_lo=0 m:mlibserv=4 m:gpoutb=0 m:gpoutc=0 m:gpoutd=0 m:totalout=1 m:circ=902 m:admin=8 m:libdev=7 m:tothrs=40 m:mtotstaf=12

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:appbygov=P t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=1770 t:webaddr=WWW.LIBRARY.STATE.AK.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:obereg=8 t:elecbibl=Y t:phys_st=AK t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=Y t:pld_oth=P t:strecmng=Y t:accoth=N t:largerag=E t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=2 t:schswdbl=Y t:nettrstf=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=99801 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=571 t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:libserv=21 m:mainout=1 m:bkservol=136582 m:ototstaf=20.5 m:govdoc=622811 m:othserv=1 m:ntotstaf=0 m:libvists=27498 m:nadmin=0 m:mothserv=1 m:bkmobile=0 m:nlibdev=0 m:mon2frce=2 m:nlibserv=0 m:oadmin=3 m:video=1510 m:otstoutd=0 m:otstoutc=0 m:atevents=1067 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=1 m:totstaf=35.5 m:grantaw=203 m:swdblicd=165340 m:tothrsce=41 m:coroutd=0 m:swdblicb=0 m:coroutb=0 m:oothserv=0 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=80 m:olibdev=5.5 m:corouta=0 m:swdblica=165340 m:madmin=1 m:gvemoutd=1 m:recfrom=1359 m:gvemoutc=0 m:olibserv=12 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=1 m:bphoutb=1 m:bphouta=0 m:provto=648 m:popu_st=731449 m:bphoutd=1 m:mlibdev=4 m:subscrip=1446 m:paiw_oth=0 m:reftrans=36159 m:audio=456 m:gpouta=1 m:pagiw_lo=8 m:mlibserv=9 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=2 m:circ=1377 m:admin=4 m:libdev=9.5 m:tothrs=85 m:mtotstaf=15

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:appbygov=P t:physaddr="1700 WEST WASHINGTON - SUITE 200" t:stlacont=N t:mailzip=85007 t:netmount=Y t:mailaddr="1700 WEST WASHINGTON, ROOM 200" t:stlaname="ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS" t:physzip4=2896 t:webaddr=WWW.AZLIBRARY.GOV t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AZ t:obereg=6 t:elecbibl=Y t:phys_st=AZ t:pla_gov=P t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=Y t:starchiv=Y t:pld_oth=X t:strecmng=Y t:accoth=N t:largerag=S t:dig_lib=Y t:branch=E t:erateapp=Y t:pubswdbl=Y t:fipsst=4 t:schswdbl=Y t:nettrstf=Y t:physcity=PHOENIX t:mailcity=PHOENIX t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=85007 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=2896 t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:stlegref=Y t:selectiv=N t:indagy=P t:acswdbl=N m:libserv=45 m:mainout=1 m:bkservol=730845 m:ototstaf=90.75 m:govdoc=482302 m:othserv=42.25 m:ntotstaf=3 m:libvists=7053 m:nadmin=0 m:mothserv=3 m:bkmobile=0 m:nlibdev=1 m:mon2frce=0 m:nlibserv=2 m:oadmin=17.5 m:video=4210 m:otstoutd=2 m:otstoutc=0 m:atevents=2538 m:otstoutb=1 m:otstouta=1 m:satsunce=0 m:otherout=1 m:totstaf=120.75 m:grantaw=60 m:swdblicd=850230 m:tothrsce=45 m:coroutd=2 m:swdblicb=767 m:coroutb=1 m:oothserv=39.25 m:nothserv=0 m:swdblicc=12087 m:coroutc=0 m:events=82 m:olibdev=7 m:corouta=1 m:swdblica=837376 m:madmin=4 m:gvemoutd=2 m:recfrom=638 m:gvemoutc=0 m:olibserv=27 m:gvemoutb=1 m:bphoutc=0 m:gvemouta=1 m:bphoutb=1 m:bphouta=0 m:provto=1827 m:popu_st=6553255 m:bphoutd=1 m:mlibdev=4 m:subscrip=1920 m:paiw_oth=0 m:reftrans=8675 m:audio=57726 m:gpouta=1 m:pagiw_lo=10 m:mlibserv=16 m:gpoutb=1 m:gpoutc=0 m:gpoutd=2 m:totalout=2 m:circ=25279 m:admin=21.5 m:libdev=12 m:tothrs=90 m:mtotstaf=27
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

metric m:nothserv p:integer l:"Other non-MLS" t:dataTypeName=number

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

entity e:2sms-kv74 l:"State Libraries Survey, FY 2012, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/2sms-kv74

property e:2sms-kv74 t:meta.view v:id=2sms-kv74 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2012, Part 1: Operations & Workforce" v:attribution=IMLS

property e:2sms-kv74 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:2sms-kv74 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:2sms-kv74 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:2sms-kv74 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```