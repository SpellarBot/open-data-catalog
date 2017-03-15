# Building Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-violations-f0f5e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/22u3-xenr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/22u3-xenr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/22u3-xenr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 22u3-xenr |
| Name | Building Violations |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | violations, inspections |
| Created | 2012-06-26T17:28:59Z |
| Publication Date | 2015-09-29T21:21:53Z |
| Rows Updated | 2017-03-15T06:46:15Z |

## Description

Violations issued by the Department of Buildings from 2006 to the present.  Lenders and title companies, please note: These data are historical in nature and should not be relied upon for real estate transactions. For transactional purposes such as closings, please consult the title commitment for outstanding enforcement actions in the Circuit Court of Cook County or the Chicago Department of Administrative Hearings. Violations are always associated to an inspection and there can be multiple violation records to one inspection record. Related Applications: Building Data Warehouse http://www.cityofchicago.org/city/en/depts/bldgs/provdrs/inspect/svcs/building_violationsonline.html. The information presented on this website is informational only and does not necessarily reflect the current condition of the building or property. The dataset contains cases where a respondent has been found to be liable as well as cases where the respondent has been found to be not liable.

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | =========== | ============================ | ============================ | ============= | ============= |
| No       |             | id                           | ID                           | text          | text          |
| Yes      | time        | violation_last_modified_date | VIOLATION LAST MODIFIED DATE | calendar_date | calendar_date |
| No       |             | violation_date               | VIOLATION DATE               | calendar_date | calendar_date |
| Yes      | series tag  | violation_code               | VIOLATION CODE               | text          | text          |
| Yes      | series tag  | violation_status             | VIOLATION STATUS             | text          | text          |
| No       |             | violation_status_date        | VIOLATION STATUS DATE        | calendar_date | calendar_date |
| Yes      | series tag  | violation_description        | VIOLATION DESCRIPTION        | text          | text          |
| Yes      | series tag  | violation_location           | VIOLATION LOCATION           | text          | text          |
| Yes      | series tag  | violation_inspector_comments | VIOLATION INSPECTOR COMMENTS | text          | text          |
| Yes      | series tag  | violation_ordinance          | VIOLATION ORDINANCE          | text          | text          |
| Yes      | series tag  | inspector_id                 | INSPECTOR ID                 | text          | text          |
| Yes      | series tag  | inspection_number            | INSPECTION NUMBER            | text          | number        |
| Yes      | series tag  | inspection_status            | INSPECTION STATUS            | text          | text          |
| Yes      | series tag  | inspection_waived            | INSPECTION WAIVED            | text          | text          |
| Yes      | series tag  | inspection_category          | INSPECTION CATEGORY          | text          | text          |
| Yes      | series tag  | department_bureau            | DEPARTMENT BUREAU            | text          | text          |
| No       |             | address                      | ADDRESS                      | text          | text          |
| Yes      | series tag  | property_group               | PROPERTY GROUP               | text          | number        |
| Yes      | series tag  | ssa                          | SSA                          | text          | text          |
| No       |             | latitude                     | LATITUDE                     | number        | number        |
| No       |             | longitude                    | LONGITUDE                    | number        | number        |
```

## Time Field

```ls
Value = violation_last_modified_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,violation_date,violation_status_date,address,latitude,longitude
```

## Data Commands

```ls
series e:22u3-xenr d:2016-02-02T08:17:42.000Z t:violation_inspector_comments="REAR PORCH WARPED AND TWISTED BEAM 2ND FLR. 5448 LOOSE TREADS, 1ST TO 2ND FLR. REAR 415 LOOSE STRINGER 1ST TO 2ND FLR. ALSO SPLIT TREADS OBTAIN PERMIT AND PLANS." t:inspection_number=1950920 t:inspection_category=COMPLAINT t:property_group=24447 t:violation_code=CN070024 t:violation_location="REWRITTEN ON 08/27/2014-INSPECTION #11320166-BL01041" t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="REPAIR PORCH SYSTEM" t:inspector_id=BL00254 t:violation_ordinance="Failed to repair or replace defective or missing members of porch system.  (13-196-570, 13-196-641)" m:row_number.22u3-xenr=1

series e:22u3-xenr d:2016-02-02T08:12:02.000Z t:violation_inspector_comments="SOUTH ELEVATION-ABOVE ENTRANCE DOOR VERTICAL CRACKS IN STONE. VERTICAL CRACKS IN BRICKS WEST/SOUTH AT 3RD FL. NORTH ELEVATION- 3RD FL. BRICK MISSING, MORTAR MISSING." t:inspection_number=2280163 t:inspection_category=COMPLAINT t:property_group=24447 t:violation_code=CN061014 t:violation_location=1041 t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="REPAIR EXTERIOR WALL" t:inspector_id=BL00804 t:violation_ordinance="Failed to maintain the exterior walls of a building or structure free from holes, breaks, loose or rotting boards or timbers and any other conditions which might admit rain or dampness to the walls.  (13-196-530(b), 13-196-641)" m:row_number.22u3-xenr=2

series e:22u3-xenr d:2016-02-02T08:12:23.000Z t:violation_inspector_comments="SOUTH ELEVATION- 5450/AT ROOF STONE/BROKE/ MORTAR MISSING." t:inspection_number=2280163 t:inspection_category=COMPLAINT t:property_group=24447 t:violation_code=CN065024 t:violation_location=1041 t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="MAINTAIN PROJECTIONS" t:inspector_id=BL00804 t:violation_ordinance="Failed to maintain projection from wall of building in good repair and free from cracks and defects.  (13-196-530(e), 13-196-641)" m:row_number.22u3-xenr=3
```

## Meta Commands

```ls
metric m:row_number.22u3-xenr p:long l:"Row Number"

entity e:22u3-xenr l:"Building Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/22u3-xenr

property e:22u3-xenr t:meta.view v:id=22u3-xenr v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Building Violations" v:attribution="City of Chicago"

property e:22u3-xenr t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false

property e:22u3-xenr t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```