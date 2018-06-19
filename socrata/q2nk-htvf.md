# State Libraries Survey, FY 2003, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2003-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/q2nk-htvf) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/q2nk-htvf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/q2nk-htvf/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | q2nk-htvf |
| Name | State Libraries Survey, FY 2003, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2003, operations, workforce |
| Created | 2016-12-20T20:46:19Z |
| Publication Date | 2016-12-20T21:43:25Z |

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
| Yes      | series tag     | nettrstf   | Internet access support thru staffing                      | text      | text        |
| Yes      | series tag     | nettrcus   | Internet access support thru st lib end-users              | text      | text        |
| Yes      | series tag     | netsub     | Internet access support thru direct funding                | text      | text        |
| Yes      | series tag     | netequip   | Intenet access support thru prov equip                     | text      | text        |
| Yes      | series tag     | netmount   | Internet access support thru online resrcs                 | text      | text        |
| Yes      | series tag     | netgoph    | Internet access support thru website/server/list mgmt      | text      | text        |
| Yes      | series tag     | ficsp      | Fastest internet speed                                     | text      | text        |
| Yes      | series tag     | ficspsp    | Other speed specified                                      | text      | text        |
| Yes      | series tag     | inrefreq   | Internet reference questions                               | text      | text        |
| Yes      | series tag     | accoldb    | DBs avail to other libr                                    | text      | text        |
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
| Yes      | series tag     | iacoop     | Grants to assist/monitor cooperation                       | text      | text        |
| Yes      | series tag     | lpartnr    | Grants to assist/monitor partnerships                      | text      | text        |
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
| Yes      | series tag     | gencol     | General collection                                         | text      | text        |
| Yes      | numeric metric | circ       | Circulation                                                | number    | number      |
| Yes      | numeric metric | provto     | ILL out                                                    | number    | number      |
| Yes      | numeric metric | recfrom    | ILL in                                                     | number    | number      |
| Yes      | numeric metric | reftrans   | Reference transactions                                     | number    | number      |
| Yes      | numeric metric | libvists   | Library visits                                             | number    | number      |
| Yes      | numeric metric | events     | Number of events                                           | number    | number      |
| Yes      | numeric metric | atevents   | Total attendance                                           | number    | number      |
| Yes      | numeric metric | grantmon   | Grants monitored                                           | number    | number      |
| Yes      | numeric metric | onsitmon   | On-site monitoring visits                                  | number    | number      |
| Yes      | numeric metric | admserva   | Admin ALA-MLS                                              | number    | number      |
| Yes      | numeric metric | admservb   | Admin professional                                         | number    | number      |
| Yes      | numeric metric | admservc   | Admin other                                                | number    | number      |
| Yes      | numeric metric | admservd   | Admin TOTAL                                                | number    | number      |
| Yes      | numeric metric | ldpuba     | Libr Dev ALA-MLS                                           | number    | number      |
| Yes      | numeric metric | ldpubb     | Libr Dev professional                                      | number    | number      |
| Yes      | numeric metric | ldpubc     | Libr Dev other                                             | number    | number      |
| Yes      | numeric metric | ldpubd     | Libr Dev TOTAL                                             | number    | number      |
| Yes      | numeric metric | ldscha     | Libr Dev school ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | ldschb     | Libr Dev school professional                               | number    | number      |
| Yes      | numeric metric | ldschc     | Libr Dev school other                                      | number    | number      |
| Yes      | numeric metric | ldschd     | Libr Dev school TOTAL                                      | number    | number      |
| Yes      | numeric metric | ldacada    | Libr Dev acad ALA-MLS                                      | number    | number      |
| Yes      | numeric metric | ldacadb    | Libr Dev acad professional                                 | number    | number      |
| Yes      | numeric metric | ldacadc    | Libr Dev acad other                                        | number    | number      |
| Yes      | numeric metric | ldacadd    | Libr Dev acad TOTAL                                        | number    | number      |
| Yes      | numeric metric | ldspeca    | Libr Dev special ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | ldspecb    | Libr Dev special professional                              | number    | number      |
| Yes      | numeric metric | ldspecc    | Libr Dev special other                                     | number    | number      |
| Yes      | numeric metric | ldspecd    | Libr Dev special TOTAL                                     | number    | number      |
| Yes      | numeric metric | ldothlba   | Libr Dev other ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | ldothlbb   | Libr Dev other professional                                | number    | number      |
| Yes      | numeric metric | ldothlbc   | Libr Dev other other                                       | number    | number      |
| Yes      | numeric metric | ldothlbd   | Libr Dev other TOTAL                                       | number    | number      |
| Yes      | numeric metric | totallda   | Libr Dev total ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | totalldb   | Libr Dev total professional                                | number    | number      |
| Yes      | numeric metric | totalldc   | Libr Dev total other                                       | number    | number      |
| Yes      | numeric metric | totalldd   | Libr Dev total TOTAL                                       | number    | number      |
| Yes      | numeric metric | lspubsva   | Libr svcs public ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | lspubsvb   | Libr svcs public professional                              | number    | number      |
| Yes      | numeric metric | lspubsvc   | Libr svcs public other                                     | number    | number      |
| Yes      | numeric metric | lspubsvd   | Libr svcs public TOTAL                                     | number    | number      |
| Yes      | numeric metric | lstecsva   | Libr svcs tech ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | lstecsvb   | Libr svcs tech professional                                | number    | number      |
| Yes      | numeric metric | lstecsvc   | Libr svcs tech other                                       | number    | number      |
| Yes      | numeric metric | lstecsvd   | Libr svcs tech TOTAL                                       | number    | number      |
| Yes      | numeric metric | lsothlsa   | Libr svcs other ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | lsothlsb   | Libr svcs other professional                               | number    | number      |
| Yes      | numeric metric | lsothlsc   | Libr svcs other other                                      | number    | number      |
| Yes      | numeric metric | lsothlsd   | Libr svcs other TOTAL                                      | number    | number      |
| Yes      | numeric metric | totallsa   | Libr svcs total ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | totallsb   | Libr svcs total professional                               | number    | number      |
| Yes      | numeric metric | totallsc   | Libr svcs total other                                      | number    | number      |
| Yes      | numeric metric | totallsd   | Libr svcs total TOTAL                                      | number    | number      |
| Yes      | numeric metric | othersva   | Other svcs ALA-MLS                                         | number    | number      |
| Yes      | numeric metric | othersvb   | Other svcs professional                                    | number    | number      |
| Yes      | numeric metric | othersvc   | Other svcs other                                           | number    | number      |
| Yes      | numeric metric | othersvd   | Other svcs TOTAL                                           | number    | number      |
| Yes      | numeric metric | totstafa   | Total staff ALA-MLS                                        | number    | number      |
| Yes      | numeric metric | totstafb   | Total staff professional                                   | number    | number      |
| Yes      | numeric metric | totstafc   | Total staff other                                          | number    | number      |
| Yes      | numeric metric | totstafd   | Total staff TOTAL                                          | number    | number      |
| Yes      | numeric metric | lstasea    | Admin of LSTA grants ALA-MLS                               | number    | number      |
| Yes      | numeric metric | lstaseb    | Admin of LSTA grants professional                          | number    | number      |
| Yes      | numeric metric | lstasec    | Admin of LSTA grants other                                 | number    | number      |
| Yes      | numeric metric | lstased    | Admin of LSTA grants TOTAL                                 | number    | number      |
| Yes      | numeric metric | staidsea   | Admin of state aid ALA-MLS                                 | number    | number      |
| Yes      | numeric metric | staidseb   | Admin of state aid professional                            | number    | number      |
| Yes      | numeric metric | staidsec   | Admin of state aid other                                   | number    | number      |
| Yes      | numeric metric | staidsed   | Admin of state aid TOTAL                                   | number    | number      |
| Yes      | numeric metric | aendsea    | Automation/electronic dev ALA-MLS                          | number    | number      |
| Yes      | numeric metric | aendseb    | Automation/electronic dev professional                     | number    | number      |
| Yes      | numeric metric | aendsec    | Automation/electronic dev other                            | number    | number      |
| Yes      | numeric metric | aendsed    | Automation/electronic dev TOTAL                            | number    | number      |
| Yes      | numeric metric | bphsea     | Blind/phys hand svcs ALA-MLS                               | number    | number      |
| Yes      | numeric metric | bphseb     | Blind/phys hand svcs professional                          | number    | number      |
| Yes      | numeric metric | bphsec     | Blind/phys hand svcs other                                 | number    | number      |
| Yes      | numeric metric | bphsed     | Blind/phys hand svcs TOTAL                                 | number    | number      |
| Yes      | numeric metric | cyasea     | Childr/YA svcs ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | cyaseb     | Childr/YA svcs professional                                | number    | number      |
| Yes      | numeric metric | cyasec     | Childr/YA svcs other                                       | number    | number      |
| Yes      | numeric metric | cyased     | Childr/YA svcs TOTAL                                       | number    | number      |
| Yes      | numeric metric | ilssea     | Inst libr svcs ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | ilsseb     | Inst libr svcs professional                                | number    | number      |
| Yes      | numeric metric | ilssec     | Inst libr svcs other                                       | number    | number      |
| Yes      | numeric metric | ilssed     | Inst libr svcs TOTAL                                       | number    | number      |
| Yes      | numeric metric | lbstasea   | Libr statistics ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | lbstaseb   | Libr statistics professional                               | number    | number      |
| Yes      | numeric metric | lbstasec   | Libr statistics other                                      | number    | number      |
| Yes      | numeric metric | lbstased   | Libr statistics TOTAL                                      | number    | number      |
| Yes      | numeric metric | litprsea   | Literacy support ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | litprseb   | Literacy support professional                              | number    | number      |
| Yes      | numeric metric | litprsec   | Literacy support other                                     | number    | number      |
| Yes      | numeric metric | litprsed   | Literacy support TOTAL                                     | number    | number      |
| Yes      | numeric metric | markcoma   | Mktg/communications ALA-MLS                                | number    | number      |
| Yes      | numeric metric | markcomb   | Mktg/communications professional                           | number    | number      |
| Yes      | numeric metric | markcomc   | Mktg/communications other                                  | number    | number      |
| Yes      | numeric metric | markcomd   | Mktg/communications TOTAL                                  | number    | number      |
| Yes      | numeric metric | pagiw_lo   | Internet access thru lib owned terminals                   | number    | number      |
| Yes      | numeric metric | paiw_oth   | Internet access thru other terminals                       | number    | number      |
| Yes      | numeric metric | swdblica   | DB licensing exp federal                                   | number    | number      |
| Yes      | numeric metric | swdblicb   | DB licensing exp state                                     | number    | number      |
| Yes      | numeric metric | swdblicc   | DB licensing exp other                                     | number    | number      |
| Yes      | numeric metric | swdblicd   | DB licensing exp TOTAL                                     | number    | number      |
| Yes      | numeric metric | readsch    | Grants to assist/sch readiness                             | money     | money       |
| Yes      | numeric metric | adfamlit   | Grants to assist/adult & fam literacy                      | money     | money       |
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
series e:q2nk-htvf d:2002-07-01T00:00:00.000Z t:appbygov=P t:stlacont=Y t:physaddr="333 WILLOUGHBY AVENUE" t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:acccdrom=N t:ficsp=T3 t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:acctlnet=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=Y t:ficspsp=P t:sthstmus=Y t:mail_st=AK t:iacoop=N t:obereg=8 t:phys_st=AK t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:othallsp=P t:starchiv=Y t:strecmng=Y t:accoth=Y t:largerag=E t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:gencol=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:pub_fips=2 t:inrefreq=Y t:elecoper=Y t:accoldb=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=99811 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=571 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:netequip=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:selectiv=Y t:stlegref=N t:indagy=P t:acswdbl=Y m:totalldc=1 m:totalldb=0 m:totallda=5 m:othersva=0 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=55383 m:othersvd=3 m:othersvc=2 m:lstecsva=2 m:lstecsvd=5 m:video=708 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=2 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=1187 m:lbstasea=0 m:otstouta=0 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0.5 m:lbstased=0.5 m:otherout=1 m:aendsed=4 m:lsothlsb=0 m:lsothlsa=4 m:admservd=5 m:admserva=2 m:litprseb=0 m:litprsea=0 m:admservc=3 m:admservb=0 m:lspubsvb=0 m:lspubsva=4 m:lspubsvd=8 m:litprsed=0 m:lspubsvc=4 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=52000 m:coroutc=0 m:swdblicc=0 m:events=95 m:corouta=0 m:swdblica=0 m:lstasea=0.4 m:recfrom=2160 m:ilssed=0 m:bphoutc=0 m:lstased=0.4 m:bphoutb=1 m:ilsseb=0 m:lstasec=0 m:bphouta=0 m:lstaseb=0 m:ilssec=0 m:ldschc=0.5 m:ldschb=0 m:bphoutd=1 m:ldscha=1 m:popu_st=648818 m:ldschd=1.5 m:paiw_oth=0 m:totalout=2 m:onsitmon=46 m:ilssea=0 m:readsch=0 m:circ=6555 m:ldpuba=1 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=1.5 m:mainout=1 m:bkservol=114387 m:govdoc=580000 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=52000 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=40 m:ldothlba=3 m:totallsd=21 m:totallsc=11 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=3 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=10 m:gvemoutb=0 m:gvemouta=1 m:provto=1052 m:markcomd=0 m:subscrip=944 m:grantmon=146 m:bphsea=0.1 m:cyasea=0.5 m:cyaseb=0 m:bphsec=2 m:cyasec=0 m:reftrans=16302 m:bphseb=0 m:cyased=0.5 m:audio=103 m:gpouta=1 m:pagiw_lo=5 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.5 m:bphsed=2.1 m:staidseb=0 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=8 m:lsothlsc=4 m:totstafc=17 m:totstafd=35 m:totstafa=17 m:tothrs=80 m:totstafb=1

