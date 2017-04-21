# New York State Executive Budget Capital Appropriations: 2014-15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-2014-15) |
| Metadata | [Link](https://data.ny.gov/api/views/p3bu-bme6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p3bu-bme6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p3bu-bme6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p3bu-bme6 |
| Name | New York State Executive Budget Capital Appropriations: 2014-15 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2014-01-21T20:40:44Z |
| Publication Date | 2014-01-21T20:52:35Z |

## Description

This data set includes 2014-15 Executive Budget capital project appropriations and reappropriations for the budget year.

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
| Yes      | numeric metric | reappropriations_recommended_2014_15 | Reappropriations Recommended 2014-15 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_01_16_2014         | Encumbrance As of 01/16/2014         | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2014_15   | Appropriations Recommended 2014-15   | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p3bu-bme6 d:2014-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/10 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2014_15=500000 m:appropriations_recommended_2014_15=0 m:encumbrance_as_of_01_16_2014=0

series e:p3bu-bme6 d:2014-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2014_15=500000 m:appropriations_recommended_2014_15=0 m:encumbrance_as_of_01_16_2014=0

series e:p3bu-bme6 d:2014-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1203 t:description="Maintenance & Improvement" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/12 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2014_15=500000 m:appropriations_recommended_2014_15=0 m:encumbrance_as_of_01_16_2014=0
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2014_15 p:integer l:"Reappropriations Recommended 2014-15" t:dataTypeName=money

metric m:encumbrance_as_of_01_16_2014 p:integer l:"Encumbrance As of 01/16/2014" t:dataTypeName=money

metric m:appropriations_recommended_2014_15 p:integer l:"Appropriations Recommended 2014-15" t:dataTypeName=money

entity e:p3bu-bme6 l:"New York State Executive Budget Capital Appropriations: 2014-15" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/p3bu-bme6

property e:p3bu-bme6 t:meta.view v:id=p3bu-bme6 v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations: 2014-15" v:attribution="Division of the Budget"

property e:p3bu-bme6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:p3bu-bme6 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:p3bu-bme6 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                            | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | reappropriations_recommended_2014_15 | encumbrance_as_of_01_16_2014 | appropriations_recommended_2014_15 | 
| ====================================== | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ==================================== | ============================ | ================================== | 
| Adirondack Park Agency                 | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                               | 0                            | 0                                  | 
| Adirondack Park Agency                 | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                               | 0                            | 0                                  | 
| Adirondack Park Agency                 | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                               | 0                            | 0                                  | 
| Agriculture and Markets, Department of | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 1789000                              | 1712524                      | 0                                  | 
| Agriculture and Markets, Department of | 60010809         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 7163000                              | 7118897                      | 0                                  | 
| Agriculture and Markets, Department of | 60MN1003         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0055/01/10           | State Fair Capital                      | 301000                               | 0                            | 0                                  | 
| Agriculture and Markets, Department of | 60MN1103         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/11           | State Fair Capital                      | 146000                               | 1415                         | 0                                  | 
| Agriculture and Markets, Department of | 60MN1203         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/12           | State Fair Maintenance                  | 172000                               | 5341                         | 0                                  | 
| Agriculture and Markets, Department of | 60MN1303         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/13           | State Fair Maintenance                  | 570000                               | 98804                        | 0                                  | 
| Agriculture and Markets, Department of | 60MN1403         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0000/00/14           | State Fair Maintenance                  | 0                                    | 0                            | 1000000                            | 
```