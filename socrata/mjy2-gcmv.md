# Board of Review - Aggregate Reductions by Year, 2008-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-review-aggregate-reductions-by-year-2008-2010-24c74) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/mjy2-gcmv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mjy2-gcmv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mjy2-gcmv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | mjy2-gcmv |
| Name | Board of Review - Aggregate Reductions by Year, 2008-2010 |
| Attribution | Cook County Board of Review |
| Category | Property & Taxation |
| Created | 2011-08-09T16:52:48Z |
| Publication Date | 2014-10-09T22:05:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | numeric metric | atv        | ATV       | number    | text        |
| Yes      | numeric metric | bortv      | BORTV     | number    | text        |
| Yes      | numeric metric | reduction  | Reduction | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mjy2-gcmv d:2008-01-01T00:00:00.000Z m:atv=26871701571 m:reduction=2029012637 m:bortv=24842688934

series e:mjy2-gcmv d:2009-01-01T00:00:00.000Z m:atv=35076173767 m:reduction=5910641610 m:bortv=29165532157

series e:mjy2-gcmv d:2010-01-01T00:00:00.000Z m:atv=26899200351 m:reduction=2573229717 m:bortv=24325970634
```

## Meta Commands

```ls
metric m:atv p:long l:ATV t:dataTypeName=number

metric m:bortv p:long l:BORTV t:dataTypeName=number

metric m:reduction p:long l:Reduction t:dataTypeName=number

entity e:mjy2-gcmv l:"Board of Review - Aggregate Reductions by Year, 2008-2010" t:attribution="Cook County Board of Review" t:url=https://datacatalog.cookcountyil.gov/api/views/mjy2-gcmv

property e:mjy2-gcmv t:meta.view v:id=mjy2-gcmv v:category="Property & Taxation" v:attributionLink=http://www.cookcountyboardofreview.com/ v:averageRating=0 v:name="Board of Review - Aggregate Reductions by Year, 2008-2010" v:attribution="Cook County Board of Review"

property e:mjy2-gcmv t:meta.view.license v:name="Public Domain"

property e:mjy2-gcmv t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:mjy2-gcmv t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | atv            | bortv          | reduction     | 
| ==== | ============== | ============== | ============= | 
| 2008 | 26,871,701,571 | 24,842,688,934 | 2,029,012,637 | 
| 2009 | 35,076,173,767 | 29,165,532,157 | 5,910,641,610 | 
| 2010 | 26,899,200,351 | 24,325,970,634 | 2,573,229,717 | 
```