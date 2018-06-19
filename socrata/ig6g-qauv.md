# Location Information Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/location-information-report) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ig6g-qauv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ig6g-qauv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ig6g-qauv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ig6g-qauv |
| Name | Location Information Report |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Created | 2015-09-01T13:59:14Z |
| Publication Date | 2017-03-03T19:35:58Z |

## Description

Report of all DOE School Information including Principal and Superintendent names, Cluster, Network, addresses & phone numbers

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                    | Data Type     | Render Type   |
| ======== | =========== | ======================================= | ======================================= | ============= | ============= |
| Yes      | series tag  | school_year                             | School Year                             | text          | text          |
| Yes      | series tag  | ats_system_code                         | ATS System Code                         | text          | text          |
| Yes      | series tag  | location_code                           | Location Code                           | text          | text          |
| Yes      | series tag  | location_name                           | Location Name                           | text          | text          |
| Yes      | series tag  | beds_number                             | BEDS Number                             | text          | number        |
| Yes      | series tag  | managed_by_name                         | Managed By Name                         | text          | text          |
| Yes      | series tag  | location_type_description               | Location Type Description               | text          | text          |
| Yes      | series tag  | location_category_description           | Location Category Description           | text          | text          |
| Yes      | series tag  | grades                                  | Grades                                  | text          | text          |
| Yes      | series tag  | grades_final                            | Grades Final                            | text          | text          |
| Yes      | time        | open_date                               | Open Date                               | calendar_date | calendar_date |
| Yes      | series tag  | status_description                      | Status Description                      | text          | text          |
| Yes      | series tag  | building_code                           | Building Code                           | text          | text          |
| No       |             | primary_address                         | Primary Address                         | text          | text          |
| Yes      | series tag  | city                                    | City                                    | text          | text          |
| Yes      | series tag  | state_code                              | State Code                              | text          | text          |
| Yes      | series tag  | zip                                     | Zip                                     | text          | number        |
| Yes      | series tag  | principal_name                          | Principal Name                          | text          | text          |
| Yes      | series tag  | principal_title                         | Principal Title                         | text          | text          |
| Yes      | series tag  | principal_email                         | Principal Email                         | text          | text          |
| Yes      | series tag  | principal_phone_number                  | Principal Phone Number                  | text          | text          |
| Yes      | series tag  | fax_number                              | Fax Number                              | text          | text          |
| Yes      | series tag  | geographical_district_code              | Geographical District Code              | text          | number        |
| Yes      | series tag  | administrative_district_code            | Administrative District Code            | text          | number        |
| Yes      | series tag  | administrative_district_location_code   | Administrative District Location Code   | text          | text          |
| Yes      | series tag  | administrative_district_name            | Administrative District Name            | text          | text          |
| Yes      | series tag  | superintendent                          | Superintendent                          | text          | text          |
| Yes      | series tag  | superintendent_location_code            | Superintendent Location Code            | text          | text          |
| Yes      | series tag  | superintendent_email                    | Superintendent Email                    | text          | text          |
| Yes      | series tag  | community_school_sup_name               | Community School Sup Name               | text          | text          |
| Yes      | series tag  | community_school_sup_email              | Community School Sup Email              | text          | text          |
| Yes      | series tag  | bfsc_location_code                      | BFSC Location Code                      | text          | text          |
| Yes      | series tag  | bfsc_director_name                      | BFSC Director Name                      | text          | text          |
| Yes      | series tag  | bfsc_director_title                     | BFSC Director Title                     | text          | text          |
| Yes      | series tag  | bfsc_director_phone                     | BFSC Director Phone                     | text          | text          |
| Yes      | series tag  | bfsc_director_email                     | BFSC Director Email                     | text          | text          |
| Yes      | series tag  | highschool_network_location_code        | HighSchool Network Location Code        | text          | text          |
| Yes      | series tag  | highschool_network_name                 | HighSchool Network Name                 | text          | text          |
| Yes      | series tag  | highschool_network_superintendent       | HighSchool Network Superintendent       | text          | text          |
| Yes      | series tag  | highschool_network_superintendent_email | HighSchool Network Superintendent Email | text          | text          |
| Yes      | series tag  | prose_school                            | PROSE SCHOOL                            | text          | text          |
| No       |             | x_coordinate                            | X Coordinate                            | number        | number        |
| No       |             | y_coordinate                            | Y Coordinate                            | number        | number        |
| No       |             | latitude                                | Latitude                                | number        | number        |
| No       |             | longitude                               | Longitude                               | number        | number        |
```

## Time Field

```ls
Value = open_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = primary_address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:ig6g-qauv d:1644-01-01T00:00:00.000Z t:bfsc_director_email=YChu@schools.nyc.gov t:principal_email=ISanchez11@schools.nyc.gov t:bfsc_director_title="BFSC Director" t:status_description=Open t:managed_by_name=DOE t:geographical_district_code=1 t:location_code=M015 t:administrative_district_location_code=M801 t:superintendent="PHILLIPS, DANIELLA" t:bfsc_director_name="CHU, YUET" t:beds_number=310000000000 t:city=MANHATTAN t:administrative_district_code=1 t:location_category_description=Elementary t:community_school_sup_name="PHILLIPS, DANIELLA" t:principal_phone_number=212-228-8730 t:principal_title=PRINCIPAL t:grades_final=PK,0K,01,02,03,04,05 t:bfsc_director_phone=646-470-0721 t:prose_school=N t:bfsc_location_code=MFSC t:superintendent_email=DPhilli@schools.nyc.gov t:fax_number=212-477-0931 t:ats_system_code=01M015 t:zip=10009 t:location_name="P.S. 015 Roberto Clemente" t:state_code=NY t:principal_name="IRENE SANCHEZ" t:community_school_sup_email=DPhilli@schools.nyc.gov t:school_year=2015-16 t:superintendent_location_code=M801 t:location_type_description="General Academic" t:building_code=M015 t:administrative_district_name="COMMUNITY SCHOOL DISTRICT 01" t:grades=PK,01,02,03,04,05,SE m:row_number.ig6g-qauv=1

