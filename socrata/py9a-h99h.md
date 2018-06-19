# Smart Start 2015-16 By Town ( May)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/smart-start-2015-16-by-town-may) |
| Metadata | [Link](https://data.ct.gov/api/views/py9a-h99h) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/py9a-h99h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/py9a-h99h/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | py9a-h99h |
| Name | Smart Start 2015-16 By Town ( May) |
| Tags | education, child care, preschool, early care, smart start |
| Created | 2016-09-23T13:53:18Z |
| Publication Date | 2016-09-23T13:56:06Z |

## Description

Connecticut OEC Funded Smart Start spaces for Preschool age children by town and space type. 2015-16 Program Year.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | town                                 | Town                                 | text      | text        |
| Yes      | numeric metric | total_smart_start_2015_16_spaces     | TOTAL Smart Start 2015-16 Spaces     | number    | number      |
| Yes      | numeric metric | smart_start_2015_16_preschool_spaces | Smart Start 2015-16 Preschool Spaces | number    | number      |
| Yes      | series tag     | capacity_cap                         | Capacity (Cap.)                      | text      | text        |
| Yes      | series tag     | funding_type                         | Funding Type                         | text      | text        |
| Yes      | series tag     | month_year_of_oec_funded_spaces      | Month & Year of OEC Funded Spaces    | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:py9a-h99h d:2015-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=May-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Ansonia m:smart_start_2015_16_preschool_spaces=15 m:total_smart_start_2015_16_spaces=15

series e:py9a-h99h d:2015-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=May-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Bridgeport m:smart_start_2015_16_preschool_spaces=60 m:total_smart_start_2015_16_spaces=60

series e:py9a-h99h d:2015-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=May-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Clinton m:smart_start_2015_16_preschool_spaces=15 m:total_smart_start_2015_16_spaces=15
```

## Meta Commands

```ls
metric m:total_smart_start_2015_16_spaces p:integer l:"TOTAL Smart Start 2015-16 Spaces" t:dataTypeName=number

metric m:smart_start_2015_16_preschool_spaces p:integer l:"Smart Start 2015-16 Preschool Spaces" t:dataTypeName=number

entity e:py9a-h99h l:"Smart Start 2015-16 By Town ( May)" t:url=https://data.ct.gov/api/views/py9a-h99h

property e:py9a-h99h t:meta.view v:id=py9a-h99h v:averageRating=0 v:name="Smart Start 2015-16 By Town ( May)"

property e:py9a-h99h t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:py9a-h99h t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town          | total_smart_start_2015_16_spaces | smart_start_2015_16_preschool_spaces | capacity_cap | funding_type | month_year_of_oec_funded_spaces | 
| ============= | ================================ | ==================================== | ============ | ============ | =============================== | 
| Ansonia       | 15                               | 15                                   | Cap.         | SS           | May-16                          | 
| Bridgeport    | 60                               | 60                                   | Cap.         | SS           | May-16                          | 
| Clinton       | 15                               | 15                                   | Cap.         | SS           | May-16                          | 
| Coventry      | 30                               | 30                                   | Cap.         | SS           | May-16                          | 
| Cromwell      | 0                                | 0                                    | Cap.         | SS           | May-16                          | 
| Derby         | 0                                | 0                                    | Cap.         | SS           | May-16                          | 
| East Hartford | 30                               | 30                                   | Cap.         | SS           | May-16                          | 
| East Haven    | 30                               | 30                                   | Cap.         | SS           | May-16                          | 
| Enfield       | 20                               | 20                                   | Cap.         | SS           | May-16                          | 
| Killingly     | 15                               | 15                                   | Cap.         | SS           | May-16                          | 
```