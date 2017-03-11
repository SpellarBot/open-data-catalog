# Law Enforcement Personnel by Agency: Beginning 2007

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/khn9-hhpq/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/law-enforcement-personnel-by-agency-beginning-2007)
* [Metadata URL](https://data.ny.gov/api/views/khn9-hhpq)
* Id = khn9-hhpq
* Name = Law Enforcement Personnel by Agency: Beginning 2007
* Attribution = New York State Division of Criminal Justice Services
* [Attribution Link](http://www.criminaljustice.ny.gov/crimnet/ojsa/crimereporting/index.htm)
* Category = Public Safety
* Tags = [personnel, law enforcement, public safety, ucr]
* Created = 2013-03-01T17:47:03Z
* Publication Date = 2016-03-22T22:00:59Z
* Rows Updated = 2016-03-22T22:00:37Z

## Description

The Division of Criminal Justice Services (DCJS) collects personnel statistics from more than 500 New York State police and sheriffs? departments. In New York State, law enforcement agencies use the Uniform Crime Reporting (UCR) system to report their annual personnel counts to DCJS.

## Columns

```ls
| Name               | Field Name         | Data Type | Render Type | Schema Type    | Included | 
| ================== | ================== | ========= | =========== | ============== | ======== | 
| County             | county             | text      | text        | series tag     | Yes      | 
| PD                 | pd                 | text      | text        |                | No       | 
| Year               | year               | number    | number      | time           | Yes      | 
| Sworn Full Time    | sworn_full_time    | number    | number      | numeric metric | Yes      | 
| Sworn Part Time    | sworn_part_time    | number    | number      | numeric metric | Yes      | 
| Sworn Total        | sworn_total        | number    | number      | numeric metric | Yes      | 
| Civilian Full Time | civilian_full_time | number    | number      | numeric metric | Yes      | 
| Civilian Part Time | civilian_park_time | number    | number      | numeric metric | Yes      | 
| Civilian Total     | civilian_total     | number    | number      | numeric metric | Yes      | 
| Full Time Total    | full_time_total    | number    | number      | numeric metric | Yes      | 
| Part Time Total    | part_time_total    | number    | number      | numeric metric | Yes      | 
| Grand Total        | grand_total        | number    | number      | numeric metric | Yes      | 
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
Excluded Fields = pd
Annotation Fields = 
```

## Data Commands

```ls
series e:khn9-hhpq d:2015-01-01T00:00:00.000Z t:county=Albany m:part_time_total=54 m:sworn_part_time=0 m:sworn_total=335 m:civilian_park_time=54 m:civilian_total=152 m:full_time_total=433 m:civilian_full_time=98 m:sworn_full_time=335 m:grand_total=487

series e:khn9-hhpq d:2014-01-01T00:00:00.000Z t:county=Albany m:part_time_total=51 m:sworn_part_time=0 m:sworn_total=337 m:civilian_park_time=51 m:civilian_total=172 m:full_time_total=458 m:civilian_full_time=121 m:sworn_full_time=337 m:grand_total=509

series e:khn9-hhpq d:2013-01-01T00:00:00.000Z t:county=Albany m:part_time_total=52 m:sworn_part_time=0 m:sworn_total=332 m:civilian_park_time=52 m:civilian_total=156 m:full_time_total=436 m:civilian_full_time=104 m:sworn_full_time=332 m:grand_total=488
```

## Meta Commands

```ls
metric m:sworn_full_time p:integer l:"Sworn Full Time" d:"Counts of allsworn law enforcement officers with full arrest powers who were on the payroll as of October 31st Personnelthat work a normalfull?time work week" t:dataTypeName=number

metric m:sworn_part_time p:integer l:"Sworn Part Time" d:"Counts of allsworn law enforcement officers with full arrest powers who were on the payroll as of October 31st Personnelthat work lessthan a normalfull?time work week" t:dataTypeName=number

metric m:sworn_total p:integer l:"Sworn Total" t:dataTypeName=number

metric m:civilian_full_time p:integer l:"Civilian Full Time" d:"Counts of all non?sworn support personnel who were on the payroll as ofOctober 31st Personnelthat work a normalfull?time work week" t:dataTypeName=number

metric m:civilian_park_time p:integer l:"Civilian Part Time" d:"Counts of all non?sworn support personnel who were on the payroll as ofOctober 31st Personnelthat work lessthan a normalfull?time work week" t:dataTypeName=number

metric m:civilian_total p:integer l:"Civilian Total" d:"Counts of all non?sworn support personnel who were on the payroll as ofOctober 31st" t:dataTypeName=number

metric m:full_time_total p:integer l:"Full Time Total" d:"Personnelthat work a normalfull?time work week" t:dataTypeName=number

metric m:part_time_total p:integer l:"Part Time Total" d:"Personnelthat work lessthan a normalfull?time work week" t:dataTypeName=number

metric m:grand_total p:integer l:"Grand Total" t:dataTypeName=number

entity e:khn9-hhpq l:"Law Enforcement Personnel by Agency:  Beginning 2007" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/khn9-hhpq

property e:khn9-hhpq t:meta.view d:2017-03-08T00:36:48.466Z v:id=khn9-hhpq v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/crimereporting/index.htm v:averageRating=0 v:name="Law Enforcement Personnel by Agency:  Beginning 2007" v:attribution="New York State Division of Criminal Justice Services"

property e:khn9-hhpq t:meta.view.owner d:2017-03-08T00:36:48.466Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:khn9-hhpq t:meta.view.tableauthor d:2017-03-08T00:36:48.466Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:khn9-hhpq t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:36:48.466Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```