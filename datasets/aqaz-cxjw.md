# Social Media - Top Commenters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/social-media-top-commenters) |
| Metadata | [Link](https://data.austintexas.gov/api/views/aqaz-cxjw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/aqaz-cxjw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/aqaz-cxjw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | aqaz-cxjw |
| Name | Social Media - Top Commenters |
| Attribution | Communications and Public Information Office |
| Category | Government |
| Tags | social media, facebook, twitter, commenter, comment, fan, fans, followers |
| Created | 2015-07-16T19:38:39Z |
| Publication Date | 2015-07-16T19:42:03Z |

## Description

Data from Archive Social platform captures top commenters on City of Austin social media and qualitative observations about their interest areas. Reporting period: April 5, 2015 to July 5, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | commenter             | Commenter             | text      | text        |
| Yes      | numeric metric | mentions              | Mentions              | number    | number      |
| Yes      | numeric metric | direct_messages       | Direct Messages       | number    | number      |
| Yes      | numeric metric | wall_comments         | Wall Comments         | number    | number      |
| Yes      | numeric metric | photo_comments        | Photo Comments        | number    | number      |
| Yes      | numeric metric | number_of_followers   | Number of Followers   | number    | number      |
| Yes      | series tag     | platform              | Platform              | text      | text        |
| Yes      | series tag     | general_interest_area | General Interest Area | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:aqaz-cxjw d:2015-07-16T12:39:07.000Z t:platform=TWITTER t:general_interest_area="General City news." t:commenter=ATXhipsters m:direct_messages=0 m:number_of_followers=23700 m:mentions=305 m:wall_comments=0 m:photo_comments=0

series e:aqaz-cxjw d:2015-07-16T12:39:07.000Z t:platform=TWITTER t:general_interest_area="Issues affecting visually-impaired Austinites." t:commenter="Anna M'" m:direct_messages=36 m:number_of_followers=838 m:mentions=0 m:wall_comments=0 m:photo_comments=0

series e:aqaz-cxjw d:2015-07-16T12:39:07.000Z t:platform=FACEBOOK t:commenter="Catherine Victor" m:direct_messages=0 m:number_of_followers=0 m:mentions=0 m:wall_comments=84 m:photo_comments=1
```

## Meta Commands

```ls
metric m:mentions p:integer l:Mentions t:dataTypeName=number

metric m:direct_messages p:integer l:"Direct Messages" t:dataTypeName=number

metric m:wall_comments p:integer l:"Wall Comments" t:dataTypeName=number

metric m:photo_comments p:integer l:"Photo Comments" t:dataTypeName=number

metric m:number_of_followers p:integer l:"Number of Followers" t:dataTypeName=number

entity e:aqaz-cxjw l:"Social Media - Top Commenters" t:attribution="Communications and Public Information Office" t:url=https://data.austintexas.gov/api/views/aqaz-cxjw

property e:aqaz-cxjw t:meta.view v:id=aqaz-cxjw v:category=Government v:attributionLink=http://www.austintexas.gov/social v:averageRating=0 v:name="Social Media - Top Commenters" v:attribution="Communications and Public Information Office"

property e:aqaz-cxjw t:meta.view.license v:name="Public Domain"

property e:aqaz-cxjw t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:aqaz-cxjw t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | commenter            | mentions | direct_messages | wall_comments | photo_comments | number_of_followers | platform | general_interest_area                                                | 
| =========== | ==================== | ======== | =============== | ============= | ============== | =================== | ======== | ==================================================================== | 
| 1437050347  | ATXhipsters          | 305      | 0               | 0             | 0              | 23700               | TWITTER  | General City news.                                                   | 
| 1437050347  | Anna M'              | 0        | 36              | 0             | 0              | 838                 | TWITTER  | Issues affecting visually-impaired Austinites.                       | 
| 1437050347  | Catherine Victor     | 0        | 0               | 84            | 1              | 0                   | FACEBOOK |                                                                      | 
| 1437050347  | Telemundo Austin     | 75       | 0               | 0             | 0              | 2287                | TWITTER  | Primarily public safety information in Spanish.                      | 
| 1437050347  | KXAN News            | 67       | 0               | 0             | 0              | 75200               | TWITTER  | General City news, particularly APD updates.                         | 
| 1437050347  | Philip Jankowski     | 55       | 0               | 0             | 0              | 1923                | TWITTER  | Police, Fire and EMS news and information.                           | 
| 1437050347  | SocialRugrats Austin | 52       | 0               | 0             | 0              | 7083                | TWITTER  | Family-friendly events in Austin.                                    | 
| 1437050347  | Great NAGW Tweets    | 50       | 0               | 0             | 0              | 59                  | TWITTER  | Sharing great Tweet ideas with other governments throughout the U.S. | 
| 1437050347  | Joe Taylor           | 46       | 0               | 0             | 0              | 1610                | TWITTER  | Emergency dispatch information and its affect on traffic.            | 
| 1437050347  | Developer Boost      | 43       | 0               | 0             | 0              | 640                 | TWITTER  | APD and its relationship with the community                          | 
```