# State Libraries Survey, FY 1995, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1995-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/fixd-rw4z) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/fixd-rw4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/fixd-rw4z/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | fixd-rw4z |
| Name | State Libraries Survey, FY 1995, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1995, operations, workforce |
| Created | 2016-12-20T22:44:20Z |
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
series e:fixd-rw4z d:1994-07-01T00:00:00.000Z t:physcity=JUNEAU t:gencol=Y t:mailcity=JUNEAU t:pub_fips=2 t:referral=Y t:elecoper=Y t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:libsci=N t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571.0 t:elecplan=Y t:othspcol=N t:othallop=N t:netgoph=Y t:physzip=99811 t:educ=N t:sthistry=Y t:geneal=N t:electext=Y t:stdeplib=Y t:law=Y t:sthstmus=Y t:stlahost=N t:mail_st=AK t:phys_st=AK t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=571.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:agric=N t:starchiv=Y t:strecmng=Y t:regional=Y t:depteduc=X t:largerag=X t:selectiv=N t:stlegref=N m:totalldc=3 m:totalldb=0 m:totallda=6 m:othersva=3 m:othersvb=3 m:totalldd=9 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=54241 m:othersvd=8 m:othersvc=2 m:lstecsva=2 m:lstecsvd=6 m:lstecsvc=4 m:video=941 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=2 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=1.8 m:atevents=460 m:otstouta=0 m:lbstaseb=0.8 m:lbstasec=0.2 m:lbstased=2.8 m:mon2fri=0 m:otherout=1 m:aendsed=4 m:lsothlsb=5 m:lsothlsa=3 m:admservd=15.5 m:litprseb=1 m:admserva=3 m:litprsea=0 m:admservc=7 m:admservb=5.5 m:lspubsvb=0 m:lspubsva=12 m:lspubsvd=24 m:lscaseb=1 m:litprsed=1 m:lscasea=0 m:litprsec=0 m:lspubsvc=12 m:lscased=1 m:lscasec=0 m:coroutd=0 m:comball=0 m:coroutb=0 m:coroutc=0 m:events=16 m:corouta=0 m:recfrom=17183 m:bphoutc=0 m:ilssed=1 m:bphoutb=1 m:bphouta=0 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:ldscha=0 m:bphoutd=1 m:ldschd=0 m:totalout=2 m:onsitmon=34 m:films=0 m:ilssea=1 m:readsch=0 m:circ=22032 m:tothrswk=40 m:ldpuba=6 m:ldpubb=0 m:ldpubc=3 m:ldpubd=9 m:mainout=1 m:bkservol=324287 m:combplal=1 m:govdoc=79000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:period_e=1079516 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=46 m:ldothlbb=0 m:totallsc=24 m:ldothlbc=0 m:ldothlbd=0 m:totallsb=5 m:gvemoutd=1 m:totallsa=17 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=17409 m:combplsl=2 m:subscrip=2176 m:grantmon=34 m:bphsea=0 m:cyasea=1 m:cyaseb=0 m:bphsec=0 m:reftrans=16636 m:cyasec=0 m:bphseb=0 m:cyased=1 m:audio=0 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=1 m:bphsed=0 m:staidseb=0 m:staidsec=0 m:staidsed=1 m:adltlitr=0 m:lsothlsd=16 m:lsothlsc=8 m:totstafc=36 m:totstafd=78.5 m:totstafa=29 m:totstafb=13.5

