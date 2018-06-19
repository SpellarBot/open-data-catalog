# Board of Review - 2010 PIN information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-review-2010-pin-information-5140a) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ex8q-9kx6) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ex8q-9kx6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ex8q-9kx6/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ex8q-9kx6 |
| Name | Board of Review - 2010 PIN information |
| Attribution | Cook County Board of Review |
| Category | Property & Taxation |
| Tags | board of review, 2010 pin information, property |
| Created | 2011-08-09T16:19:18Z |
| Publication Date | 2011-08-09T16:19:18Z |

## Description

PIN information for 2010

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | numeric metric | pin        | PIN   | number    | number      |
| Yes      | numeric metric | class      | CLASS | number    | number      |
| Yes      | numeric metric | alv        | ALV   | number    | number      |
| Yes      | numeric metric | abv        | ABV   | number    | number      |
| Yes      | numeric metric | atv        | ATV   | number    | number      |
| Yes      | numeric metric | borlv      | BORLV | number    | number      |
| Yes      | numeric metric | borbv      | BORBV | number    | number      |
| Yes      | numeric metric | bortv      | BORTV | number    | number      |
| Yes      | series tag     | type       | TYPE  | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ex8q-9kx6 d:2010-01-01T00:00:00.000Z t:type=A m:alv=491 m:abv=83587 m:pin=1011010301085 m:borlv=491 m:class=29900 m:borbv=66891 m:atv=84078 m:bortv=67382

series e:ex8q-9kx6 d:2010-01-01T00:00:00.000Z t:type=A m:alv=4948 m:abv=72002 m:pin=1011020030000 m:borlv=4948 m:class=59200 m:borbv=72002 m:atv=76950 m:bortv=76950

series e:ex8q-9kx6 d:2010-01-01T00:00:00.000Z t:type=P m:alv=17240 m:abv=54007 m:pin=1011030010000 m:borlv=17240 m:class=51700 m:borbv=39396 m:atv=71247 m:bortv=56636
```

## Meta Commands

```ls
metric m:pin p:long l:PIN t:dataTypeName=number

metric m:class p:integer l:CLASS t:dataTypeName=number

metric m:alv p:integer l:ALV t:dataTypeName=number

metric m:abv p:integer l:ABV t:dataTypeName=number

metric m:atv p:integer l:ATV t:dataTypeName=number

metric m:borlv p:integer l:BORLV t:dataTypeName=number

metric m:borbv p:integer l:BORBV t:dataTypeName=number

metric m:bortv p:integer l:BORTV t:dataTypeName=number

entity e:ex8q-9kx6 l:"Board of Review - 2010 PIN information" t:attribution="Cook County Board of Review" t:url=https://datacatalog.cookcountyil.gov/api/views/ex8q-9kx6

property e:ex8q-9kx6 t:meta.view v:id=ex8q-9kx6 v:category="Property & Taxation" v:attributionLink=http://www.cookcountyboardofreview.com/ v:averageRating=0 v:name="Board of Review - 2010 PIN information" v:attribution="Cook County Board of Review"

property e:ex8q-9kx6 t:meta.view.license v:name="Public Domain"

property e:ex8q-9kx6 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ex8q-9kx6 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| pin           | class | alv   | abv    | atv    | borlv | borbv  | bortv  | type | 
| ============= | ===== | ===== | ====== | ====== | ===== | ====== | ====== | ==== | 
| 1011010301085 | 29900 | 491   | 83587  | 84078  | 491   | 66891  | 67382  | A    | 
| 1011020030000 | 59200 | 4948  | 72002  | 76950  | 4948  | 72002  | 76950  | A    | 
| 1011030010000 | 51700 | 17240 | 54007  | 71247  | 17240 | 39396  | 56636  | P    | 
| 1011030020000 | 59200 | 34587 | 478224 | 512811 | 34587 | 478224 | 512811 | A    | 
| 1011030030000 | 59200 | 36142 | 369483 | 405625 | 36142 | 275912 | 312054 | A    | 
| 1011030040000 | 59200 | 45521 | 369479 | 415000 | 45521 | 275909 | 321430 | A    | 
| 1011030060000 | 51700 | 32482 | 158082 | 190564 | 32482 | 75126  | 107608 | A    | 
| 1011030070000 | 59000 | 19443 | 760    | 20203  | 19443 | 361    | 19804  | A    | 
| 1011040030000 | 59200 | 12566 | 154613 | 167179 | 12566 | 106144 | 118710 | A    | 
| 1011040040000 | 59200 | 28700 | 259227 | 287927 | 28700 | 177966 | 206666 | A    | 
```