# Expenditures: ESD: Lake County: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-lake-county-fiscal-year-2013-f8e5c) |
| Metadata | [Link](https://data.oregon.gov/api/views/jwiy-7t5b) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jwiy-7t5b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jwiy-7t5b/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jwiy-7t5b |
| Name | Expenditures: ESD: Lake County: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, lake county, fiscal year 2013 |
| Created | 2013-10-24T19:06:40Z |
| Publication Date | 2013-10-24T19:10:31Z |

## Description

Expenditures for Lake County ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jwiy-7t5b d:2013-01-01T00:00:00.000Z t:fund_name="200/Special Funds" t:vendor_state=OR t:esd_name="Lake County ESD" t:compt_obj_title="Student Services" t:vendor_name="4-H LAKE COUNTY LEADERS ASSOC." m:compt_obj=313 m:esd=2058 m:cash_expense=80

series e:jwiy-7t5b d:2013-01-01T00:00:00.000Z t:fund_name="501/Print Shop" t:vendor_state=MO t:esd_name="Lake County ESD" t:compt_obj_title=Tif/Facilities t:vendor_name="ABS FINANCE" m:compt_obj=324 m:esd=2058 m:cash_expense=6355.61

series e:jwiy-7t5b d:2013-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Lake County ESD" t:compt_obj_title="Repairs & Maint" t:vendor_name="ACCTECH - A SYSTEMS INTEGRATOR" m:compt_obj=322 m:esd=2058 m:cash_expense=5988
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:jwiy-7t5b l:"Expenditures: ESD: Lake County: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/jwiy-7t5b

property e:jwiy-7t5b t:meta.view v:id=jwiy-7t5b v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Lake County: Fiscal Year 2013"

property e:jwiy-7t5b t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jwiy-7t5b t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name        | fund_name         | compt_obj | compt_obj_title      | vendor_state | vendor_name                    | cash_expense | 
| ==== | =============== | ================= | ========= | ==================== | ============ | ============================== | ============ | 
| 2058 | Lake County ESD | 200/Special Funds | 313       | Student Services     | OR           | 4-H LAKE COUNTY LEADERS ASSOC. | 80.00        | 
| 2058 | Lake County ESD | 501/Print Shop    | 324       | Tif/Facilities       | MO           | ABS FINANCE                    | 6355.61      | 
| 2058 | Lake County ESD | 100/General Fund  | 322       | Repairs & Maint      | OR           | ACCTECH - A SYSTEMS INTEGRATOR | 5988.00      | 
| 2058 | Lake County ESD | 100/General Fund  | 348       | Travel-Prof Dev      | OR           | ADEL SCHOOL DISTRICT #21       | 179.80       | 
| 2058 | Lake County ESD | 100/General Fund  | 341       | Travel-In Dist.      | OR           | ADEL STORE                     | 40.00        | 
| 2058 | Lake County ESD | 100/General Fund  | 311       | Instruction Services | OR           | AIMEE QUINLIVAN                | 100.00       | 
| 2058 | Lake County ESD | 200/Special Funds | 313       | Student Services     | UT           | ALGER THEATER                  | 250.00       | 
| 2058 | Lake County ESD | 100/General Fund  | 318       | Prof Development     | OR           | ALICE HUNSAKER                 | 100.00       | 
| 2058 | Lake County ESD | 100/General Fund  | 341       | Travel-In Dist.      | OR           | ALICE HUNSAKER                 | 731.50       | 
| 2058 | Lake County ESD | 100/General Fund  | 342       | Travel-Out Of Dist.  | OR           | ALICE HUNSAKER                 | 130.13       | 
```