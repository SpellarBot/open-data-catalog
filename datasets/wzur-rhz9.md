# TLC Driver Education 24 Hour Course Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-driver-education-24-hour-course-providers) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wzur-rhz9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wzur-rhz9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wzur-rhz9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wzur-rhz9 |
| Name | TLC Driver Education 24 Hour Course Providers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, driver, education, course |
| Created | 2016-10-20T17:23:38Z |
| Publication Date | 2017-04-14T20:28:23Z |

## Description

TLC Driver License applicants must complete a 24 hour TLC Driver Education Course and pass an 80-question multiple choice exam on a computer with a grade of 70% or higher (you must answer 56 out of 80 questions correctly in order to pass). The course covers the following topics: TLC rules and regulations; geography; safe driving skills; traffic rules; and customer service.

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
series e:wzur-rhz9 d:2017-04-14T00:00:00.000Z t:languagesoffered="English, Spanish" t:time=16:14:41 t:schoolname="DTA Driver Training Associates - ????" t:suiteapt="Suite 1b" t:email=info@dtadirect.com t:zipcode=11355 t:state=NY t:web=http://www.dtadirect.com t:buildingnumber=132-49 t:telephone="(718) 886-6249" t:streetname="41st Road" t:city=Flushing m:examprice=75 m:courseprice=175

series e:wzur-rhz9 d:2017-04-14T00:00:00.000Z t:languagesoffered="English, Russian, Spanish" t:time=16:14:41 t:schoolname="Abba Training School" t:zipcode=11210 t:state=NY t:web=http://www.training4tlc.com t:buildingnumber=4301 t:telephone="(347) 829-2999" t:streetname="Glenwood Road" t:city=Brooklyn m:examprice=75 m:courseprice=175

series e:wzur-rhz9 d:2017-04-14T00:00:00.000Z t:languagesoffered="English, Mandarin, Spanish" t:time=16:14:41 t:schoolname="Abba Training School" t:suiteapt="Suite D.E." t:zipcode=10467 t:state=NY t:web=http://www.training4tlc.com t:buildingnumber=2250 t:telephone="(347) 622-1111" t:streetname="Boston Road" t:city=Bronx m:examprice=75 m:courseprice=175
```

## Meta Commands

```ls
metric m:courseprice p:long l:CoursePrice d:"The price of the course" t:dataTypeName=money

metric m:examprice p:long l:ExamPrice d:"The price of the exam" t:dataTypeName=money

entity e:wzur-rhz9 l:"TLC Driver Education 24 Hour Course Providers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/wzur-rhz9

property e:wzur-rhz9 t:meta.view v:id=wzur-rhz9 v:category=Transportation v:averageRating=0 v:name="TLC Driver Education 24 Hour Course Providers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:wzur-rhz9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wzur-rhz9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| schoolname                            | buildingnumber | streetname         | suiteapt            | city             | state | zipcode | latitude  | longitude  | contact       | telephone      | email                            | web                                        | languagesoffered                | courseprice | examprice | date                | time     | 
| ===================================== | ============== | ================== | =================== | ================ | ===== | ======= | ========= | ========== | ============= | ============== | ================================ | ========================================== | =============================== | =========== | ========= | =================== | ======== | 
| DTA Driver Training Associates - ???? | 132-49         | 41st Road          | Suite 1b            | Flushing         | NY    | 11355   | 40.756212 | -73.831919 |               | (718) 886-6249 | info@dtadirect.com               | [http://www.dtadirect.com, null]           | English, Spanish                | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| Advance Mobility Plus                 | 847            | East 43rd Street   |                     | Brooklyn         | NY    | 11210   | 40.634363 | -73.935172 | Jeff Grobman  | (718) 253-1212 | advancemobilityplus@gmail.com    | [http://www.advancemobilityplus.com, null] | English, Russian, Urdu          |             |           | 2017-04-14T00:00:00 | 16:14:41 | 
| Advance Mobility Plus                 | 3250           | Westchester Avenue | Suite 205           | Bronx            | NY    | 10461   | 40.851991 | -73.828319 | Brian Grobman | (718) 684-4889 | advancemobilityofbronx@gmail.com | [http://www.advancemobilityplus.com, null] | English                         |             |           | 2017-04-14T00:00:00 | 16:14:41 | 
| Abba Training School                  | 4301           | Glenwood Road      |                     | Brooklyn         | NY    | 11210   | 40.635028 | -73.935002 |               | (347) 829-2999 |                                  | [http://www.training4tlc.com, null]        | English, Russian, Spanish       | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| Abba Training School                  | 2250           | Boston Road        | Suite D.E.          | Bronx            | NY    | 10467   | 40.859032 | -73.867547 |               | (347) 622-1111 |                                  | [http://www.training4tlc.com, null]        | English, Mandarin, Spanish      | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| American Master Cabbie Taxi Academy   | 24-29          | Jackson Avenue     |                     | Long Island City | NY    | 11101   | 40.746598 | -73.944532 | Terry Gelber  | (718) 472-1699 |                                  | [http://www.mastercabbie.com, null]        | English, Spanish, Bengali       | $174        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| American Master Cabbie Taxi Academy   | 391            | East 149th Street  |                     | Bronx            | NY    | 10455   | 40.816422 | -73.91812  | Terry Gelber  | (347) 590-2220 |                                  | [http://www.mastercabbie.com, null]        | English, Spanish, Bengali       | $174        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| Goog Transportation Education Academy | 150-51         | 14th Avenue        | Unit A, Lower Level | Whiestone        | NY    | 11357   | 40.789361 | -73.812129 | Nawaz Amad    | 718) 746-4400  | info@googeducation.com           | [http://www.googeducation.com, null]       | English, Spanish, Urdu          | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| HANAC NYC Taxi Academy                | 33-24          | Northern Boulevard | 4th Floor           | Long Island City | NY    | 11101   | 40.751777 | -73.930235 | Hasain Shakil | (718) 433-0439 |                                  | [http://www.hanactaxi.com, null]           | English, Spanish, Bengali, Urdu | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
| HANAC NYC Taxi Academy                | 35-01          | Queens Boulevard   | Ground Floor        | Long Island City | NY    | 11101   | 40.744818 | -73.929438 | Hasain Shakil | (718) 709-1990 |                                  | [http://www.hanactaxi.com, null]           | English, Spanish, Bengali, Urdu | $175        | $75       | 2017-04-14T00:00:00 | 16:14:41 | 
```