# State Libraries Survey, FY 2009, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2009-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/rna2-j7md) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/rna2-j7md/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/rna2-j7md/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | rna2-j7md |
| Name | State Libraries Survey, FY 2009, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2009, operations, workforce |
| Created | 2016-12-20T15:29:31Z |
| Publication Date | 2016-12-20T17:04:39Z |

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
| Yes      | series tag     | acccdrom   | CDROM union catalog                                        | text      | text        |
| Yes      | series tag     | acctlnet   | Telnet gateway                                             | text      | text        |
| Yes      | series tag     | accwbcat   | Union catalog                                              | text      | text        |
| Yes      | series tag     | accoth     | Other access to other libr                                 | text      | text        |
| Yes      | series tag     | othaccsp   | Other access specified                                     | text      | text        |
| Yes      | series tag     | erateapp   | E-rate discount                                            | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                                            | text      | text        |
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
| Yes      | numeric metric | admin      | Admin TOTAL                                                | number    | number      |
| Yes      | numeric metric | libdev     | Dev TOTAL                                                  | number    | number      |
| Yes      | numeric metric | libserv    | Services TOTAL                                             | number    | number      |
| Yes      | numeric metric | othserv    | Other TOTAL                                                | number    | number      |
| Yes      | numeric metric | totstaff   | Total staff                                                | number    | number      |
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
series e:rna2-j7md d:2008-07-01T00:00:00.000Z t:appbygov=P t:physaddr="701 NORTH FOURTH STREET" t:stlacont=N t:mailzip=70821 t:netmount=Y t:acccdrom=N t:mailaddr="P.O. BOX 131" t:stlaname="STATE LIBRARY OF LOUISIANA" t:physzip4=5232 t:acctlnet=Y t:webaddr=WWW.STATE.LIB.LA.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=N t:mail_st=LA t:obereg=8 t:elecbibl=Y t:phys_st=LA t:pla_gov=P t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=X t:strecmng=N t:accoth=Y t:largerag=C t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:physcity="BATON ROUGE" t:nettrstf=Y t:mailcity="BATON ROUGE" t:pub_fips=22 t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=70802 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=131 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:libserv=24 m:mainout=1 m:bkservol=557032 m:govdoc=51607 m:othserv=3 m:libvists=40506 m:bkmobile=0 m:mon2frce=0 m:video=16764 m:otstoutd=0 m:otstoutc=0 m:atevents=3511 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:grantaw=68 m:swdblicd=113594 m:tothrsce=45 m:coroutd=0 m:coroutb=0 m:swdblicb=98106 m:coroutc=0 m:swdblicc=0 m:events=131 m:swdblica=15488 m:corouta=0 m:recfrom=9524 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=0 m:gvemouta=1 m:bphouta=1 m:provto=9776 m:bphoutd=1 m:popu_st=698473 m:subscrip=640 m:paiw_oth=0 m:reftrans=11536 m:audio=10633 m:gpouta=1 m:pagiw_lo=7 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=1 m:circ=58941 m:admin=4 m:totstaff=36 m:libdev=5 m:tothrs=45

series e:rna2-j7md d:2008-07-01T00:00:00.000Z t:appbygov=X t:physaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:stlacont=Y t:mailzip=2114 t:netmount=Y t:acccdrom=N t:mailaddr="98 NORTH WASHINGTON STREET, SUITE 401" t:stlaname="MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS" t:physzip4=1933 t:acctlnet=N t:webaddr=MBLC.STATE.MA.US t:othallop=N t:netgoph=Y t:remoteac=N t:stdeplib=N t:sthstmus=N t:mail_st=MA t:obereg=5 t:elecbibl=Y t:phys_st=MA t:pla_gov=P t:netsub=Y t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=N t:schswdbl=N t:physcity=BOSTON t:nettrstf=Y t:mailcity=BOSTON t:pub_fips=25 t:elecoper=N t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=2114 t:dig_stla=N t:electext=Y t:lcswdbl=N t:othswdbl=N t:stlahost=Y t:nettrcus=Y t:mailzip4=1933 t:othaccsp=P t:netequip=N t:pla_brco=P t:spcswdbl=N t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=N m:libserv=12 m:mainout=1 m:bkservol=2082 m:govdoc=120 m:othserv=2 m:libvists=53 m:bkmobile=0 m:mon2frce=0 m:video=38 m:otstoutd=0 m:otstoutc=0 m:atevents=1271 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:grantaw=119 m:swdblicd=0 m:tothrsce=45 m:coroutd=0 m:coroutb=0 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=68 m:swdblica=0 m:corouta=0 m:recfrom=4 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=0 m:gvemouta=1 m:bphouta=0 m:provto=51 m:bphoutd=0 m:popu_st=4708708 m:subscrip=31 m:paiw_oth=0 m:reftrans=1173 m:audio=0 m:gpouta=1 m:pagiw_lo=13 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=1 m:circ=263 m:admin=10 m:totstaff=32 m:libdev=8 m:tothrs=45

