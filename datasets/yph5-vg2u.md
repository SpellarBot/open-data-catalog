# City Social Media Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-social-media-inventory) |
| Metadata | [Link](https://data.austintexas.gov/api/views/yph5-vg2u) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/yph5-vg2u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/yph5-vg2u/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | yph5-vg2u |
| Name | City Social Media Inventory |
| Tags | social media |
| Created | 2016-06-24T18:45:18Z |
| Publication Date | 2017-02-13T15:13:23Z |
| Rows Updated | 2017-02-13T15:13:15Z |

## Description

Connect with the City of Austin. Find out the latest information about Austin initiatives, opportunities and fun things to do in the Live Music Capital of the World. Like or follow City social media to get updates from the City directly in your timeline.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | department       | Department       | text      | text        |
| Yes      | series tag  | account_platform | Account Platform | text      | text        |
| Yes      | series tag  | account_name     | Account Name     | text      | text        |
| Yes      | series tag  | account_link     | Account Link     | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yph5-vg2u d:2016-06-24T12:44:20.000Z t:account_link=https://www.facebook.com/atx311 t:department=3-1-1 t:account_platform=Facebook t:account_name="Austin 3-1-1" m:row_number.yph5-vg2u=1

series e:yph5-vg2u d:2016-06-24T12:44:20.000Z t:account_link=https://www.instagram.com/atx311/ t:department=3-1-1 t:account_platform=Instagram t:account_name=atx311 m:row_number.yph5-vg2u=2

series e:yph5-vg2u d:2016-06-24T12:44:20.000Z t:account_link=https://twitter.com/ATX_311 t:department=3-1-1 t:account_platform=Twitter t:account_name=atx_311 m:row_number.yph5-vg2u=3
```

## Meta Commands

```ls
metric m:row_number.yph5-vg2u p:long l:"Row Number"

entity e:yph5-vg2u l:"City Social Media Inventory" t:url=https://data.austintexas.gov/api/views/yph5-vg2u

property e:yph5-vg2u t:meta.view v:id=yph5-vg2u v:averageRating=0 v:name="City Social Media Inventory"

property e:yph5-vg2u t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo

property e:yph5-vg2u t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```