series e:ig6g-qauv d:20637-01-01T00:00:00.000Z t:bfsc_director_email=YChu@schools.nyc.gov t:principal_email=JFlanagan@schools.nyc.gov t:bfsc_director_title="BFSC Director" t:status_description=Open t:managed_by_name=DOE t:geographical_district_code=1 t:location_code=M019 t:administrative_district_location_code=M801 t:superintendent="PHILLIPS, DANIELLA" t:bfsc_director_name="CHU, YUET" t:beds_number=310000000000 t:city=MANHATTAN t:administrative_district_code=1 t:location_category_description=Elementary t:community_school_sup_name="PHILLIPS, DANIELLA" t:principal_phone_number=212-533-5340 t:principal_title=PRINCIPAL t:grades_final=PK,0K,01,02,03,04,05 t:bfsc_director_phone=646-470-0721 t:prose_school=N t:bfsc_location_code=MFSC t:superintendent_email=DPhilli@schools.nyc.gov t:fax_number=212-673-1477 t:ats_system_code=01M019 t:zip=10003 t:location_name="P.S. 019 Asher Levy" t:state_code=NY t:principal_name="JACQUELINE FLANAGAN" t:community_school_sup_email=DPhilli@schools.nyc.gov t:school_year=2015-16 t:superintendent_location_code=M801 t:location_type_description="General Academic" t:building_code=M019 t:administrative_district_name="COMMUNITY SCHOOL DISTRICT 01" t:grades=PK,0K,01,02,03,04,05,SE m:row_number.ig6g-qauv=2

