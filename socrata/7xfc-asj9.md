# Expenditures: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-lbl-linn-benton-lincoln-fiscal-year-2014-53e07) |
| Metadata | [Link](https://data.oregon.gov/api/views/7xfc-asj9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7xfc-asj9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7xfc-asj9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7xfc-asj9 |
| Name | Expenditures: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, expenditures, esd expenditures, lbl esd expenditures, lbl esd, linn benton lincoln esd, 2014 |
| Created | 2014-12-16T20:49:01Z |
| Publication Date | 2014-12-29T06:11:30Z |

## Description

Summary of expenditures for ESD Linn, Benton, and Lincoln for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD#            | number    | number      |
| Yes      | series tag     | esd_name        | ESD Name        | text      | text        |
| Yes      | series tag     | fund            | Fund            | text      | text        |
| Yes      | numeric metric | compt_obj       | Compt_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP_CODE | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:7xfc-asj9 d:2014-01-01T00:00:00.000Z t:vendor_city="CORAL SPRINGS" t:vendor_zip_code=33076 t:vendor_state=FL t:esd_name="Linn Benton Lincoln Education Service District" t:fund="General Fund" t:compt_obj_title="Student Services" t:vendor_name="ARDOR HEALTH SOLUTIONS" m:compt_obj=313 m:esd=2098 m:cash_expense=6892.7

series e:7xfc-asj9 d:2014-01-01T00:00:00.000Z t:vendor_city="CORAL SPRINGS" t:vendor_zip_code=33076 t:vendor_state=FL t:esd_name="Linn Benton Lincoln Education Service District" t:fund="General Fund" t:compt_obj_title="Student Services" t:vendor_name="ARDOR HEALTH SOLUTIONS" m:compt_obj=313 m:esd=2098 m:cash_expense=7921.9

series e:7xfc-asj9 d:2014-01-01T00:00:00.000Z t:vendor_city="CORAL SPRINGS" t:vendor_zip_code=33076 t:vendor_state=FL t:esd_name="Linn Benton Lincoln Education Service District" t:fund="General Fund" t:compt_obj_title="Student Services" t:vendor_name="ARDOR HEALTH SOLUTIONS" m:compt_obj=313 m:esd=2098 m:cash_expense=3077.6
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:compt_obj p:integer l:Compt_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:7xfc-asj9 l:"Expenditures: ESD: LBL (Linn, Benton, Lincoln)  Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/7xfc-asj9

property e:7xfc-asj9 t:meta.view v:id=7xfc-asj9 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: LBL (Linn, Benton, Lincoln)  Fiscal Year 2014"

property e:7xfc-asj9 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7xfc-asj9 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                       | fund         | compt_obj | compt_obj_title  | vendor_name            | vendor_address                    | vendor_city   | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ============================================== | ============ | ========= | ================ | ====================== | ================================= | ============= | ============ | =============== | ============ | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 6892.70      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 7921.90      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 3077.60      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 3510.70      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 5265.60      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 3789.40      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 988.20       | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 3991.10      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 2921.70      | 
| 2098 | Linn Benton Lincoln Education Service District | General Fund | 313       | Student Services | ARDOR HEALTH SOLUTIONS | 5830 CORAL RIDGE DRIVE, SUITE 120 | CORAL SPRINGS | FL           | 33076           | 6091.40      | 
```