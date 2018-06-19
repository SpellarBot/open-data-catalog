# Risk Management - Employee Health Costs, by Department - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employee-health-costs-by-department-fiscal-year-2011-incomplete-4a581) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6ghm-dfk7) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6ghm-dfk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6ghm-dfk7/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6ghm-dfk7 |
| Name | Risk Management - Employee Health Costs, by Department - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2011-09-07T20:55:35Z |
| Publication Date | 2014-10-09T21:22:53Z |

## Description

Data last updated September 7, 2011

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | dept_number                 | Dept Number                 | text      | text        |
| Yes      | numeric metric | number_of_employees         | Number of Employees         | number    | number      |
| Yes      | series tag     | health_costs_for_department | Health Costs for Department | text      | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6ghm-dfk7 d:2011-01-01T00:00:00.000Z t:health_costs_for_department=10765.42 t:dept_number="002 Total" m:number_of_employees=9

series e:6ghm-dfk7 d:2011-01-01T00:00:00.000Z t:health_costs_for_department=31349.90 t:dept_number="007 Total" m:number_of_employees=29

series e:6ghm-dfk7 d:2011-01-01T00:00:00.000Z t:health_costs_for_department=26061.28 t:dept_number="008 Total" m:number_of_employees=21
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

entity e:6ghm-dfk7 l:"Risk Management - Employee Health Costs, by Department - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/6ghm-dfk7

property e:6ghm-dfk7 t:meta.view v:id=6ghm-dfk7 v:category="Finance & Administration" v:averageRating=0 v:name="Risk Management - Employee Health Costs, by Department - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Risk Management"

property e:6ghm-dfk7 t:meta.view.license v:name="Public Domain"

property e:6ghm-dfk7 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6ghm-dfk7 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| dept_number | number_of_employees | health_costs_for_department | 
| =========== | =================== | =========================== | 
| 002 Total   | 9                   | 10765.42                    | 
| 007 Total   | 29                  | 31349.90                    | 
| 008 Total   | 21                  | 26061.28                    | 
| 009 Total   | 41                  | 44296.95                    | 
| 010 Total   | 16                  | 16311.01                    | 
| 011 Total   | 29                  | 28846.11                    | 
| 013 Total   | 10                  | 11456.55                    | 
| 014 Total   | 11                  | 15146.25                    | 
| 016 Total   | 67                  | 78293.91                    | 
| 018 Total   | 10                  | 12202.27                    | 
```