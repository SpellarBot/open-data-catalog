# State Libraries Survey, FY 2002, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2002-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/vsm8-pjjt) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/vsm8-pjjt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/vsm8-pjjt/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | vsm8-pjjt |
| Name | State Libraries Survey, FY 2002, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2002, operations, workforce |
| Created | 2016-12-20T20:46:06Z |
| Publication Date | 2016-12-20T21:43:13Z |

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
series e:vsm8-pjjt d:2001-07-01T00:00:00.000Z t:appbygov=P t:stlacont=N t:physaddr="E. 12TH AND GRAND" t:mailzip=50319 t:netmount=Y t:mailaddr="E. 12TH AND GRAND" t:acccdrom=N t:ficsp=T3 t:stlaname="STATE LIBRARY OF IOWA" t:physzip4=233 t:acctlnet=Y t:webaddr=WWW.SILO.LIB.IA.US t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=Y t:ficspsp=P t:sthstmus=N t:mail_st=IA t:iacoop=N t:phys_st=IA t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:othallsp=P t:starchiv=N t:strecmng=N t:accoth=Y t:largerag=E t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:gencol=Y t:nettrstf=Y t:physcity="DES MOINES" t:mailcity="DES MOINES" t:pub_fips=19 t:inrefreq=Y t:elecoper=Y t:accoldb=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:physzip=50319 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=233 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:netequip=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:selectiv=Y t:stlegref=N t:indagy=P t:acswdbl=Y m:totalldc=1 m:totalldb=0 m:totallda=5 m:othersva=0 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=66711 m:othersvd=3 m:othersvc=2 m:lstecsva=2 m:lstecsvd=5 m:video=668 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=2 m:otstoutd=2 m:otstoutc=0 m:otstoutb=1 m:atevents=1026 m:lbstasea=0.1 m:otstouta=1 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0.25 m:lbstased=0.35 m:otherout=1 m:aendsed=4 m:lsothlsb=0 m:lsothlsa=3 m:admservd=6 m:admserva=2 m:litprseb=0 m:litprsea=0.1 m:admservc=4 m:admservb=0 m:lspubsvb=0 m:lspubsva=4 m:lspubsvd=8.5 m:litprsed=0.1 m:lspubsvc=4.5 m:litprsec=0 m:coroutd=2 m:coroutb=1 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=65 m:corouta=1 m:swdblica=14709 m:lstasea=0.4 m:recfrom=1909 m:ilssed=0 m:bphoutc=0 m:lstased=0.4 m:bphoutb=1 m:ilsseb=0 m:lstasec=0 m:bphouta=1 m:lstaseb=0 m:ilssec=0 m:ldschc=0.5 m:ldschb=0 m:bphoutd=2 m:ldscha=1 m:popu_st=643786 m:ldschd=1.5 m:paiw_oth=0 m:totalout=2 m:onsitmon=43 m:ilssea=0 m:readsch=29645 m:circ=3524 m:ldpuba=1 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=1.5 m:mainout=1 m:bkservol=111652 m:govdoc=572811 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=14709 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=42 m:ldothlba=3 m:totallsd=18.5 m:totallsc=9.5 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=3 m:markcomc=0 m:markcomb=0 m:gvemoutd=2 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=9 m:gvemoutb=1 m:gvemouta=1 m:provto=1109 m:markcomd=0 m:subscrip=1723 m:grantmon=135 m:bphsea=0.1 m:cyasea=0.5 m:cyaseb=0 m:bphsec=2 m:cyasec=0 m:reftrans=19910 m:bphseb=0 m:cyased=0.5 m:audio=114 m:gpouta=1 m:pagiw_lo=5 m:gpoutb=1 m:gpoutc=0 m:gpoutd=2 m:staidsea=0.4 m:bphsed=2.1 m:staidseb=0 m:staidsec=0 m:staidsed=0.4 m:lsothlsd=5 m:lsothlsc=2 m:totstafc=16.5 m:totstafd=33.5 m:totstafa=16 m:tothrs=85 m:totstafb=1