series e:q2nk-htvf d:2002-10-01T00:00:00.000Z t:appbygov=X t:stlacont=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:acccdrom=N t:ficsp=T1 t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:acctlnet=N t:webaddr=WWW.APLS.STATE.AL.US t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=N t:ficspsp=P t:sthstmus=N t:mail_st=AL t:iacoop=N t:obereg=5 t:phys_st=AL t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:othallsp=P t:starchiv=N t:strecmng=N t:accoth=N t:largerag=P t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:gencol=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:pub_fips=1 t:inrefreq=Y t:elecoper=N t:accoldb=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=36117 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=1 t:othaccsp=P t:netequip=N t:spcswdbl=Y t:accwbcat=Y t:regional=N t:selectiv=Y t:stlegref=N t:indagy=B t:acswdbl=Y m:totalldc=1 m:totalldb=0 m:totallda=6 m:othersva=0 m:othersvb=0 m:totalldd=7 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=6915 m:othersvd=4 m:othersvc=4 m:lstecsva=5 m:lstecsvd=10 m:video=5628 m:lstecsvc=5 m:lstecsvb=0 m:aendsea=0 m:aendseb=0 m:aendsec=4 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=1050 m:lbstasea=2 m:otstouta=0 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0 m:lbstased=2 m:otherout=0 m:aendsed=4 m:lsothlsb=0 m:lsothlsa=4 m:admservd=13 m:admserva=2 m:litprseb=0 m:litprsea=1 m:admservc=8 m:admservb=3 m:lspubsvb=0 m:lspubsva=3 m:lspubsvd=10 m:litprsed=1 m:lspubsvc=7 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=2689973 m:coroutc=0 m:swdblicc=0 m:events=59 m:corouta=0 m:swdblica=0 m:lstasea=2 m:recfrom=2106 m:ilssed=0 m:bphoutc=0 m:lstased=7 m:bphoutb=0 m:ilsseb=0 m:lstasec=3 m:bphouta=1 m:lstaseb=2 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=4500752 m:ldschd=0 m:paiw_oth=0 m:totalout=1 m:onsitmon=6 m:ilssea=0 m:readsch=0 m:circ=9106 m:ldpuba=6 m:ldpubb=0 m:ldpubc=1 m:ldpubd=7 m:mainout=1 m:bkservol=147026 m:govdoc=1400 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=2689973 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=40 m:ldothlba=0 m:totallsd=28 m:totallsc=16 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=0 m:markcomb=1 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=12 m:gvemoutb=0 m:gvemouta=1 m:provto=11833 m:markcomd=1 m:subscrip=614 m:grantmon=92 m:bphsea=4 m:cyasea=1 m:cyaseb=0 m:bphsec=4 m:cyasec=0 m:reftrans=12971 m:bphseb=0 m:cyased=1 m:audio=0 m:gpouta=1 m:pagiw_lo=6 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=2 m:bphsed=8 m:staidseb=1 m:staidsec=2 m:staidsed=5 m:lsothlsd=8 m:lsothlsc=4 m:totstafc=29 m:totstafd=52 m:totstafa=20 m:tothrs=40 m:totstafb=3

