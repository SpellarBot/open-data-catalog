# New York State Executive Budget Capital Appropriations: 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-2013-14) |
| Metadata | [Link](https://data.ny.gov/api/views/a3pi-nqef) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/a3pi-nqef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/a3pi-nqef/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | a3pi-nqef |
| Name | New York State Executive Budget Capital Appropriations: 2013-14 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2013-02-19T19:23:22Z |
| Publication Date | 2016-05-16T18:41:58Z |

## Description

This data set includes 2013-14 Executive Budget capital project appropriations and reappropriations for the budget year.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | agency_name                          | Agency Name                          | text      | text        |
| Yes      | series tag     | reference_number                     | Reference Number                     | text      | text        |
| Yes      | series tag     | program_name                         | Program Name                         | text      | text        |
| Yes      | series tag     | state_purpose                        | State Purpose                        | text      | text        |
| Yes      | series tag     | fund_name                            | Fund Name                            | text      | text        |
| Yes      | series tag     | financing_source                     | Financing Source                     | text      | text        |
| Yes      | series tag     | chapter_section_year                 | Chapter/Section/Year                 | text      | text        |
| Yes      | series tag     | description                          | Description                          | text      | text        |
| Yes      | numeric metric | reappropriations_recommended_2013_14 | Reappropriations Recommended 2013-14 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_01_18_2013         | Encumbrance As of 01/18/2013         | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2013_14   | Appropriations Recommended 2013-14   | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a3pi-nqef d:2013-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/04 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2013_14=500000 m:appropriations_recommended_2013_14=0 m:encumbrance_as_of_01_18_2013=0

series e:a3pi-nqef d:2013-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2013_14=500000 m:appropriations_recommended_2013_14=0 m:encumbrance_as_of_01_18_2013=0

series e:a3pi-nqef d:2013-01-01T00:00:00.000Z t:fund_name="Capital Projects Fund" t:reference_number=11021303 t:description="Minor Rehabilitation" t:program_name=Administration t:state_purpose="Preservation of Facilities" t:agency_name="Education Department, State" t:chapter_section_year=0000/00/13 t:financing_source="Capital Projects Fund" m:reappropriations_recommended_2013_14=0 m:appropriations_recommended_2013_14=3400000 m:encumbrance_as_of_01_18_2013=0
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2013_14 p:integer l:"Reappropriations Recommended 2013-14" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:encumbrance_as_of_01_18_2013 p:integer l:"Encumbrance As of 01/18/2013" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:appropriations_recommended_2013_14 p:integer l:"Appropriations Recommended 2013-14" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

entity e:a3pi-nqef l:"New York State Executive Budget Capital Appropriations: 2013-14" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/a3pi-nqef

property e:a3pi-nqef t:meta.view v:id=a3pi-nqef v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations: 2013-14" v:attribution="Division of the Budget"

property e:a3pi-nqef t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:a3pi-nqef t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:a3pi-nqef t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                               | reference_number | program_name                                     | state_purpose                            | fund_name                 | financing_source                           | chapter_section_year | description                           | reappropriations_recommended_2013_14 | encumbrance_as_of_01_18_2013 | appropriations_recommended_2013_14 | 
| ========================================= | ================ | ================================================ | ======================================== | ========================= | ========================================== | ==================== | ===================================== | ==================================== | ============================ | ================================== | 
| Adirondack Park Agency                    | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities               | Combined Expendable Trust | Miscellaneous Gifts Account                | 0055/01/04           | Miscellaneous Gifts Account           | 500000                               | 0                            | 0                                  | 
| Adirondack Park Agency                    | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities               | Combined Expendable Trust | Miscellaneous Gifts Account                | 0054/01/11           | Miscellaneous Gifts Account           | 500000                               | 0                            | 0                                  | 
| Education Department, State               | 11021303         | Administration                                   | Preservation of Facilities               | Capital Projects Fund     | Capital Projects Fund                      | 0000/00/13           | Minor Rehabilitation                  | 0                                    | 0                            | 3400000                            | 
| Mental Health, Office of                  | 50FO00NB         | Non-Bondable                                     | Program Improvement/Change               | Capital Projects Fund     | Capital Projects Fund                      | 0054/01/00           | Non-Bondable Fallout                  | 5045000                              | 0                            | 0                                  | 
| Environmental Conservation, Department of | 9539463          | Water Resources                                  | Health and Safety                        | Capital Projects Fund     | Capital Projects Fund                      | 0054/01/94           | Jones Inlet                           | 611000                               | 0                            | 0                                  | 
| Environmental Conservation, Department of | 095489F7         | Solid and Hazardous Waste Management - EQBA 86   | Health and Safety                        | Capital Projects Fund     | Capital Projects Fund - EQBA 86 (Bondable) | 0054/01/89           | Remedial Actions Statewide            | 2042000                              | 0                            | 0                                  | 
| Environmental Conservation, Department of | 9571056          | Solid and Hazardous Waste Management - EQBA 86   | Health and Safety                        | Capital Projects Fund     | Capital Projects Fund - EQBA 86 (Bondable) | 0055/01/10           | Landfill Closures-Loans               | 342000                               | 0                            | 0                                  | 
| Environmental Conservation, Department of | 095887F7         | Solid and Hazardous Waste Management - EQBA 86   | Health and Safety                        | Capital Projects Fund     | Capital Projects Fund - EQBA 86 (Bondable) | 0054/01/87           | 1986 Solid Waste Environmental Qualit | 2117000                              | 662116                       | 0                                  | 
| Environmental Conservation, Department of | 9650257          | Water Resources - PWBA                           | Environmental Protection or Improvements | Capital Projects Fund     | Capital Projects Fund - PWBA (Bondable)    | 0054/01/02           | PWBA Li CCmp                          | 900000                               | 899999                       | 0                                  | 
| Environmental Conservation, Department of | 9650357          | Water Resources - PWBA                           | Environmental Protection or Improvements | Capital Projects Fund     | Capital Projects Fund - PWBA (Bondable)    | 0055/01/03           | 65 PWBA Water Quality                 | 1124000                              | 580001                       | 0                                  | 
```