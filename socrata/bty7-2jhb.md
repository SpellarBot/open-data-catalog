# Historical DOB Permit Issuance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-dob-permit-issuance-acc92) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bty7-2jhb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bty7-2jhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bty7-2jhb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bty7-2jhb |
| Name | Historical DOB Permit Issuance |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | permits, dob, buildings |
| Created | 2016-09-27T19:05:32Z |
| Publication Date | 2016-10-04T21:58:19Z |

## Description

A list of permits issued for a particular day and associated data. A list of permits issued between May 11 1989 through April 24, 2013.

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                             | Data Type     | Render Type   |
| ======== | =========== | ============================== | ================================ | ============= | ============= |
| Yes      | series tag  | borough                        | BOROUGH                          | text          | text          |
| Yes      | series tag  | bin                            | Bin #                            | text          | text          |
| Yes      | series tag  | house                          | House #                          | text          | text          |
| Yes      | series tag  | street_name                    | Street Name                      | text          | text          |
| Yes      | series tag  | job                            | Job #                            | text          | text          |
| Yes      | series tag  | job_doc                        | Job doc. #                       | text          | text          |
| Yes      | series tag  | job_type                       | Job Type                         | text          | text          |
| Yes      | series tag  | self_cert                      | Self_Cert                        | text          | text          |
| Yes      | series tag  | block                          | Block                            | text          | text          |
| Yes      | series tag  | lot                            | Lot                              | text          | text          |
| Yes      | series tag  | community_board                | Community Board                  | text          | text          |
| Yes      | series tag  | zip_code                       | Zip Code                         | text          | text          |
| Yes      | series tag  | bldg_type                      | Bldg Type                        | text          | text          |
| Yes      | series tag  | residential                    | Residential                      | text          | text          |
| Yes      | series tag  | special_district_1             | Special District 1               | text          | text          |
| Yes      | series tag  | special_district_2             | Special District 2               | text          | text          |
| Yes      | series tag  | work_type                      | Work Type                        | text          | text          |
| Yes      | series tag  | permit_status                  | Permit Status                    | text          | text          |
| Yes      | series tag  | filing_status                  | Filing Status                    | text          | text          |
| Yes      | series tag  | permit_type                    | Permit Type                      | text          | text          |
| Yes      | series tag  | permit_sequence                | Permit Sequence #                | text          | text          |
| Yes      | series tag  | permit_subtype                 | Permit Subtype                   | text          | text          |
| Yes      | series tag  | oil_gas                        | Oil Gas                          | text          | text          |
| Yes      | series tag  | site_fill                      | Site Fill                        | text          | text          |
| No       |             | filing_date                    | Filing Date                      | text          | text          |
| No       |             | issuance_date                  | Issuance Date                    | text          | text          |
| No       |             | expiration_date                | Expiration Date                  | text          | text          |
| No       |             | job_start_date                 | Job Start Date                   | text          | text          |
| Yes      | series tag  | permittee_s_first_name         | Permittee's First Name           | text          | text          |
| Yes      | series tag  | permittee_s_last_name          | Permittee's Last Name            | text          | text          |
| Yes      | series tag  | permittee_s_business_name      | Permittee's Business Name        | text          | text          |
| Yes      | series tag  | permittee_s_phone              | Permittee's Phone #              | text          | text          |
| Yes      | series tag  | permittee_s_license_type       | Permittee's License Type         | text          | text          |
| Yes      | series tag  | permittee_s_license            | Permittee's License #            | text          | text          |
| Yes      | series tag  | act_as_superintendent          | Act as Superintendent            | text          | text          |
| Yes      | series tag  | permittee_s_other_title        | Permittee's Other Title          | text          | text          |
| Yes      | series tag  | hic_license                    | HIC License                      | text          | text          |
| Yes      | series tag  | site_safety_mgr_s_first_name   | Site Safety Mgr's First Name     | text          | text          |
| Yes      | series tag  | site_safety_mgr_s_last_name    | Site Safety Mgr's Last Name      | text          | text          |
| Yes      | series tag  | site_safety_mgr_business_name  | Site Safety Mgr Business Name    | text          | text          |
| Yes      | series tag  | superintendent_first_last_name | Superintendent First & Last Name | text          | text          |
| Yes      | series tag  | superintendent_business_name   | Superintendent Business Name     | text          | text          |
| Yes      | series tag  | owner_s_business_type          | Owner's Business Type            | text          | text          |
| Yes      | series tag  | non_profit                     | Non-Profit                       | text          | text          |
| Yes      | series tag  | owner_s_business_name          | Owner's Business Name            | text          | text          |
| Yes      | series tag  | owner_s_first_name             | Owner's First Name               | text          | text          |
| Yes      | series tag  | owner_s_last_name              | Owner's Last Name                | text          | text          |
| Yes      | series tag  | owner_s_house                  | Owner's House #                  | text          | text          |
| Yes      | series tag  | owner_s_house_street_name      | Owner's House Street Name        | text          | text          |
| Yes      | series tag  | owner_s_house_city             | Owner?s House City               | text          | text          |
| Yes      | series tag  | owner_s_house_state            | Owner?s House State              | text          | text          |
| Yes      | series tag  | owner_s_house_zip_code         | Owner?s House Zip Code           | text          | text          |
| Yes      | series tag  | owner_s_phone                  | Owner's Phone #                  | text          | text          |
| Yes      | time        | dobrundate                     | DOBRunDate                       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dobrundate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issuance_date,expiration_date,job_start_date,filing_date
```

## Data Commands

```ls
series e:bty7-2jhb d:2016-01-03T00:00:00.000Z t:zip_code=11237 t:site_fill=NONE t:street_name="SCHOLES STREET" t:block=02969 t:house=516 t:act_as_superintendent=Y t:superintendent_first_last_name="J.G.C. PLBG & HTG INC." t:bldg_type=2 t:permittee_s_license_type="MASTER PLUMBER" t:job_type=A1 t:filing_status=INITIAL t:owner_s_house_state=NY t:permittee_s_last_name=CAMPITIELLO t:owner_s_business_name="LAUREL COHN REALTY" t:community_board=301 t:owner_s_phone=7183575500 t:superintendent_business_name="J.G.C. PLBG & HTG INC." t:permit_sequence=01 t:permit_type=PL t:self_cert=Y t:owner_s_first_name=MAKR t:owner_s_last_name=COHN t:work_type=PL t:job=301394097 t:borough=BROOKLYN t:owner_s_house=59-25 t:permittee_s_first_name=GERARD t:permit_status=ISSUED t:owner_s_house_street_name="FRESH MEADOW LANE" t:owner_s_house_zip_code=11365 t:permittee_s_phone=7182784610 t:owner_s_house_city=FLUSHING t:lot=00030 t:permittee_s_business_name="J.G.C. PLBG & HTG INC." t:permittee_s_license=0001195 t:bin=3070562 t:job_doc=01 t:owner_s_business_type=PARTNERSHIP m:row_number.bty7-2jhb=1

