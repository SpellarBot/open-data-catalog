# City Social Media Inventory

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/yph5-vg2u/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/city-social-media-inventory)
* Id = yph5-vg2u
* Name = City Social Media Inventory
* Tags = [social media]
* Created = 2016-06-24T18:45:18Z
* Publication Date = 2017-02-13T15:13:23Z
* Rows Updated = 2017-02-13T15:13:15Z

## Description

Connect with the City of Austin. Find out the latest information about Austin initiatives, opportunities and fun things to do in the Live Music Capital of the World. Like or follow City social media to get updates from the City directly in your timeline.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type | Included | 
| ================ | ================ | ========= | =========== | =========== | ======== | 
| updated_at       | :updated_at      | meta_data | meta_data   | time        | Yes      | 
| Department       | department       | text      | text        | series tag  | Yes      | 
| Account Platform | account_platform | text      | text        | series tag  | Yes      | 
| Account Name     | account_name     | text      | text        | series tag  | Yes      | 
| Account Link     | account_link     | url       | url         | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:yph5-vg2u l:"City Social Media Inventory" t:url=https://data.austintexas.gov/api/views/yph5-vg2u

property e:yph5-vg2u t:meta.view d:2017-03-03T14:30:45.599Z v:id=yph5-vg2u v:averageRating=0 v:name="City Social Media Inventory"

property e:yph5-vg2u t:meta.view.owner d:2017-03-03T14:30:45.599Z v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo

property e:yph5-vg2u t:meta.view.tableauthor d:2017-03-03T14:30:45.599Z v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```