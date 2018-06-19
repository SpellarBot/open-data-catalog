# City Sponsored Events Simple

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-sponsored-events-simple) |
| Metadata | [Link](https://data.seattle.gov/api/views/39xq-zv8h) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/39xq-zv8h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/39xq-zv8h/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 39xq-zv8h |
| Name | City Sponsored Events Simple |
| Category | Community |
| Tags | events, calendar, trumba |
| Created | 2015-11-09T23:38:29Z |
| Publication Date | 2016-02-18T17:12:51Z |

## Description

Trumba events

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | event                    | Event                    | text          | text          |
| Yes      | time        | start_time               | Start time               | calendar_date | calendar_date |
| No       |             | end_time                 | End time                 | calendar_date | calendar_date |
| Yes      | series tag  | event_description_agenda | Event Description/Agenda | text          | text          |
| Yes      | series tag  | street_address           | Street Address           | text          | text          |
| No       |             | latitude                 | Latitude                 | number        | number        |
| No       |             | longitude                | Longitude                | number        | number        |
| Yes      | series tag  | event_info_url           | Event Info Url           | url           | url           |
| Yes      | series tag  | classification           | Classification           | text          | text          |
| Yes      | series tag  | audience                 | Audience                 | text          | text          |
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
series e:39xq-zv8h d:2016-02-18T00:00:00.000Z t:audience=All t:event_info_url="http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117766146" t:event="Northwest Flower & Garden Show, Feb. 17-21, 2016" t:classification="Community,Education,Festivals/Fairs,Gardening,Hobbies,Holiday/Seasonal Events,Nature/Environment,Other,Special Events,Sports/Recreation" t:street_address="800 Convention Pl" t:event_description_agenda="Northwest Flower & Garden Show, Feb. 17-21, 2016" m:row_number.39xq-zv8h=1

series e:39xq-zv8h d:2016-02-18T00:00:00.000Z t:audience=Adults,Children t:event_info_url="http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117623466" t:event="Society of Women Engineers ABJ Regional Confernece" t:classification="Special Events,Training-Classes/Workshops" t:street_address="2211 Alaskan Way" t:event_description_agenda="Society of Women Engineers ABJ Regional Confernece" m:row_number.39xq-zv8h=2

series e:39xq-zv8h d:2016-02-18T08:30:00.000Z t:audience=Adults t:event_info_url="http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d111420253" t:event="Design Commission Meeting" t:classification="Boards & Commissions" t:street_address="Boards and Commissions Room" t:event_description_agenda="Design Commission Meeting" m:row_number.39xq-zv8h=3
```

## Meta Commands

```ls
metric m:row_number.39xq-zv8h p:long l:"Row Number"

entity e:39xq-zv8h l:"City Sponsored Events Simple" t:url=https://data.seattle.gov/api/views/39xq-zv8h

property e:39xq-zv8h t:meta.view v:id=39xq-zv8h v:category=Community v:averageRating=0 v:name="City Sponsored Events Simple"

property e:39xq-zv8h t:meta.view.license v:name="Public Domain"

property e:39xq-zv8h t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:39xq-zv8h t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| event                                                    | start_time          | end_time            | event_description_agenda                                 | street_address                            | latitude | longitude  | event_info_url                                                                                                 | classification                                                                                                                          | audience        | 
| ======================================================== | =================== | =================== | ======================================================== | ========================================= | ======== | ========== | ============================================================================================================== | ======================================================================================================================================= | =============== | 
| Northwest Flower & Garden Show, Feb. 17-21, 2016         | 2016-02-18T00:00:00 | 2016-02-19T00:00:00 | Northwest Flower & Garden Show, Feb. 17-21, 2016         | 800 Convention Pl                         | 47.61195 | -122.33167 | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117766146, null] | Community,Education,Festivals/Fairs,Gardening,Hobbies,Holiday/Seasonal Events,Nature/Environment,Other,Special Events,Sports/Recreation | All             | 
| Society of Women Engineers ABJ Regional Confernece       | 2016-02-18T00:00:00 | 2016-02-19T00:00:00 | Society of Women Engineers ABJ Regional Confernece       | 2211 Alaskan Way                          | 47.61137 | -122.34947 | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117623466, null] | Special Events,Training-Classes/Workshops                                                                                               | Adults,Children | 
| Design Commission Meeting                                | 2016-02-18T08:30:00 | 2016-02-18T16:30:00 | Design Commission Meeting                                | Boards and Commissions Room               |          |            | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d111420253, null] | Boards & Commissions                                                                                                                    | Adults          | 
| Design Commission Meeting - Seattle Opera                | 2016-02-18T09:00:00 | 2016-02-18T11:00:00 | Design Commission Meeting - Seattle Opera                | Boards and Commissions Room               |          |            | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d118005505, null] | Boards & Commissions                                                                                                                    | Adults          | 
| CANCELED - Parks, Seattle Center, Libraries & Waterfront | 2016-02-18T09:30:00 | 2016-02-18T09:30:00 | CANCELED - Parks, Seattle Center, Libraries & Waterfront |                                           |          |            | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117552111, null] | City Council Meeting                                                                                                                    | Adults,All      | 
| Promontory Point Maintenance                             | 2016-02-18T10:00:00 | 2016-02-18T13:00:00 | Promontory Point Maintenance                             | 7400 Sand Point Way NE, Seattle, WA 98115 |          |            | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117686476, null] | Volunteer/Work Party                                                                                                                    | All             | 
| Portage Bay Park - ONLINE Open House                     | 2016-02-18T12:00:00 | 2016-02-18T12:45:00 | Portage Bay Park - ONLINE Open House                     | 800 Maynard Ave S                         | 47.59554 | -122.32471 | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d118136518, null] | Public Outreach and Engagement                                                                                                          | All             | 
| Construction Codes Advisory Board Meeting                | 2016-02-18T12:00:00 | 2016-02-18T14:00:00 | Construction Codes Advisory Board Meeting                | 600 Fourth Ave                            | 47.60377 | -122.32971 | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d114613470, null] | Boards & Commissions                                                                                                                    | Adults          | 
| Youth Voice, Youth Choice Idea Assembly                  | 2016-02-18T15:30:00 | 2016-02-18T17:30:00 | Youth Voice, Youth Choice Idea Assembly                  | 7054 32nd Ave S                           | 47.53893 | -122.2902  | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117889722, null] | Community,Grants,Neighborhood Meetings,Public Forum,Youth                                                                               | All,Teen        | 
| Seattle Commission for People with disAbilities          | 2016-02-18T16:00:00 | 2016-02-18T17:30:00 | Seattle Commission for People with disAbilities          | Seattle City Hall                         |          |            | [http://www.seattle.gov/living-in-seattle/event-calendar?trumbaEmbed=view%3devent%26eventid%3d117676646, null] | Boards & Commissions                                                                                                                    | All             | 
```