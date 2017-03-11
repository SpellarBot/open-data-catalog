# Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/rpbd-ypkv/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/hawaii-renewable-energy-generation-by-utility-county-source-hawaii-public-utilities-commis)
* [Metadata URL](https://data.hawaii.gov/api/views/rpbd-ypkv)
* Id = rpbd-ypkv
* Name = Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)
* Created = 2014-01-16T00:42:45Z
* Publication Date = 2016-04-11T21:13:10Z
* Rows Updated = 2016-04-11T21:10:49Z

## Description



## Columns

```ls
| Name                | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| =================== | =========== | ========= | =========== | ============== | ======== | 
| Year                | year        | number    | number      | time           | Yes      | 
| HECO/Oahu           | heco        | number    | number      | numeric metric | Yes      | 
| HELCO/Hawaii Island | helco       | number    | number      | numeric metric | Yes      | 
| MECO/Maui County    | meco        | number    | number      | numeric metric | Yes      | 
| KIUC/Kauai          | kiuc        | number    | number      | numeric metric | Yes      | 
| State Total         | state_total | number    | number      | numeric metric | Yes      | 
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
series e:rpbd-ypkv d:2009-01-01T00:00:00.000Z m:state_total=964600 m:helco=377730 m:kiuc=41737 m:meco=165835 m:heco=379298

series e:rpbd-ypkv d:2010-01-01T00:00:00.000Z m:state_total=950741 m:helco=383622 m:kiuc=39750 m:meco=182560 m:heco=344809

series e:rpbd-ypkv d:2011-01-01T00:00:00.000Z m:state_total=1186007 m:helco=453349 m:kiuc=45562 m:meco=202270 m:heco=484826
```

## Meta Commands

```ls
metric m:heco p:integer l:HECO/Oahu t:dataTypeName=number

metric m:helco p:integer l:"HELCO/Hawaii Island" t:dataTypeName=number

metric m:meco p:integer l:"MECO/Maui County" t:dataTypeName=number

metric m:kiuc p:integer l:KIUC/Kauai t:dataTypeName=number

metric m:state_total p:integer l:"State Total" t:dataTypeName=number

entity e:rpbd-ypkv l:"Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/rpbd-ypkv

property e:rpbd-ypkv t:meta.view d:2017-03-07T17:21:41.762Z v:id=rpbd-ypkv v:averageRating=0 v:name="Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)"

property e:rpbd-ypkv t:meta.view.owner d:2017-03-07T17:21:41.762Z v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy

property e:rpbd-ypkv t:meta.view.tableauthor d:2017-03-07T17:21:41.762Z v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```