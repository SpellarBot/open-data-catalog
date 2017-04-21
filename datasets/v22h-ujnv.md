# Supervisor District to ZIP Code Crosswalk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/supervisor-district-and-zip-codes-83b57) |
| Metadata | [Link](https://data.sfgov.org/api/views/v22h-ujnv) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/v22h-ujnv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/v22h-ujnv/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | v22h-ujnv |
| Name | Supervisor District to ZIP Code Crosswalk |
| Attribution | City and County of San Francisco |
| Category | Geographic Locations and Boundaries |
| Tags | supervisor, district, zip code |
| Created | 2013-05-07T18:03:20Z |
| Publication Date | 2013-05-07T18:06:13Z |

## Description

Lists intersecting Supervisor Districts and ZIP Codes for City and County of San Francisco.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | supervisor_district | Supervisor_District | text      | number      |
| Yes      | series tag  | zip_code            | ZIP_Code            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:v22h-ujnv d:2013-05-07T11:03:21.000Z t:zip_code=94102 t:supervisor_district=8 m:row_number.v22h-ujnv=1

series e:v22h-ujnv d:2013-05-07T11:03:21.000Z t:zip_code=94102 t:supervisor_district=6 m:row_number.v22h-ujnv=2

series e:v22h-ujnv d:2013-05-07T11:03:21.000Z t:zip_code=94102 t:supervisor_district=3 m:row_number.v22h-ujnv=3
```

## Meta Commands

```ls
metric m:row_number.v22h-ujnv p:long l:"Row Number"

entity e:v22h-ujnv l:"Supervisor District to ZIP Code Crosswalk" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/v22h-ujnv

property e:v22h-ujnv t:meta.view v:id=v22h-ujnv v:category="Geographic Locations and Boundaries" v:attributionLink=http://sfgov.org v:averageRating=0 v:name="Supervisor District to ZIP Code Crosswalk" v:attribution="City and County of San Francisco"

property e:v22h-ujnv t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:v22h-ujnv t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:v22h-ujnv t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | supervisor_district | zip_code | 
| =========== | =================== | ======== | 
| 1367924601  | 8                   | 94102    | 
| 1367924601  | 6                   | 94102    | 
| 1367924601  | 3                   | 94102    | 
| 1367924601  | 5                   | 94102    | 
| 1367924601  | 8                   | 94103    | 
| 1367924601  | 9                   | 94103    | 
| 1367924601  | 10                  | 94103    | 
| 1367924601  | 6                   | 94103    | 
| 1367924601  | 3                   | 94103    | 
| 1367924601  | 5                   | 94103    | 
```