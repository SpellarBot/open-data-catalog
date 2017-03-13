# Current Medallion Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-medallion-drivers-acc0e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s22f-jsd4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s22f-jsd4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s22f-jsd4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s22f-jsd4 |
| Name | Current Medallion Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, taxi, medallion, cab, license, driver |
| Created | 2012-09-06T14:30:32Z |
| Publication Date | 2013-04-24T19:39:45Z |
| Rows Updated | 2013-04-24T19:36:34Z |

## Description

This dataset is no longer being updated by the New York City Taxi and Limousine Commission. Please update your links to the links listed below. Thank you.

Medallion Drivers - Active:
https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/n776-dsqy

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | date_updated            | Date Updated            | calendar_date | calendar_date |
| Yes      | numeric metric | license_number          | License Number          | number        | text          |
| Yes      | series tag     | name_of_licensee        | Name of Licensee        | text          | text          |
| Yes      | series tag     | license_type            | License Type            | text          | text          |
| Yes      | series tag     | license_expiration_date | License Expiration Date | text          | text          |
```

## Time Field

```ls
Value = date_updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=08/06/2014 t:license_type="MEDALLION TAXI DRIVER" t:name_of_licensee=FILS-AIME,CHARITE m:license_number=427586

series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=05/10/2013 t:license_type="MEDALLION TAXI DRIVER" t:name_of_licensee=TOKI,ABDELHAK m:license_number=5195097

series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=10/30/2012 t:license_type="MEDALLION TAXI DRIVER" t:name_of_licensee=SINGH,RAJDEEP m:license_number=5054307
```

## Meta Commands

```ls
metric m:license_number p:integer l:"License Number" t:dataTypeName=number

entity e:s22f-jsd4 l:"Current Medallion Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/s22f-jsd4

property e:s22f-jsd4 t:meta.view v:id=s22f-jsd4 v:category=Transportation v:averageRating=0 v:name="Current Medallion Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:s22f-jsd4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:s22f-jsd4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```