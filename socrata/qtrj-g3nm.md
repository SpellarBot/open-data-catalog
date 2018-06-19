# Cash Assistance Recipients in NYC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cash-assistance-recipients-in-nyc-8972b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qtrj-g3nm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qtrj-g3nm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qtrj-g3nm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qtrj-g3nm |
| Name | Cash Assistance Recipients in NYC |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | cash assistance recipients in nyc, hra, human resources administration |
| Created | 2013-05-17T18:40:29Z |
| Publication Date | 2016-05-23T18:09:42Z |

## Description

Total people receiving cash assistance on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       |                | year                             | Year                             | number    | number      |
| No       |                | month                            | Month                            | number    | number      |
| Yes      | numeric metric | total_cash_assistance_recipients | Total cash assistance recipients | number    | number      |
| Yes      | numeric metric | monthly_percent_change           | MONTHLY percent change           | percent   | percent     |
| Yes      | numeric metric | yearly_percent_change            | YEARLY percent change            | percent   | percent     |
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
series e:qtrj-g3nm d:1996-02-01T00:00:00.000Z m:total_cash_assistance_recipients=476354

series e:qtrj-g3nm d:1996-03-01T00:00:00.000Z m:total_cash_assistance_recipients=475407 m:monthly_percent_change=-0.2

series e:qtrj-g3nm d:1996-04-01T00:00:00.000Z m:total_cash_assistance_recipients=471485 m:monthly_percent_change=-0.8
```

## Meta Commands

```ls
metric m:total_cash_assistance_recipients p:integer l:"Total cash assistance recipients" t:dataTypeName=number

metric m:monthly_percent_change p:float l:"MONTHLY percent change" t:dataTypeName=percent

metric m:yearly_percent_change p:float l:"YEARLY percent change" t:dataTypeName=percent

entity e:qtrj-g3nm l:"Cash Assistance Recipients in NYC" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/qtrj-g3nm

property e:qtrj-g3nm t:meta.view v:id=qtrj-g3nm v:category="Social Services" v:averageRating=0 v:name="Cash Assistance Recipients in NYC" v:attribution="Human Resources Administration (HRA)"

property e:qtrj-g3nm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qtrj-g3nm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | month | total_cash_assistance_recipients | monthly_percent_change | yearly_percent_change | 
| ==== | ===== | ================================ | ====================== | ===================== | 
| 1996 | 2     | 476354                           |                        |                       | 
| 1996 | 3     | 475407                           | -0.2                   |                       | 
| 1996 | 4     | 471485                           | -0.8                   |                       | 
| 1996 | 5     | 466719                           | -1.0                   |                       | 
| 1996 | 6     | 458657                           | -1.7                   |                       | 
| 1996 | 7     | 456343                           | -0.5                   |                       | 
| 1996 | 8     | 451609                           | -1.0                   |                       | 
| 1996 | 9     | 444524                           | -1.6                   |                       | 
| 1996 | 10    | 441702                           | -0.6                   |                       | 
| 1996 | 11    | 431701                           | -2.3                   |                       | 
```