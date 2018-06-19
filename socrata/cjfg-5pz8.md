# State Libraries Survey, FY 2010, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2010-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/cjfg-5pz8) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/cjfg-5pz8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/cjfg-5pz8/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | cjfg-5pz8 |
| Name | State Libraries Survey, FY 2010, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2010, operations, workforce |
| Created | 2016-12-20T15:31:20Z |
| Publication Date | 2016-12-20T17:04:41Z |

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
series e:cjfg-5pz8 d:2009-07-01T00:00:00.000Z t:appbygov=P t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:webaddr=WWW.LIBRARY.STATE.AK.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:obereg=2 t:elecbibl=Y t:phys_st=AK t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=Y t:starchiv=Y t:pld_oth=P t:strecmng=Y t:accoth=N t:largerag=E t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=2 t:schswdbl=Y t:nettrstf=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=99811 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=571 t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=N t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:libserv=15 m:mainout=1 m:bkservol=216100 m:ototstaf=12 m:govdoc=4955 m:othserv=0 m:ntotstaf=0 m:libvists=103797 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=0 m:oadmin=3 m:video=1156 m:otstoutd=2 m:otstoutc=0 m:atevents=3141 m:otstoutb=1 m:otstouta=1 m:satsunce=0 m:otherout=1 m:totstaf=27.5 m:grantaw=481 m:swdblicd=2917486 m:tothrsce=42 m:coroutd=2 m:swdblicb=0 m:coroutb=1 m:oothserv=0 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=187 m:olibdev=2 m:corouta=1 m:swdblica=2917486 m:madmin=1 m:gvemoutd=2 m:recfrom=934 m:gvemoutc=0 m:olibserv=7 m:gvemoutb=1 m:bphoutc=0 m:gvemouta=1 m:bphoutb=1 m:bphouta=1 m:provto=2392 m:popu_st=19378102 m:bphoutd=2 m:mlibdev=6.5 m:subscrip=119 m:paiw_oth=1 m:reftrans=21432 m:audio=0 m:gpouta=1 m:pagiw_lo=50 m:mlibserv=8 m:gpoutb=1 m:gpoutc=0 m:gpoutd=2 m:totalout=2 m:circ=1693 m:admin=4 m:libdev=8.5 m:tothrs=85 m:mtotstaf=15.5

series e:cjfg-5pz8 d:2009-10-01T00:00:00.000Z t:appbygov=X t:physaddr="6030 MONTICELLO DRIVE" t:stlacont=N t:mailzip=36130 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=AL t:obereg=3 t:elecbibl=Y t:phys_st=AL t:pla_gov=P t:netsub=Y t:fddeplib=N t:othallsp=P t:dig_ag=Y t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=Y t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=Y t:pubswdbl=Y t:fipsst=1 t:schswdbl=Y t:nettrstf=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=2 t:physzip=36117 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=1 t:othaccsp="USE FRETWELL/DOWNING SOFTWARE TO SEARCH DISPERATE LIB CAT. TO SHARE MATERIAL" t:netequip=Y t:pla_brco=P t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=Y m:libserv=0 m:mainout=1 m:bkservol=0 m:ototstaf=29.5 m:govdoc=0 m:othserv=4 m:ntotstaf=1 m:libvists=0 m:nadmin=0 m:mothserv=0 m:bkmobile=0 m:nlibdev=1 m:mon2frce=0 m:nlibserv=0 m:oadmin=3.75 m:video=0 m:otstoutd=0 m:otstoutc=0 m:atevents=1695 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:totstaf=41.5 m:grantaw=18 m:swdblicd=3435886 m:tothrsce=0 m:coroutd=0 m:swdblicb=1042582 m:coroutb=0 m:oothserv=4 m:nothserv=0 m:swdblicc=500000 m:coroutc=0 m:events=608 m:olibdev=21.75 m:corouta=0 m:swdblica=1893304 m:madmin=2 m:gvemoutd=0 m:recfrom=0 m:gvemoutc=0 m:olibserv=0 m:gvemoutb=0 m:bphoutc=0 m:gvemouta=0 m:bphoutb=0 m:bphouta=1 m:provto=0 m:popu_st=11536504 m:bphoutd=1 m:mlibdev=9 m:subscrip=0 m:paiw_oth=0 m:reftrans=0 m:audio=0 m:gpouta=0 m:pagiw_lo=23 m:mlibserv=0 m:gpoutb=0 m:gpoutc=0 m:gpoutd=0 m:totalout=1 m:circ=0 m:admin=5.75 m:libdev=31.75 m:tothrs=40 m:mtotstaf=11

