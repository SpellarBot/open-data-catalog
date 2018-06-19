# New York State Executive Budget Capital Appropriations: 2017-2018

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-2017-2018) |
| Metadata | [Link](https://data.ny.gov/api/views/4ukq-mtyf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4ukq-mtyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4ukq-mtyf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4ukq-mtyf |
| Name | New York State Executive Budget Capital Appropriations: 2017-2018 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2017-01-18T22:36:40Z |
| Publication Date | 2017-01-19T18:18:29Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the FY 2018 Executive Budget

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
| Yes      | numeric metric | reappropriations_recommended_2017_18 | Reappropriations Recommended 2017-18 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_1_13_2017          | Encumbrance as of 1/13/2017          | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2017_18   | Appropriations Recommended 2017-18   | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4ukq-mtyf d:2017-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/10 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_1_13_2017=0 m:appropriations_recommended_2017_18=0 m:reappropriations_recommended_2017_18=500000

series e:4ukq-mtyf d:2017-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_1_13_2017=0 m:appropriations_recommended_2017_18=0 m:reappropriations_recommended_2017_18=500000

series e:4ukq-mtyf d:2017-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1203 t:description="Maintenance & Improvement" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/12 t:financing_source="Miscellaneous Gifts Account" m:encumbrance_as_of_1_13_2017=0 m:appropriations_recommended_2017_18=0 m:reappropriations_recommended_2017_18=500000
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2017_18 p:long l:"Reappropriations Recommended 2017-18" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:encumbrance_as_of_1_13_2017 p:integer l:"Encumbrance as of 1/13/2017" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:appropriations_recommended_2017_18 p:integer l:"Appropriations Recommended 2017-18" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

entity e:4ukq-mtyf l:"New York State Executive Budget Capital Appropriations: 2017-2018" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/4ukq-mtyf

property e:4ukq-mtyf t:meta.view v:id=4ukq-mtyf v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations: 2017-2018" v:attribution="Division of the Budget"

property e:4ukq-mtyf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4ukq-mtyf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | reappropriations_recommended_2017_18 | encumbrance_as_of_1_13_2017 | appropriations_recommended_2017_18 | 
| ====================================== | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ==================================== | =========================== | ================================== | 
| Adirondack Park Agency                 | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                 | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                 | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                               | 0                           | 0                                  | 
| Agriculture and Markets, Department of | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 157000                               | 2                           | 0                                  | 
| Agriculture and Markets, Department of | 60010809         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 43000                                | 0                           | 0                                  | 
| Agriculture and Markets, Department of | 60ES17AS         | New York Works                                   | Program Improvement/Change | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0000/00/17           | Equipment Expenses                      | 0                                    | 0                           | 115000                             | 
| Agriculture and Markets, Department of | 60LF1603         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0054/01/16           | Local Fairs                             | 5000000                              | 0                           | 0                                  | 
| Agriculture and Markets, Department of | 60MN1703         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0000/00/17           | State Fair Maintenance                  | 0                                    | 0                           | 1000000                            | 
| Agriculture and Markets, Department of | 60NY1503         | New York Works                                   | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/15           | New York Works Infrastructure           | 58000                                | 57004                       | 0                                  | 
| Agriculture and Markets, Department of | 60NY1603         | New York Works                                   | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/16           | New York Works Infrastructure           | 1600000                              | 140644                      | 0                                  | 
```