series e:fixd-rw4z d:1994-10-01T00:00:00.000Z t:appbygov=X t:physcity=MONTGOMERY t:gencol=Y t:mailcity=MONTGOMERY t:pub_fips=1 t:referral=Y t:stlacont=N t:elecoper=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:othspcsp="PHOT COLLECTIONS, WPA MANUSCRI" t:netmount=N t:mailaddr="6030 MONTICELLO DRIVE" t:libsci=Y t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:elecplan=Y t:othspcol=Y t:othallop=N t:netgoph=N t:physzip=36117 t:educ=N t:sthistry=Y t:geneal=Y t:electext=N t:boardcom=X t:stdeplib=Y t:law=N t:sthstmus=N t:stlahost=N t:mail_st=AL t:phys_st=AL t:elecbibl=Y t:walkin=Y t:netsub=N t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=N t:agric=N t:indepag=X t:starchiv=N t:strecmng=N t:regional=N t:selectiv=Y t:stlegref=N m:totalldc=0.75 m:totalldb=1 m:totallda=2 m:othersva=0 m:othersvb=0 m:totalldd=3.75 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=30289 m:othersvd=0 m:othersvc=0 m:lstecsva=2 m:lstecsvd=9 m:lstecsvc=7 m:video=2809 m:lstecsvb=0 m:aendsea=1 m:aendseb=0 m:aendsec=3 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=0.75 m:atevents=105 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.75 m:mon2fri=0 m:otherout=0 m:aendsed=4 m:lsothlsb=0 m:lsothlsa=1 m:admservd=5 m:litprseb=0 m:admserva=3 m:litprsea=0.3 m:admservc=1 m:admservb=1 m:lspubsvb=0 m:lspubsva=6 m:lspubsvd=11 m:lscaseb=0.5 m:litprsed=0.35 m:lscasea=0.4 m:litprsec=0.05 m:lspubsvc=5 m:lscased=1.15 m:lscasec=0.25 m:coroutd=0 m:comball=0 m:coroutb=0 m:coroutc=0 m:events=2 m:corouta=0 m:recfrom=3567 m:bphoutc=0 m:ilssed=0 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:ldscha=0 m:bphoutd=1 m:ldschd=0 m:totalout=1 m:onsitmon=3 m:films=0 m:ilssea=0 m:readsch=447421 m:circ=48420 m:tothrswk=45 m:ldpuba=2 m:ldpubb=1 m:ldpubc=0.75 m:ldpubd=3.75 m:mainout=1 m:bkservol=1009709 m:combplal=0 m:govdoc=129592 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:period_e=9332515 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=34.13 m:ldothlbb=0 m:totallsc=25.13 m:ldothlbc=0 m:ldothlbd=0 m:totallsb=0 m:gvemoutd=1 m:totallsa=9 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=19850 m:combplsl=20 m:subscrip=631 m:grantmon=115 m:bphsea=1 m:cyasea=0.5 m:cyaseb=0 m:bphsec=7.5 m:reftrans=17756 m:cyasec=0.15 m:bphseb=0 m:cyased=0.65 m:audio=558 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.1 m:bphsed=8.5 m:staidseb=0.1 m:staidsec=0.1 m:staidsed=0.3 m:adltlitr=2509308 m:lsothlsd=14.13 m:lsothlsc=13.13 m:totstafc=26.88 m:totstafd=42.88 m:totstafa=14 m:totstafb=2

