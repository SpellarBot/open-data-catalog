# Park Score (2014 - present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/park-score-2014-present) |
| Metadata | [Link](https://data.nola.gov/api/views/9r2n-ydic) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/9r2n-ydic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/9r2n-ydic/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 9r2n-ydic |
| Name | Park Score (2014 - present) |
| Attribution | Trust for Public Land |
| Category | Recreation and Culture |
| Tags | resultsnola |
| Created | 2015-04-28T21:21:29Z |
| Publication Date | 2015-08-26T21:15:28Z |

## Description

This data comes from the Trust for Public Land. It includes data for New Orleans on an annual basis beginning in 2014. It also includes data for several benchmark cities, including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville, Oklahoma City, Raleigh, and Tampa.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | number        |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | city           | City           | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | series tag     | indicator      | Indicator      | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:9r2n-ydic d:2014-01-01T00:00:00.000Z t:indicator=ParkScore t:state=GA t:rowid=2 t:city=Atlanta m:indicatorvalue=44

series e:9r2n-ydic d:2014-01-01T00:00:00.000Z t:indicator=ParkScore t:state=KY t:rowid=4 t:city=Louisville m:indicatorvalue=27.5

series e:9r2n-ydic d:2014-01-01T00:00:00.000Z t:indicator=ParkScore t:state=TN t:rowid=5 t:city=Memphis m:indicatorvalue=35
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:9r2n-ydic l:"Park Score (2014 - present)" t:attribution="Trust for Public Land" t:url=https://data.nola.gov/api/views/9r2n-ydic

property e:9r2n-ydic t:meta.view v:id=9r2n-ydic v:category="Recreation and Culture" v:attributionLink=http://parkscore.tpl.org/city.php v:averageRating=0 v:name="Park Score (2014 - present)" v:attribution="Trust for Public Land"

property e:9r2n-ydic t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:9r2n-ydic t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:9r2n-ydic t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid | date                | year | city              | state | indicator | indicatorvalue | 
| ===== | =================== | ==== | ================= | ===== | ========= | ============== | 
| 2     | 2014-01-01T00:00:00 | 2014 | Atlanta           | GA    | ParkScore | 44             | 
| 3     | 2014-01-01T00:00:00 | 2014 | Baton Rouge       | LA    | ParkScore |                | 
| 4     | 2014-01-01T00:00:00 | 2014 | Louisville        | KY    | ParkScore | 27.5           | 
| 5     | 2014-01-01T00:00:00 | 2014 | Memphis           | TN    | ParkScore | 35             | 
| 6     | 2014-01-01T00:00:00 | 2014 | Miami             | FL    | ParkScore | 40             | 
| 7     | 2014-01-01T00:00:00 | 2014 | Nashville         | TN    | ParkScore | 42             | 
| 8     | 2014-01-01T00:00:00 | 2014 | Oklahoma City     | OK    | ParkScore | 33.5           | 
| 9     | 2014-01-01T00:00:00 | 2014 | Raleigh           | NC    | ParkScore | 57             | 
| 10    | 2014-01-01T00:00:00 | 2014 | Tampa             | FL    | ParkScore | 51             | 
| 11    | 2014-08-01T00:00:00 | 2014 | Benchmark Average |       | ParkScore | 41.25          | 
```