# Medical Examiner--2009 Deaths, by Day Death Occurred

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-deaths-by-day-death-occurred-a4998) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/tcy9-nzb9) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tcy9-nzb9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tcy9-nzb9/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | tcy9-nzb9 |
| Name | Medical Examiner--2009 Deaths, by Day Death Occurred |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T18:44:03Z |
| Publication Date | 2014-10-27T16:04:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name         | Data Type | Render Type |
| ======== | ============== | ============= | ============ | ========= | =========== |
| Yes      | series tag     | day_of_death_ | DAY OF DEATH | text      | text        |
| Yes      | numeric metric | count_        | COUNT        | number    | number      |
| Yes      | numeric metric | percent_      | PERCENT      | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tcy9-nzb9 d:2009-01-01T00:00:00.000Z t:day_of_death_=SUNDAY m:count_=779 m:percent_=14.88

series e:tcy9-nzb9 d:2009-01-01T00:00:00.000Z t:day_of_death_=MONDAY m:count_=759 m:percent_=14.5

series e:tcy9-nzb9 d:2009-01-01T00:00:00.000Z t:day_of_death_=TUESDAY m:count_=748 m:percent_=14.29
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:tcy9-nzb9 l:"Medical Examiner--2009 Deaths, by Day Death Occurred" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/tcy9-nzb9

property e:tcy9-nzb9 t:meta.view v:id=tcy9-nzb9 v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Deaths, by Day Death Occurred" v:attribution="Cook County Medical Examiner"

property e:tcy9-nzb9 t:meta.view.license v:name="Public Domain"

property e:tcy9-nzb9 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:tcy9-nzb9 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| day_of_death_ | count_ | percent_ | 
| ============= | ====== | ======== | 
| SUNDAY        | 779    | 14.88    | 
| MONDAY        | 759    | 14.5     | 
| TUESDAY       | 748    | 14.29    | 
| WEDNESDAY     | 715    | 13.66    | 
| THURSDAY      | 746    | 14.25    | 
| FRIDAY        | 720    | 13.76    | 
| SATURDAY      | 750    | 14.33    | 
| UNKNOWN       | 17     | 0.32     | 
```