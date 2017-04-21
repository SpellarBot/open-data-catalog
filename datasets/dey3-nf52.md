# Capital Banner Featured Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-banner-featured-data-2cd8a) |
| Metadata | [Link](https://data.illinois.gov/api/views/dey3-nf52) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dey3-nf52/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dey3-nf52/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dey3-nf52 |
| Name | Capital Banner Featured Data |
| Created | 2013-12-05T21:22:00Z |
| Publication Date | 2014-03-14T17:26:24Z |

## Description

Socrata dataset

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | order       | Order       | number    | number      |
| Yes      | series tag     | image       | Image       | photo     | photo       |
| Yes      | series tag     | title       | Title       | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dey3-nf52 d:2014-03-14T09:42:43.000Z t:title="Education Funding" t:image=zhk782KnyoZ_FJSLtxfi3QI3bQaLEjLQms_SjOPpcdg m:order=2

series e:dey3-nf52 d:2014-03-14T09:47:38.000Z t:title="Economic Development" t:image=MW-PcXcBp_8dQqCyM5w2ERXNjv8hmQD24_AJbaT6Nv4 m:order=1

series e:dey3-nf52 d:2014-03-14T09:48:32.000Z t:title="Water Infrastructure" t:image=nShghdSWWJFrGV5Ffna7GJ4pb2EXzWC3ql5qdRTJXKA m:order=5
```

## Meta Commands

```ls
metric m:order p:integer l:Order t:dataTypeName=number

entity e:dey3-nf52 l:"Capital Banner Featured Data" t:url=https://data.illinois.gov/api/views/dey3-nf52

property e:dey3-nf52 t:meta.view v:id=dey3-nf52 v:averageRating=0 v:name="Capital Banner Featured Data"

property e:dey3-nf52 t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:dey3-nf52 t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | order | image                                       | title                          | description | 
| =========== | ===== | =========================================== | ============================== | =========== | 
| 1394790163  | 2     | zhk782KnyoZ_FJSLtxfi3QI3bQaLEjLQms_SjOPpcdg | Education Funding              |             | 
| 1394790458  | 1     | MW-PcXcBp_8dQqCyM5w2ERXNjv8hmQD24_AJbaT6Nv4 | Economic Development           |             | 
| 1394790512  | 5     | nShghdSWWJFrGV5Ffna7GJ4pb2EXzWC3ql5qdRTJXKA | Water Infrastructure           |             | 
| 1394791008  | 4     | hbaggqw_MCf2oXj0wfxnQW5ZMCfhB6B-n0GllMDXXlw | Transportation                 |             | 
| 1394792782  | 3     | 8WZiIa6uhVc88rjaAf6Vpr-pFms8WDdJTOfnJu7ZD58 | Natural and Cultural Resources |             | 
```