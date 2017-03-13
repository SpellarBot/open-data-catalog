# Early Voting Locations - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/early-voting-locations-2012-1a758) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | c5zu-3cbe |
| Name | Early Voting Locations - 2012 |
| Attribution | Cook County Clerk |
| Created | 2012-10-10T19:48:01Z |
| Publication Date | 2014-10-09T21:26:53Z |
| Rows Updated | 2014-10-09T21:26:48Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | site        | Site       | text      | text        |
| Yes      | series tag  | hours       | Hours      | text      | text        |
| No       |             | address     | Address    | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | zip         | Zip        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:c5zu-3cbe l:"Early Voting Locations - 2012" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe

property e:c5zu-3cbe t:meta.view v:id=c5zu-3cbe v:attributionLink=http://cookcountyclerk.com v:averageRating=0 v:name="Early Voting Locations - 2012" v:attribution="Cook County Clerk"

property e:c5zu-3cbe t:meta.view.license v:name="Public Domain"

property e:c5zu-3cbe t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:c5zu-3cbe t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```