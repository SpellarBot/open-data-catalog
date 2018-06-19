# TLC authorized Behind the Wheel Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-authorized-behind-the-wheel-providers) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/auuc-fqzi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/auuc-fqzi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/auuc-fqzi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | auuc-fqzi |
| Name | TLC authorized Behind the Wheel Providers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, provider, education, training, taxi |
| Created | 2016-10-27T16:48:26Z |
| Publication Date | 2016-12-21T23:49:45Z |

## Description

This list is part of the new TLC driver license (Yellow & Green Taxicab, Livery, Black Car, and Lux Limo) education requirement.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | schoolname       | SchoolName       | text          | text          |
| Yes      | series tag     | buildingnumber   | BuildingNumber   | text          | text          |
| Yes      | series tag     | streetname       | StreetName       | text          | text          |
| Yes      | series tag     | suiteapt         | SuiteApt         | text          | text          |
| Yes      | series tag     | city             | City             | text          | text          |
| Yes      | series tag     | state            | State            | text          | text          |
| Yes      | series tag     | zipcode          | ZipCode          | text          | text          |
| No       |                | latitude         | Latitude         | number        | text          |
| No       |                | longitude        | Longitude        | number        | text          |
| Yes      | series tag     | contact          | Contact          | text          | text          |
| Yes      | series tag     | telephone        | Telephone        | text          | text          |
| Yes      | series tag     | email            | Email            | email         | email         |
| Yes      | series tag     | web              | Web              | url           | url           |
| Yes      | series tag     | languagesoffered | LanguagesOffered | text          | text          |
| Yes      | numeric metric | courseprice      | CoursePrice      | money         | text          |
| Yes      | numeric metric | examprice        | ExamPrice        | money         | text          |
| Yes      | time           | date             | date             | calendar_date | calendar_date |
| Yes      | series tag     | time             | time             | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:auuc-fqzi d:2016-12-21T00:00:00.000Z t:languagesoffered="English, Spanish, Bengali, Urdu" t:time=18:44:02 t:schoolname="HANAC NYC Taxi Academy" t:suiteapt="4th Floor" t:zipcode=11101 t:state=NY t:web=http://www.hanactaxi.com t:buildingnumber=33-24 t:telephone="(718) 433-0439" t:contact="Hasain Shakil" t:streetname="Northern Boulevard" t:city="Long Island City" m:examprice=75 m:courseprice=175
```

## Meta Commands

```ls
metric m:courseprice p:long l:CoursePrice d:"The price of the course" t:dataTypeName=money

metric m:examprice p:long l:ExamPrice d:"The price of the exam" t:dataTypeName=money

entity e:auuc-fqzi l:"TLC authorized Behind the Wheel Providers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/auuc-fqzi

property e:auuc-fqzi t:meta.view v:id=auuc-fqzi v:category=Transportation v:averageRating=0 v:name="TLC authorized Behind the Wheel Providers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:auuc-fqzi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:auuc-fqzi t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| schoolname                          | buildingnumber | streetname         | suiteapt  | city             | state | zipcode | latitude  | longitude  | contact       | telephone      | email | web                                 | languagesoffered                | courseprice | examprice | date                | time     | 
| =================================== | ============== | ================== | ========= | ================ | ===== | ======= | ========= | ========== | ============= | ============== | ===== | =================================== | =============================== | =========== | ========= | =================== | ======== | 
| HANAC NYC Taxi Academy              | 33-24          | Northern Boulevard | 4th Floor | Long Island City | NY    | 11101   | 40.751777 | -73.930235 | Hasain Shakil | (718) 433-0439 |       | [http://www.hanactaxi.com, null]    | English, Spanish, Bengali, Urdu | $175        | $75       | 2016-12-21T00:00:00 | 18:44:02 | 
| American Master Cabbie Taxi Academy | 24-29          | Jackson Avenue     |           | Long Island City | NY    | 11101   | 40.746598 | -73.944532 | Terry Gelber  | (718) 472-1699 |       | [http://www.mastercabbie.com, null] |                                 |             |           | 2016-12-21T00:00:00 | 18:44:02 | 
```