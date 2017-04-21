# Medallion Drivers - Active

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-drivers-active-6f778) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jb3k-j3gp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jb3k-j3gp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jb3k-j3gp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jb3k-j3gp |
| Name | Medallion Drivers - Active |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2013-12-26T19:23:30Z |
| Publication Date | 2017-04-20T20:27:37Z |

## Description

This list contains the most recently published active  medallion drivers list. This is a list of licensees who are currently authorized to operate NYC TLC licensed Taxicabs. The old data set is no longer being updated but can be accessed from the link given below to access data from 03/07/2013 through 01/04/2014 https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/n776-dsqy. A new Change Log containing changes in status from 10/28/2013 onwards can be found at https://data.cityofnewyork.us/Transportation/TLC-MEDALLION-ACTIVE-Historical-Data/sjfe-fppp. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | license_number    | License Number    | text          | text          |
| Yes      | series tag  | name              | Name              | text          | text          |
| Yes      | series tag  | type              | Type              | text          | text          |
| Yes      | time        | expiration_date   | Expiration Date   | calendar_date | calendar_date |
| No       |             | last_updated_date | Last Date Updated | calendar_date | calendar_date |
| No       |             | last_updated_time | Last Time Updated | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_updated_date,last_updated_time
```

## Data Commands

```ls
series e:jb3k-j3gp d:2020-01-20T00:00:00.000Z t:license_number=499042 t:name=AHMAD,SHAHID t:type="MEDALLION TAXI DRIVER" m:row_number.jb3k-j3gp=1

series e:jb3k-j3gp d:2020-03-12T00:00:00.000Z t:license_number=499046 t:name=ISLAM,MOHAMMAD,R t:type="MEDALLION TAXI DRIVER" m:row_number.jb3k-j3gp=2

series e:jb3k-j3gp d:2019-03-22T00:00:00.000Z t:license_number=499121 t:name=KOITA,BOUBOU,G t:type="MEDALLION TAXI DRIVER" m:row_number.jb3k-j3gp=3
```

## Meta Commands

```ls
metric m:row_number.jb3k-j3gp p:long l:"Row Number"

entity e:jb3k-j3gp l:"Medallion Drivers - Active" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/jb3k-j3gp

property e:jb3k-j3gp t:meta.view v:id=jb3k-j3gp v:category=Transportation v:averageRating=0 v:name="Medallion Drivers - Active" v:attribution="Taxi and Limousine Commission (TLC)"

property e:jb3k-j3gp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jb3k-j3gp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name               | type                  | expiration_date     | last_updated_date   | last_updated_time | 
| ============== | ================== | ===================== | =================== | =================== | ================= | 
| 499042         | AHMAD,SHAHID       | MEDALLION TAXI DRIVER | 2020-01-20T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 499046         | ISLAM,MOHAMMAD,R   | MEDALLION TAXI DRIVER | 2020-03-12T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 499121         | KOITA,BOUBOU,G     | MEDALLION TAXI DRIVER | 2019-03-22T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 499159         | ELHABIBI,SAMIR     | MEDALLION TAXI DRIVER | 2019-03-28T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 697731         | PEREYRA,JOSE,A     | MEDALLION TAXI DRIVER | 2019-05-28T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 697707         | GUERRERO,JACINTO,H | MEDALLION TAXI DRIVER | 2019-07-19T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 662222         | CONCEPCION,GERMAN  | MEDALLION TAXI DRIVER | 2020-03-03T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 662515         | VOLODARSKY,BORIS   | MEDALLION TAXI DRIVER | 2018-03-09T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 662753         | RAMOS,LEONARDO     | MEDALLION TAXI DRIVER | 2019-03-16T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
| 497856         | PARFAIT,CLAUDE     | MEDALLION TAXI DRIVER | 2020-03-12T00:00:00 | 2017-04-20T00:00:00 | 13:20             | 
```