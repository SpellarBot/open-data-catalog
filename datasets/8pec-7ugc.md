# Public Outreach and Engagement Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-outreach-and-engagement-events-85f0f) |
| Metadata | [Link](https://data.seattle.gov/api/views/8pec-7ugc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/8pec-7ugc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/8pec-7ugc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 8pec-7ugc |
| Name | Public Outreach and Engagement Events |
| Attribution | Community Engagement Coordinator |
| Category | Community |
| Tags | engage, outreach, community, volunteer, meetings |
| Created | 2011-09-30T09:20:11Z |
| Publication Date | 2016-05-18T08:31:50Z |

## Description

The calendar represents opportunities to engage with City representatives in your neighborhood

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag  | event                             | Event                             | text          | text          |
| Yes      | time        | start_time                        | Start time                        | calendar_date | calendar_date |
| No       |             | end_time                          | End time                          | calendar_date | calendar_date |
| Yes      | series tag  | venue                             | Venue                             | text          | text          |
| Yes      | series tag  | building_name_room_number         | Building Name/Room Number         | text          | text          |
| Yes      | series tag  | street_address                    | Street Address                    | text          | text          |
| Yes      | series tag  | event_description_agenda          | Event Description/Agenda          | html          | html          |
| Yes      | series tag  | event_contact                     | Event Contact                     | text          | text          |
| Yes      | series tag  | event_contact_position_department | Event Contact Position/Department | text          | text          |
| Yes      | series tag  | event_contact_phone               | Event Contact Phone               | text          | text          |
| Yes      | series tag  | event_contact_email               | Event Contact Email               | text          | text          |
| No       |             | latitude                          | Latitude                          | number        | number        |
| No       |             | longitude                         | Longitude                         | number        | number        |
| Yes      | series tag  | event_info_url                    | Event Info Url                    | url           | url           |
| Yes      | series tag  | website                           | Website                           | url           | url           |
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
series e:8pec-7ugc d:2016-05-18T09:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118730646" t:website=http://www.seattle.gov/neighborhoods/preservation/agendas.htm t:event="Pioneer Square Preservation Board" t:street_address="600 4th Avenue" t:venue="City Hall" t:event_description_agenda="&nbsp;Pioneer Square Preservation Board meeting" m:row_number.8pec-7ugc=1

series e:8pec-7ugc d:2016-05-18T15:30:00.000Z t:event_info_url="http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118730375" t:website=http://www.seattle.gov/neighborhoods/preservation/agendas.htm t:event="Landmarks Preservation Board" t:street_address="600 4th Avenue, L280" t:venue="City Hall" t:event_description_agenda="&nbsp;Landmarks Preservation Board meeting" m:row_number.8pec-7ugc=2

series e:8pec-7ugc d:2016-05-18T18:30:00.000Z t:event_info_url="http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118472802" t:event="Design Review- 1120 Denny Way" t:street_address="1901 1st Ave W" t:venue="Queen Anne Community Center" t:event_description_agenda="Land Use Application to allow two towers (41 stories each) containing 1,067 residential units, and 28,090 sq. ft. of retail space. Parking for 1,347 vehicles to be located below grade. An Addendum to the South Lake Union Height and Density Environmental Impact Statement (EIS) has been prepared.  <a target=""_blank"" href=""http://www.seattle.gov/dpd/aboutus/news/events/DesignReview/Detail/default.aspx?id=5872&amp;b=s&amp;pn=3017232"">Meeting Details</a>" m:row_number.8pec-7ugc=3
```

## Meta Commands

```ls
metric m:row_number.8pec-7ugc p:long l:"Row Number"

entity e:8pec-7ugc l:"Public Outreach and Engagement Events" t:attribution="Community Engagement Coordinator" t:url=https://data.seattle.gov/api/views/8pec-7ugc

property e:8pec-7ugc t:meta.view v:id=8pec-7ugc v:category=Community v:attributionLink=http://www.seattle.gov/engage/access.htm v:averageRating=0 v:name="Public Outreach and Engagement Events" v:attribution="Community Engagement Coordinator"

property e:8pec-7ugc t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8pec-7ugc t:meta.view.owner v:id=6u3k-7iuy v:screenName=engage_dsg v:displayName=engage_dsg

property e:8pec-7ugc t:meta.view.tableauthor v:id=6u3k-7iuy v:screenName=engage_dsg v:displayName=engage_dsg
```

## Top Records

```ls
| event                                            | start_time          | end_time            | venue                                                                                                                                               | building_name_room_number   | street_address                           | event_description_agenda                                                                                                                                                                                                                                                                                                                                                                   | event_contact   | event_contact_position_department | event_contact_phone | event_contact_email         | latitude | longitude  | event_info_url                                                                                            | website                                                                      | 
| ================================================ | =================== | =================== | =================================================================================================================================================== | =========================== | ======================================== | ========================================================================================================================================================================================================================================================================================================================================================================================== | =============== | ================================= | =================== | =========================== | ======== | ========== | ========================================================================================================= | ============================================================================ | 
| Pioneer Square Preservation Board                | 2016-05-18T09:00:00 | 2016-05-18T11:00:00 | City Hall                                                                                                                                           |                             | 600 4th Avenue                           |  Pioneer Square Preservation Board meeting                                                                                                                                                                                                                                                                                                                                                 |                 |                                   |                     |                             | 47.60377 | -122.32971 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118730646, null] | [http://www.seattle.gov/neighborhoods/preservation/agendas.htm, null]        | 
| Landmarks Preservation Board                     | 2016-05-18T15:30:00 | 2016-05-18T17:30:00 | City Hall                                                                                                                                           |                             | 600 4th Avenue, L280                     |  Landmarks Preservation Board meeting                                                                                                                                                                                                                                                                                                                                                      |                 |                                   |                     |                             |          |            | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118730375, null] | [http://www.seattle.gov/neighborhoods/preservation/agendas.htm, null]        | 
| Design Review- 1120 Denny Way                    | 2016-05-18T18:30:00 | 2016-05-18T21:30:00 | Queen Anne Community Center                                                                                                                         |                             | 1901 1st Ave W                           | Land Use Application to allow two towers (41 stories each) containing 1,067 residential units, and 28,090 sq. ft. of retail space. Parking for 1,347 vehicles to be located below grade. An Addendum to the South Lake Union Height and Density Environmental Impact Statement (EIS) has been prepared. Meeting Details                                                                    |                 |                                   |                     |                             | 47.63629 | -122.35922 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118472802, null] | [null, null]                                                                 | 
| Delridge District Council                        | 2016-05-18T19:00:00 | 2016-05-18T20:00:00 | Youngstown Cultural Arts Center                                                                                                                     |                             | 4408 Delridge Way SW                     |                                                                                                                                                                                                                                                                                                                                                                                            |                 |                                   |                     |                             | 47.56379 | -122.36301 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d119031237, null] | [http://www.seattle.gov/neighborhoods/neighborhood-districts/delridge, null] | 
| Construction Codes Advisory Board Meeting        | 2016-05-19T12:00:00 | 2016-05-19T14:00:00 | Seattle Municipal Tower                                                                                                                             | 19th floor, room 1940-1946  | 700 5th Ave                              | Meeting Agenda Meeting DocumentsApril 7 Minutes You can review the changes to the building code chapters on our 2015 Building Code Update webpage.                                                                                                                                                                                                                                         | Maureen Traxler |                                   | 206-233-2766        | maureen.traxler@seattle.gov | 47.60501 | -122.32988 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d114613473, null] | [null, null]                                                                 | 
| Seattle Commission for People with disAbilities  | 2016-05-19T16:00:00 | 2016-05-19T18:00:00 | Monthly meeting of the Seattle Commission for People with disAbilities. Members of the public may listen to the meeting by calling: (206) 684-4718. |                             |                                          |                                                                                                                                                                                                                                                                                                                                                                                            |                 |                                   |                     |                             |          |            | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d117676649, null] | [http://www.seattle.gov/disability/calendar.htm, null]                       | 
| Levy to Move Seattle Oversight Committee Meeting | 2016-05-19T17:00:00 | 2016-05-19T18:30:00 | Seattle Municipal Tower                                                                                                                             |                             | 700 Fifth Avenue, Room 4050 (40th Floor) |                                                                                                                                                                                                                                                                                                                                                                                            |                 |                                   |                     |                             |          |            | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d119106390, null] | [http://www.seattle.gov/transportation/ltms_oversight.htm, null]             | 
| Pet Loss Support Group                           | 2016-05-19T17:30:00 | 2016-05-19T18:45:00 | Seattle Animal Shelter                                                                                                                              | Upper Level Conference Room | 2061 15th Ave W                          |  The Pet Loss Support Group provides a safe, supportive place where pet owners who have lost a beloved animal can share stories about their pet and work through their grief. Groups are led by trained facilitators.                                                                                                                                                                      |                 | Seattle Animal Shelter            | 206-386-7387        |                             | 47.63837 | -122.37654 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d117696009, null] | [http://www.seattle.gov/animalshelter/, null]                                | 
| Seattle LGBT Commission                          | 2016-05-19T18:30:00 | 2016-05-19T20:30:00 |                                                                                                                                                     |                             |                                          |                                                                                                                                                                                                                                                                                                                                                                                            |                 |                                   |                     |                             |          |            | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d117676421, null] | [http://www.seattle.gov/LGBT/, null]                                         | 
| Disaster and a Movie: Twister in Hecklevision    | 2016-05-19T20:00:00 | 2016-05-19T22:00:00 | Central Cinema                                                                                                                                      |                             | 1411 21st Ave                            | Join Central Cinema for a special 20th anniversary event screeining of Twister. Before the show, enjoy a talk from Matt Auflick of the City of Seattle Emergency Management and Ted Beuhner, Warning Coordinator Meteorologist with the National Weather Service. Then, during the film text your disaster related questions to the screen, along with any comments, jokes, or cow noises. |                 |                                   |                     |                             | 47.61306 | -122.30526 | [http://www.seattle.gov/calendar/publicoutreach.htm?trumbaEmbed=view%3devent%26eventid%3d118741409, null] | [http://central-cinema.com/, null]                                           | 
```