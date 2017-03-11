# DOP Juvenile Investigations Assigned

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/vk9f-gvzq/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/dop-juvenile-investigations-assigned)
* [Metadata URL](https://data.cityofnewyork.us/api/views/vk9f-gvzq)
* Id = vk9f-gvzq
* Name = DOP Juvenile Investigations Assigned
* Attribution = Department of Probation (DOP)
* Category = Public Safety
* Tags = [dop, investigation, probation]
* Created = 2016-11-21T15:48:22Z
* Publication Date = 2017-02-02T22:48:13Z
* Rows Updated = 2017-02-02T22:47:52Z

## Description



## Columns

```ls
| Name                          | Field Name                    | Data Type | Render Type | Schema Type    | Included | 
| ============================= | ============================= | ========= | =========== | ============== | ======== | 
| Borough                       | borough                       | text      | text        | series tag     | Yes      | 
| Total Investigations Assigned | total_investigations_assigned | text      | text        | series tag     | Yes      | 
| Month                         | month                         | text      | text        |                | No       | 
| Year                          | year                          | number    | number      |                | No       | 
| Investigations Assigned Count | investigations_assigned_count | number    | text        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = month,year
Annotation Fields = 
```

## Data Commands

```ls
series e:vk9f-gvzq d:2016-09-01T00:00:00.000Z t:total_investigations_assigned=Total t:borough=Citywide m:investigations_assigned_count=112

series e:vk9f-gvzq d:2016-11-01T00:00:00.000Z t:total_investigations_assigned=Total t:borough=Citywide m:investigations_assigned_count=146

series e:vk9f-gvzq d:2016-12-01T00:00:00.000Z t:total_investigations_assigned=Total t:borough=Citywide m:investigations_assigned_count=166
```

## Meta Commands

```ls
metric m:investigations_assigned_count p:integer l:"Investigations Assigned Count" t:dataTypeName=number

entity e:vk9f-gvzq l:"DOP Juvenile Investigations Assigned" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/vk9f-gvzq

property e:vk9f-gvzq t:meta.view d:2017-03-07T16:49:00.699Z v:id=vk9f-gvzq v:category="Public Safety" v:averageRating=0 v:name="DOP Juvenile Investigations Assigned" v:attribution="Department of Probation (DOP)"

property e:vk9f-gvzq t:meta.view.owner d:2017-03-07T16:49:00.699Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:vk9f-gvzq t:meta.view.tableauthor d:2017-03-07T16:49:00.699Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```