# State Libraries Survey, FY 1997, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1997-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/97tr-cf5g) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/97tr-cf5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/97tr-cf5g/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 97tr-cf5g |
| Name | State Libraries Survey, FY 1997, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1997, operations, workforce |
| Created | 2016-12-20T22:44:46Z |
| Publication Date | 2016-12-20T22:51:49Z |

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
| Yes      | series tag     | judbran    | Judicial branch                                            | text      | text        |
| Yes      | series tag     | legbran    | Legislative branch                                         | text      | text        |
| Yes      | series tag     | execbran   | Executive branch                                           | text      | text        |
| Yes      | series tag     | indepag    | Independent agency exec br                                 | text      | text        |
| Yes      | series tag     | governor   | Reports to Governor                                        | text      | text        |
| Yes      | series tag     | boardcom   | Reports to board/commission                                | text      | text        |
| Yes      | series tag     | appbygov   | Appointed by governor [X]Yes/[P]n/a                        | text      | text        |
| Yes      | series tag     | appbyoth   | Appointed by other official [X]Yes/[P]n/a                  | text      | text        |
| Yes      | series tag     | exoffmem   | Ex-officio members                                         | text      | text        |
| Yes      | series tag     | electmem   | Elected members                                            | text      | text        |
| Yes      | series tag     | largerag   | Part of Dept of [E]duc/[C]ult Resrc/[S]tate/[O]ther/[P]n/a | text      | text        |
| Yes      | series tag     | depteduc   | Dept of education                                          | text      | text        |
| Yes      | series tag     | deptcult   | Dept of cultural resources                                 | text      | text        |
| Yes      | series tag     | deptstat   | Dept of state                                              | text      | text        |
| Yes      | series tag     | otherag    | Other agency                                               | text      | text        |
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
| Yes      | series tag     | nettrain   | Internet access support thru training                      | text      | text        |
| Yes      | series tag     | netsub     | Internet access support thru direct funding                | text      | text        |
| Yes      | series tag     | netequip   | Intenet access support thru prov equip                     | text      | text        |
| Yes      | series tag     | netmount   | Internet access support thru online resrcs                 | text      | text        |
| Yes      | series tag     | netgoph    | Internet access support thru website/server/list mgmt      | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                                            | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy                         | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy                           | date      | date        |
| Yes      | numeric metric | tothrswk   | Hours open typical week                                    | number    | number      |
| Yes      | numeric metric | mon2fri    | Hours open M-F after 5pm                                   | number    | number      |
| Yes      | numeric metric | sat2sun    | Hours open Sat & Sun                                       | number    | number      |
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
| Yes      | series tag     | walkin     | Walk-in                                                    | text      | text        |
| Yes      | series tag     | referral   | Referral                                                   | text      | text        |
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
| Yes      | numeric metric | lscasea    | Admin of LSCA grants ALA-MLS                               | number    | number      |
| Yes      | numeric metric | lscaseb    | Admin of LSCA grants professional                          | number    | number      |
| Yes      | numeric metric | lscasec    | Admin of LSCA grants other                                 | number    | number      |
| Yes      | numeric metric | lscased    | Admin of LSCA grants TOTAL                                 | number    | number      |
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
| Yes      | numeric metric | readsch    | Grants to assist/sch readiness                             | money     | money       |
| Yes      | numeric metric | adlit      | Grants to assist/adult literacy                            | money     | money       |
| Yes      | numeric metric | lllrng     | Grants to assist/lifelong learning                         | money     | money       |
| Yes      | numeric metric | period_e   | Population estimate NCES                                   | number    | number      |
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
series e:97tr-cf5g d:1996-07-01T00:00:00.000Z t:gencol=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:pub_fips=2 t:referral=Y t:stlacont=Y t:physaddr="333 WILLOUGHBY AVENUE" t:elecoper=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:elecplan=Y t:physzip4=571.0 t:othallop=N t:physzip=99811 t:netgoph=Y t:electext=Y t:stdeplib=Y t:stlahost=N t:sthstmus=Y t:mail_st=AK t:elecbibl=Y t:phys_st=AK t:mailzip4=571.0 t:walkin=Y t:netsub=Y t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:starchiv=Y t:regional=N t:strecmng=Y t:depteduc=X t:largerag=X t:stlegref=N t:selectiv=Y m:lllrng=0 m:totalldc=1 m:totalldb=0 m:totallda=5 m:othersva=0 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=78067 m:othersvd=3 m:othersvc=2 m:lstecsva=3 m:lstecsvd=6 m:video=399 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=2 m:aendseb=1 m:otstoutd=0 m:aendsec=2 m:otstoutc=0 m:atevents=550 m:otstoutb=0 m:lbstasea=0.5 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.5 m:mon2fri=0 m:otherout=1 m:aendsed=5 m:lsothlsb=0 m:admservd=6 m:lsothlsa=3 m:admserva=2 m:litprseb=0 m:litprsea=0 m:admservc=4 m:admservb=0 m:lspubsvb=0 m:lspubsva=5 m:lspubsvd=11 m:lscaseb=0 m:litprsed=0 m:lspubsvc=6 m:lscasea=0.4 m:litprsec=0 m:lscased=0.4 m:lscasec=0 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=30 m:corouta=0 m:recfrom=1531 m:bphoutc=0 m:ilssed=0 m:bphoutb=1 m:bphouta=0 m:ilsseb=0 m:ilssec=0 m:ldschc=0.5 m:ldschb=0 m:bphoutd=1 m:ldscha=1 m:ldschd=1.5 m:totalout=2 m:onsitmon=10 m:ilssea=0 m:readsch=0 m:circ=4724 m:tothrswk=40 m:ldpuba=1 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=1.5 m:mainout=1 m:bkservol=103477 m:govdoc=80000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=607800 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=3 m:totallsd=23 m:ldothlbb=0 m:totallsc=12 m:ldothlbc=0 m:ldothlbd=3 m:gvemoutd=1 m:totallsb=0 m:gvemoutc=0 m:totallsa=11 m:gvemoutb=0 m:gvemouta=1 m:provto=1591 m:subscrip=1469 m:grantmon=115 m:bphsea=0.1 m:cyasea=0 m:cyaseb=0 m:reftrans=15117 m:bphsec=2 m:cyasec=0 m:bphseb=0 m:cyased=0 m:audio=111 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.5 m:staidseb=0 m:bphsed=2.1 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=6 m:lsothlsc=3 m:totstafc=19 m:totstafd=38 m:totstafa=18 m:totstafb=1

