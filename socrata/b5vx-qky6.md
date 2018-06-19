# State Libraries Survey, FY 1994, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1994-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/b5vx-qky6) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/b5vx-qky6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/b5vx-qky6/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | b5vx-qky6 |
| Name | State Libraries Survey, FY 1994, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1994, operations, workforce |
| Created | 2016-12-20T22:44:07Z |
| Publication Date | 2016-12-20T22:51:48Z |

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
| Yes      | series tag     | agric      | Sp Coll Ag                                                 | text      | text        |
| Yes      | series tag     | educ       | Sp Coll Ed                                                 | text      | text        |
| Yes      | series tag     | geneal     | Sp Coll Geneal                                             | text      | text        |
| Yes      | series tag     | law        | Sp Col Law                                                 | text      | text        |
| Yes      | series tag     | libsci     | Sp Col LibSci                                              | text      | text        |
| Yes      | series tag     | sthistry   | Sp Coll state hist                                         | text      | text        |
| Yes      | series tag     | othspcol   | Sp Coll other                                              | text      | text        |
| Yes      | series tag     | othspcsp   | Sp Coll other specified                                    | text      | text        |
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
| Yes      | numeric metric | films      | Films                                                      | number    | number      |
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
| Yes      | numeric metric | combplsl   | Grants to assist/pub & sch                                 | money     | money       |
| Yes      | numeric metric | combplal   | Grants to assist/pub & acad                                | money     | money       |
| Yes      | numeric metric | combalsl   | Grants to assist/acad & sch                                | money     | money       |
| Yes      | numeric metric | comball    | Grants to assist/pub & acad & sch                          | money     | money       |
| Yes      | numeric metric | readsch    | Grants to assist/sch readiness                             | money     | money       |
| Yes      | numeric metric | adltlitr   | Grants to assist/adult literacy & lifelong lrng            | money     | money       |
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
series e:b5vx-qky6 d:1993-07-01T00:00:00.000Z t:physcity=JUNEAU t:gencol=Y t:mailcity=JUNEAU t:pub_fips=2 t:referral=Y t:elecoper=Y t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:libsci=Y t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571.0 t:elecplan=Y t:othspcol=N t:othallop=N t:netgoph=Y t:physzip=99811 t:educ=Y t:sthistry=Y t:geneal=N t:electext=Y t:stdeplib=Y t:law=N t:sthstmus=Y t:stlahost=N t:mail_st=AK t:phys_st=AK t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=571.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:agric=N t:starchiv=Y t:strecmng=Y t:regional=N t:depteduc=X t:largerag=X t:selectiv=Y t:stlegref=N m:totalldc=1 m:totalldb=0 m:totallda=6.5 m:othersva=0 m:othersvb=0 m:totalldd=7.5 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=98726 m:othersvd=0 m:othersvc=0 m:lstecsva=4 m:lstecsvd=13 m:lstecsvc=8 m:video=350 m:lstecsvb=1 m:aendsea=1 m:aendseb=0 m:aendsec=0 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=0.25 m:atevents=350 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.25 m:mon2fri=0 m:otherout=1 m:aendsed=1 m:lsothlsb=0 m:lsothlsa=0 m:admservd=5.5 m:litprseb=0 m:admserva=1.5 m:litprsea=0 m:admservc=2 m:admservb=2 m:lspubsvb=0 m:lspubsva=10 m:lspubsvd=18 m:lscaseb=0 m:litprsed=0 m:lscasea=0.5 m:litprsec=0 m:lspubsvc=8 m:lscased=0.5 m:lscasec=0 m:coroutd=0 m:comball=1 m:coroutb=0 m:coroutc=0 m:events=18 m:corouta=0 m:recfrom=2608 m:bphoutc=0 m:ilssed=0 m:bphoutb=1 m:bphouta=0 m:ilsseb=0 m:ilssec=0 m:ldschc=0.5 m:ldschb=0 m:ldscha=1 m:bphoutd=1 m:ldschd=1.5 m:totalout=2 m:onsitmon=25 m:films=50 m:ilssea=0 m:readsch=0 m:circ=10730 m:tothrswk=40 m:ldpuba=3 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=3.5 m:mainout=1 m:bkservol=100000 m:combplal=3 m:govdoc=420000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:period_e=599200 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=2.5 m:totallsd=31 m:ldothlbb=0 m:totallsc=16 m:ldothlbc=0 m:ldothlbd=2.5 m:totallsb=1 m:gvemoutd=1 m:totallsa=14 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=5315 m:combplsl=16 m:subscrip=800 m:grantmon=107 m:bphsea=0 m:cyasea=0 m:cyaseb=0 m:bphsec=2 m:reftrans=16772 m:cyasec=0 m:bphseb=0 m:cyased=0 m:audio=500 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.5 m:bphsed=2 m:staidseb=0 m:staidsec=0 m:staidsed=0.5 m:adltlitr=0 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=19 m:totstafd=44 m:totstafa=22 m:totstafb=3

