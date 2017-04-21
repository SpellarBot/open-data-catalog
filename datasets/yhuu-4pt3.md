# Street Hail Livery (SHL) Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-hail-livery-permits-ccfa1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yhuu-4pt3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yhuu-4pt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yhuu-4pt3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yhuu-4pt3 |
| Name | Street Hail Livery (SHL) Permits |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | green taxi, green cab, shl, street hail livery |
| Created | 2014-10-29T17:42:50Z |
| Publication Date | 2017-04-20T18:50:46Z |

## Description

This is a list of NYC TLC authorized Street Hail Livery Permits. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.  Reason Code: G ? Good Standing, A ? Problem with Permit, B ? Problem with Base and C ? Problem with Vehicle.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | active                   | Active                   | text          | text          |
| Yes      | series tag  | license_number           | Permit License Number    | text          | text          |
| Yes      | series tag  | name                     | Name                     | text          | text          |
| Yes      | series tag  | license_type             | Expiration Date          | text          | text          |
| Yes      | series tag  | license_status           | Vehicle License Number   | text          | text          |
| Yes      | series tag  | dmv_license_plate_number | DMV License Plate Number | text          | text          |
| Yes      | series tag  | vehicle_vin_number       | Vehicle VIN Number       | text          | text          |
| Yes      | series tag  | vehicle_type             | Vehicle Type             | text          | text          |
| Yes      | time        | certification_date       | Certification Date       | calendar_date | calendar_date |
| No       |             | hack_up_date             | Hack Up Date             | calendar_date | calendar_date |
| No       |             | vehicle_year             | Vehicle Year             | calendar_date | calendar_date |
| Yes      | series tag  | base_number              | Base Number              | text          | text          |
| Yes      | series tag  | base_name                | Base Name                | text          | text          |
| Yes      | series tag  | base_telephone_number    | Base Telephone Number    | text          | text          |
| Yes      | series tag  | base_website             | Base Website             | text          | text          |
| No       |             | base_address             | Base Address             | text          | text          |
| Yes      | series tag  | suspension_reason        | Reason                   | text          | text          |
| No       |             | suspension_date          | Suspension Date          | calendar_date | calendar_date |
| No       |             | date_updated             | Last Date Updated        | calendar_date | calendar_date |
| No       |             | time_updated             | Last Time Updated        | text          | text          |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = hack_up_date,vehicle_year,base_address,suspension_date,date_updated,time_updated
```

## Data Commands

```ls
series e:yhuu-4pt3 d:2017-04-20T18:50:28.000Z t:license_type=09/12/2016 t:base_telephone_number=(718)705-8550 t:vehicle_type=WAV t:license_number=AC555 t:name=YAGODAYEV,SIMCHA t:suspension_reason=A,C t:active=NO t:base_number=B02816 t:base_name="GLS TRANS INC" m:row_number.yhuu-4pt3=1

series e:yhuu-4pt3 d:2017-04-20T18:50:28.000Z t:license_type=09/20/2016 t:base_telephone_number=(718)444-5125 t:vehicle_type=WAV t:license_number=AC907 t:name="ASHRAF, WAQAR" t:suspension_reason=A,B,C t:active=NO t:base_number=B90675 t:base_name="ABBA LOCAL TRANSPORTATION INC" m:row_number.yhuu-4pt3=2

series e:yhuu-4pt3 d:2017-04-20T18:50:28.000Z t:license_type=09/20/2016 t:base_telephone_number=(718)444-5125 t:vehicle_type=WAV t:license_number=AC909 t:name="ASHRAF, WAQAR" t:suspension_reason=A,B,C t:active=NO t:base_number=B90675 t:base_name="ABBA LOCAL TRANSPORTATION INC" m:row_number.yhuu-4pt3=3
```

## Meta Commands

```ls
metric m:row_number.yhuu-4pt3 p:long l:"Row Number"

entity e:yhuu-4pt3 l:"Street Hail Livery (SHL) Permits" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/yhuu-4pt3

property e:yhuu-4pt3 t:meta.view v:id=yhuu-4pt3 v:category=Transportation v:averageRating=0 v:name="Street Hail Livery (SHL) Permits" v:attribution="Taxi and Limousine Commission (TLC)"

