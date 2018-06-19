# Library Systems: FY 2014 Public Libraries Survey (Administrative Entity Data)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-systems-fy-2014-public-libraries-survey-administrative-entity-data) |
| Metadata | [Link](https://data.imls.gov/api/views/wzfa-2gdc) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/wzfa-2gdc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/wzfa-2gdc/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | wzfa-2gdc |
| Name | Library Systems: FY 2014 Public Libraries Survey (Administrative Entity Data) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, 2014, administrative entity |
| Created | 2016-08-03T19:54:43Z |
| Publication Date | 2016-08-16T17:13:40Z |

## Description

Find key information on library systems around the United States.<br><br>These data include imputed values for libraries that did not submit information in the FY 2014 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2014 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | state                         | STATE                         | text          | text          |
| Yes      | series tag     | fscs_id                       | FSCS ID                       | text          | text          |
| Yes      | series tag     | library_id                    | LIBRARY ID                    | text          | text          |
| Yes      | series tag     | library_name                  | LIBRARY NAME                  | text          | text          |
| Yes      | numeric metric | locale                        | LOCALE                        | number        | number        |
| Yes      | numeric metric | service_area_population       | SERVICE AREA POPULATION       | number        | number        |
| Yes      | numeric metric | unduplicated_population       | UNDUPLICATED POPULATION       | number        | number        |
| Yes      | numeric metric | central_libraries             | CENTRAL LIBRARIES             | number        | number        |
| Yes      | numeric metric | branch_libraries              | BRANCH LIBRARIES              | number        | number        |
| Yes      | numeric metric | bookmobiles                   | BOOKMOBILES                   | number        | number        |
| Yes      | numeric metric | mls_librarian_staff           | MLS LIBRARIAN STAFF           | number        | number        |
| Yes      | numeric metric | librarian_staff               | LIBRARIAN STAFF               | number        | number        |
| Yes      | numeric metric | other_staff                   | OTHER STAFF                   | number        | number        |
| Yes      | numeric metric | total_staff                   | TOTAL STAFF                   | number        | number        |
| Yes      | numeric metric | local_revenue                 | LOCAL REVENUE                 | money         | money         |
| Yes      | numeric metric | state_revenue                 | STATE REVENUE                 | money         | money         |
| Yes      | numeric metric | federal_revenue               | FEDERAL REVENUE               | money         | money         |
| Yes      | numeric metric | other_revenue                 | OTHER REVENUE                 | money         | money         |
| Yes      | numeric metric | total_revenue                 | TOTAL REVENUE                 | money         | money         |
| Yes      | numeric metric | salaries                      | SALARIES                      | money         | money         |
| Yes      | numeric metric | benefits                      | BENEFITS                      | money         | money         |
| Yes      | numeric metric | total_staff_expenditures      | TOTAL STAFF EXPENDITURES      | money         | money         |
| Yes      | numeric metric | print_expenditures            | PRINT EXPENDITURES            | money         | money         |
| Yes      | numeric metric | electronic_expenditures       | ELECTRONIC EXPENDITURES       | money         | money         |
| Yes      | numeric metric | other_collection_expenditures | OTHER COLLECTION EXPENDITURES | money         | money         |
| Yes      | numeric metric | total_collection_expenditures | TOTAL COLLECTION EXPENDITURES | money         | money         |
| Yes      | numeric metric | other_expenditures            | OTHER EXPENDITURES            | money         | money         |
| Yes      | numeric metric | total_expenditures            | TOTAL EXPENDITURES            | money         | money         |
| Yes      | numeric metric | local_capital_revenue         | LOCAL CAPITAL REVENUE         | money         | money         |
| Yes      | numeric metric | state_capital_revenue         | STATE CAPITAL REVENUE         | money         | money         |
| Yes      | numeric metric | federal_capital_revenue       | FEDERAL CAPITAL REVENUE       | money         | money         |
| Yes      | numeric metric | other_capital_revenue         | OTHER CAPITAL REVENUE         | money         | money         |
| Yes      | numeric metric | total_capital_revenue         | TOTAL CAPITAL REVENUE         | money         | money         |
| Yes      | numeric metric | capital_expenditures          | CAPITAL EXPENDITURES          | money         | money         |
| Yes      | numeric metric | print_materials               | PRINT MATERIALS               | number        | number        |
| Yes      | numeric metric | ebooks                        | EBOOKS                        | number        | number        |
| Yes      | numeric metric | audio_materials               | AUDIO MATERIALS               | number        | number        |
| Yes      | numeric metric | audio_downloads               | AUDIO DOWNLOADS               | number        | number        |
| Yes      | numeric metric | video_materials               | VIDEO MATERIALS               | number        | number        |
| Yes      | numeric metric | video_downloads               | VIDEO DOWNLOADS               | number        | number        |
| Yes      | numeric metric | local_databases               | LOCAL DATABASES               | number        | number        |
| Yes      | numeric metric | state_databases               | STATE DATABASES               | number        | number        |
| Yes      | numeric metric | total_databases               | TOTAL DATABASES               | number        | number        |
| Yes      | numeric metric | print_serials                 | PRINT SERIALS                 | number        | number        |
| Yes      | numeric metric | hours                         | HOURS                         | number        | number        |
| Yes      | numeric metric | visits                        | VISITS                        | number        | number        |
| Yes      | numeric metric | references                    | REFERENCES                    | number        | number        |
| Yes      | numeric metric | users                         | USERS                         | number        | number        |
| Yes      | numeric metric | total_circulation             | TOTAL CIRCULATION             | number        | number        |
| Yes      | numeric metric | kids_circulation              | KIDS CIRCULATION              | number        | number        |
| Yes      | numeric metric | electronic_circulation        | ELECTRONIC CIRCULATION        | number        | number        |
| Yes      | numeric metric | loans_to                      | LOANS TO                      | number        | number        |
| Yes      | numeric metric | loans_from                    | LOANS FROM                    | number        | number        |
| Yes      | numeric metric | total_programs                | TOTAL PROGRAMS                | number        | number        |
| Yes      | numeric metric | kids_programs                 | KIDS PROGRAMS                 | number        | number        |
| Yes      | numeric metric | ya_programs                   | YA PROGRAMS                   | number        | number        |
| Yes      | numeric metric | program_audience              | PROGRAM AUDIENCE              | number        | number        |
| Yes      | numeric metric | kids_program_audience         | KIDS PROGRAM AUDIENCE         | number        | number        |
| Yes      | numeric metric | ya_program_audience           | YA PROGRAM AUDIENCE           | number        | number        |
| Yes      | numeric metric | computers                     | COMPUTERS                     | number        | number        |
| Yes      | numeric metric | computer_users                | COMPUTER USES                 | number        | number        |
| Yes      | numeric metric | wifi_sessions                 | WIFI SESSIONS                 | number        | number        |
| No       |                | year                          | YEAR                          | number        | number        |
| Yes      | time           | start_date                    | START DATE                    | calendar_date | calendar_date |
| No       |                | end_date                      | END DATE                      | calendar_date | calendar_date |
| Yes      | series tag     | reporting_status              | REPORTING STATUS              | text          | number        |
| Yes      | series tag     | obereg                        | BEA REGION                    | text          | text          |
| Yes      | series tag     | structure_change              | STRUCTURE CHANGE              | text          | text          |
| Yes      | series tag     | name_change                   | NAME CHANGE                   | text          | text          |
| No       |                | address_change                | ADDRESS CHANGE                | text          | text          |
| Yes      | series tag     | interlibrary_relationship     | INTERLIBRARY RELATIONSHIP     | text          | text          |
| No       |                | mailing_address               | MAILING ADDRESS               | text          | text          |
| Yes      | series tag     | mailing_city                  | MAILING CITY                  | text          | text          |
| Yes      | series tag     | mailing_zip                   | MAILING ZIP                   | text          | text          |
| Yes      | series tag     | phone                         | PHONE                         | text          | number        |
| Yes      | series tag     | county                        | COUNTY                        | text          | text          |
| Yes      | numeric metric | county_population             | COUNTY POPULATION             | number        | number        |
| Yes      | series tag     | legal_basis                   | LEGAL BASIS                   | text          | text          |
| Yes      | series tag     | administrative_structure      | ADMINISTRATIVE STRUCTURE      | text          | text          |
| Yes      | series tag     | fscs_definition               | FSCS DEFINITION               | text          | text          |
| Yes      | series tag     | lsabound                      | LSABOUND                      | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,address_change,mailing_address,year
```

## Data Commands

```ls
series e:wzfa-2gdc d:2013-07-01T00:00:00.000Z t:phone=9072355692 t:library_id=AK0001-002 t:obereg=08 t:mailing_zip=99556 t:state=AK t:reporting_status=1 t:structure_change=00 t:name_change=00 t:interlibrary_relationship=NO t:administrative_structure=SO t:library_name="ANCHOR POINT PUBLIC LIBRARY" t:fscs_id=AK0001 t:legal_basis=NP t:county="KENAI PENINSULA" t:fscs_definition=Y t:lsabound=N t:mailing_city="ANCHOR POINT" m:users=396 m:kids_program_audience=128 m:other_staff=0 m:electronic_expenditures=0 m:video_materials=4159 m:federal_revenue=2821 m:print_serials=7 m:references=550 m:other_capital_revenue=12765 m:total_staff=0.68 m:total_expenditures=21282 m:total_collection_expenditures=4030 m:local_databases=0 m:ebooks=0 m:librarian_staff=0.68 m:kids_programs=15 m:program_audience=146 m:other_revenue=7113 m:county_population=57477 m:ya_programs=0 m:hours=1377 m:local_capital_revenue=0 m:electronic_circulation=0 m:video_downloads=0 m:audio_downloads=0 m:total_capital_revenue=12765 m:unduplicated_population=2059 m:total_revenue=28927 m:print_expenditures=3021 m:service_area_population=2059 m:state_capital_revenue=0 m:branch_libraries=0 m:audio_materials=258 m:local_revenue=0 m:total_circulation=11607 m:kids_circulation=1144 m:print_materials=16843 m:locale=43 m:total_databases=49 m:other_collection_expenditures=1009 m:computers=8 m:ya_program_audience=0 m:capital_expenditures=0 m:loans_to=0 m:mls_librarian_staff=0 m:loans_from=28 m:total_programs=17 m:federal_capital_revenue=0 m:state_revenue=18993 m:central_libraries=1 m:bookmobiles=0 m:state_databases=49 m:computer_users=1675 m:wifi_sessions=0 m:visits=5379

series e:wzfa-2gdc d:2013-01-01T00:00:00.000Z t:phone=9073432892 t:library_id=AK0002-011 t:obereg=08 t:mailing_zip=99503 t:state=AK t:reporting_status=1 t:structure_change=00 t:name_change=00 t:interlibrary_relationship=NO t:administrative_structure=MO t:library_name="ANCHORAGE PUBLIC LIBRARY" t:fscs_id=AK0002 t:legal_basis=CO t:county=ANCHORAGE t:fscs_definition=Y t:lsabound=N t:mailing_city=ANCHORAGE m:users=119619 m:kids_program_audience=41259 m:other_staff=49.8 m:electronic_expenditures=198422 m:video_materials=63779 m:federal_revenue=157386 m:print_serials=751 m:references=98871 m:other_capital_revenue=0 m:total_staff=78.9 m:total_expenditures=10910542 m:total_collection_expenditures=1152280 m:local_databases=14 m:ebooks=9773 m:librarian_staff=29.1 m:kids_programs=906 m:program_audience=68778 m:other_revenue=183440 m:county_population=301010 m:ya_programs=412 m:hours=10208 m:local_capital_revenue=0 m:electronic_circulation=112965 m:video_downloads=0 m:audio_downloads=10496 m:total_capital_revenue=1825000 m:unduplicated_population=300549 m:salaries=3214218 m:total_revenue=10846031 m:print_expenditures=700747 m:service_area_population=300549 m:state_capital_revenue=1825000 m:branch_libraries=4 m:audio_materials=28552 m:local_revenue=10448481 m:total_staff_expenditures=6068101 m:total_circulation=1886620 m:kids_circulation=484429 m:print_materials=481861 m:other_expenditures=3690161 m:locale=11 m:total_databases=63 m:other_collection_expenditures=253111 m:computers=135 m:ya_program_audience=9656 m:capital_expenditures=0 m:loans_to=5359 m:mls_librarian_staff=20.6 m:loans_from=2254 m:total_programs=1435 m:federal_capital_revenue=0 m:state_revenue=56724 m:central_libraries=1 m:bookmobiles=0 m:state_databases=49 m:computer_users=138689 m:benefits=2853883 m:wifi_sessions=0 m:visits=942873

series e:wzfa-2gdc d:2013-07-01T00:00:00.000Z t:phone=9075434516 t:library_id=AK0006-002 t:obereg=08 t:mailing_zip=99559 t:state=AK t:reporting_status=1 t:structure_change=00 t:name_change=00 t:interlibrary_relationship=NO t:administrative_structure=SO t:library_name="KUSKOKWIM CONSORTIUM LIBRARY" t:fscs_id=AK0006 t:legal_basis=MJ t:county=BETHEL t:fscs_definition=Y t:lsabound=N t:mailing_city=BETHEL m:users=1500 m:kids_program_audience=417 m:other_staff=2 m:electronic_expenditures=1635 m:video_materials=2345 m:federal_revenue=0 m:print_serials=50 m:references=1200 m:other_capital_revenue=0 m:total_staff=3 m:total_expenditures=261212 m:total_collection_expenditures=14801 m:local_databases=138 m:ebooks=165 m:librarian_staff=1 m:kids_programs=37 m:program_audience=815 m:other_revenue=184800 m:county_population=17868 m:ya_programs=1 m:hours=2912 m:local_capital_revenue=0 m:electronic_circulation=100 m:video_downloads=0 m:audio_downloads=0 m:total_capital_revenue=0 m:unduplicated_population=6241 m:salaries=167806 m:total_revenue=259000 m:print_expenditures=8295 m:service_area_population=6241 m:state_capital_revenue=0 m:branch_libraries=0 m:audio_materials=434 m:local_revenue=67600 m:total_staff_expenditures=240485 m:total_circulation=12347 m:kids_circulation=1873 m:print_materials=34115 m:other_expenditures=5926 m:locale=33 m:total_databases=187 m:other_collection_expenditures=4871 m:computers=9 m:ya_program_audience=15 m:capital_expenditures=0 m:loans_to=38 m:mls_librarian_staff=1 m:loans_from=76 m:total_programs=107 m:federal_capital_revenue=0 m:state_revenue=6600 m:central_libraries=1 m:bookmobiles=0 m:state_databases=49 m:computer_users=20000 m:benefits=72679 m:wifi_sessions=0 m:visits=44980
```

## Meta Commands

```ls
metric m:locale p:integer l:LOCALE t:dataTypeName=number

metric m:service_area_population p:integer l:"SERVICE AREA POPULATION" d:"Population of the legal service area (POPU_LSA)" t:dataTypeName=number

metric m:unduplicated_population p:integer l:"UNDUPLICATED POPULATION" d:"Unduplicated population of the legal service area for the library. This value is calculated by prorating the library's population of legal service area (POPU_LSA) to the state's total population of legal service areas (total POPU_LSA), and applying the ratio to the state-reported total unduplicated population of legal service areas. The latter item, a single figure reported by the state data coordinator, is also named POPU_UND but is located on the State Summary/State Characteristics Data File. (POPU_UND)" t:dataTypeName=number

metric m:central_libraries p:integer l:"CENTRAL LIBRARIES" d:"Number of central libraries (CENTLIB)" t:dataTypeName=number

metric m:branch_libraries p:integer l:"BRANCH LIBRARIES" d:"Number of branch libraries (BRANLIB)" t:dataTypeName=number

metric m:bookmobiles p:integer l:BOOKMOBILES d:"Number of bookmobiles (BKMOB)" t:dataTypeName=number

metric m:mls_librarian_staff p:float l:"MLS LIBRARIAN STAFF" d:"Number of full-time equivalent (FTE) paid librarians with master's degrees from programs of library and information studies accredited by the American Library Association (MASTER)" t:dataTypeName=number

metric m:librarian_staff p:float l:"LIBRARIAN STAFF" d:"Number of FTE employees holding the title of librarian (LIBRARIA)" t:dataTypeName=number

metric m:other_staff p:float l:"OTHER STAFF" d:"All other paid FTE employees (OTHPAID)" t:dataTypeName=number

metric m:total_staff p:float l:"TOTAL STAFF" d:"Total paid FTE employees, a sum of Librarian Staff and Other Staff (TOTSTAFF)" t:dataTypeName=number

metric m:local_revenue p:integer l:"LOCAL REVENUE" d:"Operating revenue from local government (LOCGVT)" t:dataTypeName=money

metric m:state_revenue p:integer l:"STATE REVENUE" d:"Operating revenue from state government (STGVT)" t:dataTypeName=money

metric m:federal_revenue p:integer l:"FEDERAL REVENUE" d:"Operating revenue from federal government (FEDGVT)" t:dataTypeName=money

metric m:other_revenue p:integer l:"OTHER REVENUE" d:"Other operating revenue (OTHINCM)" t:dataTypeName=money

metric m:total_revenue p:integer l:"TOTAL REVENUE" d:"Total operating revenue, a sum of Local, State, Federal, and Other Revenue (TOTINCM)" t:dataTypeName=money

metric m:salaries p:integer l:SALARIES d:"Staff operating expenditures for salaries and wages for all library staff (SALARIES)" t:dataTypeName=money

metric m:benefits p:integer l:BENEFITS d:"Staff operating expenditures for employee benefits for all library staff (BENEFIT)" t:dataTypeName=money

metric m:total_staff_expenditures p:integer l:"TOTAL STAFF EXPENDITURES" d:"Total staff operating expenditures, a sum of Salaries and Benefits (STAFFEXP)" t:dataTypeName=money

metric m:print_expenditures p:integer l:"PRINT EXPENDITURES" d:"Collection operating expenditures for print materials (PRMATEXP)" t:dataTypeName=money

metric m:electronic_expenditures p:integer l:"ELECTRONIC EXPENDITURES" d:"Collection operating expenditures for electronic or digital materials (ELMATEXP)" t:dataTypeName=money

metric m:other_collection_expenditures p:integer l:"OTHER COLLECTION EXPENDITURES" d:"Collection operating expenditures for other library materials (OTHMATEX)" t:dataTypeName=money

metric m:total_collection_expenditures p:integer l:"TOTAL COLLECTION EXPENDITURES" d:"Total collection operating expenditures, a sum of Print, Electronic, and Other Collection Expenditures (TOTEXPCO)" t:dataTypeName=money

metric m:other_expenditures p:integer l:"OTHER EXPENDITURES" d:"Other operating expenditures (OTHOPEXP)" t:dataTypeName=money

metric m:total_expenditures p:integer l:"TOTAL EXPENDITURES" d:"Total operating expenditures, a sum of Total Staff, Total Collection, and Other Expenditures (TOTOEXP)" t:dataTypeName=money

metric m:local_capital_revenue p:integer l:"LOCAL CAPITAL REVENUE" d:"Local government capital revenue (LCAP_REV)" t:dataTypeName=money

metric m:state_capital_revenue p:integer l:"STATE CAPITAL REVENUE" d:"State government capital revenue (SCAP_REV)" t:dataTypeName=money

metric m:federal_capital_revenue p:integer l:"FEDERAL CAPITAL REVENUE" d:"Federal government capital revenue (FCAP_REV)" t:dataTypeName=money

metric m:other_capital_revenue p:integer l:"OTHER CAPITAL REVENUE" d:"Other capital revenue (OCAP_REV)" t:dataTypeName=money

metric m:total_capital_revenue p:integer l:"TOTAL CAPITAL REVENUE" d:"Total capital revenue, a sum of Local, State, Federal, and Other Capital Revenue (CAP_REV)" t:dataTypeName=money

metric m:capital_expenditures p:integer l:"CAPITAL EXPENDITURES" d:"Total capital expenditures (CAPITAL)" t:dataTypeName=money

metric m:print_materials p:integer l:"PRINT MATERIALS" d:"Number of print materials in collection (BKVOL)" t:dataTypeName=number

metric m:ebooks p:integer l:EBOOKS d:"Number of e-books in library collection (EBOOK)" t:dataTypeName=number

metric m:audio_materials p:integer l:"AUDIO MATERIALS" d:"Number of physical audio units in collection (AUDIO_PH)" t:dataTypeName=number

metric m:audio_downloads p:integer l:"AUDIO DOWNLOADS" d:"Number of downloadable audio titles in collection (AUDIO_DL)" t:dataTypeName=number

metric m:video_materials p:integer l:"VIDEO MATERIALS" d:"Number of physical video units in collection (VIDEO_PH)" t:dataTypeName=number

metric m:video_downloads p:integer l:"VIDEO DOWNLOADS" d:"Number of downloadable video titles in collection (VIDEO_DL)" t:dataTypeName=number

metric m:local_databases p:integer l:"LOCAL DATABASES" d:"Number of licensed databases from local or other cooperative agreements (DB_LO_OT)" t:dataTypeName=number

metric m:state_databases p:integer l:"STATE DATABASES" d:"Number of state licensed databases (DB_ST)" t:dataTypeName=number

metric m:total_databases p:integer l:"TOTAL DATABASES" d:"Total number of licensed databases (DATABASE)" t:dataTypeName=number

metric m:print_serials p:integer l:"PRINT SERIALS" d:"Number of print serial subscriptions (SUBSCRIP)" t:dataTypeName=number

metric m:hours p:integer l:HOURS d:"Total number of annual public service hours for all outlets (HRS_OPEN)" t:dataTypeName=number

metric m:visits p:integer l:VISITS d:"Total number of annual library visits for all outlets (VISITS)" t:dataTypeName=number

metric m:references p:integer l:REFERENCES d:"Total number of annual reference transactions for all outlets (REFERENCE)" t:dataTypeName=number

metric m:users p:integer l:USERS d:"Number of registered users for all outlets (REGBOR)" t:dataTypeName=number

metric m:total_circulation p:integer l:"TOTAL CIRCULATION" d:"Total number of annual circulation transactions for all outlets (TOTCIR)" t:dataTypeName=number

metric m:kids_circulation p:integer l:"KIDS CIRCULATION" d:"Total number of annual circulation transactions for children's materials for all outlets (KIDCIRL)" t:dataTypeName=number

metric m:electronic_circulation p:integer l:"ELECTRONIC CIRCULATION" d:"Total number of annual circulation transactions for electronic materials for all outlets (ELMATCIR)" t:dataTypeName=number

metric m:loans_to p:integer l:"LOANS TO" d:"Total number of annual inter-library loans provided to other libraries (LOANTO)" t:dataTypeName=number

metric m:loans_from p:integer l:"LOANS FROM" d:"Total number of annual inter-library loans received from other libraries (LOANFM)" t:dataTypeName=number

metric m:total_programs p:integer l:"TOTAL PROGRAMS" d:"Total number of library programs (TOTPRO)" t:dataTypeName=number

metric m:kids_programs p:integer l:"KIDS PROGRAMS" d:"Total number of children's programs (KIDPRO)" t:dataTypeName=number

metric m:ya_programs p:integer l:"YA PROGRAMS" d:"Total number of young adult programs (YAPRO)" t:dataTypeName=number

metric m:program_audience p:integer l:"PROGRAM AUDIENCE" d:"Total audience at all library programs (TOTATTEN)" t:dataTypeName=number

metric m:kids_program_audience p:integer l:"KIDS PROGRAM AUDIENCE" d:"Total audience at all children's programs (KIDATTEN)" t:dataTypeName=number

metric m:ya_program_audience p:integer l:"YA PROGRAM AUDIENCE" d:"Total audience at all young adult programs (YAATTEN)" t:dataTypeName=number

metric m:computers p:integer l:COMPUTERS d:"Number of internet computers used by general public (GPTERMS)" t:dataTypeName=number

metric m:computer_users p:integer l:"COMPUTER USES" d:"Number of uses of public Internet computers (PITUSR)" t:dataTypeName=number

metric m:wifi_sessions p:integer l:"WIFI SESSIONS" d:"Number of wireless sessions provided by the library's wifi (WIFISESS) -1 = Nonresponse" t:dataTypeName=number

metric m:county_population p:integer l:"COUNTY POPULATION" d:"County Population -1?Missing (CNTYPOP)" t:dataTypeName=number

entity e:wzfa-2gdc l:"Library Systems: FY 2014 Public Libraries Survey (Administrative Entity Data)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/wzfa-2gdc

property e:wzfa-2gdc t:meta.view v:id=wzfa-2gdc v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Library Systems: FY 2014 Public Libraries Survey (Administrative Entity Data)" v:attribution=IMLS

property e:wzfa-2gdc t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:wzfa-2gdc t:meta.view.owner v:id=879v-x7gf v:screenName=Marisa v:displayName=Marisa

property e:wzfa-2gdc t:meta.view.tableauthor v:id=879v-x7gf v:screenName=Marisa v:roleName=administrator v:displayName=Marisa

property e:wzfa-2gdc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| state | fscs_id | library_id | library_name                     | locale | service_area_population | unduplicated_population | central_libraries | branch_libraries | bookmobiles | mls_librarian_staff | librarian_staff | other_staff | total_staff        | local_revenue | state_revenue | federal_revenue | other_revenue | total_revenue | salaries | benefits | total_staff_expenditures | print_expenditures | electronic_expenditures | other_collection_expenditures | total_collection_expenditures | other_expenditures | total_expenditures | local_capital_revenue | state_capital_revenue | federal_capital_revenue | other_capital_revenue | total_capital_revenue | capital_expenditures | print_materials | ebooks | audio_materials | audio_downloads | video_materials | video_downloads | local_databases | state_databases | total_databases | print_serials | hours | visits | references | users  | total_circulation | kids_circulation | electronic_circulation | loans_to | loans_from | total_programs | kids_programs | ya_programs | program_audience | kids_program_audience | ya_program_audience | computers | computer_users | wifi_sessions | year | start_date          | end_date            | reporting_status | obereg | structure_change | name_change | address_change | interlibrary_relationship | mailing_address    | mailing_city   | mailing_zip | phone      | county            | county_population | legal_basis | administrative_structure | fscs_definition | lsabound | 
| ===== | ======= | ========== | ================================ | ====== | ======================= | ======================= | ================= | ================ | =========== | =================== | =============== | =========== | ================== | ============= | ============= | =============== | ============= | ============= | ======== | ======== | ======================== | ================== | ======================= | ============================= | ============================= | ================== | ================== | ===================== | ===================== | ======================= | ===================== | ===================== | ==================== | =============== | ====== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | ============= | ===== | ====== | ========== | ====== | ================= | ================ | ====================== | ======== | ========== | ============== | ============= | =========== | ================ | ===================== | =================== | ========= | ============== | ============= | ==== | =================== | =================== | ================ | ====== | ================ | =========== | ============== | ========================= | ================== | ============== | =========== | ========== | ================= | ================= | =========== | ======================== | =============== | ======== | 
| AK    | AK0001  | AK0001-002 | ANCHOR POINT PUBLIC LIBRARY      | 43     | 2059                    | 2059                    | 1                 | 0                | 0           | 0                   | 0.68            | 0           | 0.68               | 0             | 18993         | 2821            | 7113          | 28927         |          |          |                          | 3021               | 0                       | 1009                          | 4030                          |                    | 21282              | 0                     | 0                     | 0                       | 12765                 | 12765                 | 0                    | 16843           | 0      | 258             | 0               | 4159            | 0               | 0               | 49              | 49              | 7             | 1377  | 5379   | 550        | 396    | 11607             | 1144             | 0                      | 0        | 28         | 17             | 15            | 0           | 146              | 128                   | 0                   | 8         | 1675           | 0             | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 129       | ANCHOR POINT   | 99556       | 9072355692 | KENAI PENINSULA   | 57477             | NP          | SO                       | Y               | N        | 
| AK    | AK0002  | AK0002-011 | ANCHORAGE PUBLIC LIBRARY         | 11     | 300549                  | 300549                  | 1                 | 4                | 0           | 20.6                | 29.1            | 49.8        | 78.900000000000006 | 10448481      | 56724         | 157386          | 183440        | 10846031      | 3214218  | 2853883  | 6068101                  | 700747             | 198422                  | 253111                        | 1152280                       | 3690161            | 10910542           | 0                     | 1825000               | 0                       | 0                     | 1825000               | 0                    | 481861          | 9773   | 28552           | 10496           | 63779           | 0               | 14              | 49              | 63              | 751           | 10208 | 942873 | 98871      | 119619 | 1886620           | 484429           | 112965                 | 5359     | 2254       | 1435           | 906           | 412         | 68778            | 41259                 | 9656                | 135       | 138689         | 0             | 2015 | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | 3600 DENALI STREET | ANCHORAGE      | 99503       | 9073432892 | ANCHORAGE         | 301010            | CO          | MO                       | Y               | N        | 
| AK    | AK0006  | AK0006-002 | KUSKOKWIM CONSORTIUM LIBRARY     | 33     | 6241                    | 6241                    | 1                 | 0                | 0           | 1                   | 1               | 2           | 3                  | 67600         | 6600          | 0               | 184800        | 259000        | 167806   | 72679    | 240485                   | 8295               | 1635                    | 4871                          | 14801                         | 5926               | 261212             | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 34115           | 165    | 434             | 0               | 2345            | 0               | 138             | 49              | 187             | 50            | 2912  | 44980  | 1200       | 1500   | 12347             | 1873             | 100                    | 38       | 76         | 107            | 37            | 1           | 815              | 417                   | 15                  | 9         | 20000          | 0             | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 368       | BETHEL         | 99559       | 9075434516 | BETHEL            | 17868             | MJ          | SO                       | Y               | N        | 
| AK    | AK0007  | AK0007-002 | BIG LAKE PUBLIC LIBRARY          | 42     | 12793                   | 12793                   | 1                 | 0                | 0           | 0                   | 1               | 2           | 3                  | 339574        | 6600          | 4979            | 0             | 351153        | 154145   | 119727   | 273872                   | 21552              | 0                       | 0                             | 21552                         | 52251              | 347675             | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 23810           | 9773   | 1813            | 10496           | 2623            | 0               | 1               | 49              | 50              | 52            | 2548  | 43285  | 3469       | 3878   | 59630             | 18330            | 4615                   | 118      | 147        | 296            | 118           | 11          | 6316             | 3893                  | 1396                | 22        | 11301          | 5148          | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 520829    | BIG LAKE       | 99652       | 9078617635 | MATANUSKA-SUSITNA | 97882             | CO          | SO                       | Y               | N        | 
| AK    | AK0008  | AK0008-002 | CANTWELL COMMUNITY LIBRARY       | 43     | 182                     | 182                     | 1                 | 0                | 0           | 0                   | 1               | 0.5         | 1.5                | 4000          | 6600          | 7000            | 2640          | 20240         |          |          |                          | 4846               | 0                       | 637                           | 5483                          |                    | 20720              | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 14550           | 0      | 208             | 0               | 315             | 0               | 1               | 49              | 50              | 12            | 750   | 3000   | 380        | 170    | 5064              | 2755             | 0                      | 20       | 50         | 27             | 23            | 1           | 169              | 116                   | 3                   | 1         | 700            | 500           | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 68        | CANTWELL       | 99729       | 9077682372 | DENALI            | 1921              | NP          | SO                       | Y               | N        | 
| AK    | AK0011  | AK0011-002 | CHINIAK PUBLIC LIBRARY           | 43     | 48                      | 48                      | 1                 | 0                | 0           | 0                   | 0               | 0.11        | 0.11               | 3000          | 25020         | 6560            | 44065         | 78645         |          |          |                          | 4123               | 224                     | 1801                          | 6148                          |                    | 78540              | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 4893            | 40     | 246             | 0               | 630             | 0               | 0               | 49              | 49              | 27            | 720   | 1029   | 72         | 55     | 1118              | 590              | 0                      | 0        | 0          | 53             | 49            | 0           | 388              | 369                   | 0                   | 11        | 436            | 200           | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 5610      | CHINIAK        | 99615       | 9074863022 | KODIAK ISLAND     | 13986             | NP          | SO                       | Y               | N        | 
| AK    | AK0014  | AK0014-002 | COLD BAY PUBLIC LIBRARY          | 43     | 89                      | 89                      | 1                 | 0                | 0           | 0                   | 0               | 0           | 0                  | 3300          | 18540         | 2642            | 50453         | 74935         |          |          |                          | 2164               | 0                       | 1774                          | 3938                          |                    | 71103              | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 7033            | 5      | 191             | 0               | 3298            | 0               | 0               | 49              | 49              | 21            | 480   | 1600   | 50         | 105    | 1939              | 816              | 10                     | 0        | 0          | 32             | 32            | 0           | 306              | 306                   | 0                   | 6         | 427            | 0             | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 87        | COLD BAY       | 99571       | 9075322878 | ALEUTIANS EAST    | 3360              | NP          | SO                       | N               | N        | 
| AK    | AK0015  | AK0015-002 | COOPER LANDING COMMUNITY LIBRARY | 43     | 295                     | 295                     | 1                 | 0                | 0           | 0                   | 0.1             | 0           | 0.1                | 0             | 9787          | 5856            | 24156         | 39799         |          |          |                          | 4788               | 0                       | 500                           | 5288                          |                    | 30060              | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 3778            | 121    | 219             | 0               | 682             | 0               | 0               | 49              | 49              | 2             | 1092  | 3349   | 160        | 545    | 3210              | 1241             | 10                     | 0        | 79         | 23             | 8             | 1           | 1005             | 691                   | 30                  | 4         | 355            | 250           | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 517       | COOPER LANDING | 99572       | 9075951241 | KENAI PENINSULA   | 57477             | NP          | SO                       | Y               | N        | 
| AK    | AK0016  | AK0016-002 | CORDOVA PUBLIC LIBRARY           | 43     | 2286                    | 2286                    | 1                 | 0                | 0           | 0                   | 3.75            | 1           | 4.75               | 472653        | 9047          | 11615           | 14929         | 508244        | 269032   | 109581   | 378613                   | 9164               | 1500                    | 352                           | 11016                         | 80356              | 469985             | 0                     | 1000000               | 0                       | 0                     | 1000000               | 0                    | 20459           | 9773   | 350             | 10496           | 1328            | 0               | 1               | 49              | 50              | 32            | 2652  | 22918  | 972        | 2073   | 13370             | 3831             | 1382                   | 0        | 295        | 188            | 135           | 0           | 3054             | 2525                  | 0                   | 5         | 6671           | 4522          | 2015 | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 1210      | CORDOVA        | 99574       | 9074246667 | VALDEZ-CORDOVA    | 9488              | CI          | SO                       | Y               | N        | 
| AK    | AK0017  | AK0017-003 | CRAIG PUBLIC LIBRARY             | 43     | 1198                    | 1198                    | 1                 | 0                | 0           | 0                   | 1               | 0.5         | 1.5                | 132077        | 9107          | 14642           | 39346         | 195172        |          |          |                          | 20605              | 1100                    | 6560                          | 28265                         |                    | 192281             | 14000                 | 0                     | 0                       | 0                     | 14000                 | 14000                | 9981            | 10120  | 195             | 10496           | 2911            | 0               | 0               | 49              | 49              | 82            | 2355  | 18370  | 3027       | 2729   | 36231             | 8070             | 9647                   | 0        | 94         | 403            | 211           | 50          | 3318             | 2138                  | 214                 | 4         | 4861           | 1698          | 2015 | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1                | 08     | 00               | 00          | 00             | NO                        | P.O. BOX 866       | CRAIG          | 99921       | 9078263281 | PR WALES-OUTER KE | 6396              | CI          | SO                       | Y               | N        | 
```