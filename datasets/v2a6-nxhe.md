# Chicago Park District: Movies in the Parks 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-park-district-movies-in-the-parks-2015) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/v2a6-nxhe) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/v2a6-nxhe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/v2a6-nxhe/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | v2a6-nxhe |
| Name | Chicago Park District: Movies in the Parks 2015 |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | movies, parks |
| Created | 2015-05-20T21:20:17Z |
| Publication Date | 2015-05-20T21:33:46Z |

## Description

List of all Movies in the Parks events. This list is a one-time upload and cancellations will not be updated.  Please visit the Chicago Park District website or call the Movies in the Parks hotline at 312-742-1134 to check for cancellations due to weather.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | eventname          | EventName          | text          | text          |
| Yes      | series tag  | moviename          | MovieName          | text          | text          |
| Yes      | series tag  | parkname           | ParkName           | text          | text          |
| Yes      | series tag  | zipcode            | ZipCode            | text          | number        |
| Yes      | series tag  | phone              | Phone              | text          | text          |
| Yes      | time        | startdate          | StartDate          | calendar_date | calendar_date |
| No       |             | enddate            | EndDate            | calendar_date | calendar_date |
| Yes      | series tag  | contactname        | ContactName        | text          | text          |
| Yes      | series tag  | contactemail       | ContactEmail       | email         | email         |
| Yes      | series tag  | eventurl           | EventUrl           | url           | url           |
| Yes      | series tag  | parkurl            | ParkUrl            | url           | url           |
| Yes      | series tag  | community          | Community          | text          | text          |
| Yes      | series tag  | movieclosedcaption | MovieClosedCaption | text          | text          |
| Yes      | series tag  | movierating        | MovieRating        | text          | text          |
```

## Time Field

```ls
Value = startdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddate
```

## Data Commands

```ls
series e:v2a6-nxhe d:2015-09-03T20:00:00.000Z t:parkname="Wicker Park" t:phone="(312) 742-7553" t:parkurl=http://www.chicagoparkdistrict.com/parks/Wicker-Park/ t:moviename="The Final Cut" t:contactname="Claribel ""Clare"" Rodriguez" t:zipcode=60622 t:contactemail=claribel.rodriguez@chicagoparkdistrict.com t:community="West Town" t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Wicker12/ t:movierating=PG-13 t:eventname="Night Out: Movies in the Parks at Wicker" t:movieclosedcaption=Yes m:row_number.v2a6-nxhe=1

series e:v2a6-nxhe d:2015-09-02T20:00:00.000Z t:parkname="Garfield Park Conservatory" t:phone="(773) 638-1766" t:parkurl=http://www.chicagoparkdistrict.com/parks/garfield-park-conservatory/ t:moviename="Ferngully: The Last Rainforest" t:contactname="Mary Eysenbach" t:zipcode=60624 t:community="East Garfield Park" t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Garfield-Conserv1/ t:movierating=G t:eventname="Night Out: Movies in the Parks at Garfield Conserv" t:movieclosedcaption=Yes m:row_number.v2a6-nxhe=2

series e:v2a6-nxhe d:2015-09-02T20:00:00.000Z t:parkname="South Shore Cultural Center" t:phone="(773) 256-0149" t:parkurl=http://www.chicagoparkdistrict.com/parks/South-Shore-Cultural-Center/ t:moviename="Sparkle (1976)" t:contactname="Andrea Adams" t:zipcode=60649 t:contactemail=andrea.adams@chicagopark.com t:community="South Shore" t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-South-Shore11/ t:movierating=PG t:eventname="Night Out: Movies in the Parks at South Shore" t:movieclosedcaption=Yes m:row_number.v2a6-nxhe=3
```

## Meta Commands

```ls
metric m:row_number.v2a6-nxhe p:long l:"Row Number"

entity e:v2a6-nxhe l:"Chicago Park District: Movies in the Parks 2015" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/v2a6-nxhe

property e:v2a6-nxhe t:meta.view v:id=v2a6-nxhe v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/events/movies v:averageRating=0 v:name="Chicago Park District: Movies in the Parks 2015" v:attribution="Chicago Park District"

property e:v2a6-nxhe t:meta.view.owner v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:displayName="CPD IT"

