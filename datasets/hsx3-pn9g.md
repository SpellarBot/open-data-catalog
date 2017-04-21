# Washington State Agencies Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/washington-state-agencies-listing) |
| Metadata | [Link](https://data.wa.gov/api/views/hsx3-pn9g) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hsx3-pn9g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hsx3-pn9g/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hsx3-pn9g |
| Name | Washington State Agencies Listing |
| Tags | washington, state, agencies |
| Created | 2016-02-23T17:03:02Z |
| Publication Date | 2016-03-02T17:09:20Z |

## Description

Listing of all Washington State Agencies and their Abbreviations

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | agency_name  | Agency Name  | html      | html        |
| Yes      | series tag  | abbreviation | Abbreviation | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hsx3-pn9g d:2016-03-02T09:08:39.000Z t:abbreviation=WBOA t:agency_name="Accountancy, State Board of (WBOA)" m:row_number.hsx3-pn9g=1

series e:hsx3-pn9g d:2016-03-02T09:08:39.000Z t:abbreviation=OSA t:agency_name="Actuary, Office of the State (OSA)" m:row_number.hsx3-pn9g=2

series e:hsx3-pn9g d:2016-03-02T09:08:39.000Z t:abbreviation=OAH t:agency_name="Administrative Hearings, Office of (OAH)" m:row_number.hsx3-pn9g=3
```

## Meta Commands

```ls
metric m:row_number.hsx3-pn9g p:long l:"Row Number"

entity e:hsx3-pn9g l:"Washington State Agencies Listing" t:url=https://data.wa.gov/api/views/hsx3-pn9g

property e:hsx3-pn9g t:meta.view v:id=hsx3-pn9g v:averageRating=0 v:name="Washington State Agencies Listing"

property e:hsx3-pn9g t:meta.view.owner v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:displayName=max.pham

property e:hsx3-pn9g t:meta.view.tableauthor v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:roleName=editor v:displayName=max.pham
```

## Top Records

```ls
| :updated_at | agency_name                                                    | abbreviation | 
| =========== | ============================================================== | ============ | 
| 1456909719  | Accountancy, State Board of (WBOA)                             | WBOA         | 
| 1456909719  | Actuary, Office of the State (OSA)                             | OSA          | 
| 1456909719  | Administrative Hearings, Office of (OAH)                       | OAH          | 
| 1456909719  | African-American Affairs, Washington State Commission on (CAA) | CAA          | 
| 1456909719  | Aging & Long Term Care of Eastern Washington (ALTCEW)          | ALTCEW       | 
| 1456909719  | Agriculture, Department of (AGR)                               | AGR          | 
| 1456909719  | Air National Guard (WAANG)                                     | WAANG        | 
| 1456909719  | Apple Commission (APPLE)                                       | APPLE        | 
| 1456909719  | Archaeology & Historic Preservation, Department of (DAHP)      | DAHP         | 
| 1456909719  | Architects, Board of Registration for (BRA)                    | BRA          | 
```