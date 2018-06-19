# Building and Safety Certificate of Occupancy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-safety-certificate-of-occupancy) |
| Metadata | [Link](https://data.lacity.org/api/views/3f9m-afei) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/3f9m-afei/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/3f9m-afei/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 3f9m-afei |
| Name | Building and Safety Certificate of Occupancy |
| Attribution | LADBS |
| Category | A Safe City |
| Tags | ladbs, department of building and safety, building and safety, building, safety, construction services, construction, permit, permit number, permit type, certificate of occupancy, occupancy, cofo ... |
| Created | 2014-04-18T22:58:12Z |
| Publication Date | 2015-12-07T20:40:00Z |

## Description

The Department of Building and Safety is required by the Los Angeles Municipal Code to issue a Certificate of Occupancy for every building or structure in the City of Los Angeles.  A Certificate of Occupancy is a document issued by the Department of Building and Safety certifying a building's compliance with applicable building codes and other laws, and indicating it to be in a condition suitable for occupancy.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================= | ======================================== | ============= | ============= |
| Yes      | series tag     | cofo_number                             | CofO Number                              | text          | number        |
| Yes      | time           | cofo_issue_date                         | CofO Issue Date                          | calendar_date | calendar_date |
| Yes      | series tag     | latest_status                           | Status                                   | text          | text          |
| No       |                | status_date                             | Status Date                              | calendar_date | calendar_date |
| Yes      | numeric metric | assessor_book                           | Assessor Book                            | number        | text          |
| Yes      | series tag     | assessor_page                           | Assessor Page                            | text          | text          |
| Yes      | series tag     | assessor_parcel                         | Assessor Parcel                          | text          | text          |
| Yes      | series tag     | tract                                   | TRACT                                    | text          | text          |
| Yes      | series tag     | block                                   | BLOCK                                    | text          | text          |
| Yes      | series tag     | lot                                     | LOT                                      | text          | text          |
| Yes      | series tag     | reference_old_permit                    | Reference # (Old Permit #)               | text          | text          |
| Yes      | series tag     | pcis_permit                             | PCIS Permit #                            | text          | text          |
| Yes      | series tag     | permit_type                             | Permit Type                              | text          | text          |
| Yes      | series tag     | permit_sub_type                         | Permit Sub-Type                          | text          | text          |
| Yes      | series tag     | permit_category                         | Permit Category                          | text          | text          |
| Yes      | series tag     | project_number                          | Project Number                           | text          | number        |
| Yes      | series tag     | event_code                              | Event Code                               | text          | text          |
| Yes      | series tag     | initiating_office                       | Initiating Office                        | text          | text          |
| No       |                | issue_date                              | Permit Issue Date                        | calendar_date | calendar_date |
| No       |                | address_start                           | Address Start                            | number        | number        |
| No       |                | address_fraction_start                  | Address Fraction Start                   | text          | text          |
| No       |                | address_end                             | Address End                              | number        | number        |
| No       |                | address_fraction_end                    | Address Fraction End                     | text          | text          |
| Yes      | series tag     | street_direction                        | Street Direction                         | text          | text          |
| Yes      | series tag     | street_name                             | Street Name                              | text          | text          |
| Yes      | series tag     | street_suffix                           | Street Suffix                            | text          | text          |
| Yes      | series tag     | suffix_direction                        | Suffix Direction                         | text          | text          |
| Yes      | series tag     | unit_range_start                        | Unit Range Start                         | text          | text          |
| Yes      | series tag     | unit_range_end                          | Unit Range End                           | text          | text          |
| Yes      | series tag     | zip_code                                | Zip Code                                 | text          | number        |
| Yes      | series tag     | work_description                        | Work Description                         | text          | text          |
| Yes      | numeric metric | valuation                               | Valuation                                | money         | money         |
| Yes      | numeric metric | floor_area_l_a_zoning_code_definition   | Floor Area-L.A. Zoning Code Definition   | number        | number        |
| Yes      | numeric metric | of_residential_dwelling_units           | # of Residential Dwelling Units          | number        | number        |
| Yes      | numeric metric | of_stories                              | # of Stories                             | number        | number        |
| Yes      | series tag     | contractors_business_name               | Contractor's Business Name               | text          | text          |
| No       |                | contractor_address                      | Contractor Address                       | text          | text          |
| Yes      | series tag     | contractor_city                         | Contractor City                          | text          | text          |
| Yes      | series tag     | contractor_state                        | Contractor State                         | text          | text          |
| Yes      | series tag     | license_type                            | License Type                             | text          | text          |
| Yes      | numeric metric | license                                 | License #                                | number        | number        |
| Yes      | series tag     | principal_first_name                    | Principal First Name                     | text          | text          |
| Yes      | series tag     | principal_middle_name                   | Principal Middle Name                    | text          | text          |
| Yes      | series tag     | principal_last_name                     | Principal Last Name                      | text          | text          |
| No       |                | license_expiration_date                 | License Expiration Date                  | calendar_date | calendar_date |
| Yes      | series tag     | applicant_first_name                    | Applicant First Name                     | text          | text          |
| Yes      | series tag     | applicant_last_name                     | Applicant Last Name                      | text          | text          |
| Yes      | series tag     | applicant_business_name                 | Applicant Business Name                  | text          | text          |
| No       |                | applicant_address_1                     | Applicant Address 1                      | text          | text          |
| No       |                | applicant_address_2                     | Applicant Address 2                      | text          | text          |
| No       |                | applicant_address_3                     | Applicant Address 3                      | text          | text          |
| Yes      | series tag     | zone                                    | ZONE                                     | text          | text          |
| Yes      | series tag     | occupancy                               | OCCUPANCY                                | text          | text          |
| Yes      | numeric metric | floor_area_l_a_building_code_definition | Floor Area-L.A. Building Code Definition | number        | number        |
| Yes      | series tag     | census_tract                            | Census Tract                             | text          | text          |
```

## Time Field

```ls
Value = cofo_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = status_date,issue_date,address_start,address_fraction_start,address_end,address_fraction_end,contractor_address,license_expiration_date,applicant_address_1,applicant_address_2,applicant_address_3
```

## Data Commands

```ls
series e:3f9m-afei d:2011-02-23T00:00:00.000Z t:permit_category="Plan Check" t:assessor_parcel=007 t:cofo_number=92126 t:permit_type=Bldg-Alter/Repair t:initiating_office=METRO t:principal_middle_name=MICHAEL t:principal_last_name=DUNCAN t:license_type=B t:zip_code=90036 t:street_suffix=BLVD t:street_name=WILSHIRE t:assessor_page=015 t:pcis_permit=10016-10000-22755 t:contractor_city="AGOURA HILLS" t:principal_first_name=JASON t:work_description="ADD ALCOHOL TO EXISTING RESTAURANT PER ZA CASE 2010-1787 (NO NEW CONST" t:applicant_business_name="BRUCE A. MILLER & ASSOC., INC." t:contractors_business_name="DUNCAN CONSTRUCTION INC" t:contractor_state=CA t:tract="P M 5608" t:street_direction=W t:lot=C t:permit_sub_type=Commercial t:latest_status="CofO Corrected" t:reference_old_permit=11LA60242 t:census_tract=2151.00 t:zone=QPB-2 m:valuation=10000 m:floor_area_l_a_building_code_definition=5091 m:license=874204 m:assessor_book=5508

series e:3f9m-afei d:2007-05-14T00:00:00.000Z t:permit_category="Plan Check" t:assessor_parcel=005 t:cofo_number=43479 t:permit_type=Bldg-Addition t:initiating_office="VAN NUYS" t:principal_last_name=RODRIGUEZ t:applicant_last_name=RODRIGUEZ t:license_type=NA t:zip_code=90001 t:street_suffix=ST t:street_name=75TH t:assessor_page=014 t:pcis_permit=06010-20000-04752 t:principal_first_name=LESLIE t:work_description="ADD IRR 32' X 53.42' ONE STORY DWLG UNIT AND ATT TWO CAR CARPORT TO EX" t:contractors_business_name=OWNER-BUILDER t:applicant_first_name=LESLIE t:tract="TR 6097" t:street_direction=E t:lot=493 t:permit_sub_type="1 or 2 Family Dwelling" t:latest_status="CofO Corrected" t:occupancy="R3 Occ. Group" t:reference_old_permit=07VN12018 t:census_tract=2395.00 t:zone=R2-1 m:floor_area_l_a_zoning_code_definition=1113 m:of_stories=1 m:valuation=105000 m:of_residential_dwelling_units=1 m:floor_area_l_a_building_code_definition=1461 m:license=0 m:assessor_book=6023

series e:3f9m-afei d:2013-08-27T00:00:00.000Z t:zip_code=90077 t:assessor_page=003 t:street_name=NALIN t:contractor_city=CHATSWORTH t:block="BLK 16" t:principal_first_name=DANIEL t:work_description="(N) 60' X 79' 2 STORY TYPE V SPRINKLERED SFD W/ ATTACHED 3 CAR GARAGE." t:contractor_state=CA t:latest_status="CofO Corrected" t:census_tract=2622.00 t:reference_old_permit=12VN07058 t:assessor_parcel=022 t:permit_category="Plan Check" t:permit_type=Bldg-New t:cofo_number=105026 t:initiating_office="VAN NUYS" t:license_type=B t:principal_last_name=BERNSTEIN t:principal_middle_name=REPHAN t:pcis_permit=12010-20000-00454 t:street_suffix=DR t:contractors_business_name="D B BUILDERS INC" t:applicant_first_name=ELLEN t:tract="SANTA MONICA LAND AND WATER CO. TRACT" t:permit_sub_type="1 or 2 Family Dwelling" t:street_direction=N t:zone=RE40-1-H m:floor_area_l_a_zoning_code_definition=6493 m:of_stories=2 m:valuation=732048 m:of_residential_dwelling_units=1 m:floor_area_l_a_building_code_definition=7549 m:license=812896 m:assessor_book=4378
```

## Meta Commands

```ls
metric m:assessor_book p:integer l:"Assessor Book" d:"""Book"" portion of the Los Angeles County Tax Assessor ""Book-Page-Parcel"" number." t:dataTypeName=number

metric m:valuation p:integer l:Valuation d:"The property/structure valuation amount is used to calculate the building permit fee and all fees calculated as percentage of the building fee. For all building permit types, except for Grading, the valuation is measured in dollars. For Grading permit applications, the valuation is measured in cubic yards of soil removed or added." t:dataTypeName=money

metric m:floor_area_l_a_zoning_code_definition p:integer l:"Floor Area-L.A. Zoning Code Definition" d:"Floor area as defined in the Los Angeles Zoning Code." t:dataTypeName=number

metric m:of_residential_dwelling_units p:integer l:"# of Residential Dwelling Units" d:"Number of dwelling units for a residential building." t:dataTypeName=number

metric m:of_stories p:integer l:"# of Stories" d:"Number of stories." t:dataTypeName=number

metric m:license p:integer l:"License #" d:"Contractor's license number." t:dataTypeName=number

metric m:floor_area_l_a_building_code_definition p:double l:"Floor Area-L.A. Building Code Definition" d:"Floor area as defined in the Los Angeles Building Code." t:dataTypeName=number

entity e:3f9m-afei l:"Building and Safety Certificate of Occupancy" t:attribution=LADBS t:url=https://data.lacity.org/api/views/3f9m-afei

property e:3f9m-afei t:meta.view v:id=3f9m-afei v:category="A Safe City" v:averageRating=0 v:name="Building and Safety Certificate of Occupancy" v:attribution=LADBS

property e:3f9m-afei t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:3f9m-afei t:meta.view.owner v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:displayName="Building and Safety OpenData"

property e:3f9m-afei t:meta.view.tableauthor v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:roleName=publisher v:displayName="Building and Safety OpenData"
```

## Top Records

```ls
| cofo_number | cofo_issue_date     | latest_status  | status_date         | assessor_book | assessor_page | assessor_parcel | tract                                                                  | block  | lot   | reference_old_permit | pcis_permit       | permit_type       | permit_sub_type        | permit_category | project_number | event_code | initiating_office | issue_date          | address_start | address_fraction_start | address_end | address_fraction_end | street_direction | street_name | street_suffix | suffix_direction | unit_range_start | unit_range_end | zip_code | work_description                                                       | valuation | floor_area_l_a_zoning_code_definition | of_residential_dwelling_units | of_stories | contractors_business_name     | contractor_address          | contractor_city | contractor_state | license_type | license | principal_first_name | principal_middle_name | principal_last_name | license_expiration_date | applicant_first_name | applicant_last_name | applicant_business_name        | applicant_address_1   | applicant_address_2 | applicant_address_3 | zone         | occupancy     | floor_area_l_a_building_code_definition | census_tract | 
| =========== | =================== | ============== | =================== | ============= | ============= | =============== | ====================================================================== | ====== | ===== | ==================== | ================= | ================= | ====================== | =============== | ============== | ========== | ================= | =================== | ============= | ====================== | =========== | ==================== | ================ | =========== | ============= | ================ | ================ | ============== | ======== | ====================================================================== | ========= | ===================================== | ============================= | ========== | ============================= | =========================== | =============== | ================ | ============ | ======= | ==================== | ===================== | =================== | ======================= | ==================== | =================== | ============================== | ===================== | =================== | =================== | ============ | ============= | ======================================= | ============ | 
| 92126       | 2011-02-23T00:00:00 | CofO Corrected | 2013-03-14T00:00:00 | 5508          | 015           | 007             | P M 5608                                                               |        | C     | 11LA60242            | 10016-10000-22755 | Bldg-Alter/Repair | Commercial             | Plan Check      |                |            | METRO             | 2013-03-14T00:00:00 | 5779          |                        | 5779        |                      | W                | WILSHIRE    | BLVD          |                  |                  |                | 90036    | ADD ALCOHOL TO EXISTING RESTAURANT PER ZA CASE 2010-1787 (NO NEW CONST | 10000     |                                       |                               |            | DUNCAN CONSTRUCTION INC       | 5737 KANAN ROAD SUITE 288   | AGOURA HILLS    | CA               | B            | 874204  | JASON                | MICHAEL               | DUNCAN              | 2012-05-31T00:00:00     |                      |                     | BRUCE A. MILLER & ASSOC., INC. | 354 S. SPRING ST.     | STE. 415            | LOS ANGELES, CA     | QPB-2        |               | 5091                                    | 2151.00      | 
| 43479       | 2007-05-14T00:00:00 | CofO Corrected | 2013-02-08T00:00:00 | 6023          | 014           | 005             | TR 6097                                                                |        | 493   | 07VN12018            | 06010-20000-04752 | Bldg-Addition     | 1 or 2 Family Dwelling | Plan Check      |                |            | VAN NUYS          | 2013-02-08T00:00:00 | 818           |                        | 820         |                      | E                | 75TH        | ST            |                  |                  |                | 90001    | ADD IRR 32' X 53.42' ONE STORY DWLG UNIT AND ATT TWO CAR CARPORT TO EX | 105000    | 1113                                  | 1                             | 1          | OWNER-BUILDER                 | 11012 VENTURA BL            |                 |                  | NA           | 0       | LESLIE               |                       | RODRIGUEZ           |                         | LESLIE               | RODRIGUEZ           |                                | 11012 VENTURA BL      | STE #204            | STUDIO CITY, CA     | R2-1         | R3 Occ. Group | 1461                                    | 2395.00      | 
| 105026      | 2013-08-27T00:00:00 | CofO Corrected | 2013-09-03T00:00:00 | 4378          | 003           | 022             | SANTA MONICA LAND AND WATER CO. TRACT                                  | BLK 16 |       | 12VN07058            | 12010-20000-00454 | Bldg-New          | 1 or 2 Family Dwelling | Plan Check      |                |            | VAN NUYS          | 2013-09-03T00:00:00 | 2350          |                        | 2350        |                      | N                | NALIN       | DR            |                  |                  |                | 90077    | (N) 60' X 79' 2 STORY TYPE V SPRINKLERED SFD W/ ATTACHED 3 CAR GARAGE. | 732048    | 6493                                  | 1                             | 2          | D B BUILDERS INC              | 9720 BADEN AVENUE           | CHATSWORTH      | CA               | B            | 812896  | DANIEL               | REPHAN                | BERNSTEIN           | 2012-09-30T00:00:00     | ELLEN                |                     |                                | 9572 TOPANGA CYN BL   |                     | CHATSWORTH          | RE40-1-H     |               | 7549                                    | 2622.00      | 
| 131668      | 2015-02-03T00:00:00 | CofO Corrected | 2015-02-09T00:00:00 | 5135          | 007           | 020             | ALVARADO TERRACE TRACT                                                 | D      | 21    | 15VN89807            | 15016-20000-00936 | Bldg-Alter/Repair | Apartment              | No Plan Check   |                |            | VAN NUYS          | 2015-02-09T00:00:00 | 1443          |                        | 1443        |                      | S                | BONNIE BRAE | ST            |                  |                  |                | 90006    | **NO FEE DEPARTMENT ERROR** Correction of CofO's of permit number's 1  | 0         | 0                                     | 0                             | 0          | OWNER-BUILDER                 |                             |                 |                  | NA           | 0       |                      |                       |                     |                         | MARIO                | HOROWITZ            |                                |                       |                     |                     | RD1.5-1-HPOZ | H3 Occ. Group | 0                                       | 2243.10      | 
| 104813      | 2012-09-27T00:00:00 | CofO Corrected | 2013-08-07T00:00:00 | 2673          | 007           | 066             | TR 22880                                                               |        | 32    | 12VN06657            | 12014-20000-02505 | Bldg-Addition     | 1 or 2 Family Dwelling | Plan Check      |                |            | VAN NUYS          | 2013-08-07T00:00:00 | 15949         |                        | 15949       |                      | W                | NAPA        | ST            |                  |                  |                | 91343    | ADD 5'-10" X 10'-0" BATHROOM TO (E) SFD PER WFPP                       | 5900      | 58.3                                  |                               | 0          | OWNER-BUILDER                 | 15949 NAPA ST.              |                 |                  | NA           | 0       | THAO                 |                       | PHAM                |                         | THAO                 | PHAM                | OWNER-BUILDER                  | 15949 NAPA ST.        |                     | NORTH HILLS, CA     | RS-1         |               | 58.3                                    | 1174.04      | 
| 68844       | 2013-09-18T00:00:00 | CofO Corrected | 2013-11-04T00:00:00 | 5534          | 029           | 003             | EL CENTRO TRACT                                                        | 9      | 3     | 08VN45138            | 07010-20000-04422 | Bldg-New          | Commercial             | Plan Check      |                |            | VAN NUYS          | 2013-11-04T00:00:00 | 5802          |                        | 5802        |                      | W                | WILLOUGHBY  | AVE           |                  |                  |                | 90038    | NEW OFFICE / IMPORT AND EXPORT with UNDERGROUND PARKING GARAGE. STORAG | 1100000   | 13683                                 |                               | 2          | V & R CONSTRUCTION INC        | 13736 CALVERT STREET        | VAN NUYS        | CA               | B            | 812590  | ALEXANDER            | YEVGENYEVICH          | RYKOV               | 2008-09-30T00:00:00     | CHRISTOPHER          | COMPTON             |                                | 1616 VICTORY BL       |                     | GLENDALE, CA        | [Q]C2-1VL    | B Occ. Group  | 13189                                   | 1918.20      | 
| 81792       | 2013-03-19T00:00:00 | CofO Corrected | 2013-09-26T00:00:00 | 5526          | 021           | 011             | TR 6143                                                                |        | 314   | 09WL33850            | 09016-30000-20849 | Bldg-Addition     | 1 or 2 Family Dwelling | Plan Check      |                |            | WEST LA           | 2013-09-26T00:00:00 | 607           |                        | 607         |                      | N                | POINSETTIA  | PL            |                  |                  |                | 90036    | 12 SF Addition to enclose Entranceway and Convert attached front cover | 8000      | 12                                    |                               | 1          | OWNER-BUILDER                 |                             |                 |                  | NA           | 0       |                      |                       |                     | 2000-01-01T00:00:00     | EMMA                 | GRIMM               |                                | 607 N POINSETTIA PL   |                     | LOS ANGELES CA      | R1-1         |               | 160                                     | 1920.00      | 
| 99332       | 2013-03-01T00:00:00 | CofO Corrected | 2013-04-03T00:00:00 | 5533          | 017           | 010             | SENECA HEIGHTS                                                         | A      | 9     | 11LA71866            | 11016-10000-13969 | Bldg-Alter/Repair | Commercial             | Plan Check      |                |            | METRO             | 2013-04-03T00:00:00 | 1057          |                        | 1057        |                      | N                | VINE        | ST            |                  |                  |                | 90038    | PROPOSED INTERIOR ALTERATIONS TO ENTIRE BUILDING. CONVERT HOTEL 64 GUE | 4000000   | 20602                                 | 34                            | 3          | SHANGRI - LA CONSTRUCTION L P | 1075 HAMILTON ROAD          | DUARTE          | CA               | B            | 926436  | CHRISTOPHER          | BRIAN                 | CARR                | 2012-12-31T00:00:00     | CRYSTAL              | WONG                |                                |                       |                     |                     | C2-1D-SN     |               | 18185                                   | 1918.10      | 
| 114380      | 2015-03-04T00:00:00 | CofO Corrected | 2015-03-07T00:00:00 | 4422          | 019           | 012             | TR 16257                                                               |        | 18    | 13WL52958            | 13010-10000-00339 | Bldg-New          | 1 or 2 Family Dwelling | Plan Check      |                |            | METRO             | 2015-03-07T00:00:00 | 15301         |                        | 15301       |                      | W                | WHITFIELD   | AVE           |                  |                  |                | 90272    | CONSTRUCT NEW 2-STORY SINGLE FAMILY DWELLING W/ ATTACHED 2-CAR GARAGE  | 501       | 5793.6                                | 1                             | 2          | BUILDING SOLUTIONS AND DESIGN | 1539 SAWTELLE BLVD SUITE 18 | LOS ANGELES     | CA               | B            | 940604  | AVIV                 |                       | MAMAN               | 2013-12-31T00:00:00     | DAVID                | ROKACH              |                                |                       |                     |                     | R1-1         |               | 5793.6                                  | 2625.01      | 
| 73682       | 2013-10-10T00:00:00 | CofO Corrected | 2013-11-12T00:00:00 | 4205          | 035           | 002             | SUBDIVISION OF THE SOUTHERN PORTION OF THE RANCHO RINCON DE LOS BUEYES |        | LT 28 | 09LA34384            | 08016-10000-09785 | Bldg-Alter/Repair | Commercial             | Plan Check      |                |            | METRO             | 2013-11-12T00:00:00 | 3121          |                        | 3121        |                      | S                | LA CIENEGA  | BLVD          |                  | BLDG 1.01        |                | 90016    | REMODEL OF EXISTING 1 STORY 11,458 SF FURNITURE BUILDING. REMOVING POR | 37500     | 3427                                  |                               | 1          | C S T CONSTRUCTION COMPANY    | 5318 E 2ND STREET #644      | LONG BEACH      | CA               | B            | 801341  | TSUYEE               |                       | TENG                | 2009-11-30T00:00:00     |                      |                     | SOUTHERN CALIFORNIA LAND USE   | 217 PALOS VERDES BLVD | SUITE 123           | REDONDO BEACH       | MR1-1VL      |               | 3427                                    | 2199.00      | 
```