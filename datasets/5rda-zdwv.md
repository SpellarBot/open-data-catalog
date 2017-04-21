# Board of Review - Aggregate PINs Filed by Year, 2008-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-review-aggregate-pins-filed-by-year-2008-2010-f51ed) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/5rda-zdwv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5rda-zdwv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5rda-zdwv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 5rda-zdwv |
| Name | Board of Review - Aggregate PINs Filed by Year, 2008-2010 |
| Attribution | Cook County Board of Review |
| Category | Property & Taxation |
| Created | 2011-08-09T16:51:19Z |
| Publication Date | 2014-10-09T21:45:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | time           | year       | Year  | number    | text        |
| Yes      | numeric metric | pins       | PINs  | number    | number      |
| Yes      | series tag     | notes      | Notes | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5rda-zdwv d:2008-01-01T00:00:00.000Z t:notes="pins filed in 2008( excluding voids)" m:pins=284148

series e:5rda-zdwv d:2009-01-01T00:00:00.000Z t:notes="pins filed in 2009 ( excluding voids)" m:pins=427089

series e:5rda-zdwv d:2010-01-01T00:00:00.000Z t:notes="pins filed in 2010( excluding voids)" m:pins=377650
```

## Meta Commands

```ls
metric m:pins p:integer l:PINs t:dataTypeName=number

entity e:5rda-zdwv l:"Board of Review - Aggregate PINs Filed by Year, 2008-2010" t:attribution="Cook County Board of Review" t:url=https://datacatalog.cookcountyil.gov/api/views/5rda-zdwv

property e:5rda-zdwv t:meta.view v:id=5rda-zdwv v:category="Property & Taxation" v:attributionLink=http://www.cookcountyboardofreview.com/ v:averageRating=0 v:name="Board of Review - Aggregate PINs Filed by Year, 2008-2010" v:attribution="Cook County Board of Review"

property e:5rda-zdwv t:meta.view.license v:name="Public Domain"

property e:5rda-zdwv t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:5rda-zdwv t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | pins   | notes                                 | 
| ==== | ====== | ===================================== | 
| 2008 | 284148 | pins filed in 2008( excluding voids)  | 
| 2009 | 427089 | pins filed in 2009 ( excluding voids) | 
| 2010 | 377650 | pins filed in 2010( excluding voids)  | 
```