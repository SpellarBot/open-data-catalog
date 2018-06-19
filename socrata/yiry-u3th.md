# School Readiness 2015-16 By Town ( May)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-readiness-2015-16-by-town-may-151b5) |
| Metadata | [Link](https://data.ct.gov/api/views/yiry-u3th) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/yiry-u3th/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/yiry-u3th/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | yiry-u3th |
| Name | School Readiness 2015-16 By Town ( May) |
| Category | Education |
| Tags | education, child day care, preschool, early care |
| Created | 2016-09-16T19:16:16Z |
| Publication Date | 2016-09-16T19:25:45Z |

## Description

OEC - School Readiness Spaces - Priority and Competitive District for Preschool aged children by town and space type.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                              | Data Type | Render Type |
| ======== | ============== | ============================================================= | ================================================================= | ========= | =========== |
| Yes      | series tag     | town_code                                                     | Town/Code                                                         | text      | text        |
| Yes      | numeric metric | total_school_readiness_preschool_spaces                       | Total School Readiness Preschool Spaces                           | number    | number      |
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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yiry-u3th d:2015-01-01T00:00:00.000Z t:town_code=Andover t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=May-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=CSR m:part_day_school_readiness_preschool_spaces=24 m:total_school_readiness_preschool_spaces=24

series e:yiry-u3th d:2015-01-01T00:00:00.000Z t:town_code=Ansonia t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=May-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=PSR m:part_day_school_readiness_preschool_spaces=21 m:total_school_readiness_preschool_spaces=132 m:full_day_school_readiness_preschool_spaces=111

series e:yiry-u3th d:2015-01-01T00:00:00.000Z t:town_code=Ashford t:capacity_cap=Cap. t:month_and_year_for_oec_sr_slot_grid=May-16 t:funding_type_priority_psr_or_competitive_csr_school_readiness=CSR m:part_day_school_readiness_preschool_spaces=24 m:total_school_readiness_preschool_spaces=24
```

## Meta Commands

```ls
metric m:total_school_readiness_preschool_spaces p:integer l:"Total School Readiness Preschool Spaces" t:dataTypeName=number

metric m:full_day_school_readiness_preschool_spaces p:integer l:"Full Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:school_day_school_readiness_preschool_spaces p:double l:"School Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:part_day_school_readiness_preschool_spaces p:double l:"Part Day School Readiness Preschool Spaces" t:dataTypeName=number

metric m:extended_day_school_readiness_preschool_spaces p:double l:"Extended Day School Readiness Preschool Spaces" t:dataTypeName=number

entity e:yiry-u3th l:"School Readiness 2015-16 By Town ( May)" t:url=https://data.ct.gov/api/views/yiry-u3th

property e:yiry-u3th t:meta.view v:id=yiry-u3th v:category=Education v:averageRating=0 v:name="School Readiness 2015-16 By Town ( May)"

property e:yiry-u3th t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:yiry-u3th t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town_code    | total_school_readiness_preschool_spaces | full_day_school_readiness_preschool_spaces | school_day_school_readiness_preschool_spaces | part_day_school_readiness_preschool_spaces | extended_day_school_readiness_preschool_spaces | capacity_cap | funding_type_priority_psr_or_competitive_csr_school_readiness | month_and_year_for_oec_sr_slot_grid | 
| ============ | ======================================= | ========================================== | ============================================ | ========================================== | ============================================== | ============ | ============================================================= | =================================== | 
| Andover      | 24                                      |                                            |                                              | 24                                         |                                                | Cap.         | CSR                                                           | May-16                              | 
| Ansonia      | 132                                     | 111                                        |                                              | 21                                         |                                                | Cap.         | PSR                                                           | May-16                              | 
| Ashford      | 24                                      |                                            |                                              | 24                                         |                                                | Cap.         | CSR                                                           | May-16                              | 
| Beacon Falls | 0.0                                     | 0.0                                        | 0.0                                          | 0.0                                        | 0.0                                            | Cap.         | N/A                                                           | May-16                              | 
| Bloomfield   | 75                                      | 71                                         |                                              | 4                                          |                                                | Cap.         | PSR                                                           | May-16                              | 
| Branford     | 13                                      | 13                                         |                                              |                                            |                                                | Cap.         | CSR                                                           | May-16                              | 
| Bridgeport   | 1705                                    | 1093                                       | 360                                          | 109                                        | 143                                            | Cap.         | PSR                                                           | May-16                              | 
| Bristol      | 404                                     | 224                                        |                                              | 180                                        |                                                | Cap.         | PSR                                                           | May-16                              | 
| Brooklyn     | 24                                      |                                            |                                              | 24                                         |                                                | Cap.         | CSR                                                           | May-16                              | 
| Canterbury   | 53                                      |                                            |                                              | 53                                         |                                                | Cap.         | CSR                                                           | May-16                              | 
```