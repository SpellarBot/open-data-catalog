# Cable Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cable-inspections-a3e12) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/tzyi-s757) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/tzyi-s757/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/tzyi-s757/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | tzyi-s757 |
| Name | Cable Inspections |
| Attribution | Montgomery County, MD Government |
| Category | Government |
| Tags | cable, inspections |
| Created | 2012-08-08T20:31:14Z |
| Publication Date | 2015-10-10T13:06:57Z |

## Description

Information on Cable Inspections performed by the Montgomery County Cable Office since September 1, 2010. This dataset will be updated on a quarterly basis.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date_inspected      | Date Inspected      | calendar_date | calendar_date |
| No       |                | date_completed      | Date Completed      | calendar_date | calendar_date |
| Yes      | series tag     | cable_company       | Cable Company       | text          | text          |
| Yes      | series tag     | type_area_inspected | Type Area Inspected | text          | text          |
| Yes      | series tag     | street_name         | Street Name         | text          | text          |
| Yes      | series tag     | street_type         | Street Type         | text          | text          |
| Yes      | series tag     | city                | City                | text          | text          |
| Yes      | series tag     | intersection        | Intersection        | text          | text          |
| Yes      | numeric metric | violation           | Violation           | number        | number        |
| Yes      | numeric metric | alert               | Alert               | number        | number        |
| Yes      | numeric metric | resident_generated  | Resident Generated  | number        | number        |
| Yes      | numeric metric | in_field_violations | In-Field Violations | number        | number        |
| Yes      | numeric metric | site_survey         | Site Survey         | number        | number        |
| Yes      | numeric metric | re_inspection       | Re-Inspection       | number        | number        |
| No       |                | re_inspection_date  | Re-Inspection Date  | calendar_date | calendar_date |
| Yes      | series tag     | violation_type      | Violation Type      | text          | text          |
```

## Time Field

```ls
Value = date_inspected
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_completed,re_inspection_date
```

## Data Commands

```ls
series e:tzyi-s757 d:2010-10-01T00:00:00.000Z t:violation_type=Equipment t:type_area_inspected=UG t:street_name="Mustard Seed" t:cable_company=Comcast t:street_type=Ct t:city=Germantown m:in_field_violations=1 m:alert=0 m:violation=1 m:re_inspection=0 m:site_survey=0 m:resident_generated=0

series e:tzyi-s757 d:2010-10-01T00:00:00.000Z t:violation_type=Drop t:type_area_inspected=UG t:street_name="Mustard Seed" t:cable_company=Comcast t:street_type=Ct t:city=Germantown m:in_field_violations=1 m:alert=0 m:violation=1 m:re_inspection=1 m:site_survey=0 m:resident_generated=0

series e:tzyi-s757 d:2010-10-01T00:00:00.000Z t:violation_type=Equipment t:type_area_inspected=UG t:street_name="Mustard Seed" t:cable_company=Verizon t:street_type=Ct t:city=Germantown m:in_field_violations=1 m:alert=0 m:violation=1 m:re_inspection=1 m:site_survey=0 m:resident_generated=0
```

## Meta Commands

```ls
metric m:violation p:integer l:Violation d:"""1"" if a violation is discovered while completing a site survey" t:dataTypeName=number

metric m:alert p:integer l:Alert d:"""1"" if a safety issue is discovered on a site survey or in-field violation which needs correction in 24 hours" t:dataTypeName=number

metric m:resident_generated p:integer l:"Resident Generated" d:"""1"" if complaint is received from a resident which is determined to be a violation" t:dataTypeName=number

metric m:in_field_violations p:integer l:"In-Field Violations" d:"""1"" if violation was discovered while driving around and found without prior notice of its existence" t:dataTypeName=number

metric m:site_survey p:integer l:"Site Survey" d:"""1"" if the address was received by the service provider as a location where they would be working and a visit is conducted to check safety and regulatory compliance" t:dataTypeName=number

metric m:re_inspection p:integer l:Re-Inspection d:"""1"" if the site was revisited for re-inspection after receiving notice from the provider that the violation was corrected" t:dataTypeName=number

entity e:tzyi-s757 l:"Cable Inspections" t:attribution="Montgomery County, MD Government" t:url=https://data.montgomerycountymd.gov/api/views/tzyi-s757

property e:tzyi-s757 t:meta.view v:id=tzyi-s757 v:category=Government v:averageRating=0 v:name="Cable Inspections" v:attribution="Montgomery County, MD Government"

property e:tzyi-s757 t:meta.view.license v:name="Public Domain"

property e:tzyi-s757 t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:tzyi-s757 t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| date_inspected      | date_completed      | cable_company | type_area_inspected | street_name  | street_type | city       | intersection   | violation | alert | resident_generated | in_field_violations | site_survey | re_inspection | re_inspection_date  | violation_type | 
| =================== | =================== | ============= | =================== | ============ | =========== | ========== | ============== | ========= | ===== | ================== | =================== | =========== | ============= | =================== | ============== | 
| 2010-10-01T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 0             |                     | Equipment      | 
| 2010-10-01T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2012-01-18T00:00:00 | Drop           | 
| 2010-10-01T00:00:00 | 2010-11-01T00:00:00 | Verizon       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2010-12-07T00:00:00 | Equipment      | 
| 2010-10-01T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2012-01-18T00:00:00 | Drop           | 
| 2010-10-01T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2012-01-18T00:00:00 | Drop           | 
| 2010-10-01T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Mustard Seed | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2012-01-18T00:00:00 | Drop           | 
| 2010-10-05T00:00:00 | 2010-10-07T00:00:00 | Comcast       | UG                  | Birdseye     | Ter         | Germantown |                | 0         | 1     | 1                  | 0                   | 0           | 1             | 2011-12-28T00:00:00 | Drop           | 
| 2010-10-04T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Cross Ridge  | Ct          | Germantown |                | 1         | 0     | 1                  | 0                   | 0           | 1             | 2011-06-17T00:00:00 | Restoration    | 
| 2010-10-04T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Cross Ridge  | Ct          | Germantown |                | 1         | 0     | 0                  | 1                   | 0           | 1             | 2011-06-17T00:00:00 | Drop           | 
| 2010-10-04T00:00:00 | 2010-10-25T00:00:00 | Comcast       | UG                  | Cross Ridge  | Ct          | Germantown | Middlebrook Rd | 1         | 0     | 0                  | 1                   | 0           | 0             |                     | Equipment      | 
```