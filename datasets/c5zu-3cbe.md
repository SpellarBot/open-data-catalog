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
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | site       | Site    | text      | text        |
| Yes      | series tag  | hours      | Hours   | text      | text        |
| No       |             | address    | Address | text      | text        |
| Yes      | series tag  | city       | City    | text      | text        |
| Yes      | series tag  | state      | State   | text      | text        |
| Yes      | series tag  | zip        | Zip     | text      | text        |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Alsip Village Hall" t:zip=60803 t:hours="Monday-Saturday: 9 a.m.?5 p.m." t:state=IL t:city=Alsip m:row_number.c5zu-3cbe=1

series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Arlington Heights Village Hall" t:zip=60005 t:hours="Monday-Saturday: 9 a.m.?5 p.m.; Sunday: 9 a.m. ? 3 p.m." t:state=IL t:city="Arlington Heights" m:row_number.c5zu-3cbe=2

series e:c5zu-3cbe d:2012-01-01T00:00:00.000Z t:site="Barrington Township Hall" t:zip=60010 t:hours="Monday-Saturday: 9 a.m.?5 p.m." t:state=IL t:city=Barrington m:row_number.c5zu-3cbe=3
```

## Meta Commands

```ls
metric m:row_number.c5zu-3cbe p:long l:"Row Number"

entity e:c5zu-3cbe l:"Early Voting Locations - 2012" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/c5zu-3cbe

property e:c5zu-3cbe t:meta.view v:id=c5zu-3cbe v:attributionLink=http://cookcountyclerk.com v:averageRating=0 v:name="Early Voting Locations - 2012" v:attribution="Cook County Clerk"

property e:c5zu-3cbe t:meta.view.license v:name="Public Domain"

property e:c5zu-3cbe t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:c5zu-3cbe t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```