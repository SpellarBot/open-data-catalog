# New York State Enacted Budget Capital Appropriations: 2013-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-enacted-budget-capital-appropriations-2013-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/tc88-gm5r) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tc88-gm5r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tc88-gm5r/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tc88-gm5r |
| Name | New York State Enacted Budget Capital Appropriations: 2013-2014 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances, budget, enacted budget, integrity |
| Created | 2013-05-03T19:30:38Z |
| Publication Date | 2016-05-13T20:46:46Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the 2013-14 Enacted Budget

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | agency_name                      | Agency Name                      | text      | text        |
| Yes      | series tag     | reference_number                 | Reference Number                 | text      | text        |
| Yes      | series tag     | program_name                     | Program Name                     | text      | text        |
| Yes      | series tag     | state_purpose                    | State Purpose                    | text      | text        |
| Yes      | series tag     | fund_name                        | Fund Name                        | text      | text        |
| Yes      | series tag     | financing_source                 | Financing Source                 | text      | text        |
| Yes      | series tag     | chapter_section_year             | Chapter/Section/Year             | text      | text        |
| Yes      | series tag     | description                      | Description                      | text      | text        |
| Yes      | numeric metric | enacted_reappropriations_2013_14 | Enacted Reappropriations 2013-14 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_07_16_2013     | Encumbrance As of 07/16/2013     | money     | money       |
| Yes      | numeric metric | enacted_appropriations_2013_14   | Enacted Appropriations 2013-14   | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tc88-gm5r d:2013-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/04 t:financing_source="Miscellaneous Gifts Account" m:enacted_reappropriations_2013_14=500000 m:encumbrance_as_of_07_16_2013=0 m:enacted_appropriations_2013_14=0

series e:tc88-gm5r d:2013-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:enacted_reappropriations_2013_14=500000 m:encumbrance_as_of_07_16_2013=0 m:enacted_appropriations_2013_14=0

series e:tc88-gm5r d:2013-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1203 t:description="Maintenance & Improvement" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/12 t:financing_source="Miscellaneous Gifts Account" m:enacted_reappropriations_2013_14=500000 m:encumbrance_as_of_07_16_2013=0 m:enacted_appropriations_2013_14=0
```

## Meta Commands

```ls
metric m:enacted_reappropriations_2013_14 p:integer l:"Enacted Reappropriations 2013-14" d:"Enacted Reappropriations" t:dataTypeName=money

metric m:encumbrance_as_of_07_16_2013 p:integer l:"Encumbrance As of 07/16/2013" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:enacted_appropriations_2013_14 p:integer l:"Enacted Appropriations 2013-14" d:"Enacted Appropriations" t:dataTypeName=money

entity e:tc88-gm5r l:"New York State Enacted Budget Capital Appropriations: 2013-2014" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/tc88-gm5r

property e:tc88-gm5r t:meta.view v:id=tc88-gm5r v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Enacted Budget Capital Appropriations: 2013-2014" v:attribution="Division of the Budget"

property e:tc88-gm5r t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tc88-gm5r t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tc88-gm5r t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                            | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | enacted_reappropriations_2013_14 | encumbrance_as_of_07_16_2013 | enacted_appropriations_2013_14 | 
| ====================================== | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ================================ | ============================ | ============================== | 
| Adirondack Park Agency                 | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/04           | Miscellaneous Gifts Account             | 500000                           | 0                            | 0                              | 
| Adirondack Park Agency                 | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                           | 0                            | 0                              | 
| Adirondack Park Agency                 | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                           | 0                            | 0                              | 
| Agriculture and Markets, Department of | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 6210000                          | 1987287                      | 0                              | 
| Agriculture and Markets, Department of | 60010809         | New Facilities                                   | Economic Development       | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 8000000                          | 7667783                      | 0                              | 
| Agriculture and Markets, Department of | 60020607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0053/05/06           | Cornell Equine Drug Testing Lab         | 1894000                          | 0                            | 0                              | 
| Agriculture and Markets, Department of | 60030607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0053/05/06           | Fredonia Vineyard Lab                   | 28000                            | 0                            | 0                              | 
| Agriculture and Markets, Department of | 60MN0903         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0055/01/09           | Maintenance                             | 1378000                          | 0                            | 0                              | 
| Agriculture and Markets, Department of | 60MN1003         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0055/01/10           | State Fair Capital                      | 301000                           | 0                            | 0                              | 
| Agriculture and Markets, Department of | 60MN1103         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/11           | State Fair Capital                      | 157000                           | 1415                         | 0                              | 
```