series e:q2nk-htvf d:2002-07-01T00:00:00.000Z t:appbygov=P t:stlacont=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:mailzip=72201 t:netmount=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:acccdrom=N t:ficsp=OTH t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:acctlnet=Y t:webaddr=WWW.ASL.LIB.AR.US t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=Y t:ficspsp="90-135 MBS" t:sthstmus=N t:mail_st=AR t:iacoop=N t:obereg=5 t:phys_st=AR t:elecbibl=Y t:netsub=N t:fddeplib=Y t:othallsp=P t:starchiv=N t:strecmng=N t:accoth=N t:largerag=E t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:nettrstf=Y t:gencol=Y t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:pub_fips=5 t:inrefreq=Y t:elecoper=Y t:accoldb=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=72201 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=1085 t:othaccsp=P t:netequip=N t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:selectiv=N t:stlegref=N t:indagy=P t:acswdbl=Y m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=2 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=9348 m:othersvd=3 m:othersvc=0 m:lstecsva=6 m:lstecsvd=16 m:video=986 m:lstecsvc=10 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=0 m:otstoutd=1 m:otstoutc=0 m:otstoutb=0 m:atevents=2394 m:lbstasea=0.5 m:otstouta=1 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0 m:lbstased=0.5 m:otherout=0 m:aendsed=2 m:lsothlsb=0 m:lsothlsa=0 m:admservd=12 m:admserva=2 m:litprseb=0 m:litprsea=0.5 m:admservc=7 m:admservb=3 m:lspubsvb=4 m:lspubsva=6 m:lspubsvd=21 m:litprsed=0.5 m:lspubsvc=11 m:litprsec=0 m:coroutd=1 m:coroutb=0 m:swdblicb=177344 m:coroutc=0 m:swdblicc=0 m:events=74 m:corouta=1 m:swdblica=746307 m:lstasea=1 m:recfrom=618 m:ilssed=0.5 m:bphoutc=0 m:lstased=1.5 m:bphoutb=0 m:ilsseb=0 m:lstasec=0 m:bphouta=1 m:lstaseb=0.5 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=2725714 m:ldschd=0 m:paiw_oth=0 m:totalout=1 m:onsitmon=0 m:ilssea=0.5 m:readsch=0 m:circ=10282 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:mainout=1 m:bkservol=103402 m:govdoc=2141464 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=923651 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=45 m:ldothlba=0 m:totallsd=37 m:totallsc=21 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=1 m:markcomb=1 m:gvemoutd=1 m:totallsb=4 m:markcoma=0 m:gvemoutc=0 m:totallsa=12 m:gvemoutb=0 m:gvemouta=1 m:provto=11586 m:markcomd=2 m:subscrip=1500 m:grantmon=0 m:bphsea=2 m:cyasea=0.5 m:cyaseb=0 m:bphsec=8.5 m:cyasec=0 m:reftrans=5591 m:bphseb=0 m:cyased=0.5 m:audio=769 m:gpouta=1 m:pagiw_lo=8 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=10.5 m:staidseb=0.5 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=30 m:totstafd=58 m:totstafa=20 m:tothrs=45 m:totstafb=8
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

