# TLC Vehicle Insurance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-vehicle-insurance-ab711) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cw8b-zbc3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cw8b-zbc3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cw8b-zbc3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cw8b-zbc3 |
| Name | TLC Vehicle Insurance |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, insure, insurance, vehicle, car, automobile, truck, taxi, limousine |
| Created | 2011-08-26T20:09:47Z |
| Publication Date | 2011-08-26T20:09:47Z |

## Description

Spreadsheet of all TLC vehicle insurance

## Columns

```ls
| Included | Schema Type | Field Name                                            | Name                                                  | Data Type | Render Type |
| ======== | =========== | ===================================================== | ===================================================== | ========= | =========== |
| No       | time        | :updated_at                                           | updated_at                                            | meta_data | meta_data   |
| Yes      | series tag  | tlc_license_type                                      | TLC_License_Type                                      | text      | text        |
| Yes      | series tag  | tlc_license_number                                    | TLC_License_Number                                    | text      | text        |
| Yes      | series tag  | dmv_plate                                             | DMV_Plate                                             | text      | text        |
| Yes      | series tag  | vin                                                   | VIN                                                   | text      | text        |
| Yes      | series tag  | automobile_insurance_code                             | Automobile_Insurance_Code                             | text      | number      |
| Yes      | series tag  | automobile_insurance_policy_number                    | Automobile_Insurance_Policy_Number                    | text      | text        |
| Yes      | series tag  | vehicle_owner_name                                    | Vehicle_Owner_Name                                    | text      | text        |
| Yes      | series tag  | affiliated_base_or_taxi_agent_or_fleet_license_number | Affiliated_Base_or_Taxi_Agent_or_Fleet_License_Number | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cw8b-zbc3 d:2011-08-26T13:09:52.000Z t:tlc_license_type=TLC_License_Type t:tlc_license_number=TLC_License_Number t:vin=VIN t:automobile_insurance_policy_number=Automobile_Insurance_Policy_Number t:vehicle_owner_name=Vehicle_Owner_Name t:dmv_plate=DMV_Plate m:row_number.cw8b-zbc3=1

series e:cw8b-zbc3 d:2011-08-26T13:09:52.000Z t:automobile_insurance_code=135 t:tlc_license_type=TLCPAR t:tlc_license_number=5281857 t:vin=1GNDM19X35B110457 t:automobile_insurance_policy_number=NET-CL-0010008-0 t:vehicle_owner_name="UNIVERSAL CARRIER INC" t:dmv_plate=T505485 m:row_number.cw8b-zbc3=2

series e:cw8b-zbc3 d:2011-08-26T13:09:52.000Z t:affiliated_base_or_taxi_agent_or_fleet_license_number=0 t:automobile_insurance_code=303 t:tlc_license_type=TLCMED t:tlc_license_number=2W22 t:vin=2FAFP70V98X143347 t:automobile_insurance_policy_number=FICA-154721-08-02 t:vehicle_owner_name="TW CHAUDHRY, LLC" t:dmv_plate=_2W22-B m:row_number.cw8b-zbc3=3
```

## Meta Commands

```ls
metric m:row_number.cw8b-zbc3 p:long l:"Row Number"

entity e:cw8b-zbc3 l:"TLC Vehicle Insurance" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/cw8b-zbc3

property e:cw8b-zbc3 t:meta.view v:id=cw8b-zbc3 v:category=Transportation v:averageRating=100 v:name="TLC Vehicle Insurance" v:attribution="Taxi and Limousine Commission (TLC)"

property e:cw8b-zbc3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cw8b-zbc3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | tlc_license_type | tlc_license_number | dmv_plate | vin               | automobile_insurance_code | automobile_insurance_policy_number | vehicle_owner_name           | affiliated_base_or_taxi_agent_or_fleet_license_number | 
| =========== | ================ | ================== | ========= | ================= | ========================= | ================================== | ============================ | ===================================================== | 
| 1314364192  | TLC_License_Type | TLC_License_Number | DMV_Plate | VIN               |                           | Automobile_Insurance_Policy_Number | Vehicle_Owner_Name           |                                                       | 
| 1314364192  | TLCPAR           | 5281857            | T505485   | 1GNDM19X35B110457 | 135                       | NET-CL-0010008-0                   | UNIVERSAL CARRIER INC        |                                                       | 
| 1314364192  | TLCMED           | 2W22               | _2W22-B   | 2FAFP70V98X143347 | 303                       | FICA-154721-08-02                  | TW CHAUDHRY, LLC             | 0                                                     | 
| 1314364192  | TLCCAR           | 5243763            | 0284EAG   | JTHBN36F755001310 | 326                       | CA238524-0                         | AZAYEV EMIL                  |                                                       | 
| 1314364192  | TLCCAR           | 5279849            | 07ALLSTR  | 2LMDU88CX7BJ04071 | 347                       | 10UENQZ9678                        | JACOME,PATRICIO,E            |                                                       | 
| 1314364192  | TLCCAR           | 5232133            | 07TAICHI  | 1LNHM82W63Y636737 | 644                       | FHPO710262                         | GUAN,YANG                    |                                                       | 
| 1314364192  | TLCCAR           | 5269650            | 0L3682G   | 1LNHM82W0XY614769 | 68                        | FKNJ08-0308                        | FUTA TRANSPORTATION          |                                                       | 
| 1314364192  | TLCCAR           | 5232767            | 0L4003G   | 1L1FM88W67Y637215 | 631                       | BA159499#4                         | AMERICAN LIMOUSINE COMPANY   |                                                       | 
| 1314364192  | TLCCAR           | 5297148            | 0L5686G   | 1LNLM82W9TY714745 | 68                        | FKNJ08-0308A1                      | FUTA TRANSPORTATION          |                                                       | 
| 1314364192  | TLCCAR           | 5324939            | 0L9435G   | 2FALP74W2VX103970 | 936                       | LNJ-02-10355                       | BEST FARE TRANSPORTATION LLC |                                                       | 
```