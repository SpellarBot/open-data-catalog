# New York State Executive Budget Capital Appropriations: 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-2015-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/d7vq-82jt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/d7vq-82jt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/d7vq-82jt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | d7vq-82jt |
| Name | New York State Executive Budget Capital Appropriations: 2015-2016 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2015-01-21T19:10:54Z |
| Publication Date | 2015-01-21T21:18:57Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the 2015-16 Executive Budget

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
| Yes      | numeric metric | reappropriations_recommended_2015_16 | Reappropriations Recommended 2015-16 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_01_15_2015         | Encumbrance as of 01/15/2015         | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2015_16   | Appropriations Recommended 2015-16   | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d7vq-82jt d:2015-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/10 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_01_15_2015=0 m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=500000

series e:d7vq-82jt d:2015-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_01_15_2015=0 m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=500000

series e:d7vq-82jt d:2015-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1203 t:description="Maintenance & Improvement" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/12 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_01_15_2015=0 m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=500000
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2015_16 p:integer l:"Reappropriations Recommended 2015-16" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:encumbrance_as_of_01_15_2015 p:integer l:"Encumbrance as of 01/15/2015" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:appropriations_recommended_2015_16 p:integer l:"Appropriations Recommended 2015-16" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

entity e:d7vq-82jt l:"New York State Executive Budget Capital Appropriations: 2015-2016" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/d7vq-82jt

property e:d7vq-82jt t:meta.view v:id=d7vq-82jt v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations: 2015-2016" v:attribution="Division of the Budget"

property e:d7vq-82jt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:d7vq-82jt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:d7vq-82jt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                            | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | reappropriations_recommended_2015_16 | encumbrance_as_of_01_15_2015 | appropriations_recommended_2015_16 | 
| ====================================== | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ==================================== | ============================ | ================================== | 
| Adirondack Park Agency                 | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                               | 0                            | 0                                  | 
| Adirondack Park Agency                 | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                               | 0                            | 0                                  | 
| Adirondack Park Agency                 | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                               | 0                            | 0                                  | 
| Agriculture and Markets, Department of | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 500000                               | 30743                        | 0                                  | 
| Agriculture and Markets, Department of | 60010809         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 3130000                              | 721009                       | 0                                  | 
| Agriculture and Markets, Department of | 60MN1103         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/11           | State Fair Capital                      | 146000                               | 1415                         | 0                                  | 
| Agriculture and Markets, Department of | 60MN1203         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/12           | State Fair Maintenance                  | 9000                                 | 1309                         | 0                                  | 
| Agriculture and Markets, Department of | 60MN1303         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/13           | State Fair Maintenance                  | 27000                                | 0                            | 0                                  | 
| Agriculture and Markets, Department of | 60MN1403         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/14           | State Fair Maintenance                  | 376000                               | 104698                       | 0                                  | 
| Agriculture and Markets, Department of | 60MN1503         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0000/00/15           | State Fair Maintenance                  | 0                                    | 0                            | 1000000                            | 
```