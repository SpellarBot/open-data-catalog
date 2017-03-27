# Risk Management - Employment Enrollment Summary, by Department - April 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employment-enrollment-summary-by-department-april-2012-7f27e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/h4i4-uff6) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/h4i4-uff6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/h4i4-uff6/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | h4i4-uff6 |
| Name | Risk Management - Employment Enrollment Summary, by Department - April 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-05-21T16:58:36Z |
| Publication Date | 2014-10-09T22:35:11Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | county_department_number | County Department Number | text      | text        |
| Yes      | numeric metric | enrollment_count         | Enrollment Count         | number    | number      |
| Yes      | numeric metric | cost                     | Cost                     | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h4i4-uff6 d:2012-01-01T00:00:00.000Z t:county_department_number=2 m:enrollment_count=11 m:cost=10674.56

series e:h4i4-uff6 d:2012-01-01T00:00:00.000Z t:county_department_number=7 m:enrollment_count=33 m:cost=29092.87

series e:h4i4-uff6 d:2012-01-01T00:00:00.000Z t:county_department_number=8 m:enrollment_count=19 m:cost=21563.41
```

## Meta Commands

```ls
metric m:enrollment_count p:integer l:"Enrollment Count" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:h4i4-uff6 l:"Risk Management - Employment Enrollment Summary, by Department - April 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/h4i4-uff6

property e:h4i4-uff6 t:meta.view v:id=h4i4-uff6 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employment Enrollment Summary, by Department - April 2012" v:attribution="Cook County Department of Risk Management"

property e:h4i4-uff6 t:meta.view.license v:name="Public Domain"

property e:h4i4-uff6 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:h4i4-uff6 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```