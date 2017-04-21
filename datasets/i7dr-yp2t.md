# Preschool Dev. Grant 2016-17 By Town ( Sept)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/preschool-dev-grant-2016-17-by-town-sept) |
| Metadata | [Link](https://data.ct.gov/api/views/i7dr-yp2t) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/i7dr-yp2t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/i7dr-yp2t/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | i7dr-yp2t |
| Name | Preschool Dev. Grant 2016-17 By Town ( Sept) |
| Category | Education |
| Tags | education, child day care, preschool, early care |
| Created | 2016-09-16T19:37:32Z |
| Publication Date | 2016-09-16T19:47:06Z |

## Description

OEC - Federal Preschool Development Grant Spaces for Preschool aged children (4 year olds) by town and space type.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | town                                        | Town                                        | text      | text        |
| Yes      | numeric metric | total_preschool_development_grant_ps_spaces | TOTAL Preschool Development Grant PS Spaces | number    | number      |
| Yes      | numeric metric | pdg_fd_fy_expansion_ps_spaces               | PDG FD-FY Expansion PS Spaces               | number    | number      |
| Yes      | numeric metric | pdg_fd_fy_improved_ps_spaces                | PDG FD-FY Improved PS Spaces                | number    | number      |
| Yes      | numeric metric | pdg_pd_to_fd_fy_improved_ps_spaces          | PDG PD to FD-FY Improved PS Spaces          | number    | number      |
| Yes      | numeric metric | sd_sy_expansion_ps_spaces                   | SD-SY Expansion PS Spaces                   | number    | number      |
| Yes      | numeric metric | pd_to_sd_sy_improved_ps_spaces              | PD to SD-SY Improved PS Spaces              | number    | number      |
| Yes      | series tag     | capacity_cap                                | Capacity (Cap.)                             | text      | text        |
| Yes      | series tag     | funding_type                                | Funding Type                                | text      | text        |
| Yes      | series tag     | month_and_year_for_oec_funded_spaces        | Month and Year for OEC Funded Spaces        | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i7dr-yp2t d:2016-01-01T00:00:00.000Z t:capacity_cap=Cap. t:funding_type=PDG t:town=Bridgeport t:month_and_year_for_oec_funded_spaces=Sep-16 m:sd_sy_expansion_ps_spaces=90 m:pdg_fd_fy_expansion_ps_spaces=90 m:total_preschool_development_grant_ps_spaces=270 m:pdg_fd_fy_improved_ps_spaces=54 m:pd_to_sd_sy_improved_ps_spaces=36

series e:i7dr-yp2t d:2016-01-01T00:00:00.000Z t:capacity_cap=Cap. t:funding_type=PDG t:town=Derby t:month_and_year_for_oec_funded_spaces=Sep-16 m:sd_sy_expansion_ps_spaces=17 m:total_preschool_development_grant_ps_spaces=35 m:pdg_fd_fy_improved_ps_spaces=18

series e:i7dr-yp2t d:2016-01-01T00:00:00.000Z t:capacity_cap=Cap. t:funding_type=PDG t:town="East Haven" t:month_and_year_for_oec_funded_spaces=Sep-16 m:pdg_fd_fy_expansion_ps_spaces=18 m:total_preschool_development_grant_ps_spaces=50 m:pdg_fd_fy_improved_ps_spaces=32
```

## Meta Commands

```ls
metric m:total_preschool_development_grant_ps_spaces p:integer l:"TOTAL Preschool Development Grant PS Spaces" t:dataTypeName=number

metric m:pdg_fd_fy_expansion_ps_spaces p:integer l:"PDG FD-FY Expansion PS Spaces" t:dataTypeName=number

metric m:pdg_fd_fy_improved_ps_spaces p:integer l:"PDG FD-FY Improved PS Spaces" t:dataTypeName=number

metric m:pdg_pd_to_fd_fy_improved_ps_spaces p:integer l:"PDG PD to FD-FY Improved PS Spaces" t:dataTypeName=number

metric m:sd_sy_expansion_ps_spaces p:integer l:"SD-SY Expansion PS Spaces" t:dataTypeName=number

metric m:pd_to_sd_sy_improved_ps_spaces p:integer l:"PD to SD-SY Improved PS Spaces" t:dataTypeName=number

entity e:i7dr-yp2t l:"Preschool Dev. Grant 2016-17 By Town ( Sept)" t:url=https://data.ct.gov/api/views/i7dr-yp2t

property e:i7dr-yp2t t:meta.view v:id=i7dr-yp2t v:category=Education v:averageRating=0 v:name="Preschool Dev. Grant 2016-17 By Town ( Sept)"

property e:i7dr-yp2t t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:i7dr-yp2t t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town       | total_preschool_development_grant_ps_spaces | pdg_fd_fy_expansion_ps_spaces | pdg_fd_fy_improved_ps_spaces | pdg_pd_to_fd_fy_improved_ps_spaces | sd_sy_expansion_ps_spaces | pd_to_sd_sy_improved_ps_spaces | capacity_cap | funding_type | month_and_year_for_oec_funded_spaces | 
| ========== | =========================================== | ============================= | ============================ | ================================== | ========================= | ============================== | ============ | ============ | ==================================== | 
| Bridgeport | 270                                         | 90                            | 54                           |                                    | 90                        | 36                             | Cap.         | PDG          | Sep-16                               | 
| Derby      | 35                                          |                               | 18                           |                                    | 17                        |                                | Cap.         | PDG          | Sep-16                               | 
| East Haven | 50                                          | 18                            | 32                           |                                    |                           |                                | Cap.         | PDG          | Sep-16                               | 
| Griswold   | 36                                          |                               | 9                            |                                    | 15                        | 12                             | Cap.         | PDG          | Sep-16                               | 
| Groton     | 10                                          |                               | 10                           |                                    |                           |                                | Cap.         | PDG          | Sep-16                               | 
| Hamden     | 21                                          | 21                            |                              |                                    |                           |                                | Cap.         | PDG          | Sep-16                               | 
| Killingly  | 36                                          |                               |                              |                                    | 18                        | 18                             | Cap.         | PDG          | Sep-16                               | 
| Manchester | 56                                          | 18                            | 20                           |                                    | 18                        |                                | Cap.         | PDG          | Sep-16                               | 
| Naugatuck  | 45                                          | 45                            |                              |                                    |                           |                                | Cap.         | PDG          | Sep-16                               | 
| Seymour    | 18                                          | 5                             | 13                           |                                    |                           |                                | Cap.         | PDG          | Sep-16                               | 
```