series e:bty7-2jhb d:2016-01-03T00:00:00.000Z t:zip_code=10458 t:residential=YES t:site_fill=ON-SITE t:street_name="BAINBRIDGE AVENUE" t:block=03292 t:house=2986 t:bldg_type=1 t:permittee_s_license_type="GENERAL CONTRACTOR" t:job_type=NB t:filing_status=RENEWAL t:owner_s_house_state=NY t:permit_subtype=FN t:permittee_s_last_name=KIM t:community_board=207 t:owner_s_phone=9172701131 t:permit_sequence=05 t:permit_type=EQ t:self_cert=Y t:owner_s_first_name=HUGO t:owner_s_last_name=IM t:work_type=EQ t:job=201079821 t:borough=BRONX t:owner_s_house=2984 t:permittee_s_first_name="DOUNG OUK" t:permit_status=ISSUED t:owner_s_house_street_name="BAINBRIDGE AVE" t:owner_s_house_zip_code=10458 t:permittee_s_phone=7184612227 t:owner_s_house_city=BRONX t:lot=00089 t:permittee_s_business_name="GWANGGAETOU DEVELOPMENT C" t:permittee_s_license=0023609 t:bin=2119236 t:job_doc=01 t:owner_s_business_type=INDIVIDUAL m:row_number.bty7-2jhb=2

