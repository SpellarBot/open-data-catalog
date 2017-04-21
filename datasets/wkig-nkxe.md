# Hudson River Valley Greenway Water Trail Designated Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hudson-river-valley-greenway-water-trail-designated-sites) |
| Metadata | [Link](https://data.ny.gov/api/views/wkig-nkxe) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wkig-nkxe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wkig-nkxe/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wkig-nkxe |
| Name | Hudson River Valley Greenway Water Trail Designated Sites |
| Attribution | Hudson River Valley Greenway |
| Category | Recreation |
| Tags | water trail, greenway, kayaking, boating, national heritage area |
| Created | 2014-02-04T14:45:54Z |
| Publication Date | 2014-04-21T15:26:12Z |

## Description

A listing of sites designated as part of the Hudson River Greenway Water Trail? National Water Trail

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | site_name_community_county   | Site                         | text      | text        |
| Yes      | series tag     | community                    | Community                    | text      | text        |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | numeric metric | statute_mile                 | Statute Mile                 | number    | number      |
| Yes      | series tag     | riverbank                    | Riverbank                    | text      | text        |
| No       |                | latitude                     | Latitude                     | number    | number      |
| No       |                | longitude                    | Longitude                    | number    | number      |
| Yes      | series tag     | cartop_launch                | Cartop Launch                | text      | text        |
| Yes      | series tag     | trailered_launch             | Trailered Launch             | text      | text        |
| Yes      | series tag     | campsite                     | Campsite                     | text      | text        |
| Yes      | series tag     | day_use_site                 | Day Use Site                 | text      | text        |
| Yes      | numeric metric | kayak_storage_racks          | Kayak Storage Racks          | number    | number      |
| Yes      | series tag     | restroom_privy               | Restroom/Privy               | text      | text        |
| Yes      | series tag     | picnicking_grills            | Picnicking/Grills            | text      | text        |
| Yes      | series tag     | dining_restaurant            | Dining/Restaurant            | text      | text        |
| Yes      | series tag     | retail_supplies              | Retail/Supplies              | text      | text        |
| Yes      | series tag     | lodging                      | Lodging                      | text      | text        |
| Yes      | series tag     | bus_service                  | Bus Service                  | text      | text        |
| Yes      | series tag     | train_service                | Train Service                | text      | text        |
| Yes      | series tag     | trail                        | Trail                        | text      | text        |
| Yes      | series tag     | swimming                     | Swimming                     | text      | text        |
| Yes      | series tag     | fishing                      | Fishing                      | text      | text        |
| Yes      | series tag     | hunting                      | Hunting                      | text      | text        |
| Yes      | series tag     | trapping                     | Trapping                     | text      | text        |
| Yes      | series tag     | bird_watching                | Bird Watching                | text      | text        |
| Yes      | series tag     | golf                         | Golf                         | text      | text        |
| Yes      | series tag     | concerts_events              | Concerts/events              | text      | text        |
| Yes      | series tag     | playground                   | Playground                   | text      | text        |
| Yes      | series tag     | tour_boat_service            | Tour Boat Service            | text      | text        |
| Yes      | series tag     | natural_cultural_resources   | Natural & Cultural Resources | text      | text        |
| Yes      | series tag     | historic_resources           | Historic Resources           | text      | text        |
| Yes      | series tag     | visitor_nature_center_museum | Visitor-Nature Center/Museum | text      | text        |
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
series e:wkig-nkxe d:2014-04-18T10:00:29.000Z t:site_name_community_county="Whitehall Harbor" t:day_use_site=DU t:county=Washington t:community="Village of Whitehall" t:fishing=Y t:cartop_launch=HL t:trailered_launch=TL t:riverbank=W m:statute_mile=218.03

series e:wkig-nkxe d:2014-04-18T10:00:29.000Z t:site_name_community_county="Fort Ann South of Lock C-11" t:day_use_site=DU t:county=Washington t:community="Town of Fort Ann" t:fishing=Y t:cartop_launch=HL t:trailered_launch=TL t:riverbank=W m:statute_mile=211.3

series e:wkig-nkxe d:2014-04-18T10:00:29.000Z t:picnicking_grills=Y t:site_name_community_county="Fort Ann Landing Clay Hill Rd" t:day_use_site=DU t:county=Washington t:community="Town of Fort Ann" t:fishing=Y t:cartop_launch=HL t:riverbank=W m:statute_mile=207.2
```

## Meta Commands

```ls
metric m:statute_mile p:float l:"Statute Mile" d:"Statute miles above Battery in NYC" t:dataTypeName=number

metric m:kayak_storage_racks p:integer l:"Kayak Storage Racks" d:"1 or 2 = the number it has, blank it has none" t:dataTypeName=number

entity e:wkig-nkxe l:"Hudson River Valley Greenway Water Trail Designated Sites" t:attribution="Hudson River Valley Greenway" t:url=https://data.ny.gov/api/views/wkig-nkxe

property e:wkig-nkxe t:meta.view v:id=wkig-nkxe v:category=Recreation v:attributionLink=http://www.hudsongreenway.ny.gov/Trailsandscenicbyways/watertrail/WTDesSites.aspx v:averageRating=0 v:name="Hudson River Valley Greenway Water Trail Designated Sites" v:attribution="Hudson River Valley Greenway"

property e:wkig-nkxe t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wkig-nkxe t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:wkig-nkxe t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | site_name_community_county                                 | community                | county     | statute_mile | riverbank | latitude  | longitude  | cartop_launch | trailered_launch | campsite | day_use_site | kayak_storage_racks | restroom_privy | picnicking_grills | dining_restaurant | retail_supplies | lodging | bus_service | train_service | trail | swimming | fishing | hunting | trapping | bird_watching | golf | concerts_events | playground | tour_boat_service | natural_cultural_resources | historic_resources | visitor_nature_center_museum | 
| =========== | ========================================================== | ======================== | ========== | ============ | ========= | ========= | ========== | ============= | ================ | ======== | ============ | =================== | ============== | ================= | ================= | =============== | ======= | =========== | ============= | ===== | ======== | ======= | ======= | ======== | ============= | ==== | =============== | ========== | ================= | ========================== | ================== | ============================ | 
| 1397815229  | Whitehall Harbor                                           | Village of Whitehall     | Washington | 218.03       | W         | 43.550833 | -73.402222 | HL            | TL               |          | DU           |                     |                |                   |                   |                 |         |             |               |       |          | Y       |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Fort Ann South of Lock C-11                                | Town of Fort Ann         | Washington | 211.3        | W         | 43.459444 | -73.441111 | HL            | TL               |          | DU           |                     |                |                   |                   |                 |         |             |               |       |          | Y       |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Fort Ann Landing Clay Hill Rd                              | Town of Fort Ann         | Washington | 207.2        | W         | 43.413889 | -73.485278 | HL            |                  |          | DU           |                     |                | Y                 |                   |                 |         |             |               |       |          | Y       |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Kingsbury Lock C-9 Access Road                             | Town of Kingsbury        | Washington | 203.1        | W         | 43.355278 | -73.495    | HL            |                  |          | DU           |                     |                |                   |                   |                 |         |             |               |       |          |         |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Village of Ft Edward Beach                                 | Village of Fort Edward   | Saratoga   | 195.8        | W         | 43.266944 | -73.590833 |               |                  |          |              |                     |                |                   |                   |                 |         |             |               |       |          |         |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Fort Edward, Lock C-7 lower end                            | Village of Fort Edward   | Saratoga   | 194.7        | E         | 43.255556 | -73.585    | HL            | TL               |          | DU           |                     |                | Y                 |                   |                 |         |             |               |       |          | Y       |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Fort Miller, North of Lock C-6                             | Town of Fort Edward      | Washington | 188.3        | E         | 43.17     | -73.579444 | HL            |                  |          | DU           |                     |                | Y                 |                   |                 |         |             |               |       |          |         |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Alfred Z. Solomon Launch at Hudson Crossing Park, Lock C-5 | Town of Saratoga         | Saratoga   | 184.04       | W         | 43.113056 | -73.576944 | HL            |                  |          | DU           | 1                   | Y              | Y                 |                   |                 |         |             |               | Y     |          | Y       |         |          | Y             |      |                 | Y          | Y                 | Y                          | Y                  |                              | 
| 1397815229  | Schuyler Park                                              | Village of Schuylerville | Saratoga   | 183.2        | W         | 43.101944 | -73.575556 | HL            | TL               | C        | DU           |                     |                |                   |                   |                 |         |             |               |       |          | Y       |         |          |               |      |                 |            |                   |                            |                    |                              | 
| 1397815229  | Fort Hardy Park                                            | Village of Schuylerville | Saratoga   | 182.9        | W         | 43.099167 | -73.576111 | HL            |                  | C        | DU           |                     | Y              | Y                 | Y                 | Y               |         |             |               | Y     |          | Y       |         |          | Y             |      | Y               | Y          |                   | Y                          | Y                  | Y                            | 
```