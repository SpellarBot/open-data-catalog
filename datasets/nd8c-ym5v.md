# Board of Review--2009 PINs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-review-2009-pins-1e614) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nd8c-ym5v) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nd8c-ym5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nd8c-ym5v/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nd8c-ym5v |
| Name | Board of Review--2009 PINs |
| Attribution | Cook County Board of Review |
| Category | Property & Taxation |
| Tags | property identification numbers, 2009 pin |
| Created | 2011-10-11T10:45:19Z |
| Publication Date | 2011-10-11T10:58:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | numeric metric | pin        | PIN   | number    | number      |
| Yes      | numeric metric | class      | CLASS | number    | text        |
| Yes      | numeric metric | alv        | ALV   | money     | money       |
| Yes      | numeric metric | abv        | ABV   | money     | money       |
| Yes      | numeric metric | atv        | ATV   | money     | money       |
| Yes      | numeric metric | borlv      | BORLV | money     | money       |
| Yes      | numeric metric | borbv      | BORBV | money     | money       |
| Yes      | numeric metric | bortv      | BORTV | money     | money       |
| Yes      | series tag     | type       | TYPE  | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nd8c-ym5v d:2009-01-01T00:00:00.000Z t:type=A m:alv=27659 m:abv=70018 m:pin=1011000020000 m:borlv=27659 m:class=59200 m:borbv=70018 m:atv=97677 m:bortv=97677

series e:nd8c-ym5v d:2009-01-01T00:00:00.000Z t:type=A m:alv=6785 m:abv=67878 m:pin=1011000090000 m:borlv=6785 m:class=21200 m:borbv=67878 m:atv=74663 m:bortv=74663

series e:nd8c-ym5v d:2009-01-01T00:00:00.000Z t:type=G m:alv=63009 m:abv=161866 m:pin=1011000100000 m:borlv=0 m:class=59200 m:borbv=0 m:atv=224875 m:bortv=0
```

## Meta Commands

```ls
metric m:pin p:long l:PIN t:dataTypeName=number

metric m:class p:integer l:CLASS t:dataTypeName=number

metric m:alv p:integer l:ALV t:dataTypeName=money

metric m:abv p:integer l:ABV t:dataTypeName=money

metric m:atv p:integer l:ATV t:dataTypeName=money

metric m:borlv p:integer l:BORLV t:dataTypeName=money

metric m:borbv p:integer l:BORBV t:dataTypeName=money

metric m:bortv p:integer l:BORTV t:dataTypeName=money

entity e:nd8c-ym5v l:"Board of Review--2009 PINs" t:attribution="Cook County Board of Review" t:url=https://datacatalog.cookcountyil.gov/api/views/nd8c-ym5v

property e:nd8c-ym5v t:meta.view v:id=nd8c-ym5v v:category="Property & Taxation" v:averageRating=0 v:name="Board of Review--2009 PINs" v:attribution="Cook County Board of Review"

property e:nd8c-ym5v t:meta.view.license v:name="Public Domain"

property e:nd8c-ym5v t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nd8c-ym5v t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| pin           | class | alv   | abv    | atv    | borlv | borbv | bortv | type | 
| ============= | ===== | ===== | ====== | ====== | ===== | ===== | ===== | ==== | 
| 1011000020000 | 59200 | 27659 | 70018  | 97677  | 27659 | 70018 | 97677 | A    | 
| 1011000090000 | 21200 | 6785  | 67878  | 74663  | 6785  | 67878 | 74663 | A    | 
| 1011000100000 | 59200 | 63009 | 161866 | 224875 | 0     | 0     | 0     | G    | 
| 1011000110000 | 51700 | 57428 | 241498 | 298926 | 0     | 0     | 0     | G    | 
| 1011000280000 | 20300 | 6776  | 21977  | 28753  | 0     | 0     | 0     | G    | 
| 1011000300000 | 59000 | 27075 | 1896   | 28971  | 0     | 0     | 0     | G    | 
| 1011000370000 | 21100 | 4290  | 90500  | 94790  | 4290  | 74533 | 78823 | A    | 
| 1011000690000 | 59200 | 27225 | 42316  | 69541  | 27225 | 38097 | 65322 | P    | 
| 1011000710000 | 59200 | 22522 | 46274  | 68796  | 22522 | 46274 | 68796 | P    | 
| 1011000810000 | 21200 | 4143  | 82282  | 86425  | 0     | 0     | 0     | G    | 
```