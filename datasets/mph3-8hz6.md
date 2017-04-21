# State Profiles: FY 2014 Public Libraries Survey (Data)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-profiles-fy-2014-public-libraries-survey-data) |
| Metadata | [Link](https://data.imls.gov/api/views/mph3-8hz6) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/mph3-8hz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/mph3-8hz6/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | mph3-8hz6 |
| Name | State Profiles: FY 2014 Public Libraries Survey (Data) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, 2014, state summary |
| Created | 2016-08-03T19:39:38Z |
| Publication Date | 2016-08-10T20:09:11Z |

## Description

Pull up a state's profile to find state-level totals on key data such as numbers of libraries and librarians, revenue and expenditures, and collection sizes.<br><br>These data include imputed values for libraries that did not submit information in the FY 2014 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing. <br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2014 at https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | state                         | STATE                         | text          | text          |
| Yes      | numeric metric | service_area_population       | SERVICE AREA POPULATION       | number        | number        |
| Yes      | numeric metric | unduplicated_population       | UNDUPLICATED POPULATION       | number        | number        |
| Yes      | numeric metric | state_population              | STATE POPULATION              | number        | number        |
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
| Yes      | time           | start_date                    | START DATE                    | calendar_date | calendar_date |
| No       |                | end_date                      | END DATE                      | calendar_date | calendar_date |
| No       |                | year                          | YEAR                          | calendar_date | calendar_date |
| Yes      | series tag     | bea_code                      | BEA REGION                    | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,year
```

## Data Commands

```ls
series e:mph3-8hz6 d:2013-10-01T00:00:00.000Z t:bea_code=9 t:state=AS m:users=14054 m:kids_program_audience=6893 m:other_staff=5 m:electronic_expenditures=23366 m:video_materials=290 m:federal_revenue=85500 m:print_serials=2 m:references=2119 m:other_capital_revenue=0 m:total_staff=12 m:total_expenditures=520024 m:total_collection_expenditures=62880 m:local_databases=0 m:ebooks=0 m:librarian_staff=7 m:kids_programs=439 m:program_audience=6999 m:other_revenue=14000 m:ya_programs=1 m:hours=3680 m:local_capital_revenue=0 m:electronic_circulation=0 m:video_downloads=0 m:audio_downloads=0 m:total_capital_revenue=0 m:unduplicated_population=61241 m:salaries=266881 m:total_revenue=484500 m:print_expenditures=29045 m:service_area_population=61811 m:state_capital_revenue=0 m:branch_libraries=1 m:audio_materials=895 m:local_revenue=0 m:total_staff_expenditures=309474 m:total_circulation=26191 m:kids_circulation=9218 m:print_materials=40880 m:other_expenditures=147670 m:total_databases=33 m:other_collection_expenditures=10469 m:computers=20 m:ya_program_audience=12 m:capital_expenditures=0 m:loans_to=0 m:mls_librarian_staff=2 m:loans_from=0 m:total_programs=448 m:federal_capital_revenue=0 m:state_revenue=385000 m:central_libraries=1 m:bookmobiles=0 m:state_databases=33 m:computer_users=6295 m:benefits=42593 m:wifi_sessions=0 m:visits=70487 m:state_population=61811

series e:mph3-8hz6 d:2013-10-01T00:00:00.000Z t:bea_code=9 t:state=MP m:users=-1 m:kids_program_audience=-1 m:other_staff=-1 m:electronic_expenditures=-1 m:video_materials=-1 m:federal_revenue=-1 m:print_serials=-1 m:references=-1 m:other_capital_revenue=-1 m:total_staff=-1 m:total_expenditures=-1 m:total_collection_expenditures=-1 m:local_databases=-1 m:ebooks=-1 m:librarian_staff=-1 m:kids_programs=-1 m:program_audience=-1 m:other_revenue=-1 m:ya_programs=-1 m:hours=-1 m:local_capital_revenue=-1 m:electronic_circulation=-1 m:video_downloads=-1 m:audio_downloads=-1 m:total_capital_revenue=-1 m:unduplicated_population=53883 m:salaries=-1 m:total_revenue=-1 m:print_expenditures=-1 m:service_area_population=53883 m:state_capital_revenue=-1 m:branch_libraries=1 m:audio_materials=-1 m:local_revenue=-1 m:total_staff_expenditures=-1 m:total_circulation=-1 m:kids_circulation=-1 m:print_materials=-1 m:other_expenditures=-1 m:total_databases=-1 m:other_collection_expenditures=-1 m:computers=-1 m:ya_program_audience=-1 m:capital_expenditures=-1 m:loans_to=-1 m:mls_librarian_staff=-1 m:loans_from=-1 m:total_programs=-1 m:federal_capital_revenue=-1 m:state_revenue=-1 m:central_libraries=1 m:bookmobiles=0 m:state_databases=-1 m:computer_users=-1 m:benefits=-1 m:wifi_sessions=-1 m:visits=-1 m:state_population=53883

series e:mph3-8hz6 d:2014-01-01T00:00:00.000Z t:bea_code=2 t:state=NJ m:users=4408002 m:kids_program_audience=2000242 m:other_staff=3323.64 m:electronic_expenditures=6113387 m:video_materials=2106354 m:federal_revenue=835625 m:print_serials=50033 m:references=7756313 m:other_capital_revenue=1385852 m:total_staff=4733.97 m:total_expenditures=453105541 m:total_collection_expenditures=40765435 m:local_databases=4318 m:ebooks=3162812 m:librarian_staff=1410.33 m:kids_programs=95163 m:program_audience=3335649 m:other_revenue=18793799 m:ya_programs=15732 m:hours=1176738 m:local_capital_revenue=9913006 m:electronic_circulation=2580124 m:video_downloads=280548.806 m:audio_downloads=2457319 m:total_capital_revenue=12029206 m:unduplicated_population=8708750 m:salaries=231317535 m:total_revenue=473030623 m:print_expenditures=26734242 m:service_area_population=9414939 m:state_capital_revenue=189548 m:branch_libraries=143 m:audio_materials=1721872 m:local_revenue=449614622 m:total_staff_expenditures=325998718 m:total_circulation=58683207 m:kids_circulation=22895245 m:print_materials=28228099 m:other_expenditures=86341388 m:total_databases=12606 m:other_collection_expenditures=7917806 m:computers=8023 m:ya_program_audience=207662 m:capital_expenditures=10372327 m:loans_to=2365731 m:mls_librarian_staff=1177.28 m:loans_from=2359827 m:total_programs=178601 m:federal_capital_revenue=540800 m:state_revenue=3786577 m:central_libraries=296 m:bookmobiles=12 m:state_databases=8288 m:computer_users=9799563 m:benefits=94681183 m:wifi_sessions=4210632 m:visits=45848755 m:state_population=8791894
```

## Meta Commands

```ls
metric m:service_area_population p:integer l:"SERVICE AREA POPULATION" d:"Population of the legal service area (POPU_LSA)" t:dataTypeName=number

metric m:unduplicated_population p:integer l:"UNDUPLICATED POPULATION" d:"Total unduplicated population of those areas in a state that receive library services. The population of unserved areas is not included in this figure. (POPU_UND)" t:dataTypeName=number

metric m:state_population p:integer l:"STATE POPULATION" d:"State population estimate (POPU_ST)" t:dataTypeName=number

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

metric m:video_downloads p:double l:"VIDEO DOWNLOADS" d:"Number of downloadable video titles in collection (VIDEO_DL)" t:dataTypeName=number

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

metric m:wifi_sessions p:integer l:"WIFI SESSIONS" d:"Number of wireless sessions provided by the library's wifi (WIFISESS)" t:dataTypeName=number

entity e:mph3-8hz6 l:"State Profiles: FY 2014 Public Libraries Survey (Data)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/mph3-8hz6

property e:mph3-8hz6 t:meta.view v:id=mph3-8hz6 v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="State Profiles: FY 2014 Public Libraries Survey (Data)" v:attribution=IMLS

property e:mph3-8hz6 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:mph3-8hz6 t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:mph3-8hz6 t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:mph3-8hz6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| state | service_area_population | unduplicated_population | state_population | central_libraries | branch_libraries | bookmobiles | mls_librarian_staff | librarian_staff | other_staff | total_staff | local_revenue | state_revenue | federal_revenue | other_revenue | total_revenue | salaries  | benefits | total_staff_expenditures | print_expenditures | electronic_expenditures | other_collection_expenditures | total_collection_expenditures | other_expenditures | total_expenditures | local_capital_revenue | state_capital_revenue | federal_capital_revenue | other_capital_revenue | total_capital_revenue | capital_expenditures | print_materials | ebooks  | audio_materials | audio_downloads | video_materials | video_downloads | local_databases | state_databases | total_databases | print_serials | hours   | visits   | references | users   | total_circulation | kids_circulation | electronic_circulation | loans_to | loans_from | total_programs | kids_programs | ya_programs | program_audience | kids_program_audience | ya_program_audience | computers | computer_users | wifi_sessions | start_date          | end_date            | year                | bea_code | 
| ===== | ======================= | ======================= | ================ | ================= | ================ | =========== | =================== | =============== | =========== | =========== | ============= | ============= | =============== | ============= | ============= | ========= | ======== | ======================== | ================== | ======================= | ============================= | ============================= | ================== | ================== | ===================== | ===================== | ======================= | ===================== | ===================== | ==================== | =============== | ======= | =============== | =============== | =============== | =============== | =============== | =============== | =============== | ============= | ======= | ======== | ========== | ======= | ================= | ================ | ====================== | ======== | ========== | ============== | ============= | =========== | ================ | ===================== | =================== | ========= | ============== | ============= | =================== | =================== | =================== | ======== | 
| AS    | 61811                   | 61241                   | 61811            | 1                 | 1                | 0           | 2                   | 7               | 5           | 12          | 0             | 385000        | 85500           | 14000         | 484500        | 266881    | 42593    | 309474                   | 29045              | 23366                   | 10469                         | 62880                         | 147670             | 520024             | 0                     | 0                     | 0                       | 0                     | 0                     | 0                    | 40880           | 0       | 895             | 0               | 290             | 0               | 0               | 33              | 33              | 2             | 3680    | 70487    | 2119       | 14054   | 26191             | 9218             | 0                      | 0        | 0          | 448            | 439           | 1           | 6999             | 6893                  | 12                  | 20        | 6295           | 0             | 2013-10-01T00:00:00 | 2014-09-01T00:00:00 | 2015-01-01T00:00:00 | 9        | 
| MP    | 53883                   | 53883                   | 53883            | 1                 | 1                | 0           | -1                  | -1              | -1          | -1          | -1            | -1            | -1              | -1            | -1            | -1        | -1       | -1                       | -1                 | -1                      | -1                            | -1                            | -1                 | -1                 | -1                    | -1                    | -1                      | -1                    | -1                    | -1                   | -1              | -1      | -1              | -1              | -1              | -1              | -1              | -1              | -1              | -1            | -1      | -1       | -1         | -1      | -1                | -1               | -1                     | -1       | -1         | -1             | -1            | -1          | -1               | -1                    | -1                  | -1        | -1             | -1            | 2013-10-01T00:00:00 | 2014-09-01T00:00:00 | 2015-01-01T00:00:00 | 9        | 
| NJ    | 9414939                 | 8708750                 | 8791894          | 296               | 143              | 12          | 1177.28             | 1410.33         | 3323.64     | 4733.97     | 449614622     | 3786577       | 835625          | 18793799      | 473030623     | 231317535 | 94681183 | 325998718                | 26734242           | 6113387                 | 7917806                       | 40765435                      | 86341388           | 453105541          | 9913006               | 189548                | 540800                  | 1385852               | 12029206              | 10372327             | 28228099        | 3162812 | 1721872         | 2457319         | 2106354         | 280548.806      | 4318            | 8288            | 12606           | 50033         | 1176738 | 45848755 | 7756313    | 4408002 | 58683207          | 22895245         | 2580124                | 2365731  | 2359827    | 178601         | 95163         | 15732       | 3335649          | 2000242               | 207662              | 8023      | 9799563        | 4210632       | 2014-01-01T00:00:00 | 2014-12-01T00:00:00 | 2015-01-01T00:00:00 | 2        | 
| PR    | 3970205                 | 1652260                 | 2548397          | 58                | 78               | 1           | 9                   | 79              | 189         | 268         | 2529128       | 53340         | 271930          | 15944         | 1713775       | 2586350   | 353245   | 2799330                  | 44115              | 18703                   | 14128                         | 65319                         | 593764             | 1313810            | 1168481               | 112517                | 164598                  | -1                    | -1                    | 1370461              | 169218          | 30152   | 3640            | 30              | 3994            | 12              | 175             | 1               | 176             | 16            | 139201  | 431263   | 85951      | 69916   | 45047             | 20285            | 20780                  | 28       | 11         | 450            | 196           | 149         | 24709            | 7306                  | 5789                | 849       | 192340         | 0             | 2014-01-01T00:00:00 | 2014-12-01T00:00:00 | 2015-01-01T00:00:00 | 9        | 
| PA    | 12446680                | 12428101                | 12702379         | 451               | 170              | 23          | 1164.29             | 1481.54         | 2961.98     | 4443.52     | 223409031     | 57379652      | 1819838         | 61268159      | 343876680     | 163050108 | 58030442 | 221080550                | 22371974           | 7011479                 | 6021933                       | 35405386                      | 78001488           | 334487424          | 1460478               | 494847                | 111517                  | 7631612               | 9698454               | 21257729             | 25780211        | 5301993 | 2140503         | 2282611         | 1857006         | 417155.8792     | 4022            | 6825            | 10847           | 45727         | 1444417 | 44791865 | 7851903    | 5330482 | 66393992          | 24540460         | 4570604                | 4436687  | 4507204    | 207872         | 125188        | 19448       | 4101104          | 2955004               | 270086              | 8050      | 8543924        | 6372909       | 2013-07-01T00:00:00 | 2014-12-01T00:00:00 | 2015-01-01T00:00:00 | 2        | 
| NM    | 1670727                 | 1646422                 | 2085287          | 95                | 27               | 1           | 125.64              | 282.04          | 377.23      | 659.27      | 42323009      | 2708991       | 207372          | 2719540       | 47958912      | 20894260  | 8057770  | 28952030                 | 4025980            | 1554520                 | 1124687                       | 6705187                       | 9816345            | 45473562           | 5671834               | 2926859               | 206057                  | 379546                | 9184296               | 7760951              | 4309295         | 197152  | 210179          | 89883           | 307311          | 1177            | 460             | 4275            | 4735            | 6300          | 257155  | 7351791  | 1426952    | 1029945 | 9226822           | 2981691          | 542564                 | 16077    | 20792      | 20050          | 11397         | 2763        | 469943           | 335275                | 37130               | 1639      | 2094371        | 1916770       | 2013-07-01T00:00:00 | 2014-06-01T00:00:00 | 2015-01-01T00:00:00 | 6        | 
| MI    | 9849089                 | 9844810                 | 9898193          | 385               | 259              | 9           | 1238.11             | 1777.89         | 3012.81     | 4790.7      | 359285768     | 11070837      | 486509          | 25404155      | 396247269     | 174190243 | 62945210 | 237135453                | 24013147           | 6630975                 | 9540514                       | 40184636                      | 93853803           | 371173892          | 6850972               | 49290                 | 159986                  | 7118309               | 14178557              | 24794044             | 32565459        | 2803502 | 1968511         | 971790          | 2451954         | 46626.19139     | 1699            | 15560           | 17259           | 50621         | 1425210 | 50132634 | 9284074    | 5128464 | 83845712          | 26693442         | 5906653                | 2740279  | 2931252    | 125326         | 69603         | 11135       | 3167988          | 2100613               | 203240              | 11930     | 10827079       | 5654741       | 2012-12-01T00:00:00 | 2014-09-01T00:00:00 | 2015-01-01T00:00:00 | 3        | 
| AZ    | 10501253                | 6667241                 | 6667241          | 85                | 135              | 11          | 461.32              | 546.24          | 1485.28     | 2031.52     | 157746903     | 1611605       | 2029032         | 7024609       | 168412149     | 77164201  | 28609129 | 105773330                | 14556902           | 6231405                 | 5788517                       | 26576824                      | 44262826           | 176612980          | 7588520               | 30000                 | 55484                   | 83500                 | 7757504               | 3436844              | 8229850         | 1367378 | 689616          | 694223          | 1116663         | 6281            | 969             | 2430            | 3399            | 14239         | 482261  | 27609711 | 5754966    | 3118825 | 43672067          | 13265778         | 3280786                | 324668   | 367263     | 73875          | 37852         | 6702        | 1472963          | 1034731               | 109545              | 5593      | 8255038        | 5880952       | 2013-07-01T00:00:00 | 2014-06-01T00:00:00 | 2015-01-01T00:00:00 | 6        | 
| MN    | 5739502                 | 5417838                 | 5417838          | 129               | 227              | 8           | 519.2               | 775.15          | 1361.81     | 2136.96     | 182233620     | 8918905       | 97563           | 19938516      | 211188604     | 98927386  | 32418492 | 131345878                | 14499431           | 5041239                 | 4471933                       | 24012603                      | 51291274           | 206649755          | 20663779              | 29332                 | 0                       | 212052                | 20905163              | 23940529             | 14612520        | 3471705 | 883217          | 458876          | 985434          | 27497           | 1015            | 6576            | 7591            | 26248         | 727435  | 24566264 | 3964376    | 4080678 | 54127960          | 20814829         | 3936316                | 1148394  | 1091411    | 62120          | 37914         | 6263        | 1396310          | 1032396               | 76959               | 5630      | 5441683        | 864660        | 2014-01-01T00:00:00 | 2014-12-01T00:00:00 | 2015-01-01T00:00:00 | 4        | 
| CT    | 4374214                 | 3596080                 | 3596080          | 192               | 47               | 4           | 752.51              | 1074.91         | 1210.12     | 2285.03     | 168823962     | 1618933       | 330504          | 24624113      | 195397512     | 114615887 | 33333225 | 147949112                | 12363802           | 3577446                 | 3217904                       | 19159152                      | 36150456           | 203258720          | 9834713               | 3037860               | 216618                  | 9350986               | 22440177              | 26583582             | 14577630        | 1312468 | 826586          | 1025994         | 1122198         | 13481           | 1687            | 7606            | 9293            | 21268         | 551274  | 21972583 | 3494403    | 1647190 | 31081616          | 10896026         | 993703                 | 934646   | 918765     | 95517          | 54737         | 7381        | 2003864          | 1226174               | 112501              | 4355      | 4465464        | 524318        | 2013-07-01T00:00:00 | 2014-06-01T00:00:00 | 2015-01-01T00:00:00 | 1        | 
```