series e:97tr-cf5g d:1996-10-01T00:00:00.000Z t:appbygov=X t:gencol=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:pub_fips=1 t:referral=Y t:stlacont=N t:physaddr="6030 MONTICELLO DRIVE" t:elecoper=N t:mailzip=36130 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:elecplan=Y t:physzip4=1.0 t:othallop=N t:physzip=36117 t:netgoph=Y t:electext=N t:boardcom=X t:stdeplib=N t:sthstmus=N t:stlahost=N t:mail_st=AL t:phys_st=AL t:elecbibl=Y t:mailzip4=1.0 t:walkin=Y t:netsub=Y t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=N t:indepag=X t:starchiv=N t:regional=N t:strecmng=N t:stlegref=N t:selectiv=Y m:lllrng=0 m:totalldc=1 m:totalldb=0 m:totallda=7 m:othersva=3 m:othersvb=0 m:totalldd=8 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=2489 m:othersvd=11 m:othersvc=8 m:lstecsva=1 m:lstecsvd=4 m:video=3703 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=1 m:aendseb=2 m:otstoutd=0 m:aendsec=1 m:otstoutc=0 m:atevents=654 m:otstoutb=0 m:lbstasea=0 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0 m:mon2fri=0 m:otherout=0 m:aendsed=4 m:lsothlsb=0 m:admservd=17 m:lsothlsa=0 m:admserva=1 m:litprseb=0 m:litprsea=0 m:admservc=12 m:admservb=4 m:lspubsvb=0 m:lspubsva=12.75 m:lspubsvd=23.25 m:lscaseb=1 m:litprsed=0 m:lspubsvc=10.5 m:lscasea=1 m:litprsec=0 m:lscased=4 m:lscasec=2 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=29 m:corouta=0 m:recfrom=544 m:bphoutc=0 m:ilssed=0 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:ldschd=0 m:totalout=1 m:onsitmon=4 m:ilssea=0 m:readsch=0 m:circ=7003 m:tothrswk=45 m:ldpuba=7 m:ldpubb=0 m:ldpubc=1 m:ldpubd=8 m:mainout=1 m:bkservol=167494 m:govdoc=3000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=4137511 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=27.25 m:ldothlbb=0 m:totallsc=13.5 m:ldothlbc=0 m:ldothlbd=0 m:gvemoutd=1 m:totallsb=0 m:gvemoutc=0 m:totallsa=13.75 m:gvemoutb=0 m:gvemouta=1 m:provto=16705 m:subscrip=1246 m:grantmon=439 m:bphsea=3 m:cyasea=1 m:cyaseb=0 m:reftrans=3975 m:bphsec=7 m:cyasec=0 m:bphseb=0 m:cyased=1 m:audio=238000 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=1 m:staidseb=1 m:bphsed=10 m:staidsec=2 m:staidsed=4 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=34.5 m:totstafd=63.25 m:totstafa=24.75 m:totstafb=4