series e:fixd-rw4z d:1994-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:gencol=Y t:mailcity="LITTLE ROCK" t:pub_fips=5 t:referral=Y t:stlacont=N t:elecoper=Y t:physaddr="ONE CAPITOL MALL" t:mailzip=72201 t:othspcsp=MANAGEMENT t:netmount=N t:mailaddr="ONE CAPITOL MALL" t:libsci=Y t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1081.0 t:elecplan=Y t:othspcol=Y t:othallop=N t:netgoph=N t:physzip=72201 t:educ=Y t:sthistry=Y t:geneal=Y t:electext=N t:stdeplib=Y t:law=Y t:sthstmus=N t:stlahost=N t:mail_st=AR t:phys_st=AR t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=1081.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:agric=N t:starchiv=N t:strecmng=N t:regional=Y t:depteduc=X t:largerag=X t:selectiv=N t:stlegref=N m:totalldc=7 m:totalldb=3 m:totallda=8 m:othersva=0 m:othersvb=0 m:totalldd=18 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=-1 m:othersvd=0 m:othersvc=0 m:lstecsva=6 m:lstecsvd=16 m:lstecsvc=10 m:video=509 m:lstecsvb=0 m:aendsea=0.25 m:aendseb=1.25 m:aendsec=0 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:lbstasea=0 m:atevents=3552 m:otstouta=0 m:lbstaseb=0.25 m:lbstasec=0.25 m:lbstased=0.5 m:mon2fri=0 m:otherout=0 m:aendsed=1.5 m:lsothlsb=2 m:lsothlsa=2 m:admservd=15 m:litprseb=0 m:admserva=4 m:litprsea=1 m:admservc=10 m:admservb=1 m:lspubsvb=0 m:lspubsva=9 m:lspubsvd=26 m:lscaseb=0 m:litprsed=3 m:lscasea=1 m:litprsec=2 m:lspubsvc=17 m:lscased=3 m:lscasec=2 m:coroutd=0 m:comball=0 m:coroutb=0 m:coroutc=0 m:events=132 m:corouta=0 m:recfrom=435 m:bphoutc=0 m:ilssed=0.67 m:bphoutb=0 m:bphouta=1 m:ilsseb=0 m:ilssec=0 m:ldschc=3 m:ldschb=2 m:ldscha=1 m:bphoutd=1 m:ldschd=6 m:totalout=1 m:onsitmon=15 m:films=0 m:ilssea=0.67 m:readsch=199231 m:circ=61780 m:tothrswk=45 m:ldpuba=6 m:ldpubb=1 m:ldpubc=4 m:ldpubd=11 m:mainout=1 m:bkservol=987422 m:combplal=0 m:govdoc=-1 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0.67 m:period_e=4515118 m:sat2sun=0 m:combalsl=0 m:ldspecc=0 m:ldspecd=0.67 m:ldothlba=0.33 m:totallsd=48 m:ldothlbb=0 m:totallsc=29 m:ldothlbc=0 m:ldothlbd=0.33 m:totallsb=2 m:gvemoutd=1 m:totallsa=17 m:gvemoutc=0 m:gvemoutb=0 m:gvemouta=1 m:provto=9445 m:combplsl=1 m:subscrip=4071 m:grantmon=235 m:bphsea=0 m:cyasea=0.5 m:cyaseb=3 m:bphsec=0 m:reftrans=43058 m:cyasec=1 m:bphseb=0 m:cyased=4.5 m:audio=753 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=0 m:staidseb=1 m:staidsec=1 m:staidsed=2 m:adltlitr=0 m:lsothlsd=6 m:lsothlsc=2 m:totstafc=46 m:totstafd=81 m:totstafa=29 m:totstafb=6
```

## Meta Commands

```ls
metric m:tothrswk p:integer l:"Hours open typical week" t:dataTypeName=number

metric m:mon2fri p:integer l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:sat2sun p:integer l:"Hours open Sat & Sun" t:dataTypeName=number

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

metric m:films p:integer l:Films t:dataTypeName=number

metric m:subscrip p:integer l:"Serial Subs" t:dataTypeName=number

metric m:govdoc p:integer l:"Govt Documents" t:dataTypeName=number

metric m:circ p:integer l:Circulation t:dataTypeName=number

metric m:provto p:integer l:"ILL out" t:dataTypeName=number

metric m:recfrom p:integer l:"ILL in" t:dataTypeName=number

metric m:reftrans p:integer l:"Reference transactions" t:dataTypeName=number

metric m:libvists p:integer l:"Library visits" t:dataTypeName=number

metric m:events p:integer l:"Number of events" t:dataTypeName=number

metric m:atevents p:integer l:"Total attendance" t:dataTypeName=number

metric m:grantmon p:integer l:"Grants monitored" t:dataTypeName=number

metric m:onsitmon p:integer l:"On-site monitoring visits" t:dataTypeName=number

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

metric m:combplsl p:integer l:"Grants to assist/pub & sch" t:dataTypeName=money

metric m:combplal p:integer l:"Grants to assist/pub & acad" t:dataTypeName=money

metric m:combalsl p:integer l:"Grants to assist/acad & sch" t:dataTypeName=money

metric m:comball p:integer l:"Grants to assist/pub & acad & sch" t:dataTypeName=money

metric m:readsch p:integer l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adltlitr p:integer l:"Grants to assist/adult literacy & lifelong lrng" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:fixd-rw4z l:"State Libraries Survey, FY 1995, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/fixd-rw4z

property e:fixd-rw4z t:meta.view v:id=fixd-rw4z v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1995, Part 1: Operations & Workforce" v:attribution=IMLS

