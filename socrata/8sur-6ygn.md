# Imagine Austin Indicators Master Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/imagine-austin-indicators-master-results) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8sur-6ygn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8sur-6ygn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8sur-6ygn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8sur-6ygn |
| Name | Imagine Austin Indicators Master Results |
| Created | 2016-11-28T21:52:42Z |
| Publication Date | 2016-12-08T15:46:51Z |

## Description

Draft master table for final results for the Imagine Austin Indicators. Values may be for testing only while the table is in draft/testing. The final information should be made available in August, 2017.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | original_number           | Original Number           | text      | number      |
| No       |                | chart_date                | Chart Date                | text      | text        |
| Yes      | series tag     | topic_area                | Topic Area                | text      | text        |
| Yes      | series tag     | key_performance_indicator | Key Performance Indicator | text      | text        |
| Yes      | numeric metric | value                     | Value                     | number    | number      |
| Yes      | series tag     | unit                      | Unit                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = chart_date
```

## Data Commands

```ls
series e:8sur-6ygn d:2016-11-28T21:53:40.000Z t:topic_area=Liveable t:key_performance_indicator="Median Gross Rent" t:original_number=4 m:value=0

series e:8sur-6ygn d:2016-11-28T21:53:40.000Z t:topic_area=Liveable t:key_performance_indicator="Median Gross Rent" t:original_number=4 m:value=0

series e:8sur-6ygn d:2016-11-28T21:53:40.000Z t:topic_area=Liveable t:key_performance_indicator="Median Gross Rent" t:original_number=4 m:value=0
```

## Meta Commands

```ls
metric m:value p:double l:Value t:dataTypeName=number

entity e:8sur-6ygn l:"Imagine Austin Indicators Master Results" t:url=https://data.austintexas.gov/api/views/8sur-6ygn

property e:8sur-6ygn t:meta.view v:id=8sur-6ygn v:averageRating=0 v:name="Imagine Austin Indicators Master Results"

property e:8sur-6ygn t:meta.view.owner v:id=4y62-vmjm v:screenName="Paul Frank" v:displayName="Paul Frank"

property e:8sur-6ygn t:meta.view.tableauthor v:id=4y62-vmjm v:screenName="Paul Frank" v:roleName=editor_stories v:displayName="Paul Frank"
```

## Top Records

```ls
| :updated_at | original_number | chart_date | topic_area | key_performance_indicator | value | unit | 
| =========== | =============== | ========== | ========== | ========================= | ===== | ==== | 
| 1480370020  | 4               | 2012       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2013       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2007       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2008       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2009       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2010       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2011       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2014       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2015       | Liveable   | Median Gross Rent         | 0     |      | 
| 1480370020  | 4               | 2016       | Liveable   | Median Gross Rent         | 0     |      | 
```