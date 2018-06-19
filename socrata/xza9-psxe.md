# Child Day Care (CDC) 2015-16 By Town ( May)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-2015-16-by-town-may) |
| Metadata | [Link](https://data.ct.gov/api/views/xza9-psxe) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/xza9-psxe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/xza9-psxe/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | xza9-psxe |
| Name | Child Day Care (CDC) 2015-16 By Town ( May) |
| Attribution | CT Office of Early Childhood |
| Category | Education |
| Tags | education, child day care, preschool, infant, toddler |
| Created | 2016-08-16T14:59:14Z |
| Publication Date | 2016-08-16T15:04:41Z |

## Description

OEC Funded Child Day Care Contract spaces for Infants, Toddlers, Preschool and School Age children by town and space type. 2015-16 Program Year.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================== | ========= | =========== |
| Yes      | series tag     | town                                             | Town                                               | text      | text        |
| Yes      | numeric metric | total_cdc_spaces_capacity                        | TOTAL CDC SPACES (Capacity)                        | number    | number      |
| Yes      | numeric metric | infant_toddler_cdc_spaces_it                     | Infant/Toddler CDC Spaces (IT)                     | number    | number      |
| Yes      | numeric metric | infant_toddler_wrap_around_cdc_spaces_it_wa      | Infant/Toddler Wrap-Around CDC Spaces (IT WA)      | number    | number      |
| Yes      | numeric metric | preschool_cdc_spaces_ps                          | Preschool CDC Spaces (PS)                          | number    | number      |
| Yes      | numeric metric | preschool_wrap_around_cdc_spaces_ps_wa           | Preschool Wrap-Around CDC Spaces (PS WA)           | number    | number      |
| Yes      | numeric metric | preschool_wrap_around_fulltime_cdc_spaces_it_waf | Preschool Wrap-Around Fulltime CDC Spaces (IT WAF) | number    | number      |
| Yes      | numeric metric | school_age_full_time_cdc_spaces_sa_ft            | School-Age Full-Time CDC Spaces (SA FT)            | number    | number      |
| Yes      | numeric metric | school_age_part_time_cdc_spaces_sa_pt            | School-Age Part-Time CDC Spaces (SA PT)            | number    | number      |
| Yes      | series tag     | capacity_cap                                     | Capacity (Cap.)                                    | text      | text        |
| Yes      | series tag     | child_day_care_cdc_contracts                     | Child Day Care (CDC) Contracts                     | text      | text        |
| Yes      | series tag     | month_and_year_for_oec_funded_spaces             | Month and Year for OEC Funded Spaces               | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xza9-psxe d:2015-01-01T00:00:00.000Z t:child_day_care_cdc_contracts=CDC t:capacity_cap=Cap. t:town=Ansonia t:month_and_year_for_oec_funded_spaces=May-16 m:school_age_part_time_cdc_spaces_sa_pt=0 m:total_cdc_spaces_capacity=10 m:preschool_cdc_spaces_ps=10 m:infant_toddler_wrap_around_cdc_spaces_it_wa=0 m:preschool_wrap_around_fulltime_cdc_spaces_it_waf=0 m:infant_toddler_cdc_spaces_it=0 m:preschool_wrap_around_cdc_spaces_ps_wa=8 m:school_age_full_time_cdc_spaces_sa_ft=0

series e:xza9-psxe d:2015-01-01T00:00:00.000Z t:child_day_care_cdc_contracts=CDC t:capacity_cap=Cap. t:town=Bloomfield t:month_and_year_for_oec_funded_spaces=May-16 m:school_age_part_time_cdc_spaces_sa_pt=0 m:total_cdc_spaces_capacity=60 m:preschool_cdc_spaces_ps=60 m:infant_toddler_wrap_around_cdc_spaces_it_wa=0 m:preschool_wrap_around_fulltime_cdc_spaces_it_waf=0 m:infant_toddler_cdc_spaces_it=0 m:preschool_wrap_around_cdc_spaces_ps_wa=0 m:school_age_full_time_cdc_spaces_sa_ft=0

series e:xza9-psxe d:2015-01-01T00:00:00.000Z t:child_day_care_cdc_contracts=CDC t:capacity_cap=Cap. t:town=Branford t:month_and_year_for_oec_funded_spaces=May-16 m:school_age_part_time_cdc_spaces_sa_pt=0 m:total_cdc_spaces_capacity=45 m:preschool_cdc_spaces_ps=37 m:infant_toddler_wrap_around_cdc_spaces_it_wa=0 m:preschool_wrap_around_fulltime_cdc_spaces_it_waf=0 m:infant_toddler_cdc_spaces_it=8 m:preschool_wrap_around_cdc_spaces_ps_wa=0 m:school_age_full_time_cdc_spaces_sa_ft=0
```

## Meta Commands

```ls
metric m:total_cdc_spaces_capacity p:integer l:"TOTAL CDC SPACES (Capacity)" t:dataTypeName=number

metric m:infant_toddler_cdc_spaces_it p:integer l:"Infant/Toddler CDC Spaces (IT)" t:dataTypeName=number

metric m:infant_toddler_wrap_around_cdc_spaces_it_wa p:integer l:"Infant/Toddler Wrap-Around CDC Spaces (IT WA)" t:dataTypeName=number

metric m:preschool_cdc_spaces_ps p:integer l:"Preschool CDC Spaces (PS)" t:dataTypeName=number

metric m:preschool_wrap_around_cdc_spaces_ps_wa p:integer l:"Preschool Wrap-Around CDC Spaces (PS WA)" t:dataTypeName=number

metric m:preschool_wrap_around_fulltime_cdc_spaces_it_waf p:integer l:"Preschool Wrap-Around Fulltime CDC Spaces (IT WAF)" t:dataTypeName=number

metric m:school_age_full_time_cdc_spaces_sa_ft p:integer l:"School-Age Full-Time CDC Spaces (SA FT)" t:dataTypeName=number

metric m:school_age_part_time_cdc_spaces_sa_pt p:integer l:"School-Age Part-Time CDC Spaces (SA PT)" t:dataTypeName=number

entity e:xza9-psxe l:"Child Day Care (CDC) 2015-16 By Town ( May)" t:attribution="CT Office of Early Childhood" t:url=https://data.ct.gov/api/views/xza9-psxe

property e:xza9-psxe t:meta.view v:id=xza9-psxe v:category=Education v:averageRating=0 v:name="Child Day Care (CDC) 2015-16 By Town ( May)" v:attribution="CT Office of Early Childhood"

property e:xza9-psxe t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:xza9-psxe t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town       | total_cdc_spaces_capacity | infant_toddler_cdc_spaces_it | infant_toddler_wrap_around_cdc_spaces_it_wa | preschool_cdc_spaces_ps | preschool_wrap_around_cdc_spaces_ps_wa | preschool_wrap_around_fulltime_cdc_spaces_it_waf | school_age_full_time_cdc_spaces_sa_ft | school_age_part_time_cdc_spaces_sa_pt | capacity_cap | child_day_care_cdc_contracts | month_and_year_for_oec_funded_spaces | 
| ========== | ========================= | ============================ | =========================================== | ======================= | ====================================== | ================================================ | ===================================== | ===================================== | ============ | ============================ | ==================================== | 
| Ansonia    | 10                        | 0                            | 0                                           | 10                      | 8                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Bloomfield | 60                        | 0                            | 0                                           | 60                      | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Branford   | 45                        | 8                            | 0                                           | 37                      | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Bridgeport | 634                       | 214                          | 88                                          | 29                      | 293                                    | 293                                              | 10                                    | 10                                    | Cap.         | CDC                          | May-16                               | 
| Bristol    | 50                        | 0                            | 0                                           | 50                      | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Brooklyn   | 18                        | 10                           | 0                                           | 8                       | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Chaplin    | 16                        | 8                            | 0                                           | 8                       | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Danbury    | 171                       | 16                           | 0                                           | 155                     | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| Derby      | 59                        | 14                           | 0                                           | 45                      | 0                                      | 0                                                | 0                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
| East Lyme  | 14                        | 0                            | 0                                           |                         | 0                                      | 0                                                | 9                                     | 0                                     | Cap.         | CDC                          | May-16                               | 
```