series e:b5vx-qky6 d:1993-10-01T00:00:00.000Z t:appbygov=X t:physcity=MONTGOMERY t:gencol=Y t:mailcity=MONTGOMERY t:pub_fips=1 t:referral=Y t:stlacont=N t:elecoper=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:othspcsp=ALABAMIANA t:netmount=N t:mailaddr="6030 MONTICELLO DRIVE" t:libsci=N t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:elecplan=Y t:othspcol=Y t:othallop=N t:netgoph=N t:physzip=36117 t:educ=N t:sthistry=N t:geneal=N t:electext=N t:boardcom=X t:stdeplib=N t:law=N t:sthstmus=N t:stlahost=N t:mail_st=AL t:phys_st=AL t:elecbibl=Y t:walkin=Y t:netsub=N t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=N t:agric=N t:indepag=X t:starchiv=N t:strecmng=N t:regional=N t:selectiv=Y t:stlegref=N m:totalldc=0 m:totalldb=1 m:totallda=7 m:othersva=3 m:othersvb=0 m:totalldd=8 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=5096 m:othersvd=14 m:othersvc=11 m:lstecsva=1 m:lstecsvd=4 m:lstecsvc=3 m:video=2218 m:lstecsvb=0 m:aendsea=0 m:aendseb=2 m:aendsec=1 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=0 m:atevents=885 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0 m:mon2fri=0 m:otherout=0 m:aendsed=3 m:lsothlsb=0 m:lsothlsa=0 m:admservd=16 m:litprseb=0 m:admserva=1 m:litprsea=0 m:admservc=11 m:admservb=4 m:lspubsvb=0 m:lspubsva=12.75 m:lspubsvd=23.25 m:lscaseb=1 m:litprsed=0 m:lscasea=2 m:litprsec=0 m:lspubsvc=10.5 m:lscased=5 m:lscasec=2 m:coroutd=0 m:comball=0 m:coroutb=0 m:coroutc=0 m:events=28 m:corouta=0 m:recfrom=1191 m:bphoutc=0 m:ilssed=1 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:ldscha=0 m:bphoutd=1 m:ldschd=0 m:totalout=1 m:onsitmon=13 m:films=4999 m:ilssea=1 m:readsch=0 m:circ=38806 m:tothrswk=45 m:ldpuba=7 m:ldpubb=1 m:ldpubc=0 m:ldpubd=8 m:mainout=1 m:bkservol=191981 m:combplal=1 m:govdoc=2175 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:period_e=4040587 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=27.25 m:ldothlbb=0 m:totallsc=13.5 m:ldothlbc=0 m:ldothlbd=0 m:totallsb=0 m:gvemoutd=1 m:totallsa=13.75 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=15784 m:combplsl=1 m:subscrip=996 m:grantmon=267 m:bphsea=3 m:cyasea=0 m:cyaseb=0 m:bphsec=7 m:reftrans=5542 m:cyasec=0 m:bphseb=0 m:cyased=0 m:audio=262489 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=2 m:bphsed=10 m:staidseb=0 m:staidsec=2 m:staidsed=4 m:adltlitr=0 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=35.5 m:totstafd=65.25 m:totstafa=24.75 m:totstafb=5

