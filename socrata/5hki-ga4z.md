# Smart Start 2016-17 By Town ( Sept)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/smart-start-2016-17-by-town-sept) |
| Metadata | [Link](https://data.ct.gov/api/views/5hki-ga4z) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/5hki-ga4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/5hki-ga4z/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 5hki-ga4z |
| Name | Smart Start 2016-17 By Town ( Sept) |
| Category | Education |
| Tags | education, preschool, early care, child care, smart start |
| Created | 2016-09-23T13:47:08Z |
| Publication Date | 2016-09-23T13:51:57Z |

## Description

Connecticut OEC Funded Smart Start spaces for Preschool age children by town and space type. 2016-17 Program Year.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | town                                 | Town                                 | text      | text        |
| Yes      | numeric metric | total_smart_start_2016_17_spaces     | TOTAL Smart Start 2016-17 Spaces     | number    | number      |
| Yes      | numeric metric | smart_start_2016_17_preschool_spaces | Smart Start 2016-17 Preschool Spaces | number    | number      |
| Yes      | numeric metric | smart_start_2016_17_classrooms       | Smart Start 2016-17 Classrooms       | number    | number      |
| Yes      | series tag     | capacity_cap                         | Capacity (Cap.)                      | text      | text        |
| Yes      | series tag     | funding_type                         | Funding Type                         | text      | text        |
| Yes      | series tag     | month_year_of_oec_funded_spaces      | Month & Year of OEC Funded Spaces    | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5hki-ga4z d:2016-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=Sep-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Ansonia m:total_smart_start_2016_17_spaces=15 m:smart_start_2016_17_preschool_spaces=15 m:smart_start_2016_17_classrooms=1

series e:5hki-ga4z d:2016-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=Sep-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Bridgeport m:total_smart_start_2016_17_spaces=60 m:smart_start_2016_17_preschool_spaces=60 m:smart_start_2016_17_classrooms=4

series e:5hki-ga4z d:2016-01-01T00:00:00.000Z t:month_year_of_oec_funded_spaces=Sep-16 t:capacity_cap=Cap. t:funding_type=SS t:town=Clinton m:total_smart_start_2016_17_spaces=30 m:smart_start_2016_17_preschool_spaces=30 m:smart_start_2016_17_classrooms=2
```

## Meta Commands

```ls
metric m:total_smart_start_2016_17_spaces p:integer l:"TOTAL Smart Start 2016-17 Spaces" t:dataTypeName=number

metric m:smart_start_2016_17_preschool_spaces p:integer l:"Smart Start 2016-17 Preschool Spaces" t:dataTypeName=number

metric m:smart_start_2016_17_classrooms p:integer l:"Smart Start 2016-17 Classrooms" t:dataTypeName=number

entity e:5hki-ga4z l:"Smart Start 2016-17 By Town ( Sept)" t:url=https://data.ct.gov/api/views/5hki-ga4z

property e:5hki-ga4z t:meta.view v:id=5hki-ga4z v:category=Education v:averageRating=0 v:name="Smart Start 2016-17 By Town ( Sept)"

property e:5hki-ga4z t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:5hki-ga4z t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| town          | total_smart_start_2016_17_spaces | smart_start_2016_17_preschool_spaces | smart_start_2016_17_classrooms | capacity_cap | funding_type | month_year_of_oec_funded_spaces | 
| ============= | ================================ | ==================================== | ============================== | ============ | ============ | =============================== | 
| Ansonia       | 15                               | 15                                   | 1                              | Cap.         | SS           | Sep-16                          | 
| Bridgeport    | 60                               | 60                                   | 4                              | Cap.         | SS           | Sep-16                          | 
| Clinton       | 30                               | 30                                   | 2                              | Cap.         | SS           | Sep-16                          | 
| Coventry      | 45                               | 45                                   | 3                              | Cap.         | SS           | Sep-16                          | 
| Cromwell      | 15                               | 15                                   | 1                              | Cap.         | SS           | Sep-16                          | 
| Derby         | 30                               | 30                                   | 2                              | Cap.         | SS           | Sep-16                          | 
| East Hartford | 30                               | 30                                   | 2                              | Cap.         | SS           | Sep-16                          | 
| East Haven    | 30                               | 30                                   | 2                              | Cap.         | SS           | Sep-16                          | 
| Enfield       | 26                               | 26                                   | 2                              | Cap.         | SS           | Sep-16                          | 
| Killingly     | 15                               | 15                                   | 1                              | Cap.         | SS           | Sep-16                          | 
```