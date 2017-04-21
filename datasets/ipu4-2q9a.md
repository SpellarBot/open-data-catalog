# DOB Permit Issuance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-permit-issuance-36530) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ipu4-2q9a) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ipu4-2q9a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ipu4-2q9a/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ipu4-2q9a |
| Name | DOB Permit Issuance |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | permit, dob, buildings |
| Created | 2013-04-18T15:18:56Z |
| Publication Date | 2017-04-20T20:16:09Z |

## Description

A list of permits issued for a particular day and associated data. Prior weekly and monthly reports are archived at DOB and are not available on NYC Open Data.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | =========== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag  | borough                          | BOROUGH                          | text          | text          |
| Yes      | series tag  | bin__                            | Bin #                            | text          | text          |
| Yes      | series tag  | house__                          | House #                          | text          | text          |
| Yes      | series tag  | street_name                      | Street Name                      | text          | text          |
| Yes      | series tag  | job__                            | Job #                            | text          | text          |
| Yes      | series tag  | job_doc___                       | Job doc. #                       | text          | text          |
| Yes      | series tag  | job_type                         | Job Type                         | text          | text          |
| Yes      | series tag  | self_cert                        | Self_Cert                        | text          | text          |
| Yes      | series tag  | block                            | Block                            | text          | text          |
| Yes      | series tag  | lot                              | Lot                              | text          | text          |
| Yes      | series tag  | community_board                  | Community Board                  | text          | text          |
| Yes      | series tag  | zip_code                         | Zip Code                         | text          | text          |
| Yes      | series tag  | bldg_type                        | Bldg Type                        | text          | text          |
| Yes      | series tag  | residential                      | Residential                      | text          | text          |
| Yes      | series tag  | special_district_1               | Special District 1               | text          | text          |
| Yes      | series tag  | special_district_2               | Special District 2               | text          | text          |
| Yes      | series tag  | work_type                        | Work Type                        | text          | text          |
| Yes      | series tag  | permit_status                    | Permit Status                    | text          | text          |
| Yes      | series tag  | filing_status                    | Filing Status                    | text          | text          |
| Yes      | series tag  | permit_type                      | Permit Type                      | text          | text          |
| Yes      | series tag  | permit_sequence__                | Permit Sequence #                | text          | text          |
| Yes      | series tag  | permit_subtype                   | Permit Subtype                   | text          | text          |
| Yes      | series tag  | oil_gas                          | Oil Gas                          | text          | text          |
| Yes      | series tag  | site_fill                        | Site Fill                        | text          | text          |
| No       |             | filing_date                      | Filing Date                      | text          | text          |
| Yes      | time        | issuance_date                    | Issuance Date                    | calendar_date | calendar_date |
| No       |             | expiration_date                  | Expiration Date                  | text          | text          |
| No       |             | job_start_date                   | Job Start Date                   | text          | text          |
| Yes      | series tag  | permittee_s_first_name           | Permittee's First Name           | text          | text          |
| Yes      | series tag  | permittee_s_last_name            | Permittee's Last Name            | text          | text          |
| Yes      | series tag  | permittee_s_business_name        | Permittee's Business Name        | text          | text          |
| Yes      | series tag  | permittee_s_phone__              | Permittee's Phone #              | text          | text          |
| Yes      | series tag  | permittee_s_license_type         | Permittee's License Type         | text          | text          |
| Yes      | series tag  | permittee_s_license__            | Permittee's License #            | text          | text          |
| Yes      | series tag  | act_as_superintendent            | Act as Superintendent            | text          | text          |
| Yes      | series tag  | permittee_s_other_title          | Permittee's Other Title          | text          | text          |
| Yes      | series tag  | hic_license                      | HIC License                      | text          | text          |
| Yes      | series tag  | site_safety_mgr_s_first_name     | Site Safety Mgr's First Name     | text          | text          |
| Yes      | series tag  | site_safety_mgr_s_last_name      | Site Safety Mgr's Last Name      | text          | text          |
| Yes      | series tag  | site_safety_mgr_business_name    | Site Safety Mgr Business Name    | text          | text          |
| Yes      | series tag  | superintendent_first___last_name | Superintendent First & Last Name | text          | text          |
| Yes      | series tag  | superintendent_business_name     | Superintendent Business Name     | text          | text          |
| Yes      | series tag  | owner_s_business_type            | Owner's Business Type            | text          | text          |
| Yes      | series tag  | non_profit                       | Non-Profit                       | text          | text          |
| Yes      | series tag  | owner_s_business_name            | Owner's Business Name            | text          | text          |
| Yes      | series tag  | owner_s_first_name               | Owner's First Name               | text          | text          |
| Yes      | series tag  | owner_s_last_name                | Owner's Last Name                | text          | text          |
| Yes      | series tag  | owner_s_house__                  | Owner's House #                  | text          | text          |
| Yes      | series tag  | owner_s_house_street_name        | Owner's House Street Name        | text          | text          |
| Yes      | series tag  | city                             | Owner?s House City               | text          | text          |
| Yes      | series tag  | state                            | Owner?s House State              | text          | text          |
| Yes      | series tag  | owner_s_zip_code                 | Owner?s House Zip Code           | text          | text          |
| Yes      | series tag  | owner_s_phone__                  | Owner's Phone #                  | text          | text          |
| No       |             | dobrundate                       | DOBRunDate                       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = issuance_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date,job_start_date,dobrundate,filing_date
```

## Data Commands

```ls
series e:ipu4-2q9a d:2016-03-29T12:00:00.000Z t:zip_code=11415 t:residential=YES t:permittee_s_phone_=9179169408 t:job_doc__=01 t:site_fill="NOT APPLICABLE" t:street_name="TALBOT STREET" t:permit_sequence_=02 t:state=NY t:block=03354 t:owner_s_phone_=5165685140 t:bin_=4080123 t:city="GREAT NECK" t:bldg_type=2 t:job_type=A2 t:permittee_s_license_type="GENERAL CONTRACTOR" t:house_=83-09 t:filing_status=RENEWAL t:permit_subtype=OT t:permittee_s_last_name=RAMIREZ t:owner_s_business_name="BENEDICT REALTY GROUP" t:community_board=409 t:owner_s_house_=150 t:permit_type=EW t:self_cert=Y t:owner_s_first_name=DANIEL t:owner_s_last_name=BENEDICT t:work_type=OT t:borough=QUEENS t:permittee_s_first_name=CARLOS t:permittee_s_license_=0613021 t:permit_status=ISSUED t:job_=421044435 t:owner_s_house_street_name="GREAT NECK ROAD" t:lot=07501 t:permittee_s_business_name="BRICK BY BRICK CONSTRUCTI" t:owner_s_zip_code=11021 t:owner_s_business_type=PARTNERSHIP m:row_number.ipu4-2q9a=1

