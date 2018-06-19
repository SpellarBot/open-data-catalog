# Other Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/other-events-fae19) |
| Metadata | [Link](https://data.seattle.gov/api/views/kjgy-var8) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kjgy-var8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kjgy-var8/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kjgy-var8 |
| Name | Other Events |
| Category | Community |
| Created | 2013-06-27T16:49:11Z |
| Publication Date | 2013-07-15T23:27:03Z |

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag  | event                             | Event                             | text          | text          |
| Yes      | time        | start_time                        | Start time                        | calendar_date | calendar_date |
| No       |             | end_time                          | End time                          | calendar_date | calendar_date |
| Yes      | series tag  | building_name_room_number         | Building Name/Room Number         | text          | text          |
| Yes      | series tag  | website                           | Website                           | url           | url           |
| Yes      | series tag  | event_description_agenda          | Event Description/Agenda          | text          | text          |
| Yes      | series tag  | sponsoring_organization           | Sponsoring Organization           | text          | text          |
| Yes      | series tag  | event_contact                     | Event Contact                     | text          | text          |
| Yes      | series tag  | event_contact_position_department | Event Contact Position/Department | text          | text          |
| Yes      | series tag  | event_contact_phone               | Event Contact Phone               | text          | text          |
| Yes      | series tag  | event_contact_email               | Event Contact Email               | text          | text          |
| Yes      | series tag  | street_address                    | Street Address                    | text          | text          |
| No       |             | latitude                          | Latitude                          | number        | number        |
| No       |             | longitude                         | Longitude                         | number        | number        |
| Yes      | series tag  | event_info_url                    | Event Info Url                    | url           | url           |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_time,latitude,longitude
```

## Data Commands

```ls
series e:kjgy-var8 d:2013-07-16T17:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105565997" t:event_contact="Bridget Anderson" t:website=https://www.seattlecityclub.org/20130716 t:event="Seattle Mayoral Debate" t:sponsoring_organization="Seattle CityClub" t:event_contact_email=banderson@seattlecityclub.org t:street_address="1000 4th Ave" t:event_description_agenda="This is not your average debate. Join us on July 16 for an interactive Seattle mayoral debate, where citizens help set the agenda and give real-time feedback to the candidates. Moderated by The Seattle Times&#8217; Joni Balter, the discussion will feature topics and questions shaped by citizens. For the first time in CityClub history, audience members will participate in our &#8220;lightning round&#8221; of yes, no and waffle questions alongside the candidates. Then, stick around to hear what some of Seattle&#8217;s leading journalists have to say about what they just saw!" t:event_contact_phone=2066827395 m:row_number.kjgy-var8=1

series e:kjgy-var8 d:2013-07-16T18:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106039838" t:event_contact="Jason Flores" t:website=http://www.prolango.com/training-events/career-mixer/ t:event="ProLango Mixer" t:sponsoring_organization="ProLango Consulting" t:event_contact_email=jason@prolango.com t:street_address="2040 Westlake Ave N" t:event_description_agenda="The free ProLango mixer has quickly become THE Seattle networking event to attend. On average, hosting 400 professionals (Project Managers to CEOs) and representatives from many companies like Starbucks, Amazon, Boeing, Microsoft, Eddie Bauer, Expedia, Concur Technologies, Swedish, and the University of Washington every month. With so many people attending it&#39;s a great opportunity for you to network, make contacts at other businesses, meet new customers or find exciting new positions. It would be great to see you there." t:event_contact_phone=206.334.6854 m:row_number.kjgy-var8=2

series e:kjgy-var8 d:2013-07-17T09:30:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d103506570" t:event_contact="Jennifer Greenlee" t:website=http://www.seattle.gov/csc/ t:event="Civil Service Commission Monthly Meeting" t:event_contact_email=jennifer.greenlee@seattle.gov t:street_address="700 5TH Ave" t:building_name_room_number="Seattle Municipal Tower, Suite 1679" t:event_contact_phone=233-7118 m:row_number.kjgy-var8=3
```

## Meta Commands

```ls
metric m:row_number.kjgy-var8 p:long l:"Row Number"

entity e:kjgy-var8 l:"Other Events" t:url=https://data.seattle.gov/api/views/kjgy-var8

property e:kjgy-var8 t:meta.view v:id=kjgy-var8 v:category=Community v:averageRating=0 v:name="Other Events"

property e:kjgy-var8 t:meta.view.license v:name="Public Domain"

property e:kjgy-var8 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:kjgy-var8 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| event                                                          | start_time          | end_time            | building_name_room_number           | website                                                                                 | event_description_agenda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | sponsoring_organization                 | event_contact                   | event_contact_position_department | event_contact_phone | event_contact_email                   | street_address       | latitude | longitude  | event_info_url                                                                          | 
| ============================================================== | =================== | =================== | =================================== | ======================================================================================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | ======================================= | =============================== | ================================= | =================== | ===================================== | ==================== | ======== | ========== | ======================================================================================= | 
| Seattle Mayoral Debate                                         | 2013-07-16T17:00:00 | 2013-07-16T18:30:00 |                                     | [https://www.seattlecityclub.org/20130716, null]                                        | This is not your average debate. Join us on July 16 for an interactive Seattle mayoral debate, where citizens help set the agenda and give real-time feedback to the candidates. Moderated by The Seattle Times? Joni Balter, the discussion will feature topics and questions shaped by citizens. For the first time in CityClub history, audience members will participate in our ?lightning round? of yes, no and waffle questions alongside the candidates. Then, stick around to hear what some of Seattle?s leading journalists have to say about what they just saw!                                                                                  | Seattle CityClub                        | Bridget Anderson                |                                   | 2066827395          | banderson@seattlecityclub.org         | 1000 4th Ave         | 47.60649 | -122.33297 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105565997, null] | 
| ProLango Mixer                                                 | 2013-07-16T18:00:00 | 2013-07-16T21:00:00 |                                     | [http://www.prolango.com/training-events/career-mixer/, null]                           | The free ProLango mixer has quickly become THE Seattle networking event to attend. On average, hosting 400 professionals (Project Managers to CEOs) and representatives from many companies like Starbucks, Amazon, Boeing, Microsoft, Eddie Bauer, Expedia, Concur Technologies, Swedish, and the University of Washington every month. With so many people attending it's a great opportunity for you to network, make contacts at other businesses, meet new customers or find exciting new positions. It would be great to see you there.                                                                                                                | ProLango Consulting                     | Jason Flores                    |                                   | 206.334.6854        | jason@prolango.com                    | 2040 Westlake Ave N  | 47.63734 | -122.33988 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106039838, null] | 
| Civil Service Commission Monthly Meeting                       | 2013-07-17T09:30:00 | 2013-07-17T11:15:00 | Seattle Municipal Tower, Suite 1679 | [http://www.seattle.gov/csc/, null]                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                         | Jennifer Greenlee               |                                   | 233-7118            | jennifer.greenlee@seattle.gov         | 700 5TH Ave          | 47.60501 | -122.32988 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d103506570, null] | 
| Demand Compassionate Release for People's Lawyer Lynne Stewart | 2013-07-17T16:00:00 | 2013-07-17T18:00:00 |                                     | [https://www.facebook.com/events/145079405696094/, null]                                | A rally demanding compassionate release for Lynne Stewart, the 73-year-old people?s lawyer dying of cancer in a Texas federal prison, will be held on Wednesday, July 17 from 4-6pm at the U.S. District Court Plaza, 700 Stewart St., in Seattle. Local legal, prisoner rights, antiwar, socialist, women?s and civil rights organizations will protest the Federal Bureau of Prison?s denial of release, this despite the Texas prison warden?s recommendations and the demand of tens of thousands supporting Lynne Stewart?s freedom.                                                                                                                    | National Lawyers Guild, Seattle Chapter | Neil Fox                        |                                   | 206-953-0233        | nationallawyersguildseattle@gmail.com | 700 Stewart St       | 47.61431 | -122.33564 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106218622, null] | 
| eWomenNetwork Networking Luncheon                              | 2013-07-18T11:15:00 | 2013-07-18T13:45:00 |                                     | [http://www.ewomennetwork.com/chapterHomePage/chapterEvent.php?chapterCode=WA101, null] | Monthly networking events designed to connect women in business and create introductions that will grow the success of women owned business in Seattle.

The events include lunch, structured and unstructured rounds of networking as well as a keynote business development presentation from world class speakers.                                                                                                                                                                                                                                                                                                                                        | eWomenNetwork                           | Debbie Whitlock                 |                                   | 206-749-5111        | debbiewhitlock@ewomennetwork.com      | 1936 Harbor Ave SW   | 47.58654 | -122.37644 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d103615828, null] | 
| Seattle's Best Damn Happy Hour                                 | 2013-07-18T17:00:00 | 2013-07-18T20:00:00 |                                     | [http://www.seattlecenter.com/happyhour/, null]                                         | Between work and play, there is Happy Hour. Seattle Center launches into 2013 with the Best. Damn. Happy Hour. Ever. Think we?re kidding? Think again. Think music by DJ D?Nelski (KEXP?s DJ Alex), think deals on specialty cocktails and delicious food from new Armory eateries like Skillet and MOD Pizza. Think mini golf, think giant Jenga, think trivia. Think fabulous prizes like tickets to concerts and shows at Seattle Center. We told you we weren?t kidding around. New Year. New Armory. New reason to be happy. Third Thursday of each month from 5 ? 8 pm in the freshly renovated Armory.

No cover | 21+ | seattlecenter.com/happyhour/ |                                         | Seattle Center Customer Service |                                   | 206-684-7200        |                                       | 305 Harrison St      | 47.62208 | -122.35398 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104008212, null] | 
| The Acrobatic Conundrum presents: The Way Out                  | 2013-07-18T19:30:00 |                     |                                     | [http://www.strangertickets.com/go/thewayout, null]                                     | ?The Way Out? is 90 minutes of heart-stopping acrobatics, aerial, theater and dance. It is a truly contemporary form of storytelling, using the raw physicality of the performers, video projection, the choreography of Elizabeth Rose and artistic direction of Terry Crane. ?The Way Out? spotlights a small company of 8 acrobats with their hearts on their sleeves and their calluses worn smooth.                                                                                                                                                                                                                                                     | The Acrobatic Conundrum                 | Joselynn Engstrom               |                                   |                     | acrobatic.conundrum@gmail.com         | 4408 Delridge Way SW | 47.56379 | -122.36301 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105933291, null] | 
| Public Safety Civil Service Commission Monthly Meeting         | 2013-07-19T10:00:00 | 2013-07-19T12:00:00 | Seatte Municipal Tower, Suite 1679  | [http://www.seattle.gov/pscsc/, null]                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                         | Jennifer Greenlee               |                                   | 233-7118            | jennifer.greenlee@seattle.gov         | 700 5TH Ave          | 47.60501 | -122.32988 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d103506603, null] | 
| Zen Meditation & Buddhism Classes                              | 2013-07-19T19:00:00 | 2013-07-19T21:00:00 |                                     | [http://www.buddhajewel.org/, null]                                                     | Buddha Jewel Monastery offers Zen Meditation & Buddhism classes throughout the year. The new class will start in May.

Date: Fridays May 3 ? July 19 (12 times)

Time: 7pm ? 9pm

Class Schedule:

7pm ? 8pm Sitting and walking meditation/ Refreshment

8pm ? 9pm Lecture

Lecturer: Venerable Master Jian Yan, Abbess of Buddha Jewel Monastery

Dress Code: Wear comfortable, modest attire. Socks are required. Optional meditation clothing may be obtained at the monastery.

All programs are free of charge and open to the public; we are supported by donations.

Please sign up via phone or online.                                             |                                         | Reception                       |                                   | 206-721-9921        | buddhajewel@ctzen.org                 | 7930 Rainier Ave S   | 47.53083 | -122.26952 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105146887, null] | 
| The Acrobatic Conundrum presents: The Way Out                  | 2013-07-25T19:30:00 |                     |                                     | [http://www.strangertickets.com/go/thewayout, null]                                     | ?The Way Out? is 90 minutes of heart-stopping acrobatics, aerial, theater and dance. It is a truly contemporary form of storytelling, using the raw physicality of the performers, video projection, the choreography of Elizabeth Rose and artistic direction of Terry Crane. ?The Way Out? spotlights a small company of 8 acrobats with their hearts on their sleeves and their calluses worn smooth.                                                                                                                                                                                                                                                     | The Acrobatic Conundrum                 | Joselynn Engstrom               |                                   |                     | acrobatic.conundrum@gmail.com         | 4408 Delridge Way SW | 47.56379 | -122.36301 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105933292, null] | 
```