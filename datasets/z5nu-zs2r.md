# GIS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gis-3f8c7) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/z5nu-zs2r) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/z5nu-zs2r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/z5nu-zs2r/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | z5nu-zs2r |
| Name | GIS |
| Attribution | King County |
| Category | Places & Boundaries |
| Tags | geographic information, maps, property |
| Created | 2011-03-24T16:52:42Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County GIS data is at http://www5.kingcounty.gov/gisdataportal/

## Columns

```ls
| Included | Schema Type | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | =========== | ========================================= | ========================================= | ========= | =========== |
| No       | time        | :updated_at                               | updated_at                                | meta_data | meta_data   |
| Yes      | series tag  | gis_information_is_stored_on_another_site | GIS information is stored on another site | text      | text        |
| Yes      | series tag  | gis_website                               | GIS Website                               | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:z5nu-zs2r d:2011-03-24T10:09:05.000Z t:gis_website=http://www5.kingcounty.gov/gisdataportal/ t:gis_information_is_stored_on_another_site="Visit the main King County GIS data portal for GIS data." m:row_number.z5nu-zs2r=1
```

## Meta Commands

```ls
metric m:row_number.z5nu-zs2r p:long l:"Row Number"

entity e:z5nu-zs2r l:GIS t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/z5nu-zs2r

property e:z5nu-zs2r t:meta.view v:id=z5nu-zs2r v:category="Places & Boundaries" v:attributionLink=http://www5.kingcounty.gov/gisdataportal/ v:averageRating=0 v:name=GIS v:attribution="King County"

property e:z5nu-zs2r t:meta.view.license v:name="Public Domain"

property e:z5nu-zs2r t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:z5nu-zs2r t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | gis_information_is_stored_on_another_site                | gis_website                                       | 
| =========== | ======================================================== | ================================================= | 
| 1300961345  | Visit the main King County GIS data portal for GIS data. | [http://www5.kingcounty.gov/gisdataportal/, null] | 
```