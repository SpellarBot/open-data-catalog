# Technology Expenditure Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/technology-expenditure-report) |
| Metadata | [Link](https://data.iowa.gov/api/views/haxp-jp5t) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/haxp-jp5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/haxp-jp5t/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | haxp-jp5t |
| Name | Technology Expenditure Report |
| Attribution | Iowa Office of the Chief Information Officer |
| Category | Government |
| Tags | technology, expenditures |
| Created | 2017-01-23T16:01:32Z |
| Publication Date | 2017-01-26T15:28:54Z |

## Description

This report contains technology expenditures for the executive branch summarized by Budget Fiscal Year, Month, Agency and Object Name.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | numeric metric | bfy             | BFY             | number        | number        |
| Yes      | time           | month_ending    | Month Ending    | calendar_date | calendar_date |
| Yes      | series tag     | department      | Department      | text          | text          |
| Yes      | series tag     | department_name | Department Name | text          | text          |
| Yes      | numeric metric | object_class    | Object Class    | number        | text          |
| Yes      | numeric metric | object          | Object          | number        | text          |
| Yes      | series tag     | object_name     | Object Name     | text          | text          |
| Yes      | numeric metric | posting_am      | Posting Amount  | money         | money         |
```

## Time Field

```ls
Value = month_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:haxp-jp5t d:2016-12-31T00:00:00.000Z t:department=005 t:object_name="Desktop HW Purchase or Lease-Non Inventory" t:department_name="Administrative Services, Dept" m:bfy=2017 m:posting_am=96147.24 m:object_class=510 m:object=3810

series e:haxp-jp5t d:2016-12-31T00:00:00.000Z t:department=005 t:object_name="Desktop SW Purchase or License" t:department_name="Administrative Services, Dept" m:bfy=2017 m:posting_am=9314.27 m:object_class=510 m:object=3820

series e:haxp-jp5t d:2016-12-31T00:00:00.000Z t:department=005 t:object_name="Desktop Misc,Parts,Supplies,Consumable" t:department_name="Administrative Services, Dept" m:bfy=2017 m:posting_am=9109.02 m:object_class=510 m:object=3830
```

## Meta Commands

```ls
metric m:bfy p:integer l:BFY d:"The budget fiscal year the technology expenditure was made. BFY runs from July 1 through June 30 and is labeled for the calendar year for which it ends." t:dataTypeName=number

metric m:object_class p:integer l:"Object Class" d:"Code for broad object class. Technology expenditures fall under 418 and 510." t:dataTypeName=number

metric m:object p:integer l:Object d:"Code representing the category of expenditure." t:dataTypeName=number

metric m:posting_am p:double l:"Posting Amount" d:"This is the total expenditure for the object name, department, month and BFY." t:dataTypeName=money

entity e:haxp-jp5t l:"Technology Expenditure Report" t:attribution="Iowa Office of the Chief Information Officer" t:url=https://data.iowa.gov/api/views/haxp-jp5t

property e:haxp-jp5t t:meta.view v:id=haxp-jp5t v:category=Government v:averageRating=0 v:name="Technology Expenditure Report" v:attribution="Iowa Office of the Chief Information Officer"

property e:haxp-jp5t t:meta.view.license v:name="Public Domain"

property e:haxp-jp5t t:meta.view.owner v:id=e8dc-yjpg v:screenName="Ken Moore" v:displayName="Ken Moore"

property e:haxp-jp5t t:meta.view.tableauthor v:id=e8dc-yjpg v:screenName="Ken Moore" v:roleName=administrator v:displayName="Ken Moore"
```

## Top Records

```ls
| bfy  | month_ending        | department | department_name                  | object_class | object | object_name                                | posting_am | 
| ==== | =================== | ========== | ================================ | ============ | ====== | ========================================== | ========== | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3810   | Desktop HW Purchase or Lease-Non Inventory | 96147.24   | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3820   | Desktop SW Purchase or License             | 9314.27    | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3830   | Desktop Misc,Parts,Supplies,Consumable     | 9109.02    | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3840   | Desktop HW Maintenance,Consumable          | 9946.20    | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3850   | Desktop SW Maintenance,Consumable          | 92020.28   | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3920   | Server SW Purchase or License              | 937388.15  | 
| 2017 | 2016-12-31T00:00:00 | 005        | Administrative Services, Dept    | 510          | 3950   | Server SW Maintenance,Consumable           | 95247.02   | 
| 2017 | 2016-12-31T00:00:00 | 009        | Agriculture and Land Stewardship | 510          | 3810   | Desktop HW Purchase or Lease-Non Inventory | 93116.03   | 
| 2017 | 2016-12-31T00:00:00 | 009        | Agriculture and Land Stewardship | 510          | 3820   | Desktop SW Purchase or License             | 9446.21    | 
| 2017 | 2016-12-31T00:00:00 | 009        | Agriculture and Land Stewardship | 510          | 4710   | Printer HW Purchase or Lease-Non Inventory | 966.79     | 
```