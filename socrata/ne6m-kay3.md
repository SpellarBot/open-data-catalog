# State Libraries Survey, FY 1998, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1998-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/ne6m-kay3) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ne6m-kay3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ne6m-kay3/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ne6m-kay3 |
| Name | State Libraries Survey, FY 1998, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1998, operations, workforce |
| Created | 2016-12-20T22:44:58Z |
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
| Yes      | series tag     | webaddr    | Web Address                                                | text      | text        |
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
| Yes      | series tag     | inrefreq   | Internet reference questions                               | text      | text        |
| Yes      | series tag     | accoldb    | DBs avail to other libr                                    | text      | text        |
| Yes      | series tag     | acccdrom   | CDROM union catalog                                        | text      | text        |
| Yes      | series tag     | accoclc    | OCLC participation                                         | text      | text        |
| Yes      | series tag     | acctlnet   | Telnet gateway                                             | text      | text        |
| Yes      | series tag     | accwbcat   | Union catalog                                              | text      | text        |
| Yes      | series tag     | acczgway   | Z39.50 gateway                                             | text      | text        |
| Yes      | series tag     | accoth     | Other access to other libr                                 | text      | text        |
| Yes      | series tag     | othaccsp   | Other access specified                                     | text      | text        |
| Yes      | series tag     | erateapp   | E-rate discount                                            | text      | text        |
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
| Yes      | numeric metric | stfterms   | Staff only terminals                                       | number    | number      |
| Yes      | numeric metric | pubterms   | Public terminals                                           | number    | number      |
| Yes      | numeric metric | totterms   | Total terminals                                            | number    | number      |
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
series e:ne6m-kay3 d:1997-07-01T00:00:00.000Z t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:acccdrom=N t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571.0 t:webaddr=WWW.STATE.AK.US/LAM/LIBRARY.HTML t:acctlnet=Y t:othallop=N t:netgoph=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:elecbibl=Y t:phys_st=AK t:netsub=Y t:fddeplib=Y t:starchiv=Y t:strecmng=Y t:accoth=Y t:largerag=X t:erateapp=N t:gencol=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:pub_fips=2 t:inrefreq=Y t:elecoper=Y t:referral=Y t:accoclc=Y t:accoldb=Y t:elecplan=Y t:physzip=99811 t:electext=Y t:stlahost=N t:mailzip4=571.0 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:walkin=Y t:nettrain=Y t:execbran=X t:netequip=Y t:accwbcat=Y t:acczgway=N t:regional=N t:depteduc=X t:stlegref=N t:selectiv=Y m:lllrng=0 m:totalldc=1 m:totalldb=0 m:totallda=5 m:othersva=0 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=81884 m:othersvd=3 m:othersvc=2 m:lstecsva=2 m:lstecsvd=5 m:video=360 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=2 m:aendseb=1 m:aendsec=2 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=1246 m:lbstasea=0.5 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.5 m:mon2fri=0 m:otherout=1 m:aendsed=5 m:lsothlsb=0 m:lsothlsa=3 m:admservd=6 m:admserva=2 m:litprseb=0 m:litprsea=0 m:admservc=4 m:admservb=0 m:lspubsvb=0 m:lspubsva=5 m:lspubsvd=11 m:litprsed=0 m:lspubsvc=6 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=109 m:corouta=0 m:lstasea=0.4 m:recfrom=1626 m:ilssed=0 m:bphoutc=0 m:lstased=0.4 m:bphoutb=1 m:ilsseb=0 m:lstasec=0 m:bphouta=0 m:ilssec=0 m:lstaseb=0 m:ldschc=0.5 m:ldschb=0 m:bphoutd=1 m:ldscha=1 m:ldschd=1.5 m:stfterms=33 m:totalout=2 m:onsitmon=25 m:ilssea=0 m:readsch=0 m:circ=3837 m:tothrswk=40 m:ldpuba=1 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=1.5 m:pubterms=16 m:mainout=1 m:bkservol=105346 m:govdoc=85000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=611300 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=3 m:totallsd=22 m:ldothlbb=0 m:totallsc=12 m:ldothlbc=0 m:ldothlbd=3 m:totterms=49 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=10 m:gvemoutb=0 m:gvemouta=1 m:provto=1891 m:markcomd=0 m:subscrip=1567 m:grantmon=114 m:bphsea=0.1 m:cyasea=0 m:cyaseb=0 m:bphsec=2 m:cyasec=0 m:reftrans=16470 m:bphseb=0 m:cyased=0 m:audio=90 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.5 m:bphsed=2.1 m:staidseb=0 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=6 m:lsothlsc=3 m:totstafc=19 m:totstafd=37 m:totstafa=17 m:totstafb=1

