# Film Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/film-permits) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tg4x-b46p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tg4x-b46p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tg4x-b46p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tg4x-b46p |
| Name | Film Permits |
| Attribution | Mayor?s Office of Media and Entertainment (MOME) |
| Category | City Government |
| Tags | mome, film, permits |
| Created | 2015-07-27T16:07:21Z |
| Publication Date | 2016-04-21T16:26:56Z |

## Description

Permits are generally required when asserting the exclusive use of city property, like a sidewalk, a street, or a park. See http://www1.nyc.gov/site/mome/permits/when-permit-required.page

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type     | Render Type   |
| ======== | =========== | ================ | ================= | ============= | ============= |
| Yes      | series tag  | eventid          | EventID           | text          | number        |
| Yes      | series tag  | eventtype        | EventType         | text          | text          |
| Yes      | time        | startdatetime    | StartDateTime     | calendar_date | calendar_date |
| No       |             | enddatetime      | EndDateTime       | calendar_date | calendar_date |
| No       |             | enteredon        | EnteredOn         | calendar_date | calendar_date |
| Yes      | series tag  | eventagency      | EventAgency       | text          | text          |
| Yes      | series tag  | parkingheld      | ParkingHeld       | text          | text          |
| Yes      | series tag  | borough          | Borough           | text          | text          |
| Yes      | series tag  | communityboard_s | CommunityBoard(s) | text          | text          |
| Yes      | series tag  | policeprecinct_s | PolicePrecinct(s) | text          | text          |
| Yes      | series tag  | category         | Category          | text          | text          |
| Yes      | series tag  | subcategoryname  | SubCategoryName   | text          | text          |
| Yes      | series tag  | country          | Country           | text          | text          |
| Yes      | series tag  | zipcode_s        | ZipCode(s)        | text          | text          |
```

## Time Field

```ls
Value = startdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddatetime,enteredon
```

## Data Commands

```ls
series e:tg4x-b46p d:2016-07-18T06:00:00.000Z t:zipcode_s=10023 t:category=Television t:subcategoryname="Morning Show" t:communityboard_s=7 t:parkingheld="COLUMBUS AVENUE between WEST   67 STREET and WEST   66 STREET" t:borough=Manhattan t:policeprecinct_s=20 t:eventid=300134 t:eventagency="Mayor's Office of Film, Theatre & Broadcasting" t:eventtype="Shooting Permit" t:country="United States of America" m:row_number.tg4x-b46p=1

series e:tg4x-b46p d:2016-07-18T07:00:00.000Z t:zipcode_s=11101 t:category=Television t:subcategoryname=Cable-episodic t:communityboard_s=2 t:parkingheld="22 STREET between QUEENS PLAZA SOUTH and 43 AVENUE,  21 STREET between QUEENS PLAZA SOUTH and 43 AVENUE,  QUEENS PLAZA SOUTH between 21 STREET and 22 STREET,  QUEENS PLAZA SOUTH between 21 STREET and 22 STREET" t:borough=Queens t:policeprecinct_s=108 t:eventid=299797 t:eventagency="Mayor's Office of Film, Theatre & Broadcasting" t:eventtype="Shooting Permit" t:country="United States of America" m:row_number.tg4x-b46p=2

series e:tg4x-b46p d:2016-07-18T07:00:00.000Z t:zipcode_s="11101, 11222, 11378" t:category=Television t:subcategoryname="Episodic series" t:communityboard_s="1, 2" t:parkingheld="MONITOR STREET between NORMAN AVENUE and GREENPOINT AVENUE,  KINGSLAND AVENUE between GREENPOINT AVENUE and NORMAN AVENUE,  GREENPOINT AVENUE between STARR AVENUE and BRADLEY AVENUE,  LAUREL HILL BOULEVARD between 56 ROAD and 54 AVENUE,  GREENPOINT AVENUE between GALE AVENUE and BORDEN AVENUE" t:borough=Queens t:policeprecinct_s="108, 94" t:eventid=300179 t:eventagency="Mayor's Office of Film, Theatre & Broadcasting" t:eventtype="Shooting Permit" t:country="United States of America" m:row_number.tg4x-b46p=3
```

## Meta Commands

```ls
metric m:row_number.tg4x-b46p p:long l:"Row Number"

entity e:tg4x-b46p l:"Film Permits" t:attribution="Mayor?s Office of Media and Entertainment (MOME)" t:url=https://data.cityofnewyork.us/api/views/tg4x-b46p

property e:tg4x-b46p t:meta.view v:id=tg4x-b46p v:category="City Government" v:averageRating=0 v:name="Film Permits" v:attribution="Mayor?s Office of Media and Entertainment (MOME)"

