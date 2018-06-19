# School Readiness 2016-17 By Town ( Sept)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-readiness-2016-17-by-town-sept) |
| Metadata | [Link](https://data.ct.gov/api/views/suk6-uupp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/suk6-uupp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/suk6-uupp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | suk6-uupp |
| Name | School Readiness 2016-17 By Town ( Sept) |
| Category | Education |
| Tags | education, child day care, preschool, early care |
| Created | 2016-11-07T21:41:52Z |
| Publication Date | 2016-11-07T22:23:29Z |

## Description

OEC - School Readiness Spaces - Priority and Competitive District for Number of Preschool aged children by town and space type.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                              | Data Type | Render Type |
| ======== | ============== | ============================================================= | ================================================================= | ========= | =========== |
| Yes      | series tag     | town_code                                                     | Town                                                              | text      | text        |
| Yes      | numeric metric | total_school_readiness_preschool_spaces_2016_17               | Total School Readiness Preschool Spaces 2016-17                   | number    | number      |
| Yes      | numeric metric | full_day_school_readiness_preschool_spaces                    | Full Day School Readiness Preschool Spaces                        | number    | number      |
| Yes      | numeric metric | school_day_school_readiness_preschool_spaces                  | School Day School Readiness Preschool Spaces                      | number    | number      |
| Yes      | numeric metric | part_day_school_readiness_preschool_spaces                    | Part Day School Readiness Preschool Spaces                        | number    | number      |
| Yes      | numeric metric | extended_day_school_readiness_preschool_spaces                | Extended Day School Readiness Preschool Spaces                    | number    | number      |
| Yes      | series tag     | capacity_cap                                                  | Capacity (Cap.)                                                   | text      | text        |
| Yes      | series tag     | funding_type_priority_psr_or_competitive_csr_school_readiness | Funding Type Priority (PSR) or Competitive (CSR) School Readiness | text      | text        |
| Yes      | series tag     | month_and_year_for_oec_sr_slot_grid                           | Month and Year for OEC SR Slot Grid                               | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:suk6-uupp d:2016-01-01T00:00:00.000Z t:town_code=Bridgeport t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=Sep-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=PSR m:part_day_school_readiness_preschool_spaces=109 m:total_school_readiness_preschool_spaces_2016_17=1703 m:full_day_school_readiness_preschool_spaces=1081 m:school_day_school_readiness_preschool_spaces=370 m:extended_day_school_readiness_preschool_spaces=143

series e:suk6-uupp d:2016-01-01T00:00:00.000Z t:town_code=Mansfield t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=Sep-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=CSR m:part_day_school_readiness_preschool_spaces=2 m:total_school_readiness_preschool_spaces_2016_17=15 m:full_day_school_readiness_preschool_spaces=11 m:school_day_school_readiness_preschool_spaces=2

series e:suk6-uupp d:2016-01-01T00:00:00.000Z t:town_code=Meriden t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=Sep-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=PSR m:part_day_school_readiness_preschool_spaces=29 m:total_school_readiness_preschool_spaces_2016_17=505 m:full_day_school_readiness_preschool_spaces=351 m:school_day_school_readiness_preschool_spaces=33 m:extended_day_school_readiness_preschool_spaces=92
```

## Meta Commands

```ls
metric m:total_school_readiness_preschool_spaces_2016_17 p:integer l:"Total School Readiness Preschool Spaces 2016-17" t:dataTypeName=number

metric m:full_day_school_readiness_preschool_spaces p:integer l:"Full Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:school_day_school_readiness_preschool_spaces p:integer l:"School Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:part_day_school_readiness_preschool_spaces p:integer l:"Part Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:extended_day_school_readiness_preschool_spaces p:integer l:"Extended Day School Readiness Preschool Spaces" t:dataTypeName=number

entity e:suk6-uupp l:"School Readiness 2016-17 By Town ( Sept)" t:url=https://data.ct.gov/api/views/suk6-uupp

property e:suk6-uupp t:meta.view v:id=suk6-uupp v:category=Education v:averageRating=0 v:name="School Readiness 2016-17 By Town ( Sept)"

property e:suk6-uupp t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:suk6-uupp t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town_code  | total_school_readiness_preschool_spaces_2016_17 | full_day_school_readiness_preschool_spaces | school_day_school_readiness_preschool_spaces | part_day_school_readiness_preschool_spaces | extended_day_school_readiness_preschool_spaces | capacity_cap | funding_type_priority_psr_or_competitive_csr_school_readiness | month_and_year_for_oec_sr_slot_grid | 
| ========== | =============================================== | ========================================== | ============================================ | ========================================== | ============================================== | ============ | ============================================================= | =================================== | 
| Bridgeport | 1703                                            | 1081                                       | 370                                          | 109                                        | 143                                            | Cap.         | PSR                                                           | Sep-16                              | 
| Mansfield  | 15                                              | 11                                         | 2                                            | 2                                          |                                                | Cap.         | CSR                                                           | Sep-16                              | 
| Meriden    | 505                                             | 351                                        | 33                                           | 29                                         | 92                                             | Cap.         | PSR                                                           | Sep-16                              | 
| Plainfield | 28                                              | 18                                         |                                              | 10                                         |                                                | Cap.         | CSR                                                           | Sep-16                              | 
| Griswold   | 44                                              | 21                                         |                                              | 23                                         |                                                | Cap.         | CSR                                                           | Sep-16                              | 
| Ellington  | 18                                              | 11                                         |                                              | 7                                          |                                                | Cap.         | CSR                                                           | Sep-16                              | 
| Danbury    | 406                                             | 359                                        |                                              | 47                                         |                                                | Cap.         | PSR                                                           | Sep-16                              | 
| Bristol    | 402                                             | 224                                        |                                              | 178                                        |                                                | Cap.         | PSR                                                           | Sep-16                              | 
| Ansonia    | 128                                             | 111                                        |                                              | 17                                         |                                                | Cap.         | PSR                                                           | Sep-16                              | 
| Stamford   | 548                                             | 406                                        | 16                                           | 66                                         | 60                                             | Cap.         | PSR                                                           | Sep-16                              | 
```