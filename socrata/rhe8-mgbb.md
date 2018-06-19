# Medallion Vehicles - Authorized

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-vehicles-authorized-44673) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rhe8-mgbb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rhe8-mgbb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rhe8-mgbb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rhe8-mgbb |
| Name | Medallion Vehicles - Authorized |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2013-03-01T19:27:08Z |
| Publication Date | 2017-04-21T00:59:24Z |

## Description

This list contains information on the status of current medallion vehicles authorized to operate in New York City. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | license_number           | License Number           | text          | text          |
| Yes      | series tag  | name                     | Name                     | text          | text          |
| Yes      | series tag  | type                     | Expiration Date          | text          | text          |
| Yes      | series tag  | current_status           | Current Status           | text          | text          |
| Yes      | series tag  | dmv_license_plate_number | DMV License Plate Number | text          | text          |
| Yes      | series tag  | vehicle_vin_number       | Vehicle VIN Number       | text          | text          |
| Yes      | series tag  | vehicle_type             | Vehicle Type             | text          | text          |
| No       |             | model_year               | Model Year               | text          | text          |
| Yes      | series tag  | medallion_type           | Medallion Type           | text          | text          |
| Yes      | series tag  | agent_number             | Agent Number             | text          | text          |
| Yes      | series tag  | agent_name               | Agent Name               | text          | text          |
| Yes      | series tag  | agent_telephone_number   | Agent Telephone Number   | text          | text          |
| Yes      | series tag  | agent_website_address    | Agent Website Address    | text          | text          |
| No       |             | agent_address            | Agent Address            | text          | text          |
| Yes      | time        | last_updated_date        | Last Date Updated        | calendar_date | calendar_date |
| No       |             | last_updated_time        | Last Time Updated        | text          | text          |
```

## Time Field

```ls
Value = last_updated_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = model_year,agent_address,last_updated_time
```

## Data Commands

```ls
series e:rhe8-mgbb d:2014-09-12T00:00:00.000Z t:medallion_type="OWNER MUST DRIVE" t:vehicle_type=HYB t:license_number=8E94 t:name=SINGH,BAGICHA t:dmv_license_plate_number=8E94H t:type=MEDALLION t:current_status=CUR t:agent_number=000 t:vehicle_vin_number=1FMCU4K35BKA45650 m:row_number.rhe8-mgbb=1

series e:rhe8-mgbb d:2013-11-14T00:00:00.000Z t:medallion_type="OWNER MUST DRIVE" t:license_number=8Y15 t:name="DOS SANTOS,ELSON N." t:dmv_license_plate_number=8Y15A t:type=MEDALLION t:current_status=CUR t:agent_number=000 t:vehicle_vin_number=2FABP7AV9BX137438 m:row_number.rhe8-mgbb=2

series e:rhe8-mgbb d:2013-09-25T00:00:00.000Z t:medallion_type="NAMED DRIVER" t:license_number=9M23 t:name="NIKOS BARKAS TAXI INC" t:dmv_license_plate_number=9M23H t:type=MEDALLION t:current_status=CUR t:agent_number=314 t:vehicle_vin_number=2FABP7AV2BX101011 m:row_number.rhe8-mgbb=3
```

## Meta Commands

```ls
metric m:row_number.rhe8-mgbb p:long l:"Row Number"

entity e:rhe8-mgbb l:"Medallion  Vehicles - Authorized" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/rhe8-mgbb

property e:rhe8-mgbb t:meta.view v:id=rhe8-mgbb v:category=Transportation v:averageRating=0 v:name="Medallion  Vehicles - Authorized" v:attribution="Taxi and Limousine Commission (TLC)"

property e:rhe8-mgbb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rhe8-mgbb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                  | type      | current_status | dmv_license_plate_number | vehicle_vin_number | vehicle_type | model_year | medallion_type   | agent_number | agent_name                   | agent_telephone_number | agent_website_address | agent_address                       | last_updated_date   | last_updated_time | 
| ============== | ===================== | ========= | ============== | ======================== | ================== | ============ | ========== | ================ | ============ | ============================ | ====================== | ===================== | =================================== | =================== | ================= | 
| 8E94           | SINGH,BAGICHA         | MEDALLION | CUR            | 8E94H                    | 1FMCU4K35BKA45650  | HYB          | 2011       | OWNER MUST DRIVE | 000          |                              |                        |                       |                                     | 2014-09-12T00:00:00 | 13:20             | 
| 8Y15           | DOS SANTOS,ELSON N.   | MEDALLION | CUR            | 8Y15A                    | 2FABP7AV9BX137438  |              | 2011       | OWNER MUST DRIVE | 000          |                              |                        |                       |                                     | 2013-11-14T00:00:00 | 13:20             | 
| 9M23           | NIKOS BARKAS TAXI INC | MEDALLION | CUR            | 9M23H                    | 2FABP7AV2BX101011  |              | 2011       | NAMED DRIVER     | 314          |                              |                        |                       |                                     | 2013-09-25T00:00:00 | 13:20             | 
| 4D98           | SINGH,BALWINDER       | MEDALLION | CUR            | 4D98A                    | 3N8CM0JTXEK702552  |              | 2014       | OWNER MUST DRIVE | 000          |                              |                        |                       |                                     | 2015-02-04T00:00:00 | 13:20             | 
| 1E58           | TURETSKY,MIKHAIL      | MEDALLION | CUR            | 1E58A                    | 4T1BB3EKXBU140742  | HYB          | 2011       | NAMED DRIVER     | 202          |                              |                        |                       |                                     | 2013-11-07T00:00:00 | 13:20             | 
| 4P99           | PEAD CAB CORP         | MEDALLION | CUR            | 4P99H                    | 1N4AL3AP8DC231442  |              | 2013       | NAMED DRIVER     | 017          |                              |                        |                       |                                     | 2013-08-27T00:00:00 | 13:20             | 
| 8V69           | PUMO TAXI INC.        | MEDALLION | CUR            | 8V69H                    | 5TDZK3DCXBS099501  | WAV          | 2011       | NAMED DRIVER     | 020          | DOWNTOWN TAXI MANAGEMENT LLC | (718)435-0660          |                       | 330 BUTLER STREET BROOKLYN NY 11217 | 2014-10-09T00:00:00 | 13:20             | 
| 6A47           | SHAFI,MAJID,N         | MEDALLION | CUR            | 6A47D                    | 1FMCU49H08KD83337  | HYB          | 2008       | OWNER MUST DRIVE | 000          |                              |                        |                       |                                     | 2013-09-11T00:00:00 | 13:20             | 
| 4J78           | POOPIE CAB CORP       | MEDALLION | CUR            | 4J78B                    | 2FABP7AV4AX111814  |              | 2010       | NAMED DRIVER     | 290          |                              |                        |                       |                                     | 2013-06-01T00:00:00 | 13:20             | 
| 9P99           | LORENA TRANSIT INC.   | MEDALLION | CUR            | 9P99B                    | 2FABP7AV8AX106132  |              | 2010       | NAMED DRIVER     | 000          |                              |                        |                       |                                     | 2014-03-06T00:00:00 | 13:20             | 
```