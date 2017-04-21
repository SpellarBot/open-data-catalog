# Administrative Hearings - Top 5 Environmental Control Violations - Sept 2011 To March 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-environmental-control-violations-sept-2011-to-march-2012-fc947) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/97yy-kfnq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/97yy-kfnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/97yy-kfnq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 97yy-kfnq |
| Name | Administrative Hearings - Top 5 Environmental Control Violations - Sept 2011 To March 2012 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2012-05-21T17:30:14Z |
| Publication Date | 2014-10-09T22:07:56Z |

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
series e:97yy-kfnq d:2011-01-01T00:00:00.000Z t:violation_text="Late Payment of Fees" t:violation_code=30-92 m:number_of_violations=186

series e:97yy-kfnq d:2011-01-01T00:00:00.000Z t:violation_text="No Valid Certificate of Operation" t:violation_code=30-186 m:number_of_violations=184

series e:97yy-kfnq d:2011-01-01T00:00:00.000Z t:violation_text="No Valid ACM Abatement Permit" t:violation_code=30-544B2 m:number_of_violations=6
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:97yy-kfnq l:"Administrative Hearings - Top 5 Environmental Control Violations - Sept 2011 To March 2012" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/97yy-kfnq

property e:97yy-kfnq t:meta.view v:id=97yy-kfnq v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Top 5 Environmental Control Violations - Sept 2011 To March 2012" v:attribution="Cook County Department of Administrative Hearings"

property e:97yy-kfnq t:meta.view.license v:name="Public Domain"

property e:97yy-kfnq t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:97yy-kfnq t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| violation_code | violation_text                          | number_of_violations | 
| ============== | ======================================= | ==================== | 
| 30-92          | Late Payment of Fees                    | 186                  | 
| 30-186         | No Valid Certificate of Operation       | 184                  | 
| 30-544B2       | No Valid ACM Abatement Permit           | 6                    | 
| 30-544B2       | No Valid Demolition Permit              | 8                    | 
| 30-189         | Certification Of Operation To Be Posted | 3                    | 
```