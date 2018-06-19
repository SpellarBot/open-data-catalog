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
series e:2sms-kv74 d:2011-10-01T00:00:00.000Z t:stlacont=N t:schswdbl=Y t:remoteac=Y t:othallop=N t:physaddr="6030 MONTICELLO DRIVE" t:othagsp=P t:branch=E t:mailzip=36117 t:othallsp=P t:obereg=5 t:mailzip4=1907 t:appbygov=X t:dig_ag=N t:netmount=Y t:appbyoth=P t:elecbibl=Y t:dig_stla=N t:accoth=N t:nettrcus=Y t:netgoph=Y t:othaccsp=P t:elecoper=N t:selectiv=N t:lcswdbl=Y t:rstatus=1 t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:strecmng=N t:spcswdbl=Y t:pla_gov=P t:dig_lib=Y t:indagy=B t:phys_st=AL t:mailaddr="6030 MONTICELLO DRIVE" t:pla_brco=P t:regional=N t:electext=Y t:erateapp=N t:nettrstf=Y t:mailcity=MONTGOMERY t:accwbcat=Y t:acswdbl=Y t:starchiv=N t:stdeplib=N t:physzip4=1907 t:elecplan=Y t:fddeplib=N t:physzip=36117 t:largerag=P t:stlegref=N t:fipsst=1 t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:mail_st=AL t:pubswdbl=Y t:stlahost=N t:physcity=MONTGOMERY t:netsub=Y t:othswdbl=Y t:netequip=N t:sthstmus=N t:pld_oth=P m:bphoutc=0 m:bphoutb=0 m:bphouta=1 m:madmin=1 m:olibdev=0 m:otherout=0 m:othserv=4 m:bkservol=64302 m:mon2frce=0 m:otstouta=0 m:otstoutc=0 m:otstoutb=0 m:bkmobile=0 m:otstoutd=0 m:swdblica=830599 m:swdblicb=269800 m:swdblicc=0 m:subscrip=310 m:nadmin=0 m:gpoutb=0 m:gpouta=0 m:gpoutd=0 m:events=75 m:gpoutc=0 m:bphoutd=1 m:atevents=4946 m:mtotstaf=12 m:ototstaf=18 m:tothrsce=40 m:oadmin=7 m:libdev=7 m:coroutd=0 m:reftrans=461 m:corouta=0 m:coroutc=0 m:coroutb=0 m:popu_st=4822023 m:circ=902 m:mothserv=0 m:recfrom=187 m:provto=1025 m:oothserv=4 m:nlibserv=0 m:mlibserv=4 m:olibserv=7 m:admin=8 m:totstaf=30 m:video=0 m:mlibdev=7 m:audio=0 m:pagiw_lo=0 m:totalout=1 m:libvists=525 m:paiw_oth=0 m:grantaw=108 m:ntotstaf=0 m:swdblicd=1100399 m:satsunce=0 m:gvemoutc=0 m:gvemoutd=1 m:gvemouta=1 m:gvemoutb=0 m:nlibdev=0 m:libserv=11 m:tothrs=40 m:govdoc=0 m:mainout=1 m:nothserv=0

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:stlacont=Y t:schswdbl=Y t:remoteac=Y t:othallop=N t:physaddr="333 WILLOUGHBY AVENUE" t:othagsp=P t:branch=E t:mailzip=99811 t:othallsp=P t:obereg=8 t:mailzip4=571 t:appbygov=P t:dig_ag=N t:netmount=Y t:appbyoth=P t:elecbibl=Y t:dig_stla=Y t:accoth=N t:nettrcus=Y t:netgoph=Y t:othaccsp=P t:elecoper=Y t:selectiv=Y t:lcswdbl=Y t:rstatus=1 t:webaddr=WWW.LIBRARY.STATE.AK.US t:strecmng=Y t:spcswdbl=Y t:pla_gov=X t:dig_lib=Y t:indagy=P t:phys_st=AK t:mailaddr="P.O. BOX 110571" t:pla_brco=Y t:regional=N t:electext=Y t:erateapp=N t:nettrstf=Y t:mailcity=JUNEAU t:accwbcat=Y t:acswdbl=Y t:starchiv=Y t:stdeplib=Y t:physzip4=1770 t:elecplan=Y t:fddeplib=Y t:physzip=99801 t:largerag=E t:stlegref=N t:fipsst=2 t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:mail_st=AK t:pubswdbl=Y t:stlahost=N t:physcity=JUNEAU t:netsub=Y t:othswdbl=Y t:netequip=Y t:sthstmus=Y t:pld_oth=P m:bphoutc=0 m:bphoutb=1 m:bphouta=0 m:madmin=1 m:olibdev=5.5 m:otherout=1 m:othserv=1 m:bkservol=136582 m:mon2frce=2 m:otstouta=0 m:otstoutc=0 m:otstoutb=0 m:bkmobile=0 m:otstoutd=0 m:swdblica=165340 m:swdblicb=0 m:swdblicc=0 m:subscrip=1446 m:nadmin=0 m:gpoutb=0 m:gpouta=1 m:gpoutd=1 m:events=80 m:gpoutc=0 m:bphoutd=1 m:atevents=1067 m:mtotstaf=15 m:ototstaf=20.5 m:tothrsce=41 m:oadmin=3 m:libdev=9.5 m:coroutd=0 m:reftrans=36159 m:corouta=0 m:coroutc=0 m:coroutb=0 m:popu_st=731449 m:circ=1377 m:mothserv=1 m:recfrom=1359 m:provto=648 m:oothserv=0 m:nlibserv=0 m:mlibserv=9 m:olibserv=12 m:admin=4 m:totstaf=35.5 m:video=1510 m:mlibdev=4 m:audio=456 m:pagiw_lo=8 m:totalout=2 m:libvists=27498 m:paiw_oth=0 m:grantaw=203 m:ntotstaf=0 m:swdblicd=165340 m:satsunce=0 m:gvemoutc=0 m:gvemoutd=1 m:gvemouta=1 m:gvemoutb=0 m:nlibdev=0 m:libserv=21 m:tothrs=85 m:govdoc=622811 m:mainout=1 m:nothserv=0

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:stlacont=N t:schswdbl=Y t:remoteac=Y t:othallop=N t:physaddr="1700 WEST WASHINGTON - SUITE 200" t:othagsp=P t:branch=E t:mailzip=85007 t:othallsp=P t:obereg=6 t:mailzip4=2896 t:appbygov=P t:dig_ag=Y t:netmount=Y t:appbyoth=P t:elecbibl=Y t:dig_stla=Y t:accoth=N t:nettrcus=Y t:netgoph=Y t:othaccsp=P t:elecoper=Y t:selectiv=N t:lcswdbl=Y t:rstatus=1 t:webaddr=WWW.AZLIBRARY.GOV t:strecmng=Y t:spcswdbl=Y t:pla_gov=P t:dig_lib=Y t:indagy=P t:phys_st=AZ t:mailaddr="1700 WEST WASHINGTON, ROOM 200" t:pla_brco=Y t:regional=Y t:electext=Y t:erateapp=Y t:nettrstf=Y t:mailcity=PHOENIX t:accwbcat=Y t:acswdbl=N t:starchiv=Y t:stdeplib=Y t:physzip4=2896 t:elecplan=Y t:fddeplib=Y t:physzip=85007 t:largerag=S t:stlegref=Y t:fipsst=4 t:stlaname="ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS" t:mail_st=AZ t:pubswdbl=Y t:stlahost=Y t:physcity=PHOENIX t:netsub=Y t:othswdbl=Y t:netequip=Y t:sthstmus=Y t:pld_oth=X m:bphoutc=0 m:bphoutb=1 m:bphouta=0 m:madmin=4 m:olibdev=7 m:otherout=1 m:othserv=42.25 m:bkservol=730845 m:mon2frce=0 m:otstouta=1 m:otstoutc=0 m:otstoutb=1 m:bkmobile=0 m:otstoutd=2 m:swdblica=837376 m:swdblicb=767 m:swdblicc=12087 m:subscrip=1920 m:nadmin=0 m:gpoutb=1 m:gpouta=1 m:gpoutd=2 m:events=82 m:gpoutc=0 m:bphoutd=1 m:atevents=2538 m:mtotstaf=27 m:ototstaf=90.75 m:tothrsce=45 m:oadmin=17.5 m:libdev=12 m:coroutd=2 m:reftrans=8675 m:corouta=1 m:coroutc=0 m:coroutb=1 m:popu_st=6553255 m:circ=25279 m:mothserv=3 m:recfrom=638 m:provto=1827 m:oothserv=39.25 m:nlibserv=2 m:mlibserv=16 m:olibserv=27 m:admin=21.5 m:totstaf=120.75 m:video=4210 m:mlibdev=4 m:audio=57726 m:pagiw_lo=10 m:totalout=2 m:libvists=7053 m:paiw_oth=0 m:grantaw=60 m:ntotstaf=3 m:swdblicd=850230 m:satsunce=0 m:gvemoutc=0 m:gvemoutd=2 m:gvemouta=1 m:gvemoutb=1 m:nlibdev=1 m:libserv=45 m:tothrs=90 m:govdoc=482302 m:mainout=1 m:nothserv=0
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

