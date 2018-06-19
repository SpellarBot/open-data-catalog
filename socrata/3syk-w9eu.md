# Issued Construction Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/issued-construction-permits) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3syk-w9eu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3syk-w9eu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3syk-w9eu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3syk-w9eu |
| Name | Issued Construction Permits |
| Attribution | Development Services Department |
| Category | Permitting |
| Tags | building, electrical, mechanical, plumbing, permits, driveway, sidewalk, development, services, land development code, permit center, one texas center, blds |
| Created | 2015-07-09T19:05:33Z |
| Publication Date | 2016-05-31T14:11:14Z |

## Description

Building, Electrical, Mechanical, and Plumbing Permits and Driveway/Sidewalk Permits issued by the City of Austin.  Includes relevant details such as issue date, location, council district, expiration date, description of work, square footage, valuation, and units.

This dataset is compliant with the Building & Land Development Specification (BLDS) data standard.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                       | Data Type     | Render Type   |
| ======== | ============== | ============================ | ========================== | ============= | ============= |
| Yes      | series tag     | permittype                   | PermitType                 | text          | text          |
| Yes      | series tag     | permit_type_desc             | PermitTypeDesc             | text          | text          |
| Yes      | series tag     | permit_number                | PermitNum                  | text          | text          |
| Yes      | series tag     | permit_class_mapped          | PermitClassMapped          | text          | text          |
| Yes      | series tag     | permit_class                 | PermitClass                | text          | text          |
| Yes      | series tag     | work_class                   | WorkClass                  | text          | text          |
| Yes      | series tag     | condominium                  | Condominium                | text          | text          |
| Yes      | series tag     | permit_location              | ProjectName                | text          | text          |
| Yes      | series tag     | description                  | Description                | text          | text          |
| Yes      | series tag     | tcad_id                      | TCAD_ID                    | text          | text          |
| Yes      | series tag     | legal_description            | PropertyLegalDescription   | text          | text          |
| No       |                | applieddate                  | AppliedDate                | calendar_date | calendar_date |
| Yes      | time           | issue_date                   | IssuedDate                 | calendar_date | calendar_date |
| Yes      | series tag     | day_issued                   | DayIssued                  | text          | text          |
| Yes      | numeric metric | calendar_year_issued         | CalendarYearIssued         | number        | number        |
| No       |                | fiscal_year_issued           | FiscalYearIssued           | number        | number        |
| Yes      | series tag     | issued_in_last_30_days       | IssuedInLast30Days         | text          | text          |
| Yes      | series tag     | issue_method                 | IssuanceMethod             | text          | text          |
| Yes      | series tag     | status_current               | StatusCurrent              | text          | text          |
| No       |                | statusdate                   | StatusDate                 | calendar_date | calendar_date |
| No       |                | expiresdate                  | ExpiresDate                | calendar_date | calendar_date |
| No       |                | completed_date               | CompletedDate              | calendar_date | calendar_date |
| Yes      | numeric metric | total_existing_bldg_sqft     | TotalExistingBldgSQFT      | number        | number        |
| Yes      | numeric metric | remodel_repair_sqft          | RemodelRepairSQFT          | number        | number        |
| Yes      | numeric metric | total_new_add_sqft           | TotalNewAddSQFT            | number        | number        |
| Yes      | numeric metric | total_valuation_remodel      | TotalValuationRemodel      | money         | money         |
| Yes      | numeric metric | total_job_valuation          | TotalJobValuation          | money         | money         |
| Yes      | numeric metric | number_of_floors             | NumberOfFloors             | number        | number        |
| Yes      | numeric metric | housing_units                | HousingUnits               | number        | number        |
| Yes      | numeric metric | building_valuation           | BuildingValuation          | money         | money         |
| Yes      | numeric metric | building_valuation_remodel   | BuildingValuationRemodel   | money         | money         |
| Yes      | numeric metric | electrical_valuation         | ElectricalValuation        | money         | money         |
| Yes      | numeric metric | electrical_valuation_remodel | ElectricalValuationRemodel | money         | money         |
| Yes      | numeric metric | mechanical_valuation         | MechanicalValuation        | money         | money         |
| Yes      | numeric metric | mechanical_valuation_remodel | MechanicalValuationRemodel | money         | money         |
| Yes      | numeric metric | plumbing_valuation           | PlumbingValuation          | money         | money         |
| Yes      | numeric metric | plumbing_valuation_remodel   | PlumbingValuationRemodel   | money         | money         |
| Yes      | numeric metric | medgas_valuation             | MedGasValuation            | money         | money         |
| Yes      | numeric metric | medgas_valuation_remodel     | MedGasValuationRemodel     | money         | money         |
| No       |                | original_address1            | OriginalAddress1           | text          | text          |
| Yes      | series tag     | original_city                | OriginalCity               | text          | text          |
| Yes      | series tag     | original_state               | OriginalState              | text          | text          |
| Yes      | series tag     | original_zip                 | OriginalZip                | text          | number        |
| Yes      | series tag     | council_district             | CouncilDistrict            | text          | number        |
| Yes      | series tag     | jurisdiction                 | Jurisdiction               | text          | text          |
| Yes      | series tag     | link                         | Link                       | url           | url           |
| Yes      | series tag     | project_id                   | ProjectID                  | text          | number        |
| Yes      | numeric metric | masterpermitnum              | MasterPermitNum            | number        | number        |
| No       |                | latitude                     | Latitude                   | number        | number        |
| No       |                | longitude                    | Longitude                  | number        | number        |
| Yes      | series tag     | contractor_trade             | ContractorTrade            | text          | text          |
| Yes      | series tag     | contractor_company_name      | ContractorCompanyName      | text          | text          |
| Yes      | series tag     | contractor_full_name         | ContractorFullName         | text          | text          |
| Yes      | series tag     | contractor_phone             | ContractorPhone            | phone         | phone         |
| No       |                | contractor_address1          | ContractorAddress1         | text          | text          |
| No       |                | contractor_address2          | ContractorAddress2         | text          | text          |
| Yes      | series tag     | contractor_city              | ContractorCity             | text          | text          |
| Yes      | series tag     | contractor_zip               | ContractorZip              | text          | text          |
| Yes      | series tag     | applicant_full_name          | ApplicantFullName          | text          | text          |
| Yes      | series tag     | applicant_org                | ApplicantOrganization      | text          | text          |
| Yes      | series tag     | applicant_phone              | ApplicantPhone             | phone         | phone         |
| No       |                | applicant_address1           | ApplicantAddress1          | text          | text          |
| No       |                | applicant_address2           | ApplicantAddress2          | text          | text          |
| Yes      | series tag     | applicant_city               | ApplicantCity              | text          | text          |
| Yes      | series tag     | applicantzip                 | ApplicantZip               | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applieddate,statusdate,expiresdate,completed_date,original_address1,latitude,longitude,contractor_address1,contractor_address2,applicant_address1,applicant_address2,fiscal_year_issued
```

## Data Commands

```ls
series e:3syk-w9eu d:2007-04-20T00:00:00.000Z t:original_city=AUSTIN t:phone_number=5123455147 t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024951" t:contractor_city=AUSTIN t:council_district=1 t:jurisdiction="AUSTIN FULL PURPOSE" t:legal_description="LOT 23 BLK Z PIONEER CROSSING WEST SEC 7" t:description="new 1 strory sf res w att garage and cov patio" t:permit_class_mapped=Residential t:issue_method="Permit Center" t:permit_class="R- 101 Single Family Houses" t:tcad_id=0247301018 t:contractor_trade="General Contractor" t:issued_in_last_30_days=No t:status_current=Expired t:permittype=BP t:original_zip=78754 t:permit_location="11436 FLUSHWING DR" t:permit_number="2007-115377 BP" t:condominium=No t:original_state=TX t:contractor_company_name="Newmark Home Corporation, L.P." t:project_id=10024951 t:day_issued=FRIDAY t:contractor_zip=78730-1124 t:permit_type_desc="Building Permit" t:work_class=New m:housing_units=1 m:number_of_floors=1 m:total_new_add_sqft=2347 m:calendar_year_issued=2007 m:total_job_valuation=102795 m:masterpermitnum=10024949

