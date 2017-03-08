# Preferred Source Procurements FY15

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/5jwd-xj5z/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/preferred-source-procurements-fy15)
* [Metadata URL](https://data.cityofnewyork.us/api/views/5jwd-xj5z)
* Id = 5jwd-xj5z
* Name = Preferred Source Procurements FY15
* Attribution = Mayor's Office of Contract Services (MOCS)
* Category = City Government
* Created = 2015-12-17T16:45:46Z
* Publication Date = 2015-12-17T16:50:04Z
* Rows Updated = 2015-12-17T16:45:53Z

## Description



## Columns

```ls
| Name                     | Field Name               | Data Type | Render Type | Schema Type    | Included | 
| ======================== | ======================== | ========= | =========== | ============== | ======== | 
| updated_at               | :updated_at              | meta_data | meta_data   | time           | No       | 
| Reason/Commodity/Service | reason_commodity_service | text      | text        | series tag     | Yes      | 
| Contract Value           | contract_value           | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Custom Ordered Products/Services" m:contract_value=513000

series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Data Entry" m:contract_value=20000

series e:5jwd-xj5z d:2015-12-17T08:45:48.000Z t:reason_commodity_service="Document Processing" m:contract_value=89398
```

## Meta Commands

```ls
entity e:5jwd-xj5z l:"Preferred Source Procurements FY15" t:attribution="Mayor's Office of Contract Services (MOCS)" t:url=https://data.cityofnewyork.us/api/views/5jwd-xj5z

property e:5jwd-xj5z t:meta.view d:2017-03-08T00:14:17.921Z v:id=5jwd-xj5z v:category="City Government" v:averageRating=0 v:name="Preferred Source Procurements FY15" v:attribution="Mayor's Office of Contract Services (MOCS)"

property e:5jwd-xj5z t:meta.view.owner d:2017-03-08T00:14:17.921Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:5jwd-xj5z t:meta.view.tableauthor d:2017-03-08T00:14:17.921Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```