series e:rna2-j7md d:2008-07-01T00:00:00.000Z t:appbygov=P t:physaddr="200 WEST BALTIMORE STREET" t:stlacont=Y t:mailzip=21201 t:netmount=Y t:acccdrom=N t:mailaddr="200 WEST BALTIMORE STREET" t:stlaname="DIVISION OF LIBRARY DEVELOPMENT AND SERVICES" t:physzip4=2595 t:acctlnet=Y t:webaddr=www.marylandpublicschools.org/MSDE/divisions/library t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=MD t:obereg=5 t:elecbibl=Y t:phys_st=MD t:pla_gov=X t:netsub=N t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=E t:dig_lib=N t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:physcity=BALTIMORE t:nettrstf=Y t:mailcity=BALTIMORE t:pub_fips=24 t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=21201 t:dig_stla=N t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=2595 t:othaccsp=P t:netequip=N t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=P t:acswdbl=Y m:libserv=35 m:mainout=0 m:bkservol=0 m:govdoc=0 m:othserv=4 m:libvists=0 m:bkmobile=0 m:mon2frce=0 m:video=0 m:otstoutd=0 m:otstoutc=0 m:atevents=1345 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=1 m:grantaw=116 m:swdblicd=870365 m:tothrsce=0 m:coroutd=0 m:coroutb=0 m:swdblicb=107000 m:coroutc=0 m:swdblicc=0 m:events=938 m:swdblica=763365 m:corouta=0 m:recfrom=0 m:gvemoutd=0 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=1 m:gvemouta=0 m:bphouta=0 m:provto=0 m:bphoutd=1 m:popu_st=2889450 m:subscrip=0 m:paiw_oth=0 m:reftrans=0 m:audio=0 m:gpouta=0 m:pagiw_lo=10 m:gpoutb=0 m:gpoutc=0 m:gpoutd=0 m:totalout=1 m:circ=0 m:admin=12 m:totstaff=56 m:libdev=5 m:tothrs=45
```

## Meta Commands

```ls
metric m:tothrs p:float l:"Hours open typical week" t:dataTypeName=number

metric m:tothrsce p:float l:"Hours open main outlet" t:dataTypeName=number

metric m:mon2frce p:float l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:satsunce p:float l:"Hours open Sat & Sun" t:dataTypeName=number

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

metric m:admin p:float l:"Admin TOTAL" t:dataTypeName=number

metric m:libdev p:float l:"Dev TOTAL" t:dataTypeName=number

metric m:libserv p:float l:"Services TOTAL" t:dataTypeName=number

metric m:othserv p:float l:"Other TOTAL" t:dataTypeName=number

metric m:totstaff p:float l:"Total staff" t:dataTypeName=number

metric m:pagiw_lo p:float l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:float l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:popu_st p:float l:Population t:dataTypeName=number

entity e:rna2-j7md l:"State Libraries Survey, FY 2009, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/rna2-j7md

property e:rna2-j7md t:meta.view v:id=rna2-j7md v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2009, Part 1: Operations & Workforce" v:attribution=IMLS

