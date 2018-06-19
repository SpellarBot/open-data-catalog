# Medallion Drivers ? Status Change Log 10/28/2013 - present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-drivers-status-change-log-10-28-2013-present-bcca6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sjfe-fppp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sjfe-fppp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sjfe-fppp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sjfe-fppp |
| Name | Medallion Drivers ? Status Change Log 10/28/2013 - present |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2013-11-20T20:45:03Z |
| Publication Date | 2013-11-20T20:57:45Z |

## Description

This list contains information on changes in status to current medallion drivers and their corresponding record history starting from 10/28/2013 (inclusive). Historical information from 03/07/2013 ? 01/04/2014 can be found at https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/n776-dsqy. The most recently published active medallion drivers list can be found at https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/jb3k-j3gp

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | license_number    | License Number    | text          | text          |
| Yes      | series tag     | name              | Name              | text          | text          |
| Yes      | series tag     | type              | Type              | text          | text          |
| No       |                | expiration_date   | Expiration Date   | text          | text          |
| Yes      | time           | last_updated_date | Last Updated Date | calendar_date | calendar_date |
| No       |                | last_updated_time | Last Updated Time | text          | text          |
| Yes      | series tag     | active_flag       | Active_Flag       | text          | text          |
| Yes      | numeric metric | row_wid           | Row_Wid           | number        | number        |
```

## Time Field

```ls
Value = last_updated_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_updated_time,expiration_date
```

## Data Commands

```ls
series e:sjfe-fppp d:2015-06-13T00:00:00.000Z t:license_number=462410 t:name=LEE,YUET,C t:type="MEDALLION TAXI DRIVER" t:active_flag=N m:row_wid=108

series e:sjfe-fppp d:2015-06-13T00:00:00.000Z t:license_number=476616 t:name=SINGH,DEVINDER t:type="MEDALLION TAXI DRIVER" t:active_flag=N m:row_wid=147

series e:sjfe-fppp d:2015-06-13T00:00:00.000Z t:license_number=476810 t:name=SINGH,BALWANT t:type="MEDALLION TAXI DRIVER" t:active_flag=N m:row_wid=264
```

## Meta Commands

```ls
metric m:row_wid p:integer l:Row_Wid t:dataTypeName=number

entity e:sjfe-fppp l:"Medallion Drivers ? Status Change Log 10/28/2013 - present" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/sjfe-fppp

property e:sjfe-fppp t:meta.view v:id=sjfe-fppp v:category=Transportation v:averageRating=0 v:name="Medallion Drivers ? Status Change Log 10/28/2013 - present" v:attribution="Taxi and Limousine Commission (TLC)"

property e:sjfe-fppp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sjfe-fppp t:meta.view.tableauthor v:id=ew5s-ts2p v:screenName=Venkat v:displayName=Venkat
```

## Top Records

```ls
| license_number | name             | type                  | expiration_date | last_updated_date   | last_updated_time | active_flag | row_wid | 
| ============== | ================ | ===================== | =============== | =================== | ================= | =========== | ======= | 
| 462410         | LEE,YUET,C       | MEDALLION TAXI DRIVER | 06/14/2015      | 2015-06-13T00:00:00 | 13:20             | N           | 108     | 
| 476616         | SINGH,DEVINDER   | MEDALLION TAXI DRIVER | 06/14/2015      | 2015-06-13T00:00:00 | 13:20             | N           | 147     | 
| 476810         | SINGH,BALWANT    | MEDALLION TAXI DRIVER | 06/22/2015      | 2015-06-13T00:00:00 | 13:20             | N           | 264     | 
| 462265         | ALEXANDRE,FRANTZ | MEDALLION TAXI DRIVER | 05/25/2014      | 2014-05-24T00:00:00 | 13:20             | N           | 32      | 
| 455160         | DEOL,GURVINDER,S | MEDALLION TAXI DRIVER | 06/12/2015      | 2015-06-10T00:00:00 | 13:20             | N           | 213     | 
| 462384         | SAINI,JAGDISH,R  | MEDALLION TAXI DRIVER | 05/07/2015      | 2015-04-20T00:00:00 | 13:20             | N           | 121     | 
| 501279         | OSMAN,MUHAMMAD,S | MEDALLION TAXI DRIVER | 07/07/2015      | 2015-06-23T00:00:00 | 13:20             | N           | 273     | 
| 500901         | KHAN,MUHAMMAD,A  | MEDALLION TAXI DRIVER | 07/23/2015      | 2015-07-14T00:00:00 | 13:20             | N           | 280     | 
| 484935         | IMRAN,MOHAMED    | MEDALLION TAXI DRIVER | 09/02/2015      | 2015-02-21T00:00:00 | 13:20             | N           | 4692    | 
| 491051         | AHMED,HELAL      | MEDALLION TAXI DRIVER | 11/12/2015      | 2015-10-26T00:00:00 | 13:20             | N           | 6456    | 
```