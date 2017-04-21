# I Love NY - See and Do

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/i-love-ny-see-and-do) |
| Metadata | [Link](https://data.ny.gov/api/views/yj39-fr9e) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/yj39-fr9e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/yj39-fr9e/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | yj39-fr9e |
| Name | I Love NY - See and Do |
| Attribution | I Love NY |
| Created | 2013-07-05T14:47:05Z |
| Publication Date | 2013-08-21T13:56:49Z |

## Description

This data set includes things that a traveler can See and Do while in New York State

## Columns

```ls
| Included | Schema Type | Field Name       | Name        | Data Type | Render Type |
| ======== | =========== | ================ | =========== | ========= | =========== |
| No       | time        | :updated_at      | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | region           | Region      | text      | text        |
| Yes      | series tag  | county           | County      | text      | text        |
| Yes      | series tag  | site_title       | Title       | text      | text        |
| Yes      | series tag  | site_description | Description | text      | text        |
| No       |             | latitude         | Latitude    | number    | number      |
| No       |             | longitude        | Longitude   | number    | number      |
| Yes      | series tag  | tags_1           | Tags 1      | text      | text        |
| Yes      | series tag  | tags_2           | Tags 2      | text      | text        |
| Yes      | series tag  | website_url      | Website URL | url       | url         |
| Yes      | series tag  | photo_url        | Photo URL   | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:yj39-fr9e d:2013-08-21T06:56:00.000Z t:region=Adirondacks t:tags_1="Camping|Hotels & Motels|Restaurants|Snow Adventures" t:site_description="Campground, motel, restaurant and saloon. Paddle boat rentals, fishing, swimming, stocked fishing pond." t:tags_2="Hotels & Motels|Privately-owned Campgrounds|Pub|Skating" t:county="Warren County" t:website_url=http://www.halfmileranch.com t:site_title="1/2 Mile Ranch Camping Resort" m:row_number.yj39-fr9e=1

series e:yj39-fr9e d:2013-08-21T06:56:00.000Z t:region=Adirondacks t:tags_1="Animals|Snow Adventures" t:site_description="Summer and winter guided trail rides. Call for rates and availability." t:tags_2=Animals|Sleigh-rides t:county="Warren County" t:website_url=http://www.1000acres.com t:site_title="1000 Acres Horseback Riding" m:row_number.yj39-fr9e=2

series e:yj39-fr9e d:2013-08-21T06:56:00.000Z t:region=Adirondacks t:tags_1="Animals|Dude Ranches|Land Adventures|Snow Adventures|Sports & Gaming" t:site_description="An authentic dude ranch in the Adirondack Mountains of northern New York. Just minutes from Lake George. Horseback riding, wagon and surrey rides, golf and plenty of activities for the whole family. Free Wi-Fi. Live entertainment. Riding packages available. Guided snowmobile rides, weather permitting." t:tags_2="Dude Ranches|Horseback riding|Rodeos|Sleigh-rides|Snowmobiling" t:county="Warren County" t:website_url=http://www.1000acres.com t:site_title="1000 Acres Ranch Resort" m:row_number.yj39-fr9e=3
```

## Meta Commands

```ls
metric m:row_number.yj39-fr9e p:long l:"Row Number"

entity e:yj39-fr9e l:"I Love NY - See and Do" t:attribution="I Love NY" t:url=https://data.ny.gov/api/views/yj39-fr9e

property e:yj39-fr9e t:meta.view v:id=yj39-fr9e v:attributionLink=http://iloveny.com/what-to-do/see-and-do v:averageRating=0 v:name="I Love NY - See and Do" v:attribution="I Love NY"

property e:yj39-fr9e t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:yj39-fr9e t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:yj39-fr9e t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | region              | county                      | site_title                       | site_description                                                                                                                                                                                                                                                                                                                          | latitude           | longitude           | tags_1                                                               | tags_2                                                         | website_url                                  | photo_url    | 
| =========== | =================== | =========================== | ================================ | ========================================================================================================================================================================================================================================================================================================================================= | ================== | =================== | ==================================================================== | ============================================================== | ============================================ | ============ | 
| 1377068160  | Adirondacks         | Warren County               | 1/2 Mile Ranch Camping Resort    | Campground, motel, restaurant and saloon. Paddle boat rentals, fishing, swimming, stocked fishing pond.                                                                                                                                                                                                                                   | 43.336074000000004 | -73.839382099999995 | Camping|Hotels & Motels|Restaurants|Snow Adventures                  | Hotels & Motels|Privately-owned Campgrounds|Pub|Skating        | [http://www.halfmileranch.com, null]         | [null, null] | 
| 1377068160  | Adirondacks         | Warren County               | 1000 Acres Horseback Riding      | Summer and winter guided trail rides. Call for rates and availability.                                                                                                                                                                                                                                                                    | 43.4325677         | -73.868698600000002 | Animals|Snow Adventures                                              | Animals|Sleigh-rides                                           | [http://www.1000acres.com, null]             | [null, null] | 
| 1377068160  | Adirondacks         | Warren County               | 1000 Acres Ranch Resort          | An authentic dude ranch in the Adirondack Mountains of northern New York. Just minutes from Lake George. Horseback riding, wagon and surrey rides, golf and plenty of activities for the whole family. Free Wi-Fi. Live entertainment. Riding packages available. Guided snowmobile rides, weather permitting.                            | 43.4325677         | -73.868698600000002 | Animals|Dude Ranches|Land Adventures|Snow Adventures|Sports & Gaming | Dude Ranches|Horseback riding|Rodeos|Sleigh-rides|Snowmobiling | [http://www.1000acres.com, null]             | [null, null] | 
| 1377068160  | 1000 Islands-Seaway | Jefferson County            | 1000 Islands - Seaway Wine Trail | The 78 mile long trail meanders throughout Jefferson County and makes a terrific day trip from any of the area's hotels. The trail is marked by green grape cluster signs. The trail uses NY Routes 3, 180, 12, 26, 11, and 342. The Thousand Islands - Seaway Wine Trail is host to many events throughout the year.                     | 44.290894799999997 | -75.977672600000005 | Arts & Culture|Local food and drinks|Tours & Excursions              | Local food and drinks|Tours & Excursions|Wineries              | [http://www.tiswinetrail.com, null]          | [null, null] | 
| 1377068160  | 1000 Islands-Seaway | Jefferson County            | 1000 Islands Fishing Charters    | Fishing the St. Lawrence River in NY and Ontario. Guided drift fishing trips from $35. Nine complete package trips, including fishing, accommodations and meals. The most experienced and innovative charter service in the 1000 Islands. North American Fishing Club approved. Call toll free for our FREE Fishing Trip Planning Packet. | 44.242758000000002 | -76.086412899999999 | Water Adventures                                                     | Fishing                                                        | [http://www.1000-islands.com/fishing/, null] | [null, null] | 
| 1377068160  | 1000 Islands-Seaway | Jefferson County            | 1000 Islands Yacht Charter       | Private yacht charter for up to six passengers. Flexibility in scheduling, with 4-6 day cruise packages. Go to places unseen by most people: lighthouses, shipwrecks, Canadian and American ports, island parks, restaurants on the river, beautiful turnof the century homes and more.                                                   | 44.341909000000001 | -75.9144139         | Outdoor Guide Services|Tours & Excursions                            | Outdoor Guides                                                 | [http://1000islandsyachtcharter.com, null]   | [null, null] | 
| 1377068160  | Finger Lakes        | Steuben County              | 171 Cedar Arts Center            | Provides instructional programs in a wide variety of art forms, presents a diverse mix of performances and art exhibitions annually. Family friendly.                                                                                                                                                                                     | 42.140382000000002 | -77.0536879         | Museums                                                              | Art & Culture Museums|Performing Arts                          | [http://www.171cedararts.com, null]          | [null, null] | 
| 1377068160  | Central New York    | Montgomery County           | 1747 Nellis Tavern               | This Georgian home was built by prosperous 1710 Palatine German immigrant/farmer Christian Nellis, Sr. and was later enlarged to become a tavern on the Mohawk Turnpike after the Revolution. One of a few surviving wooden structures, it is being restored by the Palatine Settlement Society.                                          | 42.998311999999999 | -74.692200099999994 | History & Culture                                                    | Historic sites                                                 | [http://palatinesettlementsociety.org, null] | [null, null] | 
| 1377068160  | Central New York    | Herkimer County-Cen. Leath. | 1805 Frisbie House               | Restored historical home of Salisbury Historical Society. Colonial cheese making artifacts, iron mine exhibits and more.                                                                                                                                                                                                                  | 43.142896999999998 | -74.7859981         | History & Culture                                                    | Historic sites                                                 | [null, null]                                 | [null, null] | 
| 1377068160  | Hudson Valley       | Orange County               | 1809 House                       | Largest selection of restored antique oak furniture in tri-state area.                                                                                                                                                                                                                                                                    | 41.224111800000003 | -74.292792800000001 | Shopping                                                             | Antiques                                                       | [null, null]                                 | [null, null] | 
```