# New York State Executive Budget Capital Appropriations, as Amended: 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-capital-appropriations-with-executive-amendments-2015-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/eyju-7cdr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/eyju-7cdr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/eyju-7cdr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | eyju-7cdr |
| Name | New York State Executive Budget Capital Appropriations, as Amended: 2015-2016 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriations, reappropriations, encumbrances, executive amendment |
| Created | 2015-03-04T21:11:13Z |
| Publication Date | 2015-03-04T21:20:47Z |

## Description

This data set includes capital project appropriations and reappropriations as they relate to the 2015-16 Executive Budget with Executive Amendments.

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
| Yes      | numeric metric | encumbrance_as_of_2_26_2015          | Encumbrance as of 2/26/2015          | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2015_16   | Appropriations Recommended 2015-16   | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eyju-7cdr d:2015-01-01T00:00:00.000Z t:fund_name="Clean Air Fund" t:reference_number=09MO0055 t:description="Clean Air-Mobile Source" t:program_name="Air Resources" t:state_purpose="Environmental Protection or Improvements" t:agency_name="Environmental Conservation, Department of" t:chapter_section_year=0055/01/00 t:financing_source="Clean Air Fund" m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=507000 m:encumbrance_as_of_2_26_2015=0

series e:eyju-7cdr d:2015-01-01T00:00:00.000Z t:fund_name="Division for Youth Facilities Improvement Fund" t:reference_number=25010701 t:description="Health and Safety" t:program_name="Maintenance and Improvement of Facilities" t:state_purpose="Health and Safety" t:agency_name="Children and Family Services, Office of" t:chapter_section_year=0053/01/07 t:financing_source="Youth Facilities Improvement Fund" m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=3652000 m:encumbrance_as_of_2_26_2015=0

series e:eyju-7cdr d:2015-01-01T00:00:00.000Z t:fund_name="Capital Projects Fund" t:reference_number=11020903 t:description="Minor Rehabilitation" t:program_name=Administration t:state_purpose="Preservation of Facilities" t:agency_name="Education Department, State" t:chapter_section_year=0053/01/09 t:financing_source="Capital Projects Fund" m:appropriations_recommended_2015_16=0 m:reappropriations_recommended_2015_16=625000 m:encumbrance_as_of_2_26_2015=0
```

## Meta Commands

```ls
metric m:reappropriations_recommended_2015_16 p:integer l:"Reappropriations Recommended 2015-16" d:"Reappropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

metric m:encumbrance_as_of_2_26_2015 p:integer l:"Encumbrance as of 2/26/2015" d:"Amount of an appropriation reserved for future expenditure" t:dataTypeName=money

metric m:appropriations_recommended_2015_16 p:long l:"Appropriations Recommended 2015-16" d:"Appropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

entity e:eyju-7cdr l:"New York State Executive Budget Capital Appropriations, as Amended: 2015-2016" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/eyju-7cdr

property e:eyju-7cdr t:meta.view v:id=eyju-7cdr v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Capital Appropriations, as Amended: 2015-2016" v:attribution="Division of the Budget"

property e:eyju-7cdr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:eyju-7cdr t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eyju-7cdr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                               | reference_number | program_name                                     | state_purpose                            | fund_name                                      | financing_source                        | chapter_section_year | description                             | reappropriations_recommended_2015_16 | encumbrance_as_of_2_26_2015 | appropriations_recommended_2015_16 | 
| ========================================= | ================ | ================================================ | ======================================== | ============================================== | ======================================= | ==================== | ======================================= | ==================================== | =========================== | ================================== | 
| Environmental Conservation, Department of | 09MO0055         | Air Resources                                    | Environmental Protection or Improvements | Clean Air Fund                                 | Clean Air Fund                          | 0055/01/00           | Clean Air-Mobile Source                 | 507000                               | 0                           | 0                                  | 
| Children and Family Services, Office of   | 25010701         | Maintenance and Improvement of Facilities        | Health and Safety                        | Division for Youth Facilities Improvement Fund | Youth Facilities Improvement Fund       | 0053/01/07           | Health and Safety                       | 3652000                              | 0                           | 0                                  | 
| Education Department, State               | 11020903         | Administration                                   | Preservation of Facilities               | Capital Projects Fund                          | Capital Projects Fund                   | 0053/01/09           | Minor Rehabilitation                    | 625000                               | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1003         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities               | Combined Expendable Trust                      | Miscellaneous Gifts Account             | 0055/01/10           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1103         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities               | Combined Expendable Trust                      | Miscellaneous Gifts Account             | 0054/01/11           | Miscellaneous Gifts Account             | 500000                               | 0                           | 0                                  | 
| Adirondack Park Agency                    | 13GI1203         | Maintenance & Improvement of Existing Facilities | Preservation of Facilities               | Combined Expendable Trust                      | Miscellaneous Gifts Account             | 0054/01/12           | Maintenance & Improvement               | 500000                               | 0                           | 0                                  | 
| Agriculture and Markets, Department of    | 60010607         | New Facilities                                   | New Facilities                           | Capital Projects Fund                          | Capital Projects Fund - Authority Bonds | 0108/05/06           | Food Laboratory                         | 500000                               | 53900                       | 0                                  | 
| Agriculture and Markets, Department of    | 60010809         | New Facilities                                   | New Facilities                           | Capital Projects Fund                          | Capital Projects Fund                   | 0053/05/08           | Cornell Grape Genomics Research Facilit | 3130000                              | 0                           | 0                                  | 
| Agriculture and Markets, Department of    | 60MN1103         | State Fair                                       | Preservation of Facilities               | Capital Projects Fund                          | Capital Projects Fund                   | 0054/01/11           | State Fair Capital                      | 146000                               | 1415                        | 0                                  | 
| Agriculture and Markets, Department of    | 60MN1203         | State Fair                                       | Preservation of Facilities               | Capital Projects Fund                          | Capital Projects Fund                   | 0054/01/12           | State Fair Maintenance                  | 9000                                 | 0                           | 0                                  | 
```