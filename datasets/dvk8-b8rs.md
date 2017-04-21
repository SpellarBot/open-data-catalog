# Budget Management - 2012 Budget Request - Summary of Appropriations by Object Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-management-2012-budget-request-summary-of-appropriations-by-object-classification-7bd4d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dvk8-b8rs) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dvk8-b8rs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dvk8-b8rs/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dvk8-b8rs |
| Name | Budget Management - 2012 Budget Request - Summary of Appropriations by Object Classification |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | 2012 budget |
| Created | 2011-10-25T20:48:22Z |
| Publication Date | 2011-10-26T14:08:47Z |

## Description

2012 budget requests by line-item, by bureau, and elected official.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | fundid           | FundID           | text      | text        |
| Yes      | series tag     | fundtype         | FundType         | text      | text        |
| Yes      | numeric metric | fundsort         | FundSort         | number    | text        |
| Yes      | series tag     | genfundtype      | GenFundType      | text      | text        |
| Yes      | series tag     | sort_for_summary | Sort_for_Summary | text      | text        |
| Yes      | numeric metric | dept             | Dept             | number    | text        |
| Yes      | series tag     | dept_text        | Dept_Text        | text      | text        |
| Yes      | series tag     | depttitle        | DeptTitle        | text      | text        |
| Yes      | series tag     | description      | Description      | text      | text        |
| Yes      | numeric metric | adopted          | Adopted          | money     | money       |
| Yes      | numeric metric | request          | Request          | money     | money       |
| Yes      | numeric metric | presrec          | PresRec          | money     | money       |
| Yes      | numeric metric | expenditures     | Expenditures     | money     | money       |
| No       |                | ac               | AC               | text      | text        |
| No       |                | rc               | RC               | text      | text        |
| No       |                | pc               | PC               | text      | text        |
| No       |                | builddate        | BuildDate        | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = ac,rc,pc,builddate
```

## Data Commands

```ls
series e:dvk8-b8rs d:2012-01-01T00:00:00.000Z t:fundtype=General t:depttitle="County Assessor" t:dept_text=040 t:genfundtype="Corporate Fund" t:description="Salaries and Wages of Regular Employees" t:sort_for_summary=ASSESSOR t:fundid=1000 m:adopted=21636834 m:request=20224243 m:expenditures=16903192.89 m:presrec=20224243 m:dept=40 m:fundsort=1

series e:dvk8-b8rs d:2012-01-01T00:00:00.000Z t:fundtype=General t:depttitle="County Assessor" t:dept_text=040 t:genfundtype="Corporate Fund" t:description="Overtime Compensation" t:sort_for_summary=ASSESSOR t:fundid=1000 m:adopted=124499 m:request=100000 m:expenditures=125217.95 m:presrec=100000 m:dept=40 m:fundsort=1

series e:dvk8-b8rs d:2012-01-01T00:00:00.000Z t:fundtype=General t:depttitle="County Assessor" t:dept_text=040 t:genfundtype="Corporate Fund" t:description="Mandatory  Medicare Costs" t:sort_for_summary=ASSESSOR t:fundid=1000 m:adopted=0 m:expenditures=18720.73 m:dept=40 m:fundsort=1
```

## Meta Commands

```ls
metric m:fundsort p:integer l:FundSort t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:adopted p:integer l:Adopted t:dataTypeName=money

metric m:request p:integer l:Request t:dataTypeName=money

metric m:presrec p:integer l:PresRec t:dataTypeName=money

metric m:expenditures p:double l:Expenditures t:dataTypeName=money

entity e:dvk8-b8rs l:"Budget Management - 2012 Budget Request - Summary of Appropriations by Object Classification" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/dvk8-b8rs

property e:dvk8-b8rs t:meta.view v:id=dvk8-b8rs v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget Management - 2012 Budget Request - Summary of Appropriations by Object Classification" v:attribution="Cook County Department of Budget and Management Services"

property e:dvk8-b8rs t:meta.view.license v:name="Public Domain"

property e:dvk8-b8rs t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:dvk8-b8rs t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| fundid | fundtype | fundsort | genfundtype    | sort_for_summary | dept | dept_text | depttitle       | description                                            | adopted  | request  | presrec  | expenditures | ac | rc | pc | builddate | 
| ====== | ======== | ======== | ============== | ================ | ==== | ========= | =============== | ====================================================== | ======== | ======== | ======== | ============ | == | == | == | ========= | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Salaries and Wages of Regular Employees                | 21636834 | 20224243 | 20224243 | 16903192.89  |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Overtime Compensation                                  | 124499   | 100000   | 100000   | 125217.95    |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Mandatory Medicare Costs                               | 0        |          |          | 18720.73     |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Professional and Technical Membership Fees             | 5000     | 20000    | 20000    | 23323.98     |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Training Programs for Staff Personnel                  | 20000    | 30000    | 30000    | -89          |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Transportation and Other Travel Expenses for Employees | 25000    | 60000    | 60000    | 7133.93      |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Communication Services                                 |          | 35152    | 35152    |              |    |    |    |           | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Postage                                                | 505997   | 381246   | 381246   | 503510.8     |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | Delivery Services                                      | 95       | 1000     | 1000     | 0            |    |    |    | 06-Oct-11 | 
| 1000   | General  | 1        | Corporate Fund | ASSESSOR         | 40   | 040       | County Assessor | External Graphics and Reproduction Services            | 1175724  | 881246   | 881246   | 910698.47    |    |    |    | 06-Oct-11 | 
```