series e:ipu4-2q9a d:2013-08-22T12:00:00.000Z t:zip_code=10019 t:permittee_s_phone_=7182947460 t:job_doc__=01 t:site_fill="NOT APPLICABLE" t:street_name="WEST 50TH STREET" t:permit_sequence_=01 t:state=NY t:block=01060 t:owner_s_phone_=2126102800 t:bin_=1026676 t:city="NEW YORK" t:bldg_type=2 t:permittee_s_license_type="OIL BURNER INSTALLER" t:job_type=A2 t:house_=435 t:filing_status=INITIAL t:permit_subtype=FS t:permittee_s_last_name="AGLIARDO JR" t:owner_s_business_name="435 WEST 50TH STREET LLC" t:community_board=104 t:owner_s_house_=5 t:permit_type=EW t:owner_s_first_name=MICHAEL t:owner_s_last_name=STERN t:work_type=FS t:borough=MANHATTAN t:permittee_s_first_name=PETER t:permittee_s_license_=0002626 t:permit_status=ISSUED t:job_=121330755 t:owner_s_house_street_name="EAST 17TH STREET" t:lot=00000 t:permittee_s_business_name="PETER AGLIARDO CONTRACTOR" t:owner_s_zip_code=10003 t:owner_s_business_type=PARTNERSHIP m:row_number.ipu4-2q9a=2