property e:2sms-kv74 t:meta.view d:2017-09-25T07:31:32.671Z v:averageRating=0 v:name="State Libraries Survey, FY 2012, Part 1: Operations & Workforce" v:attribution=IMLS v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:id=2sms-kv74 v:category="State Library Administrative Agencies Survey"

property e:2sms-kv74 t:meta.view.license d:2017-09-25T07:31:32.671Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:2sms-kv74 t:meta.view.owner d:2017-09-25T07:31:32.671Z v:displayName="Jason Enos" v:lastNotificationSeenAt=1504290350 v:id=xhhh-dddv v:screenName="Jason Enos"

property e:2sms-kv74 t:meta.view.tableauthor d:2017-09-25T07:31:32.671Z v:displayName="Jason Enos" v:lastNotificationSeenAt=1504290350 v:roleName=administrator v:id=xhhh-dddv v:screenName="Jason Enos"

property e:2sms-kv74 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:31:32.671Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Program_Code=000:000 v:Bureau_Code=474:00
```

## Top Records

```ls
| stlaname                                                                  | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                                  | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                             | branch | indagy | appbygov | appbyoth | largerag | othagsp | pla_brco | pla_gov | pld_oth | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                    | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | dig_stla | dig_ag | dig_lib | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | accwbcat | accoth | othaccsp                       | erateapp | fipsst | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol | audio | video | subscrip | govdoc  | circ  | provto | recfrom | reftrans | libvists | grantaw | events | atevents | madmin | nadmin | oadmin | admin | mlibdev | nlibdev | olibdev | libdev | mlibserv | nlibserv | olibserv | libserv | mothserv | nothserv | oothserv | othserv | mtotstaf | ntotstaf | ototstaf | totstaf | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | popu_st  | 
| ========================================================================= | ============================================= | =========== | ======= | ======= | ======== | ========================================= | =========== | ======= | ======= | ======== | =================================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =========================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ====== | ============================== | ======== | ====== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ======== | ===== | ===== | ======== | ======= | ===== | ====== | ======= | ======== | ======== | ======= | ====== | ======== | ====== | ====== | ====== | ===== | ======= | ======= | ======= | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| ALABAMA PUBLIC LIBRARY SERVICE                                            | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1907     | 6030 MONTICELLO DRIVE                     | MONTGOMERY  | AL      | 36117   | 1907     | HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | N        | N        | N        | N        | Y        | N        | Y        | Y        | N        | N      | Y       | Y        | Y        | Y      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 1      | 5      | 1       | 1317427200 | 1348963200 | 40     | 40       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 0      | 0      | 0      | 0      | 64302    | 0     | 0     | 310      | 0       | 902   | 1025   | 187     | 461      | 525      | 108     | 75     | 4946     | 1.0    | 0.0    | 7.0    | 8.0   | 7.0     | 0.0     | 0.0     | 7.0    | 4.0      | 0.0      | 7.0      | 11.0    | 0.0      | 0        | 4.0      | 4.0     | 12.0     | 0.0      | 18.0     | 30.0    | 0        | 0        | 830599   | 269800   | 0        | 1100399  | 4822023  | 
| ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99801   | 1770     | P.O. BOX 110571                           | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                             | E      | P      | P        | P        | E        | P       | Y        | X       | P       | Y        | N        | Y        | Y        | N        | P                           | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 2      | 8      | 1       | 1309478400 | 1341014400 | 85     | 41       | 2        | 0        | 1       | 1        | 0        | 2        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 136582   | 456   | 1510  | 1446     | 622811  | 1377  | 648    | 1359    | 36159    | 27498    | 203     | 80     | 1067     | 1.0    | 0.0    | 3.0    | 4.0   | 4.0     | 0.0     | 5.5     | 9.5    | 9.0      | 0.0      | 12.0     | 21.0    | 1.0      | 0        | 0.0      | 1.0     | 15.0     | 0.0      | 20.5     | 35.5    | 8        | 0        | 165340   | 0        | 0        | 165340   | 731449   | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS                        | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON, ROOM 200            | PHOENIX     | AZ      | 85007   | 2896     | WWW.AZLIBRARY.GOV                                   | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | Y        | Y        | Y        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | N       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | Y        | 4      | 6      | 1       | 1309478400 | 1341014400 | 90     | 45       | 0        | 0        | 1       | 1        | 0        | 2        | 0       | 1       | 0       | 1       | 1       | 1       | 0       | 2       | 1        | 1        | 0        | 2        | 1        | 1        | 0        | 2        | 1      | 1      | 0      | 2      | 730845   | 57726 | 4210  | 1920     | 482302  | 25279 | 1827   | 638     | 8675     | 7053     | 60      | 82     | 2538     | 4.0    | 0.0    | 17.5   | 21.5  | 4.0     | 1.0     | 7.0     | 12.0   | 16.0     | 2.0      | 27.0     | 45.0    | 3.0      | 0        | 39.25    | 42.25   | 27.0     | 3.0      | 90.75    | 120.75  | 10       | 0        | 837376   | 767      | 12087    | 850230   | 6553255  | 
| ARKANSAS STATE LIBRARY                                                    | 900 WEST CAPITOL, SUITE 100                   | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100               | LITTLE ROCK | AR      | 72201   | 3108     | WWW.LIBRARY.ARKANSAS.GOV                            | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | N        | N      | N       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 5      | 5      | 1       | 1309478400 | 1341014400 | 45     | 45       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 56289    | 137   | 143   | 503      | 0       | 2800  | 1119   | 209     | 2273     | 3134     | 0       | 37     | 569      | 2.0    | 0.0    | 10.0   | 12.0  | 6.0     | 0.0     | 1.0     | 7.0    | 12.0     | 0.0      | 20.5     | 32.5    | 0.0      | 0        | 0.0      | 0.0     | 20.0     | 0.0      | 31.5     | 51.5    | 10       | 0        | 798328   | 164000   | 0        | 962328   | 2949131  | 
| CALIFORNIA STATE LIBRARY                                                  | 900 N ST                                      | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                           | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                                  | E      | G      | P        | P        | P        | P       | P        | P       | P       | N        | Y        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | N       | N        | N        | N       | Y        | Y        | Y        | N      | P                              | N        | 6      | 8      | 2       | 1309478400 | 1341014400 | 108    | 33       | 0        | 0        | 1       | 2        | 0        | 3        | 1       | 0       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 1        | 2        | 0        | 3        | 1      | 1      | 0      | 2      | 917815   | 973   | 2306  | 2097     | 4720339 | 19824 | 9492   | 371     | 17249    | 70125    | 198     | 508    | 30348    | 2.0    | 0.0    | 26.0   | 28.0  | 5.0     | 0.0     | 7.0     | 12.0   | 30.0     | 0.0      | 34.0     | 64.0    | 5.0      | 0        | 25.0     | 30.0    | 42.0     | 0.0      | 92.0     | 134.0   | 31       | 0        | 26250    | 0        | 0        | 26250    | 38041430 | 
| COLORADO STATE LIBRARY                                                    | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX AVENUE, ROOM 309          | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/CDELIB/                         | E      | P      | P        | P        | E        | P       | N        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | Y        | 8      | 7      | 1       | 1309478400 | 1341014400 | 90     | 0        | 0        | 0        | 0       | 2        | 0        | 2        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 1        | 0      | 2      | 0      | 2      | 113735   | 6604  | 866   | 36       | 0       | 565   | 290    | 351     | 173      | 1979     | 104     | 161    | 3174     | 4.35   | 1.0    | 1.35   | 6.7   | 14.4    | 0.0     | 1.25    | 15.65  | 4.0      | 6.0      | 7.0      | 17.0    | 0.0      | 0        | 0.0      | 0.0     | 22.75    | 7.0      | 9.6      | 39.35   | 2        | 0        | 75000    | 0        | 0        | 75000    | 5187582  | 
| CONNECTICUT STATE LIBRARY                                                 | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                        | HARTFORD    | CT      | 6106    | 1537     | WWW.CTSTATELIBRARY.ORG                              | E      | B      | X        | X        | P        | P       | P        | P       | P       | Y        | N        | Y        | Y        | N        | P                           | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | Y        | 9      | 1      | 1       | 1309478400 | 1341014400 | 139    | 37       | 0        | 5        | 1       | 3        | 0        | 4        | 0       | 1       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 1        | 0        | 2        | 1        | 2        | 0        | 3        | 1      | 3      | 0      | 4      | 1456941  | 19180 | 7416  | 5552     | 2282281 | 811   | 64677  | 236     | 20428    | 42255    | 347     | 121    | 834      | 2.0    | 0.0    | 7.96   | 9.96  | 10.0    | 0.0     | 3.75    | 13.75  | 19.95    | 0.0      | 25.11    | 45.06   | 4.88     | 0        | 14.96    | 19.84   | 36.83    | 0.0      | 51.78    | 88.61   | 17       | 0        | 0        | 1592130  | 0        | 1592130  | 3590347  | 
| DELAWARE DIVISION OF LIBRARIES                                            | 121 MARTIN LUTHER KING JR. BLVD. NORTH        | DOVER       | DE      | 19901   | 7430     | 121 MARTIN LUTHER KING JR. BLVD. NORTH    | DOVER       | DE      | 19901   | 7430     | LIBRARIES.DELAWARE.GOV                              | E      | P      | P        | P        | S        | P       | Y        | X       | X       | N        | N        | N        | N        | N        | P                           | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | N       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | N       | N        | Y        | Y        | Y      | WEB PAGE ACCESS; STATEWIDE ILS | Y        | 10     | 2      | 1       | 1309478400 | 1341014400 | 42     | 42       | 0        | 0        | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 1016     | 2645  | 3     | 14       | 0       | 1305  | 0      | 0       | 1608     | 1500     | 11      | 20     | 906      | 2.0    | 0.0    | 1.0    | 3.0   | 4.0     | 2.0     | 0.0     | 6.0    | 1.0      | 1.0      | 1.0      | 3.0     | 0.0      | 0        | 2.0      | 2.0     | 7.0      | 3.0      | 4.0      | 14.0    | 0        | 0        | 35333    | 350000   | 0        | 385333   | 917092   | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                                       | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                        | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                                   | E      | B      | P        | X        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | N        | N        | Y        | Y        | Y        | Y        | Y        | N      | N       | N        | N        | N      | Y        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N      | P                              | N        | 11     | 2      | 1       | 1317427200 | 1348963200 | 40     | 0        | 0        | 0        | 0       | 1        | 0        | 1        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0      | 0      | 0      | 0      | 0        | 0     | 0     | 0        | 0       | 0     | 0      | 0       | 0        | 0        | 2       | 0      | 0        | 0.0    | 0.0    | 1.0    | 1.0   | 0.0     | 0.0     | 0.0     | 0.0    | 0.0      | 5.0      | 0.0      | 5.0     | 0.0      | 0        | 0.0      | 0.0     | 0.0      | 5.0      | 1.0      | 6.0     | 0        | 0        | 0        | 0        | 0        | 0        | 632323   | 
| DIVISION OF LIBRARY AND INFORMATION SERVICES                              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | R.A. GRAY BUILDING 500 S. BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | HTTP://INFO.FLORIDA.GOV/                            | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | N        | N        | Y        | Y        | FLORIDA ADMINISTRATIVE CODE | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                              | N        | 12     | 5      | 1       | 1309478400 | 1341014400 | 75     | 38       | 0        | 0        | 1       | 2        | 0        | 3        | 1       | 1       | 0       | 2       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 1        | 1        | 0        | 2        | 1      | 1      | 0      | 2      | 449939   | 70772 | 2217  | 336      | 24950   | 9750  | 3843   | 3099    | 32513    | 16391    | 134     | 4106   | 7269     | 1.0    | 0.0    | 3.0    | 4.0   | 8.0     | 0.0     | 8.0     | 16.0   | 9.0      | 2.0      | 2.0      | 13.0    | 5.0      | 0        | 35.0     | 40.0    | 23.0     | 2.0      | 48.0     | 73.0    | 10       | 0        | 3123211  | 0        | 0        | 3123211  | 19317568 | 
```