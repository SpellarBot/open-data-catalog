# Risk Management - Employee Healthcare Costs by Department - June 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employee-healthcare-costs-by-department-june-2012-71bfc) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/itxz-7spz) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/itxz-7spz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/itxz-7spz/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | itxz-7spz |
| Name | Risk Management - Employee Healthcare Costs by Department - June 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-08-03T15:17:34Z |
| Publication Date | 2014-10-09T22:08:26Z |
| Rows Updated | 2014-10-09T22:08:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | dept                | Dept                | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_cost          | Total Cost          | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:itxz-7spz d:2012-08-03T08:17:35.000Z t:dept=002 m:number_of_employees=10 m:total_cost=10114.05

series e:itxz-7spz d:2012-08-03T08:17:35.000Z t:dept=007 m:number_of_employees=38 m:total_cost=33177.28

series e:itxz-7spz d:2012-08-03T08:17:35.000Z t:dept=008 m:number_of_employees=22 m:total_cost=24649.37
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

entity e:itxz-7spz l:"Risk Management - Employee Healthcare Costs by Department - June 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/itxz-7spz

property e:itxz-7spz t:meta.view d:2017-03-10T14:16:26.714Z v:id=itxz-7spz v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employee Healthcare Costs by Department - June 2012" v:attribution="Cook County Department of Risk Management"

property e:itxz-7spz t:meta.view.license d:2017-03-10T14:16:26.714Z v:name="Public Domain"

property e:itxz-7spz t:meta.view.owner d:2017-03-10T14:16:26.714Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:itxz-7spz t:meta.view.tableauthor d:2017-03-10T14:16:26.714Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```