metric m:events p:float l:"Number of events" t:dataTypeName=number

metric m:atevents p:float l:"Total attendance" t:dataTypeName=number

metric m:grantmon p:float l:"Grants monitored" t:dataTypeName=number

metric m:onsitmon p:float l:"On-site monitoring visits" t:dataTypeName=number

metric m:admserva p:float l:"Admin ALA-MLS" t:dataTypeName=number

metric m:admservb p:float l:"Admin professional" t:dataTypeName=number

metric m:admservc p:float l:"Admin other" t:dataTypeName=number

metric m:admservd p:float l:"Admin TOTAL" t:dataTypeName=number

metric m:ldpuba p:float l:"Libr Dev ALA-MLS" t:dataTypeName=number

metric m:ldpubb p:float l:"Libr Dev professional" t:dataTypeName=number

metric m:ldpubc p:float l:"Libr Dev other" t:dataTypeName=number

metric m:ldpubd p:float l:"Libr Dev TOTAL" t:dataTypeName=number

metric m:ldscha p:float l:"Libr Dev school ALA-MLS" t:dataTypeName=number

metric m:ldschb p:float l:"Libr Dev school professional" t:dataTypeName=number

metric m:ldschc p:float l:"Libr Dev school other" t:dataTypeName=number

metric m:ldschd p:float l:"Libr Dev school TOTAL" t:dataTypeName=number

metric m:ldacada p:float l:"Libr Dev acad ALA-MLS" t:dataTypeName=number

metric m:ldacadb p:float l:"Libr Dev acad professional" t:dataTypeName=number

metric m:ldacadc p:float l:"Libr Dev acad other" t:dataTypeName=number

metric m:ldacadd p:float l:"Libr Dev acad TOTAL" t:dataTypeName=number

metric m:ldspeca p:float l:"Libr Dev special ALA-MLS" t:dataTypeName=number

metric m:ldspecb p:float l:"Libr Dev special professional" t:dataTypeName=number

metric m:ldspecc p:float l:"Libr Dev special other" t:dataTypeName=number

metric m:ldspecd p:float l:"Libr Dev special TOTAL" t:dataTypeName=number

metric m:ldothlba p:float l:"Libr Dev other ALA-MLS" t:dataTypeName=number

metric m:ldothlbb p:float l:"Libr Dev other professional" t:dataTypeName=number

metric m:ldothlbc p:float l:"Libr Dev other other" t:dataTypeName=number

metric m:ldothlbd p:float l:"Libr Dev other TOTAL" t:dataTypeName=number

metric m:totallda p:float l:"Libr Dev total ALA-MLS" t:dataTypeName=number

metric m:totalldb p:float l:"Libr Dev total professional" t:dataTypeName=number

metric m:totalldc p:float l:"Libr Dev total other" t:dataTypeName=number

