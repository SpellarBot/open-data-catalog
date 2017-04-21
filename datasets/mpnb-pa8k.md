# New York State Enacted Budget Capital Appropriations: 2016-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-enacted-budget-capital-appropriations-2016-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/mpnb-pa8k) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mpnb-pa8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mpnb-pa8k/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mpnb-pa8k |
| Name | New York State Enacted Budget Capital Appropriations: 2016-2017 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2016-06-03T20:03:20Z |
| Publication Date | 2016-06-03T20:08:45Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the 2016-17 Enacted Budget.

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
| Yes      | numeric metric | enacted_reappropriations_2016_17 | Enacted Reappropriations 2016-17 | number    | number      |
| Yes      | numeric metric | encumbrance_as_of_5_13_2016      | Encumbrance as of 5/13/2016      | number    | number      |
| Yes      | numeric metric | enacted_appropriations_2016_17   | Enacted Appropriations 2016-17   | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mpnb-pa8k d:2016-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/10 t:financing_source="Miscellaneous Gifts Account" m:enacted_appropriations_2016_17=0 m:encumbrance_as_of_5_13_2016=0 m:enacted_reappropriations_2016_17=500000

series e:mpnb-pa8k d:2016-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1103 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/11 t:financing_source="Miscellaneous Gifts Account" m:enacted_appropriations_2016_17=0 m:encumbrance_as_of_5_13_2016=0 m:enacted_reappropriations_2016_17=500000

series e:mpnb-pa8k d:2016-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1203 t:description="Maintenance & Improvement" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0054/01/12 t:financing_source="Miscellaneous Gifts Account" m:enacted_appropriations_2016_17=0 m:encumbrance_as_of_5_13_2016=0 m:enacted_reappropriations_2016_17=500000
```

## Meta Commands

```ls
metric m:enacted_reappropriations_2016_17 p:integer l:"Enacted Reappropriations 2016-17" d:"Enacted Reappropriations" t:dataTypeName=number

metric m:encumbrance_as_of_5_13_2016 p:integer l:"Encumbrance as of 5/13/2016" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=number

metric m:enacted_appropriations_2016_17 p:long l:"Enacted Appropriations 2016-17" d:"Enacted Appropriations" t:dataTypeName=number

entity e:mpnb-pa8k l:"New York State Enacted Budget Capital Appropriations: 2016-2017" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/mpnb-pa8k

property e:mpnb-pa8k t:meta.view v:id=mpnb-pa8k v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Enacted Budget Capital Appropriations: 2016-2017" v:attribution="Division of the Budget"

property e:mpnb-pa8k t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mpnb-pa8k t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | enacted_reappropriations_2016_17 | encumbrance_as_of_5_13_2016 | enacted_appropriations_2016_17 | 
| ====================================== | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ================================ | =========================== | ============================== | 
| Adirondack Park Agency                 | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                           | 0                           | 0                              | 
| Adirondack Park Agency                 | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                           | 0                           | 0                              | 
| Adirondack Park Agency                 | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                           | 0                           | 0                              | 
| Agriculture and Markets, Department of | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 166000                           | 2018                        | 0                              | 
| Agriculture and Markets, Department of | 60010809         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 513000                           | 0                           | 0                              | 
| Agriculture and Markets, Department of | 60020607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0053/05/06           | Cornell Equine Drug Testing Lab         | 198000                           | 0                           | 0                              | 
| Agriculture and Markets, Department of | 60030607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0053/05/06           | Fredonia Vineyard Lab                   | 28000                            | 0                           | 0                              | 
| Agriculture and Markets, Department of | 60LF1603         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0000/00/16           | Local Fairs                             | 0                                | 0                           | 5000000                        | 
| Agriculture and Markets, Department of | 60MN1403         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/14           | State Fair Maintenance                  | 60000                            | 58961                       | 0                              | 
| Agriculture and Markets, Department of | 60MN1503         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/15           | State Fair Maintenance                  | 544000                           | 0                           | 0                              | 
```