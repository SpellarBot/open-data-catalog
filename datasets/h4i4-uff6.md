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
| Rows Updated | 2014-10-09T22:35:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | county_department_number | County Department Number | text      | text        |
| Yes      | numeric metric | enrollment_count         | Enrollment Count         | number    | number      |
| Yes      | numeric metric | cost                     | Cost                     | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h4i4-uff6 d:2012-05-21T09:58:37.000Z t:county_department_number=2 m:enrollment_count=11 m:cost=10674.56

series e:h4i4-uff6 d:2012-05-21T09:58:37.000Z t:county_department_number=7 m:enrollment_count=33 m:cost=29092.87

series e:h4i4-uff6 d:2012-05-21T09:58:37.000Z t:county_department_number=8 m:enrollment_count=19 m:cost=21563.41
```

## Meta Commands

```ls
metric m:enrollment_count p:integer l:"Enrollment Count" t:dataTypeName=number

entity e:h4i4-uff6 l:"Risk Management - Employment Enrollment Summary, by Department - April 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/h4i4-uff6

property e:h4i4-uff6 t:meta.view d:2017-03-10T14:19:17.691Z v:id=h4i4-uff6 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employment Enrollment Summary, by Department - April 2012" v:attribution="Cook County Department of Risk Management"

property e:h4i4-uff6 t:meta.view.license d:2017-03-10T14:19:17.691Z v:name="Public Domain"

property e:h4i4-uff6 t:meta.view.owner d:2017-03-10T14:19:17.691Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:h4i4-uff6 t:meta.view.tableauthor d:2017-03-10T14:19:17.691Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```