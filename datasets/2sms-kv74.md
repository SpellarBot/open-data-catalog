# State Libraries Survey, FY 2012, Part 1: Operations & Workforce

## Dataset

* [Dataset URL](https://data.imls.gov/api/views/2sms-kv74/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/state-libraries-survey-fy-2012-part-1-operations-workforce)
* Id = 2sms-kv74
* Name = State Libraries Survey, FY 2012, Part 1: Operations & Workforce
* Attribution = IMLS
* Attribution Link = https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey
* Category = State Library Administrative Agencies Survey
* Tags = [state library, slaa, 2012, operations, workforce]
* Created = 2016-12-20T15:32:51Z
* Publication Date = 2016-12-20T17:04:42Z
* Rows Updated = 2016-12-20T17:24:25Z

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Name                                                       | Field Name | Data Type | Render Type | Schema Type    | Included | 
| ========================================================== | ========== | ========= | =========== | ============== | ======== | 
| STLA Name                                                  | stlaname   | text      | text        | series tag     | Yes      | 
| Street                                                     | physaddr   | text      | text        | series tag     | Yes      | 
| City                                                       | physcity   | text      | text        | series tag     | Yes      | 
| State                                                      | phys_st    | text      | text        | series tag     | Yes      | 
| Zip                                                        | physzip    | number    | text        | numeric metric | Yes      | 
| Zip+4                                                      | physzip4   | number    | text        | numeric metric | Yes      | 
| Street (mail)                                              | mailaddr   | text      | text        | series tag     | Yes      | 
| City (mail)                                                | mailcity   | text      | text        | series tag     | Yes      | 
| State (mail)                                               | mail_st    | text      | text        | series tag     | Yes      | 
| Zip (mail)                                                 | mailzip    | number    | text        | numeric metric | Yes      | 
| Zip+4 (mail)                                               | mailzip4   | number    | text        | numeric metric | Yes      | 
| Web Address                                                | webaddr    | text      | text        | series tag     | Yes      | 
| Branch of government [L]egis/[E]xec                        | branch     | number    | text        | numeric metric | Yes      | 
| SLAA reports to [G]overnor/[B]oard                         | indagy     | number    | text        | numeric metric | Yes      | 
| Appointed by governor [X]Yes/[P]n/a                        | appbygov   | number    | text        | numeric metric | Yes      | 
| Appointed by other official [X]Yes/[P]n/a                  | appbyoth   | number    | text        | numeric metric | Yes      | 
| Part of Dept of [E]duc/[C]ult Resrc/[S]tate/[O]ther/[P]n/a | largerag   | number    | text        | numeric metric | Yes      | 
| Other agency; [P]n/a                                       | othagsp    | text      | text        | series tag     | Yes      | 
| SLAA is sub-agency, has board [Y]es/[N]o/[P]n/a            | pla_brco   | number    | text        | numeric metric | Yes      | 
| Board appointed by Governor [X]Yes/[P]n/a                  | pla_gov    | number    | text        | numeric metric | Yes      | 
| Board appointed by other official [X]Yes/[P]n/a            | pld_oth    | number    | text        | numeric metric | Yes      | 
| State archives                                             | starchiv   | number    | text        | numeric metric | Yes      | 
| Primary state legislative research organization            | stlegref   | number    | text        | numeric metric | Yes      | 
| State history museum/art gallery                           | sthstmus   | number    | text        | numeric metric | Yes      | 
| State records management service                           | strecmng   | number    | text        | numeric metric | Yes      | 
| Other allied operation                                     | othallop   | number    | text        | numeric metric | Yes      | 
| Other allied operation; [P]n/a                             | othallsp   | text      | text        | series tag     | Yes      | 
| SLAA contracts with local/academic libraries               | stlacont   | number    | text        | numeric metric | Yes      | 
| SLAA hosts or funds State Center for the Book              | stlahost   | number    | text        | numeric metric | Yes      | 
| State depository library                                   | stdeplib   | number    | text        | numeric metric | Yes      | 
| Federal depository library                                 | fddeplib   | number    | text        | numeric metric | Yes      | 
| Regional fed dep library                                   | regional   | number    | text        | numeric metric | Yes      | 
| Selective fed dep library                                  | selectiv   | number    | text        | numeric metric | Yes      | 
| Network planning/monitoring                                | elecplan   | number    | text        | numeric metric | Yes      | 
| Network operation                                          | elecoper   | number    | text        | numeric metric | Yes      | 
| DB/Bibliographic databases                                 | elecbibl   | number    | text        | numeric metric | Yes      | 
| DB/Full text or data                                       | electext   | number    | text        | numeric metric | Yes      | 
| Digitization support/STLA                                  | dig_stla   | number    | text        | numeric metric | Yes      | 
| Digitization support/Other agencies                        | dig_ag     | number    | text        | numeric metric | Yes      | 
| Digitization support/libraries                             | dig_lib    | number    | text        | numeric metric | Yes      | 
| Internet access support thru staffing                      | nettrstf   | number    | text        | numeric metric | Yes      | 
| Internet access support thru st lib end-users              | nettrcus   | number    | text        | numeric metric | Yes      | 
| Internet access support thru direct funding                | netsub     | number    | text        | numeric metric | Yes      | 
| Intenet access support thru prov equip                     | netequip   | number    | text        | numeric metric | Yes      | 
| Internet access support thru online resrcs                 | netmount   | number    | text        | numeric metric | Yes      | 
| Internet access support thru website/server/list mgmt      | netgoph    | number    | text        | numeric metric | Yes      | 
| DBs avail to public libr                                   | pubswdbl   | number    | text        | numeric metric | Yes      | 
| DBs avail to acad libr                                     | acswdbl    | number    | text        | numeric metric | Yes      | 
| DBs avail to sch libr                                      | schswdbl   | number    | text        | numeric metric | Yes      | 
| DBs avail to special libr                                  | spcswdbl   | number    | text        | numeric metric | Yes      | 
| DBs avail to co-ops                                        | lcswdbl    | number    | text        | numeric metric | Yes      | 
| DBs avail to state agencies                                | othswdbl   | number    | text        | numeric metric | Yes      | 
| DBs avail to remote users                                  | remoteac   | number    | text        | numeric metric | Yes      | 
| Union catalog                                              | accwbcat   | number    | text        | numeric metric | Yes      | 
| Other access to other libr                                 | accoth     | number    | text        | numeric metric | Yes      | 
| Other access specified                                     | othaccsp   | text      | text        | series tag     | Yes      | 
| E-rate discount                                            | erateapp   | number    | text        | numeric metric | Yes      | 
| FIPS state code                                            | fipsst     | number    | text        | numeric metric | Yes      | 
| BEA code                                                   | obereg     | number    | text        | numeric metric | Yes      | 
| Reporting Status                                           | rstatus    | number    | text        | numeric metric | Yes      | 
| Fiscal year start date, mm/dd/yyyy                         | fystart    | date      | date        | time           | Yes      | 
| Fiscal year end date, mm/dd/yyyy                           | fyend      | date      | date        |                | No       | 
| Hours open typical week                                    | tothrs     | number    | number      | numeric metric | Yes      | 
| Hours open main outlet                                     | tothrsce   | number    | number      | numeric metric | Yes      | 
| Hours open M-F after 5pm                                   | mon2frce   | number    | number      | numeric metric | Yes      | 
| Hours open Sat & Sun                                       | satsunce   | number    | number      | numeric metric | Yes      | 
| Outlets (main)                                             | mainout    | number    | number      | numeric metric | Yes      | 
| Outlets (other)                                            | otherout   | number    | number      | numeric metric | Yes      | 
| Outlets (bookmobile)                                       | bkmobile   | number    | number      | numeric metric | Yes      | 
| Outlets (TOTAL)                                            | totalout   | number    | number      | numeric metric | Yes      | 
| BPH Outlets (main)                                         | bphouta    | number    | number      | numeric metric | Yes      | 
| BPH Outlets (other)                                        | bphoutb    | number    | number      | numeric metric | Yes      | 
| BPH Outlets (bookmobile)                                   | bphoutc    | number    | number      | numeric metric | Yes      | 
| BPH Outlets (TOTAL)                                        | bphoutd    | number    | number      | numeric metric | Yes      | 
| Corr Outlets (main)                                        | corouta    | number    | number      | numeric metric | Yes      | 
| Corr Outlets (other)                                       | coroutb    | number    | number      | numeric metric | Yes      | 
| Corr Outlets (bookmobile)                                  | coroutc    | number    | number      | numeric metric | Yes      | 
| Corr Outlets (TOTAL)                                       | coroutd    | number    | number      | numeric metric | Yes      | 
| Inst Outlets (main)                                        | otstouta   | number    | number      | numeric metric | Yes      | 
| Inst Outlets (other)                                       | otstoutb   | number    | number      | numeric metric | Yes      | 
| Inst Outlets (bookmobile)                                  | otstoutc   | number    | number      | numeric metric | Yes      | 
| Inst Outlets (TOTAL)                                       | otstoutd   | number    | number      | numeric metric | Yes      | 
| Govt Outlets (main)                                        | gvemouta   | number    | number      | numeric metric | Yes      | 
| Govt Outlets (other)                                       | gvemoutb   | number    | number      | numeric metric | Yes      | 
| Govt Outlets (bookmobile)                                  | gvemoutc   | number    | number      | numeric metric | Yes      | 
| Govt Outlets (TOTAL)                                       | gvemoutd   | number    | number      | numeric metric | Yes      | 
| Pub Outlets (main)                                         | gpouta     | number    | number      | numeric metric | Yes      | 
| Pub Outlets (other)                                        | gpoutb     | number    | number      | numeric metric | Yes      | 
| Pub Outlets (bookmobile)                                   | gpoutc     | number    | number      | numeric metric | Yes      | 
| Pub Outlets (TOTAL)                                        | gpoutd     | number    | number      | numeric metric | Yes      | 
| Volumes                                                    | bkservol   | number    | number      | numeric metric | Yes      | 
| Audio Materials                                            | audio      | number    | number      | numeric metric | Yes      | 
| Video Materials                                            | video      | number    | number      | numeric metric | Yes      | 
| Serial Subs                                                | subscrip   | number    | number      | numeric metric | Yes      | 
| Govt Documents                                             | govdoc     | number    | number      | numeric metric | Yes      | 
| Circulation                                                | circ       | number    | number      | numeric metric | Yes      | 
| ILL out                                                    | provto     | number    | number      | numeric metric | Yes      | 
| ILL in                                                     | recfrom    | number    | number      | numeric metric | Yes      | 
| Reference transactions                                     | reftrans   | number    | number      | numeric metric | Yes      | 
| Library visits                                             | libvists   | number    | number      | numeric metric | Yes      | 
| Grants awarded                                             | grantaw    | number    | number      | numeric metric | Yes      | 
| Number of events                                           | events     | number    | number      | numeric metric | Yes      | 
| Total attendance                                           | atevents   | number    | number      | numeric metric | Yes      | 
| Admin ALA-MLS                                              | madmin     | number    | number      | numeric metric | Yes      | 
| Admin non-MLS                                              | nadmin     | number    | number      | numeric metric | Yes      | 
| Admin other                                                | oadmin     | number    | number      | numeric metric | Yes      | 
| Admin TOTAL                                                | admin      | number    | number      | numeric metric | Yes      | 
| Dev ALA-MLS                                                | mlibdev    | number    | number      | numeric metric | Yes      | 
| Dev non-MLS                                                | nlibdev    | number    | number      | numeric metric | Yes      | 
| Dev other                                                  | olibdev    | number    | number      | numeric metric | Yes      | 
| Dev TOTAL                                                  | libdev     | number    | number      | numeric metric | Yes      | 
| Services ALA-MLS                                           | mlibserv   | number    | number      | numeric metric | Yes      | 
| Services non-MLS                                           | nlibserv   | number    | number      | numeric metric | Yes      | 
| Services other                                             | olibserv   | number    | number      | numeric metric | Yes      | 
| Services TOTAL                                             | libserv    | number    | number      | numeric metric | Yes      | 
| Other ALA-MLS                                              | mothserv   | number    | number      | numeric metric | Yes      | 
| Other non-MLS                                              | nothserv   | number    | number      | numeric metric | Yes      | 
| Other other                                                | oothserv   | number    | number      | numeric metric | Yes      | 
| Other TOTAL                                                | othserv    | number    | number      | numeric metric | Yes      | 
| Total ALA-MLS                                              | mtotstaf   | number    | number      | numeric metric | Yes      | 
| Total non-MLS                                              | ntotstaf   | number    | number      | numeric metric | Yes      | 
| Total other                                                | ototstaf   | number    | number      | numeric metric | Yes      | 
| TOTAL STAFF                                                | totstaf    | number    | number      | numeric metric | Yes      | 
| Internet access thru lib owned terminals                   | pagiw_lo   | number    | number      | numeric metric | Yes      | 
| Internet access thru other terminals                       | paiw_oth   | number    | number      | numeric metric | Yes      | 
| DB licensing exp federal                                   | swdblica   | number    | number      | numeric metric | Yes      | 
| DB licensing exp state                                     | swdblicb   | number    | number      | numeric metric | Yes      | 
| DB licensing exp other                                     | swdblicc   | number    | number      | numeric metric | Yes      | 
| DB licensing exp TOTAL                                     | swdblicd   | number    | number      | numeric metric | Yes      | 
| Population                                                 | popu_st    | number    | number      | numeric metric | Yes      | 
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
series e:2sms-kv74 d:2011-10-01T00:00:00.000Z t:appbygov=X t:physaddr="6030 MONTICELLO DRIVE" t:stlacont=N t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:webaddr=HTTP://WEBMINI.APLS.STATE.AL.US/APLS_WEB/APLS/APLS/ t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=AL t:elecbibl=Y t:phys_st=AL t:pla_gov=P t:netsub=Y t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:elecoper=N t:othagsp=P t:appbyoth=P t:elecplan=Y t:dig_stla=N t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=N t:nettrcus=Y t:othaccsp=P t:netequip=N t:pla_brco=P t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=Y m:mainout=1 m:libserv=11 m:ototstaf=18 m:bkservol=64302 m:mailzip=36117 m:govdoc=0 m:othserv=4 m:ntotstaf=0 m:physzip4=1907 m:nadmin=0 m:libvists=525 m:mothserv=0 m:bkmobile=0 m:nlibdev=0 m:mon2frce=0 m:nlibserv=0 m:oadmin=7 m:video=0 m:otstoutd=0 m:obereg=5 m:otstoutc=0 m:otstoutb=0 m:atevents=4946 m:otstouta=0 m:satsunce=0 m:otherout=0 m:totstaf=30 m:grantaw=108 m:swdblicd=1100399 m:fipsst=1 m:tothrsce=40 m:coroutd=0 m:coroutb=0 m:swdblicb=269800 m:oothserv=4 m:coroutc=0 m:swdblicc=0 m:nothserv=0 m:events=75 m:swdblica=830599 m:olibdev=0 m:corouta=0 m:madmin=1 m:recfrom=187 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:olibserv=7 m:bphoutb=0 m:gvemouta=1 m:bphouta=1 m:provto=1025 m:popu_st=4822023 m:bphoutd=1 m:mlibdev=7 m:rstatus=1 m:physzip=36117 m:subscrip=310 m:paiw_oth=0 m:reftrans=461 m:audio=0 m:gpouta=0 m:pagiw_lo=0 m:mlibserv=4 m:gpoutb=0 m:gpoutc=0 m:gpoutd=0 m:totalout=1 m:mailzip4=1907 m:circ=902 m:admin=8 m:libdev=7 m:tothrs=40 m:mtotstaf=12

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:appbygov=P t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:netmount=Y t:mailaddr="P.O. BOX 110571" t:stlaname="ALASKA DEPARTMENT OF EDUCATION, DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:webaddr=WWW.LIBRARY.STATE.AK.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:elecbibl=Y t:phys_st=AK t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=Y t:pld_oth=P t:strecmng=Y t:accoth=N t:largerag=E t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:dig_stla=Y t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=N t:nettrcus=Y t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:mainout=1 m:libserv=21 m:ototstaf=20.5 m:bkservol=136582 m:mailzip=99811 m:govdoc=622811 m:othserv=1 m:ntotstaf=0 m:physzip4=1770 m:nadmin=0 m:libvists=27498 m:mothserv=1 m:bkmobile=0 m:nlibdev=0 m:mon2frce=2 m:nlibserv=0 m:oadmin=3 m:video=1510 m:otstoutd=0 m:obereg=8 m:otstoutc=0 m:otstoutb=0 m:atevents=1067 m:otstouta=0 m:satsunce=0 m:otherout=1 m:totstaf=35.5 m:grantaw=203 m:swdblicd=165340 m:fipsst=2 m:tothrsce=41 m:coroutd=0 m:coroutb=0 m:swdblicb=0 m:oothserv=0 m:coroutc=0 m:swdblicc=0 m:nothserv=0 m:events=80 m:swdblica=165340 m:olibdev=5.5 m:corouta=0 m:madmin=1 m:recfrom=1359 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:olibserv=12 m:bphoutb=1 m:gvemouta=1 m:bphouta=0 m:provto=648 m:popu_st=731449 m:bphoutd=1 m:mlibdev=4 m:rstatus=1 m:physzip=99801 m:subscrip=1446 m:paiw_oth=0 m:reftrans=36159 m:audio=456 m:gpouta=1 m:pagiw_lo=8 m:mlibserv=9 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=2 m:mailzip4=571 m:circ=1377 m:admin=4 m:libdev=9.5 m:tothrs=85 m:mtotstaf=15

series e:2sms-kv74 d:2011-07-01T00:00:00.000Z t:appbygov=P t:physaddr="1700 WEST WASHINGTON - SUITE 200" t:stlacont=N t:netmount=Y t:mailaddr="1700 WEST WASHINGTON, ROOM 200" t:stlaname="ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS" t:webaddr=WWW.AZLIBRARY.GOV t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AZ t:elecbibl=Y t:phys_st=AZ t:pla_gov=P t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=Y t:starchiv=Y t:pld_oth=X t:strecmng=Y t:accoth=N t:largerag=S t:dig_lib=Y t:branch=E t:erateapp=Y t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:physcity=PHOENIX t:mailcity=PHOENIX t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:dig_stla=Y t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:othaccsp=P t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:stlegref=Y t:selectiv=N t:indagy=P t:acswdbl=N m:mainout=1 m:libserv=45 m:ototstaf=90.75 m:bkservol=730845 m:mailzip=85007 m:govdoc=482302 m:othserv=42.25 m:ntotstaf=3 m:physzip4=2896 m:nadmin=0 m:libvists=7053 m:mothserv=3 m:bkmobile=0 m:nlibdev=1 m:mon2frce=0 m:nlibserv=2 m:oadmin=17.5 m:video=4210 m:otstoutd=2 m:obereg=6 m:otstoutc=0 m:otstoutb=1 m:atevents=2538 m:otstouta=1 m:satsunce=0 m:otherout=1 m:totstaf=120.75 m:grantaw=60 m:swdblicd=850230 m:fipsst=4 m:tothrsce=45 m:coroutd=2 m:coroutb=1 m:swdblicb=767 m:oothserv=39.25 m:coroutc=0 m:swdblicc=12087 m:nothserv=0 m:events=82 m:swdblica=837376 m:olibdev=7 m:corouta=1 m:madmin=4 m:recfrom=638 m:gvemoutd=2 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=1 m:olibserv=27 m:bphoutb=1 m:gvemouta=1 m:bphouta=0 m:provto=1827 m:popu_st=6553255 m:bphoutd=1 m:mlibdev=4 m:rstatus=1 m:physzip=85007 m:subscrip=1920 m:paiw_oth=0 m:reftrans=8675 m:audio=57726 m:gpouta=1 m:pagiw_lo=10 m:mlibserv=16 m:gpoutb=1 m:gpoutc=0 m:gpoutd=2 m:totalout=2 m:mailzip4=2896 m:circ=25279 m:admin=21.5 m:libdev=12 m:tothrs=90 m:mtotstaf=27
```

## Meta Commands

```ls
metric m:physzip p:integer l:Zip t:dataTypeName=number

metric m:physzip4 p:integer l:Zip+4 t:dataTypeName=number

metric m:mailzip p:integer l:"Zip (mail)" t:dataTypeName=number

metric m:mailzip4 p:integer l:"Zip+4 (mail)" t:dataTypeName=number

metric m:fipsst p:integer l:"FIPS state code" t:dataTypeName=number

metric m:obereg p:integer l:"BEA code" t:dataTypeName=number

metric m:rstatus p:integer l:"Reporting Status" t:dataTypeName=number

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

metric m:madmin l:"Admin ALA-MLS" t:dataTypeName=number

metric m:nadmin l:"Admin non-MLS" t:dataTypeName=number

metric m:oadmin l:"Admin other" t:dataTypeName=number

metric m:admin l:"Admin TOTAL" t:dataTypeName=number

metric m:mlibdev l:"Dev ALA-MLS" t:dataTypeName=number

metric m:nlibdev l:"Dev non-MLS" t:dataTypeName=number

metric m:olibdev l:"Dev other" t:dataTypeName=number

metric m:libdev l:"Dev TOTAL" t:dataTypeName=number

metric m:mlibserv l:"Services ALA-MLS" t:dataTypeName=number

metric m:nlibserv l:"Services non-MLS" t:dataTypeName=number

metric m:olibserv l:"Services other" t:dataTypeName=number

metric m:libserv l:"Services TOTAL" t:dataTypeName=number

metric m:mothserv l:"Other ALA-MLS" t:dataTypeName=number

metric m:nothserv p:integer l:"Other non-MLS" t:dataTypeName=number

metric m:oothserv l:"Other other" t:dataTypeName=number

metric m:othserv l:"Other TOTAL" t:dataTypeName=number

metric m:mtotstaf l:"Total ALA-MLS" t:dataTypeName=number

metric m:ntotstaf l:"Total non-MLS" t:dataTypeName=number

metric m:ototstaf l:"Total other" t:dataTypeName=number

metric m:totstaf l:"TOTAL STAFF" t:dataTypeName=number

metric m:pagiw_lo p:integer l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:integer l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:popu_st p:integer l:Population t:dataTypeName=number

entity e:2sms-kv74 l:"State Libraries Survey, FY 2012, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/2sms-kv74

property e:2sms-kv74 t:meta.view d:2017-03-03T14:31:39.025Z v:id=2sms-kv74 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2012, Part 1: Operations & Workforce" v:attribution=IMLS

property e:2sms-kv74 t:meta.view.license d:2017-03-03T14:31:39.025Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:2sms-kv74 t:meta.view.owner d:2017-03-03T14:31:39.025Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:2sms-kv74 t:meta.view.tableauthor d:2017-03-03T14:31:39.025Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:2sms-kv74 t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:31:39.025Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```