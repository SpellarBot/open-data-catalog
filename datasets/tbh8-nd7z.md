# Expenditures: ESD: Grant: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-grant-fiscal-year-2013-ca0c2) |
| Metadata | [Link](https://data.oregon.gov/api/views/tbh8-nd7z) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tbh8-nd7z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tbh8-nd7z/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tbh8-nd7z |
| Name | Expenditures: ESD: Grant: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, grant, fiscal year 2013 |
| Created | 2013-11-04T19:47:35Z |
| Publication Date | 2013-11-04T19:52:28Z |

## Description

Expenditures for Grant ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD Name        | text      | text        |
| Yes      | numeric metric | fund            | Fund            | number    | number      |
| Yes      | series tag     | fund_name       | Fund Name       | text      | text        |
| Yes      | numeric metric | compt_object    | Compt Object    | number    | number      |
| Yes      | series tag     | compt_obj_title | Compt_Obj_title | text      | text        |
| Yes      | series tag     | vendor_name     | Vendor Name     | text      | text        |
| No       |                | vendor_address  | Vendor Address  | text      | text        |
| Yes      | series tag     | vendor_city     | Vendor City     | text      | text        |
| Yes      | series tag     | vendor_state    | Vendor State    | text      | text        |
| Yes      | series tag     | vendor_zip      | Vendor Zip      | text      | number      |
| Yes      | numeric metric | totalcost       | TotalCost       | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:tbh8-nd7z d:2013-01-01T00:00:00.000Z t:vendor_city="Oklahoma City" t:fund_name=General t:vendor_state=OK t:esd_name="Grant ESD" t:compt_obj_title="Consumable Supplies" t:vendor_name="AFPlan Serv_" m:totalcost=4 m:compt_object=410 m:esd=2007 m:fund=100

series e:tbh8-nd7z d:2013-01-01T00:00:00.000Z t:vendor_city="Oklahoma City" t:fund_name=General t:vendor_state=OK t:esd_name="Grant ESD" t:compt_obj_title="Consumable Supplies" t:vendor_name="AFPlan Serv_" m:totalcost=4 m:compt_object=410 m:esd=2007 m:fund=100

series e:tbh8-nd7z d:2013-01-01T00:00:00.000Z t:vendor_city="Oklahoma City" t:fund_name=General t:vendor_state=OK t:esd_name="Grant ESD" t:compt_obj_title="Consumable Supplies" t:vendor_name="AFPlan Serv_" m:totalcost=4 m:compt_object=410 m:esd=2007 m:fund=100
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:compt_object p:integer l:"Compt Object" t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:tbh8-nd7z l:"Expenditures: ESD: Grant: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/tbh8-nd7z

property e:tbh8-nd7z t:meta.view v:id=tbh8-nd7z v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Grant: Fiscal Year 2013"

property e:tbh8-nd7z t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tbh8-nd7z t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name  | fund | fund_name | compt_object | compt_obj_title     | vendor_name  | vendor_address   | vendor_city   | vendor_state | vendor_zip | totalcost | 
| ==== | ========= | ==== | ========= | ============ | =================== | ============ | ================ | ============= | ============ | ========== | ========= | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
| 2007 | Grant ESD | 100  | General   | 410          | Consumable Supplies | AFPlan Serv_ | P. O. Box 269008 | Oklahoma City | OK           |            | 4.00      | 
```