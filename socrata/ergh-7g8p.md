# 2012 APD Crash Fatality Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-apd-crash-fatality-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ergh-7g8p) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ergh-7g8p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ergh-7g8p/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ergh-7g8p |
| Name | 2012 APD Crash Fatality Data |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | traffic, crash, apd, police, fatality, 2012 |
| Created | 2013-05-21T15:19:15Z |
| Publication Date | 2013-05-21T15:22:54Z |

## Description

1. The data provided is for informational use only and is not considered official APD crime data as in official Texas DPS or FBI crime reports.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | roadofaccident | RoadofAccident | text          | text          |
| Yes      | time        | date           | Date           | calendar_date | calendar_date |
| Yes      | series tag  | day            | Day            | text          | text          |
| Yes      | series tag  | time           | Time           | text          | text          |
| Yes      | series tag  | type           | Type           | text          | text          |
| Yes      | series tag  | who_died       | WHO DIED       | text          | text          |
| Yes      | series tag  | type_of_road   | TYPE OF ROAD   | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ergh-7g8p d:2012-01-01T00:00:00.000Z t:roadofaccident="9600 S IH 35 NB" t:time=5:07:00 t:who_died=Pedestrian t:day=SUN t:type=MV/PED t:type_of_road=IH35 m:row_number.ergh-7g8p=1

series e:ergh-7g8p d:2012-01-02T00:00:00.000Z t:roadofaccident="6700 S PLEASANT VALLEY RD" t:time=2:00:00 t:who_died="Driver Unit 1" t:day=MON t:type=MV/FO t:type_of_road="Local Street" m:row_number.ergh-7g8p=2

series e:ergh-7g8p d:2012-01-10T00:00:00.000Z t:roadofaccident="1300 W WELLS BRANCH PKWY" t:time=18:55:00 t:who_died=Pedestrian t:day=TUE t:type=MV/PED t:type_of_road="Local Street" m:row_number.ergh-7g8p=3
```

## Meta Commands

```ls
metric m:row_number.ergh-7g8p p:long l:"Row Number"

entity e:ergh-7g8p l:"2012 APD Crash Fatality Data" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/ergh-7g8p

property e:ergh-7g8p t:meta.view v:id=ergh-7g8p v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="2012 APD Crash Fatality Data" v:attribution="City of Austin"

property e:ergh-7g8p t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:ergh-7g8p t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| roadofaccident             | date                | day | time     | type   | who_died                      | type_of_road                   | 
| ========================== | =================== | === | ======== | ====== | ============================= | ============================== | 
| 9600 S IH 35 NB            | 2012-01-01T00:00:00 | SUN | 5:07:00  | MV/PED | Pedestrian                    | IH35                           | 
| 6700 S PLEASANT VALLEY RD  | 2012-01-02T00:00:00 | MON | 2:00:00  | MV/FO  | Driver Unit 1                 | Local Street                   | 
| 1300 W WELLS BRANCH PKWY   | 2012-01-10T00:00:00 | TUE | 18:55:00 | MV/PED | Pedestrian                    | Local Street                   | 
| 12600 BLK N US 183 NB SVRD | 2012-01-23T00:00:00 | SUN | 22:26:00 | MV/BI  | Bicyclist                     | High Speed Roadway (not IH 35) | 
| 3700 OAK SPRINGS DR        | 2012-01-27T00:00:00 | THU | 21:11:00 | MV/MC  | Motorcyclist (scooter) Unit 2 | Local Street                   | 
| JOLLYVILLE RD @ BRAKER     | 2012-01-30T00:00:00 | MON | 18:41:00 | MV/PED | Pedestrian                    | Local Street                   | 
| 13200 BLK N. SH 45 W WB    | 2012-02-04T00:00:00 | SAT | 16:52:00 | MV/MC  | Motorcyclist Unit 1           | High Speed Roadway (not IH 35) | 
| 5500 BLK SHOAL CREEK BLVD  | 2012-02-05T00:00:00 | SUN | 2:45:00  | MV/FO  | Driver                        | Local Street                   | 
| 3100 BLK GUADALUPE ST      | 2012-02-19T00:00:00 | SUN | 19:03:00 | MV/PED | Pedestrian                    | Local Street                   | 
| 9500 BLK N MOPAC EXPY NB   | 2012-02-19T00:00:00 | SUN | 20:27:00 | MV/PED | Pedestrian                    | High Speed Roadway (not IH 35) | 
```