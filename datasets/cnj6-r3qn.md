# Performance Metrics - Chicago Park District - Natural Resources Trees and Shrubs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-natural-resources-trees-and-shrubs-c3e93) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cnj6-r3qn) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cnj6-r3qn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cnj6-r3qn/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cnj6-r3qn |
| Name | Performance Metrics - Chicago Park District - Natural Resources Trees and Shrubs |
| Attribution | Chicago Park District |
| Category | Administration & Finance |
| Tags | performance metrics, parks, sustainability |
| Created | 2011-11-25T20:40:03Z |
| Publication Date | 2012-08-03T19:19:17Z |

## Description

The Department of Natural Resources (CDNR) was created in 2001 and is responsible for ensuring the quality of the district's 7,300 acres of land. Through enhanced landscape management, staff training and constant high quality maintenance, the department is quickly becoming the benchmark by which many municipal organizations measure the quality of their landscape and gardening. The data below represents the number of trees that were removed District-wide as well as the number of shrubs and trees that were pruned.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at                 | meta_data | meta_data   |
| No       |                | date                     | Date                       | text      | text        |
| Yes      | numeric metric | removal_stumping         | Removal & Stumping         | number    | number      |
| Yes      | numeric metric | tree_s_removed           | # Tree's Removed           | number    | number      |
| Yes      | numeric metric | tree_s_pruned            | # Tree's Pruned            | number    | number      |
| Yes      | numeric metric | shrub_pruning            | Shrub Pruning              | number    | number      |
| Yes      | numeric metric | tree_s_and_shrubs_pruned | # Tree's and Shrubs Pruned | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:cnj6-r3qn d:2011-11-25T12:40:05.000Z m:shrub_pruning=0 m:tree_s_and_shrubs_pruned=227 m:tree_s_removed=121 m:tree_s_pruned=227 m:removal_stumping=28

series e:cnj6-r3qn d:2011-11-25T12:40:05.000Z m:shrub_pruning=0 m:tree_s_and_shrubs_pruned=370 m:tree_s_removed=193 m:tree_s_pruned=370 m:removal_stumping=90

series e:cnj6-r3qn d:2011-11-25T12:40:05.000Z m:shrub_pruning=126 m:tree_s_and_shrubs_pruned=461 m:tree_s_removed=21 m:tree_s_pruned=335 m:removal_stumping=0
```

## Meta Commands

```ls
metric m:removal_stumping p:integer l:"Removal & Stumping" t:dataTypeName=number

metric m:tree_s_removed p:integer l:"# Tree's Removed" t:dataTypeName=number

metric m:tree_s_pruned p:integer l:"# Tree's Pruned" t:dataTypeName=number

metric m:shrub_pruning p:integer l:"Shrub Pruning" t:dataTypeName=number

metric m:tree_s_and_shrubs_pruned p:integer l:"# Tree's and Shrubs Pruned" t:dataTypeName=number

entity e:cnj6-r3qn l:"Performance Metrics - Chicago Park District - Natural Resources Trees and Shrubs" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/cnj6-r3qn

property e:cnj6-r3qn t:meta.view v:id=cnj6-r3qn v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Natural Resources Trees and Shrubs" v:attribution="Chicago Park District"

property e:cnj6-r3qn t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:cnj6-r3qn t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | date      | removal_stumping | tree_s_removed | tree_s_pruned | shrub_pruning | tree_s_and_shrubs_pruned | 
| =========== | ========= | ================ | ============== | ============= | ============= | ======================== | 
| 1322224805  | 17-Jul-11 | 28               | 121            | 227           | 0             | 227                      | 
| 1322224805  | 24-Jul-11 | 90               | 193            | 370           | 0             | 370                      | 
| 1322224805  | 31-Jul-11 | 0                | 21             | 335           | 126           | 461                      | 
| 1322224805  | 7-Aug-11  | 0                | 30             | 242           | 40            | 282                      | 
| 1322224805  | 14-Aug-11 | 6                | 20             | 254           | 6             | 260                      | 
| 1322224805  | 21-Aug-11 | 46               | 22             | 185           | 47            | 232                      | 
| 1322224805  | 28-Aug-11 | 43               | 71             | 119           | 7             | 126                      | 
| 1322224805  | 4-Sep-11  | 43               | 71             | 159           | 45            | 204                      | 
| 1322224805  | 11-Sep-11 | 32               | 58             | 268           | 7             | 275                      | 
| 1322224805  | 18-Sep-11 | 9                | 75             | 119           | 7             | 126                      | 
```