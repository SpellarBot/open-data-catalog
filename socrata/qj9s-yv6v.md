# ODRA MA Trend

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-ma-trend-ea0e4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qj9s-yv6v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qj9s-yv6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qj9s-yv6v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qj9s-yv6v |
| Name | ODRA MA Trend |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra ma trend, hra |
| Created | 2013-05-21T12:06:37Z |
| Publication Date | 2013-05-21T12:08:34Z |

## Description

Monthly trend statistics on medicaid enrollees.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | year                   | Year                   | number    | number      |
| No       |                | month                  | Month                  | number    | number      |
| Yes      | numeric metric | medicaid_enrollees     | Medicaid Enrollees     | number    | number      |
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
series e:qj9s-yv6v d:1998-01-01T00:00:00.000Z m:yearly_percent_change=-3.7 m:medicaid_enrollees=1682264 m:monthly_percent_change=0.4

series e:qj9s-yv6v d:1998-02-01T00:00:00.000Z m:yearly_percent_change=-4.1 m:medicaid_enrollees=1670425 m:monthly_percent_change=-0.7

series e:qj9s-yv6v d:1998-03-01T00:00:00.000Z m:yearly_percent_change=-4.5 m:medicaid_enrollees=1650642 m:monthly_percent_change=-1.2
```

## Meta Commands

```ls
metric m:medicaid_enrollees p:integer l:"Medicaid Enrollees" t:dataTypeName=number

metric m:monthly_percent_change p:float l:"Monthly Percent Change" t:dataTypeName=percent

metric m:yearly_percent_change p:float l:"Yearly Percent Change" t:dataTypeName=percent

entity e:qj9s-yv6v l:"ODRA MA Trend" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/qj9s-yv6v

property e:qj9s-yv6v t:meta.view v:id=qj9s-yv6v v:category="Social Services" v:averageRating=0 v:name="ODRA MA Trend" v:attribution="Human Resources Administration (HRA)"

property e:qj9s-yv6v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qj9s-yv6v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | month | medicaid_enrollees | monthly_percent_change | yearly_percent_change | 
| ==== | ===== | ================== | ====================== | ===================== | 
| 1998 | 1     | 1682264            | 0.40                   | -3.70                 | 
| 1998 | 2     | 1670425            | -0.70                  | -4.10                 | 
| 1998 | 3     | 1650642            | -1.20                  | -4.50                 | 
| 1998 | 4     | 1646511            | -0.30                  | -4.20                 | 
| 1998 | 5     | 1645399            | -0.10                  | -4.20                 | 
| 1998 | 6     | 1644577            | 0.00                   | -3.80                 | 
| 1998 | 7     | 1645745            | 0.10                   | -3.70                 | 
| 1998 | 8     | 1634100            | -0.70                  | -3.90                 | 
| 1998 | 9     | 1637981            | 0.20                   | -3.00                 | 
| 1998 | 10    | 1643000            | 0.30                   | -2.40                 | 
```