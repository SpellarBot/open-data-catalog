# SHL Vehicles Authorized

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shl-vehicles-authorized-ef67d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/btfj-je3i) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/btfj-je3i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/btfj-je3i/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | btfj-je3i |
| Name | SHL Vehicles Authorized |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | shl vehicles authorized, tlc, taxi and limousine commission (tlc) |
| Created | 2014-03-06T06:19:39Z |
| Publication Date | 2014-03-06T06:20:54Z |

## Description

This list contains information on the status of current SHL vehicles authorized to operate in New York City.

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag  | license_number                    | License Number                    | text          | text          |
| Yes      | series tag  | name_of_licensee                  | Name of Licensee                  | text          | text          |
| Yes      | series tag  | license_type                      | License Type                      | text          | text          |
| Yes      | series tag  | dmv_plate_number                  | DMV Plate Number                  | text          | text          |
| Yes      | series tag  | affiliated_vehicle_license_number | Affiliated Vehicle License Number | text          | number        |
| Yes      | series tag  | affiliated_base_license_number    | Affiliated Base License Number    | text          | text          |
| Yes      | series tag  | affiliated_base_name              | Affiliated Base Name              | text          | text          |
| Yes      | series tag  | base_phone_number                 | Base Phone Number                 | text          | text          |
| Yes      | series tag  | base_website                      | Base Website                      | text          | text          |
| Yes      | series tag  | base_location                     | Base Location                     | text          | text          |
| Yes      | series tag  | wav_non_wav                       | WAV/NON-WAV                       | text          | text          |
| Yes      | time        | certification_date                | Certification Date                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:btfj-je3i d:2013-10-28T00:00:00.000Z t:affiliated_base_license_number=B00131 t:license_type="TLC Street Hail Livery" t:wav_non_wav=NW t:license_number=AA018 t:base_phone_number="(646) 479-5686" t:dmv_plate_number=T635163C t:affiliated_base_name="NEW MEXICANA CAR SERVICE II INC." t:name_of_licensee="A/VA SERVICE CORP" t:base_location="469   53 STREET BROOKLYN NY 11220" t:affiliated_vehicle_license_number=5485413 m:row_number.btfj-je3i=1

series e:btfj-je3i d:2014-02-28T00:00:00.000Z t:affiliated_base_license_number=B00131 t:license_type="TLC Street Hail Livery" t:wav_non_wav=NW t:license_number=AA344 t:base_phone_number="(646) 479-5686" t:affiliated_base_name="NEW MEXICANA CAR SERVICE II INC." t:name_of_licensee="DYNAMIC DUO & LIMO INC" t:base_location="469   53 STREET BROOKLYN NY 11220" m:row_number.btfj-je3i=2

series e:btfj-je3i d:2013-09-23T00:00:00.000Z t:affiliated_base_license_number=B00131 t:license_type="TLC Street Hail Livery" t:wav_non_wav=NW t:license_number=AA234 t:base_phone_number="(646) 479-5686" t:dmv_plate_number=T629390C t:affiliated_base_name="NEW MEXICANA CAR SERVICE II INC." t:name_of_licensee=MAHGOUB,MOHAMED t:base_location="469   53 STREET BROOKLYN NY 11220" t:affiliated_vehicle_license_number=5477620 m:row_number.btfj-je3i=3
```

## Meta Commands

```ls
metric m:row_number.btfj-je3i p:long l:"Row Number"

entity e:btfj-je3i l:"SHL Vehicles Authorized" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/btfj-je3i

property e:btfj-je3i t:meta.view v:id=btfj-je3i v:category=Transportation v:averageRating=0 v:name="SHL Vehicles Authorized" v:attribution="Taxi and Limousine Commission (TLC)"

property e:btfj-je3i t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:btfj-je3i t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| license_number | name_of_licensee       | license_type           | dmv_plate_number | affiliated_vehicle_license_number | affiliated_base_license_number | affiliated_base_name             | base_phone_number | base_website | base_location                   | wav_non_wav | certification_date  | 
| ============== | ====================== | ====================== | ================ | ================================= | ============================== | ================================ | ================= | ============ | =============================== | =========== | =================== | 
| AA018          | A/VA SERVICE CORP      | TLC Street Hail Livery | T635163C         | 5485413                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2013-10-28T00:00:00 | 
| AA344          | DYNAMIC DUO & LIMO INC | TLC Street Hail Livery |                  |                                   | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2014-02-28T00:00:00 | 
| AA234          | MAHGOUB,MOHAMED        | TLC Street Hail Livery | T629390C         | 5477620                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2013-09-23T00:00:00 | 
| AC192          | RAMIREZ,ROBERTO,A      | TLC Street Hail Livery |                  |                                   | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | WV          |                     | 
| AA326          | MOHAMED,AHMED,I        | TLC Street Hail Livery | T638940C         | 5498780                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2013-08-26T00:00:00 | 
| AA383          | GULF LUXURY CARS INC   | TLC Street Hail Livery |                  |                                   | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2013-10-21T00:00:00 | 
| AF456          | HANIF,MOHAMMAD         | TLC Street Hail Livery | T644059C         | 5520303                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2014-01-27T00:00:00 | 
| AC599          | HOLMES, KEITH          | TLC Street Hail Livery |                  |                                   | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | WV          |                     | 
| AA158          | AHMED,MOHAMED,F        | TLC Street Hail Livery | T614488C         | 5414238                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2013-08-07T00:00:00 | 
| AE216          | SALIM,MOHAMMAD         | TLC Street Hail Livery | T623847C         | 5452062                           | B00131                         | NEW MEXICANA CAR SERVICE II INC. | (646) 479-5686    |              | 469 53 STREET BROOKLYN NY 11220 | NW          | 2014-02-14T00:00:00 | 
```