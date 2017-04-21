# Public Defender - Pending Cases by Month, by Type - Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-defender-pending-cases-by-month-by-type-fiscal-year-2011-10239) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nv9f-asg8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nv9f-asg8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nv9f-asg8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nv9f-asg8 |
| Name | Public Defender - Pending Cases by Month, by Type - Fiscal Year 2011 |
| Attribution | Cook County Public Defender |
| Category | Courts |
| Created | 2011-09-19T19:09:41Z |
| Publication Date | 2014-10-09T21:03:51Z |

## Description

Data covers December 2010 through August 2011

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                   | Data Type | Render Type |
| ======== | ============== | ===================== | ====================== | ========= | =========== |
| Yes      | series tag     | month_location        | Month/Location         | text      | text        |
| Yes      | series tag     | homicide_26th_street_ | Homicide (26th Street) | text      | number      |
| Yes      | numeric metric | felony                | Felony                 | number    | number      |
| Yes      | numeric metric | misdemeanors          | Misdemeanors           | number    | number      |
| Yes      | numeric metric | juvenile              | Juvenile               | number    | number      |
| Yes      | numeric metric | civil                 | Civil                  | number    | number      |
| Yes      | numeric metric | pc_appeals            | PC & Appeals           | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nv9f-asg8 d:2011-01-01T00:00:00.000Z t:month_location=December-10 t:homicide_26th_street_=377 m:felony=9355 m:misdemeanors=15002 m:pc_appeals=572 m:civil=2715 m:juvenile=5265

series e:nv9f-asg8 d:2011-01-01T00:00:00.000Z t:month_location=January-11 t:homicide_26th_street_=386 m:felony=9715 m:misdemeanors=11219 m:pc_appeals=589 m:civil=2644 m:juvenile=5779

series e:nv9f-asg8 d:2011-01-01T00:00:00.000Z t:month_location=February-11 t:homicide_26th_street_=377 m:felony=11590 m:misdemeanors=11088 m:pc_appeals=560 m:civil=2653 m:juvenile=5333
```

## Meta Commands

```ls
metric m:felony p:integer l:Felony t:dataTypeName=number

metric m:misdemeanors p:integer l:Misdemeanors t:dataTypeName=number

metric m:juvenile p:integer l:Juvenile t:dataTypeName=number

metric m:civil p:integer l:Civil t:dataTypeName=number

metric m:pc_appeals p:integer l:"PC & Appeals" t:dataTypeName=number

entity e:nv9f-asg8 l:"Public Defender - Pending Cases by Month, by Type - Fiscal Year 2011" t:attribution="Cook County Public Defender" t:url=https://datacatalog.cookcountyil.gov/api/views/nv9f-asg8

property e:nv9f-asg8 t:meta.view v:id=nv9f-asg8 v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/public_defender%2C_law_office_of/260 v:averageRating=0 v:name="Public Defender - Pending Cases by Month, by Type - Fiscal Year 2011" v:attribution="Cook County Public Defender"

property e:nv9f-asg8 t:meta.view.license v:name="Public Domain"

property e:nv9f-asg8 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nv9f-asg8 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month_location | homicide_26th_street_ | felony | misdemeanors | juvenile | civil | pc_appeals | 
| ============== | ===================== | ====== | ============ | ======== | ===== | ========== | 
| December-10    | 377                   | 9355   | 15002        | 5265     | 2715  | 572        | 
| January-11     | 386                   | 9715   | 11219        | 5779     | 2644  | 589        | 
| February-11    | 377                   | 11590  | 11088        | 5333     | 2653  | 560        | 
| March-11       | 360                   | 11137  | 12978        | 5520     | 2506  | 559        | 
| April-11       | 360                   | 8949   | 12468        | 5164     | 2577  | 581        | 
| May-11         | 363                   | 8761   | 13714        | 5377     | 2490  | 580        | 
| June-11        | 361                   | 9178   | 14899        | 5250     | 2489  | 569        | 
| July-11        | 342                   | 9038   | 14551        | 7010     | 2636  | 563        | 
| August-11      | 394                   | 10481  | 18304        | 5278     | 2389  | 566        | 
| September-11   |                       |        |              |          |       |            | 
```