property e:tg4x-b46p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tg4x-b46p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| eventid | eventtype                     | startdatetime       | enddatetime         | enteredon           | eventagency                                    | parkingheld                                                                                                                                                                                                                                                                                       | borough   | communityboard_s | policeprecinct_s | category   | subcategoryname | country                  | zipcode_s           | 
| ======= | ============================= | =================== | =================== | =================== | ============================================== | ================================================================================================================================================================================================================================================================================================= | ========= | ================ | ================ | ========== | =============== | ======================== | =================== | 
| 300134  | Shooting Permit               | 2016-07-18T06:00:00 | 2016-07-18T12:00:00 | 2016-07-13T10:28:02 | Mayor's Office of Film, Theatre & Broadcasting | COLUMBUS AVENUE between WEST 67 STREET and WEST 66 STREET                                                                                                                                                                                                                                         | Manhattan | 7                | 20               | Television | Morning Show    | United States of America | 10023               | 
| 299797  | Shooting Permit               | 2016-07-18T07:00:00 | 2016-07-18T19:00:00 | 2016-07-11T18:49:08 | Mayor's Office of Film, Theatre & Broadcasting | 22 STREET between QUEENS PLAZA SOUTH and 43 AVENUE, 21 STREET between QUEENS PLAZA SOUTH and 43 AVENUE, QUEENS PLAZA SOUTH between 21 STREET and 22 STREET, QUEENS PLAZA SOUTH between 21 STREET and 22 STREET                                                                                    | Queens    | 2                | 108              | Television | Cable-episodic  | United States of America | 11101               | 
| 300179  | Shooting Permit               | 2016-07-18T07:00:00 | 2016-07-18T22:00:00 | 2016-07-13T12:11:19 | Mayor's Office of Film, Theatre & Broadcasting | MONITOR STREET between NORMAN AVENUE and GREENPOINT AVENUE, KINGSLAND AVENUE between GREENPOINT AVENUE and NORMAN AVENUE, GREENPOINT AVENUE between STARR AVENUE and BRADLEY AVENUE, LAUREL HILL BOULEVARD between 56 ROAD and 54 AVENUE, GREENPOINT AVENUE between GALE AVENUE and BORDEN AVENUE | Queens    | 1, 2             | 108, 94          | Television | Episodic series | United States of America | 11101, 11222, 11378 | 
| 300630  | Shooting Permit               | 2016-07-18T12:00:00 | 2016-07-18T21:00:00 | 2016-07-14T22:13:56 | Mayor's Office of Film, Theatre & Broadcasting | ROCKAWAY BEACH BOULEVARD between BEACH 69 STREET and BEACH 67 STREET                                                                                                                                                                                                                              | Queens    | 14               | 100              | Commercial | Commercial      | United States of America | 11692               | 
| 300127  | Shooting Permit               | 2016-07-18T06:00:00 | 2016-07-18T23:59:00 | 2016-07-13T10:04:20 | Mayor's Office of Film, Theatre & Broadcasting | 10 AVENUE between WEST 26 STREET and WEST 27 STREET, WEST 27 STREET between 10 AVENUE and 11 AVENUE                                                                                                                                                                                               | Manhattan | 4                | 10               | Television | Reality         | United States of America | 10001               | 
| 43547   | Shooting Permit               | 2012-01-10T07:00:00 | 2012-01-10T19:00:00 | 2012-01-04T12:25:37 | Mayor's Office of Film, Theatre & Broadcasting | EAGLE STREET between FRANKLIN STREET and WEST STREET, WEST STREET between EAGLE STREET and FREEMAN STREET, FREEMAN STREET between WEST STREET and FRANKLIN STREET                                                                                                                                 | Brooklyn  | 1, 2             | 108, 94          | Television | Episodic series | United States of America | 11101, 11222        | 
| 300435  | Shooting Permit               | 2016-07-18T07:00:00 | 2016-07-18T21:00:00 | 2016-07-14T11:24:19 | Mayor's Office of Film, Theatre & Broadcasting | KINGSLAND AVENUE between KINGSLAND AVENUE FORK and DEAD END, KINGSLAND AVENUE between GREENPOINT AVENUE and NORTH HENRY STREET                                                                                                                                                                    | Brooklyn  | 1                | 94               | Television | Episodic series | United States of America | 11222               | 
| 300417  | Shooting Permit               | 2016-07-18T06:00:00 | 2016-07-18T22:00:00 | 2016-07-14T10:35:52 | Mayor's Office of Film, Theatre & Broadcasting | STARR AVENUE between BORDEN AVENUE and VAN DAM STREET, REVIEW AVENUE between 29 STREET and 35 STREET                                                                                                                                                                                              | Queens    | 2                | 108              | Television | Episodic series | United States of America | 11101               | 
| 300441  | Shooting Permit               | 2016-07-18T09:30:00 | 2016-07-18T23:00:00 | 2016-07-14T11:45:04 | Mayor's Office of Film, Theatre & Broadcasting | WESTMINSTER ROAD between ALBEMARLE ROAD and CHURCH AVENUE, WESTMINSTER ROAD between CHURCH AVENUE and CATON AVENUE                                                                                                                                                                                | Brooklyn  | 14               | 70               | WEB        | Not Applicable  | United States of America | 11218               | 
| 300122  | Theater Load in and Load Outs | 2016-07-18T00:01:00 | 2016-07-20T06:00:00 | 2016-07-13T09:20:31 | Mayor's Office of Film, Theatre & Broadcasting | WEST 126 STREET between ADAM CLAYTON POWELL BOULEVARD and FREDERICK DOUGLAS BOULEVARD                                                                                                                                                                                                             | Manhattan | 10               | 28               | Theater    | Theater         | United States of America | 10027               | 
```