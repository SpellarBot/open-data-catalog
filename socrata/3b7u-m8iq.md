# Hartford Capital Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-capital-budget) |
| Metadata | [Link](https://data.hartford.gov/api/views/3b7u-m8iq) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/3b7u-m8iq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/3b7u-m8iq/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 3b7u-m8iq |
| Name | Hartford Capital Budget |
| Created | 2015-08-28T17:52:57Z |
| Publication Date | 2015-08-28T18:16:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | fiscal_year     | Fiscal Year     | number    | number      |
| Yes      | series tag     | service         | Service         | text      | text        |
| Yes      | series tag     | department      | Department      | text      | text        |
| Yes      | series tag     | project_id      | Project ID      | text      | text        |
| Yes      | series tag     | project         | Project         | text      | text        |
| Yes      | series tag     | fund            | Fund            | text      | text        |
| Yes      | series tag     | fund_type       | Fund Type       | text      | text        |
| Yes      | numeric metric | approved_amount | Approved Amount | number    | number      |
| Yes      | numeric metric | actual_amount   | Actual Amount   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3b7u-m8iq d:2018-01-01T00:00:00.000Z t:fund_type="Local Funds" t:project="Redevelopment and Implementation (property Acquisition, redevelopment, building demolition)" t:department=Development t:project_id=D1376 t:service=Development t:fund="CAPITAL PROJECTS CITY" m:approved_amount=3000000 m:actual_amount=0

series e:3b7u-m8iq d:2020-01-01T00:00:00.000Z t:fund_type="Local Funds" t:project="Redevelopment and Implementation (property Acquisition, redevelopment, building demolition)" t:department=Development t:project_id=D1376 t:service=Development t:fund="CAPITAL PROJECTS CITY" m:approved_amount=3000000 m:actual_amount=0

series e:3b7u-m8iq d:2016-01-01T00:00:00.000Z t:fund_type="Local Funds" t:project="Redevelopment and Implementation (property Acquisition, redevelopment, building demolition)" t:department=Development t:project_id=D1376 t:service=Development t:fund="CAPITAL PROJECTS CITY" m:approved_amount=3000000 m:actual_amount=0
```

## Meta Commands

```ls
metric m:approved_amount p:integer l:"Approved Amount" t:dataTypeName=number

metric m:actual_amount p:integer l:"Actual Amount" t:dataTypeName=number

entity e:3b7u-m8iq l:"Hartford Capital Budget" t:url=https://data.hartford.gov/api/views/3b7u-m8iq

property e:3b7u-m8iq t:meta.view v:id=3b7u-m8iq v:averageRating=0 v:name="Hartford Capital Budget"

property e:3b7u-m8iq t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:3b7u-m8iq t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| fiscal_year | service     | department  | project_id | project                                                                                     | fund                  | fund_type   | approved_amount | actual_amount | 
| =========== | =========== | =========== | ========== | =========================================================================================== | ===================== | =========== | =============== | ============= | 
| 2018        | Development | Development | D1376      | Redevelopment and Implementation (property Acquisition, redevelopment, building demolition) | CAPITAL PROJECTS CITY | Local Funds | 3000000         | 0             | 
| 2020        | Development | Development | D1376      | Redevelopment and Implementation (property Acquisition, redevelopment, building demolition) | CAPITAL PROJECTS CITY | Local Funds | 3000000         | 0             | 
| 2016        | Development | Development | D1376      | Redevelopment and Implementation (property Acquisition, redevelopment, building demolition) | CAPITAL PROJECTS CITY | Local Funds | 3000000         | 0             | 
| 2019        | Development | Development | D1376      | Redevelopment and Implementation (property Acquisition, redevelopment, building demolition) | CAPITAL PROJECTS CITY | Local Funds | 3000000         | 0             | 
| 2017        | Development | Development | D1376      | Redevelopment and Implementation (property Acquisition, redevelopment, building demolition) | CAPITAL PROJECTS CITY | Local Funds | 3000000         | 0             | 
| 2018        | Development | Development | D1381      | Document Conversion                                                                         | CAPITAL PROJECTS CITY | Local Funds | 300000          | 0             | 
| 2020        | Development | Development | D1381      | Document Conversion                                                                         | CAPITAL PROJECTS CITY | Local Funds | 300000          | 0             | 
| 2016        | Development | Development | D1381      | Document Conversion                                                                         | CAPITAL PROJECTS CITY | Local Funds | 300000          | 300000        | 
| 2019        | Development | Development | D1381      | Document Conversion                                                                         | CAPITAL PROJECTS CITY | Local Funds | 300000          | 0             | 
| 2017        | Development | Development | D1381      | Document Conversion                                                                         | CAPITAL PROJECTS CITY | Local Funds | 300000          | 0             | 
```