series e:vsm8-pjjt d:2001-07-01T00:00:00.000Z t:appbygov=P t:stlacont=N t:physaddr="300 COFFEE TREE ROAD" t:mailzip=40602 t:netmount=Y t:mailaddr="300 COFFEE TREE ROAD" t:acccdrom=N t:ficsp=T1 t:stlaname="KENTUCKY DEPARTMENT FOR LIBRARIES AND ARCHIVES" t:physzip4=537 t:acctlnet=N t:webaddr=WWW.KDLA.KY.GOV t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=N t:ficspsp=P t:sthstmus=N t:mail_st=KY t:iacoop=N t:phys_st=KY t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:othallsp=P t:starchiv=Y t:strecmng=Y t:accoth=N t:largerag=O t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:gencol=Y t:nettrstf=Y t:physcity=FRANKFORT t:mailcity=FRANKFORT t:pub_fips=21 t:inrefreq=Y t:elecoper=N t:accoldb=Y t:othagsp="EDUCATION, ARTS, & HUMANITIES CABINET" t:appbyoth=P t:elecplan=Y t:physzip=40601 t:electext=Y t:othswdbl=N t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=537 t:othaccsp=P t:netequip=N t:spcswdbl=N t:accwbcat=Y t:regional=N t:selectiv=Y t:stlegref=N t:indagy=P t:acswdbl=Y m:totalldc=1 m:totalldb=0 m:totallda=6 m:othersva=0 m:othersvb=0 m:totalldd=7 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=10014 m:othersvd=4.5 m:othersvc=4.5 m:lstecsva=5 m:lstecsvd=10 m:video=7901 m:lstecsvc=5 m:lstecsvb=0 m:aendsea=0 m:aendseb=0 m:aendsec=4.5 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=1215 m:lbstasea=2 m:otstouta=0 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0 m:lbstased=2 m:otherout=0 m:aendsed=4.5 m:lsothlsb=0 m:lsothlsa=4 m:admservd=13 m:admserva=2 m:litprseb=0 m:litprsea=1 m:admservc=9 m:admservb=2 m:lspubsvb=0 m:lspubsva=3 m:lspubsvd=12.25 m:litprsed=1 m:lspubsvc=9.25 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=2689000 m:coroutc=0 m:swdblicc=0 m:events=101 m:corouta=0 m:swdblica=0 m:lstasea=2 m:recfrom=3248 m:ilssed=0 m:bphoutc=0 m:lstased=6 m:bphoutb=0 m:ilsseb=0 m:lstasec=3 m:bphouta=1 m:lstaseb=1 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=4486508 m:ldschd=0 m:paiw_oth=0 m:totalout=1 m:onsitmon=2 m:ilssea=0 m:readsch=0 m:circ=4946 m:ldpuba=6 m:ldpubb=0 m:ldpubc=1 m:ldpubd=7 m:mainout=1 m:bkservol=174177 m:govdoc=1766 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=2689000 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=42 m:ldothlba=0 m:totallsd=31.25 m:totallsc=19.25 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=0 m:markcomb=1 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=12 m:gvemoutb=0 m:gvemouta=1 m:provto=10858 m:markcomd=1 m:subscrip=643 m:grantmon=78 m:bphsea=4 m:cyasea=1 m:cyaseb=0 m:bphsec=5 m:cyasec=0 m:reftrans=12685 m:bphseb=0 m:cyased=1 m:audio=0 m:gpouta=1 m:pagiw_lo=5 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=2 m:bphsed=9 m:staidseb=1 m:staidsec=2 m:staidsed=5 m:lsothlsd=9 m:lsothlsc=5 m:totstafc=33.75 m:totstafd=55.75 m:totstafa=20 m:tothrs=42 m:totstafb=2

