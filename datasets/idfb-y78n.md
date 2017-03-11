# Recreational Boating Permits

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/idfb-y78n/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/recreational-boating-permits-121b6)
* Id = idfb-y78n
* Name = Recreational Boating Permits
* Attribution = Department of Environmental Protection (DEP)
* Tags = [recreational boating permits, dep, boating]
* Created = 2014-01-08T18:18:03Z
* Publication Date = 2016-11-14T22:20:48Z
* Rows Updated = 2016-11-14T22:20:44Z

## Description



## Columns

```ls
| Name           | Field Name     | Data Type | Render Type | Schema Type    | Included | 
| ============== | ============== | ========= | =========== | ============== | ======== | 
| Year           | year           | number    | text        | time           | Yes      | 
| Basin          | company_name   | text      | text        | series tag     | Yes      | 
| Permits Issued | permits_issued | number    | text        | numeric metric | Yes      | 
| Seasonal Tags  | seasonal_tags  | number    | text        | numeric metric | Yes      | 
| Temporary Tags | temporary_tags | number    | text        | numeric metric | Yes      | 
| Canoes         | canoes         | number    | text        | numeric metric | Yes      | 
| Kayaks         | kayaks         | number    | text        | numeric metric | Yes      | 
| Rowboats       | rowboats       | number    | text        | numeric metric | Yes      | 
| Sailboats      | sailboats      | number    | text        | numeric metric | Yes      | 
| Sculls         | sculls         | number    | text        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
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
series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Cannonsville m:permits_issued=103 m:temporary_tags=45 m:seasonal_tags=58 m:sailboats=4 m:sculls=1 m:kayaks=53 m:rowboats=11 m:canoes=34

series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Neversink m:permits_issued=122 m:temporary_tags=59 m:seasonal_tags=63 m:sailboats=6 m:sculls=0 m:kayaks=91 m:rowboats=5 m:canoes=20

series e:idfb-y78n d:2013-01-01T00:00:00.000Z t:company_name=Pepacton m:permits_issued=457 m:temporary_tags=238 m:seasonal_tags=219 m:sailboats=10 m:sculls=1 m:kayaks=311 m:rowboats=15 m:canoes=120
```

## Meta Commands

```ls
metric m:permits_issued p:integer l:"Permits Issued" t:dataTypeName=number

metric m:seasonal_tags p:integer l:"Seasonal Tags" t:dataTypeName=number

metric m:temporary_tags p:integer l:"Temporary Tags" t:dataTypeName=number

metric m:canoes p:integer l:Canoes t:dataTypeName=number

metric m:kayaks p:integer l:Kayaks t:dataTypeName=number

metric m:rowboats p:integer l:Rowboats t:dataTypeName=number

metric m:sailboats p:integer l:Sailboats t:dataTypeName=number

metric m:sculls p:integer l:Sculls t:dataTypeName=number

entity e:idfb-y78n l:"Recreational Boating Permits" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/idfb-y78n

property e:idfb-y78n t:meta.view d:2017-03-03T14:37:11.953Z v:id=idfb-y78n v:averageRating=0 v:name="Recreational Boating Permits" v:attribution="Department of Environmental Protection (DEP)"

property e:idfb-y78n t:meta.view.owner d:2017-03-03T14:37:11.953Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:idfb-y78n t:meta.view.tableauthor d:2017-03-03T14:37:11.953Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```