series e:ig6g-qauv d:23193-01-01T00:00:00.000Z t:bfsc_director_email=YChu@schools.nyc.gov t:principal_email=CColon5@schools.nyc.gov t:bfsc_director_title="BFSC Director" t:status_description=Open t:managed_by_name=DOE t:geographical_district_code=1 t:location_code=M020 t:administrative_district_location_code=M801 t:superintendent="PHILLIPS, DANIELLA" t:bfsc_director_name="CHU, YUET" t:beds_number=310000000000 t:city=MANHATTAN t:administrative_district_code=1 t:location_category_description=Elementary t:community_school_sup_name="PHILLIPS, DANIELLA" t:principal_phone_number=212-254-9577 t:principal_title=PRINCIPAL t:grades_final=PK,0K,01,02,03,04,05 t:bfsc_director_phone=646-470-0721 t:prose_school=N t:bfsc_location_code=MFSC t:superintendent_email=DPhilli@schools.nyc.gov t:fax_number=212-254-3526 t:ats_system_code=01M020 t:zip=10002 t:location_name="P.S. 020 Anna Silver" t:state_code=NY t:principal_name="Carmen Colon" t:community_school_sup_email=DPhilli@schools.nyc.gov t:school_year=2015-16 t:superintendent_location_code=M801 t:location_type_description="General Academic" t:building_code=M020 t:administrative_district_name="COMMUNITY SCHOOL DISTRICT 01" t:grades=PK,0K,01,02,03,04,05,SE m:row_number.ig6g-qauv=3
```

## Meta Commands

```ls
metric m:row_number.ig6g-qauv p:long l:"Row Number"

entity e:ig6g-qauv l:"Location Information Report" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ig6g-qauv

property e:ig6g-qauv t:meta.view v:id=ig6g-qauv v:category=Education v:averageRating=0 v:name="Location Information Report" v:attribution="Department of Education (DOE)"

