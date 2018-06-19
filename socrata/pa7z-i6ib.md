# Recreation Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-events-2dd3f) |
| Metadata | [Link](https://data.seattle.gov/api/views/pa7z-i6ib) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/pa7z-i6ib/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/pa7z-i6ib/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | pa7z-i6ib |
| Name | Recreation Events |
| Category | Community |
| Created | 2013-06-27T16:49:29Z |
| Publication Date | 2013-07-15T23:27:51Z |

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
series e:pa7z-i6ib d:2013-07-15T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792924" t:event_contact="Josh Mahar" t:website=http://www.mohai.org/ t:event="Still Afloat: A Contemporary History of Seattle's Floating Homes" t:sponsoring_organization="MOHAI and Floating Homes Association" t:event_contact_email=information@mohai.org t:street_address="860 Terry Ave N" t:event_description_agenda="Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle&#39;s most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home." t:event_contact_phone=206-324-1126 m:row_number.pa7z-i6ib=1

series e:pa7z-i6ib d:2013-07-16T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792925" t:event_contact="Josh Mahar" t:website=http://www.mohai.org/ t:event="Still Afloat: A Contemporary History of Seattle's Floating Homes" t:sponsoring_organization="MOHAI and Floating Homes Association" t:event_contact_email=information@mohai.org t:street_address="860 Terry Ave N" t:event_description_agenda="Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle&#39;s most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home." t:event_contact_phone=206-324-1126 m:row_number.pa7z-i6ib=2

series e:pa7z-i6ib d:2013-07-17T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792926" t:event_contact="Josh Mahar" t:website=http://www.mohai.org/ t:event="Still Afloat: A Contemporary History of Seattle's Floating Homes" t:sponsoring_organization="MOHAI and Floating Homes Association" t:event_contact_email=information@mohai.org t:street_address="860 Terry Ave N" t:event_description_agenda="Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle&#39;s most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home." t:event_contact_phone=206-324-1126 m:row_number.pa7z-i6ib=3
```

## Meta Commands

```ls
metric m:row_number.pa7z-i6ib p:long l:"Row Number"

entity e:pa7z-i6ib l:"Recreation Events" t:url=https://data.seattle.gov/api/views/pa7z-i6ib

property e:pa7z-i6ib t:meta.view v:id=pa7z-i6ib v:category=Community v:averageRating=0 v:name="Recreation Events"

property e:pa7z-i6ib t:meta.view.license v:name="Public Domain"

property e:pa7z-i6ib t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:pa7z-i6ib t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| event                                                            | start_time          | end_time | building_name_room_number | website                       | event_description_agenda                                                                                                                                                                                                                                                                                                                                      | sponsoring_organization              | event_contact | event_contact_position_department | event_contact_phone | event_contact_email   | street_address  | latitude | longitude  | event_info_url                                                                          | 
| ================================================================ | =================== | ======== | ========================= | ============================= | ============================================================================================================================================================================================================================================================================================================================================================= | ==================================== | ============= | ================================= | =================== | ===================== | =============== | ======== | ========== | ======================================================================================= | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-15T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792924, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-16T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792925, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-17T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792926, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-18T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792927, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-19T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792928, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-20T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792929, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-21T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792930, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-22T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792931, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-23T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792932, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes | 2013-07-24T00:00:00 |          |                           | [http://www.mohai.org/, null] | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home. | MOHAI and Floating Homes Association | Josh Mahar    |                                   | 206-324-1126        | information@mohai.org | 860 Terry Ave N | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792933, null] | 
```