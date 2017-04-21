# Medallion Drivers Historical Archive 3/7/2013 -1/4/2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-drivers-historical-archive-3-7-2013-1-4-2014-ff2e1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/n776-dsqy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/n776-dsqy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/n776-dsqy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | n776-dsqy |
| Name | Medallion Drivers Historical Archive 3/7/2013 -1/4/2014 |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2013-03-01T19:08:59Z |
| Publication Date | 2013-09-05T19:58:05Z |

## Description

This list contains information on the status of current medallion drivers who were authorized to operate NYC TLC licensed Taxicabs from 03/07/2013 through 01/04/2014. The new data set which lists the current day?s snapshot of medallion drivers can be accessed from the link given below https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/jb3k-j3gp

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | license_number    | License Number    | text          | text          |
| Yes      | series tag  | name              | Name              | text          | text          |
| Yes      | series tag  | type              | Type              | text          | text          |
| Yes      | time        | expiration_date   | Expiration Date   | calendar_date | calendar_date |
| No       |             | last_updated_date | Last Updated Date | calendar_date | calendar_date |
| No       |             | last_updated_time | Last Updated Time | text          | text          |
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
series e:n776-dsqy d:2014-11-06T00:00:00.000Z t:license_number=490930 t:name=LASSANA,TIENE t:type="MEDALLION TAXI DRIVER" m:row_number.n776-dsqy=1

series e:n776-dsqy d:2015-08-15T00:00:00.000Z t:license_number=471415 t:name=NADANKANNU,GOKULADAS t:type="MEDALLION TAXI DRIVER" m:row_number.n776-dsqy=2

series e:n776-dsqy d:2015-06-07T00:00:00.000Z t:license_number=476896 t:name=RETTA,GIRMACHEW,W t:type="MEDALLION TAXI DRIVER" m:row_number.n776-dsqy=3
```

## Meta Commands

```ls
metric m:row_number.n776-dsqy p:long l:"Row Number"

entity e:n776-dsqy l:"Medallion Drivers Historical Archive 3/7/2013 -1/4/2014" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/n776-dsqy

property e:n776-dsqy t:meta.view v:id=n776-dsqy v:category=Transportation v:averageRating=0 v:name="Medallion Drivers Historical Archive 3/7/2013 -1/4/2014" v:attribution="Taxi and Limousine Commission (TLC)"

property e:n776-dsqy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:n776-dsqy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                 | type                  | expiration_date     | last_updated_date   | last_updated_time | 
| ============== | ==================== | ===================== | =================== | =================== | ================= | 
| 490930         | LASSANA,TIENE        | MEDALLION TAXI DRIVER | 2014-11-06T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 471415         | NADANKANNU,GOKULADAS | MEDALLION TAXI DRIVER | 2015-08-15T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 476896         | RETTA,GIRMACHEW,W    | MEDALLION TAXI DRIVER | 2015-06-07T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 467426         | ABDUL,GANIYU,G       | MEDALLION TAXI DRIVER | 2015-04-30T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 491867         | AMEYAW,AKWASI        | MEDALLION TAXI DRIVER | 2014-02-24T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 471745         | ATARIWA,RABIOU       | MEDALLION TAXI DRIVER | 2014-02-10T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 419487         | CANTOR,GERALD,A      | MEDALLION TAXI DRIVER | 2014-05-14T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 438925         | SHUAIB,NOORU         | MEDALLION TAXI DRIVER | 2014-04-25T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 469867         | FALLAH,FARAMARZ      | MEDALLION TAXI DRIVER | 2015-08-23T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
| 489188         | VARBANOV,STILIAN     | MEDALLION TAXI DRIVER | 2014-07-11T00:00:00 | 2013-08-15T00:00:00 | 13:20             | 
```