property e:ig6g-qauv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ig6g-qauv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| school_year | ats_system_code | location_code | location_name                  | beds_number  | managed_by_name | location_type_description | location_category_description | grades                           | grades_final                  | open_date            | status_description | building_code | primary_address    | city      | state_code | zip   | principal_name      | principal_title | principal_email            | principal_phone_number | fax_number   | geographical_district_code | administrative_district_code | administrative_district_location_code | administrative_district_name | superintendent     | superintendent_location_code | superintendent_email    | community_school_sup_name | community_school_sup_email | bfsc_location_code | bfsc_director_name | bfsc_director_title | bfsc_director_phone | bfsc_director_email  | highschool_network_location_code | highschool_network_name | highschool_network_superintendent | highschool_network_superintendent_email | prose_school | x_coordinate | y_coordinate | latitude  | longitude  | 
| =========== | =============== | ============= | ============================== | ============ | =============== | ========================= | ============================= | ================================ | ============================= | ==================== | ================== | ============= | ================== | ========= | ========== | ===== | =================== | =============== | ========================== | ====================== | ============ | ========================== | ============================ | ===================================== | ============================ | ================== | ============================ | ======================= | ========================= | ========================== | ================== | ================== | =================== | =================== | ==================== | ================================ | ======================= | ================================= | ======================================= | ============ | ============ | ============ | ========= | ========== | 
| 2015-16     | 01M015          | M015          | P.S. 015 Roberto Clemente      | 310000000000 | DOE             | General Academic          | Elementary                    | PK,01,02,03,04,05,SE             | PK,0K,01,02,03,04,05          | 1644-01-01T00:00:00  | Open               | M015          | 333 EAST 4 STREET  | MANHATTAN | NY         | 10009 | IRENE SANCHEZ       | PRINCIPAL       | ISanchez11@schools.nyc.gov | 212-228-8730           | 212-477-0931 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 990141       | 202349       | 40.722075 | -73.978747 | 
| 2015-16     | 01M019          | M019          | P.S. 019 Asher Levy            | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 20637-01-01T00:00:00 | Open               | M019          | 185 1 AVENUE       | MANHATTAN | NY         | 10003 | JACQUELINE FLANAGAN | PRINCIPAL       | JFlanagan@schools.nyc.gov  | 212-533-5340           | 212-673-1477 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988547       | 205239       | 40.730009 | -73.984496 | 
| 2015-16     | 01M020          | M020          | P.S. 020 Anna Silver           | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 23193-01-01T00:00:00 | Open               | M020          | 166 ESSEX STREET   | MANHATTAN | NY         | 10002 | Carmen Colon        | PRINCIPAL       | CColon5@schools.nyc.gov    | 212-254-9577           | 212-254-3526 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988044       | 202068       | 40.721305 | -73.986312 | 
| 2015-16     | 01M034          | M034          | P.S. 034 Franklin D. Roosevelt | 310000000000 | DOE             | General Academic          | K-8                           | PK,0K,01,02,03,04,05,06,07,08,SE | PK,0K,01,02,03,04,05,06,07,08 | 20271-01-01T00:00:00 | Open               | M034          | 730 EAST 12 STREET | MANHATTAN | NY         | 10009 | Rosemarie Gonzalez  | PRINCIPAL       | RGonzal52@schools.nyc.gov  | 212-228-4433           | 212-353-1973 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 991163       | 203782       | 40.726008 | -73.975058 | 
| 2015-16     | 01M063          | M063          | The STAR Academy - P.S.63      | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 2009-01-01T00:00:00  | Open               | M063          | 121 EAST 3 STREET  | MANHATTAN | NY         | 10009 | DARLENE CAMERON     | PRINCIPAL       | DCameron2@schools.nyc.gov  | 212-674-3180           | 212-420-9018 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988071       | 203210       | 40.72444  | -73.986214 | 
| 2015-16     | 01M064          | M064          | P.S. 064 Robert Simon          | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,06,SE       | PK,0K,01,02,03,04,05          | 19906-01-01T00:00:00 | Open               | M064          | 600 EAST 6 STREET  | MANHATTAN | NY         | 10009 | Marlon L. Hosang    | PRINCIPAL       | mhosang@schools.nyc.gov    | 212-673-6510           | 212-477-2369 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 989351       | 202733       | 40.72313  | -73.981597 | 
| 2015-16     | 01M110          | M110          | P.S. 110 Florence Nightingale  | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 0912-12-27T00:00:00  | Open               | M110          | 285 DELANCY STREET | MANHATTAN | NY         | 10002 | KAREN FEUER         | PRINCIPAL       | KFeuer@schools.nyc.gov     | 212-674-2690           | 212-475-5835 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 989817       | 199992       | 40.7162   | -73.9798   | 
| 2015-16     | 01M134          | M134          | P.S. 134 Henrietta Szold       | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 22098-01-01T00:00:00 | Open               | M134          | 293 EAST BROADWAY  | MANHATTAN | NY         | 10002 | Daniel Kim          | PRINCIPAL       | DKim@schools.nyc.gov       | 212-673-4470           | 212-475-6142 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988726       | 199497       | 40.714248 | -73.983854 | 
| 2015-16     | 01M137          | M137          | P.S. 137 John L. Bernstein     | 310000000000 | DOE             | General Academic          | Elementary                    | PK,0K,01,02,03,04,05,SE          | PK,0K,01,02,03,04,05          | 24289-01-01T00:00:00 | Open               | M134          | 293 EAST BROADWAY  | MANHATTAN | NY         | 10002 | SARAH PINTO VIAGRAN | I.A. PRINCIPAL  | SPinto4@schools.nyc.gov    | 646-602-2140           | 646-602-2146 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988726       | 199497       | 40.714248 | -73.983854 | 
| 2015-16     | 01M140          | M140          | P.S. 140 Nathan Straus         | 310000000000 | DOE             | General Academic          | K-8                           | PK,0K,01,02,03,04,05,06,07,08,SE | PK,0K,01,02,03,04,05,06,07,08 | 21732-01-01T00:00:00 | Open               | M140          | 123 RIDGE STREET   | MANHATTAN | NY         | 10002 | MELISSA RODRIGUEZ   | PRINCIPAL       | MRodrig19@schools.nyc.gov  | 212-677-4680           | 212-677-3907 | 1                          | 1                            | M801                                  | COMMUNITY SCHOOL DISTRICT 01 | PHILLIPS, DANIELLA | M801                         | DPhilli@schools.nyc.gov | PHILLIPS, DANIELLA        | DPhilli@schools.nyc.gov    | MFSC               | CHU, YUET          | BFSC Director       | 646-470-0721        | YChu@schools.nyc.gov |                                  |                         |                                   |                                         | N            | 988749       | 201282       | 40.719148 | -73.983769 | 
```