# Home Page Featured Story

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-page-featured-story-f0438) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wy7w-tcd5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wy7w-tcd5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wy7w-tcd5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wy7w-tcd5 |
| Name | Home Page Featured Story |
| Created | 2013-11-20T04:37:21Z |
| Publication Date | 2013-11-24T06:50:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | title       | Title      | text      | text        |
| Yes      | series tag     | link        | Link       | text      | text        |
| Yes      | series tag     | dataset_id  | Dataset Id | text      | text        |
| Yes      | series tag     | image       | Image      | photo     | photo       |
| Yes      | series tag     | show        | Show       | checkbox  | checkbox    |
| Yes      | numeric metric | sort_order  | Sort Order | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wy7w-tcd5 d:2013-11-23T22:43:56.000Z t:title="Hawaii's Renewable Energy Projects" t:link="https://data.hawaii.gov/browse?federation_filter=162&q=renewable+energy&utf8=%E2%9C%93&sortBy=relevance" t:dataset_id=857n-psp7 t:image=ozBOatcJWF9miMhdHmyeVaBKTORsPwoQT87CYAN1hBc t:show=true m:sort_order=1

series e:wy7w-tcd5 d:2013-11-23T22:44:07.000Z t:title="Using Open Data for Campaign Spending" t:link=/apps/campaignspending t:image=WMx0C8gYPFscMyiDJD11vNi91JrFiTnY3KDDMORj8-o t:show=true m:sort_order=2

series e:wy7w-tcd5 d:2013-11-23T22:50:03.000Z t:title="Welcome to data.hawaii.gov" t:link=/browse t:image=BYVxzKV6QIqStLE-yKiVFn9St-6ZoBo5rcKsKCiDUA8 t:show=true m:sort_order=3
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"Sort Order" t:dataTypeName=number

entity e:wy7w-tcd5 l:"Home Page Featured Story" t:url=https://data.hawaii.gov/api/views/wy7w-tcd5

property e:wy7w-tcd5 t:meta.view v:id=wy7w-tcd5 v:averageRating=0 v:name="Home Page Featured Story"

property e:wy7w-tcd5 t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:wy7w-tcd5 t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | title                                 | link                                                                                                    | dataset_id | image                                       | show | sort_order | 
| =========== | ===================================== | ======================================================================================================= | ========== | =========================================== | ==== | ========== | 
| 1384946335  | Governor Abercrombie                  |                                                                                                         |            | 1P2RrJPbetsIzx8HiWECtkm0b-WccLhDut04Q1Tv62U |      |            | 
| 1385246636  | Hawaii's Renewable Energy Projects    | https://data.hawaii.gov/browse?federation_filter=162&q=renewable+energy&utf8=%E2%9C%93&sortBy=relevance | 857n-psp7  | ozBOatcJWF9miMhdHmyeVaBKTORsPwoQT87CYAN1hBc | true | 1          | 
| 1385246647  | Using Open Data for Campaign Spending | /apps/campaignspending                                                                                  |            | WMx0C8gYPFscMyiDJD11vNi91JrFiTnY3KDDMORj8-o | true | 2          | 
| 1385246677  | Welcome to data.hawaii.gov            | /browse                                                                                                 |            | 6MzfIC3qQ95DXDSZ-eCVGDe7tq_cpcETgDtQXHG3Y3c |      |            | 
| 1385246685  | Hawaii's Renewable Energy Projects    | https://data.hawaii.gov/browse?federation_filter=162&q=renewable+energy&utf8=%E2%9C%93&sortBy=relevance |            | sVSwqhMRAkOTF8g3FhowaJ4Yqrz_wj5Gubc4A1cW6KI |      |            | 
| 1385247003  | Welcome to data.hawaii.gov            | /browse                                                                                                 |            | BYVxzKV6QIqStLE-yKiVFn9St-6ZoBo5rcKsKCiDUA8 | true | 3          | 
```