# Building Violations

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/22u3-xenr/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/building-violations-f0f5e)
* [Metadata URL](https://data.cityofchicago.org/api/views/22u3-xenr)
* Id = 22u3-xenr
* Name = Building Violations
* Attribution = City of Chicago
* [Attribution Link](http://www.cityofchicago.org)
* Category = Buildings
* Tags = [violations, inspections]
* Created = 2012-06-26T17:28:59Z
* Publication Date = 2015-09-29T21:21:53Z
* Rows Updated = 2017-03-06T07:40:53Z

## Description

Violations issued by the Department of Buildings from 2006 to the present.  Lenders and title companies, please note: These data are historical in nature and should not be relied upon for real estate transactions. For transactional purposes such as closings, please consult the title commitment for outstanding enforcement actions in the Circuit Court of Cook County or the Chicago Department of Administrative Hearings. Violations are always associated to an inspection and there can be multiple violation records to one inspection record. Related Applications: Building Data Warehouse http://www.cityofchicago.org/city/en/depts/bldgs/provdrs/inspect/svcs/building_violationsonline.html. The information presented on this website is informational only and does not necessarily reflect the current condition of the building or property. The dataset contains cases where a respondent has been found to be liable as well as cases where the respondent has been found to be not liable.

## Columns

```ls
| Name                         | Field Name                   | Data Type     | Render Type   | Schema Type    | Included | 
| ============================ | ============================ | ============= | ============= | ============== | ======== | 
| ID                           | id                           | text          | text          |                | No       | 
| VIOLATION LAST MODIFIED DATE | violation_last_modified_date | calendar_date | calendar_date | time           | Yes      | 
| VIOLATION DATE               | violation_date               | calendar_date | calendar_date |                | No       | 
| VIOLATION CODE               | violation_code               | text          | text          | series tag     | Yes      | 
| VIOLATION STATUS             | violation_status             | text          | text          | series tag     | Yes      | 
| VIOLATION STATUS DATE        | violation_status_date        | calendar_date | calendar_date |                | No       | 
| VIOLATION DESCRIPTION        | violation_description        | text          | text          | series tag     | Yes      | 
| VIOLATION LOCATION           | violation_location           | text          | text          | series tag     | Yes      | 
| VIOLATION INSPECTOR COMMENTS | violation_inspector_comments | text          | text          | series tag     | Yes      | 
| VIOLATION ORDINANCE          | violation_ordinance          | text          | text          | series tag     | Yes      | 
| INSPECTOR ID                 | inspector_id                 | text          | text          | series tag     | Yes      | 
| INSPECTION NUMBER            | inspection_number            | number        | number        | numeric metric | Yes      | 
| INSPECTION STATUS            | inspection_status            | text          | text          | series tag     | Yes      | 
| INSPECTION WAIVED            | inspection_waived            | number        | text          | numeric metric | Yes      | 
| INSPECTION CATEGORY          | inspection_category          | text          | text          | series tag     | Yes      | 
| DEPARTMENT BUREAU            | department_bureau            | text          | text          | series tag     | Yes      | 
| ADDRESS                      | address                      | text          | text          |                | No       | 
| PROPERTY GROUP               | property_group               | number        | number        | numeric metric | Yes      | 
| SSA                          | ssa                          | number        | text          | numeric metric | Yes      | 
| LATITUDE                     | latitude                     | number        | number        |                | No       | 
| LONGITUDE                    | longitude                    | number        | number        |                | No       | 
```

## Time Field

```ls
Value = violation_last_modified_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = id,address,violation_date,violation_status_date,longitude,latitude
Annotation Fields = 
```

## Data Commands

```ls
series e:22u3-xenr d:2016-02-02T08:17:42.000Z t:violation_inspector_comments="REAR PORCH WARPED AND TWISTED BEAM 2ND FLR. 5448 LOOSE TREADS, 1ST TO 2ND FLR. REAR 415 LOOSE STRINGER 1ST TO 2ND FLR. ALSO SPLIT TREADS OBTAIN PERMIT AND PLANS." t:inspection_category=COMPLAINT t:violation_code=CN070024 t:violation_location="REWRITTEN ON 08/27/2014-INSPECTION #11320166-BL01041" t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="REPAIR PORCH SYSTEM" t:inspector_id=BL00254 t:violation_ordinance="Failed to repair or replace defective or missing members of porch system.  (13-196-570, 13-196-641)" m:inspection_number=1950920 m:property_group=24447

series e:22u3-xenr d:2016-02-02T08:12:02.000Z t:violation_inspector_comments="SOUTH ELEVATION-ABOVE ENTRANCE DOOR VERTICAL CRACKS IN STONE. VERTICAL CRACKS IN BRICKS WEST/SOUTH AT 3RD FL. NORTH ELEVATION- 3RD FL. BRICK MISSING, MORTAR MISSING." t:inspection_category=COMPLAINT t:violation_code=CN061014 t:violation_location=1041 t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="REPAIR EXTERIOR WALL" t:inspector_id=BL00804 t:violation_ordinance="Failed to maintain the exterior walls of a building or structure free from holes, breaks, loose or rotting boards or timbers and any other conditions which might admit rain or dampness to the walls.  (13-196-530(b), 13-196-641)" m:inspection_number=2280163 m:property_group=24447

series e:22u3-xenr d:2016-02-02T08:12:23.000Z t:violation_inspector_comments="SOUTH ELEVATION- 5450/AT ROOF STONE/BROKE/ MORTAR MISSING." t:inspection_category=COMPLAINT t:violation_code=CN065024 t:violation_location=1041 t:inspection_waived=N t:violation_status=COMPLIED t:department_bureau=CONSERVATION t:inspection_status=FAILED t:violation_description="MAINTAIN PROJECTIONS" t:inspector_id=BL00804 t:violation_ordinance="Failed to maintain projection from wall of building in good repair and free from cracks and defects.  (13-196-530(e), 13-196-641)" m:inspection_number=2280163 m:property_group=24447
```

## Meta Commands

```ls
metric m:inspection_number p:integer l:"INSPECTION NUMBER" t:dataTypeName=number

metric m:property_group p:integer l:"PROPERTY GROUP" d:"Properties (lots) in the City of Chicago can typically have multiple point addresses, range addresses and buildings. Examples are corner lots, large lots, lots with front and rear buildings, etc.. As a result, inspections (and their associated violations), permits and complaints related to a single property could have different addresses. This problem can be reconciled by using Property Group. All point and range addresses for a property are assigned the same Property Group key." t:dataTypeName=number

metric m:ssa p:integer l:SSA d:"Special Service Areas are local tax districts that fund expanded services and programs, to foster commercial and economic development, through a localized property tax. In other cities these areas are sometimes called Business Improvement Districts (BIDs). This portal contains a map of all Chicago SSAs" t:dataTypeName=number

entity e:22u3-xenr l:"Building Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/22u3-xenr

property e:22u3-xenr t:meta.view d:2017-03-08T01:11:33.961Z v:id=22u3-xenr v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Building Violations" v:attribution="City of Chicago"

property e:22u3-xenr t:meta.view.owner d:2017-03-08T01:11:33.961Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false

property e:22u3-xenr t:meta.view.tableauthor d:2017-03-08T01:11:33.961Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```