metric m:totalldd p:float l:"Libr Dev total TOTAL" t:dataTypeName=number

metric m:lspubsva p:float l:"Libr svcs public ALA-MLS" t:dataTypeName=number

metric m:lspubsvb p:float l:"Libr svcs public professional" t:dataTypeName=number

metric m:lspubsvc p:float l:"Libr svcs public other" t:dataTypeName=number

metric m:lspubsvd p:float l:"Libr svcs public TOTAL" t:dataTypeName=number

metric m:lstecsva p:float l:"Libr svcs tech ALA-MLS" t:dataTypeName=number

metric m:lstecsvb p:float l:"Libr svcs tech professional" t:dataTypeName=number

metric m:lstecsvc p:float l:"Libr svcs tech other" t:dataTypeName=number

metric m:lstecsvd p:float l:"Libr svcs tech TOTAL" t:dataTypeName=number

metric m:lsothlsa p:float l:"Libr svcs other ALA-MLS" t:dataTypeName=number

metric m:lsothlsb p:float l:"Libr svcs other professional" t:dataTypeName=number

metric m:lsothlsc p:float l:"Libr svcs other other" t:dataTypeName=number

metric m:lsothlsd p:float l:"Libr svcs other TOTAL" t:dataTypeName=number

metric m:totallsa p:float l:"Libr svcs total ALA-MLS" t:dataTypeName=number

metric m:totallsb p:float l:"Libr svcs total professional" t:dataTypeName=number

metric m:totallsc p:float l:"Libr svcs total other" t:dataTypeName=number

metric m:totallsd p:float l:"Libr svcs total TOTAL" t:dataTypeName=number

metric m:othersva p:float l:"Other svcs ALA-MLS" t:dataTypeName=number

metric m:othersvb p:float l:"Other svcs professional" t:dataTypeName=number

metric m:othersvc p:float l:"Other svcs other" t:dataTypeName=number

metric m:othersvd p:float l:"Other svcs TOTAL" t:dataTypeName=number

metric m:totstafa p:float l:"Total staff ALA-MLS" t:dataTypeName=number

metric m:totstafb p:float l:"Total staff professional" t:dataTypeName=number

metric m:totstafc p:float l:"Total staff other" t:dataTypeName=number

metric m:totstafd p:float l:"Total staff TOTAL" t:dataTypeName=number

metric m:lstasea p:float l:"Admin of LSTA grants ALA-MLS" t:dataTypeName=number

metric m:lstaseb p:float l:"Admin of LSTA grants professional" t:dataTypeName=number

metric m:lstasec p:float l:"Admin of LSTA grants other" t:dataTypeName=number

metric m:lstased p:float l:"Admin of LSTA grants TOTAL" t:dataTypeName=number

metric m:staidsea p:float l:"Admin of state aid ALA-MLS" t:dataTypeName=number

metric m:staidseb p:float l:"Admin of state aid professional" t:dataTypeName=number

metric m:staidsec p:float l:"Admin of state aid other" t:dataTypeName=number

metric m:staidsed p:float l:"Admin of state aid TOTAL" t:dataTypeName=number

metric m:aendsea p:float l:"Automation/electronic dev ALA-MLS" t:dataTypeName=number

metric m:aendseb p:float l:"Automation/electronic dev professional" t:dataTypeName=number

metric m:aendsec p:float l:"Automation/electronic dev other" t:dataTypeName=number

metric m:aendsed p:float l:"Automation/electronic dev TOTAL" t:dataTypeName=number

metric m:bphsea p:float l:"Blind/phys hand svcs ALA-MLS" t:dataTypeName=number

metric m:bphseb p:float l:"Blind/phys hand svcs professional" t:dataTypeName=number

metric m:bphsec p:float l:"Blind/phys hand svcs other" t:dataTypeName=number

metric m:bphsed p:float l:"Blind/phys hand svcs TOTAL" t:dataTypeName=number

metric m:cyasea p:float l:"Childr/YA svcs ALA-MLS" t:dataTypeName=number

metric m:cyaseb p:float l:"Childr/YA svcs professional" t:dataTypeName=number

metric m:cyasec p:float l:"Childr/YA svcs other" t:dataTypeName=number

metric m:cyased p:float l:"Childr/YA svcs TOTAL" t:dataTypeName=number

metric m:ilssea p:float l:"Inst libr svcs ALA-MLS" t:dataTypeName=number

metric m:ilsseb p:float l:"Inst libr svcs professional" t:dataTypeName=number

metric m:ilssec p:float l:"Inst libr svcs other" t:dataTypeName=number

metric m:ilssed p:float l:"Inst libr svcs TOTAL" t:dataTypeName=number

metric m:lbstasea p:float l:"Libr statistics ALA-MLS" t:dataTypeName=number

metric m:lbstaseb p:float l:"Libr statistics professional" t:dataTypeName=number

metric m:lbstasec p:float l:"Libr statistics other" t:dataTypeName=number

metric m:lbstased p:float l:"Libr statistics TOTAL" t:dataTypeName=number

metric m:litprsea p:float l:"Literacy support ALA-MLS" t:dataTypeName=number

metric m:litprseb p:float l:"Literacy support professional" t:dataTypeName=number

metric m:litprsec p:float l:"Literacy support other" t:dataTypeName=number

metric m:litprsed p:float l:"Literacy support TOTAL" t:dataTypeName=number

metric m:markcoma p:float l:"Mktg/communications ALA-MLS" t:dataTypeName=number

metric m:markcomb p:float l:"Mktg/communications professional" t:dataTypeName=number

metric m:markcomc p:float l:"Mktg/communications other" t:dataTypeName=number

metric m:markcomd p:float l:"Mktg/communications TOTAL" t:dataTypeName=number