series e:3syk-w9eu d:2007-05-02T00:00:00.000Z t:tcad_id=0247301018 t:original_city=AUSTIN t:issued_in_last_30_days=No t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024952" t:permittype=DS t:status_current=Final t:original_zip=78754 t:council_district=1 t:jurisdiction="AUSTIN FULL PURPOSE" t:permit_location="11436 FLUSHWING DR" t:permit_number="2007-115377 DS" t:legal_description="LOT 23 BLK Z PIONEER CROSSING WEST SEC 7" t:original_state=TX t:permit_class_mapped=Residential t:description="new 1 strory sf res w att garage and cov patio" t:project_id=10024952 t:issue_method="Permit Center" t:permit_class="Res. Driveway & Sidewalk" t:day_issued=WEDNESDAY t:permit_type_desc="Driveway / Sidewalks" t:work_class=New m:calendar_year_issued=2007 m:masterpermitnum=10024951

series e:3syk-w9eu d:2007-06-01T00:00:00.000Z t:original_city=AUSTIN t:phone_number=5126423589 t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024953" t:contractor_city=Hutto t:council_district=1 t:jurisdiction="AUSTIN FULL PURPOSE" t:legal_description="LOT 23 BLK Z PIONEER CROSSING WEST SEC 7" t:description="new 1 strory sf res w att garage and cov patio" t:permit_class_mapped=Residential t:contractor_full_name="Aaron Gifford" t:issue_method="Permit Center" t:permit_class="R- 101 Single Family Houses" t:tcad_id=0247301018 t:contractor_trade="Electrical Contractor" t:issued_in_last_30_days=No t:status_current=Final t:permittype=EP t:original_zip=78754 t:permit_location="11436 FLUSHWING DR" t:condominium=No t:permit_number="2007-115377 EP" t:original_state=TX t:contractor_company_name="Elec Tech" t:project_id=10024953 t:day_issued=FRIDAY t:contractor_zip=78634 t:permit_type_desc="Electrical Permit" t:work_class=New m:housing_units=1 m:number_of_floors=1 m:total_new_add_sqft=2347 m:calendar_year_issued=2007 m:masterpermitnum=10024951
```

## Meta Commands

```ls
metric m:calendar_year_issued p:integer l:CalendarYearIssued d:"Calendar Year corresponding to when the Permit was issued" t:dataTypeName=number

