# City Council Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-council-calendar) |
| Metadata | [Link](https://data.seattle.gov/api/views/ivxr-h48f) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ivxr-h48f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ivxr-h48f/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ivxr-h48f |
| Name | City Council Calendar |
| Category | City Business |
| Tags | event, trumba, council |
| Created | 2015-12-30T16:06:35Z |
| Publication Date | 2017-04-21T08:31:42Z |

## Description

Trumba Calendar Events

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | event                    | Event                    | text          | text          |
| Yes      | time           | start_time               | Start time               | calendar_date | calendar_date |
| No       |                | end_time                 | End time                 | calendar_date | calendar_date |
| Yes      | series tag     | event_description_agenda | Event Description/Agenda | text          | text          |
| Yes      | series tag     | venue                    | Venue                    | text          | text          |
| Yes      | series tag     | street_address           | Street Address           | text          | text          |
| Yes      | numeric metric | latitude                 | Latitude                 | number        | number        |
| Yes      | numeric metric | longitude                | Longitude                | number        | number        |
| Yes      | series tag     | event_info_url           | Event Info Url           | url           | url           |
| Yes      | series tag     | classification           | Classification           | text          | text          |
| Yes      | series tag     | audience                 | Audience                 | text          | text          |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:ivxr-h48f d:2017-04-18T09:30:00.000Z t:event_info_url="http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551904" t:event="Planning, Land Use & Zoning Committee" t:street_address="600 Fourth Avenue" t:venue="Council Chambers" t:event_description_agenda="Planning, Land Use & Zoning Committee" m:longitude=-122.32971 m:latitude=47.60377

series e:ivxr-h48f d:2017-04-18T14:00:00.000Z t:event_info_url="http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551964" t:event="Sustainability & Transportation Committee" t:street_address="600 Fourth Avenue" t:venue="Council Chambers" t:event_description_agenda="Sustainability & Transportation Committee" m:longitude=-122.32971 m:latitude=47.60377

series e:ivxr-h48f d:2017-04-19T09:00:00.000Z t:event_info_url="http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551705" t:event="Affordable Housing, Neigborhoods & Finance Committee- Special Meeting- Public Hearing" t:street_address="600 Fourth Avenue" t:venue="Council Chambers" t:event_description_agenda="Affordable Housing, Neigborhoods & Finance Committee- Special Meeting- Public Hearing" m:longitude=-122.32971 m:latitude=47.60377
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude d:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude d:Longitude t:dataTypeName=number

entity e:ivxr-h48f l:"City Council Calendar" t:url=https://data.seattle.gov/api/views/ivxr-h48f

property e:ivxr-h48f t:meta.view v:id=ivxr-h48f v:category="City Business" v:averageRating=0 v:name="City Council Calendar"

property e:ivxr-h48f t:meta.view.license v:name="Public Domain"

property e:ivxr-h48f t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:ivxr-h48f t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| event                                                                                 | start_time          | end_time            | event_description_agenda                                                              | venue            | street_address           | latitude | longitude  | event_info_url                                                                                             | classification | audience | 
| ===================================================================================== | =================== | =================== | ===================================================================================== | ================ | ======================== | ======== | ========== | ========================================================================================================== | ============== | ======== | 
| Council Briefing                                                                      | 2017-04-17T09:30:00 | 2017-04-17T09:30:00 | Council Briefing                                                                      | Council Chambers | 600 Fourth Ave., Floor 2 |          |            | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551990, null] |                |          | 
| Select Committee on Civic Arenas (or after Council Briefings)                         | 2017-04-17T10:30:00 | 2017-04-17T10:30:00 | Select Committee on Civic Arenas (or after Council Briefings)                         | Council Chambers | 600 Fourth Ave., Floor 2 |          |            | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d123102056, null] |                |          | 
| Full Council                                                                          | 2017-04-17T14:00:00 | 2017-04-17T14:00:00 | Full Council                                                                          | Council Chambers | 600 Fourth Ave., Floor 2 |          |            | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117552042, null] |                |          | 
| Planning, Land Use & Zoning Committee                                                 | 2017-04-18T09:30:00 | 2017-04-18T09:30:00 | Planning, Land Use & Zoning Committee                                                 | Council Chambers | 600 Fourth Avenue        | 47.60377 | -122.32971 | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551904, null] |                |          | 
| Sustainability & Transportation Committee                                             | 2017-04-18T14:00:00 | 2017-04-18T14:00:00 | Sustainability & Transportation Committee                                             | Council Chambers | 600 Fourth Avenue        | 47.60377 | -122.32971 | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551964, null] |                |          | 
| Affordable Housing, Neigborhoods & Finance Committee- Special Meeting- Public Hearing | 2017-04-19T09:00:00 | 2017-04-19T09:00:00 | Affordable Housing, Neigborhoods & Finance Committee- Special Meeting- Public Hearing | Council Chambers | 600 Fourth Avenue        | 47.60377 | -122.32971 | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551705, null] |                |          | 
| Education, Equity & Governance                                                        | 2017-04-19T14:00:00 | 2017-04-19T14:00:00 | Education, Equity & Governance                                                        | Council Chambers | 600 Fourth Avenue        | 47.60377 | -122.32971 | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d121694376, null] |                |          | 
| Parks, Seattle Center, Libraries & Waterfront Committee                               | 2017-04-20T09:30:00 | 2017-04-20T09:30:00 | Parks, Seattle Center, Libraries & Waterfront Committee                               | Council Chambers | 600 Fourth Avenue        | 47.60377 | -122.32971 | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d121694581, null] |                |          | 
| Council Briefing                                                                      | 2017-04-24T09:30:00 | 2017-04-24T09:30:00 | Council Briefing                                                                      | Council Chambers | 600 Fourth Ave., Floor 2 |          |            | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117551991, null] |                |          | 
| Full Council                                                                          | 2017-04-24T14:00:00 | 2017-04-24T14:00:00 | Full Council                                                                          | Council Chambers | 600 Fourth Ave., Floor 2 |          |            | [http://www.seattle.gov/council/calendar/default.htm?trumbaEmbed=view%3devent%26eventid%3d117552043, null] |                |          | 
```