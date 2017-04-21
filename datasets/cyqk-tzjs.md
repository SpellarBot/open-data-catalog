# Chicago Park District: Movies in the Parks 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-park-district-movies-in-the-parks-2014-f4cd5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cyqk-tzjs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cyqk-tzjs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cyqk-tzjs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cyqk-tzjs |
| Name | Chicago Park District: Movies in the Parks 2014 |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | movies, movie, park, parks, movies in the park, movies in the parks, chicago park district |
| Created | 2014-05-15T21:13:45Z |
| Publication Date | 2014-05-15T21:20:55Z |

## Description

List of all Movies in the Parks events. Please visit the Chicago Park District website or call the Movies in the Parks hotline at 312-742-1134 to check for cancellations due to weather.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | eventname          | EventName          | text          | text          |
| Yes      | series tag  | moviename          | MovieName          | text          | text          |
| Yes      | series tag  | location           | Location           | text          | text          |
| Yes      | series tag  | zipcode            | ZipCode            | text          | text          |
| Yes      | series tag  | phone              | Phone              | text          | text          |
| Yes      | time        | startdate          | StartDate          | calendar_date | calendar_date |
| No       |             | enddate            | EndDate            | calendar_date | calendar_date |
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
series e:cyqk-tzjs d:2014-05-29T19:00:00.000Z t:phone="(773) 287-7658" t:parkurl=http://www.chicagoparkdistrict.com/parks/Austin-Town-Hall-Park/ t:moviename=@home t:location="Austin Town Hall Park" t:zipcode=60644 t:community=Austin t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Austin-Town-Hall/ t:movierating=NR t:eventname="@home Documentary at Austin Town Hall" t:movieclosedcaption=No m:row_number.cyqk-tzjs=1

series e:cyqk-tzjs d:2014-06-03T19:00:00.000Z t:phone="(773) 761-0376" t:parkurl=http://www.chicagoparkdistrict.com/parks/Berger-Park-Cultural-Center/ t:moviename=@home t:location="Berger Park Cultural Center" t:zipcode=60660 t:community=Edgewater t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Berger/ t:movierating=NR t:eventname="@home Documentary at Berger" t:movieclosedcaption=No m:row_number.cyqk-tzjs=2

series e:cyqk-tzjs d:2014-06-05T19:00:00.000Z t:phone="(312) 742-7891" t:parkurl=http://www.chicagoparkdistrict.com/parks/Lake-Shore-Park/ t:moviename=@home t:location="Lake Shore Park" t:zipcode=60611 t:community="Near North Side" t:eventurl=http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Lake-Shore/ t:movierating=NR t:eventname="@home Documentary at Lake Shore" t:movieclosedcaption=No m:row_number.cyqk-tzjs=3
```

## Meta Commands

```ls
metric m:row_number.cyqk-tzjs p:long l:"Row Number"

entity e:cyqk-tzjs l:"Chicago Park District: Movies in the Parks 2014" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/cyqk-tzjs

property e:cyqk-tzjs t:meta.view v:id=cyqk-tzjs v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/events/movies v:averageRating=0 v:name="Chicago Park District: Movies in the Parks 2014" v:attribution="Chicago Park District"

property e:cyqk-tzjs t:meta.view.owner v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:displayName="CPD IT"

property e:cyqk-tzjs t:meta.view.tableauthor v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:roleName=editor v:displayName="CPD IT"
```

## Top Records

```ls
| eventname                             | moviename    | location                    | zipcode | phone          | startdate           | enddate             | eventurl                                                                                          | parkurl                                                                       | community                    | movieclosedcaption | movierating | 
| ===================================== | ============ | =========================== | ======= | ============== | =================== | =================== | ================================================================================================= | ============================================================================= | ============================ | ================== | =========== | 
| @home Documentary at Austin Town Hall | @home        | Austin Town Hall Park       | 60644   | (773) 287-7658 | 2014-05-29T19:00:00 | 2014-05-29T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Austin-Town-Hall/, null] | [http://www.chicagoparkdistrict.com/parks/Austin-Town-Hall-Park/, null]       | Austin                       | No                 | NR          | 
| @home Documentary at Berger           | @home        | Berger Park Cultural Center | 60660   | (773) 761-0376 | 2014-06-03T19:00:00 | 2014-06-03T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Berger/, null]           | [http://www.chicagoparkdistrict.com/parks/Berger-Park-Cultural-Center/, null] | Edgewater                    | No                 | NR          | 
| @home Documentary at Lake Shore       | @home        | Lake Shore Park             | 60611   | (312) 742-7891 | 2014-06-05T19:00:00 | 2014-06-05T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Lake-Shore/, null]       | [http://www.chicagoparkdistrict.com/parks/Lake-Shore-Park/, null]             | Near North Side              | No                 | NR          | 
| @home Documentary at Loyola           | @home        | Loyola Park                 | 60626   | (773) 262-8605 | 2014-05-30T19:00:00 | 2014-05-30T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Loyola/, null]           | [http://www.chicagoparkdistrict.com/parks/Loyola-Park/, null]                 | Rogers Park, Grand Boulevard | No                 | NR          | 
| @home Documentary at Palmer           | @home        | Palmer Park                 | 60628   | (312) 747-6577 | 2014-06-06T19:00:00 | 2014-06-06T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Palmer/, null]           | [http://www.chicagoparkdistrict.com/parks/Palmer-Park/, null]                 | Roseland                     | No                 | NR          | 
| @home Documentary at Piotrowski       | @home        | Piotrowski Park             | 60623   | (312) 747-6608 | 2014-06-04T19:00:00 | 2014-06-04T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-Piotrowski/, null]       | [http://www.chicagoparkdistrict.com/parks/Piotrowski-Park/, null]             | South Lawndale               | No                 | NR          | 
| @home Documentary at West Pullman     | @home        | West Pullman Park           | 60628   | (312) 747-7090 | 2014-06-02T19:00:00 | 2014-06-02T20:30:00 | [http://www.chicagoparkdistrict.com/events/Night-Out-home-Documentary-at-West-Pullman/, null]     | [http://www.chicagoparkdistrict.com/parks/West-Pullman-Park/, null]           | West Pullman                 | No                 | NR          | 
| Family Movie Night at Austin Foster   | Lego Movie   | Austin-Foster Playlot Park  | 60630   | (773) 685-3257 | 2014-08-07T20:00:00 | 2014-08-07T22:00:00 | [http://www.chicagoparkdistrict.com/events/Night-OutFamily-Movie-Night-at-Austin-Foster/, null]   | [http://www.chicagoparkdistrict.com/parks/Austin-Foster-Playlot-Park/, null]  | Jefferson Park               | N/A                | PG          | 
| Family Movie Night at Brooks          | The Smurfs 2 | Brooks Park                 | 60631   | (773) 631-4401 | 2014-07-18T20:00:00 | 2014-07-18T22:00:00 | [http://www.chicagoparkdistrict.com/events/Night-OutFamily-Movie-Night-at-Brooks/, null]          | [http://www.chicagoparkdistrict.com/parks/Brooks-Park/, null]                 | Edison Park                  | N/A                | PG          | 
| Family Movie Night at Dunham          | Delivery Man | Dunham Park                 | 60630   | (773) 685-3257 | 2014-06-13T21:00:00 | 2014-06-13T23:00:00 | [http://www.chicagoparkdistrict.com/events/Night-OutFamily-Movie-Night-at-Dunham/, null]          | [http://www.chicagoparkdistrict.com/parks/Dunham-Park/, null]                 | Portage Park                 | N/A                | PG-13       | 
```