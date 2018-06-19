# Category Tiles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/category-tiles) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jukz-za6j) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jukz-za6j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jukz-za6j/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jukz-za6j |
| Name | Category Tiles |
| Created | 2016-05-02T21:19:10Z |
| Publication Date | 2016-06-23T18:07:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | order          | order          | number    | number      |
| Yes      | series tag     | title_en       | title_en       | text      | text        |
| Yes      | series tag     | icon           | icon           | text      | text        |
| Yes      | series tag     | link           | link           | text      | text        |
| Yes      | series tag     | description_en | description_en | text      | text        |
| Yes      | series tag     | tile_color     | Tile Color     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jukz-za6j d:2016-05-05T12:54:04.000Z t:icon=&#xE7A0; t:title_en="All Data" t:description_en="Search our entire catalog of datasets, charts, maps and so much more!" t:tile_color=#326d89 t:link=https://data.austintexas.gov/browse m:order=1

series e:jukz-za6j d:2016-05-05T12:54:04.000Z t:icon=&#x21BB; t:title_en="New Data" t:description_en="Access the newest data in our catalog" t:tile_color=#326d89 t:link="https://data.austintexas.gov/browse?sortBy=newest" m:order=2

series e:jukz-za6j d:2016-05-05T12:54:04.000Z t:icon=&#xEB82; t:title_en="Recently Updated Data" t:description_en="View the latest modified data in our catalog" t:tile_color=#326d89 t:link="https://data.austintexas.gov/browse?sortBy=last_modified" m:order=3
```

## Meta Commands

```ls
metric m:order p:integer l:order t:dataTypeName=number

entity e:jukz-za6j l:"Category Tiles" t:url=https://data.austintexas.gov/api/views/jukz-za6j

property e:jukz-za6j t:meta.view v:id=jukz-za6j v:averageRating=0 v:name="Category Tiles"

property e:jukz-za6j t:meta.view.owner v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"

property e:jukz-za6j t:meta.view.tableauthor v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"
```

## Top Records

```ls
| :updated_at | order | title_en               | icon | link                                                        | description_en                                                                                                         | tile_color | 
| =========== | ===== | ====================== | ==== | =========================================================== | ====================================================================================================================== | ========== | 
| 1462452844  | 1     | All Data               | ?    | https://data.austintexas.gov/browse                         | Search our entire catalog of datasets, charts, maps and so much more!                                                  | #326d89    | 
| 1462452844  | 2     | New Data               | ?    | https://data.austintexas.gov/browse?sortBy=newest           | Access the newest data in our catalog                                                                                  | #326d89    | 
| 1462452844  | 3     | Recently Updated Data  | ?    | https://data.austintexas.gov/browse?sortBy=last_modified    | View the latest modified data in our catalog                                                                           | #326d89    | 
| 1462452844  | 4     | Most Popular Data      | ?    | https://data.austintexas.gov/browse?sortBy=most_accessed    | Get the most accessed data from our catalog                                                                            | #326d89    | 
| 1462452844  | 6     | Health                 | ?    | https://data.austintexas.gov/browse?category=Health         | Data on public health, code enforcement, including animal, health and library services provided to the community       | #326d89    | 
| 1462452844  | 7     | Neighborhood           | ?    | https://data.austintexas.gov/browse?category=Neighborhood   | Data on public spaces, housing, neighborhood planning and real estate services                                         | #326d89    | 
| 1462452844  | 8     | Public Safety          | ?   | https://data.austintexas.gov/browse?category=Public+Safety  | Data on police arrests, fire incidents, EMS and municipal court cases                                                  | #326d89    | 
| 1462452844  | 11    | City Council Resources | ?   | http://austintexas.gov/ogcr                                 | Get information about Austin City Council, including information about open meetings and public information requests   | #723d39    | 
| 1462452844  | 12    | Austin's App Library   | ?    | http://austintexas.gov/page/mobile-app-library              | This library has cool apps created with public datasets by independent civic application developers and City employees | #61641c    | 
| 1462802208  | 9     | Austin Finance Online  | ?    | https://www.ci.austin.tx.us/financeonline/finance/index.cfm | Austin Finance Online is an award winning tool that allows you to access city financial and purchasing data online     | #A75926    | 
```