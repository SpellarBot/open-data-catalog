# Medallion Vehicles - Inactive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-vehicles-inactive-e07c9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jgtb-hmpg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jgtb-hmpg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jgtb-hmpg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jgtb-hmpg |
| Name | Medallion Vehicles - Inactive |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver, taxi suspension, suspended taxi, authorized taxi vehicle, nyc tlc taxi, inactive taxi |
| Created | 2013-05-17T17:22:00Z |
| Publication Date | 2017-04-20T20:27:54Z |

## Description

This list contains information on medallion vehicles that are currently inactive. The reason codes for an inactive medallion status are as follows: OOB for Out of Business, PEN for Pending, REV for Revoked, STO for In Storage and SUS for Suspended (Note: Reason for Suspension is also supplied). This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

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
| Yes      | time        | suspension_date          | Suspension Date          | calendar_date | calendar_date |
| Yes      | series tag  | suspension_reason        | Suspension Reason        | text          | text          |
| No       |             | last_updated_date        | Last Date Updated        | calendar_date | calendar_date |
| No       |             | last_updated_time        | Last Time Updated        | text          | text          |
```

## Time Field

```ls
Value = suspension_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = model_year,last_updated_date,last_updated_time
```

## Data Commands

```ls
series e:jgtb-hmpg d:2012-06-04T00:00:00.000Z t:medallion_type="NAMED DRIVER" t:license_number=1A16 t:name="STEED, THURSTON" t:suspension_reason="ACCOUNTS RECEIVABLE" t:dmv_license_plate_number=1A16A t:type=MEDALLION t:current_status=CUR t:agent_number=102 t:vehicle_vin_number=2FAFP70W27X156710 m:row_number.jgtb-hmpg=1

series e:jgtb-hmpg d:2012-09-11T00:00:00.000Z t:medallion_type="NAMED DRIVER" t:license_number=1A16 t:name="STEED, THURSTON" t:suspension_reason="ACCOUNTS RECEIVABLE" t:dmv_license_plate_number=1A16A t:type=MEDALLION t:current_status=CUR t:agent_number=102 t:vehicle_vin_number=2FAFP70W27X156710 m:row_number.jgtb-hmpg=2

series e:jgtb-hmpg d:2012-06-04T00:00:00.000Z t:medallion_type="NAMED DRIVER" t:license_number=5D50 t:name="MARTINEZ, MOLES JOHN" t:suspension_reason="ACCOUNTS RECEIVABLE" t:dmv_license_plate_number=5D50B t:type=MEDALLION t:current_status=CUR t:agent_number=000 t:vehicle_vin_number=2FAFP70W97X103423 m:row_number.jgtb-hmpg=3
```

## Meta Commands

```ls
metric m:row_number.jgtb-hmpg p:long l:"Row Number"

entity e:jgtb-hmpg l:"Medallion Vehicles - Inactive" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/jgtb-hmpg

property e:jgtb-hmpg t:meta.view v:id=jgtb-hmpg v:category=Transportation v:averageRating=0 v:name="Medallion Vehicles - Inactive" v:attribution="Taxi and Limousine Commission (TLC)"

property e:jgtb-hmpg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jgtb-hmpg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                 | type      | current_status | dmv_license_plate_number | vehicle_vin_number | vehicle_type | model_year | medallion_type | agent_number | suspension_date     | suspension_reason   | last_updated_date   | last_updated_time | 
| ============== | ==================== | ========= | ============== | ======================== | ================== | ============ | ========== | ============== | ============ | =================== | =================== | =================== | ================= | 
| 1A16           | STEED, THURSTON      | MEDALLION | CUR            | 1A16A                    | 2FAFP70W27X156710  |              | 2007       | NAMED DRIVER   | 102          | 2012-06-04T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 1A16           | STEED, THURSTON      | MEDALLION | CUR            | 1A16A                    | 2FAFP70W27X156710  |              | 2007       | NAMED DRIVER   | 102          | 2012-09-11T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 5D50           | MARTINEZ, MOLES JOHN | MEDALLION | CUR            | 5D50B                    | 2FAFP70W97X103423  |              | 2007       | NAMED DRIVER   | 000          | 2012-06-04T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 5D50           | MARTINEZ, MOLES JOHN | MEDALLION | CUR            | 5D50B                    | 2FAFP70W97X103423  |              | 2007       | NAMED DRIVER   | 000          | 2012-06-18T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 5J13           | MARIA HACKING INC    | MEDALLION | CUR            | 5J13B                    | 4T1BF1FK9CU522527  | HYB          | 2012       | NAMED DRIVER   | 000          | 2013-05-28T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 6D50           | LAZORJA, AUDUL       | MEDALLION | CUR            | 6D50A                    | 2FAFP70V48X160752  |              | 2008       | NAMED DRIVER   | 000          | 2012-06-18T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 9B47           | DEFTEREOS, APOSTOLOS | MEDALLION | CUR            | 9B47B                    | 2FAFP70W53X155514  |              | 2003       | NAMED DRIVER   | 000          | 2010-07-15T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 9B47           | DEFTEREOS, APOSTOLOS | MEDALLION | CUR            | 9B47B                    | 2FAFP70W53X155514  |              | 2003       | NAMED DRIVER   | 000          | 2012-06-04T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 9B47           | DEFTEREOS, APOSTOLOS | MEDALLION | CUR            | 9B47B                    | 2FAFP70W53X155514  |              | 2003       | NAMED DRIVER   | 000          | 2012-09-11T00:00:00 | ACCOUNTS RECEIVABLE | 2013-05-28T00:00:00 | 12:41             | 
| 1A16           | STEED, THURSTON      | MEDALLION | CUR            | 1A16A                    | 2FAFP70W27X156710  |              | 2007       | NAMED DRIVER   | 102          | 2011-09-21T00:00:00 | SUMM SUSP - LS      | 2013-05-28T00:00:00 | 12:41             | 
```