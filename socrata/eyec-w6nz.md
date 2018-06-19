# Austin Water - Registered Water Services Technicians

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-registered-water-services-technicians) |
| Metadata | [Link](https://data.austintexas.gov/api/views/eyec-w6nz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/eyec-w6nz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/eyec-w6nz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | eyec-w6nz |
| Name | Austin Water - Registered Water Services Technicians |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, technicians |
| Created | 2015-08-14T20:23:42Z |
| Publication Date | 2015-08-14T20:25:44Z |

## Description

A list of registered Water Services Technicians and their employers that provide the services required from customers that are regulated under the Cross Connection/Water Protection Program.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | technician  | TECHNICIAN | text      | text        |
| Yes      | series tag  | employer    | EMPLOYER   | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eyec-w6nz d:2015-08-14T13:23:44.000Z t:phone=9726997156 t:technician="HARRIS, JACK" t:employer="01 ACCURACY BACKFLOW" m:row_number.eyec-w6nz=1

series e:eyec-w6nz d:2015-08-14T13:23:44.000Z t:phone=5129476714 t:technician="LINGLE, MIKE L" t:employer="1ST CHOICE BACKFLOW TESTING" m:row_number.eyec-w6nz=2

series e:eyec-w6nz d:2015-08-14T13:23:44.000Z t:phone=2103773473 t:technician="CICHON, CLAYTON" t:employer="1ST FIRE PROTECTION SERVICES, LLC" m:row_number.eyec-w6nz=3
```

## Meta Commands

```ls
metric m:row_number.eyec-w6nz p:long l:"Row Number"

entity e:eyec-w6nz l:"Austin Water - Registered Water Services Technicians" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/eyec-w6nz

property e:eyec-w6nz t:meta.view v:id=eyec-w6nz v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Registered Water Services Technicians" v:attribution="Austin Water"

property e:eyec-w6nz t:meta.view.license v:name="Public Domain"

property e:eyec-w6nz t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:eyec-w6nz t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | technician            | employer                          | phone      | 
| =========== | ===================== | ================================= | ========== | 
| 1439558624  | HARRIS, JACK          | 01 ACCURACY BACKFLOW              | 9726997156 | 
| 1439558624  | LINGLE, MIKE L        | 1ST CHOICE BACKFLOW TESTING       | 5129476714 | 
| 1439558624  | CICHON, CLAYTON       | 1ST FIRE PROTECTION SERVICES, LLC | 2103773473 | 
| 1439558624  | SALINAS, MARIO        | 1ST FIRE PROTECTION SERVICES, LLC | 2103773473 | 
| 1439558624  | VOIGT, DONALD D       | 1ST FIRE PROTECTION SERVICES, LLC | 2103773473 | 
| 1439558624  | MONACO, STEVEN J      | 1ST FIRE SAFETY                   |            | 
| 1439558624  | HARWELL, STEPHEN M    | 1ST PLUMBING SERVICES             |            | 
| 1439558624  | LANGE, CASEY E        | 1ST PLUMBING SERVICES             |            | 
| 1439558624  | BIERSDORFER, JUSTIN S | 1ST PLUMBING SERVICES             |            | 
| 1439558624  | DOYLE, HEATH J        | 1ST RESPONSE                      | 5128440594 | 
```