series e:bty7-2jhb d:2016-01-03T00:00:00.000Z t:zip_code=11419 t:site_fill=ON-SITE t:street_name="124 STREET" t:block=09491 t:house=101-33 t:act_as_superintendent=Y t:superintendent_first_last_name="RUTTURA AND SONS CONSTRUCTION CO" t:job_type=DM t:permittee_s_license_type="GENERAL CONTRACTOR" t:filing_status=INITIAL t:owner_s_house_state=NY t:permit_subtype=FN t:permittee_s_last_name=RUTTURA t:owner_s_business_name="NY SCHOOL CONSTRUCTION AUTHORITY" t:community_board=409 t:owner_s_phone=7184728072 t:superintendent_business_name="RUTTURA AND SONS CONSTRUCTION CO" t:permit_sequence=01 t:permit_type=EQ t:self_cert=Y t:owner_s_first_name=RICHARD t:owner_s_last_name=HURTUBISE t:work_type=EQ t:job=400825185 t:borough=QUEENS t:owner_s_house=30-30 t:non_profit=Y t:permittee_s_first_name="A THOMAS" t:permit_status=ISSUED t:owner_s_house_street_name="THOMSON AVENUE" t:owner_s_house_zip_code=11101 t:permittee_s_phone=5164540291 t:owner_s_house_city=LIC t:lot=00015 t:permittee_s_business_name="RUTTURA AND SONS CONSTRUCTION CO" t:permittee_s_license=0002593 t:bin=4200748 t:job_doc=01 t:owner_s_business_type=OTHER m:row_number.bty7-2jhb=3
```

## Meta Commands

```ls
metric m:row_number.bty7-2jhb p:long l:"Row Number"

entity e:bty7-2jhb l:"Historical DOB Permit Issuance" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/bty7-2jhb

property e:bty7-2jhb t:meta.view v:id=bty7-2jhb v:category="Housing & Development" v:averageRating=0 v:name="Historical DOB Permit Issuance" v:attribution="Department of Buildings (DOB)"