metric m:total_existing_bldg_sqft p:integer l:TotalExistingBldgSQFT t:dataTypeName=number

metric m:remodel_repair_sqft p:integer l:RemodelRepairSQFT t:dataTypeName=number

metric m:total_new_add_sqft p:integer l:TotalNewAddSQFT t:dataTypeName=number

metric m:total_valuation_remodel p:integer l:TotalValuationRemodel d:"Total dollar valuation for remodeling aspects of the job" t:dataTypeName=money

metric m:total_job_valuation p:integer l:TotalJobValuation d:"Total dollar valuation for entire job for each building permit (e.g. will include Building, Electrical, Mechanical, and Plumbing valuations, but not other Building Permits in the same project)" t:dataTypeName=money

metric m:number_of_floors p:integer l:NumberOfFloors t:dataTypeName=number

metric m:housing_units p:integer l:HousingUnits d:"Number of household units for a given building" t:dataTypeName=number

metric m:building_valuation p:integer l:BuildingValuation t:dataTypeName=money

metric m:building_valuation_remodel p:integer l:BuildingValuationRemodel t:dataTypeName=money

metric m:electrical_valuation p:integer l:ElectricalValuation t:dataTypeName=money

metric m:electrical_valuation_remodel p:integer l:ElectricalValuationRemodel t:dataTypeName=money

metric m:mechanical_valuation p:integer l:MechanicalValuation t:dataTypeName=money

metric m:mechanical_valuation_remodel p:integer l:MechanicalValuationRemodel t:dataTypeName=money

metric m:plumbing_valuation p:integer l:PlumbingValuation t:dataTypeName=money

metric m:plumbing_valuation_remodel p:integer l:PlumbingValuationRemodel t:dataTypeName=money

metric m:medgas_valuation p:double l:MedGasValuation t:dataTypeName=money

metric m:medgas_valuation_remodel p:integer l:MedGasValuationRemodel t:dataTypeName=money

metric m:masterpermitnum p:integer l:MasterPermitNum d:"If the permit is listed as the child of another permit, this is the Project ID of that parent permit. A building permit's (BP) master permit number will reference the Plan Review Project ID, while trades under that BP will reference the BP's ID as their master. This may also be called the ""parent folderRSN""." t:dataTypeName=number

entity e:3syk-w9eu l:"Issued Construction Permits" t:attribution="Development Services Department" t:url=https://data.austintexas.gov/api/views/3syk-w9eu

