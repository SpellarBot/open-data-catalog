# Multi Agency Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multi-agency-permits-bab9d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xfyi-uyt5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xfyi-uyt5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xfyi-uyt5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xfyi-uyt5 |
| Name | Multi Agency Permits |
| Attribution | Mayor's Office of Data Analytics (MODA) |
| Category | City Government |
| Tags | moda, multi agency permits, dob jobs permits, dohmh permits, jobs permits, permits, dob, dohmh |
| Created | 2013-06-12T00:44:25Z |
| Publication Date | 2013-06-21T20:01:56Z |

## Description

The Multi Agency Permits dataset contains the permits data from two different data sources/exchanges ? DOB Jobs Permits and DOHMH Permits

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | source                      | Source                      | text      | text        |
| Yes      | series tag  | license_permit_holder       | License_Permit_Holder       | text      | text        |
| Yes      | series tag  | business_description        | Business_Description        | text      | text        |
| Yes      | series tag  | license_permit_number       | License/Permit_Number       | text      | text        |
| Yes      | series tag  | permit_type_description     | Permit_Type_Description     | text      | text        |
| Yes      | series tag  | permit_subtype_description  | Permit_Subtype_Description  | text      | text        |
| No       |             | permit_issuance_date        | Permit_Issuance_Date        | text      | text        |
| No       |             | permit_expiration_date      | Permit_Expiration_Date      | text      | text        |
| No       |             | permit_status_date          | Permit_Status_Date          | text      | text        |
| Yes      | series tag  | permit_status_description   | Permit_Status_Description   | text      | text        |
| No       |             | address                     | Address                     | text      | text        |
| Yes      | series tag  | street                      | Street                      | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | zip_code                    | Zip_Code                    | text      | text        |
| Yes      | series tag  | borough                     | Borough                     | text      | text        |
| Yes      | series tag  | building_id                 | Building_ID_No              | text      | text        |
| Yes      | series tag  | borough_block_lot           | Borough_Block_Lot           | text      | text        |
| Yes      | series tag  | latitude_wgs84              | Latitude_WGS84              | text      | text        |
| Yes      | series tag  | longitude_wgs84             | Longitude_WGS84             | text      | text        |
| Yes      | series tag  | license_permit_holder_name  | License/Permit_Holder_Name  | text      | text        |
| Yes      | series tag  | dob_skilled_trades_lic_num  | DOB_Skilled_Trades_Lic_Num  | text      | text        |
| Yes      | series tag  | dob_skilled_trades_lic_type | DOB_Skilled_Trades_Lic_Type | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = permit_issuance_date,permit_expiration_date,permit_status_date,address
```

## Data Commands

```ls
series e:xfyi-uyt5 d:2013-06-11T17:44:35.000Z t:license_permit_number=30043914901 t:zip_code=11203 t:building_id=3222087 t:street="EAST 52 STREET" t:borough=BROOKLYN t:permit_status_description="PERMIT ISSUED" t:city=BROOKLYN t:longitude_wgs84=-73.92708 t:permit_type_description="EQUIPMENT WORK" t:source="DOB Job Permit" t:dob_skilled_trades_lic_type=OW t:borough_block_lot=3079280038 t:license_permit_holder=SAME t:latitude_wgs84=40.641806 m:row_number.xfyi-uyt5=1

series e:xfyi-uyt5 d:2013-06-11T17:44:35.000Z t:license_permit_number=30029595402 t:zip_code=11230 t:building_id=3181570 t:street="EAST 19 STREET" t:borough=BROOKLYN t:permit_status_description="PERMIT ISSUED" t:city=BROOKLYN t:longitude_wgs84=-73.955698 t:permit_type_description="EQUIPMENT WORK" t:source="DOB Job Permit" t:license_permit_holder="A.T.A. CONSTRUCTION" t:borough_block_lot=3067560042 t:latitude_wgs84=40.613956 m:row_number.xfyi-uyt5=2

series e:xfyi-uyt5 d:2013-06-11T17:44:35.000Z t:license_permit_number=30029595401 t:zip_code=11230 t:building_id=3181570 t:street="EAST 19 STREET" t:borough=BROOKLYN t:permit_status_description="PERMIT ISSUED" t:city=BROOKLYN t:longitude_wgs84=-73.955698 t:permit_type_description="EQUIPMENT WORK" t:source="DOB Job Permit" t:license_permit_holder="A.T.A. CONSTRUCTION" t:borough_block_lot=3067560042 t:latitude_wgs84=40.613956 m:row_number.xfyi-uyt5=3
```

## Meta Commands

```ls
metric m:row_number.xfyi-uyt5 p:long l:"Row Number"

entity e:xfyi-uyt5 l:"Multi Agency Permits" t:attribution="Mayor's Office of Data Analytics (MODA)" t:url=https://data.cityofnewyork.us/api/views/xfyi-uyt5

property e:xfyi-uyt5 t:meta.view v:id=xfyi-uyt5 v:category="City Government" v:averageRating=0 v:name="Multi Agency Permits" v:attribution="Mayor's Office of Data Analytics (MODA)"