property e:bty7-2jhb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bty7-2jhb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough   | bin     | house  | street_name        | job       | job_doc | job_type | self_cert | block | lot   | community_board | zip_code | bldg_type | residential | special_district_1 | special_district_2 | work_type | permit_status | filing_status | permit_type | permit_sequence | permit_subtype | oil_gas | site_fill           | filing_date | issuance_date | expiration_date | job_start_date | permittee_s_first_name | permittee_s_last_name | permittee_s_business_name        | permittee_s_phone | permittee_s_license_type    | permittee_s_license | act_as_superintendent | permittee_s_other_title | hic_license | site_safety_mgr_s_first_name | site_safety_mgr_s_last_name | site_safety_mgr_business_name | superintendent_first_last_name   | superintendent_business_name     | owner_s_business_type | non_profit | owner_s_business_name            | owner_s_first_name | owner_s_last_name | owner_s_house | owner_s_house_street_name | owner_s_house_city | owner_s_house_state | owner_s_house_zip_code | owner_s_phone | dobrundate          | 
| ========= | ======= | ====== | ================== | ========= | ======= | ======== | ========= | ===== | ===== | =============== | ======== | ========= | =========== | ================== | ================== | ========= | ============= | ============= | =========== | =============== | ============== | ======= | =================== | =========== | ============= | =============== | ============== | ====================== | ===================== | ================================ | ================= | =========================== | =================== | ===================== | ======================= | =========== | ============================ | =========================== | ============================= | ================================ | ================================ | ===================== | ========== | ================================ | ================== | ================= | ============= | ========================= | ================== | =================== | ====================== | ============= | =================== | 
| BROOKLYN  | 3070562 | 516    | SCHOLES STREET     | 301394097 | 01      | A1       | Y         | 02969 | 00030 | 301             | 11237    | 2         |             |                    |                    | PL        | ISSUED        | INITIAL       | PL          | 01              |                |         | NONE                | 04/25/2003  | 04/25/2003    | 04/24/2004      | 04/25/2003     | GERARD                 | CAMPITIELLO           | J.G.C. PLBG & HTG INC.           | 7182784610        | MASTER PLUMBER              | 0001195             | Y                     |                         |             |                              |                             |                               | J.G.C. PLBG & HTG INC.           | J.G.C. PLBG & HTG INC.           | PARTNERSHIP           |            | LAUREL COHN REALTY               | MAKR               | COHN              | 59-25         | FRESH MEADOW LANE         | FLUSHING           | NY                  | 11365                  | 7183575500    | 2016-01-03T00:00:00 | 
| BRONX     | 2119236 | 2986   | BAINBRIDGE AVENUE  | 201079821 | 01      | NB       | Y         | 03292 | 00089 | 207             | 10458    | 1         | YES         |                    |                    | EQ        | ISSUED        | RENEWAL       | EQ          | 05              | FN             |         | ON-SITE             | 07/06/2009  | 07/06/2009    | 05/15/2010      | 12/06/2006     | DOUNG OUK              | KIM                   | GWANGGAETOU DEVELOPMENT C        | 7184612227        | GENERAL CONTRACTOR          | 0023609             |                       |                         |             |                              |                             |                               |                                  |                                  | INDIVIDUAL            |            |                                  | HUGO               | IM                | 2984          | BAINBRIDGE AVE            | BRONX              | NY                  | 10458                  | 9172701131    | 2016-01-03T00:00:00 | 
| QUEENS    | 4200748 | 101-33 | 124 STREET         | 400825185 | 01      | DM       | Y         | 09491 | 00015 | 409             | 11419    |           |             |                    |                    | EQ        | ISSUED        | INITIAL       | EQ          | 01              | FN             |         | ON-SITE             | 07/06/1998  | 07/06/1998    | 01/01/1999      | 07/06/1998     | A THOMAS               | RUTTURA               | RUTTURA AND SONS CONSTRUCTION CO | 5164540291        | GENERAL CONTRACTOR          | 0002593             | Y                     |                         |             |                              |                             |                               | RUTTURA AND SONS CONSTRUCTION CO | RUTTURA AND SONS CONSTRUCTION CO | OTHER                 | Y          | NY SCHOOL CONSTRUCTION AUTHORITY | RICHARD            | HURTUBISE         | 30-30         | THOMSON AVENUE            | LIC                | NY                  | 11101                  | 7184728072    | 2016-01-03T00:00:00 | 
| QUEENS    | 4043037 | 34-35  | 100 STREET         | 420014264 | 01      | A2       | Y         | 01734 | 00032 | 403             | 11368    | 2         | YES         |                    |                    | FB        | ISSUED        | INITIAL       | EW          | 01              | FB             | OIL     | NOT APPLICABLE      | 05/11/2009  | 05/11/2009    | 08/01/2009      | 05/11/2009     | WILLIAM                | PAUL                  | METRO FUEL OIL CORP.             | 7183831400        | OIL BURNER INSTALLER        | 0001283             |                       |                         |             |                              |                             |                               |                                  |                                  | CORPORATION           |            | 100 CB REALTY CORP               | BELLEFLEUR         | CARMELLE          | PO BOX        | 94                        | CARLE PLACE        | NY                  | 11514                  | 5169976111    | 2016-01-03T00:00:00 | 
| MANHATTAN | 1062427 | 706    | RIVERSIDE DRIVE    | 104362128 | 01      | A2       | Y         | 02094 | 00045 | 109             | 10031    | 2         |             |                    |                    | PL        | ISSUED        | INITIAL       | PL          | 01              |                |         | NONE                | 07/10/2007  | 07/10/2007    | 07/09/2008      | 07/10/2007     | HOWARD                 | TUNE                  | SEAVIEW PLUMBING INC             | 7182418259        | MASTER PLUMBER              | 0001035             |                       |                         |             |                              |                             |                               |                                  |                                  | CORPORATION           |            | Pinnacle Group                   | Meir               | Bouskila          | One           | Penn Plaza                | New York           | NY                  | 10119                  | 2126552111    | 2016-01-03T00:00:00 | 
| MANHATTAN | 1084181 | 159-20 | HARLEM RIVER DRIVE | 104068991 | 01      | A2       |           | 02106 | 00320 | 110             | 10039    | 2         |             |                    |                    | PL        | ISSUED        | INITIAL       | PL          | 01              |                |         | NONE                | 04/29/2005  | 04/29/2005    | 04/29/2006      | 04/29/2005     | NICK                   | KOULLIAS              | GKC INDUSTRIES                   | 7183578900        | MASTER PLUMBER              | 0001285             | Y                     |                         |             |                              |                             |                               | GKC INDUSTRIES                   | GKC INDUSTRIES                   | PARTNERSHIP           |            | NEW YORK CITY HOUSING AUTHORITY  | NICHOLAS           | MARANZANO         | 90            | CHURCH STREET, 10TH FLOOR | NEW YORK           | NY                  | 10011                  | 2123063000    | 2016-01-03T00:00:00 | 
| MANHATTAN | 1035732 | 390    | PARK AVENUE        | 120211252 | 01      | A2       | Y         | 01289 | 00036 | 105             | 10022    | 2         |             | MID                |                    | OT        | ISSUED        | INITIAL       | EW          | 01              | OT             |         | USE UNDER 300 CU.YD | 11/30/2009  | 11/30/2009    | 08/08/2010      | 11/30/2009     | MICHAEL                | MARRONE               | W5 GROUP LLC                     | 2015410030        | GENERAL CONTRACTOR          | 0035038             |                       |                         |             |                              |                             |                               |                                  |                                  | CORPORATION           |            | 345 PARK AVENUE SOUTH PARTNERS   | FRANK              | SPADAFORA         | C/O RFR       | REALTY 757 THIRD AVENUE   | NEW YORK           | NY                  | 10017                  | 2127526190    | 2016-01-03T00:00:00 | 
| QUEENS    | 4000470 | 11-14  | 46 AVENUE          | 420601110 | 01      | A2       | Y         | 00055 | 00029 | 402             | 11101    | 2         | YES         | LIC                |                    | PL        | ISSUED        | INITIAL       | PL          | 01              |                |         | NOT APPLICABLE      | 08/02/2012  | 08/02/2012    | 08/02/2013      | 08/02/2012     | MICHAEL                | MANISCOLCO            | APPROVED ENERGY LLC              | 7188918001        | MASTER PLUMBER              | 0001679             |                       |                         |             |                              |                             |                               |                                  |                                  | PARTNERSHIP           |            | DA11-14 LLC-C/O DAVID ASSOC      | DEBORAH            | FROMBERG          | 84-75         | MAIN STREET               | BRIARWOOD          | NY                  | 11435                  | 7182970888    | 2016-01-03T00:00:00 | 
| BROOKLYN  | 3152051 | 253    | 83 STREET          | 310092636 | 01      | A1       |           | 06006 | 00054 | 310             | 11209    | 1         | YES         |                    |                    | PL        | ISSUED        | INITIAL       | PL          | 01              |                |         | NOT APPLICABLE      | 06/20/2008  | 06/20/2008    | 06/20/2009      | 06/20/2008     | ZBIGNIEW               | WANIELISTA            | Z.W. PLUMBING & HEATING CORPORAT | 7184913023        | MASTER PLUMBER              | 0001418             |                       |                         |             |                              |                             |                               |                                  |                                  | INDIVIDUAL            |            | NA                               | DANIELLE           | BASSO             | 253           | 83RD STREET               | BROOKLYN           | NY                  | 11209                  | 7188339477    | 2016-01-03T00:00:00 | 
| MANHATTAN | 1080777 | 30     | EAST 30TH STREET   | 120399327 | 02      | A2       | Y         | 00859 | 00026 | 105             | 10016    | 2         |             |                    |                    | SP        | ISSUED        | INITIAL       | EW          | 01              | SP             |         |                     | 12/16/2010  | 12/17/2010    | 12/17/2011      | 12/17/2010     | EMANUEL                | TROISE                | DOMESTIC PLUMBING CORP           | 7188760004        | FIRE SUPPRESSION CONTRACTOR | 0000248             |                       |                         |             |                              |                             |                               |                                  |                                  | CORPORATION           |            | THIRTY EAST 30TH STREET OWNERS   | ZIEL               | FELDMAN           | 30            | EAST 30TH STREET          | NEW YORK           | NY                  | 10016                  | 2126102800    | 2016-01-03T00:00:00 | 
```