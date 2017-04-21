# Community Car Service Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-car-service-vehicles-f6407) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/scwj-eyn6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/scwj-eyn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/scwj-eyn6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | scwj-eyn6 |
| Name | Community Car Service Vehicles |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, community, car, vehicle, service |
| Created | 2011-08-29T17:53:48Z |
| Publication Date | 2013-06-26T17:21:06Z |

## Description

All TLC community car service vehicles

## Columns

```ls
| Included | Schema Type | Field Name                                         | Name                                               | Data Type     | Render Type   |
| ======== | =========== | ================================================== | ================================================== | ============= | ============= |
| Yes      | series tag  | affiliated_base_license_number                     | Affiliated Base License Number                     | text          | text          |
| Yes      | series tag  | affiliated_base_name                               | Affiliated Base Name                               | text          | text          |
| Yes      | series tag  | license_number                                     | License Number                                     | text          | number        |
| Yes      | series tag  | name_of_licensee                                   | Name of Licensee                                   | text          | text          |
| Yes      | series tag  | license_type                                       | License Type                                       | text          | text          |
| Yes      | series tag  | dmv_license_plate                                  | DMV License Plate                                  | text          | text          |
| Yes      | series tag  | vin                                                | VIN                                                | text          | text          |
| Yes      | series tag  | hybrid_accessible_cng_or_stretch_limousine_vehicle | Hybrid_Accessible_CNG_OR_Stretch_Limousine_Vehicle | text          | text          |
| No       |             | model_year                                         | Model Year                                         | number        | number        |
| Yes      | time        | license_expiration_date                            | License Expiration Date                            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = model_year
```

## Data Commands

```ls
series e:scwj-eyn6 d:2012-01-22T00:00:00.000Z t:affiliated_base_license_number=B00151 t:license_type=For-Hire-Vehicle t:license_number=5285404 t:vin=1LNHM84W34Y659083 t:dmv_license_plate=T504106C t:name_of_licensee=VIGDORCHIK,BORIS t:affiliated_base_name="KINGSBAY CAR SERVICE INC" m:row_number.scwj-eyn6=1

series e:scwj-eyn6 d:2013-05-04T00:00:00.000Z t:affiliated_base_license_number=B00882 t:license_type=For-Hire-Vehicle t:license_number=5396489 t:vin=2FAHP71V38X100548 t:dmv_license_plate=T607569C t:name_of_licensee=ASIEDU,BRIGHT t:affiliated_base_name="U N C CAR & LIMO SERVICE" m:row_number.scwj-eyn6=2

series e:scwj-eyn6 d:2013-05-10T00:00:00.000Z t:affiliated_base_license_number=B01437 t:license_type=For-Hire-Vehicle t:license_number=5395656 t:vin=1LNHM81W74Y629136 t:dmv_license_plate=T609924C t:name_of_licensee="JHOMMEL CORP" t:affiliated_base_name="MERENGUE LIMO & C/S INC" m:row_number.scwj-eyn6=3
```

## Meta Commands

```ls
metric m:row_number.scwj-eyn6 p:long l:"Row Number"

entity e:scwj-eyn6 l:"Community Car Service Vehicles" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/scwj-eyn6

property e:scwj-eyn6 t:meta.view v:id=scwj-eyn6 v:category=Transportation v:averageRating=0 v:name="Community Car Service Vehicles" v:attribution="Taxi and Limousine Commission (TLC)"

property e:scwj-eyn6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:scwj-eyn6 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| affiliated_base_license_number | affiliated_base_name     | license_number | name_of_licensee | license_type     | dmv_license_plate | vin               | hybrid_accessible_cng_or_stretch_limousine_vehicle | model_year | license_expiration_date | 
| ============================== | ======================== | ============== | ================ | ================ | ================= | ================= | ================================================== | ========== | ======================= | 
| B00151                         | KINGSBAY CAR SERVICE INC | 5285404        | VIGDORCHIK,BORIS | For-Hire-Vehicle | T504106C          | 1LNHM84W34Y659083 |                                                    | 2004       | 2012-01-22T00:00:00     | 
| B00882                         | U N C CAR & LIMO SERVICE | 5396489        | ASIEDU,BRIGHT    | For-Hire-Vehicle | T607569C          | 2FAHP71V38X100548 |                                                    | 2008       | 2013-05-04T00:00:00     | 
| B01437                         | MERENGUE LIMO & C/S INC  | 5395656        | JHOMMEL CORP     | For-Hire-Vehicle | T609924C          | 1LNHM81W74Y629136 |                                                    | 2004       | 2013-05-10T00:00:00     | 
| B01710                         | 68 INC.                  | 5355147        | MYSHKIN,VIKTOR   | For-Hire-Vehicle | T525476C          | 2FMZA50615BA09958 |                                                    | 2005       | 2012-02-05T00:00:00     | 
| B01733                         | SHMT INC.                | 5287950        | SHMT INC         | For-Hire-Vehicle | T498367C          | 2MEFM75W82X608601 |                                                    | 2002       | 2012-02-25T00:00:00     | 
| B00008                         | T-D MAINTENANCE CORP     | 5090331        | HGF LIMO CORP.   | For-Hire-Vehicle | T412825C          | 2G4WS52J331130754 |                                                    | 2003       | 2013-08-02T00:00:00     | 
| B00008                         | T-D MAINTENANCE CORP     | 5090337        | HGF LIMO CORP.   | For-Hire-Vehicle | T412828C          | 2G4WS52J121155862 |                                                    | 2002       | 2013-08-02T00:00:00     | 
| B00008                         | T-D MAINTENANCE CORP     | 5090338        | HGF LIMO CORP.   | For-Hire-Vehicle | T412824C          | 2G4WS52J721244562 |                                                    | 2002       | 2013-08-02T00:00:00     | 
| B00008                         | T-D MAINTENANCE CORP     | 5093652        | KJI LIMO CORP.   | For-Hire-Vehicle | T412873C          | 2G4WS52J211135599 |                                                    | 2001       | 2011-09-14T00:00:00     | 
| B00008                         | T-D MAINTENANCE CORP     | 5097852        | NML LIMO CORP    | For-Hire-Vehicle | T412900C          | 2G4WS52J411286928 |                                                    | 2001       | 2011-11-16T00:00:00     | 
```