# Risk Management - Employee Healthcare Costs by Department - July 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employee-healthcare-costs-by-department-july-2012-119d8) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/4r8d-ebk5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/4r8d-ebk5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/4r8d-ebk5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 4r8d-ebk5 |
| Name | Risk Management - Employee Healthcare Costs by Department - July 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-08-03T15:03:41Z |
| Publication Date | 2014-10-09T22:19:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | dept                        | Dept                        | text      | text        |
| Yes      | numeric metric | number_of_employees         | Number of Employees         | number    | number      |
| Yes      | series tag     | health_costs_for_department | Health Costs for Department | text      | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4r8d-ebk5 d:2012-01-01T00:00:00.000Z t:health_costs_for_department=10114.05 t:dept=002 m:number_of_employees=10

series e:4r8d-ebk5 d:2012-01-01T00:00:00.000Z t:health_costs_for_department=32616.77 t:dept=007 m:number_of_employees=37

series e:4r8d-ebk5 d:2012-01-01T00:00:00.000Z t:health_costs_for_department=24649.37 t:dept=008 m:number_of_employees=22
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

entity e:4r8d-ebk5 l:"Risk Management - Employee Healthcare Costs by Department - July 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/4r8d-ebk5

property e:4r8d-ebk5 t:meta.view v:id=4r8d-ebk5 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employee Healthcare Costs by Department - July 2012" v:attribution="Cook County Department of Risk Management"

property e:4r8d-ebk5 t:meta.view.license v:name="Public Domain"

property e:4r8d-ebk5 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:4r8d-ebk5 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| dept | number_of_employees | health_costs_for_department | 
| ==== | =================== | =========================== | 
| 002  | 10                  | 10114.05                    | 
| 007  | 37                  | 32616.77                    | 
| 008  | 22                  | 24649.37                    | 
| 009  | 42                  | 36803.40                    | 
| 010  | 12                  | 9789.88                     | 
| 011  | 36                  | 30479.13                    | 
| 013  | 8                   | 9399.40                     | 
| 014  | 15                  | 15930.58                    | 
| 016  | 54                  | 55947.42                    | 
| 018  | 9                   | 9675.80                     | 
```