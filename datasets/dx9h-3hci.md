# Home Page Tiles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-page-tiles) |
| Metadata | [Link](https://data.wa.gov/api/views/dx9h-3hci) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dx9h-3hci/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dx9h-3hci/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dx9h-3hci |
| Name | Home Page Tiles |
| Tags | administration |
| Created | 2016-05-20T22:50:30Z |
| Publication Date | 2016-05-21T01:00:14Z |

## Description

Data used to generate the tiles displayed on the Data.wa.gov home page.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | icon             | icon             | text      | text        |
| Yes      | series tag     | title            | title            | text      | text        |
| Yes      | series tag     | data_type        | data_type        | text      | text        |
| Yes      | series tag     | description      | description      | text      | text        |
| Yes      | series tag     | link             | link             | text      | text        |
| Yes      | series tag     | background_color | background_color | text      | text        |
| Yes      | numeric metric | sort             | sort             | number    | number      |
| Yes      | series tag     | image            | image            | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dx9h-3hci d:2016-05-20T15:53:08.000Z t:icon=&#x1F3EC; t:title="Featured Agency" t:description="Rotating spotlight list of data from a single agency" t:link=https://data.wa.gov/dataset/Agency-Spotlight/gkwx-zwe8 t:image=da123db9-2056-44d3-aa8b-e9c0a1d3562d t:background_color=#6699cc m:sort=3

series e:dx9h-3hci d:2016-05-20T15:53:35.000Z t:icon=&#x1F4B0; t:title=Fiscal.WA t:description="State budgets, checkbook, salaries and spending" t:link=http://fiscal.wa.gov t:image=3dd675b8-e948-4283-86ee-afd32401c638 t:background_color=#e7eddf m:sort=4

series e:dx9h-3hci d:2016-05-20T15:54:55.000Z t:icon=&#xE575; t:title=Results.WA t:description="Performance and Accountability data for state government" t:link=https://data.results.wa.gov/ t:image=7a786383-054d-4494-9cd3-43d820e8b34e t:background_color=#434341 m:sort=7
```

## Meta Commands

```ls
metric m:sort p:integer l:sort t:dataTypeName=number

entity e:dx9h-3hci l:"Home Page Tiles" t:url=https://data.wa.gov/api/views/dx9h-3hci

property e:dx9h-3hci t:meta.view v:id=dx9h-3hci v:averageRating=0 v:name="Home Page Tiles"

property e:dx9h-3hci t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:dx9h-3hci t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | icon | title              | data_type | description                                                                   | link                                                   | background_color | sort | image                                | 
| =========== | ==== | ================== | ========= | ============================================================================= | ====================================================== | ================ | ==== | ==================================== | 
| 1463759588  | ?   | Featured Agency    |           | Rotating spotlight list of data from a single agency                          | https://data.wa.gov/dataset/Agency-Spotlight/gkwx-zwe8 | #6699cc          | 3    | da123db9-2056-44d3-aa8b-e9c0a1d3562d | 
| 1463759615  | ?   | Fiscal.WA          |           | State budgets, checkbook, salaries and spending                               | http://fiscal.wa.gov                                   | #e7eddf          | 4    | 3dd675b8-e948-4283-86ee-afd32401c638 | 
| 1463759695  | ?    | Results.WA         |           | Performance and Accountability data for state government                      | https://data.results.wa.gov/                           | #434341          | 7    | 7a786383-054d-4494-9cd3-43d820e8b34e | 
| 1463759723  | ?   | Education Research |           | Education research and Data Center                                            | http://erdc.wa.gov                                     | #FFFFFF          | 9    | cdebf081-586b-4f09-a39b-b0a54c7c630f | 
| 1463759757  | ?    | Geography.WA       |           | Maps, apps, and more for the geospatial professional                          | http://wa-geoservices.maps.arcgis.com/home/            | #bdcc4e          | 5    | e79fb04b-0387-4797-8d70-77207a74c1d5 | 
| 1463759760  | ?    | Business.WA        |           | Find the requirements and tools you need to start, own and operate a business | http://business.wa.gov/                                | #33CCCC          | 6    | 9be873dc-4cf8-46ac-a5b2-5a7109513f90 | 
| 1463767074  | ?   | New and Notable    |           | Browsing? Check out this list of new and notable data                         | https://data.wa.gov/dataset/New-NotableData/jim6-db32  | #9bcc06          | 1    | da45cbac-a56b-46d8-bbea-9a0d531b9223 | 
| 1463767109  | ?    | Data Catalog       | Datasets  | Our general data catalog: datasets and more, sliced, diced and visualized     | /browse                                                | #5172aa          | 2    |                                      | 
| 1463767192  | ?    | Suggest            | Datasets  | Got an idea for a new dataset? Let us know.                                   | https://data.wa.gov/nominate?status=pending            | #84B209          | 8    |                                      | 
```