property e:xfyi-uyt5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xfyi-uyt5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | source         | license_permit_holder      | business_description | license_permit_number | permit_type_description | permit_subtype_description | permit_issuance_date | permit_expiration_date | permit_status_date | permit_status_description | address | street         | city     | zip_code | borough  | building_id | borough_block_lot | latitude_wgs84 | longitude_wgs84 | license_permit_holder_name | dob_skilled_trades_lic_num | dob_skilled_trades_lic_type | 
| =========== | ============== | ========================== | ==================== | ===================== | ======================= | ========================== | ==================== | ====================== | ================== | ========================= | ======= | ============== | ======== | ======== | ======== | =========== | ================= | ============== | =============== | ========================== | ========================== | =========================== | 
| 1370972675  | DOB Job Permit | SAME                       |                      | 30043914901           | EQUIPMENT WORK          |                            | 1999-06-03           | 2000-06-02             | 1999-06-03         | PERMIT ISSUED             | 753     | EAST 52 STREET | BROOKLYN | 11203    | BROOKLYN | 3222087     | 3079280038        | 40.641806      | -73.92708       |                            |                            | OW                          | 
| 1370972675  | DOB Job Permit | A.T.A. CONSTRUCTION        |                      | 30029595402           | EQUIPMENT WORK          |                            | 1997-01-15           | 1997-08-05             | 1997-01-15         | PERMIT ISSUED             | 1488    | EAST 19 STREET | BROOKLYN | 11230    | BROOKLYN | 3181570     | 3067560042        | 40.613956      | -73.955698      |                            |                            |                             | 
| 1370972675  | DOB Job Permit | A.T.A. CONSTRUCTION        |                      | 30029595401           | EQUIPMENT WORK          |                            | 1996-03-25           | 1996-08-05             | 1996-03-25         | PERMIT ISSUED             | 1488    | EAST 19 STREET | BROOKLYN | 11230    | BROOKLYN | 3181570     | 3067560042        | 40.613956      | -73.955698      |                            |                            |                             | 
| 1370972675  | DOB Job Permit | A.T.A. CONSTRUCTION        |                      | 30029595403           | EQUIPMENT WORK          |                            | 1998-12-07           | 1999-08-05             | 1998-12-07         | PERMIT ISSUED             | 1488    | EAST 19 STREET | BROOKLYN | 11230    | BROOKLYN | 3181570     | 3067560042        | 40.613956      | -73.955698      |                            | 0008164                    | GC                          | 
| 1370972675  | DOB Job Permit | VAS & SONS CORP            |                      | 32010861901           | EQUIPMENT               | FENCE                      | 2010-02-12           | 2010-04-25             | 2010-02-12         | PERMIT ISSUED             | 1954    | OCEAN AVENUE   | BROOKLYN | 11230    | BROOKLYN | 3181615     | 3067570042        | 40.614241      | -73.954631      |                            | 0600253                    | GC                          | 
| 1370972675  | DOB Job Permit | VAS & SONS CORP            |                      | 32010861901           | EQUIPMENT WORK          |                            | 2010-02-12           | 2010-04-25             | 2010-02-12         | PERMIT ISSUED             | 1954    | OCEAN AVENUE   | BROOKLYN | 11230    | BROOKLYN | 3181615     | 3067570042        | 40.614241      | -73.954631      |                            | 0600253                    | GC                          | 
| 1370972675  | DOB Job Permit | VAS & SONS CORP            |                      | 32010861902           | EQUIPMENT               | FENCE                      | 2010-05-06           | 2011-04-25             | 2010-05-06         | PERMIT ISSUED             | 1954    | OCEAN AVENUE   | BROOKLYN | 11230    | BROOKLYN | 3181615     | 3067570042        | 40.614241      | -73.954631      |                            | 0600253                    | GC                          | 
| 1370972675  | DOB Job Permit | VAS & SONS CORP            |                      | 32010861902           | EQUIPMENT WORK          |                            | 2010-05-06           | 2011-04-25             | 2010-05-06         | PERMIT ISSUED             | 1954    | OCEAN AVENUE   | BROOKLYN | 11230    | BROOKLYN | 3181615     | 3067570042        | 40.614241      | -73.954631      |                            | 0600253                    | GC                          | 
| 1370972675  | DOB Job Permit | FREEDMAN BUILT LTD.        |                      | 30065222901           | EQUIPMENT WORK          |                            | 1997-07-31           | 1998-03-28             | 1997-07-31         | PERMIT ISSUED             | 1474    | EAST 13 STREET | BROOKLYN | 11230    | BROOKLYN | 3181229     | 3067500039        | 40.613521      | -73.961364      |                            | 0003589                    | GC                          | 
| 1370972675  | DOB Job Permit | I & L PLUMBING SERVICE INC |                      | 30065222901           | PLUMBING                |                            | 1998-05-07           | 1999-05-07             | 1998-05-07         | PERMIT ISSUED             | 1474    | EAST 13 STREET | BROOKLYN | 11230    | BROOKLYN | 3181229     | 3067500039        | 40.613521      | -73.961364      |                            | 0000896                    | MP                          | 
```