series e:cjfg-5pz8 d:2009-07-01T00:00:00.000Z t:appbygov=P t:physaddr="900 WEST CAPITOL, SUITE 100" t:stlacont=N t:mailzip=72201 t:netmount=Y t:mailaddr="900 WEST CAPITOL, SUITE 100" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=3108 t:webaddr=WWW.library.arkansas.gov t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=N t:mail_st=AR t:obereg=6 t:elecbibl=Y t:phys_st=AR t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=E t:dig_lib=N t:branch=E t:erateapp=N t:pubswdbl=Y t:fipsst=5 t:schswdbl=Y t:nettrstf=Y t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=72201 t:dig_stla=Y t:electext=Y t:lcswdbl=N t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=3108 t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=N t:regional=Y t:stlegref=N t:selectiv=N t:indagy=P t:acswdbl=Y m:libserv=25.75 m:mainout=1 m:bkservol=760000 m:ototstaf=51.5 m:govdoc=3400000 m:othserv=27.75 m:ntotstaf=1 m:libvists=19894 m:nadmin=0 m:mothserv=7 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=1 m:oadmin=7 m:video=1000 m:otstoutd=0 m:otstoutc=0 m:atevents=3212 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=2 m:totstaf=82.5 m:grantaw=1693 m:swdblicd=1035219 m:tothrsce=42 m:coroutd=0 m:swdblicb=0 m:coroutb=0 m:oothserv=20.75 m:nothserv=0 m:swdblicc=0 m:coroutc=0 m:events=53 m:olibdev=11 m:corouta=0 m:swdblica=1035219 m:madmin=2 m:gvemoutd=2 m:recfrom=737 m:gvemoutc=0 m:olibserv=12.75 m:gvemoutb=1 m:bphoutc=0 m:gvemouta=1 m:bphoutb=1 m:bphouta=0 m:provto=4596 m:popu_st=3751351 m:bphoutd=1 m:mlibdev=9 m:subscrip=1020 m:paiw_oth=0 m:reftrans=11466 m:audio=310 m:gpouta=1 m:pagiw_lo=32 m:mlibserv=12 m:gpoutb=1 m:gpoutc=0 m:gpoutd=2 m:totalout=3 m:circ=12809 m:admin=9 m:libdev=20 m:tothrs=127 m:mtotstaf=30
```

## Meta Commands

```ls
metric m:tothrs p:float l:"Hours open typical week" t:dataTypeName=number

metric m:tothrsce p:float l:"Hours open main outlet" t:dataTypeName=number

metric m:mon2frce p:float l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:satsunce p:integer l:"Hours open Sat & Sun" t:dataTypeName=number

metric m:mainout p:float l:"Outlets (main)" t:dataTypeName=number

metric m:otherout p:float l:"Outlets (other)" t:dataTypeName=number

metric m:bkmobile p:float l:"Outlets (bookmobile)" t:dataTypeName=number

metric m:totalout p:float l:"Outlets (TOTAL)" t:dataTypeName=number

metric m:bphouta p:float l:"BPH Outlets (main)" t:dataTypeName=number

metric m:bphoutb p:float l:"BPH Outlets (other)" t:dataTypeName=number

metric m:bphoutc p:float l:"BPH Outlets (bookmobile)" t:dataTypeName=number

metric m:bphoutd p:float l:"BPH Outlets (TOTAL)" t:dataTypeName=number

metric m:corouta p:float l:"Corr Outlets (main)" t:dataTypeName=number

metric m:coroutb p:float l:"Corr Outlets (other)" t:dataTypeName=number

metric m:coroutc p:float l:"Corr Outlets (bookmobile)" t:dataTypeName=number

metric m:coroutd p:float l:"Corr Outlets (TOTAL)" t:dataTypeName=number

metric m:otstouta p:float l:"Inst Outlets (main)" t:dataTypeName=number

metric m:otstoutb p:float l:"Inst Outlets (other)" t:dataTypeName=number

metric m:otstoutc p:float l:"Inst Outlets (bookmobile)" t:dataTypeName=number

metric m:otstoutd p:float l:"Inst Outlets (TOTAL)" t:dataTypeName=number

