# Law Enforcement Personnel by Agency: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-enforcement-personnel-by-agency-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/khn9-hhpq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/khn9-hhpq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/khn9-hhpq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | khn9-hhpq |
| Name | Law Enforcement Personnel by Agency: Beginning 2007 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | personnel, law enforcement, public safety, ucr |
| Created | 2013-03-01T17:47:03Z |
| Publication Date | 2016-03-22T22:00:59Z |
| Rows Updated | 2016-03-22T22:00:37Z |

## Description

The Division of Criminal Justice Services (DCJS) collects personnel statistics from more than 500 New York State police and sheriffs’ departments. In New York State, law enforcement agencies use the Uniform Crime Reporting (UCR) system to report their annual personnel counts to DCJS.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | county             | County             | text      | text        |
| No       |                | pd                 | PD                 | text      | text        |
| Yes      | time           | year               | Year               | number    | number      |
| Yes      | numeric metric | sworn_full_time    | Sworn Full Time    | number    | number      |
| Yes      | numeric metric | sworn_part_time    | Sworn Part Time    | number    | number      |
| Yes      | numeric metric | sworn_total        | Sworn Total        | number    | number      |
| Yes      | numeric metric | civilian_full_time | Civilian Full Time | number    | number      |
| Yes      | numeric metric | civilian_park_time | Civilian Part Time | number    | number      |
| Yes      | numeric metric | civilian_total     | Civilian Total     | number    | number      |
| Yes      | numeric metric | full_time_total    | Full Time Total    | number    | number      |
| Yes      | numeric metric | part_time_total    | Part Time Total    | number    | number      |
| Yes      | numeric metric | grand_total        | Grand Total        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = pd
```

## Data Commands

```ls
series e:khn9-hhpq d:2015-01-01T00:00:00.000Z t:county=Albany m:part_time_total=54 m:sworn_part_time=0 m:sworn_total=335 m:civilian_park_time=54 m:civilian_total=152 m:full_time_total=433 m:civilian_full_time=98 m:sworn_full_time=335 m:grand_total=487

series e:khn9-hhpq d:2014-01-01T00:00:00.000Z t:county=Albany m:part_time_total=51 m:sworn_part_time=0 m:sworn_total=337 m:civilian_park_time=51 m:civilian_total=172 m:full_time_total=458 m:civilian_full_time=121 m:sworn_full_time=337 m:grand_total=509

series e:khn9-hhpq d:2013-01-01T00:00:00.000Z t:county=Albany m:part_time_total=52 m:sworn_part_time=0 m:sworn_total=332 m:civilian_park_time=52 m:civilian_total=156 m:full_time_total=436 m:civilian_full_time=104 m:sworn_full_time=332 m:grand_total=488
```

## Meta Commands

```ls
metric m:sworn_full_time p:integer l:"Sworn Full Time" d:"Counts of allsworn law enforcement officers with full arrest powers who were on the payroll as of October 31st Personnelthat work a normalfull‐time work week" t:dataTypeName=number

metric m:sworn_part_time p:integer l:"Sworn Part Time" d:"Counts of allsworn law enforcement officers with full arrest powers who were on the payroll as of October 31st Personnelthat work lessthan a normalfull‐time work week" t:dataTypeName=number

metric m:sworn_total p:integer l:"Sworn Total" t:dataTypeName=number

metric m:civilian_full_time p:integer l:"Civilian Full Time" d:"Counts of all non‐sworn support personnel who were on the payroll as ofOctober 31st Personnelthat work a normalfull‐time work week" t:dataTypeName=number

metric m:civilian_park_time p:integer l:"Civilian Part Time" d:"Counts of all non‐sworn support personnel who were on the payroll as ofOctober 31st Personnelthat work lessthan a normalfull‐time work week" t:dataTypeName=number

metric m:civilian_total p:integer l:"Civilian Total" d:"Counts of all non‐sworn support personnel who were on the payroll as ofOctober 31st" t:dataTypeName=number

metric m:full_time_total p:integer l:"Full Time Total" d:"Personnelthat work a normalfull‐time work week" t:dataTypeName=number

metric m:part_time_total p:integer l:"Part Time Total" d:"Personnelthat work lessthan a normalfull‐time work week" t:dataTypeName=number

metric m:grand_total p:integer l:"Grand Total" t:dataTypeName=number

entity e:khn9-hhpq l:"Law Enforcement Personnel by Agency:  Beginning 2007" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/khn9-hhpq

property e:khn9-hhpq t:meta.view v:id=khn9-hhpq v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/crimereporting/index.htm v:averageRating=0 v:name="Law Enforcement Personnel by Agency:  Beginning 2007" v:attribution="New York State Division of Criminal Justice Services"

property e:khn9-hhpq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:khn9-hhpq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:khn9-hhpq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```