# TPW_FleetTechnicianBillableHours

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tpw-fleettechnicianbillablehours) |
| Metadata | [Link](https://data.srcity.org/api/views/dyvq-j7gn) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/dyvq-j7gn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/dyvq-j7gn/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | dyvq-j7gn |
| Name | TPW_FleetTechnicianBillableHours |
| Created | 2017-02-04T01:14:16Z |
| Publication Date | 2017-02-06T04:56:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | time           | fiscalyear    | FiscalYear    | calendar_date | calendar_date |
| Yes      | numeric metric | billablehours | BillableHours | number        | number        |
```

## Time Field

```ls
Value = fiscalyear
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dyvq-j7gn d:2015-06-30T00:00:00.000Z m:billablehours=1292.74066666667

series e:dyvq-j7gn d:2016-06-30T00:00:00.000Z m:billablehours=1349.96352941176

series e:dyvq-j7gn d:2017-06-30T00:00:00.000Z m:billablehours=1232.870625
```

## Meta Commands

```ls
metric m:billablehours p:double l:BillableHours t:dataTypeName=number

entity e:dyvq-j7gn l:TPW_FleetTechnicianBillableHours t:url=https://data.srcity.org/api/views/dyvq-j7gn

property e:dyvq-j7gn t:meta.view d:2017-06-09T13:54:20.591Z v:id=dyvq-j7gn v:averageRating=0 v:name=TPW_FleetTechnicianBillableHours

property e:dyvq-j7gn t:meta.view.owner d:2017-06-09T13:54:20.591Z v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:dyvq-j7gn t:meta.view.tableauthor d:2017-06-09T13:54:20.591Z v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| fiscalyear          | billablehours    | 
| =================== | ================ | 
| 2015-06-30T00:00:00 | 1292.74066666667 | 
| 2016-06-30T00:00:00 | 1349.96352941176 | 
| 2017-06-30T00:00:00 | 1232.870625      | 
```