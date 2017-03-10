# State Libraries Survey, FY 1996, Part 2: SLAA-Provided Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-1996-part-2-slaa-provided-services) |
| Metadata | [Link](https://data.imls.gov/api/views/gdgs-utb6) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/gdgs-utb6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/gdgs-utb6/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | gdgs-utb6 |
| Name | State Libraries Survey, FY 1996, Part 2: SLAA-Provided Services |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 1996, slaa-provided services |
| Created | 2016-12-20T15:15:17Z |
| Publication Date | 2016-12-20T17:04:24Z |
| Rows Updated | 2016-12-20T17:16:30Z |

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
| Yes      | numeric metric | accrliba   | Accredits (pub)                    | number    | text        |
| Yes      | numeric metric | accrlibb   | Accredits (acad)                   | number    | text        |
| Yes      | numeric metric | accrlibc   | Accredits (school)                 | number    | text        |
| Yes      | numeric metric | accrlibd   | Accredits (special)                | number    | text        |
| Yes      | numeric metric | accrlibe   | Accredits (Co-ops)                 | number    | text        |
| Yes      | numeric metric | lscasva    | Admins LSCA grants (pub)           | number    | text        |
| Yes      | numeric metric | lscasvb    | Admins LSCA grants (acad)          | number    | text        |
| Yes      | numeric metric | lscasvc    | Admins LSCA grants (school)        | number    | text        |
| Yes      | numeric metric | lscasvd    | Admins LSCA grants (special)       | number    | text        |
| Yes      | numeric metric | lscasve    | Admins LSCA grants (Co-ops)        | number    | text        |
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
| Yes      | numeric metric | stwidpra   | PR (pub)                           | number    | text        |
| Yes      | numeric metric | stwidprb   | PR (acad)                          | number    | text        |
| Yes      | numeric metric | stwidprc   | PR (school)                        | number    | text        |
| Yes      | numeric metric | stwidprd   | PR (special)                       | number    | text        |
| Yes      | numeric metric | stwidpre   | PR (Co-ops)                        | number    | text        |
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
| Yes      | series tag     | pub_fips   | FIPS state code                    | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy   | date      | date        |
| Yes      | numeric metric | period_e   | Population estimate NCES           | number    | number      |
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
series e:gdgs-utb6 d:1995-07-01T00:00:00.000Z t:cntedpre=Y t:cntedprd=Y t:cntedprc=Y t:cntedprb=Y t:physaddr="333 WILLOUGHBY AVENUE" t:mailzip=99811 t:mailaddr="P.O. BOX 110571" t:cntedpra=Y t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571.0 t:sumreade=N t:sumreadd=N t:sumreadc=N t:sumreadb=N t:sumreada=Y t:mail_st=AK t:ststande=Y t:ststandd=N t:ststandc=Y t:ststandb=N t:ststanda=Y t:lscasvd=Y t:lscasve=Y t:physcity=JUNEAU t:lscasva=Y t:lscasvb=Y t:lscasvc=Y t:physzip=99811 t:retrocvc=N t:collbste=N t:retrocvd=N t:collbstd=N t:retrocva=N t:collbstc=Y t:retrocvb=N t:collbstb=N t:collbsta=Y t:retrocve=N t:illrefb=Y t:litprsvd=N t:illrefc=Y t:litprsve=Y t:illrefd=Y t:illrefe=Y t:litprsva=Y t:litprsvb=N t:illrefa=Y t:litprsvc=Y t:liblegb=Y t:liblega=Y t:liblegd=Y t:liblegc=Y t:liblege=Y t:stwidprb=N t:stwidpra=Y t:preservc=N t:preservd=N t:preserva=N t:preservb=N t:preserve=N t:oclcgace=Y t:cooppurd=N t:oclcgacd=Y t:cooppure=N t:oclcgacc=Y t:oclcgacb=Y t:oclcgaca=Y t:cooppura=N t:cooppurb=N t:cooppurc=N t:stwidpre=Y t:stwidprc=Y t:stwidprd=N t:accrlibe=N t:accrlibd=N t:phys_st=AK t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=Y t:accrlibc=N t:refrefb=Y t:refrefc=Y t:accrliba=N t:refrefd=Y t:refrefe=Y t:cnsltsve=Y t:cnsltsvd=Y t:mailcity=JUNEAU t:cnsltsvc=Y t:pub_fips=2 t:uniondva=Y t:uniondvb=Y t:uniondvc=Y t:uniondvd=Y t:uniondve=Y t:cnsltsva=Y t:cnsltsvb=Y t:libplana=Y t:mailzip4=571.0 t:libpland=Y t:libplane=Y t:libplanb=Y t:libplanc=Y t:staidsva=Y t:staidsve=N t:staidsvd=N t:staidsvc=N t:staidsvb=N m:period_e=615900

series e:gdgs-utb6 d:1995-10-01T00:00:00.000Z t:cntedpre=Y t:cntedprd=N t:cntedprc=N t:cntedprb=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:mailaddr="6030 MONTICELLO DRIVE" t:cntedpra=Y t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1.0 t:sumreade=Y t:sumreadd=N t:sumreadc=N t:sumreadb=N t:sumreada=Y t:mail_st=AL t:ststande=Y t:ststandd=N t:ststandc=N t:ststandb=N t:ststanda=Y t:lscasvd=N t:lscasve=Y t:physcity=MONTGOMERY t:lscasva=Y t:lscasvb=N t:lscasvc=N t:physzip=36117 t:retrocvc=N t:collbste=Y t:retrocvd=N t:collbstd=N t:retrocva=N t:collbstc=N t:retrocvb=N t:collbstb=N t:collbsta=Y t:retrocve=N t:illrefb=Y t:litprsvd=N t:illrefc=Y t:litprsve=Y t:illrefd=N t:illrefe=Y t:litprsva=Y t:litprsvb=N t:illrefa=Y t:litprsvc=N t:liblegb=N t:liblega=Y t:liblegd=N t:liblegc=N t:liblege=N t:stwidprb=N t:stwidpra=Y t:preservc=N t:preservd=N t:preserva=N t:preservb=N t:preserve=N t:oclcgace=N t:cooppurd=N t:oclcgacd=N t:cooppure=N t:oclcgacc=N t:oclcgacb=N t:oclcgaca=N t:cooppura=N t:cooppurb=N t:cooppurc=N t:stwidpre=N t:stwidprc=N t:stwidprd=N t:accrlibe=N t:accrlibd=N t:phys_st=AL t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=Y t:accrlibc=N t:refrefb=Y t:refrefc=Y t:accrliba=N t:refrefd=Y t:refrefe=Y t:cnsltsve=Y t:cnsltsvd=N t:mailcity=MONTGOMERY t:cnsltsvc=N t:pub_fips=1 t:uniondva=Y t:uniondvb=Y t:uniondvc=Y t:uniondvd=Y t:uniondve=Y t:cnsltsva=Y t:cnsltsvb=N t:libplana=Y t:mailzip4=1.0 t:libpland=N t:libplane=Y t:libplanb=N t:libplanc=N t:staidsva=Y t:staidsve=Y t:staidsvd=N t:staidsvc=N t:staidsvb=N m:period_e=4137511

series e:gdgs-utb6 d:1995-07-01T00:00:00.000Z t:cntedpre=N t:cntedprd=Y t:cntedprc=Y t:cntedprb=Y t:physaddr="ONE CAPITOL MALL" t:mailzip=72201 t:mailaddr="ONE CAPITOL MALL" t:cntedpra=Y t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1081.0 t:sumreade=N t:sumreadd=N t:sumreadc=N t:sumreadb=N t:sumreada=Y t:mail_st=AR t:ststande=N t:ststandd=N t:ststandc=N t:ststandb=N t:ststanda=Y t:lscasvd=Y t:lscasve=N t:physcity="LITTLE ROCK" t:lscasva=Y t:lscasvb=Y t:lscasvc=Y t:physzip=72201 t:retrocvc=N t:collbste=N t:retrocvd=Y t:collbstd=N t:retrocva=Y t:collbstc=N t:retrocvb=N t:collbstb=N t:collbsta=Y t:retrocve=N t:illrefb=Y t:litprsvd=N t:illrefc=Y t:litprsve=N t:illrefd=Y t:illrefe=N t:litprsva=Y t:litprsvb=N t:illrefa=Y t:litprsvc=N t:liblegb=N t:liblega=Y t:liblegd=N t:liblegc=N t:liblege=N t:stwidprb=N t:stwidpra=Y t:preservc=Y t:preservd=Y t:preserva=Y t:preservb=Y t:preserve=N t:oclcgace=N t:cooppurd=N t:oclcgacd=Y t:cooppure=N t:oclcgacc=Y t:oclcgacb=Y t:oclcgaca=Y t:cooppura=Y t:cooppurb=N t:cooppurc=N t:stwidpre=N t:stwidprc=N t:stwidprd=N t:accrlibe=N t:accrlibd=N t:phys_st=AR t:certlibe=N t:certlibc=N t:certlibd=N t:certliba=N t:certlibb=N t:accrlibb=N t:refrefa=Y t:accrlibc=N t:refrefb=Y t:refrefc=Y t:accrliba=N t:refrefd=Y t:refrefe=Y t:cnsltsve=N t:cnsltsvd=N t:mailcity="LITTLE ROCK" t:cnsltsvc=N t:pub_fips=5 t:uniondva=Y t:uniondvb=Y t:uniondvc=N t:uniondvd=N t:uniondve=N t:cnsltsva=Y t:cnsltsvb=N t:libplana=Y t:mailzip4=1081.0 t:libpland=N t:libplane=N t:libplanb=N t:libplanc=N t:staidsva=Y t:staidsve=N t:staidsvd=N t:staidsvc=N t:staidsvb=N m:period_e=2268207
```

## Meta Commands

```ls
metric m:period_e l:"Population estimate NCES" t:dataTypeName=number

entity e:gdgs-utb6 l:"State Libraries Survey, FY 1996, Part 2: SLAA-Provided Services" t:attribution=IMLS t:url=https://data.imls.gov/api/views/gdgs-utb6

property e:gdgs-utb6 t:meta.view d:2017-03-10T16:29:20.444Z v:id=gdgs-utb6 v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 1996, Part 2: SLAA-Provided Services" v:attribution=IMLS

property e:gdgs-utb6 t:meta.view.license d:2017-03-10T16:29:20.444Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:gdgs-utb6 t:meta.view.owner d:2017-03-10T16:29:20.444Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:gdgs-utb6 t:meta.view.tableauthor d:2017-03-10T16:29:20.444Z v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:gdgs-utb6 t:meta.view.metadata.custom_fields.common_core d:2017-03-10T16:29:20.444Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```