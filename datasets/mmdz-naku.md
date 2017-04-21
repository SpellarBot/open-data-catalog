# Risk Management - Department Enrollment Summary - April 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-department-enrollment-summary-april-2012-a35f7) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/mmdz-naku) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mmdz-naku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mmdz-naku/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | mmdz-naku |
| Name | Risk Management - Department Enrollment Summary - April 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-05-21T16:45:24Z |
| Publication Date | 2014-10-09T22:33:05Z |

## Description

Monthly summary of employee enrollment, by department. Data is for April 2012.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | county_department_number | County Department Number | text      | text        |
| Yes      | series tag     | enrollment_count         | Enrollment Count         | text      | text        |
| Yes      | series tag     | source_column            | Source Column            | text      | text        |
| Yes      | numeric metric | cost                     | Cost                     | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mmdz-naku d:2012-01-01T00:00:00.000Z t:enrollment_count="* 11" t:county_department_number=002 m:cost=10674.56

series e:mmdz-naku d:2012-01-01T00:00:00.000Z t:enrollment_count="* 33" t:county_department_number=007 m:cost=29092.87

series e:mmdz-naku d:2012-01-01T00:00:00.000Z t:enrollment_count="* 19" t:county_department_number=008 m:cost=21563.41
```

## Meta Commands

```ls
metric m:cost p:double l:Cost t:dataTypeName=money

entity e:mmdz-naku l:"Risk Management - Department Enrollment Summary - April 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/mmdz-naku

property e:mmdz-naku t:meta.view v:id=mmdz-naku v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Department Enrollment Summary - April 2012" v:attribution="Cook County Department of Risk Management"

property e:mmdz-naku t:meta.view.license v:name="Public Domain"

property e:mmdz-naku t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:mmdz-naku t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| county_department_number | enrollment_count | source_column | cost     | 
| ======================== | ================ | ============= | ======== | 
| 002                      | * 11             |               | 10674.56 | 
| 007                      | * 33             |               | 29092.87 | 
| 008                      | * 19             |               | 21563.41 | 
| 009                      | * 43             |               | 38354.12 | 
| 010                      | * 11             |               | 9229.37  | 
| 011                      | * 36             |               | 30479.13 | 
| 013                      | * 6              |               | 6297.96  | 
| 014                      | * 11             |               | 13336.13 | 
| 016                      | * 56             |               | 58518.37 | 
| 018                      | * 9              |               | 9675.80  | 
```