property e:yhuu-4pt3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yhuu-4pt3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| active | license_number | name               | license_type | license_status | dmv_license_plate_number | vehicle_vin_number | vehicle_type | certification_date  | hack_up_date        | vehicle_year        | base_number | base_name                     | base_telephone_number | base_website             | base_address                                   | suspension_reason | suspension_date | date_updated        | time_updated | 
| ====== | ============== | ================== | ============ | ============== | ======================== | ================== | ============ | =================== | =================== | =================== | =========== | ============================= | ===================== | ======================== | ============================================== | ================= | =============== | =================== | ============ | 
| NO     | AC555          | YAGODAYEV,SIMCHA   | 09/12/2016   |                |                          |                    | WAV          |                     |                     |                     | B02816      | GLS TRANS INC                 | (718)705-8550         |                          | 1468 WILLIAMSBRIDGE ROAD BRONX NY 10461        | A,C               |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | AC907          | ASHRAF, WAQAR      | 09/20/2016   |                |                          |                    | WAV          |                     |                     |                     | B90675      | ABBA LOCAL TRANSPORTATION INC | (718)444-5125         |                          | 4301 GLENWOOD ROAD 2ND FLOOR BROOKLYN NY 11210 | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | AC909          | ASHRAF, WAQAR      | 09/20/2016   |                |                          |                    | WAV          |                     |                     |                     | B90675      | ABBA LOCAL TRANSPORTATION INC | (718)444-5125         |                          | 4301 GLENWOOD ROAD 2ND FLOOR BROOKLYN NY 11210 | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | AC911          | ASHRAF, WAQAR      | 09/20/2016   |                |                          |                    | WAV          |                     |                     |                     | B90675      | ABBA LOCAL TRANSPORTATION INC | (718)444-5125         |                          | 4301 GLENWOOD ROAD 2ND FLOOR BROOKLYN NY 11210 | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | AC914          | ASHRAF, WAQAR      | 09/20/2016   |                |                          |                    | WAV          |                     |                     |                     | B90675      | ABBA LOCAL TRANSPORTATION INC | (718)444-5125         |                          | 4301 GLENWOOD ROAD 2ND FLOOR BROOKLYN NY 11210 | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | AC104          | HOSSAIN,SHAZIB     | 08/29/2019   |                |                          |                    |              |                     |                     |                     |             |                               |                       |                          |                                                | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| NO     | BA618          | SAAD,EMAD,E        | 09/15/2017   |                |                          |                    | WAV          |                     |                     |                     |             |                               |                       |                          |                                                | A,B,C             |                 | 2017-04-19T00:00:00 | 13:25        | 
| YES    | AA001          | REYNOSO,WILFREDO,A | 06/12/2019   | 5289560        | T502927C                 | 4T1BF3EK0AU116100  |              | 2017-01-25T00:00:00 | 2013-08-08T00:00:00 | 2010-01-01T00:00:00 | B01678      | G.T.N.Y. CAR SERVICE, INC.    | (646)852-6641         |                          | 177 SHERMAN AVENUE NEW YORK NY 10034           | G                 |                 | 2017-04-19T00:00:00 | 13:25        | 
| YES    | AA002          | ALVAREZ,VICTOR,D   | 06/12/2019   | 5136396        | T453378C                 | 3FA6P0LU5DR173559  |              | 2013-08-08T00:00:00 | 2013-08-08T00:00:00 | 2013-01-01T00:00:00 | B00937      | RIVERSIDE RADIO DISPATCHER    | (212)923-1111         | WWW.RIVERSIDECARLIMO.COM | 1642 ST NICHOLAS AVENUE NEW YORK NY 10040      | G                 |                 | 2017-04-19T00:00:00 | 13:25        | 
| YES    | AA003          | ALVAREZ,ROGELIO,A  | 06/12/2019   | C34096         | T427995C                 | JTDZN3EU3GJ045248  |              | 2016-04-28T00:00:00 | 2016-04-29T00:00:00 | 2016-01-01T00:00:00 | B00937      | RIVERSIDE RADIO DISPATCHER    | (212)923-1111         | WWW.RIVERSIDECARLIMO.COM | 1642 ST NICHOLAS AVENUE NEW YORK NY 10040      | G                 |                 | 2017-04-19T00:00:00 | 13:25        | 
```