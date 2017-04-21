# King County Social Media

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-social-media-6b32c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/rfcd-nnxe) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/rfcd-nnxe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/rfcd-nnxe/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | rfcd-nnxe |
| Name | King County Social Media |
| Attribution | King County |
| Category | Government |
| Tags | social media, flickr, facebook, twitter, pinterest, blog, wordpress, youtube, feed |
| Created | 2013-08-25T21:45:21Z |
| Publication Date | 2013-10-31T17:11:09Z |

## Description

List of social media presences maintained by King County agencies and officials

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | king_county_agency | King County agency | text      | text        |
| Yes      | series tag  | facebook           | Facebook           | url       | url         |
| Yes      | series tag  | twitter            | Twitter            | url       | url         |
| Yes      | series tag  | blog               | Blog               | url       | url         |
| Yes      | series tag  | flickr             | Flickr             | url       | url         |
| Yes      | series tag  | pinterest          | Pinterest          | url       | url         |
| Yes      | series tag  | youtube            | YouTube            | url       | url         |
| Yes      | series tag  | show_on_news_page  | Show on news page  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rfcd-nnxe d:2013-08-27T15:29:36.000Z t:king_county_agency="KC General Information" t:flickr=http://www.flickr.com/photos/kingcounty/ t:twitter=http://twitter.com/#!/kcnews/ t:show_on_news_page=true t:facebook=https://www.facebook.com/KingCountyWA t:pinterest=http://www.pinterest.com/kingcountywa m:row_number.rfcd-nnxe=1

series e:rfcd-nnxe d:2013-08-27T15:29:39.000Z t:king_county_agency="Executive Constantine" t:twitter=http://twitter.com/#!/kcexec t:show_on_news_page=true t:facebook=http://www.facebook.com/ExecutiveConstantine m:row_number.rfcd-nnxe=2

series e:rfcd-nnxe d:2013-08-27T15:29:44.000Z t:king_county_agency="King County Council" t:twitter=http://twitter.com/#!/kccouncil t:show_on_news_page=true t:facebook=http://www.facebook.com/pages/King-County-Council/40329284231 m:row_number.rfcd-nnxe=3
```

## Meta Commands

```ls
metric m:row_number.rfcd-nnxe p:long l:"Row Number"

entity e:rfcd-nnxe l:"King County Social Media" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/rfcd-nnxe

property e:rfcd-nnxe t:meta.view v:id=rfcd-nnxe v:category=Government v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="King County Social Media" v:attribution="King County"

property e:rfcd-nnxe t:meta.view.license v:name="Public Domain"

property e:rfcd-nnxe t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:rfcd-nnxe t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | king_county_agency     | facebook                                                                               | twitter                                      | blog                                                                     | flickr                                                 | pinterest                                          | youtube                                                    | show_on_news_page | 
| =========== | ====================== | ====================================================================================== | ============================================ | ======================================================================== | ====================================================== | ================================================== | ========================================================== | ================= | 
| 1377617376  | KC General Information | [https://www.facebook.com/KingCountyWA, Facebook]                                      | [http://twitter.com/#!/kcnews/, Twitter]     | [null, null]                                                             | [http://www.flickr.com/photos/kingcounty/, Flickr]     | [http://www.pinterest.com/kingcountywa, Pinterest] | [null, null]                                               | true              | 
| 1377617379  | Executive Constantine  | [http://www.facebook.com/ExecutiveConstantine, Facebook]                               | [http://twitter.com/#!/kcexec, Twitter]      | [null, null]                                                             | [null, null]                                           | [null, null]                                       | [null, null]                                               | true              | 
| 1377617384  | King County Council    | [http://www.facebook.com/pages/King-County-Council/40329284231, Facebook]              | [http://twitter.com/#!/kccouncil, Twitter]   | [null, null]                                                             | [null, null]                                           | [null, null]                                       | [null, null]                                               | true              | 
| 1377617385  | Metro Transit          | [http://www.facebook.com/kcmetro, Facebook]                                            | [http://twitter.com/#!/kcmetrobus, Twitter]  | [http://metrocommute.wordpress.com/, Blog]                               | [null, null]                                           | [null, null]                                       | [null, null]                                               | true              | 
| 1377617385  | KCDOT                  | [null, null]                                                                           | [null, null]                                 | [null, null]                                                             | [http://www.flickr.com/photos/kingcountygov/, Flickr]  | [null, null]                                       | [http://www.youtube.com/user/KCDOTVideo, YouTube]          | true              | 
| 1377617385  | Parks                  | [http://www.facebook.com/iheartkcparks, Facebook]                                      | [null, null]                                 | [http://kingcountyparks.wordpress.com/, Blog]                            | [http://www.flickr.com/photos/kingcountyparks, Flickr] | [null, null]                                       | [null, null]                                               | true              | 
| 1377617386  | Public Health          | [http://www.facebook.com/KCPubHealth, Facebook]                                        | [http://twitter.com/#!/KCPubHealth, Twitter] | [null, null]                                                             | [null, null]                                           | [null, null]                                       | [http://www.youtube.com/kcpublichealth, YouTube]           | true              | 
| 1377617386  | EcoConsumer            | [http://www.facebook.com/ecoconsumer, Facebook]                                        | [http://twitter.com/#!/ecoconsumer, Twitter] | [http://your.kingcounty.gov/solidwaste/ecoconsumer/blog.asp?ID=90, Blog] | [null, null]                                           | [null, null]                                       | [http://www.youtube.com/user/EcoConsumer, YouTube]         | true              | 
| 1377617386  | Green Teams            | [http://www.facebook.com/pages/King-County-Green-Teams/103323057509?sk=wall, Facebook] | [null, null]                                 | [null, null]                                                             | [null, null]                                           | [null, null]                                       | [null, null]                                               | true              | 
| 1377617386  | Recycle More           | [http://www.facebook.com/recyclemore, Facebook]                                        | [null, null]                                 | [null, null]                                                             | [null, null]                                           | [null, null]                                       | [http://www.youtube.com/user/KingCountyRecycling, YouTube] | true              | 
```