property e:3syk-w9eu t:meta.view v:id=3syk-w9eu v:category=Permitting v:averageRating=0 v:name="Issued Construction Permits" v:attribution="Development Services Department"

property e:3syk-w9eu t:meta.view.license v:name="Public Domain"

property e:3syk-w9eu t:meta.view.owner v:id=g2b7-fzfu v:screenName=Julia v:displayName=Julia

property e:3syk-w9eu t:meta.view.tableauthor v:id=g2b7-fzfu v:screenName=Julia v:roleName=publisher v:displayName=Julia
```

## Top Records

```ls
| permittype | permit_type_desc     | permit_number  | permit_class_mapped | permit_class                          | work_class | condominium | permit_location     | description                                                         | tcad_id    | legal_description                                                 | applieddate         | issue_date          | day_issued | calendar_year_issued | fiscal_year_issued | issued_in_last_30_days | issue_method  | status_current | statusdate          | expiresdate         | completed_date      | total_existing_bldg_sqft | remodel_repair_sqft | total_new_add_sqft | total_valuation_remodel | total_job_valuation | number_of_floors | housing_units | building_valuation | building_valuation_remodel | electrical_valuation | electrical_valuation_remodel | mechanical_valuation | mechanical_valuation_remodel | plumbing_valuation | plumbing_valuation_remodel | medgas_valuation | medgas_valuation_remodel | original_address1   | original_city | original_state | original_zip | council_district | jurisdiction        | link                                                                                                 | project_id | masterpermitnum | latitude    | longitude    | contractor_trade      | contractor_company_name        | contractor_full_name | contractor_phone   | contractor_address1                | contractor_address2       | contractor_city  | contractor_zip | applicant_full_name | applicant_org                  | applicant_phone    | applicant_address1                 | applicant_address2   | applicant_city | applicantzip | 
| ========== | ==================== | ============== | =================== | ===================================== | ========== | =========== | =================== | =================================================================== | ========== | ================================================================= | =================== | =================== | ========== | ==================== | ================== | ====================== | ============= | ============== | =================== | =================== | =================== | ======================== | =================== | ================== | ======================= | =================== | ================ | ============= | ================== | ========================== | ==================== | ============================ | ==================== | ============================ | ================== | ========================== | ================ | ======================== | =================== | ============= | ============== | ============ | ================ | =================== | ==================================================================================================== | ========== | =============== | =========== | ============ | ===================== | ============================== | ==================== | ================== | ================================== | ========================= | ================ | ============== | =================== | ============================== | ================== | ================================== | ==================== | ============== | ============ | 
| BP         | Building Permit      | 2007-115377 BP | Residential         | R- 101 Single Family Houses           | New        | No          | 11436 FLUSHWING DR  | new 1 strory sf res w att garage and cov patio                      | 0247301018 | LOT 23 BLK Z PIONEER CROSSING WEST SEC 7                          | 2007-04-20T00:00:00 | 2007-04-20T00:00:00 | FRIDAY     | 2007                 | 2007               | No                     | Permit Center | Expired        | 2008-10-09T17:21:46 | 2008-03-24T00:00:00 |                     |                          |                     | 2347               |                         | 102795              | 1                | 1             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 11436 FLUSHWING DR  | AUSTIN        | TX             | 78754        | 1                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024951, null] | 10024951   | 10024949        | 30.37482544 | -97.64972534 | General Contractor    | Newmark Home Corporation, L.P. |                      | [5123455147, null] | 6500 RIVER PLACE BLVD BLDG 2, #300 | AUSTIN TX 78730-1124      | AUSTIN           | 78730-1124     |                     |                                | [null, null]       |                                    |                      |                |              | 
| DS         | Driveway / Sidewalks | 2007-115377 DS | Residential         | Res. Driveway & Sidewalk              | New        |             | 11436 FLUSHWING DR  | new 1 strory sf res w att garage and cov patio                      | 0247301018 | LOT 23 BLK Z PIONEER CROSSING WEST SEC 7                          | 2007-04-20T00:00:00 | 2007-05-02T00:00:00 | WEDNESDAY  | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:49 | 2007-09-26T00:00:00 | 2007-09-26T00:00:00 |                          |                     |                    |                         |                     |                  |               |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 11436 FLUSHWING DR  | AUSTIN        | TX             | 78754        | 1                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024952, null] | 10024952   | 10024951        | 30.37482544 | -97.64972534 |                       |                                |                      | [null, null]       |                                    |                           |                  |                |                     |                                | [null, null]       |                                    |                      |                |              | 
| EP         | Electrical Permit    | 2007-115377 EP | Residential         | R- 101 Single Family Houses           | New        | No          | 11436 FLUSHWING DR  | new 1 strory sf res w att garage and cov patio                      | 0247301018 | LOT 23 BLK Z PIONEER CROSSING WEST SEC 7                          | 2007-04-20T00:00:00 | 2007-06-01T00:00:00 | FRIDAY     | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-09-12T00:00:00 | 2007-09-12T00:00:00 |                          |                     | 2347               |                         |                     | 1                | 1             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 11436 FLUSHWING DR  | AUSTIN        | TX             | 78754        | 1                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024953, null] | 10024953   | 10024951        | 30.37482544 | -97.64972534 | Electrical Contractor | Elec Tech                      | Aaron Gifford        | [5126423589, null] | 432 BLACKMAN TRL                   | HUTTO TX 78634            | Hutto            | 78634          |                     |                                | [null, null]       |                                    |                      |                |              | 
| MP         | Mechanical Permit    | 2007-115377 MP | Residential         | R- 101 Single Family Houses           | New        | No          | 11436 FLUSHWING DR  | new 1 strory sf res w att garage and cov patio                      | 0247301018 | LOT 23 BLK Z PIONEER CROSSING WEST SEC 7                          | 2007-04-20T00:00:00 | 2007-07-17T00:00:00 | TUESDAY    | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-09-26T00:00:00 | 2007-09-26T00:00:00 |                          |                     | 2347               |                         |                     | 1                | 1             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 11436 FLUSHWING DR  | AUSTIN        | TX             | 78754        | 1                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024954, null] | 10024954   | 10024951        | 30.37482544 | -97.64972534 | Mechanical Contractor | Big Tex Air Conditioning, Inc. | Roquey Schofield     | [5129303000, null] | P.O. BOX 5010                      | GEORGETOWN TX 78626       | Georgetown       | 78626          |                     |                                | [null, null]       |                                    |                      |                |              | 
| PP         | Plumbing Permit      | 2007-115377 PP | Residential         | R- 101 Single Family Houses           | New        | No          | 11436 FLUSHWING DR  | new 1 strory sf res w att garage and cov patio                      | 0247301018 | LOT 23 BLK Z PIONEER CROSSING WEST SEC 7                          | 2007-04-20T00:00:00 | 2007-05-29T00:00:00 | TUESDAY    | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-09-24T00:00:00 | 2007-09-24T00:00:00 |                          |                     | 2347               |                         |                     | 1                | 1             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 11436 FLUSHWING DR  | AUSTIN        | TX             | 78754        | 1                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024955, null] | 10024955   | 10024951        | 30.37482544 | -97.64972534 | Plumbing Contractor   |                                | Robert Christianson  | [5122465200, null] | 1950 LOUIS HENNA BLVD.             | ROUND ROCK TX 78664       | Round Rock       | 78664          |                     |                                | [null, null]       |                                    |                      |                |              | 
| EP         | Electrical Permit    | 2007-115381 EP | Residential         | Residential                           | Remodel    | No          | 6913 PANDA ROYLE DR | Temp Power Loop HBL For permit 20 07 105519                         | 0334361103 | LOT 3 BLK H STONEY RIDGE SUBD PHS B SEC 1                         | 2007-04-20T00:00:00 | 2007-04-20T00:00:00 | FRIDAY     | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-04-25T00:00:00 | 2007-04-25T00:00:00 |                          |                     |                    |                         |                     | 1                | 1             |                    |                            |                      | 500                          |                      |                              |                    |                            |                  |                          | 6913 PANDA ROYLE DR | AUSTIN        | TX             | 78617        | 2                | AUSTIN LTD          | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024959, null] | 10024959   |                 | 30.1596521  | -97.63927975 | Electrical Contractor | IES Residential, Inc.          | William B. Crist Jr. | [2814982212, null] | P.O BOX 947                        | STAFFORD TX 77497-0947    | Stafford         | 77497-0947     |                     |                                | [null, null]       |                                    |                      |                |              | 
| EP         | Electrical Permit    | 2007-115383 EP | Residential         | Residential                           | Remodel    | No          | 6909 PANDA ROYLE DR | Temp TPole HBL for permit 20 07 105529                              | 0334361104 | LOT 4 BLK H STONEY RIDGE SUBD PHS B SEC 1                         | 2007-04-20T00:00:00 | 2007-04-20T00:00:00 | FRIDAY     | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-04-23T00:00:00 | 2007-04-23T00:00:00 |                          |                     |                    |                         |                     | 1                | 1             |                    |                            |                      | 500                          |                      |                              |                    |                            |                  |                          | 6909 PANDA ROYLE DR | AUSTIN        | TX             | 78617        | 2                | AUSTIN LTD          | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024961, null] | 10024961   |                 | 30.15977821 | -97.63926041 | Electrical Contractor | IES Residential, Inc.          | William B. Crist Jr. | [2814982212, null] | P.O BOX 947                        | STAFFORD TX 77497-0947    | Stafford         | 77497-0947     |                     |                                | [null, null]       |                                    |                      |                |              | 
| BP         | Building Permit      | 2007-115393 BP | Residential         | R- 101 Single Family Houses           | New        | No          | 7605 JABORANDI DR   | new 1 strory sf res w att garage wood deck and breezeway            | 0426530155 | LOT 31 BLK A MERIDIAN SEC A2 B2 AMENDED PLAT OF LTS 3137217 BLK A | 2007-04-20T00:00:00 | 2007-04-24T00:00:00 | TUESDAY    | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2007-10-26T00:00:00 | 2007-10-26T00:00:00 |                          |                     | 4153               |                         | 156750              | 2                | 1             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 7605 JABORANDI DR   | AUSTIN        | TX             | 78739        | 8                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024973, null] | 10024973   | 10024970        | 30.18512968 | -97.91698716 | General Contractor    | Newmark Home Corporation, L.P. |                      | [5123455147, null] | 6500 RIVER PLACE BLVD BLDG 2, #300 | AUSTIN TX 78730-1124      | AUSTIN           | 78730-1124     |                     | Newmark Home Corporation, L.P. | [5123455147, null] | 6500 RIVER PLACE BLVD BLDG 2, #300 | AUSTIN TX 78730-1124 | AUSTIN         | 78730-1124   | 
| EP         | Electrical Permit    | 2007-103834 EP | Residential         | R- 329 Res Structures Other Than Bldg | New        | No          | 1209 TAMRANAE CT    | New Inground Swimming Pool w Spa w Reqd enclosure device for SF Res | 0105130217 | LOT 47 BLK A TREEMONT PHS B SEC 5                                 | 2007-03-06T00:00:00 | 2007-03-23T00:00:00 | FRIDAY     | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:35 | 2008-01-27T00:00:00 | 2007-07-09T00:00:00 |                          |                     | 650                |                         |                     | 0                | 0             |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 1209 TAMRANAE CT    | AUSTIN        | TX             | 78746        | 8                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10010182, null] | 10010182   | 10010181        | 30.26693191 | -97.79657427 | General Contractor    | Elite Pools Of Austin, Ltd.    | RANDY HERZOG         | [5127840954, null] | 1018 PIER BRANCH RD                | DRIPPING SPRINGS TX 78620 | DRIPPING SPRINGS | 78620          |                     |                                | [null, null]       |                                    |                      |                |              | 
| DS         | Driveway / Sidewalks | 2007-115393 DS | Residential         | Res. Driveway & Sidewalk              | New        |             | 7605 JABORANDI DR   | new 1 strory sf res w att garage wood deck and breezeway            | 0426530155 | LOT 31 BLK A MERIDIAN SEC A2 B2 AMENDED PLAT OF LTS 3137217 BLK A | 2007-04-20T00:00:00 | 2007-05-15T00:00:00 | TUESDAY    | 2007                 | 2007               | No                     | Permit Center | Final          | 2008-10-09T17:21:46 | 2008-03-22T00:00:00 | 2007-10-04T00:00:00 |                          |                     |                    |                         |                     |                  |               |                    |                            |                      |                              |                      |                              |                    |                            |                  |                          | 7605 JABORANDI DR   | AUSTIN        | TX             | 78739        | 8                | AUSTIN FULL PURPOSE | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=10024974, null] | 10024974   | 10024973        | 30.18512968 | -97.91698716 |                       |                                |                      | [null, null]       |                                    |                           |                  |                |                     |                                | [null, null]       |                                    |                      |                |              | 
```