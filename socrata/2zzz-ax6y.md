# Administrative Hearings - Top 5 Violations, Sheriff's Office - Sept 2011 to March 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-violations-sheriffs-office-sept-2011-to-march-2012-43ba3) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/2zzz-ax6y) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2zzz-ax6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2zzz-ax6y/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 2zzz-ax6y |
| Name | Administrative Hearings - Top 5 Violations, Sheriff's Office - Sept 2011 to March 2012 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2012-05-21T17:23:28Z |
| Publication Date | 2014-10-09T22:34:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | violation_code       | Violation Code       | text      | text        |
| Yes      | series tag     | violation_text       | Violation Text       | text      | text        |
| Yes      | numeric metric | number_of_violations | Number of Violations | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2zzz-ax6y d:2011-01-01T00:00:00.000Z t:violation_text="No Valid Registration" t:violation_code=82-125(F) m:number_of_violations=6742

series e:2zzz-ax6y d:2011-01-01T00:00:00.000Z t:violation_text="No Wheel Tax Sticker" t:violation_code=74-552 m:number_of_violations=5670

series e:2zzz-ax6y d:2011-01-01T00:00:00.000Z t:violation_text="No Front or Rear Plate" t:violation_code=82-125(A) m:number_of_violations=3774
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:2zzz-ax6y l:"Administrative Hearings - Top 5 Violations, Sheriff's Office - Sept 2011 to March 2012" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/2zzz-ax6y

property e:2zzz-ax6y t:meta.view v:id=2zzz-ax6y v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Top 5 Violations, Sheriff's Office - Sept 2011 to March 2012" v:attribution="Cook County Department of Administrative Hearings"

property e:2zzz-ax6y t:meta.view.license v:name="Public Domain"

property e:2zzz-ax6y t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:2zzz-ax6y t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| violation_code | violation_text                                      | number_of_violations | 
| ============== | =================================================== | ==================== | 
| 82-125(F)      | No Valid Registration                               | 6742                 | 
| 74-552         | No Wheel Tax Sticker                                | 5670                 | 
| 82-125(A)      | No Front or Rear Plate                              | 3774                 | 
| 82-128         | Broken or Inoperable Lamps: Broken or Cracked Glass | 887                  | 
| 82-114(B)      | Two Headlights Required                             | 874                  | 
```