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

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | dept                | Dept                | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_cost          | Total Cost          | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:itxz-7spz d:2012-01-01T00:00:00.000Z t:dept=002 m:number_of_employees=10 m:total_cost=10114.05

series e:itxz-7spz d:2012-01-01T00:00:00.000Z t:dept=007 m:number_of_employees=38 m:total_cost=33177.28

series e:itxz-7spz d:2012-01-01T00:00:00.000Z t:dept=008 m:number_of_employees=22 m:total_cost=24649.37
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_cost p:double l:"Total Cost" t:dataTypeName=money

entity e:itxz-7spz l:"Risk Management - Employee Healthcare Costs by Department - June 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/itxz-7spz

property e:itxz-7spz t:meta.view d:2017-09-25T07:32:08.736Z v:averageRating=0 v:name="Risk Management - Employee Healthcare Costs by Department - June 2012" v:attribution="Cook County Department of Risk Management" v:attributionLink=http://www.cookcountyrisk.com/ v:id=itxz-7spz v:category="Finance & Administration"

property e:itxz-7spz t:meta.view.license d:2017-09-25T07:32:08.736Z v:name="Public Domain"

property e:itxz-7spz t:meta.view.owner d:2017-09-25T07:32:08.736Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB

property e:itxz-7spz t:meta.view.tableauthor d:2017-09-25T07:32:08.736Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB
```

## Top Records

```ls
| dept | number_of_employees | total_cost | 
| ==== | =================== | ========== | 
| 002  | 10                  | 10114.05   | 
| 007  | 38                  | 33177.28   | 
| 008  | 22                  | 24649.37   | 
| 009  | 43                  | 38354.12   | 
| 010  | 11                  | 9229.37    | 
| 011  | 37                  | 31039.64   | 
| 013  | 6                   | 6297.96    | 
| 014  | 15                  | 15930.58   | 
| 016  | 55                  | 57866.14   | 
| 018  | 9                   | 9675.80    | 
```