series e:ne6m-kay3 d:1997-10-01T00:00:00.000Z t:appbygov=X t:physcity=MONTGOMERY t:gencol=Y t:mailcity=MONTGOMERY t:pub_fips=1 t:inrefreq=Y t:referral=Y t:physaddr="6030 MONTICELLO DRIVE" t:elecoper=N t:stlacont=N t:mailzip=36130 t:netmount=Y t:accoclc=Y t:acccdrom=Y t:mailaddr="6030 MONTICELLO DRIVE" t:accoldb=Y t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1.0 t:elecplan=Y t:acctlnet=Y t:webaddr=WWW.APLS.STATE.AL.US t:othallop=N t:netgoph=Y t:physzip=36117 t:electext=N t:boardcom=X t:stdeplib=N t:sthstmus=N t:stlahost=N t:mail_st=AL t:phys_st=AL t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=1.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=N t:indepag=X t:acczgway=Y t:accwbcat=Y t:starchiv=N t:accoth=N t:strecmng=N t:regional=N t:selectiv=Y t:stlegref=N t:erateapp=N m:lllrng=0 m:totalldc=1 m:totalldb=0 m:totallda=7 m:othersva=3 m:othersvb=0 m:totalldd=8 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=20112 m:othersvd=11 m:othersvc=8 m:lstecsva=1 m:lstecsvd=4 m:video=4778 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=1 m:aendseb=1 m:aendsec=2 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=957 m:lbstasea=0 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0 m:mon2fri=0 m:otherout=0 m:aendsed=4 m:lsothlsb=0 m:lsothlsa=0 m:admservd=18 m:admserva=1 m:litprseb=0 m:litprsea=0 m:admservc=14 m:admservb=3 m:lspubsvb=0 m:lspubsva=13 m:lspubsvd=24 m:litprsed=0 m:lspubsvc=11 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=51 m:corouta=0 m:lstasea=1 m:recfrom=2721 m:ilssed=0 m:bphoutc=0 m:lstased=4 m:bphoutb=0 m:ilsseb=0 m:lstasec=2 m:bphouta=1 m:ilssec=0 m:lstaseb=1 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:ldschd=0 m:stfterms=48 m:totalout=1 m:onsitmon=7 m:ilssea=0 m:readsch=0 m:circ=5264 m:tothrswk=45 m:ldpuba=7 m:ldpubb=0 m:ldpubc=1 m:ldpubd=8 m:pubterms=2 m:mainout=1 m:bkservol=172318 m:govdoc=3000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=4137511 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=28 m:ldothlbb=0 m:totallsc=14 m:ldothlbc=0 m:ldothlbd=0 m:totterms=50 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=14 m:gvemoutb=0 m:gvemouta=1 m:provto=9885 m:markcomd=0 m:subscrip=1603 m:grantmon=314 m:bphsea=3 m:cyasea=0 m:cyaseb=0 m:bphsec=7 m:cyasec=0 m:reftrans=14635 m:bphseb=0 m:cyased=0 m:audio=256500 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=1 m:bphsed=10 m:staidseb=1 m:staidsec=2 m:staidsed=4 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=37 m:totstafd=65 m:totstafa=25 m:totstafb=3

