# State of Oregon Social Media Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-oregon-social-media-sites-14998) |
| Metadata | [Link](https://data.oregon.gov/api/views/hqhe-shsc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hqhe-shsc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hqhe-shsc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hqhe-shsc |
| Name | State of Oregon Social Media Sites |
| Attribution | Department of Administrative Services |
| Category | Administrative |
| Tags | oregon, social media, facebook, twitter, youtube, blog, flickr, slideshare |
| Created | 2011-09-22T15:41:01Z |
| Publication Date | 2017-02-02T18:35:32Z |

## Description

List of social media sites by agency

## Columns

```ls
| Included | Schema Type | Field Name              | Name                      | Data Type      | Render Type    |
| ======== | =========== | ======================= | ========================= | ============== | ============== |
| No       | time        | :updated_at             | updated_at                | meta_data      | meta_data      |
| Yes      | series tag  | agency_board_commission | Agency, Board, Commission | text           | text           |
| Yes      | series tag  | type_of_social_media    | Type of Social Media      | drop_down_list | drop_down_list |
| Yes      | series tag  | social_media_link       | Social Media Link         | url            | url            |
| Yes      | series tag  | description             | Description               | text           | text           |
| Yes      | series tag  | acronym                 | Acronym                   | text           | text           |
| Yes      | series tag  | active_inactive         | Active/Inactive           | drop_down_list | drop_down_list |
| Yes      | series tag  | type_of_agency          | Type of Agency            | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hqhe-shsc d:2011-09-22T08:41:04.000Z t:acronym="DAS (OEA)" t:description="A Blog of Oregon Economic News and Analysis" t:type_of_agency=b9hz-zyvx t:social_media_link=http://oregoneconomicanalysis.wordpress.com/ t:active_inactive=u82v-56bq t:type_of_social_media=p4uw-we3n t:agency_board_commission="Administrative Services" m:row_number.hqhe-shsc=1

series e:hqhe-shsc d:2011-09-22T08:41:04.000Z t:acronym="DAS (GEO)" t:description="Provides info on upcoming GIS-related events, new or updated datasets posted to the Spatial Data Library and any other info that may be relevant to Oregon's geospatial community." t:type_of_agency=b9hz-zyvx t:social_media_link=http://twitter.com/OregonGEO t:active_inactive=u82v-56bq t:type_of_social_media=ewvt-rsve t:agency_board_commission="Administrative Services" m:row_number.hqhe-shsc=2

series e:hqhe-shsc d:2011-09-22T08:41:04.000Z t:acronym="DAS (Surplus)" t:description="Used for advertising online auction sites, to spotlight auction items, notify of office closures, upcoming events, games and Oregon trivia." t:type_of_agency=b9hz-zyvx t:social_media_link="http://www.facebook.com/pages/State-of-Oregon-State-and-Federal-Surplus-Property-Program/178607196917?ref=mf" t:active_inactive=u82v-56bq t:type_of_social_media=riy5-du4v t:agency_board_commission="Administrative Services" m:row_number.hqhe-shsc=3
```

## Meta Commands

```ls
metric m:row_number.hqhe-shsc p:long l:"Row Number"

entity e:hqhe-shsc l:"State of Oregon Social Media Sites" t:attribution="Department of Administrative Services" t:url=https://data.oregon.gov/api/views/hqhe-shsc

property e:hqhe-shsc t:meta.view v:id=hqhe-shsc v:category=Administrative v:attributionLink=http://oregon.gov/social_media.shtml v:averageRating=0 v:name="State of Oregon Social Media Sites" v:attribution="Department of Administrative Services"

property e:hqhe-shsc t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:hqhe-shsc t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| :updated_at | agency_board_commission | type_of_social_media | social_media_link                                                                                                                                                          | description                                                                                                                                                                        | acronym       | active_inactive | type_of_agency | 
| =========== | ======================= | ==================== | ========================================================================================================================================================================== | ================================================================================================================================================================================== | ============= | =============== | ============== | 
| 1316680864  | Administrative Services | p4uw-we3n            | [http://oregoneconomicanalysis.wordpress.com/, Oregon Office of Economic Analysis]                                                                                         | A Blog of Oregon Economic News and Analysis                                                                                                                                        | DAS (OEA)     | u82v-56bq       | b9hz-zyvx      | 
| 1316680864  | Administrative Services | ewvt-rsve            | [http://twitter.com/OregonGEO, OregonGEO]                                                                                                                                  | Provides info on upcoming GIS-related events, new or updated datasets posted to the Spatial Data Library and any other info that may be relevant to Oregon's geospatial community. | DAS (GEO)     | u82v-56bq       | b9hz-zyvx      | 
| 1316680864  | Administrative Services | riy5-du4v            | [http://www.facebook.com/pages/State-of-Oregon-State-and-Federal-Surplus-Property-Program/178607196917?ref=mf, State of Oregon State and Federal Surplus Property Program] | Used for advertising online auction sites, to spotlight auction items, notify of office closures, upcoming events, games and Oregon trivia.                                        | DAS (Surplus) | u82v-56bq       | b9hz-zyvx      | 
| 1316680864  | Agriculture             | ewvt-rsve            | [http://twitter.com/ORagriculture, Oregon Department of Agriculture]                                                                                                       | News releases, "Story of the Week," and timely information from ODA                                                                                                                | ODA           | u82v-56bq       | b9hz-zyvx      | 
| 1316680864  | Agriculture             | yh4b-jiu3            | [http://www.youtube.com/user/ORGovODA, Oregon Department of Agriculture]                                                                                                   | ODA and agriculture on video: see it now, hear it now                                                                                                                              | ODA           | u82v-56bq       | b9hz-zyvx      | 
| 1316680864  | Albany                  | riy5-du4v            | [http://facebook.com/cityofalbany, City of Albany, Oregon Facebook fan page]                                                                                               | Official Facebook page of the City of Albany, Oregon.                                                                                                                              | Albany        | u82v-56bq       | mn57-6app      | 
| 1316680864  | Albany                  | riy5-du4v            | [http://facebook.com/albanyparksandrecreation, Albany Parks & Recreation Facebook Fan page]                                                                                | Albany Parks and Recreation                                                                                                                                                        | Albany        | u82v-56bq       | mn57-6app      | 
| 1316680864  | Albany                  | riy5-du4v            | [http://facebook.com/cityofalbanyhr, City of Albany Human Resources Facebook Fan page]                                                                                     | Current job opportunities with the City of Albany, Oregon                                                                                                                          | Albany        | u82v-56bq       | mn57-6app      | 
| 1316680864  | Albany                  | 63wd-t6se            | [http://www.flickr.com/photos/cityofalbanyoregon, City of Albany Flickr]                                                                                                   | Images of and from the City of Albany                                                                                                                                              | Albany        | u82v-56bq       | mn57-6app      | 
| 1316680864  | Albany                  | ewvt-rsve            | [http://twitter.com/cityofalbany, City of Albany Twitter]                                                                                                                  | Official Twitter feed for the City of Albany, Oregon                                                                                                                               | Albany        | u82v-56bq       | mn57-6app      | 
```