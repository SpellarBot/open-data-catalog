# State Libraries Survey, FY 2005, Part 2: SLAA-Provided Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2005-part-2-slaa-provided-services) |
| Metadata | [Link](https://data.imls.gov/api/views/9uhv-6je7) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/9uhv-6je7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/9uhv-6je7/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 9uhv-6je7 |
| Name | State Libraries Survey, FY 2005, Part 2: SLAA-Provided Services |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2005, slaa-provided services |
| Created | 2016-12-20T15:26:53Z |
| Publication Date | 2016-12-20T17:04:35Z |
| Rows Updated | 2016-12-20T17:21:22Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                               | Data Type | Render Type |
| ======== | ============== | ========== | ================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                          | text      | text        |
| Yes      | series tag     | physaddr   | Street                             | text      | text        |
| Yes      | series tag     | physcity   | City                               | text      | text        |
| Yes      | series tag     | phys_st    | State                              | text      | text        |
| Yes      | series tag     | physzip    | Zip                                | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                              | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                      | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                        | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                       | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                         | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                       | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                        | text      | text        |
| Yes      | numeric metric | accrliba   | Accredits (pub)                    | number    | text        |
| Yes      | numeric metric | accrlibb   | Accredits (acad)                   | number    | text        |
| Yes      | numeric metric | accrlibc   | Accredits (school)                 | number    | text        |
| Yes      | numeric metric | accrlibd   | Accredits (special)                | number    | text        |
| Yes      | numeric metric | accrlibe   | Accredits (Co-ops)                 | number    | text        |
| Yes      | numeric metric | lstasva    | Admins LSTA grants (pub)           | number    | text        |
| Yes      | numeric metric | lstasvb    | Admins LSTA grants (acad)          | number    | text        |
| Yes      | numeric metric | lstasvc    | Admins LSTA grants (school)        | number    | text        |
| Yes      | numeric metric | lstasvd    | Admins LSTA grants (special)       | number    | text        |
| Yes      | numeric metric | lstasve    | Admins LSTA grants (Co-ops)        | number    | text        |
| Yes      | numeric metric | staidsva   | Admins state aid (pub)             | number    | text        |
| Yes      | numeric metric | staidsvb   | Admins state aid (acad)            | number    | text        |
| Yes      | numeric metric | staidsvc   | Admins state aid (school)          | number    | text        |
| Yes      | numeric metric | staidsvd   | Admins state aid (special)         | number    | text        |
| Yes      | numeric metric | staidsve   | Admins state aid (Co-ops)          | number    | text        |
| Yes      | numeric metric | certliba   | Certs librarians (pub)             | number    | text        |
| Yes      | numeric metric | certlibb   | Certs librarians (acad)            | number    | text        |
| Yes      | numeric metric | certlibc   | Certs librarians (school)          | number    | text        |
| Yes      | numeric metric | certlibd   | Certs librarians (special)         | number    | text        |
| Yes      | numeric metric | certlibe   | Certs librarians (Co-ops)          | number    | text        |
| Yes      | numeric metric | collbsta   | Collects stats (pub)               | number    | text        |
| Yes      | numeric metric | collbstb   | Collects stats (acad)              | number    | text        |
| Yes      | numeric metric | collbstc   | Collects stats (school)            | number    | text        |
| Yes      | numeric metric | collbstd   | Collects stats (special)           | number    | text        |
| Yes      | numeric metric | collbste   | Collects stats (Co-ops)            | number    | text        |
| Yes      | numeric metric | cnsltsva   | Consulting svcs (pub)              | number    | text        |
| Yes      | numeric metric | cnsltsvb   | Consulting svcs (acad)             | number    | text        |
| Yes      | numeric metric | cnsltsvc   | Consulting svcs (school)           | number    | text        |
| Yes      | numeric metric | cnsltsvd   | Consulting svcs (special)          | number    | text        |
| Yes      | numeric metric | cnsltsve   | Consulting svcs (Co-ops)           | number    | text        |
| Yes      | numeric metric | cntedpra   | ConEd programs (pub)               | number    | text        |
| Yes      | numeric metric | cntedprb   | ConEd programs (acad)              | number    | text        |
| Yes      | numeric metric | cntedprc   | ConEd programs (school)            | number    | text        |
| Yes      | numeric metric | cntedprd   | ConEd programs (special)           | number    | text        |
| Yes      | numeric metric | cntedpre   | ConEd programs (Co-ops)            | number    | text        |
| Yes      | numeric metric | cooppura   | Coop Purchasing (pub)              | number    | text        |
| Yes      | numeric metric | cooppurb   | Coop Purchasing (acad)             | number    | text        |
| Yes      | numeric metric | cooppurc   | Coop Purchasing (school)           | number    | text        |
| Yes      | numeric metric | cooppurd   | Coop Purchasing (special)          | number    | text        |
| Yes      | numeric metric | cooppure   | Coop Purchasing (Co-ops)           | number    | text        |
| Yes      | numeric metric | illrefa    | ILL referral (pub)                 | number    | text        |
| Yes      | numeric metric | illrefb    | ILL referral (acad)                | number    | text        |
| Yes      | numeric metric | illrefc    | ILL referral (school)              | number    | text        |
| Yes      | numeric metric | illrefd    | ILL referral (special)             | number    | text        |
| Yes      | numeric metric | illrefe    | ILL referral (Co-ops)              | number    | text        |
| Yes      | numeric metric | liblega    | Legislation prep (pub)             | number    | text        |
| Yes      | numeric metric | liblegb    | Legislation prep (acad)            | number    | text        |
| Yes      | numeric metric | liblegc    | Legislation prep (school)          | number    | text        |
| Yes      | numeric metric | liblegd    | Legislation prep (special)         | number    | text        |
| Yes      | numeric metric | liblege    | Legislation prep (Co-ops)          | number    | text        |
| Yes      | numeric metric | libplana   | Planning/Eval/Rsch (pub)           | number    | text        |
| Yes      | numeric metric | libplanb   | Planning/Eval/Rsch (acad)          | number    | text        |
| Yes      | numeric metric | libplanc   | Planning/Eval/Rsch (school)        | number    | text        |
| Yes      | numeric metric | libpland   | Planning/Eval/Rsch (special)       | number    | text        |
| Yes      | numeric metric | libplane   | Planning/Eval/Rsch (Co-ops)        | number    | text        |
| Yes      | numeric metric | litprsva   | Literacy Prog Support (pub)        | number    | text        |
| Yes      | numeric metric | litprsvb   | Literacy Prog Support (acad)       | number    | text        |
| Yes      | numeric metric | litprsvc   | Literacy Prog Support (school)     | number    | text        |
| Yes      | numeric metric | litprsvd   | Literacy Prog Support (special)    | number    | text        |
| Yes      | numeric metric | litprsve   | Literacy Prog Support (Co-ops)     | number    | text        |
| Yes      | numeric metric | oclcgaca   | OCLC Grp Access (pub)              | number    | text        |
| Yes      | numeric metric | oclcgacb   | OCLC Grp Access (acad)             | number    | text        |
| Yes      | numeric metric | oclcgacc   | OCLC Grp Access (school)           | number    | text        |
| Yes      | numeric metric | oclcgacd   | OCLC Grp Access (special)          | number    | text        |
| Yes      | numeric metric | oclcgace   | OCLC Grp Access (Co-ops)           | number    | text        |
| Yes      | numeric metric | preserva   | Pres/Conserv (pub)                 | number    | text        |
| Yes      | numeric metric | preservb   | Pres/Conserv (acad)                | number    | text        |
| Yes      | numeric metric | preservc   | Pres/Conserv (school)              | number    | text        |
| Yes      | numeric metric | preservd   | Pres/Conserv (special)             | number    | text        |
| Yes      | numeric metric | preserve   | Pres/Conserv (Co-ops)              | number    | text        |
| Yes      | numeric metric | refrefa    | Ref referral (pub)                 | number    | text        |
| Yes      | numeric metric | refrefb    | Ref referral (acad)                | number    | text        |
| Yes      | numeric metric | refrefc    | Ref referral (school)              | number    | text        |
| Yes      | numeric metric | refrefd    | Ref referral (special)             | number    | text        |
| Yes      | numeric metric | refrefe    | Ref referral (Co-ops)              | number    | text        |
| Yes      | numeric metric | retrocva   | Biblio Conversion (pub)            | number    | text        |
| Yes      | numeric metric | retrocvb   | Biblio Conversion (acad)           | number    | text        |
| Yes      | numeric metric | retrocvc   | Biblio Conversion (school)         | number    | text        |
| Yes      | numeric metric | retrocvd   | Biblio Conversion (special)        | number    | text        |
| Yes      | numeric metric | retrocve   | Biblio Conversion (Co-ops)         | number    | text        |
| Yes      | numeric metric | ststanda   | State standards (pub)              | number    | text        |
| Yes      | numeric metric | ststandb   | State standards (acad)             | number    | text        |
| Yes      | numeric metric | ststandc   | State standards (school)           | number    | text        |
| Yes      | numeric metric | ststandd   | State standards (special)          | number    | text        |
| Yes      | numeric metric | ststande   | State standards (Co-ops)           | number    | text        |
| Yes      | numeric metric | swdigpra   | Digital prog/svc (pub)             | number    | text        |
| Yes      | numeric metric | swdigprb   | Digital prog/svc (acad)            | number    | text        |
| Yes      | numeric metric | swdigprc   | Digital prog/svc (school)          | number    | text        |
| Yes      | numeric metric | swdigprd   | Digital prog/svc (special)         | number    | text        |
| Yes      | numeric metric | swdigpre   | Digital prog/svc (Co-ops)          | number    | text        |
| Yes      | numeric metric | stwidpra   | PR (pub)                           | number    | text        |
| Yes      | numeric metric | stwidprb   | PR (acad)                          | number    | text        |
| Yes      | numeric metric | stwidprc   | PR (school)                        | number    | text        |
| Yes      | numeric metric | stwidprd   | PR (special)                       | number    | text        |
| Yes      | numeric metric | stwidpre   | PR (Co-ops)                        | number    | text        |
| Yes      | numeric metric | swvrsa     | Virtual Ref Svc (pub)              | number    | text        |
| Yes      | numeric metric | swvrsb     | Virtual Ref Svc (acad)             | number    | text        |
| Yes      | numeric metric | swvrsc     | Virtual Ref Svc (school)           | number    | text        |
| Yes      | numeric metric | swvrsd     | Virtual Ref Svc (special)          | number    | text        |
| Yes      | numeric metric | swvrse     | Virtual Ref Svc (Co-ops)           | number    | text        |
| Yes      | numeric metric | sumreada   | SRP support (pub)                  | number    | text        |
| Yes      | numeric metric | sumreadb   | SRP support (acad)                 | number    | text        |
| Yes      | numeric metric | sumreadc   | SRP support (school)               | number    | text        |
| Yes      | numeric metric | sumreadd   | SRP support (special)              | number    | text        |
| Yes      | numeric metric | sumreade   | SRP support (Co-ops)               | number    | text        |
| Yes      | numeric metric | uniondva   | Union list dev (pub)               | number    | text        |
| Yes      | numeric metric | uniondvb   | Union list dev (acad)              | number    | text        |
| Yes      | numeric metric | uniondvc   | Union list dev (school)            | number    | text        |
| Yes      | numeric metric | uniondvd   | Union list dev (special)           | number    | text        |
| Yes      | numeric metric | uniondve   | Union list dev (Co-ops)            | number    | text        |
| Yes      | numeric metric | univsera   | Univ Service prog (pub)            | number    | text        |
| Yes      | numeric metric | univserb   | Univ Service prog (acad)           | number    | text        |
| Yes      | numeric metric | univserc   | Univ Service prog (school)         | number    | text        |
| Yes      | numeric metric | univserd   | Univ Service prog (special)        | number    | text        |
| Yes      | numeric metric | univsere   | Univ Service prog (Co-ops)         | number    | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                    | text      | text        |
| Yes      | numeric metric | obereg     | BEA code                           | number    | text        |
| Yes      | numeric metric | rstatus    | Reporting Status                   | number    | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy   | date      | date        |
| Yes      | numeric metric | popu_st    | Population                         | number    | number      |
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
series e:9uhv-6je7 d:2004-07-01T00:00:00.000Z t:cntedpre=D t:cntedprd=D t:cntedprc=D t:cntedprb=D t:physaddr="333 WILLOUGHBY AVENUE" t:mailzip=99811 t:mailaddr="P.O. BOX 110571" t:cntedpra=D t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:sumreade=N t:sumreadd=N t:sumreadc=N t:sumreadb=N t:sumreada=D t:mail_st=AK t:ststande=D t:ststandd=N t:ststandc=D t:ststandb=N t:ststanda=D t:physcity=JUNEAU t:physzip=99811 t:retrocvc=N t:lstasvc=D t:collbste=N t:lstasvd=D t:retrocvd=N t:collbstd=N t:lstasve=D t:retrocva=N t:collbstc=D t:retrocvb=N t:collbstb=N t:collbsta=D t:lstasva=D t:retrocve=N t:lstasvb=D t:illrefb=D t:litprsvd=N t:illrefc=D t:litprsve=N t:illrefd=D t:illrefe=D t:litprsva=N t:litprsvb=N t:illrefa=D t:litprsvc=N t:liblegb=D t:liblega=D t:liblegd=D t:liblegc=D t:liblege=D t:swdigprd=N t:stwidprb=N t:swdigpre=N t:stwidpra=C t:swdigpra=D t:swdigprb=N t:swdigprc=N t:preservc=N t:preservd=N t:preserva=N t:preservb=N t:preserve=N t:oclcgace=D t:cooppurd=N t:oclcgacd=D t:cooppure=N t:oclcgacc=D t:oclcgacb=D t:webaddr=WWW.LIBRARY.STATE.AK.US t:oclcgaca=D t:cooppura=N t:cooppurb=N t:cooppurc=N t:stwidpre=C t:stwidprc=C t:stwidprd=N t:accrlibe=N t:accrlibd=N t:phys_st=AK t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=D t:accrlibc=N t:refrefb=D t:refrefc=D t:accrliba=N t:refrefd=D t:refrefe=D t:cnsltsve=D t:cnsltsvd=D t:cnsltsvc=D t:mailcity=JUNEAU t:pub_fips=2 t:uniondva=C t:uniondvb=C t:uniondvc=C t:uniondvd=C t:uniondve=C t:cnsltsva=D t:cnsltsvb=D t:swvrsa=N t:swvrsb=N t:libplana=D t:mailzip4=571 t:libpland=D t:libplane=D t:libplanb=D t:libplanc=D t:staidsva=D t:univsera=D t:staidsve=N t:staidsvd=N t:staidsvc=N t:staidsvb=N t:swvrsd=N t:swvrsc=N t:swvrse=N t:univserc=D t:univserb=N t:univsere=D t:univserd=N m:popu_st=663661 m:obereg=8 m:rstatus=1

series e:9uhv-6je7 d:2004-10-01T00:00:00.000Z t:cntedpre=D t:cntedprd=N t:cntedprc=N t:cntedprb=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:mailaddr="6030 MONTICELLO DRIVE" t:cntedpra=D t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:sumreade=D t:sumreadd=N t:sumreadc=N t:sumreadb=N t:sumreada=D t:mail_st=AL t:ststande=D t:ststandd=N t:ststandc=N t:ststandb=N t:ststanda=D t:physcity=MONTGOMERY t:physzip=36117 t:retrocvc=N t:lstasvc=N t:collbste=D t:lstasvd=N t:retrocvd=N t:collbstd=N t:lstasve=D t:retrocva=N t:collbstc=N t:retrocvb=N t:collbstb=N t:collbsta=D t:lstasva=D t:retrocve=N t:lstasvb=N t:illrefb=N t:litprsvd=N t:illrefc=N t:litprsve=D t:illrefd=N t:illrefe=D t:litprsva=D t:litprsvb=N t:illrefa=D t:litprsvc=N t:liblegb=N t:liblega=N t:liblegd=N t:liblegc=N t:liblege=N t:swdigprd=N t:stwidprb=N t:swdigpre=D t:stwidpra=D t:swdigpra=D t:swdigprb=N t:swdigprc=N t:preservc=N t:preservd=N t:preserva=N t:preservb=N t:preserve=N t:oclcgace=D t:cooppurd=N t:oclcgacd=N t:cooppure=N t:oclcgacc=N t:oclcgacb=N t:webaddr=WWW.APLS.STATE.AL.US t:oclcgaca=D t:cooppura=N t:cooppurb=N t:cooppurc=N t:stwidpre=D t:stwidprc=N t:stwidprd=N t:accrlibe=N t:accrlibd=N t:phys_st=AL t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=D t:accrlibc=N t:refrefb=D t:refrefc=D t:accrliba=N t:refrefd=D t:refrefe=D t:cnsltsve=D t:cnsltsvd=N t:cnsltsvc=N t:mailcity=MONTGOMERY t:pub_fips=1 t:uniondva=N t:uniondvb=N t:uniondvc=N t:uniondvd=N t:uniondve=N t:cnsltsva=D t:cnsltsvb=N t:swvrsa=D t:swvrsb=N t:libplana=D t:mailzip4=1 t:libpland=N t:libplane=D t:libplanb=N t:libplanc=N t:staidsva=D t:univsera=D t:staidsve=D t:staidsvd=N t:staidsvc=N t:staidsvb=N t:swvrsd=N t:swvrsc=N t:swvrse=D t:univserc=N t:univserb=N t:univsere=D t:univserd=N m:popu_st=4557808 m:obereg=5 m:rstatus=1

series e:9uhv-6je7 d:2004-07-01T00:00:00.000Z t:cntedpre=N t:cntedprd=N t:cntedprc=D t:cntedprb=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:mailzip=72201 t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:cntedpra=D t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:sumreade=N t:sumreadd=N t:sumreadc=D t:sumreadb=N t:sumreada=D t:mail_st=AR t:ststande=N t:ststandd=N t:ststandc=N t:ststandb=N t:ststanda=D t:physcity="LITTLE ROCK" t:physzip=72201 t:retrocvc=N t:lstasvc=D t:collbste=N t:lstasvd=D t:retrocvd=N t:collbstd=N t:lstasve=N t:retrocva=N t:collbstc=N t:retrocvb=N t:collbstb=N t:collbsta=D t:lstasva=D t:retrocve=N t:lstasvb=D t:illrefb=D t:litprsvd=N t:illrefc=D t:litprsve=N t:illrefd=D t:illrefe=N t:litprsva=D t:litprsvb=N t:illrefa=D t:litprsvc=N t:liblegb=N t:liblega=D t:liblegd=N t:liblegc=N t:liblege=N t:swdigprd=N t:stwidprb=D t:swdigpre=N t:stwidpra=D t:swdigpra=N t:swdigprb=N t:swdigprc=N t:preservc=D t:preservd=D t:preserva=D t:preservb=D t:preserve=N t:oclcgace=N t:cooppurd=N t:oclcgacd=D t:cooppure=N t:oclcgacc=D t:oclcgacb=D t:webaddr=WWW.ASL.LIB.AR.US t:oclcgaca=D t:cooppura=N t:cooppurb=N t:cooppurc=N t:stwidpre=N t:stwidprc=D t:stwidprd=D t:accrlibe=N t:accrlibd=N t:phys_st=AR t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=D t:accrlibc=N t:refrefb=D t:refrefc=D t:accrliba=N t:refrefd=D t:refrefe=N t:cnsltsve=N t:cnsltsvd=N t:cnsltsvc=N t:mailcity="LITTLE ROCK" t:pub_fips=5 t:uniondva=D t:uniondvb=D t:uniondvc=D t:uniondvd=D t:uniondve=N t:cnsltsva=D t:cnsltsvb=N t:swvrsa=N t:swvrsb=N t:libplana=D t:mailzip4=1085 t:libpland=N t:libplane=N t:libplanb=N t:libplanc=N t:staidsva=D t:univsera=D t:staidsve=N t:staidsvd=N t:staidsvc=N t:staidsvb=N t:swvrsd=N t:swvrsc=N t:swvrse=N t:univserc=N t:univserb=N t:univsere=N t:univserd=N m:popu_st=2779154 m:obereg=5 m:rstatus=1
```

## Meta Commands

```ls
metric m:obereg p:integer l:"BEA code" t:dataTypeName=number

metric m:rstatus p:integer l:"Reporting Status" t:dataTypeName=number

metric m:popu_st l:Population t:dataTypeName=number

entity e:9uhv-6je7 l:"State Libraries Survey, FY 2005, Part 2: SLAA-Provided Services" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9uhv-6je7

property e:9uhv-6je7 t:meta.view v:id=9uhv-6je7 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2005, Part 2: SLAA-Provided Services" v:attribution=IMLS

property e:9uhv-6je7 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9uhv-6je7 t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9uhv-6je7 t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:9uhv-6je7 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```