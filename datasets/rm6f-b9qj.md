# Nursing Facility Registry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nursing-facility-registry) |
| Metadata | [Link](https://data.ct.gov/api/views/rm6f-b9qj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rm6f-b9qj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rm6f-b9qj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rm6f-b9qj |
| Name | Nursing Facility Registry |
| Category | Health and Human Services |
| Tags | opm, ltc, nursing facilities, long term care, pdpd |
| Created | 2016-06-20T17:22:26Z |
| Publication Date | 2016-06-23T14:37:49Z |

## Description

This registry provides a list of licensed nursing facilities in Connecticut as of September 30 each year, beginning with data from 2013 including demographic, rate information, and occupancy levels.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                          | Data Type | Render Type |
| ======== | ============== | ========================================================== | ============================================================= | ========= | =========== |
| Yes      | series tag     | level_of_care                                              | Level of Care                                                 | text      | text        |
| Yes      | series tag     | facility_name                                              | FACILITY NAME                                                 | text      | text        |
| Yes      | series tag     | facility_telephone                                         | FACILITY TELEPHONE                                            | text      | text        |
| Yes      | series tag     | town                                                       | TOWN                                                          | text      | text        |
| Yes      | series tag     | county                                                     | COUNTY                                                        | text      | text        |
| Yes      | series tag     | ownership_type                                             | OWNERSHIP TYPE                                                | text      | text        |
| Yes      | numeric metric | medicare_certified                                         | MEDICARE CERTIFIED                                            | number    | number      |
| Yes      | numeric metric | medicaid_certified                                         | MEDICAID CERTIFIED                                            | number    | number      |
| Yes      | numeric metric | total_licensed_beds                                        | Total Licensed Beds                                           | number    | number      |
| Yes      | numeric metric | licensed_ccnh_beds                                         | Licensed CCNH Beds                                            | number    | number      |
| Yes      | numeric metric | licensed_ccnh_beds_occupied                                | Licensed CCNH Beds Occupied                                   | number    | number      |
| Yes      | numeric metric | licensed_rhns_beds                                         | Licensed RHNS Beds                                            | number    | number      |
| Yes      | numeric metric | licensed_rhns_beds_occupied                                | Licensed RHNS Beds Occupied                                   | number    | number      |
| Yes      | numeric metric | ccnh_room_rate_private_1_bed                               | CCNH Room Rate: PRIVATE (1 BED)                               | number    | number      |
| Yes      | numeric metric | ccnh_room_rate_semi_private_2_beds                         | CCNH Room Rate: SEMI-PRIVATE (2 BEDS)                         | number    | number      |
| Yes      | numeric metric | ccnh_room_rate_3_4_beds                                    | CCNH Room Rate: 3 - 4 BEDS                                    | number    | number      |
| Yes      | numeric metric | rhns_room_rate_private_1_bed                               | RHNS Room Rate: PRIVATE (1 BED)                               | number    | number      |
| Yes      | numeric metric | rhns_room_rate_semi_private_2_beds                         | RHNS Room Rate: SEMI-PRIVATE (2 BEDS)                         | number    | number      |
| Yes      | numeric metric | rhns_room_rate_3_4_beds                                    | RHNS Room Rate: 3 - 4 BEDS                                    | number    | number      |
| Yes      | numeric metric | total_number_of_patients                                   | Total number of patients                                      | number    | number      |
| Yes      | numeric metric | _18                                                        | <18                                                           | number    | number      |
| Yes      | numeric metric | 18_24                                                      | 18 - 24                                                       | number    | number      |
| Yes      | numeric metric | 25_34                                                      | 25 - 34                                                       | number    | number      |
| Yes      | numeric metric | 35_44                                                      | 35 - 44                                                       | number    | number      |
| Yes      | numeric metric | 45_54                                                      | 45 - 54                                                       | number    | number      |
| Yes      | numeric metric | 55_64                                                      | 55 - 64                                                       | number    | number      |
| Yes      | numeric metric | 65_74                                                      | 65 - 74                                                       | number    | number      |
| Yes      | numeric metric | 75_84                                                      | 75 - 84                                                       | number    | number      |
| Yes      | numeric metric | 85_94                                                      | 85 - 94                                                       | number    | number      |
| Yes      | numeric metric | 95_and_older                                               | 95 and older                                                  | number    | number      |
| Yes      | numeric metric | unknown_age                                                | Unknown age                                                   | number    | number      |
| Yes      | numeric metric | male                                                       | Male                                                          | number    | number      |
| Yes      | numeric metric | female                                                     | Female                                                        | number    | number      |
| Yes      | numeric metric | unknown_gender                                             | Unknown gender                                                | number    | number      |
| Yes      | numeric metric | married                                                    | Married                                                       | number    | number      |
| Yes      | numeric metric | never_married                                              | Never married                                                 | number    | number      |
| Yes      | numeric metric | widowed                                                    | Widowed                                                       | number    | number      |
| Yes      | numeric metric | separated                                                  | Separated                                                     | number    | number      |
| Yes      | numeric metric | divorced                                                   | Divorced                                                      | number    | number      |
| Yes      | series tag     | unknown_marital_status                                     | Unknown marital status                                        | text      | number      |
| Yes      | numeric metric | white                                                      | White                                                         | number    | number      |
| Yes      | numeric metric | african_american                                           | African American                                              | number    | number      |
| Yes      | numeric metric | hispanic_or_latino_origin                                  | Hispanic or Latino Origin                                     | number    | number      |
| Yes      | numeric metric | american_indian_or_alaskan_native                          | American Indian or Alaskan Native                             | number    | number      |
| Yes      | numeric metric | asian_or_pacific_islander                                  | Asian or Pacific Islander                                     | number    | number      |
| Yes      | numeric metric | other_or_unknown                                           | Other or Unknown                                              | number    | number      |
| Yes      | numeric metric | medicaid_fee_for_service_ct                                | Medicaid fee-for-service -- CT                                | number    | number      |
| Yes      | numeric metric | medicaid_fee_for_service_out_of_state                      | Medicaid fee-for-service -- Out of state                      | number    | number      |
| Yes      | numeric metric | medicaid_managed_care_out_of_state                         | Medicaid managed care -- Out of state                         | number    | number      |
| Yes      | numeric metric | medicaid_pending_ct                                        | Medicaid pending -- CT                                        | number    | number      |
| Yes      | numeric metric | medicaid_pending_out_of_state                              | Medicaid pending -- Out of state                              | number    | number      |
| Yes      | numeric metric | medicare_fee_for_service_traditional                       | Medicare fee-for-service (traditional)                        | number    | number      |
| Yes      | numeric metric | medicare_managed_care                                      | Medicare managed care                                         | number    | number      |
| Yes      | numeric metric | veterans_administration                                    | Veterans administration                                       | number    | number      |
| Yes      | numeric metric | ccrc_life_care                                             | CCRC -- Life Care                                             | number    | number      |
| No       |                | long_term_care_insurance_ct_partnership_for_long_term_care | Long-term care insurance -- CT Partnership for Long-Term Care | number    | number      |
| No       |                | long_term_care_insurance_not_ct_partnership                | Long-Term care insurance -- Not CT Partnership                | number    | number      |
| Yes      | series tag     | private_insurance_not_long_term_care                       | Private insurance (not long-term care)                        | text      | text        |
| Yes      | numeric metric | private_pay_no_insurance                                   | Private pay (no insurance)                                    | number    | number      |
| Yes      | numeric metric | unknown_payment_source                                     | Unknown Payment Source                                        | number    | number      |
| Yes      | time           | reporting_year                                             | Reporting Year                                                | number    | number      |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = long_term_care_insurance_ct_partnership_for_long_term_care,long_term_care_insurance_not_ct_partnership
```

## Data Commands

```ls
series e:rm6f-b9qj d:2013-01-01T00:00:00.000Z t:level_of_care=CCNH/RHNS t:ownership_type="For Profit" t:facility_name="Harbor View Manor" t:facility_telephone="(203) 932-6411" t:county=NEW_HAVEN t:unknown_marital_status=0 t:town="West Haven" t:private_insurance_not_long_term_care=0 m:divorced=4 m:medicaid_managed_care_out_of_state=0 m:private_pay_no_insurance=6 m:unknown_payment_source=2 m:unknown_age=0 m:separated=0 m:medicaid_certified=1 m:other_or_unknown=0 m:65_74=6 m:ccnh_room_rate_private_1_bed=430 m:medicare_managed_care=4 m:35_44=1 m:medicaid_pending_out_of_state=0 m:married=12 m:widowed=51 m:licensed_ccnh_beds_occupied=81 m:veterans_administration=0 m:medicare_certified=1 m:medicaid_fee_for_service_out_of_state=0 m:75_84=22 m:total_licensed_beds=90 m:55_64=6 m:medicare_fee_for_service_traditional=13 m:male=17 m:white=74 m:_18=0 m:rhns_room_rate_private_1_bed=430 m:licensed_rhns_beds_occupied=1 m:ccrc_life_care=0 m:total_number_of_patients=82 m:african_american=5 m:hispanic_or_latino_origin=3 m:asian_or_pacific_islander=0 m:rhns_room_rate_semi_private_2_beds=399 m:medicaid_fee_for_service_ct=55 m:licensed_ccnh_beds=89 m:female=65 m:95_and_older=11 m:medicaid_pending_ct=2 m:ccnh_room_rate_semi_private_2_beds=399 m:american_indian_or_alaskan_native=0 m:unknown_gender=0 m:85_94=35 m:never_married=15 m:25_34=1 m:18_24=0 m:licensed_rhns_beds=1 m:45_54=0

series e:rm6f-b9qj d:2013-01-01T00:00:00.000Z t:level_of_care=CCNH t:ownership_type=Non-profit t:facility_name="Mary Wade Home, Inc." t:facility_telephone="(203) 562-7222" t:county=NEW_HAVEN t:unknown_marital_status=0 t:town="New Haven" t:private_insurance_not_long_term_care=0 m:divorced=7 m:medicaid_managed_care_out_of_state=0 m:private_pay_no_insurance=21 m:unknown_payment_source=0 m:unknown_age=0 m:separated=0 m:medicaid_certified=1 m:other_or_unknown=0 m:65_74=5 m:ccnh_room_rate_private_1_bed=440 m:medicare_managed_care=2 m:35_44=0 m:medicaid_pending_out_of_state=0 m:married=12 m:widowed=59 m:licensed_ccnh_beds_occupied=93 m:veterans_administration=0 m:medicare_certified=1 m:medicaid_fee_for_service_out_of_state=0 m:75_84=22 m:total_licensed_beds=94 m:55_64=1 m:medicare_fee_for_service_traditional=7 m:male=14 m:white=80 m:_18=0 m:licensed_rhns_beds_occupied=0 m:ccrc_life_care=0 m:total_number_of_patients=93 m:african_american=10 m:hispanic_or_latino_origin=2 m:asian_or_pacific_islander=0 m:medicaid_fee_for_service_ct=59 m:licensed_ccnh_beds=94 m:female=79 m:95_and_older=9 m:medicaid_pending_ct=1 m:ccnh_room_rate_semi_private_2_beds=400 m:american_indian_or_alaskan_native=1 m:unknown_gender=0 m:85_94=56 m:never_married=15 m:25_34=0 m:18_24=0 m:licensed_rhns_beds=0 m:45_54=0

series e:rm6f-b9qj d:2013-01-01T00:00:00.000Z t:level_of_care=CCNH t:ownership_type="For Profit" t:facility_name="Kindred Nursing and Rehabilitation - Crossings East" t:facility_telephone="(860) 447-1416" t:county=NEW_LONDON t:unknown_marital_status=0 t:town="New London" t:private_insurance_not_long_term_care=0 m:divorced=15 m:medicaid_managed_care_out_of_state=0 m:private_pay_no_insurance=4 m:unknown_payment_source=4 m:unknown_age=0 m:ccnh_room_rate_3_4_beds=345 m:separated=1 m:medicaid_certified=1 m:other_or_unknown=0 m:65_74=32 m:ccnh_room_rate_private_1_bed=415 m:medicare_managed_care=0 m:35_44=3 m:medicaid_pending_out_of_state=0 m:married=17 m:widowed=48 m:licensed_ccnh_beds_occupied=120 m:veterans_administration=0 m:medicare_certified=1 m:medicaid_fee_for_service_out_of_state=0 m:75_84=30 m:total_licensed_beds=128 m:55_64=19 m:male=49 m:medicare_fee_for_service_traditional=11 m:_18=0 m:white=104 m:licensed_rhns_beds_occupied=0 m:ccrc_life_care=0 m:total_number_of_patients=120 m:african_american=9 m:hispanic_or_latino_origin=7 m:asian_or_pacific_islander=0 m:medicaid_fee_for_service_ct=88 m:licensed_ccnh_beds=128 m:female=71 m:95_and_older=4 m:medicaid_pending_ct=13 m:ccnh_room_rate_semi_private_2_beds=395 m:american_indian_or_alaskan_native=0 m:unknown_gender=0 m:85_94=27 m:never_married=39 m:25_34=0 m:18_24=0 m:licensed_rhns_beds=0 m:45_54=5
```

## Meta Commands

```ls
metric m:medicare_certified p:integer l:"MEDICARE CERTIFIED" t:dataTypeName=number

metric m:medicaid_certified p:integer l:"MEDICAID CERTIFIED" t:dataTypeName=number

metric m:total_licensed_beds p:integer l:"Total Licensed Beds" t:dataTypeName=number

metric m:licensed_ccnh_beds p:integer l:"Licensed CCNH Beds" t:dataTypeName=number

metric m:licensed_ccnh_beds_occupied p:double l:"Licensed CCNH Beds Occupied" t:dataTypeName=number

metric m:licensed_rhns_beds p:float l:"Licensed RHNS Beds" t:dataTypeName=number

metric m:licensed_rhns_beds_occupied p:float l:"Licensed RHNS Beds Occupied" t:dataTypeName=number

metric m:ccnh_room_rate_private_1_bed p:float l:"CCNH Room Rate: PRIVATE (1 BED)" t:dataTypeName=number

metric m:ccnh_room_rate_semi_private_2_beds p:float l:"CCNH Room Rate: SEMI-PRIVATE (2 BEDS)" t:dataTypeName=number

metric m:ccnh_room_rate_3_4_beds p:float l:"CCNH Room Rate: 3 - 4 BEDS" t:dataTypeName=number

metric m:rhns_room_rate_private_1_bed p:float l:"RHNS Room Rate: PRIVATE (1 BED)" t:dataTypeName=number

metric m:rhns_room_rate_semi_private_2_beds p:float l:"RHNS Room Rate: SEMI-PRIVATE (2 BEDS)" t:dataTypeName=number

metric m:rhns_room_rate_3_4_beds p:float l:"RHNS Room Rate: 3 - 4 BEDS" t:dataTypeName=number

metric m:total_number_of_patients p:integer l:"Total number of patients" t:dataTypeName=number

metric m:_18 p:integer l:<18 t:dataTypeName=number

metric m:18_24 p:integer l:"18 - 24" t:dataTypeName=number

metric m:25_34 p:integer l:"25 - 34" t:dataTypeName=number

metric m:35_44 p:integer l:"35 - 44" t:dataTypeName=number

metric m:45_54 p:integer l:"45 - 54" t:dataTypeName=number

metric m:55_64 p:integer l:"55 - 64" t:dataTypeName=number

metric m:65_74 p:integer l:"65 - 74" t:dataTypeName=number

metric m:75_84 p:integer l:"75 - 84" t:dataTypeName=number

metric m:85_94 p:integer l:"85 - 94" t:dataTypeName=number

metric m:95_and_older p:integer l:"95 and older" t:dataTypeName=number

metric m:unknown_age p:integer l:"Unknown age" t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:unknown_gender p:integer l:"Unknown gender" t:dataTypeName=number

metric m:married p:integer l:Married t:dataTypeName=number

metric m:never_married p:integer l:"Never married" t:dataTypeName=number

metric m:widowed p:integer l:Widowed t:dataTypeName=number

metric m:separated p:integer l:Separated t:dataTypeName=number

metric m:divorced p:integer l:Divorced t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:african_american p:integer l:"African American" t:dataTypeName=number

metric m:hispanic_or_latino_origin p:integer l:"Hispanic or Latino Origin" t:dataTypeName=number

metric m:american_indian_or_alaskan_native p:integer l:"American Indian or Alaskan Native" t:dataTypeName=number

metric m:asian_or_pacific_islander p:integer l:"Asian or Pacific Islander" t:dataTypeName=number

metric m:other_or_unknown p:integer l:"Other or Unknown" t:dataTypeName=number

metric m:medicaid_fee_for_service_ct p:integer l:"Medicaid fee-for-service -- CT" t:dataTypeName=number

metric m:medicaid_fee_for_service_out_of_state p:integer l:"Medicaid fee-for-service -- Out of state" t:dataTypeName=number

metric m:medicaid_managed_care_out_of_state p:integer l:"Medicaid managed care -- Out of state" t:dataTypeName=number

metric m:medicaid_pending_ct p:integer l:"Medicaid pending -- CT" t:dataTypeName=number

metric m:medicaid_pending_out_of_state p:integer l:"Medicaid pending -- Out of state" t:dataTypeName=number

metric m:medicare_fee_for_service_traditional p:integer l:"Medicare fee-for-service (traditional)" t:dataTypeName=number

metric m:medicare_managed_care p:integer l:"Medicare managed care" t:dataTypeName=number

metric m:veterans_administration p:integer l:"Veterans administration" t:dataTypeName=number

metric m:ccrc_life_care p:integer l:"CCRC -- Life Care" t:dataTypeName=number

metric m:private_pay_no_insurance p:integer l:"Private pay (no insurance)" t:dataTypeName=number

metric m:unknown_payment_source p:integer l:"Unknown Payment Source" t:dataTypeName=number

entity e:rm6f-b9qj l:"Nursing Facility Registry" t:url=https://data.ct.gov/api/views/rm6f-b9qj

property e:rm6f-b9qj t:meta.view v:id=rm6f-b9qj v:category="Health and Human Services" v:averageRating=0 v:name="Nursing Facility Registry"

property e:rm6f-b9qj t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:rm6f-b9qj t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| level_of_care | facility_name                                             | facility_telephone | town        | county     | ownership_type | medicare_certified | medicaid_certified | total_licensed_beds | licensed_ccnh_beds | licensed_ccnh_beds_occupied | licensed_rhns_beds | licensed_rhns_beds_occupied | ccnh_room_rate_private_1_bed | ccnh_room_rate_semi_private_2_beds | ccnh_room_rate_3_4_beds | rhns_room_rate_private_1_bed | rhns_room_rate_semi_private_2_beds | rhns_room_rate_3_4_beds | total_number_of_patients | _18 | 18_24 | 25_34 | 35_44 | 45_54 | 55_64 | 65_74 | 75_84 | 85_94 | 95_and_older | unknown_age | male | female | unknown_gender | married | never_married | widowed | separated | divorced | unknown_marital_status | white | african_american | hispanic_or_latino_origin | american_indian_or_alaskan_native | asian_or_pacific_islander | other_or_unknown | medicaid_fee_for_service_ct | medicaid_fee_for_service_out_of_state | medicaid_managed_care_out_of_state | medicaid_pending_ct | medicaid_pending_out_of_state | medicare_fee_for_service_traditional | medicare_managed_care | veterans_administration | ccrc_life_care | long_term_care_insurance_ct_partnership_for_long_term_care | long_term_care_insurance_not_ct_partnership | private_insurance_not_long_term_care | private_pay_no_insurance | unknown_payment_source | reporting_year | 
| ============= | ========================================================= | ================== | =========== | ========== | ============== | ================== | ================== | =================== | ================== | =========================== | ================== | =========================== | ============================ | ================================== | ======================= | ============================ | ================================== | ======================= | ======================== | === | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ============ | =========== | ==== | ====== | ============== | ======= | ============= | ======= | ========= | ======== | ====================== | ===== | ================ | ========================= | ================================= | ========================= | ================ | =========================== | ===================================== | ================================== | =================== | ============================= | ==================================== | ===================== | ======================= | ============== | ========================================================== | =========================================== | ==================================== | ======================== | ====================== | ============== | 
| CCNH/RHNS     | Harbor View Manor                                         | (203) 932-6411     | West Haven  | NEW_HAVEN  | For Profit     | 1                  | 1                  | 90                  | 89                 | 81                          | 1                  | 1                           | 430.00                       | 399.00                             |                         | 430.00                       | 399.00                             |                         | 82                       | 0   | 0     | 1     | 1     | 0     | 6     | 6     | 22    | 35    | 11           | 0           | 17   | 65     | 0              | 12      | 15            | 51      | 0         | 4        | 0                      | 74    | 5                | 3                         | 0                                 | 0                         | 0                | 55                          | 0                                     | 0                                  | 2                   | 0                             | 13                                   | 4                     | 0                       | 0              | 0                                                          | 0                                           | 0                                    | 6                        | 2                      | 2013           | 
| CCNH          | Mary Wade Home, Inc.                                      | (203) 562-7222     | New Haven   | NEW_HAVEN  | Non-profit     | 1                  | 1                  | 94                  | 94                 | 93                          | 0                  | 0                           | 440.00                       | 400.00                             |                         |                              |                                    |                         | 93                       | 0   | 0     | 0     | 0     | 0     | 1     | 5     | 22    | 56    | 9            | 0           | 14   | 79     | 0              | 12      | 15            | 59      | 0         | 7        | 0                      | 80    | 10               | 2                         | 1                                 | 0                         | 0                | 59                          | 0                                     | 0                                  | 1                   | 0                             | 7                                    | 2                     | 0                       | 0              | 0                                                          | 3                                           | 0                                    | 21                       | 0                      | 2013           | 
| CCNH          | Kindred Nursing and Rehabilitation - Crossings East       | (860) 447-1416     | New London  | NEW_LONDON | For Profit     | 1                  | 1                  | 128                 | 128                | 120                         | 0                  | 0                           | 415.00                       | 395.00                             | 345.00                  |                              |                                    |                         | 120                      | 0   | 0     | 0     | 3     | 5     | 19    | 32    | 30    | 27    | 4            | 0           | 49   | 71     | 0              | 17      | 39            | 48      | 1         | 15       | 0                      | 104   | 9                | 7                         | 0                                 | 0                         | 0                | 88                          | 0                                     | 0                                  | 13                  | 0                             | 11                                   | 0                     | 0                       | 0              | 0                                                          | 0                                           | 0                                    | 4                        | 4                      | 2013           | 
| CCNH/RHNS     | Crestfield Rehabilitation Center and Fenwood Manor        | (860) 643-5151     | Manchester  | HARTFORD   | For Profit     | 1                  | 1                  | 155                 | 95                 | 90                          | 60                 | 26                          | 405.00                       | 350.00                             |                         | 370.00                       | 310.00                             |                         | 116                      | 0   | 0     | 0     | 2     | 0     | 6     | 14    | 37    | 45    | 12           | 0           | 32   | 84     | 0              | 24      | 15            | 67      | 0         | 10       | 0                      | 111   | 4                | 0                         | 0                                 | 1                         | 0                | 65                          | 0                                     | 0                                  | 8                   | 0                             | 22                                   | 1                     | 0                       | 0              | 0                                                          | 0                                           | 3                                    | 17                       | 0                      | 2013           | 
| CCNH          | Skyview Center                                            | (203) 265-0981     | Wallingford | NEW_HAVEN  | For Profit     | 1                  | 1                  | 97                  | 97                 | 86                          | 0                  | 0                           | 370.00                       | 355.00                             |                         |                              |                                    |                         | 86                       | 0   | 0     | 0     | 0     | 1     | 8     | 10    | 20    | 35    | 12           | 0           | 25   | 61     | 0              | 15      | 6             | 54      | 1         | 10       | 0                      | 80    | 2                | 4                         | 0                                 | 0                         | 0                | 60                          | 0                                     | 0                                  | 9                   | 0                             | 9                                    | 2                     | 0                       | 0              | 0                                                          | 1                                           | 0                                    | 4                        | 1                      | 2013           | 
| CCNH          | Westfield Care and Rehabilitation Center                  | (203) 238-1291     | Meriden     | NEW_HAVEN  | For Profit     | 1                  | 1                  | 100                 | 100                | 80                          | 0                  | 0                           | 434.00                       | 387.00                             | 365.00                  |                              |                                    |                         | 80                       | 0   | 0     | 0     | 0     | 2     | 8     | 9     | 45    | 12    | 4            | 0           | 28   | 52     | 0              | 6       | 13            | 59      | 0         | 2        | 0                      | 67    | 3                | 10                        | 0                                 | 0                         | 0                | 70                          | 0                                     | 0                                  | 2                   | 0                             | 1                                    | 4                     | 0                       | 0              | 0                                                          | 0                                           | 0                                    | 2                        | 1                      | 2013           | 
| CCNH          | Village Green of Bristol Rehabilitation and Health Center | (860) 589-2923     | Forestville | HARTFORD   | For Profit     | 1                  | 1                  | 120                 | 120                | 85                          | 0                  | 0                           | 375.00                       | 348.00                             | 321.00                  |                              |                                    |                         | 85                       | 0   | 0     | 1     | 5     | 6     | 17    | 13    | 24    | 18    | 1            | 0           | 40   | 45     | 0              | 16      | 25            | 29      | 3         | 12       | 0                      | 75    | 3                | 6                         | 0                                 | 1                         | 0                | 65                          | 0                                     | 0                                  | 6                   | 0                             | 5                                    | 0                     | 2                       | 0              | 0                                                          | 0                                           | 3                                    | 4                        | 0                      | 2013           | 
| CCNH          | Matulaitis Nursing Home, Inc.                             | (860) 928-7976     | Putnam      | WINDHAM    | Non-profit     | 1                  | 1                  | 119                 | 119                | 114                         | 0                  | 0                           | 367.00                       | 345.00                             |                         |                              |                                    |                         | 114                      | 0   | 0     | 0     | 0     | 1     | 2     | 3     | 26    | 63    | 19           | 0           | 25   | 89     | 0              | 23      | 18            | 71      | 0         | 2        | 0                      | 112   | 2                | 0                         | 0                                 | 0                         | 0                | 75                          | 0                                     | 0                                  | 7                   | 0                             | 15                                   | 3                     | 0                       | 0              | 0                                                          | 0                                           | 0                                    | 14                       | 0                      | 2013           | 
| CCNH          | Maple View Center for Health and Rehabilitation           | (860) 563-2861     | Rocky Hill  | HARTFORD   | For Profit     | 1                  | 1                  | 120                 | 120                | 120                         | 0                  | 0                           | 414.00                       | 374.00                             |                         |                              |                                    |                         | 120                      | 0   | 0     | 0     | 0     | 1     | 1     | 12    | 42    | 55    | 9            | 0           | 24   | 96     | 0              | 24      | 22            | 65      | 9         | 0        | 0                      | 106   | 8                | 5                         | 1                                 | 0                         | 0                | 81                          | 0                                     | 0                                  | 7                   | 0                             | 16                                   | 5                     | 0                       | 0              | 0                                                          | 0                                           | 1                                    | 8                        | 2                      | 2013           | 
| CCNH          | Middlebury Convalescent Home, Inc.                        | (203) 758-2471     | Middlebury  | NEW_HAVEN  | For Profit     | 1                  | 1                  | 58                  | 58                 | 54                          | 0                  | 0                           | 365.00                       | 340.00                             |                         |                              |                                    |                         | 54                       | 0   | 0     | 0     | 0     | 0     | 0     | 1     | 7     | 32    | 14           | 0           | 9    | 45     | 0              | 7       | 3             | 43      | 0         | 1        | 0                      | 54    | 0                | 0                         | 0                                 | 0                         | 0                | 31                          | 0                                     | 0                                  | 2                   | 0                             | 3                                    | 0                     | 0                       | 0              | 1                                                          | 3                                           | 0                                    | 13                       | 1                      | 2013           | 
```