series e:vsm8-pjjt d:2001-07-01T00:00:00.000Z t:appbygov=P t:stlacont=N t:physaddr="701 NORTH FOURTH STREET" t:mailzip=70821 t:netmount=Y t:mailaddr="P.O. BOX 131" t:acccdrom=N t:ficsp=OTH t:stlaname="STATE LIBRARY OF LOUISIANA" t:physzip4=5232 t:acctlnet=Y t:webaddr=WWW.STATE.LIB.LA.US t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=Y t:ficspsp="90-135 MBS" t:sthstmus=N t:mail_st=LA t:iacoop=N t:phys_st=LA t:elecbibl=Y t:netsub=N t:fddeplib=Y t:othallsp=P t:starchiv=N t:strecmng=N t:accoth=N t:largerag=C t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:gencol=Y t:nettrstf=Y t:physcity="BATON ROUGE" t:mailcity="BATON ROUGE" t:pub_fips=22 t:inrefreq=Y t:elecoper=N t:accoldb=Y t:othagsp=P t:appbyoth=P t:elecplan=N t:physzip=70802 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=131 t:othaccsp=P t:netequip=N t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:selectiv=N t:stlegref=N t:indagy=P t:acswdbl=Y m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=1 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=10949 m:othersvd=2 m:othersvc=0 m:lstecsva=5 m:lstecsvd=15 m:video=864 m:lstecsvc=10 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=0 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=1149 m:lbstasea=0.5 m:otstouta=0 m:lbstaseb=0 m:satsunce=0 m:lbstasec=0 m:lbstased=0.5 m:otherout=0 m:aendsed=2 m:lsothlsb=0 m:lsothlsa=0 m:admservd=12 m:admserva=2 m:litprseb=0 m:litprsea=0.5 m:admservc=7 m:admservb=3 m:lspubsvb=0 m:lspubsva=6 m:lspubsvd=19 m:litprsed=0.5 m:lspubsvc=13 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=50582 m:coroutc=0 m:swdblicc=0 m:events=113 m:corouta=0 m:swdblica=703251 m:lstasea=1 m:recfrom=549 m:ilssed=0.5 m:bphoutc=0 m:lstased=1.5 m:bphoutb=0 m:ilsseb=0 m:lstasec=0 m:bphouta=1 m:lstaseb=0.5 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=2710079 m:ldschd=0 m:paiw_oth=0 m:totalout=1 m:onsitmon=0 m:ilssea=0.5 m:readsch=0 m:circ=12437 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:mainout=1 m:bkservol=101440 m:govdoc=2092167 m:bkmobile=0 m:mon2frce=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=753833 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:tothrsce=43 m:ldothlba=0 m:totallsd=34 m:totallsc=23 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=1 m:markcomb=1 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=11 m:gvemoutb=0 m:gvemouta=1 m:provto=11583 m:markcomd=2 m:subscrip=1500 m:grantmon=0 m:bphsea=2 m:cyasea=0.5 m:cyaseb=0 m:bphsec=7.5 m:cyasec=0 m:reftrans=4919 m:bphseb=0 m:cyased=0.5 m:audio=767 m:gpouta=1 m:pagiw_lo=7 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=9.5 m:staidseb=0.5 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=32 m:totstafd=54 m:totstafa=18 m:tothrs=43 m:totstafb=4
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

entity e:vsm8-pjjt l:"State Libraries Survey, FY 2002, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/vsm8-pjjt

property e:vsm8-pjjt t:meta.view v:id=vsm8-pjjt v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2002, Part 1: Operations & Workforce" v:attribution=IMLS