series e:ne6m-kay3 d:1997-07-01T00:00:00.000Z t:physcity="LITTLE ROCK" t:gencol=Y t:mailcity="LITTLE ROCK" t:pub_fips=5 t:inrefreq=Y t:referral=Y t:elecoper=Y t:stlacont=N t:physaddr="ONE CAPITOL MALL" t:mailzip=72201 t:netmount=Y t:accoclc=Y t:acccdrom=N t:mailaddr="ONE CAPITOL MALL" t:accoldb=Y t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1081.0 t:elecplan=Y t:acctlnet=Y t:webaddr=WWW.ASL.LIB.AR.US t:othallop=N t:netgoph=Y t:physzip=72201 t:electext=Y t:stdeplib=Y t:sthstmus=N t:stlahost=N t:mail_st=AR t:phys_st=AR t:elecbibl=Y t:walkin=Y t:netsub=Y t:mailzip4=1081.0 t:nettrain=Y t:execbran=X t:fddeplib=Y t:netequip=Y t:acczgway=Y t:accwbcat=Y t:starchiv=N t:accoth=N t:strecmng=N t:regional=Y t:depteduc=X t:largerag=X t:selectiv=N t:stlegref=N t:erateapp=N m:lllrng=0 m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=1 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=11516 m:othersvd=2 m:othersvc=0 m:lstecsva=6 m:lstecsvd=24 m:video=16518 m:lstecsvc=14 m:lstecsvb=4 m:aendsea=1 m:aendseb=1 m:aendsec=0 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=693 m:lbstasea=0.25 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.25 m:mon2fri=0 m:otherout=0 m:aendsed=2 m:lsothlsb=0 m:lsothlsa=4 m:admservd=16 m:admserva=3 m:litprseb=0 m:litprsea=0 m:admservc=8 m:admservb=5 m:lspubsvb=2 m:lspubsva=4 m:lspubsvd=11 m:litprsed=0 m:lspubsvc=5 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:coroutc=0 m:events=13 m:corouta=0 m:lstasea=1 m:recfrom=316 m:ilssed=0.5 m:bphoutc=0 m:lstased=1 m:bphoutb=0 m:ilsseb=0 m:lstasec=0 m:bphouta=1 m:ilssec=0 m:lstaseb=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:ldschd=0 m:stfterms=52 m:totalout=1 m:onsitmon=13 m:ilssea=0.5 m:readsch=0 m:circ=11867 m:tothrswk=45 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:pubterms=2 m:mainout=1 m:bkservol=95101 m:govdoc=1821954 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:adlit=0 m:period_e=2274511 m:sat2sun=0 m:ldspecc=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=44.5 m:ldothlbb=0 m:totallsc=24.5 m:ldothlbc=0 m:ldothlbd=0 m:totterms=54 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=6 m:markcoma=0 m:gvemoutc=0 m:totallsa=14 m:gvemoutb=0 m:gvemouta=1 m:provto=13730 m:markcomd=0 m:subscrip=1081 m:grantmon=26 m:bphsea=2 m:cyasea=0.5 m:cyaseb=0 m:bphsec=6 m:cyasec=0 m:reftrans=5598 m:bphseb=1 m:cyased=0.5 m:audio=580 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=9 m:staidseb=0.25 m:staidsec=0 m:staidsed=0.25 m:lsothlsd=9.5 m:lsothlsc=5.5 m:totstafc=34.5 m:totstafd=68.5 m:totstafa=22 m:totstafb=12
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

metric m:stfterms p:float l:"Staff only terminals" t:dataTypeName=number

metric m:pubterms p:float l:"Public terminals" t:dataTypeName=number

metric m:totterms p:float l:"Total terminals" t:dataTypeName=number

