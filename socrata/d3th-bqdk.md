# What's Happening LA Calendar Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/whats-happening-la-calendar-dataset) |
| Metadata | [Link](https://data.lacity.org/api/views/d3th-bqdk) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/d3th-bqdk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/d3th-bqdk/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | d3th-bqdk |
| Name | What's Happening LA Calendar Dataset |
| Category | A Livable and Sustainable City |
| Tags | event, calendar, all city |
| Created | 2014-03-09T17:14:04Z |
| Publication Date | 2016-11-08T18:04:47Z |

## Description

All-City event calendar

## Columns

```ls
| Included | Schema Type | Field Name            | Name                         | Data Type     | Render Type   |
| ======== | =========== | ===================== | ============================ | ============= | ============= |
| Yes      | series tag  | event_name            | Event Name                   | text          | text          |
| Yes      | series tag  | event_description     | Event Description            | text          | text          |
| Yes      | series tag  | fee_required          | Fee Required                 | text          | text          |
| Yes      | series tag  | type_of_event         | Type of Event                | text          | text          |
| Yes      | series tag  | subject_matter        | Subject Matter               | text          | text          |
| Yes      | series tag  | age_groupings         | Age Groupings                | text          | text          |
| Yes      | series tag  | event_by_service_area | Event by Service Area        | text          | text          |
| Yes      | series tag  | event_sponsor         | Event Sponsor                | text          | text          |
| Yes      | time        | event_date_time_start | Event Date & Time Start      | calendar_date | calendar_date |
| No       |             | event_date_time_ends  | Event Date & Time Ends       | calendar_date | calendar_date |
| Yes      | series tag  | location_common_name  | Location Common Name         | text          | text          |
| Yes      | series tag  | contact_name          | Contact Name                 | text          | text          |
| Yes      | series tag  | contact_number        | Contact Number               | phone         | phone         |
| Yes      | series tag  | contact_email         | Contact Email                | email         | email         |
| Yes      | series tag  | information_website   | Information Website          | url           | url           |
| Yes      | series tag  | council_district      | Elected Official Office Name | text          | text          |
| Yes      | series tag  | elected_officials     | Elected Officials Name       | text          | text          |
| Yes      | series tag  | neighborhood_council  | Neighborhood Council         | text          | text          |
| Yes      | series tag  | city_reference_id     | City Reference ID            | text          | text          |
```

## Time Field

```ls
Value = event_date_time_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_date_time_ends
```

## Data Commands

```ls
series e:d3th-bqdk d:2014-05-21T14:00:00.000Z t:fee_required=No t:location_common_name="Griffith Park Adult Community Center" t:phone_number="(323) 644-5579" t:subject_matter=Recreation t:age_groupings=Senior t:event_description="Making music for films." t:council_district="Council District 4" t:elected_officials="Tom LaBonge" t:event_name="Film Presentation at Griffith Park Adult Community Center" m:row_number.d3th-bqdk=1

series e:d3th-bqdk d:2014-05-23T20:30:00.000Z t:fee_required=No t:location_common_name="Pershing Square" t:subject_matter=Recreation t:age_groupings=All t:event_description="Bring a picnic, blanket or lawn chair and join us for a free screening of your favorite films." t:council_district="Council District 14" t:elected_officials="Jose Huizar" t:information_website=http://www.laparks.org/pershingsquare/friday-night-flicks.html t:event_name="Movie Screenings at Pershing Square (05/23/14)" m:row_number.d3th-bqdk=2

series e:d3th-bqdk d:2014-05-24T08:00:00.000Z t:fee_required=Yes t:location_common_name="Cabrillo Marine Aquarium" t:phone_number="(310) 548-7562" t:subject_matter=Recreation t:age_groupings=Child t:event_description="Discover the wonder of the Channel Islands as you join CMA Educators on an adventure to Anacapa Island, which is part of the Channel Islands National Marine Sanctuary. During the crossing watch for marine birds and mammals, then join a guided walk and check out nesting gulls as you greet spring on Anacapa Island. The trip leaves from Oxnard. Visit our website for more details. Reservations a must." t:council_district="Council District 15" t:elected_officials="Joe Buscaino" t:information_website="http://www.cabrillomarineaquarium.org/events-news/events-details.asp?id=1191" t:event_name="Channel Islands Adventure-Anacapa Island" m:row_number.d3th-bqdk=3
```

## Meta Commands

```ls
metric m:row_number.d3th-bqdk p:long l:"Row Number"

entity e:d3th-bqdk l:"What's Happening LA Calendar Dataset" t:url=https://data.lacity.org/api/views/d3th-bqdk

property e:d3th-bqdk t:meta.view v:id=d3th-bqdk v:category="A Livable and Sustainable City" v:averageRating=0 v:name="What's Happening LA Calendar Dataset"

property e:d3th-bqdk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:d3th-bqdk t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:d3th-bqdk t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| event_name                                                | event_description                                                                                                                                                                                                                                                                                                                                                                                                                                                         | fee_required | type_of_event | subject_matter | age_groupings | event_by_service_area | event_sponsor | event_date_time_start | event_date_time_ends | location_common_name                             | contact_name              | contact_number         | contact_email | information_website                                                                  | council_district    | elected_officials | neighborhood_council | city_reference_id | 
| ========================================================= | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ============ | ============= | ============== | ============= | ===================== | ============= | ===================== | ==================== | ================================================ | ========================= | ====================== | ============= | ==================================================================================== | =================== | ================= | ==================== | ================= | 
| Film Presentation at Griffith Park Adult Community Center | Making music for films.                                                                                                                                                                                                                                                                                                                                                                                                                                                   | No           |               | Recreation     | Senior        |                       |               | 2014-05-21T14:00:00   | 2014-05-21T16:00:00  | Griffith Park Adult Community Center             |                           | [(323) 644-5579, null] |               | [null, null]                                                                         | Council District 4  | Tom LaBonge       |                      |                   | 
| Movie Screenings at Pershing Square (05/23/14)            | Bring a picnic, blanket or lawn chair and join us for a free screening of your favorite films.                                                                                                                                                                                                                                                                                                                                                                            | No           |               | Recreation     | All           |                       |               | 2014-05-23T20:30:00   | 2014-05-23T22:30:00  | Pershing Square                                  |                           | [null, null]           |               | [http://www.laparks.org/pershingsquare/friday-night-flicks.html, null]               | Council District 14 | Jose Huizar       |                      |                   | 
| Channel Islands Adventure-Anacapa Island                  | Discover the wonder of the Channel Islands as you join CMA Educators on an adventure to Anacapa Island, which is part of the Channel Islands National Marine Sanctuary. During the crossing watch for marine birds and mammals, then join a guided walk and check out nesting gulls as you greet spring on Anacapa Island. The trip leaves from Oxnard. Visit our website for more details. Reservations a must.                                                          | Yes          |               | Recreation     | Child         |                       |               | 2014-05-24T08:00:00   | 2014-05-24T17:00:00  | Cabrillo Marine Aquarium                         |                           | [(310) 548-7562, null] |               | [http://www.cabrillomarineaquarium.org/events-news/events-details.asp?id=1191, null] | Council District 15 | Joe Buscaino      |                      |                   | 
| Memorial Day Event at Rio de Los Angeles                  | Salute to the Armed Forces.                                                                                                                                                                                                                                                                                                                                                                                                                                               | No           |               | Recreation     | All           |                       |               | 2014-05-24T10:00:00   | 2014-05-24T13:00:00  | Rio De Los Angeles State Park                    |                           | [(323) 276-3015, null] |               | [null, null]                                                                         | Council District 1  | Gilbert Cedillo   |                      |                   | 
| Body Building Competition at Venice Beach                 | Come to Venice Beach for the annual Memorial Day Body Building Competition!                                                                                                                                                                                                                                                                                                                                                                                               | No           |               | Recreation     | Adult         |                       |               | 2014-05-26T13:00:00   | 2014-05-26T17:00:00  | Venice Beach Recreation Area                     |                           | [(310) 399-2775, null] |               | [null, null]                                                                         | Council District 11 | Mike Bonin        |                      |                   | 
| American Cetacean Society Lecture at Cabrillo Aquarium    | The American Cetacean Society/Los Angeles Chapter offers free monthly lectures in the John M. Olguin Auditorium on the last Tuesday of each month through May (resuming in September). For information and scheduled speakers, visit www.acs-la.org.                                                                                                                                                                                                                      | No           |               | Recreation     | Adult         |                       |               | 2014-05-27T19:30:00   | 2014-05-27T21:00:00  | Cabrillo Marine Aquarium                         |                           | [(310) 548-7562, null] |               | [http://www.cabrillomarineaquarium.org/events-news/events-details.asp?id=1176, null] | Council District 15 | Joe Buscaino      |                      |                   | 
| Rustic Canyon Eucalyptus Grove Dedication                 | Join the Department of Recreation and Parks and Councilmember Mike Bonin, 11th District for the reopening/dedication of the Eucalyptus Grove at Rustic Canyon.                                                                                                                                                                                                                                                                                                            | No           |               | Recreation     | All           |                       |               | 2014-05-29T09:30:00   | 2014-05-29T10:30:00  | Rustic Canyon Park                               | Public Information Office | [(213) 202-2700, null] |               | [null, null]                                                                         | Council District 11 | Mike Bonin        |                      |                   | 
| Grunion Fishtival at Cabrillo Aquarium                    | Watch the captivating grunion come up on the beach to spawn! The Aquarium opens at 8pm and an auditorium program begins at 9pm, followed by guided observation at the beach. Warm clothing and a flashlight are recommended. During April and May (closed season) grunion may be observed but not touched. March, June and July are open season, when grunion may only be taken by hand. Grunion hunters, 16 years or older must have a valid California fishing license. | Yes          |               | Recreation     | All           |                       |               | 2014-05-30T19:00:00   | 2014-05-30T23:30:00  | Cabrillo Marine Aquarium                         |                           | [(310) 548-7562, null] |               | [http://www.cabrillomarineaquarium.org/events-news/events-details.asp?id=1160, null] | Council District 15 | Joe Buscaino      |                      |                   | 
| A Fairy Hunt at Griffith Park                             | A Fairy Hunt - Interactive play                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes          |               | Recreation     | All           |                       |               | 2014-05-31T08:00:00   | 2014-05-31T13:00:00  | Griffith Park - Ferndell Nature Museum / Gardens | Jessica Castro            | [(323) 644-6252, null] |               | [null, null]                                                                         | Council District 4  | Tom LaBonge       |                      |                   | 
| Cystic Fibrosis Walk at Griffith Park                     | Fundraising walk for the Cystic Fibrosis Foundation. Registration fee required.                                                                                                                                                                                                                                                                                                                                                                                           | Yes          |               | Recreation     | All           |                       |               | 2014-05-31T07:00:00   | 2014-05-31T14:00:00  | Griffith Park                                    |                           | [(323) 644-6252, null] |               | [null, null]                                                                         | Council District 4  | Tom LaBonge       |                      |                   | 
```