series e:ipu4-2q9a d:2014-04-02T12:00:00.000Z t:zip_code=10016 t:permittee_s_phone_=2123023000 t:job_doc__=01 t:site_fill="NOT APPLICABLE" t:street_name="MADISON AVENUE" t:permit_sequence_=02 t:state=NY t:block=00862 t:owner_s_phone_=2123023000 t:bin_=1080791 t:city=NY t:bldg_type=2 t:permittee_s_license_type="GENERAL CONTRACTOR" t:job_type=A2 t:house_=165 t:filing_status=RENEWAL t:permit_subtype=OT t:permittee_s_last_name=SILBERMAN t:owner_s_business_name="TAMAR  PROPERTIES N.V. INC." t:community_board=105 t:owner_s_house_=167 t:permit_type=EW t:owner_s_first_name=CARLOS t:owner_s_last_name=SILBERMAN t:work_type=OT t:borough=MANHATTAN t:permittee_s_first_name=CARLOS t:permittee_s_license_=0004218 t:permit_status=ISSUED t:job_=121781955 t:owner_s_house_street_name="MADISON AVENUE" t:lot=00051 t:permittee_s_business_name="FALCON PROPERTIES INC" t:owner_s_zip_code=10016 t:owner_s_business_type=CORPORATION m:row_number.ipu4-2q9a=3
```

## Meta Commands

```ls
metric m:row_number.ipu4-2q9a p:long l:"Row Number"

entity e:ipu4-2q9a l:"DOB Permit Issuance" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/ipu4-2q9a

property e:ipu4-2q9a t:meta.view v:id=ipu4-2q9a v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/foilmonthly.shtml#permit v:averageRating=0 v:name="DOB Permit Issuance" v:attribution="Department of Buildings (DOB)"