metric m:gvemouta p:float l:"Govt Outlets (main)" t:dataTypeName=number

metric m:gvemoutb p:float l:"Govt Outlets (other)" t:dataTypeName=number

metric m:gvemoutc p:float l:"Govt Outlets (bookmobile)" t:dataTypeName=number

metric m:gvemoutd p:float l:"Govt Outlets (TOTAL)" t:dataTypeName=number

metric m:gpouta p:float l:"Pub Outlets (main)" t:dataTypeName=number

metric m:gpoutb p:float l:"Pub Outlets (other)" t:dataTypeName=number

metric m:gpoutc p:float l:"Pub Outlets (bookmobile)" t:dataTypeName=number

metric m:gpoutd p:float l:"Pub Outlets (TOTAL)" t:dataTypeName=number

metric m:bkservol p:float l:Volumes t:dataTypeName=number

metric m:audio p:float l:"Audio Materials" t:dataTypeName=number

metric m:video p:float l:"Video Materials" t:dataTypeName=number

metric m:subscrip p:float l:"Serial Subs" t:dataTypeName=number

metric m:govdoc p:float l:"Govt Documents" t:dataTypeName=number

metric m:circ p:float l:Circulation t:dataTypeName=number

metric m:provto p:float l:"ILL out" t:dataTypeName=number

metric m:recfrom p:float l:"ILL in" t:dataTypeName=number

metric m:reftrans p:float l:"Reference transactions" t:dataTypeName=number

metric m:libvists p:float l:"Library visits" t:dataTypeName=number

metric m:grantaw p:float l:"Grants awarded" t:dataTypeName=number

metric m:events p:float l:"Number of events" t:dataTypeName=number

metric m:atevents p:float l:"Total attendance" t:dataTypeName=number

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

metric m:pagiw_lo p:float l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:float l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:float l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:float l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:float l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:float l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:popu_st p:float l:Population t:dataTypeName=number

entity e:cjfg-5pz8 l:"State Libraries Survey, FY 2010, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/cjfg-5pz8

property e:cjfg-5pz8 t:meta.view v:id=cjfg-5pz8 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2010, Part 1: Operations & Workforce" v:attribution=IMLS

