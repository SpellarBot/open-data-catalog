# Administrative Hearings - Top 5 Violations - Sept 2011 To Mar 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-violations-sept-2011-to-mar-2012-9cb75) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3a6z-d5eu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3a6z-d5eu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3a6z-d5eu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3a6z-d5eu |
| Name | Administrative Hearings - Top 5 Violations - Sept 2011 To Mar 2012 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2012-05-21T17:20:51Z |
| Publication Date | 2014-10-09T22:32:40Z |

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
series e:3a6z-d5eu d:2011-01-01T00:00:00.000Z t:violation_text="Violation of Tobacco Tax Ordinance Section 74-430" t:violation_code=74-435A4 m:number_of_violations=382

series e:3a6z-d5eu d:2011-01-01T00:00:00.000Z t:violation_text="Violation of Tobacco Tax Ordinance" t:violation_code=74-435B2 m:number_of_violations=203

series e:3a6z-d5eu d:2011-01-01T00:00:00.000Z t:violation_text="Violation of Tobacco Tax Ordinance" t:violation_code=74-435B3 m:number_of_violations=193
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:3a6z-d5eu l:"Administrative Hearings - Top 5 Violations - Sept 2011 To Mar 2012" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/3a6z-d5eu

property e:3a6z-d5eu t:meta.view v:id=3a6z-d5eu v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Top 5 Violations - Sept 2011 To Mar 2012" v:attribution="Cook County Department of Administrative Hearings"

property e:3a6z-d5eu t:meta.view.license v:name="Public Domain"

property e:3a6z-d5eu t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:3a6z-d5eu t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| violation_code | violation_text                                    | number_of_violations | 
| ============== | ================================================= | ==================== | 
| 74-435A4       | Violation of Tobacco Tax Ordinance Section 74-430 | 382                  | 
| 74-435B2       | Violation of Tobacco Tax Ordinance                | 203                  | 
| 74-435B3       | Violation of Tobacco Tax Ordinance                | 193                  | 
| 74-435B5       | Safe                                              | 84                   | 
```