property e:ipu4-2q9a t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ipu4-2q9a t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough   | bin__   | house__ | street_name      | job__     | job_doc___ | job_type | self_cert | block | lot   | community_board | zip_code | bldg_type | residential | special_district_1 | special_district_2 | work_type | permit_status | filing_status | permit_type | permit_sequence__ | permit_subtype | oil_gas | site_fill      | filing_date | issuance_date       | expiration_date | job_start_date | permittee_s_first_name | permittee_s_last_name | permittee_s_business_name | permittee_s_phone__ | permittee_s_license_type | permittee_s_license__ | act_as_superintendent | permittee_s_other_title | hic_license | site_safety_mgr_s_first_name | site_safety_mgr_s_last_name | site_safety_mgr_business_name | superintendent_first___last_name | superintendent_business_name | owner_s_business_type | non_profit | owner_s_business_name          | owner_s_first_name | owner_s_last_name | owner_s_house__ | owner_s_house_street_name | city       | state | owner_s_zip_code | owner_s_phone__ | dobrundate          | 
| ========= | ======= | ======= | ================ | ========= | ========== | ======== | ========= | ===== | ===== | =============== | ======== | ========= | =========== | ================== | ================== | ========= | ============= | ============= | =========== | ================= | ============== | ======= | ============== | =========== | =================== | =============== | ============== | ====================== | ===================== | ========================= | =================== | ======================== | ===================== | ===================== | ======================= | =========== | ============================ | =========================== | ============================= | ================================ | ============================ | ===================== | ========== | ============================== | ================== | ================= | =============== | ========================= | ========== | ===== | ================ | =============== | =================== | 
| QUEENS    | 4080123 | 83-09   | TALBOT STREET    | 421044435 | 01         | A2       | Y         | 03354 | 07501 | 409             | 11415    | 2         | YES         |                    |                    | OT        | ISSUED        | RENEWAL       | EW          | 02                | OT             |         | NOT APPLICABLE | 03/29/2016  | 2016-03-29T12:00:00 | 07/01/2016      | 10/29/2014     | CARLOS                 | RAMIREZ               | BRICK BY BRICK CONSTRUCTI | 9179169408          | GENERAL CONTRACTOR       | 0613021               |                       |                         |             |                              |                             |                               |                                  |                              | PARTNERSHIP           |            | BENEDICT REALTY GROUP          | DANIEL             | BENEDICT          | 150             | GREAT NECK ROAD           | GREAT NECK | NY    | 11021            | 5165685140      | 2016-03-30T12:00:00 | 
| MANHATTAN | 1026676 | 435     | WEST 50TH STREET | 121330755 | 01         | A2       |           | 01060 | 00000 | 104             | 10019    | 2         |             |                    |                    | FS        | ISSUED        | INITIAL       | EW          | 01                | FS             |         | NOT APPLICABLE | 08/22/2013  | 2013-08-22T12:00:00 | 08/22/2014      | 08/22/2013     | PETER                  | AGLIARDO JR           | PETER AGLIARDO CONTRACTOR | 7182947460          | OIL BURNER INSTALLER     | 0002626               |                       |                         |             |                              |                             |                               |                                  |                              | PARTNERSHIP           |            | 435 WEST 50TH STREET LLC       | MICHAEL            | STERN             | 5               | EAST 17TH STREET          | NEW YORK   | NY    | 10003            | 2126102800      | 2013-08-23T12:00:00 | 
| MANHATTAN | 1080791 | 165     | MADISON AVENUE   | 121781955 | 01         | A2       |           | 00862 | 00051 | 105             | 10016    | 2         |             |                    |                    | OT        | ISSUED        | RENEWAL       | EW          | 02                | OT             |         | NOT APPLICABLE | 04/02/2014  | 2014-04-02T12:00:00 | 03/29/2015      | 11/18/2013     | CARLOS                 | SILBERMAN             | FALCON PROPERTIES INC     | 2123023000          | GENERAL CONTRACTOR       | 0004218               |                       |                         |             |                              |                             |                               |                                  |                              | CORPORATION           |            | TAMAR PROPERTIES N.V. INC.     | CARLOS             | SILBERMAN         | 167             | MADISON AVENUE            | NY         | NY    | 10016            | 2123023000      | 2014-04-03T12:00:00 | 
| MANHATTAN | 1055643 | 943     | COLUMBUS AVENUE  | 140355407 | 01         | A2       | Y         | 01842 | 00002 | 107             | 10025    | 2         | YES         |                    |                    | OT        | ISSUED        | INITIAL       | EW          | 01                | OT             |         | NOT APPLICABLE | 06/03/2015  | 2015-06-03T12:00:00 | 01/07/2016      | 06/03/2015     | ALLEN                  | YU                    | FUTUREISTIC DEVELOPMENT I | 9174358552          | GENERAL CONTRACTOR       | 0610441               |                       |                         |             |                              |                             |                               |                                  |                              | INDIVIDUAL            |            | N/A                            | ALLEN              | YU                | 943             | COLUMBUS AVENUE           | MANHATTAN  | NY    | 10025            | 9174358552      | 2015-06-04T12:00:00 | 
| MANHATTAN | 1041379 | 50      | EAST 72ND STREET | 121713618 | 01         | A2       |           | 01386 | 07501 | 108             | 10021    | 2         | YES         | PI                 |                    | OT        | ISSUED        | RENEWAL       | EW          | 02                | OT             |         | NOT APPLICABLE | 09/16/2014  | 2014-09-16T12:00:00 | 09/12/2015      | 04/23/2014     | ELLIOT                 | BERKOWITZ             | RIVERSIDE BUILDERS INC    | 2126143040          | GENERAL CONTRACTOR       | 0034596               |                       |                         |             |                              |                             |                               |                                  |                              | CONDO/CO-OP           |            | JR LIMITED PARTNERSHIP         | WILLIAM            | PAILEY, JR.       | 21451           | WEST OAK TRAIL            | KILDEER    | IL    | 60047            | 8474384191      | 2014-09-17T12:00:00 | 
| QUEENS    | 4019806 | 2217    | ASTORIA BLVD     | 421198171 | 01         | A2       | Y         | 00884 | 00001 | 401             | 11102    | 2         |             |                    |                    | OT        | ISSUED        | RENEWAL       | EW          | 02                | OT             |         | NOT APPLICABLE | 08/13/2015  | 2015-08-13T12:00:00 | 03/21/2016      | 08/13/2015     | ARIEL                  | ORIOL                 | NOBEL CONSTRUCTION CORP   | 7182661793          | GENERAL CONTRACTOR       | 0604076               |                       |                         |             |                              |                             |                               |                                  |                              | INDIVIDUAL            |            | N/A                            | GIULIO             | DIVIRGILIO        | 2217            | ASTORIA BLVD              | QUEENS     | NY    | 11102            | 9174186071      | 2015-08-14T12:00:00 | 
| MANHATTAN | 1028593 | 20      | WEST 71 STREET   | 140368064 | 01         | A3       | Y         | 01123 | 00143 | 107             | 10023    | 2         | YES         |                    |                    | EQ        | ISSUED        | INITIAL       | EQ          | 01                | SF             |         |                | 06/30/2015  | 2015-06-30T12:00:00 | 06/29/2016      | 06/30/2015     | CHRISTOPHER            | DOWNES                | EVEREST SCAFFOLDING INC   | 7183281004          | GENERAL CONTRACTOR       | 0032158               |                       |                         |             |                              |                             |                               |                                  |                              | CORPORATION           |            | TWENTY SEVENTY ONE REALTY CORP | KENNETH            | FOLLANSBEE        | 20              | WEST 71 STREET            | NEW YORK   | NY    | 10023            | 6173599159      | 2015-07-01T12:00:00 | 
| MANHATTAN | 1028636 | 15      | WEST 72ND STREET | 122144143 | 01         | A2       |           | 01125 | 00024 | 107             | 10023    | 2         | YES         |                    |                    | OT        | ISSUED        | INITIAL       | EW          | 01                | OT             |         | NOT APPLICABLE | 11/17/2014  | 2014-11-17T12:00:00 | 04/13/2015      | 11/17/2014     | PETER                  | KOMININOS             | MELVA CONSTRUCTION CORP   | 7184821932          | GENERAL CONTRACTOR       | 0009073               |                       |                         |             |                              |                             |                               |                                  |                              | CORPORATION           |            | 15 WEST 72ND ST OWNERS CORP    | ALBERT             | MAYAS             | 4               | PARK AVENUE               | NEW YORK   | NY    | 10016            | 2123409300      | 2014-11-18T12:00:00 | 
| BRONX     | 2042035 | 1656    | PARKER STREET    | 220287785 | 01         | A2       | Y         | 03991 | 00026 | 210             | 10462    | 2         | YES         |                    |                    | OT        | ISSUED        | INITIAL       | EW          | 01                | OT             |         | NOT APPLICABLE | 05/10/2013  | 2013-05-10T12:00:00 | 03/09/2014      | 05/10/2013     | LUIGE                  | TRINCHESE             | TRINCHESE CONSTRUCTION IN | 7186594800          | GENERAL CONTRACTOR       | 0038649               |                       |                         |             |                              |                             |                               |                                  |                              | INDIVIDUAL            |            | N/A                            | PETER              | AGLIARDO          | 1656            | PARKER STREET             | BRONX      | NY    | 10462            | 3477481394      | 2013-05-11T12:00:00 | 
| BROOKLYN  | 3094312 | 439     | CRESCENT STREET  | 340196781 | 01         | A2       | Y         | 04198 | 00007 | 305             | 11208    | 2         |             |                    |                    | PL        | ISSUED        | INITIAL       | PL          | 01                |                |         | NOT APPLICABLE | 10/20/2014  | 2014-10-30T12:00:00 | 10/30/2015      | 10/30/2014     | MORRIS                 | MILLER                | BARMOR REHAB INC          | 2125790859          | MASTER PLUMBER           | 0010535               |                       |                         |             |                              |                             |                               |                                  |                              | PARTNERSHIP           |            | FLORIN-JAKER LLC               | FRANK              | MOREA             | 439             | CRESCENT STREET           | BROOKLYN   | NY    | 11208            | 3472960114      | 2014-10-31T12:00:00 | 
```