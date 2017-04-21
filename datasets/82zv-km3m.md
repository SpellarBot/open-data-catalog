# Medical Examiner--2009 Deaths Attributable to Work Injuries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-deaths-attributable-to-work-injuries-c518b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/82zv-km3m) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/82zv-km3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/82zv-km3m/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 82zv-km3m |
| Name | Medical Examiner--2009 Deaths Attributable to Work Injuries |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:31:33Z |
| Publication Date | 2014-10-27T16:03:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | work_inj_status | WORK INJ STATUS | text      | text        |
| Yes      | numeric metric | count_          | COUNT           | number    | text        |
| Yes      | numeric metric | percent_        | PERCENT         | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:82zv-km3m d:2009-01-01T00:00:00.000Z t:work_inj_status=YES m:count_=86 m:percent_=1.64

series e:82zv-km3m d:2009-01-01T00:00:00.000Z t:work_inj_status=NO m:count_=5145 m:percent_=98.3

series e:82zv-km3m d:2009-01-01T00:00:00.000Z t:work_inj_status=UNKNOWN m:count_=3 m:percent_=0.06
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:82zv-km3m l:"Medical Examiner--2009 Deaths Attributable to Work Injuries" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/82zv-km3m

property e:82zv-km3m t:meta.view v:id=82zv-km3m v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Deaths Attributable to Work Injuries" v:attribution="Cook County Medical Examiner"

property e:82zv-km3m t:meta.view.license v:name="Public Domain"

property e:82zv-km3m t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:82zv-km3m t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| work_inj_status | count_ | percent_ | 
| =============== | ====== | ======== | 
| YES             | 86     | 1.64     | 
| NO              | 5145   | 98.3     | 
| UNKNOWN         | 3      | 0.06     | 
```