series e:97tr-cf5g d:1996-07-01T00:00:00.000Z t:gencol=Y t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:pub_fips=5 t:referral=Y t:stlacont=N t:physaddr="ONE CAPITOL MALL" t:elecoper=Y t:mailzip=72201 t:netmount=N t:mailaddr="ONE CAPITOL MALL" t:stlaname="ARKANSAS STATE LIBRARY" t:elecplan=Y t:physzip4=1081.0 t:othallop=N t:physzip=72201 t:netgoph=N t:electext=N t:stdeplib=Y t:stlahost=N t:sthstmus=N t:mail_st=AR t:elecbibl=Y t:phys_st=AR t:mailzip4=1081.0 t:walkin=Y t:netsub=Y t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:starchiv=N t:regional=Y t:strecmng=N t:depteduc=X t:largerag=X t:stlegref=N t:selectiv=N m:lllrng=0 m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=1 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=11393 m:othersvd=2 m:othersvc=0 m:lstecsva=6 m:lstecsvd=24 m:video=17098 m:lstecsvc=14 m:lstecsvb=4 m:aendsea=1 m:aendseb=1 m:otstoutd=0 m:aendsec=0 m:otstoutc=0 m:atevents=1030 m:otstoutb=0 m:lbstasea=1 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=1 m:mon2fri=0 m:otherout=0 m:aendsed=2 m:lsothlsb=0 m:admservd=16 m:lsothlsa=4 m:admserva=3 m:litprseb=0 m:litprsea=0 m:admservc=8 m:admservb=5 m:lspubsvb=2 m:lspubsva=4 m:lspubsvd=11 m:lscaseb=0 m:litprsed=0 m:lspubsvc=5 m:lscasea=1 m:litprsec=0 m:lscased=1 m:lscasec=0 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=19 m:corouta=0 m:recfrom=272 m:bphoutc=0 m:ilssed=0.5 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:ldschd=0 m:totalout=1 m:onsitmon=18 m:ilssea=0.5 m:readsch=0 m:circ=12871 m:tothrswk=45 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:mainout=1 m:bkservol=96479 m:govdoc=1732322 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=2264510 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=44.5 m:ldothlbb=0 m:totallsc=24.5 m:ldothlbc=0 m:ldothlbd=0 m:gvemoutd=1 m:totallsb=6 m:gvemoutc=0 m:totallsa=14 m:gvemoutb=0 m:gvemouta=1 m:provto=15891 m:subscrip=963 m:grantmon=20 m:bphsea=4 m:cyasea=0.5 m:cyaseb=0 m:reftrans=6074 m:bphsec=6.5 m:cyasec=0 m:bphseb=0 m:cyased=0.5 m:audio=0 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:staidseb=0.25 m:bphsed=10.5 m:staidsec=0 m:staidsed=0.25 m:lsothlsd=9.5 m:lsothlsc=5.5 m:totstafc=34.5 m:totstafd=68.5 m:totstafa=22 m:totstafb=12
```

## Meta Commands

```ls
metric m:tothrswk p:float l:"Hours open typical week" t:dataTypeName=number