property e:rna2-j7md t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:rna2-j7md t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:rna2-j7md t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:rna2-j7md t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                     | physaddr                              | physcity       | phys_st | physzip | physzip4 | mailaddr                              | mailcity       | mail_st | mailzip | mailzip4 | webaddr                                                                       | branch | indagy | appbygov | appbyoth | largerag | othagsp | pla_brco | pla_gov | pld_oth | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                            | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | dig_stla | dig_ag | dig_lib | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | acccdrom | acctlnet | accwbcat | accoth | othaccsp                              | erateapp | pub_fips | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio   | video   | subscrip | govdoc   | circ     | provto  | recfrom | reftrans | libvists | grantaw | events | atevents | admin | libdev | libserv | othserv | totstaff | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | popu_st    | 
| ============================================ | ===================================== | ============== | ======= | ======= | ======== | ===================================== | ============== | ======= | ======= | ======== | ============================================================================= | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =================================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ===================================== | ======== | ======== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======= | ====== | ======== | ===== | ====== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========== | 
| STATE LIBRARY OF LOUISIANA                   | 701 NORTH FOURTH STREET               | BATON ROUGE    | LA      | 70802   | 5232     | P.O. BOX 131                          | BATON ROUGE    | LA      | 70821   | 131      | WWW.STATE.LIB.LA.US                                                           | E      | P      | P        | P        | C        | P       | Y        | P       | X       | N        | N        | N        | N        | N        | P                                   | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE | N        | 22       | 8      | 1       | 1214870400 | 1246320000 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 557032.0  | 10633.0 | 16764.0 | 640.0    | 51607.0  | 58941.0  | 9776.0  | 9524.0  | 11536.0  | 40506.0  | 68.0    | 131.0  | 3511.0   | 4.0   | 5.0    | 24.0    | 3.0     | 36.0     | 7.0      | 0.0      | 15488    | 98106    | 0        | 113594   | 698473.0   | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | 98 NORTH WASHINGTON STREET, SUITE 401 | BOSTON         | MA      | 2114    | 1933     | MBLC.STATE.MA.US                                                              | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                                   | Y        | Y        | N        | N        | N        | N        | Y        | N        | Y        | Y        | N        | N      | Y       | Y        | Y        | Y      | N        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N        | Y        | N      | P                                     | N        | 25       | 5      | 1       | 1214870400 | 1246320000 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 2082.0    | 0.0     | 38.0    | 31.0     | 120.0    | 263.0    | 51.0    | 4.0     | 1173.0   | 53.0     | 119.0   | 68.0   | 1271.0   | 10.0  | 8.0    | 12.0    | 2.0     | 32.0     | 13.0     | 0.0      | 0        | 0        | 0        | 0        | 4708708.0  | 
| DIVISION OF LIBRARY DEVELOPMENT AND SERVICES | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | 200 WEST BALTIMORE STREET             | BALTIMORE      | MD      | 21201   | 2595     | www.marylandpublicschools.org/MSDE/divisions/library                          | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                                   | Y        | Y        | N        | N        | N        | N        | Y        | Y        | Y        | Y        | N        | N      | N       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | N        | 24       | 5      | 1       | 1214870400 | 1246320000 | 45.0   | 0.0      | 0.0      | 0.0      | 0.0     | 1.0      | 0.0      | 1.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0      | 0.0      | 116.0   | 938.0  | 1345.0   | 12.0  | 5.0    | 35.0    | 4.0     | 56.0     | 10.0     | 0.0      | 763365   | 107000   | 0        | 870365   | 2889450.0  | 
| MAINE STATE LIBRARY                          | 230 STATE STREET                      | AUGUSTA        | ME      | 4333    | 64       | 64 STATE HOUSE STATION                | AUGUSTA        | ME      | 4333    | 64       | www.maine.gov/msl/                                                            | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                                   | Y        | N        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | N       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 23       | 6      | 1       | 1214870400 | 1246320000 | 57.0   | 57.0     | 12.0     | 5.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 350615.0  | 848.0   | 650.0   | 474.0    | 250888.0 | 157239.0 | 44440.0 | 35238.0 | 11361.0  | 75455.0  | 18.0    | 91.0   | 2185.0   | 20.0  | 10.0   | 45.8    | 39.0    | 114.8    | 9.0      | 0.0      | 677072   | 948      | 125      | 678145   | 6595778.0  | 
| LIBRARY OF MICHIGAN                          | 702 WEST KALAMAZOO STREET             | LANSING        | MI      | 48909   | 7507     | P.O. BOX 30007                        | LANSING        | MI      | 48909   | 7507     | www.michigan.gov/libraryofmichigan                                            | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                                   | N        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | N       | N        | N        | N       | N        | Y        | N        | N        | Y        | N      | P                                     | N        | 26       | 8      | 2       | 1222819200 | 1254268800 | 42.0   | 42.0     | 0.0      | 7.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 2478143.0 | 1755.0  | 3070.0  | 4903.0   | 992016.0 | 247056.0 | 11574.0 | 2137.0  | 32980.0  | 98000.0  | 1.0     | 13.0   | 939.0    | 31.0  | 22.0   | 56.5    | 23.0    | 132.5    | 10.0     | 0.0      | 1125000  | 0        | 0        | 1125000  | 36961664.0 | 
| STATE LIBRARY SERVICES                       | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4266     | 1500 HIGHWAY 36 WEST                  | ROSEVILLE      | MN      | 55113   | 4035     | http://education.state.mn.us/MDE/Learning_Support/Library_Services/index.html | E      | P      | P        | P        | E        | P       | Y        | P       | X       | N        | N        | N        | N        | N        | P                                   | Y        | N        | N        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 27       | 7      | 1       | 1214870400 | 1246320000 | 85.0   | 40.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0     | 0.0     | 0.0      | 343.0    | 23.0    | 14.0   | 397.0    | 9.5   | 14.0   | 17.0    | 0.0     | 40.5     | 2.0      | 0.0      | 0        | 1000000  | 0        | 1000000  | 5024748.0  | 
| MISSOURI STATE LIBRARY                       | 600 WEST MAIN STREET, 2ND FLOOR       | JEFFERSON CITY | MO      | 65101   | 1592     | PO BOX 387                            | JEFFERSON CITY | MO      | 65102   | 387      | WWW.SOS.MO.GOV/LIBRARY/                                                       | E      | P      | P        | P        | S        | P       | Y        | P       | X       | N        | N        | N        | N        | N        | P                                   | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 29       | 1      | 2       | 1214870400 | 1246320000 | 48.0   | 48.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 82724.0   | 22.0    | 148.0   | 89.0     | 16000.0  | 3129.0   | 179.0   | 599.0   | 5413.0   | 4511.0   | 524.0   | 96.0   | 1552.0   | 13.0  | 16.0   | 54.0    | 18.0    | 101.0    | 22.0     | 0.0      | 0        | 1964111  | 0        | 1964111  | 3518288.0  | 
| MISSISSIPPI LIBRARY COMMISSION               | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | 3881 EASTWOOD DRIVE                   | JACKSON        | MS      | 39211   | 6473     | WWW.MLC.LIB.MS.US                                                             | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                                   | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N      | N       | N        | N        | N      | Y        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N        | N        | N      | P                                     | N        | 28       | 2      | 1       | 1214870400 | 1246320000 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 114601.0  | 718.0   | 1349.0  | 92.0     | 0.0      | 9872.0   | 8037.0  | 343.0   | 25137.0  | 6062.0   | 160.0   | 71.0   | 1303.0   | 1.0   | 0.0    | 7.0     | 0.0     | 8.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 599657.0   | 
| MONTANA STATE LIBRARY                        | 1515 EAST 6TH AVENUE                  | HELENA         | MT      | 59620   | 1800     | PO BOX 201800                         | HELENA         | MT      | 59620   | 1800     | msl.mt.gov                                                                    | E      | B      | X        | X        | P        | P       | P        | P       | P       | N        | N        | N        | N        | Y        | NATURAL RESOURCE INFORMATION SYSTEM | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | N        | Y        | N        | N        | Y        | Y      | WEB PAGE ACCESS                       | N        | 30       | 2      | 1       | 1214870400 | 1246320000 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 52861.0   | 4.0     | 68.0    | 31.0     | 39695.0  | 876.0    | 280.0   | 859.0   | 444.0    | 20621.0  | 8.0     | 99.0   | 860.0    | 3.0   | 3.0    | 7.0     | 2.0     | 15.0     | 30.0     | 0.0      | 0        | 408120   | 9532     | 417652   | 885122.0   | 
| STATE LIBRARY OF NORTH CAROLINA              | 109 EAST JONES STREET                 | RALEIGH        | NC      | 27601   | 2807     | 4640 MAIL SERVICE CENTER              | RALEIGH        | NC      | 27699   | 4640     | STATELIBRARY.NCDCR.GOV                                                        | E      | P      | P        | P        | C        | P       | Y        | X       | X       | N        | N        | N        | N        | N        | P                                   | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | N        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 37       | 5      | 1       | 1214870400 | 1246320000 | 95.0   | 50.0     | 0.0      | 7.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 279870.0  | 0.0     | 6129.0  | 257.0    | 579732.0 | 35255.0  | 1896.0  | 227.0   | 14244.0  | 11181.0  | 161.0   | 76.0   | 1496.0   | 4.0   | 15.5   | 20.25   | 64.0    | 103.75   | 21.0     | 3.0      | 2878352  | 0        | 0        | 2878352  | 18537969.0 | 
```