series e:b5vx-qky6 d:1993-07-01T00:00:00.000Z t:physcity=LITTLEROCK t:gencol=Y t:mailcity=LITTLEROCK t:pub_fips=5 t:referral=Y t:stlacont=N t:elecoper=Y t:physaddr="ONE CAPITOL MALL" t:mailzip=72201 t:othspcsp="ERIC,PTDL,ST.CENSUS DATA CTR." t:netmount=N t:mailaddr="ONE CAPITOL MALL" t:libsci=Y t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1081.0 t:elecplan=Y t:othspcol=Y t:othallop=N t:netgoph=N t:physzip=72201 t:educ=N t:sthistry=Y t:geneal=N t:electext=N t:stdeplib=Y t:law=N t:sthstmus=N t:stlahost=N t:mail_st=AR t:phys_st=AR t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=1081.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:agric=N t:starchiv=N t:strecmng=N t:regional=Y t:depteduc=X t:largerag=X t:selectiv=N t:stlegref=N m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=0 m:othersvb=0 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=11700 m:othersvd=0 m:othersvc=0 m:lstecsva=5 m:lstecsvd=16 m:lstecsvc=8 m:video=13103 m:lstecsvb=3 m:aendsea=1 m:aendseb=0 m:aendsec=0 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=1 m:atevents=927 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=1 m:mon2fri=0 m:otherout=0 m:aendsed=1 m:lsothlsb=0 m:lsothlsa=0 m:admservd=11 m:litprseb=0 m:admserva=2 m:litprsea=0.1 m:admservc=6 m:admservb=3 m:lspubsvb=2 m:lspubsva=8 m:lspubsvd=19 m:lscaseb=0 m:litprsed=0.1 m:lscasea=1 m:litprsec=0 m:lspubsvc=9 m:lscased=1 m:lscasec=0 m:coroutd=0 m:comball=0 m:coroutb=0 m:coroutc=0 m:events=18 m:corouta=0 m:recfrom=780 m:bphoutc=0 m:ilssed=0.5 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:ldscha=0 m:bphoutd=1 m:ldschd=0 m:totalout=1 m:onsitmon=58 m:films=0 m:ilssea=0.5 m:readsch=20000 m:circ=12032 m:tothrswk=45 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:mainout=1 m:bkservol=284694 m:combplal=1 m:govdoc=1307360 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:period_e=2350725 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=35 m:ldothlbb=0 m:totallsc=17 m:ldothlbc=0 m:ldothlbd=0 m:totallsb=5 m:gvemoutd=1 m:totallsa=13 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=26000 m:combplsl=0 m:subscrip=869 m:grantmon=24 m:bphsea=2 m:cyasea=0.5 m:cyaseb=0 m:bphsec=5 m:reftrans=5360 m:cyasec=0 m:bphseb=1 m:cyased=0.5 m:audio=0 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=8 m:staidseb=1 m:staidsec=0 m:staidsed=1 m:adltlitr=0 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=25 m:totstafd=52 m:totstafa=19 m:totstafb=8
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

metric m:films p:float l:Films t:dataTypeName=number

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

metric m:combplsl p:double l:"Grants to assist/pub & sch" t:dataTypeName=money

metric m:combplal p:double l:"Grants to assist/pub & acad" t:dataTypeName=money

metric m:combalsl p:double l:"Grants to assist/acad & sch" t:dataTypeName=money

metric m:comball p:double l:"Grants to assist/pub & acad & sch" t:dataTypeName=money

metric m:readsch p:double l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adltlitr p:double l:"Grants to assist/adult literacy & lifelong lrng" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:b5vx-qky6 l:"State Libraries Survey, FY 1994, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/b5vx-qky6

property e:b5vx-qky6 t:meta.view v:id=b5vx-qky6 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1994, Part 1: Operations & Workforce" v:attribution=IMLS