metric m:mon2fri p:float l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:sat2sun p:float l:"Hours open Sat & Sun" t:dataTypeName=number

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

metric m:lscasea p:float l:"Admin of LSCA grants ALA-MLS" t:dataTypeName=number

metric m:lscaseb p:float l:"Admin of LSCA grants professional" t:dataTypeName=number

metric m:lscasec p:float l:"Admin of LSCA grants other" t:dataTypeName=number

metric m:lscased p:float l:"Admin of LSCA grants TOTAL" t:dataTypeName=number

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

metric m:readsch p:double l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adlit p:double l:"Grants to assist/adult literacy" t:dataTypeName=money

metric m:lllrng p:double l:"Grants to assist/lifelong learning" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:97tr-cf5g l:"State Libraries Survey, FY 1997, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/97tr-cf5g

property e:97tr-cf5g t:meta.view v:id=97tr-cf5g v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1997, Part 1: Operations & Workforce" v:attribution=IMLS

property e:97tr-cf5g t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:97tr-cf5g t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:97tr-cf5g t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:97tr-cf5g t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | judbran | legbran | execbran | indepag | governor | boardcom | appbygov | appbyoth | exoffmem | electmem | largerag | depteduc | deptcult | deptstat | otherag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp        | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | nettrain | netsub | netequip | netmount | netgoph | pub_fips | fystart   | fyend     | tothrswk | mon2fri | sat2sun | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol | audio    | video   | subscrip | govdoc    | gencol | circ    | provto  | recfrom | reftrans | libvists | walkin | referral | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lscasea | lscaseb | lscasec | lscased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | readsch   | adlit     | lllrng    | period_e   | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =============== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ========= | ========= | ======== | ======= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ======== | ======== | ======= | ======== | ========= | ====== | ======= | ======= | ======= | ======== | ======== | ====== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | N        |                 | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 2        | 836179200 | 867628800 | 40.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 103477.0 | 111.0    | 399.0   | 1469.0   | 80000.0   | Y      | 4724.0  | 1591.0  | 1531.0  | 15117.0  | 78067.0  | Y      | Y        | 30.0   | 550.0    | 115.0    | 10.0     | 2.0      | 0.0      | 4.0      | 6.0      | 1.0    | 0.0    | 0.5    | 1.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 0.0      | 3.0      | 5.0      | 0.0      | 1.0      | 6.0      | 5.0      | 0.0      | 6.0      | 11.0     | 3.0      | 0.0      | 3.0      | 6.0      | 3.0      | 0.0      | 3.0      | 6.0      | 11.0     | 0.0      | 12.0     | 23.0     | 0.0      | 1.0      | 2.0      | 3.0      | 18.0     | 1.0      | 19.0     | 38.0     | 0.4     | 0.0     | 0.0     | 0.4     | 0.5      | 0.0      | 0.0      | 0.5      | 2.0     | 1.0     | 2.0     | 5.0     | 0.1    | 0.0    | 2.0    | 2.1    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 607800.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1.0      | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   | 1.0      |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | N        | Y        | N        | Y        | Y        | N        | Y        | N        | Y        | Y      | N        | Y        | Y       | 1        | 844128000 | 875577600 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 167494.0 | 238000.0 | 3703.0  | 1246.0   | 3000.0    | Y      | 7003.0  | 16705.0 | 544.0   | 3975.0   | 2489.0   | Y      | Y        | 29.0   | 654.0    | 439.0    | 4.0      | 1.0      | 4.0      | 12.0     | 17.0     | 7.0    | 0.0    | 1.0    | 8.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 0.0      | 1.0      | 8.0      | 12.75    | 0.0      | 10.5     | 23.25    | 1.0      | 0.0      | 3.0      | 4.0      | 0.0      | 0.0      | 0.0      | 0.0      | 13.75    | 0.0      | 13.5     | 27.25    | 3.0      | 0.0      | 8.0      | 11.0     | 24.75    | 4.0      | 34.5     | 63.25    | 1.0     | 1.0     | 2.0     | 4.0     | 1.0      | 1.0      | 2.0      | 4.0      | 1.0     | 2.0     | 1.0     | 4.0     | 3.0    | 0.0    | 7.0    | 10.0   | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 4137511.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLE ROCK | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLE ROCK | AR      | 72201   | 1081.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 5        | 836179200 | 867628800 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 96479.0  | 0.0      | 17098.0 | 963.0    | 1732322.0 | Y      | 12871.0 | 15891.0 | 272.0   | 6074.0   | 11393.0  | Y      | Y        | 19.0   | 1030.0   | 20.0     | 18.0     | 3.0      | 5.0      | 8.0      | 16.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 4.0      | 2.0      | 5.0      | 11.0     | 6.0      | 4.0      | 14.0     | 24.0     | 4.0      | 0.0      | 5.5      | 9.5      | 14.0     | 6.0      | 24.5     | 44.5     | 1.0      | 1.0      | 0.0      | 2.0      | 22.0     | 12.0     | 34.5     | 68.5     | 1.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.25     | 0.0      | 0.25     | 1.0     | 1.0     | 0.0     | 2.0     | 4.0    | 0.0    | 6.5    | 10.5   | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 2264510.0  | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   |         | X       |          |         |          |          |          |          |          |          |          |          |          |          |         |         | Y        | Y        | Y        | Y        | N        |                 | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 4        | 836179200 | 867628800 | 360.0    | 0.0     | 0.0     | 8.0     | 0.0      | 0.0      | 8.0      | 1.0     | 0.0     | 0.0     | 1.0     | 2.0     | 0.0     | 0.0     | 2.0     | 2.0      | 0.0      | 0.0      | 2.0      | 3.0      | 0.0      | 0.0      | 3.0      | 6.0    | 0.0    | 0.0    | 6.0    | 311795.0 | 16057.0  | 430.0   | 980.0    | 806403.0  | Y      | 2276.0  | 1406.0  | 1009.0  | 49626.0  | 33199.0  | Y      | Y        | 72.0   | 1517.0   | 162.0    | 18.0     | 2.0      | 1.0      | 8.0      | 11.0     | 4.0    | 0.0    | 5.0    | 9.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 5.0      | 9.0      | 20.0     | 6.0      | 12.0     | 38.0     | 8.0      | 1.0      | 11.0     | 20.0     | 0.0      | 1.0      | 3.0      | 4.0      | 28.0     | 8.0      | 26.0     | 62.0     | 0.0      | 12.0     | 22.0     | 34.0     | 34.0     | 21.0     | 61.0     | 116.0    | 0.5     | 0.0     | 0.0     | 0.5     | 0.5      | 0.0      | 0.0      | 0.5      | 1.0     | 0.0     | 0.0     | 1.0     | 6.0    | 5.0    | 11.0   | 22.0   | 0.25   | 0.0    | 0.0    | 0.25   | 0.0    | 0.0    | 0.0    | 0.0    | 0.25     | 0.0      | 0.0      | 0.25     | 0.1      | 0.0      | 0.0      | 0.1      | 10000.0   | 1036208.0 | 1086208.0 | 4107569.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      |         |         | X        | X       | X        |          |          |          |          |          |          |          |          |          |         |         | N        | Y        | N        | N        | N        |                 | Y        | N        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | Y      | Y        | Y        | Y       | 6        | 836179200 | 867628800 | 108.0    | 0.0     | 0.0     | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 738382.0 | 532.0    | 288.0   | 7711.0   | 3952412.0 | Y      | 30361.0 | 24638.0 | 494.0   | 140654.0 | -1.0     | Y      | N        | 141.0  | 4414.0   | 435.0    | 112.0    | 2.0      | 18.0     | 24.0     | 44.0     | 12.0   | 3.0    | 8.0    | 23.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 12.0     | 3.0      | 8.0      | 23.0     | 14.5     | 0.0      | 27.0     | 41.5     | 9.0      | 0.0      | 17.0     | 26.0     | 7.0      | 0.0      | 19.0     | 26.0     | 30.5     | 0.0      | 63.0     | 93.5     | 5.0      | 22.0     | 10.0     | 37.0     | 49.5     | 43.0     | 105.0    | 197.5    | 2.0     | 0.0     | 0.5     | 2.5     | 1.0      | 0.0      | 3.0      | 4.0      | 2.0     | 0.0     | 2.0     | 4.0     | 3.0    | 0.0    | 18.0   | 21.0   | 1.0    | 0.0    | 0.5    | 1.5    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.5      | 1.5      | 0.0      | 2.0      | 0.0      | 2.0      | 1228642.0 | 4884365.0 | 3067872.0 | 32323595.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                 | Y        | Y        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | N      | N        | Y        | Y       | 8        | 836179200 | 867628800 | 47.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 3.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 1.0    | 0.0    | 1.0    | 26800.0  | 23.0     | 107.0   | 259.0    | 327.0     | N      | 6144.0  | 848.0   | 589.0   | 2597.0   | 13000.0  | Y      | Y        | 19.0   | 510.0    | 45.0     | 39.0     | 2.0      | 2.75     | 3.37     | 8.12     | 0.5    | 0.0    | 0.0    | 0.5    | 1.0    | 0.0    | 0.3    | 1.3    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 1.3      | 1.0      | 5.3      | 4.5      | 1.3      | 1.3      | 7.1      | 6.5      | 2.0      | 3.0      | 11.5     | 0.75     | 0.0      | 1.0      | 1.75     | 2.0      | 0.0      | 8.33     | 10.33    | 9.25     | 2.0      | 12.33    | 23.58    | 0.0      | 0.0      | 0.0      | 0.0      | 15.75    | 6.05     | 17.0     | 38.8     | 0.0     | 1.0     | 0.33    | 1.33    | 0.1      | 0.0      | 0.1      | 0.2      | 2.0     | 0.0     | 0.33    | 2.33    | 2.0    | 1.0    | 8.5    | 11.5   | 1.0    | 0.0    | 0.33   | 1.33   | 4.5    | 1.0    | 0.33   | 5.83   | 0.0      | 1.75     | 0.67     | 2.42     | 0.0      | 0.0      | 0.0      | 0.0      | 27141.0   | 21585.0   | 23095.0   | 3822676.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | Y        | ARTS COMMISSION | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 9        | 836179200 | 867628800 | 37.0     | 0.0     | 0.0     | 1.0     | 3.0      | 0.0      | 4.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 948924.0 | 200.0    | 20.0    | 9792.0   | 1606300.0 | N      | 1188.0  | 1450.0  | 284.0   | 100234.0 | 145454.0 | Y      | N        | 51.0   | 867.0    | 81.0     | 22.0     | 3.0      | 5.0      | 12.0     | 20.0     | 6.0    | 0.0    | 20.0   | 26.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 0.0      | 20.0     | 26.0     | 17.0     | 1.0      | 9.0      | 27.0     | 6.0      | 4.0      | 7.0      | 17.0     | 3.0      | 0.0      | 12.0     | 15.0     | 26.0     | 5.0      | 28.0     | 59.0     | 1.0      | 4.0      | 4.0      | 9.0      | 36.0     | 14.0     | 64.0     | 114.0    | 1.0     | 1.0     | 1.0     | 3.0     | 1.0      | 0.0      | 1.0      | 2.0      | 1.0     | 0.0     | 0.0     | 1.0     | 2.0    | 0.0    | 9.0    | 11.0   | 1.0    | 0.0    | 0.0    | 1.0    | 1.0    | 0.0    | 0.0    | 1.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0       | 25000.0   | 67039.0   | 3274662.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N      | Y        | Y        | Y       | 11       | 844128000 | 875577600 | 0.0      | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | N      | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | N      | N        | 17.0   | 408.0    | 4.0      | 12.0     | 1.0      | 1.0      | 0.0      | 2.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 1.0      | 0.5      | 0.0      | 1.5      | 1.0      | 0.5      | 0.0      | 1.5      | 0.0      | 1.0      | 1.0      | 2.0      | 0.0      | 0.5      | 0.0      | 0.5      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0      | 2.5      | 1.0      | 3.5      | 0.0      | 0.0      | 0.0      | 0.0      | 2.0      | 4.0      | 1.0      | 7.0      | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.25    | 0.0     | 0.0     | 0.25    | 0.25   | 1.0    | 0.0    | 1.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 1.0      | 0.0      | 1.25     | 0.0       | 0.0       | 0.0       | 543000.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 10       | 836179200 | 867628800 | 47.0     | 4.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 4880.0   | 0.0      | 0.0     | 115.0    | 23584.0   | Y      | 1227.0  | 30.0    | 781.0   | 7732.0   | 12493.0  | Y      | N        | 12.0   | 216.0    | 30.0     | 5.0      | 1.0      | 1.0      | 2.0      | 4.0      | 2.75   | 1.25   | 0.0    | 4.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 2.75     | 2.25     | 0.0      | 5.0      | 1.0      | 1.0      | 1.5      | 3.5      | 1.25     | 0.0      | 0.5      | 1.75     | 0.0      | 2.75     | 3.0      | 5.75     | 2.25     | 3.75     | 5.0      | 11.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 7.0      | 7.0      | 20.0     | 0.25    | 0.25    | 0.0     | 0.5     | 0.25     | 0.25     | 0.0      | 0.5      | 2.0     | 2.3     | 0.0     | 4.3     | 0.0    | 1.5    | 2.0    | 3.5    | 0.0    | 0.1    | 0.1    | 0.2    | 0.0    | 0.4    | 0.0    | 0.4    | 0.0      | 0.25     | 0.0      | 0.25     | 0.0      | 0.1      | 0.0      | 0.1      | 0.0       | 0.0       | 0.0       | 666168.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | Y        | N        | N        | Y        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 12       | 836179200 | 867628800 | 96.0     | 0.0     | 6.0     | 1.0     | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 0.0     | 2.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 300764.0 | 374.0    | 7734.0  | 769.0    | 209637.0  | Y      | 74363.0 | 34428.0 | 4615.0  | 114662.0 | 85000.0  | Y      | Y        | 61.0   | 2347.0   | 298.0    | 92.0     | 2.0      | 1.0      | 8.0      | 11.0     | 9.0    | 0.0    | 4.0    | 13.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 0.0      | 2.0      | 6.0      | 13.0     | 0.0      | 6.0      | 19.0     | 13.0     | 0.0      | 11.0     | 24.0     | 3.5      | 0.0      | 5.0      | 8.5      | 0.0      | 1.0      | 2.0      | 3.0      | 16.5     | 1.0      | 18.0     | 35.5     | 0.0      | 17.0     | 34.5     | 51.5     | 31.5     | 19.0     | 66.5     | 117.0    | 2.15    | 0.0     | 1.85    | 4.0     | 0.85     | 0.0      | 0.65     | 1.5      | 2.85    | 1.0     | 0.95    | 4.8     | 0.1    | 0.1    | 0.05   | 0.25   | 0.5    | 0.0    | 0.25   | 0.75   | 0.15   | 0.0    | 0.05   | 0.2    | 0.15     | 0.0      | 0.05     | 0.2      | 0.1      | 0.0      | 0.05     | 0.15     | 96147.0   | 77000.0   | 0.0       | 14411563.0 | 
```