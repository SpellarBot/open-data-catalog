# TLC authorized Wheelchair Passenger Assistance Training Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-authorized-wheelchair-passenger-assistance-training-providers) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ayeb-p4mv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ayeb-p4mv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ayeb-p4mv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ayeb-p4mv |
| Name | TLC authorized Wheelchair Passenger Assistance Training Providers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, taxi, wheelchair, requirement, training, provider |
| Created | 2016-10-27T16:48:17Z |
| Publication Date | 2017-04-14T20:37:03Z |

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
| Yes      | numeric metric | courseprice      | CoursePrice      | money         | money         |
| Yes      | numeric metric | examprice        | ExamPrice        | money         | money         |
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
```

## Meta Commands

```ls
metric m:courseprice p:double l:CoursePrice d:"The price of the course" t:dataTypeName=money

metric m:examprice p:double l:ExamPrice d:"The price of the exam" t:dataTypeName=money

entity e:ayeb-p4mv l:"TLC authorized Wheelchair Passenger Assistance Training Providers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/ayeb-p4mv

property e:ayeb-p4mv t:meta.view v:id=ayeb-p4mv v:category=Transportation v:averageRating=0 v:name="TLC authorized Wheelchair Passenger Assistance Training Providers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:ayeb-p4mv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ayeb-p4mv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| schoolname                                | buildingnumber | streetname         | suiteapt   | city             | state | zipcode | latitude  | longitude  | contact          | telephone      | email                            | web                                        | languagesoffered | courseprice | examprice | date                | time     | 
| ========================================= | ============== | ================== | ========== | ================ | ===== | ======= | ========= | ========== | ================ | ============== | ================================ | ========================================== | ================ | =========== | ========= | =================== | ======== | 
| AAA DTA Driver Training Associates - ???? | 132-49         | 41st Road          | Suite 1b   | Flushing         | NY    | 11355   | 40.756224 | -73.831928 |                  | (718) 886-6249 | info@dtadirect.com               | [http://www.dtadirect.com, null]           |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Abba Training School                      | 4301           | Glenwood Road      |            | Brooklyn         | NY    | 11210   | 40.635028 | -73.935002 |                  | (347) 829-2999 |                                  | [http://www.training4tlc.com, null]        |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Abba Training School                      | 2250           | Boston Road        | Suite D.E. | Bronx            | NY    | 10467   | 40.859032 | -73.867547 |                  | (347) 622-1111 |                                  | [http://www.training4tlc.com, null]        |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Advance Mobility Plus                     | 847            | East 43rd Street   |            | Brooklyn         | NY    | 11210   | 40.634363 | -73.935172 | Jeff Grobman     | (718) 253-1212 | advancemobilityplus@gmail.com    | [http://www.advancemobilityplus.com, null] |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Advance Mobility Plus                     | 3250           | Westchester Ave    | Suite 2015 | Bronx            | NY    | 10461   | 40.851991 | -73.828319 | Brian Grobman    | (718) 684-4889 | advancemobilityplus@gmail.com    | [http://www.advancemobilityplus.com, null] |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| American Master Cabbie Taxi Academy       | 24-29          | Jackson Avenue     |            | Long Island City | NY    | 11101   | 40.746598 | -73.944532 | Terry Gelber     | (718) 472-1699 |                                  | [http://www.mastercabbie.com, null]        |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| American Master Cabbie Taxi Academy       | 391            | East 149th Street  |            | Bronx            | NY    | 10455   | 40.816422 | -73.91812  | Terry Gelber     | (347) 590-2220 |                                  | [http://www.mastercabbie.com, null]        |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Bussani Mobility Team                     | 19-54          | Jerome Ave         |            | Bronx            | NY    | 10453   | 40.851797 | -73.909214 | Pavel Lopez      | (718) 733-1220 |                                  | [http://www.bronxtaxischool.com, null]     |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Easter Seals of New York/FEDCAP           | 20             | 1 East 43rd Street | 3rd Floor  | New York         | NY    | 10017   | 40.753637 | -73.979182 |                  | (877) 369-0940 |                                  | [http://www.fedcap.org/wavtraining, null]  |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
| Fleet Radio Leasing                       | 712            | 3rd Avenue         |            | Brooklyn         | NY    | 11232   | 40.663353 | -73.998939 | Gavriel Gavrilov | (718) 514-6500 | gavriel@nextcenturyinsurance.com | [http://www.cabclass.com, null]            |                  |             |           | 2017-04-14T00:00:00 | 16:16:53 | 
```