metric m:pagiw_lo p:float l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:float l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:readsch p:double l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adfamlit p:double l:"Grants to assist/adult & fam literacy" t:dataTypeName=money

metric m:popu_st p:double l:Population t:dataTypeName=number

entity e:q2nk-htvf l:"State Libraries Survey, FY 2003, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/q2nk-htvf

property e:q2nk-htvf t:meta.view v:id=q2nk-htvf v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2003, Part 1: Operations & Workforce" v:attribution=IMLS

property e:q2nk-htvf t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:q2nk-htvf t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:q2nk-htvf t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:q2nk-htvf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | branch | indagy | appbygov | appbyoth | largerag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp        | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | ficsp | ficspsp    | inrefreq | accoldb | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | acccdrom | acctlnet | accwbcat | accoth | othaccsp                              | erateapp | iacoop | lpartnr | pub_fips | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio   | video   | subscrip | govdoc    | gencol | circ    | provto  | recfrom | reftrans | libvists | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lstasea | lstaseb | lstasec | lstased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | markcoma | markcomb | markcomc | markcomd | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | readsch  | adfamlit  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | ===================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | =============== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ===== | ========== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ===================================== | ======== | ====== | ======= | ======== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======= | ======= | ======== | ========= | ====== | ======= | ======= | ======= | ======== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US               | E      | P      | P        | P        | E        | P       | Y        | N        | Y        | Y        | N        | P               | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T3    | P          | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE | N        | N      | N       | 2        | 8      | 1       | 1025481600 | 1056931200 | 80.0   | 40.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 114387.0  | 103.0   | 708.0   | 944.0    | 580000.0  | Y      | 6555.0  | 1052.0  | 2160.0  | 16302.0  | 55383.0  | 95.0   | 1187.0   | 146.0    | 46.0     | 2.0      | 0.0      | 3.0      | 5.0      | 1.0    | 0.0    | 0.5    | 1.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 0.0      | 3.0      | 5.0      | 0.0      | 1.0      | 6.0      | 4.0      | 0.0      | 4.0      | 8.0      | 2.0      | 0.0      | 3.0      | 5.0      | 4.0      | 0.0      | 4.0      | 8.0      | 10.0     | 0.0      | 11.0     | 21.0     | 0.0      | 1.0      | 2.0      | 3.0      | 17.0     | 1.0      | 17.0     | 35.0     | 0.4     | 0.0     | 0.0     | 0.4     | 0.5      | 0.0      | 0.0      | 0.5      | 1.0     | 1.0     | 2.0     | 4.0     | 0.1    | 0.0    | 2.0    | 2.1    | 0.5    | 0.0    | 0.0    | 0.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0      | 0.0      | 0.5      | 0.5      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 5.0      | 0.0      | 0        | 52000    | 0        | 52000    | 0.0      | 0.0       | 648818.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | E      | B      | X        | P        | P        | P       | N        | N        | N        | N        | N        | P               | N        | N        | N        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y      | N        | Y        | Y       | T1    | P          | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | N        | N      | N       | 1        | 5      | 1       | 1033430400 | 1064880000 | 40.0   | 40.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 147026.0  | 0.0     | 5628.0  | 614.0    | 1400.0    | Y      | 9106.0  | 11833.0 | 2106.0  | 12971.0  | 6915.0   | 59.0   | 1050.0   | 92.0     | 6.0      | 2.0      | 3.0      | 8.0      | 13.0     | 6.0    | 0.0    | 1.0    | 7.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 0.0      | 1.0      | 7.0      | 3.0      | 0.0      | 7.0      | 10.0     | 5.0      | 0.0      | 5.0      | 10.0     | 4.0      | 0.0      | 4.0      | 8.0      | 12.0     | 0.0      | 16.0     | 28.0     | 0.0      | 0.0      | 4.0      | 4.0      | 20.0     | 3.0      | 29.0     | 52.0     | 2.0     | 2.0     | 3.0     | 7.0     | 2.0      | 1.0      | 2.0      | 5.0      | 0.0     | 0.0     | 4.0     | 4.0     | 4.0    | 0.0    | 4.0    | 8.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 2.0      | 0.0      | 0.0      | 2.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0      | 1.0      | 6.0      | 0.0      | 0        | 2689973  | 0        | 2689973  | 0.0      | 0.0       | 4500752.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     | E      | P      | P        | P        | E        | P       | N        | N        | N        | N        | N        | P               | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | N        | Y        | Y       | OTH   | 90-135 MBS | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | N        | N      | N       | 5        | 5      | 1       | 1025481600 | 1056931200 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 103402.0  | 769.0   | 986.0   | 1500.0   | 2141464.0 | Y      | 10282.0 | 11586.0 | 618.0   | 5591.0   | 9348.0   | 74.0   | 2394.0   | 0.0      | 0.0      | 2.0      | 3.0      | 7.0      | 12.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 6.0      | 4.0      | 11.0     | 21.0     | 6.0      | 0.0      | 10.0     | 16.0     | 0.0      | 0.0      | 0.0      | 0.0      | 12.0     | 4.0      | 21.0     | 37.0     | 2.0      | 1.0      | 0.0      | 3.0      | 20.0     | 8.0      | 30.0     | 58.0     | 1.0     | 0.5     | 0.0     | 1.5     | 0.0      | 0.5      | 0.0      | 0.5      | 1.0     | 1.0     | 0.0     | 2.0     | 2.0    | 0.0    | 8.5    | 10.5   | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5      | 0.0      | 0.0      | 0.5      | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 1.0      | 1.0      | 2.0      | 8.0      | 0.0      | 746307   | 177344   | 0        | 923651   | 0.0      | 0.0       | 2725714.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                         | L      | P      | P        | P        | P        | P       | Y        | Y        | Y        | Y        | N        | P               | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T3    | P          | Y        | Y       | Y        | Y       | N        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | Y        | Y      | Y       | 4        | 6      | 1       | 1025481600 | 1056931200 | 90.0   | 45.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 569605.0  | 15404.0 | 288.0   | 700.0    | 499888.0  | N      | 28144.0 | 2134.0  | 1289.0  | 20712.0  | 18401.0  | 195.0  | 4542.0   | 99.0     | 39.0     | 2.0      | 6.0      | 8.0      | 16.0     | 4.0    | 1.0    | 3.0    | 8.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 1.0      | 3.0      | 8.0      | 17.0     | 4.0      | 12.0     | 33.0     | 5.0      | 1.0      | 7.0      | 13.0     | 0.0      | 2.0      | 6.0      | 8.0      | 22.0     | 7.0      | 25.0     | 54.0     | 0.0      | 15.0     | 27.0     | 42.0     | 28.0     | 29.0     | 63.0     | 120.0    | 0.05    | 0.65    | 0.95    | 1.65    | 0.28     | 0.21     | 0.3      | 0.79     | 0.4     | 0.0     | 0.0     | 0.4     | 5.9    | 4.0    | 11.0   | 20.9   | 0.33   | 0.0    | 0.35   | 0.68   | 0.1    | 0.0    | 0.0    | 0.1    | 0.3      | 0.05     | 0.4      | 0.75     | 0.35     | 0.1      | 0.05     | 0.5      | 0.55     | 0.05     | 0.0      | 0.6      | 12.0     | 0.0      | 537198   | 0        | 0        | 537198   | 0.0      | 123523.0  | 5580811.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    | E      | G      | P        | P        | P        | P       | N        | Y        | N        | N        | N        | P               | Y        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | Y        | Y      | N        | Y        | Y       | T1    | P          | Y        | N       | N        | N       | N        | N        | N       | N        | N        | N        | N        | Y        | N      | P                                     | N        | Y      | Y       | 6        | 8      | 2       | 1025481600 | 1056931200 | 115.0  | 32.0     | 0.0      | 0.0      | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 1.0    | 0.0    | 2.0    | 794407.0  | 782.0   | 718.0   | 6018.0   | 4384451.0 | Y      | 40531.0 | 19527.0 | 987.0   | 92752.0  | 85000.0  | 500.0  | 8598.0   | 520.0    | 257.0    | 2.0      | 8.0      | 14.7     | 24.7     | 10.0   | 7.5    | 6.5    | 24.0   | 1.0    | 1.0    | 5.0    | 7.0    | 1.0     | 0.5     | 0.5     | 2.0     | 1.0     | 0.5     | 0.5     | 2.0     | 2.0      | 0.5      | 0.5      | 3.0      | 15.0     | 10.0     | 13.0     | 38.0     | 25.75    | 0.0      | 34.5     | 60.25    | 5.0      | 0.0      | 14.8     | 19.8     | 2.0      | 0.0      | 1.5      | 3.5      | 32.75    | 0.0      | 50.8     | 83.55    | 8.75     | 19.75    | 5.5      | 34.0     | 58.5     | 37.75    | 84.0     | 180.25   | 2.0     | 1.0     | 0.5     | 3.5     | 5.5      | 1.0      | 2.0      | 8.5      | 2.5     | 1.0     | 0.5     | 4.0     | 3.0    | 0.0    | 15.8   | 18.8   | 1.0    | 0.0    | 0.0    | 1.0    | 0.1    | 0.0    | 0.0    | 0.1    | 0.4      | 0.3      | 0.5      | 1.2      | 1.0      | 3.0      | 0.5      | 4.5      | 0.5      | 0.0      | 0.0      | 0.5      | 16.0     | 0.0      | 0        | 0        | 0        | 0        | 292399.0 | 8989557.0 | 35484453.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX                       | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM | E      | P      | P        | P        | E        | P       | N        | N        | N        | N        | N        | P               | N        | N        | Y        | N        | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | N      | N        | Y        | Y       | T1    | P          | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | Y      | Y       | 8        | 7      | 1       | 1025481600 | 1056931200 | 90.0   | 0.0      | 0.0      | 0.0      | 0.0     | 2.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 1.0    | 0.0    | 1.0    | 16721.0   | 49.0    | 137.0   | 7703.0   | 0.0       | N      | 507.0   | 165.0   | 0.0     | 413.0    | 297.0    | 183.0  | 2785.0   | 37.0     | 12.0     | 2.0      | 2.0      | 2.5      | 6.5      | 1.0    | 0.0    | 0.0    | 1.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 10.0     | 1.0      | 1.9      | 12.9     | 12.0     | 1.0      | 1.9      | 14.9     | 1.5      | 0.0      | 4.0      | 5.5      | 1.5      | 0.0      | 1.5      | 3.0      | 0.0      | 0.0      | 8.0      | 8.0      | 3.0      | 0.0      | 13.5     | 16.5     | 0.0      | 4.0      | 0.0      | 4.0      | 17.0     | 7.0      | 17.9     | 41.9     | 0.2     | 0.0     | 0.2     | 0.4     | 0.2      | 0.0      | 0.0      | 0.2      | 5.0     | 3.0     | 2.0     | 10.0    | 1.0    | 1.0    | 10.0   | 12.0   | 1.0    | 0.0    | 0.0    | 1.0    | 5.0    | 1.0    | 0.0    | 6.0    | 1.0      | 1.0      | 0.7      | 2.7      | 0.0      | 0.2      | 0.0      | 0.2      | 0.0      | 0.8      | 0.3      | 1.1      | 2.0      | 0.0      | 100000   | 0        | 0        | 100000   | 112105.0 | 409815.0  | 4550688.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | E      | P      | P        | P        | E        | P       | Y        | N        | Y        | Y        | Y        | ARTS COMMISSION | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    | P          | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 9        | 1      | 1       | 1025481600 | 1056931200 | 155.0  | 45.0     | 0.0      | 5.0      | 1.0     | 3.0      | 0.0      | 4.0      | 0.0     | 1.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 1.0    | 0.0    | 2.0    | 1113566.0 | 200.0   | 20.0    | 4327.0   | 1718597.0 | Y      | 1231.0  | 1232.0  | 93.0    | 69989.0  | 50976.0  | 171.0  | 2365.0   | 44.0     | 9.0      | 3.0      | 7.0      | 8.0      | 18.0     | 6.0    | 0.0    | 8.0    | 14.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 0.0      | 0.0      | 4.0      | 10.0     | 0.0      | 8.0      | 18.0     | 20.0     | 0.0      | 31.0     | 51.0     | 5.0      | 1.0      | 9.0      | 15.0     | 1.0      | 0.0      | 0.0      | 1.0      | 26.0     | 1.0      | 40.0     | 67.0     | 1.0      | 13.0     | 17.0     | 31.0     | 40.0     | 21.0     | 73.0     | 134.0    | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 6.0     | 8.0     | 1.0    | 0.0    | 11.0   | 12.0   | 2.0    | 0.0    | 0.0    | 2.0    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0      | 1.0      | 16.0     | 23.0     | 0        | 500000   | 0        | 500000   | 21485.0  | 38746.0   | 3483372.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | HTTP://DCLIBRARY.ORG                  | E      | B      | X        | P        | P        | P       | N        | N        | N        | N        | N        | P               | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N        | N      | Y        | Y        | Y       | T3    | P          | N        | N       | N        | N       | N        | N        | N       | N        | N        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 11       | 2      | 1       | 1033430400 | 1064880000 | 40.0   | 0.0      | 0.0      | 0.0      | 0.0     | 1.0      | 0.0      | 1.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0       | N      | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 43.0   | 1357.0   | 1.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 3.0      | 2.0      | 9.0      | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.25    | 0.0     | 0.0     | 0.25    | 0.25   | 1.0    | 0.0    | 1.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 1.0      | 0.0      | 1.25     | 0.1      | 0.1      | 0.0      | 0.2      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 0.0      | 0.0       | 563384.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         | E      | P      | P        | P        | S        | P       | N        | N        | N        | N        | N        | P               | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    | P          | N        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y        | Y        | Y      | WEB PAGE ACCESS                       | Y        | N      | N       | 10       | 2      | 1       | 1025481600 | 1056931200 | 47.0   | 47.0     | 4.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 888.0     | 0.0     | 0.0     | 55.0     | 22132.0   | N      | 590.0   | 46.0    | 3490.0  | 200.0    | 8500.0   | 55.0   | 653.0    | 67.0     | 30.0     | 2.0      | 1.0      | 1.0      | 4.0      | 2.0    | 0.5    | 0.0    | 2.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 1.0      | 0.0      | 4.0      | 5.0      | 1.5      | 0.0      | 6.5      | 1.0      | 1.0      | 1.0      | 3.0      | 1.0      | 2.0      | 0.0      | 3.0      | 0.0      | 0.5      | 4.0      | 4.5      | 2.0      | 3.5      | 5.0      | 10.5     | 0.0      | 0.0      | 0.0      | 0.0      | 9.0      | 6.0      | 6.0      | 21.0     | 0.1     | 0.34    | 0.0     | 0.44    | 0.35     | 0.33     | 0.0      | 0.68     | 3.3     | 2.0     | 0.0     | 5.3     | 1.0    | 1.0    | 2.0    | 4.0    | 0.1    | 0.75   | 0.0    | 0.85   | 0.0    | 0.0    | 0.0    | 0.0    | 0.12     | 0.75     | 0.2      | 1.07     | 0.02     | 0.0      | 0.0      | 0.02     | 1.98     | 3.3      | 0.8      | 6.08     | 35.0     | 0.0      | 0        | 258934   | 0        | 258934   | 0.0      | 0.0       | 817491.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | E      | P      | P        | P        | S        | P       | Y        | N        | N        | Y        | N        | P               | N        | N        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | OTH   | 10 MBPS    | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 12       | 5      | 2       | 1025481600 | 1056931200 | 152.0  | 51.0     | 3.0      | 6.0      | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 2.0     | 0.0     | 3.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 2.0    | 0.0    | 3.0    | 348036.0  | 474.0   | 14666.0 | 1323.0   | 357580.0  | Y      | 23544.0 | 21326.0 | 14159.0 | 112099.0 | 47153.0  | 19.0   | 1202.0   | 272.0    | 200.0    | 4.0      | 5.5      | 5.0      | 14.5     | 11.0   | 0.0    | 5.0    | 16.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 3.0      | 0.0      | 3.0      | 11.0     | 3.0      | 5.0      | 19.0     | 11.5     | 0.0      | 9.5      | 21.0     | 5.0      | 1.0      | 0.0      | 6.0      | 0.0      | 4.0      | 6.0      | 10.0     | 16.5     | 5.0      | 15.5     | 37.0     | 4.0      | 18.0     | 32.5     | 54.5     | 35.5     | 31.5     | 58.0     | 125.0    | 1.5     | 0.0     | 1.0     | 2.5     | 1.0      | 0.0      | 1.0      | 2.0      | 3.0     | 1.0     | 0.0     | 4.0     | 0.1    | 0.0    | 0.0    | 0.1    | 0.5    | 0.0    | 0.3    | 0.8    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.5      | 1.0      | 0.5      | 0.0      | 0.3      | 0.8      | 1.0      | 1.0      | 1.0      | 3.0      | 26.0     | 0.0      | 1514150  | 0        | 0        | 1514150  | 183930.0 | 469585.0  | 17019068.0 | 
```