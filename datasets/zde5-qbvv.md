# Human Resources--2010 Employees, Union vs Non-Union Positiong, by Pay Period

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-2010-employees-union-vs-non-union-positiong-by-pay-period-c6d40) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/zde5-qbvv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/zde5-qbvv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/zde5-qbvv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | zde5-qbvv |
| Name | Human Resources--2010 Employees, Union vs Non-Union Positiong, by Pay Period |
| Attribution | Cook County Department of Human Resources |
| Category | Finance & Administration |
| Created | 2011-09-12T18:28:02Z |
| Publication Date | 2014-10-09T21:05:08Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | pay_period_end_date | Pay Period End Date | date      | date        |
| Yes      | numeric metric | total_employees_utp | Total Employees UTP | number    | number      |
| Yes      | numeric metric | amount_union        | Amount Union        | number    | number      |
| Yes      | numeric metric | amount_non_union    | Amount Non-Union    | number    | number      |
| Yes      | numeric metric | percent_union       | Percent Union       | percent   | percent     |
| Yes      | numeric metric | percent_non_union   | Percent Non-Union   | percent   | percent     |
```

## Time Field

```ls
Value = pay_period_end_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:zde5-qbvv d:2010-01-16T08:00:00.000Z m:amount_non_union=794 m:percent_non_union=31.24 m:total_employees_utp=2542 m:amount_union=1748 m:percent_union=68.76

series e:zde5-qbvv d:2010-02-27T08:00:00.000Z m:amount_non_union=775 m:percent_non_union=33.55 m:total_employees_utp=2310 m:amount_union=1535 m:percent_union=66.45

series e:zde5-qbvv d:2010-03-13T08:00:00.000Z m:amount_non_union=770 m:percent_non_union=33.36 m:total_employees_utp=2308 m:amount_union=1538 m:percent_union=66.64
```

## Meta Commands

```ls
metric m:total_employees_utp p:integer l:"Total Employees UTP" d:"Total amount of employees Under the authority of the County Board President that were paid in that pay period" t:dataTypeName=number

metric m:amount_union p:integer l:"Amount Union" d:"Amount of employees paid that were covered by a collective bargaining agreement." t:dataTypeName=number

metric m:amount_non_union p:integer l:"Amount Non-Union" d:"Employees paid in that period not covered by a collective bargaining agreement." t:dataTypeName=number

metric m:percent_union p:float l:"Percent Union" d:"Percentage of the entire amount of employees Under the Office of the President of the County Board represented by a collective bargaining agreement." t:dataTypeName=percent

metric m:percent_non_union p:float l:"Percent Non-Union" d:"Percentage of the entire amount of employees under the Office of the County Board President not represented by a collective bargaining agreement." t:dataTypeName=percent

entity e:zde5-qbvv l:"Human Resources--2010 Employees, Union vs Non-Union Positiong, by Pay Period" t:attribution="Cook County Department of Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/zde5-qbvv

property e:zde5-qbvv t:meta.view v:id=zde5-qbvv v:category="Finance & Administration" v:averageRating=0 v:name="Human Resources--2010 Employees, Union vs Non-Union Positiong, by Pay Period" v:attribution="Cook County Department of Human Resources"

property e:zde5-qbvv t:meta.view.license v:name="Public Domain"

property e:zde5-qbvv t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:zde5-qbvv t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| pay_period_end_date | total_employees_utp | amount_union | amount_non_union | percent_union | percent_non_union | 
| =================== | =================== | ============ | ================ | ============= | ================= | 
| 1263628800          | 2542                | 1748         | 794              | 68.76         | 31.24             | 
| 1267257600          | 2310                | 1535         | 775              | 66.45         | 33.55             | 
| 1268467200          | 2308                | 1538         | 770              | 66.64         | 33.36             | 
| 1270882800          | 2302                | 1538         | 764              | 66.81         | 33.19             | 
| 1273474800          | 2299                | 1529         | 770              | 66.51         | 33.49             | 
| 1275721200          | 2326                | 1547         | 779              | 66.51         | 33.49             | 
| 1279350000          | 2495                | 1548         | 947              | 62.04         | 37.96             | 
| 1281769200          | 2567                | 1549         | 1018             | 60.34         | 39.66             | 
| 1285398000          | 2485                | 1557         | 928              | 62.66         | 37.34             | 
| 1286607600          | 2466                | 1560         | 906              | 63.26         | 36.74             | 
```