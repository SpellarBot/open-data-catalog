# Chicago Street Names

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-street-names-7875c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/i6bp-fvbx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/i6bp-fvbx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/i6bp-fvbx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | i6bp-fvbx |
| Name | Chicago Street Names |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | streets, gis |
| Created | 2010-12-22T01:42:52Z |
| Publication Date | 2012-05-30T22:29:43Z |

## Description

List of all Chicago streets with suffixes and minimum and maximum address numbers.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | full_street_name | Full Street Name | text      | text        |
| Yes      | series tag  | direction        | Direction        | text      | text        |
| Yes      | series tag  | street           | Street           | text      | text        |
| Yes      | series tag  | suffix           | Suffix           | text      | text        |
| Yes      | series tag  | suffix_direction | Suffix Direction | text      | text        |
| No       |             | min_address      | Min Address      | number    | number      |
| No       |             | max_address      | Max Address      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = min_address,max_address
```

## Data Commands

```ls
series e:i6bp-fvbx d:2012-05-30T15:29:10.000Z t:direction=E t:street=100TH t:full_street_name="E 100TH PL" t:suffix=PL m:row_number.i6bp-fvbx=1

series e:i6bp-fvbx d:2012-05-30T15:29:10.000Z t:direction=W t:street=100TH t:full_street_name="W 100TH PL" t:suffix=PL m:row_number.i6bp-fvbx=2

series e:i6bp-fvbx d:2012-05-30T15:29:10.000Z t:direction=E t:street=100TH t:full_street_name="E 100TH ST" t:suffix=ST m:row_number.i6bp-fvbx=3
```

## Meta Commands

```ls
metric m:row_number.i6bp-fvbx p:long l:"Row Number"

entity e:i6bp-fvbx l:"Chicago Street Names" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/i6bp-fvbx

property e:i6bp-fvbx t:meta.view v:id=i6bp-fvbx v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Chicago Street Names" v:attribution="City of Chicago"

property e:i6bp-fvbx t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:i6bp-fvbx t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | full_street_name | direction | street | suffix | suffix_direction | min_address | max_address | 
| =========== | ================ | ========= | ====== | ====== | ================ | =========== | =========== | 
| 1338391750  | E 100TH PL       | E         | 100TH  | PL     |                  | 1           | 1199        | 
| 1338391750  | W 100TH PL       | W         | 100TH  | PL     |                  | 300         | 2629        | 
| 1338391750  | E 100TH ST       | E         | 100TH  | ST     |                  | 1           | 4001        | 
| 1338391750  | W 100TH ST       | W         | 100TH  | ST     |                  | 1           | 2799        | 
| 1338391750  | E 101ST PL       | E         | 101ST  | PL     |                  | 1           | 699         | 
| 1338391750  | W 101ST PL       | W         | 101ST  | PL     |                  | 300         | 3999        | 
| 1338391750  | E 101ST ST       | E         | 101ST  | ST     |                  | 1           | 3699        | 
| 1338391750  | W 101ST ST       | W         | 101ST  | ST     |                  | 1           | 3999        | 
| 1338391750  | E 102ND PL       | E         | 102ND  | PL     |                  | 1           | 699         | 
| 1338391750  | W 102ND PL       | W         | 102ND  | PL     |                  | 300         | 3947        | 
```