property e:cjfg-5pz8 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:cjfg-5pz8 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:cjfg-5pz8 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:cjfg-5pz8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                     | branch | indagy | appbygov | appbyoth | largerag | othagsp | pla_brco | pla_gov | pld_oth | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                    | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | dig_stla | dig_ag | dig_lib | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | accwbcat | accoth | othaccsp                                                                     | erateapp | fipsst | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio   | video   | subscrip | govdoc    | circ     | provto  | recfrom | reftrans | libvists | grantaw | events | atevents | madmin | nadmin | oadmin | admin | mlibdev | nlibdev | olibdev | libdev | mlibserv | nlibserv | olibserv | libserv | mothserv | nothserv | oothserv | othserv | mtotstaf | ntotstaf | ototstaf | totstaf | pagiw_lo | paiw_oth | swdblica  | swdblicb  | swdblicc  | swdblicd  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | =========================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =========================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ====== | ============================================================================ | ======== | ====== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======= | ======= | ======== | ========= | ======== | ======= | ======= | ======== | ======== | ======= | ====== | ======== | ====== | ====== | ====== | ===== | ======= | ======= | ======= | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ========= | ========= | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                     | E      | P      | P        | P        | E        | P       | Y        | X       | P       | Y        | N        | Y        | Y        | N        | P                           | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N      | P                                                                            | N        | 2      | 2      | 1       | 1246406400 | 1277856000 | 85.0   | 42.0     | 0.0      | 0        | 1.0     | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 0.0     | 2.0     | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 216100.0  | 0.0     | 1156.0  | 119.0    | 4955.0    | 1693.0   | 2392.0  | 934.0   | 21432.0  | 103797.0 | 481.0   | 187.0  | 3141.0   | 1.0    | 0.0    | 3.0    | 4.0   | 6.5     | 0.0     | 2.0     | 8.5    | 8.0      | 0.0      | 7.0      | 15.0    | 0.0      | 0.0      | 0.0      | 0.0     | 15.5     | 0.0      | 12.0     | 27.5    | 50.0     | 1.0      | 2917486.0 | 0.0       | 0.0       | 2917486.0 | 19378102.0 | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | statelibrary.alabama.gov/Content/Index.aspx | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | N        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y      | USE FRETWELL/DOWNING SOFTWARE TO SEARCH DISPERATE LIB CAT. TO SHARE MATERIAL | Y        | 1      | 3      | 2       | 1254355200 | 1285804800 | 40.0   | 0.0      | 0.0      | 0        | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 18.0    | 608.0  | 1695.0   | 2.0    | 0.0    | 3.75   | 5.75  | 9.0     | 1.0     | 21.75   | 31.75  | 0.0      | 0.0      | 0.0      | 0.0     | 0.0      | 0.0      | 4.0      | 4.0     | 11.0     | 1.0      | 29.5     | 41.5    | 23.0     | 0.0      | 1893304.0 | 1042582.0 | 500000.0  | 3435886.0 | 11536504.0 | 
| ARKANSAS STATE LIBRARY                             | 900 WEST CAPITOL, SUITE 100                   | LITTLE ROCK | AR      | 72201   | 3108     | 900 WEST CAPITOL, SUITE 100           | LITTLE ROCK | AR      | 72201   | 3108     | WWW.library.arkansas.gov                    | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | N        | N      | P                                                                            | N        | 5      | 6      | 1       | 1246406400 | 1277856000 | 127.0  | 42.0     | 0.0      | 0        | 1.0     | 2.0      | 0.0      | 3.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 760000.0  | 310.0   | 1000.0  | 1020.0   | 3400000.0 | 12809.0  | 4596.0  | 737.0   | 11466.0  | 19894.0  | 1693.0  | 53.0   | 3212.0   | 2.0    | 0.0    | 7.0    | 9.0   | 9.0     | 0.0     | 11.0    | 20.0   | 12.0     | 1.0      | 12.75    | 25.75   | 7.0      | 0.0      | 20.75    | 27.75   | 30.0     | 1.0      | 51.5     | 82.5    | 32.0     | 0.0      | 1035219.0 | 0.0       | 0.0       | 1035219.0 | 3751351.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                               | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | Y        | Y        | Y        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | N        | Y       | Y        | Y        | Y        | N      | P                                                                            | N        | 4      | 8      | 1       | 1246406400 | 1277856000 | 53.0   | 53.0     | 2.0      | 8        | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 2282579.0 | 1039.0  | 9260.0  | 585.0    | 2000.0    | 3599.0   | 6929.0  | 85.0    | 90606.0  | 10698.0  | 228.0   | 515.0  | 7853.0   | 1.87   | 0.0    | 5.63   | 7.5   | 9.37    | 0.0     | 2.82    | 12.19  | 17.81    | 1.87     | 21.57    | 41.25   | 0.0      | 0.0      | 0.0      | 0.0     | 29.05    | 1.87     | 30.02    | 60.94   | 9.0      | 0.0      | 324564.0  | 0.0       | 0.0       | 324564.0  | 3831074.0  | 
| CALIFORNIA STATE LIBRARY                           | 900 N ST                                      | SACRAMENTO  | CA      | 95814   | 4800     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                          | E      | G      | P        | P        | P        | P       | P        | P       | P       | N        | Y        | N        | N        | N        | P                           | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y      | DRIVE SWAP-OUT                                                               | N        | 6      | 2      | 1       | 1246406400 | 1277856000 | 90.0   | 45.0     | 0.0      | 0        | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 1.0    | 0.0    | 2.0    | 195414.0  | 625.0   | 50.0    | 56.0     | 16547.0   | 4512.0   | 809.0   | 596.0   | 10032.0  | 21139.0  | 12.0    | 110.0  | 2471.0   | 2.0    | 0.0    | 3.0    | 5.0   | 2.0     | 0.0     | 0.0     | 2.0    | 11.0     | 0.0      | 8.5      | 19.5    | 0.0      | 0.0      | 0.0      | 0.0     | 15.0     | 0.0      | 11.5     | 26.5    | 26.0     | 0.0      | 99995.0   | 670000.0  | 0.0       | 769995.0  | 12702379.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | www.cde.state.co.us/cdelib/                 | E      | P      | P        | P        | E        | P       | N        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y      | WEB INTERFACE TO MULTITYPE CATALOGS                                          | N        | 8      | 1      | 1       | 1246406400 | 1277856000 | 80.0   | 42.0     | 0.0      | 0        | 1.0     | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 0.0     | 2.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 30400.0   | 6122.0  | 5710.0  | 14.0     | 50000.0   | 9042.0   | 8458.0  | 1698.0  | 3540.0   | 2584.0   | 33.0    | 113.0  | 1940.0   | 0.94   | 0.0    | 14.06  | 15.0  | 14.06   | 0.0     | 10.31   | 24.37  | 13.13    | 0.0      | 3.75     | 16.88   | 2.81     | 0.0      | 36.56    | 39.37   | 30.94    | 0.0      | 64.68    | 95.62   | 2.0      | 0.0      | 0.0       | 669243.0  | 0.0       | 669243.0  | 1052567.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                               | E      | B      | X        | X        | P        | P       | P        | P       | P       | Y        | N        | Y        | Y        | N        | P                           | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | N        | Y       | Y        | Y        | Y        | N      | P                                                                            | Y        | 9      | 5      | 1       | 1246406400 | 1277856000 | 45.0   | 45.0     | 0.0      | 0        | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 540747.0  | 10676.0 | 17626.0 | 640.0    | 66576.0   | 58472.0  | 12054.0 | 9620.0  | 10600.0  | 77936.0  | 68.0    | 114.0  | 2233.0   | 2.0    | 0.0    | 6.0    | 8.0   | 5.0     | 0.0     | 2.0     | 7.0    | 16.0     | 0.0      | 24.0     | 40.0    | 0.0      | 0.0      | 0.0      | 0.0     | 23.0     | 0.0      | 32.0     | 55.0    | 41.0     | 2.0      | 0.0       | 2208823.0 | 0.0       | 2208823.0 | 4625364.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                           | E      | B      | P        | X        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | N        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | Y        | N      | P                                                                            | N        | 11     | 4      | 1       | 1254355200 | 1285804800 | 45.0   | 45.0     | 0.0      | 0        | 1.0     | 0.0      | 0.0      | 1.0      | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 1847.0    | 0.0     | 33.0    | 29.0     | 120.0     | 167.0    | 2.0     | 1.0     | 954.0    | 26.0     | 60.0    | 62.0   | 1616.0   | 1.88   | 0.0    | 4.22   | 6.1   | 5.63    | 0.0     | 3.75    | 9.38   | 0.94     | 0.0      | 0.0      | 0.94    | 0.0      | 0.0      | 5.16     | 5.16    | 8.45     | 0.0      | 13.13    | 21.58   | 2.0      | 0.0      | 383651.0  | 0.0       | 0.0       | 383651.0  | 814180.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 121 DUKE OF YORK STREET                       | DOVER       | DE      | 19901   | 7430     | 121 DUKE OF YORK STREET               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                         | E      | P      | P        | P        | S        | P       | Y        | X       | X       | N        | N        | N        | N        | N        | P                           | Y        | Y        | N        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                                                                            | Y        | 10     | 5      | 1       | 1246406400 | 1277856000 | 45.0   | 0.0      | 0.0      | 0        | 0.0     | 1.0      | 0.0      | 1.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0       | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 16.0    | 1712.0 | 2014.0   | 2.0    | 0.0    | 2.0    | 4.0   | 4.0     | 0.0     | 2.0     | 6.0    | 4.0      | 0.0      | 11.0     | 15.0    | 0.0      | 0.0      | 0.0      | 0.0     | 10.0     | 0.0      | 15.0     | 25.0    | 7.0      | 0.0      | 1160733.0 | 651658.0  | 0.0       | 1812391.0 | 6346105.0  | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                        | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | N        | N        | Y        | Y        | FLORIDA ADMINISTRATIVE CODE | N        | N        | Y        | N        | N        | N        | N        | N        | N        | N        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | N      | P                                                                            | Y        | 12     | 6      | 1       | 1246406400 | 1277856000 | 50.0   | 50.0     | 5.0      | 5        | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 416274.0  | 1071.0  | 1445.0  | 410.0    | 3255.0    | 188768.0 | 35488.0 | 26302.0 | 10409.0  | 65481.0  | 4.0     | 43.0   | 1116.0   | 3.0    | 1.0    | 0.0    | 4.0   | 5.0     | 1.0     | 0.0     | 6.0    | 9.0      | 0.0      | 27.0     | 36.0    | 0.0      | 0.0      | 0.0      | 0.0     | 17.0     | 2.0      | 27.0     | 46.0    | 17.0     | 0.0      | 1571670.0 | 6221440.0 | 1532724.0 | 9325834.0 | 25145561.0 | 
```