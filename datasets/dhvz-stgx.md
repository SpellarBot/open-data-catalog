# Austin Water Authorized Irrigation Inspector List

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/dhvz-stgx/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/austin-water-authorized-irrigation-inspector-list)
* Id = dhvz-stgx
* Name = Austin Water Authorized Irrigation Inspector List
* Attribution = Austin Water
* Attribution Link = http://waterwiseaustin.org
* Category = Environmental
* Tags = [austin water, irrigation, inspector, water, code, property owner]
* Created = 2016-10-06T21:01:26Z
* Publication Date = 2016-10-06T21:06:32Z
* Rows Updated = 2016-10-06T21:01:32Z

## Description

Austin Water?s authorized irrigation inspectors are approved to perform the irrigation evaluation required by City Code 6-4-10(A) Facilities Regulated. Each property owner/manager is responsible for selecting an inspector. Individuals on this list are provided as a resource without endorsement by the City of Austin.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type | Included | 
| ================ | ================ | ========= | =========== | =========== | ======== | 
| updated_at       | :updated_at      | meta_data | meta_data   | time        | Yes      | 
| Inspector Number | inspector_number | text      | text        | series tag  | Yes      | 
| First Name       | first_name       | text      | text        | series tag  | Yes      | 
| Last Name        | last_name        | text      | text        | series tag  | Yes      | 
| Company          | company          | text      | text        | series tag  | Yes      | 
| Telephone        | telephone        | text      | text        | series tag  | Yes      | 
| Email            | email            | email     | email       | series tag  | Yes      | 
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
entity e:dhvz-stgx l:"Austin Water Authorized Irrigation Inspector List" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/dhvz-stgx

property e:dhvz-stgx t:meta.view d:2017-03-03T14:03:36.671Z v:id=dhvz-stgx v:category=Environmental v:attributionLink=http://waterwiseaustin.org v:averageRating=0 v:name="Austin Water Authorized Irrigation Inspector List" v:attribution="Austin Water"

property e:dhvz-stgx t:meta.view.owner d:2017-03-03T14:03:36.671Z v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"

property e:dhvz-stgx t:meta.view.tableauthor d:2017-03-03T14:03:36.671Z v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"
```