# Designated Scenic Byways

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/designated-scenic-byways) |
| Metadata | [Link](https://data.ny.gov/api/views/q8sd-9bib) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q8sd-9bib/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q8sd-9bib/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q8sd-9bib |
| Name | Designated Scenic Byways |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | scenic byways, national scenic byways, new york state scenic byways, cmp, corridor management plan, scenic roads, all american road |
| Created | 2013-02-14T21:48:27Z |
| Publication Date | 2013-03-01T15:51:34Z |

## Description

The New York State Scenic Byways program was created in 1992 by the State Legislature. The program encourages both economic development and resource conservation, recognizing that each of these aspects of a byway must be fostered to ensure the success of the other. This dataset is a listing of all designated State and National Scenic Byways in New York State with Scenic Byway Corridor Management Plans: Includes location, length, route description, designation and website. Information is current as of the publication date.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | scenic_byway             | Scenic Byway               | text      | text        |
| Yes      | numeric metric | approximate_length_miles | Approximate Length (Miles) | number    | number      |
| Yes      | series tag     | region                   | Region                     | text      | text        |
| Yes      | series tag     | connects                 | Connects                   | text      | text        |
| Yes      | series tag     | primary_designation      | Primary Designation        | text      | text        |
| Yes      | series tag     | secondary_designation    | Secondary Designation      | text      | text        |
| Yes      | series tag     | tertiary_designation     | Tertiary Designation       | text      | text        |
| Yes      | series tag     | for_more_information_url | For more information (URL) | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region="Great Lakes/ Canadian Border" t:for_more_information_url=http://www.seawaytrail.com/ t:primary_designation="National Scenic Byway (National Designation)" t:secondary_designation="State Scenic Byway" t:scenic_byway="Great Lakes Seaway Trail" t:connects="Ripley and Massena" m:approximate_length_miles=454

series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region="Champlain and Hudson Valleys" t:for_more_information_url=http://www.lakestolocks.org/ t:primary_designation="All-American Road (National Designation)" t:secondary_designation="State Scenic Byway" t:scenic_byway="Lakes to Locks Passage" t:connects="Canadian Border and Waterford" m:approximate_length_miles=225

series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region=Adirondacks t:for_more_information_url=http://www.adirondackscenicbyways.org/byway/adirondack-trail.html t:primary_designation="State Scenic Byway" t:scenic_byway="Adirondack Trail" t:connects="Fonda and Malone" m:approximate_length_miles=179
```

## Meta Commands

```ls
metric m:approximate_length_miles p:integer l:"Approximate Length (Miles)" d:"Approximate total length of the byway measured in miles." t:dataTypeName=number

entity e:q8sd-9bib l:"Designated Scenic Byways" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/q8sd-9bib

property e:q8sd-9bib t:meta.view d:2017-06-09T13:54:59.154Z v:id=q8sd-9bib v:category=Transportation v:attributionLink=https://www.dot.ny.gov/display/programs/scenic-byways v:averageRating=0 v:name="Designated Scenic Byways" v:attribution="New York State Department of Transportation"

property e:q8sd-9bib t:meta.view.owner d:2017-06-09T13:54:59.154Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q8sd-9bib t:meta.view.tableauthor d:2017-06-09T13:54:59.154Z v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:q8sd-9bib t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:54:59.154Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | scenic_byway                            | approximate_length_miles | region                       | connects                       | primary_designation                          | secondary_designation | tertiary_designation | for_more_information_url                                                                                               | 
| =========== | ======================================= | ======================== | ============================ | ============================== | ============================================ | ===================== | ==================== | ====================================================================================================================== | 
| 1360849709  | Great Lakes Seaway Trail                | 454                      | Great Lakes/ Canadian Border | Ripley and Massena             | National Scenic Byway (National Designation) | State Scenic Byway    |                      | [http://www.seawaytrail.com/, null]                                                                                    | 
| 1360849709  | Lakes to Locks Passage                  | 225                      | Champlain and Hudson Valleys | Canadian Border and Waterford  | All-American Road (National Designation)     | State Scenic Byway    |                      | [http://www.lakestolocks.org/, null]                                                                                   | 
| 1360849709  | Adirondack Trail                        | 179                      | Adirondacks                  | Fonda and Malone               | State Scenic Byway                           |                       |                      | [http://www.adirondackscenicbyways.org/byway/adirondack-trail.html, null]                                              | 
| 1360849709  | Black River Trail                       | 95                       | Adirondacks                  | Rome and Dexter                | State Scenic Byway                           |                       |                      | [http://www.tughill.org/about/tug-hill-commission/projects/black-river-projects/black-river-trail-scenic-byway/, null] | 
| 1360849709  | Cayuga Lake Scenic Byway                | 87                       | Finger Lakes                 | Loop around Cayuga Lake        | State Scenic Byway                           |                       |                      | [http://www.fingerlakes.org/things-to-do/attractions/wineries-more/cayuga-lake-scenic-byway, null]                     | 
| 1360849709  | Central Adirondack Trail                | 153                      | Adirondacks                  | Rome and Glens Falls           | State Scenic Byway                           |                       |                      | [http://www.adirondackscenicbyways.org/byway/central-adirondack-trail.html, null]                                      | 
| 1360849709  | Dude Ranch Trail/First Wilderness Byway | 40                       | Adirondacks                  | Loop in Lake George Region     | State Scenic Byway                           |                       |                      | [https://www.dot.ny.gov/display/programs/scenic-byways/dude-ranch-trail, null]                                         | 
| 1360849709  | Military Trail/North Country Byway      | 84                       | Adirondacks                  | Rouses Point and Massena       | State Scenic Byway                           |                       |                      | [https://www.dot.ny.gov/display/programs/scenic-byways/military-trail, null]                                           | 
| 1360849709  | North Fork Trail                        | 36                       | Long Island                  | Southhold to Orient Point      | State Scenic Byway                           |                       |                      | [http://www.northfork.org/, null]                                                                                      | 
| 1360849709  | Olympic Trail                           | 168                      | Adirondacks                  | Keeseveille and Sackets Harbor | State Scenic Byway                           |                       |                      | [http://www.adirondackscenicbyways.org/byway/olympic-trail.html, null]                                                 | 
```