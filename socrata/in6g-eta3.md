# New York State Executive Budget Capital Appropriations: 2016-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-2016-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/in6g-eta3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/in6g-eta3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/in6g-eta3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | in6g-eta3 |
| Name | New York State Executive Budget Capital Appropriations: 2016-2017 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances |
| Created | 2016-01-13T16:28:41Z |
| Publication Date | 2016-01-13T19:56:15Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the 2016-17 Executive Budget

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
| Yes      | numeric metric | reappropriations_recommended_2016_17 | Reappropriations Recommended 2016-17 | money     | money       |
| Yes      | numeric metric | encumbrance_as_of_1_11_2016          | Encumbrance as of 1/11/2016          | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2016_17   | Appropriations Recommended 2016-17   | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:in6g-eta3 d:2016-01-01T00:00:00.000Z t:fund_name="Capital Projects Fund" t:reference_number=09DS1251 t:description="Dam Safety" t:program_name=Operations t:state_purpose="Health and Safety" t:agency_name="Environmental Conservation, Department of" t:chapter_section_year=0054/01/13 t:financing_source="Capital Projects Fund" m:reappropriations_recommended_2016_17=1500000 m:encumbrance_as_of_1_11_2016=0 m:appropriations_recommended_2016_17=0

series e:in6g-eta3 d:2016-01-01T00:00:00.000Z t:fund_name="Capital Projects Fund" t:reference_number=17551514 t:description="NYW aviation" t:program_name="New York Works" t:state_purpose=Aviation t:agency_name="Transportation, Department of" t:chapter_section_year=0054/01/15 t:financing_source="Capital Projects Fund - Authority Bonds" m:reappropriations_recommended_2016_17=10000000 m:encumbrance_as_of_1_11_2016=0 m:appropriations_recommended_2016_17=0

series e:in6g-eta3 d:2016-01-01T00:00:00.000Z t:fund_name="Combined Expendable Trust" t:reference_number=13GI1003 t:description="Miscellaneous Gifts Account" t:program_name="Maintenance & Improvement of Existing Facilities" t:state_purpose="Preservation of Facilities" t:agency_name="Adirondack Park Agency" t:chapter_section_year=0055/01/10 t:financing_source="Miscellaneous Gifts Account" m:reappropriations_recommended_2016_17=500000 m:encumbrance_as_of_1_11_2016=0 m:appropriations_recommended_2016_17=0
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2016_17 p:integer l:"Reappropriations Recommended 2016-17" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:encumbrance_as_of_1_11_2016 p:integer l:"Encumbrance as of 1/11/2016" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:appropriations_recommended_2016_17 p:integer l:"Appropriations Recommended 2016-17" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

entity e:in6g-eta3 l:"New York State Executive Budget Capital Appropriations: 2016-2017" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/in6g-eta3

property e:in6g-eta3 t:meta.view v:id=in6g-eta3 v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations: 2016-2017" v:attribution="Division of the Budget"

property e:in6g-eta3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:in6g-eta3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                               | reference_number | program_name                                     | state_purpose              | fund_name                 | financing_source                        | chapter_section_year | description                             | reappropriations_recommended_2016_17 | encumbrance_as_of_1_11_2016 | appropriations_recommended_2016_17 | 
| ========================================= | ================ | ================================================ | ========================== | ========================= | ======================================= | ==================== | ======================================= | ==================================== | =========================== | ================================== | 
| Environmental Conservation, Department of | 09DS1251         | Operations                                       | Health and Safety          | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/13           | Dam Safety                              | 1500000                              | 0                           | 0                                  | 
| Transportation, Department of             | 17551514         | New York Works                                   | Aviation                   | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0054/01/15           | NYW aviation                            | 10000000                             | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities | Combined Expendable Trust | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                               | 0                           | 0                                  | 
| Agriculture and Markets, Department of    | 60010607         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 166000                               | 2018                        | 0                                  | 
| Agriculture and Markets, Department of    | 60010809         | New Facilities                                   | New Facilities             | Capital Projects Fund     | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 513000                               | 0                           | 0                                  | 
| Agriculture and Markets, Department of    | 60MN1403         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/14           | State Fair Maintenance                  | 60000                                | 58961                       | 0                                  | 
| Agriculture and Markets, Department of    | 60MN1503         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0054/01/15           | State Fair Maintenance                  | 544000                               | 0                           | 0                                  | 
| Agriculture and Markets, Department of    | 60MN1603         | State Fair                                       | Preservation of Facilities | Capital Projects Fund     | Capital Projects Fund                   | 0000/00/16           | State Fair Maintenance                  | 0                                    | 0                           | 1000000                            | 
```