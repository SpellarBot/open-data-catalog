# Algae Bloom Advisories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/algae-bloom-advisories-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/hhdb-h5ge) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hhdb-h5ge/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hhdb-h5ge/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hhdb-h5ge |
| Name | Algae Bloom Advisories |
| Attribution | Oregon Public Health Division |
| Category | Recreation |
| Tags | algae blooms |
| Created | 2016-05-17T20:31:57Z |
| Publication Date | 2017-03-09T21:10:58Z |

## Description

Only a fraction of all water bodies in Oregon are monitored due to limited physical and monetary resources. A water body with no advisory is not an indication that a bloom is not present. You are your own best advocate when ensuring your safety, and that of your family and pets. Be aware and "when in doubt, stay out."

## Columns

```ls
| Included | Schema Type | Field Name           | Name                   | Data Type | Render Type |
| ======== | =========== | ==================== | ====================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | waterbody            | Waterbody              | text      | text        |
| Yes      | series tag  | issued               | Issued                 | url       | url         |
| Yes      | series tag  | lifted               | Lifted                 | url       | url         |
| Yes      | series tag  | icon                 | Icon                   | photo     | photo       |
| Yes      | series tag  | image                | Image                  | photo     | photo       |
| Yes      | series tag  | county               | County                 | text      | text        |
| Yes      | series tag  | dominant_genus_toxin | Dominant genus / toxin | text      | text        |
| Yes      | series tag  | cell_count_toxin     | Cell count/Toxin       | text      | text        |
| Yes      | series tag  | photo_credit         | Photo credit           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hhdb-h5ge d:2016-05-17T13:56:28.000Z t:icon=16dc9d68-8628-4087-8dca-f607f906e909 t:county=Douglas t:waterbody="South Umpqua River" t:issued=http://public.health.oregon.gov/HealthyEnvironments/Recreation/HarmfulAlgaeBlooms/Documents/Permanent%20Umpqua%20River%20Sign.jpg t:dominant_genus_toxin=Anatoxin-a t:image=9a5685d8-087b-4592-9e3f-b584bf309b0d m:row_number.hhdb-h5ge=1
```

## Meta Commands

```ls
metric m:row_number.hhdb-h5ge p:long l:"Row Number"

entity e:hhdb-h5ge l:"Algae Bloom Advisories" t:attribution="Oregon Public Health Division" t:url=https://data.oregon.gov/api/views/hhdb-h5ge

property e:hhdb-h5ge t:meta.view v:id=hhdb-h5ge v:category=Recreation v:attributionLink=http://public.health.oregon.gov v:averageRating=0 v:name="Algae Bloom Advisories" v:attribution="Oregon Public Health Division"

property e:hhdb-h5ge t:meta.view.owner v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:displayName="Britt Parrott"

property e:hhdb-h5ge t:meta.view.tableauthor v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:roleName=editor v:displayName="Britt Parrott"
```

## Top Records

```ls
| :updated_at | waterbody          | issued                                                                                                                                         | lifted       | icon                                 | image                                | county  | dominant_genus_toxin | cell_count_toxin | photo_credit | 
| =========== | ================== | ============================================================================================================================================== | ============ | ==================================== | ==================================== | ======= | ==================== | ================ | ============ | 
| 1463493388  | South Umpqua River | [http://public.health.oregon.gov/HealthyEnvironments/Recreation/HarmfulAlgaeBlooms/Documents/Permanent%20Umpqua%20River%20Sign.jpg, Permanent] | [null, null] | 16dc9d68-8628-4087-8dca-f607f906e909 | 9a5685d8-087b-4592-9e3f-b584bf309b0d | Douglas | Anatoxin-a           |                  |              | 
```