property e:fixd-rw4z t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:fixd-rw4z t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:fixd-rw4z t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:fixd-rw4z t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | judbran | legbran | execbran | indepag | governor | boardcom | appbygov | appbyoth | exoffmem | electmem | largerag | depteduc | deptcult | deptstat | otherag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                   | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | agric | educ | geneal | law | libsci | sthistry | othspcol | othspcsp                          | elecplan | elecoper | elecbibl | electext | nettrain | netsub | netequip | netmount | netgoph | pub_fips | fystart   | fyend     | tothrswk | mon2fri | sat2sun | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol | audio | video | films | subscrip | govdoc  | gencol | circ   | provto | recfrom | reftrans | libvists | walkin | referral | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lscasea | lscaseb | lscasec | lscased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | combplsl | combplal | combalsl | comball | readsch | adltlitr | period_e  | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ========================== | ======== | ======== | ======== | ======== | ======== | ======== | ===== | ==== | ====== | === | ====== | ======== | ======== | ================================= | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ========= | ========= | ======== | ======= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ======== | ===== | ===== | ===== | ======== | ======= | ====== | ====== | ====== | ======= | ======== | ======== | ====== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ========= | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | N        |                            | Y        | N        | Y        | Y        | Y        | N        | N     | N    | N      | Y   | N      | Y        | N        |                                   | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 2        | 773020800 | 804470400 | 40       | 0       | 0       | 1       | 1        | 0        | 2        | 0       | 1       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 324287   | 0     | 941   | 0     | 2176     | 79000   | Y      | 22032  | 17409  | 17183   | 16636    | 54241    | Y      | Y        | 16     | 460      | 34       | 34       | 3.0      | 5.5      | 7.0      | 15.5     | 6.0    | 0.0    | 3.0    | 9.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 6.0      | 0.0      | 3.0      | 9.0      | 12.0     | 0.0      | 12.0     | 24.0     | 2.0      | 0.0      | 4.0      | 6.0      | 3.0      | 5.0      | 8.0      | 16.0     | 17.0     | 5.0      | 24.0     | 46.0     | 3.0      | 3.0      | 2.0      | 8.0      | 29.0     | 13.5     | 36.0     | 78.5     | 0.0     | 1.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0     | 1.0     | 2.0     | 4.0     | 0.0    | 0.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 1.0    | 1.0    | 0.0    | 0.0    | 1.0    | 1.8      | 0.8      | 0.2      | 2.8      | 0.0      | 1.0      | 0.0      | 1.0      | 2        | 1        | 0        | 0       | 0       | 0        | 1079516.0 | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   |          | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   |          |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | Y      | N   | Y      | Y        | Y        | PHOT COLLECTIONS, WPA MANUSCRI    | Y        | N        | Y        | N        | Y        | N      | N        | N        | N       | 1        | 780969600 | 812419200 | 45       | 0       | 0       | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 1009709  | 558   | 2809  | 0     | 631      | 129592  | Y      | 48420  | 19850  | 3567    | 17756    | 30289    | Y      | Y        | 2      | 105      | 115      | 3        | 3.0      | 1.0      | 1.0      | 5.0      | 2.0    | 1.0    | 0.75   | 3.75   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 2.0      | 1.0      | 0.75     | 3.75     | 6.0      | 0.0      | 5.0      | 11.0     | 2.0      | 0.0      | 7.0      | 9.0      | 1.0      | 0.0      | 13.13    | 14.13    | 9.0      | 0.0      | 25.13    | 34.13    | 0.0      | 0.0      | 0.0      | 0.0      | 14.0     | 2.0      | 26.88    | 42.88    | 0.4     | 0.5     | 0.25    | 1.15    | 0.1      | 0.1      | 0.1      | 0.3      | 1.0     | 0.0     | 3.0     | 4.0     | 1.0    | 0.0    | 7.5    | 8.5    | 0.5    | 0.0    | 0.15   | 0.65   | 0.0    | 0.0    | 0.0    | 0.0    | 0.75     | 0.0      | 0.0      | 0.75     | 0.3      | 0.0      | 0.05     | 0.35     | 20       | 0        | 0        | 0       | 447421  | 2509308  | 9332515.0 | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLE ROCK | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLE ROCK | AR      | 72201   | 1081.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | Y        | N        | N     | Y    | Y      | Y   | Y      | Y        | Y        | MANAGEMENT                        | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 5        | 773020800 | 804470400 | 45       | 0       | 0       | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 987422   | 753   | 509   | 0     | 4071     | -1      | Y      | 61780  | 9445   | 435     | 43058    | -1       | Y      | Y        | 132    | 3552     | 235      | 15       | 4.0      | 1.0      | 10.0     | 15.0     | 6.0    | 1.0    | 4.0    | 11.0   | 1.0    | 2.0    | 3.0    | 6.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.67    | 0.0     | 0.0     | 0.67    | 0.33     | 0.0      | 0.0      | 0.33     | 8.0      | 3.0      | 7.0      | 18.0     | 9.0      | 0.0      | 17.0     | 26.0     | 6.0      | 0.0      | 10.0     | 16.0     | 2.0      | 2.0      | 2.0      | 6.0      | 17.0     | 2.0      | 29.0     | 48.0     | 0.0      | 0.0      | 0.0      | 0.0      | 29.0     | 6.0      | 46.0     | 81.0     | 1.0     | 0.0     | 2.0     | 3.0     | 0.0      | 1.0      | 1.0      | 2.0      | 0.25    | 1.25    | 0.0     | 1.5     | 0.0    | 0.0    | 0.0    | 0.0    | 0.5    | 3.0    | 1.0    | 4.5    | 0.67   | 0.0    | 0.0    | 0.67   | 0.0      | 0.25     | 0.25     | 0.5      | 1.0      | 0.0      | 2.0      | 3.0      | 1        | 0        | 0        | 0       | 199231  | 0        | 4515118.0 | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   |         | X       |          |         |          |          |          |          |          |          |          |          |          |          |         |         | Y        | Y        | Y        | Y        | N        |                            | N        | N        | Y        | N        | N        | N        | N     | N    | N      | N   | Y      | N        | N        |                                   | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 4        | 773020800 | 804470400 | 45       | 0       | 0       | 4       | 0        | 0        | 4        | 1       | 0       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 3        | 0        | 0        | 3        | 3      | 0      | 0      | 3      | 5000     | 5     | 50    | 0     | 200      | 1000    | N      | 1537   | 321    | 150     | 1100     | 350      | Y      | Y        | 31     | 431      | 5        | 0        | 2.6      | 0.9      | 0.9      | 4.4      | 0.9    | 0.0    | 0.0    | 0.9    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.9      | 0.0      | 0.9      | 0.9      | 0.9      | 0.0      | 1.8      | 1.8      | 0.9      | 1.4      | 4.1      | 0.0      | 0.0      | 0.2      | 0.2      | 5.5      | 0.9      | 1.0      | 7.4      | 7.3      | 1.8      | 2.6      | 11.7     | 0.0      | 0.0      | 1.0      | 1.0      | 10.8     | 3.6      | 4.5      | 18.9     | 0.5     | 0.6     | 0.05    | 1.15    | 0.6      | 0.7      | 0.05     | 1.35     | 2.3     | 0.9     | 0.0     | 3.2     | 2.3    | 0.0    | 1.8    | 4.1    | 0.7    | 0.0    | 0.1    | 0.8    | 0.7    | 0.0    | 0.1    | 0.8    | 0.2      | 0.0      | 1.8      | 2.0      | 0.2      | 0.0      | 0.0      | 0.2      | 0        | 0        | 0        | 0       | 14780   | 209051   | 5277640.0 | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      |         |         | X        | X       | X        |          |          |          |          |          |          |          |          |          |         |         | N        | Y        | N        | N        | Y        | CALIFORNIA RESEARCH BUREAU | Y        | N        | Y        | Y        | N        | Y        | N     | Y    | N      | N   | Y      | Y        | Y        | GRANTS RESEARCH COLLECTION        | Y        | Y        | Y        | N        | Y        | Y      | Y        | Y        | Y       | 6        | 773020800 | 804470400 | 108      | 0       | 0       | 1       | 2        | 0        | 3        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 1        | 0        | 2        | 1      | 1      | 0      | 2      | 260488   | 294   | 1846  | 1967  | 2548     | 244511  | Y      | 52056  | 43816  | 861     | 25518    | 31040    | Y      | N        | 21     | 610      | 191      | 132      | 1.88     | 3.75     | 1.87     | 7.5      | 3.75   | 0.0    | 0.94   | 4.69   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 3.75     | 0.0      | 0.94     | 4.69     | 11.25    | 0.94     | 11.25    | 23.44    | 1.87     | 0.0      | 4.69     | 6.56     | 1.87     | 0.94     | 0.0      | 2.81     | 14.99    | 1.88     | 15.94    | 32.81    | 0.0      | 0.0      | 0.0      | 0.0      | 20.62    | 5.63     | 18.75    | 45.0     | 0.52    | 0.0     | 0.0     | 0.52    | 0.14     | 0.0      | 0.0      | 0.14     | 1.88    | 0.93    | 0.0     | 2.81    | 1.88   | 0.94   | 5.62   | 8.44   | 0.94   | 0.0    | 0.0    | 0.94   | 0.0    | 0.0    | 0.0    | 0.0    | 0.09     | 0.0      | 0.0      | 0.09     | 0.0      | 0.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0       | 43185   | 14538    | 2573216.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                            | Y        | Y        | Y        | Y        | N        | Y        | N     | N    | N      | N   | Y      | Y        | Y        | NATIVE AMERICAN LAKOTA COLLECTION | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | 8        | 773020800 | 804470400 | 45       | 0       | 0       | 0       | 7        | 0        | 7        | 0       | 1       | 0       | 1       | 0       | 4       | 0       | 4       | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 1        | 0      | 1      | 0      | 1      | 161567   | 110   | 9000  | 2000  | 1052     | 125000  | Y      | 51166  | 57896  | 10261   | 7721     | -1       | Y      | Y        | 16     | 750      | 23       | 10       | 1.0      | 0.0      | 3.5      | 4.5      | 2.0    | 0.0    | 0.0    | 2.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 3.0      | 1.0      | 0.0      | 4.0      | 4.0      | 1.0      | 9.25     | 14.25    | 1.0      | 0.0      | 4.0      | 5.0      | 0.0      | 2.0      | 7.5      | 9.5      | 5.0      | 3.0      | 20.75    | 28.75    | 0.0      | 0.0      | 0.0      | 0.0      | 9.0      | 4.0      | 24.25    | 37.25    | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.75    | 0.0     | 0.25    | 1.0     | 0.0    | 2.0    | 7.5    | 9.5    | 0.1    | 0.0    | 0.0    | 0.1    | 0.0    | 0.75   | 0.0    | 0.75   | 0.1      | 0.0      | 0.0      | 0.1      | 0.0      | 0.1      | 0.0      | 0.1      | 4        | 0        | 0        | 0       | 0       | 0        | 822347.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | Y        | Y        | Y        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | Y      | N   | N      | Y        | N        |                                   | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | N       | 9        | 773020800 | 804470400 | 37       | 0       | 0       | 1       | 3        | 0        | 4        | 1       | 1       | 0       | 2       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 558264   | 35062 | 80    | 265   | 538      | 140841  | Y      | 0      | 1857   | 342     | 30584    | 26691    | Y      | N        | 59     | 1002     | 58       | 138      | 3.0      | 1.0      | 1.0      | 5.0      | 4.0    | 0.0    | 1.0    | 5.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 1.0      | 5.0      | 5.0      | 5.0      | 14.0     | 24.0     | 4.0      | 2.0      | 17.0     | 23.0     | 3.0      | 3.0      | 28.0     | 34.0     | 12.0     | 10.0     | 59.0     | 81.0     | 0.0      | 0.0      | 0.0      | 0.0      | 19.0     | 11.0     | 61.0     | 91.0     | 3.0     | 0.0     | 1.0     | 4.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 3.0    | 0.0    | 12.0   | 15.0   | 0.5    | 0.0    | 0.0    | 0.5    | 0.3    | 0.0    | 0.0    | 0.3    | 0.4      | 0.0      | 0.0      | 0.4      | 0.4      | 0.0      | 0.0      | 0.4      | 0        | 0        | 0        | 0       | 62791   | 13844    | 6631836.0 | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   |         |         | X        | X       |          | X        |          | X        |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | Y        | N        | N     | N    | Y      | N   | Y      | Y        | N        |                                   | N        | N        | N        | N        | N        | N      | N        | Y        | N       | 11       | 780969600 | 812419200 | 0        | 0       | 0       | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 0        | 0        | 0        | 0        | 0      | 0      | 0      | 0      | 138164   | 1038  | 206   | 0     | 597      | 1700000 | Y      | 13256  | 3328   | 2529    | 111006   | 34755    | N      | N        | 100    | 3534     | 70       | 40       | 2.0      | 7.0      | 9.0      | 18.0     | 7.0    | 2.0    | 6.0    | 15.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 2.0      | 6.0      | 15.0     | 10.0     | 0.0      | 12.0     | 22.0     | 6.75     | 0.0      | 3.5      | 10.25    | 16.0     | 8.75     | 38.25    | 63.0     | 32.75    | 8.75     | 53.75    | 95.25    | 5.0      | 27.0     | 46.25    | 78.25    | 46.75    | 44.75    | 115.0    | 206.5    | 10.0    | 0.0     | 12.0    | 22.0    | 6.75     | 0.5      | 3.5      | 10.75    | 2.75    | 2.0     | 0.0     | 4.75    | 8.0    | 7.0    | 37.5   | 52.5   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 3        | 0        | 0        | 0       | 0       | 0        | 643042.0  | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | N        | N        | N        | N        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | N      | N   | Y      | N        | N        |                                   | Y        | Y        | Y        | N        | Y        | Y      | Y        | N        | Y       | 10       | 773020800 | 804470400 | 49       | 4       | 0       | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 1       | 0       | 0       | 1       | 1        | 0        | 0        | 1        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 53000    | 0     | 0     | 0     | 57       | -1      | Y      | 16547  | 9434   | 2595    | 2775     | -1       | Y      | N        | 16     | 480      | 125      | 20       | 1.0      | 3.0      | 6.0      | 10.0     | 5.5    | 2.0    | 0.0    | 7.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 5.5      | 2.0      | 0.0      | 7.5      | 3.5      | 1.0      | 2.0      | 6.5      | 0.0      | 1.0      | 3.0      | 4.0      | 4.0      | 1.0      | 21.2     | 26.2     | 7.5      | 3.0      | 26.2     | 36.7     | 0.0      | 13.0     | 12.97    | 25.97    | 14.0     | 21.0     | 45.17    | 80.17    | 0.35    | 0.25    | 0.1     | 0.7     | 0.15     | 0.05     | 0.0      | 0.2      | 0.85    | 0.5     | 0.0     | 1.35    | 4.0    | 1.0    | 21.2   | 26.2   | 0.3    | 0.0    | 0.0    | 0.3    | 0.0    | 0.0    | 0.0    | 0.0    | 0.3      | 0.0      | 0.0      | 0.3      | 0.0      | 0.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0       | 8939    | 0        | 1580976.0 | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | Y        | N        | N        | Y        | N        |                            | N        | N        | Y        | Y        | N        | Y        | N     | N    | Y      | N   | Y      | Y        | Y        | VIRGINIANA, TOBACCO, VITICULTURE  | Y        | N        | Y        | N        | Y        | Y      | Y        | Y        | Y       | 12       | 773020800 | 804470400 | 45       | 0       | 0       | 1       | 0        | 0        | 1        | 1       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 1        | 1      | 0      | 0      | 1      | 687802   | 0     | 954   | 0     | 834      | 575264  | Y      | 224429 | 16393  | 582     | 89875    | 47880    | Y      | Y        | 81     | 1236     | 103      | 10       | 1.0      | 4.0      | 2.0      | 7.0      | 5.0    | 0.0    | 1.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 2.0      | 5.0      | 0.0      | 7.0      | 7.0      | 5.0      | 1.0      | 13.0     | 7.0      | 5.0      | 14.0     | 26.0     | 4.0      | 0.0      | 10.0     | 14.0     | 1.0      | 6.0      | 3.0      | 10.0     | 12.0     | 11.0     | 27.0     | 50.0     | 6.0      | 23.0     | 34.0     | 63.0     | 26.0     | 43.0     | 64.0     | 133.0    | 0.75    | 0.0     | 0.0     | 0.75    | 1.0      | 0.0      | 0.0      | 1.0      | 4.0     | 2.0     | 1.0     | 7.0     | 0.0    | 0.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.3      | 0.0      | 0.0      | 0.3      | 0.0      | 0.0      | 0.0      | 0.0      | 5        | 1        | 0        | 0       | 0       | 0        | 1125000.0 | 
```