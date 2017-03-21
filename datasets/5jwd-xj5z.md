# Preferred Source Procurements FY15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/preferred-source-procurements-fy15) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5jwd-xj5z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5jwd-xj5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5jwd-xj5z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5jwd-xj5z |
| Name | Preferred Source Procurements FY15 |
| Attribution | Mayor's Office of Contract Services (MOCS) |
| Category | City Government |
| Created | 2015-12-17T16:45:46Z |
| Publication Date | 2015-12-17T16:50:04Z |
| Rows Updated | 2015-12-17T16:45:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | reason_commodity_service | Reason/Commodity/Service | text      | text        |
| Yes      | numeric metric | contract_value           | Contract Value           | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Custom Ordered Products/Services" m:contract_value=513000

series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Data Entry" m:contract_value=20000

series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Document Processing" m:contract_value=89398
```

## Meta Commands

```ls
metric m:contract_value p:integer l:"Contract Value" t:dataTypeName=money

entity e:5jwd-xj5z l:"Preferred Source Procurements FY15" t:attribution="Mayor's Office of Contract Services (MOCS)" t:url=https://data.cityofnewyork.us/api/views/5jwd-xj5z

property e:5jwd-xj5z t:meta.view v:id=5jwd-xj5z v:category="City Government" v:averageRating=0 v:name="Preferred Source Procurements FY15" v:attribution="Mayor's Office of Contract Services (MOCS)"

property e:5jwd-xj5z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:5jwd-xj5z t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```