property e:vsm8-pjjt t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:vsm8-pjjt t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:vsm8-pjjt t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:vsm8-pjjt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                       | physaddr                        | physcity       | phys_st | physzip | physzip4 | mailaddr                  | mailcity       | mail_st | mailzip | mailzip4 | webaddr                                         | branch | indagy | appbygov | appbyoth | largerag | othagsp                                     | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | ficsp | ficspsp    | inrefreq | accoldb | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | acccdrom | acctlnet | accwbcat | accoth | othaccsp                              | erateapp | iacoop | lpartnr | pub_fips | fystart   | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio   | video   | subscrip | govdoc    | gencol | circ    | provto  | recfrom | reftrans | libvists | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lstasea | lstaseb | lstasec | lstased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | markcoma | markcomb | markcomc | markcomd | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | readsch  | adfamlit   | popu_st    | 
| ============================================== | =============================== | ============== | ======= | ======= | ======== | ========================= | ============== | ======= | ======= | ======== | =============================================== | ====== | ====== | ======== | ======== | ======== | =========================================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ===== | ========== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ===================================== | ======== | ====== | ======= | ======== | ========= | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======= | ======= | ======== | ========= | ====== | ======= | ======= | ======= | ======== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========== | ========== | 
| STATE LIBRARY OF IOWA                          | E. 12TH AND GRAND               | DES MOINES     | IA      | 50319   | 233      | E. 12TH AND GRAND         | DES MOINES     | IA      | 50319   | 233      | WWW.SILO.LIB.IA.US                              | E      | P      | P        | P        | E        | P                                           | N        | N        | N        | N        | N        | P        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T3    | P          | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE | N        | N      | N       | 19       | 993945600 | 1025395200 | 85.0   | 42.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 0.0     | 2.0     | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 111652.0  | 114.0   | 668.0   | 1723.0   | 572811.0  | Y      | 3524.0  | 1109.0  | 1909.0  | 19910.0  | 66711.0  | 65.0   | 1026.0   | 135.0    | 43.0     | 2.0      | 0.0      | 4.0      | 6.0      | 1.0    | 0.0    | 0.5    | 1.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 0.0      | 3.0      | 5.0      | 0.0      | 1.0      | 6.0      | 4.0      | 0.0      | 4.5      | 8.5      | 2.0      | 0.0      | 3.0      | 5.0      | 3.0      | 0.0      | 2.0      | 5.0      | 9.0      | 0.0      | 9.5      | 18.5     | 0.0      | 1.0      | 2.0      | 3.0      | 16.0     | 1.0      | 16.5     | 33.5     | 0.4     | 0.0     | 0.0     | 0.4     | 0.4      | 0.0      | 0.0      | 0.4      | 1.0     | 1.0     | 2.0     | 4.0     | 0.1    | 0.0    | 2.0    | 2.1    | 0.5    | 0.0    | 0.0    | 0.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.1      | 0.0      | 0.25     | 0.35     | 0.1      | 0.0      | 0.0      | 0.1      | 0.0      | 0.0      | 0.0      | 0.0      | 5.0      | 0.0      | 14709    | 0        | 0        | 14709    | 29645.0  | 0.0        | 643786.0   | 
| KENTUCKY DEPARTMENT FOR LIBRARIES AND ARCHIVES | 300 COFFEE TREE ROAD            | FRANKFORT      | KY      | 40601   | 537      | 300 COFFEE TREE ROAD      | FRANKFORT      | KY      | 40602   | 537      | WWW.KDLA.KY.GOV                                 | E      | P      | P        | P        | O        | EDUCATION, ARTS, & HUMANITIES CABINET       | Y        | N        | N        | Y        | N        | P        | N        | Y        | N        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y      | N        | Y        | Y       | T1    | P          | Y        | Y       | Y        | Y       | Y        | N        | Y       | N        | Y        | N        | N        | Y        | N      | P                                     | N        | N      | N       | 21       | 993945600 | 1025395200 | 42.0   | 42.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 174177.0  | 0.0     | 7901.0  | 643.0    | 1766.0    | Y      | 4946.0  | 10858.0 | 3248.0  | 12685.0  | 10014.0  | 101.0  | 1215.0   | 78.0     | 2.0      | 2.0      | 2.0      | 9.0      | 13.0     | 6.0    | 0.0    | 1.0    | 7.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 0.0      | 1.0      | 7.0      | 3.0      | 0.0      | 9.25     | 12.25    | 5.0      | 0.0      | 5.0      | 10.0     | 4.0      | 0.0      | 5.0      | 9.0      | 12.0     | 0.0      | 19.25    | 31.25    | 0.0      | 0.0      | 4.5      | 4.5      | 20.0     | 2.0      | 33.75    | 55.75    | 2.0     | 1.0     | 3.0     | 6.0     | 2.0      | 1.0      | 2.0      | 5.0      | 0.0     | 0.0     | 4.5     | 4.5     | 4.0    | 0.0    | 5.0    | 9.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 2.0      | 0.0      | 0.0      | 2.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0      | 1.0      | 5.0      | 0.0      | 0        | 2689000  | 0        | 2689000  | 0.0      | 0.0        | 4486508.0  | 
| STATE LIBRARY OF LOUISIANA                     | 701 NORTH FOURTH STREET         | BATON ROUGE    | LA      | 70802   | 5232     | P.O. BOX 131              | BATON ROUGE    | LA      | 70821   | 131      | WWW.STATE.LIB.LA.US                             | E      | P      | P        | P        | C        | P                                           | N        | N        | N        | N        | N        | P        | N        | Y        | Y        | Y        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | N      | N        | Y        | Y       | OTH   | 90-135 MBS | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | N        | N      | N       | 22       | 993945600 | 1025395200 | 43.0   | 43.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 101440.0  | 767.0   | 864.0   | 1500.0   | 2092167.0 | Y      | 12437.0 | 11583.0 | 549.0   | 4919.0   | 10949.0  | 113.0  | 1149.0   | 0.0      | 0.0      | 2.0      | 3.0      | 7.0      | 12.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 6.0      | 0.0      | 13.0     | 19.0     | 5.0      | 0.0      | 10.0     | 15.0     | 0.0      | 0.0      | 0.0      | 0.0      | 11.0     | 0.0      | 23.0     | 34.0     | 1.0      | 1.0      | 0.0      | 2.0      | 18.0     | 4.0      | 32.0     | 54.0     | 1.0     | 0.5     | 0.0     | 1.5     | 0.0      | 0.5      | 0.0      | 0.5      | 1.0     | 1.0     | 0.0     | 2.0     | 2.0    | 0.0    | 7.5    | 9.5    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5      | 0.0      | 0.0      | 0.5      | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 1.0      | 1.0      | 2.0      | 7.0      | 0.0      | 703251   | 50582    | 0        | 753833   | 0.0      | 0.0        | 2710079.0  | 
| MASSACHUSETTS BOARD OF LIBRARY COMMISSIONERS   | 648 BEACON STREET               | BOSTON         | MA      | 2215    | 2002     | 648 BEACON STREET         | BOSTON         | MA      | 2215    | 2002     | WWW.MLIN.LIB.MA.US                              | E      | G      | P        | P        | P        | P                                           | N        | N        | N        | N        | N        | P        | Y        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | OTH   | 100 MBPS   | Y        | Y       | Y        | Y       | N        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | Y        | Y      | Y       | 25       | 993945600 | 1025395200 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 493673.0  | 15299.0 | 280.0   | 756.0    | 499888.0  | N      | 19559.0 | 1822.0  | 1435.0  | 24372.0  | 10872.0  | 165.0  | 4246.0   | 118.0    | 25.0     | 2.0      | 2.0      | 7.0      | 11.0     | 4.0    | 0.75   | 3.0    | 7.75   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.75     | 3.0      | 7.75     | 21.0     | 4.0      | 12.0     | 37.0     | 9.0      | 3.0      | 11.0     | 23.0     | 0.0      | 2.0      | 6.0      | 8.0      | 30.0     | 9.0      | 29.0     | 68.0     | 0.0      | 17.0     | 38.0     | 55.0     | 36.0     | 28.75    | 77.0     | 141.75   | 0.05    | 0.95    | 0.95    | 1.95    | 0.28     | 0.01     | 0.3      | 0.59     | 0.4     | 1.0     | 5.0     | 6.4     | 6.0    | 3.0    | 13.0   | 22.0   | 0.33   | 0.0    | 0.1    | 0.43   | 0.0    | 0.0    | 0.0    | 0.0    | 0.31     | 0.0      | 0.4      | 0.71     | 0.15     | 0.05     | 0.05     | 0.25     | 0.7      | 0.05     | 0.0      | 0.75     | 17.0     | 0.0      | 390696   | 0        | 0        | 390696   | 0.0      | 636303.0   | 5456453.0  | 
| DIVISION OF LIBRARY DEVELOPMENT AND SERVICES   | 200 WEST BALTIMORE STREET       | BALTIMORE      | MD      | 21201   | 2595     | 200 WEST BALTIMORE STREET | BALTIMORE      | MD      | 21201   | 2595     | WWW.MARYLANDPUBLICSCHOOLS.ORG/DIVISIONS/LDS     | E      | P      | P        | P        | E        | P                                           | N        | N        | N        | N        | N        | P        | Y        | N        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | Y        | Y      | N        | Y        | Y       | T1    | P          | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N        | Y        | N      | P                                     | N        | Y      | Y       | 24       | 993945600 | 1025395200 | 45.0   | 0.0      | 0.0      | 0.0      | 0.0     | 1.0      | 0.0      | 1.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 786244.0  | 680.0   | 558.0   | 7347.0   | 4325512.0 | Y      | 50670.0 | 14180.0 | 933.0   | 68098.0  | 93865.0  | 500.0  | 17000.0  | 439.0    | 247.0    | 3.0      | 10.0     | 24.0     | 37.0     | 10.0   | 8.5    | 8.5    | 27.0   | 2.0    | 1.0    | 1.0    | 4.0    | 2.0     | 0.5     | 0.5     | 3.0     | 2.0     | 0.5     | 0.5     | 3.0     | 2.0      | 0.5      | 0.5      | 3.0      | 18.0     | 11.0     | 11.0     | 40.0     | 32.0     | 28.0     | 23.0     | 83.0     | 6.0      | 10.0     | 12.0     | 28.0     | 2.0      | 3.0      | 2.5      | 7.5      | 40.0     | 41.0     | 37.5     | 118.5    | 11.0     | 31.0     | 5.0      | 47.0     | 72.0     | 93.0     | 77.5     | 242.5    | 2.0     | 1.0     | 0.5     | 3.5     | 5.5      | 2.0      | 3.0      | 10.5     | 3.5     | 1.0     | 1.0     | 5.5     | 4.0    | 0.0    | 21.0   | 25.0   | 1.0    | 0.0    | 0.0    | 1.0    | 0.1    | 0.0    | 0.0    | 0.1    | 0.4      | 0.3      | 1.0      | 1.7      | 1.0      | 4.0      | 1.0      | 6.0      | 0.5      | 0.0      | 0.0      | 0.5      | 18.0     | 0.0      | 0        | 0        | 0        | 0        | 70000.0  | 11338940.0 | 35116033.0 | 
| IDAHO STATE LIBRARY                            | 325 WEST STATE STREET           | BOISE          | ID      | 83702   | 6072     | 325 WEST STATE STREET     | BOISE          | ID      | 83702   | 6072     | WWW.LILI.ORG/ISL                                | E      | P      | P        | P        | O        | OFFICE OF THE STATE BOARD OF EDUCATION      | N        | N        | N        | N        | N        | P        | N        | N        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | N        | Y        | Y       | T1    | P          | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | Y        | Y        | N      | P                                     | Y        | N      | N       | 16       | 993945600 | 1025395200 | 40.0   | 40.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 16467.0   | 32.0    | 126.0   | 7742.0   | 0.0       | N      | 563.0   | 182.0   | 0.0     | 360.0    | 317.0    | 167.0  | 2532.0   | 43.0     | 6.0      | 3.0      | 2.0      | 2.5      | 7.5      | 1.0    | 0.0    | 0.0    | 1.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 8.75     | 1.0      | 2.0      | 11.75    | 10.75    | 1.0      | 2.0      | 13.75    | 2.5      | 0.0      | 3.0      | 5.5      | 1.5      | 0.0      | 1.5      | 3.0      | 0.0      | 0.0      | 7.0      | 7.0      | 4.0      | 0.0      | 11.5     | 15.5     | 0.0      | 4.0      | 0.0      | 4.0      | 17.75    | 7.0      | 16.0     | 40.75    | 0.2     | 0.0     | 0.2     | 0.4     | 0.2      | 0.0      | 0.2      | 0.4      | 4.0     | 3.0     | 2.0     | 9.0     | 2.0    | 1.0    | 8.0    | 11.0   | 1.0    | 0.0    | 0.0    | 1.0    | 4.5    | 1.0    | 0.0    | 5.5    | 1.0      | 1.0      | 0.7      | 2.7      | 0.0      | 0.2      | 0.0      | 0.2      | 0.0      | 0.8      | 0.3      | 1.1      | 2.0      | 0.0      | 0        | 0        | 0        | 0        | 19998.0  | 38742.0    | 4506542.0  | 
| ILLINOIS STATE LIBRARY                         | 300 SOUTH SECOND                | SPRINGFIELD    | IL      | 62701   | 1796     | 300 SOUTH SECOND          | SPRINGFIELD    | IL      | 62701   | 1796     | WWW.CYBERDRIVEILLINOIS.COM/LIBRARY/ISL/ISL.HTML | E      | P      | P        | P        | S        | P                                           | N        | N        | N        | N        | N        | P        | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    | P          | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 17       | 993945600 | 1025395200 | 126.0  | 42.0     | 0.0      | 0.0      | 1.0     | 2.0      | 0.0      | 3.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 0.0    | 0.0    | 1.0    | 1093080.0 | 200.0   | 20.0    | 4630.0   | 1711087.0 | Y      | 1498.0  | 1194.0  | 127.0   | 60886.0  | 46140.0  | 151.0  | 1783.0   | 55.0     | 13.0     | 3.0      | 5.0      | 5.0      | 13.0     | 7.0    | 0.0    | 7.0    | 14.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 1.0      | 4.0      | 10.0     | 0.0      | 8.0      | 18.0     | 22.0     | 0.0      | 19.0     | 41.0     | 5.0      | 3.0      | 5.0      | 13.0     | 2.0      | 0.0      | 2.0      | 4.0      | 29.0     | 3.0      | 26.0     | 58.0     | 3.0      | 17.0     | 19.0     | 39.0     | 45.0     | 25.0     | 58.0     | 128.0    | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 3.0     | 0.0     | 1.0     | 4.0     | 2.0    | 0.0    | 9.0    | 11.0   | 2.0    | 0.0    | 0.0    | 2.0    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 5.0      | 22.0     | 60000    | 2000000  | 0        | 2060000  | 57748.0  | 20877.0    | 3460503.0  | 
| MINNESOTA LIBRARY DEVELOPMENT AND SERVICES     | 1500 HIGHWAY 36 WEST            | ROSEVILLE      | MN      | 55113   | 4266     | 1500 HIGHWAY 36 WEST      | ROSEVILLE      | MN      | 55113   | 4266     | CFL.STATE.MN.US/LIBRARY                         | E      | P      | P        | P        | O        | DEPARTMENT OF CHILDREN, FAMILIES & LEARNING | N        | N        | N        | N        | N        | P        | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N        | N      | Y        | Y        | Y       | T3    | P          | N        | N       | N        | N       | N        | N        | N       | N        | N        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 27       | 993945600 | 1025395200 | 96.0   | 49.0     | 4.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0       | N      | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 47.0   | 1255.0   | 1.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 3.0      | 2.0      | 9.0      | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.25    | 0.0     | 0.0     | 0.25    | 0.25   | 1.0    | 0.0    | 1.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 1.0      | 0.0      | 1.25     | 0.1      | 0.1      | 0.0      | 0.2      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 0.0      | 0.0        | 570898.0   | 
| MISSOURI STATE LIBRARY                         | 600 WEST MAIN STREET, 2ND FLOOR | JEFFERSON CITY | MO      | 65102   | 387      | PO BOX 387                | JEFFERSON CITY | MO      | 65102   | 387      | WWW.SOS.STATE.MO.US/LIBRARY/                    | E      | P      | P        | P        | S        | P                                           | N        | N        | N        | N        | N        | P        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    | P          | N        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y        | Y        | Y      | WEB PAGE ACCESS                       | Y        | N      | N       | 29       | 993945600 | 1025395200 | 47.0   | 47.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 1440.0    | 0.0     | 0.0     | 50.0     | 21551.0   | N      | 62.0    | 48135.0 | 27.0    | 21.0     | 5200.0   | 41.0   | 663.0    | 44.0     | 28.0     | 2.0      | 1.0      | 1.0      | 4.0      | 2.0    | 0.5    | 0.0    | 2.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 1.0      | 0.0      | 5.0      | 6.0      | 1.5      | 0.0      | 7.5      | 1.0      | 1.0      | 1.0      | 3.0      | 1.0      | 2.0      | 0.0      | 3.0      | 0.0      | 0.5      | 4.0      | 4.5      | 2.0      | 3.5      | 5.0      | 10.5     | 0.0      | 0.0      | 0.0      | 0.0      | 10.0     | 6.0      | 6.0      | 22.0     | 0.5     | 0.34    | 0.0     | 0.84    | 0.35     | 0.33     | 0.0      | 0.68     | 2.3     | 2.0     | 0.0     | 4.3     | 1.0    | 1.0    | 2.0    | 4.0    | 0.1    | 0.5    | 0.0    | 0.6    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.53     | 0.2      | 1.23     | 0.2      | 0.0      | 0.0      | 0.2      | 0.5      | 0.5      | 0.0      | 1.0      | 17.0     | 0.0      | 0        | 367280   | 0        | 367280   | 0.0      | 0.0        | 807385.0   | 
| MISSISSIPPI LIBRARY COMMISSION                 | 1221 ELLIS AVENUE               | JACKSON        | MS      | 39209   | 7328     | 1221 ELLIS AVENUE         | JACKSON        | MS      | 39209   | 7328     | MLC.LIB.MS.US                                   | E      | B      | X        | P        | P        | P                                           | N        | N        | N        | N        | N        | P        | N        | Y        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T3    | P          | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | N        | N        | N        | Y        | N      | P                                     | Y        | N      | N       | 28       | 993945600 | 1025395200 | 48.0   | 48.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 338087.0  | 474.0   | 14599.0 | 1358.0   | 357580.0  | Y      | 61328.0 | 19294.0 | 39653.0 | 109861.0 | 52071.0  | 39.0   | 1772.0   | 213.0    | 213.0    | 2.0      | 3.0      | 9.0      | 14.0     | 13.0   | 0.0    | 6.0    | 19.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 13.0     | 0.0      | 6.0      | 19.0     | 10.0     | 0.0      | 11.0     | 21.0     | 10.0     | 0.0      | 6.0      | 16.0     | 0.0      | 0.0      | 0.0      | 0.0      | 20.0     | 0.0      | 17.0     | 37.0     | 0.0      | 22.0     | 28.0     | 50.0     | 35.0     | 25.0     | 60.0     | 120.0    | 1.5     | 0.0     | 1.0     | 2.5     | 1.5      | 0.0      | 1.0      | 2.5      | 3.0     | 1.0     | 0.0     | 4.0     | 0.1    | 0.0    | 0.0    | 0.1    | 0.5    | 0.0    | 0.3    | 0.8    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.5      | 1.0      | 0.5      | 0.0      | 0.3      | 0.8      | 0.0      | 1.0      | 0.0      | 1.0      | 26.0     | 0.0      | 265310   | 0        | 0        | 265310   | 336649.0 | 578681.0   | 16713149.0 | 
```