# County Clerk - Suburban Early Voting Locations - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-clerk-suburban-early-voting-locations-2012-d0f06) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xq7j-aaw5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xq7j-aaw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xq7j-aaw5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xq7j-aaw5 |
| Name | County Clerk - Suburban Early Voting Locations - 2012 |
| Attribution | Cook County Clerk |
| Created | 2012-10-09T22:55:08Z |
| Publication Date | 2014-10-09T21:38:16Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name  | Data Type | Render Type |
| ======== | =========== | ========== | ===== | ========= | =========== |
| Yes      | series tag  | site       | Site  | text      | text        |
| Yes      | series tag  | hours      | Hours | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xq7j-aaw5 d:2012-01-01T00:00:00.000Z t:site="Alsip Village Hall" t:hours="Monday-Saturday: 9 a.m.?5 p.m." m:row_number.xq7j-aaw5=1

series e:xq7j-aaw5 d:2012-01-01T00:00:00.000Z t:site="Stickney-Forest View Public Library" t:hours="Monday-Saturday: 9 a.m.?5 p.m." m:row_number.xq7j-aaw5=2

series e:xq7j-aaw5 d:2012-01-01T00:00:00.000Z t:site="Orland Township Hall--NEW" t:hours="Monday-Saturday: 9 a.m.?5 p.m." m:row_number.xq7j-aaw5=3
```

## Meta Commands

```ls
metric m:row_number.xq7j-aaw5 p:long l:"Row Number"

entity e:xq7j-aaw5 l:"County Clerk - Suburban Early Voting Locations - 2012" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/xq7j-aaw5

property e:xq7j-aaw5 t:meta.view v:id=xq7j-aaw5 v:attributionLink=http://www.cookcountyclerk.com/ v:averageRating=0 v:name="County Clerk - Suburban Early Voting Locations - 2012" v:attribution="Cook County Clerk"

property e:xq7j-aaw5 t:meta.view.license v:name="Public Domain"

property e:xq7j-aaw5 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:xq7j-aaw5 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| site                                | hours                          | 
| =================================== | ============================== | 
| Alsip Village Hall                  | Monday-Saturday: 9 a.m.?5 p.m. | 
| Stickney-Forest View Public Library | Monday-Saturday: 9 a.m.?5 p.m. | 
| Orland Township Hall--NEW           | Monday-Saturday: 9 a.m.?5 p.m. | 
| *Rolling Meadows Courthouse         | Monday-Friday: 9 a.m.?5 p.m.   | 
| Oak Forest City Hall                | Monday-Saturday: 9 a.m.?5 p.m. | 
| Elk Grove Village Hall              | Monday-Saturday: 9 a.m.?5 p.m. | 
| *Bridgeview Courthouse              | Monday-Friday: 9 a.m.?5 p.m.   | 
| Chicago Heights City Hall           | Monday-Saturday: 9 a.m.?5 p.m. | 
| Lemont Library District             | Monday-Saturday: 9 a.m.?5 p.m. | 
| Park Ridge City Hall                | Monday-Saturday: 9 a.m.?5 p.m. | 
```