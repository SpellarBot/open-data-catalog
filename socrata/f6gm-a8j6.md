# COA ODP FUELBYTYPE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-odp-fuelbytype) |
| Metadata | [Link](https://data.austintexas.gov/api/views/f6gm-a8j6) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/f6gm-a8j6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/f6gm-a8j6/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | f6gm-a8j6 |
| Name | COA ODP FUELBYTYPE |
| Category | Environmental |
| Created | 2015-06-29T15:30:15Z |
| Publication Date | 2017-01-11T09:00:25Z |

## Description

This is a breakdown of fuel usage from the City of Austin by type of fuel consumed

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | numeric metric | fisc_yr      | FISC_YR      | number    | number      |
| Yes      | numeric metric | propane      | PROPANE      | number    | number      |
| Yes      | numeric metric | e10_unleaded | E10_UNLEADED | number    | number      |
| Yes      | numeric metric | diesel       | DIESEL       | number    | number      |
| Yes      | numeric metric | biodiesel    | BIODIESEL    | number    | text        |
| Yes      | numeric metric | cng          | CNG          | number    | number      |
| Yes      | numeric metric | e85          | E85          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f6gm-a8j6 d:2017-01-11T09:00:19.000Z m:diesel=585451.991 m:cng=336251.6 m:propane=166203.51 m:e10_unleaded=1702534.399 m:biodiesel=2039784.358 m:e85=619961.2 m:fisc_yr=2016

series e:f6gm-a8j6 d:2017-04-20T10:00:17.000Z m:diesel=138245.7 m:cng=167250.4 m:propane=87639 m:e10_unleaded=783797.049 m:biodiesel=1287463.29 m:e85=483497.7 m:fisc_yr=2017
```

## Meta Commands

```ls
metric m:fisc_yr p:integer l:FISC_YR t:dataTypeName=number

metric m:propane p:double l:PROPANE t:dataTypeName=number

metric m:e10_unleaded p:double l:E10_UNLEADED t:dataTypeName=number

metric m:diesel p:double l:DIESEL t:dataTypeName=number

metric m:biodiesel p:double l:BIODIESEL t:dataTypeName=number

metric m:cng p:float l:CNG t:dataTypeName=number

metric m:e85 p:float l:E85 t:dataTypeName=number

entity e:f6gm-a8j6 l:"COA ODP FUELBYTYPE" t:url=https://data.austintexas.gov/api/views/f6gm-a8j6

property e:f6gm-a8j6 t:meta.view v:id=f6gm-a8j6 v:category=Environmental v:averageRating=0 v:name="COA ODP FUELBYTYPE"

property e:f6gm-a8j6 t:meta.view.license v:name="Public Domain"

property e:f6gm-a8j6 t:meta.view.owner v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:displayName="Fleet Services"

property e:f6gm-a8j6 t:meta.view.tableauthor v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:roleName=editor v:displayName="Fleet Services"
```

## Top Records

```ls
| :updated_at | fisc_yr | propane   | e10_unleaded | diesel     | biodiesel   | cng      | e85      | 
| =========== | ======= | ========= | ============ | ========== | =========== | ======== | ======== | 
| 1484125219  | 2016    | 166203.51 | 1702534.399  | 585451.991 | 2039784.358 | 336251.6 | 619961.2 | 
| 1492682417  | 2017    | 87639     | 783797.049   | 138245.7   | 1287463.29  | 167250.4 | 483497.7 | 
```