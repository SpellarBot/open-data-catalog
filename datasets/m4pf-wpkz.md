# Trained Medallion Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trained-medallion-drivers-bb891) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m4pf-wpkz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m4pf-wpkz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m4pf-wpkz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m4pf-wpkz |
| Name | Trained Medallion Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, medallion, taxi, driver, training, trained |
| Created | 2012-09-06T14:05:20Z |
| Publication Date | 2013-04-24T19:41:42Z |

## Description

This dataset is no longer being updated by the New York City Taxi and Limousine Commission. Please update your links to the links listed below. Thank you.

Medallion Drivers - Trained:
https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Trained/td5q-ry6d

## Columns

```ls
| Included | Schema Type | Field Name                                 | Name                                       | Data Type     | Render Type   |
| ======== | =========== | ========================================== | ========================================== | ============= | ============= |
| Yes      | time        | date_updated                               | Date Updated                               | calendar_date | calendar_date |
| Yes      | series tag  | license_number                             | License Number                             | text          | text          |
| Yes      | series tag  | name_of_licensee                           | Name of Licensee                           | text          | text          |
| Yes      | series tag  | license_type                               | License Type                               | text          | text          |
| Yes      | series tag  | license_expiration_date                    | License Expiration Date                    | text          | text          |
| Yes      | series tag  | completed_both_accessible_training_courses | Completed Both Accessible Training Courses | text          | text          |
```

## Time Field

```ls
Value = date_updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:m4pf-wpkz d:2012-09-06T00:00:00.000Z t:license_expiration_date=09/12/2013 t:license_type="MEDALLION TAXI DRIVER" t:completed_both_accessible_training_courses=YES t:license_number=5206638 t:name_of_licensee=ANDERSON,SVETLANA m:row_number.m4pf-wpkz=1

series e:m4pf-wpkz d:2012-09-06T00:00:00.000Z t:license_expiration_date=01/19/2013 t:license_type="MEDALLION TAXI DRIVER" t:completed_both_accessible_training_courses=YES t:license_number=5348440 t:name_of_licensee=SATOROV,NOSIRDJON m:row_number.m4pf-wpkz=2

series e:m4pf-wpkz d:2012-09-06T00:00:00.000Z t:license_expiration_date=02/28/2014 t:license_type="MEDALLION TAXI DRIVER" t:completed_both_accessible_training_courses=YES t:license_number=5211857 t:name_of_licensee=DIALLO,IBRAHIMA,S m:row_number.m4pf-wpkz=3
```

## Meta Commands

```ls
metric m:row_number.m4pf-wpkz p:long l:"Row Number"

entity e:m4pf-wpkz l:"Trained Medallion Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/m4pf-wpkz

property e:m4pf-wpkz t:meta.view v:id=m4pf-wpkz v:category=Transportation v:averageRating=0 v:name="Trained Medallion Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:m4pf-wpkz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m4pf-wpkz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date_updated        | license_number | name_of_licensee  | license_type          | license_expiration_date | completed_both_accessible_training_courses | 
| =================== | ============== | ================= | ===================== | ======================= | ========================================== | 
| 2012-09-06T00:00:00 | 5206638        | ANDERSON,SVETLANA | MEDALLION TAXI DRIVER | 09/12/2013              | YES                                        | 
| 2012-09-06T00:00:00 | 5348440        | SATOROV,NOSIRDJON | MEDALLION TAXI DRIVER | 01/19/2013              | YES                                        | 
| 2012-09-06T00:00:00 | 5211857        | DIALLO,IBRAHIMA,S | MEDALLION TAXI DRIVER | 02/28/2014              | YES                                        | 
| 2012-09-06T00:00:00 | 5110452        | SOW,MAMOUDOU      | MEDALLION TAXI DRIVER | 06/07/2014              | YES                                        | 
| 2012-09-06T00:00:00 | 5207142        | AZAD,MOHAMMAD,A   | MEDALLION TAXI DRIVER | 01/31/2014              | YES                                        | 
| 2012-09-06T00:00:00 | 5324350        | UDDIN,SM,TANVIR   | MEDALLION TAXI DRIVER | 06/12/2014              | YES                                        | 
| 2012-09-06T00:00:00 | 5407244        | ASKAROV,FARHOD,T  | MEDALLION TAXI DRIVER | 11/09/2012              | YES                                        | 
| 2012-09-06T00:00:00 | 5182087        | HOSSAIN,MD,A      | MEDALLION TAXI DRIVER | 12/02/2012              | YES                                        | 
| 2012-09-06T00:00:00 | 5101355        | HAZAN,MARCO,J     | MEDALLION TAXI DRIVER | 03/14/2014              | YES                                        | 
| 2012-09-06T00:00:00 | 5268359        | SEHBANI,TAOUFIK   | MEDALLION TAXI DRIVER | 08/28/2014              | YES                                        | 
```