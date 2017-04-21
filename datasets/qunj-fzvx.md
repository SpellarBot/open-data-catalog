# Austin Public Library Social Media Presence

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-public-library-social-media-presence) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qunj-fzvx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qunj-fzvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qunj-fzvx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qunj-fzvx |
| Name | Austin Public Library Social Media Presence |
| Attribution | Austin Public Library |
| Category | Fun |
| Tags | library, social media |
| Created | 2015-07-09T18:37:07Z |
| Publication Date | 2016-11-04T20:09:22Z |

## Description

The Austin Public Library maintains several social networking sites. Various Library staff are responsible for overall administration of these sites. The mission of these social networking sites is to promote Austin Public Library's resources and services. These sites might include thematic item lists from our collection; topics related to today's events and news; research tips; field trips to other libraries; Texas authors and artists; photos; videos; and library trends.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | social_media | Social Media | text      | text        |
| Yes      | series tag  | link         | Link         | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qunj-fzvx d:2016-11-04T20:08:53.000Z t:social_media="Austin Public Library Facebook" t:link=https://www.facebook.com/AustinLibrary m:row_number.qunj-fzvx=1

series e:qunj-fzvx d:2016-11-04T20:08:53.000Z t:social_media="Austin Public Library Twitter" t:link=https://twitter.com/AustinPublicLib m:row_number.qunj-fzvx=2

series e:qunj-fzvx d:2016-11-04T20:08:53.000Z t:social_media="Austin Public Library Google+" t:link=https://plus.google.com/116195613010459749637/posts m:row_number.qunj-fzvx=3
```

## Meta Commands

```ls
metric m:row_number.qunj-fzvx p:long l:"Row Number"

entity e:qunj-fzvx l:"Austin Public Library Social Media Presence" t:attribution="Austin Public Library" t:url=https://data.austintexas.gov/api/views/qunj-fzvx

property e:qunj-fzvx t:meta.view v:id=qunj-fzvx v:category=Fun v:averageRating=0 v:name="Austin Public Library Social Media Presence" v:attribution="Austin Public Library"

property e:qunj-fzvx t:meta.view.license v:name="Public Domain"

property e:qunj-fzvx t:meta.view.owner v:id=knx5-5zd7 v:screenName=Sarah v:displayName=Sarah

property e:qunj-fzvx t:meta.view.tableauthor v:id=knx5-5zd7 v:screenName=Sarah v:roleName=editor_stories v:displayName=Sarah
```

## Top Records

```ls
| :updated_at | social_media                             | link                                                        | 
| =========== | ======================================== | =========================================================== | 
| 1478290133  | Austin Public Library Facebook           | [https://www.facebook.com/AustinLibrary, null]              | 
| 1478290133  | Austin Public Library Twitter            | [https://twitter.com/AustinPublicLib, null]                 | 
| 1478290133  | Austin Public Library Google+            | [https://plus.google.com/116195613010459749637/posts, null] | 
| 1478290133  | Austin Public Library YouTube            | [http://www.youtube.com/user/aplacmc, null]                 | 
| 1478290133  | Austin Public Library Flickr             | [https://www.flickr.com/photos/123672095@N02, null]         | 
| 1478290133  | Austin Public Library Instagram          | [http://instagram.com/austinpubliclibrary, null]            | 
| 1478290133  | Austin Public Library Soundcloud         | [https://soundcloud.com/austin-public-library, null]        | 
| 1478290133  | La Biblioteca P?blica de Austin Facebook | [https://www.facebook.com/bibliotecapublicadeaustin, null]  | 
| 1478290133  | La Biblioteca P?blica de Austin Twitter  | [https://twitter.com/BiblioPublicaAu, null]                 | 
| 1478290133  | Austin History Center Facebook           | [http://www.facebook.com/AustinHistoryCenter, null]         | 
```