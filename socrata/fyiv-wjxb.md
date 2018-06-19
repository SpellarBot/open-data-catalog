# Expenditures: ESD: Clackamas: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-clackamas-fy-2013-c9d68) |
| Metadata | [Link](https://data.oregon.gov/api/views/fyiv-wjxb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fyiv-wjxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fyiv-wjxb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fyiv-wjxb |
| Name | Expenditures: ESD: Clackamas: FY 2013 |
| Category | Revenue & Expense |
| Tags | esd expenditures, clackamas esd, clackamas esd expenditures, esd, education service district |
| Created | 2013-11-26T16:02:41Z |
| Publication Date | 2013-11-26T16:05:59Z |

## Description

Summary of expenditures for Clackamas ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | schoolyear      | SchoolYear      | text      | text        |
| Yes      | series tag     | esd_id          | ESD_ID          | text      | number      |
| Yes      | series tag     | esd_name        | ESD_Name        | text      | text        |
| Yes      | numeric metric | fund            | FUND            | number    | number      |
| Yes      | series tag     | fund_name       | Fund_Name       | text      | text        |
| Yes      | numeric metric | compt_obj       | Compt_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | Compt_OBJ_Title | text      | text        |
| Yes      | series tag     | vendor_name     | Vendor_Name     | text      | text        |
| Yes      | series tag     | vendor_street   | Vendor_Street   | text      | text        |
| Yes      | series tag     | vendor_city     | Vendor_City     | text      | text        |
| Yes      | series tag     | vendor_state    | Vendor_State    | text      | text        |
| Yes      | series tag     | vendor_zip      | Vendor_Zip      | text      | text        |
| Yes      | numeric metric | cash_expense    | Cash_Expense    | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fyiv-wjxb d:2013-01-01T00:00:00.000Z t:fund_name="General Fund" t:vendor_city=Salem t:esd_name="Clackamas Educational Service District" t:vendor_state=OR t:vendor_zip=97308-0523 t:schoolyear=2012-13 t:esd_id=1902 t:vendor_street="PO Box 523" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="OSHA Salem" m:compt_obj=312 m:fund=100 m:cash_expense=305

series e:fyiv-wjxb d:2013-01-01T00:00:00.000Z t:fund_name="General Fund" t:vendor_city=Tigard t:esd_name="Clackamas Educational Service District" t:vendor_state=OR t:vendor_zip=97223 t:schoolyear=2012-13 t:esd_id=1902 t:vendor_street="7165 SW Fir Loop, Suite 200" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="Alternative Services - Oregon Inc." m:compt_obj=312 m:fund=100 m:cash_expense=1100

series e:fyiv-wjxb d:2013-01-01T00:00:00.000Z t:fund_name="General Fund" t:vendor_city=Alexandria t:esd_name="Clackamas Educational Service District" t:vendor_state=VA t:vendor_zip=22314-1484 t:schoolyear=2012-13 t:esd_id=1902 t:vendor_street="1111 N Fairfax St" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="American Physical Therapy" m:compt_obj=312 m:fund=100 m:cash_expense=895
```

## Meta Commands

```ls
metric m:fund p:integer l:FUND t:dataTypeName=number

metric m:compt_obj p:integer l:Compt_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:Cash_Expense t:dataTypeName=money

entity e:fyiv-wjxb l:"Expenditures:  ESD: Clackamas: FY 2013" t:url=https://data.oregon.gov/api/views/fyiv-wjxb

property e:fyiv-wjxb t:meta.view v:id=fyiv-wjxb v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures:  ESD: Clackamas: FY 2013"

property e:fyiv-wjxb t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:fyiv-wjxb t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esd_id | esd_name                               | fund | fund_name    | compt_obj | compt_obj_title        | vendor_name                        | vendor_street                          | vendor_city | vendor_state | vendor_zip | cash_expense | 
| ========== | ====== | ====================================== | ==== | ============ | ========= | ====================== | ================================== | ====================================== | =========== | ============ | ========== | ============ | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | OSHA Salem                         | PO Box 523                             | Salem       | OR           | 97308-0523 | 305.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | Alternative Services - Oregon Inc. | 7165 SW Fir Loop, Suite 200            | Tigard      | OR           | 97223      | 1100.00      | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | American Physical Therapy          | 1111 N Fairfax St                      | Alexandria  | VA           | 22314-1484 | 895.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | ASCD                               | PO Box 17035                           | Baltimore   | MD           | 21297-0203 | 219.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | ASHA                               | c/o Suntrust Bank PO Box 79952         | Baltimore   | MD           | 21279-0952 | 900.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | ATG Rehab                          | 24581 Network Place                    | Chicago     | IL           | 60673-1245 | 120.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | Bankcard Center                    | PO Box 15796                           | Wilmington  | DE           | 19886-5796 | 1880.07      | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | Bureau of Education & Research     | 915 118th Ave SE                       | Bellevue    | WA           | 98005-3819 | 225.00       | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | CMI Education Institute, Inc       | Premier Education Solutions PO Box 900 | Eau Claire  | WI           | 54702-0900 | 1006.90      | 
| 2012-13    | 1902   | Clackamas Educational Service District | 100  | General Fund | 312       | Inst Prog Improve Serv | Communication Plus                 | PO Box 30310                           | Spokane     | WA           | 99223-3005 | 220.00       | 
```