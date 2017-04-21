# Home Care Caseload

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-home-care-trends-71943) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xjur-zbxw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xjur-zbxw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xjur-zbxw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xjur-zbxw |
| Name | Home Care Caseload |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra home care trends, hra |
| Created | 2013-05-21T11:50:52Z |
| Publication Date | 2016-11-04T14:12:31Z |

## Description

Monthly trend analysis on home care cases.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | year                   | Year                   | number    | number      |
| No       |                | month                  | Month                  | number    | number      |
| Yes      | numeric metric | cases                  | Cases                  | number    | number      |
| Yes      | numeric metric | monthly_percent_change | Monthly Percent Change | percent   | percent     |
| Yes      | numeric metric | yearly_percent_change  | Yearly Percent Change  | percent   | percent     |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:xjur-zbxw d:1995-01-01T00:00:00.000Z m:yearly_percent_change=5.2 m:cases=63500 m:monthly_percent_change=-0.5

series e:xjur-zbxw d:1995-02-01T00:00:00.000Z m:yearly_percent_change=5.4 m:cases=63346 m:monthly_percent_change=-0.2

series e:xjur-zbxw d:1995-03-01T00:00:00.000Z m:yearly_percent_change=3.8 m:cases=62665 m:monthly_percent_change=-1.1
```

## Meta Commands

```ls
metric m:cases p:integer l:Cases t:dataTypeName=number

metric m:monthly_percent_change p:float l:"Monthly Percent Change" t:dataTypeName=percent

metric m:yearly_percent_change p:float l:"Yearly Percent Change" t:dataTypeName=percent

entity e:xjur-zbxw l:"Home Care Caseload" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/xjur-zbxw

property e:xjur-zbxw t:meta.view v:id=xjur-zbxw v:category="Social Services" v:averageRating=0 v:name="Home Care Caseload" v:attribution="Human Resources Administration (HRA)"

property e:xjur-zbxw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xjur-zbxw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | month | cases | monthly_percent_change | yearly_percent_change | 
| ==== | ===== | ===== | ====================== | ===================== | 
| 1995 | 1     | 63500 | -0.50                  | 5.20                  | 
| 1995 | 2     | 63346 | -0.20                  | 5.40                  | 
| 1995 | 3     | 62665 | -1.10                  | 3.80                  | 
| 1995 | 4     | 62677 | 0.00                   | 1.80                  | 
| 1995 | 5     | 62961 | 0.50                   | 2.80                  | 
| 1995 | 6     | 63189 | 0.40                   | 2.40                  | 
| 1995 | 7     | 62564 | -1.00                  | 0.60                  | 
| 1995 | 8     | 62656 | 0.10                   | 0.10                  | 
| 1995 | 9     | 62910 | 0.40                   | -0.40                 | 
| 1995 | 10    | 62285 | -1.00                  | -1.10                 | 
```