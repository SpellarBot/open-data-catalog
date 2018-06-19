# ESD Expenditures 2016 - Composite Dataset - V1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esd-expenditures-2016-composite-dataset-v1) |
| Metadata | [Link](https://data.oregon.gov/api/views/2t2b-sfjh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2t2b-sfjh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2t2b-sfjh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2t2b-sfjh |
| Name | ESD Expenditures 2016 - Composite Dataset - V1 |
| Category | Revenue & Expense |
| Tags | 2016, expenditures, esd, fiscal year 2016, esd expenditures |
| Created | 2017-01-08T23:17:22Z |
| Publication Date | 2017-01-08T23:22:49Z |

## Description

This is a composite listing of expenditure data from all ESD's per SB250 for Fiscal Year 2016. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | fiscal_year           | FISCAL YEAR           | number    | number      |
| Yes      | series tag     | esd_id                | ESD ID                | text      | number      |
| Yes      | series tag     | esd_name              | ESD NAME              | text      | text        |
| Yes      | series tag     | fund_name             | FUND NAME             | text      | text        |
| Yes      | numeric metric | compt_obj             | COMPT_OBJ             | number    | number      |
| Yes      | series tag     | compt_obj_title       | COMPT_OBJ_TITLE       | text      | text        |
| Yes      | series tag     | vendor_name           | VENDOR_NAME           | text      | text        |
| Yes      | series tag     | vendor_street_address | VENDOR_STREET ADDRESS | text      | text        |
| Yes      | series tag     | vendor_city           | VENDOR_CITY           | text      | text        |
| Yes      | series tag     | vendor_state          | VENDOR_STATE          | text      | text        |
| Yes      | series tag     | vendor_zip            | VENDOR_ZIP            | text      | text        |
| Yes      | numeric metric | cash_expense          | CASH_EXPENSE          | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2t2b-sfjh d:2016-01-01T00:00:00.000Z t:vendor_city=Portland t:fund_name="General Fund" t:vendor_state=OR t:esd_name="Clackamas ESD" t:vendor_zip=97228-6053 t:esd_id=1902 t:vendor_street_address="Professionals In Education) PO Box 6053" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="ACPE (Association For Compute" m:compt_obj=312 m:cash_expense=1300

series e:2t2b-sfjh d:2016-01-01T00:00:00.000Z t:vendor_city=Rockville t:fund_name="General Fund" t:vendor_state=MD t:esd_name="Clackamas ESD" t:vendor_zip=20849-3289 t:esd_id=1902 t:vendor_street_address="PO Box 1160 #435" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name=ASHA m:compt_obj=312 m:cash_expense=225

series e:2t2b-sfjh d:2016-01-01T00:00:00.000Z t:vendor_city=Wilmington t:fund_name="General Fund" t:vendor_state=DE t:esd_name="Clackamas ESD" t:vendor_zip=19886-5796 t:esd_id=1902 t:vendor_street_address="PO Box 15796" t:compt_obj_title="Inst Prog Improve Serv" t:vendor_name="Bankcard Center" m:compt_obj=312 m:cash_expense=9513.47
```

## Meta Commands

```ls
metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:2t2b-sfjh l:"ESD Expenditures 2016 - Composite Dataset - V1" t:url=https://data.oregon.gov/api/views/2t2b-sfjh

property e:2t2b-sfjh t:meta.view v:id=2t2b-sfjh v:category="Revenue & Expense" v:averageRating=0 v:name="ESD Expenditures 2016 - Composite Dataset - V1"

property e:2t2b-sfjh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:2t2b-sfjh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd_id | esd_name      | fund_name    | compt_obj | compt_obj_title        | vendor_name                         | vendor_street_address                       | vendor_city | vendor_state | vendor_zip | cash_expense | 
| =========== | ====== | ============= | ============ | ========= | ====================== | =================================== | =========================================== | =========== | ============ | ========== | ============ | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | ACPE (Association For Compute       | Professionals In Education) PO Box 6053     | Portland    | OR           | 97228-6053 | 1300.00      | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | ASHA                                | PO Box 1160 #435                            | Rockville   | MD           | 20849-3289 | 225.00       | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Bankcard Center                     | PO Box 15796                                | Wilmington  | DE           | 19886-5796 | 9513.47      | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Confederation Of Oregon             | School Adminstrators 707 13th St SE Ste 100 | Salem       | OR           | 97301-4036 | 299.00       | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | COSA                                | 707 13th St SE Ste 100                      | Salem       | OR           | 97301-4036 | 2328.00      | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | North Clackamas SD 12               | 12400 SE Freeman Way                        | Milwaukie   | OR           | 97222-4740 | 20.00        | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Northwest Regional ESD              | 5825 NE Ray Circle                          | Hillsboro   | OR           | 97124-6436 | 129.00       | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | OASBO                               | 707 13th St SE Ste 100                      | Salem       | OR           | 97301-4036 | 400.00       | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Oregon Employment Relations Boad    | 528 Cottage St., NE Suite 400               | Salem       | OR           | 97301-3807 | 40.00        | 
| 2016        | 1902   | Clackamas ESD | General Fund | 312       | Inst Prog Improve Serv | Oregon School Personnel Association | 707 13th St., SE Suite 100                  | Salem       | OR           | 97301      | 1158.00      | 
```