metric m:readsch p:double l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adlit p:double l:"Grants to assist/adult literacy" t:dataTypeName=money

metric m:lllrng p:double l:"Grants to assist/lifelong learning" t:dataTypeName=money

metric m:period_e p:double l:"Population estimate NCES" t:dataTypeName=number

entity e:ne6m-kay3 l:"State Libraries Survey, FY 1998, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ne6m-kay3

property e:ne6m-kay3 t:meta.view v:id=ne6m-kay3 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1998, Part 1: Operations & Workforce" v:attribution=IMLS

property e:ne6m-kay3 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ne6m-kay3 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:ne6m-kay3 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:ne6m-kay3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                         | mailcity    | mail_st | mailzip | mailzip4 | webaddr                          | judbran | legbran | execbran | indepag | governor | boardcom | appbygov | appbyoth | exoffmem | electmem | largerag | depteduc | deptcult | deptstat | otherag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp        | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | nettrain | netsub | netequip | netmount | netgoph | inrefreq | accoldb | acccdrom | accoclc | acctlnet | accwbcat | acczgway | accoth | othaccsp                                           | erateapp | pub_fips | fystart   | fyend     | tothrswk | mon2fri | sat2sun | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol | audio    | video   | subscrip | govdoc    | gencol | circ    | provto  | recfrom | reftrans | libvists | walkin | referral | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lstasea | lstaseb | lstasec | lstased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | markcoma | markcomb | markcomc | markcomd | stfterms | pubterms | totterms | readsch   | adlit     | lllrng    | period_e   | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ================================ | =========== | ======= | ======= | ======== | ================================ | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =============== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======= | ======== | ======== | ======== | ====== | ================================================== | ======== | ======== | ========= | ========= | ======== | ======= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ======== | ======== | ======= | ======== | ========= | ====== | ======= | ======= | ======= | ======== | ======== | ====== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571.0    | P.O. BOX 110571                  | JUNEAU      | AK      | 99811   | 571.0    | WWW.STATE.AK.US/LAM/LIBRARY.HTML |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | N        |                 | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | N        | Y       | Y        | Y        | N        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE              | N        | 2        | 867715200 | 899164800 | 40.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 105346.0 | 90.0     | 360.0   | 1567.0   | 85000.0   | Y      | 3837.0  | 1891.0  | 1626.0  | 16470.0  | 81884.0  | Y      | Y        | 109.0  | 1246.0   | 114.0    | 25.0     | 2.0      | 0.0      | 4.0      | 6.0      | 1.0    | 0.0    | 0.5    | 1.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 0.0      | 3.0      | 5.0      | 0.0      | 1.0      | 6.0      | 5.0      | 0.0      | 6.0      | 11.0     | 2.0      | 0.0      | 3.0      | 5.0      | 3.0      | 0.0      | 3.0      | 6.0      | 10.0     | 0.0      | 12.0     | 22.0     | 0.0      | 1.0      | 2.0      | 3.0      | 17.0     | 1.0      | 19.0     | 37.0     | 0.4     | 0.0     | 0.0     | 0.4     | 0.5      | 0.0      | 0.0      | 0.5      | 2.0     | 1.0     | 2.0     | 5.0     | 0.1    | 0.0    | 2.0    | 2.1    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 33.0     | 16.0     | 49.0     | 0.0       | 0.0       | 0.0       | 611300.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1.0      | 6030 MONTICELLO DRIVE            | MONTGOMERY  | AL      | 36130   | 1.0      | WWW.APLS.STATE.AL.US             |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | N        | Y        | N        | Y        | Y        | N        | Y        | N        | Y        | Y      | N        | Y        | Y       | Y        | Y       | Y        | Y       | Y        | Y        | Y        | N      |                                                    | N        | 1        | 875664000 | 907113600 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 172318.0 | 256500.0 | 4778.0  | 1603.0   | 3000.0    | Y      | 5264.0  | 9885.0  | 2721.0  | 14635.0  | 20112.0  | Y      | Y        | 51.0   | 957.0    | 314.0    | 7.0      | 1.0      | 3.0      | 14.0     | 18.0     | 7.0    | 0.0    | 1.0    | 8.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 0.0      | 1.0      | 8.0      | 13.0     | 0.0      | 11.0     | 24.0     | 1.0      | 0.0      | 3.0      | 4.0      | 0.0      | 0.0      | 0.0      | 0.0      | 14.0     | 0.0      | 14.0     | 28.0     | 3.0      | 0.0      | 8.0      | 11.0     | 25.0     | 3.0      | 37.0     | 65.0     | 1.0     | 1.0     | 2.0     | 4.0     | 1.0      | 1.0      | 2.0      | 4.0      | 1.0     | 1.0     | 2.0     | 4.0     | 3.0    | 0.0    | 7.0    | 10.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 48.0     | 2.0      | 50.0     | 0.0       | 0.0       | 0.0       | 4137511.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL                              | LITTLE ROCK | AR      | 72201   | 1081.0   | ONE CAPITOL MALL                 | LITTLE ROCK | AR      | 72201   | 1081.0   | WWW.ASL.LIB.AR.US                |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | N        | Y       | Y        | Y        | Y        | N      |                                                    | N        | 5        | 867715200 | 899164800 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 95101.0  | 580.0    | 16518.0 | 1081.0   | 1821954.0 | Y      | 11867.0 | 13730.0 | 316.0   | 5598.0   | 11516.0  | Y      | Y        | 13.0   | 693.0    | 26.0     | 13.0     | 3.0      | 5.0      | 8.0      | 16.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 4.0      | 2.0      | 5.0      | 11.0     | 6.0      | 4.0      | 14.0     | 24.0     | 4.0      | 0.0      | 5.5      | 9.5      | 14.0     | 6.0      | 24.5     | 44.5     | 1.0      | 1.0      | 0.0      | 2.0      | 22.0     | 12.0     | 34.5     | 68.5     | 1.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.25     | 0.0      | 0.25     | 1.0     | 1.0     | 0.0     | 2.0     | 2.0    | 1.0    | 6.0    | 9.0    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 0.25     | 0.0      | 0.0      | 0.25     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 52.0     | 2.0      | 54.0     | 0.0       | 0.0       | 0.0       | 2274511.0  | 
| DEPARTMENT OF LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896.0   | 1700 WEST WASHINGTON - SUITE 200 | PHOENIX     | AZ      | 85007   | 2896.0   | WWW.LIB.AZ.US                    |         | X       |          |         |          |          |          |          |          |          |          |          |          |          |         |         | Y        | Y        | Y        | Y        | N        |                 | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | N        | Y       | N        | N        | Y        | Y      | LINKS TO OTHER WEB-BASED CATALOGS FROM OUR WEBSITE | Y        | 4        | 867715200 | 899164800 | 360.0    | 0.0     | 5.0     | 8.0     | 0.0      | 0.0      | 8.0      | 1.0     | 0.0     | 0.0     | 1.0     | 3.0     | 0.0     | 0.0     | 3.0     | 3.0      | 0.0      | 0.0      | 3.0      | 7.0      | 0.0      | 0.0      | 7.0      | 5.0    | 0.0    | 0.0    | 5.0    | 235031.0 | 14897.0  | 447.0   | 651.0    | 816760.0  | Y      | 1827.0  | 1265.0  | 1019.0  | 55947.0  | 76006.0  | Y      | Y        | 80.0   | 1660.0   | 15.0     | 6.0      | 2.0      | 1.0      | 8.0      | 11.0     | 5.0    | 0.0    | 5.0    | 10.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 5.0      | 0.0      | 5.0      | 10.0     | 18.0     | 6.0      | 14.0     | 38.0     | 7.0      | 1.0      | 10.0     | 18.0     | 0.0      | 1.0      | 3.0      | 4.0      | 25.0     | 8.0      | 27.0     | 60.0     | 0.0      | 13.0     | 21.0     | 34.0     | 32.0     | 22.0     | 61.0     | 115.0    | 0.5     | 0.0     | 0.0     | 0.5     | 0.5      | 0.0      | 0.0      | 0.5      | 1.0     | 0.0     | 0.0     | 1.0     | 6.0    | 5.0    | 11.0   | 22.0   | 0.25   | 0.0    | 0.0    | 0.25   | 0.0    | 0.0    | 0.0    | 0.0    | 0.25     | 0.0      | 0.0      | 0.25     | 0.1      | 0.0      | 0.0      | 0.1      | 0.0      | 0.0      | 0.0      | 0.0      | 130.0    | 30.0     | 160.0    | 51126.0   | 0.0       | 1823142.0 | 4595379.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 0.0      | P.O. BOX 942837                  | SACRAMENTO  | CA      | 94237   | 1.0      | WWW.LIBRARY.CA.GOV               |         |         | X        | X       | X        |          |          |          |          |          |          |          |          |          |         |         | N        | Y        | N        | N        | N        |                 | Y        | N        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | Y      | Y        | Y        | Y       | N        | N       | Y        | Y       | Y        | Y        | Y        | N      |                                                    | N        | 6        | 867715200 | 899164800 | 140.0    | 0.0     | 0.0     | 2.0     | 3.0      | 0.0      | 5.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 2.0      | 3.0      | 0.0      | 5.0      | 2.0    | 2.0    | 0.0    | 4.0    | 747770.0 | 547.0    | 349.0   | 7130.0   | 4048793.0 | Y      | 46690.0 | 18272.0 | 387.0   | 119826.0 | -1.0     | Y      | N        | 228.0  | 8631.0   | 386.0    | 119.0    | 5.0      | 4.0      | 32.0     | 41.0     | 11.0   | 4.0    | 10.0   | 25.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 11.0     | 4.0      | 10.0     | 25.0     | 17.0     | 0.0      | 27.0     | 44.0     | 9.5      | 0.0      | 27.5     | 37.0     | 6.5      | 0.0      | 17.0     | 23.5     | 33.0     | 0.0      | 71.5     | 104.5    | 6.5      | 20.0     | 7.0      | 33.5     | 55.5     | 28.0     | 120.5    | 204.0    | 2.0     | 0.0     | 0.5     | 2.5     | 1.0      | 0.0      | 3.0      | 4.0      | 5.5     | 2.0     | 5.5     | 13.0    | 3.0    | 0.0    | 18.0   | 21.0   | 1.0    | 0.0    | 0.5    | 1.5    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.5      | 1.5      | 0.0      | 2.0      | 0.5      | 2.5      | 0.25     | 0.0      | 0.0      | 0.25     | 255.0    | 24.0     | 279.0    | 1598195.0 | 3849028.0 | 2423324.0 | 32617665.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704.0   | 201 EAST COLFAX AVENUE, #309     | DENVER      | CO      | 80203   | 1704.0   | WWW.CDE.STATE.CO.US/SLINDEX.HTM  |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | N        | N        | N        | N        | N        |                 | Y        | Y        | Y        | N        | N        | N        | Y        | Y        | N        | N        | Y        | N      | N        | Y        | Y       | Y        | Y       | N        | Y       | Y        | N        | N        | N      |                                                    | Y        | 8        | 867715200 | 899164800 | 47.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 3.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 1.0    | 0.0    | 1.0    | 27318.0  | 26.0     | 103.0   | 131.0    | 325.0     | N      | 5961.0  | 661.0   | 496.0   | 2511.0   | 13250.0  | Y      | Y        | 17.0   | 442.0    | 41.0     | 26.0     | 2.5      | 2.75     | 3.7      | 8.95     | 0.5    | 0.0    | 0.0    | 0.5    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 1.3      | 1.0      | 5.3      | 4.5      | 1.3      | 1.0      | 6.8      | 5.5      | 1.0      | 2.0      | 8.5      | 0.75     | 0.0      | 1.5      | 2.25     | 0.5      | 0.0      | 7.5      | 8.0      | 6.75     | 1.0      | 11.0     | 18.75    | 0.5      | 0.5      | 1.0      | 2.0      | 14.25    | 5.55     | 16.7     | 36.5     | 0.0     | 1.0     | 0.3     | 1.3     | 0.1      | 0.0      | 0.1      | 0.2      | 2.0     | 0.0     | 0.0     | 2.0     | 2.0    | 1.0    | 8.5    | 11.5   | 1.0    | 0.0    | 0.0    | 1.0    | 4.5    | 1.0    | 0.0    | 5.5    | 0.0      | 1.75     | 0.3      | 2.05     | 0.0      | 0.3      | 0.0      | 0.3      | 0.0      | 0.0      | 1.0      | 1.0      | 37.0     | 3.0      | 40.0     | 0.0       | 0.0       | 87749.0   | 3892644.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537.0   | 231 CAPITOL AVENUE               | HARTFORD    | CT      | 6106    | 1537.0   | WWW.CSLIB.ORG                    |         |         | X        |         |          |          |          |          |          |          | X        | X        |          |          |         |         | Y        | N        | Y        | Y        | Y        | ARTS COMMISSION | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | N       | N        | Y        | N        | N      |                                                    | Y        | 9        | 867715200 | 899164800 | 40.0     | 0.0     | 0.0     | 1.0     | 3.0      | 0.0      | 4.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 977087.0 | 200.0    | 20.0    | 9910.0   | 1646700.0 | N      | 283.0   | 616.0   | 202.0   | 111797.0 | 131517.0 | Y      | N        | 55.0   | 1015.0   | 88.0     | 19.0     | 3.0      | 6.0      | 12.0     | 21.0     | 8.0    | 0.0    | 20.0   | 28.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 8.0      | 0.0      | 20.0     | 28.0     | 17.0     | 1.0      | 9.0      | 27.0     | 6.0      | 4.0      | 7.0      | 17.0     | 3.0      | 2.0      | 12.0     | 17.0     | 26.0     | 7.0      | 28.0     | 61.0     | 1.0      | 4.0      | 5.0      | 10.0     | 38.0     | 17.0     | 65.0     | 120.0    | 1.0     | 1.0     | 1.0     | 3.0     | 1.0      | 0.0      | 0.0      | 1.0      | 2.0     | 2.0     | 0.0     | 4.0     | 2.0    | 0.0    | 9.0    | 11.0   | 2.0    | 0.0    | 0.0    | 2.0    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 67.0     | 25.0     | 92.0     | 61137.0   | 64425.0   | 38750.0   | 3274238.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599.0   | 901 G STREET, N.W.               | WASHINGTON  | DC      | 20001   | 4599.0   | WWW.DCLIBRARY.ORG                |         |         | X        | X       |          | X        | X        |          |          |          |          |          |          |          |         |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N      | Y        | Y        | Y       | N        | N       | N        | Y       | N        | N        | N        | N      |                                                    | Y        | 11       | 875664000 | 907113600 | 0.0      | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0      | 0.0      | 0.0     | 0.0      | 0.0       | N      | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | N      | N        | 35.0   | 666.0    | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 4.0      | 2.0      | 10.0     | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.25    | 0.0     | 0.0     | 0.25    | 0.25   | 1.0    | 0.0    | 1.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 1.0      | 0.0      | 1.25     | 0.1      | 0.1      | 0.0      | 0.2      | 0.0      | 0.0      | 0.0      | 0.0       | 0.0       | 0.0       | 543000.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430.0   | 43 SOUTH DUPONT HIGHWAY          | DOVER       | DE      | 19901   | 7430.0   | WWW.LIB.DE.US                    |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | N        | N        | N        | N        | N        |                 | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | N        | Y       | Y        | Y       | Y        | N        | N        | Y      | WEB PAGE ACCESS                                    | Y        | 10       | 867715200 | 899164800 | 47.0     | 4.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 1035.0   | 0.0      | 0.0     | 54.0     | 33665.0   | N      | 1625.0  | 21.0    | 52.0    | 2999.0   | 18100.0  | Y      | N        | 32.0   | 413.0    | 30.0     | 5.0      | 1.0      | 1.0      | 2.0      | 4.0      | 3.25   | 0.75   | 0.0    | 4.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 1.0      | 0.0      | 1.0      | 3.25     | 1.75     | 0.0      | 5.0      | 1.0      | 1.0      | 1.0      | 3.0      | 1.25     | 1.0      | 0.0      | 2.25     | 0.5      | 2.25     | 3.0      | 5.75     | 2.75     | 4.25     | 4.0      | 11.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 7.0      | 6.0      | 20.0     | 0.25    | 0.25    | 0.0     | 0.5     | 0.25     | 0.25     | 0.0      | 0.5      | 2.3     | 2.0     | 0.0     | 4.3     | 0.5    | 1.0    | 2.0    | 3.5    | 0.1    | 0.0    | 0.1    | 0.2    | 0.0    | 0.4    | 0.0    | 0.4    | 0.0      | 0.25     | 0.0      | 0.25     | 0.1      | 0.0      | 0.0      | 0.1      | 0.0      | 0.0      | 0.0      | 0.0      | 20.0     | 2.0      | 22.0     | 0.0       | 0.0       | 0.0       | 666168.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250.0    | 500 SOUTH BRONOUGH               | TALLAHASSEE | FL      | 32399   | 250.0    | WWW.DOS.STATE.FL.US/DLIS         |         |         | X        |         |          |          |          |          |          |          | X        |          |          | X        |         |         | Y        | N        | N        | Y        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | N        | Y       | N        | N        | N        | N      |                                                    | Y        | 12       | 867715200 | 899164800 | 51.0     | 0.0     | 6.0     | 1.0     | 1.0      | 0.0      | 2.0      | 1.0     | 1.0     | 0.0     | 2.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 308290.0 | 454.0    | 8678.0  | 769.0    | 209637.0  | Y      | 76620.0 | 35657.0 | 4088.0  | 111082.0 | 73960.0  | Y      | Y        | 41.0   | 1780.0   | 285.0    | 285.0    | 2.0      | 1.0      | 8.0      | 11.0     | 9.0    | 0.0    | 4.0    | 13.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 0.0      | 2.0      | 6.0      | 13.0     | 0.0      | 6.0      | 19.0     | 13.0     | 0.0      | 11.0     | 24.0     | 3.5      | 0.0      | 5.0      | 8.5      | 0.0      | 1.0      | 2.0      | 3.0      | 16.5     | 1.0      | 18.0     | 35.5     | 0.0      | 17.0     | 34.5     | 51.5     | 31.5     | 19.0     | 66.5     | 117.0    | 2.15    | 0.0     | 1.85    | 4.0     | 0.85     | 0.0      | 0.65     | 1.5      | 2.85    | 1.0     | 0.95    | 4.8     | 0.1    | 0.1    | 0.05   | 0.25   | 0.5    | 0.0    | 0.25   | 0.75   | 0.15   | 0.0    | 0.05   | 0.2    | 0.15     | 0.0      | 0.05     | 0.2      | 0.1      | 0.0      | 0.05     | 0.15     | 0.0      | 0.0      | 0.0      | 0.0      | 148.0    | 21.0     | 169.0    | 88095.0   | 0.0       | 91917.0   | 14712922.0 | 
```