property e:b5vx-qky6 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:b5vx-qky6 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:b5vx-qky6 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:b5vx-qky6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | judbran | legbran | execbran | indepag | governor | boardcom | appbygov | appbyoth | exoffmem | electmem | largerag | depteduc | deptcult | deptstat | otherag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                   | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | agric | educ | geneal | law | libsci | sthistry | othspcol | othspcsp                       | elecplan | elecoper | elecbibl | electext | nettrain | netsub | netequip | netmount | netgoph | pub_fips | fystart   | fyend     | tothrswk | mon2fri | sat2sun | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio    | video   | films  | subscrip | govdoc    | gencol | circ      | provto  | recfrom | reftrans | libvists  | walkin | referral | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lscasea | lscaseb | lscasec | lscased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | combplsl | combplal | combalsl | comball | readsch   | adltlitr  | period_e   | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ========================== | ======== | ======== | ======== | ======== | ======== | ======== | ===== | ==== | ====== | === | ====== | ======== | ======== | ============================== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ========= | ========= | ======== | ======= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======== | ======= | ====== | ======== | ========= | ====== | ========= | ======= | ======= | ======== | ========= | ====== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | N        |                            | Y        | N        | Y        | Y        | N        | Y        | N     | Y    | N      | N   | Y      | Y        | N        |                                | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 2        | 741484800 | 772934400 | 40.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 100000.0  | 500.0    | 350.0   | 50.0   | 800.0    | 420000.0  | Y      | 10730.0   | 5315.0  | 2608.0  | 16772.0  | 98726.0   | Y      | Y        | 18.0   | 350.0    | 107.0    | 25.0     | 1.5      | 2.0      | 2.0      | 5.5      | 3.0    | 0.0    | 0.5    | 3.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 2.5      | 0.0      | 0.0      | 2.5      | 6.5      | 0.0      | 1.0      | 7.5      | 10.0     | 0.0      | 8.0      | 18.0     | 4.0      | 1.0      | 8.0      | 13.0     | 0.0      | 0.0      | 0.0      | 0.0      | 14.0     | 1.0      | 16.0     | 31.0     | 0.0      | 0.0      | 0.0      | 0.0      | 22.0     | 3.0      | 19.0     | 44.0     | 0.5     | 0.0     | 0.0     | 0.5     | 0.5      | 0.0      | 0.0      | 0.5      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0    | 0.0    | 2.0    | 2.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.25     | 0.0      | 0.0      | 0.25     | 0.0      | 0.0      | 0.0      | 0.0      | 16.0     | 3.0      | 0.0      | 1.0     | 0.0       | 0.0       | 599200.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   |          | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   |          |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | N        | Y        | N        | Y        | N     | N    | N      | N   | N      | N        | Y        | ALABAMIANA                     | Y        | N        | Y        | N        | Y        | N      | N        | N        | N       | 1        | 749433600 | 780883200 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 191981.0  | 262489.0 | 2218.0  | 4999.0 | 996.0    | 2175.0    | Y      | 38806.0   | 15784.0 | 1191.0  | 5542.0   | 5096.0    | Y      | Y        | 28.0   | 885.0    | 267.0    | 13.0     | 1.0      | 4.0      | 11.0     | 16.0     | 7.0    | 1.0    | 0.0    | 8.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 1.0      | 0.0      | 8.0      | 12.75    | 0.0      | 10.5     | 23.25    | 1.0      | 0.0      | 3.0      | 4.0      | 0.0      | 0.0      | 0.0      | 0.0      | 13.75    | 0.0      | 13.5     | 27.25    | 3.0      | 0.0      | 11.0     | 14.0     | 24.75    | 5.0      | 35.5     | 65.25    | 2.0     | 1.0     | 2.0     | 5.0     | 2.0      | 0.0      | 2.0      | 4.0      | 0.0     | 2.0     | 1.0     | 3.0     | 3.0    | 0.0    | 7.0    | 10.0   | 0.0    | 0.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0     | 0.0       | 0.0       | 4040587.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLEROCK  | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLEROCK  | AR      | 72201   | 1081.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | Y        | N        | N     | N    | N      | N   | Y      | Y        | Y        | ERIC,PTDL,ST.CENSUS DATA CTR.  | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 5        | 741484800 | 772934400 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 284694.0  | 0.0      | 13103.0 | 0.0    | 869.0    | 1307360.0 | Y      | 12032.0   | 26000.0 | 780.0   | 5360.0   | 11700.0   | Y      | Y        | 18.0   | 927.0    | 24.0     | 58.0     | 2.0      | 3.0      | 6.0      | 11.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 8.0      | 2.0      | 9.0      | 19.0     | 5.0      | 3.0      | 8.0      | 16.0     | 0.0      | 0.0      | 0.0      | 0.0      | 13.0     | 5.0      | 17.0     | 35.0     | 0.0      | 0.0      | 0.0      | 0.0      | 19.0     | 8.0      | 25.0     | 52.0     | 1.0     | 0.0     | 0.0     | 1.0     | 0.0      | 1.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 2.0    | 1.0    | 5.0    | 8.0    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 1.0      | 0.0      | 0.0      | 1.0      | 0.1      | 0.0      | 0.0      | 0.1      | 0.0      | 1.0      | 0.0      | 0.0     | 20000.0   | 0.0       | 2350725.0  | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   |         | X       |          |         |          |          |          |          |          |          |          |          |          |          |         |         | Y        | Y        | Y        | Y        | N        |                            | N        | N        | Y        | Y        | Y        | N        | N     | N    | Y      | Y   | Y      | Y        | N        |                                | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | Y       | 4        | 741484800 | 772934400 | 45.0     | 0.0     | 0.0     | 4.0     | 0.0      | 0.0      | 4.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 3.0      | 0.0      | 0.0      | 3.0      | 3.0    | 0.0    | 0.0    | 3.0    | 1046796.0 | 818.0    | 446.0   | 848.0  | 2341.0   | 784999.0  | Y      | 3683.0    | 1536.0  | 886.0   | 29508.0  | 27714.0   | Y      | Y        | 51.0   | 657.0    | 87.0     | 12.0     | 2.0      | 2.0      | 9.0      | 13.0     | 5.0    | 0.0    | 4.0    | 9.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 5.0      | 0.0      | 4.0      | 9.0      | 21.0     | 5.0      | 26.0     | 52.0     | 4.0      | 1.0      | 7.0      | 12.0     | 0.0      | 0.0      | 0.0      | 0.0      | 25.0     | 6.0      | 33.0     | 64.0     | 0.0      | 7.0      | 27.0     | 34.0     | 32.0     | 15.0     | 73.0     | 120.0    | 0.75    | 0.0     | 0.0     | 0.75    | 0.25     | 0.0      | 0.0      | 0.25     | 0.5     | 0.0     | 0.0     | 0.5     | 6.0    | 3.7    | 10.0   | 19.7   | 0.25   | 0.0    | 0.0    | 0.25   | 0.0    | 0.0    | 0.0    | 0.0    | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 0.0      | 0.0      | 0.25     | 0.0      | 0.0      | 0.0      | 0.0     | 13938.0   | 659052.0  | 3958875.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      |         |         | X        | X       | X        |          |          |          |          |          |          |          |          |          |         |         | N        | Y        | N        | N        | Y        | CALIFORNIA RESEARCH BUREAU | Y        | N        | Y        | Y        | Y        | N        | N     | Y    | Y      | Y   | Y      | Y        | Y        | GOV'T,PUB. FINANCE,BUSINESS, C | Y        | Y        | Y        | N        | Y        | Y      | Y        | Y        | Y       | 6        | 741484800 | 772934400 | 108.0    | 0.0     | 0.0     | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 716555.0  | 250.0    | 194.0   | 11.0   | 9630.0   | 2100000.0 | Y      | 75744.0   | 34164.0 | 708.0   | 144820.0 | -1.0      | Y      | N        | 52.0   | 2723.0   | 313.0    | 115.0    | 2.0      | 12.0     | 17.0     | 31.0     | 12.0   | 3.0    | 8.0    | 23.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 12.0     | 3.0      | 8.0      | 23.0     | 14.5     | 0.0      | 27.0     | 41.5     | 9.0      | 0.0      | 17.0     | 26.0     | 7.0      | 0.0      | 19.0     | 26.0     | 30.5     | 0.0      | 63.0     | 93.5     | 4.0      | 17.0     | 8.0      | 29.0     | 48.5     | 32.0     | 96.0     | 176.5    | 2.0     | 0.0     | 0.5     | 2.5     | 1.0      | 0.0      | 3.0      | 4.0      | 2.0     | 0.0     | 2.0     | 4.0     | 3.0    | 0.0    | 18.0   | 21.0   | 1.0    | 0.0    | 0.5    | 1.5    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.5      | 1.5      | 0.0      | 2.0      | 0.0      | 2.0      | 0.0      | 0.0      | 0.0      | 0.0     | 2703979.0 | 3823842.0 | 31509515.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                            | Y        | Y        | Y        | N        | N        | N        | N     | Y    | N      | N   | Y      | N        | N        |                                | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 8        | 741484800 | 772934400 | 45.0     | 0.0     | 0.0     | 0.0     | 13.0     | 0.0      | 13.0     | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 11.0    | 0.0     | 11.0    | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 1.0    | 0.0    | 1.0    | 18000.0   | 50.0     | 60.0    | 0.0    | 55.0     | 0.0       | N      | 4863.0    | 767.0   | 834.0   | 3218.0   | 780.0     | Y      | Y        | 13.0   | 328.0    | 91.0     | 72.0     | 2.0      | 0.5      | 2.0      | 4.5      | 0.5    | 0.0    | 0.33   | 0.83   | 1.0    | 0.0    | 0.34   | 1.34   | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 1.8      | 1.0      | 5.8      | 4.5      | 1.8      | 1.67     | 7.97     | 12.5     | 1.0      | 4.0      | 17.5     | 0.5      | 0.0      | 6.0      | 6.5      | 1.0      | 1.0      | 0.0      | 2.0      | 14.0     | 2.0      | 10.0     | 26.0     | 0.0      | 3.0      | 1.66     | 4.66     | 20.5     | 7.3      | 15.33    | 43.13    | 0.0     | 1.0     | 0.33    | 1.33    | 0.25     | 0.0      | 0.17     | 0.42     | 1.25    | 0.0     | 0.33    | 1.58    | 2.0    | 1.0    | 6.5    | 9.5    | 2.0    | 0.0    | 0.33   | 2.33   | 1.0    | 0.0    | 0.0    | 1.0    | 1.0      | 0.5      | 0.34     | 1.84     | 0.0      | 1.0      | 0.33     | 1.33     | 7.0      | 0.0      | 1.0      | 0.0     | 0.0       | 0.0       | 3565957.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | Y        | Y        | Y        | N        |                            | N        | N        | Y        | Y        | Y        | N        | N     | N    | Y      | Y   | Y      | Y        | Y        | MUSEUM OF CONNECTICUT HISTORY  | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 9        | 741484800 | 772934400 | 37.0     | 0.0     | 0.0     | 1.0     | 3.0      | 0.0      | 4.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 879000.0  | 200.0    | 20.0    | 0.0    | 9273.0   | 1560000.0 | N      | 1034.0    | 2189.0  | 187.0   | 83831.0  | 150000.0  | Y      | N        | 20.0   | 400.0    | 137.0    | 8.0      | 1.0      | 5.0      | 9.0      | 15.0     | 6.0    | 0.0    | 17.0   | 23.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 0.0      | 17.0     | 23.0     | 16.0     | 1.0      | 6.0      | 23.0     | 5.0      | 4.0      | 6.0      | 15.0     | 7.0      | 2.0      | 0.0      | 9.0      | 28.0     | 7.0      | 12.0     | 47.0     | 1.0      | 1.0      | 23.0     | 25.0     | 36.0     | 13.0     | 61.0     | 110.0    | 1.0     | 1.0     | 1.0     | 3.0     | 1.0      | 0.0      | 1.0      | 2.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0    | 1.0    | 11.0   | 13.0   | 1.0    | 0.0    | 0.0    | 1.0    | 1.0    | 0.0    | 0.0    | 1.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0       | 60000.0   | 3279340.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   |         |         | X        | X       |          | X        |          | X        |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | N      | N   | N      | Y        | N        |                                | N        | N        | N        | N        | N        | N      | N        | Y        | N       | 11       | 749433600 | 780883200 | 1404.0   | 184.0   | 191.0   | 1.0     | 26.0     | 1.0      | 28.0     | 1.0     | 26.0    | 1.0     | 28.0    | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 1.0      | 2.0      | 1.0      | 26.0     | 0.0      | 27.0     | 1.0    | 26.0   | 1.0    | 28.0   | 2140126.0 | 312183.0 | 8306.0  | 3376.0 | 1613.0   | 79000.0   | Y      | 1784619.0 | 7059.0  | 115.0   | 997464.0 | 2145166.0 | Y      | Y        | 1.0    | 80.0     | 3.0      | 12.0     | 5.0      | 1.0      | 26.5     | 32.5     | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 118.0    | 32.5     | 151.5    | 302.0    | 6.0      | 0.0      | 37.5     | 43.5     | 0.0      | 2.0      | 58.0     | 60.0     | 124.0    | 34.5     | 247.0    | 405.5    | 0.0      | 0.0      | 0.0      | 0.0      | 129.0    | 35.5     | 273.5    | 438.0    | 1.0     | 1.0     | 0.0     | 2.0     | 0.0      | 0.0      | 0.0      | 0.0      | 2.0     | 0.0     | 0.0     | 2.0     | 1.0    | 2.0    | 6.0    | 9.0    | 32.0   | 9.0    | 2.0    | 43.0   | 1.0    | 0.0    | 1.0    | 2.0    | 1.0      | 0.0      | 1.0      | 2.0      | 1.0      | 6.0      | 0.0      | 7.0      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0       | 0.0       | 606900.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | N      | N   | Y      | Y        | N        |                                | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 10       | 741484800 | 772934400 | 46.0     | 4.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 47000.0   | 0.0      | 1012.0  | 0.0    | 151.0    | 4693.0    | Y      | 4811.0    | 394.0   | 1522.0  | 11623.0  | 12073.0   | Y      | N        | 4.0    | 430.0    | 29.0     | 24.0     | 1.0      | 0.75     | 2.4      | 4.15     | 1.0    | 0.25   | 0.0    | 1.25   | 0.0    | 0.1    | 0.0    | 0.1    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.35     | 0.0      | 1.35     | 1.0      | 1.0      | 0.6      | 2.6      | 1.0      | 0.0      | 1.0      | 2.0      | 0.0      | 3.9      | 3.0      | 6.9      | 2.0      | 4.9      | 4.6      | 11.5     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 6.0      | 7.0      | 17.0     | 0.25    | 0.25    | 0.0     | 0.5     | 0.25     | 0.25     | 0.0      | 0.5      | 0.5     | 1.0     | 0.0     | 1.5     | 0.0    | 1.5    | 2.0    | 3.5    | 0.0    | 0.1    | 0.0    | 0.1    | 0.0    | 0.4    | 0.0    | 0.4    | 0.0      | 0.25     | 0.1      | 0.35     | 0.0      | 0.1      | 0.0      | 0.1      | 0.0      | 0.0      | 0.0      | 0.0     | 0.0       | 0.0       | 666168.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | Y        | N        | N        | Y        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | Y    | Y      | N   | Y      | Y        | Y        | STATE DOCUMENTS, SOUTHERN HIST | Y        | N        | Y        | N        | Y        | Y      | Y        | Y        | N       | 12       | 741484800 | 772934400 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 272233.0  | 284.0    | 4513.0  | 4810.0 | 760.0    | 269054.0  | Y      | 73800.0   | 16017.0 | 5994.0  | 33998.0  | 62400.0   | Y      | Y        | 62.0   | 2210.0   | 336.0    | 72.0     | 2.0      | 4.0      | 5.0      | 11.0     | 10.0   | 0.0    | 6.0    | 16.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 1.0      | 4.0      | 13.0     | 0.0      | 7.0      | 20.0     | 12.0     | 0.0      | 14.0     | 26.0     | 3.5      | 0.0      | 5.0      | 8.5      | 0.0      | 3.0      | 1.0      | 4.0      | 15.5     | 3.0      | 20.0     | 38.5     | 0.0      | 28.5     | 25.0     | 53.5     | 30.5     | 35.5     | 57.0     | 123.0    | 2.15    | 0.0     | 1.85    | 4.0     | 0.85     | 0.0      | 0.65     | 1.5      | 2.85    | 0.0     | 0.95    | 3.8     | 0.1    | 0.0    | 0.05   | 0.15   | 0.5    | 0.0    | 0.25   | 0.75   | 0.15   | 0.0    | 0.05   | 0.2    | 0.15     | 0.0      | 0.05     | 0.2      | 0.1      | 0.0      | 0.05     | 0.15     | 0.0      | 0.0      | 0.0      | 0.0     | 552243.0  | 47469.0   | 13608627.0 | 
```