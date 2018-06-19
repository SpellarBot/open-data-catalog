# Performance Metrics - Chicago Park District - Natural Resources Recycling

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-natural-resources-recycling-8b8d5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kes6-wskt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kes6-wskt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kes6-wskt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kes6-wskt |
| Name | Performance Metrics - Chicago Park District - Natural Resources Recycling |
| Attribution | Chicago Park District |
| Category | Administration & Finance |
| Tags | performance metrics, parks, sustainability |
| Created | 2011-11-25T20:20:38Z |
| Publication Date | 2012-07-19T14:15:02Z |

## Description

The Department of Natural Resources (CDNR) was created in 2001 and is responsible for ensuring the quality of the district's 7,300 acres of land. Through enhanced landscape management, staff training and constant high quality maintenance, the department is quickly becoming the benchmark by which many municipal organizations measure the quality of their landscape and gardening. The Department also manages the contract that the Park District uses for garbage and recycling pick-ups. The data displayed below represents the monthly gross recycling  tonnage that is collected compared to 2010.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | year        | Month      | text      | text        |
| No       |                | _1          | 2010       | number    | number      |
| No       |                | _2          | 2011       | number    | number      |
| No       |                | _           | 2012       | number    | number      |
| Yes      | numeric metric | target      | Target     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_
```

## Data Commands

```ls
series e:kes6-wskt d:2011-11-25T12:20:41.000Z t:year=Aug m:target=122

series e:kes6-wskt d:2011-11-25T12:20:41.000Z t:year=Sep m:target=122

series e:kes6-wskt d:2011-11-25T12:20:41.000Z t:year=Oct m:target=122
```

## Meta Commands

```ls
metric m:target p:integer l:Target t:dataTypeName=number

entity e:kes6-wskt l:"Performance Metrics - Chicago Park District - Natural Resources Recycling" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/kes6-wskt

property e:kes6-wskt t:meta.view v:id=kes6-wskt v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Natural Resources Recycling" v:attribution="Chicago Park District"

property e:kes6-wskt t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:kes6-wskt t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | year | _1     | _2     | _   | target | 
| =========== | ==== | ====== | ====== | === | ====== | 
| 1322223641  | Aug  | 195.95 | 184.88 |     | 122    | 
| 1322223641  | Sep  | 132.05 | 119.62 |     | 122    | 
| 1322223641  | Oct  | 114.67 | 135    |     | 122    | 
| 1323264272  | Nov  | 113.86 | 128    |     | 122    | 
| 1326884456  | Dec  | 98.27  | 174    |     | 122    | 
| 1341233253  | Jul  | 162.51 | 165.85 |     | 122    | 
| 1341233264  | Apr  | 110.8  | 107.91 | 138 | 122    | 
| 1341233268  | Mar  | 130.55 | 136.97 | 136 | 122    | 
| 1341233270  | Feb  | 91.24  | 93.7   | 197 | 122    | 
| 1341233273  | Jan  | 66.6   | 97.1   | 171 | 122    | 
```