property e:v2a6-nxhe t:meta.view.tableauthor v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:roleName=editor v:displayName="CPD IT"
```

## Top Records

```ls
| eventname                                          | moviename                      | parkname                    | zipcode | phone          | startdate           | enddate             | contactname                              | contactemail                               | eventurl                                                                                              | parkurl                                                                       | community               | movieclosedcaption | movierating | 
| ================================================== | ============================== | =========================== | ======= | ============== | =================== | =================== | ======================================== | ========================================== | ===================================================================================================== | ============================================================================= | ======================= | ================== | =========== | 
| Night Out: Movies in the Parks at Wicker           | The Final Cut                  | Wicker Park                 | 60622   | (312) 742-7553 | 2015-09-03T20:00:00 | 2015-09-03T21:35:00 | Claribel "Clare" Rodriguez               | claribel.rodriguez@chicagoparkdistrict.com | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Wicker12/, null]          | [http://www.chicagoparkdistrict.com/parks/Wicker-Park/, null]                 | West Town               | Yes                | PG-13       | 
| Night Out: Movies in the Parks at Garfield Conserv | Ferngully: The Last Rainforest | Garfield Park Conservatory  | 60624   | (773) 638-1766 | 2015-09-02T20:00:00 | 2015-09-02T21:12:00 | Mary Eysenbach                           |                                            | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Garfield-Conserv1/, null] | [http://www.chicagoparkdistrict.com/parks/garfield-park-conservatory/, null]  | East Garfield Park      | Yes                | G           | 
| Night Out: Movies in the Parks at South Shore      | Sparkle (1976)                 | South Shore Cultural Center | 60649   | (773) 256-0149 | 2015-09-02T20:00:00 | 2015-09-02T21:38:00 | Andrea Adams                             | andrea.adams@chicagopark.com               | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-South-Shore11/, null]     | [http://www.chicagoparkdistrict.com/parks/South-Shore-Cultural-Center/, null] | South Shore             | Yes                | PG          | 
| Night Out: Movies in the Parks at Grant            | Batman Returns                 | Grant Park                  | 60602   | (312) 742-3918 | 2015-08-31T20:00:00 | 2015-08-31T22:06:00 | Jackie Guthrie (Daley Bicentennial Park) | jacqueline.guthrie@chicagoparkdistrict.com | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Grant3/, null]            | [http://www.chicagoparkdistrict.com/parks/grant-park/, null]                  | Loop                    |                    |             | 
| Night Out: Movies in the Parks at Rosenblum        | Maleficent                     | Rosenblum Park              | 60617   | (312) 747-7661 | 2015-08-30T20:00:00 | 2015-08-30T21:37:00 | TBD                                      |                                            | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Rosenblum/, null]         | [http://www.chicagoparkdistrict.com/parks/Rosenblum-Park/, null]              | South Chicago           | Yes                | PG          | 
| Night Out: Movies in the Parks at La Villita       | Rio 2                          | La Villita Park             | 60608   | 312-746-5962   | 2015-08-29T20:00:00 | 2015-08-29T21:41:00 | Andrew Del Rivero (Piotrowski Park)      | andrew.derivero@chicagoparkdistrict.com    | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-La-Villita1/, null]       | [http://www.chicagoparkdistrict.com/parks/la-villita-park/, null]             | Douglas, South Lawndale | Yes                | G           | 
| Night Out: Movies in the Parks at Berger           | Who Framed Roger Rabbit        | Berger Park Cultural Center | 60660   | (773) 761-0376 | 2015-08-29T20:00:00 | 2015-08-29T21:44:00 | Justin "J.D." Ostergaard                 |                                            | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Berger2/, null]           | [http://www.chicagoparkdistrict.com/parks/Berger-Park-Cultural-Center/, null] | Edgewater               | Yes                | PG          | 
| Night Out: Movies in the Parks at Hiawatha         | Ferris Bueller's Day Off       | Hiawatha Park               | 60634   | (312) 746-5559 | 2015-08-29T20:00:00 | 2015-08-29T21:43:00 | Larry Krawetz                            | lawrence.krawetz@chicagoparkdistrict.com   | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Hiawatha1/, null]         | [http://www.chicagoparkdistrict.com/parks/Hiawatha-Park/, null]               | Dunning                 | Yes                | PG-13       | 
| Night Out: Movies in the Parks at Athletic Field   | McFarland USA                  | Athletic Field Park         | 60618   | (773) 478-2889 | 2015-08-28T20:15:00 | 2015-08-28T22:15:00 | Gualberto Roldan                         |                                            | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Athletic-Field2/, null]   | [http://www.chicagoparkdistrict.com/parks/Athletic-Field-Park/, null]         | Irving Park             | N/A                | PG          | 
| Night Out: Movies in the Parks at Golden Gate      | The Avengers                   | Golden Gate Park            | 60627   | (312) 747-6047 | 2015-08-28T20:00:00 | 2015-08-28T22:23:00 | Carver Park                              |                                            | [http://www.chicagoparkdistrict.com/events/Night-Out-Movies-in-the-Parks-at-Golden-Gate2/, null]      | [http://www.chicagoparkdistrict.com/parks/Golden-Gate-Park/, null]            | Riverdale               | Yes                | PG-13       | 
```