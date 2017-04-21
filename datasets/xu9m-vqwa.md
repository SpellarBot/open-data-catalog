# 2015 Composite All ESD Expenditures SB250

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-composite-all-esd-expenditures-sb250) |
| Metadata | [Link](https://data.oregon.gov/api/views/xu9m-vqwa) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xu9m-vqwa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xu9m-vqwa/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xu9m-vqwa |
| Name | 2015 Composite All ESD Expenditures SB250 |
| Category | Revenue & Expense |
| Tags | 2015; expenditures; esd, fiscal year 2015: esd expenditures |
| Created | 2016-01-04T06:49:33Z |
| Publication Date | 2016-01-04T07:31:11Z |

## Description

This is a composite listing of expenditure data from all ESD's per SB250 for Fiscal Year 2015. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | fiscal_year     | FISCAL YEAR     | number    | number      |
| Yes      | series tag     | esd_id          | ESD ID          | text      | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip      | VENDOR_ZIP      | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:xu9m-vqwa d:2015-01-01T00:00:00.000Z t:vendor_city=Reston t:fund_name="General Fund" t:vendor_state=VA t:esd_name="Clackamas ESD" t:vendor_zip=20191-1598 t:esd_id=1902 t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name=AAHPERD m:compt_obj=312 m:cash_expense=109

series e:xu9m-vqwa d:2015-01-01T00:00:00.000Z t:vendor_city=Branford t:fund_name="General Fund" t:vendor_state=CT t:esd_name="Clackamas ESD" t:vendor_zip=06405-5409 t:esd_id=1902 t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name=AESA m:compt_obj=312 m:cash_expense=495

series e:xu9m-vqwa d:2015-01-01T00:00:00.000Z t:vendor_city=Tigard t:fund_name="General Fund" t:vendor_state=OR t:esd_name="Clackamas ESD" t:vendor_zip=97223 t:esd_id=1902 t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="Alternative Services - Oregon Inc." m:compt_obj=312 m:cash_expense=1300
```

## Meta Commands

```ls
metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:xu9m-vqwa l:"2015 Composite All ESD Expenditures  SB250" t:url=https://data.oregon.gov/api/views/xu9m-vqwa

property e:xu9m-vqwa t:meta.view v:id=xu9m-vqwa v:category="Revenue & Expense" v:averageRating=0 v:name="2015 Composite All ESD Expenditures  SB250"

property e:xu9m-vqwa t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:xu9m-vqwa t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd_id | esd_name      | fund_name    | compt_obj | compt_obj_title        | vendor_name                        | vendor_address                 | vendor_city  | vendor_state | vendor_zip | cash_expense | 
| =========== | ====== | ============= | ============ | ========= | ====================== | ================================== | ============================== | ============ | ============ | ========== | ============ | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | AAHPERD                            | 1900 Association Drive         | Reston       | VA           | 20191-1598 | 109          | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | AESA                               | 53 Hotchkiss Grove Road        | Branford     | CT           | 06405-5409 | 495          | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Alternative Services - Oregon Inc. | 7165 SW Fir Loop, Suite 200    | Tigard       | OR           | 97223      | 1300.00      | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | American Physical Therapy          | 1111 N Fairfax St              | Alexandria   | VA           | 22314-1484 | 465          | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | ASCD                               | PO Box 17035                   | Baltimore    | MD           | 21297-0203 | 209          | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | ASHA                               | c/o Suntrust Bank PO Box 79952 | Baltimore    | MD           | 21279-0952 | 450          | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Bajio Mexican Grill                | 9220 SE 82nd Ave               | Happy Valley | OR           | 97086-3642 | 1525.75      | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Bankcard Center                    | PO Box 15796                   | Wilmington   | DE           | 19886-5796 | 11676.94     | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Bend Inn & Suites                  | 15 NE Butler Market Rd         | Bend         | OR           | 97701      | 344.07       | 
| 2015        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Career Track                       | PO Box 219468                  | Kansas City  | MO           | 64121-9468 | 149          | 
```